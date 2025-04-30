# \PortfolioMarginEndpointsApi

All URIs are relative to *https://dapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**cmfutures_get_pm_account_info_v1**](PortfolioMarginEndpointsApi.md#cmfutures_get_pm_account_info_v1) | **GET** /dapi/v1/pmAccountInfo | Classic Portfolio Margin Account Information (USER_DATA)



## cmfutures_get_pm_account_info_v1

> models::CmfuturesGetPmAccountInfoV1Resp cmfutures_get_pm_account_info_v1(asset, recv_window)
Classic Portfolio Margin Account Information (USER_DATA)

Get Classic Portfolio Margin current account information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CmfuturesGetPmAccountInfoV1Resp**](CmfuturesGetPmAccountInfoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

