# \BorrowAndRepayApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**margin_create_margin_borrow_repay_v1**](BorrowAndRepayApi.md#margin_create_margin_borrow_repay_v1) | **POST** /sapi/v1/margin/borrow-repay | Margin account borrow/repay(MARGIN)
[**margin_get_margin_borrow_repay_v1**](BorrowAndRepayApi.md#margin_get_margin_borrow_repay_v1) | **GET** /sapi/v1/margin/borrow-repay | Query borrow/repay records in Margin account(USER_DATA)
[**margin_get_margin_interest_history_v1**](BorrowAndRepayApi.md#margin_get_margin_interest_history_v1) | **GET** /sapi/v1/margin/interestHistory | Get Interest History (USER_DATA)
[**margin_get_margin_interest_rate_history_v1**](BorrowAndRepayApi.md#margin_get_margin_interest_rate_history_v1) | **GET** /sapi/v1/margin/interestRateHistory | Query Margin Interest Rate History (USER_DATA)
[**margin_get_margin_max_borrowable_v1**](BorrowAndRepayApi.md#margin_get_margin_max_borrowable_v1) | **GET** /sapi/v1/margin/maxBorrowable | Query Max Borrow (USER_DATA)
[**margin_get_margin_next_hourly_interest_rate_v1**](BorrowAndRepayApi.md#margin_get_margin_next_hourly_interest_rate_v1) | **GET** /sapi/v1/margin/next-hourly-interest-rate | Get future hourly interest rate (USER_DATA)



## margin_create_margin_borrow_repay_v1

> models::MarginCreateMarginBorrowRepayV1Resp margin_create_margin_borrow_repay_v1(amount, asset, is_isolated, symbol, timestamp, r#type, recv_window)
Margin account borrow/repay(MARGIN)

Margin account borrow/repay(MARGIN)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**is_isolated** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::MarginCreateMarginBorrowRepayV1Resp**](MarginCreateMarginBorrowRepayV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_borrow_repay_v1

> models::MarginGetMarginBorrowRepayV1Resp margin_get_margin_borrow_repay_v1(r#type, timestamp, asset, isolated_symbol, tx_id, start_time, end_time, current, size, recv_window)
Query borrow/repay records in Margin account(USER_DATA)

Query borrow/repay records in Margin account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**r#type** | **String** | `BORROW` or `REPAY` | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**isolated_symbol** | Option<**String**> | Symbol in Isolated Margin |  |[default to ]
**tx_id** | Option<**i64**> | `tranId` in `POST /sapi/v1/margin/loan` |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Current querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::MarginGetMarginBorrowRepayV1Resp**](MarginGetMarginBorrowRepayV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_interest_history_v1

> models::MarginGetMarginInterestHistoryV1Resp margin_get_margin_interest_history_v1(timestamp, asset, isolated_symbol, start_time, end_time, current, size, recv_window)
Get Interest History (USER_DATA)

Get Interest History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**isolated_symbol** | Option<**String**> | isolated symbol |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::MarginGetMarginInterestHistoryV1Resp**](MarginGetMarginInterestHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_interest_rate_history_v1

> Vec<models::MarginGetMarginInterestRateHistoryV1RespItem> margin_get_margin_interest_rate_history_v1(asset, timestamp, vip_level, start_time, end_time, recv_window)
Query Margin Interest Rate History (USER_DATA)

Query Margin Interest Rate History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**vip_level** | Option<**i32**> | Default: user&#39;s vip level |  |
**start_time** | Option<**i64**> | Default: 7 days ago |  |
**end_time** | Option<**i64**> | Default: present. Maximum range: 1 months. |  |
**recv_window** | Option<**i64**> | No more than 60000 |  |

### Return type

[**Vec<models::MarginGetMarginInterestRateHistoryV1RespItem>**](MarginGetMarginInterestRateHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_max_borrowable_v1

> models::MarginGetMarginMaxBorrowableV1Resp margin_get_margin_max_borrowable_v1(asset, timestamp, isolated_symbol, recv_window)
Query Max Borrow (USER_DATA)

Query Max Borrow

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**isolated_symbol** | Option<**String**> | isolated symbol |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::MarginGetMarginMaxBorrowableV1Resp**](MarginGetMarginMaxBorrowableV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_next_hourly_interest_rate_v1

> Vec<models::MarginGetMarginNextHourlyInterestRateV1RespItem> margin_get_margin_next_hourly_interest_rate_v1(assets, is_isolated)
Get future hourly interest rate (USER_DATA)

Get future hourly interest rate

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**assets** | **String** | List of assets, separated by commas, up to 20 | [required] |[default to ]
**is_isolated** | **bool** | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34; | [required] |

### Return type

[**Vec<models::MarginGetMarginNextHourlyInterestRateV1RespItem>**](MarginGetMarginNextHourlyInterestRateV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

