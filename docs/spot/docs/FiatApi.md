# \FiatApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_fiat_orders_v1**](FiatApi.md#get_fiat_orders_v1) | **GET** /sapi/v1/fiat/orders | Get Fiat Deposit/Withdraw History (USER_DATA)
[**get_fiat_payments_v1**](FiatApi.md#get_fiat_payments_v1) | **GET** /sapi/v1/fiat/payments | Get Fiat Payments History (USER_DATA)



## get_fiat_orders_v1

> models::GetFiatOrdersV1Resp get_fiat_orders_v1(transaction_type, timestamp, begin_time, end_time, page, rows, recv_window)
Get Fiat Deposit/Withdraw History (USER_DATA)

Get Fiat Deposit/Withdraw History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**transaction_type** | **String** | 0-deposit,1-withdraw | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**begin_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**page** | Option<**i32**> | default 1 |  |[default to 1]
**rows** | Option<**i32**> | default 100, max 500 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetFiatOrdersV1Resp**](GetFiatOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_fiat_payments_v1

> models::GetFiatPaymentsV1Resp get_fiat_payments_v1(transaction_type, timestamp, begin_time, end_time, page, rows, recv_window)
Get Fiat Payments History (USER_DATA)

Get Fiat Deposit/Withdraw History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**transaction_type** | **String** | 0-buy,1-sell | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**begin_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**page** | Option<**i32**> | default 1 |  |[default to 1]
**rows** | Option<**i32**> | default 100, max 500 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetFiatPaymentsV1Resp**](GetFiatPaymentsV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

