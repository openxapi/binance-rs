# \TradeApi

All URIs are relative to *https://papi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**pmargin_create_cm_conditional_order_v1**](TradeApi.md#pmargin_create_cm_conditional_order_v1) | **POST** /papi/v1/cm/conditional/order | New CM Conditional Order(TRADE)
[**pmargin_create_cm_order_v1**](TradeApi.md#pmargin_create_cm_order_v1) | **POST** /papi/v1/cm/order | New CM Order(TRADE)
[**pmargin_create_margin_loan_v1**](TradeApi.md#pmargin_create_margin_loan_v1) | **POST** /papi/v1/marginLoan | Margin Account Borrow(MARGIN)
[**pmargin_create_margin_order_oco_v1**](TradeApi.md#pmargin_create_margin_order_oco_v1) | **POST** /papi/v1/margin/order/oco | Margin Account New OCO(TRADE)
[**pmargin_create_margin_order_v1**](TradeApi.md#pmargin_create_margin_order_v1) | **POST** /papi/v1/margin/order | New Margin Order(TRADE)
[**pmargin_create_margin_repay_debt_v1**](TradeApi.md#pmargin_create_margin_repay_debt_v1) | **POST** /papi/v1/margin/repay-debt | Margin Account Repay Debt(TRADE)
[**pmargin_create_repay_loan_v1**](TradeApi.md#pmargin_create_repay_loan_v1) | **POST** /papi/v1/repayLoan | Margin Account Repay(MARGIN)
[**pmargin_create_um_conditional_order_v1**](TradeApi.md#pmargin_create_um_conditional_order_v1) | **POST** /papi/v1/um/conditional/order | New UM Conditional Order (TRADE)
[**pmargin_create_um_fee_burn_v1**](TradeApi.md#pmargin_create_um_fee_burn_v1) | **POST** /papi/v1/um/feeBurn | Toggle BNB Burn On UM Futures Trade (TRADE)
[**pmargin_create_um_order_v1**](TradeApi.md#pmargin_create_um_order_v1) | **POST** /papi/v1/um/order | New UM Order (TRADE)
[**pmargin_delete_cm_all_open_orders_v1**](TradeApi.md#pmargin_delete_cm_all_open_orders_v1) | **DELETE** /papi/v1/cm/allOpenOrders | Cancel All CM Open Orders(TRADE)
[**pmargin_delete_cm_conditional_all_open_orders_v1**](TradeApi.md#pmargin_delete_cm_conditional_all_open_orders_v1) | **DELETE** /papi/v1/cm/conditional/allOpenOrders | Cancel All CM Open Conditional Orders(TRADE)
[**pmargin_delete_cm_conditional_order_v1**](TradeApi.md#pmargin_delete_cm_conditional_order_v1) | **DELETE** /papi/v1/cm/conditional/order | Cancel CM Conditional Order(TRADE)
[**pmargin_delete_cm_order_v1**](TradeApi.md#pmargin_delete_cm_order_v1) | **DELETE** /papi/v1/cm/order | Cancel CM Order(TRADE)
[**pmargin_delete_margin_all_open_orders_v1**](TradeApi.md#pmargin_delete_margin_all_open_orders_v1) | **DELETE** /papi/v1/margin/allOpenOrders | Cancel Margin Account All Open Orders on a Symbol(TRADE)
[**pmargin_delete_margin_order_list_v1**](TradeApi.md#pmargin_delete_margin_order_list_v1) | **DELETE** /papi/v1/margin/orderList | Cancel Margin Account OCO Orders(TRADE)
[**pmargin_delete_margin_order_v1**](TradeApi.md#pmargin_delete_margin_order_v1) | **DELETE** /papi/v1/margin/order | Cancel Margin Account Order(TRADE)
[**pmargin_delete_um_all_open_orders_v1**](TradeApi.md#pmargin_delete_um_all_open_orders_v1) | **DELETE** /papi/v1/um/allOpenOrders | Cancel All UM Open Orders(TRADE)
[**pmargin_delete_um_conditional_all_open_orders_v1**](TradeApi.md#pmargin_delete_um_conditional_all_open_orders_v1) | **DELETE** /papi/v1/um/conditional/allOpenOrders | Cancel All UM Open Conditional Orders (TRADE)
[**pmargin_delete_um_conditional_order_v1**](TradeApi.md#pmargin_delete_um_conditional_order_v1) | **DELETE** /papi/v1/um/conditional/order | Cancel UM Conditional Order(TRADE)
[**pmargin_delete_um_order_v1**](TradeApi.md#pmargin_delete_um_order_v1) | **DELETE** /papi/v1/um/order | Cancel UM Order(TRADE)
[**pmargin_get_cm_adl_quantile_v1**](TradeApi.md#pmargin_get_cm_adl_quantile_v1) | **GET** /papi/v1/cm/adlQuantile | CM Position ADL Quantile Estimation(USER_DATA)
[**pmargin_get_cm_all_orders_v1**](TradeApi.md#pmargin_get_cm_all_orders_v1) | **GET** /papi/v1/cm/allOrders | Query All CM Orders (USER_DATA)
[**pmargin_get_cm_conditional_all_orders_v1**](TradeApi.md#pmargin_get_cm_conditional_all_orders_v1) | **GET** /papi/v1/cm/conditional/allOrders | Query All CM Conditional Orders(USER_DATA)
[**pmargin_get_cm_conditional_open_order_v1**](TradeApi.md#pmargin_get_cm_conditional_open_order_v1) | **GET** /papi/v1/cm/conditional/openOrder | Query Current CM Open Conditional Order(USER_DATA)
[**pmargin_get_cm_conditional_open_orders_v1**](TradeApi.md#pmargin_get_cm_conditional_open_orders_v1) | **GET** /papi/v1/cm/conditional/openOrders | Query All Current CM Open Conditional Orders (USER_DATA)
[**pmargin_get_cm_conditional_order_history_v1**](TradeApi.md#pmargin_get_cm_conditional_order_history_v1) | **GET** /papi/v1/cm/conditional/orderHistory | Query CM Conditional Order History(USER_DATA)
[**pmargin_get_cm_force_orders_v1**](TradeApi.md#pmargin_get_cm_force_orders_v1) | **GET** /papi/v1/cm/forceOrders | Query User's CM Force Orders(USER_DATA)
[**pmargin_get_cm_open_order_v1**](TradeApi.md#pmargin_get_cm_open_order_v1) | **GET** /papi/v1/cm/openOrder | Query Current CM Open Order (USER_DATA)
[**pmargin_get_cm_open_orders_v1**](TradeApi.md#pmargin_get_cm_open_orders_v1) | **GET** /papi/v1/cm/openOrders | Query All Current CM Open Orders(USER_DATA)
[**pmargin_get_cm_order_amendment_v1**](TradeApi.md#pmargin_get_cm_order_amendment_v1) | **GET** /papi/v1/cm/orderAmendment | Query CM Modify Order History(TRADE)
[**pmargin_get_cm_order_v1**](TradeApi.md#pmargin_get_cm_order_v1) | **GET** /papi/v1/cm/order | Query CM Order(USER_DATA)
[**pmargin_get_cm_user_trades_v1**](TradeApi.md#pmargin_get_cm_user_trades_v1) | **GET** /papi/v1/cm/userTrades | CM Account Trade List(USER_DATA)
[**pmargin_get_margin_all_order_list_v1**](TradeApi.md#pmargin_get_margin_all_order_list_v1) | **GET** /papi/v1/margin/allOrderList | Query Margin Account's all OCO (USER_DATA)
[**pmargin_get_margin_all_orders_v1**](TradeApi.md#pmargin_get_margin_all_orders_v1) | **GET** /papi/v1/margin/allOrders | Query All Margin Account Orders (USER_DATA)
[**pmargin_get_margin_force_orders_v1**](TradeApi.md#pmargin_get_margin_force_orders_v1) | **GET** /papi/v1/margin/forceOrders | Query User's Margin Force Orders(USER_DATA)
[**pmargin_get_margin_my_trades_v1**](TradeApi.md#pmargin_get_margin_my_trades_v1) | **GET** /papi/v1/margin/myTrades | Margin Account Trade List (USER_DATA)
[**pmargin_get_margin_open_order_list_v1**](TradeApi.md#pmargin_get_margin_open_order_list_v1) | **GET** /papi/v1/margin/openOrderList | Query Margin Account's Open OCO (USER_DATA)
[**pmargin_get_margin_open_orders_v1**](TradeApi.md#pmargin_get_margin_open_orders_v1) | **GET** /papi/v1/margin/openOrders | Query Current Margin Open Order (USER_DATA)
[**pmargin_get_margin_order_list_v1**](TradeApi.md#pmargin_get_margin_order_list_v1) | **GET** /papi/v1/margin/orderList | Query Margin Account's OCO (USER_DATA)
[**pmargin_get_margin_order_v1**](TradeApi.md#pmargin_get_margin_order_v1) | **GET** /papi/v1/margin/order | Query Margin Account Order (USER_DATA)
[**pmargin_get_um_adl_quantile_v1**](TradeApi.md#pmargin_get_um_adl_quantile_v1) | **GET** /papi/v1/um/adlQuantile | UM Position ADL Quantile Estimation(USER_DATA)
[**pmargin_get_um_all_orders_v1**](TradeApi.md#pmargin_get_um_all_orders_v1) | **GET** /papi/v1/um/allOrders | Query All UM Orders(USER_DATA)
[**pmargin_get_um_conditional_all_orders_v1**](TradeApi.md#pmargin_get_um_conditional_all_orders_v1) | **GET** /papi/v1/um/conditional/allOrders | Query All UM Conditional Orders(USER_DATA)
[**pmargin_get_um_conditional_open_order_v1**](TradeApi.md#pmargin_get_um_conditional_open_order_v1) | **GET** /papi/v1/um/conditional/openOrder | Query Current UM Open Conditional Order(USER_DATA)
[**pmargin_get_um_conditional_open_orders_v1**](TradeApi.md#pmargin_get_um_conditional_open_orders_v1) | **GET** /papi/v1/um/conditional/openOrders | Query All Current UM Open Conditional Orders(USER_DATA)
[**pmargin_get_um_conditional_order_history_v1**](TradeApi.md#pmargin_get_um_conditional_order_history_v1) | **GET** /papi/v1/um/conditional/orderHistory | Query UM Conditional Order History(USER_DATA)
[**pmargin_get_um_fee_burn_v1**](TradeApi.md#pmargin_get_um_fee_burn_v1) | **GET** /papi/v1/um/feeBurn | Get UM Futures BNB Burn Status (USER_DATA)
[**pmargin_get_um_force_orders_v1**](TradeApi.md#pmargin_get_um_force_orders_v1) | **GET** /papi/v1/um/forceOrders | Query User's UM Force Orders (USER_DATA)
[**pmargin_get_um_open_order_v1**](TradeApi.md#pmargin_get_um_open_order_v1) | **GET** /papi/v1/um/openOrder | Query Current UM Open Order(USER_DATA)
[**pmargin_get_um_open_orders_v1**](TradeApi.md#pmargin_get_um_open_orders_v1) | **GET** /papi/v1/um/openOrders | Query All Current UM Open Orders(USER_DATA)
[**pmargin_get_um_order_amendment_v1**](TradeApi.md#pmargin_get_um_order_amendment_v1) | **GET** /papi/v1/um/orderAmendment | Query UM Modify Order History(TRADE)
[**pmargin_get_um_order_v1**](TradeApi.md#pmargin_get_um_order_v1) | **GET** /papi/v1/um/order | Query UM Order (USER_DATA)
[**pmargin_get_um_user_trades_v1**](TradeApi.md#pmargin_get_um_user_trades_v1) | **GET** /papi/v1/um/userTrades | UM Account Trade List(USER_DATA)
[**pmargin_update_cm_order_v1**](TradeApi.md#pmargin_update_cm_order_v1) | **PUT** /papi/v1/cm/order | Modify CM Order(TRADE)
[**pmargin_update_um_order_v1**](TradeApi.md#pmargin_update_um_order_v1) | **PUT** /papi/v1/um/order | Modify UM Order(TRADE)



## pmargin_create_cm_conditional_order_v1

> models::PmarginCreateCmConditionalOrderV1Resp pmargin_create_cm_conditional_order_v1(side, strategy_type, symbol, timestamp, activation_price, callback_rate, new_client_strategy_id, position_side, price, price_protect, quantity, recv_window, reduce_only, stop_price, time_in_force, working_type)
New CM Conditional Order(TRADE)

New CM Conditional Order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**side** | **String** |  | [required] |[default to ]
**strategy_type** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**activation_price** | Option<**String**> |  |  |[default to ]
**callback_rate** | Option<**String**> |  |  |[default to ]
**new_client_strategy_id** | Option<**String**> |  |  |[default to ]
**position_side** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**price_protect** | Option<**String**> |  |  |[default to ]
**quantity** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**reduce_only** | Option<**String**> |  |  |[default to ]
**stop_price** | Option<**String**> |  |  |[default to ]
**time_in_force** | Option<**String**> |  |  |[default to ]
**working_type** | Option<**String**> |  |  |[default to ]

### Return type

[**models::PmarginCreateCmConditionalOrderV1Resp**](PmarginCreateCmConditionalOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_cm_order_v1

> models::PmarginCreateCmOrderV1Resp pmargin_create_cm_order_v1(side, symbol, timestamp, r#type, new_client_order_id, new_order_resp_type, position_side, price, price_match, quantity, recv_window, reduce_only, time_in_force)
New CM Order(TRADE)

Place new CM order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**new_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**position_side** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**price_match** | Option<**String**> |  |  |[default to ]
**quantity** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**reduce_only** | Option<**String**> |  |  |[default to ]
**time_in_force** | Option<**String**> |  |  |[default to ]

### Return type

[**models::PmarginCreateCmOrderV1Resp**](PmarginCreateCmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_margin_loan_v1

> models::PmarginCreateMarginLoanV1Resp pmargin_create_margin_loan_v1(amount, asset, timestamp, recv_window)
Margin Account Borrow(MARGIN)

Apply for a margin loan.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginCreateMarginLoanV1Resp**](PmarginCreateMarginLoanV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_margin_order_oco_v1

> models::PmarginCreateMarginOrderOcoV1Resp pmargin_create_margin_order_oco_v1(price, quantity, side, stop_price, symbol, timestamp, limit_client_order_id, limit_iceberg_qty, list_client_order_id, new_order_resp_type, recv_window, side_effect_type, stop_client_order_id, stop_iceberg_qty, stop_limit_price, stop_limit_time_in_force)
Margin Account New OCO(TRADE)

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
**limit_client_order_id** | Option<**String**> |  |  |[default to ]
**limit_iceberg_qty** | Option<**String**> |  |  |[default to ]
**list_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**side_effect_type** | Option<**String**> |  |  |[default to ]
**stop_client_order_id** | Option<**String**> |  |  |[default to ]
**stop_iceberg_qty** | Option<**String**> |  |  |[default to ]
**stop_limit_price** | Option<**String**> |  |  |[default to ]
**stop_limit_time_in_force** | Option<**String**> |  |  |[default to ]

### Return type

[**models::PmarginCreateMarginOrderOcoV1Resp**](PmarginCreateMarginOrderOcoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_margin_order_v1

> models::PmarginCreateMarginOrderV1Resp pmargin_create_margin_order_v1(side, symbol, timestamp, r#type, auto_repay_at_cancel, iceberg_qty, new_client_order_id, new_order_resp_type, price, quantity, quote_order_qty, recv_window, self_trade_prevention_mode, side_effect_type, stop_price, time_in_force)
New Margin Order(TRADE)

New Margin Order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**auto_repay_at_cancel** | Option<**bool**> |  |  |
**iceberg_qty** | Option<**String**> |  |  |[default to ]
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

[**models::PmarginCreateMarginOrderV1Resp**](PmarginCreateMarginOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_margin_repay_debt_v1

> models::PmarginCreateMarginRepayDebtV1Resp pmargin_create_margin_repay_debt_v1(asset, timestamp, amount, recv_window, specify_repay_assets)
Margin Account Repay Debt(TRADE)

Repay debt for a margin loan.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**amount** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**specify_repay_assets** | Option<**String**> |  |  |[default to ]

### Return type

[**models::PmarginCreateMarginRepayDebtV1Resp**](PmarginCreateMarginRepayDebtV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_repay_loan_v1

> models::PmarginCreateRepayLoanV1Resp pmargin_create_repay_loan_v1(amount, asset, timestamp, recv_window)
Margin Account Repay(MARGIN)

Repay for a margin loan.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginCreateRepayLoanV1Resp**](PmarginCreateRepayLoanV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_um_conditional_order_v1

> models::PmarginCreateUmConditionalOrderV1Resp pmargin_create_um_conditional_order_v1(side, strategy_type, symbol, timestamp, activation_price, callback_rate, good_till_date, new_client_strategy_id, position_side, price, price_match, price_protect, quantity, recv_window, reduce_only, self_trade_prevention_mode, stop_price, time_in_force, working_type)
New UM Conditional Order (TRADE)

Place new UM conditional order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**side** | **String** |  | [required] |[default to ]
**strategy_type** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**activation_price** | Option<**String**> |  |  |[default to ]
**callback_rate** | Option<**String**> |  |  |[default to ]
**good_till_date** | Option<**i64**> |  |  |
**new_client_strategy_id** | Option<**String**> |  |  |[default to ]
**position_side** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**price_match** | Option<**String**> |  |  |[default to ]
**price_protect** | Option<**String**> |  |  |[default to ]
**quantity** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**reduce_only** | Option<**String**> |  |  |[default to ]
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**stop_price** | Option<**String**> |  |  |[default to ]
**time_in_force** | Option<**String**> |  |  |[default to ]
**working_type** | Option<**String**> |  |  |[default to ]

### Return type

[**models::PmarginCreateUmConditionalOrderV1Resp**](PmarginCreateUmConditionalOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_um_fee_burn_v1

> models::PmarginCreateUmFeeBurnV1Resp pmargin_create_um_fee_burn_v1(fee_burn, timestamp, recv_window)
Toggle BNB Burn On UM Futures Trade (TRADE)

Change user's BNB Fee Discount for UM Futures (Fee Discount On or Fee Discount Off ) on EVERY symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**fee_burn** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginCreateUmFeeBurnV1Resp**](PmarginCreateUmFeeBurnV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_create_um_order_v1

> models::PmarginCreateUmOrderV1Resp pmargin_create_um_order_v1(side, symbol, timestamp, r#type, good_till_date, new_client_order_id, new_order_resp_type, position_side, price, price_match, quantity, recv_window, reduce_only, self_trade_prevention_mode, time_in_force)
New UM Order (TRADE)

Place new UM order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**r#type** | **String** |  | [required] |[default to ]
**good_till_date** | Option<**i64**> |  |  |
**new_client_order_id** | Option<**String**> |  |  |[default to ]
**new_order_resp_type** | Option<**String**> |  |  |[default to ]
**position_side** | Option<**String**> |  |  |[default to ]
**price** | Option<**String**> |  |  |[default to ]
**price_match** | Option<**String**> |  |  |[default to ]
**quantity** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |
**reduce_only** | Option<**String**> |  |  |[default to ]
**self_trade_prevention_mode** | Option<**String**> |  |  |[default to ]
**time_in_force** | Option<**String**> |  |  |[default to ]

### Return type

[**models::PmarginCreateUmOrderV1Resp**](PmarginCreateUmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_delete_cm_all_open_orders_v1

> models::PmarginDeleteCmAllOpenOrdersV1Resp pmargin_delete_cm_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel All CM Open Orders(TRADE)

Cancel all active LIMIT orders on specific symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginDeleteCmAllOpenOrdersV1Resp**](PmarginDeleteCmAllOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_delete_cm_conditional_all_open_orders_v1

> models::PmarginDeleteCmConditionalAllOpenOrdersV1Resp pmargin_delete_cm_conditional_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel All CM Open Conditional Orders(TRADE)

Cancel All CM Open Conditional Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginDeleteCmConditionalAllOpenOrdersV1Resp**](PmarginDeleteCmConditionalAllOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_delete_cm_conditional_order_v1

> models::PmarginDeleteCmConditionalOrderV1Resp pmargin_delete_cm_conditional_order_v1(symbol, timestamp, strategy_id, new_client_strategy_id, recv_window)
Cancel CM Conditional Order(TRADE)

Cancel CM Conditional Order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**strategy_id** | Option<**i64**> |  |  |
**new_client_strategy_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginDeleteCmConditionalOrderV1Resp**](PmarginDeleteCmConditionalOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_delete_cm_order_v1

> models::PmarginDeleteCmOrderV1Resp pmargin_delete_cm_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
Cancel CM Order(TRADE)

Cancel an active LIMIT order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginDeleteCmOrderV1Resp**](PmarginDeleteCmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_delete_margin_all_open_orders_v1

> Vec<models::PmarginDeleteMarginAllOpenOrdersV1RespInner> pmargin_delete_margin_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel Margin Account All Open Orders on a Symbol(TRADE)

Cancel Margin Account All Open Orders on a Symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::PmarginDeleteMarginAllOpenOrdersV1RespInner>**](PmarginDeleteMarginAllOpenOrdersV1Resp_inner.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_delete_margin_order_list_v1

> models::PmarginDeleteMarginOrderListV1Resp pmargin_delete_margin_order_list_v1(symbol, timestamp, order_list_id, list_client_order_id, new_client_order_id, recv_window)
Cancel Margin Account OCO Orders(TRADE)

Cancel Margin Account OCO Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_list_id** | Option<**i64**> | Either `orderListId` or `listClientOrderId` must be provided |  |
**list_client_order_id** | Option<**String**> | Either `orderListId` or `listClientOrderId` must be provided |  |[default to ]
**new_client_order_id** | Option<**String**> | Used to uniquely identify this cancel. Automatically generated by default |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::PmarginDeleteMarginOrderListV1Resp**](PmarginDeleteMarginOrderListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_delete_margin_order_v1

> models::PmarginDeleteMarginOrderV1Resp pmargin_delete_margin_order_v1(symbol, timestamp, order_id, orig_client_order_id, new_client_order_id, recv_window)
Cancel Margin Account Order(TRADE)

Cancel Margin Account Order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**new_client_order_id** | Option<**String**> | Used to uniquely identify this cancel. Automatically generated by default. |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::PmarginDeleteMarginOrderV1Resp**](PmarginDeleteMarginOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_delete_um_all_open_orders_v1

> models::PmarginDeleteUmAllOpenOrdersV1Resp pmargin_delete_um_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel All UM Open Orders(TRADE)

Cancel all active LIMIT orders on specific symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginDeleteUmAllOpenOrdersV1Resp**](PmarginDeleteUmAllOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_delete_um_conditional_all_open_orders_v1

> models::PmarginDeleteUmConditionalAllOpenOrdersV1Resp pmargin_delete_um_conditional_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel All UM Open Conditional Orders (TRADE)

Cancel All UM Open Conditional Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginDeleteUmConditionalAllOpenOrdersV1Resp**](PmarginDeleteUmConditionalAllOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_delete_um_conditional_order_v1

> models::PmarginDeleteUmConditionalOrderV1Resp pmargin_delete_um_conditional_order_v1(symbol, timestamp, strategy_id, new_client_strategy_id, recv_window)
Cancel UM Conditional Order(TRADE)

Cancel UM Conditional Order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**strategy_id** | Option<**i64**> |  |  |
**new_client_strategy_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginDeleteUmConditionalOrderV1Resp**](PmarginDeleteUmConditionalOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_delete_um_order_v1

> models::PmarginDeleteUmOrderV1Resp pmargin_delete_um_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
Cancel UM Order(TRADE)

Cancel an active UM LIMIT order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginDeleteUmOrderV1Resp**](PmarginDeleteUmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_adl_quantile_v1

> Vec<models::PmarginGetCmAdlQuantileV1RespItem> pmargin_get_cm_adl_quantile_v1()
CM Position ADL Quantile Estimation(USER_DATA)

Query CM Position ADL Quantile Estimation

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::PmarginGetCmAdlQuantileV1RespItem>**](PmarginGetCmAdlQuantileV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_all_orders_v1

> Vec<models::PmarginGetCmAllOrdersV1RespItem> pmargin_get_cm_all_orders_v1(symbol, timestamp, pair, order_id, start_time, end_time, limit, recv_window)
Query All CM Orders (USER_DATA)

Get all account CM orders; active, canceled, or filled.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**pair** | Option<**String**> |  |  |[default to ]
**order_id** | Option<**i64**> |  |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 50; max 100. |  |[default to 50]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetCmAllOrdersV1RespItem>**](PmarginGetCmAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_conditional_all_orders_v1

> Vec<models::PmarginGetCmConditionalAllOrdersV1RespItem> pmargin_get_cm_conditional_all_orders_v1(timestamp, symbol, strategy_id, start_time, end_time, limit, recv_window)
Query All CM Conditional Orders(USER_DATA)

Query All CM Conditional Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**strategy_id** | Option<**i64**> |  |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetCmConditionalAllOrdersV1RespItem>**](PmarginGetCmConditionalAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_conditional_open_order_v1

> models::PmarginGetCmConditionalOpenOrderV1Resp pmargin_get_cm_conditional_open_order_v1(symbol, timestamp, strategy_id, new_client_strategy_id, recv_window)
Query Current CM Open Conditional Order(USER_DATA)

Query Current CM Open Conditional Order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**strategy_id** | Option<**i64**> |  |  |
**new_client_strategy_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetCmConditionalOpenOrderV1Resp**](PmarginGetCmConditionalOpenOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_conditional_open_orders_v1

> Vec<models::PmarginGetCmConditionalOpenOrdersV1RespItem> pmargin_get_cm_conditional_open_orders_v1(timestamp, symbol, recv_window)
Query All Current CM Open Conditional Orders (USER_DATA)

Get all open conditional orders on a symbol. Careful when accessing this with no symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetCmConditionalOpenOrdersV1RespItem>**](PmarginGetCmConditionalOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_conditional_order_history_v1

> models::PmarginGetCmConditionalOrderHistoryV1Resp pmargin_get_cm_conditional_order_history_v1(symbol, timestamp, strategy_id, new_client_strategy_id, recv_window)
Query CM Conditional Order History(USER_DATA)

Query CM Conditional Order History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**strategy_id** | Option<**i64**> |  |  |
**new_client_strategy_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetCmConditionalOrderHistoryV1Resp**](PmarginGetCmConditionalOrderHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_force_orders_v1

> Vec<models::PmarginGetCmForceOrdersV1RespItem> pmargin_get_cm_force_orders_v1(timestamp, symbol, auto_close_type, start_time, end_time, limit, recv_window)
Query User's CM Force Orders(USER_DATA)

Query User's CM Force Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**auto_close_type** | Option<**String**> | &#34;LIQUIDATION&#34; for liquidation orders, &#34;ADL&#34; for ADL orders. |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 50; max 100. |  |[default to 50]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::PmarginGetCmForceOrdersV1RespItem>**](PmarginGetCmForceOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_open_order_v1

> models::PmarginGetCmOpenOrderV1Resp pmargin_get_cm_open_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
Query Current CM Open Order (USER_DATA)

Query current CM open order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetCmOpenOrderV1Resp**](PmarginGetCmOpenOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_open_orders_v1

> Vec<models::PmarginGetCmOpenOrdersV1RespItem> pmargin_get_cm_open_orders_v1(timestamp, symbol, pair, recv_window)
Query All Current CM Open Orders(USER_DATA)

Get all open orders on a symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetCmOpenOrdersV1RespItem>**](PmarginGetCmOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_order_amendment_v1

> Vec<models::PmarginGetCmOrderAmendmentV1RespItem> pmargin_get_cm_order_amendment_v1(symbol, timestamp, order_id, orig_client_order_id, start_time, end_time, limit, recv_window)
Query CM Modify Order History(TRADE)

Get order modification history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get modification history from INCLUSIVE |  |
**end_time** | Option<**i64**> | Timestamp in ms to get modification history until INCLUSIVE |  |
**limit** | Option<**i32**> | Default 50, max 100 |  |[default to 50]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetCmOrderAmendmentV1RespItem>**](PmarginGetCmOrderAmendmentV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_order_v1

> models::PmarginGetCmOrderV1Resp pmargin_get_cm_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
Query CM Order(USER_DATA)

Check an CM order's status.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetCmOrderV1Resp**](PmarginGetCmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_cm_user_trades_v1

> Vec<models::PmarginGetCmUserTradesV1RespItem> pmargin_get_cm_user_trades_v1(timestamp, symbol, pair, start_time, end_time, from_id, limit, recv_window)
CM Account Trade List(USER_DATA)

Get trades for a specific account and CM symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**from_id** | Option<**i64**> | Trade id to fetch from. Default gets most recent trades. |  |
**limit** | Option<**i32**> | Default 50; max 1000. |  |[default to 50]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetCmUserTradesV1RespItem>**](PmarginGetCmUserTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_all_order_list_v1

> Vec<models::PmarginGetMarginAllOrderListV1RespItem> pmargin_get_margin_all_order_list_v1(timestamp, from_id, start_time, end_time, limit, recv_window)
Query Margin Account's all OCO (USER_DATA)

Query all OCO for a specific margin account based on provided optional parameters

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**from_id** | Option<**i64**> | If supplied, neither startTime or endTime can be provided |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500; max 500. |  |[default to 500]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::PmarginGetMarginAllOrderListV1RespItem>**](PmarginGetMarginAllOrderListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_all_orders_v1

> Vec<models::PmarginGetMarginAllOrdersV1RespItem> pmargin_get_margin_all_orders_v1(symbol, timestamp, order_id, start_time, end_time, limit, recv_window)
Query All Margin Account Orders (USER_DATA)

Query All Margin Account Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500; max 500. |  |[default to 500]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::PmarginGetMarginAllOrdersV1RespItem>**](PmarginGetMarginAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_force_orders_v1

> models::PmarginGetMarginForceOrdersV1Resp pmargin_get_margin_force_orders_v1(timestamp, start_time, end_time, current, size, recv_window)
Query User's Margin Force Orders(USER_DATA)

Query user's margin force orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::PmarginGetMarginForceOrdersV1Resp**](PmarginGetMarginForceOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_my_trades_v1

> Vec<models::PmarginGetMarginMyTradesV1RespItem> pmargin_get_margin_my_trades_v1(symbol, timestamp, order_id, start_time, end_time, from_id, limit, recv_window)
Margin Account Trade List (USER_DATA)

Margin Account Trade List

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**from_id** | Option<**i64**> | TradeId to fetch from. Default gets most recent trades. |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::PmarginGetMarginMyTradesV1RespItem>**](PmarginGetMarginMyTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_open_order_list_v1

> Vec<models::PmarginGetMarginOpenOrderListV1RespItem> pmargin_get_margin_open_order_list_v1(timestamp, recv_window)
Query Margin Account's Open OCO (USER_DATA)

Query Margin Account's Open OCO

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::PmarginGetMarginOpenOrderListV1RespItem>**](PmarginGetMarginOpenOrderListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_open_orders_v1

> Vec<models::PmarginGetMarginOpenOrdersV1RespItem> pmargin_get_margin_open_orders_v1(symbol, timestamp, recv_window)
Query Current Margin Open Order (USER_DATA)

Query Current Margin Open Order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::PmarginGetMarginOpenOrdersV1RespItem>**](PmarginGetMarginOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_order_list_v1

> models::PmarginGetMarginOrderListV1Resp pmargin_get_margin_order_list_v1(timestamp, order_list_id, orig_client_order_id, recv_window)
Query Margin Account's OCO (USER_DATA)

Retrieves a specific OCO based on provided optional parameters

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**order_list_id** | Option<**i64**> | Either orderListId or origClientOrderId must be provided |  |
**orig_client_order_id** | Option<**String**> | Either orderListId or origClientOrderId must be provided |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::PmarginGetMarginOrderListV1Resp**](PmarginGetMarginOrderListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_margin_order_v1

> models::PmarginGetMarginOrderV1Resp pmargin_get_margin_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
Query Margin Account Order (USER_DATA)

Query Margin Account Order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::PmarginGetMarginOrderV1Resp**](PmarginGetMarginOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_adl_quantile_v1

> Vec<models::PmarginGetUmAdlQuantileV1RespItem> pmargin_get_um_adl_quantile_v1(timestamp, symbol, recv_window)
UM Position ADL Quantile Estimation(USER_DATA)

Query UM Position ADL Quantile Estimation

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetUmAdlQuantileV1RespItem>**](PmarginGetUmAdlQuantileV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_all_orders_v1

> Vec<models::PmarginGetUmAllOrdersV1RespItem> pmargin_get_um_all_orders_v1(symbol, timestamp, order_id, start_time, end_time, limit, recv_window)
Query All UM Orders(USER_DATA)

Get all account UM orders; active, canceled, or filled.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetUmAllOrdersV1RespItem>**](PmarginGetUmAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_conditional_all_orders_v1

> Vec<models::PmarginGetUmConditionalAllOrdersV1RespItem> pmargin_get_um_conditional_all_orders_v1(timestamp, symbol, strategy_id, start_time, end_time, limit, recv_window)
Query All UM Conditional Orders(USER_DATA)

Query All UM Conditional Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**strategy_id** | Option<**i64**> |  |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetUmConditionalAllOrdersV1RespItem>**](PmarginGetUmConditionalAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_conditional_open_order_v1

> models::PmarginGetUmConditionalOpenOrderV1Resp pmargin_get_um_conditional_open_order_v1(symbol, timestamp, strategy_id, new_client_strategy_id, recv_window)
Query Current UM Open Conditional Order(USER_DATA)

Query Current UM Open Conditional Order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**strategy_id** | Option<**i64**> |  |  |
**new_client_strategy_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmConditionalOpenOrderV1Resp**](PmarginGetUmConditionalOpenOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_conditional_open_orders_v1

> Vec<models::PmarginGetUmConditionalOpenOrdersV1RespItem> pmargin_get_um_conditional_open_orders_v1()
Query All Current UM Open Conditional Orders(USER_DATA)

Get all open conditional orders on a symbol.

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::PmarginGetUmConditionalOpenOrdersV1RespItem>**](PmarginGetUmConditionalOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_conditional_order_history_v1

> models::PmarginGetUmConditionalOrderHistoryV1Resp pmargin_get_um_conditional_order_history_v1(symbol, timestamp, strategy_id, new_client_strategy_id, recv_window)
Query UM Conditional Order History(USER_DATA)

Query UM Conditional Order History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**strategy_id** | Option<**i64**> |  |  |
**new_client_strategy_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmConditionalOrderHistoryV1Resp**](PmarginGetUmConditionalOrderHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_fee_burn_v1

> models::PmarginGetUmFeeBurnV1Resp pmargin_get_um_fee_burn_v1(timestamp, recv_window)
Get UM Futures BNB Burn Status (USER_DATA)

Get user's BNB Fee Discount for UM Futures (Fee Discount On or Fee Discount Off )

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmFeeBurnV1Resp**](PmarginGetUmFeeBurnV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_force_orders_v1

> Vec<models::PmarginGetUmForceOrdersV1RespItem> pmargin_get_um_force_orders_v1(timestamp, symbol, auto_close_type, start_time, end_time, limit, recv_window)
Query User's UM Force Orders (USER_DATA)

Query User's UM Force Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**auto_close_type** | Option<**String**> | `LIQUIDATION` for liquidation orders, `ADL` for ADL orders. |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**limit** | Option<**i32**> | Default 50; max 100. |  |[default to 50]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::PmarginGetUmForceOrdersV1RespItem>**](PmarginGetUmForceOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_open_order_v1

> models::PmarginGetUmOpenOrderV1Resp pmargin_get_um_open_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
Query Current UM Open Order(USER_DATA)

Query current UM open order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmOpenOrderV1Resp**](PmarginGetUmOpenOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_open_orders_v1

> Vec<models::PmarginGetUmOpenOrdersV1RespItem> pmargin_get_um_open_orders_v1(timestamp, symbol, recv_window)
Query All Current UM Open Orders(USER_DATA)

Get all open orders on a symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetUmOpenOrdersV1RespItem>**](PmarginGetUmOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_order_amendment_v1

> Vec<models::PmarginGetUmOrderAmendmentV1RespItem> pmargin_get_um_order_amendment_v1(symbol, timestamp, order_id, orig_client_order_id, start_time, end_time, limit, recv_window)
Query UM Modify Order History(TRADE)

Get order modification history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get modification history from INCLUSIVE |  |
**end_time** | Option<**i64**> | Timestamp in ms to get modification history until INCLUSIVE |  |
**limit** | Option<**i32**> | Default 500, max 1000 |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetUmOrderAmendmentV1RespItem>**](PmarginGetUmOrderAmendmentV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_order_v1

> models::PmarginGetUmOrderV1Resp pmargin_get_um_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
Query UM Order (USER_DATA)

Check an UM order's status.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetUmOrderV1Resp**](PmarginGetUmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_get_um_user_trades_v1

> Vec<models::PmarginGetUmUserTradesV1RespItem> pmargin_get_um_user_trades_v1(symbol, timestamp, start_time, end_time, from_id, limit, recv_window)
UM Account Trade List(USER_DATA)

Get trades for a specific account and UM symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**from_id** | Option<**i64**> | Trade id to fetch from. Default gets most recent trades. |  |
**limit** | Option<**i32**> | Default 500; max 1000. |  |[default to 500]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::PmarginGetUmUserTradesV1RespItem>**](PmarginGetUmUserTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_update_cm_order_v1

> models::PmarginUpdateCmOrderV1Resp pmargin_update_cm_order_v1(price, quantity, side, symbol, timestamp, order_id, orig_client_order_id, price_match, recv_window)
Modify CM Order(TRADE)

Order modify function, currently only LIMIT order modification is supported, modified orders will be reordered in the match queue

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**price** | **String** |  | [required] |[default to ]
**quantity** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**price_match** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginUpdateCmOrderV1Resp**](PmarginUpdateCmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## pmargin_update_um_order_v1

> models::PmarginUpdateUmOrderV1Resp pmargin_update_um_order_v1(price, quantity, side, symbol, timestamp, order_id, orig_client_order_id, price_match, recv_window)
Modify UM Order(TRADE)

Order modify function, currently only LIMIT order modification is supported, modified orders will be reordered in the match queue

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**price** | **String** |  | [required] |[default to ]
**quantity** | **String** |  | [required] |[default to ]
**side** | **String** |  | [required] |[default to ]
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**order_id** | Option<**i64**> |  |  |
**orig_client_order_id** | Option<**String**> |  |  |[default to ]
**price_match** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginUpdateUmOrderV1Resp**](PmarginUpdateUmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

