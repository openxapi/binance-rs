# \UserDataStreamsApi

All URIs are relative to *https://fapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**umfutures_create_listen_key_v1**](UserDataStreamsApi.md#umfutures_create_listen_key_v1) | **POST** /fapi/v1/listenKey | Start User Data Stream (USER_STREAM)
[**umfutures_delete_listen_key_v1**](UserDataStreamsApi.md#umfutures_delete_listen_key_v1) | **DELETE** /fapi/v1/listenKey | Close User Data Stream (USER_STREAM)
[**umfutures_update_listen_key_v1**](UserDataStreamsApi.md#umfutures_update_listen_key_v1) | **PUT** /fapi/v1/listenKey | Keepalive User Data Stream (USER_STREAM)



## umfutures_create_listen_key_v1

> models::UmfuturesCreateListenKeyV1Resp umfutures_create_listen_key_v1()
Start User Data Stream (USER_STREAM)

Start a new user data stream. The stream will close after 60 minutes unless a keepalive is sent. If the account has an active listenKey, that listenKey will be returned and its validity will be extended for 60 minutes.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::UmfuturesCreateListenKeyV1Resp**](UmfuturesCreateListenKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## umfutures_delete_listen_key_v1

> serde_json::Value umfutures_delete_listen_key_v1()
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


## umfutures_update_listen_key_v1

> models::UmfuturesUpdateListenKeyV1Resp umfutures_update_listen_key_v1()
Keepalive User Data Stream (USER_STREAM)

Keepalive a user data stream to prevent a time out. User data streams will close after 60 minutes. It's recommended to send a ping about every 60 minutes.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::UmfuturesUpdateListenKeyV1Resp**](UmfuturesUpdateListenKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

