# \AccountApi

All URIs are relative to *https://eapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**options_get_account_v1**](AccountApi.md#options_get_account_v1) | **GET** /eapi/v1/account | Option Account Information(TRADE)
[**options_get_bill_v1**](AccountApi.md#options_get_bill_v1) | **GET** /eapi/v1/bill | Account Funding Flow (USER_DATA)
[**options_get_income_asyn_id_v1**](AccountApi.md#options_get_income_asyn_id_v1) | **GET** /eapi/v1/income/asyn/id | Get Option Transaction History Download Link by Id (USER_DATA)
[**options_get_income_asyn_v1**](AccountApi.md#options_get_income_asyn_v1) | **GET** /eapi/v1/income/asyn | Get Download Id For Option Transaction History (USER_DATA)



## options_get_account_v1

> models::OptionsGetAccountV1Resp options_get_account_v1(timestamp, recv_window)
Option Account Information(TRADE)

Get current account information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::OptionsGetAccountV1Resp**](OptionsGetAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_bill_v1

> Vec<models::OptionsGetBillV1RespItem> options_get_bill_v1(currency, timestamp, record_id, start_time, end_time, limit, recv_window)
Account Funding Flow (USER_DATA)

Query account funding flows.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**currency** | **String** | Asset type, only support USDT  as of now | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**record_id** | Option<**i64**> | Return the recordId and subsequent data, the latest data is returned by default, e.g 100000 |  |
**start_time** | Option<**i64**> | Start Time, e.g 1593511200000 |  |
**end_time** | Option<**i64**> | End Time, e.g 1593512200000 |  |
**limit** | Option<**i32**> | Number of result sets returned Default:100 Max:1000 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::OptionsGetBillV1RespItem>**](OptionsGetBillV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_income_asyn_id_v1

> models::OptionsGetIncomeAsynIdV1Resp options_get_income_asyn_id_v1(download_id, timestamp, recv_window)
Get Option Transaction History Download Link by Id (USER_DATA)

Get option transaction history download Link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::OptionsGetIncomeAsynIdV1Resp**](OptionsGetIncomeAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_income_asyn_v1

> models::OptionsGetIncomeAsynV1Resp options_get_income_asyn_v1()
Get Download Id For Option Transaction History (USER_DATA)

Get download id for option transaction history

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::OptionsGetIncomeAsynV1Resp**](OptionsGetIncomeAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

