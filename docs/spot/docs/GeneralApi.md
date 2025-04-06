# \GeneralApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**spot_get_exchange_info_v3**](GeneralApi.md#spot_get_exchange_info_v3) | **GET** /api/v3/exchangeInfo | Exchange information
[**spot_get_ping_v3**](GeneralApi.md#spot_get_ping_v3) | **GET** /api/v3/ping | Test connectivity
[**spot_get_time_v3**](GeneralApi.md#spot_get_time_v3) | **GET** /api/v3/time | Check server time



## spot_get_exchange_info_v3

> models::SpotGetExchangeInfoV3Resp spot_get_exchange_info_v3(symbol, symbols, permissions, show_permission_sets, symbol_status)
Exchange information

Current exchange trading rules and symbol information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> | Example: curl -X GET &#34;<a href=\"https://api.binance.com/api/v3/exchangeInfo?symbol=BNBBTC\" target=\"_blank\" rel=\"noopener noreferrer\">https://api.binance.com/api/v3/exchangeInfo?symbol=BNBBTC</a>&#34; |  |[default to ]
**symbols** | Option<[**Vec<String>**](String.md)> | Examples: curl -X GET &#34;<a href=\"https://api.binance.com/api/v3/exchangeInfo?symbols=%5B%22BNBBTC%22,%22BTCUSDT%22%5D\" target=\"_blank\" rel=\"noopener noreferrer\">https://api.binance.com/api/v3/exchangeInfo?symbols=%5B%22BNBBTC%22,%22BTCUSDT%22%5D</a>&#34; <br/> or <br/> curl -g -X  GET &#39;<a href=\"https://api.binance.com/api/v3/exchangeInfo?symbols=%5B%22BTCUSDT%22,%22BNBBTC\" target=\"_blank\" rel=\"noopener noreferrer\">https://api.binance.com/api/v3/exchangeInfo?symbols=[&#34;BTCUSDT&#34;,&#34;BNBBTC</a>&#34;]&#39; |  |
**permissions** | Option<**String**> | Examples: curl -X GET &#34;<a href=\"https://api.binance.com/api/v3/exchangeInfo?permissions=SPOT\" target=\"_blank\" rel=\"noopener noreferrer\">https://api.binance.com/api/v3/exchangeInfo?permissions=SPOT</a>&#34; <br/> or <br/> curl -X GET &#34;<a href=\"https://api.binance.com/api/v3/exchangeInfo?permissions=%5B%22MARGIN%22%2C%22LEVERAGED%22%5D\" target=\"_blank\" rel=\"noopener noreferrer\">https://api.binance.com/api/v3/exchangeInfo?permissions=%5B%22MARGIN%22%2C%22LEVERAGED%22%5D</a>&#34; <br/> or <br/> curl -g -X GET &#39;<a href=\"https://api.binance.com/api/v3/exchangeInfo?permissions=%5B%22MARGIN%22,%22LEVERAGED\" target=\"_blank\" rel=\"noopener noreferrer\">https://api.binance.com/api/v3/exchangeInfo?permissions=[&#34;MARGIN&#34;,&#34;LEVERAGED</a>&#34;]&#39; |  |[default to ]
**show_permission_sets** | Option<**bool**> | Controls whether the content of the `permissionSets` field is populated or not. Defaults to `true` |  |
**symbol_status** | Option<**String**> | Filters symbols that have this `tradingStatus`. Valid values: `TRADING`, `HALT`, `BREAK` <br/> Cannot be used in combination with `symbols` or `symbol`. |  |[default to ]

### Return type

[**models::SpotGetExchangeInfoV3Resp**](SpotGetExchangeInfoV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_ping_v3

> serde_json::Value spot_get_ping_v3()
Test connectivity

Test connectivity to the Rest API.

### Parameters

This endpoint does not need any parameter.

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_time_v3

> models::SpotGetTimeV3Resp spot_get_time_v3()
Check server time

Test connectivity to the Rest API and get the current server time.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::SpotGetTimeV3Resp**](SpotGetTimeV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

