# \TradeApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**convert_create_convert_accept_quote_v1**](TradeApi.md#convert_create_convert_accept_quote_v1) | **POST** /sapi/v1/convert/acceptQuote | Accept Quote (TRADE)
[**convert_create_convert_get_quote_v1**](TradeApi.md#convert_create_convert_get_quote_v1) | **POST** /sapi/v1/convert/getQuote | Send Quote Request(USER_DATA)
[**convert_create_convert_limit_cancel_order_v1**](TradeApi.md#convert_create_convert_limit_cancel_order_v1) | **POST** /sapi/v1/convert/limit/cancelOrder | Cancel limit order (USER_DATA)
[**convert_create_convert_limit_place_order_v1**](TradeApi.md#convert_create_convert_limit_place_order_v1) | **POST** /sapi/v1/convert/limit/placeOrder | Place limit order (USER_DATA)
[**convert_create_convert_limit_query_open_orders_v1**](TradeApi.md#convert_create_convert_limit_query_open_orders_v1) | **POST** /sapi/v1/convert/limit/queryOpenOrders | Query limit open orders (USER_DATA)
[**convert_get_convert_order_status_v1**](TradeApi.md#convert_get_convert_order_status_v1) | **GET** /sapi/v1/convert/orderStatus | Order status(USER_DATA)
[**convert_get_convert_trade_flow_v1**](TradeApi.md#convert_get_convert_trade_flow_v1) | **GET** /sapi/v1/convert/tradeFlow | Get Convert Trade History(USER_DATA)



## convert_create_convert_accept_quote_v1

> models::ConvertCreateConvertAcceptQuoteV1Resp convert_create_convert_accept_quote_v1(quote_id, timestamp, recv_window)
Accept Quote (TRADE)

Accept the offered quote by quote ID.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**quote_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::ConvertCreateConvertAcceptQuoteV1Resp**](ConvertCreateConvertAcceptQuoteV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## convert_create_convert_get_quote_v1

> models::ConvertCreateConvertGetQuoteV1Resp convert_create_convert_get_quote_v1(from_asset, timestamp, to_asset, from_amount, recv_window, to_amount, valid_time, wallet_type)
Send Quote Request(USER_DATA)

Request a quote for the requested token pairs

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**from_asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**to_asset** | **String** |  | [required] |[default to ]
**from_amount** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**to_amount** | Option<**String**> |  |  |[default to ]
**valid_time** | Option<**String**> |  |  |[default to 10]
**wallet_type** | Option<**String**> |  |  |[default to ]

### Return type

[**models::ConvertCreateConvertGetQuoteV1Resp**](ConvertCreateConvertGetQuoteV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## convert_create_convert_limit_cancel_order_v1

> models::ConvertCreateConvertLimitCancelOrderV1Resp convert_create_convert_limit_cancel_order_v1(order_id, timestamp, recv_window)
Cancel limit order (USER_DATA)

Enable users to cancel a limit order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**order_id** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::ConvertCreateConvertLimitCancelOrderV1Resp**](ConvertCreateConvertLimitCancelOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## convert_create_convert_limit_place_order_v1

> models::ConvertCreateConvertLimitPlaceOrderV1Resp convert_create_convert_limit_place_order_v1(base_asset, expired_type, limit_price, quote_asset, side, timestamp, base_amount, quote_amount, recv_window, wallet_type)
Place limit order (USER_DATA)

Enable users to place a limit order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**base_asset** | **String** |  | [required] |[default to ]
**expired_type** | **String** |  | [required] |[default to ]
**limit_price** | **String** |  | [required] |[default to ]
**quote_asset** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**base_amount** | Option<**String**> |  |  |[default to ]
**quote_amount** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**wallet_type** | Option<**String**> |  |  |[default to ]

### Return type

[**models::ConvertCreateConvertLimitPlaceOrderV1Resp**](ConvertCreateConvertLimitPlaceOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## convert_create_convert_limit_query_open_orders_v1

> models::ConvertCreateConvertLimitQueryOpenOrdersV1Resp convert_create_convert_limit_query_open_orders_v1(timestamp, recv_window)
Query limit open orders (USER_DATA)

Request a quote for the requested token pairs

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::ConvertCreateConvertLimitQueryOpenOrdersV1Resp**](ConvertCreateConvertLimitQueryOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## convert_get_convert_order_status_v1

> models::ConvertGetConvertOrderStatusV1Resp convert_get_convert_order_status_v1(order_id, quote_id)
Order status(USER_DATA)

Query order status by order ID.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**order_id** | Option<**String**> | Either orderId or quoteId is required |  |[default to ]
**quote_id** | Option<**String**> | Either orderId or quoteId is required |  |[default to ]

### Return type

[**models::ConvertGetConvertOrderStatusV1Resp**](ConvertGetConvertOrderStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## convert_get_convert_trade_flow_v1

> models::ConvertGetConvertTradeFlowV1Resp convert_get_convert_trade_flow_v1(start_time, end_time, timestamp, limit, recv_window)
Get Convert Trade History(USER_DATA)

Get Convert Trade History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** |  | [required] |
**end_time** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**limit** | Option<**i32**> | Default 100, Max 1000 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::ConvertGetConvertTradeFlowV1Resp**](ConvertGetConvertTradeFlowV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

