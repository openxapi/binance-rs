# \MarketDataApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**spot_get_agg_trades_v3**](MarketDataApi.md#spot_get_agg_trades_v3) | **GET** /api/v3/aggTrades | Compressed/Aggregate trades list
[**spot_get_avg_price_v3**](MarketDataApi.md#spot_get_avg_price_v3) | **GET** /api/v3/avgPrice | Current average price
[**spot_get_depth_v3**](MarketDataApi.md#spot_get_depth_v3) | **GET** /api/v3/depth | Order book
[**spot_get_historical_trades_v3**](MarketDataApi.md#spot_get_historical_trades_v3) | **GET** /api/v3/historicalTrades | Old trade lookup
[**spot_get_klines_v3**](MarketDataApi.md#spot_get_klines_v3) | **GET** /api/v3/klines | Kline/Candlestick data
[**spot_get_ticker24hr_v3**](MarketDataApi.md#spot_get_ticker24hr_v3) | **GET** /api/v3/ticker/24hr | 24hr ticker price change statistics
[**spot_get_ticker_book_ticker_v3**](MarketDataApi.md#spot_get_ticker_book_ticker_v3) | **GET** /api/v3/ticker/bookTicker | Symbol order book ticker
[**spot_get_ticker_price_v3**](MarketDataApi.md#spot_get_ticker_price_v3) | **GET** /api/v3/ticker/price | Symbol price ticker
[**spot_get_ticker_trading_day_v3**](MarketDataApi.md#spot_get_ticker_trading_day_v3) | **GET** /api/v3/ticker/tradingDay | Trading Day Ticker
[**spot_get_ticker_v3**](MarketDataApi.md#spot_get_ticker_v3) | **GET** /api/v3/ticker | Rolling window price change statistics
[**spot_get_trades_v3**](MarketDataApi.md#spot_get_trades_v3) | **GET** /api/v3/trades | Recent trades list
[**spot_get_ui_klines_v3**](MarketDataApi.md#spot_get_ui_klines_v3) | **GET** /api/v3/uiKlines | UIKlines



## spot_get_agg_trades_v3

> Vec<models::SpotGetAggTradesV3RespItem> spot_get_agg_trades_v3(symbol, from_id, start_time, end_time, limit)
Compressed/Aggregate trades list

Get compressed, aggregate trades. Trades that fill at the time, from the same taker order, with the same price will have the quantity aggregated.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**from_id** | Option<**i64**> | ID to get aggregate trades from INCLUSIVE. |  |
**start_time** | Option<**i64**> | Timestamp in ms to get aggregate trades from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get aggregate trades until INCLUSIVE. |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]

### Return type

[**Vec<models::SpotGetAggTradesV3RespItem>**](SpotGetAggTradesV3RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_avg_price_v3

> models::SpotGetAvgPriceV3Resp spot_get_avg_price_v3(symbol)
Current average price

Current average price for a symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::SpotGetAvgPriceV3Resp**](SpotGetAvgPriceV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_depth_v3

> models::SpotGetDepthV3Resp spot_get_depth_v3(symbol, limit)
Order book

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 100; max 5000. <br/> If limit &gt; 5000. then the response will truncate to 5000. |  |[default to 100]

### Return type

[**models::SpotGetDepthV3Resp**](SpotGetDepthV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_historical_trades_v3

> Vec<models::SpotGetHistoricalTradesV3RespItem> spot_get_historical_trades_v3(symbol, limit, from_id)
Old trade lookup

Get older trades.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]
**from_id** | Option<**i64**> | TradeId to fetch from. Default gets most recent trades. |  |

### Return type

[**Vec<models::SpotGetHistoricalTradesV3RespItem>**](SpotGetHistoricalTradesV3RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_klines_v3

> Vec<Vec<models::SpotGetKlinesV3200ResponseInnerInner>> spot_get_klines_v3(symbol, interval, start_time, end_time, time_zone, limit)
Kline/Candlestick data

Kline/candlestick bars for a symbol. Klines are uniquely identified by their open time.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**interval** | **String** |  | [required] |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**time_zone** | Option<**String**> | Default: 0 (UTC) |  |[default to 0]
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]

### Return type

[**Vec<Vec<models::SpotGetKlinesV3200ResponseInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_ticker24hr_v3

> models::SpotGetTicker24hrV3Resp spot_get_ticker24hr_v3(symbol, symbols, r#type)
24hr ticker price change statistics

24 hour rolling window price change statistics. Careful when accessing this with no symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> | Parameter symbol and symbols cannot be used in combination. <br/> If neither parameter is sent, tickers for all symbols will be returned in an array. <br/><br/>          Examples of accepted format for the symbols parameter:          [&#34;BTCUSDT&#34;,&#34;BNBUSDT&#34;] <br/>          or <br/>          %5B%22BTCUSDT%22,%22BNBUSDT%22%5D |  |[default to ]
**symbols** | Option<**String**> | Parameter symbol and symbols cannot be used in combination. <br/> If neither parameter is sent, tickers for all symbols will be returned in an array. <br/><br/>          Examples of accepted format for the symbols parameter:          [&#34;BTCUSDT&#34;,&#34;BNBUSDT&#34;] <br/>          or <br/>          %5B%22BTCUSDT%22,%22BNBUSDT%22%5D |  |[default to ]
**r#type** | Option<**String**> | Supported values: `FULL` or `MINI`. <br/>If none provided, the default is `FULL` |  |[default to ]

### Return type

[**models::SpotGetTicker24hrV3Resp**](SpotGetTicker24hrV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_ticker_book_ticker_v3

> models::SpotGetTickerBookTickerV3Resp spot_get_ticker_book_ticker_v3(symbol, symbols)
Symbol order book ticker

Best price/qty on the order book for a symbol or symbols.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> | Parameter symbol and symbols cannot be used in combination. <br/> If neither parameter is sent, bookTickers for all symbols will be returned in an array.          <br/><br/>         Examples of accepted format for the symbols parameter:          [&#34;BTCUSDT&#34;,&#34;BNBUSDT&#34;] <br/>          or <br/>          %5B%22BTCUSDT%22,%22BNBUSDT%22%5D |  |[default to ]
**symbols** | Option<**String**> | Parameter symbol and symbols cannot be used in combination. <br/> If neither parameter is sent, bookTickers for all symbols will be returned in an array.          <br/><br/>         Examples of accepted format for the symbols parameter:          [&#34;BTCUSDT&#34;,&#34;BNBUSDT&#34;] <br/>          or <br/>          %5B%22BTCUSDT%22,%22BNBUSDT%22%5D |  |[default to ]

### Return type

[**models::SpotGetTickerBookTickerV3Resp**](SpotGetTickerBookTickerV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_ticker_price_v3

> models::SpotGetTickerPriceV3Resp spot_get_ticker_price_v3(symbol, symbols)
Symbol price ticker

Latest price for a symbol or symbols.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> | Parameter symbol and symbols cannot be used in combination. <br/> If neither parameter is sent, prices for all symbols will be returned in an array. <br/><br/>         Examples of accepted format for the symbols parameter:          [&#34;BTCUSDT&#34;,&#34;BNBUSDT&#34;] <br/>          or <br/>          %5B%22BTCUSDT%22,%22BNBUSDT%22%5D |  |[default to ]
**symbols** | Option<**String**> | Parameter symbol and symbols cannot be used in combination. <br/> If neither parameter is sent, prices for all symbols will be returned in an array. <br/><br/>         Examples of accepted format for the symbols parameter:          [&#34;BTCUSDT&#34;,&#34;BNBUSDT&#34;] <br/>          or <br/>          %5B%22BTCUSDT%22,%22BNBUSDT%22%5D |  |[default to ]

### Return type

[**models::SpotGetTickerPriceV3Resp**](SpotGetTickerPriceV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_ticker_trading_day_v3

> models::SpotGetTickerTradingDayV3Resp spot_get_ticker_trading_day_v3(symbol, symbols, time_zone, r#type)
Trading Day Ticker

Price change statistics for a trading day. 4 for each requested symbol.  The weight for this request will cap at 200 once the number of symbols in the request is more than 50.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Either `symbol` or `symbols` must be provided <br/><br/> Examples of accepted format for the `symbols` parameter: <br/> [&#34;BTCUSDT&#34;,&#34;BNBUSDT&#34;] <br/>or <br/>%5B%22BTCUSDT%22,%22BNBUSDT%22%5D <br/><br/> The maximum number of `symbols` allowed in a request is 100. | [required] |[default to ]
**symbols** | **String** | Either `symbol` or `symbols` must be provided <br/><br/> Examples of accepted format for the `symbols` parameter: <br/> [&#34;BTCUSDT&#34;,&#34;BNBUSDT&#34;] <br/>or <br/>%5B%22BTCUSDT%22,%22BNBUSDT%22%5D <br/><br/> The maximum number of `symbols` allowed in a request is 100. | [required] |[default to ]
**time_zone** | Option<**String**> | Default: 0 (UTC) |  |[default to 0]
**r#type** | Option<**String**> | Supported values: `FULL` or `MINI`. <br/>If none provided, the default is `FULL` |  |[default to ]

### Return type

[**models::SpotGetTickerTradingDayV3Resp**](SpotGetTickerTradingDayV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_ticker_v3

> models::SpotGetTickerV3Resp spot_get_ticker_v3(symbol, symbols, window_size, r#type)
Rolling window price change statistics

Note: This endpoint is different from the GET /api/v3/ticker/24hr endpoint. The window used to compute statistics will be no more than 59999ms from the requested windowSize. openTime for /api/v3/ticker always starts on a minute, while the closeTime is the current time of the request. As such, the effective window will be up to 59999ms wider than windowSize. E.g. If the closeTime is 1641287867099 (January 04, 2022 09:17:47:099 UTC) , and the windowSize is 1d. the openTime will be: 1641201420000 (January 3, 2022, 09:17:00) 4 for each requested symbol regardless of windowSize.  The weight for this request will cap at 200 once the number of symbols in the request is more than 50.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Either `symbol` or `symbols` must be provided <br/><br/> Examples of accepted format for the `symbols` parameter: <br/> [&#34;BTCUSDT&#34;,&#34;BNBUSDT&#34;] <br/>or <br/>%5B%22BTCUSDT%22,%22BNBUSDT%22%5D <br/><br/> The maximum number of `symbols` allowed in a request is 100. | [required] |[default to ]
**symbols** | **String** | Either `symbol` or `symbols` must be provided <br/><br/> Examples of accepted format for the `symbols` parameter: <br/> [&#34;BTCUSDT&#34;,&#34;BNBUSDT&#34;] <br/>or <br/>%5B%22BTCUSDT%22,%22BNBUSDT%22%5D <br/><br/> The maximum number of `symbols` allowed in a request is 100. | [required] |[default to ]
**window_size** | Option<**String**> | Defaults to `1d` if no parameter provided <br/> Supported `windowSize` values: <br/> `1m`,`2m`....`59m` for minutes <br/> `1h`, `2h`....`23h` - for hours <br/> `1d`...`7d` - for days <br/><br/> Units cannot be combined (e.g. `1d2h` is not allowed) |  |[default to ]
**r#type** | Option<**String**> | Supported values: `FULL` or `MINI`. <br/>If none provided, the default is `FULL` |  |[default to ]

### Return type

[**models::SpotGetTickerV3Resp**](SpotGetTickerV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_trades_v3

> Vec<models::SpotGetTradesV3RespItem> spot_get_trades_v3(symbol, limit)
Recent trades list

Get recent trades.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]

### Return type

[**Vec<models::SpotGetTradesV3RespItem>**](SpotGetTradesV3RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_ui_klines_v3

> Vec<Vec<models::SpotGetKlinesV3200ResponseInnerInner>> spot_get_ui_klines_v3(symbol, interval, start_time, end_time, time_zone, limit)
UIKlines

The request is similar to klines having the same parameters and response. uiKlines return modified kline data, optimized for presentation of candlestick charts.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**interval** | **String** | See <a href=\"/docs/binance-spot-api-docs/rest-api/market-data-endpoints#kline-intervals\">`klines`</a> | [required] |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**time_zone** | Option<**String**> | Default: 0 (UTC) |  |[default to 0]
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]

### Return type

[**Vec<Vec<models::SpotGetKlinesV3200ResponseInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

