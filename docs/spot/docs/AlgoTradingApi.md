# \AlgoTradingApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_algo_futures_new_order_twap_v1**](AlgoTradingApi.md#create_algo_futures_new_order_twap_v1) | **POST** /sapi/v1/algo/futures/newOrderTwap | Time-Weighted Average Price(Twap) New Order(TRADE)
[**create_algo_futures_new_order_vp_v1**](AlgoTradingApi.md#create_algo_futures_new_order_vp_v1) | **POST** /sapi/v1/algo/futures/newOrderVp | Volume Participation(VP) New Order (TRADE)
[**create_algo_spot_new_order_twap_v1**](AlgoTradingApi.md#create_algo_spot_new_order_twap_v1) | **POST** /sapi/v1/algo/spot/newOrderTwap | Time-Weighted Average Price(Twap) New Order(TRADE)
[**delete_algo_futures_order_v1**](AlgoTradingApi.md#delete_algo_futures_order_v1) | **DELETE** /sapi/v1/algo/futures/order | Cancel Algo Order(TRADE)
[**delete_algo_spot_order_v1**](AlgoTradingApi.md#delete_algo_spot_order_v1) | **DELETE** /sapi/v1/algo/spot/order | Cancel Algo Order(TRADE)
[**get_algo_futures_historical_orders_v1**](AlgoTradingApi.md#get_algo_futures_historical_orders_v1) | **GET** /sapi/v1/algo/futures/historicalOrders | Query Historical Algo Orders(USER_DATA)
[**get_algo_futures_open_orders_v1**](AlgoTradingApi.md#get_algo_futures_open_orders_v1) | **GET** /sapi/v1/algo/futures/openOrders | Query Current Algo Open Orders(USER_DATA)
[**get_algo_futures_sub_orders_v1**](AlgoTradingApi.md#get_algo_futures_sub_orders_v1) | **GET** /sapi/v1/algo/futures/subOrders | Query Sub Orders(USER_DATA)
[**get_algo_spot_historical_orders_v1**](AlgoTradingApi.md#get_algo_spot_historical_orders_v1) | **GET** /sapi/v1/algo/spot/historicalOrders | Query Historical Algo Orders(USER_DATA)
[**get_algo_spot_open_orders_v1**](AlgoTradingApi.md#get_algo_spot_open_orders_v1) | **GET** /sapi/v1/algo/spot/openOrders | Query Current Algo Open Orders(USER_DATA)
[**get_algo_spot_sub_orders_v1**](AlgoTradingApi.md#get_algo_spot_sub_orders_v1) | **GET** /sapi/v1/algo/spot/subOrders | Query Sub Orders(USER_DATA)



## create_algo_futures_new_order_twap_v1

> models::CreateAlgoFuturesNewOrderTwapV1Resp create_algo_futures_new_order_twap_v1(duration, quantity, side, symbol, timestamp, client_algo_id, limit_price, position_side, recv_window, reduce_only)
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

[**models::CreateAlgoFuturesNewOrderTwapV1Resp**](CreateAlgoFuturesNewOrderTwapV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_algo_futures_new_order_vp_v1

> models::CreateAlgoFuturesNewOrderVpV1Resp create_algo_futures_new_order_vp_v1(quantity, side, symbol, timestamp, urgency, client_algo_id, limit_price, position_side, recv_window, reduce_only)
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

[**models::CreateAlgoFuturesNewOrderVpV1Resp**](CreateAlgoFuturesNewOrderVpV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_algo_spot_new_order_twap_v1

> models::CreateAlgoSpotNewOrderTwapV1Resp create_algo_spot_new_order_twap_v1(duration, quantity, side, symbol, timestamp, client_algo_id, limit_price)
Time-Weighted Average Price(Twap) New Order(TRADE)

Place a new spot TWAP order with Algo service.

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

### Return type

[**models::CreateAlgoSpotNewOrderTwapV1Resp**](CreateAlgoSpotNewOrderTwapV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_algo_futures_order_v1

> models::DeleteAlgoFuturesOrderV1Resp delete_algo_futures_order_v1(algo_id, timestamp, recv_window)
Cancel Algo Order(TRADE)

Cancel an active order.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo_id** | **i64** | eg. 14511 | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::DeleteAlgoFuturesOrderV1Resp**](DeleteAlgoFuturesOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_algo_spot_order_v1

> models::DeleteAlgoSpotOrderV1Resp delete_algo_spot_order_v1(algo_id, timestamp, recv_window)
Cancel Algo Order(TRADE)

Cancel an open TWAP order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo_id** | **i64** | eg. 14511 | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::DeleteAlgoSpotOrderV1Resp**](DeleteAlgoSpotOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_algo_futures_historical_orders_v1

> models::GetAlgoFuturesHistoricalOrdersV1Resp get_algo_futures_historical_orders_v1(timestamp, symbol, side, start_time, end_time, page, page_size, recv_window)
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

[**models::GetAlgoFuturesHistoricalOrdersV1Resp**](GetAlgoFuturesHistoricalOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_algo_futures_open_orders_v1

> models::GetAlgoFuturesOpenOrdersV1Resp get_algo_futures_open_orders_v1(timestamp, recv_window)
Query Current Algo Open Orders(USER_DATA)

Query Current Algo Open Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAlgoFuturesOpenOrdersV1Resp**](GetAlgoFuturesOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_algo_futures_sub_orders_v1

> models::GetAlgoFuturesSubOrdersV1Resp get_algo_futures_sub_orders_v1(algo_id, timestamp, page, page_size, recv_window)
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

[**models::GetAlgoFuturesSubOrdersV1Resp**](GetAlgoFuturesSubOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_algo_spot_historical_orders_v1

> models::GetAlgoSpotHistoricalOrdersV1Resp get_algo_spot_historical_orders_v1(timestamp, symbol, side, start_time, end_time, page, page_size, recv_window)
Query Historical Algo Orders(USER_DATA)

Get all historical SPOT TWAP orders

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

[**models::GetAlgoSpotHistoricalOrdersV1Resp**](GetAlgoSpotHistoricalOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_algo_spot_open_orders_v1

> models::GetAlgoSpotOpenOrdersV1Resp get_algo_spot_open_orders_v1(timestamp, recv_window)
Query Current Algo Open Orders(USER_DATA)

Get all open SPOT TWAP orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAlgoSpotOpenOrdersV1Resp**](GetAlgoSpotOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_algo_spot_sub_orders_v1

> models::GetAlgoSpotSubOrdersV1Resp get_algo_spot_sub_orders_v1(algo_id, timestamp, page, page_size, recv_window)
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

[**models::GetAlgoSpotSubOrdersV1Resp**](GetAlgoSpotSubOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

