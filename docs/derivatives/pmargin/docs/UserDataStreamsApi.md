# \UserDataStreamsApi

All URIs are relative to *https://papi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**pmargin_create_listen_key_v1**](UserDataStreamsApi.md#pmargin_create_listen_key_v1) | **POST** /papi/v1/listenKey | Start User Data Stream(USER_STREAM)
[**pmargin_delete_listen_key_v1**](UserDataStreamsApi.md#pmargin_delete_listen_key_v1) | **DELETE** /papi/v1/listenKey | Close User Data Stream(USER_STREAM)
[**pmargin_update_listen_key_v1**](UserDataStreamsApi.md#pmargin_update_listen_key_v1) | **PUT** /papi/v1/listenKey | Keepalive User Data Stream (USER_STREAM)



## pmargin_create_listen_key_v1

> models::PmarginCreateListenKeyV1Resp pmargin_create_listen_key_v1()
Start User Data Stream(USER_STREAM)

Start a new user data stream. The stream will close after 60 minutes unless a keepalive is sent. If the account has an active listenKey, that listenKey will be returned and its validity will be extended for 60 minutes.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::PmarginCreateListenKeyV1Resp**](PmarginCreateListenKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_delete_listen_key_v1

> serde_json::Value pmargin_delete_listen_key_v1()
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


## pmargin_update_listen_key_v1

> serde_json::Value pmargin_update_listen_key_v1()
Keepalive User Data Stream (USER_STREAM)

Keepalive a user data stream to prevent a time out. User data streams will close after 60 minutes. It's recommended to send a ping about every 60 minutes.

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

