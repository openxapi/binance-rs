# \VipLoanApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_loan_vip_borrow_v1**](VipLoanApi.md#create_loan_vip_borrow_v1) | **POST** /sapi/v1/loan/vip/borrow | VIP Loan Borrow(TRADE)
[**create_loan_vip_renew_v1**](VipLoanApi.md#create_loan_vip_renew_v1) | **POST** /sapi/v1/loan/vip/renew | VIP Loan Renew(TRADE)
[**create_loan_vip_repay_v1**](VipLoanApi.md#create_loan_vip_repay_v1) | **POST** /sapi/v1/loan/vip/repay | VIP Loan Repay(TRADE)
[**get_loan_vip_accrued_interest_v1**](VipLoanApi.md#get_loan_vip_accrued_interest_v1) | **GET** /sapi/v1/loan/vip/accruedInterest | Get VIP Loan Accrued Interest(USER_DATA)
[**get_loan_vip_collateral_account_v1**](VipLoanApi.md#get_loan_vip_collateral_account_v1) | **GET** /sapi/v1/loan/vip/collateral/account | Check VIP Loan Collateral Account (USER_DATA)
[**get_loan_vip_collateral_data_v1**](VipLoanApi.md#get_loan_vip_collateral_data_v1) | **GET** /sapi/v1/loan/vip/collateral/data | Get Collateral Asset Data(USER_DATA)
[**get_loan_vip_interest_rate_history_v1**](VipLoanApi.md#get_loan_vip_interest_rate_history_v1) | **GET** /sapi/v1/loan/vip/interestRateHistory | Get VIP Loan Interest Rate History (USER_DATA)
[**get_loan_vip_loanable_data_v1**](VipLoanApi.md#get_loan_vip_loanable_data_v1) | **GET** /sapi/v1/loan/vip/loanable/data | Get Loanable Assets Data(USER_DATA)
[**get_loan_vip_ongoing_orders_v1**](VipLoanApi.md#get_loan_vip_ongoing_orders_v1) | **GET** /sapi/v1/loan/vip/ongoing/orders | Get VIP Loan Ongoing Orders(USER_DATA)
[**get_loan_vip_repay_history_v1**](VipLoanApi.md#get_loan_vip_repay_history_v1) | **GET** /sapi/v1/loan/vip/repay/history | Get VIP Loan Repayment History(USER_DATA)
[**get_loan_vip_request_data_v1**](VipLoanApi.md#get_loan_vip_request_data_v1) | **GET** /sapi/v1/loan/vip/request/data | Query Application Status(USER_DATA)
[**get_loan_vip_request_interest_rate_v1**](VipLoanApi.md#get_loan_vip_request_interest_rate_v1) | **GET** /sapi/v1/loan/vip/request/interestRate | Get Borrow Interest Rate(USER_DATA)



## create_loan_vip_borrow_v1

> models::CreateLoanVipBorrowV1Resp create_loan_vip_borrow_v1()
VIP Loan Borrow(TRADE)

VIP loan is available for VIP users only.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::CreateLoanVipBorrowV1Resp**](CreateLoanVipBorrowV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_loan_vip_renew_v1

> models::CreateLoanVipRenewV1Resp create_loan_vip_renew_v1(loan_term, order_id, timestamp, recv_window)
VIP Loan Renew(TRADE)

VIP loan is available for VIP users only.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**loan_term** | **i32** |  | [required] |
**order_id** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateLoanVipRenewV1Resp**](CreateLoanVipRenewV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_loan_vip_repay_v1

> models::CreateLoanVipRepayV1Resp create_loan_vip_repay_v1(amount, order_id, timestamp, recv_window)
VIP Loan Repay(TRADE)

VIP loan is available for VIP users only.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**order_id** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateLoanVipRepayV1Resp**](CreateLoanVipRepayV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_vip_accrued_interest_v1

> models::GetLoanVipAccruedInterestV1Resp get_loan_vip_accrued_interest_v1(recv_window, timestamp, order_id, loan_coin, start_time, end_time, current, limit)
Get VIP Loan Accrued Interest(USER_DATA)

GET /sapi/v1/loan/vip/accruedInterest

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**recv_window** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**loan_coin** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Current querying page. Start from 1; default: 1; max: 1000 |  |[default to 1]
**limit** | Option<**i64**> | Default: 10; max: 100 |  |[default to 10]

### Return type

[**models::GetLoanVipAccruedInterestV1Resp**](GetLoanVipAccruedInterestV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_vip_collateral_account_v1

> models::GetLoanVipCollateralAccountV1Resp get_loan_vip_collateral_account_v1(timestamp, order_id, collateral_account_id, recv_window)
Check VIP Loan Collateral Account (USER_DATA)

VIP loan is available for VIP users only

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**collateral_account_id** | Option<**i64**> |  |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanVipCollateralAccountV1Resp**](GetLoanVipCollateralAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_vip_collateral_data_v1

> models::GetLoanVipCollateralDataV1Resp get_loan_vip_collateral_data_v1(timestamp, collateral_coin, recv_window)
Get Collateral Asset Data(USER_DATA)

Get Collateral Asset Data

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**collateral_coin** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanVipCollateralDataV1Resp**](GetLoanVipCollateralDataV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_vip_interest_rate_history_v1

> models::GetLoanVipInterestRateHistoryV1Resp get_loan_vip_interest_rate_history_v1(coin, recv_window, timestamp, start_time, end_time, current, limit)
Get VIP Loan Interest Rate History (USER_DATA)

Get VIP Loan Interest Rate History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**coin** | **String** |  | [required] |[default to ]
**recv_window** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Check current querying page, start from 1. Default：1；Max：1000. |  |
**limit** | Option<**i64**> | Default：10; Max：100. |  |

### Return type

[**models::GetLoanVipInterestRateHistoryV1Resp**](GetLoanVipInterestRateHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_vip_loanable_data_v1

> models::GetLoanVipLoanableDataV1Resp get_loan_vip_loanable_data_v1(timestamp, loan_coin, vip_level, recv_window)
Get Loanable Assets Data(USER_DATA)

Get interest rate and borrow limit of loanable assets. The borrow limit is shown in USD value.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**loan_coin** | Option<**String**> |  |  |[default to ]
**vip_level** | Option<**i32**> | default:user&#39;s vip level |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanVipLoanableDataV1Resp**](GetLoanVipLoanableDataV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_vip_ongoing_orders_v1

> models::GetLoanVipOngoingOrdersV1Resp get_loan_vip_ongoing_orders_v1(timestamp, order_id, collateral_account_id, loan_coin, collateral_coin, current, limit, recv_window)
Get VIP Loan Ongoing Orders(USER_DATA)

VIP loan is available for VIP users only.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**collateral_account_id** | Option<**i64**> |  |  |
**loan_coin** | Option<**String**> |  |  |[default to ]
**collateral_coin** | Option<**String**> |  |  |[default to ]
**current** | Option<**i64**> | Currently querying page. Start from 1, Default:1, Max: 1000. |  |
**limit** | Option<**i64**> | Default: 10, Max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanVipOngoingOrdersV1Resp**](GetLoanVipOngoingOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_vip_repay_history_v1

> models::GetLoanVipRepayHistoryV1Resp get_loan_vip_repay_history_v1(timestamp, order_id, loan_coin, start_time, end_time, current, limit, recv_window)
Get VIP Loan Repayment History(USER_DATA)

GET /sapi/v1/loan/vip/repay/history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**loan_coin** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1, Default:1, Max: 1000 |  |
**limit** | Option<**i64**> | Default: 10, Max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanVipRepayHistoryV1Resp**](GetLoanVipRepayHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_vip_request_data_v1

> models::GetLoanVipRequestDataV1Resp get_loan_vip_request_data_v1(timestamp, current, limit, recv_window)
Query Application Status(USER_DATA)

Query Application Status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**current** | Option<**i64**> | Currently querying page. Start from 1, Default:1, Max: 1000 |  |
**limit** | Option<**i64**> | Default: 10, Max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanVipRequestDataV1Resp**](GetLoanVipRequestDataV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_vip_request_interest_rate_v1

> Vec<models::GetLoanVipRequestInterestRateV1RespItem> get_loan_vip_request_interest_rate_v1(loan_coin, timestamp, recv_window)
Get Borrow Interest Rate(USER_DATA)

Get Borrow Interest Rate

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**loan_coin** | **String** | Max 10 assets, Multiple split by &#34;,&#34; | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetLoanVipRequestInterestRateV1RespItem>**](GetLoanVipRequestInterestRateV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

