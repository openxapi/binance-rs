# \SpotAlgoApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**algo_create_algo_spot_new_order_twap_v1**](SpotAlgoApi.md#algo_create_algo_spot_new_order_twap_v1) | **POST** /sapi/v1/algo/spot/newOrderTwap | Time-Weighted Average Price(Twap) New Order(TRADE)
[**algo_delete_algo_spot_order_v1**](SpotAlgoApi.md#algo_delete_algo_spot_order_v1) | **DELETE** /sapi/v1/algo/spot/order | Cancel Algo Order(TRADE)
[**algo_get_algo_spot_historical_orders_v1**](SpotAlgoApi.md#algo_get_algo_spot_historical_orders_v1) | **GET** /sapi/v1/algo/spot/historicalOrders | Query Historical Algo Orders(USER_DATA)
[**algo_get_algo_spot_open_orders_v1**](SpotAlgoApi.md#algo_get_algo_spot_open_orders_v1) | **GET** /sapi/v1/algo/spot/openOrders | Query Current Algo Open Orders(USER_DATA)
[**algo_get_algo_spot_sub_orders_v1**](SpotAlgoApi.md#algo_get_algo_spot_sub_orders_v1) | **GET** /sapi/v1/algo/spot/subOrders | Query Sub Orders(USER_DATA)



## algo_create_algo_spot_new_order_twap_v1

> models::AlgoCreateAlgoSpotNewOrderTwapV1Resp algo_create_algo_spot_new_order_twap_v1(duration, quantity, side, symbol, timestamp, client_algo_id, limit_price)
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

[**models::AlgoCreateAlgoSpotNewOrderTwapV1Resp**](AlgoCreateAlgoSpotNewOrderTwapV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## algo_delete_algo_spot_order_v1

> models::AlgoDeleteAlgoSpotOrderV1Resp algo_delete_algo_spot_order_v1(algo_id, timestamp, recv_window)
Cancel Algo Order(TRADE)

Cancel an open TWAP order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo_id** | **i64** | eg. 14511 | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::AlgoDeleteAlgoSpotOrderV1Resp**](AlgoDeleteAlgoSpotOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## algo_get_algo_spot_historical_orders_v1

> models::AlgoGetAlgoSpotHistoricalOrdersV1Resp algo_get_algo_spot_historical_orders_v1(timestamp, symbol, side, start_time, end_time, page, page_size, recv_window)
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

[**models::AlgoGetAlgoSpotHistoricalOrdersV1Resp**](AlgoGetAlgoSpotHistoricalOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## algo_get_algo_spot_open_orders_v1

> models::AlgoGetAlgoSpotOpenOrdersV1Resp algo_get_algo_spot_open_orders_v1(timestamp, recv_window)
Query Current Algo Open Orders(USER_DATA)

Get all open SPOT TWAP orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::AlgoGetAlgoSpotOpenOrdersV1Resp**](AlgoGetAlgoSpotOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## algo_get_algo_spot_sub_orders_v1

> models::AlgoGetAlgoSpotSubOrdersV1Resp algo_get_algo_spot_sub_orders_v1(algo_id, timestamp, page, page_size, recv_window)
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

[**models::AlgoGetAlgoSpotSubOrdersV1Resp**](AlgoGetAlgoSpotSubOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

