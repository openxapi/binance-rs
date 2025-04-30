# \CapitalApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**wallet_create_capital_deposit_credit_apply_v1**](CapitalApi.md#wallet_create_capital_deposit_credit_apply_v1) | **POST** /sapi/v1/capital/deposit/credit-apply | One click arrival deposit apply (for expired address deposit) (USER_DATA)
[**wallet_create_capital_withdraw_apply_v1**](CapitalApi.md#wallet_create_capital_withdraw_apply_v1) | **POST** /sapi/v1/capital/withdraw/apply | Withdraw(USER_DATA)
[**wallet_get_capital_config_getall_v1**](CapitalApi.md#wallet_get_capital_config_getall_v1) | **GET** /sapi/v1/capital/config/getall | All Coins' Information (USER_DATA)
[**wallet_get_capital_deposit_address_list_v1**](CapitalApi.md#wallet_get_capital_deposit_address_list_v1) | **GET** /sapi/v1/capital/deposit/address/list | Fetch deposit address list with network(USER_DATA)
[**wallet_get_capital_deposit_address_v1**](CapitalApi.md#wallet_get_capital_deposit_address_v1) | **GET** /sapi/v1/capital/deposit/address | Deposit Address(supporting network) (USER_DATA)
[**wallet_get_capital_deposit_hisrec_v1**](CapitalApi.md#wallet_get_capital_deposit_hisrec_v1) | **GET** /sapi/v1/capital/deposit/hisrec | Deposit History (supporting network) (USER_DATA)
[**wallet_get_capital_withdraw_address_list_v1**](CapitalApi.md#wallet_get_capital_withdraw_address_list_v1) | **GET** /sapi/v1/capital/withdraw/address/list | Fetch withdraw address list (USER_DATA)
[**wallet_get_capital_withdraw_history_v1**](CapitalApi.md#wallet_get_capital_withdraw_history_v1) | **GET** /sapi/v1/capital/withdraw/history | Withdraw History (supporting network) (USER_DATA)



## wallet_create_capital_deposit_credit_apply_v1

> models::WalletCreateCapitalDepositCreditApplyV1Resp wallet_create_capital_deposit_credit_apply_v1(deposit_id, sub_account_id, sub_user_id, tx_id)
One click arrival deposit apply (for expired address deposit) (USER_DATA)

Apply deposit credit for expired address (One click arrival)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**deposit_id** | Option<**i64**> |  |  |
**sub_account_id** | Option<**i64**> |  |  |
**sub_user_id** | Option<**i64**> |  |  |
**tx_id** | Option<**String**> |  |  |[default to ]

### Return type

[**models::WalletCreateCapitalDepositCreditApplyV1Resp**](WalletCreateCapitalDepositCreditApplyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_create_capital_withdraw_apply_v1

> models::WalletCreateCapitalWithdrawApplyV1Resp wallet_create_capital_withdraw_apply_v1(address, amount, coin, timestamp, address_tag, name, network, recv_window, transaction_fee_flag, wallet_type, withdraw_order_id)
Withdraw(USER_DATA)

Submit a withdraw request.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**address** | **String** |  | [required] |[default to ]
**amount** | **String** |  | [required] |[default to ]
**coin** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**address_tag** | Option<**String**> |  |  |[default to ]
**name** | Option<**String**> |  |  |[default to ]
**network** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**transaction_fee_flag** | Option<**bool**> |  |  |[default to false]
**wallet_type** | Option<**i32**> |  |  |
**withdraw_order_id** | Option<**String**> |  |  |[default to ]

### Return type

[**models::WalletCreateCapitalWithdrawApplyV1Resp**](WalletCreateCapitalWithdrawApplyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_capital_config_getall_v1

> Vec<models::WalletGetCapitalConfigGetallV1RespItem> wallet_get_capital_config_getall_v1(timestamp, recv_window)
All Coins' Information (USER_DATA)

Get information of coins (available for deposit and withdraw) for user.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::WalletGetCapitalConfigGetallV1RespItem>**](WalletGetCapitalConfigGetallV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_capital_deposit_address_list_v1

> Vec<models::WalletGetCapitalDepositAddressListV1RespItem> wallet_get_capital_deposit_address_list_v1(coin, timestamp, network)
Fetch deposit address list with network(USER_DATA)

Fetch deposit address list with network.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**coin** | **String** | `coin` refers to the parent network address format that the address is using | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**network** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::WalletGetCapitalDepositAddressListV1RespItem>**](WalletGetCapitalDepositAddressListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_capital_deposit_address_v1

> models::WalletGetCapitalDepositAddressV1Resp wallet_get_capital_deposit_address_v1(coin, timestamp, network, amount, recv_window)
Deposit Address(supporting network) (USER_DATA)

Fetch deposit address with network.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**coin** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**network** | Option<**String**> |  |  |[default to ]
**amount** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::WalletGetCapitalDepositAddressV1Resp**](WalletGetCapitalDepositAddressV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_capital_deposit_hisrec_v1

> Vec<models::WalletGetCapitalDepositHisrecV1RespItem> wallet_get_capital_deposit_hisrec_v1(timestamp, include_source, coin, status, start_time, end_time, offset, limit, recv_window, tx_id)
Deposit History (supporting network) (USER_DATA)

Fetch deposit history.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**include_source** | Option<**bool**> | Default: `false`, return `sourceAddress`field when set to `true` |  |[default to false]
**coin** | Option<**String**> |  |  |[default to ]
**status** | Option<**i32**> | 0(0:pending, 6:credited but cannot withdraw, 7:Wrong Deposit, 8:Waiting User confirm, 1:success, 2:rejected) |  |
**start_time** | Option<**i64**> | Default: 90 days from current timestamp |  |
**end_time** | Option<**i64**> | Default: present timestamp |  |
**offset** | Option<**i32**> | Default:0 |  |
**limit** | Option<**i32**> | Default:1000, Max:1000 |  |
**recv_window** | Option<**i64**> |  |  |
**tx_id** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::WalletGetCapitalDepositHisrecV1RespItem>**](WalletGetCapitalDepositHisrecV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_capital_withdraw_address_list_v1

> Vec<models::WalletGetCapitalWithdrawAddressListV1RespItem> wallet_get_capital_withdraw_address_list_v1()
Fetch withdraw address list (USER_DATA)

Fetch withdraw address list

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::WalletGetCapitalWithdrawAddressListV1RespItem>**](WalletGetCapitalWithdrawAddressListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_capital_withdraw_history_v1

> Vec<models::WalletGetCapitalWithdrawHistoryV1RespItem> wallet_get_capital_withdraw_history_v1(timestamp, coin, withdraw_order_id, status, offset, limit, id_list, start_time, end_time, recv_window)
Withdraw History (supporting network) (USER_DATA)

Fetch withdraw history.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**coin** | Option<**String**> |  |  |[default to ]
**withdraw_order_id** | Option<**String**> |  |  |[default to ]
**status** | Option<**i32**> | 0(0:Email Sent, 2:Awaiting Approval 3:Rejected 4:Processing 6:Completed) |  |
**offset** | Option<**i32**> |  |  |
**limit** | Option<**i32**> | Default: 1000, Max: 1000 |  |[default to 1000]
**id_list** | Option<**String**> | id list returned in the response of POST `/sapi/v1/capital/withdraw/apply`, separated by `,` |  |[default to ]
**start_time** | Option<**i64**> | Default: 90 days from current timestamp |  |
**end_time** | Option<**i64**> | Default: present timestamp |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::WalletGetCapitalWithdrawHistoryV1RespItem>**](WalletGetCapitalWithdrawHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

