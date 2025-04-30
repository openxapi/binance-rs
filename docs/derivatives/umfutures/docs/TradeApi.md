# \TradeApi

All URIs are relative to *https://fapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**umfutures_create_batch_orders_v1**](TradeApi.md#umfutures_create_batch_orders_v1) | **POST** /fapi/v1/batchOrders | Place Multiple Orders(TRADE)
[**umfutures_create_countdown_cancel_all_v1**](TradeApi.md#umfutures_create_countdown_cancel_all_v1) | **POST** /fapi/v1/countdownCancelAll | Auto-Cancel All Open Orders (TRADE)
[**umfutures_create_leverage_v1**](TradeApi.md#umfutures_create_leverage_v1) | **POST** /fapi/v1/leverage | Change Initial Leverage(TRADE)
[**umfutures_create_margin_type_v1**](TradeApi.md#umfutures_create_margin_type_v1) | **POST** /fapi/v1/marginType | Change Margin Type(TRADE)
[**umfutures_create_multi_assets_margin_v1**](TradeApi.md#umfutures_create_multi_assets_margin_v1) | **POST** /fapi/v1/multiAssetsMargin | Change Multi-Assets Mode (TRADE)
[**umfutures_create_order_test_v1**](TradeApi.md#umfutures_create_order_test_v1) | **POST** /fapi/v1/order/test | Test Order(TRADE)
[**umfutures_create_order_v1**](TradeApi.md#umfutures_create_order_v1) | **POST** /fapi/v1/order | New Order(TRADE)
[**umfutures_create_position_margin_v1**](TradeApi.md#umfutures_create_position_margin_v1) | **POST** /fapi/v1/positionMargin | Modify Isolated Position Margin(TRADE)
[**umfutures_create_position_side_dual_v1**](TradeApi.md#umfutures_create_position_side_dual_v1) | **POST** /fapi/v1/positionSide/dual | Change Position Mode(TRADE)
[**umfutures_delete_all_open_orders_v1**](TradeApi.md#umfutures_delete_all_open_orders_v1) | **DELETE** /fapi/v1/allOpenOrders | Cancel All Open Orders (TRADE)
[**umfutures_delete_batch_orders_v1**](TradeApi.md#umfutures_delete_batch_orders_v1) | **DELETE** /fapi/v1/batchOrders | Cancel Multiple Orders (TRADE)
[**umfutures_delete_order_v1**](TradeApi.md#umfutures_delete_order_v1) | **DELETE** /fapi/v1/order | Cancel Order (TRADE)
[**umfutures_get_adl_quantile_v1**](TradeApi.md#umfutures_get_adl_quantile_v1) | **GET** /fapi/v1/adlQuantile | Position ADL Quantile Estimation(USER_DATA)
[**umfutures_get_all_orders_v1**](TradeApi.md#umfutures_get_all_orders_v1) | **GET** /fapi/v1/allOrders | All Orders (USER_DATA)
[**umfutures_get_force_orders_v1**](TradeApi.md#umfutures_get_force_orders_v1) | **GET** /fapi/v1/forceOrders | User's Force Orders (USER_DATA)
[**umfutures_get_open_order_v1**](TradeApi.md#umfutures_get_open_order_v1) | **GET** /fapi/v1/openOrder | Query Current Open Order (USER_DATA)
[**umfutures_get_open_orders_v1**](TradeApi.md#umfutures_get_open_orders_v1) | **GET** /fapi/v1/openOrders | Current All Open Orders (USER_DATA)
[**umfutures_get_order_amendment_v1**](TradeApi.md#umfutures_get_order_amendment_v1) | **GET** /fapi/v1/orderAmendment | Get Order Modify History (USER_DATA)
[**umfutures_get_order_v1**](TradeApi.md#umfutures_get_order_v1) | **GET** /fapi/v1/order | Query Order (USER_DATA)
[**umfutures_get_position_margin_history_v1**](TradeApi.md#umfutures_get_position_margin_history_v1) | **GET** /fapi/v1/positionMargin/history | Get Position Margin Change History (TRADE)
[**umfutures_get_position_risk_v2**](TradeApi.md#umfutures_get_position_risk_v2) | **GET** /fapi/v2/positionRisk | Position Information V2 (USER_DATA)
[**umfutures_get_position_risk_v3**](TradeApi.md#umfutures_get_position_risk_v3) | **GET** /fapi/v3/positionRisk | Position Information V3 (USER_DATA)
[**umfutures_get_user_trades_v1**](TradeApi.md#umfutures_get_user_trades_v1) | **GET** /fapi/v1/userTrades | Account Trade List (USER_DATA)
[**umfutures_update_batch_orders_v1**](TradeApi.md#umfutures_update_batch_orders_v1) | **PUT** /fapi/v1/batchOrders | Modify Multiple Orders(TRADE)
[**umfutures_update_order_v1**](TradeApi.md#umfutures_update_order_v1) | **PUT** /fapi/v1/order | Modify Order (TRADE)



## umfutures_create_batch_orders_v1

> Vec<models::UmfuturesCreateBatchOrdersV1RespInner> umfutures_create_batch_orders_v1(batch_orders, timestamp, recv_window)
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


## umfutures_create_countdown_cancel_all_v1

> models::UmfuturesCreateCountdownCancelAllV1Resp umfutures_create_countdown_cancel_all_v1(umfutures_create_countdown_cancel_all_v1_req)
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


## umfutures_create_leverage_v1

> models::UmfuturesCreateLeverageV1Resp umfutures_create_leverage_v1(leverage, symbol, timestamp, recv_window)
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

[**models::UmfuturesCreateLeverageV1Resp**](UmfuturesCreateLeverageV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_create_margin_type_v1

> models::UmfuturesCreateMarginTypeV1Resp umfutures_create_margin_type_v1(margin_type, symbol, timestamp, recv_window)
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

[**models::UmfuturesCreateMarginTypeV1Resp**](UmfuturesCreateMarginTypeV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_create_multi_assets_margin_v1

> models::UmfuturesCreateMultiAssetsMarginV1Resp umfutures_create_multi_assets_margin_v1(multi_assets_margin, timestamp, recv_window)
Change Multi-Assets Mode (TRADE)

Change user's Multi-Assets mode (Multi-Assets Mode or Single-Asset Mode) on Every symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**multi_assets_margin** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesCreateMultiAssetsMarginV1Resp**](UmfuturesCreateMultiAssetsMarginV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_create_order_test_v1

> models::UmfuturesCreateOrderTestV1Resp umfutures_create_order_test_v1(side, symbol, timestamp, r#type, activation_price, callback_rate, close_position, good_till_date, new_client_order_id, new_order_resp_type, position_side, price, price_match, price_protect, quantity, recv_window, reduce_only, self_trade_prevention_mode, stop_price, time_in_force, working_type)
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

[**models::UmfuturesCreateOrderTestV1Resp**](UmfuturesCreateOrderTestV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_create_order_v1

> models::UmfuturesCreateOrderV1Resp umfutures_create_order_v1(side, symbol, timestamp, r#type, activation_price, callback_rate, close_position, good_till_date, new_client_order_id, new_order_resp_type, position_side, price, price_match, price_protect, quantity, recv_window, reduce_only, self_trade_prevention_mode, stop_price, time_in_force, working_type)
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

[**models::UmfuturesCreateOrderV1Resp**](UmfuturesCreateOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_create_position_margin_v1

> models::UmfuturesCreatePositionMarginV1Resp umfutures_create_position_margin_v1(amount, symbol, timestamp, r#type, position_side, recv_window)
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

[**models::UmfuturesCreatePositionMarginV1Resp**](UmfuturesCreatePositionMarginV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_create_position_side_dual_v1

> models::UmfuturesCreatePositionSideDualV1Resp umfutures_create_position_side_dual_v1(dual_side_position, timestamp, recv_window)
Change Position Mode(TRADE)

Change user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**dual_side_position** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesCreatePositionSideDualV1Resp**](UmfuturesCreatePositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_delete_all_open_orders_v1

> models::UmfuturesDeleteAllOpenOrdersV1Resp umfutures_delete_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel All Open Orders (TRADE)

Cancel All Open Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesDeleteAllOpenOrdersV1Resp**](UmfuturesDeleteAllOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_delete_batch_orders_v1

> Vec<models::UmfuturesDeleteBatchOrdersV1RespInner> umfutures_delete_batch_orders_v1(symbol, timestamp, order_id_list, orig_client_order_id_list, recv_window)
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


## umfutures_delete_order_v1

> models::UmfuturesDeleteOrderV1Resp umfutures_delete_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::UmfuturesDeleteOrderV1Resp**](UmfuturesDeleteOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_adl_quantile_v1

> Vec<models::UmfuturesGetAdlQuantileV1RespItem> umfutures_get_adl_quantile_v1(timestamp, symbol, recv_window)
Position ADL Quantile Estimation(USER_DATA)

Position ADL Quantile Estimation

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetAdlQuantileV1RespItem>**](UmfuturesGetAdlQuantileV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_all_orders_v1

> Vec<models::UmfuturesGetAllOrdersV1RespItem> umfutures_get_all_orders_v1(symbol, timestamp, order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::UmfuturesGetAllOrdersV1RespItem>**](UmfuturesGetAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_force_orders_v1

> Vec<models::UmfuturesGetForceOrdersV1RespItem> umfutures_get_force_orders_v1(timestamp, symbol, auto_close_type, start_time, end_time, limit, recv_window)
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

[**Vec<models::UmfuturesGetForceOrdersV1RespItem>**](UmfuturesGetForceOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_open_order_v1

> models::UmfuturesGetOpenOrderV1Resp umfutures_get_open_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::UmfuturesGetOpenOrderV1Resp**](UmfuturesGetOpenOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_open_orders_v1

> Vec<models::UmfuturesGetOpenOrdersV1RespItem> umfutures_get_open_orders_v1(timestamp, symbol, recv_window)
Current All Open Orders (USER_DATA)

Get all open orders on a symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetOpenOrdersV1RespItem>**](UmfuturesGetOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_order_amendment_v1

> Vec<models::UmfuturesGetOrderAmendmentV1RespItem> umfutures_get_order_amendment_v1(symbol, timestamp, order_id, orig_client_order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::UmfuturesGetOrderAmendmentV1RespItem>**](UmfuturesGetOrderAmendmentV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_order_v1

> models::UmfuturesGetOrderV1Resp umfutures_get_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::UmfuturesGetOrderV1Resp**](UmfuturesGetOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_position_margin_history_v1

> Vec<models::UmfuturesGetPositionMarginHistoryV1RespItem> umfutures_get_position_margin_history_v1(symbol, timestamp, r#type, start_time, end_time, limit, recv_window)
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

[**Vec<models::UmfuturesGetPositionMarginHistoryV1RespItem>**](UmfuturesGetPositionMarginHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_position_risk_v2

> Vec<models::UmfuturesGetPositionRiskV2RespItem> umfutures_get_position_risk_v2(timestamp, symbol, recv_window)
Position Information V2 (USER_DATA)

Get current position information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetPositionRiskV2RespItem>**](UmfuturesGetPositionRiskV2RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_position_risk_v3

> Vec<models::UmfuturesGetPositionRiskV3RespItem> umfutures_get_position_risk_v3(timestamp, symbol, recv_window)
Position Information V3 (USER_DATA)

Get current position information(only symbol that has position or open orders will be returned).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetPositionRiskV3RespItem>**](UmfuturesGetPositionRiskV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_user_trades_v1

> Vec<models::UmfuturesGetUserTradesV1RespItem> umfutures_get_user_trades_v1(symbol, timestamp, order_id, start_time, end_time, from_id, limit, recv_window)
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

[**Vec<models::UmfuturesGetUserTradesV1RespItem>**](UmfuturesGetUserTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_update_batch_orders_v1

> Vec<models::UmfuturesUpdateBatchOrdersV1RespItem> umfutures_update_batch_orders_v1(batch_orders, timestamp, recv_window)
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


## umfutures_update_order_v1

> models::UmfuturesUpdateOrderV1Resp umfutures_update_order_v1(price, quantity, side, symbol, timestamp, order_id, orig_client_order_id, price_match, recv_window)
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

[**models::UmfuturesUpdateOrderV1Resp**](UmfuturesUpdateOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

