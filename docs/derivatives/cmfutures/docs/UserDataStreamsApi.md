# \UserDataStreamsApi

All URIs are relative to *https://dapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**cmfutures_create_listen_key_v1**](UserDataStreamsApi.md#cmfutures_create_listen_key_v1) | **POST** /dapi/v1/listenKey | Start User Data Stream (USER_STREAM)
[**cmfutures_delete_listen_key_v1**](UserDataStreamsApi.md#cmfutures_delete_listen_key_v1) | **DELETE** /dapi/v1/listenKey | Close User Data Stream(USER_STREAM)
[**cmfutures_update_listen_key_v1**](UserDataStreamsApi.md#cmfutures_update_listen_key_v1) | **PUT** /dapi/v1/listenKey | Keepalive User Data Stream (USER_STREAM)



## cmfutures_create_listen_key_v1

> models::CmfuturesCreateListenKeyV1Resp cmfutures_create_listen_key_v1()
Start User Data Stream (USER_STREAM)

Start a new user data stream. The stream will close after 60 minutes unless a keepalive is sent. If the account has an active listenKey, that listenKey will be returned and its validity will be extended for 60 minutes.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::CmfuturesCreateListenKeyV1Resp**](CmfuturesCreateListenKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## cmfutures_delete_listen_key_v1

> serde_json::Value cmfutures_delete_listen_key_v1()
Close User Data Stream(USER_STREAM)

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


## cmfutures_update_listen_key_v1

> serde_json::Value cmfutures_update_listen_key_v1()
Keepalive User Data Stream (USER_STREAM)

Keepalive a user data stream to prevent a time out. User data streams will close after 60 minutes.

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

