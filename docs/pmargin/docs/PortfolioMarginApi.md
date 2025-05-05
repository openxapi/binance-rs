# \PortfolioMarginApi

All URIs are relative to *https://papi.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_asset_collection_v1**](PortfolioMarginApi.md#create_asset_collection_v1) | **POST** /papi/v1/asset-collection | Fund Collection by Asset(TRADE)
[**create_auto_collection_v1**](PortfolioMarginApi.md#create_auto_collection_v1) | **POST** /papi/v1/auto-collection | Fund Auto-collection(TRADE)
[**create_bnb_transfer_v1**](PortfolioMarginApi.md#create_bnb_transfer_v1) | **POST** /papi/v1/bnb-transfer | BNB transfer (TRADE)
[**create_cm_conditional_order_v1**](PortfolioMarginApi.md#create_cm_conditional_order_v1) | **POST** /papi/v1/cm/conditional/order | New CM Conditional Order(TRADE)
[**create_cm_leverage_v1**](PortfolioMarginApi.md#create_cm_leverage_v1) | **POST** /papi/v1/cm/leverage | Change CM Initial Leverage (TRADE)
[**create_cm_order_v1**](PortfolioMarginApi.md#create_cm_order_v1) | **POST** /papi/v1/cm/order | New CM Order(TRADE)
[**create_cm_position_side_dual_v1**](PortfolioMarginApi.md#create_cm_position_side_dual_v1) | **POST** /papi/v1/cm/positionSide/dual | Change CM Position Mode(TRADE)
[**create_listen_key_v1**](PortfolioMarginApi.md#create_listen_key_v1) | **POST** /papi/v1/listenKey | Start User Data Stream(USER_STREAM)
[**create_margin_loan_v1**](PortfolioMarginApi.md#create_margin_loan_v1) | **POST** /papi/v1/marginLoan | Margin Account Borrow(MARGIN)
[**create_margin_order_oco_v1**](PortfolioMarginApi.md#create_margin_order_oco_v1) | **POST** /papi/v1/margin/order/oco | Margin Account New OCO(TRADE)
[**create_margin_order_v1**](PortfolioMarginApi.md#create_margin_order_v1) | **POST** /papi/v1/margin/order | New Margin Order(TRADE)
[**create_margin_repay_debt_v1**](PortfolioMarginApi.md#create_margin_repay_debt_v1) | **POST** /papi/v1/margin/repay-debt | Margin Account Repay Debt(TRADE)
[**create_repay_futures_negative_balance_v1**](PortfolioMarginApi.md#create_repay_futures_negative_balance_v1) | **POST** /papi/v1/repay-futures-negative-balance | Repay futures Negative Balance(USER_DATA)
[**create_repay_futures_switch_v1**](PortfolioMarginApi.md#create_repay_futures_switch_v1) | **POST** /papi/v1/repay-futures-switch | Change Auto-repay-futures Status(TRADE)
[**create_repay_loan_v1**](PortfolioMarginApi.md#create_repay_loan_v1) | **POST** /papi/v1/repayLoan | Margin Account Repay(MARGIN)
[**create_um_conditional_order_v1**](PortfolioMarginApi.md#create_um_conditional_order_v1) | **POST** /papi/v1/um/conditional/order | New UM Conditional Order (TRADE)
[**create_um_fee_burn_v1**](PortfolioMarginApi.md#create_um_fee_burn_v1) | **POST** /papi/v1/um/feeBurn | Toggle BNB Burn On UM Futures Trade (TRADE)
[**create_um_leverage_v1**](PortfolioMarginApi.md#create_um_leverage_v1) | **POST** /papi/v1/um/leverage | Change UM Initial Leverage(TRADE)
[**create_um_order_v1**](PortfolioMarginApi.md#create_um_order_v1) | **POST** /papi/v1/um/order | New UM Order (TRADE)
[**create_um_position_side_dual_v1**](PortfolioMarginApi.md#create_um_position_side_dual_v1) | **POST** /papi/v1/um/positionSide/dual | Change UM Position Mode(TRADE)
[**delete_cm_all_open_orders_v1**](PortfolioMarginApi.md#delete_cm_all_open_orders_v1) | **DELETE** /papi/v1/cm/allOpenOrders | Cancel All CM Open Orders(TRADE)
[**delete_cm_conditional_all_open_orders_v1**](PortfolioMarginApi.md#delete_cm_conditional_all_open_orders_v1) | **DELETE** /papi/v1/cm/conditional/allOpenOrders | Cancel All CM Open Conditional Orders(TRADE)
[**delete_cm_conditional_order_v1**](PortfolioMarginApi.md#delete_cm_conditional_order_v1) | **DELETE** /papi/v1/cm/conditional/order | Cancel CM Conditional Order(TRADE)
[**delete_cm_order_v1**](PortfolioMarginApi.md#delete_cm_order_v1) | **DELETE** /papi/v1/cm/order | Cancel CM Order(TRADE)
[**delete_listen_key_v1**](PortfolioMarginApi.md#delete_listen_key_v1) | **DELETE** /papi/v1/listenKey | Close User Data Stream(USER_STREAM)
[**delete_margin_all_open_orders_v1**](PortfolioMarginApi.md#delete_margin_all_open_orders_v1) | **DELETE** /papi/v1/margin/allOpenOrders | Cancel Margin Account All Open Orders on a Symbol(TRADE)
[**delete_margin_order_list_v1**](PortfolioMarginApi.md#delete_margin_order_list_v1) | **DELETE** /papi/v1/margin/orderList | Cancel Margin Account OCO Orders(TRADE)
[**delete_margin_order_v1**](PortfolioMarginApi.md#delete_margin_order_v1) | **DELETE** /papi/v1/margin/order | Cancel Margin Account Order(TRADE)
[**delete_um_all_open_orders_v1**](PortfolioMarginApi.md#delete_um_all_open_orders_v1) | **DELETE** /papi/v1/um/allOpenOrders | Cancel All UM Open Orders(TRADE)
[**delete_um_conditional_all_open_orders_v1**](PortfolioMarginApi.md#delete_um_conditional_all_open_orders_v1) | **DELETE** /papi/v1/um/conditional/allOpenOrders | Cancel All UM Open Conditional Orders (TRADE)
[**delete_um_conditional_order_v1**](PortfolioMarginApi.md#delete_um_conditional_order_v1) | **DELETE** /papi/v1/um/conditional/order | Cancel UM Conditional Order(TRADE)
[**delete_um_order_v1**](PortfolioMarginApi.md#delete_um_order_v1) | **DELETE** /papi/v1/um/order | Cancel UM Order(TRADE)
[**get_account_v1**](PortfolioMarginApi.md#get_account_v1) | **GET** /papi/v1/account | Account Information(USER_DATA)
[**get_balance_v1**](PortfolioMarginApi.md#get_balance_v1) | **GET** /papi/v1/balance | Account Balance(USER_DATA)
[**get_cm_account_v1**](PortfolioMarginApi.md#get_cm_account_v1) | **GET** /papi/v1/cm/account | Get CM Account Detail(USER_DATA)
[**get_cm_adl_quantile_v1**](PortfolioMarginApi.md#get_cm_adl_quantile_v1) | **GET** /papi/v1/cm/adlQuantile | CM Position ADL Quantile Estimation(USER_DATA)
[**get_cm_all_orders_v1**](PortfolioMarginApi.md#get_cm_all_orders_v1) | **GET** /papi/v1/cm/allOrders | Query All CM Orders (USER_DATA)
[**get_cm_commission_rate_v1**](PortfolioMarginApi.md#get_cm_commission_rate_v1) | **GET** /papi/v1/cm/commissionRate | Get User Commission Rate for CM(USER_DATA)
[**get_cm_conditional_all_orders_v1**](PortfolioMarginApi.md#get_cm_conditional_all_orders_v1) | **GET** /papi/v1/cm/conditional/allOrders | Query All CM Conditional Orders(USER_DATA)
[**get_cm_conditional_open_order_v1**](PortfolioMarginApi.md#get_cm_conditional_open_order_v1) | **GET** /papi/v1/cm/conditional/openOrder | Query Current CM Open Conditional Order(USER_DATA)
[**get_cm_conditional_open_orders_v1**](PortfolioMarginApi.md#get_cm_conditional_open_orders_v1) | **GET** /papi/v1/cm/conditional/openOrders | Query All Current CM Open Conditional Orders (USER_DATA)
[**get_cm_conditional_order_history_v1**](PortfolioMarginApi.md#get_cm_conditional_order_history_v1) | **GET** /papi/v1/cm/conditional/orderHistory | Query CM Conditional Order History(USER_DATA)
[**get_cm_force_orders_v1**](PortfolioMarginApi.md#get_cm_force_orders_v1) | **GET** /papi/v1/cm/forceOrders | Query User's CM Force Orders(USER_DATA)
[**get_cm_income_v1**](PortfolioMarginApi.md#get_cm_income_v1) | **GET** /papi/v1/cm/income | Get CM Income History(USER_DATA)
[**get_cm_leverage_bracket_v1**](PortfolioMarginApi.md#get_cm_leverage_bracket_v1) | **GET** /papi/v1/cm/leverageBracket | CM Notional and Leverage Brackets(USER_DATA)
[**get_cm_open_order_v1**](PortfolioMarginApi.md#get_cm_open_order_v1) | **GET** /papi/v1/cm/openOrder | Query Current CM Open Order (USER_DATA)
[**get_cm_open_orders_v1**](PortfolioMarginApi.md#get_cm_open_orders_v1) | **GET** /papi/v1/cm/openOrders | Query All Current CM Open Orders(USER_DATA)
[**get_cm_order_amendment_v1**](PortfolioMarginApi.md#get_cm_order_amendment_v1) | **GET** /papi/v1/cm/orderAmendment | Query CM Modify Order History(TRADE)
[**get_cm_order_v1**](PortfolioMarginApi.md#get_cm_order_v1) | **GET** /papi/v1/cm/order | Query CM Order(USER_DATA)
[**get_cm_position_risk_v1**](PortfolioMarginApi.md#get_cm_position_risk_v1) | **GET** /papi/v1/cm/positionRisk | Query CM Position Information(USER_DATA)
[**get_cm_position_side_dual_v1**](PortfolioMarginApi.md#get_cm_position_side_dual_v1) | **GET** /papi/v1/cm/positionSide/dual | Get CM Current Position Mode(USER_DATA)
[**get_cm_user_trades_v1**](PortfolioMarginApi.md#get_cm_user_trades_v1) | **GET** /papi/v1/cm/userTrades | CM Account Trade List(USER_DATA)
[**get_margin_all_order_list_v1**](PortfolioMarginApi.md#get_margin_all_order_list_v1) | **GET** /papi/v1/margin/allOrderList | Query Margin Account's all OCO (USER_DATA)
[**get_margin_all_orders_v1**](PortfolioMarginApi.md#get_margin_all_orders_v1) | **GET** /papi/v1/margin/allOrders | Query All Margin Account Orders (USER_DATA)
[**get_margin_force_orders_v1**](PortfolioMarginApi.md#get_margin_force_orders_v1) | **GET** /papi/v1/margin/forceOrders | Query User's Margin Force Orders(USER_DATA)
[**get_margin_margin_interest_history_v1**](PortfolioMarginApi.md#get_margin_margin_interest_history_v1) | **GET** /papi/v1/margin/marginInterestHistory | Get Margin Borrow/Loan Interest History(USER_DATA)
[**get_margin_margin_loan_v1**](PortfolioMarginApi.md#get_margin_margin_loan_v1) | **GET** /papi/v1/margin/marginLoan | Query Margin Loan Record(USER_DATA)
[**get_margin_max_borrowable_v1**](PortfolioMarginApi.md#get_margin_max_borrowable_v1) | **GET** /papi/v1/margin/maxBorrowable | Margin Max Borrow(USER_DATA)
[**get_margin_max_withdraw_v1**](PortfolioMarginApi.md#get_margin_max_withdraw_v1) | **GET** /papi/v1/margin/maxWithdraw | Query Margin Max Withdraw(USER_DATA)
[**get_margin_my_trades_v1**](PortfolioMarginApi.md#get_margin_my_trades_v1) | **GET** /papi/v1/margin/myTrades | Margin Account Trade List (USER_DATA)
[**get_margin_open_order_list_v1**](PortfolioMarginApi.md#get_margin_open_order_list_v1) | **GET** /papi/v1/margin/openOrderList | Query Margin Account's Open OCO (USER_DATA)
[**get_margin_open_orders_v1**](PortfolioMarginApi.md#get_margin_open_orders_v1) | **GET** /papi/v1/margin/openOrders | Query Current Margin Open Order (USER_DATA)
[**get_margin_order_list_v1**](PortfolioMarginApi.md#get_margin_order_list_v1) | **GET** /papi/v1/margin/orderList | Query Margin Account's OCO (USER_DATA)
[**get_margin_order_v1**](PortfolioMarginApi.md#get_margin_order_v1) | **GET** /papi/v1/margin/order | Query Margin Account Order (USER_DATA)
[**get_margin_repay_loan_v1**](PortfolioMarginApi.md#get_margin_repay_loan_v1) | **GET** /papi/v1/margin/repayLoan | Query Margin repay Record(USER_DATA)
[**get_ping_v1**](PortfolioMarginApi.md#get_ping_v1) | **GET** /papi/v1/ping | Test Connectivity
[**get_portfolio_interest_history_v1**](PortfolioMarginApi.md#get_portfolio_interest_history_v1) | **GET** /papi/v1/portfolio/interest-history | Query Portfolio Margin Negative Balance Interest History(USER_DATA)
[**get_portfolio_negative_balance_exchange_record_v1**](PortfolioMarginApi.md#get_portfolio_negative_balance_exchange_record_v1) | **GET** /papi/v1/portfolio/negative-balance-exchange-record | Query User Negative Balance Auto Exchange Record (USER_DATA)
[**get_rate_limit_order_v1**](PortfolioMarginApi.md#get_rate_limit_order_v1) | **GET** /papi/v1/rateLimit/order | Query User Rate Limit (USER_DATA)
[**get_repay_futures_switch_v1**](PortfolioMarginApi.md#get_repay_futures_switch_v1) | **GET** /papi/v1/repay-futures-switch | Get Auto-repay-futures Status(USER_DATA)
[**get_um_account_config_v1**](PortfolioMarginApi.md#get_um_account_config_v1) | **GET** /papi/v1/um/accountConfig | UM Futures Account Configuration(USER_DATA)
[**get_um_account_v1**](PortfolioMarginApi.md#get_um_account_v1) | **GET** /papi/v1/um/account | Get UM Account Detail(USER_DATA)
[**get_um_account_v2**](PortfolioMarginApi.md#get_um_account_v2) | **GET** /papi/v2/um/account | Get UM Account Detail V2(USER_DATA)
[**get_um_adl_quantile_v1**](PortfolioMarginApi.md#get_um_adl_quantile_v1) | **GET** /papi/v1/um/adlQuantile | UM Position ADL Quantile Estimation(USER_DATA)
[**get_um_all_orders_v1**](PortfolioMarginApi.md#get_um_all_orders_v1) | **GET** /papi/v1/um/allOrders | Query All UM Orders(USER_DATA)
[**get_um_api_trading_status_v1**](PortfolioMarginApi.md#get_um_api_trading_status_v1) | **GET** /papi/v1/um/apiTradingStatus | Portfolio Margin UM Trading Quantitative Rules Indicators(USER_DATA)
[**get_um_commission_rate_v1**](PortfolioMarginApi.md#get_um_commission_rate_v1) | **GET** /papi/v1/um/commissionRate | Get User Commission Rate for UM(USER_DATA)
[**get_um_conditional_all_orders_v1**](PortfolioMarginApi.md#get_um_conditional_all_orders_v1) | **GET** /papi/v1/um/conditional/allOrders | Query All UM Conditional Orders(USER_DATA)
[**get_um_conditional_open_order_v1**](PortfolioMarginApi.md#get_um_conditional_open_order_v1) | **GET** /papi/v1/um/conditional/openOrder | Query Current UM Open Conditional Order(USER_DATA)
[**get_um_conditional_open_orders_v1**](PortfolioMarginApi.md#get_um_conditional_open_orders_v1) | **GET** /papi/v1/um/conditional/openOrders | Query All Current UM Open Conditional Orders(USER_DATA)
[**get_um_conditional_order_history_v1**](PortfolioMarginApi.md#get_um_conditional_order_history_v1) | **GET** /papi/v1/um/conditional/orderHistory | Query UM Conditional Order History(USER_DATA)
[**get_um_fee_burn_v1**](PortfolioMarginApi.md#get_um_fee_burn_v1) | **GET** /papi/v1/um/feeBurn | Get UM Futures BNB Burn Status (USER_DATA)
[**get_um_force_orders_v1**](PortfolioMarginApi.md#get_um_force_orders_v1) | **GET** /papi/v1/um/forceOrders | Query User's UM Force Orders (USER_DATA)
[**get_um_income_asyn_id_v1**](PortfolioMarginApi.md#get_um_income_asyn_id_v1) | **GET** /papi/v1/um/income/asyn/id | Get UM Futures Transaction Download Link by Id(USER_DATA)
[**get_um_income_asyn_v1**](PortfolioMarginApi.md#get_um_income_asyn_v1) | **GET** /papi/v1/um/income/asyn | Get Download Id For UM Futures Transaction History (USER_DATA)
[**get_um_income_v1**](PortfolioMarginApi.md#get_um_income_v1) | **GET** /papi/v1/um/income | Get UM Income History(USER_DATA)
[**get_um_leverage_bracket_v1**](PortfolioMarginApi.md#get_um_leverage_bracket_v1) | **GET** /papi/v1/um/leverageBracket | UM Notional and Leverage Brackets (USER_DATA)
[**get_um_open_order_v1**](PortfolioMarginApi.md#get_um_open_order_v1) | **GET** /papi/v1/um/openOrder | Query Current UM Open Order(USER_DATA)
[**get_um_open_orders_v1**](PortfolioMarginApi.md#get_um_open_orders_v1) | **GET** /papi/v1/um/openOrders | Query All Current UM Open Orders(USER_DATA)
[**get_um_order_amendment_v1**](PortfolioMarginApi.md#get_um_order_amendment_v1) | **GET** /papi/v1/um/orderAmendment | Query UM Modify Order History(TRADE)
[**get_um_order_asyn_id_v1**](PortfolioMarginApi.md#get_um_order_asyn_id_v1) | **GET** /papi/v1/um/order/asyn/id | Get UM Futures Order Download Link by Id(USER_DATA)
[**get_um_order_asyn_v1**](PortfolioMarginApi.md#get_um_order_asyn_v1) | **GET** /papi/v1/um/order/asyn | Get Download Id For UM Futures Order History (USER_DATA)
[**get_um_order_v1**](PortfolioMarginApi.md#get_um_order_v1) | **GET** /papi/v1/um/order | Query UM Order (USER_DATA)
[**get_um_position_risk_v1**](PortfolioMarginApi.md#get_um_position_risk_v1) | **GET** /papi/v1/um/positionRisk | Query UM Position Information(USER_DATA)
[**get_um_position_side_dual_v1**](PortfolioMarginApi.md#get_um_position_side_dual_v1) | **GET** /papi/v1/um/positionSide/dual | Get UM Current Position Mode(USER_DATA)
[**get_um_symbol_config_v1**](PortfolioMarginApi.md#get_um_symbol_config_v1) | **GET** /papi/v1/um/symbolConfig | UM Futures Symbol Configuration(USER_DATA)
[**get_um_trade_asyn_id_v1**](PortfolioMarginApi.md#get_um_trade_asyn_id_v1) | **GET** /papi/v1/um/trade/asyn/id | Get UM Futures Trade Download Link by Id(USER_DATA)
[**get_um_trade_asyn_v1**](PortfolioMarginApi.md#get_um_trade_asyn_v1) | **GET** /papi/v1/um/trade/asyn | Get Download Id For UM Futures Trade History (USER_DATA)
[**get_um_user_trades_v1**](PortfolioMarginApi.md#get_um_user_trades_v1) | **GET** /papi/v1/um/userTrades | UM Account Trade List(USER_DATA)
[**update_cm_order_v1**](PortfolioMarginApi.md#update_cm_order_v1) | **PUT** /papi/v1/cm/order | Modify CM Order(TRADE)
[**update_listen_key_v1**](PortfolioMarginApi.md#update_listen_key_v1) | **PUT** /papi/v1/listenKey | Keepalive User Data Stream (USER_STREAM)
[**update_um_order_v1**](PortfolioMarginApi.md#update_um_order_v1) | **PUT** /papi/v1/um/order | Modify UM Order(TRADE)



## create_asset_collection_v1

> models::CreateAssetCollectionV1Resp create_asset_collection_v1(asset, timestamp, recv_window)
Fund Collection by Asset(TRADE)

Transfers specific asset from Futures Account to Margin account

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateAssetCollectionV1Resp**](CreateAssetCollectionV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_auto_collection_v1

> models::CreateAutoCollectionV1Resp create_auto_collection_v1(timestamp, recv_window)
Fund Auto-collection(TRADE)

Fund collection for Portfolio Margin

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateAutoCollectionV1Resp**](CreateAutoCollectionV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_bnb_transfer_v1

> models::CreateBnbTransferV1Resp create_bnb_transfer_v1(amount, timestamp, transfer_side, recv_window)
BNB transfer (TRADE)

Transfer BNB in and out of UM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**transfer_side** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateBnbTransferV1Resp**](CreateBnbTransferV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_cm_conditional_order_v1

> models::CreateCmConditionalOrderV1Resp create_cm_conditional_order_v1(side, strategy_type, symbol, timestamp, activation_price, callback_rate, new_client_strategy_id, position_side, price, price_protect, quantity, recv_window, reduce_only, stop_price, time_in_force, working_type)
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

[**models::CreateCmConditionalOrderV1Resp**](CreateCmConditionalOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_cm_leverage_v1

> models::CreateCmLeverageV1Resp create_cm_leverage_v1(leverage, symbol, timestamp, recv_window)
Change CM Initial Leverage (TRADE)

Change user's initial leverage of specific symbol in CM.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**leverage** | **i32** |  | [required] |
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateCmLeverageV1Resp**](CreateCmLeverageV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_cm_order_v1

> models::CreateCmOrderV1Resp create_cm_order_v1(side, symbol, timestamp, r#type, new_client_order_id, new_order_resp_type, position_side, price, price_match, quantity, recv_window, reduce_only, time_in_force)
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

[**models::CreateCmOrderV1Resp**](CreateCmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_cm_position_side_dual_v1

> models::CreateCmPositionSideDualV1Resp create_cm_position_side_dual_v1(dual_side_position, timestamp, recv_window)
Change CM Position Mode(TRADE)

Change user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol in CM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**dual_side_position** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateCmPositionSideDualV1Resp**](CreateCmPositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_listen_key_v1

> models::CreateListenKeyV1Resp create_listen_key_v1()
Start User Data Stream(USER_STREAM)

Start a new user data stream. The stream will close after 60 minutes unless a keepalive is sent. If the account has an active listenKey, that listenKey will be returned and its validity will be extended for 60 minutes.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::CreateListenKeyV1Resp**](CreateListenKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_loan_v1

> models::CreateMarginLoanV1Resp create_margin_loan_v1(amount, asset, timestamp, recv_window)
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

[**models::CreateMarginLoanV1Resp**](CreateMarginLoanV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_order_oco_v1

> models::CreateMarginOrderOcoV1Resp create_margin_order_oco_v1(price, quantity, side, stop_price, symbol, timestamp, limit_client_order_id, limit_iceberg_qty, list_client_order_id, new_order_resp_type, recv_window, side_effect_type, stop_client_order_id, stop_iceberg_qty, stop_limit_price, stop_limit_time_in_force)
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

[**models::CreateMarginOrderOcoV1Resp**](CreateMarginOrderOcoV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_order_v1

> models::CreateMarginOrderV1Resp create_margin_order_v1(side, symbol, timestamp, r#type, auto_repay_at_cancel, iceberg_qty, new_client_order_id, new_order_resp_type, price, quantity, quote_order_qty, recv_window, self_trade_prevention_mode, side_effect_type, stop_price, time_in_force)
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

[**models::CreateMarginOrderV1Resp**](CreateMarginOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_margin_repay_debt_v1

> models::CreateMarginRepayDebtV1Resp create_margin_repay_debt_v1(asset, timestamp, amount, recv_window, specify_repay_assets)
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

[**models::CreateMarginRepayDebtV1Resp**](CreateMarginRepayDebtV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_repay_futures_negative_balance_v1

> models::CreateRepayFuturesNegativeBalanceV1Resp create_repay_futures_negative_balance_v1(timestamp, recv_window)
Repay futures Negative Balance(USER_DATA)

Repay futures Negative Balance

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateRepayFuturesNegativeBalanceV1Resp**](CreateRepayFuturesNegativeBalanceV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_repay_futures_switch_v1

> models::CreateRepayFuturesSwitchV1Resp create_repay_futures_switch_v1(auto_repay, timestamp, recv_window)
Change Auto-repay-futures Status(TRADE)

Change Auto-repay-futures Status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**auto_repay** | **String** |  | [required] |[default to true]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateRepayFuturesSwitchV1Resp**](CreateRepayFuturesSwitchV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_repay_loan_v1

> models::CreateRepayLoanV1Resp create_repay_loan_v1(amount, asset, timestamp, recv_window)
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

[**models::CreateRepayLoanV1Resp**](CreateRepayLoanV1Resp.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_um_conditional_order_v1

> models::CreateUmConditionalOrderV1Resp create_um_conditional_order_v1(side, strategy_type, symbol, timestamp, activation_price, callback_rate, good_till_date, new_client_strategy_id, position_side, price, price_match, price_protect, quantity, recv_window, reduce_only, self_trade_prevention_mode, stop_price, time_in_force, working_type)
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

[**models::CreateUmConditionalOrderV1Resp**](CreateUmConditionalOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_um_fee_burn_v1

> models::CreateUmFeeBurnV1Resp create_um_fee_burn_v1(fee_burn, timestamp, recv_window)
Toggle BNB Burn On UM Futures Trade (TRADE)

Change user's BNB Fee Discount for UM Futures (Fee Discount On or Fee Discount Off ) on EVERY symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**fee_burn** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateUmFeeBurnV1Resp**](CreateUmFeeBurnV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_um_leverage_v1

> models::CreateUmLeverageV1Resp create_um_leverage_v1(leverage, symbol, timestamp, recv_window)
Change UM Initial Leverage(TRADE)

Change user's initial leverage of specific symbol in UM.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**leverage** | **i32** |  | [required] |
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateUmLeverageV1Resp**](CreateUmLeverageV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_um_order_v1

> models::CreateUmOrderV1Resp create_um_order_v1(side, symbol, timestamp, r#type, good_till_date, new_client_order_id, new_order_resp_type, position_side, price, price_match, quantity, recv_window, reduce_only, self_trade_prevention_mode, time_in_force)
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

[**models::CreateUmOrderV1Resp**](CreateUmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_um_position_side_dual_v1

> models::CreateUmPositionSideDualV1Resp create_um_position_side_dual_v1(dual_side_position, timestamp, recv_window)
Change UM Position Mode(TRADE)

Change user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol in UM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**dual_side_position** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateUmPositionSideDualV1Resp**](CreateUmPositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_cm_all_open_orders_v1

> models::DeleteCmAllOpenOrdersV1Resp delete_cm_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel All CM Open Orders(TRADE)

Cancel all active LIMIT orders on specific symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::DeleteCmAllOpenOrdersV1Resp**](DeleteCmAllOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_cm_conditional_all_open_orders_v1

> models::DeleteCmConditionalAllOpenOrdersV1Resp delete_cm_conditional_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel All CM Open Conditional Orders(TRADE)

Cancel All CM Open Conditional Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::DeleteCmConditionalAllOpenOrdersV1Resp**](DeleteCmConditionalAllOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_cm_conditional_order_v1

> models::DeleteCmConditionalOrderV1Resp delete_cm_conditional_order_v1(symbol, timestamp, strategy_id, new_client_strategy_id, recv_window)
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

[**models::DeleteCmConditionalOrderV1Resp**](DeleteCmConditionalOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_cm_order_v1

> models::DeleteCmOrderV1Resp delete_cm_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::DeleteCmOrderV1Resp**](DeleteCmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_listen_key_v1

> serde_json::Value delete_listen_key_v1()
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


## delete_margin_all_open_orders_v1

> Vec<models::PmarginDeleteMarginAllOpenOrdersV1RespInner> delete_margin_all_open_orders_v1(symbol, timestamp, recv_window)
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


## delete_margin_order_list_v1

> models::DeleteMarginOrderListV1Resp delete_margin_order_list_v1(symbol, timestamp, order_list_id, list_client_order_id, new_client_order_id, recv_window)
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

[**models::DeleteMarginOrderListV1Resp**](DeleteMarginOrderListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_margin_order_v1

> models::DeleteMarginOrderV1Resp delete_margin_order_v1(symbol, timestamp, order_id, orig_client_order_id, new_client_order_id, recv_window)
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

[**models::DeleteMarginOrderV1Resp**](DeleteMarginOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_um_all_open_orders_v1

> models::DeleteUmAllOpenOrdersV1Resp delete_um_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel All UM Open Orders(TRADE)

Cancel all active LIMIT orders on specific symbol

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::DeleteUmAllOpenOrdersV1Resp**](DeleteUmAllOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_um_conditional_all_open_orders_v1

> models::DeleteUmConditionalAllOpenOrdersV1Resp delete_um_conditional_all_open_orders_v1(symbol, timestamp, recv_window)
Cancel All UM Open Conditional Orders (TRADE)

Cancel All UM Open Conditional Orders

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::DeleteUmConditionalAllOpenOrdersV1Resp**](DeleteUmConditionalAllOpenOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_um_conditional_order_v1

> models::DeleteUmConditionalOrderV1Resp delete_um_conditional_order_v1(symbol, timestamp, strategy_id, new_client_strategy_id, recv_window)
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

[**models::DeleteUmConditionalOrderV1Resp**](DeleteUmConditionalOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_um_order_v1

> models::DeleteUmOrderV1Resp delete_um_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::DeleteUmOrderV1Resp**](DeleteUmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_account_v1

> models::GetAccountV1Resp get_account_v1(timestamp, recv_window)
Account Information(USER_DATA)

Query account information

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetAccountV1Resp**](GetAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_balance_v1

> models::PmarginGetBalanceV1Resp get_balance_v1(timestamp, asset, recv_window)
Account Balance(USER_DATA)

Query account balance

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::PmarginGetBalanceV1Resp**](PmarginGetBalanceV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_account_v1

> models::GetCmAccountV1Resp get_cm_account_v1(timestamp, recv_window)
Get CM Account Detail(USER_DATA)

Get current CM account asset and position information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetCmAccountV1Resp**](GetCmAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_adl_quantile_v1

> Vec<models::GetCmAdlQuantileV1RespItem> get_cm_adl_quantile_v1()
CM Position ADL Quantile Estimation(USER_DATA)

Query CM Position ADL Quantile Estimation

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::GetCmAdlQuantileV1RespItem>**](GetCmAdlQuantileV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_all_orders_v1

> Vec<models::GetCmAllOrdersV1RespItem> get_cm_all_orders_v1(symbol, timestamp, pair, order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetCmAllOrdersV1RespItem>**](GetCmAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_commission_rate_v1

> models::GetCmCommissionRateV1Resp get_cm_commission_rate_v1(symbol, timestamp, recv_window)
Get User Commission Rate for CM(USER_DATA)

Get User Commission Rate for CM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetCmCommissionRateV1Resp**](GetCmCommissionRateV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_conditional_all_orders_v1

> Vec<models::GetCmConditionalAllOrdersV1RespItem> get_cm_conditional_all_orders_v1(timestamp, symbol, strategy_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetCmConditionalAllOrdersV1RespItem>**](GetCmConditionalAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_conditional_open_order_v1

> models::GetCmConditionalOpenOrderV1Resp get_cm_conditional_open_order_v1(symbol, timestamp, strategy_id, new_client_strategy_id, recv_window)
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

[**models::GetCmConditionalOpenOrderV1Resp**](GetCmConditionalOpenOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_conditional_open_orders_v1

> Vec<models::GetCmConditionalOpenOrdersV1RespItem> get_cm_conditional_open_orders_v1(timestamp, symbol, recv_window)
Query All Current CM Open Conditional Orders (USER_DATA)

Get all open conditional orders on a symbol. Careful when accessing this with no symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetCmConditionalOpenOrdersV1RespItem>**](GetCmConditionalOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_conditional_order_history_v1

> models::GetCmConditionalOrderHistoryV1Resp get_cm_conditional_order_history_v1(symbol, timestamp, strategy_id, new_client_strategy_id, recv_window)
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

[**models::GetCmConditionalOrderHistoryV1Resp**](GetCmConditionalOrderHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_force_orders_v1

> Vec<models::GetCmForceOrdersV1RespItem> get_cm_force_orders_v1(timestamp, symbol, auto_close_type, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetCmForceOrdersV1RespItem>**](GetCmForceOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_income_v1

> Vec<models::GetCmIncomeV1RespItem> get_cm_income_v1(timestamp, symbol, income_type, start_time, end_time, page, limit, recv_window)
Get CM Income History(USER_DATA)

Get CM Income History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**income_type** | Option<**String**> | &#34;TRANSFER&#34;,&#34;WELCOME_BONUS&#34;, &#34;FUNDING_FEE&#34;, &#34;REALIZED_PNL&#34;, &#34;COMMISSION&#34;, &#34;INSURANCE_CLEAR&#34;, and &#34;DELIVERED_SETTELMENT&#34; |  |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get funding from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get funding until INCLUSIVE. |  |
**page** | Option<**i32**> |  |  |
**limit** | Option<**i32**> | Default 100; max 1000 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetCmIncomeV1RespItem>**](GetCmIncomeV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_leverage_bracket_v1

> Vec<models::GetCmLeverageBracketV1RespItem> get_cm_leverage_bracket_v1(timestamp, symbol, recv_window)
CM Notional and Leverage Brackets(USER_DATA)

Query CM notional and leverage brackets

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetCmLeverageBracketV1RespItem>**](GetCmLeverageBracketV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_open_order_v1

> models::GetCmOpenOrderV1Resp get_cm_open_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::GetCmOpenOrderV1Resp**](GetCmOpenOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_open_orders_v1

> Vec<models::GetCmOpenOrdersV1RespItem> get_cm_open_orders_v1(timestamp, symbol, pair, recv_window)
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

[**Vec<models::GetCmOpenOrdersV1RespItem>**](GetCmOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_order_amendment_v1

> Vec<models::GetCmOrderAmendmentV1RespItem> get_cm_order_amendment_v1(symbol, timestamp, order_id, orig_client_order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetCmOrderAmendmentV1RespItem>**](GetCmOrderAmendmentV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_order_v1

> models::GetCmOrderV1Resp get_cm_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::GetCmOrderV1Resp**](GetCmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_position_risk_v1

> Vec<models::GetCmPositionRiskV1RespItem> get_cm_position_risk_v1(timestamp, margin_asset, pair, recv_window)
Query CM Position Information(USER_DATA)

Get current CM position information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**margin_asset** | Option<**String**> |  |  |[default to ]
**pair** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetCmPositionRiskV1RespItem>**](GetCmPositionRiskV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_position_side_dual_v1

> models::GetCmPositionSideDualV1Resp get_cm_position_side_dual_v1(timestamp, recv_window)
Get CM Current Position Mode(USER_DATA)

Get user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol in CM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetCmPositionSideDualV1Resp**](GetCmPositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_cm_user_trades_v1

> Vec<models::GetCmUserTradesV1RespItem> get_cm_user_trades_v1(timestamp, symbol, pair, start_time, end_time, from_id, limit, recv_window)
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

[**Vec<models::GetCmUserTradesV1RespItem>**](GetCmUserTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_all_order_list_v1

> Vec<models::GetMarginAllOrderListV1RespItem> get_margin_all_order_list_v1(timestamp, from_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetMarginAllOrderListV1RespItem>**](GetMarginAllOrderListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_all_orders_v1

> Vec<models::GetMarginAllOrdersV1RespItem> get_margin_all_orders_v1(symbol, timestamp, order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetMarginAllOrdersV1RespItem>**](GetMarginAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_force_orders_v1

> models::GetMarginForceOrdersV1Resp get_margin_force_orders_v1(timestamp, start_time, end_time, current, size, recv_window)
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

[**models::GetMarginForceOrdersV1Resp**](GetMarginForceOrdersV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_margin_interest_history_v1

> models::GetMarginMarginInterestHistoryV1Resp get_margin_margin_interest_history_v1(timestamp, asset, start_time, end_time, current, size, archived, recv_window)
Get Margin Borrow/Loan Interest History(USER_DATA)

Get Margin Borrow/Loan Interest History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**archived** | Option<**String**> | Default: `false`. Set to `true` for archived data from 6 months ago |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetMarginMarginInterestHistoryV1Resp**](GetMarginMarginInterestHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_margin_loan_v1

> models::GetMarginMarginLoanV1Resp get_margin_margin_loan_v1(asset, timestamp, tx_id, start_time, end_time, current, size, archived, recv_window)
Query Margin Loan Record(USER_DATA)

Query margin loan record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**tx_id** | Option<**i64**> | the `tranId` in `POST/papi/v1/marginLoan` |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**archived** | Option<**String**> | Default: `false`. Set to `true` for archived data from 6 months ago |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetMarginMarginLoanV1Resp**](GetMarginMarginLoanV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_max_borrowable_v1

> models::GetMarginMaxBorrowableV1Resp get_margin_max_borrowable_v1(asset, timestamp, recv_window)
Margin Max Borrow(USER_DATA)

Query margin max borrow

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetMarginMaxBorrowableV1Resp**](GetMarginMaxBorrowableV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_max_withdraw_v1

> models::GetMarginMaxWithdrawV1Resp get_margin_max_withdraw_v1(asset, timestamp, recv_window)
Query Margin Max Withdraw(USER_DATA)

Query Margin Max Withdraw

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than `60000` |  |

### Return type

[**models::GetMarginMaxWithdrawV1Resp**](GetMarginMaxWithdrawV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_my_trades_v1

> Vec<models::GetMarginMyTradesV1RespItem> get_margin_my_trades_v1(symbol, timestamp, order_id, start_time, end_time, from_id, limit, recv_window)
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

[**Vec<models::GetMarginMyTradesV1RespItem>**](GetMarginMyTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_open_order_list_v1

> Vec<models::GetMarginOpenOrderListV1RespItem> get_margin_open_order_list_v1(timestamp, recv_window)
Query Margin Account's Open OCO (USER_DATA)

Query Margin Account's Open OCO

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::GetMarginOpenOrderListV1RespItem>**](GetMarginOpenOrderListV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_open_orders_v1

> Vec<models::GetMarginOpenOrdersV1RespItem> get_margin_open_orders_v1(symbol, timestamp, recv_window)
Query Current Margin Open Order (USER_DATA)

Query Current Margin Open Order

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**Vec<models::GetMarginOpenOrdersV1RespItem>**](GetMarginOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_order_list_v1

> models::GetMarginOrderListV1Resp get_margin_order_list_v1(timestamp, order_list_id, orig_client_order_id, recv_window)
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

[**models::GetMarginOrderListV1Resp**](GetMarginOrderListV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_order_v1

> models::GetMarginOrderV1Resp get_margin_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::GetMarginOrderV1Resp**](GetMarginOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_margin_repay_loan_v1

> models::GetMarginRepayLoanV1Resp get_margin_repay_loan_v1(asset, timestamp, tx_id, start_time, end_time, current, size, archived, recv_window)
Query Margin repay Record(USER_DATA)

Query margin repay record.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**asset** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**tx_id** | Option<**i64**> | the tranId in `POST/papi/v1/repayLoan` |  |
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**current** | Option<**i64**> | Currently querying page. Start from 1. Default:1 |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**archived** | Option<**String**> | Default: `false`. Set to `true` for archived data from 6 months ago |  |[default to ]
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetMarginRepayLoanV1Resp**](GetMarginRepayLoanV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_ping_v1

> serde_json::Value get_ping_v1()
Test Connectivity

Test connectivity to the Rest API.

### Parameters

This endpoint does not need any parameter.

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_interest_history_v1

> Vec<models::GetPortfolioInterestHistoryV1RespItem> get_portfolio_interest_history_v1(timestamp, asset, start_time, end_time, size, recv_window)
Query Portfolio Margin Negative Balance Interest History(USER_DATA)

Query interest history of negative balance for portfolio margin.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**asset** | Option<**String**> |  |  |[default to ]
**start_time** | Option<**i64**> |  |  |
**end_time** | Option<**i64**> |  |  |
**size** | Option<**i64**> | Default:10 Max:100 |  |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetPortfolioInterestHistoryV1RespItem>**](GetPortfolioInterestHistoryV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_portfolio_negative_balance_exchange_record_v1

> models::GetPortfolioNegativeBalanceExchangeRecordV1Resp get_portfolio_negative_balance_exchange_record_v1(start_time, end_time, timestamp, recv_window)
Query User Negative Balance Auto Exchange Record (USER_DATA)

Query user negative balance auto exchange record

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** |  | [required] |
**end_time** | **i64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> | The value cannot be greater than 60000 |  |

### Return type

[**models::GetPortfolioNegativeBalanceExchangeRecordV1Resp**](GetPortfolioNegativeBalanceExchangeRecordV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_rate_limit_order_v1

> Vec<models::GetRateLimitOrderV1RespItem> get_rate_limit_order_v1(timestamp, recv_window)
Query User Rate Limit (USER_DATA)

Query User Rate Limit

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetRateLimitOrderV1RespItem>**](GetRateLimitOrderV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_repay_futures_switch_v1

> models::GetRepayFuturesSwitchV1Resp get_repay_futures_switch_v1(timestamp, recv_window)
Get Auto-repay-futures Status(USER_DATA)

Query Auto-repay-futures Status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetRepayFuturesSwitchV1Resp**](GetRepayFuturesSwitchV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_account_config_v1

> models::GetUmAccountConfigV1Resp get_um_account_config_v1(timestamp, recv_window)
UM Futures Account Configuration(USER_DATA)

Query UM Futures account configuration

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmAccountConfigV1Resp**](GetUmAccountConfigV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_account_v1

> models::GetUmAccountV1Resp get_um_account_v1(timestamp, recv_window)
Get UM Account Detail(USER_DATA)

Get current UM account asset and position information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmAccountV1Resp**](GetUmAccountV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_account_v2

> models::GetUmAccountV2Resp get_um_account_v2(timestamp, recv_window)
Get UM Account Detail V2(USER_DATA)

Get current UM account asset and position information.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmAccountV2Resp**](GetUmAccountV2Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_adl_quantile_v1

> Vec<models::GetUmAdlQuantileV1RespItem> get_um_adl_quantile_v1(timestamp, symbol, recv_window)
UM Position ADL Quantile Estimation(USER_DATA)

Query UM Position ADL Quantile Estimation

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetUmAdlQuantileV1RespItem>**](GetUmAdlQuantileV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_all_orders_v1

> Vec<models::GetUmAllOrdersV1RespItem> get_um_all_orders_v1(symbol, timestamp, order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetUmAllOrdersV1RespItem>**](GetUmAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_api_trading_status_v1

> models::GetUmApiTradingStatusV1Resp get_um_api_trading_status_v1(timestamp, symbol, recv_window)
Portfolio Margin UM Trading Quantitative Rules Indicators(USER_DATA)

Portfolio Margin UM Trading Quantitative Rules Indicators

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmApiTradingStatusV1Resp**](GetUmApiTradingStatusV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_commission_rate_v1

> models::GetUmCommissionRateV1Resp get_um_commission_rate_v1(symbol, timestamp, recv_window)
Get User Commission Rate for UM(USER_DATA)

Get User Commission Rate for UM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**symbol** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmCommissionRateV1Resp**](GetUmCommissionRateV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_conditional_all_orders_v1

> Vec<models::GetUmConditionalAllOrdersV1RespItem> get_um_conditional_all_orders_v1(timestamp, symbol, strategy_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetUmConditionalAllOrdersV1RespItem>**](GetUmConditionalAllOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_conditional_open_order_v1

> models::GetUmConditionalOpenOrderV1Resp get_um_conditional_open_order_v1(symbol, timestamp, strategy_id, new_client_strategy_id, recv_window)
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

[**models::GetUmConditionalOpenOrderV1Resp**](GetUmConditionalOpenOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_conditional_open_orders_v1

> Vec<models::GetUmConditionalOpenOrdersV1RespItem> get_um_conditional_open_orders_v1()
Query All Current UM Open Conditional Orders(USER_DATA)

Get all open conditional orders on a symbol.

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::GetUmConditionalOpenOrdersV1RespItem>**](GetUmConditionalOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_conditional_order_history_v1

> models::GetUmConditionalOrderHistoryV1Resp get_um_conditional_order_history_v1(symbol, timestamp, strategy_id, new_client_strategy_id, recv_window)
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

[**models::GetUmConditionalOrderHistoryV1Resp**](GetUmConditionalOrderHistoryV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_fee_burn_v1

> models::GetUmFeeBurnV1Resp get_um_fee_burn_v1(timestamp, recv_window)
Get UM Futures BNB Burn Status (USER_DATA)

Get user's BNB Fee Discount for UM Futures (Fee Discount On or Fee Discount Off )

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmFeeBurnV1Resp**](GetUmFeeBurnV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_force_orders_v1

> Vec<models::GetUmForceOrdersV1RespItem> get_um_force_orders_v1(timestamp, symbol, auto_close_type, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetUmForceOrdersV1RespItem>**](GetUmForceOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_income_asyn_id_v1

> models::GetUmIncomeAsynIdV1Resp get_um_income_asyn_id_v1(download_id, timestamp, recv_window)
Get UM Futures Transaction Download Link by Id(USER_DATA)

Get UM futures Transaction download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmIncomeAsynIdV1Resp**](GetUmIncomeAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_income_asyn_v1

> models::GetUmIncomeAsynV1Resp get_um_income_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For UM Futures Transaction History (USER_DATA)

Get download id for UM futures transaction history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmIncomeAsynV1Resp**](GetUmIncomeAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_income_v1

> Vec<models::GetUmIncomeV1RespItem> get_um_income_v1(timestamp, symbol, income_type, start_time, end_time, page, limit, recv_window)
Get UM Income History(USER_DATA)

Get UM Income History

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**income_type** | Option<**String**> | TRANSFER, WELCOME_BONUS, REALIZED_PNL, FUNDING_FEE, COMMISSION, INSURANCE_CLEAR, REFERRAL_KICKBACK, COMMISSION_REBATE, API_REBATE, CONTEST_REWARD, CROSS_COLLATERAL_TRANSFER, OPTIONS_PREMIUM_FEE, OPTIONS_SETTLE_PROFIT, INTERNAL_TRANSFER, AUTO_EXCHANGE, DELIVERED_SETTELMENT, COIN_SWAP_DEPOSIT, COIN_SWAP_WITHDRAW, POSITION_LIMIT_INCREASE_FEE |  |[default to ]
**start_time** | Option<**i64**> | Timestamp in ms to get funding from INCLUSIVE. |  |
**end_time** | Option<**i64**> | Timestamp in ms to get funding until INCLUSIVE. |  |
**page** | Option<**i32**> |  |  |
**limit** | Option<**i32**> | Default 100; max 1000 |  |[default to 100]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetUmIncomeV1RespItem>**](GetUmIncomeV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_leverage_bracket_v1

> Vec<models::GetUmLeverageBracketV1RespItem> get_um_leverage_bracket_v1(timestamp, symbol, recv_window)
UM Notional and Leverage Brackets (USER_DATA)

Query UM notional and leverage brackets

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetUmLeverageBracketV1RespItem>**](GetUmLeverageBracketV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_open_order_v1

> models::GetUmOpenOrderV1Resp get_um_open_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::GetUmOpenOrderV1Resp**](GetUmOpenOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_open_orders_v1

> Vec<models::GetUmOpenOrdersV1RespItem> get_um_open_orders_v1(timestamp, symbol, recv_window)
Query All Current UM Open Orders(USER_DATA)

Get all open orders on a symbol.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetUmOpenOrdersV1RespItem>**](GetUmOpenOrdersV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_order_amendment_v1

> Vec<models::GetUmOrderAmendmentV1RespItem> get_um_order_amendment_v1(symbol, timestamp, order_id, orig_client_order_id, start_time, end_time, limit, recv_window)
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

[**Vec<models::GetUmOrderAmendmentV1RespItem>**](GetUmOrderAmendmentV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_order_asyn_id_v1

> models::GetUmOrderAsynIdV1Resp get_um_order_asyn_id_v1(download_id, timestamp, recv_window)
Get UM Futures Order Download Link by Id(USER_DATA)

Get UM futures order download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmOrderAsynIdV1Resp**](GetUmOrderAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_order_asyn_v1

> models::GetUmOrderAsynV1Resp get_um_order_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For UM Futures Order History (USER_DATA)

Get download id for UM futures order history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmOrderAsynV1Resp**](GetUmOrderAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_order_v1

> models::GetUmOrderV1Resp get_um_order_v1(symbol, timestamp, order_id, orig_client_order_id, recv_window)
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

[**models::GetUmOrderV1Resp**](GetUmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_position_risk_v1

> Vec<models::GetUmPositionRiskV1RespItem> get_um_position_risk_v1()
Query UM Position Information(USER_DATA)

Get current UM position information.

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::GetUmPositionRiskV1RespItem>**](GetUmPositionRiskV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_position_side_dual_v1

> models::GetUmPositionSideDualV1Resp get_um_position_side_dual_v1(timestamp, recv_window)
Get UM Current Position Mode(USER_DATA)

Get user's position mode (Hedge Mode or One-way Mode ) on EVERY symbol in UM

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmPositionSideDualV1Resp**](GetUmPositionSideDualV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_symbol_config_v1

> Vec<models::GetUmSymbolConfigV1RespItem> get_um_symbol_config_v1(timestamp, symbol, recv_window)
UM Futures Symbol Configuration(USER_DATA)

Get current UM account symbol configuration.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**symbol** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**Vec<models::GetUmSymbolConfigV1RespItem>**](GetUmSymbolConfigV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_trade_asyn_id_v1

> models::GetUmTradeAsynIdV1Resp get_um_trade_asyn_id_v1(download_id, timestamp, recv_window)
Get UM Futures Trade Download Link by Id(USER_DATA)

Get UM futures trade download link by Id

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**download_id** | **String** | get by download id api | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmTradeAsynIdV1Resp**](GetUmTradeAsynIdV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_trade_asyn_v1

> models::GetUmTradeAsynV1Resp get_um_trade_asyn_v1(start_time, end_time, timestamp, recv_window)
Get Download Id For UM Futures Trade History (USER_DATA)

Get download id for UM futures trade history

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**start_time** | **i64** | Timestamp in ms | [required] |
**end_time** | **i64** | Timestamp in ms | [required] |
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetUmTradeAsynV1Resp**](GetUmTradeAsynV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_um_user_trades_v1

> Vec<models::GetUmUserTradesV1RespItem> get_um_user_trades_v1(symbol, timestamp, start_time, end_time, from_id, limit, recv_window)
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

[**Vec<models::GetUmUserTradesV1RespItem>**](GetUmUserTradesV1RespItem.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_cm_order_v1

> models::UpdateCmOrderV1Resp update_cm_order_v1(price, quantity, side, symbol, timestamp, order_id, orig_client_order_id, price_match, recv_window)
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

[**models::UpdateCmOrderV1Resp**](UpdateCmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_listen_key_v1

> serde_json::Value update_listen_key_v1()
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


## update_um_order_v1

> models::UpdateUmOrderV1Resp update_um_order_v1(price, quantity, side, symbol, timestamp, order_id, orig_client_order_id, price_match, recv_window)
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

[**models::UpdateUmOrderV1Resp**](UpdateUmOrderV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

