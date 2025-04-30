# \FutureCopyTradingApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**copytrading_get_copy_trading_futures_lead_symbol_v1**](FutureCopyTradingApi.md#copytrading_get_copy_trading_futures_lead_symbol_v1) | **GET** /sapi/v1/copyTrading/futures/leadSymbol | Get Futures Lead Trading Symbol Whitelist(USER_DATA)
[**copytrading_get_copy_trading_futures_user_status_v1**](FutureCopyTradingApi.md#copytrading_get_copy_trading_futures_user_status_v1) | **GET** /sapi/v1/copyTrading/futures/userStatus | Get Futures Lead Trader Status(TRADE)



## copytrading_get_copy_trading_futures_lead_symbol_v1

> models::CopytradingGetCopyTradingFuturesLeadSymbolV1Resp copytrading_get_copy_trading_futures_lead_symbol_v1(timestamp, recv_window)
Get Futures Lead Trading Symbol Whitelist(USER_DATA)

Get Futures Lead Trading Symbol Whitelist

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CopytradingGetCopyTradingFuturesLeadSymbolV1Resp**](CopytradingGetCopyTradingFuturesLeadSymbolV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## copytrading_get_copy_trading_futures_user_status_v1

> models::CopytradingGetCopyTradingFuturesUserStatusV1Resp copytrading_get_copy_trading_futures_user_status_v1(timestamp, recv_window)
Get Futures Lead Trader Status(TRADE)

Get Futures Lead Trader Status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CopytradingGetCopyTradingFuturesUserStatusV1Resp**](CopytradingGetCopyTradingFuturesUserStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

