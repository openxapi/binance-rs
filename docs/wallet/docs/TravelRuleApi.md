# \TravelRuleApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**wallet_create_localentity_broker_withdraw_apply_v1**](TravelRuleApi.md#wallet_create_localentity_broker_withdraw_apply_v1) | **POST** /sapi/v1/localentity/broker/withdraw/apply | Broker Withdraw (for brokers of local entities that require travel rule) (USER_DATA)
[**wallet_create_localentity_withdraw_apply_v1**](TravelRuleApi.md#wallet_create_localentity_withdraw_apply_v1) | **POST** /sapi/v1/localentity/withdraw/apply | Withdraw (for local entities that require travel rule) (USER_DATA)
[**wallet_get_localentity_deposit_history_v1**](TravelRuleApi.md#wallet_get_localentity_deposit_history_v1) | **GET** /sapi/v1/localentity/deposit/history | Deposit History (for local entities that required travel rule) (supporting network) (USER_DATA)
[**wallet_get_localentity_vasp_v1**](TravelRuleApi.md#wallet_get_localentity_vasp_v1) | **GET** /sapi/v1/localentity/vasp | Onboarded VASP list (for local entities that require travel rule) (supporting network) (USER_DATA)
[**wallet_get_localentity_withdraw_history_v1**](TravelRuleApi.md#wallet_get_localentity_withdraw_history_v1) | **GET** /sapi/v1/localentity/withdraw/history | Withdraw History (for local entities that require travel rule) (supporting network) (USER_DATA)
[**wallet_get_localentity_withdraw_history_v2**](TravelRuleApi.md#wallet_get_localentity_withdraw_history_v2) | **GET** /sapi/v2/localentity/withdraw/history | Withdraw History V2 (for local entities that require travel rule) (supporting network) (USER_DATA)
[**wallet_update_localentity_broker_deposit_provide_info_v1**](TravelRuleApi.md#wallet_update_localentity_broker_deposit_provide_info_v1) | **PUT** /sapi/v1/localentity/broker/deposit/provide-info | Submit Deposit Questionnaire (For local entities that require travel rule) (supporting network) (USER_DATA)
[**wallet_update_localentity_deposit_provide_info_v1**](TravelRuleApi.md#wallet_update_localentity_deposit_provide_info_v1) | **PUT** /sapi/v1/localentity/deposit/provide-info | Submit Deposit Questionnaire (For local entities that require travel rule) (supporting network) (USER_DATA)



## wallet_create_localentity_broker_withdraw_apply_v1

> models::WalletCreateLocalentityBrokerWithdrawApplyV1Resp wallet_create_localentity_broker_withdraw_apply_v1(address, amount, coin, originator_pii, questionnaire, signature, sub_account_id, timestamp, withdraw_order_id, address_name, address_tag, network, transaction_fee_flag, wallet_type)
Broker Withdraw (for brokers of local entities that require travel rule) (USER_DATA)

Submit a withdrawal request for brokers of local entities that required travel rule.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**address** | **String** |  | [required] |[default to ]
**amount** | **String** |  | [required] |[default to ]
**coin** | **String** |  | [required] |[default to ]
**originator_pii** | **String** |  | [required] |[default to ]
**questionnaire** | **String** |  | [required] |[default to ]
**signature** | **String** |  | [required] |[default to ]
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**withdraw_order_id** | **String** |  | [required] |[default to ]
**address_name** | Option<**String**> |  |  |[default to ]
**address_tag** | Option<**String**> |  |  |[default to ]
**network** | Option<**String**> |  |  |[default to ]
**transaction_fee_flag** | Option<**bool**> |  |  |[default to false]
**wallet_type** | Option<**i32**> |  |  |

### Return type

[**models::WalletCreateLocalentityBrokerWithdrawApplyV1Resp**](WalletCreateLocalentityBrokerWithdrawApplyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_create_localentity_withdraw_apply_v1

> models::WalletCreateLocalentityWithdrawApplyV1Resp wallet_create_localentity_withdraw_apply_v1(address, amount, coin, questionnaire, timestamp, address_tag, name, network, recv_window, transaction_fee_flag, wallet_type, withdraw_order_id)
Withdraw (for local entities that require travel rule) (USER_DATA)

Submit a withdrawal request for local entities that required travel rule.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**address** | **String** |  | [required] |[default to ]
**amount** | **String** |  | [required] |[default to ]
**coin** | **String** |  | [required] |[default to ]
**questionnaire** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**address_tag** | Option<**String**> |  |  |[default to ]
**name** | Option<**String**> |  |  |[default to ]
**network** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**transaction_fee_flag** | Option<**bool**> |  |  |[default to false]
**wallet_type** | Option<**i32**> |  |  |
**withdraw_order_id** | Option<**String**> |  |  |[default to ]

### Return type

[**models::WalletCreateLocalentityWithdrawApplyV1Resp**](WalletCreateLocalentityWithdrawApplyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_localentity_deposit_history_v1

> Vec<models::WalletGetLocalentityDepositHistoryV1RespItem> wallet_get_localentity_deposit_history_v1(timestamp, tr_id, tx_id, tran_id, network, coin, travel_rule_status, pending_questionnaire, start_time, end_time, offset, limit)
Deposit History (for local entities that required travel rule) (supporting network) (USER_DATA)

Fetch deposit history for local entities that required travel rule.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**tr_id** | Option<**String**> | Comma(,) separated list of travel rule record Ids. |  |[default to ]
**tx_id** | Option<**String**> | Comma(,) separated list of transaction Ids. |  |[default to ]
**tran_id** | Option<**String**> | Comma(,) separated list of wallet tran Ids. |  |[default to ]
**network** | Option<**String**> |  |  |[default to ]
**coin** | Option<**String**> |  |  |[default to ]
**travel_rule_status** | Option<**i32**> | 0:Completed,1:Pending,2:Failed |  |
**pending_questionnaire** | Option<**bool**> | true: Only return records that pending deposit questionnaire. false/not provided: return all records. |  |
**start_time** | Option<**i64**> | Default: 90 days from current timestamp |  |
**end_time** | Option<**i64**> | Default: present timestamp |  |
**offset** | Option<**i32**> | Default:0 |  |
**limit** | Option<**i32**> | Default:1000, Max:1000 |  |

### Return type

[**Vec<models::WalletGetLocalentityDepositHistoryV1RespItem>**](WalletGetLocalentityDepositHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_localentity_vasp_v1

> Vec<models::WalletGetLocalentityVaspV1RespItem> wallet_get_localentity_vasp_v1()
Onboarded VASP list (for local entities that require travel rule) (supporting network) (USER_DATA)

Fetch the onboarded VASP list for local entities that required travel rule.

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::WalletGetLocalentityVaspV1RespItem>**](WalletGetLocalentityVaspV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_localentity_withdraw_history_v1

> Vec<models::WalletGetLocalentityWithdrawHistoryV1RespItem> wallet_get_localentity_withdraw_history_v1(timestamp, tr_id, tx_id, withdraw_order_id, network, coin, travel_rule_status, offset, limit, start_time, end_time, recv_window)
Withdraw History (for local entities that require travel rule) (supporting network) (USER_DATA)

Fetch withdraw history for local entities that required travel rule.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**tr_id** | Option<**String**> | Comma(,) separated list of travel rule record Ids. |  |[default to ]
**tx_id** | Option<**String**> | Comma(,) separated list of transaction Ids. |  |[default to ]
**withdraw_order_id** | Option<**String**> | Comma(,) separated list of withdrawID defined by the client (i.e. client&#39;s internal withdrawID). |  |[default to ]
**network** | Option<**String**> |  |  |[default to ]
**coin** | Option<**String**> |  |  |[default to ]
**travel_rule_status** | Option<**i32**> | 0:Completed,1:Pending,2:Failed |  |
**offset** | Option<**i32**> | Default: 0 |  |[default to 0]
**limit** | Option<**i32**> | Default: 1000, Max: 1000 |  |[default to 1000]
**start_time** | Option<**i64**> | Default: 90 days from current timestamp |  |
**end_time** | Option<**i64**> | Default: present timestamp |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::WalletGetLocalentityWithdrawHistoryV1RespItem>**](WalletGetLocalentityWithdrawHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_localentity_withdraw_history_v2

> Vec<models::WalletGetLocalentityWithdrawHistoryV2RespItem> wallet_get_localentity_withdraw_history_v2(timestamp, tr_id, tx_id, withdraw_order_id, network, coin, travel_rule_status, offset, limit, start_time, end_time, recv_window)
Withdraw History V2 (for local entities that require travel rule) (supporting network) (USER_DATA)

Fetch withdraw history for local entities that required travel rule.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**tr_id** | Option<**String**> | Comma(,) separated list of travel rule record Ids. |  |[default to ]
**tx_id** | Option<**String**> | Comma(,) separated list of transaction Ids. |  |[default to ]
**withdraw_order_id** | Option<**String**> | Withdraw ID defined by the client (i.e. client&#39;s internal withdrawID). |  |[default to ]
**network** | Option<**String**> |  |  |[default to ]
**coin** | Option<**String**> |  |  |[default to ]
**travel_rule_status** | Option<**i32**> | 0:Completed,1:Pending,2:Failed |  |
**offset** | Option<**i32**> | Default: 0 |  |[default to 0]
**limit** | Option<**i32**> | Default: 1000, Max: 1000 |  |[default to 1000]
**start_time** | Option<**i64**> | Default: 90 days from current timestamp |  |
**end_time** | Option<**i64**> | Default: present timestamp |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::WalletGetLocalentityWithdrawHistoryV2RespItem>**](WalletGetLocalentityWithdrawHistoryV2RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_update_localentity_broker_deposit_provide_info_v1

> models::WalletUpdateLocalentityBrokerDepositProvideInfoV1Resp wallet_update_localentity_broker_deposit_provide_info_v1(beneficiary_pii, deposit_id, questionnaire, signature, sub_account_id, timestamp, address, address_tag, amount, coin, network)
Submit Deposit Questionnaire (For local entities that require travel rule) (supporting network) (USER_DATA)

Submit questionnaire for brokers of local entities that require travel rule. The questionnaire is only applies to transactions from un-hosted wallets or VASPs that are not yet onboarded with GTR.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**beneficiary_pii** | **String** |  | [required] |[default to ]
**deposit_id** | **String** |  | [required] |[default to ]
**questionnaire** | **String** |  | [required] |[default to ]
**signature** | **String** |  | [required] |[default to ]
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**address** | Option<**String**> |  |  |[default to ]
**address_tag** | Option<**String**> |  |  |[default to ]
**amount** | Option<**String**> |  |  |[default to ]
**coin** | Option<**String**> |  |  |[default to ]
**network** | Option<**String**> |  |  |[default to ]

### Return type

[**models::WalletUpdateLocalentityBrokerDepositProvideInfoV1Resp**](WalletUpdateLocalentityBrokerDepositProvideInfoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_update_localentity_deposit_provide_info_v1

> models::WalletUpdateLocalentityDepositProvideInfoV1Resp wallet_update_localentity_deposit_provide_info_v1(questionnaire, timestamp, tran_id)
Submit Deposit Questionnaire (For local entities that require travel rule) (supporting network) (USER_DATA)

Submit questionnaire for local entities that require travel rule. The questionnaire is only applies to transactions from unhosted wallets or VASPs that are not yet onboarded with GTR.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**questionnaire** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**tran_id** | **i64** |  | [required] |

### Return type

[**models::WalletUpdateLocalentityDepositProvideInfoV1Resp**](WalletUpdateLocalentityDepositProvideInfoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

