---
title: Credit Cards
slug: CreditCardConcepts
published: master
tags:
  - concepts
  - credit_cards
  - 2020-09
---

# Credit Cards

Processing **Credit Cards** transactions in Auctria requires connecting to a supported payment processing service. Auctria currently supports integrating with either [Stripe.com](https://stripe.com/) (*recommended*), or [Authorize.Net](https://www.authorize.net/) (in general, when you have an existing merchant account).

Opening an account with one of these services is generally a straight-forward online process although it does require verifying your identity so you can process charges for the Organization you represent. Your Organization would need to open an account with one of these payment processors (if you don't already have one) and authorize Auctria to process charges through your account.

::: tip
**IMPORTANT**
These credit card transactions are happening between **your Organization and your bidders**, Auctria is **only** *facilitating* these transactions and has **no access** to any account settings of your processing service.
:::

::: warning
An Organization can only connect to a **single** processor account at a time in Auctria.
:::

For more information on **Credit Cards** and how to connect to one of the supported credit card processing services, please see our <IndexLink slug="CreditCards"/> section under <IndexLink slug="AuctionTeamExperience"/>.

::: tip
All **Credit Card** features require a payment processing integration feature set be enabled.
:::

Once a credit card number has been entered, it is **impossible** to retrieve the original credit card number again. Cards can be *registered* against a bidder and charged in the future although **no one can see the number**.

::: warning
Auctria **does not support** capturing raw credit card numbers. **All integrated card processing** is handled securely, in a PCI compliant manner, through the connected payment processor.
:::

<ChildPages/>
<Revised date="September 2020"/>
