# \StakingApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_eth_staking_eth_redeem_v1**](StakingApi.md#create_eth_staking_eth_redeem_v1) | **POST** /sapi/v1/eth-staking/eth/redeem | Redeem ETH(TRADE)
[**create_eth_staking_eth_stake_v2**](StakingApi.md#create_eth_staking_eth_stake_v2) | **POST** /sapi/v2/eth-staking/eth/stake | Subscribe ETH Staking(TRADE)
[**create_eth_staking_wbeth_wrap_v1**](StakingApi.md#create_eth_staking_wbeth_wrap_v1) | **POST** /sapi/v1/eth-staking/wbeth/wrap | Wrap BETH(TRADE)
[**create_sol_staking_sol_claim_v1**](StakingApi.md#create_sol_staking_sol_claim_v1) | **POST** /sapi/v1/sol-staking/sol/claim | Claim Boost Rewards(TRADE)
[**create_sol_staking_sol_redeem_v1**](StakingApi.md#create_sol_staking_sol_redeem_v1) | **POST** /sapi/v1/sol-staking/sol/redeem | Redeem SOL(TRADE)
[**create_sol_staking_sol_stake_v1**](StakingApi.md#create_sol_staking_sol_stake_v1) | **POST** /sapi/v1/sol-staking/sol/stake | Subscribe SOL Staking(TRADE)
[**get_eth_staking_account_v2**](StakingApi.md#get_eth_staking_account_v2) | **GET** /sapi/v2/eth-staking/account | ETH Staking account(USER_DATA)
[**get_eth_staking_eth_history_rate_history_v1**](StakingApi.md#get_eth_staking_eth_history_rate_history_v1) | **GET** /sapi/v1/eth-staking/eth/history/rateHistory | Get WBETH Rate History(USER_DATA)
[**get_eth_staking_eth_history_redemption_history_v1**](StakingApi.md#get_eth_staking_eth_history_redemption_history_v1) | **GET** /sapi/v1/eth-staking/eth/history/redemptionHistory | Get ETH redemption history(USER_DATA)
[**get_eth_staking_eth_history_rewards_history_v1**](StakingApi.md#get_eth_staking_eth_history_rewards_history_v1) | **GET** /sapi/v1/eth-staking/eth/history/rewardsHistory | Get BETH rewards distribution history(USER_DATA)
[**get_eth_staking_eth_history_staking_history_v1**](StakingApi.md#get_eth_staking_eth_history_staking_history_v1) | **GET** /sapi/v1/eth-staking/eth/history/stakingHistory | Get ETH staking history(USER_DATA)
[**get_eth_staking_eth_history_wbeth_rewards_history_v1**](StakingApi.md#get_eth_staking_eth_history_wbeth_rewards_history_v1) | **GET** /sapi/v1/eth-staking/eth/history/wbethRewardsHistory | Get WBETH rewards history(USER_DATA)
[**get_eth_staking_eth_quota_v1**](StakingApi.md#get_eth_staking_eth_quota_v1) | **GET** /sapi/v1/eth-staking/eth/quota | Get current ETH staking quota(USER_DATA)
[**get_eth_staking_wbeth_history_unwrap_history_v1**](StakingApi.md#get_eth_staking_wbeth_history_unwrap_history_v1) | **GET** /sapi/v1/eth-staking/wbeth/history/unwrapHistory | Get WBETH unwrap history(USER_DATA)
[**get_eth_staking_wbeth_history_wrap_history_v1**](StakingApi.md#get_eth_staking_wbeth_history_wrap_history_v1) | **GET** /sapi/v1/eth-staking/wbeth/history/wrapHistory | Get WBETH wrap history(USER_DATA)
[**get_sol_staking_account_v1**](StakingApi.md#get_sol_staking_account_v1) | **GET** /sapi/v1/sol-staking/account | SOL Staking account(USER_DATA)
[**get_sol_staking_sol_history_bnsol_rewards_history_v1**](StakingApi.md#get_sol_staking_sol_history_bnsol_rewards_history_v1) | **GET** /sapi/v1/sol-staking/sol/history/bnsolRewardsHistory | Get BNSOL rewards history(USER_DATA)
[**get_sol_staking_sol_history_boost_rewards_history_v1**](StakingApi.md#get_sol_staking_sol_history_boost_rewards_history_v1) | **GET** /sapi/v1/sol-staking/sol/history/boostRewardsHistory | Get Boost Rewards History(USER_DATA)
[**get_sol_staking_sol_history_rate_history_v1**](StakingApi.md#get_sol_staking_sol_history_rate_history_v1) | **GET** /sapi/v1/sol-staking/sol/history/rateHistory | Get BNSOL Rate History(USER_DATA)
[**get_sol_staking_sol_history_redemption_history_v1**](StakingApi.md#get_sol_staking_sol_history_redemption_history_v1) | **GET** /sapi/v1/sol-staking/sol/history/redemptionHistory | Get SOL redemption history(USER_DATA)
[**get_sol_staking_sol_history_staking_history_v1**](StakingApi.md#get_sol_staking_sol_history_staking_history_v1) | **GET** /sapi/v1/sol-staking/sol/history/stakingHistory | Get SOL staking history(USER_DATA)
[**get_sol_staking_sol_history_unclaimed_rewards_v1**](StakingApi.md#get_sol_staking_sol_history_unclaimed_rewards_v1) | **GET** /sapi/v1/sol-staking/sol/history/unclaimedRewards | Get Unclaimed Rewards(USER_DATA)
[**get_sol_staking_sol_quota_v1**](StakingApi.md#get_sol_staking_sol_quota_v1) | **GET** /sapi/v1/sol-staking/sol/quota | Get SOL staking quota details(USER_DATA)



## create_eth_staking_eth_redeem_v1

> models::CreateEthStakingEthRedeemV1Resp create_eth_staking_eth_redeem_v1(amount, timestamp, asset, recv_window)
Redeem ETH(TRADE)

Redeem WBETH or BETH and get ETH

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateEthStakingEthRedeemV1Resp**](CreateEthStakingEthRedeemV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_eth_staking_eth_stake_v2

> models::CreateEthStakingEthStakeV2Resp create_eth_staking_eth_stake_v2(amount, timestamp, recv_window)
Subscribe ETH Staking(TRADE)

Subscribe ETH Staking

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateEthStakingEthStakeV2Resp**](CreateEthStakingEthStakeV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_eth_staking_wbeth_wrap_v1

> models::CreateEthStakingWbethWrapV1Resp create_eth_staking_wbeth_wrap_v1(amount, timestamp, recv_window)
Wrap BETH(TRADE)

Wrap BETH

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateEthStakingWbethWrapV1Resp**](CreateEthStakingWbethWrapV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sol_staking_sol_claim_v1

> models::CreateSolStakingSolClaimV1Resp create_sol_staking_sol_claim_v1(timestamp, recv_window)
Claim Boost Rewards(TRADE)

Claim Boost APR Airdrop Rewards

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSolStakingSolClaimV1Resp**](CreateSolStakingSolClaimV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sol_staking_sol_redeem_v1

> models::CreateSolStakingSolRedeemV1Resp create_sol_staking_sol_redeem_v1(amount, timestamp, recv_window)
Redeem SOL(TRADE)

Redeem BNSOL get SOL

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSolStakingSolRedeemV1Resp**](CreateSolStakingSolRedeemV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_sol_staking_sol_stake_v1

> models::CreateSolStakingSolStakeV1Resp create_sol_staking_sol_stake_v1(amount, timestamp, recv_window)
Subscribe SOL Staking(TRADE)

Subscribe SOL Staking

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateSolStakingSolStakeV1Resp**](CreateSolStakingSolStakeV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_eth_staking_account_v2

> models::GetEthStakingAccountV2Resp get_eth_staking_account_v2(timestamp, recv_window)
ETH Staking account(USER_DATA)

ETH Staking account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetEthStakingAccountV2Resp**](GetEthStakingAccountV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_eth_staking_eth_history_rate_history_v1

> models::GetEthStakingEthHistoryRateHistoryV1Resp get_eth_staking_eth_history_rate_history_v1(timestamp, start_time, end_time, current, size, recv_window)
Get WBETH Rate History(USER_DATA)

Get WBETH Rate History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetEthStakingEthHistoryRateHistoryV1Resp**](GetEthStakingEthHistoryRateHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_eth_staking_eth_history_redemption_history_v1

> models::GetEthStakingEthHistoryRedemptionHistoryV1Resp get_eth_staking_eth_history_redemption_history_v1(timestamp, start_time, end_time, current, size, recv_window)
Get ETH redemption history(USER_DATA)

Get ETH redemption history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default: 1 |  |[default to 1]
**size** | Option<**i64**> | Default: 10, Max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetEthStakingEthHistoryRedemptionHistoryV1Resp**](GetEthStakingEthHistoryRedemptionHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_eth_staking_eth_history_rewards_history_v1

> models::GetEthStakingEthHistoryRewardsHistoryV1Resp get_eth_staking_eth_history_rewards_history_v1(timestamp, start_time, end_time, current, size, recv_window)
Get BETH rewards distribution history(USER_DATA)

Get BETH rewards distribution history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default: 1 |  |[default to 1]
**size** | Option<**i64**> | Default: 10, Max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetEthStakingEthHistoryRewardsHistoryV1Resp**](GetEthStakingEthHistoryRewardsHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_eth_staking_eth_history_staking_history_v1

> models::GetEthStakingEthHistoryStakingHistoryV1Resp get_eth_staking_eth_history_staking_history_v1(timestamp, start_time, end_time, current, size, recv_window)
Get ETH staking history(USER_DATA)

Get ETH staking history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default: 1 |  |[default to 1]
**size** | Option<**i64**> | Default: 10, Max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetEthStakingEthHistoryStakingHistoryV1Resp**](GetEthStakingEthHistoryStakingHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_eth_staking_eth_history_wbeth_rewards_history_v1

> models::GetEthStakingEthHistoryWbethRewardsHistoryV1Resp get_eth_staking_eth_history_wbeth_rewards_history_v1(timestamp, start_time, end_time, current, size, recv_window)
Get WBETH rewards history(USER_DATA)

Get WBETH rewards history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default: 1 |  |[default to 1]
**size** | Option<**i64**> | Default: 10, Max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetEthStakingEthHistoryWbethRewardsHistoryV1Resp**](GetEthStakingEthHistoryWbethRewardsHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_eth_staking_eth_quota_v1

> models::GetEthStakingEthQuotaV1Resp get_eth_staking_eth_quota_v1(timestamp, recv_window)
Get current ETH staking quota(USER_DATA)

Get current ETH staking quota

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetEthStakingEthQuotaV1Resp**](GetEthStakingEthQuotaV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_eth_staking_wbeth_history_unwrap_history_v1

> models::GetEthStakingWbethHistoryUnwrapHistoryV1Resp get_eth_staking_wbeth_history_unwrap_history_v1(timestamp, start_time, end_time, current, size, recv_window)
Get WBETH unwrap history(USER_DATA)

Get WBETH unwrap history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetEthStakingWbethHistoryUnwrapHistoryV1Resp**](GetEthStakingWbethHistoryUnwrapHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_eth_staking_wbeth_history_wrap_history_v1

> models::GetEthStakingWbethHistoryWrapHistoryV1Resp get_eth_staking_wbeth_history_wrap_history_v1(timestamp, start_time, end_time, current, size, recv_window)
Get WBETH wrap history(USER_DATA)

Get WBETH wrap history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetEthStakingWbethHistoryWrapHistoryV1Resp**](GetEthStakingWbethHistoryWrapHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sol_staking_account_v1

> models::GetSolStakingAccountV1Resp get_sol_staking_account_v1(timestamp, recv_window)
SOL Staking account(USER_DATA)

SOL Staking account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetSolStakingAccountV1Resp**](GetSolStakingAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sol_staking_sol_history_bnsol_rewards_history_v1

> models::GetSolStakingSolHistoryBnsolRewardsHistoryV1Resp get_sol_staking_sol_history_bnsol_rewards_history_v1(timestamp, start_time, end_time, current, size, recv_window)
Get BNSOL rewards history(USER_DATA)

Get BNSOL rewards history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default: 1 |  |[default to 1]
**size** | Option<**i64**> | Default: 10, Max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSolStakingSolHistoryBnsolRewardsHistoryV1Resp**](GetSolStakingSolHistoryBnsolRewardsHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sol_staking_sol_history_boost_rewards_history_v1

> models::GetSolStakingSolHistoryBoostRewardsHistoryV1Resp get_sol_staking_sol_history_boost_rewards_history_v1(r#type, timestamp, start_time, end_time, current, size, recv_window)
Get Boost Rewards History(USER_DATA)

Get Boost rewards history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**r#type** | **String** | &#34;CLAIM&#34;, &#34;DISTRIBUTE&#34;, default &#34;CLAIM&#34; | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default: 1 |  |[default to 1]
**size** | Option<**i64**> | Default: 10, Max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSolStakingSolHistoryBoostRewardsHistoryV1Resp**](GetSolStakingSolHistoryBoostRewardsHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sol_staking_sol_history_rate_history_v1

> models::GetSolStakingSolHistoryRateHistoryV1Resp get_sol_staking_sol_history_rate_history_v1(timestamp, start_time, end_time, current, size, recv_window)
Get BNSOL Rate History(USER_DATA)

Get BNSOL Rate History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10, Max:100 |  |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetSolStakingSolHistoryRateHistoryV1Resp**](GetSolStakingSolHistoryRateHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sol_staking_sol_history_redemption_history_v1

> models::GetSolStakingSolHistoryRedemptionHistoryV1Resp get_sol_staking_sol_history_redemption_history_v1(timestamp, start_time, end_time, current, size, recv_window)
Get SOL redemption history(USER_DATA)

Get SOL redemption history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default: 1 |  |[default to 1]
**size** | Option<**i64**> | Default: 10, Max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSolStakingSolHistoryRedemptionHistoryV1Resp**](GetSolStakingSolHistoryRedemptionHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sol_staking_sol_history_staking_history_v1

> models::GetSolStakingSolHistoryStakingHistoryV1Resp get_sol_staking_sol_history_staking_history_v1(timestamp, start_time, end_time, current, size, recv_window)
Get SOL staking history(USER_DATA)

Get SOL staking history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default: 1 |  |[default to 1]
**size** | Option<**i64**> | Default: 10, Max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetSolStakingSolHistoryStakingHistoryV1Resp**](GetSolStakingSolHistoryStakingHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sol_staking_sol_history_unclaimed_rewards_v1

> Vec<models::GetSolStakingSolHistoryUnclaimedRewardsV1RespItem> get_sol_staking_sol_history_unclaimed_rewards_v1(timestamp, recv_window)
Get Unclaimed Rewards(USER_DATA)

Get Unclaimed rewards

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetSolStakingSolHistoryUnclaimedRewardsV1RespItem>**](GetSolStakingSolHistoryUnclaimedRewardsV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_sol_staking_sol_quota_v1

> models::GetSolStakingSolQuotaV1Resp get_sol_staking_sol_quota_v1(timestamp, recv_window)
Get SOL staking quota details(USER_DATA)

Get SOL staking quota

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetSolStakingSolQuotaV1Resp**](GetSolStakingSolQuotaV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

