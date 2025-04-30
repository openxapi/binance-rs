# \AccountManagementApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**subaccount_create_sub_account_blvt_enable_v1**](AccountManagementApi.md#subaccount_create_sub_account_blvt_enable_v1) | **POST** /sapi/v1/sub-account/blvt/enable | Enable Leverage Token for Sub-account(For Master Account)
[**subaccount_create_sub_account_eoptions_enable_v1**](AccountManagementApi.md#subaccount_create_sub_account_eoptions_enable_v1) | **POST** /sapi/v1/sub-account/eoptions/enable | Enable Options for Sub-account(For Master Account)(USER_DATA)
[**subaccount_create_sub_account_futures_enable_v1**](AccountManagementApi.md#subaccount_create_sub_account_futures_enable_v1) | **POST** /sapi/v1/sub-account/futures/enable | Enable Futures for Sub-account(For Master Account)
[**subaccount_create_sub_account_margin_enable_v1**](AccountManagementApi.md#subaccount_create_sub_account_margin_enable_v1) | **POST** /sapi/v1/sub-account/margin/enable | Enable Margin for Sub-account(For Master Account)
[**subaccount_create_sub_account_virtual_sub_account_v1**](AccountManagementApi.md#subaccount_create_sub_account_virtual_sub_account_v1) | **POST** /sapi/v1/sub-account/virtualSubAccount | Create a Virtual Sub-account(For Master Account)
[**subaccount_get_sub_account_futures_position_risk_v1**](AccountManagementApi.md#subaccount_get_sub_account_futures_position_risk_v1) | **GET** /sapi/v1/sub-account/futures/positionRisk | Get Futures Position-Risk of Sub-account(For Master Account)
[**subaccount_get_sub_account_futures_position_risk_v2**](AccountManagementApi.md#subaccount_get_sub_account_futures_position_risk_v2) | **GET** /sapi/v2/sub-account/futures/positionRisk | Get Futures Position-Risk of Sub-account V2(For Master Account)
[**subaccount_get_sub_account_list_v1**](AccountManagementApi.md#subaccount_get_sub_account_list_v1) | **GET** /sapi/v1/sub-account/list | Query Sub-account List(For Master Account)
[**subaccount_get_sub_account_status_v1**](AccountManagementApi.md#subaccount_get_sub_account_status_v1) | **GET** /sapi/v1/sub-account/status | Get Sub-account's Status on Margin Or Futures(For Master Account)
[**subaccount_get_sub_account_transaction_statistics_v1**](AccountManagementApi.md#subaccount_get_sub_account_transaction_statistics_v1) | **GET** /sapi/v1/sub-account/transaction-statistics | Query Sub-account Transaction Statistics(For Master Account)(USER_DATA)



## subaccount_create_sub_account_blvt_enable_v1

> models::SubaccountCreateSubAccountBlvtEnableV1Resp subaccount_create_sub_account_blvt_enable_v1(email, enable_blvt, timestamp, recv_window)
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

[**models::SubaccountCreateSubAccountBlvtEnableV1Resp**](SubaccountCreateSubAccountBlvtEnableV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_create_sub_account_eoptions_enable_v1

> models::SubaccountCreateSubAccountEoptionsEnableV1Resp subaccount_create_sub_account_eoptions_enable_v1(email, timestamp, recv_window)
Enable Options for Sub-account(For Master Account)(USER_DATA)

Enable Options for Sub-account (For Master Account).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateSubAccountEoptionsEnableV1Resp**](SubaccountCreateSubAccountEoptionsEnableV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_create_sub_account_futures_enable_v1

> models::SubaccountCreateSubAccountFuturesEnableV1Resp subaccount_create_sub_account_futures_enable_v1(email, timestamp, recv_window)
Enable Futures for Sub-account(For Master Account)

Enable Futures for Sub-account for Master Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateSubAccountFuturesEnableV1Resp**](SubaccountCreateSubAccountFuturesEnableV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_create_sub_account_margin_enable_v1

> models::SubaccountCreateSubAccountMarginEnableV1Resp subaccount_create_sub_account_margin_enable_v1(email, timestamp, recv_window)
Enable Margin for Sub-account(For Master Account)

Enable Margin for Sub-account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateSubAccountMarginEnableV1Resp**](SubaccountCreateSubAccountMarginEnableV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_create_sub_account_virtual_sub_account_v1

> models::SubaccountCreateSubAccountVirtualSubAccountV1Resp subaccount_create_sub_account_virtual_sub_account_v1(sub_account_string, timestamp, recv_window)
Create a Virtual Sub-account(For Master Account)

Create a Virtual Sub-account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sub_account_string** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateSubAccountVirtualSubAccountV1Resp**](SubaccountCreateSubAccountVirtualSubAccountV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_futures_position_risk_v1

> Vec<models::SubaccountGetSubAccountFuturesPositionRiskV1RespItem> subaccount_get_sub_account_futures_position_risk_v1(email, timestamp, recv_window)
Get Futures Position-Risk of Sub-account(For Master Account)

Get Futures Position-Risk of Sub-account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/account-management/Get-Futures-Position-Risk-of-Sub-account#email-address\">Sub-account email</a> | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::SubaccountGetSubAccountFuturesPositionRiskV1RespItem>**](SubaccountGetSubAccountFuturesPositionRiskV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_futures_position_risk_v2

> models::SubaccountGetSubAccountFuturesPositionRiskV2Resp subaccount_get_sub_account_futures_position_risk_v2(email, futures_type, timestamp, recv_window)
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

[**models::SubaccountGetSubAccountFuturesPositionRiskV2Resp**](SubaccountGetSubAccountFuturesPositionRiskV2Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_list_v1

> models::SubaccountGetSubAccountListV1Resp subaccount_get_sub_account_list_v1(timestamp, email, is_freeze, page, limit, recv_window)
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

[**models::SubaccountGetSubAccountListV1Resp**](SubaccountGetSubAccountListV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_status_v1

> Vec<models::SubaccountGetSubAccountStatusV1RespItem> subaccount_get_sub_account_status_v1(timestamp, email, recv_window)
Get Sub-account's Status on Margin Or Futures(For Master Account)

Get Sub-account's Status on Margin Or Futures

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**email** | Option<**String**> | <a href=\"/docs/sub_account/account-management/Get-Sub-accounts-Status-on-Margin-Or-Futures#email-address\">Sub-account email</a> |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::SubaccountGetSubAccountStatusV1RespItem>**](SubaccountGetSubAccountStatusV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_transaction_statistics_v1

> models::SubaccountGetSubAccountTransactionStatisticsV1Resp subaccount_get_sub_account_transaction_statistics_v1(email, timestamp, recv_window)
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

