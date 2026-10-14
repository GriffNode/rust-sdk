# WebhookPayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**event** | **String** |  | 
**timestamp** | **String** |  | 
**transaction_id** | **String** |  | 
**status** | [**models::TransactionStatus**](TransactionStatus.md) |  | 
**exception** | Option<[**models::TransactionException**](TransactionException.md)> |  | [optional]
**currency_crypto** | Option<[**models::CryptoSymbol**](CryptoSymbol.md)> |  | [optional]
**currency_fiat** | Option<[**models::FiatCurrency**](FiatCurrency.md)> |  | [optional]
**amount_fiat** | Option<**String**> | Decimal string. | [optional]
**amount_usd** | Option<**String**> | Decimal string. | [optional]
**amount_crypto** | Option<**String**> | Decimal string. | [optional]
**order_id** | Option<**String**> |  | [optional]
**receipt_url** | Option<**String**> | Present on completed/overpaid. | [optional]
**metadata** | Option<**std::collections::HashMap<String, String>**> | Free-form key/value (≤20 keys, string values ≤500 chars, ≤4 KB total). | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


