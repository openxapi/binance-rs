# \TradingApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**spot_create_order_cancel_replace_v3**](TradingApi.md#spot_create_order_cancel_replace_v3) | **POST** /api/v3/order/cancelReplace | Cancel an Existing Order and Send a New Order (TRADE)
[**spot_create_order_list_oco_v3**](TradingApi.md#spot_create_order_list_oco_v3) | **POST** /api/v3/orderList/oco | New Order list - OCO (TRADE)
[**spot_create_order_list_oto_v3**](TradingApi.md#spot_create_order_list_oto_v3) | **POST** /api/v3/orderList/oto | New Order list - OTO (TRADE)
[**spot_create_order_list_otoco_v3**](TradingApi.md#spot_create_order_list_otoco_v3) | **POST** /api/v3/orderList/otoco | New Order list - OTOCO (TRADE)
[**spot_create_order_oco_v3**](TradingApi.md#spot_create_order_oco_v3) | **POST** /api/v3/order/oco | New OCO - Deprecated (TRADE)
[**spot_create_order_test_v3**](TradingApi.md#spot_create_order_test_v3) | **POST** /api/v3/order/test | Test new order (TRADE)
[**spot_create_order_v3**](TradingApi.md#spot_create_order_v3) | **POST** /api/v3/order | New order (TRADE)
[**spot_create_sor_order_test_v3**](TradingApi.md#spot_create_sor_order_test_v3) | **POST** /api/v3/sor/order/test | Test new order using SOR (TRADE)
[**spot_create_sor_order_v3**](TradingApi.md#spot_create_sor_order_v3) | **POST** /api/v3/sor/order | New order using SOR (TRADE)
[**spot_delete_open_orders_v3**](TradingApi.md#spot_delete_open_orders_v3) | **DELETE** /api/v3/openOrders | Cancel All Open Orders on a Symbol (TRADE)
[**spot_delete_order_list_v3**](TradingApi.md#spot_delete_order_list_v3) | **DELETE** /api/v3/orderList | Cancel Order list (TRADE)
[**spot_delete_order_v3**](TradingApi.md#spot_delete_order_v3) | **DELETE** /api/v3/order | Cancel order (TRADE)
[**spot_get_all_order_list_v3**](TradingApi.md#spot_get_all_order_list_v3) | **GET** /api/v3/allOrderList | Query all Order lists (USER_DATA)
[**spot_get_all_orders_v3**](TradingApi.md#spot_get_all_orders_v3) | **GET** /api/v3/allOrders | All orders (USER_DATA)
[**spot_get_open_order_list_v3**](TradingApi.md#spot_get_open_order_list_v3) | **GET** /api/v3/openOrderList | Query Open Order lists (USER_DATA)
[**spot_get_open_orders_v3**](TradingApi.md#spot_get_open_orders_v3) | **GET** /api/v3/openOrders | Current open orders (USER_DATA)
[**spot_get_order_list_v3**](TradingApi.md#spot_get_order_list_v3) | **GET** /api/v3/orderList | Query Order list (USER_DATA)
[**spot_get_order_v3**](TradingApi.md#spot_get_order_v3) | **GET** /api/v3/order | Query order (USER_DATA)



## spot_create_order_cancel_replace_v3

> models::SpotCreateOrderCancelReplaceV3Resp spot_create_order_cancel_replace_v3(cancel_replace_mode, side, symbol, timestamp, r#type, cancel_new_client_order_id, cancel_order_id, cancel_orig_client_order_id, cancel_restrictions, iceberg_qty, new_client_order_id, new_order_resp_type, order_rate_limit_exceeded_mode, price, quantity, quote_order_qty, recv_window, self_trade_prevention_mode, stop_price, strategy_id, strategy_type, time_in_force, trailing_delta)
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


## spot_create_order_list_oco_v3

> models::SpotCreateOrderListOcoV3Resp spot_create_order_list_oco_v3(above_type, below_type, quantity, side, symbol, timestamp, above_client_order_id, above_iceberg_qty, above_price, above_stop_price, above_strategy_id, above_strategy_type, above_time_in_force, above_trailing_delta, below_client_order_id, below_iceberg_qty, below_price, below_stop_price, below_strategy_id, below_strategy_type, below_time_in_force, below_trailing_delta, list_client_order_id, new_order_resp_type, recv_window, self_trade_prevention_mode)
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

[**models::SpotCreateOrderListOcoV3Resp**](SpotCreateOrderListOcoV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_create_order_list_oto_v3

> models::SpotCreateOrderListOtoV3Resp spot_create_order_list_oto_v3(pending_quantity, pending_side, pending_type, symbol, timestamp, working_price, working_quantity, working_side, working_type, list_client_order_id, new_order_resp_type, pending_client_order_id, pending_iceberg_qty, pending_price, pending_stop_price, pending_strategy_id, pending_strategy_type, pending_time_in_force, pending_trailing_delta, recv_window, self_trade_prevention_mode, working_client_order_id, working_iceberg_qty, working_strategy_id, working_strategy_type, working_time_in_force)
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

[**models::SpotCreateOrderListOtoV3Resp**](SpotCreateOrderListOtoV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_create_order_list_otoco_v3

> models::SpotCreateOrderListOtocoV3Resp spot_create_order_list_otoco_v3(pending_above_type, pending_quantity, pending_side, symbol, timestamp, working_price, working_quantity, working_side, working_type, list_client_order_id, new_order_resp_type, pending_above_client_order_id, pending_above_iceberg_qty, pending_above_price, pending_above_stop_price, pending_above_strategy_id, pending_above_strategy_type, pending_above_time_in_force, pending_above_trailing_delta, pending_below_client_order_id, pending_below_iceberg_qty, pending_below_price, pending_below_stop_price, pending_below_strategy_id, pending_below_strategy_type, pending_below_time_in_force, pending_below_trailing_delta, pending_below_type, recv_window, self_trade_prevention_mode, working_client_order_id, working_iceberg_qty, working_strategy_id, working_strategy_type, working_time_in_force)
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

[**models::SpotCreateOrderListOtocoV3Resp**](SpotCreateOrderListOtocoV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_create_order_oco_v3

> models::SpotCreateOrderOcoV3Resp spot_create_order_oco_v3(price, quantity, side, stop_price, symbol, timestamp, limit_client_order_id, limit_iceberg_qty, limit_strategy_id, limit_strategy_type, list_client_order_id, new_order_resp_type, recv_window, self_trade_prevention_mode, stop_client_order_id, stop_iceberg_qty, stop_limit_price, stop_limit_time_in_force, stop_strategy_id, stop_strategy_type, trailing_delta)
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

[**models::SpotCreateOrderOcoV3Resp**](SpotCreateOrderOcoV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_create_order_test_v3

> models::SpotCreateOrderTestV3Resp spot_create_order_test_v3(side, symbol, timestamp, r#type, compute_commission_rates, iceberg_qty, new_client_order_id, new_order_resp_type, price, quantity, quote_order_qty, recv_window, self_trade_prevention_mode, stop_price, strategy_id, strategy_type, time_in_force, trailing_delta)
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


## spot_create_order_v3

> models::SpotCreateOrderV3Resp spot_create_order_v3(side, symbol, timestamp, r#type, iceberg_qty, new_client_order_id, new_order_resp_type, price, quantity, quote_order_qty, recv_window, self_trade_prevention_mode, stop_price, strategy_id, strategy_type, time_in_force, trailing_delta)
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


## spot_create_sor_order_test_v3

> models::SpotCreateSorOrderTestV3Resp spot_create_sor_order_test_v3(quantity, side, symbol, timestamp, r#type, compute_commission_rates, iceberg_qty, new_client_order_id, new_order_resp_type, price, recv_window, self_trade_prevention_mode, strategy_id, strategy_type, time_in_force)
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


## spot_create_sor_order_v3

> models::SpotCreateSorOrderV3Resp spot_create_sor_order_v3(quantity, side, symbol, timestamp, r#type, iceberg_qty, new_client_order_id, new_order_resp_type, price, recv_window, self_trade_prevention_mode, strategy_id, strategy_type, time_in_force)
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

[**models::SpotCreateSorOrderV3Resp**](SpotCreateSorOrderV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_delete_open_orders_v3

> Vec<Vec<models::SpotDeleteOpenOrdersV3RespInner>> spot_delete_open_orders_v3(symbol, timestamp, recv_window)
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


## spot_delete_order_list_v3

> models::SpotDeleteOrderListV3Resp spot_delete_order_list_v3(symbol, timestamp, order_list_id, list_client_order_id, new_client_order_id, recv_window)
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

[**models::SpotDeleteOrderListV3Resp**](SpotDeleteOrderListV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_delete_order_v3

> models::SpotDeleteOrderV3Resp spot_delete_order_v3(symbol, timestamp, order_id, orig_client_order_id, new_client_order_id, cancel_restrictions, recv_window)
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

[**models::SpotDeleteOrderV3Resp**](SpotDeleteOrderV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_all_order_list_v3

> Vec<models::SpotGetAllOrderListV3RespItem> spot_get_all_order_list_v3(timestamp, from_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::SpotGetAllOrderListV3RespItem>**](SpotGetAllOrderListV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_all_orders_v3

> Vec<models::SpotGetAllOrdersV3RespItem> spot_get_all_orders_v3(symbol, timestamp, order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::SpotGetAllOrdersV3RespItem>**](SpotGetAllOrdersV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_open_order_list_v3

> Vec<models::SpotGetOpenOrderListV3RespItem> spot_get_open_order_list_v3(timestamp, recv_window)
Query Open Order lists (USER_DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::SpotGetOpenOrderListV3RespItem>**](SpotGetOpenOrderListV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_open_orders_v3

> Vec<models::SpotGetOpenOrdersV3RespItem> spot_get_open_orders_v3(timestamp, symbol, recv_window)
Current open orders (USER_DATA)

Get all open orders on a symbol. Careful when accessing this with no symbol. Weight: 6 for a single symbol; 80 when the symbol parameter is omitted

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::SpotGetOpenOrdersV3RespItem>**](SpotGetOpenOrdersV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_order_list_v3

> models::SpotGetOrderListV3Resp spot_get_order_list_v3(timestamp, order_list_id, orig_client_order_id, recv_window)
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

[**models::SpotGetOrderListV3Resp**](SpotGetOrderListV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_order_v3

> models::SpotGetOrderV3Resp spot_get_order_v3(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::SpotGetOrderV3Resp**](SpotGetOrderV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

