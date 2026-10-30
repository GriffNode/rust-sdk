# Plan

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**tier** | Option<[**models::PlanTier**](PlanTier.md)> |  | [optional]
**monthly_price_usd** | Option<**f64**> |  | [optional]
**yearly_price_usd** | Option<**f64**> |  | [optional]
**monthly_transaction_limit** | Option<**i32**> |  | [optional]
**overage_cost_per_tx** | Option<**f64**> | Always 0. Plans have a hard monthly limit and no overage. | [optional]
**webhook_support** | Option<**bool**> |  | [optional]
**webhook_limit** | Option<**i32**> |  | [optional]
**ip_whitelist** | Option<**bool**> |  | [optional]
**api_rate_limit_per_minute** | Option<**i32**> |  | [optional]
**api_rate_limit_per_hour** | Option<**i32**> |  | [optional]
**custom_pricing** | Option<**bool**> |  | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


