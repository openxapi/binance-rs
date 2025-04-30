# \MarketDataApi

All URIs are relative to *https://eapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**options_get_block_trades_v1**](MarketDataApi.md#options_get_block_trades_v1) | **GET** /eapi/v1/blockTrades | Recent Block Trades List
[**options_get_depth_v1**](MarketDataApi.md#options_get_depth_v1) | **GET** /eapi/v1/depth | Order Book
[**options_get_exchange_info_v1**](MarketDataApi.md#options_get_exchange_info_v1) | **GET** /eapi/v1/exchangeInfo | Exchange Information
[**options_get_exercise_history_v1**](MarketDataApi.md#options_get_exercise_history_v1) | **GET** /eapi/v1/exerciseHistory | Historical Exercise Records
[**options_get_historical_trades_v1**](MarketDataApi.md#options_get_historical_trades_v1) | **GET** /eapi/v1/historicalTrades | Old Trades Lookup (MARKET_DATA)
[**options_get_index_v1**](MarketDataApi.md#options_get_index_v1) | **GET** /eapi/v1/index | Symbol Price Ticker
[**options_get_klines_v1**](MarketDataApi.md#options_get_klines_v1) | **GET** /eapi/v1/klines | Kline/Candlestick Data
[**options_get_mark_v1**](MarketDataApi.md#options_get_mark_v1) | **GET** /eapi/v1/mark | Option Mark Price
[**options_get_open_interest_v1**](MarketDataApi.md#options_get_open_interest_v1) | **GET** /eapi/v1/openInterest | Open Interest
[**options_get_ping_v1**](MarketDataApi.md#options_get_ping_v1) | **GET** /eapi/v1/ping | Test Connectivity
[**options_get_ticker_v1**](MarketDataApi.md#options_get_ticker_v1) | **GET** /eapi/v1/ticker | 24hr Ticker Price Change Statistics
[**options_get_time_v1**](MarketDataApi.md#options_get_time_v1) | **GET** /eapi/v1/time | Check Server Time
[**options_get_trades_v1**](MarketDataApi.md#options_get_trades_v1) | **GET** /eapi/v1/trades | Recent Trades List



## options_get_block_trades_v1

> Vec<models::OptionsGetBlockTradesV1RespItem> options_get_block_trades_v1(symbol, limit)
Recent Block Trades List

Get recent block trades

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> | Option trading pair, e.g. BTC-200730-9000-C |  |[default to ]
**limit** | Option<**i32**> | Number of records; Default: 100 and Max: 500 |  |[default to 100]

### Return type

[**Vec<models::OptionsGetBlockTradesV1RespItem>**](OptionsGetBlockTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_depth_v1

> models::OptionsGetDepthV1Resp options_get_depth_v1(symbol, limit)
Order Book

Check orderbook depth on specific symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair, e.g BTC-200730-9000-C | [required] |[default to ]
**limit** | Option<**i32**> | Default:100 Max:1000.Optional value:[10, 20, 50, 100, 500, 1000] |  |

### Return type

[**models::OptionsGetDepthV1Resp**](OptionsGetDepthV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_exchange_info_v1

> models::OptionsGetExchangeInfoV1Resp options_get_exchange_info_v1()
Exchange Information

Current exchange trading rules and symbol information

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::OptionsGetExchangeInfoV1Resp**](OptionsGetExchangeInfoV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_exercise_history_v1

> Vec<models::OptionsGetExerciseHistoryV1RespItem> options_get_exercise_history_v1(underlying, start_time, end_time, limit)
Historical Exercise Records

Get historical exercise records.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**underlying** | Option<**String**> | Underlying index like BTCUSDT |  |[default to ]
**start_time** | Option<**i64**> | Start Time |  |
**end_time** | Option<**i64**> | End Time |  |
**limit** | Option<**i32**> | Number of records Default:100 Max:100 |  |

### Return type

[**Vec<models::OptionsGetExerciseHistoryV1RespItem>**](OptionsGetExerciseHistoryV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_historical_trades_v1

> Vec<models::OptionsGetHistoricalTradesV1RespItem> options_get_historical_trades_v1(symbol, from_id, limit)
Old Trades Lookup (MARKET_DATA)

Get older market historical trades.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair, e.g BTC-200730-9000-C | [required] |[default to ]
**from_id** | Option<**i64**> | The UniqueId ID from which to return. The latest deal record is returned by default |  |
**limit** | Option<**i32**> | Number of records Default:100 Max:500 |  |

### Return type

[**Vec<models::OptionsGetHistoricalTradesV1RespItem>**](OptionsGetHistoricalTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_index_v1

> models::OptionsGetIndexV1Resp options_get_index_v1(underlying)
Symbol Price Ticker

Get spot index price for option underlying.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**underlying** | **String** | Spot pair（Option contract underlying asset, e.g BTCUSDT) | [required] |[default to ]

### Return type

[**models::OptionsGetIndexV1Resp**](OptionsGetIndexV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_klines_v1

> Vec<models::OptionsGetKlinesV1RespItem> options_get_klines_v1(symbol, interval, start_time, end_time, limit)
Kline/Candlestick Data

Kline/candlestick bars for an option symbol. Klines are uniquely identified by their open time.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair, e.g BTC-200730-9000-C | [required] |[default to ]
**interval** | **String** | Time interval | [required] |[default to ]
**start_time** | Option<**i64**> | Start Time  1592317127349 |  |
**end_time** | Option<**i64**> | End Time |  |
**limit** | Option<**i32**> | Number of records Default:500 Max:1500 |  |

### Return type

[**Vec<models::OptionsGetKlinesV1RespItem>**](OptionsGetKlinesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_mark_v1

> Vec<models::OptionsGetMarkV1RespItem> options_get_mark_v1(symbol)
Option Mark Price

Option mark price and greek info.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> | Option trading pair, e.g BTC-200730-9000-C |  |[default to ]

### Return type

[**Vec<models::OptionsGetMarkV1RespItem>**](OptionsGetMarkV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_open_interest_v1

> Vec<models::OptionsGetOpenInterestV1RespItem> options_get_open_interest_v1(underlying_asset, expiration)
Open Interest

Get open interest for specific underlying asset on specific expiration date.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**underlying_asset** | **String** | underlying asset, e.g ETH/BTC | [required] |[default to ]
**expiration** | **String** | expiration date, e.g 221225 | [required] |[default to ]

### Return type

[**Vec<models::OptionsGetOpenInterestV1RespItem>**](OptionsGetOpenInterestV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_ping_v1

> serde_json::Value options_get_ping_v1()
Test Connectivity

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


## options_get_ticker_v1

> Vec<models::OptionsGetTickerV1RespItem> options_get_ticker_v1(symbol)
24hr Ticker Price Change Statistics

24 hour rolling window price change statistics.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> | Option trading pair, e.g BTC-200730-9000-C |  |[default to ]

### Return type

[**Vec<models::OptionsGetTickerV1RespItem>**](OptionsGetTickerV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_time_v1

> models::OptionsGetTimeV1Resp options_get_time_v1()
Check Server Time

Test connectivity to the Rest API and get the current server time.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::OptionsGetTimeV1Resp**](OptionsGetTimeV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_trades_v1

> Vec<models::OptionsGetTradesV1RespItem> options_get_trades_v1(symbol, limit)
Recent Trades List

Get recent market trades

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair, e.g BTC-200730-9000-C | [required] |[default to ]
**limit** | Option<**i32**> | Number of records Default:100 Max:500 |  |

### Return type

[**Vec<models::OptionsGetTradesV1RespItem>**](OptionsGetTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

