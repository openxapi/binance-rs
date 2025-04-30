# \PortfolioMarginEndpointsApi

All URIs are relative to *https://fapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**umfutures_get_pm_account_info_v1**](PortfolioMarginEndpointsApi.md#umfutures_get_pm_account_info_v1) | **GET** /fapi/v1/pmAccountInfo | Classic Portfolio Margin Account Information (USER_DATA)



## umfutures_get_pm_account_info_v1

> models::UmfuturesGetPmAccountInfoV1Resp umfutures_get_pm_account_info_v1(asset, timestamp, recv_window)
Classic Portfolio Margin Account Information (USER_DATA)

Get Classic Portfolio Margin current account information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetPmAccountInfoV1Resp**](UmfuturesGetPmAccountInfoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

