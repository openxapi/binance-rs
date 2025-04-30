# \TradeDataStreamApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**margin_create_user_data_stream_isolated_v1**](TradeDataStreamApi.md#margin_create_user_data_stream_isolated_v1) | **POST** /sapi/v1/userDataStream/isolated | Start Isolated Margin User Data Stream (USER_STREAM)
[**margin_create_user_data_stream_v1**](TradeDataStreamApi.md#margin_create_user_data_stream_v1) | **POST** /sapi/v1/userDataStream | Start Margin User Data Stream (USER_STREAM)
[**margin_delete_user_data_stream_isolated_v1**](TradeDataStreamApi.md#margin_delete_user_data_stream_isolated_v1) | **DELETE** /sapi/v1/userDataStream/isolated | Close Isolated Margin User Data Stream (USER_STREAM)
[**margin_delete_user_data_stream_v1**](TradeDataStreamApi.md#margin_delete_user_data_stream_v1) | **DELETE** /sapi/v1/userDataStream | Close Margin User Data Stream (USER_STREAM)
[**margin_update_user_data_stream_isolated_v1**](TradeDataStreamApi.md#margin_update_user_data_stream_isolated_v1) | **PUT** /sapi/v1/userDataStream/isolated | Keepalive Isolated Margin User Data Stream (USER_STREAM)
[**margin_update_user_data_stream_v1**](TradeDataStreamApi.md#margin_update_user_data_stream_v1) | **PUT** /sapi/v1/userDataStream | Keepalive Margin User Data Stream (USER_STREAM)



## margin_create_user_data_stream_isolated_v1

> models::MarginCreateUserDataStreamIsolatedV1Resp margin_create_user_data_stream_isolated_v1(symbol)
Start Isolated Margin User Data Stream (USER_STREAM)

Start a new isolated margin user data stream. The stream will close after 60 minutes unless a keepalive is sent. If the account has an active listenKey, that listenKey will be returned and its validity will be extended for 60 minutes.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::MarginCreateUserDataStreamIsolatedV1Resp**](MarginCreateUserDataStreamIsolatedV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_create_user_data_stream_v1

> models::MarginCreateUserDataStreamV1Resp margin_create_user_data_stream_v1()
Start Margin User Data Stream (USER_STREAM)

Start a new margin user data stream. The stream will close after 60 minutes unless a keepalive is sent. If the account has an active listenKey, that listenKey will be returned and its validity will be extended for 60 minutes.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::MarginCreateUserDataStreamV1Resp**](MarginCreateUserDataStreamV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_delete_user_data_stream_isolated_v1

> serde_json::Value margin_delete_user_data_stream_isolated_v1(symbol, listenkey)
Close Isolated Margin User Data Stream (USER_STREAM)

Close out a isolated margin user data stream.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**listenkey** | **String** |  | [required] |[default to ]

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_delete_user_data_stream_v1

> serde_json::Value margin_delete_user_data_stream_v1(listenkey)
Close Margin User Data Stream (USER_STREAM)

Close out a Margin user data stream.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**listenkey** | **String** |  | [required] |[default to ]

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_update_user_data_stream_isolated_v1

> serde_json::Value margin_update_user_data_stream_isolated_v1(listen_key, symbol)
Keepalive Isolated Margin User Data Stream (USER_STREAM)

Keepalive an isolated margin user data stream to prevent a time out.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**listen_key** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_update_user_data_stream_v1

> serde_json::Value margin_update_user_data_stream_v1(listen_key)
Keepalive Margin User Data Stream (USER_STREAM)

Keepalive a margin user data stream to prevent a time out.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**listen_key** | **String** |  | [required] |[default to ]

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

