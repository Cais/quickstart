---
title: Item Types
slug: ItemTypes
published: master
first_published: 2010-01
tags:
  - item_types
  - examples
  - 2021-11
---

# Item Types

Items are crucial to all events in Auctria and one of the first tasks is to add the items you need.

The <IndexLink slug="ItemTypes"/> are selected from a **pre-set** list, each with an intended **specific functionality**. Before you set up your items, it is best to understand the different **Items Types**.

::: info
When you create items, you **must** set the item to be one of the Auctria **Item Types**. The item type can be changed at any time. This may change how Auctria handles the item. Please remember to double-check the item is behaving as expected if you do change its type.
:::

The following **Item Types** are available:

- <IndexLink slug="SilentItems"/>: sold via a paper bid sheet at your event.
- <IndexLink slug="LiveItems"/>: included in a live auction, there is no bid sheet produced.
- <IndexLink slug="OnlineItems"/>: sold fully online via the website, mobile app or text based bidding.
- <IndexLink slug="PartialItems"/>: items that have been donated but which are not being sold on their own, but will be included as part of a basket item.
- <IndexLink slug="ForSaleItems"/>: items you are selling for a "fixed price" and may have a limited quantity available. "For Sale Items" are more commonly used for <IndexLink slug="Tickets"/> and similar items not normally bid on.
- <IndexLink slug="DonationItems"/>: projects bidders can donate to but which they don't actually "win".
- <IndexLink slug="RaffleItems"/>: prizes for a raffle, or similar event, that are awarded to a bidder without a cost.

::: info
The most commonly used **Item Types** are *Silent*, *Live*, and *Online* -- the "Biddable" items. One way to decide if these types are what you are looking for, and which to use, is to consider where the final bidding for the item will be taking place.

- paper bid sheet -> <IndexLink slug="SilentItems"/>
- auctioneer -> <IndexLink slug="LiveItems"/>
- electronic -> <IndexLink slug="OnlineItems"/>
:::

The **Item Type** of an item can be changed in its <IndexLink slug="ItemDetails"/> **Summary** tab.

<Link/> <IndexLink slug="EditItemDetails"/>

<HRDiv/>

## Examples Items

The following examples show how to create items for different scenarios.

### Silent Auction With Pre-bidding Enabled

Silent auction item types are often seen at traditional gala events and can be created with the option to allow for online bidding prior to the actual event itself.

The item should be created with a type of **silent** and have the **Participate in online bidding** option enabled. This option is enabled by default for all items. For more details see <IndexLink slug="OnlineBiddingType"/>.

### Basket / Packaged Item

A handful of cosmetic items have been donated separately but will be sold together as a "basket" or "packaged" item/lot.

In this case, you would need the following:

1. A single item that represents the "basket" of items being sold. The auction type for this item can be "<IndexLink slug="LiveItems">live</IndexLink>", "<IndexLink slug="SilentItems">silent</IndexLink>", or "<IndexLink slug="OnlineItems">online</IndexLink>" depending on how you will be selling the basket.

2. You will want to track one item per donation with a type of "<IndexLink slug="PartialItems">partial</IndexLink>" (the individual cosmetic items). Each of these items can have its own donor and relevant value.

By default, *the "basket" item will calculate its value from the "partial" items* that are assigned to it.
You can learn more about how to set this up in <IndexLink slug="Baskets">Baskets and Packages</IndexLink>.

### Raffle Tickets

A raffle where tickets are sold `1 for $5`, or `4 for $15`, with multiple prizes available.

In this case, you would use **two** "<IndexLink slug="ForSaleItems"/>" to represent the raffle tickets.

- An item for a **single ticket**, with a "For Sale" item type and a value of `$5`. You might assign a meaningful item number *value* such as *RAFFLE* to help identify the item as a "Raffle ticket" item although you could use any item number you wish.

- An item for a **pack of 4 tickets**, with a **For Sale** item type and a value of `$15`. You could give this an item number a value such as *RAFFLE4* to help identify the item with reference to the *RAFFLE* ticket.

You may also want to have another item per prize with an item type of **Raffle**. The **Raffle** item type is used for prizes **_only_**. Its value can optionally be set to the item's actual value. For more information see <IndexLink slug="RunARaffle"/>.

### Dinner Party

A silent auction where up to `12` people can win a seat at the table for a dinner party.

This case be be handled in a couple of ways, depending on how you want to work the bidding.  

- If bidders are able to place their bids on the "<IndexLink slug="BidSheets">bid sheet</IndexLink>", you can create this as a normal <IndexLink slug="SilentItems">silent auction item</IndexLink> and check the **Allow multiple winners** field.

- If you are selling the seats at a *fixed price*, you can either create it as a "silent auction item" and set the <IndexLink slug="BuyItNowItems">Buy-It-Now</IndexLink> price to equal the starting bid or you can create it as a <IndexLink slug="ForSaleItems">For Sale</IndexLink> item.

See <IndexLink slug="MultipleQuantities"/>, <IndexLink slug="MultipleWinners"/>, and <IndexLink slug="SellingItems"/> for more information.

<ChildPages />
<Revised date="November 2021"/>
