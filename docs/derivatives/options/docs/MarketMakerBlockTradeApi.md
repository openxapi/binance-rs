# \MarketMakerBlockTradeApi

All URIs are relative to *https://eapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**options_create_block_order_create_v1**](MarketMakerBlockTradeApi.md#options_create_block_order_create_v1) | **POST** /eapi/v1/block/order/create | New Block Trade Order (TRADE)
[**options_create_block_order_execute_v1**](MarketMakerBlockTradeApi.md#options_create_block_order_execute_v1) | **POST** /eapi/v1/block/order/execute | Accept Block Trade Order (TRADE)
[**options_delete_block_order_create_v1**](MarketMakerBlockTradeApi.md#options_delete_block_order_create_v1) | **DELETE** /eapi/v1/block/order/create | Cancel Block Trade Order (TRADE)
[**options_get_block_order_execute_v1**](MarketMakerBlockTradeApi.md#options_get_block_order_execute_v1) | **GET** /eapi/v1/block/order/execute | Query Block Trade Details (USER_DATA)
[**options_get_block_order_orders_v1**](MarketMakerBlockTradeApi.md#options_get_block_order_orders_v1) | **GET** /eapi/v1/block/order/orders | Query Block Trade Order (TRADE)
[**options_get_block_user_trades_v1**](MarketMakerBlockTradeApi.md#options_get_block_user_trades_v1) | **GET** /eapi/v1/block/user-trades | Account Block Trade List (USER_DATA)
[**options_update_block_order_create_v1**](MarketMakerBlockTradeApi.md#options_update_block_order_create_v1) | **PUT** /eapi/v1/block/order/create | Extend Block Trade Order (TRADE)



## options_create_block_order_create_v1

> models::OptionsCreateBlockOrderCreateV1Resp options_create_block_order_create_v1(legs, liquidity, price, quantity, side, symbol, timestamp, recv_window)
New Block Trade Order (TRADE)

Send in a new block trade order.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**legs** | [**Vec<String>**](String.md) |  | [required] |
**liquidity** | **String** |  | [required] |[default to ]
**price** | **String** |  | [required] |[default to ]
**quantity** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i32** |  | [required] |
**recv_window** | Option<**i32**> |  |  |

### Return type

[**models::OptionsCreateBlockOrderCreateV1Resp**](OptionsCreateBlockOrderCreateV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_create_block_order_execute_v1

> models::OptionsCreateBlockOrderExecuteV1Resp options_create_block_order_execute_v1(block_order_matching_key, timestamp, recv_window)
Accept Block Trade Order (TRADE)

Accept a block trade order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**block_order_matching_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::OptionsCreateBlockOrderExecuteV1Resp**](OptionsCreateBlockOrderExecuteV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_delete_block_order_create_v1

> serde_json::Value options_delete_block_order_create_v1(block_order_matching_key, timestamp, recv_window)
Cancel Block Trade Order (TRADE)

Cancel a block trade order.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**block_order_matching_key** | **String** |  | [required] |[default to ]
**timestamp** | **i32** |  | [required] |
**recv_window** | Option<**i32**> | The value cannot be greater than 60000 |  |

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_block_order_execute_v1

> models::OptionsGetBlockOrderExecuteV1Resp options_get_block_order_execute_v1(block_order_matching_key, timestamp, recv_window)
Query Block Trade Details (USER_DATA)

Query block trade details; returns block trade details from counterparty's perspective.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**block_order_matching_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::OptionsGetBlockOrderExecuteV1Resp**](OptionsGetBlockOrderExecuteV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_block_order_orders_v1

> Vec<models::OptionsGetBlockOrderOrdersV1RespItem> options_get_block_order_orders_v1(timestamp, block_order_matching_key, end_time, start_time, underlying, recv_window)
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

[**Vec<models::OptionsGetBlockOrderOrdersV1RespItem>**](OptionsGetBlockOrderOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_block_user_trades_v1

> Vec<models::OptionsGetBlockUserTradesV1RespItem> options_get_block_user_trades_v1(timestamp, end_time, start_time, underlying, recv_window)
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

[**Vec<models::OptionsGetBlockUserTradesV1RespItem>**](OptionsGetBlockUserTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_update_block_order_create_v1

> models::OptionsUpdateBlockOrderCreateV1Resp options_update_block_order_create_v1(block_order_matching_key, timestamp, recv_window)
Extend Block Trade Order (TRADE)

Extends a block trade expire time by 30 mins from the current time.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**block_order_matching_key** | **String** |  | [required] |[default to ]
**timestamp** | **i32** |  | [required] |
**recv_window** | Option<**i32**> |  |  |

### Return type

[**models::OptionsUpdateBlockOrderCreateV1Resp**](OptionsUpdateBlockOrderCreateV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

