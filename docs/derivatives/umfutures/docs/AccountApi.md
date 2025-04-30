# \AccountApi

All URIs are relative to *https://fapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**umfutures_create_fee_burn_v1**](AccountApi.md#umfutures_create_fee_burn_v1) | **POST** /fapi/v1/feeBurn | Toggle BNB Burn On Futures Trade (TRADE)
[**umfutures_get_account_config_v1**](AccountApi.md#umfutures_get_account_config_v1) | **GET** /fapi/v1/accountConfig | Futures Account Configuration(USER_DATA)
[**umfutures_get_account_v2**](AccountApi.md#umfutures_get_account_v2) | **GET** /fapi/v2/account | Account Information V2(USER_DATA)
[**umfutures_get_account_v3**](AccountApi.md#umfutures_get_account_v3) | **GET** /fapi/v3/account | Account Information V3(USER_DATA)
[**umfutures_get_api_trading_status_v1**](AccountApi.md#umfutures_get_api_trading_status_v1) | **GET** /fapi/v1/apiTradingStatus | Futures Trading Quantitative Rules Indicators (USER_DATA)
[**umfutures_get_balance_v2**](AccountApi.md#umfutures_get_balance_v2) | **GET** /fapi/v2/balance | Futures Account Balance V2 (USER_DATA)
[**umfutures_get_balance_v3**](AccountApi.md#umfutures_get_balance_v3) | **GET** /fapi/v3/balance | Futures Account Balance V3 (USER_DATA)
[**umfutures_get_commission_rate_v1**](AccountApi.md#umfutures_get_commission_rate_v1) | **GET** /fapi/v1/commissionRate | User Commission Rate (USER_DATA)
[**umfutures_get_fee_burn_v1**](AccountApi.md#umfutures_get_fee_burn_v1) | **GET** /fapi/v1/feeBurn | Get BNB Burn Status (USER_DATA)
[**umfutures_get_income_asyn_id_v1**](AccountApi.md#umfutures_get_income_asyn_id_v1) | **GET** /fapi/v1/income/asyn/id | Get Futures Transaction History Download Link by Id (USER_DATA)
[**umfutures_get_income_asyn_v1**](AccountApi.md#umfutures_get_income_asyn_v1) | **GET** /fapi/v1/income/asyn | Get Download Id For Futures Transaction History(USER_DATA)
[**umfutures_get_income_v1**](AccountApi.md#umfutures_get_income_v1) | **GET** /fapi/v1/income | Get Income History (USER_DATA)
[**umfutures_get_leverage_bracket_v1**](AccountApi.md#umfutures_get_leverage_bracket_v1) | **GET** /fapi/v1/leverageBracket | Notional and Leverage Brackets (USER_DATA)
[**umfutures_get_multi_assets_margin_v1**](AccountApi.md#umfutures_get_multi_assets_margin_v1) | **GET** /fapi/v1/multiAssetsMargin | Get Current Multi-Assets Mode (USER_DATA)
[**umfutures_get_order_asyn_id_v1**](AccountApi.md#umfutures_get_order_asyn_id_v1) | **GET** /fapi/v1/order/asyn/id | Get Futures Order History Download Link by Id (USER_DATA)
[**umfutures_get_order_asyn_v1**](AccountApi.md#umfutures_get_order_asyn_v1) | **GET** /fapi/v1/order/asyn | Get Download Id For Futures Order History (USER_DATA)
[**umfutures_get_position_side_dual_v1**](AccountApi.md#umfutures_get_position_side_dual_v1) | **GET** /fapi/v1/positionSide/dual | Get Current Position Mode(USER_DATA)
[**umfutures_get_rate_limit_order_v1**](AccountApi.md#umfutures_get_rate_limit_order_v1) | **GET** /fapi/v1/rateLimit/order | Query User Rate Limit (USER_DATA)
[**umfutures_get_symbol_config_v1**](AccountApi.md#umfutures_get_symbol_config_v1) | **GET** /fapi/v1/symbolConfig | Symbol Configuration(USER_DATA)
[**umfutures_get_trade_asyn_id_v1**](AccountApi.md#umfutures_get_trade_asyn_id_v1) | **GET** /fapi/v1/trade/asyn/id | Get Futures Trade Download Link by Id(USER_DATA)
[**umfutures_get_trade_asyn_v1**](AccountApi.md#umfutures_get_trade_asyn_v1) | **GET** /fapi/v1/trade/asyn | Get Download Id For Futures Trade History (USER_DATA)



## umfutures_create_fee_burn_v1

> models::UmfuturesCreateFeeBurnV1Resp umfutures_create_fee_burn_v1(fee_burn, timestamp, recv_window)
Toggle BNB Burn On Futures Trade (TRADE)

Change user's BNB Fee Discount (Fee Discount On or Fee Discount Off ) on EVERY symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**fee_burn** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesCreateFeeBurnV1Resp**](UmfuturesCreateFeeBurnV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_account_config_v1

> models::UmfuturesGetAccountConfigV1Resp umfutures_get_account_config_v1(timestamp, recv_window)
Futures Account Configuration(USER_DATA)

Query account configuration

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetAccountConfigV1Resp**](UmfuturesGetAccountConfigV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_account_v2

> models::UmfuturesGetAccountV2Resp umfutures_get_account_v2(timestamp, recv_window)
Account Information V2(USER_DATA)

Get current account information. User in single-asset/ multi-assets mode will see different value, see comments in response section for detail.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetAccountV2Resp**](UmfuturesGetAccountV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_account_v3

> models::UmfuturesGetAccountV3Resp umfutures_get_account_v3(timestamp, recv_window)
Account Information V3(USER_DATA)

Get current account information. User in single-asset/ multi-assets mode will see different value, see comments in response section for detail.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetAccountV3Resp**](UmfuturesGetAccountV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_api_trading_status_v1

> models::UmfuturesGetApiTradingStatusV1Resp umfutures_get_api_trading_status_v1(timestamp, symbol, recv_window)
Futures Trading Quantitative Rules Indicators (USER_DATA)

Futures trading quantitative rules indicators, for more information on this, please refer to the Futures Trading Quantitative Rules

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetApiTradingStatusV1Resp**](UmfuturesGetApiTradingStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_balance_v2

> Vec<models::UmfuturesGetBalanceV2RespItem> umfutures_get_balance_v2(timestamp, recv_window)
Futures Account Balance V2 (USER_DATA)

Query account balance info

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetBalanceV2RespItem>**](UmfuturesGetBalanceV2RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_balance_v3

> Vec<models::UmfuturesGetBalanceV3RespItem> umfutures_get_balance_v3(timestamp, recv_window)
Futures Account Balance V3 (USER_DATA)

Query account balance info

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetBalanceV3RespItem>**](UmfuturesGetBalanceV3RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_commission_rate_v1

> models::UmfuturesGetCommissionRateV1Resp umfutures_get_commission_rate_v1(symbol, timestamp, recv_window)
User Commission Rate (USER_DATA)

Get User Commission Rate

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetCommissionRateV1Resp**](UmfuturesGetCommissionRateV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_fee_burn_v1

> models::UmfuturesGetFeeBurnV1Resp umfutures_get_fee_burn_v1(timestamp, recv_window)
Get BNB Burn Status (USER_DATA)

Get user's BNB Fee Discount (Fee Discount On or Fee Discount Off )

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetFeeBurnV1Resp**](UmfuturesGetFeeBurnV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_income_asyn_id_v1

> models::UmfuturesGetIncomeAsynIdV1Resp umfutures_get_income_asyn_id_v1(download_id, timestamp, recv_window)
Get Futures Transaction History Download Link by Id (USER_DATA)

Get futures transaction history download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetIncomeAsynIdV1Resp**](UmfuturesGetIncomeAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_income_asyn_v1

> models::UmfuturesGetIncomeAsynV1Resp umfutures_get_income_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For Futures Transaction History(USER_DATA)

Get download id for futures transaction history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetIncomeAsynV1Resp**](UmfuturesGetIncomeAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_income_v1

> Vec<models::UmfuturesGetIncomeV1RespItem> umfutures_get_income_v1(timestamp, symbol, income_type, start_time, end_time, page, limit, recv_window)
Get Income History (USER_DATA)

Query income history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**income_type** | Option<**String**> | TRANSFER, WELCOME_BONUS, REALIZED_PNL, FUNDING_FEE, COMMISSION, INSURANCE_CLEAR, REFERRAL_KICKBACK, COMMISSION_REBATE, API_REBATE, CONTEST_REWARD, CROSS_COLLATERAL_TRANSFER, OPTIONS_PREMIUM_FEE, OPTIONS_SETTLE_PROFIT, INTERNAL_TRANSFER, AUTO_EXCHANGE, DELIVERED_SETTELMENT, COIN_SWAP_DEPOSIT, COIN_SWAP_WITHDRAW, POSITION_LIMIT_INCREASE_FEE, STRATEGY_UMFUTURES_TRANSFER，FEE_RETURN，BFUSD_REWARD |  |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get funding from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get funding until INCLUSIVE. |  |
**page** | Option<**i32**> |  |  |
**limit** | Option<**i32**> | Default 100; max 1000 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetIncomeV1RespItem>**](UmfuturesGetIncomeV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_leverage_bracket_v1

> models::UmfuturesGetLeverageBracketV1Resp umfutures_get_leverage_bracket_v1(timestamp, symbol, recv_window)
Notional and Leverage Brackets (USER_DATA)

Query user notional and leverage bracket on speicfic symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetLeverageBracketV1Resp**](UmfuturesGetLeverageBracketV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_multi_assets_margin_v1

> models::UmfuturesGetMultiAssetsMarginV1Resp umfutures_get_multi_assets_margin_v1(timestamp, recv_window)
Get Current Multi-Assets Mode (USER_DATA)

Get user's Multi-Assets mode (Multi-Assets Mode or Single-Asset Mode) on Every symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetMultiAssetsMarginV1Resp**](UmfuturesGetMultiAssetsMarginV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_order_asyn_id_v1

> models::UmfuturesGetOrderAsynIdV1Resp umfutures_get_order_asyn_id_v1(download_id, timestamp, recv_window)
Get Futures Order History Download Link by Id (USER_DATA)

Get futures order history download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetOrderAsynIdV1Resp**](UmfuturesGetOrderAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_order_asyn_v1

> models::UmfuturesGetOrderAsynV1Resp umfutures_get_order_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For Futures Order History (USER_DATA)

Get Download Id For Futures Order History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetOrderAsynV1Resp**](UmfuturesGetOrderAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_position_side_dual_v1

> models::UmfuturesGetPositionSideDualV1Resp umfutures_get_position_side_dual_v1(timestamp, recv_window)
Get Current Position Mode(USER_DATA)

Get user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetPositionSideDualV1Resp**](UmfuturesGetPositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_rate_limit_order_v1

> Vec<models::UmfuturesGetRateLimitOrderV1RespItem> umfutures_get_rate_limit_order_v1(timestamp, recv_window)
Query User Rate Limit (USER_DATA)

Query User Rate Limit

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetRateLimitOrderV1RespItem>**](UmfuturesGetRateLimitOrderV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_symbol_config_v1

> Vec<models::UmfuturesGetSymbolConfigV1RespItem> umfutures_get_symbol_config_v1(timestamp, symbol, recv_window)
Symbol Configuration(USER_DATA)

Get current account symbol configuration.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::UmfuturesGetSymbolConfigV1RespItem>**](UmfuturesGetSymbolConfigV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_trade_asyn_id_v1

> models::UmfuturesGetTradeAsynIdV1Resp umfutures_get_trade_asyn_id_v1(download_id, timestamp, recv_window)
Get Futures Trade Download Link by Id(USER_DATA)

Get futures trade download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetTradeAsynIdV1Resp**](UmfuturesGetTradeAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_get_trade_asyn_v1

> models::UmfuturesGetTradeAsynV1Resp umfutures_get_trade_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For Futures Trade History (USER_DATA)

Get download id for futures trade history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::UmfuturesGetTradeAsynV1Resp**](UmfuturesGetTradeAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

