---
title: Connectivity
slug: Connectivity
published: master
tags:
  - concepts
  - online_auctions
  - connectivity
  - 2021-01
---

# Connectivity

A common concern when planning for online/mobile bidding at an event is how bidders will access Auctria.

There are a number of factors to consider:

## Texting

Texting is the simplest, and generally most trouble free, option for connectivity. Assuming you have a reasonable cell phone signal throughout the venue, sending and receiving texts should work fine.

If possible, it is worth confirming there is a strong signal for each of the major telephone providers in your area.

## Cellular Data

Bidders that are using the mobile app, or accessing the website from their phone, can use the cellular data associated with their plan. Other than confirming there is a strong signal throughout the venue, there is nothing you can do to affect this. Most phones will show the type of data connection they are able to achieve in the status bar.

Bidders may be concerned about bandwidth if they have a limited amount of data per-month, or some plans may not have any cellular data option at all.

Using the website or mobile app is a low bandwidth activity, akin to browsing Facebook (**without videos!**) and typically would not consume more than a few megabytes at most with browsing and bidding.

Installing the mobile app is a larger download and may take 20-30MB of data depending on the phone.

## WiFi

Using a venue's WiFi network is another option to but is more complex to validate than relying on the cell network.

There are a number of advantages to WiFi:

- bidders do not need to have (or use) their cellular data
- for more rural events cellular data may not be reliable
- you can use non-cellular devices (for example, tablets)

The questions that you need to answer when considering using WiFi include:

- how will bidders access the network:
  - is it password protected?
  - does it require going through a sign on (portal) page?
- how many clients can the network support?
- what internet bandwidth is available overall?

If your event is at a commercial venue, for example at a hotel or conference center, then you will have no control over the network and should ask the venue for details on the connection. Often these venues will have different tiers of WiFi access you can buy, however, they can become very price prohibitive for a large number of guests.

If your event is at location like a school or church you will have to ask the IT group for details of the WiFi network.

### Connecting to WiFi

If you are providing bidders with access to the WiFi then it is important to provide clear instructions. This is especially important if a password or portal page needs to be accessed to connect successfully.

While many people will be comfortable with attaching to a WiFi network, there will be those that don't know how to do this on their phone and having volunteers available to help will ensure a smoother experience for them.

There is also the possibility that certain phones will simply not connect to some networks. While this is a rare occurrence, if you have 200+ devices to connect then the probability goes up. Ideally the bidder can just fall back on cellular data, or texting as an option. Providing <IndexLink slug="KioskModeBidding">kiosk mode bidding</IndexLink> devices also provides them a way to participate.

### Clients & Bandwidth

The question of how many clients the network supports and the bandwidth required are related but should be considered separately.

**Bandwidth** is generally not the bottleneck assuming you have a 10MBps+ connection and your guests are only using the WiFi for the auction and **not streaming videos!** Most venues with a reasonable broadband connection should not see an issue here.

::: warning IMPORTANT
At 10-20MB+ per download, 200 bidders would total 4GB+ of data or around an hour of a maxed out 10Mbps connection, but only 6 minutes for 100Mbps.
:::

The number of **clients** the WiFi network can support is often more of a challenge, especially for non-commercial networks.

At the extreme end, a church hall set up with a few **residential class** WiFi access points will **not support** 100+ bidders.  Residential class hardware is unlikely to reliably support more than **10-20 clients per access point**.

A school that is set up to provide WiFi access to its students will generally be fine since it will be scaled to support hundreds of devices. However, it is worth confirming with the IT department that having all the devices clustered in one area would be supported rather than spread out over the campus.

The challenge with these questions is that it is not possible to test the situation beforehand. Ideally the group responsible for the network will have experienced a similar situation in the past to know how it performs, or at least will know from capacity planning if the network can be expected handle it.

### Firewalls and Filtering

No special firewall rules are needed for mobile bidding via either the website or mobile app. The normal access used to browse the web is fine. However, if a network has filtering in place, you should confirm that this doesn't interfere with Auctria.

Generally this is not a problem for mobile bidding but if, for example, bidders are using the Facebook sign-in feature and the network has blocked Facebook then that won't work.

## WiFi Hotspots

Using a WiFi hotspot as a backup internet connection for running the event works great for your staff/volunteers.

A single phone can easily provide Wifi to 5-10 clients to allow them to record bids, run checkout, etc. However, it is not a suitable option for mobile bidding as a phone will simply not support enough connections to work.
