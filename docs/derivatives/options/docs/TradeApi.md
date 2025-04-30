# \TradeApi

All URIs are relative to *https://eapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**options_create_batch_orders_v1**](TradeApi.md#options_create_batch_orders_v1) | **POST** /eapi/v1/batchOrders | Place Multiple Orders(TRADE)
[**options_create_order_v1**](TradeApi.md#options_create_order_v1) | **POST** /eapi/v1/order | New Order (TRADE)
[**options_delete_all_open_orders_by_underlying_v1**](TradeApi.md#options_delete_all_open_orders_by_underlying_v1) | **DELETE** /eapi/v1/allOpenOrdersByUnderlying | Cancel All Option Orders By Underlying (TRADE)
[**options_delete_all_open_orders_v1**](TradeApi.md#options_delete_all_open_orders_v1) | **DELETE** /eapi/v1/allOpenOrders | Cancel all Option orders on specific symbol (TRADE)
[**options_delete_batch_orders_v1**](TradeApi.md#options_delete_batch_orders_v1) | **DELETE** /eapi/v1/batchOrders | Cancel Multiple Option Orders (TRADE)
[**options_delete_order_v1**](TradeApi.md#options_delete_order_v1) | **DELETE** /eapi/v1/order | Cancel Option Order (TRADE)
[**options_get_exercise_record_v1**](TradeApi.md#options_get_exercise_record_v1) | **GET** /eapi/v1/exerciseRecord | User Exercise Record (USER_DATA)
[**options_get_history_orders_v1**](TradeApi.md#options_get_history_orders_v1) | **GET** /eapi/v1/historyOrders | Query Option Order History (TRADE)
[**options_get_open_orders_v1**](TradeApi.md#options_get_open_orders_v1) | **GET** /eapi/v1/openOrders | Query Current Open Option Orders (USER_DATA)
[**options_get_order_v1**](TradeApi.md#options_get_order_v1) | **GET** /eapi/v1/order | Query Single Order (TRADE)
[**options_get_position_v1**](TradeApi.md#options_get_position_v1) | **GET** /eapi/v1/position | Option Position Information (USER_DATA)
[**options_get_user_trades_v1**](TradeApi.md#options_get_user_trades_v1) | **GET** /eapi/v1/userTrades | Account Trade List (USER_DATA)



## options_create_batch_orders_v1

> Vec<models::OptionsCreateBatchOrdersV1RespInner> options_create_batch_orders_v1(orders, timestamp, recv_window)
Place Multiple Orders(TRADE)

Send multiple option orders.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**orders** | [**Vec<models::OptionsCreateBatchOrdersV1ReqOrdersItem>**](models::OptionsCreateBatchOrdersV1ReqOrdersItem.md) |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::OptionsCreateBatchOrdersV1RespInner>**](OptionsCreateBatchOrdersV1Resp_inner.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_create_order_v1

> models::OptionsCreateOrderV1Resp options_create_order_v1(quantity, side, symbol, timestamp, r#type, client_order_id, is_mmp, new_order_resp_type, post_only, price, recv_window, reduce_only, time_in_force)
New Order (TRADE)

Send a new order.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**quantity** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**client_order_id** | Option<**String**> |  |  |[default to ]
**is_mmp** | Option<**bool**> |  |  |
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**post_only** | Option<**bool**> |  |  |[default to false]
**price** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**reduce_only** | Option<**bool**> |  |  |[default to false]
**time_in_force** | Option<**String**> |  |  |[default to ]

### Return type

[**models::OptionsCreateOrderV1Resp**](OptionsCreateOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_delete_all_open_orders_by_underlying_v1

> models::OptionsDeleteAllOpenOrdersByUnderlyingV1Resp options_delete_all_open_orders_by_underlying_v1(underlying, timestamp, recv_window)
Cancel All Option Orders By Underlying (TRADE)

Cancel all active orders on specified underlying.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**underlying** | **String** | Option underlying, e.g BTCUSDT | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::OptionsDeleteAllOpenOrdersByUnderlyingV1Resp**](OptionsDeleteAllOpenOrdersByUnderlyingV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_delete_all_open_orders_v1

> models::OptionsDeleteAllOpenOrdersV1Resp options_delete_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel all Option orders on specific symbol (TRADE)

Cancel all active order on a symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair, e.g BTC-200730-9000-C | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::OptionsDeleteAllOpenOrdersV1Resp**](OptionsDeleteAllOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_delete_batch_orders_v1

> Vec<models::OptionsDeleteBatchOrdersV1RespInner> options_delete_batch_orders_v1(symbol, timestamp, order_ids, client_order_ids, recv_window)
Cancel Multiple Option Orders (TRADE)

Cancel multiple orders.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair, e.g BTC-200730-9000-C | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_ids** | Option<[**Vec<i64>**](i64.md)> | Order ID, e.g [4611875134427365377,4611875134427365378] |  |
**client_order_ids** | Option<[**Vec<String>**](String.md)> | User-defined order ID, e.g [&#34;my_id_1&#34;,&#34;my_id_2&#34;] |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::OptionsDeleteBatchOrdersV1RespInner>**](OptionsDeleteBatchOrdersV1Resp_inner.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_delete_order_v1

> models::OptionsDeleteOrderV1Resp options_delete_order_v1(symbol, timestamp, order_id, client_order_id, recv_window)
Cancel Option Order (TRADE)

Cancel an active order.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair, e.g BTC-200730-9000-C | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> | Order ID, e.g 4611875134427365377 |  |
**client_order_id** | Option<**String**> | User-defined order ID, e.g 10000 |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::OptionsDeleteOrderV1Resp**](OptionsDeleteOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_exercise_record_v1

> Vec<models::OptionsGetExerciseRecordV1RespItem> options_get_exercise_record_v1(timestamp, symbol, start_time, end_time, limit, recv_window)
User Exercise Record (USER_DATA)

Get account exercise records.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> | Option trading pair, e.g BTC-200730-9000-C |  |[default to ]
**start_time** | Option<**i64**> | startTime |  |
**end_time** | Option<**i64**> | endTime |  |
**limit** | Option<**i32**> | default 1000, max 1000 |  |[default to 1000]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::OptionsGetExerciseRecordV1RespItem>**](OptionsGetExerciseRecordV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_history_orders_v1

> Vec<models::OptionsGetHistoryOrdersV1RespItem> options_get_history_orders_v1(symbol, timestamp, order_id, start_time, end_time, limit, recv_window)
Query Option Order History (TRADE)

Query all finished orders within 5 days, finished status: CANCELLED FILLED REJECTED.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> | Returns the orderId and subsequent orders, the most recent order is returned by default |  |
**start_time** | Option<**i64**> | Start Time, e.g 1593511200000 |  |
**end_time** | Option<**i64**> | End Time, e.g 1593512200000 |  |
**limit** | Option<**i32**> | Number of result sets returned Default:100 Max:1000 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::OptionsGetHistoryOrdersV1RespItem>**](OptionsGetHistoryOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_open_orders_v1

> Vec<models::OptionsGetOpenOrdersV1RespItem> options_get_open_orders_v1(timestamp, symbol, order_id, start_time, end_time, limit, recv_window)
Query Current Open Option Orders (USER_DATA)

Query current all open orders, status: ACCEPTED PARTIALLY_FILLED

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> | return all orders if don&#39;t pass, Option trading pair, e.g BTC-200730-9000-C, |  |[default to ]
**order_id** | Option<**i64**> | Returns the orderId and subsequent orders, the most recent order is returned by default |  |
**start_time** | Option<**i64**> | Start Time |  |
**end_time** | Option<**i64**> | End Time |  |
**limit** | Option<**i32**> | Number of result sets returned Default:100 Max:1000 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::OptionsGetOpenOrdersV1RespItem>**](OptionsGetOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_order_v1

> models::OptionsGetOrderV1Resp options_get_order_v1(symbol, timestamp, order_id, client_order_id, recv_window)
Query Single Order (TRADE)

Check an order status.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair, e.g BTC-200730-9000-C | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> | Order id |  |
**client_order_id** | Option<**String**> | User-defined order ID cannot be repeated in pending orders |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::OptionsGetOrderV1Resp**](OptionsGetOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_position_v1

> Vec<models::OptionsGetPositionV1RespItem> options_get_position_v1(timestamp, symbol, recv_window)
Option Position Information (USER_DATA)

Get current position information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> | Option trading pair, e.g BTC-200730-9000-C |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::OptionsGetPositionV1RespItem>**](OptionsGetPositionV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_user_trades_v1

> Vec<models::OptionsGetUserTradesV1RespItem> options_get_user_trades_v1(timestamp, symbol, from_id, start_time, end_time, limit, recv_window)
Account Trade List (USER_DATA)

Get trades for a specific account and symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> | Option symbol, e.g BTC-200730-9000-C |  |[default to ]
**from_id** | Option<**i64**> | Trade id to fetch from. Default gets most recent trades, e.g 4611875134427365376 |  |
**start_time** | Option<**i64**> | Start time, e.g 1593511200000 |  |
**end_time** | Option<**i64**> | End time, e.g 1593512200000 |  |
**limit** | Option<**i32**> | Default 100; max 1000 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::OptionsGetUserTradesV1RespItem>**](OptionsGetUserTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

