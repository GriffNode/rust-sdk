# RecurringWebhookPayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **String** |  | 
**event** | **String** |  | 
**timestamp** | **String** |  | 
**schedule_id** | [**uuid::Uuid**](uuid::Uuid.md) |  | 
**reference** | Option<**String**> | Your own customer/order id, as entered on the schedule. | [optional]
**customer_email** | Option<**String**> |  | [optional]
**description** | Option<**String**> |  | [optional]
**amount_fiat** | Option<**String**> | Decimal string. | [optional]
**currency_fiat** | Option<**String**> |  | [optional]
**interval** | Option<**String**> |  | [optional]
**status** | **String** |  | 
**period_no** | Option<**i32**> | recurring.payment.* only. | [optional]
**transaction_id** | Option<**String**> | recurring.payment.completed only. | [optional]
**reason** | Option<**String**> | recurring.stopped only. | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


