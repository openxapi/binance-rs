# \AccountApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**margin_create_margin_isolated_account_v1**](AccountApi.md#margin_create_margin_isolated_account_v1) | **POST** /sapi/v1/margin/isolated/account | Enable Isolated Margin Account (TRADE)
[**margin_create_margin_max_leverage_v1**](AccountApi.md#margin_create_margin_max_leverage_v1) | **POST** /sapi/v1/margin/max-leverage | Adjust cross margin max leverage (USER_DATA)
[**margin_delete_margin_isolated_account_v1**](AccountApi.md#margin_delete_margin_isolated_account_v1) | **DELETE** /sapi/v1/margin/isolated/account | Disable Isolated Margin Account (TRADE)
[**margin_get_bnb_burn_v1**](AccountApi.md#margin_get_bnb_burn_v1) | **GET** /sapi/v1/bnbBurn | Get BNB Burn Status (USER_DATA)
[**margin_get_margin_account_v1**](AccountApi.md#margin_get_margin_account_v1) | **GET** /sapi/v1/margin/account | Query Cross Margin Account Details (USER_DATA)
[**margin_get_margin_capital_flow_v1**](AccountApi.md#margin_get_margin_capital_flow_v1) | **GET** /sapi/v1/margin/capital-flow | Query Cross Isolated Margin Capital Flow (USER_DATA)
[**margin_get_margin_cross_margin_data_v1**](AccountApi.md#margin_get_margin_cross_margin_data_v1) | **GET** /sapi/v1/margin/crossMarginData | Query Cross Margin Fee Data (USER_DATA)
[**margin_get_margin_isolated_account_limit_v1**](AccountApi.md#margin_get_margin_isolated_account_limit_v1) | **GET** /sapi/v1/margin/isolated/accountLimit | Query Enabled Isolated Margin Account Limit (USER_DATA)
[**margin_get_margin_isolated_account_v1**](AccountApi.md#margin_get_margin_isolated_account_v1) | **GET** /sapi/v1/margin/isolated/account | Query Isolated Margin Account Info (USER_DATA)
[**margin_get_margin_isolated_margin_data_v1**](AccountApi.md#margin_get_margin_isolated_margin_data_v1) | **GET** /sapi/v1/margin/isolatedMarginData | Query Isolated Margin Fee Data (USER_DATA)
[**margin_get_margin_trade_coeff_v1**](AccountApi.md#margin_get_margin_trade_coeff_v1) | **GET** /sapi/v1/margin/tradeCoeff | Get Summary of Margin account (USER_DATA)



## margin_create_margin_isolated_account_v1

> models::MarginCreateMarginIsolatedAccountV1Resp margin_create_margin_isolated_account_v1(symbol, timestamp, recv_window)
Enable Isolated Margin Account (TRADE)

Enable isolated margin account for a specific symbol(Only supports activation of previously disabled accounts).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::MarginCreateMarginIsolatedAccountV1Resp**](MarginCreateMarginIsolatedAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_create_margin_max_leverage_v1

> models::MarginCreateMarginMaxLeverageV1Resp margin_create_margin_max_leverage_v1(max_leverage)
Adjust cross margin max leverage (USER_DATA)

Adjust cross margin max leverage

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**max_leverage** | **i32** |  | [required] |

### Return type

[**models::MarginCreateMarginMaxLeverageV1Resp**](MarginCreateMarginMaxLeverageV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_delete_margin_isolated_account_v1

> models::MarginDeleteMarginIsolatedAccountV1Resp margin_delete_margin_isolated_account_v1(symbol, timestamp, recv_window)
Disable Isolated Margin Account (TRADE)

Disable isolated margin account for a specific symbol. Each trading pair can only be deactivated once every 24 hours.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | No more than 60000 |  |

### Return type

[**models::MarginDeleteMarginIsolatedAccountV1Resp**](MarginDeleteMarginIsolatedAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_bnb_burn_v1

> models::MarginGetBnbBurnV1Resp margin_get_bnb_burn_v1(timestamp, recv_window)
Get BNB Burn Status (USER_DATA)

Get BNB Burn Status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | No more than 60000 |  |

### Return type

[**models::MarginGetBnbBurnV1Resp**](MarginGetBnbBurnV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_account_v1

> models::MarginGetMarginAccountV1Resp margin_get_margin_account_v1(timestamp, recv_window)
Query Cross Margin Account Details (USER_DATA)

Query Cross Margin Account Details

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::MarginGetMarginAccountV1Resp**](MarginGetMarginAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_capital_flow_v1

> Vec<models::MarginGetMarginCapitalFlowV1RespItem> margin_get_margin_capital_flow_v1(timestamp, asset, symbol, r#type, start_time, end_time, from_id, limit, recv_window)
Query Cross Isolated Margin Capital Flow (USER_DATA)

Query Cross Isolated Margin Capital Flow

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**symbol** | Option<**String**> | 查询逐仓数据时必填 |  |[default to ]
**r#type** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> | 只支持查询最近90天的数据 |  |
**end_time** | Option<**i64**> |  |  |
**from_id** | Option<**i64**> | 如设置fromId, 将返回id &gt; fromId的数据。否则将返回最新数据 |  |
**limit** | Option<**i64**> | 每次返回的数据条数限制。默认 500; 最大 1000. |  |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::MarginGetMarginCapitalFlowV1RespItem>**](MarginGetMarginCapitalFlowV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_cross_margin_data_v1

> Vec<models::MarginGetMarginCrossMarginDataV1RespItem> margin_get_margin_cross_margin_data_v1(timestamp, vip_level, coin, recv_window)
Query Cross Margin Fee Data (USER_DATA)

Get cross margin fee data collection with any vip level or user's current specific data as https://www.binance.com/en/margin-fee

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**vip_level** | Option<**i32**> | User&#39;s current specific margin data will be returned if vipLevel is omitted |  |
**coin** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | No more than `60000` |  |

### Return type

[**Vec<models::MarginGetMarginCrossMarginDataV1RespItem>**](MarginGetMarginCrossMarginDataV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_isolated_account_limit_v1

> models::MarginGetMarginIsolatedAccountLimitV1Resp margin_get_margin_isolated_account_limit_v1(timestamp, recv_window)
Query Enabled Isolated Margin Account Limit (USER_DATA)

Query enabled isolated margin account limit.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | No more than 60000 |  |

### Return type

[**models::MarginGetMarginIsolatedAccountLimitV1Resp**](MarginGetMarginIsolatedAccountLimitV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_isolated_account_v1

> models::MarginGetMarginIsolatedAccountV1Resp margin_get_margin_isolated_account_v1(timestamp, symbols, recv_window)
Query Isolated Margin Account Info (USER_DATA)

Query Isolated Margin Account Info

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbols** | Option<**String**> | Max 5 symbols can be sent; separated by &#34;,&#34;. e.g. &#34;BTCUSDT,BNBUSDT,ADAUSDT&#34; |  |[default to ]
**recv_window** | Option<**i64**> | No more than 60000 |  |

### Return type

[**models::MarginGetMarginIsolatedAccountV1Resp**](MarginGetMarginIsolatedAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_isolated_margin_data_v1

> Vec<models::MarginGetMarginIsolatedMarginDataV1RespItem> margin_get_margin_isolated_margin_data_v1(timestamp, vip_level, symbol, recv_window)
Query Isolated Margin Fee Data (USER_DATA)

Get isolated margin fee data collection with any vip level or user's current specific data as https://www.binance.com/en/margin-fee

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**vip_level** | Option<**i32**> | User&#39;s current specific margin data will be returned if vipLevel is omitted |  |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | No more than `60000` |  |

### Return type

[**Vec<models::MarginGetMarginIsolatedMarginDataV1RespItem>**](MarginGetMarginIsolatedMarginDataV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_trade_coeff_v1

> models::MarginGetMarginTradeCoeffV1Resp margin_get_margin_trade_coeff_v1(timestamp, recv_window)
Get Summary of Margin account (USER_DATA)

Get personal margin level information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::MarginGetMarginTradeCoeffV1Resp**](MarginGetMarginTradeCoeffV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

