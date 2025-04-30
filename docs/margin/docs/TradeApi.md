# \TradeApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**margin_create_margin_api_key_v1**](TradeApi.md#margin_create_margin_api_key_v1) | **POST** /sapi/v1/margin/apiKey | Create Special Key(Low-Latency Trading)(TRADE)
[**margin_create_margin_exchange_small_liability_v1**](TradeApi.md#margin_create_margin_exchange_small_liability_v1) | **POST** /sapi/v1/margin/exchange-small-liability | Small Liability Exchange (MARGIN)
[**margin_create_margin_manual_liquidation_v1**](TradeApi.md#margin_create_margin_manual_liquidation_v1) | **POST** /sapi/v1/margin/manual-liquidation | Margin Manual Liquidation(MARGIN)
[**margin_create_margin_order_oco_v1**](TradeApi.md#margin_create_margin_order_oco_v1) | **POST** /sapi/v1/margin/order/oco | Margin Account New OCO (TRADE)
[**margin_create_margin_order_oto_v1**](TradeApi.md#margin_create_margin_order_oto_v1) | **POST** /sapi/v1/margin/order/oto | Margin Account New OTO (TRADE)
[**margin_create_margin_order_otoco_v1**](TradeApi.md#margin_create_margin_order_otoco_v1) | **POST** /sapi/v1/margin/order/otoco | Margin Account New OTOCO (TRADE)
[**margin_create_margin_order_v1**](TradeApi.md#margin_create_margin_order_v1) | **POST** /sapi/v1/margin/order | Margin Account New Order (TRADE)
[**margin_delete_margin_api_key_v1**](TradeApi.md#margin_delete_margin_api_key_v1) | **DELETE** /sapi/v1/margin/apiKey | Delete Special Key(Low-Latency Trading)(TRADE)
[**margin_delete_margin_open_orders_v1**](TradeApi.md#margin_delete_margin_open_orders_v1) | **DELETE** /sapi/v1/margin/openOrders | Margin Account Cancel all Open Orders on a Symbol (TRADE)
[**margin_delete_margin_order_list_v1**](TradeApi.md#margin_delete_margin_order_list_v1) | **DELETE** /sapi/v1/margin/orderList | Margin Account Cancel OCO (TRADE)
[**margin_delete_margin_order_v1**](TradeApi.md#margin_delete_margin_order_v1) | **DELETE** /sapi/v1/margin/order | Margin Account Cancel Order (TRADE)
[**margin_get_margin_all_order_list_v1**](TradeApi.md#margin_get_margin_all_order_list_v1) | **GET** /sapi/v1/margin/allOrderList | Query Margin Account's all OCO (USER_DATA)
[**margin_get_margin_all_orders_v1**](TradeApi.md#margin_get_margin_all_orders_v1) | **GET** /sapi/v1/margin/allOrders | Query Margin Account's All Orders (USER_DATA)
[**margin_get_margin_api_key_list_v1**](TradeApi.md#margin_get_margin_api_key_list_v1) | **GET** /sapi/v1/margin/api-key-list | Query Special key List(Low Latency Trading)(TRADE)
[**margin_get_margin_api_key_v1**](TradeApi.md#margin_get_margin_api_key_v1) | **GET** /sapi/v1/margin/apiKey | Query Special key(Low Latency Trading)(TRADE)
[**margin_get_margin_exchange_small_liability_history_v1**](TradeApi.md#margin_get_margin_exchange_small_liability_history_v1) | **GET** /sapi/v1/margin/exchange-small-liability-history | Get Small Liability Exchange History (USER_DATA)
[**margin_get_margin_exchange_small_liability_v1**](TradeApi.md#margin_get_margin_exchange_small_liability_v1) | **GET** /sapi/v1/margin/exchange-small-liability | Get Small Liability Exchange Coin List (USER_DATA)
[**margin_get_margin_force_liquidation_rec_v1**](TradeApi.md#margin_get_margin_force_liquidation_rec_v1) | **GET** /sapi/v1/margin/forceLiquidationRec | Get Force Liquidation Record (USER_DATA)
[**margin_get_margin_my_trades_v1**](TradeApi.md#margin_get_margin_my_trades_v1) | **GET** /sapi/v1/margin/myTrades | Query Margin Account's Trade List (USER_DATA)
[**margin_get_margin_open_order_list_v1**](TradeApi.md#margin_get_margin_open_order_list_v1) | **GET** /sapi/v1/margin/openOrderList | Query Margin Account's Open OCO (USER_DATA)
[**margin_get_margin_open_orders_v1**](TradeApi.md#margin_get_margin_open_orders_v1) | **GET** /sapi/v1/margin/openOrders | Query Margin Account's Open Orders (USER_DATA)
[**margin_get_margin_order_list_v1**](TradeApi.md#margin_get_margin_order_list_v1) | **GET** /sapi/v1/margin/orderList | Query Margin Account's OCO (USER_DATA)
[**margin_get_margin_order_v1**](TradeApi.md#margin_get_margin_order_v1) | **GET** /sapi/v1/margin/order | Query Margin Account's Order (USER_DATA)
[**margin_get_margin_rate_limit_order_v1**](TradeApi.md#margin_get_margin_rate_limit_order_v1) | **GET** /sapi/v1/margin/rateLimit/order | Query Current Margin Order Count Usage (TRADE)
[**margin_update_margin_api_key_ip_v1**](TradeApi.md#margin_update_margin_api_key_ip_v1) | **PUT** /sapi/v1/margin/apiKey/ip | Edit ip for Special Key(Low-Latency Trading)(TRADE)



## margin_create_margin_api_key_v1

> models::MarginCreateMarginApiKeyV1Resp margin_create_margin_api_key_v1(api_name, timestamp, ip, permission_mode, public_key, recv_window, symbol)
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

[**models::MarginCreateMarginApiKeyV1Resp**](MarginCreateMarginApiKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_create_margin_exchange_small_liability_v1

> models::MarginCreateMarginExchangeSmallLiabilityV1Resp margin_create_margin_exchange_small_liability_v1(asset_names, timestamp, recv_window)
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


## margin_create_margin_manual_liquidation_v1

> models::MarginCreateMarginManualLiquidationV1Resp margin_create_margin_manual_liquidation_v1(timestamp, r#type, recv_window, symbol)
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

[**models::MarginCreateMarginManualLiquidationV1Resp**](MarginCreateMarginManualLiquidationV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_create_margin_order_oco_v1

> models::MarginCreateMarginOrderOcoV1Resp margin_create_margin_order_oco_v1(price, quantity, side, stop_price, symbol, timestamp, auto_repay_at_cancel, is_isolated, limit_client_order_id, limit_iceberg_qty, list_client_order_id, new_order_resp_type, recv_window, self_trade_prevention_mode, side_effect_type, stop_client_order_id, stop_iceberg_qty, stop_limit_price, stop_limit_time_in_force)
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

[**models::MarginCreateMarginOrderOcoV1Resp**](MarginCreateMarginOrderOcoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_create_margin_order_oto_v1

> models::MarginCreateMarginOrderOtoV1Resp margin_create_margin_order_oto_v1(pending_quantity, pending_side, pending_type, symbol, working_iceberg_qty, working_price, working_quantity, working_side, working_type, auto_repay_at_cancel, is_isolated, list_client_order_id, new_order_resp_type, pending_client_order_id, pending_iceberg_qty, pending_price, pending_stop_price, pending_time_in_force, pending_trailing_delta, self_trade_prevention_mode, side_effect_type, working_client_order_id, working_time_in_force)
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

[**models::MarginCreateMarginOrderOtoV1Resp**](MarginCreateMarginOrderOtoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_create_margin_order_otoco_v1

> models::MarginCreateMarginOrderOtocoV1Resp margin_create_margin_order_otoco_v1(pending_above_type, pending_quantity, pending_side, symbol, working_price, working_quantity, working_side, working_type, auto_repay_at_cancel, is_isolated, list_client_order_id, new_order_resp_type, pending_above_client_order_id, pending_above_iceberg_qty, pending_above_price, pending_above_stop_price, pending_above_time_in_force, pending_above_trailing_delta, pending_below_client_order_id, pending_below_iceberg_qty, pending_below_price, pending_below_stop_price, pending_below_time_in_force, pending_below_trailing_delta, pending_below_type, self_trade_prevention_mode, side_effect_type, working_client_order_id, working_iceberg_qty, working_time_in_force)
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

[**models::MarginCreateMarginOrderOtocoV1Resp**](MarginCreateMarginOrderOtocoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_create_margin_order_v1

> models::MarginCreateMarginOrderV1Resp margin_create_margin_order_v1(side, symbol, timestamp, r#type, auto_repay_at_cancel, iceberg_qty, is_isolated, new_client_order_id, new_order_resp_type, price, quantity, quote_order_qty, recv_window, self_trade_prevention_mode, side_effect_type, stop_price, time_in_force)
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


## margin_delete_margin_api_key_v1

> serde_json::Value margin_delete_margin_api_key_v1(timestamp, api_key, api_name, symbol, recv_window)
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


## margin_delete_margin_open_orders_v1

> Vec<models::MarginDeleteMarginOpenOrdersV1RespItem> margin_delete_margin_open_orders_v1(symbol, timestamp, is_isolated, recv_window)
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

[**Vec<models::MarginDeleteMarginOpenOrdersV1RespItem>**](MarginDeleteMarginOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_delete_margin_order_list_v1

> models::MarginDeleteMarginOrderListV1Resp margin_delete_margin_order_list_v1(symbol, timestamp, is_isolated, order_list_id, list_client_order_id, new_client_order_id, recv_window)
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

[**models::MarginDeleteMarginOrderListV1Resp**](MarginDeleteMarginOrderListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_delete_margin_order_v1

> models::MarginDeleteMarginOrderV1Resp margin_delete_margin_order_v1(symbol, timestamp, is_isolated, order_id, orig_client_order_id, new_client_order_id, recv_window)
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

[**models::MarginDeleteMarginOrderV1Resp**](MarginDeleteMarginOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_all_order_list_v1

> Vec<models::MarginGetMarginAllOrderListV1RespItem> margin_get_margin_all_order_list_v1(timestamp, is_isolated, symbol, from_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::MarginGetMarginAllOrderListV1RespItem>**](MarginGetMarginAllOrderListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_all_orders_v1

> Vec<models::MarginGetMarginAllOrdersV1RespItem> margin_get_margin_all_orders_v1(symbol, timestamp, is_isolated, order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::MarginGetMarginAllOrdersV1RespItem>**](MarginGetMarginAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_api_key_list_v1

> Vec<models::MarginGetMarginApiKeyListV1RespItem> margin_get_margin_api_key_list_v1(timestamp, symbol, recv_window)
Query Special key List(Low Latency Trading)(TRADE)

This only applies to Special Key for Low Latency Trading.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> | isolated margin pair |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**Vec<models::MarginGetMarginApiKeyListV1RespItem>**](MarginGetMarginApiKeyListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_api_key_v1

> models::MarginGetMarginApiKeyV1Resp margin_get_margin_api_key_v1(api_key, timestamp, symbol, recv_window)
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

[**models::MarginGetMarginApiKeyV1Resp**](MarginGetMarginApiKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_exchange_small_liability_history_v1

> models::MarginGetMarginExchangeSmallLiabilityHistoryV1Resp margin_get_margin_exchange_small_liability_history_v1(current, size, timestamp, start_time, end_time, recv_window)
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

[**models::MarginGetMarginExchangeSmallLiabilityHistoryV1Resp**](MarginGetMarginExchangeSmallLiabilityHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_exchange_small_liability_v1

> Vec<models::MarginGetMarginExchangeSmallLiabilityV1RespItem> margin_get_margin_exchange_small_liability_v1(timestamp, recv_window)
Get Small Liability Exchange Coin List (USER_DATA)

Query the coins which can be small liability exchange

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::MarginGetMarginExchangeSmallLiabilityV1RespItem>**](MarginGetMarginExchangeSmallLiabilityV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_force_liquidation_rec_v1

> models::MarginGetMarginForceLiquidationRecV1Resp margin_get_margin_force_liquidation_rec_v1(timestamp, start_time, end_time, isolated_symbol, current, size, recv_window)
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

[**models::MarginGetMarginForceLiquidationRecV1Resp**](MarginGetMarginForceLiquidationRecV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_my_trades_v1

> Vec<models::MarginGetMarginMyTradesV1RespItem> margin_get_margin_my_trades_v1(symbol, timestamp, is_isolated, order_id, start_time, end_time, from_id, limit, recv_window)
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

[**Vec<models::MarginGetMarginMyTradesV1RespItem>**](MarginGetMarginMyTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_open_order_list_v1

> Vec<models::MarginGetMarginOpenOrderListV1RespItem> margin_get_margin_open_order_list_v1(timestamp, is_isolated, symbol, recv_window)
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

[**Vec<models::MarginGetMarginOpenOrderListV1RespItem>**](MarginGetMarginOpenOrderListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_open_orders_v1

> Vec<models::MarginGetMarginOpenOrdersV1RespItem> margin_get_margin_open_orders_v1(timestamp, symbol, is_isolated, recv_window)
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


## margin_get_margin_order_list_v1

> models::MarginGetMarginOrderListV1Resp margin_get_margin_order_list_v1(timestamp, is_isolated, symbol, order_list_id, orig_client_order_id, recv_window)
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

[**models::MarginGetMarginOrderListV1Resp**](MarginGetMarginOrderListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_order_v1

> models::MarginGetMarginOrderV1Resp margin_get_margin_order_v1(symbol, timestamp, is_isolated, order_id, orig_client_order_id, recv_window)
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

[**models::MarginGetMarginOrderV1Resp**](MarginGetMarginOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_get_margin_rate_limit_order_v1

> Vec<models::MarginGetMarginRateLimitOrderV1RespItem> margin_get_margin_rate_limit_order_v1(timestamp, is_isolated, symbol, recv_window)
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

[**Vec<models::MarginGetMarginRateLimitOrderV1RespItem>**](MarginGetMarginRateLimitOrderV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## margin_update_margin_api_key_ip_v1

> serde_json::Value margin_update_margin_api_key_ip_v1(api_key, ip, timestamp, recv_window, symbol)
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

