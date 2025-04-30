# \AccountApi

All URIs are relative to *https://dapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**cmfutures_get_account_v1**](AccountApi.md#cmfutures_get_account_v1) | **GET** /dapi/v1/account | Account Information (USER_DATA)
[**cmfutures_get_balance_v1**](AccountApi.md#cmfutures_get_balance_v1) | **GET** /dapi/v1/balance | Futures Account Balance (USER_DATA)
[**cmfutures_get_commission_rate_v1**](AccountApi.md#cmfutures_get_commission_rate_v1) | **GET** /dapi/v1/commissionRate | User Commission Rate (USER_DATA)
[**cmfutures_get_income_asyn_id_v1**](AccountApi.md#cmfutures_get_income_asyn_id_v1) | **GET** /dapi/v1/income/asyn/id | Get Futures Transaction History Download Link by Id (USER_DATA)
[**cmfutures_get_income_asyn_v1**](AccountApi.md#cmfutures_get_income_asyn_v1) | **GET** /dapi/v1/income/asyn | Get Download Id For Futures Transaction History(USER_DATA)
[**cmfutures_get_income_v1**](AccountApi.md#cmfutures_get_income_v1) | **GET** /dapi/v1/income | Get Income History(USER_DATA)
[**cmfutures_get_leverage_bracket_v1**](AccountApi.md#cmfutures_get_leverage_bracket_v1) | **GET** /dapi/v1/leverageBracket | Notional Bracket for Pair(USER_DATA)
[**cmfutures_get_leverage_bracket_v2**](AccountApi.md#cmfutures_get_leverage_bracket_v2) | **GET** /dapi/v2/leverageBracket | Notional Bracket for Symbol(USER_DATA)
[**cmfutures_get_order_asyn_id_v1**](AccountApi.md#cmfutures_get_order_asyn_id_v1) | **GET** /dapi/v1/order/asyn/id | Get Futures Order History Download Link by Id (USER_DATA)
[**cmfutures_get_order_asyn_v1**](AccountApi.md#cmfutures_get_order_asyn_v1) | **GET** /dapi/v1/order/asyn | Get Download Id For Futures Order History (USER_DATA)
[**cmfutures_get_position_side_dual_v1**](AccountApi.md#cmfutures_get_position_side_dual_v1) | **GET** /dapi/v1/positionSide/dual | Get Current Position Mode(USER_DATA)
[**cmfutures_get_trade_asyn_id_v1**](AccountApi.md#cmfutures_get_trade_asyn_id_v1) | **GET** /dapi/v1/trade/asyn/id | Get Futures Trade Download Link by Id(USER_DATA)
[**cmfutures_get_trade_asyn_v1**](AccountApi.md#cmfutures_get_trade_asyn_v1) | **GET** /dapi/v1/trade/asyn | Get Download Id For Futures Trade History (USER_DATA)



## cmfutures_get_account_v1

> models::CmfuturesGetAccountV1Resp cmfutures_get_account_v1(timestamp, recv_window)
Account Information (USER_DATA)

Get current account information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CmfuturesGetAccountV1Resp**](CmfuturesGetAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_balance_v1

> Vec<models::CmfuturesGetBalanceV1RespItem> cmfutures_get_balance_v1(timestamp, recv_window)
Futures Account Balance (USER_DATA)

Check futures account balance

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesGetBalanceV1RespItem>**](CmfuturesGetBalanceV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_commission_rate_v1

> models::CmfuturesGetCommissionRateV1Resp cmfutures_get_commission_rate_v1(symbol, timestamp, recv_window)
User Commission Rate (USER_DATA)

Query user commission rate

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CmfuturesGetCommissionRateV1Resp**](CmfuturesGetCommissionRateV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_income_asyn_id_v1

> models::CmfuturesGetIncomeAsynIdV1Resp cmfutures_get_income_asyn_id_v1(download_id, timestamp, recv_window)
Get Futures Transaction History Download Link by Id (USER_DATA)

Get futures transaction history download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CmfuturesGetIncomeAsynIdV1Resp**](CmfuturesGetIncomeAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_income_asyn_v1

> models::CmfuturesGetIncomeAsynV1Resp cmfutures_get_income_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For Futures Transaction History(USER_DATA)

Get download id for futures transaction history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CmfuturesGetIncomeAsynV1Resp**](CmfuturesGetIncomeAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_income_v1

> Vec<models::CmfuturesGetIncomeV1RespItem> cmfutures_get_income_v1(timestamp, symbol, income_type, start_time, end_time, page, limit, recv_window)
Get Income History(USER_DATA)

Get income history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**income_type** | Option<**String**> | &#34;TRANSFER&#34;,&#34;WELCOME_BONUS&#34;, &#34;FUNDING_FEE&#34;, &#34;REALIZED_PNL&#34;, &#34;COMMISSION&#34;, &#34;INSURANCE_CLEAR&#34;, and &#34;DELIVERED_SETTELMENT&#34; |  |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get funding from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get funding until INCLUSIVE. |  |
**page** | Option<**i32**> |  |  |
**limit** | Option<**i32**> | Default 100; max 1000 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesGetIncomeV1RespItem>**](CmfuturesGetIncomeV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_leverage_bracket_v1

> Vec<models::CmfuturesGetLeverageBracketV1RespItem> cmfutures_get_leverage_bracket_v1(timestamp, pair, recv_window)
Notional Bracket for Pair(USER_DATA)

Not recommended to continue using this v1 endpoint

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**pair** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesGetLeverageBracketV1RespItem>**](CmfuturesGetLeverageBracketV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_leverage_bracket_v2

> Vec<models::CmfuturesGetLeverageBracketV2RespItem> cmfutures_get_leverage_bracket_v2(timestamp, symbol, recv_window)
Notional Bracket for Symbol(USER_DATA)

Get the symbol's notional bracket list.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CmfuturesGetLeverageBracketV2RespItem>**](CmfuturesGetLeverageBracketV2RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_order_asyn_id_v1

> models::CmfuturesGetOrderAsynIdV1Resp cmfutures_get_order_asyn_id_v1(download_id, timestamp, recv_window)
Get Futures Order History Download Link by Id (USER_DATA)

Get futures order history download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CmfuturesGetOrderAsynIdV1Resp**](CmfuturesGetOrderAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_order_asyn_v1

> models::CmfuturesGetOrderAsynV1Resp cmfutures_get_order_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For Futures Order History (USER_DATA)

Get Download Id For Futures Order History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CmfuturesGetOrderAsynV1Resp**](CmfuturesGetOrderAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_position_side_dual_v1

> models::CmfuturesGetPositionSideDualV1Resp cmfutures_get_position_side_dual_v1(timestamp, recv_window)
Get Current Position Mode(USER_DATA)

Get user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CmfuturesGetPositionSideDualV1Resp**](CmfuturesGetPositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_trade_asyn_id_v1

> models::CmfuturesGetTradeAsynIdV1Resp cmfutures_get_trade_asyn_id_v1(download_id, timestamp, recv_window)
Get Futures Trade Download Link by Id(USER_DATA)

Get futures trade download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CmfuturesGetTradeAsynIdV1Resp**](CmfuturesGetTradeAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_get_trade_asyn_v1

> models::CmfuturesGetTradeAsynV1Resp cmfutures_get_trade_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For Futures Trade History (USER_DATA)

Get download id for futures trade history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CmfuturesGetTradeAsynV1Resp**](CmfuturesGetTradeAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

