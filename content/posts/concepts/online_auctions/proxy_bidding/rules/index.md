---
title: Proxy Bidding Rules
slug: ProxyBiddingRules
published: master
first_published: 2010-01
tags:
  - concepts
  - online_auctions
  - proxy_bidding
  - rules
  - 2022-03
---

# Proxy Bidding Rules <Updated/>

The following rules apply to **Proxy Bidding**:

- **Proxy Bids** can only be placed on <IndexLink slug="OnlineItems"/> types.
- **Proxy Bids** *cannot* be used with <IndexLink slug="LiveItems"/> or <IndexLink slug="SilentItems"/>.
- **Proxy Bids** *cannot* be applied outside of the <IndexLink slug="OnlineBiddingTimes"/> that have been set for the event.
- **Proxy Bids** *cannot* be used when the <IndexLink slug="MultipleWinners"/> option is enabled for the item.
- **Proxy Bids** *cannot* be reduced once placed.
- **Proxy Bids** can be raised.
  For example, if a bidder has a **Proxy Bid** in place for $1,000 and they place another bid for $1,200, the actual winning bid will not change but their **Proxy Bid** will be raised to $1,200.
- **Proxy Bids** can be placed on <IndexLink slug="BuyItNowItems"/> as long as the bid is less than the **Buy-It-Now** price. Please note, another bidder can still bid the **Buy-It-Now** value to win the item.

---

- Bids placed at just above an existing **Proxy Bid** may fail even though the new winning bid is less than your bid. This can happen if the bid value lands in the gap between the **Proxy Bid** and the next bid point (for example, the dollar amount placed between the **Proxy Bid** and the *minimum bid increment*).
- Any bid over a **Proxy Bid** will become a winning bid as long as the amount is at least one **Bid Increment** over the previously **_visible_** bid (and for multiples it must be a multiple over the previous bid). The new bid will show as one bid increment over the previous (proxy) bid if it can.
  - If it cannot be increased to the full bid increment (for example, due to a **Buy It Now** value set) the bid will be maxed out.
- **Proxy Bids** are still applied if the <IndexLink slug="RecordBid"/> function is used on an <IndexLink slug="OnlineItems"/> with an existing **Proxy Bid**.
- When bidding, if the **Place as a proxy bid?** checkbox is cleared, the bid will be placed immediately for its full value. If there is an existing **Proxy Bid** it would be applied afterward.
- **Proxy Bidding** is available when using catalog bidding in **Kiosk Mode**, however the **What am I winning** option does not show "Proxy bids" in **Kiosk Mode**.

::: yellow
**IMPORTANT -- When A Reserve Price Is Set**
When an item has a **Reserved Price** set, a **Proxy Bid** will be increased until it reaches, or exceeds due to *bid increments*, the "Reserved Price" value. If the *Reserve Price* value is not met, the **Proxy Bid** will be used to set the *Current Bid* for the item.
:::

<HRDiv/>

## Text Based Bidding

If Text based bidding is available for bidders to use, bids placed by text will follow the auction's **Proxy Bidding** settings by default. See <IndexLink slug="OnlineBidding" anchor="online-bidding-behavior"/> for more details on this.

With **Proxy Bidding** enabled, **all text bids will be considered as Proxy Bids**, or *Maximum Bids*.

::: tip
**EXAMPLE**
An item has no current bid, a *Starting Bid* of $10, and a *Bid Increment* of $10.
A *Text* bid of $40 will set the current bid to $10 and will be increased, following the **Proxy Bidding Rules**, to $40 as needed.
:::

<ChildPages/>
<Revised date="2022-03-09"/>
