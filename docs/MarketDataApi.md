# \MarketDataApi

All URIs are relative to *https://api.griffnode.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_prices**](MarketDataApi.md#get_prices) | **GET** /prices | Current crypto and fiat exchange rates (USD-denominated)
[**list_cryptocurrencies**](MarketDataApi.md#list_cryptocurrencies) | **GET** /cryptos/list | All supported cryptocurrencies and tokens
[**list_merchant_cryptocurrencies**](MarketDataApi.md#list_merchant_cryptocurrencies) | **GET** /merchant/cryptos | Cryptocurrencies this merchant has wallets configured for



## get_prices

> models::GetPrices200Response get_prices()
Current crypto and fiat exchange rates (USD-denominated)

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::GetPrices200Response**](getPrices_200_response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## list_cryptocurrencies

> models::ListCryptocurrencies200Response list_cryptocurrencies()
All supported cryptocurrencies and tokens

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::ListCryptocurrencies200Response**](listCryptocurrencies_200_response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## list_merchant_cryptocurrencies

> models::ListCryptocurrencies200Response list_merchant_cryptocurrencies()
Cryptocurrencies this merchant has wallets configured for

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::ListCryptocurrencies200Response**](listCryptocurrencies_200_response.md)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

