# \CopyTradingApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_copy_trading_futures_lead_symbol_v1**](CopyTradingApi.md#get_copy_trading_futures_lead_symbol_v1) | **GET** /sapi/v1/copyTrading/futures/leadSymbol | Get Futures Lead Trading Symbol Whitelist(USER_DATA)
[**get_copy_trading_futures_user_status_v1**](CopyTradingApi.md#get_copy_trading_futures_user_status_v1) | **GET** /sapi/v1/copyTrading/futures/userStatus | Get Futures Lead Trader Status(TRADE)



## get_copy_trading_futures_lead_symbol_v1

> models::GetCopyTradingFuturesLeadSymbolV1Resp get_copy_trading_futures_lead_symbol_v1(timestamp, recv_window)
Get Futures Lead Trading Symbol Whitelist(USER_DATA)

Get Futures Lead Trading Symbol Whitelist

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetCopyTradingFuturesLeadSymbolV1Resp**](GetCopyTradingFuturesLeadSymbolV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_copy_trading_futures_user_status_v1

> models::GetCopyTradingFuturesUserStatusV1Resp get_copy_trading_futures_user_status_v1(timestamp, recv_window)
Get Futures Lead Trader Status(TRADE)

Get Futures Lead Trader Status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetCopyTradingFuturesUserStatusV1Resp**](GetCopyTradingFuturesUserStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

