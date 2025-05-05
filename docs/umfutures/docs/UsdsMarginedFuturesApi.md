# \UsdsMarginedFuturesApi

All URIs are relative to *https://fapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_batch_orders_v1**](UsdsMarginedFuturesApi.md#create_batch_orders_v1) | **POST** /fapi/v1/batchOrders | Place Multiple Orders(TRADE)
[**create_convert_accept_quote_v1**](UsdsMarginedFuturesApi.md#create_convert_accept_quote_v1) | **POST** /fapi/v1/convert/acceptQuote | Accept the offered quote (USER_DATA)
[**create_convert_get_quote_v1**](UsdsMarginedFuturesApi.md#create_convert_get_quote_v1) | **POST** /fapi/v1/convert/getQuote | Send Quote Request(USER_DATA)
[**create_countdown_cancel_all_v1**](UsdsMarginedFuturesApi.md#create_countdown_cancel_all_v1) | **POST** /fapi/v1/countdownCancelAll | Auto-Cancel All Open Orders (TRADE)
[**create_fee_burn_v1**](UsdsMarginedFuturesApi.md#create_fee_burn_v1) | **POST** /fapi/v1/feeBurn | Toggle BNB Burn On Futures Trade (TRADE)
[**create_leverage_v1**](UsdsMarginedFuturesApi.md#create_leverage_v1) | **POST** /fapi/v1/leverage | Change Initial Leverage(TRADE)
[**create_listen_key_v1**](UsdsMarginedFuturesApi.md#create_listen_key_v1) | **POST** /fapi/v1/listenKey | Start User Data Stream (USER_STREAM)
[**create_margin_type_v1**](UsdsMarginedFuturesApi.md#create_margin_type_v1) | **POST** /fapi/v1/marginType | Change Margin Type(TRADE)
[**create_multi_assets_margin_v1**](UsdsMarginedFuturesApi.md#create_multi_assets_margin_v1) | **POST** /fapi/v1/multiAssetsMargin | Change Multi-Assets Mode (TRADE)
[**create_order_test_v1**](UsdsMarginedFuturesApi.md#create_order_test_v1) | **POST** /fapi/v1/order/test | Test Order(TRADE)
[**create_order_v1**](UsdsMarginedFuturesApi.md#create_order_v1) | **POST** /fapi/v1/order | New Order(TRADE)
[**create_position_margin_v1**](UsdsMarginedFuturesApi.md#create_position_margin_v1) | **POST** /fapi/v1/positionMargin | Modify Isolated Position Margin(TRADE)
[**create_position_side_dual_v1**](UsdsMarginedFuturesApi.md#create_position_side_dual_v1) | **POST** /fapi/v1/positionSide/dual | Change Position Mode(TRADE)
[**delete_all_open_orders_v1**](UsdsMarginedFuturesApi.md#delete_all_open_orders_v1) | **DELETE** /fapi/v1/allOpenOrders | Cancel All Open Orders (TRADE)
[**delete_batch_orders_v1**](UsdsMarginedFuturesApi.md#delete_batch_orders_v1) | **DELETE** /fapi/v1/batchOrders | Cancel Multiple Orders (TRADE)
[**delete_listen_key_v1**](UsdsMarginedFuturesApi.md#delete_listen_key_v1) | **DELETE** /fapi/v1/listenKey | Close User Data Stream (USER_STREAM)
[**delete_order_v1**](UsdsMarginedFuturesApi.md#delete_order_v1) | **DELETE** /fapi/v1/order | Cancel Order (TRADE)
[**get_account_config_v1**](UsdsMarginedFuturesApi.md#get_account_config_v1) | **GET** /fapi/v1/accountConfig | Futures Account Configuration(USER_DATA)
[**get_account_v2**](UsdsMarginedFuturesApi.md#get_account_v2) | **GET** /fapi/v2/account | Account Information V2(USER_DATA)
[**get_account_v3**](UsdsMarginedFuturesApi.md#get_account_v3) | **GET** /fapi/v3/account | Account Information V3(USER_DATA)
[**get_adl_quantile_v1**](UsdsMarginedFuturesApi.md#get_adl_quantile_v1) | **GET** /fapi/v1/adlQuantile | Position ADL Quantile Estimation(USER_DATA)
[**get_agg_trades_v1**](UsdsMarginedFuturesApi.md#get_agg_trades_v1) | **GET** /fapi/v1/aggTrades | Compressed/Aggregate Trades List
[**get_all_orders_v1**](UsdsMarginedFuturesApi.md#get_all_orders_v1) | **GET** /fapi/v1/allOrders | All Orders (USER_DATA)
[**get_api_trading_status_v1**](UsdsMarginedFuturesApi.md#get_api_trading_status_v1) | **GET** /fapi/v1/apiTradingStatus | Futures Trading Quantitative Rules Indicators (USER_DATA)
[**get_asset_index_v1**](UsdsMarginedFuturesApi.md#get_asset_index_v1) | **GET** /fapi/v1/assetIndex | Multi-Assets Mode Asset Index
[**get_balance_v2**](UsdsMarginedFuturesApi.md#get_balance_v2) | **GET** /fapi/v2/balance | Futures Account Balance V2 (USER_DATA)
[**get_balance_v3**](UsdsMarginedFuturesApi.md#get_balance_v3) | **GET** /fapi/v3/balance | Futures Account Balance V3 (USER_DATA)
[**get_commission_rate_v1**](UsdsMarginedFuturesApi.md#get_commission_rate_v1) | **GET** /fapi/v1/commissionRate | User Commission Rate (USER_DATA)
[**get_constituents_v1**](UsdsMarginedFuturesApi.md#get_constituents_v1) | **GET** /fapi/v1/constituents | Query Index Price Constituents
[**get_continuous_klines_v1**](UsdsMarginedFuturesApi.md#get_continuous_klines_v1) | **GET** /fapi/v1/continuousKlines | Continuous Contract Kline/Candlestick Data
[**get_convert_exchange_info_v1**](UsdsMarginedFuturesApi.md#get_convert_exchange_info_v1) | **GET** /fapi/v1/convert/exchangeInfo | List All Convert Pairs
[**get_convert_order_status_v1**](UsdsMarginedFuturesApi.md#get_convert_order_status_v1) | **GET** /fapi/v1/convert/orderStatus | Order status(USER_DATA)
[**get_depth_v1**](UsdsMarginedFuturesApi.md#get_depth_v1) | **GET** /fapi/v1/depth | Order Book
[**get_exchange_info_v1**](UsdsMarginedFuturesApi.md#get_exchange_info_v1) | **GET** /fapi/v1/exchangeInfo | Exchange Information
[**get_fee_burn_v1**](UsdsMarginedFuturesApi.md#get_fee_burn_v1) | **GET** /fapi/v1/feeBurn | Get BNB Burn Status (USER_DATA)
[**get_force_orders_v1**](UsdsMarginedFuturesApi.md#get_force_orders_v1) | **GET** /fapi/v1/forceOrders | User's Force Orders (USER_DATA)
[**get_funding_info_v1**](UsdsMarginedFuturesApi.md#get_funding_info_v1) | **GET** /fapi/v1/fundingInfo | Get Funding Rate Info
[**get_funding_rate_v1**](UsdsMarginedFuturesApi.md#get_funding_rate_v1) | **GET** /fapi/v1/fundingRate | Get Funding Rate History
[**get_futures_data_basis**](UsdsMarginedFuturesApi.md#get_futures_data_basis) | **GET** /futures/data/basis | Basis
[**get_futures_data_delivery_price**](UsdsMarginedFuturesApi.md#get_futures_data_delivery_price) | **GET** /futures/data/delivery-price | Quarterly Contract Settlement Price
[**get_futures_data_global_long_short_account_ratio**](UsdsMarginedFuturesApi.md#get_futures_data_global_long_short_account_ratio) | **GET** /futures/data/globalLongShortAccountRatio | Long/Short Ratio
[**get_futures_data_open_interest_hist**](UsdsMarginedFuturesApi.md#get_futures_data_open_interest_hist) | **GET** /futures/data/openInterestHist | Open Interest Statistics
[**get_futures_data_takerlongshort_ratio**](UsdsMarginedFuturesApi.md#get_futures_data_takerlongshort_ratio) | **GET** /futures/data/takerlongshortRatio | Taker Buy/Sell Volume
[**get_futures_data_top_long_short_account_ratio**](UsdsMarginedFuturesApi.md#get_futures_data_top_long_short_account_ratio) | **GET** /futures/data/topLongShortAccountRatio | Top Trader Long/Short Ratio (Accounts)
[**get_futures_data_top_long_short_position_ratio**](UsdsMarginedFuturesApi.md#get_futures_data_top_long_short_position_ratio) | **GET** /futures/data/topLongShortPositionRatio | Top Trader Long/Short Ratio (Positions)
[**get_historical_trades_v1**](UsdsMarginedFuturesApi.md#get_historical_trades_v1) | **GET** /fapi/v1/historicalTrades | Old Trades Lookup (MARKET_DATA)
[**get_income_asyn_id_v1**](UsdsMarginedFuturesApi.md#get_income_asyn_id_v1) | **GET** /fapi/v1/income/asyn/id | Get Futures Transaction History Download Link by Id (USER_DATA)
[**get_income_asyn_v1**](UsdsMarginedFuturesApi.md#get_income_asyn_v1) | **GET** /fapi/v1/income/asyn | Get Download Id For Futures Transaction History(USER_DATA)
[**get_index_info_v1**](UsdsMarginedFuturesApi.md#get_index_info_v1) | **GET** /fapi/v1/indexInfo | Composite Index Symbol Information
[**get_index_price_klines_v1**](UsdsMarginedFuturesApi.md#get_index_price_klines_v1) | **GET** /fapi/v1/indexPriceKlines | Index Price Kline/Candlestick Data
[**get_klines_v1**](UsdsMarginedFuturesApi.md#get_klines_v1) | **GET** /fapi/v1/klines | Kline/Candlestick Data
[**get_leverage_bracket_v1**](UsdsMarginedFuturesApi.md#get_leverage_bracket_v1) | **GET** /fapi/v1/leverageBracket | Notional and Leverage Brackets (USER_DATA)
[**get_mark_price_klines_v1**](UsdsMarginedFuturesApi.md#get_mark_price_klines_v1) | **GET** /fapi/v1/markPriceKlines | Mark Price Kline/Candlestick Data
[**get_multi_assets_margin_v1**](UsdsMarginedFuturesApi.md#get_multi_assets_margin_v1) | **GET** /fapi/v1/multiAssetsMargin | Get Current Multi-Assets Mode (USER_DATA)
[**get_open_interest_v1**](UsdsMarginedFuturesApi.md#get_open_interest_v1) | **GET** /fapi/v1/openInterest | Open Interest
[**get_open_order_v1**](UsdsMarginedFuturesApi.md#get_open_order_v1) | **GET** /fapi/v1/openOrder | Query Current Open Order (USER_DATA)
[**get_open_orders_v1**](UsdsMarginedFuturesApi.md#get_open_orders_v1) | **GET** /fapi/v1/openOrders | Current All Open Orders (USER_DATA)
[**get_order_amendment_v1**](UsdsMarginedFuturesApi.md#get_order_amendment_v1) | **GET** /fapi/v1/orderAmendment | Get Order Modify History (USER_DATA)
[**get_order_asyn_id_v1**](UsdsMarginedFuturesApi.md#get_order_asyn_id_v1) | **GET** /fapi/v1/order/asyn/id | Get Futures Order History Download Link by Id (USER_DATA)
[**get_order_asyn_v1**](UsdsMarginedFuturesApi.md#get_order_asyn_v1) | **GET** /fapi/v1/order/asyn | Get Download Id For Futures Order History (USER_DATA)
[**get_order_v1**](UsdsMarginedFuturesApi.md#get_order_v1) | **GET** /fapi/v1/order | Query Order (USER_DATA)
[**get_ping_v1**](UsdsMarginedFuturesApi.md#get_ping_v1) | **GET** /fapi/v1/ping | Test Connectivity
[**get_pm_account_info_v1**](UsdsMarginedFuturesApi.md#get_pm_account_info_v1) | **GET** /fapi/v1/pmAccountInfo | Classic Portfolio Margin Account Information (USER_DATA)
[**get_position_margin_history_v1**](UsdsMarginedFuturesApi.md#get_position_margin_history_v1) | **GET** /fapi/v1/positionMargin/history | Get Position Margin Change History (TRADE)
[**get_position_risk_v2**](UsdsMarginedFuturesApi.md#get_position_risk_v2) | **GET** /fapi/v2/positionRisk | Position Information V2 (USER_DATA)
[**get_position_risk_v3**](UsdsMarginedFuturesApi.md#get_position_risk_v3) | **GET** /fapi/v3/positionRisk | Position Information V3 (USER_DATA)
[**get_position_side_dual_v1**](UsdsMarginedFuturesApi.md#get_position_side_dual_v1) | **GET** /fapi/v1/positionSide/dual | Get Current Position Mode(USER_DATA)
[**get_premium_index_klines_v1**](UsdsMarginedFuturesApi.md#get_premium_index_klines_v1) | **GET** /fapi/v1/premiumIndexKlines | Premium index Kline Data
[**get_premium_index_v1**](UsdsMarginedFuturesApi.md#get_premium_index_v1) | **GET** /fapi/v1/premiumIndex | Mark Price
[**get_rate_limit_order_v1**](UsdsMarginedFuturesApi.md#get_rate_limit_order_v1) | **GET** /fapi/v1/rateLimit/order | Query User Rate Limit (USER_DATA)
[**get_symbol_config_v1**](UsdsMarginedFuturesApi.md#get_symbol_config_v1) | **GET** /fapi/v1/symbolConfig | Symbol Configuration(USER_DATA)
[**get_ticker24hr_v1**](UsdsMarginedFuturesApi.md#get_ticker24hr_v1) | **GET** /fapi/v1/ticker/24hr | 24hr Ticker Price Change Statistics
[**get_ticker_book_ticker_v1**](UsdsMarginedFuturesApi.md#get_ticker_book_ticker_v1) | **GET** /fapi/v1/ticker/bookTicker | Symbol Order Book Ticker
[**get_ticker_price_v1**](UsdsMarginedFuturesApi.md#get_ticker_price_v1) | **GET** /fapi/v1/ticker/price | Symbol Price Ticker
[**get_ticker_price_v2**](UsdsMarginedFuturesApi.md#get_ticker_price_v2) | **GET** /fapi/v2/ticker/price | Symbol Price Ticker V2
[**get_time_v1**](UsdsMarginedFuturesApi.md#get_time_v1) | **GET** /fapi/v1/time | Check Server Time
[**get_trade_asyn_id_v1**](UsdsMarginedFuturesApi.md#get_trade_asyn_id_v1) | **GET** /fapi/v1/trade/asyn/id | Get Futures Trade Download Link by Id(USER_DATA)
[**get_trade_asyn_v1**](UsdsMarginedFuturesApi.md#get_trade_asyn_v1) | **GET** /fapi/v1/trade/asyn | Get Download Id For Futures Trade History (USER_DATA)
[**get_trades_v1**](UsdsMarginedFuturesApi.md#get_trades_v1) | **GET** /fapi/v1/trades | Recent Trades List
[**get_user_trades_v1**](UsdsMarginedFuturesApi.md#get_user_trades_v1) | **GET** /fapi/v1/userTrades | Account Trade List (USER_DATA)
[**update_batch_orders_v1**](UsdsMarginedFuturesApi.md#update_batch_orders_v1) | **PUT** /fapi/v1/batchOrders | Modify Multiple Orders(TRADE)
[**update_listen_key_v1**](UsdsMarginedFuturesApi.md#update_listen_key_v1) | **PUT** /fapi/v1/listenKey | Keepalive User Data Stream (USER_STREAM)
[**update_order_v1**](UsdsMarginedFuturesApi.md#update_order_v1) | **PUT** /fapi/v1/order | Modify Order (TRADE)



## create_batch_orders_v1

> Vec<models::UmfuturesCreateBatchOrdersV1RespInner> create_batch_orders_v1(batch_orders, timestamp, recv_window)
Place Multiple Orders(TRADE)

Place Multiple Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**batch_orders** | [**Vec<models::UmfuturesCreateBatchOrdersV1ReqBatchOrdersItem>**](models::UmfuturesCreateBatchOrdersV1ReqBatchOrdersItem.md) |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesCreateBatchOrdersV1RespInner>**](UmfuturesCreateBatchOrdersV1Resp_inner.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_convert_accept_quote_v1

> models::CreateConvertAcceptQuoteV1Resp create_convert_accept_quote_v1(quote_id, timestamp, recv_window)
Accept the offered quote (USER_DATA)

Accept the offered quote by quote ID.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**quote_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateConvertAcceptQuoteV1Resp**](CreateConvertAcceptQuoteV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_convert_get_quote_v1

> models::CreateConvertGetQuoteV1Resp create_convert_get_quote_v1(from_asset, timestamp, to_asset, from_amount, recv_window, to_amount, valid_time)
Send Quote Request(USER_DATA)

Request a quote for the requested token pairs

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**from_asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**to_asset** | **String** |  | [required] |[default to ]
**from_amount** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**to_amount** | Option<**String**> |  |  |[default to ]
**valid_time** | Option<**String**> |  |  |[default to 10]

### Return type

[**models::CreateConvertGetQuoteV1Resp**](CreateConvertGetQuoteV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_countdown_cancel_all_v1

> models::UmfuturesCreateCountdownCancelAllV1Resp create_countdown_cancel_all_v1(umfutures_create_countdown_cancel_all_v1_req)
Auto-Cancel All Open Orders (TRADE)

Cancel all open orders of the specified symbol at the end of the specified countdown. The endpoint should be called repeatedly as heartbeats so that the existing countdown time can be canceled and replaced by a new one.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**umfutures_create_countdown_cancel_all_v1_req** | Option<[**UmfuturesCreateCountdownCancelAllV1Req**](UmfuturesCreateCountdownCancelAllV1Req.md)> |  |  |

### Return type

[**models::UmfuturesCreateCountdownCancelAllV1Resp**](UmfuturesCreateCountdownCancelAllV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_fee_burn_v1

> models::CreateFeeBurnV1Resp create_fee_burn_v1(fee_burn, timestamp, recv_window)
Toggle BNB Burn On Futures Trade (TRADE)

Change user's BNB Fee Discount (Fee Discount On or Fee Discount Off ) on EVERY symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**fee_burn** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateFeeBurnV1Resp**](CreateFeeBurnV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_leverage_v1

> models::CreateLeverageV1Resp create_leverage_v1(leverage, symbol, timestamp, recv_window)
Change Initial Leverage(TRADE)

Change user's initial leverage of specific symbol market.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**leverage** | **i32** |  | [required] |
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateLeverageV1Resp**](CreateLeverageV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_listen_key_v1

> models::CreateListenKeyV1Resp create_listen_key_v1()
Start User Data Stream (USER_STREAM)

Start a new user data stream. The stream will close after 60 minutes unless a keepalive is sent. If the account has an active listenKey, that listenKey will be returned and its validity will be extended for 60 minutes.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::CreateListenKeyV1Resp**](CreateListenKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_type_v1

> models::CreateMarginTypeV1Resp create_margin_type_v1(margin_type, symbol, timestamp, recv_window)
Change Margin Type(TRADE)

Change symbol level margin type

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**margin_type** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateMarginTypeV1Resp**](CreateMarginTypeV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_multi_assets_margin_v1

> models::CreateMultiAssetsMarginV1Resp create_multi_assets_margin_v1(multi_assets_margin, timestamp, recv_window)
Change Multi-Assets Mode (TRADE)

Change user's Multi-Assets mode (Multi-Assets Mode or Single-Asset Mode) on Every symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**multi_assets_margin** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateMultiAssetsMarginV1Resp**](CreateMultiAssetsMarginV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_order_test_v1

> models::CreateOrderTestV1Resp create_order_test_v1(side, symbol, timestamp, r#type, activation_price, callback_rate, close_position, good_till_date, new_client_order_id, new_order_resp_type, position_side, price, price_match, price_protect, quantity, recv_window, reduce_only, self_trade_prevention_mode, stop_price, time_in_force, working_type)
Test Order(TRADE)

Testing order request, this order will not be submitted to matching engine

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**activation_price** | Option<**String**> |  |  |[default to ]
**callback_rate** | Option<**String**> |  |  |[default to ]
**close_position** | Option<**String**> |  |  |[default to ]
**good_till_date** | Option<**i64**> |  |  |
**new_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**position_side** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**price_match** | Option<**String**> |  |  |[default to ]
**price_protect** | Option<**String**> |  |  |[default to ]
**quantity** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**reduce_only** | Option<**String**> |  |  |[default to ]
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**stop_price** | Option<**String**> |  |  |[default to ]
**time_in_force** | Option<**String**> |  |  |[default to ]
**working_type** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateOrderTestV1Resp**](CreateOrderTestV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_order_v1

> models::CreateOrderV1Resp create_order_v1(side, symbol, timestamp, r#type, activation_price, callback_rate, close_position, good_till_date, new_client_order_id, new_order_resp_type, position_side, price, price_match, price_protect, quantity, recv_window, reduce_only, self_trade_prevention_mode, stop_price, time_in_force, working_type)
New Order(TRADE)

Send in a new order.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**activation_price** | Option<**String**> |  |  |[default to ]
**callback_rate** | Option<**String**> |  |  |[default to ]
**close_position** | Option<**String**> |  |  |[default to ]
**good_till_date** | Option<**i64**> |  |  |
**new_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**position_side** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**price_match** | Option<**String**> |  |  |[default to ]
**price_protect** | Option<**String**> |  |  |[default to ]
**quantity** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**reduce_only** | Option<**String**> |  |  |[default to ]
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**stop_price** | Option<**String**> |  |  |[default to ]
**time_in_force** | Option<**String**> |  |  |[default to ]
**working_type** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateOrderV1Resp**](CreateOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_position_margin_v1

> models::CreatePositionMarginV1Resp create_position_margin_v1(amount, symbol, timestamp, r#type, position_side, recv_window)
Modify Isolated Position Margin(TRADE)

Modify Isolated Position Margin

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **i32** |  | [required] |
**position_side** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreatePositionMarginV1Resp**](CreatePositionMarginV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_position_side_dual_v1

> models::CreatePositionSideDualV1Resp create_position_side_dual_v1(dual_side_position, timestamp, recv_window)
Change Position Mode(TRADE)

Change user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**dual_side_position** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreatePositionSideDualV1Resp**](CreatePositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_all_open_orders_v1

> models::DeleteAllOpenOrdersV1Resp delete_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel All Open Orders (TRADE)

Cancel All Open Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::DeleteAllOpenOrdersV1Resp**](DeleteAllOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_batch_orders_v1

> Vec<models::UmfuturesDeleteBatchOrdersV1RespInner> delete_batch_orders_v1(symbol, timestamp, order_id_list, orig_client_order_id_list, recv_window)
Cancel Multiple Orders (TRADE)

Cancel Multiple Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id_list** | Option<[**Vec<i64>**](i64.md)> | max length 10 <br/> e.g. [1234567,2345678] |  |
**orig_client_order_id_list** | Option<[**Vec<String>**](String.md)> | max length 10<br/> e.g. [&#34;my_id_1&#34;,&#34;my_id_2&#34;], encode the double quotes. No space after comma. |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesDeleteBatchOrdersV1RespInner>**](UmfuturesDeleteBatchOrdersV1Resp_inner.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_listen_key_v1

> serde_json::Value delete_listen_key_v1()
Close User Data Stream (USER_STREAM)

Close out a user data stream.

### Parameters

This endpoint does not need any parameter.

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_order_v1

> models::DeleteOrderV1Resp delete_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
Cancel Order (TRADE)

Cancel an active order.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::DeleteOrderV1Resp**](DeleteOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_account_config_v1

> models::GetAccountConfigV1Resp get_account_config_v1(timestamp, recv_window)
Futures Account Configuration(USER_DATA)

Query account configuration

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAccountConfigV1Resp**](GetAccountConfigV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_account_v2

> models::GetAccountV2Resp get_account_v2(timestamp, recv_window)
Account Information V2(USER_DATA)

Get current account information. User in single-asset/ multi-assets mode will see different value, see comments in response section for detail.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAccountV2Resp**](GetAccountV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_account_v3

> models::GetAccountV3Resp get_account_v3(timestamp, recv_window)
Account Information V3(USER_DATA)

Get current account information. User in single-asset/ multi-assets mode will see different value, see comments in response section for detail.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAccountV3Resp**](GetAccountV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_adl_quantile_v1

> Vec<models::GetAdlQuantileV1RespItem> get_adl_quantile_v1(timestamp, symbol, recv_window)
Position ADL Quantile Estimation(USER_DATA)

Position ADL Quantile Estimation

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetAdlQuantileV1RespItem>**](GetAdlQuantileV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_agg_trades_v1

> Vec<models::UmfuturesGetAggTradesV1RespItem> get_agg_trades_v1(symbol, from_id, start_time, end_time, limit)
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


## get_all_orders_v1

> Vec<models::GetAllOrdersV1RespItem> get_all_orders_v1(symbol, timestamp, order_id, start_time, end_time, limit, recv_window)
All Orders (USER_DATA)

Get all account orders; active, canceled, or filled.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetAllOrdersV1RespItem>**](GetAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_trading_status_v1

> models::UmfuturesGetApiTradingStatusV1Resp get_api_trading_status_v1(timestamp, symbol, recv_window)
Futures Trading Quantitative Rules Indicators (USER_DATA)

Futures trading quantitative rules indicators, for more information on this, please refer to the Futures Trading Quantitative Rules

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetApiTradingStatusV1Resp**](UmfuturesGetApiTradingStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_asset_index_v1

> models::UmfuturesGetAssetIndexV1Resp get_asset_index_v1(symbol)
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


## get_balance_v2

> Vec<models::GetBalanceV2RespItem> get_balance_v2(timestamp, recv_window)
Futures Account Balance V2 (USER_DATA)

Query account balance info

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBalanceV2RespItem>**](GetBalanceV2RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_balance_v3

> Vec<models::GetBalanceV3RespItem> get_balance_v3(timestamp, recv_window)
Futures Account Balance V3 (USER_DATA)

Query account balance info

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBalanceV3RespItem>**](GetBalanceV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_commission_rate_v1

> models::GetCommissionRateV1Resp get_commission_rate_v1(symbol, timestamp, recv_window)
User Commission Rate (USER_DATA)

Get User Commission Rate

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetCommissionRateV1Resp**](GetCommissionRateV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_constituents_v1

> models::GetConstituentsV1Resp get_constituents_v1(symbol)
Query Index Price Constituents

Query index price constituents

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::GetConstituentsV1Resp**](GetConstituentsV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_continuous_klines_v1

> Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>> get_continuous_klines_v1(pair, contract_type, interval, start_time, end_time, limit)
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


## get_convert_exchange_info_v1

> Vec<models::GetConvertExchangeInfoV1RespItem> get_convert_exchange_info_v1(from_asset, to_asset)
List All Convert Pairs

Query for all convertible token pairs and the tokens’ respective upper/lower limits

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**from_asset** | Option<**String**> | User spends coin |  |[default to ]
**to_asset** | Option<**String**> | User receives coin |  |[default to ]

### Return type

[**Vec<models::GetConvertExchangeInfoV1RespItem>**](GetConvertExchangeInfoV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_convert_order_status_v1

> models::GetConvertOrderStatusV1Resp get_convert_order_status_v1(order_id, quote_id)
Order status(USER_DATA)

Query order status by order ID.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**order_id** | Option<**String**> | Either orderId or quoteId is required |  |[default to ]
**quote_id** | Option<**String**> | Either orderId or quoteId is required |  |[default to ]

### Return type

[**models::GetConvertOrderStatusV1Resp**](GetConvertOrderStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_depth_v1

> models::GetDepthV1Resp get_depth_v1(symbol, limit)
Order Book

Query symbol orderbook

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 500; Valid limits:[5, 10, 20, 50, 100, 500, 1000] |  |[default to 500]

### Return type

[**models::GetDepthV1Resp**](GetDepthV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_exchange_info_v1

> models::UmfuturesGetExchangeInfoV1Resp get_exchange_info_v1()
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


## get_fee_burn_v1

> models::GetFeeBurnV1Resp get_fee_burn_v1(timestamp, recv_window)
Get BNB Burn Status (USER_DATA)

Get user's BNB Fee Discount (Fee Discount On or Fee Discount Off )

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetFeeBurnV1Resp**](GetFeeBurnV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_force_orders_v1

> Vec<models::GetForceOrdersV1RespItem> get_force_orders_v1(timestamp, symbol, auto_close_type, start_time, end_time, limit, recv_window)
User's Force Orders (USER_DATA)

Query user's Force Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**auto_close_type** | Option<**String**> | &#34;LIQUIDATION&#34; for liquidation orders, &#34;ADL&#34; for ADL orders. |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 50; max 100. |  |[default to 50]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetForceOrdersV1RespItem>**](GetForceOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_funding_info_v1

> Vec<models::GetFundingInfoV1RespItem> get_funding_info_v1()
Get Funding Rate Info

Query funding rate info for symbols that had FundingRateCap/ FundingRateFloor / fundingIntervalHours adjustment

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::GetFundingInfoV1RespItem>**](GetFundingInfoV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_funding_rate_v1

> Vec<models::GetFundingRateV1RespItem> get_funding_rate_v1(symbol, start_time, end_time, limit)
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

[**Vec<models::GetFundingRateV1RespItem>**](GetFundingRateV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_futures_data_basis

> Vec<models::GetFuturesDataBasisRespItem> get_futures_data_basis(pair, contract_type, period, limit, start_time, end_time)
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

[**Vec<models::GetFuturesDataBasisRespItem>**](GetFuturesDataBasisRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_futures_data_delivery_price

> Vec<models::UmfuturesGetFuturesDataDeliveryPriceRespItem> get_futures_data_delivery_price(pair)
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


## get_futures_data_global_long_short_account_ratio

> Vec<models::GetFuturesDataGlobalLongShortAccountRatioRespItem> get_futures_data_global_long_short_account_ratio(symbol, period, limit, start_time, end_time)
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

[**Vec<models::GetFuturesDataGlobalLongShortAccountRatioRespItem>**](GetFuturesDataGlobalLongShortAccountRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_futures_data_open_interest_hist

> Vec<models::GetFuturesDataOpenInterestHistRespItem> get_futures_data_open_interest_hist(symbol, period, limit, start_time, end_time)
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

[**Vec<models::GetFuturesDataOpenInterestHistRespItem>**](GetFuturesDataOpenInterestHistRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_futures_data_takerlongshort_ratio

> Vec<models::GetFuturesDataTakerlongshortRatioRespItem> get_futures_data_takerlongshort_ratio(symbol, period, limit, start_time, end_time)
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

[**Vec<models::GetFuturesDataTakerlongshortRatioRespItem>**](GetFuturesDataTakerlongshortRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_futures_data_top_long_short_account_ratio

> Vec<models::GetFuturesDataTopLongShortAccountRatioRespItem> get_futures_data_top_long_short_account_ratio(symbol, period, limit, start_time, end_time)
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

[**Vec<models::GetFuturesDataTopLongShortAccountRatioRespItem>**](GetFuturesDataTopLongShortAccountRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_futures_data_top_long_short_position_ratio

> Vec<models::GetFuturesDataTopLongShortPositionRatioRespItem> get_futures_data_top_long_short_position_ratio(symbol, period, limit, start_time, end_time)
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

[**Vec<models::GetFuturesDataTopLongShortPositionRatioRespItem>**](GetFuturesDataTopLongShortPositionRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_historical_trades_v1

> Vec<models::GetHistoricalTradesV1RespItem> get_historical_trades_v1(symbol, limit, from_id)
Old Trades Lookup (MARKET_DATA)

Get older market historical trades.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 100; max 500. |  |[default to 100]
**from_id** | Option<**i64**> | TradeId to fetch from. Default gets most recent trades. |  |

### Return type

[**Vec<models::GetHistoricalTradesV1RespItem>**](GetHistoricalTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_income_asyn_id_v1

> models::GetIncomeAsynIdV1Resp get_income_asyn_id_v1(download_id, timestamp, recv_window)
Get Futures Transaction History Download Link by Id (USER_DATA)

Get futures transaction history download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetIncomeAsynIdV1Resp**](GetIncomeAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_income_asyn_v1

> models::GetIncomeAsynV1Resp get_income_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For Futures Transaction History(USER_DATA)

Get download id for futures transaction history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetIncomeAsynV1Resp**](GetIncomeAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_index_info_v1

> Vec<models::GetIndexInfoV1RespItem> get_index_info_v1(symbol)
Composite Index Symbol Information

Query composite index symbol information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::GetIndexInfoV1RespItem>**](GetIndexInfoV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_index_price_klines_v1

> Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>> get_index_price_klines_v1(pair, interval, start_time, end_time, limit)
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


## get_klines_v1

> Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>> get_klines_v1(symbol, interval, start_time, end_time, limit)
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


## get_leverage_bracket_v1

> models::UmfuturesGetLeverageBracketV1Resp get_leverage_bracket_v1(timestamp, symbol, recv_window)
Notional and Leverage Brackets (USER_DATA)

Query user notional and leverage bracket on speicfic symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetLeverageBracketV1Resp**](UmfuturesGetLeverageBracketV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mark_price_klines_v1

> Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>> get_mark_price_klines_v1(symbol, interval, start_time, end_time, limit)
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


## get_multi_assets_margin_v1

> models::GetMultiAssetsMarginV1Resp get_multi_assets_margin_v1(timestamp, recv_window)
Get Current Multi-Assets Mode (USER_DATA)

Get user's Multi-Assets mode (Multi-Assets Mode or Single-Asset Mode) on Every symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMultiAssetsMarginV1Resp**](GetMultiAssetsMarginV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_open_interest_v1

> models::GetOpenInterestV1Resp get_open_interest_v1(symbol)
Open Interest

Get present open interest of a specific symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::GetOpenInterestV1Resp**](GetOpenInterestV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_open_order_v1

> models::GetOpenOrderV1Resp get_open_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
Query Current Open Order (USER_DATA)

Query open order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetOpenOrderV1Resp**](GetOpenOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_open_orders_v1

> Vec<models::GetOpenOrdersV1RespItem> get_open_orders_v1(timestamp, symbol, recv_window)
Current All Open Orders (USER_DATA)

Get all open orders on a symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetOpenOrdersV1RespItem>**](GetOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_order_amendment_v1

> Vec<models::GetOrderAmendmentV1RespItem> get_order_amendment_v1(symbol, timestamp, order_id, orig_client_order_id, start_time, end_time, limit, recv_window)
Get Order Modify History (USER_DATA)

Get order modification history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get modification history from INCLUSIVE |  |
**end_time** | Option<**i64**> | Timestamp in ms to get modification history until INCLUSIVE |  |
**limit** | Option<**i32**> | Default 50; max 100 |  |[default to 50]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetOrderAmendmentV1RespItem>**](GetOrderAmendmentV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_order_asyn_id_v1

> models::GetOrderAsynIdV1Resp get_order_asyn_id_v1(download_id, timestamp, recv_window)
Get Futures Order History Download Link by Id (USER_DATA)

Get futures order history download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetOrderAsynIdV1Resp**](GetOrderAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_order_asyn_v1

> models::UmfuturesGetOrderAsynV1Resp get_order_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For Futures Order History (USER_DATA)

Get Download Id For Futures Order History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetOrderAsynV1Resp**](UmfuturesGetOrderAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_order_v1

> models::GetOrderV1Resp get_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
Query Order (USER_DATA)

Check an order's status.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetOrderV1Resp**](GetOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_ping_v1

> serde_json::Value get_ping_v1()
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


## get_pm_account_info_v1

> models::GetPmAccountInfoV1Resp get_pm_account_info_v1(asset, timestamp, recv_window)
Classic Portfolio Margin Account Information (USER_DATA)

Get Classic Portfolio Margin current account information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetPmAccountInfoV1Resp**](GetPmAccountInfoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_position_margin_history_v1

> Vec<models::GetPositionMarginHistoryV1RespItem> get_position_margin_history_v1(symbol, timestamp, r#type, start_time, end_time, limit, recv_window)
Get Position Margin Change History (TRADE)

Get Position Margin Change History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | Option<**i32**> | 1: Add position margin，2: Reduce position margin |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> | Default current time if not pass |  |
**limit** | Option<**i32**> | Default: 500 |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetPositionMarginHistoryV1RespItem>**](GetPositionMarginHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_position_risk_v2

> Vec<models::GetPositionRiskV2RespItem> get_position_risk_v2(timestamp, symbol, recv_window)
Position Information V2 (USER_DATA)

Get current position information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetPositionRiskV2RespItem>**](GetPositionRiskV2RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_position_risk_v3

> Vec<models::GetPositionRiskV3RespItem> get_position_risk_v3(timestamp, symbol, recv_window)
Position Information V3 (USER_DATA)

Get current position information(only symbol that has position or open orders will be returned).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetPositionRiskV3RespItem>**](GetPositionRiskV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_position_side_dual_v1

> models::GetPositionSideDualV1Resp get_position_side_dual_v1(timestamp, recv_window)
Get Current Position Mode(USER_DATA)

Get user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetPositionSideDualV1Resp**](GetPositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_premium_index_klines_v1

> Vec<Vec<models::UmfuturesGetContinuousKlinesV1RespInnerInner>> get_premium_index_klines_v1(symbol, interval, start_time, end_time, limit)
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


## get_premium_index_v1

> models::UmfuturesGetPremiumIndexV1Resp get_premium_index_v1(symbol)
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


## get_rate_limit_order_v1

> Vec<models::GetRateLimitOrderV1RespItem> get_rate_limit_order_v1(timestamp, recv_window)
Query User Rate Limit (USER_DATA)

Query User Rate Limit

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetRateLimitOrderV1RespItem>**](GetRateLimitOrderV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_symbol_config_v1

> Vec<models::GetSymbolConfigV1RespItem> get_symbol_config_v1(timestamp, symbol, recv_window)
Symbol Configuration(USER_DATA)

Get current account symbol configuration.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetSymbolConfigV1RespItem>**](GetSymbolConfigV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_ticker24hr_v1

> models::UmfuturesGetTicker24hrV1Resp get_ticker24hr_v1(symbol)
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


## get_ticker_book_ticker_v1

> models::UmfuturesGetTickerBookTickerV1Resp get_ticker_book_ticker_v1(symbol)
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


## get_ticker_price_v1

> models::UmfuturesGetTickerPriceV1Resp get_ticker_price_v1(symbol)
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


## get_ticker_price_v2

> models::UmfuturesGetTickerPriceV2Resp get_ticker_price_v2(symbol)
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


## get_time_v1

> models::GetTimeV1Resp get_time_v1()
Check Server Time

Test connectivity to the Rest API and get the current server time.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::GetTimeV1Resp**](GetTimeV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_trade_asyn_id_v1

> models::GetTradeAsynIdV1Resp get_trade_asyn_id_v1(download_id, timestamp, recv_window)
Get Futures Trade Download Link by Id(USER_DATA)

Get futures trade download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetTradeAsynIdV1Resp**](GetTradeAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_trade_asyn_v1

> models::GetTradeAsynV1Resp get_trade_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For Futures Trade History (USER_DATA)

Get download id for futures trade history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetTradeAsynV1Resp**](GetTradeAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_trades_v1

> Vec<models::GetTradesV1RespItem> get_trades_v1(symbol, limit)
Recent Trades List

Get recent market trades

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]

### Return type

[**Vec<models::GetTradesV1RespItem>**](GetTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_user_trades_v1

> Vec<models::GetUserTradesV1RespItem> get_user_trades_v1(symbol, timestamp, order_id, start_time, end_time, from_id, limit, recv_window)
Account Trade List (USER_DATA)

Get trades for a specific account and symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> | This can only be used in combination with `symbol` |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**from_id** | Option<**i64**> | Trade id to fetch from. Default gets most recent trades. |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetUserTradesV1RespItem>**](GetUserTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_batch_orders_v1

> Vec<models::UmfuturesUpdateBatchOrdersV1RespItem> update_batch_orders_v1(batch_orders, timestamp, recv_window)
Modify Multiple Orders(TRADE)

Modify Multiple Orders (TRADE)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**batch_orders** | [**Vec<models::UmfuturesUpdateBatchOrdersV1ReqBatchOrdersItem>**](models::UmfuturesUpdateBatchOrdersV1ReqBatchOrdersItem.md) |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesUpdateBatchOrdersV1RespItem>**](UmfuturesUpdateBatchOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_listen_key_v1

> models::UpdateListenKeyV1Resp update_listen_key_v1()
Keepalive User Data Stream (USER_STREAM)

Keepalive a user data stream to prevent a time out. User data streams will close after 60 minutes. It's recommended to send a ping about every 60 minutes.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::UpdateListenKeyV1Resp**](UpdateListenKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_order_v1

> models::UpdateOrderV1Resp update_order_v1(price, quantity, side, symbol, timestamp, order_id, orig_client_order_id, price_match, recv_window)
Modify Order (TRADE)

Order modify function, currently only LIMIT order modification is supported, modified orders will be reordered in the match queue

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**price** | **String** |  | [required] |[default to ]
**quantity** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**price_match** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UpdateOrderV1Resp**](UpdateOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

