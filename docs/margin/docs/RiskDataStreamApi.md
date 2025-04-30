# \RiskDataStreamApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**margin_create_margin_listen_key_v1**](RiskDataStreamApi.md#margin_create_margin_listen_key_v1) | **POST** /sapi/v1/margin/listen-key | Start User Data Stream (USER_STREAM)
[**margin_delete_margin_listen_key_v1**](RiskDataStreamApi.md#margin_delete_margin_listen_key_v1) | **DELETE** /sapi/v1/margin/listen-key | Close User Data Stream (USER_STREAM)
[**margin_update_margin_listen_key_v1**](RiskDataStreamApi.md#margin_update_margin_listen_key_v1) | **PUT** /sapi/v1/margin/listen-key | Keepalive User Data Stream (USER_STREAM)



## margin_create_margin_listen_key_v1

> models::MarginCreateMarginListenKeyV1Resp margin_create_margin_listen_key_v1()
Start User Data Stream (USER_STREAM)

Start a new user data stream.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::MarginCreateMarginListenKeyV1Resp**](MarginCreateMarginListenKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_delete_margin_listen_key_v1

> serde_json::Value margin_delete_margin_listen_key_v1()
Close User Data Stream (USER_STREAM)

Close out a user data stream.

### Parameters

This endpoint does not need any parameter.

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_update_margin_listen_key_v1

> serde_json::Value margin_update_margin_listen_key_v1(listen_key)
Keepalive User Data Stream (USER_STREAM)

Keepalive a user data stream to prevent a time out.

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

