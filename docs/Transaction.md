# Transaction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**transaction_id** | **String** |  | 
**status** | [**models::TransactionStatus**](TransactionStatus.md) |  | 
**exception** | Option<[**models::TransactionException**](TransactionException.md)> |  | [optional]
**r#type** | Option<**String**> |  | [optional]
**crypto** | [**models::CryptoSymbol**](CryptoSymbol.md) |  | 
**deposit_address** | Option<**String**> |  | [optional]
**amount_crypto** | Option<**f64**> |  | [optional]
**amount_fiat** | **f64** |  | 
**amount_usd** | **f64** |  | 
**amount_paid** | Option<**f64**> |  | [optional]
**amount_remaining** | Option<**f64**> |  | [optional]
**currency_fiat** | [**models::FiatCurrency**](FiatCurrency.md) |  | 
**fiat_to_usd_rate** | Option<**f64**> |  | [optional]
**exchange_rate** | Option<**f64**> | USD per unit of crypto, locked at creation. | [optional]
**confirmations_required** | Option<**i32**> |  | [optional]
**payment_url** | Option<**String**> |  | [optional]
**order_id** | Option<**String**> |  | [optional]
**customer_email** | Option<**String**> |  | [optional]
**items** | Option<[**Vec<models::LineItem>**](LineItem.md)> |  | [optional]
**payments** | Option<[**Vec<models::PaymentSplit>**](PaymentSplit.md)> | On-chain payments detected toward this transaction. | [optional]
**metadata** | Option<**std::collections::HashMap<String, String>**> | Free-form key/value (≤20 keys, string values ≤500 chars, ≤4 KB total). | [optional]
**success_url** | Option<**String**> |  | [optional]
**cancel_url** | Option<**String**> |  | [optional]
**created_at** | **String** |  | 
**updated_at** | Option<**String**> |  | [optional]
**expires_at** | **String** |  | 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


