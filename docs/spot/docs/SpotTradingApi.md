# \SpotTradingApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_order_cancel_replace_v3**](SpotTradingApi.md#create_order_cancel_replace_v3) | **POST** /api/v3/order/cancelReplace | Cancel an Existing Order and Send a New Order (TRADE)
[**create_order_list_oco_v3**](SpotTradingApi.md#create_order_list_oco_v3) | **POST** /api/v3/orderList/oco | New Order list - OCO (TRADE)
[**create_order_list_oto_v3**](SpotTradingApi.md#create_order_list_oto_v3) | **POST** /api/v3/orderList/oto | New Order list - OTO (TRADE)
[**create_order_list_otoco_v3**](SpotTradingApi.md#create_order_list_otoco_v3) | **POST** /api/v3/orderList/otoco | New Order list - OTOCO (TRADE)
[**create_order_oco_v3**](SpotTradingApi.md#create_order_oco_v3) | **POST** /api/v3/order/oco | New OCO - Deprecated (TRADE)
[**create_order_test_v3**](SpotTradingApi.md#create_order_test_v3) | **POST** /api/v3/order/test | Test new order (TRADE)
[**create_order_v3**](SpotTradingApi.md#create_order_v3) | **POST** /api/v3/order | New order (TRADE)
[**create_sor_order_test_v3**](SpotTradingApi.md#create_sor_order_test_v3) | **POST** /api/v3/sor/order/test | Test new order using SOR (TRADE)
[**create_sor_order_v3**](SpotTradingApi.md#create_sor_order_v3) | **POST** /api/v3/sor/order | New order using SOR (TRADE)
[**create_user_data_stream_v3**](SpotTradingApi.md#create_user_data_stream_v3) | **POST** /api/v3/userDataStream | Start user data stream (USER_STREAM)
[**delete_open_orders_v3**](SpotTradingApi.md#delete_open_orders_v3) | **DELETE** /api/v3/openOrders | Cancel All Open Orders on a Symbol (TRADE)
[**delete_order_list_v3**](SpotTradingApi.md#delete_order_list_v3) | **DELETE** /api/v3/orderList | Cancel Order list (TRADE)
[**delete_order_v3**](SpotTradingApi.md#delete_order_v3) | **DELETE** /api/v3/order | Cancel order (TRADE)
[**delete_user_data_stream_v3**](SpotTradingApi.md#delete_user_data_stream_v3) | **DELETE** /api/v3/userDataStream | Close user data stream (USER_STREAM)
[**get_account_commission_v3**](SpotTradingApi.md#get_account_commission_v3) | **GET** /api/v3/account/commission | Query Commission Rates (USER_DATA)
[**get_account_v3**](SpotTradingApi.md#get_account_v3) | **GET** /api/v3/account | Account information (USER_DATA)
[**get_agg_trades_v3**](SpotTradingApi.md#get_agg_trades_v3) | **GET** /api/v3/aggTrades | Compressed/Aggregate trades list
[**get_all_order_list_v3**](SpotTradingApi.md#get_all_order_list_v3) | **GET** /api/v3/allOrderList | Query all Order lists (USER_DATA)
[**get_all_orders_v3**](SpotTradingApi.md#get_all_orders_v3) | **GET** /api/v3/allOrders | All orders (USER_DATA)
[**get_avg_price_v3**](SpotTradingApi.md#get_avg_price_v3) | **GET** /api/v3/avgPrice | Current average price
[**get_depth_v3**](SpotTradingApi.md#get_depth_v3) | **GET** /api/v3/depth | Order book
[**get_exchange_info_v3**](SpotTradingApi.md#get_exchange_info_v3) | **GET** /api/v3/exchangeInfo | Exchange information
[**get_historical_trades_v3**](SpotTradingApi.md#get_historical_trades_v3) | **GET** /api/v3/historicalTrades | Old trade lookup
[**get_klines_v3**](SpotTradingApi.md#get_klines_v3) | **GET** /api/v3/klines | Kline/Candlestick data
[**get_my_allocations_v3**](SpotTradingApi.md#get_my_allocations_v3) | **GET** /api/v3/myAllocations | Query Allocations (USER_DATA)
[**get_my_prevented_matches_v3**](SpotTradingApi.md#get_my_prevented_matches_v3) | **GET** /api/v3/myPreventedMatches | Query Prevented Matches (USER_DATA)
[**get_my_trades_v3**](SpotTradingApi.md#get_my_trades_v3) | **GET** /api/v3/myTrades | Account trade list (USER_DATA)
[**get_open_order_list_v3**](SpotTradingApi.md#get_open_order_list_v3) | **GET** /api/v3/openOrderList | Query Open Order lists (USER_DATA)
[**get_open_orders_v3**](SpotTradingApi.md#get_open_orders_v3) | **GET** /api/v3/openOrders | Current open orders (USER_DATA)
[**get_order_list_v3**](SpotTradingApi.md#get_order_list_v3) | **GET** /api/v3/orderList | Query Order list (USER_DATA)
[**get_order_v3**](SpotTradingApi.md#get_order_v3) | **GET** /api/v3/order | Query order (USER_DATA)
[**get_ping_v3**](SpotTradingApi.md#get_ping_v3) | **GET** /api/v3/ping | Test connectivity
[**get_rate_limit_order_v3**](SpotTradingApi.md#get_rate_limit_order_v3) | **GET** /api/v3/rateLimit/order | Query Unfilled Order Count (USER_DATA)
[**get_ticker24hr_v3**](SpotTradingApi.md#get_ticker24hr_v3) | **GET** /api/v3/ticker/24hr | 24hr ticker price change statistics
[**get_ticker_book_ticker_v3**](SpotTradingApi.md#get_ticker_book_ticker_v3) | **GET** /api/v3/ticker/bookTicker | Symbol order book ticker
[**get_ticker_price_v3**](SpotTradingApi.md#get_ticker_price_v3) | **GET** /api/v3/ticker/price | Symbol price ticker
[**get_ticker_trading_day_v3**](SpotTradingApi.md#get_ticker_trading_day_v3) | **GET** /api/v3/ticker/tradingDay | Trading Day Ticker
[**get_ticker_v3**](SpotTradingApi.md#get_ticker_v3) | **GET** /api/v3/ticker | Rolling window price change statistics
[**get_time_v3**](SpotTradingApi.md#get_time_v3) | **GET** /api/v3/time | Check server time
[**get_trades_v3**](SpotTradingApi.md#get_trades_v3) | **GET** /api/v3/trades | Recent trades list
[**get_ui_klines_v3**](SpotTradingApi.md#get_ui_klines_v3) | **GET** /api/v3/uiKlines | UIKlines
[**update_user_data_stream_v3**](SpotTradingApi.md#update_user_data_stream_v3) | **PUT** /api/v3/userDataStream | Keepalive user data stream (USER_STREAM)



## create_order_cancel_replace_v3

> models::SpotCreateOrderCancelReplaceV3Resp create_order_cancel_replace_v3(cancel_replace_mode, side, symbol, timestamp, r#type, cancel_new_client_order_id, cancel_order_id, cancel_orig_client_order_id, cancel_restrictions, iceberg_qty, new_client_order_id, new_order_resp_type, order_rate_limit_exceeded_mode, price, quantity, quote_order_qty, recv_window, self_trade_prevention_mode, stop_price, strategy_id, strategy_type, time_in_force, trailing_delta)
Cancel an Existing Order and Send a New Order (TRADE)

Cancels an existing order and places a new order on the same symbol. Filters and Order Count are evaluated before the processing of the cancellation and order placement occurs. A new order that was not attempted (i.e. when newOrderResult: NOT_ATTEMPTED ), will still increase the order count by 1.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**cancel_replace_mode** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**cancel_new_client_order_id** | Option<**String**> |  |  |[default to ]
**cancel_order_id** | Option<**i64**> |  |  |
**cancel_orig_client_order_id** | Option<**String**> |  |  |[default to ]
**cancel_restrictions** | Option<**String**> |  |  |[default to ]
**iceberg_qty** | Option<**String**> |  |  |[default to ]
**new_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**order_rate_limit_exceeded_mode** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**quantity** | Option<**String**> |  |  |[default to ]
**quote_order_qty** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**stop_price** | Option<**String**> |  |  |[default to ]
**strategy_id** | Option<**i64**> |  |  |
**strategy_type** | Option<**i32**> |  |  |
**time_in_force** | Option<**String**> |  |  |[default to ]
**trailing_delta** | Option<**i64**> |  |  |

### Return type

[**models::SpotCreateOrderCancelReplaceV3Resp**](SpotCreateOrderCancelReplaceV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_order_list_oco_v3

> models::CreateOrderListOcoV3Resp create_order_list_oco_v3(above_type, below_type, quantity, side, symbol, timestamp, above_client_order_id, above_iceberg_qty, above_price, above_stop_price, above_strategy_id, above_strategy_type, above_time_in_force, above_trailing_delta, below_client_order_id, below_iceberg_qty, below_price, below_stop_price, below_strategy_id, below_strategy_type, below_time_in_force, below_trailing_delta, list_client_order_id, new_order_resp_type, recv_window, self_trade_prevention_mode)
New Order list - OCO (TRADE)

Send in an one-cancels-the-other (OCO) pair, where activation of one order immediately cancels the other. - An OCO has 2 orders called the above order and below order. - One of the orders must be a LIMIT_MAKER/TAKE_PROFIT/TAKE_PROFIT_LIMIT order and the other must be STOP_LOSS or STOP_LOSS_LIMIT order. - Price restrictions  If the OCO is on the SELL side:  LIMIT_MAKER/TAKE_PROFIT_LIMIT price > Last Traded Price >  STOP_LOSS/STOP_LOSS_LIMIT stopPrice TAKE_PROFIT stopPrice > Last Traded Price > STOP_LOSS/STOP_LOSS_LIMIT stopPrice   If the OCO is on the BUY side:  LIMIT_MAKER/TAKE_PROFIT_LIMIT price < Last Traded Price < stopPrice TAKE_PROFIT stopPrice < Last Traded Price < STOP_LOSS/STOP_LOSS_LIMIT stopPrice - OCOs add 2 orders to the unfilled order count, EXCHANGE_MAX_ORDERS filter, and the MAX_NUM_ORDERS filter.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**above_type** | **String** |  | [required] |[default to ]
**below_type** | **String** |  | [required] |[default to ]
**quantity** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**above_client_order_id** | Option<**String**> |  |  |[default to ]
**above_iceberg_qty** | Option<**i64**> |  |  |
**above_price** | Option<**String**> |  |  |[default to ]
**above_stop_price** | Option<**String**> |  |  |[default to ]
**above_strategy_id** | Option<**i64**> |  |  |
**above_strategy_type** | Option<**i32**> |  |  |
**above_time_in_force** | Option<**String**> |  |  |[default to ]
**above_trailing_delta** | Option<**i64**> |  |  |
**below_client_order_id** | Option<**String**> |  |  |[default to ]
**below_iceberg_qty** | Option<**i64**> |  |  |
**below_price** | Option<**String**> |  |  |[default to ]
**below_stop_price** | Option<**String**> |  |  |[default to ]
**below_strategy_id** | Option<**i64**> |  |  |
**below_strategy_type** | Option<**i32**> |  |  |
**below_time_in_force** | Option<**String**> |  |  |[default to ]
**below_trailing_delta** | Option<**i64**> |  |  |
**list_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateOrderListOcoV3Resp**](CreateOrderListOcoV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_order_list_oto_v3

> models::CreateOrderListOtoV3Resp create_order_list_oto_v3(pending_quantity, pending_side, pending_type, symbol, timestamp, working_price, working_quantity, working_side, working_type, list_client_order_id, new_order_resp_type, pending_client_order_id, pending_iceberg_qty, pending_price, pending_stop_price, pending_strategy_id, pending_strategy_type, pending_time_in_force, pending_trailing_delta, recv_window, self_trade_prevention_mode, working_client_order_id, working_iceberg_qty, working_strategy_id, working_strategy_type, working_time_in_force)
New Order list - OTO (TRADE)

Places an OTO. - An OTO (One-Triggers-the-Other) is an order list comprised of 2 orders. - The first order is called the working order and must be LIMIT or LIMIT_MAKER. Initially, only the working order goes on the order book. - The second order is called the pending order. It can be any order type except for MARKET orders using parameter quoteOrderQty. The pending order is only placed on the order book when the working order gets fully filled. - If either the working order or the pending order is cancelled individually, the other order in the order list will also be canceled or expired. - When the order list is placed, if the working order gets immediately fully filled, the placement response will show the working order as FILLED but the pending order will still appear as PENDING_NEW. You need to query the status of the pending order again to see its updated status. - OTOs add 2 orders to the unfilled order count, EXCHANGE_MAX_NUM_ORDERS filter and MAX_NUM_ORDERS filter.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pending_quantity** | **String** |  | [required] |[default to ]
**pending_side** | **String** |  | [required] |[default to ]
**pending_type** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**working_price** | **String** |  | [required] |[default to ]
**working_quantity** | **String** |  | [required] |[default to ]
**working_side** | **String** |  | [required] |[default to ]
**working_type** | **String** |  | [required] |[default to ]
**list_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**pending_client_order_id** | Option<**String**> |  |  |[default to ]
**pending_iceberg_qty** | Option<**String**> |  |  |[default to ]
**pending_price** | Option<**String**> |  |  |[default to ]
**pending_stop_price** | Option<**String**> |  |  |[default to ]
**pending_strategy_id** | Option<**i64**> |  |  |
**pending_strategy_type** | Option<**i32**> |  |  |
**pending_time_in_force** | Option<**String**> |  |  |[default to ]
**pending_trailing_delta** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**working_client_order_id** | Option<**String**> |  |  |[default to ]
**working_iceberg_qty** | Option<**String**> |  |  |[default to ]
**working_strategy_id** | Option<**i64**> |  |  |
**working_strategy_type** | Option<**i32**> |  |  |
**working_time_in_force** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateOrderListOtoV3Resp**](CreateOrderListOtoV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_order_list_otoco_v3

> models::CreateOrderListOtocoV3Resp create_order_list_otoco_v3(pending_above_type, pending_quantity, pending_side, symbol, timestamp, working_price, working_quantity, working_side, working_type, list_client_order_id, new_order_resp_type, pending_above_client_order_id, pending_above_iceberg_qty, pending_above_price, pending_above_stop_price, pending_above_strategy_id, pending_above_strategy_type, pending_above_time_in_force, pending_above_trailing_delta, pending_below_client_order_id, pending_below_iceberg_qty, pending_below_price, pending_below_stop_price, pending_below_strategy_id, pending_below_strategy_type, pending_below_time_in_force, pending_below_trailing_delta, pending_below_type, recv_window, self_trade_prevention_mode, working_client_order_id, working_iceberg_qty, working_strategy_id, working_strategy_type, working_time_in_force)
New Order list - OTOCO (TRADE)

Place an OTOCO. - An OTOCO (One-Triggers-One-Cancels-the-Other) is an order list comprised of 3 orders. - The first order is called the working order and must be LIMIT or LIMIT_MAKER. Initially, only the working order goes on the order book.  The behavior of the working order is the same as the OTO. - OTOCO has 2 pending orders (pending above and pending below), forming an OCO pair. The pending orders are only placed on the order book when the working order gets fully filled.  The rules of the pending above and pending below follow the same rules as the Order list OCO. - OTOCOs add 3 orders against the unfilled order count, EXCHANGE_MAX_NUM_ORDERS filter, and MAX_NUM_ORDERS filter.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pending_above_type** | **String** |  | [required] |[default to ]
**pending_quantity** | **String** |  | [required] |[default to ]
**pending_side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**working_price** | **String** |  | [required] |[default to ]
**working_quantity** | **String** |  | [required] |[default to ]
**working_side** | **String** |  | [required] |[default to ]
**working_type** | **String** |  | [required] |[default to ]
**list_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**pending_above_client_order_id** | Option<**String**> |  |  |[default to ]
**pending_above_iceberg_qty** | Option<**String**> |  |  |[default to ]
**pending_above_price** | Option<**String**> |  |  |[default to ]
**pending_above_stop_price** | Option<**String**> |  |  |[default to ]
**pending_above_strategy_id** | Option<**i64**> |  |  |
**pending_above_strategy_type** | Option<**i32**> |  |  |
**pending_above_time_in_force** | Option<**String**> |  |  |[default to ]
**pending_above_trailing_delta** | Option<**String**> |  |  |[default to ]
**pending_below_client_order_id** | Option<**String**> |  |  |[default to ]
**pending_below_iceberg_qty** | Option<**String**> |  |  |[default to ]
**pending_below_price** | Option<**String**> |  |  |[default to ]
**pending_below_stop_price** | Option<**String**> |  |  |[default to ]
**pending_below_strategy_id** | Option<**i64**> |  |  |
**pending_below_strategy_type** | Option<**i32**> |  |  |
**pending_below_time_in_force** | Option<**String**> |  |  |[default to ]
**pending_below_trailing_delta** | Option<**String**> |  |  |[default to ]
**pending_below_type** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**working_client_order_id** | Option<**String**> |  |  |[default to ]
**working_iceberg_qty** | Option<**String**> |  |  |[default to ]
**working_strategy_id** | Option<**i64**> |  |  |
**working_strategy_type** | Option<**i32**> |  |  |
**working_time_in_force** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateOrderListOtocoV3Resp**](CreateOrderListOtocoV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_order_oco_v3

> models::CreateOrderOcoV3Resp create_order_oco_v3(price, quantity, side, stop_price, symbol, timestamp, limit_client_order_id, limit_iceberg_qty, limit_strategy_id, limit_strategy_type, list_client_order_id, new_order_resp_type, recv_window, self_trade_prevention_mode, stop_client_order_id, stop_iceberg_qty, stop_limit_price, stop_limit_time_in_force, stop_strategy_id, stop_strategy_type, trailing_delta)
New OCO - Deprecated (TRADE)

Send in a new OCO. - Price Restrictions:  SELL: Limit Price > Last Price > Stop Price BUY: Limit Price < Last Price < Stop Price - Quantity Restrictions:  Both legs must have the same quantity. ICEBERG quantities however do not have to be the same - OCO adds 2 orders to the unfilled order count, EXCHANGE_MAX_ORDERS filter and the MAX_NUM_ORDERS filter.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**price** | **String** |  | [required] |[default to ]
**quantity** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**stop_price** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**limit_client_order_id** | Option<**String**> |  |  |[default to ]
**limit_iceberg_qty** | Option<**String**> |  |  |[default to ]
**limit_strategy_id** | Option<**i64**> |  |  |
**limit_strategy_type** | Option<**i32**> |  |  |
**list_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**stop_client_order_id** | Option<**String**> |  |  |[default to ]
**stop_iceberg_qty** | Option<**String**> |  |  |[default to ]
**stop_limit_price** | Option<**String**> |  |  |[default to ]
**stop_limit_time_in_force** | Option<**String**> |  |  |[default to ]
**stop_strategy_id** | Option<**i64**> |  |  |
**stop_strategy_type** | Option<**i32**> |  |  |
**trailing_delta** | Option<**i64**> |  |  |

### Return type

[**models::CreateOrderOcoV3Resp**](CreateOrderOcoV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_order_test_v3

> models::SpotCreateOrderTestV3Resp create_order_test_v3(side, symbol, timestamp, r#type, compute_commission_rates, iceberg_qty, new_client_order_id, new_order_resp_type, price, quantity, quote_order_qty, recv_window, self_trade_prevention_mode, stop_price, strategy_id, strategy_type, time_in_force, trailing_delta)
Test new order (TRADE)

Test new order creation and signature/recvWindow long. Creates and validates a new order but does not send it into the matching engine.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**compute_commission_rates** | Option<**bool**> |  |  |
**iceberg_qty** | Option<**String**> |  |  |[default to ]
**new_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**quantity** | Option<**String**> |  |  |[default to ]
**quote_order_qty** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**stop_price** | Option<**String**> |  |  |[default to ]
**strategy_id** | Option<**i64**> |  |  |
**strategy_type** | Option<**i32**> |  |  |
**time_in_force** | Option<**String**> |  |  |[default to ]
**trailing_delta** | Option<**i64**> |  |  |

### Return type

[**models::SpotCreateOrderTestV3Resp**](SpotCreateOrderTestV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_order_v3

> models::SpotCreateOrderV3Resp create_order_v3(side, symbol, timestamp, r#type, iceberg_qty, new_client_order_id, new_order_resp_type, price, quantity, quote_order_qty, recv_window, self_trade_prevention_mode, stop_price, strategy_id, strategy_type, time_in_force, trailing_delta)
New order (TRADE)

Send in a new order.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**iceberg_qty** | Option<**String**> |  |  |[default to ]
**new_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**quantity** | Option<**String**> |  |  |[default to ]
**quote_order_qty** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**stop_price** | Option<**String**> |  |  |[default to ]
**strategy_id** | Option<**i64**> |  |  |
**strategy_type** | Option<**i32**> |  |  |
**time_in_force** | Option<**String**> |  |  |[default to ]
**trailing_delta** | Option<**i64**> |  |  |

### Return type

[**models::SpotCreateOrderV3Resp**](SpotCreateOrderV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sor_order_test_v3

> models::SpotCreateSorOrderTestV3Resp create_sor_order_test_v3(quantity, side, symbol, timestamp, r#type, compute_commission_rates, iceberg_qty, new_client_order_id, new_order_resp_type, price, recv_window, self_trade_prevention_mode, strategy_id, strategy_type, time_in_force)
Test new order using SOR (TRADE)

Test new order creation and signature/recvWindow using smart order routing (SOR). Creates and validates a new order but does not send it into the matching engine.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**quantity** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**compute_commission_rates** | Option<**bool**> |  |  |
**iceberg_qty** | Option<**String**> |  |  |[default to ]
**new_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**strategy_id** | Option<**i64**> |  |  |
**strategy_type** | Option<**i32**> |  |  |
**time_in_force** | Option<**String**> |  |  |[default to ]

### Return type

[**models::SpotCreateSorOrderTestV3Resp**](SpotCreateSorOrderTestV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sor_order_v3

> models::CreateSorOrderV3Resp create_sor_order_v3(quantity, side, symbol, timestamp, r#type, iceberg_qty, new_client_order_id, new_order_resp_type, price, recv_window, self_trade_prevention_mode, strategy_id, strategy_type, time_in_force)
New order using SOR (TRADE)

Places an order using smart order routing (SOR).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**quantity** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**iceberg_qty** | Option<**String**> |  |  |[default to ]
**new_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**strategy_id** | Option<**i64**> |  |  |
**strategy_type** | Option<**i32**> |  |  |
**time_in_force** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateSorOrderV3Resp**](CreateSorOrderV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_user_data_stream_v3

> models::CreateUserDataStreamV3Resp create_user_data_stream_v3()
Start user data stream (USER_STREAM)

Start a new user data stream. The stream will close after 60 minutes unless a keepalive is sent.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::CreateUserDataStreamV3Resp**](CreateUserDataStreamV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_open_orders_v3

> Vec<Vec<models::SpotDeleteOpenOrdersV3RespInner>> delete_open_orders_v3(symbol, timestamp, recv_window)
Cancel All Open Orders on a Symbol (TRADE)

Cancels all active orders on a symbol. This includes orders that are part of an order list.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<Vec<models::SpotDeleteOpenOrdersV3RespInner>>**](Vec.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_order_list_v3

> models::DeleteOrderListV3Resp delete_order_list_v3(symbol, timestamp, order_list_id, list_client_order_id, new_client_order_id, recv_window)
Cancel Order list (TRADE)

Cancel an entire Order list

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_list_id** | Option<**i64**> | Either `orderListId` or `listClientOrderId` must be provided |  |
**list_client_order_id** | Option<**String**> | Either `orderListId` or `listClientOrderId` must be provided |  |[default to ]
**new_client_order_id** | Option<**String**> | Used to uniquely identify this cancel. Automatically generated by default |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::DeleteOrderListV3Resp**](DeleteOrderListV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_order_v3

> models::DeleteOrderV3Resp delete_order_v3(symbol, timestamp, order_id, orig_client_order_id, new_client_order_id, cancel_restrictions, recv_window)
Cancel order (TRADE)

Cancel an active order.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**new_client_order_id** | Option<**String**> | Used to uniquely identify this cancel. Automatically generated by default. |  |[default to ]
**cancel_restrictions** | Option<**String**> | Supported values: <br/>`ONLY_NEW` - Cancel will succeed if the order status is `NEW`.<br/> `ONLY_PARTIALLY_FILLED ` - Cancel will succeed if order status is `PARTIALLY_FILLED`. |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000`. |  |

### Return type

[**models::DeleteOrderV3Resp**](DeleteOrderV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_user_data_stream_v3

> serde_json::Value delete_user_data_stream_v3(listen_key)
Close user data stream (USER_STREAM)

Close out a user data stream.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**listen_key** | **String** |  | [required] |[default to ]

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_account_commission_v3

> models::GetAccountCommissionV3Resp get_account_commission_v3(symbol)
Query Commission Rates (USER_DATA)

Get current account commission rates.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::GetAccountCommissionV3Resp**](GetAccountCommissionV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_account_v3

> models::GetAccountV3Resp get_account_v3(timestamp, omit_zero_balances, recv_window)
Account information (USER_DATA)

Get current account information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**omit_zero_balances** | Option<**bool**> | When set to `true`, emits only the non-zero balances of an account. <br/>Default value: `false` |  |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetAccountV3Resp**](GetAccountV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_agg_trades_v3

> Vec<models::SpotGetAggTradesV3RespItem> get_agg_trades_v3(symbol, from_id, start_time, end_time, limit)
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


## get_all_order_list_v3

> Vec<models::GetAllOrderListV3RespItem> get_all_order_list_v3(timestamp, from_id, start_time, end_time, limit, recv_window)
Query all Order lists (USER_DATA)

Retrieves all order lists based on provided optional parameters. Note that the time between startTime and endTime can't be longer than 24 hours.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**from_id** | Option<**i64**> | If supplied, neither `startTime` or `endTime` can be provided |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default Value: 500; Max Value: 1000 |  |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetAllOrderListV3RespItem>**](GetAllOrderListV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_all_orders_v3

> Vec<models::GetAllOrdersV3RespItem> get_all_orders_v3(symbol, timestamp, order_id, start_time, end_time, limit, recv_window)
All orders (USER_DATA)

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
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetAllOrdersV3RespItem>**](GetAllOrdersV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_avg_price_v3

> models::GetAvgPriceV3Resp get_avg_price_v3(symbol)
Current average price

Current average price for a symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::GetAvgPriceV3Resp**](GetAvgPriceV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_depth_v3

> models::GetDepthV3Resp get_depth_v3(symbol, limit)
Order book

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 100; max 5000. <br/> If limit &gt; 5000. then the response will truncate to 5000. |  |[default to 100]

### Return type

[**models::GetDepthV3Resp**](GetDepthV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_exchange_info_v3

> models::SpotGetExchangeInfoV3Resp get_exchange_info_v3(symbol, symbols, permissions, show_permission_sets, symbol_status)
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


## get_historical_trades_v3

> Vec<models::GetHistoricalTradesV3RespItem> get_historical_trades_v3(symbol, limit, from_id)
Old trade lookup

Get older trades.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]
**from_id** | Option<**i64**> | TradeId to fetch from. Default gets most recent trades. |  |

### Return type

[**Vec<models::GetHistoricalTradesV3RespItem>**](GetHistoricalTradesV3RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_klines_v3

> Vec<Vec<models::GetKlinesV3200ResponseInnerInner>> get_klines_v3(symbol, interval, start_time, end_time, time_zone, limit)
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

[**Vec<Vec<models::GetKlinesV3200ResponseInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_my_allocations_v3

> Vec<models::GetMyAllocationsV3RespItem> get_my_allocations_v3(symbol, start_time, end_time, from_allocation_id, limit, order_id, recv_window, timestamp)
Query Allocations (USER_DATA)

Retrieves allocations resulting from SOR order placement.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**from_allocation_id** | Option<**i32**> |  |  |
**limit** | Option<**i32**> | Default 500;Max 1000 |  |[default to 500]
**order_id** | Option<**i64**> |  |  |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000`. |  |
**timestamp** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetMyAllocationsV3RespItem>**](GetMyAllocationsV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_my_prevented_matches_v3

> Vec<models::GetMyPreventedMatchesV3RespItem> get_my_prevented_matches_v3(symbol, timestamp, prevented_match_id, order_id, from_prevented_match_id, limit, recv_window)
Query Prevented Matches (USER_DATA)

Displays the list of orders that were expired due to STP. These are the combinations supported: - symbol + preventedMatchId - symbol + orderId - symbol + orderId + fromPreventedMatchId (limit will default to 500) - symbol + orderId + fromPreventedMatchId + limit

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**prevented_match_id** | Option<**i64**> |  |  |
**order_id** | Option<**i64**> |  |  |
**from_prevented_match_id** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default: `500`; Max: `1000` |  |[default to 500]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetMyPreventedMatchesV3RespItem>**](GetMyPreventedMatchesV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_my_trades_v3

> Vec<models::GetMyTradesV3RespItem> get_my_trades_v3(symbol, timestamp, order_id, start_time, end_time, from_id, limit, recv_window)
Account trade list (USER_DATA)

Get trades for a specific account and symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> | This can only be used in combination with `symbol`. |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**from_id** | Option<**i64**> | TradeId to fetch from. Default gets most recent trades. |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetMyTradesV3RespItem>**](GetMyTradesV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_open_order_list_v3

> Vec<models::GetOpenOrderListV3RespItem> get_open_order_list_v3(timestamp, recv_window)
Query Open Order lists (USER_DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetOpenOrderListV3RespItem>**](GetOpenOrderListV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_open_orders_v3

> Vec<models::GetOpenOrdersV3RespItem> get_open_orders_v3(timestamp, symbol, recv_window)
Current open orders (USER_DATA)

Get all open orders on a symbol. Careful when accessing this with no symbol. Weight: 6 for a single symbol; 80 when the symbol parameter is omitted

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetOpenOrdersV3RespItem>**](GetOpenOrdersV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_order_list_v3

> models::GetOrderListV3Resp get_order_list_v3(timestamp, order_list_id, orig_client_order_id, recv_window)
Query Order list (USER_DATA)

Retrieves a specific order list based on provided optional parameters.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**order_list_id** | Option<**i64**> | Either `orderListId` or `listClientOrderId` must be provided |  |
**orig_client_order_id** | Option<**String**> | Either `orderListId` or `listClientOrderId` must be provided |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetOrderListV3Resp**](GetOrderListV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_order_v3

> models::GetOrderV3Resp get_order_v3(symbol, timestamp, order_id, orig_client_order_id, recv_window)
Query order (USER_DATA)

Check an order's status.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetOrderV3Resp**](GetOrderV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_ping_v3

> serde_json::Value get_ping_v3()
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


## get_rate_limit_order_v3

> Vec<models::GetRateLimitOrderV3RespItem> get_rate_limit_order_v3(timestamp, recv_window)
Query Unfilled Order Count (USER_DATA)

Displays the user's unfilled order count for all intervals.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetRateLimitOrderV3RespItem>**](GetRateLimitOrderV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_ticker24hr_v3

> models::SpotGetTicker24hrV3Resp get_ticker24hr_v3(symbol, symbols, r#type)
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


## get_ticker_book_ticker_v3

> models::SpotGetTickerBookTickerV3Resp get_ticker_book_ticker_v3(symbol, symbols)
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


## get_ticker_price_v3

> models::SpotGetTickerPriceV3Resp get_ticker_price_v3(symbol, symbols)
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


## get_ticker_trading_day_v3

> models::SpotGetTickerTradingDayV3Resp get_ticker_trading_day_v3(symbol, symbols, time_zone, r#type)
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


## get_ticker_v3

> models::SpotGetTickerV3Resp get_ticker_v3(symbol, symbols, window_size, r#type)
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


## get_time_v3

> models::GetTimeV3Resp get_time_v3()
Check server time

Test connectivity to the Rest API and get the current server time.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::GetTimeV3Resp**](GetTimeV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_trades_v3

> Vec<models::GetTradesV3RespItem> get_trades_v3(symbol, limit)
Recent trades list

Get recent trades.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]

### Return type

[**Vec<models::GetTradesV3RespItem>**](GetTradesV3RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_ui_klines_v3

> Vec<Vec<models::GetKlinesV3200ResponseInnerInner>> get_ui_klines_v3(symbol, interval, start_time, end_time, time_zone, limit)
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

[**Vec<Vec<models::GetKlinesV3200ResponseInnerInner>>**](Vec.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_user_data_stream_v3

> serde_json::Value update_user_data_stream_v3(listen_key)
Keepalive user data stream (USER_STREAM)

Keepalive a user data stream to prevent a time out. User data streams will close after 60 minutes. It's recommended to send a ping about every 30 minutes.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**listen_key** | **String** |  | [required] |[default to ]

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

