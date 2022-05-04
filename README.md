# [svelte-stripe](https://sveltestripe.com)

Everything you need to add Stripe to your Svelte project. 100% [svelte-kit](https://kit.svelte.dev/) compatible.

> Stripe is now [sponsoring this project](#sponsors)

[Documentation](https://sveltestripe.com)

## Components

The following components are provided:

- `<Container/>`: A wrapper component to set context.
- `<CardNumber/>`: Input field for the card's number.
- `<CardExpiry/>`: Input field for the card's expiration date.
- `<CardCvc/>`: Input field for Card Verification Value.
- `<Card/>`: All-in-one component that has inputs for card number, expiry, cvc, and zip code.
- `<PaymentRequestButton/>`: A GooglePay or ApplePay button, depending on browser.
- `<Iban/>`: Input field for IBAN (International bank account number).
- `<Ideal/>`: Input field for iDEAL (payment system used in the Netherlands).
- `<PaymentElement/>`: All-in-one component that allows the user to choose the type of payment.

## Examples

There is example code for:

- [Payment Element](/tree/main/src/routes/examples/payment-element)
- [Credit card](/tree/main/src/routes/examples/credit-card)
- [GooglePay](/tree/main/src/routes/examples/payment-request)
- [ApplePay](/tree/main/src/routes/examples/payment-request)
- [SEPA direct deposit](/tree/main/src/routes/examples/sepa)
- [iDEAL](/tree/main/src/routes/examples/ideal)
- [Alipay](/tree/main/src/routes/examples/alipay)

Please open a PR or issue, if you'd like to add more.

## Usage

See [documentation](https://sveltestripe.com) for setup instructions and examples.

## Sponsors

<a href="https://stripe.com">
  <img src="https://raw.githubusercontent.com/joshnuss/svelte-stripe/main/static/logos/stripe.svg" width="150px" alt="Stripe's logo"/>
</a>

## Code contributors

![GitHub Contributors Image](https://contrib.rocks/image?repo=joshnuss/svelte-stripe)

## License

MIT
