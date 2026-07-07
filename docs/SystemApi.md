# \SystemApi

All URIs are relative to *https://api.griffnode.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_health**](SystemApi.md#get_health) | **GET** /health | API health check
[**hosted_checkout_redirect**](SystemApi.md#hosted_checkout_redirect) | **GET** /pay | Hosted-checkout redirect (browser flow, publishable key)



## get_health

> models::GetHealth200Response get_health()
API health check

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::GetHealth200Response**](getHealth_200_response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## hosted_checkout_redirect

> hosted_checkout_redirect(pk, amount, crypto, link)
Hosted-checkout redirect (browser flow, publishable key)

Browser-facing redirect to the hosted payment page, authenticated by a **publishable** key in the query string (safe to expose client-side). Not used by the server-side SDKs — included for completeness. 

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pk** | **String** | Publishable key, pk_live_… / pk_test_… | [required] |
**amount** | **String** | Fiat amount (≥ 1.00 USD equivalent). | [required] |
**crypto** | [**CryptoSymbol**](.md) |  | [required] |
**link** | Option<**String**> | Payment-link slug for attribution. |  |

### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

