---
title: Credit Card Costs
slug: CreditCardCosts
published: master
first_published: 2010-01
tags:
  - concepts
  - credit_cards
  - costs
  - 2022-05
---

# Credit Card Costs

The costs associated with credit card processing consist of credit card processing integration fees **plus** the payment processor's fees.

<Linked slug="AuctriaCosts"/>
<Linked slug="CreditCardFees"/>

<HRDiv/>

## Auctria Costs

Our fees for integrated credit card processing varies based on the plan in effect **when the charge is made**:

::: middle

| Plan      | Fee  |
| --------- | ---- |
| Diamond   | 0.25% |
| Emerald   | 0.5% |
| Explorer  | 1.0% |

:::

Auctria's fee will be *automatically* deducted when you are using **Stripe** as the payment processor (see <IndexLink slug="CreditCardFees"/> for more details). If you are using **Authorize.Net**, we will *invoice* you for the fees after the event.

<HRDiv/>

## Payment Processors

### Stripe Costs

Stripe's default credit card processing fees are $0.30 + 2.9% per transaction. They do not charge any monthly, or minimum, fees though. You just pay for the transactions you process with them.

However, for **501(c)3** organizations, they may offer some additional discounts. See [Does Stripe offer a fee discount for non-profit organizations?](https://support.stripe.com/questions/does-stripe-offer-a-fee-discount-for-non-profit-organizations) for some more details.

### Authorize.Net Costs

When used as a gateway, Authorize.Net currently costs $25/month (**regardless of usage**) + $0.10 per transaction. You would also pay the processing fees for your merchant account.

::: info
It is important to note the organization will always be paying the credit card processing fees **and** the Auctria integration fees on credit card transactions only.

When a **_bidder pays the fees_**, they will be **_paying an extra amount_**. This *extra payment amount* is based on the the credit card processing fees plus the Auctria integration fees and applied to their balance during checkout.

This *extra payment amount* will cover the fees being charged leaving the entire donation, purchase, and winning bid amounts to the organization.

<Linked slug="CreditCardFees" anchor="example-surcharge-fees">Processing Fees - Example: Surcharge Fees</Linked>
&nbsp;
:::

<HRDiv/>

## Refunds

When you issue a refund of a credit card charge through Auctria, we will refund our portion of the credit card cost.

### Stripe Refunds

If you are using Stripe, then it depends on the age of your account:
- for Stripe accounts opened prior to September 14th 2017, the Stripe fees will be refunded as well;
- for Stripe accounts opened after this date, Stripe have changed their policy and do not refund the fees.

For more details on this please contact Stripe at [support@stripe.com](mailto://support@stripe.com).

### Authorize.Net Refunds

If you are using Authorize.Net, we do not have any visibility to the refund policy of your merchant account. You will need to contact them directly to see what happens.

<ChildPages/>
<Revised date="May 2022"/>
