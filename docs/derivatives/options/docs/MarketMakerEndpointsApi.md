# \MarketMakerEndpointsApi

All URIs are relative to *https://eapi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**options_create_countdown_cancel_all_heart_beat_v1**](MarketMakerEndpointsApi.md#options_create_countdown_cancel_all_heart_beat_v1) | **POST** /eapi/v1/countdownCancelAllHeartBeat | Auto-Cancel All Open Orders (Kill-Switch) Heartbeat (TRADE)
[**options_create_countdown_cancel_all_v1**](MarketMakerEndpointsApi.md#options_create_countdown_cancel_all_v1) | **POST** /eapi/v1/countdownCancelAll | Set Auto-Cancel All Open Orders (Kill-Switch) Config (TRADE)
[**options_create_mmp_reset_v1**](MarketMakerEndpointsApi.md#options_create_mmp_reset_v1) | **POST** /eapi/v1/mmpReset | Reset Market Maker Protection Config (TRADE)
[**options_create_mmp_set_v1**](MarketMakerEndpointsApi.md#options_create_mmp_set_v1) | **POST** /eapi/v1/mmpSet | Set Market Maker Protection Config (TRADE)
[**options_get_countdown_cancel_all_v1**](MarketMakerEndpointsApi.md#options_get_countdown_cancel_all_v1) | **GET** /eapi/v1/countdownCancelAll | Get Auto-Cancel All Open Orders (Kill-Switch) Config (TRADE)
[**options_get_margin_account_v1**](MarketMakerEndpointsApi.md#options_get_margin_account_v1) | **GET** /eapi/v1/marginAccount | Option Margin Account Information (USER_DATA)
[**options_get_mmp_v1**](MarketMakerEndpointsApi.md#options_get_mmp_v1) | **GET** /eapi/v1/mmp | Get Market Maker Protection Config (TRADE)



## options_create_countdown_cancel_all_heart_beat_v1

> models::OptionsCreateCountdownCancelAllHeartBeatV1Resp options_create_countdown_cancel_all_heart_beat_v1(timestamp, underlyings, recv_window)
Auto-Cancel All Open Orders (Kill-Switch) Heartbeat (TRADE)

This endpoint resets the time from which the countdown will begin to the time this messaged is received.  It should be called repeatedly as heartbeats.  Multiple heartbeats can be updated at once by specifying the underlying symbols as a list (ex. BTCUSDT,ETHUSDT) in the underlyings parameter.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**underlyings** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::OptionsCreateCountdownCancelAllHeartBeatV1Resp**](OptionsCreateCountdownCancelAllHeartBeatV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_create_countdown_cancel_all_v1

> models::OptionsCreateCountdownCancelAllV1Resp options_create_countdown_cancel_all_v1(countdown_time, timestamp, underlying, recv_window)
Set Auto-Cancel All Open Orders (Kill-Switch) Config (TRADE)

This endpoint sets the parameters of the auto-cancel feature which cancels all open orders (both market maker protection and non market maker protection order types) of the underlying symbol at the end of the specified countdown time period if no heartbeat message is sent.  After the countdown time period, all open orders will be cancelled and new orders will be rejected with error code -2010 until either a heartbeat message is sent or the auto-cancel feature is turned off by setting countdownTime to 0.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**countdown_time** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**underlying** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::OptionsCreateCountdownCancelAllV1Resp**](OptionsCreateCountdownCancelAllV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_create_mmp_reset_v1

> models::OptionsCreateMmpResetV1Resp options_create_mmp_reset_v1(timestamp, recv_window, underlying)
Reset Market Maker Protection Config (TRADE)

Reset MMP, start MMP order again.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |
**underlying** | Option<**String**> |  |  |[default to ]

### Return type

[**models::OptionsCreateMmpResetV1Resp**](OptionsCreateMmpResetV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_create_mmp_set_v1

> models::OptionsCreateMmpSetV1Resp options_create_mmp_set_v1(timestamp, delta_limit, frozen_time_in_milliseconds, qty_limit, recv_window, underlying, window_time_in_milliseconds)
Set Market Maker Protection Config (TRADE)

Set config for MMP. Market Maker Protection(MMP) is a set of protection mechanism for option market maker, this mechanism is able to prevent mass trading in short period time. Once market maker's account branches the threshold, the Market Maker Protection will be triggered. When Market Maker Protection triggers, all the current MMP orders will be canceled, new MMP orders will be rejected. Market maker can use this time to reevaluate market and modify order price.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**delta_limit** | Option<**String**> |  |  |[default to ]
**frozen_time_in_milliseconds** | Option<**i64**> |  |  |
**qty_limit** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**underlying** | Option<**String**> |  |  |[default to ]
**window_time_in_milliseconds** | Option<**i64**> |  |  |

### Return type

[**models::OptionsCreateMmpSetV1Resp**](OptionsCreateMmpSetV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_countdown_cancel_all_v1

> models::OptionsGetCountdownCancelAllV1Resp options_get_countdown_cancel_all_v1(timestamp, underlying, recv_window)
Get Auto-Cancel All Open Orders (Kill-Switch) Config (TRADE)

This endpoint returns the auto-cancel parameters for each underlying symbol. Note only active auto-cancel parameters will be returned, if countdownTime is set to 0 (ie. countdownTime has been turned off), the underlying symbol and corresponding countdownTime parameter will not be returned in the response.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**underlying** | Option<**String**> | Option underlying, e.g BTCUSDT |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::OptionsGetCountdownCancelAllV1Resp**](OptionsGetCountdownCancelAllV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_margin_account_v1

> models::OptionsGetMarginAccountV1Resp options_get_margin_account_v1(timestamp, recv_window)
Option Margin Account Information (USER_DATA)

Get current account information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::OptionsGetMarginAccountV1Resp**](OptionsGetMarginAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## options_get_mmp_v1

> models::OptionsGetMmpV1Resp options_get_mmp_v1(timestamp, underlying, recv_window)
Get Market Maker Protection Config (TRADE)

Get config for MMP.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**underlying** | Option<**String**> | underlying, e.g BTCUSDT |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::OptionsGetMmpV1Resp**](OptionsGetMmpV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

