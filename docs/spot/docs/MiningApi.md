# \MiningApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_mining_hash_transfer_config_cancel_v1**](MiningApi.md#create_mining_hash_transfer_config_cancel_v1) | **POST** /sapi/v1/mining/hash-transfer/config/cancel | Cancel hashrate resale configuration(USER_DATA)
[**create_mining_hash_transfer_config_v1**](MiningApi.md#create_mining_hash_transfer_config_v1) | **POST** /sapi/v1/mining/hash-transfer/config | Hashrate Resale Request(USER_DATA)
[**get_mining_hash_transfer_config_details_list_v1**](MiningApi.md#get_mining_hash_transfer_config_details_list_v1) | **GET** /sapi/v1/mining/hash-transfer/config/details/list | Hashrate Resale List (USER_DATA)
[**get_mining_hash_transfer_profit_details_v1**](MiningApi.md#get_mining_hash_transfer_profit_details_v1) | **GET** /sapi/v1/mining/hash-transfer/profit/details | Hashrate Resale Detail(USER_DATA)
[**get_mining_payment_list_v1**](MiningApi.md#get_mining_payment_list_v1) | **GET** /sapi/v1/mining/payment/list | Earnings List(USER_DATA)
[**get_mining_payment_other_v1**](MiningApi.md#get_mining_payment_other_v1) | **GET** /sapi/v1/mining/payment/other | Extra Bonus List(USER_DATA)
[**get_mining_payment_uid_v1**](MiningApi.md#get_mining_payment_uid_v1) | **GET** /sapi/v1/mining/payment/uid | Mining Account Earning(USER_DATA)
[**get_mining_pub_algo_list_v1**](MiningApi.md#get_mining_pub_algo_list_v1) | **GET** /sapi/v1/mining/pub/algoList | Acquiring Algorithm(MARKET_DATA)
[**get_mining_pub_coin_list_v1**](MiningApi.md#get_mining_pub_coin_list_v1) | **GET** /sapi/v1/mining/pub/coinList | Acquiring CoinName(MARKET_DATA)
[**get_mining_statistics_user_list_v1**](MiningApi.md#get_mining_statistics_user_list_v1) | **GET** /sapi/v1/mining/statistics/user/list | Account List(USER_DATA)
[**get_mining_statistics_user_status_v1**](MiningApi.md#get_mining_statistics_user_status_v1) | **GET** /sapi/v1/mining/statistics/user/status | Statistic List(USER_DATA)
[**get_mining_worker_detail_v1**](MiningApi.md#get_mining_worker_detail_v1) | **GET** /sapi/v1/mining/worker/detail | Request for Detail Miner List(USER_DATA)
[**get_mining_worker_list_v1**](MiningApi.md#get_mining_worker_list_v1) | **GET** /sapi/v1/mining/worker/list | Request for Miner List(USER_DATA)



## create_mining_hash_transfer_config_cancel_v1

> models::CreateMiningHashTransferConfigCancelV1Resp create_mining_hash_transfer_config_cancel_v1(config_id, timestamp, user_name, recv_window)
Cancel hashrate resale configuration(USER_DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**config_id** | **i32** |  | [required] |
**timestamp** | **i64** |  | [required] |
**user_name** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateMiningHashTransferConfigCancelV1Resp**](CreateMiningHashTransferConfigCancelV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_mining_hash_transfer_config_v1

> models::CreateMiningHashTransferConfigV1Resp create_mining_hash_transfer_config_v1(algo, end_date, hash_rate, start_date, timestamp, to_pool_user, user_name, recv_window)
Hashrate Resale Request(USER_DATA)

Hashrate Resale Request

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo** | **String** |  | [required] |[default to ]
**end_date** | **i64** |  | [required] |
**hash_rate** | **i64** |  | [required] |
**start_date** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**to_pool_user** | **String** |  | [required] |[default to ]
**user_name** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateMiningHashTransferConfigV1Resp**](CreateMiningHashTransferConfigV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mining_hash_transfer_config_details_list_v1

> models::GetMiningHashTransferConfigDetailsListV1Resp get_mining_hash_transfer_config_details_list_v1(timestamp, page_index, page_size, recv_window)
Hashrate Resale List (USER_DATA)

Hashrate Resale List

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**page_index** | Option<**i32**> | Page number, empty default first page, starting from 1 |  |
**page_size** | Option<**i32**> | Number of pages, minimum 10, maximum 200 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMiningHashTransferConfigDetailsListV1Resp**](GetMiningHashTransferConfigDetailsListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mining_hash_transfer_profit_details_v1

> models::GetMiningHashTransferProfitDetailsV1Resp get_mining_hash_transfer_profit_details_v1(config_id, user_name, timestamp, page_index, page_size, recv_window)
Hashrate Resale Detail(USER_DATA)

Hashrate Resale Detail(USER_DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**config_id** | **i32** | Mining ID | [required] |
**user_name** | **String** | Mining Account | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**page_index** | Option<**i32**> | Page number, empty default first page, starting from 1 |  |
**page_size** | Option<**i32**> | Number of pages, minimum 10, maximum 200 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMiningHashTransferProfitDetailsV1Resp**](GetMiningHashTransferProfitDetailsV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mining_payment_list_v1

> models::GetMiningPaymentListV1Resp get_mining_payment_list_v1(algo, user_name, timestamp, coin, start_date, end_date, page_index, page_size, recv_window)
Earnings List(USER_DATA)

Query Earnings List

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo** | **String** | Transfer algorithm(sha256) | [required] |[default to ]
**user_name** | **String** | Mining account | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**coin** | Option<**String**> | Coin name |  |[default to ]
**start_date** | Option<**i64**> | Search date, millisecond timestamp, while empty query all |  |
**end_date** | Option<**i64**> | Search date, millisecond timestamp, while empty query all |  |
**page_index** | Option<**i32**> | Page number, empty default first page, starting from 1 |  |
**page_size** | Option<**i32**> | Number of pages, minimum 10, maximum 200 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMiningPaymentListV1Resp**](GetMiningPaymentListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mining_payment_other_v1

> models::GetMiningPaymentOtherV1Resp get_mining_payment_other_v1(algo, user_name, timestamp, coin, start_date, end_date, page_index, page_size, recv_window)
Extra Bonus List(USER_DATA)

Extra Bonus List

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo** | **String** | Transfer algorithm(sha256) | [required] |[default to ]
**user_name** | **String** | Mining Account | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**coin** | Option<**String**> | Coin Name |  |[default to ]
**start_date** | Option<**i64**> | Search date, millisecond timestamp, while empty query all |  |
**end_date** | Option<**i64**> | Search date, millisecond timestamp, while empty query all |  |
**page_index** | Option<**i32**> | Page number, empty default first page, starting from 1 |  |
**page_size** | Option<**i32**> | Number of pages, minimum 10, maximum 200 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMiningPaymentOtherV1Resp**](GetMiningPaymentOtherV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mining_payment_uid_v1

> models::GetMiningPaymentUidV1Resp get_mining_payment_uid_v1(algo, timestamp, start_date, end_date, page_index, page_size, recv_window)
Mining Account Earning(USER_DATA)

Mining Account Earning

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo** | **String** | Algorithm(sha256) | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**start_date** | Option<**i64**> | Millisecond timestamp |  |
**end_date** | Option<**i64**> | Millisecond timestamp |  |
**page_index** | Option<**i32**> | Default 1 |  |[default to 1]
**page_size** | Option<**i32**> | Min 10,Max 200 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMiningPaymentUidV1Resp**](GetMiningPaymentUidV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mining_pub_algo_list_v1

> models::GetMiningPubAlgoListV1Resp get_mining_pub_algo_list_v1()
Acquiring Algorithm(MARKET_DATA)

Acquiring Algorithm

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::GetMiningPubAlgoListV1Resp**](GetMiningPubAlgoListV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mining_pub_coin_list_v1

> models::GetMiningPubCoinListV1Resp get_mining_pub_coin_list_v1()
Acquiring CoinName(MARKET_DATA)

Acquiring CoinName

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::GetMiningPubCoinListV1Resp**](GetMiningPubCoinListV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mining_statistics_user_list_v1

> models::GetMiningStatisticsUserListV1Resp get_mining_statistics_user_list_v1(algo, user_name, timestamp, recv_window)
Account List(USER_DATA)

Query Account List

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo** | **String** | Algorithm(sha256) | [required] |[default to ]
**user_name** | **String** | Mining account | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMiningStatisticsUserListV1Resp**](GetMiningStatisticsUserListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mining_statistics_user_status_v1

> models::GetMiningStatisticsUserStatusV1Resp get_mining_statistics_user_status_v1(algo, user_name, timestamp, recv_window)
Statistic List(USER_DATA)

Statistic List

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo** | **String** | Algorithm(sha256) | [required] |[default to ]
**user_name** | **String** | Mining account | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMiningStatisticsUserStatusV1Resp**](GetMiningStatisticsUserStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mining_worker_detail_v1

> models::GetMiningWorkerDetailV1Resp get_mining_worker_detail_v1(algo, user_name, worker_name, timestamp, recv_window)
Request for Detail Miner List(USER_DATA)

Request for Detail Miner List

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo** | **String** | Algorithm(sha256) | [required] |[default to ]
**user_name** | **String** | Mining account | [required] |[default to ]
**worker_name** | **String** | Miner’s name(required) | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMiningWorkerDetailV1Resp**](GetMiningWorkerDetailV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_mining_worker_list_v1

> models::GetMiningWorkerListV1Resp get_mining_worker_list_v1(algo, user_name, timestamp, page_index, sort, sort_column, worker_status, recv_window)
Request for Miner List(USER_DATA)

Request for Miner List

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**algo** | **String** | Algorithm(sha256) | [required] |[default to ]
**user_name** | **String** | Mining account | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**page_index** | Option<**i32**> | Page number，default is first page，start form 1 |  |
**sort** | Option<**i32**> | sort sequence(default=0)0 positive sequence，1 negative sequence |  |
**sort_column** | Option<**i32**> | Sort by( default 1): <br/><br/>1: miner name, <br/><br/>2: real-time computing power, <br/><br/>3: daily average computing power, <br/><br/>4: real-time rejection rate, <br/><br/>5: last submission time |  |[default to 1]
**worker_status** | Option<**i32**> | miners status(default=0),0 all，1 valid，2 invalid，3 failure |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMiningWorkerListV1Resp**](GetMiningWorkerListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

