---
title: Ticket Concepts
slug: TicketConcepts
published: master
first_published: 2019-12
tags:
  - concepts
  - tickets
  - 2021-01
---

# Tickets Concepts

An important aspect of an in-person event is often <IndexLink slug="Tickets"/>. **Tickets** are a specially configured **For Sale Item** that provides a means to have an admission requirement to an in-person event; or, as needed, a means to restrict bidding to those that have been assigned a ticket.

::: yellow
**IMPORTANT**
Tickets are tied directly to <IndexLink slug="Bidders"/> and **Bidder Record** creation. Tickets should be used for event admission and similar requirements only.
:::

::: green
**NOTE**
When selling tickets via the <IndexLink slug="AuctionDashboard"/>, always use the <IndexLink slug="SellTickets"/> function to ensure the connection to bidder record creation is maintained.
:::

## Admissions

All **Ticket** items require a value be set for the **Admission Tickets Included** under their <IndexLink slug="ForSaleItemsDetailed" anchor="for-sale-items"/> section. This is what triggers the underlying functionality to create the "tickets" and build out the bidder records attached to the tickets.

## Buying Tickets

When a visitor to your auction website purchases a ticket item, the <IndexLink slug="BidderRegistration"/> functions are triggered during the <IndexLink slug="Checkout"/> process.

## Selling Tickets

Although your guests will mostly be buying tickets you can also sell them tickets via the <IndexLink slug="AuctionDashboard"/>. The **only way to do this correctly** is to use the <IndexLink slug="SellTickets"/> function as it will trigger the bidder creation process where the <IndexLink slug="RecordPurchase"/> function would only record the sale of the <IndexLink slug="ForSaleItems">For Sale Item</IndexLink> (the <IndexLink slug="Tickets"/> item in this case) and **not** attach any bidders to it.

![img](./index.assets/Tickets.jpg)

## Ticket Extras

Providing **Ticket Items** for your guests also allows you to add some additional features such as providing for **Meal Choices** as well as creating **Tables** and assigning **Seats** to those table.

### Meal Choices

Along with helping with the management of attendance using **Ticket** items also allows you to have <IndexLink slug="MealChoices"/> as an options for the ticket item.

### Tables And Seating

As part of the **Ticket Item** set up you can also create a **Table** when the ticket is purchased. Often this is when there are larger numbers of admissions included with the ticket as well as being a very common approach to "<IndexLink slug="AddDonorDonation" anchor="sell-sponsorships"/>" for an event.

See <IndexLink slug="TablesAndSeating"/> and <IndexLink slug="AssignSeating"/> for more information on how these feature sets work.

<ChildPages/>
<Revised text="Reviewed" date="2021-08-17"/>
