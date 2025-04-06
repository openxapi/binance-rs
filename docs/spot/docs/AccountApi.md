# \AccountApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**spot_get_account_commission_v3**](AccountApi.md#spot_get_account_commission_v3) | **GET** /api/v3/account/commission | Query Commission Rates (USER_DATA)
[**spot_get_account_v3**](AccountApi.md#spot_get_account_v3) | **GET** /api/v3/account | Account information (USER_DATA)
[**spot_get_my_allocations_v3**](AccountApi.md#spot_get_my_allocations_v3) | **GET** /api/v3/myAllocations | Query Allocations (USER_DATA)
[**spot_get_my_prevented_matches_v3**](AccountApi.md#spot_get_my_prevented_matches_v3) | **GET** /api/v3/myPreventedMatches | Query Prevented Matches (USER_DATA)
[**spot_get_my_trades_v3**](AccountApi.md#spot_get_my_trades_v3) | **GET** /api/v3/myTrades | Account trade list (USER_DATA)
[**spot_get_rate_limit_order_v3**](AccountApi.md#spot_get_rate_limit_order_v3) | **GET** /api/v3/rateLimit/order | Query Unfilled Order Count (USER_DATA)



## spot_get_account_commission_v3

> models::SpotGetAccountCommissionV3Resp spot_get_account_commission_v3(symbol)
Query Commission Rates (USER_DATA)

Get current account commission rates.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::SpotGetAccountCommissionV3Resp**](SpotGetAccountCommissionV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_account_v3

> models::SpotGetAccountV3Resp spot_get_account_v3(timestamp, omit_zero_balances, recv_window)
Account information (USER_DATA)

Get current account information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**omit_zero_balances** | Option<**bool**> | When set to `true`, emits only the non-zero balances of an account. <br/>Default value: `false` |  |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::SpotGetAccountV3Resp**](SpotGetAccountV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_my_allocations_v3

> Vec<models::SpotGetMyAllocationsV3RespItem> spot_get_my_allocations_v3(symbol, start_time, end_time, from_allocation_id, limit, order_id, recv_window, timestamp)
Query Allocations (USER_DATA)

Retrieves allocations resulting from SOR order placement.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**from_allocation_id** | Option<**i32**> |  |  |
**limit** | Option<**i32**> | Default 500;Max 1000 |  |[default to 500]
**order_id** | Option<**i64**> |  |  |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000`. |  |
**timestamp** | Option<**i64**> |  |  |

### Return type

[**Vec<models::SpotGetMyAllocationsV3RespItem>**](SpotGetMyAllocationsV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_my_prevented_matches_v3

> Vec<models::SpotGetMyPreventedMatchesV3RespItem> spot_get_my_prevented_matches_v3(symbol, timestamp, prevented_match_id, order_id, from_prevented_match_id, limit, recv_window)
Query Prevented Matches (USER_DATA)

Displays the list of orders that were expired due to STP. These are the combinations supported: - symbol + preventedMatchId - symbol + orderId - symbol + orderId + fromPreventedMatchId (limit will default to 500) - symbol + orderId + fromPreventedMatchId + limit

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**prevented_match_id** | Option<**i64**> |  |  |
**order_id** | Option<**i64**> |  |  |
**from_prevented_match_id** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default: `500`; Max: `1000` |  |[default to 500]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::SpotGetMyPreventedMatchesV3RespItem>**](SpotGetMyPreventedMatchesV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_my_trades_v3

> Vec<models::SpotGetMyTradesV3RespItem> spot_get_my_trades_v3(symbol, timestamp, order_id, start_time, end_time, from_id, limit, recv_window)
Account trade list (USER_DATA)

Get trades for a specific account and symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> | This can only be used in combination with `symbol`. |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**from_id** | Option<**i64**> | TradeId to fetch from. Default gets most recent trades. |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::SpotGetMyTradesV3RespItem>**](SpotGetMyTradesV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_get_rate_limit_order_v3

> Vec<models::SpotGetRateLimitOrderV3RespItem> spot_get_rate_limit_order_v3(timestamp, recv_window)
Query Unfilled Order Count (USER_DATA)

Displays the user's unfilled order count for all intervals.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::SpotGetRateLimitOrderV3RespItem>**](SpotGetRateLimitOrderV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

