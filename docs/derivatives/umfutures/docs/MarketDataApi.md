# \MarketDataApi

All URIs are relative to *https://fapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**umfutures_get_agg_trades_v1**](MarketDataApi.md#umfutures_get_agg_trades_v1) | **GET** /fapi/v1/aggTrades | Compressed/Aggregate Trades List
[**umfutures_get_asset_index_v1**](MarketDataApi.md#umfutures_get_asset_index_v1) | **GET** /fapi/v1/assetIndex | Multi-Assets Mode Asset Index
[**umfutures_get_constituents_v1**](MarketDataApi.md#umfutures_get_constituents_v1) | **GET** /fapi/v1/constituents | Query Index Price Constituents
[**umfutures_get_continuous_klines_v1**](MarketDataApi.md#umfutures_get_continuous_klines_v1) | **GET** /fapi/v1/continuousKlines | Continuous Contract Kline/Candlestick Data
[**umfutures_get_depth_v1**](MarketDataApi.md#umfutures_get_depth_v1) | **GET** /fapi/v1/depth | Order Book
[**umfutures_get_exchange_info_v1**](MarketDataApi.md#umfutures_get_exchange_info_v1) | **GET** /fapi/v1/exchangeInfo | Exchange Information
[**umfutures_get_funding_info_v1**](MarketDataApi.md#umfutures_get_funding_info_v1) | **GET** /fapi/v1/fundingInfo | Get Funding Rate Info
[**umfutures_get_funding_rate_v1**](MarketDataApi.md#umfutures_get_funding_rate_v1) | **GET** /fapi/v1/fundingRate | Get Funding Rate History
[**umfutures_get_futures_data_basis**](MarketDataApi.md#umfutures_get_futures_data_basis) | **GET** /futures/data/basis | Basis
[**umfutures_get_futures_data_delivery_price**](MarketDataApi.md#umfutures_get_futures_data_delivery_price) | **GET** /futures/data/delivery-price | Quarterly Contract Settlement Price
[**umfutures_get_futures_data_global_long_short_account_ratio**](MarketDataApi.md#umfutures_get_futures_data_global_long_short_account_ratio) | **GET** /futures/data/globalLongShortAccountRatio | Long/Short Ratio
[**umfutures_get_futures_data_open_interest_hist**](MarketDataApi.md#umfutures_get_futures_data_open_interest_hist) | **GET** /futures/data/openInterestHist | Open Interest Statistics
[**umfutures_get_futures_data_takerlongshort_ratio**](MarketDataApi.md#umfutures_get_futures_data_takerlongshort_ratio) | **GET** /futures/data/takerlongshortRatio | Taker Buy/Sell Volume
[**umfutures_get_futures_data_top_long_short_account_ratio**](MarketDataApi.md#umfutures_get_futures_data_top_long_short_account_ratio) | **GET** /futures/data/topLongShortAccountRatio | Top Trader Long/Short Ratio (Accounts)
[**umfutures_get_futures_data_top_long_short_position_ratio**](MarketDataApi.md#umfutures_get_futures_data_top_long_short_position_ratio) | **GET** /futures/data/topLongShortPositionRatio | Top Trader Long/Short Ratio (Positions)
[**umfutures_get_historical_trades_v1**](MarketDataApi.md#umfutures_get_historical_trades_v1) | **GET** /fapi/v1/historicalTrades | Old Trades Lookup (MARKET_DATA)
[**umfutures_get_index_info_v1**](MarketDataApi.md#umfutures_get_index_info_v1) | **GET** /fapi/v1/indexInfo | Composite Index Symbol Information
[**umfutures_get_index_price_klines_v1**](MarketDataApi.md#umfutures_get_index_price_klines_v1) | **GET** /fapi/v1/indexPriceKlines | Index Price Kline/Candlestick Data
[**umfutures_get_klines_v1**](MarketDataApi.md#umfutures_get_klines_v1) | **GET** /fapi/v1/klines | Kline/Candlestick Data
[**umfutures_get_mark_price_klines_v1**](MarketDataApi.md#umfutures_get_mark_price_klines_v1) | **GET** /fapi/v1/markPriceKlines | Mark Price Kline/Candlestick Data
[**umfutures_get_open_interest_v1**](MarketDataApi.md#umfutures_get_open_interest_v1) | **GET** /fapi/v1/openInterest | Open Interest
[**umfutures_get_ping_v1**](MarketDataApi.md#umfutures_get_ping_v1) | **GET** /fapi/v1/ping | Test Connectivity
[**umfutures_get_premium_index_klines_v1**](MarketDataApi.md#umfutures_get_premium_index_klines_v1) | **GET** /fapi/v1/premiumIndexKlines | Premium index Kline Data
[**umfutures_get_premium_index_v1**](MarketDataApi.md#umfutures_get_premium_index_v1) | **GET** /fapi/v1/premiumIndex | Mark Price
[**umfutures_get_ticker24hr_v1**](MarketDataApi.md#umfutures_get_ticker24hr_v1) | **GET** /fapi/v1/ticker/24hr | 24hr Ticker Price Change Statistics
[**umfutures_get_ticker_book_ticker_v1**](MarketDataApi.md#umfutures_get_ticker_book_ticker_v1) | **GET** /fapi/v1/ticker/bookTicker | Symbol Order Book Ticker
[**umfutures_get_ticker_price_v1**](MarketDataApi.md#umfutures_get_ticker_price_v1) | **GET** /fapi/v1/ticker/price | Symbol Price Ticker
[**umfutures_get_ticker_price_v2**](MarketDataApi.md#umfutures_get_ticker_price_v2) | **GET** /fapi/v2/ticker/price | Symbol Price Ticker V2
[**umfutures_get_time_v1**](MarketDataApi.md#umfutures_get_time_v1) | **GET** /fapi/v1/time | Check Server Time
[**umfutures_get_trades_v1**](MarketDataApi.md#umfutures_get_trades_v1) | **GET** /fapi/v1/trades | Recent Trades List



## umfutures_get_agg_trades_v1

> Vec<models::UmfuturesGetAggTradesV1RespItem> umfutures_get_agg_trades_v1(symbol, from_id, start_time, end_time, limit)
Compressed/Aggregate Trades List

Get compressed, aggregate market trades. Market trades that fill in 100ms with the same price and the same taking side will have the quantity aggregated.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**from_id** | Option<**i64**> | ID to get aggregate trades from INCLUSIVE. |  |
**start_time** | Option<**i64**> | Timestamp in ms to get aggregate trades from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get aggregate trades until INCLUSIVE. |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]

### Return type

[**Vec<models::UmfuturesGetAggTradesV1RespItem>**](UmfuturesGetAggTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_asset_index_v1

> models::UmfuturesGetAssetIndexV1Resp umfutures_get_asset_index_v1(symbol)
Multi-Assets Mode Asset Index

asset index for Multi-Assets mode

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> | Asset pair |  |[default to ]

### Return type

[**models::UmfuturesGetAssetIndexV1Resp**](UmfuturesGetAssetIndexV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_constituents_v1

> models::UmfuturesGetConstituentsV1Resp umfutures_get_constituents_v1(symbol)
Query Index Price Constituents

Query index price constituents

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::UmfuturesGetConstituentsV1Resp**](UmfuturesGetConstituentsV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_continuous_klines_v1

> Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>> umfutures_get_continuous_klines_v1(pair, contract_type, interval, start_time, end_time, limit)
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

[**Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_depth_v1

> models::UmfuturesGetDepthV1Resp umfutures_get_depth_v1(symbol, limit)
Order Book

Query symbol orderbook

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 500; Valid limits:[5, 10, 20, 50, 100, 500, 1000] |  |[default to 500]

### Return type

[**models::UmfuturesGetDepthV1Resp**](UmfuturesGetDepthV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_exchange_info_v1

> models::UmfuturesGetExchangeInfoV1Resp umfutures_get_exchange_info_v1()
Exchange Information

Current exchange trading rules and symbol information

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::UmfuturesGetExchangeInfoV1Resp**](UmfuturesGetExchangeInfoV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_funding_info_v1

> Vec<models::UmfuturesGetFundingInfoV1RespItem> umfutures_get_funding_info_v1()
Get Funding Rate Info

Query funding rate info for symbols that had FundingRateCap/ FundingRateFloor / fundingIntervalHours adjustment

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::UmfuturesGetFundingInfoV1RespItem>**](UmfuturesGetFundingInfoV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_funding_rate_v1

> Vec<models::UmfuturesGetFundingRateV1RespItem> umfutures_get_funding_rate_v1(symbol, start_time, end_time, limit)
Get Funding Rate History

Get Funding Rate History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get funding rate from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get funding rate  until INCLUSIVE. |  |
**limit** | Option<**i32**> | Default 100; max 1000 |  |[default to 100]

### Return type

[**Vec<models::UmfuturesGetFundingRateV1RespItem>**](UmfuturesGetFundingRateV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_futures_data_basis

> Vec<models::UmfuturesGetFuturesDataBasisRespItem> umfutures_get_futures_data_basis(pair, contract_type, period, limit, start_time, end_time)
Basis

Query future basis

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pair** | **String** | BTCUSDT | [required] |[default to ]
**contract_type** | **String** | CURRENT_QUARTER, NEXT_QUARTER, PERPETUAL | [required] |[default to ]
**period** | **String** | &#34;5m&#34;,&#34;15m&#34;,&#34;30m&#34;,&#34;1h&#34;,&#34;2h&#34;,&#34;4h&#34;,&#34;6h&#34;,&#34;12h&#34;,&#34;1d&#34; | [required] |[default to ]
**limit** | **i64** | Default 30,Max 500 | [required] |[default to 30]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetFuturesDataBasisRespItem>**](UmfuturesGetFuturesDataBasisRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_futures_data_delivery_price

> Vec<models::UmfuturesGetFuturesDataDeliveryPriceRespItem> umfutures_get_futures_data_delivery_price(pair)
Quarterly Contract Settlement Price

Latest price for a symbol or symbols.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pair** | **String** | e.g BTCUSDT | [required] |[default to ]

### Return type

[**Vec<models::UmfuturesGetFuturesDataDeliveryPriceRespItem>**](UmfuturesGetFuturesDataDeliveryPriceRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_futures_data_global_long_short_account_ratio

> Vec<models::UmfuturesGetFuturesDataGlobalLongShortAccountRatioRespItem> umfutures_get_futures_data_global_long_short_account_ratio(symbol, period, limit, start_time, end_time)
Long/Short Ratio

Query symbol Long/Short Ratio

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**period** | **String** | &#34;5m&#34;,&#34;15m&#34;,&#34;30m&#34;,&#34;1h&#34;,&#34;2h&#34;,&#34;4h&#34;,&#34;6h&#34;,&#34;12h&#34;,&#34;1d&#34; | [required] |[default to ]
**limit** | Option<**i64**> | default 30, max 500 |  |[default to 30]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetFuturesDataGlobalLongShortAccountRatioRespItem>**](UmfuturesGetFuturesDataGlobalLongShortAccountRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_futures_data_open_interest_hist

> Vec<models::UmfuturesGetFuturesDataOpenInterestHistRespItem> umfutures_get_futures_data_open_interest_hist(symbol, period, limit, start_time, end_time)
Open Interest Statistics

Open Interest Statistics

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**period** | **String** | &#34;5m&#34;,&#34;15m&#34;,&#34;30m&#34;,&#34;1h&#34;,&#34;2h&#34;,&#34;4h&#34;,&#34;6h&#34;,&#34;12h&#34;,&#34;1d&#34; | [required] |[default to ]
**limit** | Option<**i64**> | default 30, max 500 |  |[default to 30]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetFuturesDataOpenInterestHistRespItem>**](UmfuturesGetFuturesDataOpenInterestHistRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_futures_data_takerlongshort_ratio

> Vec<models::UmfuturesGetFuturesDataTakerlongshortRatioRespItem> umfutures_get_futures_data_takerlongshort_ratio(symbol, period, limit, start_time, end_time)
Taker Buy/Sell Volume

Taker Buy/Sell Volume

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**period** | **String** | &#34;5m&#34;,&#34;15m&#34;,&#34;30m&#34;,&#34;1h&#34;,&#34;2h&#34;,&#34;4h&#34;,&#34;6h&#34;,&#34;12h&#34;,&#34;1d&#34; | [required] |[default to ]
**limit** | Option<**i64**> | default 30, max 500 |  |[default to 30]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetFuturesDataTakerlongshortRatioRespItem>**](UmfuturesGetFuturesDataTakerlongshortRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_futures_data_top_long_short_account_ratio

> Vec<models::UmfuturesGetFuturesDataTopLongShortAccountRatioRespItem> umfutures_get_futures_data_top_long_short_account_ratio(symbol, period, limit, start_time, end_time)
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

[**Vec<models::UmfuturesGetFuturesDataTopLongShortAccountRatioRespItem>**](UmfuturesGetFuturesDataTopLongShortAccountRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_futures_data_top_long_short_position_ratio

> Vec<models::UmfuturesGetFuturesDataTopLongShortPositionRatioRespItem> umfutures_get_futures_data_top_long_short_position_ratio(symbol, period, limit, start_time, end_time)
Top Trader Long/Short Ratio (Positions)

The proportion of net long and net short positions to total open positions of the top 20% users with the highest margin balance. Long Position % = Long positions of top traders / Total open positions of top traders Short Position % = Short positions of top traders / Total open positions of top traders Long/Short Ratio (Positions) = Long Position % / Short Position %

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**period** | **String** | &#34;5m&#34;,&#34;15m&#34;,&#34;30m&#34;,&#34;1h&#34;,&#34;2h&#34;,&#34;4h&#34;,&#34;6h&#34;,&#34;12h&#34;,&#34;1d&#34; | [required] |[default to ]
**limit** | Option<**i64**> | default 30, max 500 |  |[default to 30]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetFuturesDataTopLongShortPositionRatioRespItem>**](UmfuturesGetFuturesDataTopLongShortPositionRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_historical_trades_v1

> Vec<models::UmfuturesGetHistoricalTradesV1RespItem> umfutures_get_historical_trades_v1(symbol, limit, from_id)
Old Trades Lookup (MARKET_DATA)

Get older market historical trades.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 100; max 500. |  |[default to 100]
**from_id** | Option<**i64**> | TradeId to fetch from. Default gets most recent trades. |  |

### Return type

[**Vec<models::UmfuturesGetHistoricalTradesV1RespItem>**](UmfuturesGetHistoricalTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_index_info_v1

> Vec<models::UmfuturesGetIndexInfoV1RespItem> umfutures_get_index_info_v1(symbol)
Composite Index Symbol Information

Query composite index symbol information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::UmfuturesGetIndexInfoV1RespItem>**](UmfuturesGetIndexInfoV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_index_price_klines_v1

> Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>> umfutures_get_index_price_klines_v1(pair, interval, start_time, end_time, limit)
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

[**Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_klines_v1

> Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>> umfutures_get_klines_v1(symbol, interval, start_time, end_time, limit)
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

[**Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_mark_price_klines_v1

> Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>> umfutures_get_mark_price_klines_v1(symbol, interval, start_time, end_time, limit)
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

[**Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_open_interest_v1

> models::UmfuturesGetOpenInterestV1Resp umfutures_get_open_interest_v1(symbol)
Open Interest

Get present open interest of a specific symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::UmfuturesGetOpenInterestV1Resp**](UmfuturesGetOpenInterestV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_ping_v1

> serde_json::Value umfutures_get_ping_v1()
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


## umfutures_get_premium_index_klines_v1

> Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>> umfutures_get_premium_index_klines_v1(symbol, interval, start_time, end_time, limit)
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

[**Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_premium_index_v1

> models::UmfuturesGetPremiumIndexV1Resp umfutures_get_premium_index_v1(symbol)
Mark Price

Mark Price and Funding Rate

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**models::UmfuturesGetPremiumIndexV1Resp**](UmfuturesGetPremiumIndexV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_ticker24hr_v1

> models::UmfuturesGetTicker24hrV1Resp umfutures_get_ticker24hr_v1(symbol)
24hr Ticker Price Change Statistics

24 hour rolling window price change statistics. Careful when accessing this with no symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**models::UmfuturesGetTicker24hrV1Resp**](UmfuturesGetTicker24hrV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_ticker_book_ticker_v1

> models::UmfuturesGetTickerBookTickerV1Resp umfutures_get_ticker_book_ticker_v1(symbol)
Symbol Order Book Ticker

Best price/qty on the order book for a symbol or symbols.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**models::UmfuturesGetTickerBookTickerV1Resp**](UmfuturesGetTickerBookTickerV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_ticker_price_v1

> models::UmfuturesGetTickerPriceV1Resp umfutures_get_ticker_price_v1(symbol)
Symbol Price Ticker

Latest price for a symbol or symbols.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**models::UmfuturesGetTickerPriceV1Resp**](UmfuturesGetTickerPriceV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_ticker_price_v2

> models::UmfuturesGetTickerPriceV2Resp umfutures_get_ticker_price_v2(symbol)
Symbol Price Ticker V2

Latest price for a symbol or symbols.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**models::UmfuturesGetTickerPriceV2Resp**](UmfuturesGetTickerPriceV2Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_time_v1

> models::UmfuturesGetTimeV1Resp umfutures_get_time_v1()
Check Server Time

Test connectivity to the Rest API and get the current server time.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::UmfuturesGetTimeV1Resp**](UmfuturesGetTimeV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_trades_v1

> Vec<models::UmfuturesGetTradesV1RespItem> umfutures_get_trades_v1(symbol, limit)
Recent Trades List

Get recent market trades

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]

### Return type

[**Vec<models::UmfuturesGetTradesV1RespItem>**](UmfuturesGetTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

