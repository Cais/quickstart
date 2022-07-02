---
Title: Credit Cards
slug: KeyTopics_CreditCards
published: master
first_published: 2021-12-09
tags:
  - key_topics
  - credit_cards
---

# Credit Cards

A curated collection of User Guide pages and section focused on **Credit Cards** and how **_Credit Card Processing_** is implemented for organizations on the Auctria platform.

## Credit Card Processors

Processing **Credit Card** transactions in Auctria requires connecting to a supported payment processing service. Auctria currently supports integrating with the following:
- [Stripe.com](https://stripe.com/)
  **_Recommended_** for its ease of use and speed with verifications; or,
- [Authorize.Net](https://www.authorize.net/)
  This service, in general, may be easiest when you have an existing merchant account.

::: red
**WARNING**
All **Credit Card** functions in Auctria are tied directly to having **_Credit Card Integration_** enabled. If it is not enabled, you will not see these feature sets.
:::

::: recread
- <IndexLink slug="Concepts_CreditCards_PaymentProcessors_Accounts"/>
- <IndexLink slug="CreditCardFundsTransferred"/>
- <IndexLink slug="CreditCardFees"/>
- <IndexLink slug="CreditCardSettings" anchor="surcharge-settings-current-auction">Credit Card Settings | Surcharge Settings (current auction)</IndexLink>
:::

<HRDiv/>

## Registering Credit Cards

**Credit Cards** can be registered at multiple points on the Auctria platform. The most common approach is to have your guest register their credit card when registering for the event (under **Online Payment Options**).

The option to register a **Credit Card** for future use with the event is also available during the **Checkout** process.

**_Registering Credit Cards_** is also an option that can be set as a requirement for bidding (under **Online Bidding Behavior**).

If you should have your guests register their **Credit Card** is mostly dependent on your audience and their expectations. There is no requirement to use **_Credit Card Integration_** although most organizers find it very convenient over using multiple systems to process and record payments accurately.

::: danger
**WARNING**: In order to **Register Credit Cards** you must have **Credit Card Processing** enabled.
:::

<Link/> <IndexLink slug="BidderRegistration" anchor="online-payment-options">Bidder Registration/Checkout | Online Payment Options</IndexLink>
<br/>
<Link/> <IndexLink slug="OnlineBidding" anchor="online-bidding-behavior">Online Bidding | Online Bidding Behavior</IndexLink>

<HRDiv/>

## Credit Card Reports

The most common reports for **Credit Cards** are the **_Credit Card Charges_** and **_Credit Card Summary_** reports.

- **Reports > Financial | Payments > Credit Card Charges**
- **Reports > Financial | Payments > Credit Card Summary**

These reports provide basic information generally looked for about the credit card transactions from the event. You can also expand on these default reports using the <IndexLink slug="ChoosingColumns"/> function.

For more information about these reports, see <IndexLink slug="CreditCardReports"/> in our **User Guide** under the **Auction Team Experience** > **Credit Cards** section.

<HRDiv/>

::: recread More Recommended Reading
- <IndexLink slug="CreditCardRefund"/>
- <IndexLink slug="CreditCardMode"/>
- <IndexLink slug="CancelledCharges"/>
:::

<ChildPages/>
<Revised text="Reviewed" date="2022-04-25"/>
