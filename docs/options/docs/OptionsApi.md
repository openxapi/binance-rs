# \OptionsApi

All URIs are relative to *https://eapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_batch_orders_v1**](OptionsApi.md#create_batch_orders_v1) | **POST** /eapi/v1/batchOrders | Place Multiple Orders(TRADE)
[**create_block_order_execute_v1**](OptionsApi.md#create_block_order_execute_v1) | **POST** /eapi/v1/block/order/execute | Accept Block Trade Order (TRADE)
[**create_countdown_cancel_all_heart_beat_v1**](OptionsApi.md#create_countdown_cancel_all_heart_beat_v1) | **POST** /eapi/v1/countdownCancelAllHeartBeat | Auto-Cancel All Open Orders (Kill-Switch) Heartbeat (TRADE)
[**create_countdown_cancel_all_v1**](OptionsApi.md#create_countdown_cancel_all_v1) | **POST** /eapi/v1/countdownCancelAll | Set Auto-Cancel All Open Orders (Kill-Switch) Config (TRADE)
[**create_listen_key_v1**](OptionsApi.md#create_listen_key_v1) | **POST** /eapi/v1/listenKey | Start User Data Stream (USER_STREAM)
[**create_mmp_reset_v1**](OptionsApi.md#create_mmp_reset_v1) | **POST** /eapi/v1/mmpReset | Reset Market Maker Protection Config (TRADE)
[**create_mmp_set_v1**](OptionsApi.md#create_mmp_set_v1) | **POST** /eapi/v1/mmpSet | Set Market Maker Protection Config (TRADE)
[**create_order_v1**](OptionsApi.md#create_order_v1) | **POST** /eapi/v1/order | New Order (TRADE)
[**delete_all_open_orders_by_underlying_v1**](OptionsApi.md#delete_all_open_orders_by_underlying_v1) | **DELETE** /eapi/v1/allOpenOrdersByUnderlying | Cancel All Option Orders By Underlying (TRADE)
[**delete_all_open_orders_v1**](OptionsApi.md#delete_all_open_orders_v1) | **DELETE** /eapi/v1/allOpenOrders | Cancel all Option orders on specific symbol (TRADE)
[**delete_batch_orders_v1**](OptionsApi.md#delete_batch_orders_v1) | **DELETE** /eapi/v1/batchOrders | Cancel Multiple Option Orders (TRADE)
[**delete_listen_key_v1**](OptionsApi.md#delete_listen_key_v1) | **DELETE** /eapi/v1/listenKey | Close User Data Stream (USER_STREAM)
[**delete_order_v1**](OptionsApi.md#delete_order_v1) | **DELETE** /eapi/v1/order | Cancel Option Order (TRADE)
[**get_account_v1**](OptionsApi.md#get_account_v1) | **GET** /eapi/v1/account | Option Account Information(TRADE)
[**get_bill_v1**](OptionsApi.md#get_bill_v1) | **GET** /eapi/v1/bill | Account Funding Flow (USER_DATA)
[**get_block_order_execute_v1**](OptionsApi.md#get_block_order_execute_v1) | **GET** /eapi/v1/block/order/execute | Query Block Trade Details (USER_DATA)
[**get_block_order_orders_v1**](OptionsApi.md#get_block_order_orders_v1) | **GET** /eapi/v1/block/order/orders | Query Block Trade Order (TRADE)
[**get_block_trades_v1**](OptionsApi.md#get_block_trades_v1) | **GET** /eapi/v1/blockTrades | Recent Block Trades List
[**get_block_user_trades_v1**](OptionsApi.md#get_block_user_trades_v1) | **GET** /eapi/v1/block/user-trades | Account Block Trade List (USER_DATA)
[**get_countdown_cancel_all_v1**](OptionsApi.md#get_countdown_cancel_all_v1) | **GET** /eapi/v1/countdownCancelAll | Get Auto-Cancel All Open Orders (Kill-Switch) Config (TRADE)
[**get_depth_v1**](OptionsApi.md#get_depth_v1) | **GET** /eapi/v1/depth | Order Book
[**get_exchange_info_v1**](OptionsApi.md#get_exchange_info_v1) | **GET** /eapi/v1/exchangeInfo | Exchange Information
[**get_exercise_history_v1**](OptionsApi.md#get_exercise_history_v1) | **GET** /eapi/v1/exerciseHistory | Historical Exercise Records
[**get_exercise_record_v1**](OptionsApi.md#get_exercise_record_v1) | **GET** /eapi/v1/exerciseRecord | User Exercise Record (USER_DATA)
[**get_historical_trades_v1**](OptionsApi.md#get_historical_trades_v1) | **GET** /eapi/v1/historicalTrades | Old Trades Lookup (MARKET_DATA)
[**get_history_orders_v1**](OptionsApi.md#get_history_orders_v1) | **GET** /eapi/v1/historyOrders | Query Option Order History (TRADE)
[**get_income_asyn_id_v1**](OptionsApi.md#get_income_asyn_id_v1) | **GET** /eapi/v1/income/asyn/id | Get Option Transaction History Download Link by Id (USER_DATA)
[**get_income_asyn_v1**](OptionsApi.md#get_income_asyn_v1) | **GET** /eapi/v1/income/asyn | Get Download Id For Option Transaction History (USER_DATA)
[**get_index_v1**](OptionsApi.md#get_index_v1) | **GET** /eapi/v1/index | Symbol Price Ticker
[**get_klines_v1**](OptionsApi.md#get_klines_v1) | **GET** /eapi/v1/klines | Kline/Candlestick Data
[**get_margin_account_v1**](OptionsApi.md#get_margin_account_v1) | **GET** /eapi/v1/marginAccount | Option Margin Account Information (USER_DATA)
[**get_mark_v1**](OptionsApi.md#get_mark_v1) | **GET** /eapi/v1/mark | Option Mark Price
[**get_mmp_v1**](OptionsApi.md#get_mmp_v1) | **GET** /eapi/v1/mmp | Get Market Maker Protection Config (TRADE)
[**get_open_interest_v1**](OptionsApi.md#get_open_interest_v1) | **GET** /eapi/v1/openInterest | Open Interest
[**get_open_orders_v1**](OptionsApi.md#get_open_orders_v1) | **GET** /eapi/v1/openOrders | Query Current Open Option Orders (USER_DATA)
[**get_order_v1**](OptionsApi.md#get_order_v1) | **GET** /eapi/v1/order | Query Single Order (TRADE)
[**get_ping_v1**](OptionsApi.md#get_ping_v1) | **GET** /eapi/v1/ping | Test Connectivity
[**get_position_v1**](OptionsApi.md#get_position_v1) | **GET** /eapi/v1/position | Option Position Information (USER_DATA)
[**get_ticker_v1**](OptionsApi.md#get_ticker_v1) | **GET** /eapi/v1/ticker | 24hr Ticker Price Change Statistics
[**get_time_v1**](OptionsApi.md#get_time_v1) | **GET** /eapi/v1/time | Check Server Time
[**get_trades_v1**](OptionsApi.md#get_trades_v1) | **GET** /eapi/v1/trades | Recent Trades List
[**get_user_trades_v1**](OptionsApi.md#get_user_trades_v1) | **GET** /eapi/v1/userTrades | Account Trade List (USER_DATA)
[**update_block_order_create_v1**](OptionsApi.md#update_block_order_create_v1) | **PUT** /eapi/v1/block/order/create | Extend Block Trade Order (TRADE)
[**update_listen_key_v1**](OptionsApi.md#update_listen_key_v1) | **PUT** /eapi/v1/listenKey | Keepalive User Data Stream (USER_STREAM)



## create_batch_orders_v1

> Vec<models::OptionsCreateBatchOrdersV1RespInner> create_batch_orders_v1(orders, timestamp, recv_window)
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


## create_block_order_execute_v1

> models::CreateBlockOrderExecuteV1Resp create_block_order_execute_v1(block_order_matching_key, timestamp, recv_window)
Accept Block Trade Order (TRADE)

Accept a block trade order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**block_order_matching_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateBlockOrderExecuteV1Resp**](CreateBlockOrderExecuteV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_countdown_cancel_all_heart_beat_v1

> models::CreateCountdownCancelAllHeartBeatV1Resp create_countdown_cancel_all_heart_beat_v1(timestamp, underlyings, recv_window)
Auto-Cancel All Open Orders (Kill-Switch) Heartbeat (TRADE)

This endpoint resets the time from which the countdown will begin to the time this messaged is received.  It should be called repeatedly as heartbeats.  Multiple heartbeats can be updated at once by specifying the underlying symbols as a list (ex. BTCUSDT,ETHUSDT) in the underlyings parameter.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**underlyings** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateCountdownCancelAllHeartBeatV1Resp**](CreateCountdownCancelAllHeartBeatV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_countdown_cancel_all_v1

> models::CreateCountdownCancelAllV1Resp create_countdown_cancel_all_v1(countdown_time, timestamp, underlying, recv_window)
Set Auto-Cancel All Open Orders (Kill-Switch) Config (TRADE)

This endpoint sets the parameters of the auto-cancel feature which cancels all open orders (both market maker protection and non market maker protection order types) of the underlying symbol at the end of the specified countdown time period if no heartbeat message is sent.  After the countdown time period, all open orders will be cancelled and new orders will be rejected with error code -2010 until either a heartbeat message is sent or the auto-cancel feature is turned off by setting countdownTime to 0.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**countdown_time** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**underlying** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateCountdownCancelAllV1Resp**](CreateCountdownCancelAllV1Resp.md)

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


## create_mmp_reset_v1

> models::CreateMmpResetV1Resp create_mmp_reset_v1(timestamp, recv_window, underlying)
Reset Market Maker Protection Config (TRADE)

Reset MMP, start MMP order again.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |
**underlying** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateMmpResetV1Resp**](CreateMmpResetV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_mmp_set_v1

> models::CreateMmpSetV1Resp create_mmp_set_v1(timestamp, delta_limit, frozen_time_in_milliseconds, qty_limit, recv_window, underlying, window_time_in_milliseconds)
Set Market Maker Protection Config (TRADE)

Set config for MMP. Market Maker Protection(MMP) is a set of protection mechanism for option market maker, this mechanism is able to prevent mass trading in short period time. Once market maker's account branches the threshold, the Market Maker Protection will be triggered. When Market Maker Protection triggers, all the current MMP orders will be canceled, new MMP orders will be rejected. Market maker can use this time to reevaluate market and modify order price.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**delta_limit** | Option<**String**> |  |  |[default to ]
**frozen_time_in_milliseconds** | Option<**i64**> |  |  |
**qty_limit** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**underlying** | Option<**String**> |  |  |[default to ]
**window_time_in_milliseconds** | Option<**i64**> |  |  |

### Return type

[**models::CreateMmpSetV1Resp**](CreateMmpSetV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_order_v1

> models::OptionsCreateOrderV1Resp create_order_v1(quantity, side, symbol, timestamp, r#type, client_order_id, is_mmp, new_order_resp_type, post_only, price, recv_window, reduce_only, time_in_force)
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


## delete_all_open_orders_by_underlying_v1

> models::DeleteAllOpenOrdersByUnderlyingV1Resp delete_all_open_orders_by_underlying_v1(underlying, timestamp, recv_window)
Cancel All Option Orders By Underlying (TRADE)

Cancel all active orders on specified underlying.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**underlying** | **String** | Option underlying, e.g BTCUSDT | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::DeleteAllOpenOrdersByUnderlyingV1Resp**](DeleteAllOpenOrdersByUnderlyingV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_all_open_orders_v1

> models::DeleteAllOpenOrdersV1Resp delete_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel all Option orders on specific symbol (TRADE)

Cancel all active order on a symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair, e.g BTC-200730-9000-C | [required] |[default to ]
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

> Vec<models::OptionsDeleteBatchOrdersV1RespInner> delete_batch_orders_v1(symbol, timestamp, order_ids, client_order_ids, recv_window)
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

> models::DeleteOrderV1Resp delete_order_v1(symbol, timestamp, order_id, client_order_id, recv_window)
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

[**models::DeleteOrderV1Resp**](DeleteOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_account_v1

> models::GetAccountV1Resp get_account_v1(timestamp, recv_window)
Option Account Information(TRADE)

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


## get_bill_v1

> Vec<models::GetBillV1RespItem> get_bill_v1(currency, timestamp, record_id, start_time, end_time, limit, recv_window)
Account Funding Flow (USER_DATA)

Query account funding flows.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**currency** | **String** | Asset type, only support USDT  as of now | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**record_id** | Option<**i64**> | Return the recordId and subsequent data, the latest data is returned by default, e.g 100000 |  |
**start_time** | Option<**i64**> | Start Time, e.g 1593511200000 |  |
**end_time** | Option<**i64**> | End Time, e.g 1593512200000 |  |
**limit** | Option<**i32**> | Number of result sets returned Default:100 Max:1000 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBillV1RespItem>**](GetBillV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_block_order_execute_v1

> models::GetBlockOrderExecuteV1Resp get_block_order_execute_v1(block_order_matching_key, timestamp, recv_window)
Query Block Trade Details (USER_DATA)

Query block trade details; returns block trade details from counterparty's perspective.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**block_order_matching_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetBlockOrderExecuteV1Resp**](GetBlockOrderExecuteV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_block_order_orders_v1

> Vec<models::GetBlockOrderOrdersV1RespItem> get_block_order_orders_v1(timestamp, block_order_matching_key, end_time, start_time, underlying, recv_window)
Query Block Trade Order (TRADE)

Check block trade order status.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**block_order_matching_key** | Option<**String**> | If specified, returns the specific block trade associated with the blockOrderMatchingKey |  |[default to ]
**end_time** | Option<**i64**> |  |  |
**start_time** | Option<**i64**> |  |  |
**underlying** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::GetBlockOrderOrdersV1RespItem>**](GetBlockOrderOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_block_trades_v1

> Vec<models::GetBlockTradesV1RespItem> get_block_trades_v1(symbol, limit)
Recent Block Trades List

Get recent block trades

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> | Option trading pair, e.g. BTC-200730-9000-C |  |[default to ]
**limit** | Option<**i32**> | Number of records; Default: 100 and Max: 500 |  |[default to 100]

### Return type

[**Vec<models::GetBlockTradesV1RespItem>**](GetBlockTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_block_user_trades_v1

> Vec<models::GetBlockUserTradesV1RespItem> get_block_user_trades_v1(timestamp, end_time, start_time, underlying, recv_window)
Account Block Trade List (USER_DATA)

Gets block trades for a specific account.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**end_time** | Option<**i64**> |  |  |
**start_time** | Option<**i64**> |  |  |
**underlying** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::GetBlockUserTradesV1RespItem>**](GetBlockUserTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_countdown_cancel_all_v1

> models::GetCountdownCancelAllV1Resp get_countdown_cancel_all_v1(timestamp, underlying, recv_window)
Get Auto-Cancel All Open Orders (Kill-Switch) Config (TRADE)

This endpoint returns the auto-cancel parameters for each underlying symbol. Note only active auto-cancel parameters will be returned, if countdownTime is set to 0 (ie. countdownTime has been turned off), the underlying symbol and corresponding countdownTime parameter will not be returned in the response.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**underlying** | Option<**String**> | Option underlying, e.g BTCUSDT |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetCountdownCancelAllV1Resp**](GetCountdownCancelAllV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_depth_v1

> models::GetDepthV1Resp get_depth_v1(symbol, limit)
Order Book

Check orderbook depth on specific symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair, e.g BTC-200730-9000-C | [required] |[default to ]
**limit** | Option<**i32**> | Default:100 Max:1000.Optional value:[10, 20, 50, 100, 500, 1000] |  |

### Return type

[**models::GetDepthV1Resp**](GetDepthV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_exchange_info_v1

> models::OptionsGetExchangeInfoV1Resp get_exchange_info_v1()
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


## get_exercise_history_v1

> Vec<models::GetExerciseHistoryV1RespItem> get_exercise_history_v1(underlying, start_time, end_time, limit)
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

[**Vec<models::GetExerciseHistoryV1RespItem>**](GetExerciseHistoryV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_exercise_record_v1

> Vec<models::GetExerciseRecordV1RespItem> get_exercise_record_v1(timestamp, symbol, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetExerciseRecordV1RespItem>**](GetExerciseRecordV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_historical_trades_v1

> Vec<models::GetHistoricalTradesV1RespItem> get_historical_trades_v1(symbol, from_id, limit)
Old Trades Lookup (MARKET_DATA)

Get older market historical trades.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair, e.g BTC-200730-9000-C | [required] |[default to ]
**from_id** | Option<**i64**> | The UniqueId ID from which to return. The latest deal record is returned by default |  |
**limit** | Option<**i32**> | Number of records Default:100 Max:500 |  |

### Return type

[**Vec<models::GetHistoricalTradesV1RespItem>**](GetHistoricalTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_history_orders_v1

> Vec<models::GetHistoryOrdersV1RespItem> get_history_orders_v1(symbol, timestamp, order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetHistoryOrdersV1RespItem>**](GetHistoryOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_income_asyn_id_v1

> models::GetIncomeAsynIdV1Resp get_income_asyn_id_v1(download_id, timestamp, recv_window)
Get Option Transaction History Download Link by Id (USER_DATA)

Get option transaction history download Link by Id

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

> models::GetIncomeAsynV1Resp get_income_asyn_v1()
Get Download Id For Option Transaction History (USER_DATA)

Get download id for option transaction history

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::GetIncomeAsynV1Resp**](GetIncomeAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_index_v1

> models::GetIndexV1Resp get_index_v1(underlying)
Symbol Price Ticker

Get spot index price for option underlying.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**underlying** | **String** | Spot pair（Option contract underlying asset, e.g BTCUSDT) | [required] |[default to ]

### Return type

[**models::GetIndexV1Resp**](GetIndexV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_klines_v1

> Vec<models::GetKlinesV1RespItem> get_klines_v1(symbol, interval, start_time, end_time, limit)
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

[**Vec<models::GetKlinesV1RespItem>**](GetKlinesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_account_v1

> models::GetMarginAccountV1Resp get_margin_account_v1(timestamp, recv_window)
Option Margin Account Information (USER_DATA)

Get current account information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMarginAccountV1Resp**](GetMarginAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mark_v1

> Vec<models::GetMarkV1RespItem> get_mark_v1(symbol)
Option Mark Price

Option mark price and greek info.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> | Option trading pair, e.g BTC-200730-9000-C |  |[default to ]

### Return type

[**Vec<models::GetMarkV1RespItem>**](GetMarkV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mmp_v1

> models::GetMmpV1Resp get_mmp_v1(timestamp, underlying, recv_window)
Get Market Maker Protection Config (TRADE)

Get config for MMP.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**underlying** | Option<**String**> | underlying, e.g BTCUSDT |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMmpV1Resp**](GetMmpV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_open_interest_v1

> Vec<models::GetOpenInterestV1RespItem> get_open_interest_v1(underlying_asset, expiration)
Open Interest

Get open interest for specific underlying asset on specific expiration date.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**underlying_asset** | **String** | underlying asset, e.g ETH/BTC | [required] |[default to ]
**expiration** | **String** | expiration date, e.g 221225 | [required] |[default to ]

### Return type

[**Vec<models::GetOpenInterestV1RespItem>**](GetOpenInterestV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_open_orders_v1

> Vec<models::GetOpenOrdersV1RespItem> get_open_orders_v1(timestamp, symbol, order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetOpenOrdersV1RespItem>**](GetOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_order_v1

> models::GetOrderV1Resp get_order_v1(symbol, timestamp, order_id, client_order_id, recv_window)
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


## get_position_v1

> Vec<models::GetPositionV1RespItem> get_position_v1(timestamp, symbol, recv_window)
Option Position Information (USER_DATA)

Get current position information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> | Option trading pair, e.g BTC-200730-9000-C |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetPositionV1RespItem>**](GetPositionV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_ticker_v1

> Vec<models::GetTickerV1RespItem> get_ticker_v1(symbol)
24hr Ticker Price Change Statistics

24 hour rolling window price change statistics.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> | Option trading pair, e.g BTC-200730-9000-C |  |[default to ]

### Return type

[**Vec<models::GetTickerV1RespItem>**](GetTickerV1RespItem.md)

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


## get_trades_v1

> Vec<models::GetTradesV1RespItem> get_trades_v1(symbol, limit)
Recent Trades List

Get recent market trades

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** | Option trading pair, e.g BTC-200730-9000-C | [required] |[default to ]
**limit** | Option<**i32**> | Number of records Default:100 Max:500 |  |

### Return type

[**Vec<models::GetTradesV1RespItem>**](GetTradesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_user_trades_v1

> Vec<models::GetUserTradesV1RespItem> get_user_trades_v1(timestamp, symbol, from_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetUserTradesV1RespItem>**](GetUserTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_block_order_create_v1

> models::UpdateBlockOrderCreateV1Resp update_block_order_create_v1(block_order_matching_key, timestamp, recv_window)
Extend Block Trade Order (TRADE)

Extends a block trade expire time by 30 mins from the current time.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**block_order_matching_key** | **String** |  | [required] |[default to ]
**timestamp** | **i32** |  | [required] |
**recv_window** | Option<**i32**> |  |  |

### Return type

[**models::UpdateBlockOrderCreateV1Resp**](UpdateBlockOrderCreateV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_listen_key_v1

> serde_json::Value update_listen_key_v1()
Keepalive User Data Stream (USER_STREAM)

Keepalive a user data stream to prevent a time out. User data streams will close after 60 minutes. It's recommended to send a ping about every 60 minutes.

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

