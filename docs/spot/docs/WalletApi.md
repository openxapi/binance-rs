# \WalletApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_account_disable_fast_withdraw_switch_v1**](WalletApi.md#create_account_disable_fast_withdraw_switch_v1) | **POST** /sapi/v1/account/disableFastWithdrawSwitch | Disable Fast Withdraw Switch (USER_DATA)
[**create_account_enable_fast_withdraw_switch_v1**](WalletApi.md#create_account_enable_fast_withdraw_switch_v1) | **POST** /sapi/v1/account/enableFastWithdrawSwitch | Enable Fast Withdraw Switch (USER_DATA)
[**create_asset_dust_btc_v1**](WalletApi.md#create_asset_dust_btc_v1) | **POST** /sapi/v1/asset/dust-btc | Get Assets That Can Be Converted Into BNB (USER_DATA)
[**create_asset_dust_v1**](WalletApi.md#create_asset_dust_v1) | **POST** /sapi/v1/asset/dust | Dust Transfer (USER_DATA)
[**create_asset_get_funding_asset_v1**](WalletApi.md#create_asset_get_funding_asset_v1) | **POST** /sapi/v1/asset/get-funding-asset | Funding Wallet (USER_DATA)
[**create_asset_get_user_asset_v3**](WalletApi.md#create_asset_get_user_asset_v3) | **POST** /sapi/v3/asset/getUserAsset | User Asset (USER_DATA)
[**create_asset_transfer_v1**](WalletApi.md#create_asset_transfer_v1) | **POST** /sapi/v1/asset/transfer | User Universal Transfer (USER_DATA)
[**create_bnb_burn_v1**](WalletApi.md#create_bnb_burn_v1) | **POST** /sapi/v1/bnbBurn | Toggle BNB Burn On Spot Trade And Margin Interest (USER_DATA)
[**create_capital_deposit_credit_apply_v1**](WalletApi.md#create_capital_deposit_credit_apply_v1) | **POST** /sapi/v1/capital/deposit/credit-apply | One click arrival deposit apply (for expired address deposit) (USER_DATA)
[**create_capital_withdraw_apply_v1**](WalletApi.md#create_capital_withdraw_apply_v1) | **POST** /sapi/v1/capital/withdraw/apply | Withdraw(USER_DATA)
[**create_localentity_broker_withdraw_apply_v1**](WalletApi.md#create_localentity_broker_withdraw_apply_v1) | **POST** /sapi/v1/localentity/broker/withdraw/apply | Broker Withdraw (for brokers of local entities that require travel rule) (USER_DATA)
[**create_localentity_withdraw_apply_v1**](WalletApi.md#create_localentity_withdraw_apply_v1) | **POST** /sapi/v1/localentity/withdraw/apply | Withdraw (for local entities that require travel rule) (USER_DATA)
[**get_account_api_restrictions_v1**](WalletApi.md#get_account_api_restrictions_v1) | **GET** /sapi/v1/account/apiRestrictions | Get API Key Permission (USER_DATA)
[**get_account_api_trading_status_v1**](WalletApi.md#get_account_api_trading_status_v1) | **GET** /sapi/v1/account/apiTradingStatus | Account API Trading Status (USER_DATA)
[**get_account_info_v1**](WalletApi.md#get_account_info_v1) | **GET** /sapi/v1/account/info | Account info (USER_DATA)
[**get_account_snapshot_v1**](WalletApi.md#get_account_snapshot_v1) | **GET** /sapi/v1/accountSnapshot | Daily Account Snapshot (USER_DATA)
[**get_account_status_v1**](WalletApi.md#get_account_status_v1) | **GET** /sapi/v1/account/status | Account Status (USER_DATA)
[**get_asset_asset_detail_v1**](WalletApi.md#get_asset_asset_detail_v1) | **GET** /sapi/v1/asset/assetDetail | Asset Detail (USER_DATA)
[**get_asset_asset_dividend_v1**](WalletApi.md#get_asset_asset_dividend_v1) | **GET** /sapi/v1/asset/assetDividend | Asset Dividend Record (USER_DATA)
[**get_asset_custody_transfer_history_v1**](WalletApi.md#get_asset_custody_transfer_history_v1) | **GET** /sapi/v1/asset/custody/transfer-history | Query User Delegation History(For Master Account)(USER_DATA)
[**get_asset_dribblet_v1**](WalletApi.md#get_asset_dribblet_v1) | **GET** /sapi/v1/asset/dribblet | DustLog(USER_DATA)
[**get_asset_ledger_transfer_cloud_mining_query_by_page_v1**](WalletApi.md#get_asset_ledger_transfer_cloud_mining_query_by_page_v1) | **GET** /sapi/v1/asset/ledger-transfer/cloud-mining/queryByPage | Get Cloud-Mining payment and refund history (USER_DATA)
[**get_asset_trade_fee_v1**](WalletApi.md#get_asset_trade_fee_v1) | **GET** /sapi/v1/asset/tradeFee | Trade Fee (USER_DATA)
[**get_asset_transfer_v1**](WalletApi.md#get_asset_transfer_v1) | **GET** /sapi/v1/asset/transfer | Query User Universal Transfer History(USER_DATA)
[**get_asset_wallet_balance_v1**](WalletApi.md#get_asset_wallet_balance_v1) | **GET** /sapi/v1/asset/wallet/balance | Query User Wallet Balance (USER_DATA)
[**get_capital_config_getall_v1**](WalletApi.md#get_capital_config_getall_v1) | **GET** /sapi/v1/capital/config/getall | All Coins' Information (USER_DATA)
[**get_capital_deposit_address_list_v1**](WalletApi.md#get_capital_deposit_address_list_v1) | **GET** /sapi/v1/capital/deposit/address/list | Fetch deposit address list with network(USER_DATA)
[**get_capital_deposit_address_v1**](WalletApi.md#get_capital_deposit_address_v1) | **GET** /sapi/v1/capital/deposit/address | Deposit Address(supporting network) (USER_DATA)
[**get_capital_deposit_hisrec_v1**](WalletApi.md#get_capital_deposit_hisrec_v1) | **GET** /sapi/v1/capital/deposit/hisrec | Deposit History (supporting network) (USER_DATA)
[**get_capital_withdraw_address_list_v1**](WalletApi.md#get_capital_withdraw_address_list_v1) | **GET** /sapi/v1/capital/withdraw/address/list | Fetch withdraw address list (USER_DATA)
[**get_capital_withdraw_history_v1**](WalletApi.md#get_capital_withdraw_history_v1) | **GET** /sapi/v1/capital/withdraw/history | Withdraw History (supporting network) (USER_DATA)
[**get_localentity_deposit_history_v1**](WalletApi.md#get_localentity_deposit_history_v1) | **GET** /sapi/v1/localentity/deposit/history | Deposit History (for local entities that required travel rule) (supporting network) (USER_DATA)
[**get_localentity_vasp_v1**](WalletApi.md#get_localentity_vasp_v1) | **GET** /sapi/v1/localentity/vasp | Onboarded VASP list (for local entities that require travel rule) (supporting network) (USER_DATA)
[**get_localentity_withdraw_history_v1**](WalletApi.md#get_localentity_withdraw_history_v1) | **GET** /sapi/v1/localentity/withdraw/history | Withdraw History (for local entities that require travel rule) (supporting network) (USER_DATA)
[**get_localentity_withdraw_history_v2**](WalletApi.md#get_localentity_withdraw_history_v2) | **GET** /sapi/v2/localentity/withdraw/history | Withdraw History V2 (for local entities that require travel rule) (supporting network) (USER_DATA)
[**get_spot_delist_schedule_v1**](WalletApi.md#get_spot_delist_schedule_v1) | **GET** /sapi/v1/spot/delist-schedule | Get Spot Delist Schedule (MARKET_DATA)
[**get_spot_open_symbol_list_v1**](WalletApi.md#get_spot_open_symbol_list_v1) | **GET** /sapi/v1/spot/open-symbol-list | Get Open Symbol List (MARKET_DATA)
[**get_system_status_v1**](WalletApi.md#get_system_status_v1) | **GET** /sapi/v1/system/status | System Status (System)
[**update_localentity_broker_deposit_provide_info_v1**](WalletApi.md#update_localentity_broker_deposit_provide_info_v1) | **PUT** /sapi/v1/localentity/broker/deposit/provide-info | Submit Deposit Questionnaire (For local entities that require travel rule) (supporting network) (USER_DATA)
[**update_localentity_deposit_provide_info_v1**](WalletApi.md#update_localentity_deposit_provide_info_v1) | **PUT** /sapi/v1/localentity/deposit/provide-info | Submit Deposit Questionnaire (For local entities that require travel rule) (supporting network) (USER_DATA)



## create_account_disable_fast_withdraw_switch_v1

> serde_json::Value create_account_disable_fast_withdraw_switch_v1(timestamp, recv_window)
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


## create_account_enable_fast_withdraw_switch_v1

> serde_json::Value create_account_enable_fast_withdraw_switch_v1(timestamp, recv_window)
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


## create_asset_dust_btc_v1

> models::CreateAssetDustBtcV1Resp create_asset_dust_btc_v1(timestamp, account_type, recv_window)
Get Assets That Can Be Converted Into BNB (USER_DATA)

Get Assets That Can Be Converted Into BNB

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**account_type** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateAssetDustBtcV1Resp**](CreateAssetDustBtcV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_asset_dust_v1

> models::CreateAssetDustV1Resp create_asset_dust_v1(asset, timestamp, account_type, recv_window)
Dust Transfer (USER_DATA)

Convert dust assets to BNB.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | [**Vec<String>**](String.md) |  | [required] |
**timestamp** | **i64** |  | [required] |
**account_type** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateAssetDustV1Resp**](CreateAssetDustV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_asset_get_funding_asset_v1

> Vec<models::CreateAssetGetFundingAssetV1RespItem> create_asset_get_funding_asset_v1(timestamp, asset, need_btc_valuation, recv_window)
Funding Wallet (USER_DATA)

Query Funding Wallet

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**need_btc_valuation** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CreateAssetGetFundingAssetV1RespItem>**](CreateAssetGetFundingAssetV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_asset_get_user_asset_v3

> Vec<models::CreateAssetGetUserAssetV3RespItem> create_asset_get_user_asset_v3(timestamp, asset, need_btc_valuation, recv_window)
User Asset (USER_DATA)

Get user assets, just for positive data.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**need_btc_valuation** | Option<**bool**> |  |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::CreateAssetGetUserAssetV3RespItem>**](CreateAssetGetUserAssetV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_asset_transfer_v1

> models::CreateAssetTransferV1Resp create_asset_transfer_v1(amount, asset, timestamp, r#type, from_symbol, recv_window, to_symbol)
User Universal Transfer (USER_DATA)

user universal transfer

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**from_symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**to_symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateAssetTransferV1Resp**](CreateAssetTransferV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_bnb_burn_v1

> models::CreateBnbBurnV1Resp create_bnb_burn_v1(timestamp, interest_bnb_burn, recv_window, spot_bnb_burn)
Toggle BNB Burn On Spot Trade And Margin Interest (USER_DATA)

Toggle BNB Burn On Spot Trade And Margin Interest

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**interest_bnb_burn** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**spot_bnb_burn** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateBnbBurnV1Resp**](CreateBnbBurnV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_capital_deposit_credit_apply_v1

> models::CreateCapitalDepositCreditApplyV1Resp create_capital_deposit_credit_apply_v1(deposit_id, sub_account_id, sub_user_id, tx_id)
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

[**models::CreateCapitalDepositCreditApplyV1Resp**](CreateCapitalDepositCreditApplyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_capital_withdraw_apply_v1

> models::CreateCapitalWithdrawApplyV1Resp create_capital_withdraw_apply_v1(address, amount, coin, timestamp, address_tag, name, network, recv_window, transaction_fee_flag, wallet_type, withdraw_order_id)
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

[**models::CreateCapitalWithdrawApplyV1Resp**](CreateCapitalWithdrawApplyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_localentity_broker_withdraw_apply_v1

> models::CreateLocalentityBrokerWithdrawApplyV1Resp create_localentity_broker_withdraw_apply_v1(address, amount, coin, originator_pii, questionnaire, signature, sub_account_id, timestamp, withdraw_order_id, address_name, address_tag, network, transaction_fee_flag, wallet_type)
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

[**models::CreateLocalentityBrokerWithdrawApplyV1Resp**](CreateLocalentityBrokerWithdrawApplyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_localentity_withdraw_apply_v1

> models::CreateLocalentityWithdrawApplyV1Resp create_localentity_withdraw_apply_v1(address, amount, coin, questionnaire, timestamp, address_tag, name, network, recv_window, transaction_fee_flag, wallet_type, withdraw_order_id)
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

[**models::CreateLocalentityWithdrawApplyV1Resp**](CreateLocalentityWithdrawApplyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_account_api_restrictions_v1

> models::GetAccountApiRestrictionsV1Resp get_account_api_restrictions_v1(timestamp, recv_window)
Get API Key Permission (USER_DATA)

Get API Key Permission

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAccountApiRestrictionsV1Resp**](GetAccountApiRestrictionsV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_account_api_trading_status_v1

> models::GetAccountApiTradingStatusV1Resp get_account_api_trading_status_v1(timestamp, recv_window)
Account API Trading Status (USER_DATA)

Fetch account api trading status detail.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAccountApiTradingStatusV1Resp**](GetAccountApiTradingStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_account_info_v1

> models::GetAccountInfoV1Resp get_account_info_v1(timestamp, recv_window)
Account info (USER_DATA)

Fetch account info detail.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAccountInfoV1Resp**](GetAccountInfoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_account_snapshot_v1

> models::GetAccountSnapshotV1Resp get_account_snapshot_v1(r#type, timestamp, start_time, end_time, limit, recv_window)
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

[**models::GetAccountSnapshotV1Resp**](GetAccountSnapshotV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_account_status_v1

> models::GetAccountStatusV1Resp get_account_status_v1(timestamp, recv_window)
Account Status (USER_DATA)

Fetch account status detail.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAccountStatusV1Resp**](GetAccountStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_asset_asset_detail_v1

> std::collections::HashMap<String, models::WalletGetAssetAssetDetailV1RespValue> get_asset_asset_detail_v1(timestamp, recv_window)
Asset Detail (USER_DATA)

Fetch details of assets supported on Binance.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**std::collections::HashMap<String, models::WalletGetAssetAssetDetailV1RespValue>**](WalletGetAssetAssetDetailV1Resp_value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_asset_asset_dividend_v1

> models::GetAssetAssetDividendV1Resp get_asset_asset_dividend_v1(timestamp, asset, start_time, end_time, limit, recv_window)
Asset Dividend Record (USER_DATA)

Query asset dividend record.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 20, max 500 |  |[default to 20]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAssetAssetDividendV1Resp**](GetAssetAssetDividendV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_asset_custody_transfer_history_v1

> models::GetAssetCustodyTransferHistoryV1Resp get_asset_custody_transfer_history_v1(email, start_time, end_time, timestamp, r#type, asset, current, size, recv_window)
Query User Delegation History(For Master Account)(USER_DATA)

Query User Delegation History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**start_time** | **i64** |  | [required] |
**end_time** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**r#type** | Option<**String**> | Delegate/Undelegate |  |[default to ]
**asset** | Option<**String**> |  |  |[default to ]
**current** | Option<**i32**> | default 1 |  |[default to 1]
**size** | Option<**i32**> | default 10, max 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAssetCustodyTransferHistoryV1Resp**](GetAssetCustodyTransferHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_asset_dribblet_v1

> models::GetAssetDribbletV1Resp get_asset_dribblet_v1(timestamp, start_time, end_time, recv_window)
DustLog(USER_DATA)

Dustlog

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAssetDribbletV1Resp**](GetAssetDribbletV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_asset_ledger_transfer_cloud_mining_query_by_page_v1

> models::GetAssetLedgerTransferCloudMiningQueryByPageV1Resp get_asset_ledger_transfer_cloud_mining_query_by_page_v1(start_time, end_time, tran_id, client_tran_id, asset, current, size)
Get Cloud-Mining payment and refund history (USER_DATA)

The query of Cloud-Mining payment and refund history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | inclusive, unit: ms | [required] |
**end_time** | **i64** | exclusive, unit: ms | [required] |
**tran_id** | Option<**i64**> | The transaction id |  |
**client_tran_id** | Option<**String**> | The unique flag |  |[default to ]
**asset** | Option<**String**> | If it is blank, we will query all assets |  |[default to ]
**current** | Option<**i32**> | current page, default 1, the min value is 1 |  |[default to 1]
**size** | Option<**i32**> | page size, default 10, the max value is 100 |  |[default to 10]

### Return type

[**models::GetAssetLedgerTransferCloudMiningQueryByPageV1Resp**](GetAssetLedgerTransferCloudMiningQueryByPageV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_asset_trade_fee_v1

> Vec<models::GetAssetTradeFeeV1RespItem> get_asset_trade_fee_v1(timestamp, symbol, recv_window)
Trade Fee (USER_DATA)

Fetch trade fee

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetAssetTradeFeeV1RespItem>**](GetAssetTradeFeeV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_asset_transfer_v1

> models::GetAssetTransferV1Resp get_asset_transfer_v1(r#type, timestamp, start_time, end_time, current, size, from_symbol, to_symbol, recv_window)
Query User Universal Transfer History(USER_DATA)

Query User Universal Transfer History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**r#type** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i32**> | Default 1 |  |[default to 1]
**size** | Option<**i32**> | Default 10, Max 100 |  |[default to 10]
**from_symbol** | Option<**String**> |  |  |[default to ]
**to_symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAssetTransferV1Resp**](GetAssetTransferV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_asset_wallet_balance_v1

> Vec<models::GetAssetWalletBalanceV1RespItem> get_asset_wallet_balance_v1(timestamp, quote_asset, recv_window)
Query User Wallet Balance (USER_DATA)

Query User Wallet Balance

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**quote_asset** | Option<**String**> | `USDT`, `ETH`, `USDC`, `BNB`, etc. default `BTC` |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetAssetWalletBalanceV1RespItem>**](GetAssetWalletBalanceV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_capital_config_getall_v1

> Vec<models::GetCapitalConfigGetallV1RespItem> get_capital_config_getall_v1(timestamp, recv_window)
All Coins' Information (USER_DATA)

Get information of coins (available for deposit and withdraw) for user.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetCapitalConfigGetallV1RespItem>**](GetCapitalConfigGetallV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_capital_deposit_address_list_v1

> Vec<models::GetCapitalDepositAddressListV1RespItem> get_capital_deposit_address_list_v1(coin, timestamp, network)
Fetch deposit address list with network(USER_DATA)

Fetch deposit address list with network.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**coin** | **String** | `coin` refers to the parent network address format that the address is using | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**network** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::GetCapitalDepositAddressListV1RespItem>**](GetCapitalDepositAddressListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_capital_deposit_address_v1

> models::GetCapitalDepositAddressV1Resp get_capital_deposit_address_v1(coin, timestamp, network, amount, recv_window)
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

[**models::GetCapitalDepositAddressV1Resp**](GetCapitalDepositAddressV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_capital_deposit_hisrec_v1

> Vec<models::GetCapitalDepositHisrecV1RespItem> get_capital_deposit_hisrec_v1(timestamp, include_source, coin, status, start_time, end_time, offset, limit, recv_window, tx_id)
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

[**Vec<models::GetCapitalDepositHisrecV1RespItem>**](GetCapitalDepositHisrecV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_capital_withdraw_address_list_v1

> Vec<models::GetCapitalWithdrawAddressListV1RespItem> get_capital_withdraw_address_list_v1()
Fetch withdraw address list (USER_DATA)

Fetch withdraw address list

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::GetCapitalWithdrawAddressListV1RespItem>**](GetCapitalWithdrawAddressListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_capital_withdraw_history_v1

> Vec<models::GetCapitalWithdrawHistoryV1RespItem> get_capital_withdraw_history_v1(timestamp, coin, withdraw_order_id, status, offset, limit, id_list, start_time, end_time, recv_window)
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

[**Vec<models::GetCapitalWithdrawHistoryV1RespItem>**](GetCapitalWithdrawHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_localentity_deposit_history_v1

> Vec<models::GetLocalentityDepositHistoryV1RespItem> get_localentity_deposit_history_v1(timestamp, tr_id, tx_id, tran_id, network, coin, travel_rule_status, pending_questionnaire, start_time, end_time, offset, limit)
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

[**Vec<models::GetLocalentityDepositHistoryV1RespItem>**](GetLocalentityDepositHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_localentity_vasp_v1

> Vec<models::GetLocalentityVaspV1RespItem> get_localentity_vasp_v1()
Onboarded VASP list (for local entities that require travel rule) (supporting network) (USER_DATA)

Fetch the onboarded VASP list for local entities that required travel rule.

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::GetLocalentityVaspV1RespItem>**](GetLocalentityVaspV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_localentity_withdraw_history_v1

> Vec<models::GetLocalentityWithdrawHistoryV1RespItem> get_localentity_withdraw_history_v1(timestamp, tr_id, tx_id, withdraw_order_id, network, coin, travel_rule_status, offset, limit, start_time, end_time, recv_window)
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

[**Vec<models::GetLocalentityWithdrawHistoryV1RespItem>**](GetLocalentityWithdrawHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_localentity_withdraw_history_v2

> Vec<models::GetLocalentityWithdrawHistoryV2RespItem> get_localentity_withdraw_history_v2(timestamp, tr_id, tx_id, withdraw_order_id, network, coin, travel_rule_status, offset, limit, start_time, end_time, recv_window)
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

[**Vec<models::GetLocalentityWithdrawHistoryV2RespItem>**](GetLocalentityWithdrawHistoryV2RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_spot_delist_schedule_v1

> Vec<models::GetSpotDelistScheduleV1RespItem> get_spot_delist_schedule_v1(timestamp, recv_window)
Get Spot Delist Schedule (MARKET_DATA)

Get symbols delist schedule for spot

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetSpotDelistScheduleV1RespItem>**](GetSpotDelistScheduleV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_spot_open_symbol_list_v1

> Vec<models::GetSpotOpenSymbolListV1RespItem> get_spot_open_symbol_list_v1()
Get Open Symbol List (MARKET_DATA)

Get the list of symbols that are scheduled to be opened for trading in the market.

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::GetSpotOpenSymbolListV1RespItem>**](GetSpotOpenSymbolListV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_system_status_v1

> models::GetSystemStatusV1Resp get_system_status_v1()
System Status (System)

Fetch system status.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::GetSystemStatusV1Resp**](GetSystemStatusV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_localentity_broker_deposit_provide_info_v1

> models::UpdateLocalentityBrokerDepositProvideInfoV1Resp update_localentity_broker_deposit_provide_info_v1(beneficiary_pii, deposit_id, questionnaire, signature, sub_account_id, timestamp, address, address_tag, amount, coin, network)
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

[**models::UpdateLocalentityBrokerDepositProvideInfoV1Resp**](UpdateLocalentityBrokerDepositProvideInfoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_localentity_deposit_provide_info_v1

> models::UpdateLocalentityDepositProvideInfoV1Resp update_localentity_deposit_provide_info_v1(questionnaire, timestamp, tran_id)
Submit Deposit Questionnaire (For local entities that require travel rule) (supporting network) (USER_DATA)

Submit questionnaire for local entities that require travel rule. The questionnaire is only applies to transactions from unhosted wallets or VASPs that are not yet onboarded with GTR.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**questionnaire** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**tran_id** | **i64** |  | [required] |

### Return type

[**models::UpdateLocalentityDepositProvideInfoV1Resp**](UpdateLocalentityDepositProvideInfoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

