# \BinancePayHistoryApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_pay_transactions_v1**](BinancePayHistoryApi.md#get_pay_transactions_v1) | **GET** /sapi/v1/pay/transactions | Get Pay Trade History



## get_pay_transactions_v1

> models::GetPayTransactionsV1Resp get_pay_transactions_v1(timestamp, start_time, end_time, limit, recv_window)
Get Pay Trade History

Get Pay Trade History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | default 100, max 100 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetPayTransactionsV1Resp**](GetPayTransactionsV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

