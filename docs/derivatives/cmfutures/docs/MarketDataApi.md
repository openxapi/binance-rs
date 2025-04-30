# \MarketDataApi

All URIs are relative to *https://dapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**cmfutures_get_agg_trades_v1**](MarketDataApi.md#cmfutures_get_agg_trades_v1) | **GET** /dapi/v1/aggTrades | Compressed/Aggregate Trades List
[**cmfutures_get_constituents_v1**](MarketDataApi.md#cmfutures_get_constituents_v1) | **GET** /dapi/v1/constituents | Query Index Price Constituents
[**cmfutures_get_continuous_klines_v1**](MarketDataApi.md#cmfutures_get_continuous_klines_v1) | **GET** /dapi/v1/continuousKlines | Continuous Contract Kline/Candlestick Data
[**cmfutures_get_depth_v1**](MarketDataApi.md#cmfutures_get_depth_v1) | **GET** /dapi/v1/depth | Order Book
[**cmfutures_get_exchange_info_v1**](MarketDataApi.md#cmfutures_get_exchange_info_v1) | **GET** /dapi/v1/exchangeInfo | Exchange Information
[**cmfutures_get_funding_info_v1**](MarketDataApi.md#cmfutures_get_funding_info_v1) | **GET** /dapi/v1/fundingInfo | Get Funding Rate Info
[**cmfutures_get_funding_rate_v1**](MarketDataApi.md#cmfutures_get_funding_rate_v1) | **GET** /dapi/v1/fundingRate | Get Funding Rate History of Perpetual Futures
[**cmfutures_get_futures_data_basis**](MarketDataApi.md#cmfutures_get_futures_data_basis) | **GET** /futures/data/basis | Basis
[**cmfutures_get_futures_data_global_long_short_account_ratio**](MarketDataApi.md#cmfutures_get_futures_data_global_long_short_account_ratio) | **GET** /futures/data/globalLongShortAccountRatio | Long/Short Ratio
[**cmfutures_get_futures_data_open_interest_hist**](MarketDataApi.md#cmfutures_get_futures_data_open_interest_hist) | **GET** /futures/data/openInterestHist | Open Interest Statistics
[**cmfutures_get_futures_data_taker_buy_sell_vol**](MarketDataApi.md#cmfutures_get_futures_data_taker_buy_sell_vol) | **GET** /futures/data/takerBuySellVol | Taker Buy/Sell Volume
[**cmfutures_get_futures_data_top_long_short_account_ratio**](MarketDataApi.md#cmfutures_get_futures_data_top_long_short_account_ratio) | **GET** /futures/data/topLongShortAccountRatio | Top Trader Long/Short Ratio (Accounts)
[**cmfutures_get_futures_data_top_long_short_position_ratio**](MarketDataApi.md#cmfutures_get_futures_data_top_long_short_position_ratio) | **GET** /futures/data/topLongShortPositionRatio | Top Trader Long/Short Ratio (Positions)
[**cmfutures_get_historical_trades_v1**](MarketDataApi.md#cmfutures_get_historical_trades_v1) | **GET** /dapi/v1/historicalTrades | Old Trades Lookup(MARKET_DATA)
[**cmfutures_get_index_price_klines_v1**](MarketDataApi.md#cmfutures_get_index_price_klines_v1) | **GET** /dapi/v1/indexPriceKlines | Index Price Kline/Candlestick Data
[**cmfutures_get_klines_v1**](MarketDataApi.md#cmfutures_get_klines_v1) | **GET** /dapi/v1/klines | Kline/Candlestick Data
[**cmfutures_get_mark_price_klines_v1**](MarketDataApi.md#cmfutures_get_mark_price_klines_v1) | **GET** /dapi/v1/markPriceKlines | Mark Price Kline/Candlestick Data
[**cmfutures_get_open_interest_v1**](MarketDataApi.md#cmfutures_get_open_interest_v1) | **GET** /dapi/v1/openInterest | Open Interest
[**cmfutures_get_ping_v1**](MarketDataApi.md#cmfutures_get_ping_v1) | **GET** /dapi/v1/ping | Test Connectivity
[**cmfutures_get_premium_index_klines_v1**](MarketDataApi.md#cmfutures_get_premium_index_klines_v1) | **GET** /dapi/v1/premiumIndexKlines | Premium index Kline Data
[**cmfutures_get_premium_index_v1**](MarketDataApi.md#cmfutures_get_premium_index_v1) | **GET** /dapi/v1/premiumIndex | Index Price and Mark Price
[**cmfutures_get_ticker24hr_v1**](MarketDataApi.md#cmfutures_get_ticker24hr_v1) | **GET** /dapi/v1/ticker/24hr | 24hr Ticker Price Change Statistics
[**cmfutures_get_ticker_book_ticker_v1**](MarketDataApi.md#cmfutures_get_ticker_book_ticker_v1) | **GET** /dapi/v1/ticker/bookTicker | Symbol Order Book Ticker
[**cmfutures_get_ticker_price_v1**](MarketDataApi.md#cmfutures_get_ticker_price_v1) | **GET** /dapi/v1/ticker/price | Symbol Price Ticker
[**cmfutures_get_time_v1**](MarketDataApi.md#cmfutures_get_time_v1) | **GET** /dapi/v1/time | Check Server time
[**cmfutures_get_trades_v1**](MarketDataApi.md#cmfutures_get_trades_v1) | **GET** /dapi/v1/trades | Recent Trades List



## cmfutures_get_agg_trades_v1

> Vec<models::CmfuturesGetAggTradesV1RespItem> cmfutures_get_agg_trades_v1(symbol, from_id, start_time, end_time, limit)
Compressed/Aggregate Trades List

Get compressed, aggregate trades. Market trades that fill in 100ms with the same price and the same taking side will have the quantity aggregated.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**from_id** | Option<**i64**> | ID to get aggregate trades from INCLUSIVE. |  |
**start_time** | Option<**i64**> | Timestamp in ms to get aggregate trades from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get aggregate trades until INCLUSIVE. |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]

### Return type

[**Vec<models::CmfuturesGetAggTradesV1RespItem>**](CmfuturesGetAggTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_constituents_v1

> models::CmfuturesGetConstituentsV1Resp cmfutures_get_constituents_v1(symbol)
Query Index Price Constituents

Query index price constituents

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::CmfuturesGetConstituentsV1Resp**](CmfuturesGetConstituentsV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_continuous_klines_v1

> Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>> cmfutures_get_continuous_klines_v1(pair, contract_type, interval, start_time, end_time, limit)
Continuous Contract Kline/Candlestick Data

Kline/candlestick bars for a specific contract type. Klines are uniquely identified by their open time.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pair** | **String** |  | [required] |[default to ]
**contract_type** | **String** |  | [required] |[default to ]
**interval** | **String** |  | [required] |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500; max 1500. |  |[default to 500]

### Return type

[**Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_depth_v1

> models::CmfuturesGetDepthV1Resp cmfutures_get_depth_v1(symbol, limit)
Order Book

Query orderbook on specific symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 500; Valid limits:[5, 10, 20, 50, 100, 500, 1000] |  |[default to 500]

### Return type

[**models::CmfuturesGetDepthV1Resp**](CmfuturesGetDepthV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_exchange_info_v1

> models::CmfuturesGetExchangeInfoV1Resp cmfutures_get_exchange_info_v1()
Exchange Information

Current exchange trading rules and symbol information

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::CmfuturesGetExchangeInfoV1Resp**](CmfuturesGetExchangeInfoV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_funding_info_v1

> Vec<models::CmfuturesGetFundingInfoV1RespItem> cmfutures_get_funding_info_v1()
Get Funding Rate Info

Query funding rate info for symbols that had FundingRateCap/ FundingRateFloor / fundingIntervalHours adjustment

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::CmfuturesGetFundingInfoV1RespItem>**](CmfuturesGetFundingInfoV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_funding_rate_v1

> Vec<models::CmfuturesGetFundingRateV1RespItem> cmfutures_get_funding_rate_v1(symbol, start_time, end_time, limit)
Get Funding Rate History of Perpetual Futures

Get Funding Rate History of Perpetual Futures

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get funding rate from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get funding rate  until INCLUSIVE. |  |
**limit** | Option<**i32**> | Default 100; max 1000 |  |[default to 100]

### Return type

[**Vec<models::CmfuturesGetFundingRateV1RespItem>**](CmfuturesGetFundingRateV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_futures_data_basis

> Vec<models::CmfuturesGetFuturesDataBasisRespItem> cmfutures_get_futures_data_basis(pair, contract_type, period, limit, start_time, end_time)
Basis

Query basis

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pair** | **String** | BTCUSD | [required] |[default to ]
**contract_type** | **String** | CURRENT_QUARTER, NEXT_QUARTER, PERPETUAL | [required] |[default to ]
**period** | **String** | &#34;5m&#34;,&#34;15m&#34;,&#34;30m&#34;,&#34;1h&#34;,&#34;2h&#34;,&#34;4h&#34;,&#34;6h&#34;,&#34;12h&#34;,&#34;1d&#34; | [required] |[default to ]
**limit** | Option<**i64**> | Default 30,Max 500 |  |[default to 30]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesGetFuturesDataBasisRespItem>**](CmfuturesGetFuturesDataBasisRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_futures_data_global_long_short_account_ratio

> Vec<models::CmfuturesGetFuturesDataGlobalLongShortAccountRatioRespItem> cmfutures_get_futures_data_global_long_short_account_ratio(pair, period, limit, start_time, end_time)
Long/Short Ratio

Query symbol Long/Short Ratio

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pair** | **String** | BTCUSD | [required] |[default to ]
**period** | **String** | &#34;5m&#34;,&#34;15m&#34;,&#34;30m&#34;,&#34;1h&#34;,&#34;2h&#34;,&#34;4h&#34;,&#34;6h&#34;,&#34;12h&#34;,&#34;1d&#34; | [required] |[default to ]
**limit** | Option<**i64**> | Default 30,Max 500 |  |[default to 30]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesGetFuturesDataGlobalLongShortAccountRatioRespItem>**](CmfuturesGetFuturesDataGlobalLongShortAccountRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_futures_data_open_interest_hist

> Vec<models::CmfuturesGetFuturesDataOpenInterestHistRespItem> cmfutures_get_futures_data_open_interest_hist(pair, contract_type, period, limit, start_time, end_time)
Open Interest Statistics

Query open interest stats

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pair** | **String** | BTCUSD | [required] |[default to ]
**contract_type** | **String** | ALL, CURRENT_QUARTER, NEXT_QUARTER, PERPETUAL | [required] |[default to ]
**period** | **String** | &#34;5m&#34;,&#34;15m&#34;,&#34;30m&#34;,&#34;1h&#34;,&#34;2h&#34;,&#34;4h&#34;,&#34;6h&#34;,&#34;12h&#34;,&#34;1d&#34; | [required] |[default to ]
**limit** | Option<**i64**> | Default 30,Max 500 |  |[default to 30]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesGetFuturesDataOpenInterestHistRespItem>**](CmfuturesGetFuturesDataOpenInterestHistRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_futures_data_taker_buy_sell_vol

> Vec<models::CmfuturesGetFuturesDataTakerBuySellVolRespItem> cmfutures_get_futures_data_taker_buy_sell_vol(pair, contract_type, period, limit, start_time, end_time)
Taker Buy/Sell Volume

Taker Buy Volume: the total volume of buy orders filled by takers within the period. Taker Sell Volume: the total volume of sell orders filled by takers within the period.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pair** | **String** | BTCUSD | [required] |[default to ]
**contract_type** | **String** | ALL, CURRENT_QUARTER, NEXT_QUARTER, PERPETUAL | [required] |[default to ]
**period** | **String** | &#34;5m&#34;,&#34;15m&#34;,&#34;30m&#34;,&#34;1h&#34;,&#34;2h&#34;,&#34;4h&#34;,&#34;6h&#34;,&#34;12h&#34;,&#34;1d&#34; | [required] |[default to ]
**limit** | Option<**i64**> | Default 30,Max 500 |  |[default to 30]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesGetFuturesDataTakerBuySellVolRespItem>**](CmfuturesGetFuturesDataTakerBuySellVolRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_futures_data_top_long_short_account_ratio

> Vec<models::CmfuturesGetFuturesDataTopLongShortAccountRatioRespItem> cmfutures_get_futures_data_top_long_short_account_ratio(symbol, period, limit, start_time, end_time)
Top Trader Long/Short Ratio (Accounts)

The proportion of net long and net short accounts to total accounts of the top 20% users with the highest margin balance. Each account is counted once only. Long Account % = Accounts of top traders with net long positions / Total accounts of top traders with open positions Short Account % = Accounts of top traders with net short positions / Total accounts of top traders with open positions Long/Short Ratio (Accounts) = Long Account % / Short Account %

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**period** | **String** | &#34;5m&#34;,&#34;15m&#34;,&#34;30m&#34;,&#34;1h&#34;,&#34;2h&#34;,&#34;4h&#34;,&#34;6h&#34;,&#34;12h&#34;,&#34;1d&#34; | [required] |[default to ]
**limit** | Option<**i64**> | default 30, max 500 |  |[default to 30]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesGetFuturesDataTopLongShortAccountRatioRespItem>**](CmfuturesGetFuturesDataTopLongShortAccountRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_futures_data_top_long_short_position_ratio

> Vec<models::CmfuturesGetFuturesDataTopLongShortPositionRatioRespItem> cmfutures_get_futures_data_top_long_short_position_ratio(pair, period, limit, start_time, end_time)
Top Trader Long/Short Ratio (Positions)

The proportion of net long and net short positions to total open positions of the top 20% users with the highest margin balance. Long Position % = Long positions of top traders / Total open positions of top traders Short Position % = Short positions of top traders / Total open positions of top traders Long/Short Ratio (Positions) = Long Position % / Short Position %

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pair** | **String** | BTCUSD | [required] |[default to ]
**period** | **String** | &#34;5m&#34;,&#34;15m&#34;,&#34;30m&#34;,&#34;1h&#34;,&#34;2h&#34;,&#34;4h&#34;,&#34;6h&#34;,&#34;12h&#34;,&#34;1d&#34; | [required] |[default to ]
**limit** | Option<**i64**> | Default 30,Max 500 |  |[default to 30]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesGetFuturesDataTopLongShortPositionRatioRespItem>**](CmfuturesGetFuturesDataTopLongShortPositionRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_historical_trades_v1

> Vec<models::CmfuturesGetHistoricalTradesV1RespItem> cmfutures_get_historical_trades_v1(symbol, limit, from_id)
Old Trades Lookup(MARKET_DATA)

Get older market historical trades.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 100; max 500. |  |[default to 100]
**from_id** | Option<**i64**> | TradeId to fetch from. Default gets most recent trades. |  |

### Return type

[**Vec<models::CmfuturesGetHistoricalTradesV1RespItem>**](CmfuturesGetHistoricalTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_index_price_klines_v1

> Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>> cmfutures_get_index_price_klines_v1(pair, interval, start_time, end_time, limit)
Index Price Kline/Candlestick Data

Kline/candlestick bars for the index price of a pair. Klines are uniquely identified by their open time.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pair** | **String** |  | [required] |[default to ]
**interval** | **String** |  | [required] |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500; max 1500. |  |[default to 500]

### Return type

[**Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_klines_v1

> Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>> cmfutures_get_klines_v1(symbol, interval, start_time, end_time, limit)
Kline/Candlestick Data

Kline/candlestick bars for a symbol. Klines are uniquely identified by their open time.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**interval** | **String** |  | [required] |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500; max 1500. |  |[default to 500]

### Return type

[**Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_mark_price_klines_v1

> Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>> cmfutures_get_mark_price_klines_v1(symbol, interval, start_time, end_time, limit)
Mark Price Kline/Candlestick Data

Kline/candlestick bars for the mark price of a symbol. Klines are uniquely identified by their open time.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**interval** | **String** |  | [required] |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500; max 1500. |  |[default to 500]

### Return type

[**Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_open_interest_v1

> models::CmfuturesGetOpenInterestV1Resp cmfutures_get_open_interest_v1(symbol)
Open Interest

Get present open interest of a specific symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::CmfuturesGetOpenInterestV1Resp**](CmfuturesGetOpenInterestV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_ping_v1

> serde_json::Value cmfutures_get_ping_v1()
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


## cmfutures_get_premium_index_klines_v1

> Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>> cmfutures_get_premium_index_klines_v1(symbol, interval, start_time, end_time, limit)
Premium index Kline Data

Premium index kline bars of a symbol. Klines are uniquely identified by their open time.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**interval** | **String** |  | [required] |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500; max 1500. |  |[default to 500]

### Return type

[**Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_premium_index_v1

> Vec<models::CmfuturesGetPremiumIndexV1RespItem> cmfutures_get_premium_index_v1(symbol, pair)
Index Price and Mark Price

Query index price and mark price

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::CmfuturesGetPremiumIndexV1RespItem>**](CmfuturesGetPremiumIndexV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_ticker24hr_v1

> Vec<models::CmfuturesGetTicker24hrV1RespItem> cmfutures_get_ticker24hr_v1(symbol, pair)
24hr Ticker Price Change Statistics

24 hour rolling window price change statistics.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::CmfuturesGetTicker24hrV1RespItem>**](CmfuturesGetTicker24hrV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_ticker_book_ticker_v1

> Vec<models::CmfuturesGetTickerBookTickerV1RespItem> cmfutures_get_ticker_book_ticker_v1(symbol, pair)
Symbol Order Book Ticker

Best price/qty on the order book for a symbol or symbols.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::CmfuturesGetTickerBookTickerV1RespItem>**](CmfuturesGetTickerBookTickerV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_ticker_price_v1

> Vec<models::CmfuturesGetTickerPriceV1RespItem> cmfutures_get_ticker_price_v1(symbol, pair)
Symbol Price Ticker

Latest price for a symbol or symbols.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::CmfuturesGetTickerPriceV1RespItem>**](CmfuturesGetTickerPriceV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_time_v1

> models::CmfuturesGetTimeV1Resp cmfutures_get_time_v1()
Check Server time

Test connectivity to the Rest API and get the current server time.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::CmfuturesGetTimeV1Resp**](CmfuturesGetTimeV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_trades_v1

> Vec<models::CmfuturesGetTradesV1RespItem> cmfutures_get_trades_v1(symbol, limit)
Recent Trades List

Get recent market trades

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]

### Return type

[**Vec<models::CmfuturesGetTradesV1RespItem>**](CmfuturesGetTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

