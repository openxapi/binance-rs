# \PortfolioMarginProApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_portfolio_asset_collection_v1**](PortfolioMarginProApi.md#create_portfolio_asset_collection_v1) | **POST** /sapi/v1/portfolio/asset-collection | Fund Collection by Asset(USER_DATA)
[**create_portfolio_auto_collection_v1**](PortfolioMarginProApi.md#create_portfolio_auto_collection_v1) | **POST** /sapi/v1/portfolio/auto-collection | Fund Auto-collection(USER_DATA)
[**create_portfolio_bnb_transfer_v1**](PortfolioMarginProApi.md#create_portfolio_bnb_transfer_v1) | **POST** /sapi/v1/portfolio/bnb-transfer | BNB transfer(USER_DATA)
[**create_portfolio_mint_v1**](PortfolioMarginProApi.md#create_portfolio_mint_v1) | **POST** /sapi/v1/portfolio/mint | Mint BFUSD for Portfolio Margin(TRADE)
[**create_portfolio_redeem_v1**](PortfolioMarginProApi.md#create_portfolio_redeem_v1) | **POST** /sapi/v1/portfolio/redeem | Redeem BFUSD for Portfolio Margin(TRADE)
[**create_portfolio_repay_futures_negative_balance_v1**](PortfolioMarginProApi.md#create_portfolio_repay_futures_negative_balance_v1) | **POST** /sapi/v1/portfolio/repay-futures-negative-balance | Repay futures Negative Balance(USER_DATA)
[**create_portfolio_repay_futures_switch_v1**](PortfolioMarginProApi.md#create_portfolio_repay_futures_switch_v1) | **POST** /sapi/v1/portfolio/repay-futures-switch | Change Auto-repay-futures Status(TRADE)
[**create_portfolio_repay_v1**](PortfolioMarginProApi.md#create_portfolio_repay_v1) | **POST** /sapi/v1/portfolio/repay | Portfolio Margin Pro Bankruptcy Loan Repay
[**get_portfolio_account_v1**](PortfolioMarginProApi.md#get_portfolio_account_v1) | **GET** /sapi/v1/portfolio/account | Get Portfolio Margin Pro Account Info(USER_DATA)
[**get_portfolio_account_v2**](PortfolioMarginProApi.md#get_portfolio_account_v2) | **GET** /sapi/v2/portfolio/account | Get Portfolio Margin Pro SPAN Account Info(USER_DATA)
[**get_portfolio_asset_index_price_v1**](PortfolioMarginProApi.md#get_portfolio_asset_index_price_v1) | **GET** /sapi/v1/portfolio/asset-index-price | Query Portfolio Margin Asset Index Price (MARKET_DATA)
[**get_portfolio_balance_v1**](PortfolioMarginProApi.md#get_portfolio_balance_v1) | **GET** /sapi/v1/portfolio/balance | Get Portfolio Margin Pro Account Balance(USER_DATA)
[**get_portfolio_collateral_rate_v1**](PortfolioMarginProApi.md#get_portfolio_collateral_rate_v1) | **GET** /sapi/v1/portfolio/collateralRate | Portfolio Margin Collateral Rate(MARKET_DATA)
[**get_portfolio_collateral_rate_v2**](PortfolioMarginProApi.md#get_portfolio_collateral_rate_v2) | **GET** /sapi/v2/portfolio/collateralRate | Portfolio Margin Pro Tiered Collateral Rate(USER_DATA)
[**get_portfolio_interest_history_v1**](PortfolioMarginProApi.md#get_portfolio_interest_history_v1) | **GET** /sapi/v1/portfolio/interest-history | Query Portfolio Margin Pro Negative Balance Interest History(USER_DATA)
[**get_portfolio_margin_asset_leverage_v1**](PortfolioMarginProApi.md#get_portfolio_margin_asset_leverage_v1) | **GET** /sapi/v1/portfolio/margin-asset-leverage | Get Portfolio Margin Asset Leverage(USER_DATA)
[**get_portfolio_pm_loan_history_v1**](PortfolioMarginProApi.md#get_portfolio_pm_loan_history_v1) | **GET** /sapi/v1/portfolio/pmLoan-history | Query Portfolio Margin Pro Bankruptcy Loan Repay History(USER_DATA)
[**get_portfolio_pm_loan_v1**](PortfolioMarginProApi.md#get_portfolio_pm_loan_v1) | **GET** /sapi/v1/portfolio/pmLoan | Query Portfolio Margin Pro Bankruptcy Loan Amount(USER_DATA)
[**get_portfolio_repay_futures_switch_v1**](PortfolioMarginProApi.md#get_portfolio_repay_futures_switch_v1) | **GET** /sapi/v1/portfolio/repay-futures-switch | Get Auto-repay-futures Status(USER_DATA)



## create_portfolio_asset_collection_v1

> models::CreatePortfolioAssetCollectionV1Resp create_portfolio_asset_collection_v1(asset, timestamp, recv_window)
Fund Collection by Asset(USER_DATA)

Transfers specific asset from Futures Account to Margin account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreatePortfolioAssetCollectionV1Resp**](CreatePortfolioAssetCollectionV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_portfolio_auto_collection_v1

> models::CreatePortfolioAutoCollectionV1Resp create_portfolio_auto_collection_v1(timestamp, recv_window)
Fund Auto-collection(USER_DATA)

Transfers all assets from Futures Account to Margin account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreatePortfolioAutoCollectionV1Resp**](CreatePortfolioAutoCollectionV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_portfolio_bnb_transfer_v1

> models::CreatePortfolioBnbTransferV1Resp create_portfolio_bnb_transfer_v1(amount, timestamp, transfer_side, recv_window)
BNB transfer(USER_DATA)

BNB transfer can be between Margin Account and USDM Account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**transfer_side** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreatePortfolioBnbTransferV1Resp**](CreatePortfolioBnbTransferV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_portfolio_mint_v1

> models::CreatePortfolioMintV1Resp create_portfolio_mint_v1(amount, from_asset, target_asset, timestamp, recv_window)
Mint BFUSD for Portfolio Margin(TRADE)

Mint BFUSD for all types of Portfolio Margin account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**from_asset** | **String** |  | [required] |[default to ]
**target_asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreatePortfolioMintV1Resp**](CreatePortfolioMintV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_portfolio_redeem_v1

> models::CreatePortfolioRedeemV1Resp create_portfolio_redeem_v1(amount, from_asset, target_asset, timestamp, recv_window)
Redeem BFUSD for Portfolio Margin(TRADE)

Redeem BFUSD for all types of Portfolio Margin account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**from_asset** | **String** |  | [required] |[default to ]
**target_asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreatePortfolioRedeemV1Resp**](CreatePortfolioRedeemV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_portfolio_repay_futures_negative_balance_v1

> models::CreatePortfolioRepayFuturesNegativeBalanceV1Resp create_portfolio_repay_futures_negative_balance_v1(timestamp, from, recv_window)
Repay futures Negative Balance(USER_DATA)

Repay futures Negative Balance

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**from** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreatePortfolioRepayFuturesNegativeBalanceV1Resp**](CreatePortfolioRepayFuturesNegativeBalanceV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_portfolio_repay_futures_switch_v1

> models::CreatePortfolioRepayFuturesSwitchV1Resp create_portfolio_repay_futures_switch_v1(auto_repay, timestamp, recv_window)
Change Auto-repay-futures Status(TRADE)

Change Auto-repay-futures Status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**auto_repay** | **String** |  | [required] |[default to true]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreatePortfolioRepayFuturesSwitchV1Resp**](CreatePortfolioRepayFuturesSwitchV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_portfolio_repay_v1

> models::CreatePortfolioRepayV1Resp create_portfolio_repay_v1(timestamp, from, recv_window)
Portfolio Margin Pro Bankruptcy Loan Repay

Repay Portfolio Margin Pro Bankruptcy Loan

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**from** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreatePortfolioRepayV1Resp**](CreatePortfolioRepayV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_account_v1

> models::GetPortfolioAccountV1Resp get_portfolio_account_v1(timestamp, recv_window)
Get Portfolio Margin Pro Account Info(USER_DATA)

Get Portfolio Margin Pro Account Info

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetPortfolioAccountV1Resp**](GetPortfolioAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_account_v2

> get_portfolio_account_v2(timestamp, recv_window)
Get Portfolio Margin Pro SPAN Account Info(USER_DATA)

Get Portfolio Margin Pro SPAN Account Info (For Portfolio Margin Pro SPAN users only)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

 (empty response body)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_asset_index_price_v1

> Vec<models::GetPortfolioAssetIndexPriceV1RespItem> get_portfolio_asset_index_price_v1(asset)
Query Portfolio Margin Asset Index Price (MARKET_DATA)

Query Portfolio Margin Asset Index Price

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::GetPortfolioAssetIndexPriceV1RespItem>**](GetPortfolioAssetIndexPriceV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_balance_v1

> Vec<models::GetPortfolioBalanceV1RespItem> get_portfolio_balance_v1(timestamp, asset, recv_window)
Get Portfolio Margin Pro Account Balance(USER_DATA)

Query Portfolio Margin Pro account balance

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetPortfolioBalanceV1RespItem>**](GetPortfolioBalanceV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_collateral_rate_v1

> Vec<models::GetPortfolioCollateralRateV1RespItem> get_portfolio_collateral_rate_v1()
Portfolio Margin Collateral Rate(MARKET_DATA)

Portfolio Margin Collateral Rate

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::GetPortfolioCollateralRateV1RespItem>**](GetPortfolioCollateralRateV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_collateral_rate_v2

> Vec<models::GetPortfolioCollateralRateV2RespItem> get_portfolio_collateral_rate_v2(timestamp, recv_window)
Portfolio Margin Pro Tiered Collateral Rate(USER_DATA)

Portfolio Margin PRO Tiered Collateral Rate

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetPortfolioCollateralRateV2RespItem>**](GetPortfolioCollateralRateV2RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_interest_history_v1

> Vec<models::GetPortfolioInterestHistoryV1RespItem> get_portfolio_interest_history_v1(timestamp, asset, start_time, end_time, size, recv_window)
Query Portfolio Margin Pro Negative Balance Interest History(USER_DATA)

Query interest history of negative balance for portfolio margin.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetPortfolioInterestHistoryV1RespItem>**](GetPortfolioInterestHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_margin_asset_leverage_v1

> Vec<models::GetPortfolioMarginAssetLeverageV1RespItem> get_portfolio_margin_asset_leverage_v1()
Get Portfolio Margin Asset Leverage(USER_DATA)

Get Portfolio Margin Asset Leverage

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::GetPortfolioMarginAssetLeverageV1RespItem>**](GetPortfolioMarginAssetLeverageV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_pm_loan_history_v1

> models::GetPortfolioPmLoanHistoryV1Resp get_portfolio_pm_loan_history_v1(timestamp, start_time, end_time, current, size, recv_window)
Query Portfolio Margin Pro Bankruptcy Loan Repay History(USER_DATA)

Query repay history of pmloan for portfolio margin pro.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetPortfolioPmLoanHistoryV1Resp**](GetPortfolioPmLoanHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_pm_loan_v1

> models::GetPortfolioPmLoanV1Resp get_portfolio_pm_loan_v1(timestamp, recv_window)
Query Portfolio Margin Pro Bankruptcy Loan Amount(USER_DATA)

Query Portfolio Margin Pro Bankruptcy Loan Amount

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetPortfolioPmLoanV1Resp**](GetPortfolioPmLoanV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_repay_futures_switch_v1

> models::GetPortfolioRepayFuturesSwitchV1Resp get_portfolio_repay_futures_switch_v1(timestamp, recv_window)
Get Auto-repay-futures Status(USER_DATA)

Query Auto-repay-futures Status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetPortfolioRepayFuturesSwitchV1Resp**](GetPortfolioRepayFuturesSwitchV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

