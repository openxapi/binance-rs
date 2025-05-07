# \RebateApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_rebate_tax_query_v1**](RebateApi.md#get_rebate_tax_query_v1) | **GET** /sapi/v1/rebate/taxQuery | Get Spot Rebate History Records (USER_DATA)



## get_rebate_tax_query_v1

> models::GetRebateTaxQueryV1Resp get_rebate_tax_query_v1(timestamp, start_time, end_time, page, recv_window)
Get Spot Rebate History Records (USER_DATA)

Get Spot Rebate History Records

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**page** | Option<**i32**> | Default 1 |  |[default to 1]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetRebateTaxQueryV1Resp**](GetRebateTaxQueryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

