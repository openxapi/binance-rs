# \NftApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**get_nft_history_deposit_v1**](NftApi.md#get_nft_history_deposit_v1) | **GET** /sapi/v1/nft/history/deposit | Get NFT Deposit History(USER_DATA)
[**get_nft_history_transactions_v1**](NftApi.md#get_nft_history_transactions_v1) | **GET** /sapi/v1/nft/history/transactions | Get NFT Transaction History(USER_DATA)
[**get_nft_history_withdraw_v1**](NftApi.md#get_nft_history_withdraw_v1) | **GET** /sapi/v1/nft/history/withdraw | Get NFT Withdraw History(USER_DATA)
[**get_nft_user_get_asset_v1**](NftApi.md#get_nft_user_get_asset_v1) | **GET** /sapi/v1/nft/user/getAsset | Get NFT Asset(USER_DATA)



## get_nft_history_deposit_v1

> models::GetNftHistoryDepositV1Resp get_nft_history_deposit_v1(timestamp, start_time, end_time, limit, page, recv_window)
Get NFT Deposit History(USER_DATA)

et NFT Deposit History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 50, Max 50 |  |[default to 50]
**page** | Option<**i32**> | Default 1 |  |[default to 1]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetNftHistoryDepositV1Resp**](GetNftHistoryDepositV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_nft_history_transactions_v1

> models::GetNftHistoryTransactionsV1Resp get_nft_history_transactions_v1(order_type, timestamp, start_time, end_time, limit, page, recv_window)
Get NFT Transaction History(USER_DATA)

Get NFT Transaction History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**order_type** | **i32** | 0: purchase order, 1: sell order, 2: royalty income, 3: primary market order, 4: mint fee | [required] |
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 50, Max 50 |  |[default to 50]
**page** | Option<**i32**> | Default 1 |  |[default to 1]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetNftHistoryTransactionsV1Resp**](GetNftHistoryTransactionsV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_nft_history_withdraw_v1

> models::GetNftHistoryWithdrawV1Resp get_nft_history_withdraw_v1(timestamp, start_time, end_time, limit, page, recv_window)
Get NFT Withdraw History(USER_DATA)

Get NFT Withdraw History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 50, Max 50 |  |[default to 50]
**page** | Option<**i32**> | Default 1 |  |[default to 1]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetNftHistoryWithdrawV1Resp**](GetNftHistoryWithdrawV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_nft_user_get_asset_v1

> models::GetNftUserGetAssetV1Resp get_nft_user_get_asset_v1(timestamp, limit, page, recv_window)
Get NFT Asset(USER_DATA)

Get NFT Asset

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**limit** | Option<**i32**> | Default 50, Max 50 |  |[default to 50]
**page** | Option<**i32**> | Default 1 |  |[default to 1]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetNftUserGetAssetV1Resp**](GetNftUserGetAssetV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

