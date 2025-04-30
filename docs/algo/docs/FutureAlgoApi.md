# \FutureAlgoApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**algo_create_algo_futures_new_order_twap_v1**](FutureAlgoApi.md#algo_create_algo_futures_new_order_twap_v1) | **POST** /sapi/v1/algo/futures/newOrderTwap | Time-Weighted Average Price(Twap) New Order(TRADE)
[**algo_create_algo_futures_new_order_vp_v1**](FutureAlgoApi.md#algo_create_algo_futures_new_order_vp_v1) | **POST** /sapi/v1/algo/futures/newOrderVp | Volume Participation(VP) New Order (TRADE)
[**algo_delete_algo_futures_order_v1**](FutureAlgoApi.md#algo_delete_algo_futures_order_v1) | **DELETE** /sapi/v1/algo/futures/order | Cancel Algo Order(TRADE)
[**algo_get_algo_futures_historical_orders_v1**](FutureAlgoApi.md#algo_get_algo_futures_historical_orders_v1) | **GET** /sapi/v1/algo/futures/historicalOrders | Query Historical Algo Orders(USER_DATA)
[**algo_get_algo_futures_open_orders_v1**](FutureAlgoApi.md#algo_get_algo_futures_open_orders_v1) | **GET** /sapi/v1/algo/futures/openOrders | Query Current Algo Open Orders(USER_DATA)
[**algo_get_algo_futures_sub_orders_v1**](FutureAlgoApi.md#algo_get_algo_futures_sub_orders_v1) | **GET** /sapi/v1/algo/futures/subOrders | Query Sub Orders(USER_DATA)



## algo_create_algo_futures_new_order_twap_v1

> models::AlgoCreateAlgoFuturesNewOrderTwapV1Resp algo_create_algo_futures_new_order_twap_v1(duration, quantity, side, symbol, timestamp, client_algo_id, limit_price, position_side, recv_window, reduce_only)
Time-Weighted Average Price(Twap) New Order(TRADE)

Send in a Twap new order. Only support on USDⓈ-M Contracts.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**duration** | **i64** |  | [required] |
**quantity** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**client_algo_id** | Option<**String**> |  |  |[default to ]
**limit_price** | Option<**String**> |  |  |[default to ]
**position_side** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**reduce_only** | Option<**bool**> |  |  |

### Return type

[**models::AlgoCreateAlgoFuturesNewOrderTwapV1Resp**](AlgoCreateAlgoFuturesNewOrderTwapV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## algo_create_algo_futures_new_order_vp_v1

> models::AlgoCreateAlgoFuturesNewOrderVpV1Resp algo_create_algo_futures_new_order_vp_v1(quantity, side, symbol, timestamp, urgency, client_algo_id, limit_price, position_side, recv_window, reduce_only)
Volume Participation(VP) New Order (TRADE)

Send in a VP new order. Only support on USDⓈ-M Contracts.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**quantity** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**urgency** | **String** |  | [required] |[default to ]
**client_algo_id** | Option<**String**> |  |  |[default to ]
**limit_price** | Option<**String**> |  |  |[default to ]
**position_side** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**reduce_only** | Option<**bool**> |  |  |

### Return type

[**models::AlgoCreateAlgoFuturesNewOrderVpV1Resp**](AlgoCreateAlgoFuturesNewOrderVpV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## algo_delete_algo_futures_order_v1

> models::AlgoDeleteAlgoFuturesOrderV1Resp algo_delete_algo_futures_order_v1(algo_id, timestamp, recv_window)
Cancel Algo Order(TRADE)

Cancel an active order.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo_id** | **i64** | eg. 14511 | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::AlgoDeleteAlgoFuturesOrderV1Resp**](AlgoDeleteAlgoFuturesOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## algo_get_algo_futures_historical_orders_v1

> models::AlgoGetAlgoFuturesHistoricalOrdersV1Resp algo_get_algo_futures_historical_orders_v1(timestamp, symbol, side, start_time, end_time, page, page_size, recv_window)
Query Historical Algo Orders(USER_DATA)

Query Historical Algo Order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> | Trading symbol eg. BTCUSDT |  |[default to ]
**side** | Option<**String**> | BUY or SELL |  |[default to ]
**start_time** | Option<**i64**> | in milliseconds  eg.1641522717552 |  |
**end_time** | Option<**i64**> | in milliseconds  eg.1641522526562 |  |
**page** | Option<**i32**> | Default is 1 |  |
**page_size** | Option<**i32**> | MIN 1, MAX 100; Default 100 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::AlgoGetAlgoFuturesHistoricalOrdersV1Resp**](AlgoGetAlgoFuturesHistoricalOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## algo_get_algo_futures_open_orders_v1

> models::AlgoGetAlgoFuturesOpenOrdersV1Resp algo_get_algo_futures_open_orders_v1(timestamp, recv_window)
Query Current Algo Open Orders(USER_DATA)

Query Current Algo Open Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::AlgoGetAlgoFuturesOpenOrdersV1Resp**](AlgoGetAlgoFuturesOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## algo_get_algo_futures_sub_orders_v1

> models::AlgoGetAlgoFuturesSubOrdersV1Resp algo_get_algo_futures_sub_orders_v1(algo_id, timestamp, page, page_size, recv_window)
Query Sub Orders(USER_DATA)

Get respective sub orders for a specified algoId

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo_id** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**page** | Option<**i32**> | Default is 1 |  |
**page_size** | Option<**i32**> | MIN 1, MAX 100; Default 100 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::AlgoGetAlgoFuturesSubOrdersV1Resp**](AlgoGetAlgoFuturesSubOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

