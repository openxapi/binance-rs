# \AssetManagementApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**subaccount_create_sub_account_futures_internal_transfer_v1**](AssetManagementApi.md#subaccount_create_sub_account_futures_internal_transfer_v1) | **POST** /sapi/v1/sub-account/futures/internalTransfer | Sub-account Futures Asset Transfer(For Master Account)
[**subaccount_create_sub_account_futures_move_position_v1**](AssetManagementApi.md#subaccount_create_sub_account_futures_move_position_v1) | **POST** /sapi/v1/sub-account/futures/move-position | Move Position for Sub-account (For Master Account)
[**subaccount_create_sub_account_futures_transfer_v1**](AssetManagementApi.md#subaccount_create_sub_account_futures_transfer_v1) | **POST** /sapi/v1/sub-account/futures/transfer | Futures Transfer for Sub-account(For Master Account)
[**subaccount_create_sub_account_margin_transfer_v1**](AssetManagementApi.md#subaccount_create_sub_account_margin_transfer_v1) | **POST** /sapi/v1/sub-account/margin/transfer | Margin Transfer for Sub-account(For Master Account)
[**subaccount_create_sub_account_transfer_sub_to_master_v1**](AssetManagementApi.md#subaccount_create_sub_account_transfer_sub_to_master_v1) | **POST** /sapi/v1/sub-account/transfer/subToMaster | Transfer to Master(For Sub-account)
[**subaccount_create_sub_account_transfer_sub_to_sub_v1**](AssetManagementApi.md#subaccount_create_sub_account_transfer_sub_to_sub_v1) | **POST** /sapi/v1/sub-account/transfer/subToSub | Transfer to Sub-account of Same Master(For Sub-account)
[**subaccount_create_sub_account_universal_transfer_v1**](AssetManagementApi.md#subaccount_create_sub_account_universal_transfer_v1) | **POST** /sapi/v1/sub-account/universalTransfer | Universal Transfer(For Master Account)
[**subaccount_get_capital_deposit_sub_address_v1**](AssetManagementApi.md#subaccount_get_capital_deposit_sub_address_v1) | **GET** /sapi/v1/capital/deposit/subAddress | Get Sub-account Deposit Address(For Master Account)
[**subaccount_get_capital_deposit_sub_hisrec_v1**](AssetManagementApi.md#subaccount_get_capital_deposit_sub_hisrec_v1) | **GET** /sapi/v1/capital/deposit/subHisrec | Get Sub-account Deposit History(For Master Account)
[**subaccount_get_sub_account_assets_v3**](AssetManagementApi.md#subaccount_get_sub_account_assets_v3) | **GET** /sapi/v3/sub-account/assets | Query Sub-account Assets(For Master Account)
[**subaccount_get_sub_account_assets_v4**](AssetManagementApi.md#subaccount_get_sub_account_assets_v4) | **GET** /sapi/v4/sub-account/assets | Query Sub-account Assets (For Master Account)(USER_DATA)
[**subaccount_get_sub_account_futures_account_summary_v1**](AssetManagementApi.md#subaccount_get_sub_account_futures_account_summary_v1) | **GET** /sapi/v1/sub-account/futures/accountSummary | Get Summary of Sub-account's Futures Account(For Master Account)
[**subaccount_get_sub_account_futures_account_summary_v2**](AssetManagementApi.md#subaccount_get_sub_account_futures_account_summary_v2) | **GET** /sapi/v2/sub-account/futures/accountSummary | Get Summary of Sub-account's Futures Account V2(For Master Account)
[**subaccount_get_sub_account_futures_account_v1**](AssetManagementApi.md#subaccount_get_sub_account_futures_account_v1) | **GET** /sapi/v1/sub-account/futures/account | Get Detail on Sub-account's Futures Account(For Master Account)
[**subaccount_get_sub_account_futures_account_v2**](AssetManagementApi.md#subaccount_get_sub_account_futures_account_v2) | **GET** /sapi/v2/sub-account/futures/account | Get Detail on Sub-account's Futures Account V2(For Master Account)
[**subaccount_get_sub_account_futures_internal_transfer_v1**](AssetManagementApi.md#subaccount_get_sub_account_futures_internal_transfer_v1) | **GET** /sapi/v1/sub-account/futures/internalTransfer | Query Sub-account Futures Asset Transfer History(For Master Account)
[**subaccount_get_sub_account_futures_move_position_v1**](AssetManagementApi.md#subaccount_get_sub_account_futures_move_position_v1) | **GET** /sapi/v1/sub-account/futures/move-position | Get Move Position History for Sub-account (For Master Account)
[**subaccount_get_sub_account_margin_account_summary_v1**](AssetManagementApi.md#subaccount_get_sub_account_margin_account_summary_v1) | **GET** /sapi/v1/sub-account/margin/accountSummary | Get Summary of Sub-account's Margin Account(For Master Account)
[**subaccount_get_sub_account_margin_account_v1**](AssetManagementApi.md#subaccount_get_sub_account_margin_account_v1) | **GET** /sapi/v1/sub-account/margin/account | Get Detail on Sub-account's Margin Account(For Master Account)
[**subaccount_get_sub_account_spot_summary_v1**](AssetManagementApi.md#subaccount_get_sub_account_spot_summary_v1) | **GET** /sapi/v1/sub-account/spotSummary | Query Sub-account Spot Assets Summary(For Master Account)
[**subaccount_get_sub_account_sub_transfer_history_v1**](AssetManagementApi.md#subaccount_get_sub_account_sub_transfer_history_v1) | **GET** /sapi/v1/sub-account/sub/transfer/history | Query Sub-account Spot Asset Transfer History(For Master Account)
[**subaccount_get_sub_account_transfer_sub_user_history_v1**](AssetManagementApi.md#subaccount_get_sub_account_transfer_sub_user_history_v1) | **GET** /sapi/v1/sub-account/transfer/subUserHistory | Sub-account Transfer History(For Sub-account)
[**subaccount_get_sub_account_universal_transfer_v1**](AssetManagementApi.md#subaccount_get_sub_account_universal_transfer_v1) | **GET** /sapi/v1/sub-account/universalTransfer | Query Universal Transfer History(For Master Account)



## subaccount_create_sub_account_futures_internal_transfer_v1

> models::SubaccountCreateSubAccountFuturesInternalTransferV1Resp subaccount_create_sub_account_futures_internal_transfer_v1(amount, asset, from_email, futures_type, timestamp, to_email, recv_window)
Sub-account Futures Asset Transfer(For Master Account)

Sub-account Futures Asset Transfer

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**from_email** | **String** |  | [required] |[default to ]
**futures_type** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**to_email** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateSubAccountFuturesInternalTransferV1Resp**](SubaccountCreateSubAccountFuturesInternalTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_create_sub_account_futures_move_position_v1

> models::SubaccountCreateSubAccountFuturesMovePositionV1Resp subaccount_create_sub_account_futures_move_position_v1(from_user_email, order_args, product_type, timestamp, to_user_email, recv_window)
Move Position for Sub-account (For Master Account)

Move position between sub-master, master-sub, or sub-sub accounts when necessary

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**from_user_email** | **String** |  | [required] |[default to ]
**order_args** | [**Vec<serde_json::Value>**](serde_json::Value.md) |  | [required] |
**product_type** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**to_user_email** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateSubAccountFuturesMovePositionV1Resp**](SubaccountCreateSubAccountFuturesMovePositionV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_create_sub_account_futures_transfer_v1

> models::SubaccountCreateSubAccountFuturesTransferV1Resp subaccount_create_sub_account_futures_transfer_v1(amount, asset, email, timestamp, r#type, recv_window)
Futures Transfer for Sub-account(For Master Account)

Futures Transfer for Sub-account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**email** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **i32** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateSubAccountFuturesTransferV1Resp**](SubaccountCreateSubAccountFuturesTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_create_sub_account_margin_transfer_v1

> models::SubaccountCreateSubAccountMarginTransferV1Resp subaccount_create_sub_account_margin_transfer_v1(amount, asset, email, timestamp, r#type, recv_window)
Margin Transfer for Sub-account(For Master Account)

Margin Transfer for Sub-account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**email** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **i32** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateSubAccountMarginTransferV1Resp**](SubaccountCreateSubAccountMarginTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_create_sub_account_transfer_sub_to_master_v1

> models::SubaccountCreateSubAccountTransferSubToMasterV1Resp subaccount_create_sub_account_transfer_sub_to_master_v1(amount, asset, timestamp, recv_window)
Transfer to Master(For Sub-account)

Transfer to Master

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateSubAccountTransferSubToMasterV1Resp**](SubaccountCreateSubAccountTransferSubToMasterV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_create_sub_account_transfer_sub_to_sub_v1

> models::SubaccountCreateSubAccountTransferSubToSubV1Resp subaccount_create_sub_account_transfer_sub_to_sub_v1(amount, asset, timestamp, to_email, recv_window)
Transfer to Sub-account of Same Master(For Sub-account)

Transfer to Sub-account of Same Master

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**to_email** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateSubAccountTransferSubToSubV1Resp**](SubaccountCreateSubAccountTransferSubToSubV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_create_sub_account_universal_transfer_v1

> models::SubaccountCreateSubAccountUniversalTransferV1Resp subaccount_create_sub_account_universal_transfer_v1(amount, asset, from_account_type, timestamp, to_account_type, client_tran_id, from_email, recv_window, symbol, to_email)
Universal Transfer(For Master Account)

Universal Transfer

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**from_account_type** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**to_account_type** | **String** |  | [required] |[default to ]
**client_tran_id** | Option<**String**> |  |  |[default to ]
**from_email** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**symbol** | Option<**String**> |  |  |[default to ]
**to_email** | Option<**String**> |  |  |[default to ]

### Return type

[**models::SubaccountCreateSubAccountUniversalTransferV1Resp**](SubaccountCreateSubAccountUniversalTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_capital_deposit_sub_address_v1

> models::SubaccountGetCapitalDepositSubAddressV1Resp subaccount_get_capital_deposit_sub_address_v1(email, coin, timestamp, network, amount, recv_window)
Get Sub-account Deposit Address(For Master Account)

Fetch sub-account deposit address

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Sub account email | [required] |[default to ]
**coin** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**network** | Option<**String**> |  |  |[default to ]
**amount** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetCapitalDepositSubAddressV1Resp**](SubaccountGetCapitalDepositSubAddressV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_capital_deposit_sub_hisrec_v1

> Vec<models::SubaccountGetCapitalDepositSubHisrecV1RespItem> subaccount_get_capital_deposit_sub_hisrec_v1(email, timestamp, coin, status, start_time, end_time, limit, offset, recv_window, tx_id)
Get Sub-account Deposit History(For Master Account)

Fetch sub-account deposit history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Sub account email | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**coin** | Option<**String**> |  |  |[default to ]
**status** | Option<**i32**> | 0(0:pending,6: credited but cannot withdraw,7:Wrong Deposit,8:Waiting User confirm,1:success) |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> |  |  |
**offset** | Option<**i32**> | default:0 |  |
**recv_window** | Option<**i64**> |  |  |
**tx_id** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::SubaccountGetCapitalDepositSubHisrecV1RespItem>**](SubaccountGetCapitalDepositSubHisrecV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_assets_v3

> models::SubaccountGetSubAccountAssetsV3Resp subaccount_get_sub_account_assets_v3(email, timestamp, recv_window)
Query Sub-account Assets(For Master Account)

Fetch sub-account assets

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Sub account email | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountAssetsV3Resp**](SubaccountGetSubAccountAssetsV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_assets_v4

> models::SubaccountGetSubAccountAssetsV4Resp subaccount_get_sub_account_assets_v4(email, timestamp, recv_window)
Query Sub-account Assets (For Master Account)(USER_DATA)

Fetch sub-account assets

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Sub Account Email | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountAssetsV4Resp**](SubaccountGetSubAccountAssetsV4Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_futures_account_summary_v1

> models::SubaccountGetSubAccountFuturesAccountSummaryV1Resp subaccount_get_sub_account_futures_account_summary_v1(timestamp, recv_window)
Get Summary of Sub-account's Futures Account(For Master Account)

Get Summary of Sub-account's Futures Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountFuturesAccountSummaryV1Resp**](SubaccountGetSubAccountFuturesAccountSummaryV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_futures_account_summary_v2

> models::SubaccountGetSubAccountFuturesAccountSummaryV2Resp subaccount_get_sub_account_futures_account_summary_v2(futures_type, timestamp, page, limit, recv_window)
Get Summary of Sub-account's Futures Account V2(For Master Account)

Get Summary of Sub-account's Futures Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**futures_type** | **i32** | 1:USDT Margined Futures, 2:COIN Margined Futures | [required] |
**timestamp** | **i64** |  | [required] |
**page** | Option<**i32**> | default:1 |  |
**limit** | Option<**i32**> | default:10, max:20 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountFuturesAccountSummaryV2Resp**](SubaccountGetSubAccountFuturesAccountSummaryV2Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_futures_account_v1

> models::SubaccountGetSubAccountFuturesAccountV1Resp subaccount_get_sub_account_futures_account_v1(email, timestamp, recv_window)
Get Detail on Sub-account's Futures Account(For Master Account)

Get Detail on Sub-account's Futures Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/asset-management/Get-Detail-on-Sub-accounts-Futures-Account#email-address\">Sub-account email</a> | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountFuturesAccountV1Resp**](SubaccountGetSubAccountFuturesAccountV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_futures_account_v2

> models::SubaccountGetSubAccountFuturesAccountV2Resp subaccount_get_sub_account_futures_account_v2(email, futures_type, timestamp, recv_window)
Get Detail on Sub-account's Futures Account V2(For Master Account)

Get Detail on Sub-account's Futures Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/asset-management/Get-Detail-on-Sub-accounts-Futures-Account-V2#email-address\">Sub-account email</a> | [required] |[default to ]
**futures_type** | **i32** | 1:USDT Margined Futures, 2:COIN Margined Futures | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountFuturesAccountV2Resp**](SubaccountGetSubAccountFuturesAccountV2Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_futures_internal_transfer_v1

> models::SubaccountGetSubAccountFuturesInternalTransferV1Resp subaccount_get_sub_account_futures_internal_transfer_v1(email, futures_type, timestamp, start_time, end_time, page, limit, recv_window)
Query Sub-account Futures Asset Transfer History(For Master Account)

Query Sub-account Futures Asset Transfer History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/asset-management/Query-Sub-account-Futures-Asset-Transfer-History#email-address\">Sub-account email</a> | [required] |[default to ]
**futures_type** | **i64** | 1:USDT-margined Futures，2: Coin-margined Futures | [required] |
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> | Cannot be earlier than 1 month ago |  |
**end_time** | Option<**i64**> |  |  |
**page** | Option<**i32**> | Default value: 1 |  |
**limit** | Option<**i32**> | Default value: 50, Max value: 500 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountFuturesInternalTransferV1Resp**](SubaccountGetSubAccountFuturesInternalTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_futures_move_position_v1

> models::SubaccountGetSubAccountFuturesMovePositionV1Resp subaccount_get_sub_account_futures_move_position_v1(symbol, page, row, timestamp, start_time, end_time, recv_window)
Get Move Position History for Sub-account (For Master Account)

Query move position history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**page** | **i32** |  | [required] |
**row** | **i32** |  | [required] |
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountFuturesMovePositionV1Resp**](SubaccountGetSubAccountFuturesMovePositionV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_margin_account_summary_v1

> models::SubaccountGetSubAccountMarginAccountSummaryV1Resp subaccount_get_sub_account_margin_account_summary_v1(timestamp, recv_window)
Get Summary of Sub-account's Margin Account(For Master Account)

Get Summary of Sub-account's Margin Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountMarginAccountSummaryV1Resp**](SubaccountGetSubAccountMarginAccountSummaryV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_margin_account_v1

> models::SubaccountGetSubAccountMarginAccountV1Resp subaccount_get_sub_account_margin_account_v1(email, timestamp, recv_window)
Get Detail on Sub-account's Margin Account(For Master Account)

Get Detail on Sub-account's Margin Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/asset-management/Get-Detail-on-Sub-accounts-Margin-Account#email-address\">Sub-account email</a> | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountMarginAccountV1Resp**](SubaccountGetSubAccountMarginAccountV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_spot_summary_v1

> models::SubaccountGetSubAccountSpotSummaryV1Resp subaccount_get_sub_account_spot_summary_v1(timestamp, email, page, size, recv_window)
Query Sub-account Spot Assets Summary(For Master Account)

Get BTC valued asset summary of subaccounts.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**email** | Option<**String**> | Sub account email |  |[default to ]
**page** | Option<**i64**> | default 1 |  |[default to 1]
**size** | Option<**i64**> | default 10, max 20 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountSpotSummaryV1Resp**](SubaccountGetSubAccountSpotSummaryV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_sub_transfer_history_v1

> Vec<models::SubaccountGetSubAccountSubTransferHistoryV1RespItem> subaccount_get_sub_account_sub_transfer_history_v1(timestamp, from_email, to_email, start_time, end_time, page, limit, recv_window)
Query Sub-account Spot Asset Transfer History(For Master Account)

Query Sub-account Spot Asset Transfer History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**from_email** | Option<**String**> |  |  |[default to ]
**to_email** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**page** | Option<**i32**> | Default value: 1 |  |
**limit** | Option<**i32**> | Default value: 500 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::SubaccountGetSubAccountSubTransferHistoryV1RespItem>**](SubaccountGetSubAccountSubTransferHistoryV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_transfer_sub_user_history_v1

> Vec<models::SubaccountGetSubAccountTransferSubUserHistoryV1RespItem> subaccount_get_sub_account_transfer_sub_user_history_v1(timestamp, asset, r#type, start_time, end_time, limit, return_fail_history, recv_window)
Sub-account Transfer History(For Sub-account)

Sub-account Transfer History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> | If not sent, result of all assets will be returned |  |[default to ]
**r#type** | Option<**i32**> | 1: transfer in, 2: transfer out |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500 |  |[default to 500]
**return_fail_history** | Option<**bool**> | Default `False`, return PROCESS and SUCCESS status history; If `True`,return PROCESS and SUCCESS and FAILURE status history |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::SubaccountGetSubAccountTransferSubUserHistoryV1RespItem>**](SubaccountGetSubAccountTransferSubUserHistoryV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_universal_transfer_v1

> models::SubaccountGetSubAccountUniversalTransferV1Resp subaccount_get_sub_account_universal_transfer_v1(timestamp, from_email, to_email, client_tran_id, start_time, end_time, page, limit, recv_window)
Query Universal Transfer History(For Master Account)

Query Universal Transfer History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**from_email** | Option<**String**> |  |  |[default to ]
**to_email** | Option<**String**> |  |  |[default to ]
**client_tran_id** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**page** | Option<**i32**> | Default 1 |  |[default to 1]
**limit** | Option<**i32**> | Default 500, Max 500 |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountUniversalTransferV1Resp**](SubaccountGetSubAccountUniversalTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

