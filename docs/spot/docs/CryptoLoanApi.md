# \CryptoLoanApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_loan_flexible_adjust_ltv_v2**](CryptoLoanApi.md#create_loan_flexible_adjust_ltv_v2) | **POST** /sapi/v2/loan/flexible/adjust/ltv | Flexible Loan Adjust LTV(TRADE)
[**create_loan_flexible_borrow_v2**](CryptoLoanApi.md#create_loan_flexible_borrow_v2) | **POST** /sapi/v2/loan/flexible/borrow | Flexible Loan Borrow(TRADE)
[**create_loan_flexible_repay_collateral_v2**](CryptoLoanApi.md#create_loan_flexible_repay_collateral_v2) | **POST** /sapi/v2/loan/flexible/repay/collateral | Flexible Loan Collateral Repayment (TRADE)
[**create_loan_flexible_repay_v2**](CryptoLoanApi.md#create_loan_flexible_repay_v2) | **POST** /sapi/v2/loan/flexible/repay | Flexible Loan Repay(TRADE)
[**get_loan_borrow_history_v1**](CryptoLoanApi.md#get_loan_borrow_history_v1) | **GET** /sapi/v1/loan/borrow/history | Get Loan Borrow History(USER_DATA)
[**get_loan_flexible_borrow_history_v2**](CryptoLoanApi.md#get_loan_flexible_borrow_history_v2) | **GET** /sapi/v2/loan/flexible/borrow/history | Get Flexible Loan Borrow History(USER_DATA)
[**get_loan_flexible_collateral_data_v2**](CryptoLoanApi.md#get_loan_flexible_collateral_data_v2) | **GET** /sapi/v2/loan/flexible/collateral/data | Get Flexible Loan Collateral Assets Data(USER_DATA)
[**get_loan_flexible_liquidation_history_v2**](CryptoLoanApi.md#get_loan_flexible_liquidation_history_v2) | **GET** /sapi/v2/loan/flexible/liquidation/history | Get Flexible Loan Liquidation History (USER_DATA)
[**get_loan_flexible_loanable_data_v2**](CryptoLoanApi.md#get_loan_flexible_loanable_data_v2) | **GET** /sapi/v2/loan/flexible/loanable/data | Get Flexible Loan Assets Data(USER_DATA)
[**get_loan_flexible_ltv_adjustment_history_v2**](CryptoLoanApi.md#get_loan_flexible_ltv_adjustment_history_v2) | **GET** /sapi/v2/loan/flexible/ltv/adjustment/history | Get Flexible Loan LTV Adjustment History(USER_DATA)
[**get_loan_flexible_ongoing_orders_v2**](CryptoLoanApi.md#get_loan_flexible_ongoing_orders_v2) | **GET** /sapi/v2/loan/flexible/ongoing/orders | Get Flexible Loan Ongoing Orders(USER_DATA)
[**get_loan_flexible_repay_history_v2**](CryptoLoanApi.md#get_loan_flexible_repay_history_v2) | **GET** /sapi/v2/loan/flexible/repay/history | Get Flexible Loan Repayment History(USER_DATA)
[**get_loan_flexible_repay_rate_v2**](CryptoLoanApi.md#get_loan_flexible_repay_rate_v2) | **GET** /sapi/v2/loan/flexible/repay/rate | Check Collateral Repay Rate (USER_DATA)
[**get_loan_income_v1**](CryptoLoanApi.md#get_loan_income_v1) | **GET** /sapi/v1/loan/income | Get Crypto Loans Income History(USER_DATA)
[**get_loan_ltv_adjustment_history_v1**](CryptoLoanApi.md#get_loan_ltv_adjustment_history_v1) | **GET** /sapi/v1/loan/ltv/adjustment/history | Get Loan LTV Adjustment History(USER_DATA)
[**get_loan_repay_history_v1**](CryptoLoanApi.md#get_loan_repay_history_v1) | **GET** /sapi/v1/loan/repay/history | Get Loan Repayment History(USER_DATA)



## create_loan_flexible_adjust_ltv_v2

> models::CreateLoanFlexibleAdjustLtvV2Resp create_loan_flexible_adjust_ltv_v2(adjustment_amount, collateral_coin, direction, loan_coin, timestamp, recv_window)
Flexible Loan Adjust LTV(TRADE)

Flexible Loan Adjust LTV

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**adjustment_amount** | **String** |  | [required] |[default to ]
**collateral_coin** | **String** |  | [required] |[default to ]
**direction** | **String** |  | [required] |[default to ]
**loan_coin** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateLoanFlexibleAdjustLtvV2Resp**](CreateLoanFlexibleAdjustLtvV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_loan_flexible_borrow_v2

> models::CreateLoanFlexibleBorrowV2Resp create_loan_flexible_borrow_v2(collateral_coin, loan_coin, timestamp, collateral_amount, loan_amount, recv_window)
Flexible Loan Borrow(TRADE)

Borrow Flexible Loan

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**collateral_coin** | **String** |  | [required] |[default to ]
**loan_coin** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**collateral_amount** | Option<**String**> |  |  |[default to ]
**loan_amount** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateLoanFlexibleBorrowV2Resp**](CreateLoanFlexibleBorrowV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_loan_flexible_repay_collateral_v2

> models::CreateLoanFlexibleRepayCollateralV2Resp create_loan_flexible_repay_collateral_v2()
Flexible Loan Collateral Repayment (TRADE)

** Request Weight(UID) ** 6000 Parameters: - repayAmount refers to the loan amount the user would like to repay

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::CreateLoanFlexibleRepayCollateralV2Resp**](CreateLoanFlexibleRepayCollateralV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_loan_flexible_repay_v2

> models::CreateLoanFlexibleRepayV2Resp create_loan_flexible_repay_v2(collateral_coin, loan_coin, repay_amount, timestamp, collateral_return, full_repayment, recv_window)
Flexible Loan Repay(TRADE)

Flexible Loan Repay

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**collateral_coin** | **String** |  | [required] |[default to ]
**loan_coin** | **String** |  | [required] |[default to ]
**repay_amount** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**collateral_return** | Option<**bool**> |  |  |
**full_repayment** | Option<**bool**> |  |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateLoanFlexibleRepayV2Resp**](CreateLoanFlexibleRepayV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_borrow_history_v1

> models::GetLoanBorrowHistoryV1Resp get_loan_borrow_history_v1(timestamp, order_id, loan_coin, collateral_coin, start_time, end_time, current, limit, recv_window)
Get Loan Borrow History(USER_DATA)

Get Loan Borrow History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> | orderId in `POST /sapi/v1/loan/borrow` |  |
**loan_coin** | Option<**String**> |  |  |[default to ]
**collateral_coin** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Current querying page. Start from 1; default: 1; max: 1000. |  |[default to 1]
**limit** | Option<**i64**> | Default: 10; max: 100. |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanBorrowHistoryV1Resp**](GetLoanBorrowHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_flexible_borrow_history_v2

> models::GetLoanFlexibleBorrowHistoryV2Resp get_loan_flexible_borrow_history_v2(timestamp, loan_coin, collateral_coin, start_time, end_time, current, limit, recv_window)
Get Flexible Loan Borrow History(USER_DATA)

Get Flexible Loan Borrow History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**loan_coin** | Option<**String**> |  |  |[default to ]
**collateral_coin** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Current querying page. Start from 1; default: 1; max: 1000 |  |[default to 1]
**limit** | Option<**i64**> | Default: 10; max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanFlexibleBorrowHistoryV2Resp**](GetLoanFlexibleBorrowHistoryV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_flexible_collateral_data_v2

> models::GetLoanFlexibleCollateralDataV2Resp get_loan_flexible_collateral_data_v2(timestamp, collateral_coin, recv_window)
Get Flexible Loan Collateral Assets Data(USER_DATA)

Get LTV information and collateral limit of flexible loan's collateral assets. The collateral limit is shown in USD value.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**collateral_coin** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanFlexibleCollateralDataV2Resp**](GetLoanFlexibleCollateralDataV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_flexible_liquidation_history_v2

> models::GetLoanFlexibleLiquidationHistoryV2Resp get_loan_flexible_liquidation_history_v2(timestamp, loan_coin, collateral_coin, start_time, end_time, current, limit, recv_window)
Get Flexible Loan Liquidation History (USER_DATA)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**loan_coin** | Option<**String**> |  |  |[default to ]
**collateral_coin** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Current querying page. Start from 1; default: 1; max: 1000 |  |[default to 1]
**limit** | Option<**i64**> | Default: 10; max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanFlexibleLiquidationHistoryV2Resp**](GetLoanFlexibleLiquidationHistoryV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_flexible_loanable_data_v2

> models::GetLoanFlexibleLoanableDataV2Resp get_loan_flexible_loanable_data_v2(timestamp, loan_coin, recv_window)
Get Flexible Loan Assets Data(USER_DATA)

Get interest rate and borrow limit of flexible loanable assets. The borrow limit is shown in USD value.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**loan_coin** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanFlexibleLoanableDataV2Resp**](GetLoanFlexibleLoanableDataV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_flexible_ltv_adjustment_history_v2

> models::GetLoanFlexibleLtvAdjustmentHistoryV2Resp get_loan_flexible_ltv_adjustment_history_v2(timestamp, loan_coin, collateral_coin, start_time, end_time, current, limit, recv_window)
Get Flexible Loan LTV Adjustment History(USER_DATA)

Get Flexible Loan LTV Adjustment History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**loan_coin** | Option<**String**> |  |  |[default to ]
**collateral_coin** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Current querying page. Start from 1; default: 1; max: 1000 |  |[default to 1]
**limit** | Option<**i64**> | Default: 10; max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanFlexibleLtvAdjustmentHistoryV2Resp**](GetLoanFlexibleLtvAdjustmentHistoryV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_flexible_ongoing_orders_v2

> models::GetLoanFlexibleOngoingOrdersV2Resp get_loan_flexible_ongoing_orders_v2(timestamp, loan_coin, collateral_coin, current, limit, recv_window)
Get Flexible Loan Ongoing Orders(USER_DATA)

Get Flexible Loan Ongoing Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**loan_coin** | Option<**String**> |  |  |[default to ]
**collateral_coin** | Option<**String**> |  |  |[default to ]
**current** | Option<**i64**> | Current querying page. Start from 1; default: 1; max: 1000 |  |[default to 1]
**limit** | Option<**i64**> | Default: 10; max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanFlexibleOngoingOrdersV2Resp**](GetLoanFlexibleOngoingOrdersV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_flexible_repay_history_v2

> models::GetLoanFlexibleRepayHistoryV2Resp get_loan_flexible_repay_history_v2(timestamp, loan_coin, collateral_coin, start_time, end_time, current, limit, recv_window)
Get Flexible Loan Repayment History(USER_DATA)

Get Flexible Loan Repayment History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**loan_coin** | Option<**String**> |  |  |[default to ]
**collateral_coin** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Current querying page. Start from 1; default: 1; max: 1000 |  |[default to 1]
**limit** | Option<**i64**> | Default: 10; max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanFlexibleRepayHistoryV2Resp**](GetLoanFlexibleRepayHistoryV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_flexible_repay_rate_v2

> models::GetLoanFlexibleRepayRateV2Resp get_loan_flexible_repay_rate_v2(loan_coin, collateral_coin, timestamp, recv_window)
Check Collateral Repay Rate (USER_DATA)

Get the latest rate of collateral coin/loan coin when using collateral repay.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**loan_coin** | **String** |  | [required] |[default to ]
**collateral_coin** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanFlexibleRepayRateV2Resp**](GetLoanFlexibleRepayRateV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_income_v1

> Vec<models::GetLoanIncomeV1RespItem> get_loan_income_v1(timestamp, asset, r#type, start_time, end_time, limit, recv_window)
Get Crypto Loans Income History(USER_DATA)

Get Crypto Loans Income History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**r#type** | Option<**String**> | All types will be returned by default. Enum：`borrowIn` ,`collateralSpent`, `repayAmount`, `collateralReturn`(Collateral return after repayment), `addCollateral`, `removeCollateral`, `collateralReturnAfterLiquidation` |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | default 20, max 100 |  |[default to 20]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetLoanIncomeV1RespItem>**](GetLoanIncomeV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_ltv_adjustment_history_v1

> models::GetLoanLtvAdjustmentHistoryV1Resp get_loan_ltv_adjustment_history_v1(timestamp, order_id, loan_coin, collateral_coin, start_time, end_time, current, limit, recv_window)
Get Loan LTV Adjustment History(USER_DATA)

Get Loan LTV Adjustment History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**loan_coin** | Option<**String**> |  |  |[default to ]
**collateral_coin** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Current querying page. Start from 1; default: 1; max: 1000 |  |[default to 1]
**limit** | Option<**i64**> | Default: 10; max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanLtvAdjustmentHistoryV1Resp**](GetLoanLtvAdjustmentHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_loan_repay_history_v1

> models::GetLoanRepayHistoryV1Resp get_loan_repay_history_v1(timestamp, order_id, loan_coin, collateral_coin, start_time, end_time, current, limit, recv_window)
Get Loan Repayment History(USER_DATA)

Get Loan Repayment History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**loan_coin** | Option<**String**> |  |  |[default to ]
**collateral_coin** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Current querying page. Start from 1; default: 1; max: 1000 |  |[default to 1]
**limit** | Option<**i64**> | Default: 10; max: 100 |  |[default to 10]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetLoanRepayHistoryV1Resp**](GetLoanRepayHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

