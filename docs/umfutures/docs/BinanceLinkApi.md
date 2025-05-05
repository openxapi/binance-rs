# \BinanceLinkApi

All URIs are relative to *https://fapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_api_referral_customization_v1**](BinanceLinkApi.md#create_api_referral_customization_v1) | **POST** /fapi/v1/apiReferral/customization | Customize Id For Client (USER DATA)(For Partner)
[**create_api_referral_user_customization_papiv1**](BinanceLinkApi.md#create_api_referral_user_customization_papiv1) | **POST** /papi/v1/apiReferral/userCustomization | Customize Id For Client  (USER DATA)(For client)(PAPI)
[**create_api_referral_user_customization_v1**](BinanceLinkApi.md#create_api_referral_user_customization_v1) | **POST** /fapi/v1/apiReferral/userCustomization | Customize Id For Client  (USER DATA)(For client)
[**get_api_referral_customization_v1**](BinanceLinkApi.md#get_api_referral_customization_v1) | **GET** /fapi/v1/apiReferral/customization | Get Client Email Customized Id (USER DATA)
[**get_api_referral_if_new_user_papiv1**](BinanceLinkApi.md#get_api_referral_if_new_user_papiv1) | **GET** /papi/v1/apiReferral/ifNewUser | Query Client If The New User (USER DATA)(PAPI)
[**get_api_referral_if_new_user_v1**](BinanceLinkApi.md#get_api_referral_if_new_user_v1) | **GET** /fapi/v1/apiReferral/ifNewUser | Query Client If The New User (USER DATA)
[**get_api_referral_overview_v1**](BinanceLinkApi.md#get_api_referral_overview_v1) | **GET** /fapi/v1/apiReferral/overview | Get Rebate Data Overview (USER DATA)
[**get_api_referral_rebate_vol_v1**](BinanceLinkApi.md#get_api_referral_rebate_vol_v1) | **GET** /fapi/v1/apiReferral/rebateVol | Get Rebate Volume (USER DATA)
[**get_api_referral_trade_vol_v1**](BinanceLinkApi.md#get_api_referral_trade_vol_v1) | **GET** /fapi/v1/apiReferral/tradeVol | Get User Trade Volume (USER DATA)
[**get_api_referral_trader_num_v1**](BinanceLinkApi.md#get_api_referral_trader_num_v1) | **GET** /fapi/v1/apiReferral/traderNum | Get Trader Number (USER DATA)
[**get_api_referral_trader_summary_v1**](BinanceLinkApi.md#get_api_referral_trader_summary_v1) | **GET** /fapi/v1/apiReferral/traderSummary | Get Trader Detail (USER DATA)
[**get_api_referral_user_customization_papiv1**](BinanceLinkApi.md#get_api_referral_user_customization_papiv1) | **GET** /papi/v1/apiReferral/userCustomization | Get User’s Customize Id (USER DATA)(PAPI)
[**get_api_referral_user_customization_v1**](BinanceLinkApi.md#get_api_referral_user_customization_v1) | **GET** /fapi/v1/apiReferral/userCustomization | Get User’s Customize Id (USER DATA)
[**get_income_v1**](BinanceLinkApi.md#get_income_v1) | **GET** /fapi/v1/income | Get Income History(USER DATA)



## create_api_referral_customization_v1

> models::CreateApiReferralCustomizationV1Resp create_api_referral_customization_v1(customer_id, email, timestamp, recv_window)
Customize Id For Client (USER DATA)(For Partner)

- CustomerId must be unique

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


## create_api_referral_user_customization_papiv1

> models::CreateApiReferralUserCustomizationV1Resp create_api_referral_user_customization_papiv1(broker_id, customer_id, timestamp, recv_window)
Customize Id For Client  (USER DATA)(For client)(PAPI)

- CustomerId must be unique

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**broker_id** | **String** |  | [required] |[default to ]
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


## create_api_referral_user_customization_v1

> models::CreateApiReferralUserCustomizationV1Resp create_api_referral_user_customization_v1(broker_id, customer_id, timestamp, recv_window)
Customize Id For Client  (USER DATA)(For client)

- CustomerId must be unique - If the user enabled Portfolio Margin, please user relevant /papi endpoint

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**broker_id** | **String** |  | [required] |[default to ]
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


## get_api_referral_customization_v1

> Vec<models::GetApiReferralCustomizationV1RespItem> get_api_referral_customization_v1(timestamp, customer_id, email, page, limit, recv_window)
Get Client Email Customized Id (USER DATA)

- CustomerId and email can not be sent at the same time

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**customer_id** | Option<**String**> |  |  |[default to ]
**email** | Option<**String**> |  |  |[default to ]
**page** | Option<**i64**> | default 1 |  |[default to 1]
**limit** | Option<**i64**> | items num of one page，default 100，max 1000 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetApiReferralCustomizationV1RespItem>**](GetApiReferralCustomizationV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_if_new_user_papiv1

> models::GetApiReferralIfNewUserV1Resp get_api_referral_if_new_user_papiv1(broker_id, timestamp, r#type, recv_window)
Query Client If The New User (USER DATA)(PAPI)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**broker_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | Option<**i32**> | 1:USDT-margined Futures,  2: Coin-margined Futures ; Default：1:USDT-margined Futures |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetApiReferralIfNewUserV1Resp**](GetApiReferralIfNewUserV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_if_new_user_v1

> models::GetApiReferralIfNewUserV1Resp get_api_referral_if_new_user_v1(broker_id, timestamp, r#type, recv_window)
Query Client If The New User (USER DATA)

- If the user enabled Portfolio Margin, please user relevant /papi endpoint

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**broker_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | Option<**i32**> | 1:USDT-margined Futures，2: Coin-margined Futures; Default：1:USDT-margined Futures |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetApiReferralIfNewUserV1Resp**](GetApiReferralIfNewUserV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_overview_v1

> models::GetApiReferralOverviewV1Resp get_api_referral_overview_v1(timestamp, r#type, recv_window)
Get Rebate Data Overview (USER DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**r#type** | Option<**i32**> | 1:USDT Margined Futures, 2:COIN Margined Futures Default： USDT Margined Futures |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetApiReferralOverviewV1Resp**](GetApiReferralOverviewV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_rebate_vol_v1

> Vec<models::GetApiReferralRebateVolV1RespItem> get_api_referral_rebate_vol_v1(timestamp, r#type, start_time, end_time, limit, recv_window)
Get Rebate Volume (USER DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**r#type** | Option<**i32**> | 1:USDT Margined Futures, 2:COIN Margined Futures Default： USDT Margined Futures |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | default 500, max 1000 |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetApiReferralRebateVolV1RespItem>**](GetApiReferralRebateVolV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_trade_vol_v1

> Vec<models::GetApiReferralTradeVolV1RespItem> get_api_referral_trade_vol_v1(timestamp, r#type, start_time, end_time, limit, recv_window)
Get User Trade Volume (USER DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**r#type** | Option<**i32**> | 1:USDT Margined Futures, 2:COIN Margined Futures Default： USDT Margined Futures |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | default 500, max 1000 |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetApiReferralTradeVolV1RespItem>**](GetApiReferralTradeVolV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_trader_num_v1

> Vec<models::GetApiReferralTraderNumV1RespItem> get_api_referral_trader_num_v1(timestamp, r#type, start_time, end_time, limit, recv_window)
Get Trader Number (USER DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**r#type** | Option<**i32**> | 1:USDT Margined Futures, 2:COIN Margined Futures Default： USDT Margined Futures |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | default 500, max 1000 |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetApiReferralTraderNumV1RespItem>**](GetApiReferralTraderNumV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_trader_summary_v1

> Vec<models::GetApiReferralTraderSummaryV1RespItem> get_api_referral_trader_summary_v1(timestamp, customer_id, r#type, start_time, end_time, limit, recv_window)
Get Trader Detail (USER DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**customer_id** | Option<**String**> |  |  |[default to ]
**r#type** | Option<**i32**> | 1:USDT Margined Futures, 2:COIN Margined Futures Default： USDT Margined Futures |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | default 500, max 1000 |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetApiReferralTraderSummaryV1RespItem>**](GetApiReferralTraderSummaryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_api_referral_user_customization_papiv1

> models::GetApiReferralUserCustomizationV1Resp get_api_referral_user_customization_papiv1(broker_id, timestamp, recv_window)
Get User’s Customize Id (USER DATA)(PAPI)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**broker_id** | **String** |  | [required] |[default to ]
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


## get_api_referral_user_customization_v1

> models::GetApiReferralUserCustomizationV1Resp get_api_referral_user_customization_v1(broker_id, timestamp, recv_window)
Get User’s Customize Id (USER DATA)

- CustomerId must be unique - If the user enabled Portfolio Margin, please user relevant /papi endpoint

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**broker_id** | **String** |  | [required] |[default to ]
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


## get_income_v1

> Vec<models::GetIncomeV1RespItem> get_income_v1(timestamp, symbol, income_type, start_time, end_time, limit, recv_window)
Get Income History(USER DATA)

- If incomeType  is not sent, all kinds of flow will be returned - If startTime and endTime are not sent, the most recent limit datas will be returned. - If the number of data between startTime and endTime is larger than limit, response will be return as startTime + limit.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**income_type** | Option<**String**> | &#34;TRANSFER&#34;，&#34;WELCOME_BONUS&#34;, &#34;REALIZED_PNL&#34;，&#34;FUNDING_FEE&#34;, &#34;COMMISSION&#34;, and &#34;INSURANCE_CLEAR&#34; |  |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get funding from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get funding until INCLUSIVE. |  |
**limit** | Option<**i32**> | Default 100; max 1000 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetIncomeV1RespItem>**](GetIncomeV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

