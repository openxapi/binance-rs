# \ManagedSubAccountApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**subaccount_create_managed_subaccount_deposit_v1**](ManagedSubAccountApi.md#subaccount_create_managed_subaccount_deposit_v1) | **POST** /sapi/v1/managed-subaccount/deposit | Deposit Assets Into The Managed Sub-account(For Investor Master Account)
[**subaccount_create_managed_subaccount_withdraw_v1**](ManagedSubAccountApi.md#subaccount_create_managed_subaccount_withdraw_v1) | **POST** /sapi/v1/managed-subaccount/withdraw | Withdrawl Assets From The Managed Sub-account(For Investor Master Account)
[**subaccount_get_managed_subaccount_account_snapshot_v1**](ManagedSubAccountApi.md#subaccount_get_managed_subaccount_account_snapshot_v1) | **GET** /sapi/v1/managed-subaccount/accountSnapshot | Query Managed Sub-account Snapshot(For Investor Master Account)
[**subaccount_get_managed_subaccount_asset_v1**](ManagedSubAccountApi.md#subaccount_get_managed_subaccount_asset_v1) | **GET** /sapi/v1/managed-subaccount/asset | Query Managed Sub-account Asset Details(For Investor Master Account)
[**subaccount_get_managed_subaccount_deposit_address_v1**](ManagedSubAccountApi.md#subaccount_get_managed_subaccount_deposit_address_v1) | **GET** /sapi/v1/managed-subaccount/deposit/address | Get Managed Sub-account Deposit Address (For Investor Master Account)(USER_DATA)
[**subaccount_get_managed_subaccount_fetch_future_asset_v1**](ManagedSubAccountApi.md#subaccount_get_managed_subaccount_fetch_future_asset_v1) | **GET** /sapi/v1/managed-subaccount/fetch-future-asset | Query Managed Sub-account Futures Asset Details(For Investor Master Account)(USER_DATA)
[**subaccount_get_managed_subaccount_info_v1**](ManagedSubAccountApi.md#subaccount_get_managed_subaccount_info_v1) | **GET** /sapi/v1/managed-subaccount/info | Query Managed Sub-account List(For Investor)(USER_DATA)
[**subaccount_get_managed_subaccount_margin_asset_v1**](ManagedSubAccountApi.md#subaccount_get_managed_subaccount_margin_asset_v1) | **GET** /sapi/v1/managed-subaccount/marginAsset | Query Managed Sub-account Margin Asset Details(For Investor Master Account)(USER_DATA)
[**subaccount_get_managed_subaccount_query_trans_log_for_investor_v1**](ManagedSubAccountApi.md#subaccount_get_managed_subaccount_query_trans_log_for_investor_v1) | **GET** /sapi/v1/managed-subaccount/queryTransLogForInvestor | Query Managed Sub Account Transfer Log(For Investor Master Account)(USER_DATA)
[**subaccount_get_managed_subaccount_query_trans_log_for_trade_parent_v1**](ManagedSubAccountApi.md#subaccount_get_managed_subaccount_query_trans_log_for_trade_parent_v1) | **GET** /sapi/v1/managed-subaccount/queryTransLogForTradeParent | Query Managed Sub Account Transfer Log(For Trading Team Master Account)(USER_DATA)
[**subaccount_get_managed_subaccount_query_trans_log_v1**](ManagedSubAccountApi.md#subaccount_get_managed_subaccount_query_trans_log_v1) | **GET** /sapi/v1/managed-subaccount/query-trans-log | Query Managed Sub Account Transfer Log (For Trading Team Sub Account)(USER_DATA)



## subaccount_create_managed_subaccount_deposit_v1

> models::SubaccountCreateManagedSubaccountDepositV1Resp subaccount_create_managed_subaccount_deposit_v1(amount, asset, timestamp, to_email, recv_window)
Deposit Assets Into The Managed Sub-account(For Investor Master Account)

Deposit Assets Into The Managed Sub-account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**to_email** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateManagedSubaccountDepositV1Resp**](SubaccountCreateManagedSubaccountDepositV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_create_managed_subaccount_withdraw_v1

> models::SubaccountCreateManagedSubaccountWithdrawV1Resp subaccount_create_managed_subaccount_withdraw_v1(amount, asset, from_email, timestamp, recv_window, transfer_date)
Withdrawl Assets From The Managed Sub-account(For Investor Master Account)

Withdrawl Assets From The Managed Sub-account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**from_email** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |
**transfer_date** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateManagedSubaccountWithdrawV1Resp**](SubaccountCreateManagedSubaccountWithdrawV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_managed_subaccount_account_snapshot_v1

> models::SubaccountGetManagedSubaccountAccountSnapshotV1Resp subaccount_get_managed_subaccount_account_snapshot_v1(email, r#type, timestamp, start_time, end_time, limit, recv_window)
Query Managed Sub-account Snapshot(For Investor Master Account)

Query Managed Sub-account Snapshot

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**r#type** | **String** | &#34;SPOT&#34;, &#34;MARGIN&#34;（cross）, &#34;FUTURES&#34;（UM） | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | min 7, max 30, default 7 |  |[default to 7]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetManagedSubaccountAccountSnapshotV1Resp**](SubaccountGetManagedSubaccountAccountSnapshotV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_managed_subaccount_asset_v1

> Vec<models::SubaccountGetManagedSubaccountAssetV1RespItem> subaccount_get_managed_subaccount_asset_v1(email, timestamp, recv_window)
Query Managed Sub-account Asset Details(For Investor Master Account)

Query Managed Sub-account Asset Details

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::SubaccountGetManagedSubaccountAssetV1RespItem>**](SubaccountGetManagedSubaccountAssetV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_managed_subaccount_deposit_address_v1

> models::SubaccountGetManagedSubaccountDepositAddressV1Resp subaccount_get_managed_subaccount_deposit_address_v1(email, coin, timestamp, network, amount, recv_window)
Get Managed Sub-account Deposit Address (For Investor Master Account)(USER_DATA)

Get investor's managed sub-account deposit address.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Sub user email | [required] |[default to ]
**coin** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**network** | Option<**String**> | networks can be found in `GET /sapi/v1/capital/deposit/address` |  |[default to ]
**amount** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetManagedSubaccountDepositAddressV1Resp**](SubaccountGetManagedSubaccountDepositAddressV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_managed_subaccount_fetch_future_asset_v1

> models::SubaccountGetManagedSubaccountFetchFutureAssetV1Resp subaccount_get_managed_subaccount_fetch_future_asset_v1(email, account_type)
Query Managed Sub-account Futures Asset Details(For Investor Master Account)(USER_DATA)

Investor can use this api to query managed sub account futures asset details

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Managed Sub Account Email | [required] |[default to ]
**account_type** | Option<**String**> | No input or input &#34;USDT_FUTURE&#34; to get UM Futures account details. Input &#34;COIN_FUTURE&#34; to get CM Futures account details. |  |[default to ]

### Return type

[**models::SubaccountGetManagedSubaccountFetchFutureAssetV1Resp**](SubaccountGetManagedSubaccountFetchFutureAssetV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_managed_subaccount_info_v1

> models::SubaccountGetManagedSubaccountInfoV1Resp subaccount_get_managed_subaccount_info_v1(timestamp, email, page, limit, recv_window)
Query Managed Sub-account List(For Investor)(USER_DATA)

Get investor's managed sub-account list.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**email** | Option<**String**> | Managed sub-account email |  |[default to ]
**page** | Option<**i32**> | Default value: 1 |  |
**limit** | Option<**i32**> | Default value: 20, Max value: 20 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetManagedSubaccountInfoV1Resp**](SubaccountGetManagedSubaccountInfoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_managed_subaccount_margin_asset_v1

> models::SubaccountGetManagedSubaccountMarginAssetV1Resp subaccount_get_managed_subaccount_margin_asset_v1(email, account_type)
Query Managed Sub-account Margin Asset Details(For Investor Master Account)(USER_DATA)

Investor can use this api to query managed sub account margin asset details

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Managed Sub Account Email | [required] |[default to ]
**account_type** | Option<**String**> | No input or input &#34;MARGIN&#34; to get Cross Margin account details. Input &#34;ISOLATED_MARGIN&#34; to get Isolated Margin account details. |  |[default to ]

### Return type

[**models::SubaccountGetManagedSubaccountMarginAssetV1Resp**](SubaccountGetManagedSubaccountMarginAssetV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_managed_subaccount_query_trans_log_for_investor_v1

> models::SubaccountGetManagedSubaccountQueryTransLogForInvestorV1Resp subaccount_get_managed_subaccount_query_trans_log_for_investor_v1(email, start_time, end_time, page, limit, transfers, transfer_function_account_type)
Query Managed Sub Account Transfer Log(For Investor Master Account)(USER_DATA)

Investor can use this api to query managed sub account transfer log. This endpoint is available for investor of Managed Sub-Account. A Managed Sub-Account is an account type for investors who value flexibility in asset allocation and account application, while delegating trades to a professional trading team. Please refer to link

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Managed Sub Account Email | [required] |[default to ]
**start_time** | **i64** | Start Time | [required] |
**end_time** | **i64** | End Time (The start time and end time interval cannot exceed half a year) | [required] |
**page** | **i32** | Page | [required] |
**limit** | **i32** | Limit (Max: 500) | [required] |
**transfers** | Option<**String**> | Transfer Direction (FROM/TO) |  |[default to ]
**transfer_function_account_type** | Option<**String**> | Transfer function account type (SPOT/MARGIN/ISOLATED_MARGIN/USDT_FUTURE/COIN_FUTURE) |  |[default to ]

### Return type

[**models::SubaccountGetManagedSubaccountQueryTransLogForInvestorV1Resp**](SubaccountGetManagedSubaccountQueryTransLogForInvestorV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_managed_subaccount_query_trans_log_for_trade_parent_v1

> models::SubaccountGetManagedSubaccountQueryTransLogForTradeParentV1Resp subaccount_get_managed_subaccount_query_trans_log_for_trade_parent_v1(email, start_time, end_time, page, limit, transfers, transfer_function_account_type)
Query Managed Sub Account Transfer Log(For Trading Team Master Account)(USER_DATA)

Trading team can use this api to query managed sub account transfer log. This endpoint is available for trading team of Managed Sub-Account. A Managed Sub-Account is an account type for investors who value flexibility in asset allocation and account application, while delegating trades to a professional trading team. Please refer to link

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Managed Sub Account Email | [required] |[default to ]
**start_time** | **i64** | Start Time | [required] |
**end_time** | **i64** | End Time (The start time and end time interval cannot exceed half a year) | [required] |
**page** | **i32** | Page | [required] |
**limit** | **i32** | Limit (Max: 500) | [required] |
**transfers** | Option<**String**> | Transfer Direction (FROM/TO) |  |[default to ]
**transfer_function_account_type** | Option<**String**> | Transfer function account type (SPOT/MARGIN/ISOLATED_MARGIN/USDT_FUTURE/COIN_FUTURE) |  |[default to ]

### Return type

[**models::SubaccountGetManagedSubaccountQueryTransLogForTradeParentV1Resp**](SubaccountGetManagedSubaccountQueryTransLogForTradeParentV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_managed_subaccount_query_trans_log_v1

> models::SubaccountGetManagedSubaccountQueryTransLogV1Resp subaccount_get_managed_subaccount_query_trans_log_v1(start_time, end_time, page, limit, timestamp, transfers, transfer_function_account_type, recv_window)
Query Managed Sub Account Transfer Log (For Trading Team Sub Account)(USER_DATA)

Query Managed Sub Account Transfer Log (For Trading Team Sub Account)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Start Time | [required] |
**end_time** | **i64** | End Time (The start time and end time interval cannot exceed half a year) | [required] |
**page** | **i32** | Page | [required] |
**limit** | **i32** | Limit (Max: 500) | [required] |
**timestamp** | **i64** |  | [required] |
**transfers** | Option<**String**> | Transfer Direction (FROM/TO) |  |[default to ]
**transfer_function_account_type** | Option<**String**> | Transfer function account type (SPOT/MARGIN/ISOLATED_MARGIN/USDT_FUTURE/COIN_FUTURE) |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetManagedSubaccountQueryTransLogV1Resp**](SubaccountGetManagedSubaccountQueryTransLogV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

