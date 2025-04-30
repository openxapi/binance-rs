# \MarketDataApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**margin_get_margin_all_assets_v1**](MarketDataApi.md#margin_get_margin_all_assets_v1) | **GET** /sapi/v1/margin/allAssets | Get All Margin Assets (MARKET_DATA)
[**margin_get_margin_all_pairs_v1**](MarketDataApi.md#margin_get_margin_all_pairs_v1) | **GET** /sapi/v1/margin/allPairs | Get All Cross Margin Pairs (MARKET_DATA)
[**margin_get_margin_available_inventory_v1**](MarketDataApi.md#margin_get_margin_available_inventory_v1) | **GET** /sapi/v1/margin/available-inventory | Query Margin Available Inventory(USER_DATA)
[**margin_get_margin_cross_margin_collateral_ratio_v1**](MarketDataApi.md#margin_get_margin_cross_margin_collateral_ratio_v1) | **GET** /sapi/v1/margin/crossMarginCollateralRatio | Cross margin collateral ratio (MARKET_DATA)
[**margin_get_margin_delist_schedule_v1**](MarketDataApi.md#margin_get_margin_delist_schedule_v1) | **GET** /sapi/v1/margin/delist-schedule | Get Delist Schedule (MARKET_DATA)
[**margin_get_margin_isolated_all_pairs_v1**](MarketDataApi.md#margin_get_margin_isolated_all_pairs_v1) | **GET** /sapi/v1/margin/isolated/allPairs | Get All Isolated Margin Symbol(MARKET_DATA)
[**margin_get_margin_isolated_margin_tier_v1**](MarketDataApi.md#margin_get_margin_isolated_margin_tier_v1) | **GET** /sapi/v1/margin/isolatedMarginTier | Query Isolated Margin Tier Data (USER_DATA)
[**margin_get_margin_leverage_bracket_v1**](MarketDataApi.md#margin_get_margin_leverage_bracket_v1) | **GET** /sapi/v1/margin/leverageBracket | Query Liability Coin Leverage Bracket in Cross Margin Pro Mode(MARKET_DATA)
[**margin_get_margin_price_index_v1**](MarketDataApi.md#margin_get_margin_price_index_v1) | **GET** /sapi/v1/margin/priceIndex | Query Margin PriceIndex (MARKET_DATA)



## margin_get_margin_all_assets_v1

> Vec<models::MarginGetMarginAllAssetsV1RespItem> margin_get_margin_all_assets_v1(asset)
Get All Margin Assets (MARKET_DATA)

Get All Margin Assets.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::MarginGetMarginAllAssetsV1RespItem>**](MarginGetMarginAllAssetsV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_all_pairs_v1

> Vec<models::MarginGetMarginAllPairsV1RespItem> margin_get_margin_all_pairs_v1(symbol)
Get All Cross Margin Pairs (MARKET_DATA)

Get All Cross Margin Pairs

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::MarginGetMarginAllPairsV1RespItem>**](MarginGetMarginAllPairsV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_available_inventory_v1

> models::MarginGetMarginAvailableInventoryV1Resp margin_get_margin_available_inventory_v1(r#type)
Query Margin Available Inventory(USER_DATA)

Margin available Inventory query

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**r#type** | **String** | MARGIN,ISOLATED | [required] |[default to ]

### Return type

[**models::MarginGetMarginAvailableInventoryV1Resp**](MarginGetMarginAvailableInventoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_cross_margin_collateral_ratio_v1

> Vec<models::MarginGetMarginCrossMarginCollateralRatioV1RespItem> margin_get_margin_cross_margin_collateral_ratio_v1()
Cross margin collateral ratio (MARKET_DATA)

Cross margin collateral ratio

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::MarginGetMarginCrossMarginCollateralRatioV1RespItem>**](MarginGetMarginCrossMarginCollateralRatioV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_delist_schedule_v1

> Vec<models::MarginGetMarginDelistScheduleV1RespItem> margin_get_margin_delist_schedule_v1(timestamp, recv_window)
Get Delist Schedule (MARKET_DATA)

Get tokens or symbols delist schedule for cross margin and isolated margin

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::MarginGetMarginDelistScheduleV1RespItem>**](MarginGetMarginDelistScheduleV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_isolated_all_pairs_v1

> Vec<models::MarginGetMarginIsolatedAllPairsV1RespItem> margin_get_margin_isolated_all_pairs_v1(timestamp, symbol, recv_window)
Get All Isolated Margin Symbol(MARKET_DATA)

Get All Isolated Margin Symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | No more than 60000 |  |

### Return type

[**Vec<models::MarginGetMarginIsolatedAllPairsV1RespItem>**](MarginGetMarginIsolatedAllPairsV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_isolated_margin_tier_v1

> Vec<models::MarginGetMarginIsolatedMarginTierV1RespItem> margin_get_margin_isolated_margin_tier_v1(symbol, timestamp, tier, recv_window)
Query Isolated Margin Tier Data (USER_DATA)

Get isolated margin tier data collection with any tier as https://www.binance.com/en/margin-data

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**tier** | Option<**i32**> | All margin tier data will be returned if tier is omitted |  |
**recv_window** | Option<**i64**> | No more than `60000` |  |

### Return type

[**Vec<models::MarginGetMarginIsolatedMarginTierV1RespItem>**](MarginGetMarginIsolatedMarginTierV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_leverage_bracket_v1

> Vec<models::MarginGetMarginLeverageBracketV1RespItem> margin_get_margin_leverage_bracket_v1()
Query Liability Coin Leverage Bracket in Cross Margin Pro Mode(MARKET_DATA)

Liability Coin Leverage Bracket in Cross Margin Pro Mode

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::MarginGetMarginLeverageBracketV1RespItem>**](MarginGetMarginLeverageBracketV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_price_index_v1

> models::MarginGetMarginPriceIndexV1Resp margin_get_margin_price_index_v1(symbol)
Query Margin PriceIndex (MARKET_DATA)

Query Margin PriceIndex

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::MarginGetMarginPriceIndexV1Resp**](MarginGetMarginPriceIndexV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

