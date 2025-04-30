# \ConvertApi

All URIs are relative to *https://fapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**umfutures_create_convert_accept_quote_v1**](ConvertApi.md#umfutures_create_convert_accept_quote_v1) | **POST** /fapi/v1/convert/acceptQuote | Accept the offered quote (USER_DATA)
[**umfutures_create_convert_get_quote_v1**](ConvertApi.md#umfutures_create_convert_get_quote_v1) | **POST** /fapi/v1/convert/getQuote | Send Quote Request(USER_DATA)
[**umfutures_get_convert_exchange_info_v1**](ConvertApi.md#umfutures_get_convert_exchange_info_v1) | **GET** /fapi/v1/convert/exchangeInfo | List All Convert Pairs
[**umfutures_get_convert_order_status_v1**](ConvertApi.md#umfutures_get_convert_order_status_v1) | **GET** /fapi/v1/convert/orderStatus | Order status(USER_DATA)



## umfutures_create_convert_accept_quote_v1

> models::UmfuturesCreateConvertAcceptQuoteV1Resp umfutures_create_convert_accept_quote_v1(quote_id, timestamp, recv_window)
Accept the offered quote (USER_DATA)

Accept the offered quote by quote ID.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**quote_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesCreateConvertAcceptQuoteV1Resp**](UmfuturesCreateConvertAcceptQuoteV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_create_convert_get_quote_v1

> models::UmfuturesCreateConvertGetQuoteV1Resp umfutures_create_convert_get_quote_v1(from_asset, timestamp, to_asset, from_amount, recv_window, to_amount, valid_time)
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

### Return type

[**models::UmfuturesCreateConvertGetQuoteV1Resp**](UmfuturesCreateConvertGetQuoteV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_convert_exchange_info_v1

> Vec<models::UmfuturesGetConvertExchangeInfoV1RespItem> umfutures_get_convert_exchange_info_v1(from_asset, to_asset)
List All Convert Pairs

Query for all convertible token pairs and the tokens’ respective upper/lower limits

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**from_asset** | Option<**String**> | User spends coin |  |[default to ]
**to_asset** | Option<**String**> | User receives coin |  |[default to ]

### Return type

[**Vec<models::UmfuturesGetConvertExchangeInfoV1RespItem>**](UmfuturesGetConvertExchangeInfoV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_convert_order_status_v1

> models::UmfuturesGetConvertOrderStatusV1Resp umfutures_get_convert_order_status_v1(order_id, quote_id)
Order status(USER_DATA)

Query order status by order ID.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**order_id** | Option<**String**> | Either orderId or quoteId is required |  |[default to ]
**quote_id** | Option<**String**> | Either orderId or quoteId is required |  |[default to ]

### Return type

[**models::UmfuturesGetConvertOrderStatusV1Resp**](UmfuturesGetConvertOrderStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

