# \DefaultApi

All URIs are relative to *https://api.griffnode.com/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**payment_webhook**](DefaultApi.md#payment_webhook) | **POST** /paymentEvent | Payment lifecycle event delivered to the merchant's webhook URL



## payment_webhook

> payment_webhook(webhook_payload)
Payment lifecycle event delivered to the merchant's webhook URL

Signed with HMAC-SHA256 over the RAW request body. Verify by comparing `X-GriffNode-Signature: sha256=<hex>` to `hex(hmac_sha256(webhook_secret, raw_body))` using a constant-time compare. Also sent: `X-GriffNode-Event` (the event type) and `X-Webhook-ID` (unique delivery id — use for idempotency). 

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**webhook_payload** | Option<[**WebhookPayload**](WebhookPayload.md)> |  |  |

### Return type

 (empty response body)

### Authorization

[SecretKey](../README.md#SecretKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

