# \MarketDataApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**convert_get_convert_asset_info_v1**](MarketDataApi.md#convert_get_convert_asset_info_v1) | **GET** /sapi/v1/convert/assetInfo | Query order quantity precision per asset(USER_DATA)
[**convert_get_convert_exchange_info_v1**](MarketDataApi.md#convert_get_convert_exchange_info_v1) | **GET** /sapi/v1/convert/exchangeInfo | List All Convert Pairs



## convert_get_convert_asset_info_v1

> Vec<models::ConvertGetConvertAssetInfoV1RespItem> convert_get_convert_asset_info_v1(timestamp, recv_window)
Query order quantity precision per asset(USER_DATA)

Query for supported asset’s precision information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::ConvertGetConvertAssetInfoV1RespItem>**](ConvertGetConvertAssetInfoV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## convert_get_convert_exchange_info_v1

> Vec<models::ConvertGetConvertExchangeInfoV1RespItem> convert_get_convert_exchange_info_v1(from_asset, to_asset)
List All Convert Pairs

Query for all convertible token pairs and the tokens’ respective upper/lower limits

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**from_asset** | Option<**String**> | User spends coin |  |[default to ]
**to_asset** | Option<**String**> | User receives coin |  |[default to ]

### Return type

[**Vec<models::ConvertGetConvertExchangeInfoV1RespItem>**](ConvertGetConvertExchangeInfoV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

