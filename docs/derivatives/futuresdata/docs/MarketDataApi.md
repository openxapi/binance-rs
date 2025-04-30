# \MarketDataApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**futuresdata_get_futures_hist_data_link_v1**](MarketDataApi.md#futuresdata_get_futures_hist_data_link_v1) | **GET** /sapi/v1/futures/histDataLink | Get Future TickLevel Orderbook Historical Data Download Link(USER_DATA)



## futuresdata_get_futures_hist_data_link_v1

> models::FuturesdataGetFuturesHistDataLinkV1Resp futuresdata_get_futures_hist_data_link_v1(symbol, data_type, start_time, end_time, timestamp, recv_window)
Get Future TickLevel Orderbook Historical Data Download Link(USER_DATA)

Get Future TickLevel Orderbook Historical Data Download Link

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | symbol name, e.g. BTCUSDT or BTCUSD_PERP ｜ | [required] |[default to ]
**data_type** | **String** | `T_DEPTH` for ticklevel orderbook data, `S_DEPTH` for orderbook snapshot data | [required] |[default to ]
**start_time** | **i64** |  | [required] |
**end_time** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::FuturesdataGetFuturesHistDataLinkV1Resp**](FuturesdataGetFuturesHistDataLinkV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

