# \BinanceLinkApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_api_referral_customization_v1**](BinanceLinkApi.md#create_api_referral_customization_v1) | **POST** /sapi/v1/apiReferral/customization | Customize Id For Client (USER DATA) （For Partner）
[**create_api_referral_user_customization_v1**](BinanceLinkApi.md#create_api_referral_user_customization_v1) | **POST** /sapi/v1/apiReferral/userCustomization | Customize Id For Client  (USER DATA)(For client)
[**create_broker_sub_account_api_commission_coin_futures_v1**](BinanceLinkApi.md#create_broker_sub_account_api_commission_coin_futures_v1) | **POST** /sapi/v1/broker/subAccountApi/commission/coinFutures | Change Sub Account COIN-Ⓜ Futures Commission Adjustment
[**create_broker_sub_account_api_commission_futures_v1**](BinanceLinkApi.md#create_broker_sub_account_api_commission_futures_v1) | **POST** /sapi/v1/broker/subAccountApi/commission/futures | Change Sub Account USDT-Ⓜ Futures Commission Adjustment
[**create_broker_sub_account_api_commission_v1**](BinanceLinkApi.md#create_broker_sub_account_api_commission_v1) | **POST** /sapi/v1/broker/subAccountApi/commission | Change Sub Account Commission
[**create_broker_sub_account_api_ip_restriction_v2**](BinanceLinkApi.md#create_broker_sub_account_api_ip_restriction_v2) | **POST** /sapi/v2/broker/subAccountApi/ipRestriction | Update IP Restriction for Sub-Account API key (For Master Account)
[**create_broker_sub_account_api_permission_universal_transfer_v1**](BinanceLinkApi.md#create_broker_sub_account_api_permission_universal_transfer_v1) | **POST** /sapi/v1/broker/subAccountApi/permission/universalTransfer | Enable Universal Transfer Permission For Sub Account Api Key
[**create_broker_sub_account_api_permission_v1**](BinanceLinkApi.md#create_broker_sub_account_api_permission_v1) | **POST** /sapi/v1/broker/subAccountApi/permission | Change Sub Account Api Permission
[**create_broker_sub_account_api_v1**](BinanceLinkApi.md#create_broker_sub_account_api_v1) | **POST** /sapi/v1/broker/subAccountApi | Create Api Key for Sub Account
[**create_broker_sub_account_bnb_burn_margin_interest_v1**](BinanceLinkApi.md#create_broker_sub_account_bnb_burn_margin_interest_v1) | **POST** /sapi/v1/broker/subAccount/bnbBurn/marginInterest | Enable Or Disable BNB Burn for Sub Account Margin Interest
[**create_broker_sub_account_bnb_burn_spot_v1**](BinanceLinkApi.md#create_broker_sub_account_bnb_burn_spot_v1) | **POST** /sapi/v1/broker/subAccount/bnbBurn/spot | Enable Or Disable BNB Burn for Sub Account SPOT and MARGIN
[**create_broker_sub_account_futures_v1**](BinanceLinkApi.md#create_broker_sub_account_futures_v1) | **POST** /sapi/v1/broker/subAccount/futures | Enable Futures for Sub Account
[**create_broker_sub_account_v1**](BinanceLinkApi.md#create_broker_sub_account_v1) | **POST** /sapi/v1/broker/subAccount | Create a Sub Account
[**create_broker_transfer_futures_v1**](BinanceLinkApi.md#create_broker_transfer_futures_v1) | **POST** /sapi/v1/broker/transfer/futures | Sub Account Transfer（FUTURES）
[**create_broker_transfer_v1**](BinanceLinkApi.md#create_broker_transfer_v1) | **POST** /sapi/v1/broker/transfer | Sub Account Transfer（SPOT）
[**create_broker_universal_transfer_v1**](BinanceLinkApi.md#create_broker_universal_transfer_v1) | **POST** /sapi/v1/broker/universalTransfer | Universal Transfer
[**delete_broker_sub_account_api_ip_restriction_ip_list_v1**](BinanceLinkApi.md#delete_broker_sub_account_api_ip_restriction_ip_list_v1) | **DELETE** /sapi/v1/broker/subAccountApi/ipRestriction/ipList | Delete IP Restriction for Sub Account Api Key
[**delete_broker_sub_account_api_v1**](BinanceLinkApi.md#delete_broker_sub_account_api_v1) | **DELETE** /sapi/v1/broker/subAccountApi | Delete Sub Account Api Key
[**delete_broker_sub_account_v1**](BinanceLinkApi.md#delete_broker_sub_account_v1) | **DELETE** /sapi/v1/broker/subAccount | Delete Sub Account
[**get_api_referral_customization_v1**](BinanceLinkApi.md#get_api_referral_customization_v1) | **GET** /sapi/v1/apiReferral/customization | Get Client Email Customized Id (USER DATA) （For Partner）
[**get_api_referral_if_new_user_v1**](BinanceLinkApi.md#get_api_referral_if_new_user_v1) | **GET** /sapi/v1/apiReferral/ifNewUser | Query Client If The New User (USER  DATA)
[**get_api_referral_kickback_recent_record_v1**](BinanceLinkApi.md#get_api_referral_kickback_recent_record_v1) | **GET** /sapi/v1/apiReferral/kickback/recentRecord | Query Rebate Recent Record(For Client)
[**get_api_referral_rebate_recent_record_v1**](BinanceLinkApi.md#get_api_referral_rebate_recent_record_v1) | **GET** /sapi/v1/apiReferral/rebate/recentRecord | Query Rebate Recent Record （USER DATA）(For Partner)
[**get_api_referral_user_customization_v1**](BinanceLinkApi.md#get_api_referral_user_customization_v1) | **GET** /sapi/v1/apiReferral/userCustomization | Get User’s Customize Id (USER DATA)
[**get_broker_info_v1**](BinanceLinkApi.md#get_broker_info_v1) | **GET** /sapi/v1/broker/info | Link Account Information
[**get_broker_rebate_futures_recent_record_v1**](BinanceLinkApi.md#get_broker_rebate_futures_recent_record_v1) | **GET** /sapi/v1/broker/rebate/futures/recentRecord | Query Broker Futures Commission Rebate Record
[**get_broker_rebate_recent_record_v1**](BinanceLinkApi.md#get_broker_rebate_recent_record_v1) | **GET** /sapi/v1/broker/rebate/recentRecord | Query Broker Commission Rebate Recent Record（Spot）
[**get_broker_sub_account_api_commission_coin_futures_v1**](BinanceLinkApi.md#get_broker_sub_account_api_commission_coin_futures_v1) | **GET** /sapi/v1/broker/subAccountApi/commission/coinFutures | Query Sub Account COIN-Ⓜ Futures Commission Adjustment
[**get_broker_sub_account_api_commission_futures_v1**](BinanceLinkApi.md#get_broker_sub_account_api_commission_futures_v1) | **GET** /sapi/v1/broker/subAccountApi/commission/futures | Query Sub Account USDT-Ⓜ Futures Commission Adjustment
[**get_broker_sub_account_api_ip_restriction_v1**](BinanceLinkApi.md#get_broker_sub_account_api_ip_restriction_v1) | **GET** /sapi/v1/broker/subAccountApi/ipRestriction | Get IP Restriction for Sub Account Api Key
[**get_broker_sub_account_api_v1**](BinanceLinkApi.md#get_broker_sub_account_api_v1) | **GET** /sapi/v1/broker/subAccountApi | Query Sub Account Api Key
[**get_broker_sub_account_bnb_burn_status_v1**](BinanceLinkApi.md#get_broker_sub_account_bnb_burn_status_v1) | **GET** /sapi/v1/broker/subAccount/bnbBurn/status | Get BNB Burn Status for Sub Account
[**get_broker_sub_account_deposit_hist_v1**](BinanceLinkApi.md#get_broker_sub_account_deposit_hist_v1) | **GET** /sapi/v1/broker/subAccount/depositHist | Get Sub Account Deposit History
[**get_broker_sub_account_deposit_hist_v2**](BinanceLinkApi.md#get_broker_sub_account_deposit_hist_v2) | **GET** /sapi/v2/broker/subAccount/depositHist | Get Sub Account Deposit History V2
[**get_broker_sub_account_futures_summary_v3**](BinanceLinkApi.md#get_broker_sub_account_futures_summary_v3) | **GET** /sapi/v3/broker/subAccount/futuresSummary | Query Sub Account Futures Asset info (V3)
[**get_broker_sub_account_margin_summary_v1**](BinanceLinkApi.md#get_broker_sub_account_margin_summary_v1) | **GET** /sapi/v1/broker/subAccount/marginSummary | Query Sub Account Margin Asset info
[**get_broker_sub_account_spot_summary_v1**](BinanceLinkApi.md#get_broker_sub_account_spot_summary_v1) | **GET** /sapi/v1/broker/subAccount/spotSummary | Query Sub Account Spot Asset info
[**get_broker_sub_account_v1**](BinanceLinkApi.md#get_broker_sub_account_v1) | **GET** /sapi/v1/broker/subAccount | Query Sub Account
[**get_broker_transfer_futures_v1**](BinanceLinkApi.md#get_broker_transfer_futures_v1) | **GET** /sapi/v1/broker/transfer/futures | Query Sub Account Transfer History（FUTURES）
[**get_broker_transfer_v1**](BinanceLinkApi.md#get_broker_transfer_v1) | **GET** /sapi/v1/broker/transfer | Query Sub Account Transfer History（SPOT）
[**get_broker_universal_transfer_v1**](BinanceLinkApi.md#get_broker_universal_transfer_v1) | **GET** /sapi/v1/broker/universalTransfer | Query Universal Transfer History



## create_api_referral_customization_v1

> models::CreateApiReferralCustomizationV1Resp create_api_referral_customization_v1(customer_id, email, timestamp, recv_window)
Customize Id For Client (USER DATA) （For Partner）

- CustomerId must be unique - For the same email, the customerId will be modified in real time

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**customer_id** | **String** |  | [required] |[default to ]
**email** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateApiReferralCustomizationV1Resp**](CreateApiReferralCustomizationV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_api_referral_user_customization_v1

> models::CreateApiReferralUserCustomizationV1Resp create_api_referral_user_customization_v1(api_agent_code, customer_id, timestamp, recv_window)
Customize Id For Client  (USER DATA)(For client)

- CustomerId must be unique for each apiAgent

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**api_agent_code** | **String** |  | [required] |[default to ]
**customer_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateApiReferralUserCustomizationV1Resp**](CreateApiReferralUserCustomizationV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_sub_account_api_commission_coin_futures_v1

> models::CreateBrokerSubAccountApiCommissionCoinFuturesV1Resp create_broker_sub_account_api_commission_coin_futures_v1(maker_adjustment, pair, sub_account_id, taker_adjustment, timestamp, recv_window)
Change Sub Account COIN-Ⓜ Futures Commission Adjustment

This request will change the COIN-Ⓜ futures commission for a sub account. You need to enable \"trade\" option for the api key which requests this endpoint. The sub-account's COIN-Ⓜ futures commission of a symbol equals to the base commission of the symbol on the sub-account's fee tier plus the commission adjustment.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**maker_adjustment** | **i32** |  | [required] |
**pair** | **String** |  | [required] |[default to ]
**sub_account_id** | **String** |  | [required] |[default to ]
**taker_adjustment** | **i32** |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateBrokerSubAccountApiCommissionCoinFuturesV1Resp**](CreateBrokerSubAccountApiCommissionCoinFuturesV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_sub_account_api_commission_futures_v1

> models::CreateBrokerSubAccountApiCommissionFuturesV1Resp create_broker_sub_account_api_commission_futures_v1(maker_adjustment, sub_account_id, symbol, taker_adjustment, timestamp, recv_window)
Change Sub Account USDT-Ⓜ Futures Commission Adjustment

This request will change the USDT-Ⓜ futures commission for a sub account. You need to enable \"trade\" option for the api key which requests this endpoint. The sub-account's USDT-Ⓜ futures commission of a symbol equals to the base commission of the symbol on the sub-account's fee tier plus the commission adjustment.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**maker_adjustment** | **i32** |  | [required] |
**sub_account_id** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**taker_adjustment** | **i32** |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateBrokerSubAccountApiCommissionFuturesV1Resp**](CreateBrokerSubAccountApiCommissionFuturesV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_sub_account_api_commission_v1

> models::CreateBrokerSubAccountApiCommissionV1Resp create_broker_sub_account_api_commission_v1(maker_commission, sub_account_id, taker_commission, timestamp, margin_maker_commission, margin_taker_commission, recv_window)
Change Sub Account Commission

This request will change the commission for a sub account. You need to enable \"trade\" option for the api key which requests this endpoint.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**maker_commission** | **f64** |  | [required] |
**sub_account_id** | **String** |  | [required] |[default to ]
**taker_commission** | **f64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**margin_maker_commission** | Option<**f64**> |  |  |
**margin_taker_commission** | Option<**f64**> |  |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateBrokerSubAccountApiCommissionV1Resp**](CreateBrokerSubAccountApiCommissionV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_sub_account_api_ip_restriction_v2

> models::CreateBrokerSubAccountApiIpRestrictionV2Resp create_broker_sub_account_api_ip_restriction_v2(status, sub_account_api_key, sub_account_id, timestamp, ip_address, recv_window)
Update IP Restriction for Sub-Account API key (For Master Account)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**status** | **String** |  | [required] |[default to ]
**sub_account_api_key** | **String** |  | [required] |[default to ]
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**ip_address** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateBrokerSubAccountApiIpRestrictionV2Resp**](CreateBrokerSubAccountApiIpRestrictionV2Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_sub_account_api_permission_universal_transfer_v1

> models::CreateBrokerSubAccountApiPermissionUniversalTransferV1Resp create_broker_sub_account_api_permission_universal_transfer_v1(can_universal_transfer, sub_account_api_key, sub_account_id, timestamp, recv_window)
Enable Universal Transfer Permission For Sub Account Api Key

Caution: - This request will enable the api permission for a sub account to use POST /sapi/v1/asset/transferendpoint. - You need to enable \"trade\" option for the api key which requests this endpoint.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**can_universal_transfer** | **String** |  | [required] |[default to ]
**sub_account_api_key** | **String** |  | [required] |[default to ]
**sub_account_id** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateBrokerSubAccountApiPermissionUniversalTransferV1Resp**](CreateBrokerSubAccountApiPermissionUniversalTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_sub_account_api_permission_v1

> models::CreateBrokerSubAccountApiPermissionV1Resp create_broker_sub_account_api_permission_v1(can_trade, futures_trade, margin_trade, sub_account_api_key, sub_account_id, timestamp, recv_window)
Change Sub Account Api Permission

Caution: - This request will change the api permission for a sub account. - You need to enable \"trade\" option for the api key which requests this endpoint. - Sub account should be enable margin before its api-key's marginTrade being enabled. - Sub account should be enable futures before its api-key's futuresTrade being enabled.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**can_trade** | **String** |  | [required] |[default to ]
**futures_trade** | **String** |  | [required] |[default to ]
**margin_trade** | **String** |  | [required] |[default to ]
**sub_account_api_key** | **String** |  | [required] |[default to ]
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateBrokerSubAccountApiPermissionV1Resp**](CreateBrokerSubAccountApiPermissionV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_sub_account_api_v1

> models::CreateBrokerSubAccountApiV1Resp create_broker_sub_account_api_v1(can_trade, sub_account_id, timestamp, futures_trade, margin_trade, public_key, recv_window)
Create Api Key for Sub Account

Caution: - This request will generate a api key for a sub account. - You need to enable \"trade\" option for the api key which requests this endpoint - Sub account should be enable margin before its api-key's marginTrade being enabled - Sub account should be enable futures before its api-key's futuresTrade being enabled - You can only create 1 api key for each sub account per second

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**can_trade** | **String** |  | [required] |[default to ]
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**futures_trade** | Option<**String**> |  |  |[default to ]
**margin_trade** | Option<**String**> |  |  |[default to ]
**public_key** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateBrokerSubAccountApiV1Resp**](CreateBrokerSubAccountApiV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_sub_account_bnb_burn_margin_interest_v1

> models::CreateBrokerSubAccountBnbBurnMarginInterestV1Resp create_broker_sub_account_bnb_burn_margin_interest_v1(interest_bnb_burn, sub_account_id, timestamp, recv_window)
Enable Or Disable BNB Burn for Sub Account Margin Interest

- Subaccount must be enabled margin before using this switch

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**interest_bnb_burn** | **String** |  | [required] |[default to ]
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateBrokerSubAccountBnbBurnMarginInterestV1Resp**](CreateBrokerSubAccountBnbBurnMarginInterestV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_sub_account_bnb_burn_spot_v1

> models::CreateBrokerSubAccountBnbBurnSpotV1Resp create_broker_sub_account_bnb_burn_spot_v1(spot_bnb_burn, sub_account_id, timestamp, recv_window)
Enable Or Disable BNB Burn for Sub Account SPOT and MARGIN

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**spot_bnb_burn** | **String** |  | [required] |[default to ]
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateBrokerSubAccountBnbBurnSpotV1Resp**](CreateBrokerSubAccountBnbBurnSpotV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_sub_account_futures_v1

> models::CreateBrokerSubAccountFuturesV1Resp create_broker_sub_account_futures_v1(futures, sub_account_id, timestamp, recv_window)
Enable Futures for Sub Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**futures** | **String** |  | [required] |[default to ]
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateBrokerSubAccountFuturesV1Resp**](CreateBrokerSubAccountFuturesV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_sub_account_v1

> models::CreateBrokerSubAccountV1Resp create_broker_sub_account_v1(timestamp, recv_window, tag)
Create a Sub Account

To create a link sub-account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |
**tag** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateBrokerSubAccountV1Resp**](CreateBrokerSubAccountV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_transfer_futures_v1

> models::CreateBrokerTransferFuturesV1Resp create_broker_transfer_futures_v1(amount, asset, futures_type, timestamp, client_tran_id, from_id, recv_window, to_id)
Sub Account Transfer（FUTURES）

Caution: - You need to enable \"internal transfer\" option for the api key which requests this endpoint. - Transfer from master account if fromId not sent. - Transfer to master account if toId not sent. - Each master account could transfer 5000 times/min

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**futures_type** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**client_tran_id** | Option<**String**> |  |  |[default to ]
**from_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**to_id** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateBrokerTransferFuturesV1Resp**](CreateBrokerTransferFuturesV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_transfer_v1

> models::CreateBrokerTransferV1Resp create_broker_transfer_v1(amount, asset, timestamp, client_tran_id, from_id, recv_window, to_id)
Sub Account Transfer（SPOT）

Caution: - You need to enable \"internal transfer\" option for the api key which requests this endpoint. - Transfer from master account if fromId not sent. - Transfer to master account if toId not sent.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**client_tran_id** | Option<**String**> |  |  |[default to ]
**from_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**to_id** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateBrokerTransferV1Resp**](CreateBrokerTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_broker_universal_transfer_v1

> models::CreateBrokerUniversalTransferV1Resp create_broker_universal_transfer_v1(amount, asset, from_account_type, timestamp, to_account_type, client_tran_id, from_id, recv_window, to_id)
Universal Transfer

Caution: - You need to enable \"internal transfer\" option for the api key which requests this endpoint. - Transfer from master account if fromId not sent. - Transfer to master account if toId not sent. - Transfer between futures acount is not supported.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**from_account_type** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**to_account_type** | **String** |  | [required] |[default to ]
**client_tran_id** | Option<**String**> |  |  |[default to ]
**from_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**to_id** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateBrokerUniversalTransferV1Resp**](CreateBrokerUniversalTransferV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_broker_sub_account_api_ip_restriction_ip_list_v1

> models::DeleteBrokerSubAccountApiIpRestrictionIpListV1Resp delete_broker_sub_account_api_ip_restriction_ip_list_v1(sub_account_id, sub_account_api_key, timestamp, ip_address, recv_window)
Delete IP Restriction for Sub Account Api Key

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sub_account_id** | **String** |  | [required] |[default to ]
**sub_account_api_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**ip_address** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::DeleteBrokerSubAccountApiIpRestrictionIpListV1Resp**](DeleteBrokerSubAccountApiIpRestrictionIpListV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_broker_sub_account_api_v1

> serde_json::Value delete_broker_sub_account_api_v1(sub_account_id, sub_account_api_key, timestamp, recv_window)
Delete Sub Account Api Key

Caution: - This request will delete a api key for a sub account - You need to enable \"trade\" option for the api key which requests this endpoint - You can only delete 1 api key for each sub account per second

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sub_account_id** | **String** |  | [required] |[default to ]
**sub_account_api_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_broker_sub_account_v1

> serde_json::Value delete_broker_sub_account_v1(sub_account_id, timestamp, recv_window)
Delete Sub Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_customization_v1

> Vec<models::GetApiReferralCustomizationV1RespItem> get_api_referral_customization_v1(timestamp, customer_id, email, recv_window)
Get Client Email Customized Id (USER DATA) （For Partner）

- CustomerId and email can not be sent at the same time

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**customer_id** | Option<**String**> |  |  |[default to ]
**email** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetApiReferralCustomizationV1RespItem>**](GetApiReferralCustomizationV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_if_new_user_v1

> models::GetApiReferralIfNewUserV1Resp get_api_referral_if_new_user_v1(api_agent_code, timestamp, recv_window)
Query Client If The New User (USER  DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**api_agent_code** | **String** | brokerId | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetApiReferralIfNewUserV1Resp**](GetApiReferralIfNewUserV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_kickback_recent_record_v1

> Vec<models::GetApiReferralKickbackRecentRecordV1RespItem> get_api_referral_kickback_recent_record_v1(timestamp, start_time, end_time, limit, recv_window)
Query Rebate Recent Record(For Client)

- Only get the latest history of past 7 days.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500, max 1000 |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetApiReferralKickbackRecentRecordV1RespItem>**](GetApiReferralKickbackRecentRecordV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_rebate_recent_record_v1

> Vec<models::GetApiReferralRebateRecentRecordV1RespItem> get_api_referral_rebate_recent_record_v1(start_time, end_time, limit, timestamp, customer_id, recv_window)
Query Rebate Recent Record （USER DATA）(For Partner)

- startTime and endTime must be both specified or both omitted. - When both omitted it returns last 7 days. - When both specified the span has to be within 7 days.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** |  | [required] |
**end_time** | **i64** |  | [required] |
**limit** | **i32** | max 500 | [required] |
**timestamp** | **i64** |  | [required] |
**customer_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetApiReferralRebateRecentRecordV1RespItem>**](GetApiReferralRebateRecentRecordV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_user_customization_v1

> models::GetApiReferralUserCustomizationV1Resp get_api_referral_user_customization_v1(api_agent_code, timestamp, recv_window)
Get User’s Customize Id (USER DATA)

- CustomerId must be unique

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**api_agent_code** | **String** | brokerId | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetApiReferralUserCustomizationV1Resp**](GetApiReferralUserCustomizationV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_info_v1

> models::GetBrokerInfoV1Resp get_broker_info_v1(timestamp, recv_window)
Link Account Information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetBrokerInfoV1Resp**](GetBrokerInfoV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_rebate_futures_recent_record_v1

> Vec<models::GetBrokerRebateFuturesRecentRecordV1RespItem> get_broker_rebate_futures_recent_record_v1(futures_type, start_time, end_time, timestamp, page, size, filter_result, recv_window)
Query Broker Futures Commission Rebate Record

- If filterResult = TRUE, rebates not from its own sub accounts will be filtered out in response.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**futures_type** | **i64** | 1:USDT Futures, 2: Coin Futures | [required] |
**start_time** | **i64** |  | [required] |
**end_time** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**page** | Option<**i64**> | default 1 |  |[default to 1]
**size** | Option<**i64**> | default 10, max 100 |  |[default to 10]
**filter_result** | Option<**bool**> | TRUE or FALSE. Default: FALSE |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBrokerRebateFuturesRecentRecordV1RespItem>**](GetBrokerRebateFuturesRecentRecordV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_rebate_recent_record_v1

> Vec<models::GetBrokerRebateRecentRecordV1RespItem> get_broker_rebate_recent_record_v1(timestamp, sub_account_id, start_time, end_time, page, size, recv_window)
Query Broker Commission Rebate Recent Record（Spot）

- The query time period must be less than 7 days (default as the recent 7 days).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**sub_account_id** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> | Default: 7 days from current timestamp |  |
**end_time** | Option<**i64**> | Default: present timestamp |  |
**page** | Option<**i64**> | default 1 |  |[default to 1]
**size** | Option<**i64**> | default 500，max500 |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBrokerRebateRecentRecordV1RespItem>**](GetBrokerRebateRecentRecordV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_sub_account_api_commission_coin_futures_v1

> Vec<models::GetBrokerSubAccountApiCommissionCoinFuturesV1RespItem> get_broker_sub_account_api_commission_coin_futures_v1(sub_account_id, timestamp, pair, recv_window)
Query Sub Account COIN-Ⓜ Futures Commission Adjustment

- The sub-account's COIN-Ⓜ futures commission of a symbol equals to the base commission of the symbol on the sub-account's fee tier plus the commission adjustment. - If symbol not sent, commission adjustment of all symbols will be returned. - If futures disabled, it is not allowed to set subaccount's COIN-Ⓜ futures commission adjustment on any symbol. - Different symbols have the same commission for the same pair

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**pair** | Option<**String**> | BTCUSD |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBrokerSubAccountApiCommissionCoinFuturesV1RespItem>**](GetBrokerSubAccountApiCommissionCoinFuturesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_sub_account_api_commission_futures_v1

> Vec<models::GetBrokerSubAccountApiCommissionFuturesV1RespItem> get_broker_sub_account_api_commission_futures_v1(sub_account_id, timestamp, symbol, recv_window)
Query Sub Account USDT-Ⓜ Futures Commission Adjustment

The sub-account's USDT-Ⓜ futures commission of a symbol equals to the base commission of the symbol on the sub-account's fee tier plus the commission adjustment.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBrokerSubAccountApiCommissionFuturesV1RespItem>**](GetBrokerSubAccountApiCommissionFuturesV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_sub_account_api_ip_restriction_v1

> models::GetBrokerSubAccountApiIpRestrictionV1Resp get_broker_sub_account_api_ip_restriction_v1(sub_account_id, sub_account_api_key, timestamp, recv_window)
Get IP Restriction for Sub Account Api Key

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sub_account_id** | **String** |  | [required] |[default to ]
**sub_account_api_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetBrokerSubAccountApiIpRestrictionV1Resp**](GetBrokerSubAccountApiIpRestrictionV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_sub_account_api_v1

> Vec<models::GetBrokerSubAccountApiV1RespItem> get_broker_sub_account_api_v1(sub_account_id, timestamp, sub_account_api_key, page, size, recv_window)
Query Sub Account Api Key

Caution: - You need to enable \"trade\" option for the api key which requests this endpoint

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**sub_account_api_key** | Option<**String**> |  |  |[default to ]
**page** | Option<**i64**> | default 1 |  |[default to 1]
**size** | Option<**i64**> | default 500, max 500 |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBrokerSubAccountApiV1RespItem>**](GetBrokerSubAccountApiV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_sub_account_bnb_burn_status_v1

> models::GetBrokerSubAccountBnbBurnStatusV1Resp get_broker_sub_account_bnb_burn_status_v1(sub_account_id, timestamp, recv_window)
Get BNB Burn Status for Sub Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetBrokerSubAccountBnbBurnStatusV1Resp**](GetBrokerSubAccountBnbBurnStatusV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_sub_account_deposit_hist_v1

> Vec<models::GetBrokerSubAccountDepositHistV1RespItem> get_broker_sub_account_deposit_hist_v1(timestamp, sub_account_id, coin, status, start_time, end_time, limit, offset, recv_window)
Get Sub Account Deposit History

- The query time period must be less than 7 days( default as the recent 7 days).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**sub_account_id** | Option<**String**> |  |  |[default to ]
**coin** | Option<**String**> |  |  |[default to ]
**status** | Option<**i32**> | 0(0:pending,6: credited but cannot withdraw, 1:success) |  |
**start_time** | Option<**i64**> | Default: 7 days from current timestamp |  |
**end_time** | Option<**i64**> | Default: present timestamp |  |
**limit** | Option<**i32**> | Default：500 |  |
**offset** | Option<**i32**> | Default：0 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBrokerSubAccountDepositHistV1RespItem>**](GetBrokerSubAccountDepositHistV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_sub_account_deposit_hist_v2

> Vec<models::GetBrokerSubAccountDepositHistV2RespItem> get_broker_sub_account_deposit_hist_v2(deposit_id, sub_account_id, timestamp, limit, offset, recv_window)
Get Sub Account Deposit History V2

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**deposit_id** | **String** |  | [required] |[default to ]
**sub_account_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**limit** | Option<**i32**> | Default：500 |  |
**offset** | Option<**i32**> | Default：0 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBrokerSubAccountDepositHistV2RespItem>**](GetBrokerSubAccountDepositHistV2RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_sub_account_futures_summary_v3

> models::ExchangelinkGetBrokerSubAccountFuturesSummaryV3Resp get_broker_sub_account_futures_summary_v3(futures_type, timestamp, sub_account_id, page, size, recv_window)
Query Sub Account Futures Asset info (V3)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**futures_type** | **i32** | 1:USD Margined Futures, 2:COIN Margined Futures | [required] |
**timestamp** | **i64** |  | [required] |
**sub_account_id** | Option<**String**> |  |  |[default to ]
**page** | Option<**i64**> | default 1 |  |[default to 1]
**size** | Option<**i64**> | default 10, max 20 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::ExchangelinkGetBrokerSubAccountFuturesSummaryV3Resp**](ExchangelinkGetBrokerSubAccountFuturesSummaryV3Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_sub_account_margin_summary_v1

> models::GetBrokerSubAccountMarginSummaryV1Resp get_broker_sub_account_margin_summary_v1(timestamp, sub_account_id, page, size, recv_window)
Query Sub Account Margin Asset info

- If subaccountId is not sent, the size must be sent

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**sub_account_id** | Option<**String**> |  |  |[default to ]
**page** | Option<**i64**> | default 1 |  |[default to 1]
**size** | Option<**i64**> | default 10, max 20 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetBrokerSubAccountMarginSummaryV1Resp**](GetBrokerSubAccountMarginSummaryV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_sub_account_spot_summary_v1

> models::GetBrokerSubAccountSpotSummaryV1Resp get_broker_sub_account_spot_summary_v1(timestamp, sub_account_id, page, size, recv_window)
Query Sub Account Spot Asset info

- If subaccountId is not sent, the size must be sent - Requests per UID are limited to 60 requests per minute

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**sub_account_id** | Option<**String**> |  |  |[default to ]
**page** | Option<**i64**> | default 1 |  |[default to 1]
**size** | Option<**i64**> | default 10, max 20 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetBrokerSubAccountSpotSummaryV1Resp**](GetBrokerSubAccountSpotSummaryV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_sub_account_v1

> Vec<models::GetBrokerSubAccountV1RespItem> get_broker_sub_account_v1(timestamp, sub_account_id, page, size, recv_window)
Query Sub Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**sub_account_id** | Option<**String**> |  |  |[default to ]
**page** | Option<**i64**> | default 1 |  |[default to 1]
**size** | Option<**i64**> | default 500 |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBrokerSubAccountV1RespItem>**](GetBrokerSubAccountV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_transfer_futures_v1

> models::GetBrokerTransferFuturesV1Resp get_broker_transfer_futures_v1(sub_account_id, futures_type, timestamp, client_tran_id, start_time, end_time, page, limit, recv_window)
Query Sub Account Transfer History（FUTURES）

- Only get the latest history of past 30 days.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sub_account_id** | **String** |  | [required] |[default to ]
**futures_type** | **i64** | 1:USDT Futures,2: COIN Futures | [required] |
**timestamp** | **i64** |  | [required] |
**client_tran_id** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> | default 30 days records |  |
**end_time** | Option<**i64**> | default 30 days records |  |
**page** | Option<**i32**> | default 1 |  |[default to 1]
**limit** | Option<**i32**> | default 50, max 500 |  |[default to 50]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetBrokerTransferFuturesV1Resp**](GetBrokerTransferFuturesV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_transfer_v1

> Vec<models::GetBrokerTransferV1RespItem> get_broker_transfer_v1(timestamp, from_id, to_id, client_tran_id, show_all_status, start_time, end_time, page, limit, recv_window)
Query Sub Account Transfer History（SPOT）

Caution: - If showAllStatus is true, the status in response will show four types: INIT,PROCESS,SUCCESS,FAILURE. - If showAllStatus is false, the status in response will show three types: INIT,PROCESS,SUCCESS. - Either fromId or toId must be sent. Return fromId equal master account by default. Query scope is limited to 100 days: - Both startTime and endTime are provided: If it exceeds, the endTime will be re-calculated 100 days after the startTime. - Neither startTime nor endTime are provided: Calculate 100 days before today. - endTime is not provided: Calculate 100 days after startTime. - startTime is not provided: Calculate 100 days before endTime.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**from_id** | Option<**String**> |  |  |[default to ]
**to_id** | Option<**String**> |  |  |[default to ]
**client_tran_id** | Option<**String**> | client transfer id |  |[default to ]
**show_all_status** | Option<**String**> | true or false, default: false |  |[default to false]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**page** | Option<**i32**> |  |  |
**limit** | Option<**i32**> | default 500, max 500 |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBrokerTransferV1RespItem>**](GetBrokerTransferV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_broker_universal_transfer_v1

> Vec<models::GetBrokerUniversalTransferV1RespItem> get_broker_universal_transfer_v1(timestamp, from_id, to_id, client_tran_id, start_time, end_time, page, limit, show_all_status, recv_window)
Query Universal Transfer History

Caution: - Either fromId or toId must be sent. - If either fromId or toId is the master account itself, it will not return in response. - If showAllStatus is true, the status in response will show four types: INIT,PROCESS,SUCCESS,FAILURE. Query scope is limited to 100 days: - Both startTime and endTime are provided: If it exceeds, the endTime will be re-calculated 100 days after the startTime. - Neither startTime nor endTime are provided: Calculate 30 days before today. - endTime is not provided: Calculate as Current time. - startTime is not provided: Calculate 30 days before endTime.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**from_id** | Option<**String**> |  |  |[default to ]
**to_id** | Option<**String**> |  |  |[default to ]
**client_tran_id** | Option<**String**> | client transfer id |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**page** | Option<**i32**> | default 1 |  |[default to 1]
**limit** | Option<**i32**> | default 500, max 500 |  |[default to 500]
**show_all_status** | Option<**bool**> | TRUE or FALSE |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetBrokerUniversalTransferV1RespItem>**](GetBrokerUniversalTransferV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

