# \TradeApi

All URIs are relative to *https://dapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**cmfutures_create_batch_orders_v1**](TradeApi.md#cmfutures_create_batch_orders_v1) | **POST** /dapi/v1/batchOrders | Place Multiple Orders(TRADE)
[**cmfutures_create_countdown_cancel_all_v1**](TradeApi.md#cmfutures_create_countdown_cancel_all_v1) | **POST** /dapi/v1/countdownCancelAll | Auto-Cancel All Open Orders (TRADE)
[**cmfutures_create_leverage_v1**](TradeApi.md#cmfutures_create_leverage_v1) | **POST** /dapi/v1/leverage | Change Initial Leverage (TRADE)
[**cmfutures_create_margin_type_v1**](TradeApi.md#cmfutures_create_margin_type_v1) | **POST** /dapi/v1/marginType | Change Margin Type (TRADE)
[**cmfutures_create_order_v1**](TradeApi.md#cmfutures_create_order_v1) | **POST** /dapi/v1/order | New Order (TRADE)
[**cmfutures_create_position_margin_v1**](TradeApi.md#cmfutures_create_position_margin_v1) | **POST** /dapi/v1/positionMargin | Modify Isolated Position Margin(TRADE)
[**cmfutures_create_position_side_dual_v1**](TradeApi.md#cmfutures_create_position_side_dual_v1) | **POST** /dapi/v1/positionSide/dual | Change Position Mode(TRADE)
[**cmfutures_delete_all_open_orders_v1**](TradeApi.md#cmfutures_delete_all_open_orders_v1) | **DELETE** /dapi/v1/allOpenOrders | Cancel All Open Orders(TRADE)
[**cmfutures_delete_batch_orders_v1**](TradeApi.md#cmfutures_delete_batch_orders_v1) | **DELETE** /dapi/v1/batchOrders | Cancel Multiple Orders(TRADE)
[**cmfutures_delete_order_v1**](TradeApi.md#cmfutures_delete_order_v1) | **DELETE** /dapi/v1/order | Cancel Order (TRADE)
[**cmfutures_get_adl_quantile_v1**](TradeApi.md#cmfutures_get_adl_quantile_v1) | **GET** /dapi/v1/adlQuantile | Position ADL Quantile Estimation(USER_DATA)
[**cmfutures_get_all_orders_v1**](TradeApi.md#cmfutures_get_all_orders_v1) | **GET** /dapi/v1/allOrders | All Orders (USER_DATA)
[**cmfutures_get_force_orders_v1**](TradeApi.md#cmfutures_get_force_orders_v1) | **GET** /dapi/v1/forceOrders | User's Force Orders(USER_DATA)
[**cmfutures_get_open_order_v1**](TradeApi.md#cmfutures_get_open_order_v1) | **GET** /dapi/v1/openOrder | Query Current Open Order(USER_DATA)
[**cmfutures_get_open_orders_v1**](TradeApi.md#cmfutures_get_open_orders_v1) | **GET** /dapi/v1/openOrders | Current All Open Orders (USER_DATA)
[**cmfutures_get_order_amendment_v1**](TradeApi.md#cmfutures_get_order_amendment_v1) | **GET** /dapi/v1/orderAmendment | Get Order Modify History (USER_DATA)
[**cmfutures_get_order_v1**](TradeApi.md#cmfutures_get_order_v1) | **GET** /dapi/v1/order | Query Order (USER_DATA)
[**cmfutures_get_position_margin_history_v1**](TradeApi.md#cmfutures_get_position_margin_history_v1) | **GET** /dapi/v1/positionMargin/history | Get Position Margin Change History(TRADE)
[**cmfutures_get_position_risk_v1**](TradeApi.md#cmfutures_get_position_risk_v1) | **GET** /dapi/v1/positionRisk | Position Information(USER_DATA)
[**cmfutures_get_user_trades_v1**](TradeApi.md#cmfutures_get_user_trades_v1) | **GET** /dapi/v1/userTrades | Account Trade List (USER_DATA)
[**cmfutures_update_batch_orders_v1**](TradeApi.md#cmfutures_update_batch_orders_v1) | **PUT** /dapi/v1/batchOrders | Modify Multiple Orders(TRADE)
[**cmfutures_update_order_v1**](TradeApi.md#cmfutures_update_order_v1) | **PUT** /dapi/v1/order | Modify Order (TRADE)



## cmfutures_create_batch_orders_v1

> Vec<models::CmfuturesCreateBatchOrdersV1RespInner> cmfutures_create_batch_orders_v1(batch_orders, timestamp, recv_window)
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


## cmfutures_create_countdown_cancel_all_v1

> models::CmfuturesCreateCountdownCancelAllV1Resp cmfutures_create_countdown_cancel_all_v1(countdown_time, symbol, timestamp, recv_window)
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

[**models::CmfuturesCreateCountdownCancelAllV1Resp**](CmfuturesCreateCountdownCancelAllV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_create_leverage_v1

> models::CmfuturesCreateLeverageV1Resp cmfutures_create_leverage_v1(leverage, symbol, timestamp, recv_window)
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

[**models::CmfuturesCreateLeverageV1Resp**](CmfuturesCreateLeverageV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_create_margin_type_v1

> models::CmfuturesCreateMarginTypeV1Resp cmfutures_create_margin_type_v1(margin_type, symbol, timestamp, recv_window)
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

[**models::CmfuturesCreateMarginTypeV1Resp**](CmfuturesCreateMarginTypeV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_create_order_v1

> models::CmfuturesCreateOrderV1Resp cmfutures_create_order_v1(side, symbol, timestamp, r#type, activation_price, callback_rate, close_position, new_client_order_id, new_order_resp_type, position_side, price, price_match, price_protect, quantity, recv_window, reduce_only, self_trade_prevention_mode, stop_price, time_in_force, working_type)
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

[**models::CmfuturesCreateOrderV1Resp**](CmfuturesCreateOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_create_position_margin_v1

> models::CmfuturesCreatePositionMarginV1Resp cmfutures_create_position_margin_v1(amount, symbol, timestamp, r#type, position_side, recv_window)
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

[**models::CmfuturesCreatePositionMarginV1Resp**](CmfuturesCreatePositionMarginV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_create_position_side_dual_v1

> models::CmfuturesCreatePositionSideDualV1Resp cmfutures_create_position_side_dual_v1(dual_side_position, timestamp, recv_window)
Change Position Mode(TRADE)

Change user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**dual_side_position** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CmfuturesCreatePositionSideDualV1Resp**](CmfuturesCreatePositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_delete_all_open_orders_v1

> models::CmfuturesDeleteAllOpenOrdersV1Resp cmfutures_delete_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel All Open Orders(TRADE)

Cancel All Open Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CmfuturesDeleteAllOpenOrdersV1Resp**](CmfuturesDeleteAllOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_delete_batch_orders_v1

> Vec<models::CmfuturesDeleteBatchOrdersV1RespInner> cmfutures_delete_batch_orders_v1(symbol, timestamp, order_id_list, orig_client_order_id_list, recv_window)
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


## cmfutures_delete_order_v1

> models::CmfuturesDeleteOrderV1Resp cmfutures_delete_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::CmfuturesDeleteOrderV1Resp**](CmfuturesDeleteOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_adl_quantile_v1

> Vec<models::CmfuturesGetAdlQuantileV1RespItem> cmfutures_get_adl_quantile_v1(timestamp, symbol, recv_window)
Position ADL Quantile Estimation(USER_DATA)

Query position ADL quantile estimation

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesGetAdlQuantileV1RespItem>**](CmfuturesGetAdlQuantileV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_all_orders_v1

> Vec<models::CmfuturesGetAllOrdersV1RespItem> cmfutures_get_all_orders_v1(timestamp, symbol, pair, order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::CmfuturesGetAllOrdersV1RespItem>**](CmfuturesGetAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_force_orders_v1

> Vec<models::CmfuturesGetForceOrdersV1RespItem> cmfutures_get_force_orders_v1(timestamp, symbol, auto_close_type, recv_window, limit, start_time, end_time)
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


## cmfutures_get_open_order_v1

> models::CmfuturesGetOpenOrderV1Resp cmfutures_get_open_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::CmfuturesGetOpenOrderV1Resp**](CmfuturesGetOpenOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_open_orders_v1

> Vec<models::CmfuturesGetOpenOrdersV1RespItem> cmfutures_get_open_orders_v1(timestamp, symbol, pair, recv_window)
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

[**Vec<models::CmfuturesGetOpenOrdersV1RespItem>**](CmfuturesGetOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_order_amendment_v1

> Vec<models::CmfuturesGetOrderAmendmentV1RespItem> cmfutures_get_order_amendment_v1(symbol, timestamp, order_id, orig_client_order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::CmfuturesGetOrderAmendmentV1RespItem>**](CmfuturesGetOrderAmendmentV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_order_v1

> models::CmfuturesGetOrderV1Resp cmfutures_get_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::CmfuturesGetOrderV1Resp**](CmfuturesGetOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_position_margin_history_v1

> Vec<models::CmfuturesGetPositionMarginHistoryV1RespItem> cmfutures_get_position_margin_history_v1(symbol, timestamp, r#type, start_time, end_time, limit, recv_window)
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

[**Vec<models::CmfuturesGetPositionMarginHistoryV1RespItem>**](CmfuturesGetPositionMarginHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_position_risk_v1

> Vec<models::CmfuturesGetPositionRiskV1RespItem> cmfutures_get_position_risk_v1(timestamp, margin_asset, pair, recv_window)
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

[**Vec<models::CmfuturesGetPositionRiskV1RespItem>**](CmfuturesGetPositionRiskV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_user_trades_v1

> Vec<models::CmfuturesGetUserTradesV1RespItem> cmfutures_get_user_trades_v1(timestamp, symbol, pair, order_id, start_time, end_time, from_id, limit, recv_window)
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

[**Vec<models::CmfuturesGetUserTradesV1RespItem>**](CmfuturesGetUserTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_update_batch_orders_v1

> Vec<models::CmfuturesUpdateBatchOrdersV1RespInner> cmfutures_update_batch_orders_v1(batch_orders, timestamp, recv_window)
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


## cmfutures_update_order_v1

> models::CmfuturesUpdateOrderV1Resp cmfutures_update_order_v1(side, symbol, timestamp, order_id, orig_client_order_id, price, price_match, quantity, recv_window)
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

[**models::CmfuturesUpdateOrderV1Resp**](CmfuturesUpdateOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

