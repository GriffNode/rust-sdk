# \TransactionsApi

All URIs are relative to *https://api.griffnode.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_detailed_transaction**](TransactionsApi.md#create_detailed_transaction) | **POST** /transactions/create-detailed | Create an itemized transaction (Professional/Enterprise plans)
[**create_transaction**](TransactionsApi.md#create_transaction) | **POST** /transactions/create | Create a payment transaction
[**get_transaction**](TransactionsApi.md#get_transaction) | **GET** /transactions/{transaction_id} | Retrieve a single transaction
[**list_transactions**](TransactionsApi.md#list_transactions) | **GET** /transactions/list | List the merchant's transactions (newest first)



## create_detailed_transaction

> models::TransactionEnvelope create_detailed_transaction(create_detailed_transaction_request, x_idempotency_key)
Create an itemized transaction (Professional/Enterprise plans)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**create_detailed_transaction_request** | [**CreateDetailedTransactionRequest**](CreateDetailedTransactionRequest.md) |  | [required] |
**x_idempotency_key** | Option<**String**> | Optional unique key for a create request (e.g. a UUID). A retried create with the same key returns the original transaction instead of creating a duplicate — send it on every create so a network retry can't double-charge the customer.  |  |

### Return type

[**models::TransactionEnvelope**](TransactionEnvelope.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_transaction

> models::TransactionEnvelope create_transaction(create_transaction_request, x_idempotency_key)
Create a payment transaction

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**create_transaction_request** | [**CreateTransactionRequest**](CreateTransactionRequest.md) |  | [required] |
**x_idempotency_key** | Option<**String**> | Optional unique key for a create request (e.g. a UUID). A retried create with the same key returns the original transaction instead of creating a duplicate — send it on every create so a network retry can't double-charge the customer.  |  |

### Return type

[**models::TransactionEnvelope**](TransactionEnvelope.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_transaction

> models::TransactionEnvelope get_transaction(transaction_id)
Retrieve a single transaction

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**transaction_id** | **String** |  | [required] |

### Return type

[**models::TransactionEnvelope**](TransactionEnvelope.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## list_transactions

> models::ListTransactions200Response list_transactions(limit, offset, status, crypto)
List the merchant's transactions (newest first)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**limit** | Option<**i32**> |  |  |[default to 20]
**offset** | Option<**i32**> |  |  |[default to 0]
**status** | Option<[**TransactionStatus**](.md)> |  |  |
**crypto** | Option<[**CryptoSymbol**](.md)> |  |  |

### Return type

[**models::ListTransactions200Response**](listTransactions_200_response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

