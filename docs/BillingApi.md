# \BillingApi

All URIs are relative to *https://api.griffnode.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_billing_checkout**](BillingApi.md#create_billing_checkout) | **POST** /billing/checkout | Start a plan upgrade or account top-up



## create_billing_checkout

> models::TransactionEnvelope create_billing_checkout(create_billing_checkout_request)
Start a plan upgrade or account top-up

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**create_billing_checkout_request** | [**CreateBillingCheckoutRequest**](CreateBillingCheckoutRequest.md) |  | [required] |

### Return type

[**models::TransactionEnvelope**](TransactionEnvelope.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

