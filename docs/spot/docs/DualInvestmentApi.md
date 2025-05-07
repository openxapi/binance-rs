# \DualInvestmentApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_dci_product_auto_compound_edit_status_v1**](DualInvestmentApi.md#create_dci_product_auto_compound_edit_status_v1) | **POST** /sapi/v1/dci/product/auto_compound/edit-status | Change Auto-Compound status(USER_DATA)
[**create_dci_product_subscribe_v1**](DualInvestmentApi.md#create_dci_product_subscribe_v1) | **POST** /sapi/v1/dci/product/subscribe | Subscribe Dual Investment products(USER_DATA)
[**get_dci_product_accounts_v1**](DualInvestmentApi.md#get_dci_product_accounts_v1) | **GET** /sapi/v1/dci/product/accounts | Check Dual Investment accounts(USER_DATA)
[**get_dci_product_list_v1**](DualInvestmentApi.md#get_dci_product_list_v1) | **GET** /sapi/v1/dci/product/list | Get Dual Investment product list
[**get_dci_product_positions_v1**](DualInvestmentApi.md#get_dci_product_positions_v1) | **GET** /sapi/v1/dci/product/positions | Get Dual Investment positions(USER_DATA)



## create_dci_product_auto_compound_edit_status_v1

> models::CreateDciProductAutoCompoundEditStatusV1Resp create_dci_product_auto_compound_edit_status_v1(position_id, timestamp, auto_compound_plan, recv_window)
Change Auto-Compound status(USER_DATA)

Change Auto-Compound status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**position_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**auto_compound_plan** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateDciProductAutoCompoundEditStatusV1Resp**](CreateDciProductAuto_compoundEditStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_dci_product_subscribe_v1

> models::CreateDciProductSubscribeV1Resp create_dci_product_subscribe_v1(auto_compound_plan, deposit_amount, id, order_id, timestamp, recv_window)
Subscribe Dual Investment products(USER_DATA)

Subscribe Dual Investment products

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**auto_compound_plan** | **String** |  | [required] |[default to ]
**deposit_amount** | **String** |  | [required] |[default to ]
**id** | **String** |  | [required] |[default to ]
**order_id** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateDciProductSubscribeV1Resp**](CreateDciProductSubscribeV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_dci_product_accounts_v1

> models::GetDciProductAccountsV1Resp get_dci_product_accounts_v1(timestamp, recv_window)
Check Dual Investment accounts(USER_DATA)

Check Dual Investment accounts

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetDciProductAccountsV1Resp**](GetDciProductAccountsV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_dci_product_list_v1

> models::GetDciProductListV1Resp get_dci_product_list_v1(option_type, exercised_coin, invest_coin, timestamp, page_size, page_index, recv_window)
Get Dual Investment product list

Get Dual Investment product list

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**option_type** | **String** | Input CALL or PUT | [required] |[default to ]
**exercised_coin** | **String** | Target exercised asset, e.g.: if you subscribe to a high sell product (call option), you should input: `optionType`:CALL,`exercisedCoin`:USDT,`investCoin`:BNB; if you subscribe to a low buy product (put option), you should input: `optionType`:PUT,`exercisedCoin`:BNB,`investCoin`:USDT | [required] |[default to ]
**invest_coin** | **String** | Asset used for subscribing, e.g.: if you subscribe to a high sell product (call option), you should input: `optionType`:CALL,`exercisedCoin`:USDT,`investCoin`:BNB; if you subscribe to a low buy product (put option), you should input: `optionType`:PUT,`exercisedCoin`:BNB,`investCoin`:USDT | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**page_size** | Option<**i64**> | Default: 10, Maximum: 100 |  |[default to 10]
**page_index** | Option<**i32**> | Default: 1 |  |[default to 1]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetDciProductListV1Resp**](GetDciProductListV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_dci_product_positions_v1

> models::GetDciProductPositionsV1Resp get_dci_product_positions_v1(timestamp, status, page_size, page_index, recv_window)
Get Dual Investment positions(USER_DATA)

Get Dual Investment positions (batch)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**status** | Option<**String**> | `PENDING`:Products are purchasing, will give results later;`PURCHASE_SUCCESS`:purchase successfully;`SETTLED`: Products are finish settling;`PURCHASE_FAIL`:fail to purchase;`REFUNDING`:refund ongoing;`REFUND_SUCCESS`:refund to spot account successfully; `SETTLING`:Products are settling. If don&#39;t fill this field, will response all the position status. |  |[default to ]
**page_size** | Option<**i64**> | Default: 10, Max:100 |  |[default to 10]
**page_index** | Option<**i32**> | Default:1 |  |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetDciProductPositionsV1Resp**](GetDciProductPositionsV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

