# \AssetApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**wallet_create_asset_dust_btc_v1**](AssetApi.md#wallet_create_asset_dust_btc_v1) | **POST** /sapi/v1/asset/dust-btc | Get Assets That Can Be Converted Into BNB (USER_DATA)
[**wallet_create_asset_dust_v1**](AssetApi.md#wallet_create_asset_dust_v1) | **POST** /sapi/v1/asset/dust | Dust Transfer (USER_DATA)
[**wallet_create_asset_get_funding_asset_v1**](AssetApi.md#wallet_create_asset_get_funding_asset_v1) | **POST** /sapi/v1/asset/get-funding-asset | Funding Wallet (USER_DATA)
[**wallet_create_asset_get_user_asset_v3**](AssetApi.md#wallet_create_asset_get_user_asset_v3) | **POST** /sapi/v3/asset/getUserAsset | User Asset (USER_DATA)
[**wallet_create_asset_transfer_v1**](AssetApi.md#wallet_create_asset_transfer_v1) | **POST** /sapi/v1/asset/transfer | User Universal Transfer (USER_DATA)
[**wallet_create_bnb_burn_v1**](AssetApi.md#wallet_create_bnb_burn_v1) | **POST** /sapi/v1/bnbBurn | Toggle BNB Burn On Spot Trade And Margin Interest (USER_DATA)
[**wallet_get_asset_asset_detail_v1**](AssetApi.md#wallet_get_asset_asset_detail_v1) | **GET** /sapi/v1/asset/assetDetail | Asset Detail (USER_DATA)
[**wallet_get_asset_asset_dividend_v1**](AssetApi.md#wallet_get_asset_asset_dividend_v1) | **GET** /sapi/v1/asset/assetDividend | Asset Dividend Record (USER_DATA)
[**wallet_get_asset_custody_transfer_history_v1**](AssetApi.md#wallet_get_asset_custody_transfer_history_v1) | **GET** /sapi/v1/asset/custody/transfer-history | Query User Delegation History(For Master Account)(USER_DATA)
[**wallet_get_asset_dribblet_v1**](AssetApi.md#wallet_get_asset_dribblet_v1) | **GET** /sapi/v1/asset/dribblet | DustLog(USER_DATA)
[**wallet_get_asset_ledger_transfer_cloud_mining_query_by_page_v1**](AssetApi.md#wallet_get_asset_ledger_transfer_cloud_mining_query_by_page_v1) | **GET** /sapi/v1/asset/ledger-transfer/cloud-mining/queryByPage | Get Cloud-Mining payment and refund history (USER_DATA)
[**wallet_get_asset_trade_fee_v1**](AssetApi.md#wallet_get_asset_trade_fee_v1) | **GET** /sapi/v1/asset/tradeFee | Trade Fee (USER_DATA)
[**wallet_get_asset_transfer_v1**](AssetApi.md#wallet_get_asset_transfer_v1) | **GET** /sapi/v1/asset/transfer | Query User Universal Transfer History(USER_DATA)
[**wallet_get_asset_wallet_balance_v1**](AssetApi.md#wallet_get_asset_wallet_balance_v1) | **GET** /sapi/v1/asset/wallet/balance | Query User Wallet Balance (USER_DATA)
[**wallet_get_spot_delist_schedule_v1**](AssetApi.md#wallet_get_spot_delist_schedule_v1) | **GET** /sapi/v1/spot/delist-schedule | Get Spot Delist Schedule (MARKET_DATA)
[**wallet_get_spot_open_symbol_list_v1**](AssetApi.md#wallet_get_spot_open_symbol_list_v1) | **GET** /sapi/v1/spot/open-symbol-list | Get Open Symbol List (MARKET_DATA)



## wallet_create_asset_dust_btc_v1

> models::WalletCreateAssetDustBtcV1Resp wallet_create_asset_dust_btc_v1(timestamp, account_type, recv_window)
Get Assets That Can Be Converted Into BNB (USER_DATA)

Get Assets That Can Be Converted Into BNB

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**account_type** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::WalletCreateAssetDustBtcV1Resp**](WalletCreateAssetDustBtcV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_create_asset_dust_v1

> models::WalletCreateAssetDustV1Resp wallet_create_asset_dust_v1(asset, timestamp, account_type, recv_window)
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

[**models::WalletCreateAssetDustV1Resp**](WalletCreateAssetDustV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_create_asset_get_funding_asset_v1

> Vec<models::WalletCreateAssetGetFundingAssetV1RespItem> wallet_create_asset_get_funding_asset_v1(timestamp, asset, need_btc_valuation, recv_window)
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

[**Vec<models::WalletCreateAssetGetFundingAssetV1RespItem>**](WalletCreateAssetGetFundingAssetV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_create_asset_get_user_asset_v3

> Vec<models::WalletCreateAssetGetUserAssetV3RespItem> wallet_create_asset_get_user_asset_v3(timestamp, asset, need_btc_valuation, recv_window)
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

[**Vec<models::WalletCreateAssetGetUserAssetV3RespItem>**](WalletCreateAssetGetUserAssetV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_create_asset_transfer_v1

> models::WalletCreateAssetTransferV1Resp wallet_create_asset_transfer_v1(amount, asset, timestamp, r#type, from_symbol, recv_window, to_symbol)
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

[**models::WalletCreateAssetTransferV1Resp**](WalletCreateAssetTransferV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_create_bnb_burn_v1

> models::WalletCreateBnbBurnV1Resp wallet_create_bnb_burn_v1(timestamp, interest_bnb_burn, recv_window, spot_bnb_burn)
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

[**models::WalletCreateBnbBurnV1Resp**](WalletCreateBnbBurnV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_asset_asset_detail_v1

> std::collections::HashMap<String, models::WalletGetAssetAssetDetailV1RespValue> wallet_get_asset_asset_detail_v1(timestamp, recv_window)
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


## wallet_get_asset_asset_dividend_v1

> models::WalletGetAssetAssetDividendV1Resp wallet_get_asset_asset_dividend_v1(timestamp, asset, start_time, end_time, limit, recv_window)
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

[**models::WalletGetAssetAssetDividendV1Resp**](WalletGetAssetAssetDividendV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_asset_custody_transfer_history_v1

> models::WalletGetAssetCustodyTransferHistoryV1Resp wallet_get_asset_custody_transfer_history_v1(email, start_time, end_time, timestamp, r#type, asset, current, size, recv_window)
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

[**models::WalletGetAssetCustodyTransferHistoryV1Resp**](WalletGetAssetCustodyTransferHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_asset_dribblet_v1

> models::WalletGetAssetDribbletV1Resp wallet_get_asset_dribblet_v1(timestamp, start_time, end_time, recv_window)
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

[**models::WalletGetAssetDribbletV1Resp**](WalletGetAssetDribbletV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_asset_ledger_transfer_cloud_mining_query_by_page_v1

> models::WalletGetAssetLedgerTransferCloudMiningQueryByPageV1Resp wallet_get_asset_ledger_transfer_cloud_mining_query_by_page_v1(start_time, end_time, tran_id, client_tran_id, asset, current, size)
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

[**models::WalletGetAssetLedgerTransferCloudMiningQueryByPageV1Resp**](WalletGetAssetLedgerTransferCloudMiningQueryByPageV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_asset_trade_fee_v1

> Vec<models::WalletGetAssetTradeFeeV1RespItem> wallet_get_asset_trade_fee_v1(timestamp, symbol, recv_window)
Trade Fee (USER_DATA)

Fetch trade fee

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::WalletGetAssetTradeFeeV1RespItem>**](WalletGetAssetTradeFeeV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_asset_transfer_v1

> models::WalletGetAssetTransferV1Resp wallet_get_asset_transfer_v1(r#type, timestamp, start_time, end_time, current, size, from_symbol, to_symbol, recv_window)
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

[**models::WalletGetAssetTransferV1Resp**](WalletGetAssetTransferV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_asset_wallet_balance_v1

> Vec<models::WalletGetAssetWalletBalanceV1RespItem> wallet_get_asset_wallet_balance_v1(timestamp, quote_asset, recv_window)
Query User Wallet Balance (USER_DATA)

Query User Wallet Balance

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**quote_asset** | Option<**String**> | `USDT`, `ETH`, `USDC`, `BNB`, etc. default `BTC` |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::WalletGetAssetWalletBalanceV1RespItem>**](WalletGetAssetWalletBalanceV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_spot_delist_schedule_v1

> Vec<models::WalletGetSpotDelistScheduleV1RespItem> wallet_get_spot_delist_schedule_v1(timestamp, recv_window)
Get Spot Delist Schedule (MARKET_DATA)

Get symbols delist schedule for spot

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::WalletGetSpotDelistScheduleV1RespItem>**](WalletGetSpotDelistScheduleV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## wallet_get_spot_open_symbol_list_v1

> Vec<models::WalletGetSpotOpenSymbolListV1RespItem> wallet_get_spot_open_symbol_list_v1()
Get Open Symbol List (MARKET_DATA)

Get the list of symbols that are scheduled to be opened for trading in the market.

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::WalletGetSpotOpenSymbolListV1RespItem>**](WalletGetSpotOpenSymbolListV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

