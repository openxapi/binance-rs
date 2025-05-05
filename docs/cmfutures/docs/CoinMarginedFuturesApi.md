# \CoinMarginedFuturesApi

All URIs are relative to *https://dapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_batch_orders_v1**](CoinMarginedFuturesApi.md#create_batch_orders_v1) | **POST** /dapi/v1/batchOrders | Place Multiple Orders(TRADE)
[**create_countdown_cancel_all_v1**](CoinMarginedFuturesApi.md#create_countdown_cancel_all_v1) | **POST** /dapi/v1/countdownCancelAll | Auto-Cancel All Open Orders (TRADE)
[**create_leverage_v1**](CoinMarginedFuturesApi.md#create_leverage_v1) | **POST** /dapi/v1/leverage | Change Initial Leverage (TRADE)
[**create_listen_key_v1**](CoinMarginedFuturesApi.md#create_listen_key_v1) | **POST** /dapi/v1/listenKey | Start User Data Stream (USER_STREAM)
[**create_margin_type_v1**](CoinMarginedFuturesApi.md#create_margin_type_v1) | **POST** /dapi/v1/marginType | Change Margin Type (TRADE)
[**create_order_v1**](CoinMarginedFuturesApi.md#create_order_v1) | **POST** /dapi/v1/order | New Order (TRADE)
[**create_position_margin_v1**](CoinMarginedFuturesApi.md#create_position_margin_v1) | **POST** /dapi/v1/positionMargin | Modify Isolated Position Margin(TRADE)
[**create_position_side_dual_v1**](CoinMarginedFuturesApi.md#create_position_side_dual_v1) | **POST** /dapi/v1/positionSide/dual | Change Position Mode(TRADE)
[**delete_all_open_orders_v1**](CoinMarginedFuturesApi.md#delete_all_open_orders_v1) | **DELETE** /dapi/v1/allOpenOrders | Cancel All Open Orders(TRADE)
[**delete_batch_orders_v1**](CoinMarginedFuturesApi.md#delete_batch_orders_v1) | **DELETE** /dapi/v1/batchOrders | Cancel Multiple Orders(TRADE)
[**delete_listen_key_v1**](CoinMarginedFuturesApi.md#delete_listen_key_v1) | **DELETE** /dapi/v1/listenKey | Close User Data Stream(USER_STREAM)
[**delete_order_v1**](CoinMarginedFuturesApi.md#delete_order_v1) | **DELETE** /dapi/v1/order | Cancel Order (TRADE)
[**get_account_v1**](CoinMarginedFuturesApi.md#get_account_v1) | **GET** /dapi/v1/account | Account Information (USER_DATA)
[**get_adl_quantile_v1**](CoinMarginedFuturesApi.md#get_adl_quantile_v1) | **GET** /dapi/v1/adlQuantile | Position ADL Quantile Estimation(USER_DATA)
[**get_agg_trades_v1**](CoinMarginedFuturesApi.md#get_agg_trades_v1) | **GET** /dapi/v1/aggTrades | Compressed/Aggregate Trades List
[**get_all_orders_v1**](CoinMarginedFuturesApi.md#get_all_orders_v1) | **GET** /dapi/v1/allOrders | All Orders (USER_DATA)
[**get_balance_v1**](CoinMarginedFuturesApi.md#get_balance_v1) | **GET** /dapi/v1/balance | Futures Account Balance (USER_DATA)
[**get_commission_rate_v1**](CoinMarginedFuturesApi.md#get_commission_rate_v1) | **GET** /dapi/v1/commissionRate | User Commission Rate (USER_DATA)
[**get_constituents_v1**](CoinMarginedFuturesApi.md#get_constituents_v1) | **GET** /dapi/v1/constituents | Query Index Price Constituents
[**get_continuous_klines_v1**](CoinMarginedFuturesApi.md#get_continuous_klines_v1) | **GET** /dapi/v1/continuousKlines | Continuous Contract Kline/Candlestick Data
[**get_depth_v1**](CoinMarginedFuturesApi.md#get_depth_v1) | **GET** /dapi/v1/depth | Order Book
[**get_exchange_info_v1**](CoinMarginedFuturesApi.md#get_exchange_info_v1) | **GET** /dapi/v1/exchangeInfo | Exchange Information
[**get_force_orders_v1**](CoinMarginedFuturesApi.md#get_force_orders_v1) | **GET** /dapi/v1/forceOrders | User's Force Orders(USER_DATA)
[**get_funding_info_v1**](CoinMarginedFuturesApi.md#get_funding_info_v1) | **GET** /dapi/v1/fundingInfo | Get Funding Rate Info
[**get_funding_rate_v1**](CoinMarginedFuturesApi.md#get_funding_rate_v1) | **GET** /dapi/v1/fundingRate | Get Funding Rate History of Perpetual Futures
[**get_futures_data_basis**](CoinMarginedFuturesApi.md#get_futures_data_basis) | **GET** /futures/data/basis | Basis
[**get_futures_data_global_long_short_account_ratio**](CoinMarginedFuturesApi.md#get_futures_data_global_long_short_account_ratio) | **GET** /futures/data/globalLongShortAccountRatio | Long/Short Ratio
[**get_futures_data_open_interest_hist**](CoinMarginedFuturesApi.md#get_futures_data_open_interest_hist) | **GET** /futures/data/openInterestHist | Open Interest Statistics
[**get_futures_data_taker_buy_sell_vol**](CoinMarginedFuturesApi.md#get_futures_data_taker_buy_sell_vol) | **GET** /futures/data/takerBuySellVol | Taker Buy/Sell Volume
[**get_futures_data_top_long_short_account_ratio**](CoinMarginedFuturesApi.md#get_futures_data_top_long_short_account_ratio) | **GET** /futures/data/topLongShortAccountRatio | Top Trader Long/Short Ratio (Accounts)
[**get_futures_data_top_long_short_position_ratio**](CoinMarginedFuturesApi.md#get_futures_data_top_long_short_position_ratio) | **GET** /futures/data/topLongShortPositionRatio | Top Trader Long/Short Ratio (Positions)
[**get_historical_trades_v1**](CoinMarginedFuturesApi.md#get_historical_trades_v1) | **GET** /dapi/v1/historicalTrades | Old Trades Lookup(MARKET_DATA)
[**get_income_asyn_id_v1**](CoinMarginedFuturesApi.md#get_income_asyn_id_v1) | **GET** /dapi/v1/income/asyn/id | Get Futures Transaction History Download Link by Id (USER_DATA)
[**get_income_asyn_v1**](CoinMarginedFuturesApi.md#get_income_asyn_v1) | **GET** /dapi/v1/income/asyn | Get Download Id For Futures Transaction History(USER_DATA)
[**get_income_v1**](CoinMarginedFuturesApi.md#get_income_v1) | **GET** /dapi/v1/income | Get Income History(USER_DATA)
[**get_index_price_klines_v1**](CoinMarginedFuturesApi.md#get_index_price_klines_v1) | **GET** /dapi/v1/indexPriceKlines | Index Price Kline/Candlestick Data
[**get_klines_v1**](CoinMarginedFuturesApi.md#get_klines_v1) | **GET** /dapi/v1/klines | Kline/Candlestick Data
[**get_leverage_bracket_v1**](CoinMarginedFuturesApi.md#get_leverage_bracket_v1) | **GET** /dapi/v1/leverageBracket | Notional Bracket for Pair(USER_DATA)
[**get_leverage_bracket_v2**](CoinMarginedFuturesApi.md#get_leverage_bracket_v2) | **GET** /dapi/v2/leverageBracket | Notional Bracket for Symbol(USER_DATA)
[**get_mark_price_klines_v1**](CoinMarginedFuturesApi.md#get_mark_price_klines_v1) | **GET** /dapi/v1/markPriceKlines | Mark Price Kline/Candlestick Data
[**get_open_interest_v1**](CoinMarginedFuturesApi.md#get_open_interest_v1) | **GET** /dapi/v1/openInterest | Open Interest
[**get_open_order_v1**](CoinMarginedFuturesApi.md#get_open_order_v1) | **GET** /dapi/v1/openOrder | Query Current Open Order(USER_DATA)
[**get_open_orders_v1**](CoinMarginedFuturesApi.md#get_open_orders_v1) | **GET** /dapi/v1/openOrders | Current All Open Orders (USER_DATA)
[**get_order_amendment_v1**](CoinMarginedFuturesApi.md#get_order_amendment_v1) | **GET** /dapi/v1/orderAmendment | Get Order Modify History (USER_DATA)
[**get_order_asyn_id_v1**](CoinMarginedFuturesApi.md#get_order_asyn_id_v1) | **GET** /dapi/v1/order/asyn/id | Get Futures Order History Download Link by Id (USER_DATA)
[**get_order_asyn_v1**](CoinMarginedFuturesApi.md#get_order_asyn_v1) | **GET** /dapi/v1/order/asyn | Get Download Id For Futures Order History (USER_DATA)
[**get_order_v1**](CoinMarginedFuturesApi.md#get_order_v1) | **GET** /dapi/v1/order | Query Order (USER_DATA)
[**get_ping_v1**](CoinMarginedFuturesApi.md#get_ping_v1) | **GET** /dapi/v1/ping | Test Connectivity
[**get_pm_account_info_v1**](CoinMarginedFuturesApi.md#get_pm_account_info_v1) | **GET** /dapi/v1/pmAccountInfo | Classic Portfolio Margin Account Information (USER_DATA)
[**get_position_margin_history_v1**](CoinMarginedFuturesApi.md#get_position_margin_history_v1) | **GET** /dapi/v1/positionMargin/history | Get Position Margin Change History(TRADE)
[**get_position_risk_v1**](CoinMarginedFuturesApi.md#get_position_risk_v1) | **GET** /dapi/v1/positionRisk | Position Information(USER_DATA)
[**get_position_side_dual_v1**](CoinMarginedFuturesApi.md#get_position_side_dual_v1) | **GET** /dapi/v1/positionSide/dual | Get Current Position Mode(USER_DATA)
[**get_premium_index_klines_v1**](CoinMarginedFuturesApi.md#get_premium_index_klines_v1) | **GET** /dapi/v1/premiumIndexKlines | Premium index Kline Data
[**get_premium_index_v1**](CoinMarginedFuturesApi.md#get_premium_index_v1) | **GET** /dapi/v1/premiumIndex | Index Price and Mark Price
[**get_ticker24hr_v1**](CoinMarginedFuturesApi.md#get_ticker24hr_v1) | **GET** /dapi/v1/ticker/24hr | 24hr Ticker Price Change Statistics
[**get_ticker_book_ticker_v1**](CoinMarginedFuturesApi.md#get_ticker_book_ticker_v1) | **GET** /dapi/v1/ticker/bookTicker | Symbol Order Book Ticker
[**get_ticker_price_v1**](CoinMarginedFuturesApi.md#get_ticker_price_v1) | **GET** /dapi/v1/ticker/price | Symbol Price Ticker
[**get_time_v1**](CoinMarginedFuturesApi.md#get_time_v1) | **GET** /dapi/v1/time | Check Server time
[**get_trade_asyn_id_v1**](CoinMarginedFuturesApi.md#get_trade_asyn_id_v1) | **GET** /dapi/v1/trade/asyn/id | Get Futures Trade Download Link by Id(USER_DATA)
[**get_trade_asyn_v1**](CoinMarginedFuturesApi.md#get_trade_asyn_v1) | **GET** /dapi/v1/trade/asyn | Get Download Id For Futures Trade History (USER_DATA)
[**get_trades_v1**](CoinMarginedFuturesApi.md#get_trades_v1) | **GET** /dapi/v1/trades | Recent Trades List
[**get_user_trades_v1**](CoinMarginedFuturesApi.md#get_user_trades_v1) | **GET** /dapi/v1/userTrades | Account Trade List (USER_DATA)
[**update_batch_orders_v1**](CoinMarginedFuturesApi.md#update_batch_orders_v1) | **PUT** /dapi/v1/batchOrders | Modify Multiple Orders(TRADE)
[**update_listen_key_v1**](CoinMarginedFuturesApi.md#update_listen_key_v1) | **PUT** /dapi/v1/listenKey | Keepalive User Data Stream (USER_STREAM)
[**update_order_v1**](CoinMarginedFuturesApi.md#update_order_v1) | **PUT** /dapi/v1/order | Modify Order (TRADE)



## create_batch_orders_v1

> Vec<models::CmfuturesCreateBatchOrdersV1RespInner> create_batch_orders_v1(batch_orders, timestamp, recv_window)
Place Multiple Orders(TRADE)

Place multiple orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**batch_orders** | [**Vec<models::CmfuturesCreateBatchOrderV1ReqBatchOrdersItem>**](models::CmfuturesCreateBatchOrderV1ReqBatchOrdersItem.md) |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesCreateBatchOrdersV1RespInner>**](CmfuturesCreateBatchOrdersV1Resp_inner.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_countdown_cancel_all_v1

> models::CreateCountdownCancelAllV1Resp create_countdown_cancel_all_v1(countdown_time, symbol, timestamp, recv_window)
Auto-Cancel All Open Orders (TRADE)

Cancel all open orders of the specified symbol at the end of the specified countdown. This rest endpoint means to ensure your open orders are canceled in case of an outage. The endpoint should be called repeatedly as heartbeats so that the existing countdown time can be canceled and repalced by a new one. The system will check all countdowns approximately every 10 milliseconds, so please note that sufficient redundancy should be considered when using this function. We do not recommend setting the countdown time to be too precise or too small.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**countdown_time** | **i64** |  | [required] |
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateCountdownCancelAllV1Resp**](CreateCountdownCancelAllV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_leverage_v1

> models::CreateLeverageV1Resp create_leverage_v1(leverage, symbol, timestamp, recv_window)
Change Initial Leverage (TRADE)

Change user's initial leverage in the specific symbol market. For Hedge Mode, LONG and SHORT positions of one symbol use the same initial leverage and share a total notional value.

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
Change Margin Type (TRADE)

Change user's margin type in the specific symbol market.For Hedge Mode, LONG and SHORT positions of one symbol use the same margin type. With ISOLATED margin type, margins of the LONG and SHORT positions are isolated from each other.

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


## create_order_v1

> models::CreateOrderV1Resp create_order_v1(side, symbol, timestamp, r#type, activation_price, callback_rate, close_position, new_client_order_id, new_order_resp_type, position_side, price, price_match, price_protect, quantity, recv_window, reduce_only, self_trade_prevention_mode, stop_price, time_in_force, working_type)
New Order (TRADE)

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
Cancel All Open Orders(TRADE)

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

> Vec<models::CmfuturesDeleteBatchOrdersV1RespInner> delete_batch_orders_v1(symbol, timestamp, order_id_list, orig_client_order_id_list, recv_window)
Cancel Multiple Orders(TRADE)

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

[**Vec<models::CmfuturesDeleteBatchOrdersV1RespInner>**](CmfuturesDeleteBatchOrdersV1Resp_inner.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_listen_key_v1

> serde_json::Value delete_listen_key_v1()
Close User Data Stream(USER_STREAM)

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


## get_account_v1

> models::GetAccountV1Resp get_account_v1(timestamp, recv_window)
Account Information (USER_DATA)

Get current account information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAccountV1Resp**](GetAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_adl_quantile_v1

> Vec<models::GetAdlQuantileV1RespItem> get_adl_quantile_v1(timestamp, symbol, recv_window)
Position ADL Quantile Estimation(USER_DATA)

Query position ADL quantile estimation

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

> Vec<models::GetAggTradesV1RespItem> get_agg_trades_v1(symbol, from_id, start_time, end_time, limit)
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

[**Vec<models::GetAggTradesV1RespItem>**](GetAggTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_all_orders_v1

> Vec<models::GetAllOrdersV1RespItem> get_all_orders_v1(timestamp, symbol, pair, order_id, start_time, end_time, limit, recv_window)
All Orders (USER_DATA)

Get all account orders; active, canceled, or filled.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]
**order_id** | Option<**i64**> |  |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 50; max 100. |  |[default to 50]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetAllOrdersV1RespItem>**](GetAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_balance_v1

> Vec<models::GetBalanceV1RespItem> get_balance_v1(timestamp, recv_window)
Futures Account Balance (USER_DATA)

Check futures account balance

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBalanceV1RespItem>**](GetBalanceV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_commission_rate_v1

> models::GetCommissionRateV1Resp get_commission_rate_v1(symbol, timestamp, recv_window)
User Commission Rate (USER_DATA)

Query user commission rate

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

> Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>> get_continuous_klines_v1(pair, contract_type, interval, start_time, end_time, limit)
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


## get_depth_v1

> models::GetDepthV1Resp get_depth_v1(symbol, limit)
Order Book

Query orderbook on specific symbol

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

> models::CmfuturesGetExchangeInfoV1Resp get_exchange_info_v1()
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


## get_force_orders_v1

> Vec<models::CmfuturesGetForceOrdersV1RespItem> get_force_orders_v1(timestamp, symbol, auto_close_type, recv_window, limit, start_time, end_time)
User's Force Orders(USER_DATA)

User's Force Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**auto_close_type** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**limit** | Option<**i32**> |  |  |[default to 50]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesGetForceOrdersV1RespItem>**](CmfuturesGetForceOrdersV1RespItem.md)

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

[**Vec<models::GetFuturesDataBasisRespItem>**](GetFuturesDataBasisRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_futures_data_global_long_short_account_ratio

> Vec<models::GetFuturesDataGlobalLongShortAccountRatioRespItem> get_futures_data_global_long_short_account_ratio(pair, period, limit, start_time, end_time)
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

[**Vec<models::GetFuturesDataGlobalLongShortAccountRatioRespItem>**](GetFuturesDataGlobalLongShortAccountRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_futures_data_open_interest_hist

> Vec<models::GetFuturesDataOpenInterestHistRespItem> get_futures_data_open_interest_hist(pair, contract_type, period, limit, start_time, end_time)
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

[**Vec<models::GetFuturesDataOpenInterestHistRespItem>**](GetFuturesDataOpenInterestHistRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_futures_data_taker_buy_sell_vol

> Vec<models::GetFuturesDataTakerBuySellVolRespItem> get_futures_data_taker_buy_sell_vol(pair, contract_type, period, limit, start_time, end_time)
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

[**Vec<models::GetFuturesDataTakerBuySellVolRespItem>**](GetFuturesDataTakerBuySellVolRespItem.md)

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

> Vec<models::GetFuturesDataTopLongShortPositionRatioRespItem> get_futures_data_top_long_short_position_ratio(pair, period, limit, start_time, end_time)
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

[**Vec<models::GetFuturesDataTopLongShortPositionRatioRespItem>**](GetFuturesDataTopLongShortPositionRatioRespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_historical_trades_v1

> Vec<models::GetHistoricalTradesV1RespItem> get_historical_trades_v1(symbol, limit, from_id)
Old Trades Lookup(MARKET_DATA)

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


## get_income_v1

> Vec<models::GetIncomeV1RespItem> get_income_v1(timestamp, symbol, income_type, start_time, end_time, page, limit, recv_window)
Get Income History(USER_DATA)

Get income history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**income_type** | Option<**String**> | &#34;TRANSFER&#34;,&#34;WELCOME_BONUS&#34;, &#34;FUNDING_FEE&#34;, &#34;REALIZED_PNL&#34;, &#34;COMMISSION&#34;, &#34;INSURANCE_CLEAR&#34;, and &#34;DELIVERED_SETTELMENT&#34; |  |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get funding from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get funding until INCLUSIVE. |  |
**page** | Option<**i32**> |  |  |
**limit** | Option<**i32**> | Default 100; max 1000 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetIncomeV1RespItem>**](GetIncomeV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_index_price_klines_v1

> Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>> get_index_price_klines_v1(pair, interval, start_time, end_time, limit)
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


## get_klines_v1

> Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>> get_klines_v1(symbol, interval, start_time, end_time, limit)
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


## get_leverage_bracket_v1

> Vec<models::GetLeverageBracketV1RespItem> get_leverage_bracket_v1(timestamp, pair, recv_window)
Notional Bracket for Pair(USER_DATA)

Not recommended to continue using this v1 endpoint

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**pair** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetLeverageBracketV1RespItem>**](GetLeverageBracketV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_leverage_bracket_v2

> Vec<models::GetLeverageBracketV2RespItem> get_leverage_bracket_v2(timestamp, symbol, recv_window)
Notional Bracket for Symbol(USER_DATA)

Get the symbol's notional bracket list.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetLeverageBracketV2RespItem>**](GetLeverageBracketV2RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mark_price_klines_v1

> Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>> get_mark_price_klines_v1(symbol, interval, start_time, end_time, limit)
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
Query Current Open Order(USER_DATA)

Query Current Open Order

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

> Vec<models::GetOpenOrdersV1RespItem> get_open_orders_v1(timestamp, symbol, pair, recv_window)
Current All Open Orders (USER_DATA)

Get all open orders on a symbol. Careful when accessing this with no symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]
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

> models::GetOrderAsynV1Resp get_order_asyn_v1(start_time, end_time, timestamp, recv_window)
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

[**models::GetOrderAsynV1Resp**](GetOrderAsynV1Resp.md)

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

> models::GetPmAccountInfoV1Resp get_pm_account_info_v1(asset, recv_window)
Classic Portfolio Margin Account Information (USER_DATA)

Get Classic Portfolio Margin current account information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
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
Get Position Margin Change History(TRADE)

Get position margin change history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | Option<**i32**> | 1: Add position margin,2: Reduce position margin |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default: 50 |  |[default to 50]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetPositionMarginHistoryV1RespItem>**](GetPositionMarginHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_position_risk_v1

> Vec<models::GetPositionRiskV1RespItem> get_position_risk_v1(timestamp, margin_asset, pair, recv_window)
Position Information(USER_DATA)

Get current account information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**margin_asset** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetPositionRiskV1RespItem>**](GetPositionRiskV1RespItem.md)

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

> Vec<Vec<models::CmfuturesGetContinuousKlinesV1RespInnerInner>> get_premium_index_klines_v1(symbol, interval, start_time, end_time, limit)
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


## get_premium_index_v1

> Vec<models::GetPremiumIndexV1RespItem> get_premium_index_v1(symbol, pair)
Index Price and Mark Price

Query index price and mark price

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::GetPremiumIndexV1RespItem>**](GetPremiumIndexV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_ticker24hr_v1

> Vec<models::GetTicker24hrV1RespItem> get_ticker24hr_v1(symbol, pair)
24hr Ticker Price Change Statistics

24 hour rolling window price change statistics.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::GetTicker24hrV1RespItem>**](GetTicker24hrV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_ticker_book_ticker_v1

> Vec<models::GetTickerBookTickerV1RespItem> get_ticker_book_ticker_v1(symbol, pair)
Symbol Order Book Ticker

Best price/qty on the order book for a symbol or symbols.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::GetTickerBookTickerV1RespItem>**](GetTickerBookTickerV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_ticker_price_v1

> Vec<models::GetTickerPriceV1RespItem> get_ticker_price_v1(symbol, pair)
Symbol Price Ticker

Latest price for a symbol or symbols.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::GetTickerPriceV1RespItem>**](GetTickerPriceV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_time_v1

> models::GetTimeV1Resp get_time_v1()
Check Server time

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

> Vec<models::GetUserTradesV1RespItem> get_user_trades_v1(timestamp, symbol, pair, order_id, start_time, end_time, from_id, limit, recv_window)
Account Trade List (USER_DATA)

Get trades for a specific account and symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]
**order_id** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**from_id** | Option<**i64**> | Trade id to fetch from. Default gets most recent trades. |  |
**limit** | Option<**i32**> | Default 50; max 1000 |  |[default to 50]
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

> Vec<models::CmfuturesUpdateBatchOrdersV1RespInner> update_batch_orders_v1(batch_orders, timestamp, recv_window)
Modify Multiple Orders(TRADE)

Modify Multiple Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**batch_orders** | [**Vec<models::CmfuturesUpdateBatchOrdersV1ReqBatchOrdersItem>**](models::CmfuturesUpdateBatchOrdersV1ReqBatchOrdersItem.md) |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesUpdateBatchOrdersV1RespInner>**](CmfuturesUpdateBatchOrdersV1Resp_inner.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_listen_key_v1

> serde_json::Value update_listen_key_v1()
Keepalive User Data Stream (USER_STREAM)

Keepalive a user data stream to prevent a time out. User data streams will close after 60 minutes.

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


## update_order_v1

> models::UpdateOrderV1Resp update_order_v1(side, symbol, timestamp, order_id, orig_client_order_id, price, price_match, quantity, recv_window)
Modify Order (TRADE)

Order modify function, currently only LIMIT order modification is supported, modified orders will be reordered in the match queue

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**price_match** | Option<**String**> |  |  |[default to ]
**quantity** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UpdateOrderV1Resp**](UpdateOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

