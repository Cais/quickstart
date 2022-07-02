---
title: Images
slug: KeyTopic_Images
published: master
first_published: 2021-08
tags:
  - key_topics
  - images
  - 2022-01
---

# Images

As the old adage goes "a picture is worth a thousand words" and Auctria provides for using images on the platform with items, as logos for donors, sponsors, and the organization as well as a means to provide decorative [elements](./#website-elements) on your **Auction Website**.

<Linked slug="ItemDetailsImagesAndLinks"/>
<Linked slug="AddDonorImage"/>
<Linked slug="BidderDetails"/>

<HRDiv/>

<details open>
  <summary class="title">
    Images Key Topic: Table Of Contents
  </summary>

  [[toc]]

</details>

<HRDiv/>

## Concepts

- **Images**
  To further customize your auctions you can add images for the following items: **Organization Logo**; **Auction Logo**; **Item Images**; **Donor Images**; and, if a **_Sponsor_**, you can also add **Bidder Images**.
- **Image Sizes**
  In Auctria, **Image Sizes** (or "dimensions") can play a very important role where they are used. High resolution images are **_not_** necessary for **Auction Website** usage and *will* slow page loading times.
- **Image Type**
  Only **JPEG** (`.jpg`, `.jpeg`) and **PNG** (`.png`) file formats are currently accepted.


<Linked slug="OrganizationLogo"/>
<Linked slug="AuctionLogo">Auction Logo</Linked>
<Linked slug="EditItemDetails" anchor="add-or-modify-images">Item Images</Linked>
<Linked slug="AddDonorImage">Donor Images</Linked>
<Linked slug="BidderDetails" anchor="images">Bidder Images</Linked>

::: recread
- See <IndexLink slug="UsingImages"/> under the **Using Auctria** section for more information.
- Have a look at <IndexLink slug="ImageSizes"/> as it goes into more detail on **Image Sizes** and what may work best on your **Auction Website**.
:::

<HRDiv/>

## Items

- **Images And Links**
  You can save and manage your item images on the **Images/Links** tab. These are the specific images associated with the item. You can set the default item image used as the primary display reference. Additional images can also be uploaded to automatically generate an image carousel on the **Item Details** website page.
  <Linked slug="ItemDetailsImagesAndLinks"/> <Linked slug="RowContent_ItemDetails">Item Details Element</Linked>
- **Add New Item** - **Images**
  You can add **Images** when you are creating your auction items.
  <Linked slug="AddNewItem" anchor="images">Add New Item | Images</Linked>
- **Batch Image Upload** <Advanced/>
  You can upload multiple images at once and have the system automatically assign them to different items. Each image **must be mapped** to a **single item**, however, if you have a folder of images named `item_1`, `item_2`, `item_3` the system will upload the highlighted images in the folder and assign them to items# `1`, `2`, `3`, etc.
  <Linked slug="BatchImageUpload"/>

::: recread
- See <IndexLink slug="EditItemDetails" anchor="add-or-modify-images-and-links"/> under <IndexLink slug="EditItemDetails"/> for more information on modifying item images.
:::

<HRDiv/>

## Logos

- **Bidder Details** - **Sponsor Logos**
  The **IMAGES** tab is *only* used when a **Bidder** purchases an item with the **Is Sponsorship** option checked. See <IndexLink slug="Concepts_SellingSponsorships"/> for more information on this.
  <Linked slug="BidderDetails" anchor="images">Bidder Images</Linked>
- **Add Donors** - **Logos**
  The Logos section shows the images that have been uploaded for the Donors, such as a company logo or brand logo.
  <Linked slug="AddDonors" anchor="logos">Donor Logos</Linked>
  ::: info
  When you upload **Donor Logos** the system will resize them as necessary. An original source size of *no more than 1000px* works well; and, ideally, the logo should be "square" rather than wide and short, or tall and narrow.
  :::
- **Add Images To Donors**
  One or more images may be added to each donor record. By adding an image to a donor, that image will be available to be included in the auction catalog and on gift certificates.
  <Linked slug="AddDonorImage"/>
- **Donor Details** - **Images Tab**
  The **Images** tab lets you upload a **Donor Logo**.
  <Linked slug="DonorDetails" anchor="images-tab">Donor Details - Images Tab</Linked> <Linked slug="AddDonorImage">Donor Logo</Linked>.

<HRDiv/>

## Website

- **Choose Image**
  Clicking on the preview icon beside the "image" text will open the **Choose Image** pop-up window. You can also open "Choose Image" pop-up window by double-clicking the default image or using the cog action pencil icon.
  <Linked slug="ChooseImage"/>
- **How Do I Link Images?**
  You can make an inserted **Image** using the **Image** element "click-able" by using its **Add Behavior** property.
  <Linked slug="LinkImages"/>
  <Linked slug="BasicContent_Image">Image Element</Linked> <Linked slug="AddBehavior"/>

### Website Elements

A collection of image-specific website elements used with images.

- Dashboard<sup>*</sup> | Website | Website Content | Column Content > <IndexLink slug="BasicContent_Image"/>
- Dashboard<sup>*</sup> | Website | Website Content | Column Content > <IndexLink slug="BasicContent_ImageCarousel"/>
- Dashboard<sup>*</sup> | Website | Website Content | Column Content > <IndexLink slug="BasicContent_ParallaxImage"/>
- Dashboard<sup>*</sup> | Website | Website Content | Column Content > <IndexLink slug="BasicContent_ItemImageCarousel"/>
  - The **Item Image Carousel** only works with the default images of the selected items.

::: feet NOTE
*Dashboard* (above) is in reference to <IndexLink slug="AuctionTeamExperience"/> in the **User Guide**.
:::

<HRDiv/>

::: recread Related Topics
- The <IndexLink slug="BasicContent_Video"/> element can be inserted in the same fashion as a basic image element and may suit your needs better in some cases.
- You can <IndexLink slug="CustomizeEmailHeader"/> and <IndexLink slug="CustomizeEmailFooter"/> if you want to change the default image used by the system.
:::

<ChildPages/>
<Revised text="Reviewed" date="2022-04-04"/>
