# \MarketMakerBlockTradeApi

All URIs are relative to *https://eapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_block_order_create_v1**](MarketMakerBlockTradeApi.md#create_block_order_create_v1) | **POST** /eapi/v1/block/order/create | New Block Trade Order (TRADE)
[**delete_block_order_create_v1**](MarketMakerBlockTradeApi.md#delete_block_order_create_v1) | **DELETE** /eapi/v1/block/order/create | Cancel Block Trade Order (TRADE)



## create_block_order_create_v1

> models::OptionsCreateBlockOrderCreateV1Resp create_block_order_create_v1(legs, liquidity, price, quantity, side, symbol, timestamp, recv_window)
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


## delete_block_order_create_v1

> serde_json::Value delete_block_order_create_v1(block_order_matching_key, timestamp, recv_window)
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

