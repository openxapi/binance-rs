# \ApiManagementApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**subaccount_create_sub_account_sub_account_api_ip_restriction_v2**](ApiManagementApi.md#subaccount_create_sub_account_sub_account_api_ip_restriction_v2) | **POST** /sapi/v2/sub-account/subAccountApi/ipRestriction | Add IP Restriction for Sub-Account API key(For Master Account)
[**subaccount_delete_sub_account_sub_account_api_ip_restriction_ip_list_v1**](ApiManagementApi.md#subaccount_delete_sub_account_sub_account_api_ip_restriction_ip_list_v1) | **DELETE** /sapi/v1/sub-account/subAccountApi/ipRestriction/ipList | Delete IP List For a Sub-account API Key(For Master Account)
[**subaccount_get_sub_account_sub_account_api_ip_restriction_v1**](ApiManagementApi.md#subaccount_get_sub_account_sub_account_api_ip_restriction_v1) | **GET** /sapi/v1/sub-account/subAccountApi/ipRestriction | Get IP Restriction for a Sub-account API Key(For Master Account)



## subaccount_create_sub_account_sub_account_api_ip_restriction_v2

> models::SubaccountCreateSubAccountSubAccountApiIpRestrictionV2Resp subaccount_create_sub_account_sub_account_api_ip_restriction_v2(email, status, sub_account_api_key, timestamp, ip_address, recv_window)
Add IP Restriction for Sub-Account API key(For Master Account)

Add IP Restriction for Sub-Account API key

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** |  | [required] |[default to ]
**status** | **String** |  | [required] |[default to ]
**sub_account_api_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**ip_address** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountCreateSubAccountSubAccountApiIpRestrictionV2Resp**](SubaccountCreateSubAccountSubAccountApiIpRestrictionV2Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_delete_sub_account_sub_account_api_ip_restriction_ip_list_v1

> models::SubaccountDeleteSubAccountSubAccountApiIpRestrictionIpListV1Resp subaccount_delete_sub_account_sub_account_api_ip_restriction_ip_list_v1(email, sub_account_api_key, timestamp, ip_address, recv_window)
Delete IP List For a Sub-account API Key(For Master Account)

Delete IP List For a Sub-account API Key

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/api-management/Delete-IP-List-For-a-Sub-account-API-Key#email-address\">Sub-account email</a> | [required] |[default to ]
**sub_account_api_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**ip_address** | Option<**String**> | Can be added in batches, separated by commas |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountDeleteSubAccountSubAccountApiIpRestrictionIpListV1Resp**](SubaccountDeleteSubAccountSubAccountApiIpRestrictionIpListV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## subaccount_get_sub_account_sub_account_api_ip_restriction_v1

> models::SubaccountGetSubAccountSubAccountApiIpRestrictionV1Resp subaccount_get_sub_account_sub_account_api_ip_restriction_v1(email, sub_account_api_key, timestamp, recv_window)
Get IP Restriction for a Sub-account API Key(For Master Account)

Get IP Restriction for a Sub-account API Key

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**email** | **String** | <a href=\"/docs/sub_account/api-management#email-address\">Sub-account email</a> | [required] |[default to ]
**sub_account_api_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::SubaccountGetSubAccountSubAccountApiIpRestrictionV1Resp**](SubaccountGetSubAccountSubAccountApiIpRestrictionV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

