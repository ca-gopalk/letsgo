[@letsgo/stripe](../README.md) / CreateNewPaymentSetupResponse

# Interface: CreateNewPaymentSetupResponse

Parameters describing a newly created Stripe payment setup. This allows the caller to continue
the collection of the new payment method in the front-end.

## Table of contents

### Properties

- [clientSecret](CreateNewPaymentSetupResponse.md#clientsecret)
- [publicKey](CreateNewPaymentSetupResponse.md#publickey)

## Properties

### clientSecret

• **clientSecret**: `string`

Client secret for the Stripe payment intent.

#### Defined in

[index.ts:312](https://github.com/47chapters/letsgo/blob/11c7e19/packages/stripe/src/index.ts#L312)

___

### publicKey

• **publicKey**: `string`

Stripe public key to use for the payment form. This may be a _live_ or _test_ key depending
on the Stripe configuration.

#### Defined in

[index.ts:317](https://github.com/47chapters/letsgo/blob/11c7e19/packages/stripe/src/index.ts#L317)
