# \MarketDataApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**pmarginpro_get_portfolio_asset_index_price_v1**](MarketDataApi.md#pmarginpro_get_portfolio_asset_index_price_v1) | **GET** /sapi/v1/portfolio/asset-index-price | Query Portfolio Margin Asset Index Price (MARKET_DATA)
[**pmarginpro_get_portfolio_collateral_rate_v1**](MarketDataApi.md#pmarginpro_get_portfolio_collateral_rate_v1) | **GET** /sapi/v1/portfolio/collateralRate | Portfolio Margin Collateral Rate(MARKET_DATA)
[**pmarginpro_get_portfolio_collateral_rate_v2**](MarketDataApi.md#pmarginpro_get_portfolio_collateral_rate_v2) | **GET** /sapi/v2/portfolio/collateralRate | Portfolio Margin Pro Tiered Collateral Rate(USER_DATA)
[**pmarginpro_get_portfolio_margin_asset_leverage_v1**](MarketDataApi.md#pmarginpro_get_portfolio_margin_asset_leverage_v1) | **GET** /sapi/v1/portfolio/margin-asset-leverage | Get Portfolio Margin Asset Leverage(USER_DATA)



## pmarginpro_get_portfolio_asset_index_price_v1

> Vec<models::PmarginproGetPortfolioAssetIndexPriceV1RespItem> pmarginpro_get_portfolio_asset_index_price_v1(asset)
Query Portfolio Margin Asset Index Price (MARKET_DATA)

Query Portfolio Margin Asset Index Price

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::PmarginproGetPortfolioAssetIndexPriceV1RespItem>**](PmarginproGetPortfolioAssetIndexPriceV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmarginpro_get_portfolio_collateral_rate_v1

> Vec<models::PmarginproGetPortfolioCollateralRateV1RespItem> pmarginpro_get_portfolio_collateral_rate_v1()
Portfolio Margin Collateral Rate(MARKET_DATA)

Portfolio Margin Collateral Rate

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::PmarginproGetPortfolioCollateralRateV1RespItem>**](PmarginproGetPortfolioCollateralRateV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmarginpro_get_portfolio_collateral_rate_v2

> Vec<models::PmarginproGetPortfolioCollateralRateV2RespItem> pmarginpro_get_portfolio_collateral_rate_v2(timestamp, recv_window)
Portfolio Margin Pro Tiered Collateral Rate(USER_DATA)

Portfolio Margin PRO Tiered Collateral Rate

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginproGetPortfolioCollateralRateV2RespItem>**](PmarginproGetPortfolioCollateralRateV2RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmarginpro_get_portfolio_margin_asset_leverage_v1

> Vec<models::PmarginproGetPortfolioMarginAssetLeverageV1RespItem> pmarginpro_get_portfolio_margin_asset_leverage_v1()
Get Portfolio Margin Asset Leverage(USER_DATA)

Get Portfolio Margin Asset Leverage

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::PmarginproGetPortfolioMarginAssetLeverageV1RespItem>**](PmarginproGetPortfolioMarginAssetLeverageV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

