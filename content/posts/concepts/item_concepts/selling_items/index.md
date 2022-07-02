---
title: Selling Items
slug: SellingItems
published: master
first_published: 2020-10
tags:
  - key_topic
  - concepts
  - item_concepts
  - for_sale_items
  - buy_it_now_only_items
  - 2021-09
---

# Selling Items

You can use Auctria to "sell" items online from your Auction Website.

::: info
Any transaction on the **Auction Website** that requires a payment, especially those using <IndexLink slug="CreditCards"/> integration, will trigger the full <IndexLink slug="BidderRegistration"/> process **and** create a bidder record for the purchaser as part of that process.
:::

## For Sale Items Versus Buy It Now Only Items

When **Selling Items** in Auctria there are essentially two ways to set up items. You can use the <IndexLink slug="ForSaleItems"/> approach or you can use <IndexLink slug="BuyItNowItems"/> approach.

For example, **For Sale Items** are used for <IndexLink slug="Tickets"/> in Auctria because they often require immediate payment, or assurances of payment, by the purchaser while **Buy It Now Only Items** will go "on account" for the bidder (aka purchaser) to be paid for at a later time -- generally during <IndexLink slug="Checkout"/> or via an online payment link from a **Won Item Notification**.

| Item Concept | For Sale Item | Buy It Now Item |
| ------------ | ------------- | --------------- |
| <IndexLink slug="BidderRegistration"/> | **Not** required first | Required first |
| <IndexLink slug="Tickets"/> | Admission to the in-person event | Admission to another event, venue, etc. (**not** the in-person event) |
| <IndexLink slug="BidderStatements"/> | Displays under Purchases | Displays under Won Items |
| <IndexLink slug="Concepts_SellingSponsorships">Sponsorships</IndexLink> | Sold prior to event | Use <IndexLink slug="DonationItems"/> during events for sponsorships  |
| <IndexLink slug="RunARaffle">Raffle Tickets</IndexLink> | To sell with **Tickets** | To sell during event / via mobile app |
| <IndexLink slug="HowGuestsPay">Online Payments</IndexLink> | Immediate payment required | Item "winning bid" value added to bidder balance, immediate payment may **not** be required |

::: yellow
**IMPORTANT**
Under the <IndexLink slug="ForSaleItems"/> approach, items added to the cart may be removed by bidder.
Under the <IndexLink slug="BuyItNowItems"/> approach, items are immediately added to the bidder balance **and** cannot be removed by the bidder. This would **require** an organizer use the <IndexLink slug="RemoveBid">Remove Bid</IndexLink> function.
:::

Both **For Sale Items** and **Buy It Now Items** have the ability to limit quantity by setting a value for the <IndexLink slug="EditItemDetails" anchor="availability"/> **Quantity** field (leaving blank or using `0` would be considered as *unlimited*).

::: info
By default, **For Sale Items** are not displayed in the website <IndexLink slug="RowContent_ItemCatalog"/> while **Buy It Now Only Items** appear in **Auction Catalogs** as they are <IndexLink slug="SilentItems"/>, <IndexLink slug="LiveItems"/>, or <IndexLink slug="OnlineItems"/>.
:::

<HRDiv/>

## Export Individual Sales

As a special case, <IndexLink slug="ForSaleItems"/> have an additional *Activity* related option under **Exporting & Printing** (in the sidebar) that allows you to **Export Individual Sales** for the specific item as an XLS formatted file.

![img](./index.assets/ExportAndPrinting.png)

Clicking the button will immediately start the process and download the file in your browser.

::: ideas
Using the **Export Individual Sales** on a *Raffle Ticket* item (see <IndexLink slug="RunARaffle"/> for more information) will provide you with a list of buyers of that item. The exported list could then be further reviewed and potentially used for a raffle "drawing" **external** to Auctria.

Also see <IndexLink slug="AfterEventSales"/> for more information on selling those biddable items left after the event has closed.
:::

<ChildPages/>
<Revised text="Reviewed" date="2022-04-04"/>
