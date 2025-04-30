# \AccountApi

All URIs are relative to *https://papi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**pmargin_create_asset_collection_v1**](AccountApi.md#pmargin_create_asset_collection_v1) | **POST** /papi/v1/asset-collection | Fund Collection by Asset(TRADE)
[**pmargin_create_auto_collection_v1**](AccountApi.md#pmargin_create_auto_collection_v1) | **POST** /papi/v1/auto-collection | Fund Auto-collection(TRADE)
[**pmargin_create_bnb_transfer_v1**](AccountApi.md#pmargin_create_bnb_transfer_v1) | **POST** /papi/v1/bnb-transfer | BNB transfer (TRADE)
[**pmargin_create_cm_leverage_v1**](AccountApi.md#pmargin_create_cm_leverage_v1) | **POST** /papi/v1/cm/leverage | Change CM Initial Leverage (TRADE)
[**pmargin_create_cm_position_side_dual_v1**](AccountApi.md#pmargin_create_cm_position_side_dual_v1) | **POST** /papi/v1/cm/positionSide/dual | Change CM Position Mode(TRADE)
[**pmargin_create_repay_futures_negative_balance_v1**](AccountApi.md#pmargin_create_repay_futures_negative_balance_v1) | **POST** /papi/v1/repay-futures-negative-balance | Repay futures Negative Balance(USER_DATA)
[**pmargin_create_repay_futures_switch_v1**](AccountApi.md#pmargin_create_repay_futures_switch_v1) | **POST** /papi/v1/repay-futures-switch | Change Auto-repay-futures Status(TRADE)
[**pmargin_create_um_leverage_v1**](AccountApi.md#pmargin_create_um_leverage_v1) | **POST** /papi/v1/um/leverage | Change UM Initial Leverage(TRADE)
[**pmargin_create_um_position_side_dual_v1**](AccountApi.md#pmargin_create_um_position_side_dual_v1) | **POST** /papi/v1/um/positionSide/dual | Change UM Position Mode(TRADE)
[**pmargin_get_account_v1**](AccountApi.md#pmargin_get_account_v1) | **GET** /papi/v1/account | Account Information(USER_DATA)
[**pmargin_get_balance_v1**](AccountApi.md#pmargin_get_balance_v1) | **GET** /papi/v1/balance | Account Balance(USER_DATA)
[**pmargin_get_cm_account_v1**](AccountApi.md#pmargin_get_cm_account_v1) | **GET** /papi/v1/cm/account | Get CM Account Detail(USER_DATA)
[**pmargin_get_cm_commission_rate_v1**](AccountApi.md#pmargin_get_cm_commission_rate_v1) | **GET** /papi/v1/cm/commissionRate | Get User Commission Rate for CM(USER_DATA)
[**pmargin_get_cm_income_v1**](AccountApi.md#pmargin_get_cm_income_v1) | **GET** /papi/v1/cm/income | Get CM Income History(USER_DATA)
[**pmargin_get_cm_leverage_bracket_v1**](AccountApi.md#pmargin_get_cm_leverage_bracket_v1) | **GET** /papi/v1/cm/leverageBracket | CM Notional and Leverage Brackets(USER_DATA)
[**pmargin_get_cm_position_risk_v1**](AccountApi.md#pmargin_get_cm_position_risk_v1) | **GET** /papi/v1/cm/positionRisk | Query CM Position Information(USER_DATA)
[**pmargin_get_cm_position_side_dual_v1**](AccountApi.md#pmargin_get_cm_position_side_dual_v1) | **GET** /papi/v1/cm/positionSide/dual | Get CM Current Position Mode(USER_DATA)
[**pmargin_get_margin_margin_interest_history_v1**](AccountApi.md#pmargin_get_margin_margin_interest_history_v1) | **GET** /papi/v1/margin/marginInterestHistory | Get Margin Borrow/Loan Interest History(USER_DATA)
[**pmargin_get_margin_margin_loan_v1**](AccountApi.md#pmargin_get_margin_margin_loan_v1) | **GET** /papi/v1/margin/marginLoan | Query Margin Loan Record(USER_DATA)
[**pmargin_get_margin_max_borrowable_v1**](AccountApi.md#pmargin_get_margin_max_borrowable_v1) | **GET** /papi/v1/margin/maxBorrowable | Margin Max Borrow(USER_DATA)
[**pmargin_get_margin_max_withdraw_v1**](AccountApi.md#pmargin_get_margin_max_withdraw_v1) | **GET** /papi/v1/margin/maxWithdraw | Query Margin Max Withdraw(USER_DATA)
[**pmargin_get_margin_repay_loan_v1**](AccountApi.md#pmargin_get_margin_repay_loan_v1) | **GET** /papi/v1/margin/repayLoan | Query Margin repay Record(USER_DATA)
[**pmargin_get_portfolio_interest_history_v1**](AccountApi.md#pmargin_get_portfolio_interest_history_v1) | **GET** /papi/v1/portfolio/interest-history | Query Portfolio Margin Negative Balance Interest History(USER_DATA)
[**pmargin_get_portfolio_negative_balance_exchange_record_v1**](AccountApi.md#pmargin_get_portfolio_negative_balance_exchange_record_v1) | **GET** /papi/v1/portfolio/negative-balance-exchange-record | Query User Negative Balance Auto Exchange Record (USER_DATA)
[**pmargin_get_rate_limit_order_v1**](AccountApi.md#pmargin_get_rate_limit_order_v1) | **GET** /papi/v1/rateLimit/order | Query User Rate Limit (USER_DATA)
[**pmargin_get_repay_futures_switch_v1**](AccountApi.md#pmargin_get_repay_futures_switch_v1) | **GET** /papi/v1/repay-futures-switch | Get Auto-repay-futures Status(USER_DATA)
[**pmargin_get_um_account_config_v1**](AccountApi.md#pmargin_get_um_account_config_v1) | **GET** /papi/v1/um/accountConfig | UM Futures Account Configuration(USER_DATA)
[**pmargin_get_um_account_v1**](AccountApi.md#pmargin_get_um_account_v1) | **GET** /papi/v1/um/account | Get UM Account Detail(USER_DATA)
[**pmargin_get_um_account_v2**](AccountApi.md#pmargin_get_um_account_v2) | **GET** /papi/v2/um/account | Get UM Account Detail V2(USER_DATA)
[**pmargin_get_um_api_trading_status_v1**](AccountApi.md#pmargin_get_um_api_trading_status_v1) | **GET** /papi/v1/um/apiTradingStatus | Portfolio Margin UM Trading Quantitative Rules Indicators(USER_DATA)
[**pmargin_get_um_commission_rate_v1**](AccountApi.md#pmargin_get_um_commission_rate_v1) | **GET** /papi/v1/um/commissionRate | Get User Commission Rate for UM(USER_DATA)
[**pmargin_get_um_income_asyn_id_v1**](AccountApi.md#pmargin_get_um_income_asyn_id_v1) | **GET** /papi/v1/um/income/asyn/id | Get UM Futures Transaction Download Link by Id(USER_DATA)
[**pmargin_get_um_income_asyn_v1**](AccountApi.md#pmargin_get_um_income_asyn_v1) | **GET** /papi/v1/um/income/asyn | Get Download Id For UM Futures Transaction History (USER_DATA)
[**pmargin_get_um_income_v1**](AccountApi.md#pmargin_get_um_income_v1) | **GET** /papi/v1/um/income | Get UM Income History(USER_DATA)
[**pmargin_get_um_leverage_bracket_v1**](AccountApi.md#pmargin_get_um_leverage_bracket_v1) | **GET** /papi/v1/um/leverageBracket | UM Notional and Leverage Brackets (USER_DATA)
[**pmargin_get_um_order_asyn_id_v1**](AccountApi.md#pmargin_get_um_order_asyn_id_v1) | **GET** /papi/v1/um/order/asyn/id | Get UM Futures Order Download Link by Id(USER_DATA)
[**pmargin_get_um_order_asyn_v1**](AccountApi.md#pmargin_get_um_order_asyn_v1) | **GET** /papi/v1/um/order/asyn | Get Download Id For UM Futures Order History (USER_DATA)
[**pmargin_get_um_position_risk_v1**](AccountApi.md#pmargin_get_um_position_risk_v1) | **GET** /papi/v1/um/positionRisk | Query UM Position Information(USER_DATA)
[**pmargin_get_um_position_side_dual_v1**](AccountApi.md#pmargin_get_um_position_side_dual_v1) | **GET** /papi/v1/um/positionSide/dual | Get UM Current Position Mode(USER_DATA)
[**pmargin_get_um_symbol_config_v1**](AccountApi.md#pmargin_get_um_symbol_config_v1) | **GET** /papi/v1/um/symbolConfig | UM Futures Symbol Configuration(USER_DATA)
[**pmargin_get_um_trade_asyn_id_v1**](AccountApi.md#pmargin_get_um_trade_asyn_id_v1) | **GET** /papi/v1/um/trade/asyn/id | Get UM Futures Trade Download Link by Id(USER_DATA)
[**pmargin_get_um_trade_asyn_v1**](AccountApi.md#pmargin_get_um_trade_asyn_v1) | **GET** /papi/v1/um/trade/asyn | Get Download Id For UM Futures Trade History (USER_DATA)



## pmargin_create_asset_collection_v1

> models::PmarginCreateAssetCollectionV1Resp pmargin_create_asset_collection_v1(asset, timestamp, recv_window)
Fund Collection by Asset(TRADE)

Transfers specific asset from Futures Account to Margin account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginCreateAssetCollectionV1Resp**](PmarginCreateAssetCollectionV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_auto_collection_v1

> models::PmarginCreateAutoCollectionV1Resp pmargin_create_auto_collection_v1(timestamp, recv_window)
Fund Auto-collection(TRADE)

Fund collection for Portfolio Margin

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginCreateAutoCollectionV1Resp**](PmarginCreateAutoCollectionV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_bnb_transfer_v1

> models::PmarginCreateBnbTransferV1Resp pmargin_create_bnb_transfer_v1(amount, timestamp, transfer_side, recv_window)
BNB transfer (TRADE)

Transfer BNB in and out of UM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**transfer_side** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginCreateBnbTransferV1Resp**](PmarginCreateBnbTransferV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_cm_leverage_v1

> models::PmarginCreateCmLeverageV1Resp pmargin_create_cm_leverage_v1(leverage, symbol, timestamp, recv_window)
Change CM Initial Leverage (TRADE)

Change user's initial leverage of specific symbol in CM.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**leverage** | **i32** |  | [required] |
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginCreateCmLeverageV1Resp**](PmarginCreateCmLeverageV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_cm_position_side_dual_v1

> models::PmarginCreateCmPositionSideDualV1Resp pmargin_create_cm_position_side_dual_v1(dual_side_position, timestamp, recv_window)
Change CM Position Mode(TRADE)

Change user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol in CM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**dual_side_position** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginCreateCmPositionSideDualV1Resp**](PmarginCreateCmPositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_repay_futures_negative_balance_v1

> models::PmarginCreateRepayFuturesNegativeBalanceV1Resp pmargin_create_repay_futures_negative_balance_v1(timestamp, recv_window)
Repay futures Negative Balance(USER_DATA)

Repay futures Negative Balance

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginCreateRepayFuturesNegativeBalanceV1Resp**](PmarginCreateRepayFuturesNegativeBalanceV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_repay_futures_switch_v1

> models::PmarginCreateRepayFuturesSwitchV1Resp pmargin_create_repay_futures_switch_v1(auto_repay, timestamp, recv_window)
Change Auto-repay-futures Status(TRADE)

Change Auto-repay-futures Status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**auto_repay** | **String** |  | [required] |[default to true]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginCreateRepayFuturesSwitchV1Resp**](PmarginCreateRepayFuturesSwitchV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_um_leverage_v1

> models::PmarginCreateUmLeverageV1Resp pmargin_create_um_leverage_v1(leverage, symbol, timestamp, recv_window)
Change UM Initial Leverage(TRADE)

Change user's initial leverage of specific symbol in UM.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**leverage** | **i32** |  | [required] |
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginCreateUmLeverageV1Resp**](PmarginCreateUmLeverageV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_um_position_side_dual_v1

> models::PmarginCreateUmPositionSideDualV1Resp pmargin_create_um_position_side_dual_v1(dual_side_position, timestamp, recv_window)
Change UM Position Mode(TRADE)

Change user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol in UM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**dual_side_position** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginCreateUmPositionSideDualV1Resp**](PmarginCreateUmPositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_account_v1

> models::PmarginGetAccountV1Resp pmargin_get_account_v1(timestamp, recv_window)
Account Information(USER_DATA)

Query account information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetAccountV1Resp**](PmarginGetAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_balance_v1

> models::PmarginGetBalanceV1Resp pmargin_get_balance_v1(timestamp, asset, recv_window)
Account Balance(USER_DATA)

Query account balance

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetBalanceV1Resp**](PmarginGetBalanceV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_account_v1

> models::PmarginGetCmAccountV1Resp pmargin_get_cm_account_v1(timestamp, recv_window)
Get CM Account Detail(USER_DATA)

Get current CM account asset and position information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetCmAccountV1Resp**](PmarginGetCmAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_commission_rate_v1

> models::PmarginGetCmCommissionRateV1Resp pmargin_get_cm_commission_rate_v1(symbol, timestamp, recv_window)
Get User Commission Rate for CM(USER_DATA)

Get User Commission Rate for CM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetCmCommissionRateV1Resp**](PmarginGetCmCommissionRateV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_income_v1

> Vec<models::PmarginGetCmIncomeV1RespItem> pmargin_get_cm_income_v1(timestamp, symbol, income_type, start_time, end_time, page, limit, recv_window)
Get CM Income History(USER_DATA)

Get CM Income History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**income_type** | Option<**String**> | &#34;TRANSFER&#34;,&#34;WELCOME_BONUS&#34;, &#34;FUNDING_FEE&#34;, &#34;REALIZED_PNL&#34;, &#34;COMMISSION&#34;, &#34;INSURANCE_CLEAR&#34;, and &#34;DELIVERED_SETTELMENT&#34; |  |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get funding from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get funding until INCLUSIVE. |  |
**page** | Option<**i32**> |  |  |
**limit** | Option<**i32**> | Default 100; max 1000 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetCmIncomeV1RespItem>**](PmarginGetCmIncomeV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_leverage_bracket_v1

> Vec<models::PmarginGetCmLeverageBracketV1RespItem> pmargin_get_cm_leverage_bracket_v1(timestamp, symbol, recv_window)
CM Notional and Leverage Brackets(USER_DATA)

Query CM notional and leverage brackets

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetCmLeverageBracketV1RespItem>**](PmarginGetCmLeverageBracketV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_position_risk_v1

> Vec<models::PmarginGetCmPositionRiskV1RespItem> pmargin_get_cm_position_risk_v1(timestamp, margin_asset, pair, recv_window)
Query CM Position Information(USER_DATA)

Get current CM position information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**margin_asset** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetCmPositionRiskV1RespItem>**](PmarginGetCmPositionRiskV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_position_side_dual_v1

> models::PmarginGetCmPositionSideDualV1Resp pmargin_get_cm_position_side_dual_v1(timestamp, recv_window)
Get CM Current Position Mode(USER_DATA)

Get user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol in CM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetCmPositionSideDualV1Resp**](PmarginGetCmPositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_margin_interest_history_v1

> models::PmarginGetMarginMarginInterestHistoryV1Resp pmargin_get_margin_margin_interest_history_v1(timestamp, asset, start_time, end_time, current, size, archived, recv_window)
Get Margin Borrow/Loan Interest History(USER_DATA)

Get Margin Borrow/Loan Interest History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**archived** | Option<**String**> | Default: `false`. Set to `true` for archived data from 6 months ago |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::PmarginGetMarginMarginInterestHistoryV1Resp**](PmarginGetMarginMarginInterestHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_margin_loan_v1

> models::PmarginGetMarginMarginLoanV1Resp pmargin_get_margin_margin_loan_v1(asset, timestamp, tx_id, start_time, end_time, current, size, archived, recv_window)
Query Margin Loan Record(USER_DATA)

Query margin loan record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**tx_id** | Option<**i64**> | the `tranId` in `POST/papi/v1/marginLoan` |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**archived** | Option<**String**> | Default: `false`. Set to `true` for archived data from 6 months ago |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::PmarginGetMarginMarginLoanV1Resp**](PmarginGetMarginMarginLoanV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_max_borrowable_v1

> models::PmarginGetMarginMaxBorrowableV1Resp pmargin_get_margin_max_borrowable_v1(asset, timestamp, recv_window)
Margin Max Borrow(USER_DATA)

Query margin max borrow

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::PmarginGetMarginMaxBorrowableV1Resp**](PmarginGetMarginMaxBorrowableV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_max_withdraw_v1

> models::PmarginGetMarginMaxWithdrawV1Resp pmargin_get_margin_max_withdraw_v1(asset, timestamp, recv_window)
Query Margin Max Withdraw(USER_DATA)

Query Margin Max Withdraw

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::PmarginGetMarginMaxWithdrawV1Resp**](PmarginGetMarginMaxWithdrawV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_repay_loan_v1

> models::PmarginGetMarginRepayLoanV1Resp pmargin_get_margin_repay_loan_v1(asset, timestamp, tx_id, start_time, end_time, current, size, archived, recv_window)
Query Margin repay Record(USER_DATA)

Query margin repay record.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**tx_id** | Option<**i64**> | the tranId in `POST/papi/v1/repayLoan` |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**archived** | Option<**String**> | Default: `false`. Set to `true` for archived data from 6 months ago |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::PmarginGetMarginRepayLoanV1Resp**](PmarginGetMarginRepayLoanV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_portfolio_interest_history_v1

> Vec<models::PmarginGetPortfolioInterestHistoryV1RespItem> pmargin_get_portfolio_interest_history_v1(timestamp, asset, start_time, end_time, size, recv_window)
Query Portfolio Margin Negative Balance Interest History(USER_DATA)

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

[**Vec<models::PmarginGetPortfolioInterestHistoryV1RespItem>**](PmarginGetPortfolioInterestHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_portfolio_negative_balance_exchange_record_v1

> models::PmarginGetPortfolioNegativeBalanceExchangeRecordV1Resp pmargin_get_portfolio_negative_balance_exchange_record_v1(start_time, end_time, timestamp, recv_window)
Query User Negative Balance Auto Exchange Record (USER_DATA)

Query user negative balance auto exchange record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** |  | [required] |
**end_time** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::PmarginGetPortfolioNegativeBalanceExchangeRecordV1Resp**](PmarginGetPortfolioNegativeBalanceExchangeRecordV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_rate_limit_order_v1

> Vec<models::PmarginGetRateLimitOrderV1RespItem> pmargin_get_rate_limit_order_v1(timestamp, recv_window)
Query User Rate Limit (USER_DATA)

Query User Rate Limit

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetRateLimitOrderV1RespItem>**](PmarginGetRateLimitOrderV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_repay_futures_switch_v1

> models::PmarginGetRepayFuturesSwitchV1Resp pmargin_get_repay_futures_switch_v1(timestamp, recv_window)
Get Auto-repay-futures Status(USER_DATA)

Query Auto-repay-futures Status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetRepayFuturesSwitchV1Resp**](PmarginGetRepayFuturesSwitchV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_account_config_v1

> models::PmarginGetUmAccountConfigV1Resp pmargin_get_um_account_config_v1(timestamp, recv_window)
UM Futures Account Configuration(USER_DATA)

Query UM Futures account configuration

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmAccountConfigV1Resp**](PmarginGetUmAccountConfigV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_account_v1

> models::PmarginGetUmAccountV1Resp pmargin_get_um_account_v1(timestamp, recv_window)
Get UM Account Detail(USER_DATA)

Get current UM account asset and position information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmAccountV1Resp**](PmarginGetUmAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_account_v2

> models::PmarginGetUmAccountV2Resp pmargin_get_um_account_v2(timestamp, recv_window)
Get UM Account Detail V2(USER_DATA)

Get current UM account asset and position information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmAccountV2Resp**](PmarginGetUmAccountV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_api_trading_status_v1

> models::PmarginGetUmApiTradingStatusV1Resp pmargin_get_um_api_trading_status_v1(timestamp, symbol, recv_window)
Portfolio Margin UM Trading Quantitative Rules Indicators(USER_DATA)

Portfolio Margin UM Trading Quantitative Rules Indicators

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmApiTradingStatusV1Resp**](PmarginGetUmApiTradingStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_commission_rate_v1

> models::PmarginGetUmCommissionRateV1Resp pmargin_get_um_commission_rate_v1(symbol, timestamp, recv_window)
Get User Commission Rate for UM(USER_DATA)

Get User Commission Rate for UM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmCommissionRateV1Resp**](PmarginGetUmCommissionRateV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_income_asyn_id_v1

> models::PmarginGetUmIncomeAsynIdV1Resp pmargin_get_um_income_asyn_id_v1(download_id, timestamp, recv_window)
Get UM Futures Transaction Download Link by Id(USER_DATA)

Get UM futures Transaction download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmIncomeAsynIdV1Resp**](PmarginGetUmIncomeAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_income_asyn_v1

> models::PmarginGetUmIncomeAsynV1Resp pmargin_get_um_income_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For UM Futures Transaction History (USER_DATA)

Get download id for UM futures transaction history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmIncomeAsynV1Resp**](PmarginGetUmIncomeAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_income_v1

> Vec<models::PmarginGetUmIncomeV1RespItem> pmargin_get_um_income_v1(timestamp, symbol, income_type, start_time, end_time, page, limit, recv_window)
Get UM Income History(USER_DATA)

Get UM Income History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**income_type** | Option<**String**> | TRANSFER, WELCOME_BONUS, REALIZED_PNL, FUNDING_FEE, COMMISSION, INSURANCE_CLEAR, REFERRAL_KICKBACK, COMMISSION_REBATE, API_REBATE, CONTEST_REWARD, CROSS_COLLATERAL_TRANSFER, OPTIONS_PREMIUM_FEE, OPTIONS_SETTLE_PROFIT, INTERNAL_TRANSFER, AUTO_EXCHANGE, DELIVERED_SETTELMENT, COIN_SWAP_DEPOSIT, COIN_SWAP_WITHDRAW, POSITION_LIMIT_INCREASE_FEE |  |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get funding from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get funding until INCLUSIVE. |  |
**page** | Option<**i32**> |  |  |
**limit** | Option<**i32**> | Default 100; max 1000 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetUmIncomeV1RespItem>**](PmarginGetUmIncomeV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_leverage_bracket_v1

> Vec<models::PmarginGetUmLeverageBracketV1RespItem> pmargin_get_um_leverage_bracket_v1(timestamp, symbol, recv_window)
UM Notional and Leverage Brackets (USER_DATA)

Query UM notional and leverage brackets

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetUmLeverageBracketV1RespItem>**](PmarginGetUmLeverageBracketV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_order_asyn_id_v1

> models::PmarginGetUmOrderAsynIdV1Resp pmargin_get_um_order_asyn_id_v1(download_id, timestamp, recv_window)
Get UM Futures Order Download Link by Id(USER_DATA)

Get UM futures order download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmOrderAsynIdV1Resp**](PmarginGetUmOrderAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_order_asyn_v1

> models::PmarginGetUmOrderAsynV1Resp pmargin_get_um_order_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For UM Futures Order History (USER_DATA)

Get download id for UM futures order history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmOrderAsynV1Resp**](PmarginGetUmOrderAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_position_risk_v1

> Vec<models::PmarginGetUmPositionRiskV1RespItem> pmargin_get_um_position_risk_v1()
Query UM Position Information(USER_DATA)

Get current UM position information.

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::PmarginGetUmPositionRiskV1RespItem>**](PmarginGetUmPositionRiskV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_position_side_dual_v1

> models::PmarginGetUmPositionSideDualV1Resp pmargin_get_um_position_side_dual_v1(timestamp, recv_window)
Get UM Current Position Mode(USER_DATA)

Get user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol in UM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmPositionSideDualV1Resp**](PmarginGetUmPositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_symbol_config_v1

> Vec<models::PmarginGetUmSymbolConfigV1RespItem> pmargin_get_um_symbol_config_v1(timestamp, symbol, recv_window)
UM Futures Symbol Configuration(USER_DATA)

Get current UM account symbol configuration.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetUmSymbolConfigV1RespItem>**](PmarginGetUmSymbolConfigV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_trade_asyn_id_v1

> models::PmarginGetUmTradeAsynIdV1Resp pmargin_get_um_trade_asyn_id_v1(download_id, timestamp, recv_window)
Get UM Futures Trade Download Link by Id(USER_DATA)

Get UM futures trade download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmTradeAsynIdV1Resp**](PmarginGetUmTradeAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_trade_asyn_v1

> models::PmarginGetUmTradeAsynV1Resp pmargin_get_um_trade_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For UM Futures Trade History (USER_DATA)

Get download id for UM futures trade history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmTradeAsynV1Resp**](PmarginGetUmTradeAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

