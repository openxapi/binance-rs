# \MarginTradingApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_margin_api_key_v1**](MarginTradingApi.md#create_margin_api_key_v1) | **POST** /sapi/v1/margin/apiKey | Create Special Key(Low-Latency Trading)(TRADE)
[**create_margin_borrow_repay_v1**](MarginTradingApi.md#create_margin_borrow_repay_v1) | **POST** /sapi/v1/margin/borrow-repay | Margin account borrow/repay(MARGIN)
[**create_margin_exchange_small_liability_v1**](MarginTradingApi.md#create_margin_exchange_small_liability_v1) | **POST** /sapi/v1/margin/exchange-small-liability | Small Liability Exchange (MARGIN)
[**create_margin_isolated_account_v1**](MarginTradingApi.md#create_margin_isolated_account_v1) | **POST** /sapi/v1/margin/isolated/account | Enable Isolated Margin Account (TRADE)
[**create_margin_listen_key_v1**](MarginTradingApi.md#create_margin_listen_key_v1) | **POST** /sapi/v1/margin/listen-key | Start User Data Stream (USER_STREAM)
[**create_margin_manual_liquidation_v1**](MarginTradingApi.md#create_margin_manual_liquidation_v1) | **POST** /sapi/v1/margin/manual-liquidation | Margin Manual Liquidation(MARGIN)
[**create_margin_max_leverage_v1**](MarginTradingApi.md#create_margin_max_leverage_v1) | **POST** /sapi/v1/margin/max-leverage | Adjust cross margin max leverage (USER_DATA)
[**create_margin_order_oco_v1**](MarginTradingApi.md#create_margin_order_oco_v1) | **POST** /sapi/v1/margin/order/oco | Margin Account New OCO (TRADE)
[**create_margin_order_oto_v1**](MarginTradingApi.md#create_margin_order_oto_v1) | **POST** /sapi/v1/margin/order/oto | Margin Account New OTO (TRADE)
[**create_margin_order_otoco_v1**](MarginTradingApi.md#create_margin_order_otoco_v1) | **POST** /sapi/v1/margin/order/otoco | Margin Account New OTOCO (TRADE)
[**create_margin_order_v1**](MarginTradingApi.md#create_margin_order_v1) | **POST** /sapi/v1/margin/order | Margin Account New Order (TRADE)
[**create_user_data_stream_isolated_v1**](MarginTradingApi.md#create_user_data_stream_isolated_v1) | **POST** /sapi/v1/userDataStream/isolated | Start Isolated Margin User Data Stream (USER_STREAM)
[**create_user_data_stream_v1**](MarginTradingApi.md#create_user_data_stream_v1) | **POST** /sapi/v1/userDataStream | Start Margin User Data Stream (USER_STREAM)
[**delete_margin_api_key_v1**](MarginTradingApi.md#delete_margin_api_key_v1) | **DELETE** /sapi/v1/margin/apiKey | Delete Special Key(Low-Latency Trading)(TRADE)
[**delete_margin_isolated_account_v1**](MarginTradingApi.md#delete_margin_isolated_account_v1) | **DELETE** /sapi/v1/margin/isolated/account | Disable Isolated Margin Account (TRADE)
[**delete_margin_listen_key_v1**](MarginTradingApi.md#delete_margin_listen_key_v1) | **DELETE** /sapi/v1/margin/listen-key | Close User Data Stream (USER_STREAM)
[**delete_margin_open_orders_v1**](MarginTradingApi.md#delete_margin_open_orders_v1) | **DELETE** /sapi/v1/margin/openOrders | Margin Account Cancel all Open Orders on a Symbol (TRADE)
[**delete_margin_order_list_v1**](MarginTradingApi.md#delete_margin_order_list_v1) | **DELETE** /sapi/v1/margin/orderList | Margin Account Cancel OCO (TRADE)
[**delete_margin_order_v1**](MarginTradingApi.md#delete_margin_order_v1) | **DELETE** /sapi/v1/margin/order | Margin Account Cancel Order (TRADE)
[**delete_user_data_stream_isolated_v1**](MarginTradingApi.md#delete_user_data_stream_isolated_v1) | **DELETE** /sapi/v1/userDataStream/isolated | Close Isolated Margin User Data Stream (USER_STREAM)
[**delete_user_data_stream_v1**](MarginTradingApi.md#delete_user_data_stream_v1) | **DELETE** /sapi/v1/userDataStream | Close Margin User Data Stream (USER_STREAM)
[**get_bnb_burn_v1**](MarginTradingApi.md#get_bnb_burn_v1) | **GET** /sapi/v1/bnbBurn | Get BNB Burn Status (USER_DATA)
[**get_margin_account_v1**](MarginTradingApi.md#get_margin_account_v1) | **GET** /sapi/v1/margin/account | Query Cross Margin Account Details (USER_DATA)
[**get_margin_all_assets_v1**](MarginTradingApi.md#get_margin_all_assets_v1) | **GET** /sapi/v1/margin/allAssets | Get All Margin Assets (MARKET_DATA)
[**get_margin_all_order_list_v1**](MarginTradingApi.md#get_margin_all_order_list_v1) | **GET** /sapi/v1/margin/allOrderList | Query Margin Account's all OCO (USER_DATA)
[**get_margin_all_orders_v1**](MarginTradingApi.md#get_margin_all_orders_v1) | **GET** /sapi/v1/margin/allOrders | Query Margin Account's All Orders (USER_DATA)
[**get_margin_all_pairs_v1**](MarginTradingApi.md#get_margin_all_pairs_v1) | **GET** /sapi/v1/margin/allPairs | Get All Cross Margin Pairs (MARKET_DATA)
[**get_margin_api_key_list_v1**](MarginTradingApi.md#get_margin_api_key_list_v1) | **GET** /sapi/v1/margin/api-key-list | Query Special key List(Low Latency Trading)(TRADE)
[**get_margin_api_key_v1**](MarginTradingApi.md#get_margin_api_key_v1) | **GET** /sapi/v1/margin/apiKey | Query Special key(Low Latency Trading)(TRADE)
[**get_margin_available_inventory_v1**](MarginTradingApi.md#get_margin_available_inventory_v1) | **GET** /sapi/v1/margin/available-inventory | Query Margin Available Inventory(USER_DATA)
[**get_margin_borrow_repay_v1**](MarginTradingApi.md#get_margin_borrow_repay_v1) | **GET** /sapi/v1/margin/borrow-repay | Query borrow/repay records in Margin account(USER_DATA)
[**get_margin_capital_flow_v1**](MarginTradingApi.md#get_margin_capital_flow_v1) | **GET** /sapi/v1/margin/capital-flow | Query Cross Isolated Margin Capital Flow (USER_DATA)
[**get_margin_cross_margin_collateral_ratio_v1**](MarginTradingApi.md#get_margin_cross_margin_collateral_ratio_v1) | **GET** /sapi/v1/margin/crossMarginCollateralRatio | Cross margin collateral ratio (MARKET_DATA)
[**get_margin_cross_margin_data_v1**](MarginTradingApi.md#get_margin_cross_margin_data_v1) | **GET** /sapi/v1/margin/crossMarginData | Query Cross Margin Fee Data (USER_DATA)
[**get_margin_delist_schedule_v1**](MarginTradingApi.md#get_margin_delist_schedule_v1) | **GET** /sapi/v1/margin/delist-schedule | Get Delist Schedule (MARKET_DATA)
[**get_margin_exchange_small_liability_history_v1**](MarginTradingApi.md#get_margin_exchange_small_liability_history_v1) | **GET** /sapi/v1/margin/exchange-small-liability-history | Get Small Liability Exchange History (USER_DATA)
[**get_margin_exchange_small_liability_v1**](MarginTradingApi.md#get_margin_exchange_small_liability_v1) | **GET** /sapi/v1/margin/exchange-small-liability | Get Small Liability Exchange Coin List (USER_DATA)
[**get_margin_force_liquidation_rec_v1**](MarginTradingApi.md#get_margin_force_liquidation_rec_v1) | **GET** /sapi/v1/margin/forceLiquidationRec | Get Force Liquidation Record (USER_DATA)
[**get_margin_interest_history_v1**](MarginTradingApi.md#get_margin_interest_history_v1) | **GET** /sapi/v1/margin/interestHistory | Get Interest History (USER_DATA)
[**get_margin_interest_rate_history_v1**](MarginTradingApi.md#get_margin_interest_rate_history_v1) | **GET** /sapi/v1/margin/interestRateHistory | Query Margin Interest Rate History (USER_DATA)
[**get_margin_isolated_account_limit_v1**](MarginTradingApi.md#get_margin_isolated_account_limit_v1) | **GET** /sapi/v1/margin/isolated/accountLimit | Query Enabled Isolated Margin Account Limit (USER_DATA)
[**get_margin_isolated_account_v1**](MarginTradingApi.md#get_margin_isolated_account_v1) | **GET** /sapi/v1/margin/isolated/account | Query Isolated Margin Account Info (USER_DATA)
[**get_margin_isolated_all_pairs_v1**](MarginTradingApi.md#get_margin_isolated_all_pairs_v1) | **GET** /sapi/v1/margin/isolated/allPairs | Get All Isolated Margin Symbol(MARKET_DATA)
[**get_margin_isolated_margin_data_v1**](MarginTradingApi.md#get_margin_isolated_margin_data_v1) | **GET** /sapi/v1/margin/isolatedMarginData | Query Isolated Margin Fee Data (USER_DATA)
[**get_margin_isolated_margin_tier_v1**](MarginTradingApi.md#get_margin_isolated_margin_tier_v1) | **GET** /sapi/v1/margin/isolatedMarginTier | Query Isolated Margin Tier Data (USER_DATA)
[**get_margin_leverage_bracket_v1**](MarginTradingApi.md#get_margin_leverage_bracket_v1) | **GET** /sapi/v1/margin/leverageBracket | Query Liability Coin Leverage Bracket in Cross Margin Pro Mode(MARKET_DATA)
[**get_margin_max_borrowable_v1**](MarginTradingApi.md#get_margin_max_borrowable_v1) | **GET** /sapi/v1/margin/maxBorrowable | Query Max Borrow (USER_DATA)
[**get_margin_max_transferable_v1**](MarginTradingApi.md#get_margin_max_transferable_v1) | **GET** /sapi/v1/margin/maxTransferable | Query Max Transfer-Out Amount (USER_DATA)
[**get_margin_my_trades_v1**](MarginTradingApi.md#get_margin_my_trades_v1) | **GET** /sapi/v1/margin/myTrades | Query Margin Account's Trade List (USER_DATA)
[**get_margin_next_hourly_interest_rate_v1**](MarginTradingApi.md#get_margin_next_hourly_interest_rate_v1) | **GET** /sapi/v1/margin/next-hourly-interest-rate | Get future hourly interest rate (USER_DATA)
[**get_margin_open_order_list_v1**](MarginTradingApi.md#get_margin_open_order_list_v1) | **GET** /sapi/v1/margin/openOrderList | Query Margin Account's Open OCO (USER_DATA)
[**get_margin_open_orders_v1**](MarginTradingApi.md#get_margin_open_orders_v1) | **GET** /sapi/v1/margin/openOrders | Query Margin Account's Open Orders (USER_DATA)
[**get_margin_order_list_v1**](MarginTradingApi.md#get_margin_order_list_v1) | **GET** /sapi/v1/margin/orderList | Query Margin Account's OCO (USER_DATA)
[**get_margin_order_v1**](MarginTradingApi.md#get_margin_order_v1) | **GET** /sapi/v1/margin/order | Query Margin Account's Order (USER_DATA)
[**get_margin_price_index_v1**](MarginTradingApi.md#get_margin_price_index_v1) | **GET** /sapi/v1/margin/priceIndex | Query Margin PriceIndex (MARKET_DATA)
[**get_margin_rate_limit_order_v1**](MarginTradingApi.md#get_margin_rate_limit_order_v1) | **GET** /sapi/v1/margin/rateLimit/order | Query Current Margin Order Count Usage (TRADE)
[**get_margin_trade_coeff_v1**](MarginTradingApi.md#get_margin_trade_coeff_v1) | **GET** /sapi/v1/margin/tradeCoeff | Get Summary of Margin account (USER_DATA)
[**get_margin_transfer_v1**](MarginTradingApi.md#get_margin_transfer_v1) | **GET** /sapi/v1/margin/transfer | Get Cross Margin Transfer History (USER_DATA)
[**update_margin_api_key_ip_v1**](MarginTradingApi.md#update_margin_api_key_ip_v1) | **PUT** /sapi/v1/margin/apiKey/ip | Edit ip for Special Key(Low-Latency Trading)(TRADE)
[**update_margin_listen_key_v1**](MarginTradingApi.md#update_margin_listen_key_v1) | **PUT** /sapi/v1/margin/listen-key | Keepalive User Data Stream (USER_STREAM)
[**update_user_data_stream_isolated_v1**](MarginTradingApi.md#update_user_data_stream_isolated_v1) | **PUT** /sapi/v1/userDataStream/isolated | Keepalive Isolated Margin User Data Stream (USER_STREAM)
[**update_user_data_stream_v1**](MarginTradingApi.md#update_user_data_stream_v1) | **PUT** /sapi/v1/userDataStream | Keepalive Margin User Data Stream (USER_STREAM)



## create_margin_api_key_v1

> models::CreateMarginApiKeyV1Resp create_margin_api_key_v1(api_name, timestamp, ip, permission_mode, public_key, recv_window, symbol)
Create Special Key(Low-Latency Trading)(TRADE)

**Binance Margin offers low-latency trading through a special key, available exclusively to users with VIP level 4 or higher. **

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**api_name** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**ip** | Option<**String**> |  |  |[default to ]
**permission_mode** | Option<**String**> |  |  |[default to ]
**public_key** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateMarginApiKeyV1Resp**](CreateMarginApiKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_borrow_repay_v1

> models::CreateMarginBorrowRepayV1Resp create_margin_borrow_repay_v1(amount, asset, is_isolated, symbol, timestamp, r#type, recv_window)
Margin account borrow/repay(MARGIN)

Margin account borrow/repay(MARGIN)

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**is_isolated** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateMarginBorrowRepayV1Resp**](CreateMarginBorrowRepayV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_exchange_small_liability_v1

> models::MarginCreateMarginExchangeSmallLiabilityV1Resp create_margin_exchange_small_liability_v1(asset_names, timestamp, recv_window)
Small Liability Exchange (MARGIN)

Small Liability Exchange

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset_names** | [**Vec<String>**](String.md) |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::MarginCreateMarginExchangeSmallLiabilityV1Resp**](MarginCreateMarginExchangeSmallLiabilityV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_isolated_account_v1

> models::CreateMarginIsolatedAccountV1Resp create_margin_isolated_account_v1(symbol, timestamp, recv_window)
Enable Isolated Margin Account (TRADE)

Enable isolated margin account for a specific symbol(Only supports activation of previously disabled accounts).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateMarginIsolatedAccountV1Resp**](CreateMarginIsolatedAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_listen_key_v1

> models::CreateMarginListenKeyV1Resp create_margin_listen_key_v1()
Start User Data Stream (USER_STREAM)

Start a new user data stream.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::CreateMarginListenKeyV1Resp**](CreateMarginListenKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_manual_liquidation_v1

> models::CreateMarginManualLiquidationV1Resp create_margin_manual_liquidation_v1(timestamp, r#type, recv_window, symbol)
Margin Manual Liquidation(MARGIN)

Margin Manual Liquidation

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |
**symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateMarginManualLiquidationV1Resp**](CreateMarginManualLiquidationV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_max_leverage_v1

> models::CreateMarginMaxLeverageV1Resp create_margin_max_leverage_v1(max_leverage)
Adjust cross margin max leverage (USER_DATA)

Adjust cross margin max leverage

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**max_leverage** | **i32** |  | [required] |

### Return type

[**models::CreateMarginMaxLeverageV1Resp**](CreateMarginMaxLeverageV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_order_oco_v1

> models::CreateMarginOrderOcoV1Resp create_margin_order_oco_v1(price, quantity, side, stop_price, symbol, timestamp, auto_repay_at_cancel, is_isolated, limit_client_order_id, limit_iceberg_qty, list_client_order_id, new_order_resp_type, recv_window, self_trade_prevention_mode, side_effect_type, stop_client_order_id, stop_iceberg_qty, stop_limit_price, stop_limit_time_in_force)
Margin Account New OCO (TRADE)

Send in a new OCO for a margin account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**price** | **String** |  | [required] |[default to ]
**quantity** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**stop_price** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**auto_repay_at_cancel** | Option<**bool**> |  |  |
**is_isolated** | Option<**String**> |  |  |[default to ]
**limit_client_order_id** | Option<**String**> |  |  |[default to ]
**limit_iceberg_qty** | Option<**String**> |  |  |[default to ]
**list_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**side_effect_type** | Option<**String**> |  |  |[default to ]
**stop_client_order_id** | Option<**String**> |  |  |[default to ]
**stop_iceberg_qty** | Option<**String**> |  |  |[default to ]
**stop_limit_price** | Option<**String**> |  |  |[default to ]
**stop_limit_time_in_force** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateMarginOrderOcoV1Resp**](CreateMarginOrderOcoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_order_oto_v1

> models::CreateMarginOrderOtoV1Resp create_margin_order_oto_v1(pending_quantity, pending_side, pending_type, symbol, working_iceberg_qty, working_price, working_quantity, working_side, working_type, auto_repay_at_cancel, is_isolated, list_client_order_id, new_order_resp_type, pending_client_order_id, pending_iceberg_qty, pending_price, pending_stop_price, pending_time_in_force, pending_trailing_delta, self_trade_prevention_mode, side_effect_type, working_client_order_id, working_time_in_force)
Margin Account New OTO (TRADE)

Post a new OTO order for margin account:

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pending_quantity** | **String** |  | [required] |[default to ]
**pending_side** | **String** |  | [required] |[default to ]
**pending_type** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**working_iceberg_qty** | **String** |  | [required] |[default to ]
**working_price** | **String** |  | [required] |[default to ]
**working_quantity** | **String** |  | [required] |[default to ]
**working_side** | **String** |  | [required] |[default to ]
**working_type** | **String** |  | [required] |[default to ]
**auto_repay_at_cancel** | Option<**bool**> |  |  |
**is_isolated** | Option<**String**> |  |  |[default to ]
**list_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**pending_client_order_id** | Option<**String**> |  |  |[default to ]
**pending_iceberg_qty** | Option<**String**> |  |  |[default to ]
**pending_price** | Option<**String**> |  |  |[default to ]
**pending_stop_price** | Option<**String**> |  |  |[default to ]
**pending_time_in_force** | Option<**String**> |  |  |[default to ]
**pending_trailing_delta** | Option<**String**> |  |  |[default to ]
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**side_effect_type** | Option<**String**> |  |  |[default to ]
**working_client_order_id** | Option<**String**> |  |  |[default to ]
**working_time_in_force** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateMarginOrderOtoV1Resp**](CreateMarginOrderOtoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_order_otoco_v1

> models::CreateMarginOrderOtocoV1Resp create_margin_order_otoco_v1(pending_above_type, pending_quantity, pending_side, symbol, working_price, working_quantity, working_side, working_type, auto_repay_at_cancel, is_isolated, list_client_order_id, new_order_resp_type, pending_above_client_order_id, pending_above_iceberg_qty, pending_above_price, pending_above_stop_price, pending_above_time_in_force, pending_above_trailing_delta, pending_below_client_order_id, pending_below_iceberg_qty, pending_below_price, pending_below_stop_price, pending_below_time_in_force, pending_below_trailing_delta, pending_below_type, self_trade_prevention_mode, side_effect_type, working_client_order_id, working_iceberg_qty, working_time_in_force)
Margin Account New OTOCO (TRADE)

Post a new OTOCO order for margin account：

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pending_above_type** | **String** |  | [required] |[default to ]
**pending_quantity** | **String** |  | [required] |[default to ]
**pending_side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**working_price** | **String** |  | [required] |[default to ]
**working_quantity** | **String** |  | [required] |[default to ]
**working_side** | **String** |  | [required] |[default to ]
**working_type** | **String** |  | [required] |[default to ]
**auto_repay_at_cancel** | Option<**bool**> |  |  |
**is_isolated** | Option<**String**> |  |  |[default to ]
**list_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**pending_above_client_order_id** | Option<**String**> |  |  |[default to ]
**pending_above_iceberg_qty** | Option<**String**> |  |  |[default to ]
**pending_above_price** | Option<**String**> |  |  |[default to ]
**pending_above_stop_price** | Option<**String**> |  |  |[default to ]
**pending_above_time_in_force** | Option<**String**> |  |  |[default to ]
**pending_above_trailing_delta** | Option<**String**> |  |  |[default to ]
**pending_below_client_order_id** | Option<**String**> |  |  |[default to ]
**pending_below_iceberg_qty** | Option<**String**> |  |  |[default to ]
**pending_below_price** | Option<**String**> |  |  |[default to ]
**pending_below_stop_price** | Option<**String**> |  |  |[default to ]
**pending_below_time_in_force** | Option<**String**> |  |  |[default to ]
**pending_below_trailing_delta** | Option<**String**> |  |  |[default to ]
**pending_below_type** | Option<**String**> |  |  |[default to ]
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**side_effect_type** | Option<**String**> |  |  |[default to ]
**working_client_order_id** | Option<**String**> |  |  |[default to ]
**working_iceberg_qty** | Option<**String**> |  |  |[default to ]
**working_time_in_force** | Option<**String**> |  |  |[default to ]

### Return type

[**models::CreateMarginOrderOtocoV1Resp**](CreateMarginOrderOtocoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_order_v1

> models::MarginCreateMarginOrderV1Resp create_margin_order_v1(side, symbol, timestamp, r#type, auto_repay_at_cancel, iceberg_qty, is_isolated, new_client_order_id, new_order_resp_type, price, quantity, quote_order_qty, recv_window, self_trade_prevention_mode, side_effect_type, stop_price, time_in_force)
Margin Account New Order (TRADE)

Post a new order for margin account.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**auto_repay_at_cancel** | Option<**bool**> |  |  |
**iceberg_qty** | Option<**String**> |  |  |[default to ]
**is_isolated** | Option<**String**> |  |  |[default to ]
**new_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**quantity** | Option<**String**> |  |  |[default to ]
**quote_order_qty** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**side_effect_type** | Option<**String**> |  |  |[default to ]
**stop_price** | Option<**String**> |  |  |[default to ]
**time_in_force** | Option<**String**> |  |  |[default to ]

### Return type

[**models::MarginCreateMarginOrderV1Resp**](MarginCreateMarginOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_user_data_stream_isolated_v1

> models::CreateUserDataStreamIsolatedV1Resp create_user_data_stream_isolated_v1(symbol)
Start Isolated Margin User Data Stream (USER_STREAM)

Start a new isolated margin user data stream. The stream will close after 60 minutes unless a keepalive is sent. If the account has an active listenKey, that listenKey will be returned and its validity will be extended for 60 minutes.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::CreateUserDataStreamIsolatedV1Resp**](CreateUserDataStreamIsolatedV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_user_data_stream_v1

> models::CreateUserDataStreamV1Resp create_user_data_stream_v1()
Start Margin User Data Stream (USER_STREAM)

Start a new margin user data stream. The stream will close after 60 minutes unless a keepalive is sent. If the account has an active listenKey, that listenKey will be returned and its validity will be extended for 60 minutes.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::CreateUserDataStreamV1Resp**](CreateUserDataStreamV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_margin_api_key_v1

> serde_json::Value delete_margin_api_key_v1(timestamp, api_key, api_name, symbol, recv_window)
Delete Special Key(Low-Latency Trading)(TRADE)

This only applies to Special Key for Low Latency Trading.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**api_key** | Option<**String**> |  |  |[default to ]
**api_name** | Option<**String**> |  |  |[default to ]
**symbol** | Option<**String**> | isolated margin pair |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_margin_isolated_account_v1

> models::DeleteMarginIsolatedAccountV1Resp delete_margin_isolated_account_v1(symbol, timestamp, recv_window)
Disable Isolated Margin Account (TRADE)

Disable isolated margin account for a specific symbol. Each trading pair can only be deactivated once every 24 hours.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | No more than 60000 |  |

### Return type

[**models::DeleteMarginIsolatedAccountV1Resp**](DeleteMarginIsolatedAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_margin_listen_key_v1

> serde_json::Value delete_margin_listen_key_v1()
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


## delete_margin_open_orders_v1

> Vec<models::DeleteMarginOpenOrdersV1RespItem> delete_margin_open_orders_v1(symbol, timestamp, is_isolated, recv_window)
Margin Account Cancel all Open Orders on a Symbol (TRADE)

Cancels all active orders on a symbol for margin account. This includes OCO orders.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**is_isolated** | Option<**String**> | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34;，default &#34;FALSE&#34; |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::DeleteMarginOpenOrdersV1RespItem>**](DeleteMarginOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_margin_order_list_v1

> models::DeleteMarginOrderListV1Resp delete_margin_order_list_v1(symbol, timestamp, is_isolated, order_list_id, list_client_order_id, new_client_order_id, recv_window)
Margin Account Cancel OCO (TRADE)

Cancel an entire Order List for a margin account.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**is_isolated** | Option<**String**> | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34;，default &#34;FALSE&#34; |  |[default to ]
**order_list_id** | Option<**i64**> | Either `orderListId` or `listClientOrderId` must be provided |  |
**list_client_order_id** | Option<**String**> | Either `orderListId` or `listClientOrderId` must be provided |  |[default to ]
**new_client_order_id** | Option<**String**> | Used to uniquely identify this cancel. Automatically generated by default |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::DeleteMarginOrderListV1Resp**](DeleteMarginOrderListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_margin_order_v1

> models::DeleteMarginOrderV1Resp delete_margin_order_v1(symbol, timestamp, is_isolated, order_id, orig_client_order_id, new_client_order_id, recv_window)
Margin Account Cancel Order (TRADE)

Cancel an active order for margin account.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**is_isolated** | Option<**String**> | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34;，default &#34;FALSE&#34; |  |[default to ]
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**new_client_order_id** | Option<**String**> | Used to uniquely identify this cancel. Automatically generated by default. |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::DeleteMarginOrderV1Resp**](DeleteMarginOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_user_data_stream_isolated_v1

> serde_json::Value delete_user_data_stream_isolated_v1(symbol, listenkey)
Close Isolated Margin User Data Stream (USER_STREAM)

Close out a isolated margin user data stream.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**listenkey** | **String** |  | [required] |[default to ]

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_user_data_stream_v1

> serde_json::Value delete_user_data_stream_v1(listenkey)
Close Margin User Data Stream (USER_STREAM)

Close out a Margin user data stream.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**listenkey** | **String** |  | [required] |[default to ]

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_bnb_burn_v1

> models::GetBnbBurnV1Resp get_bnb_burn_v1(timestamp, recv_window)
Get BNB Burn Status (USER_DATA)

Get BNB Burn Status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | No more than 60000 |  |

### Return type

[**models::GetBnbBurnV1Resp**](GetBnbBurnV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_account_v1

> models::GetMarginAccountV1Resp get_margin_account_v1(timestamp, recv_window)
Query Cross Margin Account Details (USER_DATA)

Query Cross Margin Account Details

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetMarginAccountV1Resp**](GetMarginAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_all_assets_v1

> Vec<models::GetMarginAllAssetsV1RespItem> get_margin_all_assets_v1(asset)
Get All Margin Assets (MARKET_DATA)

Get All Margin Assets.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::GetMarginAllAssetsV1RespItem>**](GetMarginAllAssetsV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_all_order_list_v1

> Vec<models::GetMarginAllOrderListV1RespItem> get_margin_all_order_list_v1(timestamp, is_isolated, symbol, from_id, start_time, end_time, limit, recv_window)
Query Margin Account's all OCO (USER_DATA)

Retrieves all OCO for a specific margin account based on provided optional parameters

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**is_isolated** | Option<**String**> | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34;，default &#34;FALSE&#34; |  |[default to ]
**symbol** | Option<**String**> | mandatory for isolated margin, not supported for cross margin |  |[default to ]
**from_id** | Option<**i64**> | If supplied, neither `startTime` or `endTime` can be provided |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default Value: 500; Max Value: 1000 |  |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetMarginAllOrderListV1RespItem>**](GetMarginAllOrderListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_all_orders_v1

> Vec<models::GetMarginAllOrdersV1RespItem> get_margin_all_orders_v1(symbol, timestamp, is_isolated, order_id, start_time, end_time, limit, recv_window)
Query Margin Account's All Orders (USER_DATA)

Query Margin Account's All Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**is_isolated** | Option<**String**> | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34;，default &#34;FALSE&#34; |  |[default to ]
**order_id** | Option<**i64**> |  |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500; max 500. |  |[default to 500]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetMarginAllOrdersV1RespItem>**](GetMarginAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_all_pairs_v1

> Vec<models::GetMarginAllPairsV1RespItem> get_margin_all_pairs_v1(symbol)
Get All Cross Margin Pairs (MARKET_DATA)

Get All Cross Margin Pairs

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**Vec<models::GetMarginAllPairsV1RespItem>**](GetMarginAllPairsV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_api_key_list_v1

> Vec<models::GetMarginApiKeyListV1RespItem> get_margin_api_key_list_v1(timestamp, symbol, recv_window)
Query Special key List(Low Latency Trading)(TRADE)

This only applies to Special Key for Low Latency Trading.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> | isolated margin pair |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetMarginApiKeyListV1RespItem>**](GetMarginApiKeyListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_api_key_v1

> models::GetMarginApiKeyV1Resp get_margin_api_key_v1(api_key, timestamp, symbol, recv_window)
Query Special key(Low Latency Trading)(TRADE)

Query Special Key Information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**api_key** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> | isolated margin pair |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetMarginApiKeyV1Resp**](GetMarginApiKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_available_inventory_v1

> models::MarginGetMarginAvailableInventoryV1Resp get_margin_available_inventory_v1(r#type)
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


## get_margin_borrow_repay_v1

> models::GetMarginBorrowRepayV1Resp get_margin_borrow_repay_v1(r#type, timestamp, asset, isolated_symbol, tx_id, start_time, end_time, current, size, recv_window)
Query borrow/repay records in Margin account(USER_DATA)

Query borrow/repay records in Margin account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**r#type** | **String** | `BORROW` or `REPAY` | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**isolated_symbol** | Option<**String**> | Symbol in Isolated Margin |  |[default to ]
**tx_id** | Option<**i64**> | `tranId` in `POST /sapi/v1/margin/loan` |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Current querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetMarginBorrowRepayV1Resp**](GetMarginBorrowRepayV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_capital_flow_v1

> Vec<models::GetMarginCapitalFlowV1RespItem> get_margin_capital_flow_v1(timestamp, asset, symbol, r#type, start_time, end_time, from_id, limit, recv_window)
Query Cross Isolated Margin Capital Flow (USER_DATA)

Query Cross Isolated Margin Capital Flow

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**symbol** | Option<**String**> | 查询逐仓数据时必填 |  |[default to ]
**r#type** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> | 只支持查询最近90天的数据 |  |
**end_time** | Option<**i64**> |  |  |
**from_id** | Option<**i64**> | 如设置fromId, 将返回id &gt; fromId的数据。否则将返回最新数据 |  |
**limit** | Option<**i64**> | 每次返回的数据条数限制。默认 500; 最大 1000. |  |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetMarginCapitalFlowV1RespItem>**](GetMarginCapitalFlowV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_cross_margin_collateral_ratio_v1

> Vec<models::GetMarginCrossMarginCollateralRatioV1RespItem> get_margin_cross_margin_collateral_ratio_v1()
Cross margin collateral ratio (MARKET_DATA)

Cross margin collateral ratio

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::GetMarginCrossMarginCollateralRatioV1RespItem>**](GetMarginCrossMarginCollateralRatioV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_cross_margin_data_v1

> Vec<models::GetMarginCrossMarginDataV1RespItem> get_margin_cross_margin_data_v1(timestamp, vip_level, coin, recv_window)
Query Cross Margin Fee Data (USER_DATA)

Get cross margin fee data collection with any vip level or user's current specific data as https://www.binance.com/en/margin-fee

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**vip_level** | Option<**i32**> | User&#39;s current specific margin data will be returned if vipLevel is omitted |  |
**coin** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | No more than `60000` |  |

### Return type

[**Vec<models::GetMarginCrossMarginDataV1RespItem>**](GetMarginCrossMarginDataV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_delist_schedule_v1

> Vec<models::GetMarginDelistScheduleV1RespItem> get_margin_delist_schedule_v1(timestamp, recv_window)
Get Delist Schedule (MARKET_DATA)

Get tokens or symbols delist schedule for cross margin and isolated margin

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetMarginDelistScheduleV1RespItem>**](GetMarginDelistScheduleV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_exchange_small_liability_history_v1

> models::GetMarginExchangeSmallLiabilityHistoryV1Resp get_margin_exchange_small_liability_history_v1(current, size, timestamp, start_time, end_time, recv_window)
Get Small Liability Exchange History (USER_DATA)

Get Small liability Exchange History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**current** | **i32** | Currently querying page. Start from 1. Default:1 | [required] |
**size** | **i32** | Default:10, Max:100 | [required] |
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> | Default: 30 days from current timestamp |  |
**end_time** | Option<**i64**> | Default: present timestamp |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMarginExchangeSmallLiabilityHistoryV1Resp**](GetMarginExchangeSmallLiabilityHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_exchange_small_liability_v1

> Vec<models::GetMarginExchangeSmallLiabilityV1RespItem> get_margin_exchange_small_liability_v1(timestamp, recv_window)
Get Small Liability Exchange Coin List (USER_DATA)

Query the coins which can be small liability exchange

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetMarginExchangeSmallLiabilityV1RespItem>**](GetMarginExchangeSmallLiabilityV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_force_liquidation_rec_v1

> models::GetMarginForceLiquidationRecV1Resp get_margin_force_liquidation_rec_v1(timestamp, start_time, end_time, isolated_symbol, current, size, recv_window)
Get Force Liquidation Record (USER_DATA)

Get Force Liquidation Record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**isolated_symbol** | Option<**String**> |  |  |[default to ]
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetMarginForceLiquidationRecV1Resp**](GetMarginForceLiquidationRecV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_interest_history_v1

> models::GetMarginInterestHistoryV1Resp get_margin_interest_history_v1(timestamp, asset, isolated_symbol, start_time, end_time, current, size, recv_window)
Get Interest History (USER_DATA)

Get Interest History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**isolated_symbol** | Option<**String**> | isolated symbol |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetMarginInterestHistoryV1Resp**](GetMarginInterestHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_interest_rate_history_v1

> Vec<models::GetMarginInterestRateHistoryV1RespItem> get_margin_interest_rate_history_v1(asset, timestamp, vip_level, start_time, end_time, recv_window)
Query Margin Interest Rate History (USER_DATA)

Query Margin Interest Rate History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**vip_level** | Option<**i32**> | Default: user&#39;s vip level |  |
**start_time** | Option<**i64**> | Default: 7 days ago |  |
**end_time** | Option<**i64**> | Default: present. Maximum range: 1 months. |  |
**recv_window** | Option<**i64**> | No more than 60000 |  |

### Return type

[**Vec<models::GetMarginInterestRateHistoryV1RespItem>**](GetMarginInterestRateHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_isolated_account_limit_v1

> models::GetMarginIsolatedAccountLimitV1Resp get_margin_isolated_account_limit_v1(timestamp, recv_window)
Query Enabled Isolated Margin Account Limit (USER_DATA)

Query enabled isolated margin account limit.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | No more than 60000 |  |

### Return type

[**models::GetMarginIsolatedAccountLimitV1Resp**](GetMarginIsolatedAccountLimitV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_isolated_account_v1

> models::GetMarginIsolatedAccountV1Resp get_margin_isolated_account_v1(timestamp, symbols, recv_window)
Query Isolated Margin Account Info (USER_DATA)

Query Isolated Margin Account Info

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbols** | Option<**String**> | Max 5 symbols can be sent; separated by &#34;,&#34;. e.g. &#34;BTCUSDT,BNBUSDT,ADAUSDT&#34; |  |[default to ]
**recv_window** | Option<**i64**> | No more than 60000 |  |

### Return type

[**models::GetMarginIsolatedAccountV1Resp**](GetMarginIsolatedAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_isolated_all_pairs_v1

> Vec<models::GetMarginIsolatedAllPairsV1RespItem> get_margin_isolated_all_pairs_v1(timestamp, symbol, recv_window)
Get All Isolated Margin Symbol(MARKET_DATA)

Get All Isolated Margin Symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | No more than 60000 |  |

### Return type

[**Vec<models::GetMarginIsolatedAllPairsV1RespItem>**](GetMarginIsolatedAllPairsV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_isolated_margin_data_v1

> Vec<models::GetMarginIsolatedMarginDataV1RespItem> get_margin_isolated_margin_data_v1(timestamp, vip_level, symbol, recv_window)
Query Isolated Margin Fee Data (USER_DATA)

Get isolated margin fee data collection with any vip level or user's current specific data as https://www.binance.com/en/margin-fee

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**vip_level** | Option<**i32**> | User&#39;s current specific margin data will be returned if vipLevel is omitted |  |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | No more than `60000` |  |

### Return type

[**Vec<models::GetMarginIsolatedMarginDataV1RespItem>**](GetMarginIsolatedMarginDataV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_isolated_margin_tier_v1

> Vec<models::GetMarginIsolatedMarginTierV1RespItem> get_margin_isolated_margin_tier_v1(symbol, timestamp, tier, recv_window)
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

[**Vec<models::GetMarginIsolatedMarginTierV1RespItem>**](GetMarginIsolatedMarginTierV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_leverage_bracket_v1

> Vec<models::GetMarginLeverageBracketV1RespItem> get_margin_leverage_bracket_v1()
Query Liability Coin Leverage Bracket in Cross Margin Pro Mode(MARKET_DATA)

Liability Coin Leverage Bracket in Cross Margin Pro Mode

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::GetMarginLeverageBracketV1RespItem>**](GetMarginLeverageBracketV1RespItem.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_max_borrowable_v1

> models::GetMarginMaxBorrowableV1Resp get_margin_max_borrowable_v1(asset, timestamp, isolated_symbol, recv_window)
Query Max Borrow (USER_DATA)

Query Max Borrow

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**isolated_symbol** | Option<**String**> | isolated symbol |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetMarginMaxBorrowableV1Resp**](GetMarginMaxBorrowableV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_max_transferable_v1

> models::GetMarginMaxTransferableV1Resp get_margin_max_transferable_v1(asset, timestamp, isolated_symbol, recv_window)
Query Max Transfer-Out Amount (USER_DATA)

Query Max Transfer-Out Amount

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**isolated_symbol** | Option<**String**> | isolated symbol |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetMarginMaxTransferableV1Resp**](GetMarginMaxTransferableV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_my_trades_v1

> Vec<models::GetMarginMyTradesV1RespItem> get_margin_my_trades_v1(symbol, timestamp, is_isolated, order_id, start_time, end_time, from_id, limit, recv_window)
Query Margin Account's Trade List (USER_DATA)

Query Margin Account's Trade List

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**is_isolated** | Option<**String**> | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34;，default &#34;FALSE&#34; |  |[default to ]
**order_id** | Option<**i64**> |  |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**from_id** | Option<**i64**> | TradeId to fetch from. Default gets most recent trades. |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetMarginMyTradesV1RespItem>**](GetMarginMyTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_next_hourly_interest_rate_v1

> Vec<models::GetMarginNextHourlyInterestRateV1RespItem> get_margin_next_hourly_interest_rate_v1(assets, is_isolated)
Get future hourly interest rate (USER_DATA)

Get future hourly interest rate

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**assets** | **String** | List of assets, separated by commas, up to 20 | [required] |[default to ]
**is_isolated** | **bool** | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34; | [required] |

### Return type

[**Vec<models::GetMarginNextHourlyInterestRateV1RespItem>**](GetMarginNextHourlyInterestRateV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_open_order_list_v1

> Vec<models::GetMarginOpenOrderListV1RespItem> get_margin_open_order_list_v1(timestamp, is_isolated, symbol, recv_window)
Query Margin Account's Open OCO (USER_DATA)

Query Margin Account's Open OCO

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**is_isolated** | Option<**String**> | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34;，default &#34;FALSE&#34; |  |[default to ]
**symbol** | Option<**String**> | mandatory for isolated margin, not supported for cross margin |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetMarginOpenOrderListV1RespItem>**](GetMarginOpenOrderListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_open_orders_v1

> Vec<models::MarginGetMarginOpenOrdersV1RespItem> get_margin_open_orders_v1(timestamp, symbol, is_isolated, recv_window)
Query Margin Account's Open Orders (USER_DATA)

Query Margin Account's Open Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**is_isolated** | Option<**String**> | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34;，default &#34;FALSE&#34; |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::MarginGetMarginOpenOrdersV1RespItem>**](MarginGetMarginOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_order_list_v1

> models::GetMarginOrderListV1Resp get_margin_order_list_v1(timestamp, is_isolated, symbol, order_list_id, orig_client_order_id, recv_window)
Query Margin Account's OCO (USER_DATA)

Retrieves a specific OCO based on provided optional parameters

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**is_isolated** | Option<**String**> | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34;，default &#34;FALSE&#34; |  |[default to ]
**symbol** | Option<**String**> | mandatory for isolated margin, not supported for cross margin |  |[default to ]
**order_list_id** | Option<**i64**> | Either `orderListId` or `origClientOrderId` must be provided |  |
**orig_client_order_id** | Option<**String**> | Either `orderListId` or `origClientOrderId` must be provided |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetMarginOrderListV1Resp**](GetMarginOrderListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_order_v1

> models::GetMarginOrderV1Resp get_margin_order_v1(symbol, timestamp, is_isolated, order_id, orig_client_order_id, recv_window)
Query Margin Account's Order (USER_DATA)

Query Margin Account's Order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**is_isolated** | Option<**String**> | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34;，default &#34;FALSE&#34; |  |[default to ]
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetMarginOrderV1Resp**](GetMarginOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_price_index_v1

> models::GetMarginPriceIndexV1Resp get_margin_price_index_v1(symbol)
Query Margin PriceIndex (MARKET_DATA)

Query Margin PriceIndex

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**models::GetMarginPriceIndexV1Resp**](GetMarginPriceIndexV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_rate_limit_order_v1

> Vec<models::GetMarginRateLimitOrderV1RespItem> get_margin_rate_limit_order_v1(timestamp, is_isolated, symbol, recv_window)
Query Current Margin Order Count Usage (TRADE)

Displays the user's current margin order count usage for all intervals.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**is_isolated** | Option<**String**> | for isolated margin or not, &#34;TRUE&#34;, &#34;FALSE&#34;，default &#34;FALSE&#34; |  |[default to ]
**symbol** | Option<**String**> | isolated symbol, mandatory for isolated margin |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::GetMarginRateLimitOrderV1RespItem>**](GetMarginRateLimitOrderV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_trade_coeff_v1

> models::GetMarginTradeCoeffV1Resp get_margin_trade_coeff_v1(timestamp, recv_window)
Get Summary of Margin account (USER_DATA)

Get personal margin level information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetMarginTradeCoeffV1Resp**](GetMarginTradeCoeffV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_transfer_v1

> models::GetMarginTransferV1Resp get_margin_transfer_v1(timestamp, asset, r#type, start_time, end_time, current, size, isolated_symbol, recv_window)
Get Cross Margin Transfer History (USER_DATA)

Get Cross Margin Transfer History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**r#type** | Option<**String**> | Transfer Type: ROLL_IN, ROLL_OUT |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**isolated_symbol** | Option<**String**> | Symbol in Isolated Margin |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetMarginTransferV1Resp**](GetMarginTransferV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_margin_api_key_ip_v1

> serde_json::Value update_margin_api_key_ip_v1(api_key, ip, timestamp, recv_window, symbol)
Edit ip for Special Key(Low-Latency Trading)(TRADE)

Edit ip restriction. This only applies to Special Key for Low Latency Trading.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**api_key** | **String** |  | [required] |[default to ]
**ip** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |
**symbol** | Option<**String**> |  |  |[default to ]

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_margin_listen_key_v1

> serde_json::Value update_margin_listen_key_v1(listen_key)
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


## update_user_data_stream_isolated_v1

> serde_json::Value update_user_data_stream_isolated_v1(listen_key, symbol)
Keepalive Isolated Margin User Data Stream (USER_STREAM)

Keepalive an isolated margin user data stream to prevent a time out.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**listen_key** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_user_data_stream_v1

> serde_json::Value update_user_data_stream_v1(listen_key)
Keepalive Margin User Data Stream (USER_STREAM)

Keepalive a margin user data stream to prevent a time out.

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

