---
title: How To Track Donations
slug: Walkthroughs_TrackDonations
published: master
first_published: 2021-11-24
tags:
  - walkthroughs
  - donations
  - donation_reports
---

# How To Track Donations <New/>

When you want to track how well your donations are doing for an auction event you will have to also look at how you are receiving, or will be receiving, those donations. Essentially, you will be manually recording donations and/or you will be receiving donations from bidders on your auction website.

&nbsp;
::: prereq
- **Auctria Auction Website** (see <IndexLink slug="Walkthroughs_CreateNewWebSite2021"/> if needed)
- **Donation Item(s)** (optional - see <IndexLink slug="DonationItems"/> as needed)
- **Add New Items** (optional - see <IndexLink slug="AddNewItem"/> as needed)
:::

## How To Record A Donation

There are three basic methods to record a donation using Auctria.

1. Manually record the donations via the auction dashboard using the **Record Donation** function;
2. Provide a **Donation Element** on the auction website for your guests to pledge an amount; or,
3. Manually enter a **Donor Donation** (*non-item donation*) using the **Add New Donation** function.

<Link/> <IndexLink slug="RecordDonation"/>
<Link/> <IndexLink slug="RowContent_DonationElement"/>
<Link/> <IndexLink slug="AddDonorDonation">Add New Donation</IndexLink>

### Via The Auction Dashboard

For donations recorded **Via The Auction Dashboard**, you would use the **Record Donation** function. This will allow you to record a **Cash Donation** or a donation directly associated with a **Donation Item**.

<Link/> <IndexLink slug="RecordDonation"/>

### Via The Auction Website

For donations recorded **Via The Auction Website**, your **_Bidders_** would be using a **Donation** element configured in either **_Cash Donation_** or **_Donation Item_** mode. This would assign the donations in the same manner as if you manually recorded them using the **Record Donation** function.

<Link/> <IndexLink slug="RowContent_DonationElement"/>
<Link/> <IndexLink slug="Walkthroughs_AddDonationPage"/>

### Donor Donations

For **Donor Donations**, or those donations that are **_not associated with an item_** being made available for bidding or purchase, you can use the **Add New Donation** function. This will create a Donor record (saved to the Organization) as well as potentially adding the Donor to those being displayed on the auction website via the **Donor Catalog** element.

::: info
Using the **Add New Donation** function will require a separate report to view the records of these donations. Something to consider before using this option is if it would be better to create a **Bidder Record** for the donor and use the **Record Donation** function as described above.
:::

<Link/> <IndexLink slug="AddDonorDonation">Add New Donation</IndexLink>

<HRDiv/>

## Reporting On The Donations

When **Reporting On The Donations** you will have to know if you have both **Bidder** donations and **Donor** donations. If you only have **Bidder Donations** then you only need to run one report to see all of the donations that were made by bidders.

![GIF](./index.assets/Reports_Financial.gif)

The **Reports** can be found from the main **Auction Dashboard** board and then clicking on the **_Financial_** tab to locate the *Income* reports.

### Donations Made By Bidders

**_Reports > Financial | Income > Bidder Donations_**

This report will display all of the bidder donations, both their **Cash** donations and the donations recorded on **Donation Items**.

### Donations Made By Donors

**_Reports > Financial | Income > Donor Donations_**

This report will display all of the bidder donations, both their **Cash** donations and their pledges on **Donation Items**.

<HRDiv/>

## Merge Bidder And Donor Donations

In the case where you have both **Bidder** and **Donor** donations and you want to see those numbers combined you will need to **Export** both donation "Reports" in XLS formatted files and merge (external to Auctria) them together using an appropriate spreadsheet application.

::: ideas
Deciding to only use the **Bidder Record** approaches (providing for bidders to use the auction website or using the **Record Donation** function) for cash donations and donation pledged to **Donation Items** will save this extra work.
:::

<HRDiv/>

::: recread
- <IndexLink slug="Walkthroughs_AddDonationPage"/>
- <IndexLink slug="Walkthroughs_DonationOnlyEvent"/>
- <IndexLink slug="TrackPaddleRaiseDonations"/>
:::

<ChildPages/>
<Revised text="Added" date="2021-11-24"/>
<Revised text="Updated" date="2021-11-25"/>
