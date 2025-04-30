# \TransferApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**margin_get_margin_max_transferable_v1**](TransferApi.md#margin_get_margin_max_transferable_v1) | **GET** /sapi/v1/margin/maxTransferable | Query Max Transfer-Out Amount (USER_DATA)
[**margin_get_margin_transfer_v1**](TransferApi.md#margin_get_margin_transfer_v1) | **GET** /sapi/v1/margin/transfer | Get Cross Margin Transfer History (USER_DATA)



## margin_get_margin_max_transferable_v1

> models::MarginGetMarginMaxTransferableV1Resp margin_get_margin_max_transferable_v1(asset, timestamp, isolated_symbol, recv_window)
Query Max Transfer-Out Amount (USER_DATA)

Query Max Transfer-Out Amount

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**isolated_symbol** | Option<**String**> | isolated symbol |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::MarginGetMarginMaxTransferableV1Resp**](MarginGetMarginMaxTransferableV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_transfer_v1

> models::MarginGetMarginTransferV1Resp margin_get_margin_transfer_v1(timestamp, asset, r#type, start_time, end_time, current, size, isolated_symbol, recv_window)
Get Cross Margin Transfer History (USER_DATA)

Get Cross Margin Transfer History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**r#type** | Option<**String**> | Transfer Type: ROLL_IN, ROLL_OUT |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**isolated_symbol** | Option<**String**> | Symbol in Isolated Margin |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::MarginGetMarginTransferV1Resp**](MarginGetMarginTransferV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

