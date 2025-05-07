# \SimpleEarnApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_simple_earn_flexible_redeem_v1**](SimpleEarnApi.md#create_simple_earn_flexible_redeem_v1) | **POST** /sapi/v1/simple-earn/flexible/redeem | Redeem Flexible Product(TRADE)
[**create_simple_earn_flexible_set_auto_subscribe_v1**](SimpleEarnApi.md#create_simple_earn_flexible_set_auto_subscribe_v1) | **POST** /sapi/v1/simple-earn/flexible/setAutoSubscribe | Set Flexible Auto Subscribe(USER_DATA)
[**create_simple_earn_flexible_subscribe_v1**](SimpleEarnApi.md#create_simple_earn_flexible_subscribe_v1) | **POST** /sapi/v1/simple-earn/flexible/subscribe | Subscribe Flexible Product(TRADE)
[**create_simple_earn_locked_redeem_v1**](SimpleEarnApi.md#create_simple_earn_locked_redeem_v1) | **POST** /sapi/v1/simple-earn/locked/redeem | Redeem Locked Product(TRADE)
[**create_simple_earn_locked_set_auto_subscribe_v1**](SimpleEarnApi.md#create_simple_earn_locked_set_auto_subscribe_v1) | **POST** /sapi/v1/simple-earn/locked/setAutoSubscribe | Set Locked Auto Subscribe(USER_DATA)
[**create_simple_earn_locked_set_redeem_option_v1**](SimpleEarnApi.md#create_simple_earn_locked_set_redeem_option_v1) | **POST** /sapi/v1/simple-earn/locked/setRedeemOption | Set Locked Product Redeem Option(USER_DATA)
[**create_simple_earn_locked_subscribe_v1**](SimpleEarnApi.md#create_simple_earn_locked_subscribe_v1) | **POST** /sapi/v1/simple-earn/locked/subscribe | Subscribe Locked Product(TRADE)
[**get_simple_earn_account_v1**](SimpleEarnApi.md#get_simple_earn_account_v1) | **GET** /sapi/v1/simple-earn/account | Simple Account(USER_DATA)
[**get_simple_earn_flexible_history_collateral_record_v1**](SimpleEarnApi.md#get_simple_earn_flexible_history_collateral_record_v1) | **GET** /sapi/v1/simple-earn/flexible/history/collateralRecord | Get Collateral Record(USER_DATA)
[**get_simple_earn_flexible_history_rate_history_v1**](SimpleEarnApi.md#get_simple_earn_flexible_history_rate_history_v1) | **GET** /sapi/v1/simple-earn/flexible/history/rateHistory | Get Rate History(USER_DATA)
[**get_simple_earn_flexible_history_redemption_record_v1**](SimpleEarnApi.md#get_simple_earn_flexible_history_redemption_record_v1) | **GET** /sapi/v1/simple-earn/flexible/history/redemptionRecord | Get Flexible Redemption Record(USER_DATA)
[**get_simple_earn_flexible_history_rewards_record_v1**](SimpleEarnApi.md#get_simple_earn_flexible_history_rewards_record_v1) | **GET** /sapi/v1/simple-earn/flexible/history/rewardsRecord | Get Flexible Rewards History(USER_DATA)
[**get_simple_earn_flexible_history_subscription_record_v1**](SimpleEarnApi.md#get_simple_earn_flexible_history_subscription_record_v1) | **GET** /sapi/v1/simple-earn/flexible/history/subscriptionRecord | Get Flexible Subscription Record(USER_DATA)
[**get_simple_earn_flexible_list_v1**](SimpleEarnApi.md#get_simple_earn_flexible_list_v1) | **GET** /sapi/v1/simple-earn/flexible/list | Get Simple Earn Flexible Product List(USER_DATA)
[**get_simple_earn_flexible_personal_left_quota_v1**](SimpleEarnApi.md#get_simple_earn_flexible_personal_left_quota_v1) | **GET** /sapi/v1/simple-earn/flexible/personalLeftQuota | Get Flexible Personal Left Quota(USER_DATA)
[**get_simple_earn_flexible_position_v1**](SimpleEarnApi.md#get_simple_earn_flexible_position_v1) | **GET** /sapi/v1/simple-earn/flexible/position | Get Flexible Product Position(USER_DATA)
[**get_simple_earn_flexible_subscription_preview_v1**](SimpleEarnApi.md#get_simple_earn_flexible_subscription_preview_v1) | **GET** /sapi/v1/simple-earn/flexible/subscriptionPreview | Get Flexible Subscription Preview(USER_DATA)
[**get_simple_earn_locked_history_redemption_record_v1**](SimpleEarnApi.md#get_simple_earn_locked_history_redemption_record_v1) | **GET** /sapi/v1/simple-earn/locked/history/redemptionRecord | Get Locked Redemption Record(USER_DATA)
[**get_simple_earn_locked_history_rewards_record_v1**](SimpleEarnApi.md#get_simple_earn_locked_history_rewards_record_v1) | **GET** /sapi/v1/simple-earn/locked/history/rewardsRecord | Get Locked Rewards History(USER_DATA)
[**get_simple_earn_locked_history_subscription_record_v1**](SimpleEarnApi.md#get_simple_earn_locked_history_subscription_record_v1) | **GET** /sapi/v1/simple-earn/locked/history/subscriptionRecord | Get Locked Subscription Record(USER_DATA)
[**get_simple_earn_locked_list_v1**](SimpleEarnApi.md#get_simple_earn_locked_list_v1) | **GET** /sapi/v1/simple-earn/locked/list | Get Simple Earn Locked Product List(USER_DATA)
[**get_simple_earn_locked_personal_left_quota_v1**](SimpleEarnApi.md#get_simple_earn_locked_personal_left_quota_v1) | **GET** /sapi/v1/simple-earn/locked/personalLeftQuota | Get Locked Personal Left Quota(USER_DATA)
[**get_simple_earn_locked_position_v1**](SimpleEarnApi.md#get_simple_earn_locked_position_v1) | **GET** /sapi/v1/simple-earn/locked/position | Get Locked Product Position
[**get_simple_earn_locked_subscription_preview_v1**](SimpleEarnApi.md#get_simple_earn_locked_subscription_preview_v1) | **GET** /sapi/v1/simple-earn/locked/subscriptionPreview | Get Locked Subscription Preview(USER_DATA)



## create_simple_earn_flexible_redeem_v1

> models::CreateSimpleEarnFlexibleRedeemV1Resp create_simple_earn_flexible_redeem_v1(product_id, timestamp, amount, dest_account, recv_window, redeem_all)
Redeem Flexible Product(TRADE)

Redeem Flexible Product

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**product_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**amount** | Option<**String**> |  |  |[default to ]
**dest_account** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**redeem_all** | Option<**bool**> |  |  |

### Return type

[**models::CreateSimpleEarnFlexibleRedeemV1Resp**](CreateSimpleEarnFlexibleRedeemV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_simple_earn_flexible_set_auto_subscribe_v1

> models::CreateSimpleEarnFlexibleSetAutoSubscribeV1Resp create_simple_earn_flexible_set_auto_subscribe_v1(auto_subscribe, product_id, timestamp, recv_window)
Set Flexible Auto Subscribe(USER_DATA)

Set Flexible Auto Subscribe

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**auto_subscribe** | **bool** |  | [required] |
**product_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSimpleEarnFlexibleSetAutoSubscribeV1Resp**](CreateSimpleEarnFlexibleSetAutoSubscribeV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_simple_earn_flexible_subscribe_v1

> models::CreateSimpleEarnFlexibleSubscribeV1Resp create_simple_earn_flexible_subscribe_v1(amount, product_id, timestamp, auto_subscribe, recv_window, source_account)
Subscribe Flexible Product(TRADE)

Subscribe Flexible Product

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**product_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**auto_subscribe** | Option<**bool**> |  |  |[default to true]
**recv_window** | Option<**i64**> |  |  |
**source_account** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateSimpleEarnFlexibleSubscribeV1Resp**](CreateSimpleEarnFlexibleSubscribeV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_simple_earn_locked_redeem_v1

> models::CreateSimpleEarnLockedRedeemV1Resp create_simple_earn_locked_redeem_v1(position_id, timestamp, recv_window)
Redeem Locked Product(TRADE)

Redeem Locked Product

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**position_id** | **i32** |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSimpleEarnLockedRedeemV1Resp**](CreateSimpleEarnLockedRedeemV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_simple_earn_locked_set_auto_subscribe_v1

> models::CreateSimpleEarnLockedSetAutoSubscribeV1Resp create_simple_earn_locked_set_auto_subscribe_v1(auto_subscribe, position_id, timestamp, recv_window)
Set Locked Auto Subscribe(USER_DATA)

Set locked auto subscribe

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**auto_subscribe** | **bool** |  | [required] |
**position_id** | **i32** |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSimpleEarnLockedSetAutoSubscribeV1Resp**](CreateSimpleEarnLockedSetAutoSubscribeV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_simple_earn_locked_set_redeem_option_v1

> models::CreateSimpleEarnLockedSetRedeemOptionV1Resp create_simple_earn_locked_set_redeem_option_v1(position_id, redeem_to, timestamp, recv_window)
Set Locked Product Redeem Option(USER_DATA)

Set redeem option for Locked product

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**position_id** | **String** |  | [required] |[default to ]
**redeem_to** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSimpleEarnLockedSetRedeemOptionV1Resp**](CreateSimpleEarnLockedSetRedeemOptionV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_simple_earn_locked_subscribe_v1

> models::CreateSimpleEarnLockedSubscribeV1Resp create_simple_earn_locked_subscribe_v1(amount, project_id, timestamp, auto_subscribe, recv_window, redeem_to, source_account)
Subscribe Locked Product(TRADE)

Subscribe Locked Product

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**project_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**auto_subscribe** | Option<**bool**> |  |  |[default to false]
**recv_window** | Option<**i64**> |  |  |
**redeem_to** | Option<**String**> |  |  |[default to ]
**source_account** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateSimpleEarnLockedSubscribeV1Resp**](CreateSimpleEarnLockedSubscribeV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_account_v1

> models::GetSimpleEarnAccountV1Resp get_simple_earn_account_v1(timestamp, recv_window)
Simple Account(USER_DATA)

Simple Account query

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetSimpleEarnAccountV1Resp**](GetSimpleEarnAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_flexible_history_collateral_record_v1

> models::GetSimpleEarnFlexibleHistoryCollateralRecordV1Resp get_simple_earn_flexible_history_collateral_record_v1(timestamp, product_id, start_time, end_time, current, size, recv_window)
Get Collateral Record(USER_DATA)

Get Collateral Record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**product_id** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetSimpleEarnFlexibleHistoryCollateralRecordV1Resp**](GetSimpleEarnFlexibleHistoryCollateralRecordV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_flexible_history_rate_history_v1

> models::GetSimpleEarnFlexibleHistoryRateHistoryV1Resp get_simple_earn_flexible_history_rate_history_v1(product_id, timestamp, apr_period, start_time, end_time, current, size, recv_window)
Get Rate History(USER_DATA)

Get Rate History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**product_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**apr_period** | Option<**String**> | &#34;DAY&#34;,&#34;YEAR&#34;,default&#34;DAY&#34; |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetSimpleEarnFlexibleHistoryRateHistoryV1Resp**](GetSimpleEarnFlexibleHistoryRateHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_flexible_history_redemption_record_v1

> models::GetSimpleEarnFlexibleHistoryRedemptionRecordV1Resp get_simple_earn_flexible_history_redemption_record_v1(product_id, redeem_id, asset, start_time, end_time, current, size)
Get Flexible Redemption Record(USER_DATA)

Get Flexible Redemption Record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**product_id** | Option<**String**> |  |  |[default to ]
**redeem_id** | Option<**String**> |  |  |[default to ]
**asset** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying the page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |

### Return type

[**models::GetSimpleEarnFlexibleHistoryRedemptionRecordV1Resp**](GetSimpleEarnFlexibleHistoryRedemptionRecordV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_flexible_history_rewards_record_v1

> models::GetSimpleEarnFlexibleHistoryRewardsRecordV1Resp get_simple_earn_flexible_history_rewards_record_v1(r#type, timestamp, product_id, asset, start_time, end_time, current, size, recv_window)
Get Flexible Rewards History(USER_DATA)

Get Flexible Rewards History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**r#type** | **String** | `Bonus` - Bonus tiered APR, `REALTIME` Real-time APR, `REWARDS` Historical rewards,`ALL`(set to default) | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**product_id** | Option<**String**> |  |  |[default to ]
**asset** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying the page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSimpleEarnFlexibleHistoryRewardsRecordV1Resp**](GetSimpleEarnFlexibleHistoryRewardsRecordV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_flexible_history_subscription_record_v1

> models::GetSimpleEarnFlexibleHistorySubscriptionRecordV1Resp get_simple_earn_flexible_history_subscription_record_v1(timestamp, product_id, purchase_id, asset, start_time, end_time, current, size, recv_window)
Get Flexible Subscription Record(USER_DATA)

Get Flexible Subscription Record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**product_id** | Option<**String**> |  |  |[default to ]
**purchase_id** | Option<**String**> |  |  |[default to ]
**asset** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying the page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSimpleEarnFlexibleHistorySubscriptionRecordV1Resp**](GetSimpleEarnFlexibleHistorySubscriptionRecordV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_flexible_list_v1

> models::GetSimpleEarnFlexibleListV1Resp get_simple_earn_flexible_list_v1(timestamp, asset, current, size, recv_window)
Get Simple Earn Flexible Product List(USER_DATA)

Get available Simple Earn flexible product list

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSimpleEarnFlexibleListV1Resp**](GetSimpleEarnFlexibleListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_flexible_personal_left_quota_v1

> models::GetSimpleEarnFlexiblePersonalLeftQuotaV1Resp get_simple_earn_flexible_personal_left_quota_v1(product_id, timestamp, recv_window)
Get Flexible Personal Left Quota(USER_DATA)

Get Flexible Personal Left Quota

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**product_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSimpleEarnFlexiblePersonalLeftQuotaV1Resp**](GetSimpleEarnFlexiblePersonalLeftQuotaV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_flexible_position_v1

> models::GetSimpleEarnFlexiblePositionV1Resp get_simple_earn_flexible_position_v1(timestamp, asset, product_id, current, size, recv_window)
Get Flexible Product Position(USER_DATA)

Get Flexible Product Position

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**product_id** | Option<**String**> |  |  |[default to ]
**current** | Option<**i64**> | Currently querying the page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSimpleEarnFlexiblePositionV1Resp**](GetSimpleEarnFlexiblePositionV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_flexible_subscription_preview_v1

> models::GetSimpleEarnFlexibleSubscriptionPreviewV1Resp get_simple_earn_flexible_subscription_preview_v1(product_id, amount, timestamp, recv_window)
Get Flexible Subscription Preview(USER_DATA)

Get Flexible Subscription Preview

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**product_id** | **String** |  | [required] |[default to ]
**amount** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSimpleEarnFlexibleSubscriptionPreviewV1Resp**](GetSimpleEarnFlexibleSubscriptionPreviewV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_locked_history_redemption_record_v1

> models::GetSimpleEarnLockedHistoryRedemptionRecordV1Resp get_simple_earn_locked_history_redemption_record_v1(timestamp, position_id, redeem_id, asset, start_time, end_time, current, size, recv_window)
Get Locked Redemption Record(USER_DATA)

Get Locked Redemption Record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**position_id** | Option<**i32**> |  |  |
**redeem_id** | Option<**String**> |  |  |[default to ]
**asset** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying the page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSimpleEarnLockedHistoryRedemptionRecordV1Resp**](GetSimpleEarnLockedHistoryRedemptionRecordV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_locked_history_rewards_record_v1

> models::GetSimpleEarnLockedHistoryRewardsRecordV1Resp get_simple_earn_locked_history_rewards_record_v1(timestamp, position_id, asset, start_time, end_time, current, size, recv_window)
Get Locked Rewards History(USER_DATA)

Get Locked Rewards History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**position_id** | Option<**i32**> |  |  |
**asset** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying the page. Start from 1, Default:1, Max: 1,000 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSimpleEarnLockedHistoryRewardsRecordV1Resp**](GetSimpleEarnLockedHistoryRewardsRecordV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_locked_history_subscription_record_v1

> models::GetSimpleEarnLockedHistorySubscriptionRecordV1Resp get_simple_earn_locked_history_subscription_record_v1(timestamp, purchase_id, asset, start_time, end_time, current, size, recv_window)
Get Locked Subscription Record(USER_DATA)

Get Locked Subscription Record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**purchase_id** | Option<**String**> |  |  |[default to ]
**asset** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying the page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSimpleEarnLockedHistorySubscriptionRecordV1Resp**](GetSimpleEarnLockedHistorySubscriptionRecordV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_locked_list_v1

> models::GetSimpleEarnLockedListV1Resp get_simple_earn_locked_list_v1(timestamp, asset, current, size, recv_window)
Get Simple Earn Locked Product List(USER_DATA)

Get Simple Earn Locked Product List

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSimpleEarnLockedListV1Resp**](GetSimpleEarnLockedListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_locked_personal_left_quota_v1

> models::GetSimpleEarnLockedPersonalLeftQuotaV1Resp get_simple_earn_locked_personal_left_quota_v1(project_id, timestamp, recv_window)
Get Locked Personal Left Quota(USER_DATA)

Get Locked Personal Left Quota

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**project_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSimpleEarnLockedPersonalLeftQuotaV1Resp**](GetSimpleEarnLockedPersonalLeftQuotaV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_locked_position_v1

> models::GetSimpleEarnLockedPositionV1Resp get_simple_earn_locked_position_v1(timestamp, asset, position_id, project_id, current, size, recv_window)
Get Locked Product Position

Get Locked Product Position

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**position_id** | Option<**i32**> |  |  |
**project_id** | Option<**String**> |  |  |[default to ]
**current** | Option<**i64**> | Currently querying the page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSimpleEarnLockedPositionV1Resp**](GetSimpleEarnLockedPositionV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_simple_earn_locked_subscription_preview_v1

> Vec<models::GetSimpleEarnLockedSubscriptionPreviewV1RespItem> get_simple_earn_locked_subscription_preview_v1(project_id, amount, timestamp, auto_subscribe, recv_window)
Get Locked Subscription Preview(USER_DATA)

Get Locked Subscription Preview

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**project_id** | **String** |  | [required] |[default to ]
**amount** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**auto_subscribe** | Option<**bool**> | true or false, default true. |  |[default to true]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetSimpleEarnLockedSubscriptionPreviewV1RespItem>**](GetSimpleEarnLockedSubscriptionPreviewV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

