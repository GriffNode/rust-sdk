# \AccountApi

All URIs are relative to *https://api.griffnode.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_account**](AccountApi.md#get_account) | **GET** /account | Merchant plan, usage and limits
[**get_stats**](AccountApi.md#get_stats) | **GET** /stats | Merchant transaction analytics
[**list_balances**](AccountApi.md#list_balances) | **GET** /balances | On-platform balances (for overage/top-up; NOT crypto settlement)
[**list_invoices**](AccountApi.md#list_invoices) | **GET** /invoices | GriffNode billing invoices (platform ↔ merchant)
[**list_plans**](AccountApi.md#list_plans) | **GET** /plans | Plan catalogue and pricing



## get_account

> models::GetAccount200Response get_account()
Merchant plan, usage and limits

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::GetAccount200Response**](getAccount_200_response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_stats

> models::GetStats200Response get_stats()
Merchant transaction analytics

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::GetStats200Response**](getStats_200_response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## list_balances

> models::ListBalances200Response list_balances()
On-platform balances (for overage/top-up; NOT crypto settlement)

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::ListBalances200Response**](listBalances_200_response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## list_invoices

> models::ListInvoices200Response list_invoices(limit, offset)
GriffNode billing invoices (platform ↔ merchant)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**limit** | Option<**i32**> |  |  |[default to 20]
**offset** | Option<**i32**> |  |  |[default to 0]

### Return type

[**models::ListInvoices200Response**](listInvoices_200_response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## list_plans

> models::ListPlans200Response list_plans()
Plan catalogue and pricing

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::ListPlans200Response**](listPlans_200_response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

