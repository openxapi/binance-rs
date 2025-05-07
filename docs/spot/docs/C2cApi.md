# \C2cApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_c2c_order_match_list_user_order_history_v1**](C2cApi.md#get_c2c_order_match_list_user_order_history_v1) | **GET** /sapi/v1/c2c/orderMatch/listUserOrderHistory | Get C2C Trade History (USER_DATA)



## get_c2c_order_match_list_user_order_history_v1

> models::GetC2cOrderMatchListUserOrderHistoryV1Resp get_c2c_order_match_list_user_order_history_v1(timestamp, start_time, end_time, page, recv_window)
Get C2C Trade History (USER_DATA)

Get C2C Trade History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**page** | Option<**i32**> | Default 1 |  |[default to 1]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetC2cOrderMatchListUserOrderHistoryV1Resp**](GetC2cOrderMatchListUserOrderHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

