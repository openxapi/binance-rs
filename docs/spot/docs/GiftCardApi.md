# \GiftCardApi

All URIs are relative to *https://api.binance.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_giftcard_buy_code_v1**](GiftCardApi.md#create_giftcard_buy_code_v1) | **POST** /sapi/v1/giftcard/buyCode | Create a dual-token gift card(fixed value, discount feature)(TRADE)
[**create_giftcard_create_code_v1**](GiftCardApi.md#create_giftcard_create_code_v1) | **POST** /sapi/v1/giftcard/createCode | Create a single-token gift card (USER_DATA)
[**create_giftcard_redeem_code_v1**](GiftCardApi.md#create_giftcard_redeem_code_v1) | **POST** /sapi/v1/giftcard/redeemCode | Redeem a Binance Gift Card(USER_DATA)
[**get_giftcard_buy_code_token_limit_v1**](GiftCardApi.md#get_giftcard_buy_code_token_limit_v1) | **GET** /sapi/v1/giftcard/buyCode/token-limit | Fetch Token Limit(USER_DATA)
[**get_giftcard_cryptography_rsa_public_key_v1**](GiftCardApi.md#get_giftcard_cryptography_rsa_public_key_v1) | **GET** /sapi/v1/giftcard/cryptography/rsa-public-key | Fetch RSA Public Key(USER_DATA)
[**get_giftcard_verify_v1**](GiftCardApi.md#get_giftcard_verify_v1) | **GET** /sapi/v1/giftcard/verify | Verify Binance Gift Card by Gift Card Number(USER_DATA)



## create_giftcard_buy_code_v1

> models::CreateGiftcardBuyCodeV1Resp create_giftcard_buy_code_v1(base_token, base_token_amount, face_token, timestamp, recv_window)
Create a dual-token gift card(fixed value, discount feature)(TRADE)

This API is for creating a dual-token ( stablecoin-denominated) Binance Gift Card. You may create a gift card using USDT as baseToken, that is redeemable to another designated token (faceToken). For example, you can create a fixed-value BTC gift card and pay with 100 USDT plus 1 USDT fee. This gift card can keep the value fixed at 100 USDT before redemption, and will be redeemable to BTC equivalent to 100 USDT upon redemption.   Once successfully created, the amount of baseToken (e.g. USDT) in the fixed-value gift card along with the fee would be deducted from your funding wallet.   To get started with, please make sure:  You have a Binance account You have passed KYB You have a sufﬁcient balance(Gift Card amount and fee amount) in your Binance funding wallet You need Enable Withdrawals for the API Key which requests this endpoint.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**base_token** | **String** |  | [required] |[default to ]
**base_token_amount** | **f64** |  | [required] |
**face_token** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateGiftcardBuyCodeV1Resp**](CreateGiftcardBuyCodeV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_giftcard_create_code_v1

> models::CreateGiftcardCreateCodeV1Resp create_giftcard_create_code_v1(amount, timestamp, token, recv_window)
Create a single-token gift card (USER_DATA)

This API is for creating a Binance Gift Card.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**amount** | **f64** |  | [required] |
**timestamp** | **i64** |  | [required] |
**token** | **String** |  | [required] |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateGiftcardCreateCodeV1Resp**](CreateGiftcardCreateCodeV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_giftcard_redeem_code_v1

> models::CreateGiftcardRedeemCodeV1Resp create_giftcard_redeem_code_v1(code, timestamp, external_uid, recv_window)
Redeem a Binance Gift Card(USER_DATA)

This API is for redeeming a Binance Gift Card Once redeemed, the coins will be deposited in your funding wallet.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**code** | **String** |  | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**external_uid** | Option<**String**> |  |  |[default to ]
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::CreateGiftcardRedeemCodeV1Resp**](CreateGiftcardRedeemCodeV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_giftcard_buy_code_token_limit_v1

> models::GetGiftcardBuyCodeTokenLimitV1Resp get_giftcard_buy_code_token_limit_v1(base_token, timestamp, recv_window)
Fetch Token Limit(USER_DATA)

This API is to help you verify which tokens are available for you to create Stablecoin-Denominated gift cards as mentioned in section 2 and its’ limitation.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**base_token** | **String** | The token you want to pay, example: BUSD | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetGiftcardBuyCodeTokenLimitV1Resp**](GetGiftcardBuyCodeTokenLimitV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_giftcard_cryptography_rsa_public_key_v1

> models::GetGiftcardCryptographyRsaPublicKeyV1Resp get_giftcard_cryptography_rsa_public_key_v1(timestamp, recv_window)
Fetch RSA Public Key(USER_DATA)

This API is for fetching the RSA Public Key. This RSA Public key will be used to encrypt the card code.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetGiftcardCryptographyRsaPublicKeyV1Resp**](GetGiftcardCryptographyRsaPublicKeyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_giftcard_verify_v1

> models::GetGiftcardVerifyV1Resp get_giftcard_verify_v1(reference_no, timestamp, recv_window)
Verify Binance Gift Card by Gift Card Number(USER_DATA)

This API is for verifying whether the Binance Gift Card is valid or not by entering Gift Card Number.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**reference_no** | **String** | Enter the Gift Card Number | [required] |[default to ]
**timestamp** | **i64** |  | [required] |
**recv_window** | Option<**i64**> |  |  |

### Return type

[**models::GetGiftcardVerifyV1Resp**](GetGiftcardVerifyV1Resp.md)

### Authorization

[ApiKey](../README.md#ApiKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

