# \UserDataStreamApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**spot_create_user_data_stream_v3**](UserDataStreamApi.md#spot_create_user_data_stream_v3) | **POST** /api/v3/userDataStream | Start user data stream (USER_STREAM)
[**spot_delete_user_data_stream_v3**](UserDataStreamApi.md#spot_delete_user_data_stream_v3) | **DELETE** /api/v3/userDataStream | Close user data stream (USER_STREAM)
[**spot_update_user_data_stream_v3**](UserDataStreamApi.md#spot_update_user_data_stream_v3) | **PUT** /api/v3/userDataStream | Keepalive user data stream (USER_STREAM)



## spot_create_user_data_stream_v3

> models::SpotCreateUserDataStreamV3Resp spot_create_user_data_stream_v3()
Start user data stream (USER_STREAM)

Start a new user data stream. The stream will close after 60 minutes unless a keepalive is sent.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::SpotCreateUserDataStreamV3Resp**](SpotCreateUserDataStreamV3Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_delete_user_data_stream_v3

> serde_json::Value spot_delete_user_data_stream_v3(listen_key)
Close user data stream (USER_STREAM)

Close out a user data stream.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**listen_key** | **String** |  | [required] |[default to ]

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## spot_update_user_data_stream_v3

> serde_json::Value spot_update_user_data_stream_v3(listen_key)
Keepalive user data stream (USER_STREAM)

Keepalive a user data stream to prevent a time out. User data streams will close after 60 minutes. It's recommended to send a ping about every 30 minutes.

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

