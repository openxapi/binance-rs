# \SubAccountApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_managed_subaccount_deposit_v1**](SubAccountApi.md#create_managed_subaccount_deposit_v1) | **POST** /sapi/v1/managed-subaccount/deposit | Deposit Assets Into The Managed Sub-account(For Investor Master Account)
[**create_managed_subaccount_withdraw_v1**](SubAccountApi.md#create_managed_subaccount_withdraw_v1) | **POST** /sapi/v1/managed-subaccount/withdraw | Withdrawl Assets From The Managed Sub-account(For Investor Master Account)
[**create_sub_account_blvt_enable_v1**](SubAccountApi.md#create_sub_account_blvt_enable_v1) | **POST** /sapi/v1/sub-account/blvt/enable | Enable Leverage Token for Sub-account(For Master Account)
[**create_sub_account_eoptions_enable_v1**](SubAccountApi.md#create_sub_account_eoptions_enable_v1) | **POST** /sapi/v1/sub-account/eoptions/enable | Enable Options for Sub-account(For Master Account)(USER_DATA)
[**create_sub_account_futures_enable_v1**](SubAccountApi.md#create_sub_account_futures_enable_v1) | **POST** /sapi/v1/sub-account/futures/enable | Enable Futures for Sub-account(For Master Account)
[**create_sub_account_futures_internal_transfer_v1**](SubAccountApi.md#create_sub_account_futures_internal_transfer_v1) | **POST** /sapi/v1/sub-account/futures/internalTransfer | Sub-account Futures Asset Transfer(For Master Account)
[**create_sub_account_futures_move_position_v1**](SubAccountApi.md#create_sub_account_futures_move_position_v1) | **POST** /sapi/v1/sub-account/futures/move-position | Move Position for Sub-account (For Master Account)
[**create_sub_account_futures_transfer_v1**](SubAccountApi.md#create_sub_account_futures_transfer_v1) | **POST** /sapi/v1/sub-account/futures/transfer | Futures Transfer for Sub-account(For Master Account)
[**create_sub_account_margin_enable_v1**](SubAccountApi.md#create_sub_account_margin_enable_v1) | **POST** /sapi/v1/sub-account/margin/enable | Enable Margin for Sub-account(For Master Account)
[**create_sub_account_margin_transfer_v1**](SubAccountApi.md#create_sub_account_margin_transfer_v1) | **POST** /sapi/v1/sub-account/margin/transfer | Margin Transfer for Sub-account(For Master Account)
[**create_sub_account_sub_account_api_ip_restriction_v2**](SubAccountApi.md#create_sub_account_sub_account_api_ip_restriction_v2) | **POST** /sapi/v2/sub-account/subAccountApi/ipRestriction | Add IP Restriction for Sub-Account API key(For Master Account)
[**create_sub_account_transfer_sub_to_master_v1**](SubAccountApi.md#create_sub_account_transfer_sub_to_master_v1) | **POST** /sapi/v1/sub-account/transfer/subToMaster | Transfer to Master(For Sub-account)
[**create_sub_account_transfer_sub_to_sub_v1**](SubAccountApi.md#create_sub_account_transfer_sub_to_sub_v1) | **POST** /sapi/v1/sub-account/transfer/subToSub | Transfer to Sub-account of Same Master(For Sub-account)
[**create_sub_account_universal_transfer_v1**](SubAccountApi.md#create_sub_account_universal_transfer_v1) | **POST** /sapi/v1/sub-account/universalTransfer | Universal Transfer(For Master Account)
[**create_sub_account_virtual_sub_account_v1**](SubAccountApi.md#create_sub_account_virtual_sub_account_v1) | **POST** /sapi/v1/sub-account/virtualSubAccount | Create a Virtual Sub-account(For Master Account)
[**delete_sub_account_sub_account_api_ip_restriction_ip_list_v1**](SubAccountApi.md#delete_sub_account_sub_account_api_ip_restriction_ip_list_v1) | **DELETE** /sapi/v1/sub-account/subAccountApi/ipRestriction/ipList | Delete IP List For a Sub-account API Key(For Master Account)
[**get_capital_deposit_sub_address_v1**](SubAccountApi.md#get_capital_deposit_sub_address_v1) | **GET** /sapi/v1/capital/deposit/subAddress | Get Sub-account Deposit Address(For Master Account)
[**get_capital_deposit_sub_hisrec_v1**](SubAccountApi.md#get_capital_deposit_sub_hisrec_v1) | **GET** /sapi/v1/capital/deposit/subHisrec | Get Sub-account Deposit History(For Master Account)
[**get_managed_subaccount_account_snapshot_v1**](SubAccountApi.md#get_managed_subaccount_account_snapshot_v1) | **GET** /sapi/v1/managed-subaccount/accountSnapshot | Query Managed Sub-account Snapshot(For Investor Master Account)
[**get_managed_subaccount_asset_v1**](SubAccountApi.md#get_managed_subaccount_asset_v1) | **GET** /sapi/v1/managed-subaccount/asset | Query Managed Sub-account Asset Details(For Investor Master Account)
[**get_managed_subaccount_deposit_address_v1**](SubAccountApi.md#get_managed_subaccount_deposit_address_v1) | **GET** /sapi/v1/managed-subaccount/deposit/address | Get Managed Sub-account Deposit Address (For Investor Master Account)(USER_DATA)
[**get_managed_subaccount_fetch_future_asset_v1**](SubAccountApi.md#get_managed_subaccount_fetch_future_asset_v1) | **GET** /sapi/v1/managed-subaccount/fetch-future-asset | Query Managed Sub-account Futures Asset Details(For Investor Master Account)(USER_DATA)
[**get_managed_subaccount_info_v1**](SubAccountApi.md#get_managed_subaccount_info_v1) | **GET** /sapi/v1/managed-subaccount/info | Query Managed Sub-account List(For Investor)(USER_DATA)
[**get_managed_subaccount_margin_asset_v1**](SubAccountApi.md#get_managed_subaccount_margin_asset_v1) | **GET** /sapi/v1/managed-subaccount/marginAsset | Query Managed Sub-account Margin Asset Details(For Investor Master Account)(USER_DATA)
[**get_managed_subaccount_query_trans_log_for_investor_v1**](SubAccountApi.md#get_managed_subaccount_query_trans_log_for_investor_v1) | **GET** /sapi/v1/managed-subaccount/queryTransLogForInvestor | Query Managed Sub Account Transfer Log(For Investor Master Account)(USER_DATA)
[**get_managed_subaccount_query_trans_log_for_trade_parent_v1**](SubAccountApi.md#get_managed_subaccount_query_trans_log_for_trade_parent_v1) | **GET** /sapi/v1/managed-subaccount/queryTransLogForTradeParent | Query Managed Sub Account Transfer Log(For Trading Team Master Account)(USER_DATA)
[**get_managed_subaccount_query_trans_log_v1**](SubAccountApi.md#get_managed_subaccount_query_trans_log_v1) | **GET** /sapi/v1/managed-subaccount/query-trans-log | Query Managed Sub Account Transfer Log (For Trading Team Sub Account)(USER_DATA)
[**get_sub_account_assets_v3**](SubAccountApi.md#get_sub_account_assets_v3) | **GET** /sapi/v3/sub-account/assets | Query Sub-account Assets(For Master Account)
[**get_sub_account_assets_v4**](SubAccountApi.md#get_sub_account_assets_v4) | **GET** /sapi/v4/sub-account/assets | Query Sub-account Assets (For Master Account)(USER_DATA)
[**get_sub_account_futures_account_summary_v1**](SubAccountApi.md#get_sub_account_futures_account_summary_v1) | **GET** /sapi/v1/sub-account/futures/accountSummary | Get Summary of Sub-account's Futures Account(For Master Account)
[**get_sub_account_futures_account_summary_v2**](SubAccountApi.md#get_sub_account_futures_account_summary_v2) | **GET** /sapi/v2/sub-account/futures/accountSummary | Get Summary of Sub-account's Futures Account V2(For Master Account)
[**get_sub_account_futures_account_v1**](SubAccountApi.md#get_sub_account_futures_account_v1) | **GET** /sapi/v1/sub-account/futures/account | Get Detail on Sub-account's Futures Account(For Master Account)
[**get_sub_account_futures_account_v2**](SubAccountApi.md#get_sub_account_futures_account_v2) | **GET** /sapi/v2/sub-account/futures/account | Get Detail on Sub-account's Futures Account V2(For Master Account)
[**get_sub_account_futures_internal_transfer_v1**](SubAccountApi.md#get_sub_account_futures_internal_transfer_v1) | **GET** /sapi/v1/sub-account/futures/internalTransfer | Query Sub-account Futures Asset Transfer History(For Master Account)
[**get_sub_account_futures_move_position_v1**](SubAccountApi.md#get_sub_account_futures_move_position_v1) | **GET** /sapi/v1/sub-account/futures/move-position | Get Move Position History for Sub-account (For Master Account)
[**get_sub_account_futures_position_risk_v1**](SubAccountApi.md#get_sub_account_futures_position_risk_v1) | **GET** /sapi/v1/sub-account/futures/positionRisk | Get Futures Position-Risk of Sub-account(For Master Account)
[**get_sub_account_futures_position_risk_v2**](SubAccountApi.md#get_sub_account_futures_position_risk_v2) | **GET** /sapi/v2/sub-account/futures/positionRisk | Get Futures Position-Risk of Sub-account V2(For Master Account)
[**get_sub_account_list_v1**](SubAccountApi.md#get_sub_account_list_v1) | **GET** /sapi/v1/sub-account/list | Query Sub-account List(For Master Account)
[**get_sub_account_margin_account_summary_v1**](SubAccountApi.md#get_sub_account_margin_account_summary_v1) | **GET** /sapi/v1/sub-account/margin/accountSummary | Get Summary of Sub-account's Margin Account(For Master Account)
[**get_sub_account_margin_account_v1**](SubAccountApi.md#get_sub_account_margin_account_v1) | **GET** /sapi/v1/sub-account/margin/account | Get Detail on Sub-account's Margin Account(For Master Account)
[**get_sub_account_spot_summary_v1**](SubAccountApi.md#get_sub_account_spot_summary_v1) | **GET** /sapi/v1/sub-account/spotSummary | Query Sub-account Spot Assets Summary(For Master Account)
[**get_sub_account_status_v1**](SubAccountApi.md#get_sub_account_status_v1) | **GET** /sapi/v1/sub-account/status | Get Sub-account's Status on Margin Or Futures(For Master Account)
[**get_sub_account_sub_account_api_ip_restriction_v1**](SubAccountApi.md#get_sub_account_sub_account_api_ip_restriction_v1) | **GET** /sapi/v1/sub-account/subAccountApi/ipRestriction | Get IP Restriction for a Sub-account API Key(For Master Account)
[**get_sub_account_sub_transfer_history_v1**](SubAccountApi.md#get_sub_account_sub_transfer_history_v1) | **GET** /sapi/v1/sub-account/sub/transfer/history | Query Sub-account Spot Asset Transfer History(For Master Account)
[**get_sub_account_transaction_statistics_v1**](SubAccountApi.md#get_sub_account_transaction_statistics_v1) | **GET** /sapi/v1/sub-account/transaction-statistics | Query Sub-account Transaction Statistics(For Master Account)(USER_DATA)
[**get_sub_account_transfer_sub_user_history_v1**](SubAccountApi.md#get_sub_account_transfer_sub_user_history_v1) | **GET** /sapi/v1/sub-account/transfer/subUserHistory | Sub-account Transfer History(For Sub-account)
[**get_sub_account_universal_transfer_v1**](SubAccountApi.md#get_sub_account_universal_transfer_v1) | **GET** /sapi/v1/sub-account/universalTransfer | Query Universal Transfer History(For Master Account)



## create_managed_subaccount_deposit_v1

> models::CreateManagedSubaccountDepositV1Resp create_managed_subaccount_deposit_v1(amount, asset, timestamp, to_email, recv_window)
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

[**models::CreateManagedSubaccountDepositV1Resp**](CreateManagedSubaccountDepositV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_managed_subaccount_withdraw_v1

> models::CreateManagedSubaccountWithdrawV1Resp create_managed_subaccount_withdraw_v1(amount, asset, from_email, timestamp, recv_window, transfer_date)
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

[**models::CreateManagedSubaccountWithdrawV1Resp**](CreateManagedSubaccountWithdrawV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_blvt_enable_v1

> models::CreateSubAccountBlvtEnableV1Resp create_sub_account_blvt_enable_v1(email, enable_blvt, timestamp, recv_window)
Enable Leverage Token for Sub-account(For Master Account)

Enable Leverage Token for Sub-account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**enable_blvt** | **bool** |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSubAccountBlvtEnableV1Resp**](CreateSubAccountBlvtEnableV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_eoptions_enable_v1

> models::CreateSubAccountEoptionsEnableV1Resp create_sub_account_eoptions_enable_v1(email, timestamp, recv_window)
Enable Options for Sub-account(For Master Account)(USER_DATA)

Enable Options for Sub-account (For Master Account).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSubAccountEoptionsEnableV1Resp**](CreateSubAccountEoptionsEnableV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_futures_enable_v1

> models::CreateSubAccountFuturesEnableV1Resp create_sub_account_futures_enable_v1(email, timestamp, recv_window)
Enable Futures for Sub-account(For Master Account)

Enable Futures for Sub-account for Master Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSubAccountFuturesEnableV1Resp**](CreateSubAccountFuturesEnableV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_futures_internal_transfer_v1

> models::CreateSubAccountFuturesInternalTransferV1Resp create_sub_account_futures_internal_transfer_v1(amount, asset, from_email, futures_type, timestamp, to_email, recv_window)
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

[**models::CreateSubAccountFuturesInternalTransferV1Resp**](CreateSubAccountFuturesInternalTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_futures_move_position_v1

> models::CreateSubAccountFuturesMovePositionV1Resp create_sub_account_futures_move_position_v1(from_user_email, order_args, product_type, timestamp, to_user_email, recv_window)
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

[**models::CreateSubAccountFuturesMovePositionV1Resp**](CreateSubAccountFuturesMovePositionV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_futures_transfer_v1

> models::CreateSubAccountFuturesTransferV1Resp create_sub_account_futures_transfer_v1(amount, asset, email, timestamp, r#type, recv_window)
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

[**models::CreateSubAccountFuturesTransferV1Resp**](CreateSubAccountFuturesTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_margin_enable_v1

> models::CreateSubAccountMarginEnableV1Resp create_sub_account_margin_enable_v1(email, timestamp, recv_window)
Enable Margin for Sub-account(For Master Account)

Enable Margin for Sub-account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSubAccountMarginEnableV1Resp**](CreateSubAccountMarginEnableV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_margin_transfer_v1

> models::CreateSubAccountMarginTransferV1Resp create_sub_account_margin_transfer_v1(amount, asset, email, timestamp, r#type, recv_window)
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

[**models::CreateSubAccountMarginTransferV1Resp**](CreateSubAccountMarginTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_sub_account_api_ip_restriction_v2

> models::CreateSubAccountSubAccountApiIpRestrictionV2Resp create_sub_account_sub_account_api_ip_restriction_v2(email, status, sub_account_api_key, timestamp, ip_address, recv_window)
Add IP Restriction for Sub-Account API key(For Master Account)

Add IP Restriction for Sub-Account API key

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**status** | **String** |  | [required] |[default to ]
**sub_account_api_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**ip_address** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSubAccountSubAccountApiIpRestrictionV2Resp**](CreateSubAccountSubAccountApiIpRestrictionV2Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_transfer_sub_to_master_v1

> models::CreateSubAccountTransferSubToMasterV1Resp create_sub_account_transfer_sub_to_master_v1(amount, asset, timestamp, recv_window)
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

[**models::CreateSubAccountTransferSubToMasterV1Resp**](CreateSubAccountTransferSubToMasterV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_transfer_sub_to_sub_v1

> models::CreateSubAccountTransferSubToSubV1Resp create_sub_account_transfer_sub_to_sub_v1(amount, asset, timestamp, to_email, recv_window)
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

[**models::CreateSubAccountTransferSubToSubV1Resp**](CreateSubAccountTransferSubToSubV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_universal_transfer_v1

> models::CreateSubAccountUniversalTransferV1Resp create_sub_account_universal_transfer_v1(amount, asset, from_account_type, timestamp, to_account_type, client_tran_id, from_email, recv_window, symbol, to_email)
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

[**models::CreateSubAccountUniversalTransferV1Resp**](CreateSubAccountUniversalTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sub_account_virtual_sub_account_v1

> models::CreateSubAccountVirtualSubAccountV1Resp create_sub_account_virtual_sub_account_v1(sub_account_string, timestamp, recv_window)
Create a Virtual Sub-account(For Master Account)

Create a Virtual Sub-account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sub_account_string** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSubAccountVirtualSubAccountV1Resp**](CreateSubAccountVirtualSubAccountV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_sub_account_sub_account_api_ip_restriction_ip_list_v1

> models::DeleteSubAccountSubAccountApiIpRestrictionIpListV1Resp delete_sub_account_sub_account_api_ip_restriction_ip_list_v1(email, sub_account_api_key, timestamp, ip_address, recv_window)
Delete IP List For a Sub-account API Key(For Master Account)

Delete IP List For a Sub-account API Key

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/api-management/Delete-IP-List-For-a-Sub-account-API-Key#email-address\">Sub-account email</a> | [required] |[default to ]
**sub_account_api_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**ip_address** | Option<**String**> | Can be added in batches, separated by commas |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::DeleteSubAccountSubAccountApiIpRestrictionIpListV1Resp**](DeleteSubAccountSubAccountApiIpRestrictionIpListV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_capital_deposit_sub_address_v1

> models::GetCapitalDepositSubAddressV1Resp get_capital_deposit_sub_address_v1(email, coin, timestamp, network, amount, recv_window)
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

[**models::GetCapitalDepositSubAddressV1Resp**](GetCapitalDepositSubAddressV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_capital_deposit_sub_hisrec_v1

> Vec<models::GetCapitalDepositSubHisrecV1RespItem> get_capital_deposit_sub_hisrec_v1(email, timestamp, coin, status, start_time, end_time, limit, offset, recv_window, tx_id)
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

[**Vec<models::GetCapitalDepositSubHisrecV1RespItem>**](GetCapitalDepositSubHisrecV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_managed_subaccount_account_snapshot_v1

> models::GetManagedSubaccountAccountSnapshotV1Resp get_managed_subaccount_account_snapshot_v1(email, r#type, timestamp, start_time, end_time, limit, recv_window)
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

[**models::GetManagedSubaccountAccountSnapshotV1Resp**](GetManagedSubaccountAccountSnapshotV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_managed_subaccount_asset_v1

> Vec<models::GetManagedSubaccountAssetV1RespItem> get_managed_subaccount_asset_v1(email, timestamp, recv_window)
Query Managed Sub-account Asset Details(For Investor Master Account)

Query Managed Sub-account Asset Details

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetManagedSubaccountAssetV1RespItem>**](GetManagedSubaccountAssetV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_managed_subaccount_deposit_address_v1

> models::GetManagedSubaccountDepositAddressV1Resp get_managed_subaccount_deposit_address_v1(email, coin, timestamp, network, amount, recv_window)
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

[**models::GetManagedSubaccountDepositAddressV1Resp**](GetManagedSubaccountDepositAddressV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_managed_subaccount_fetch_future_asset_v1

> models::GetManagedSubaccountFetchFutureAssetV1Resp get_managed_subaccount_fetch_future_asset_v1(email, account_type)
Query Managed Sub-account Futures Asset Details(For Investor Master Account)(USER_DATA)

Investor can use this api to query managed sub account futures asset details

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Managed Sub Account Email | [required] |[default to ]
**account_type** | Option<**String**> | No input or input &#34;USDT_FUTURE&#34; to get UM Futures account details. Input &#34;COIN_FUTURE&#34; to get CM Futures account details. |  |[default to ]

### Return type

[**models::GetManagedSubaccountFetchFutureAssetV1Resp**](GetManagedSubaccountFetchFutureAssetV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_managed_subaccount_info_v1

> models::GetManagedSubaccountInfoV1Resp get_managed_subaccount_info_v1(timestamp, email, page, limit, recv_window)
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

[**models::GetManagedSubaccountInfoV1Resp**](GetManagedSubaccountInfoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_managed_subaccount_margin_asset_v1

> models::GetManagedSubaccountMarginAssetV1Resp get_managed_subaccount_margin_asset_v1(email, account_type)
Query Managed Sub-account Margin Asset Details(For Investor Master Account)(USER_DATA)

Investor can use this api to query managed sub account margin asset details

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Managed Sub Account Email | [required] |[default to ]
**account_type** | Option<**String**> | No input or input &#34;MARGIN&#34; to get Cross Margin account details. Input &#34;ISOLATED_MARGIN&#34; to get Isolated Margin account details. |  |[default to ]

### Return type

[**models::GetManagedSubaccountMarginAssetV1Resp**](GetManagedSubaccountMarginAssetV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_managed_subaccount_query_trans_log_for_investor_v1

> models::GetManagedSubaccountQueryTransLogForInvestorV1Resp get_managed_subaccount_query_trans_log_for_investor_v1(email, start_time, end_time, page, limit, transfers, transfer_function_account_type)
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

[**models::GetManagedSubaccountQueryTransLogForInvestorV1Resp**](GetManagedSubaccountQueryTransLogForInvestorV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_managed_subaccount_query_trans_log_for_trade_parent_v1

> models::GetManagedSubaccountQueryTransLogForTradeParentV1Resp get_managed_subaccount_query_trans_log_for_trade_parent_v1(email, start_time, end_time, page, limit, transfers, transfer_function_account_type)
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

[**models::GetManagedSubaccountQueryTransLogForTradeParentV1Resp**](GetManagedSubaccountQueryTransLogForTradeParentV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_managed_subaccount_query_trans_log_v1

> models::GetManagedSubaccountQueryTransLogV1Resp get_managed_subaccount_query_trans_log_v1(start_time, end_time, page, limit, timestamp, transfers, transfer_function_account_type, recv_window)
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

[**models::GetManagedSubaccountQueryTransLogV1Resp**](GetManagedSubaccountQueryTransLogV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_assets_v3

> models::GetSubAccountAssetsV3Resp get_sub_account_assets_v3(email, timestamp, recv_window)
Query Sub-account Assets(For Master Account)

Fetch sub-account assets

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Sub account email | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSubAccountAssetsV3Resp**](GetSubAccountAssetsV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_assets_v4

> models::GetSubAccountAssetsV4Resp get_sub_account_assets_v4(email, timestamp, recv_window)
Query Sub-account Assets (For Master Account)(USER_DATA)

Fetch sub-account assets

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Sub Account Email | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSubAccountAssetsV4Resp**](GetSubAccountAssetsV4Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_futures_account_summary_v1

> models::GetSubAccountFuturesAccountSummaryV1Resp get_sub_account_futures_account_summary_v1(timestamp, recv_window)
Get Summary of Sub-account's Futures Account(For Master Account)

Get Summary of Sub-account's Futures Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSubAccountFuturesAccountSummaryV1Resp**](GetSubAccountFuturesAccountSummaryV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_futures_account_summary_v2

> models::GetSubAccountFuturesAccountSummaryV2Resp get_sub_account_futures_account_summary_v2(futures_type, timestamp, page, limit, recv_window)
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

[**models::GetSubAccountFuturesAccountSummaryV2Resp**](GetSubAccountFuturesAccountSummaryV2Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_futures_account_v1

> models::GetSubAccountFuturesAccountV1Resp get_sub_account_futures_account_v1(email, timestamp, recv_window)
Get Detail on Sub-account's Futures Account(For Master Account)

Get Detail on Sub-account's Futures Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/asset-management/Get-Detail-on-Sub-accounts-Futures-Account#email-address\">Sub-account email</a> | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSubAccountFuturesAccountV1Resp**](GetSubAccountFuturesAccountV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_futures_account_v2

> models::GetSubAccountFuturesAccountV2Resp get_sub_account_futures_account_v2(email, futures_type, timestamp, recv_window)
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

[**models::GetSubAccountFuturesAccountV2Resp**](GetSubAccountFuturesAccountV2Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_futures_internal_transfer_v1

> models::GetSubAccountFuturesInternalTransferV1Resp get_sub_account_futures_internal_transfer_v1(email, futures_type, timestamp, start_time, end_time, page, limit, recv_window)
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

[**models::GetSubAccountFuturesInternalTransferV1Resp**](GetSubAccountFuturesInternalTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_futures_move_position_v1

> models::GetSubAccountFuturesMovePositionV1Resp get_sub_account_futures_move_position_v1(symbol, page, row, timestamp, start_time, end_time, recv_window)
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

[**models::GetSubAccountFuturesMovePositionV1Resp**](GetSubAccountFuturesMovePositionV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_futures_position_risk_v1

> Vec<models::GetSubAccountFuturesPositionRiskV1RespItem> get_sub_account_futures_position_risk_v1(email, timestamp, recv_window)
Get Futures Position-Risk of Sub-account(For Master Account)

Get Futures Position-Risk of Sub-account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/account-management/Get-Futures-Position-Risk-of-Sub-account#email-address\">Sub-account email</a> | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetSubAccountFuturesPositionRiskV1RespItem>**](GetSubAccountFuturesPositionRiskV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_futures_position_risk_v2

> models::GetSubAccountFuturesPositionRiskV2Resp get_sub_account_futures_position_risk_v2(email, futures_type, timestamp, recv_window)
Get Futures Position-Risk of Sub-account V2(For Master Account)

Get Futures Position-Risk of Sub-account V2

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/account-management/Get-Futures-Position-Risk-of-Sub-account-V2#email-address\">Sub-account email</a> | [required] |[default to ]
**futures_type** | **i32** | 1:USDT Margined Futures, 2:COIN Margined Futures | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSubAccountFuturesPositionRiskV2Resp**](GetSubAccountFuturesPositionRiskV2Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_list_v1

> models::GetSubAccountListV1Resp get_sub_account_list_v1(timestamp, email, is_freeze, page, limit, recv_window)
Query Sub-account List(For Master Account)

Query Sub-account List

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**email** | Option<**String**> | <a href=\"/docs/sub_account/account-management/Query-Sub-account-List#email-address\">Sub-account email</a> |  |[default to ]
**is_freeze** | Option<**String**> | true or false |  |[default to ]
**page** | Option<**i32**> | Default value: 1 |  |
**limit** | Option<**i32**> | Default value: 1, Max value: 200 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSubAccountListV1Resp**](GetSubAccountListV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_margin_account_summary_v1

> models::GetSubAccountMarginAccountSummaryV1Resp get_sub_account_margin_account_summary_v1(timestamp, recv_window)
Get Summary of Sub-account's Margin Account(For Master Account)

Get Summary of Sub-account's Margin Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSubAccountMarginAccountSummaryV1Resp**](GetSubAccountMarginAccountSummaryV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_margin_account_v1

> models::GetSubAccountMarginAccountV1Resp get_sub_account_margin_account_v1(email, timestamp, recv_window)
Get Detail on Sub-account's Margin Account(For Master Account)

Get Detail on Sub-account's Margin Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/asset-management/Get-Detail-on-Sub-accounts-Margin-Account#email-address\">Sub-account email</a> | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSubAccountMarginAccountV1Resp**](GetSubAccountMarginAccountV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_spot_summary_v1

> models::GetSubAccountSpotSummaryV1Resp get_sub_account_spot_summary_v1(timestamp, email, page, size, recv_window)
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

[**models::GetSubAccountSpotSummaryV1Resp**](GetSubAccountSpotSummaryV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_status_v1

> Vec<models::GetSubAccountStatusV1RespItem> get_sub_account_status_v1(timestamp, email, recv_window)
Get Sub-account's Status on Margin Or Futures(For Master Account)

Get Sub-account's Status on Margin Or Futures

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**email** | Option<**String**> | <a href=\"/docs/sub_account/account-management/Get-Sub-accounts-Status-on-Margin-Or-Futures#email-address\">Sub-account email</a> |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetSubAccountStatusV1RespItem>**](GetSubAccountStatusV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_sub_account_api_ip_restriction_v1

> models::GetSubAccountSubAccountApiIpRestrictionV1Resp get_sub_account_sub_account_api_ip_restriction_v1(email, sub_account_api_key, timestamp, recv_window)
Get IP Restriction for a Sub-account API Key(For Master Account)

Get IP Restriction for a Sub-account API Key

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/api-management#email-address\">Sub-account email</a> | [required] |[default to ]
**sub_account_api_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSubAccountSubAccountApiIpRestrictionV1Resp**](GetSubAccountSubAccountApiIpRestrictionV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_sub_transfer_history_v1

> Vec<models::GetSubAccountSubTransferHistoryV1RespItem> get_sub_account_sub_transfer_history_v1(timestamp, from_email, to_email, start_time, end_time, page, limit, recv_window)
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

[**Vec<models::GetSubAccountSubTransferHistoryV1RespItem>**](GetSubAccountSubTransferHistoryV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_transaction_statistics_v1

> models::SubaccountGetSubAccountTransactionStatisticsV1Resp get_sub_account_transaction_statistics_v1(email, timestamp, recv_window)
Query Sub-account Transaction Statistics(For Master Account)(USER_DATA)

Query Sub-account Transaction statistics (For Master Account).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | Sub user email | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountTransactionStatisticsV1Resp**](SubaccountGetSubAccountTransactionStatisticsV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_transfer_sub_user_history_v1

> Vec<models::GetSubAccountTransferSubUserHistoryV1RespItem> get_sub_account_transfer_sub_user_history_v1(timestamp, asset, r#type, start_time, end_time, limit, return_fail_history, recv_window)
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

[**Vec<models::GetSubAccountTransferSubUserHistoryV1RespItem>**](GetSubAccountTransferSubUserHistoryV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sub_account_universal_transfer_v1

> models::GetSubAccountUniversalTransferV1Resp get_sub_account_universal_transfer_v1(timestamp, from_email, to_email, client_tran_id, start_time, end_time, page, limit, recv_window)
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

[**models::GetSubAccountUniversalTransferV1Resp**](GetSubAccountUniversalTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

