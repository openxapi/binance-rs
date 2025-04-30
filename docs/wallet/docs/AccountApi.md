# \AccountApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**wallet_create_account_disable_fast_withdraw_switch_v1**](AccountApi.md#wallet_create_account_disable_fast_withdraw_switch_v1) | **POST** /sapi/v1/account/disableFastWithdrawSwitch | Disable Fast Withdraw Switch (USER_DATA)
[**wallet_create_account_enable_fast_withdraw_switch_v1**](AccountApi.md#wallet_create_account_enable_fast_withdraw_switch_v1) | **POST** /sapi/v1/account/enableFastWithdrawSwitch | Enable Fast Withdraw Switch (USER_DATA)
[**wallet_get_account_api_restrictions_v1**](AccountApi.md#wallet_get_account_api_restrictions_v1) | **GET** /sapi/v1/account/apiRestrictions | Get API Key Permission (USER_DATA)
[**wallet_get_account_api_trading_status_v1**](AccountApi.md#wallet_get_account_api_trading_status_v1) | **GET** /sapi/v1/account/apiTradingStatus | Account API Trading Status (USER_DATA)
[**wallet_get_account_info_v1**](AccountApi.md#wallet_get_account_info_v1) | **GET** /sapi/v1/account/info | Account info (USER_DATA)
[**wallet_get_account_snapshot_v1**](AccountApi.md#wallet_get_account_snapshot_v1) | **GET** /sapi/v1/accountSnapshot | Daily Account Snapshot (USER_DATA)
[**wallet_get_account_status_v1**](AccountApi.md#wallet_get_account_status_v1) | **GET** /sapi/v1/account/status | Account Status (USER_DATA)



## wallet_create_account_disable_fast_withdraw_switch_v1

> serde_json::Value wallet_create_account_disable_fast_withdraw_switch_v1(timestamp, recv_window)
Disable Fast Withdraw Switch (USER_DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_create_account_enable_fast_withdraw_switch_v1

> serde_json::Value wallet_create_account_enable_fast_withdraw_switch_v1(timestamp, recv_window)
Enable Fast Withdraw Switch (USER_DATA)

Enable Fast Withdraw Switch (USER_DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_account_api_restrictions_v1

> models::WalletGetAccountApiRestrictionsV1Resp wallet_get_account_api_restrictions_v1(timestamp, recv_window)
Get API Key Permission (USER_DATA)

Get API Key Permission

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::WalletGetAccountApiRestrictionsV1Resp**](WalletGetAccountApiRestrictionsV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_account_api_trading_status_v1

> models::WalletGetAccountApiTradingStatusV1Resp wallet_get_account_api_trading_status_v1(timestamp, recv_window)
Account API Trading Status (USER_DATA)

Fetch account api trading status detail.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::WalletGetAccountApiTradingStatusV1Resp**](WalletGetAccountApiTradingStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_account_info_v1

> models::WalletGetAccountInfoV1Resp wallet_get_account_info_v1(timestamp, recv_window)
Account info (USER_DATA)

Fetch account info detail.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::WalletGetAccountInfoV1Resp**](WalletGetAccountInfoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_account_snapshot_v1

> models::WalletGetAccountSnapshotV1Resp wallet_get_account_snapshot_v1(r#type, timestamp, start_time, end_time, limit, recv_window)
Daily Account Snapshot (USER_DATA)

Daily account snapshot

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**r#type** | **String** | &#34;SPOT&#34;, &#34;MARGIN&#34;, &#34;FUTURES&#34; | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | min 7, max 30, default 7 |  |[default to 7]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::WalletGetAccountSnapshotV1Resp**](WalletGetAccountSnapshotV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_account_status_v1

> models::WalletGetAccountStatusV1Resp wallet_get_account_status_v1(timestamp, recv_window)
Account Status (USER_DATA)

Fetch account status detail.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::WalletGetAccountStatusV1Resp**](WalletGetAccountStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

