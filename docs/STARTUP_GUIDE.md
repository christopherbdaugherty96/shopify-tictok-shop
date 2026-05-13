# Startup Guide

This guide is for starting a simple print-on-demand shirt business without touching inventory in person.

## Business Model

The business model is:

1. Design a shirt.
2. Create product mockups.
3. Post the shirt online.
4. Customer buys the shirt.
5. A print-on-demand provider prints and ships it.
6. You track the sale and improve the product/content.

You do not buy bulk inventory at the beginning.
You do not store shirts.
You do not package orders yourself.
You do not ship products by hand.

## Free-First Tool Stack

### Design

Start with:
- Canva free plan
- Photopea
- Kittl free plan if needed

Use these for:
- shirt graphics
- text designs
- simple brand assets
- social media post images

### Mockups

Start with:
- Printful mockup generator
- Printify mockup generator
- Canva mockup templates

Use mockups to show what the shirt looks like before anyone buys.

### Storefront

Start with one of these:

Option A: Shopify
- Best long-term storefront
- Usually has a monthly cost after trial
- Good for building a real brand

Option B: Etsy
- Lower starting friction
- Good for testing designs
- Marketplace already has buyers

Option C: TikTok Shop
- Useful if content is the main sales channel
- Requires setup and approval

Recommended starting path:

Use Printify or Printful for fulfillment and connect it to Shopify once the business idea is ready.

If money is tight, test designs with social posts first before paying for too many tools.

### Print-On-Demand Fulfillment

Use one provider first:

- Printify
- Printful

The provider handles:
- printing
- packing
- shipping
- fulfillment updates

You handle:
- design selection
- product listing
- pricing
- marketing
- customer communication
- tracking performance

### Content and Posting

Start with:
- TikTok
- Instagram Reels
- Facebook page/profile
- Pinterest if designs are visual

Use free tools:
- CapCut free plan
- Canva free plan
- phone camera/screen recording

### Tracking

Start with simple CSV trackers in this repo:
- `trackers/products.csv`
- `trackers/content_calendar.csv`
- `trackers/sales_pipeline.csv`
- `trackers/design_backlog.csv`

Do not overbuild tracking at the beginning.

## Step-By-Step Setup

### Step 1: Pick One Niche

Do not start with random shirts for everyone.

Pick one audience, such as:
- gym humor
- blue collar workers
- dog owners
- local pride
- car culture
- faith-based designs
- funny dad shirts
- gaming humor
- relationship humor

Write the niche in `docs/BRAND_IDENTITY.md`.

### Step 2: Create 10 Shirt Ideas

Use `trackers/design_backlog.csv` to list ideas.

For each idea, track:
- idea name
- audience
- design phrase
- style
- status
- notes

### Step 3: Make 1 to 3 Designs

Create the first designs using Canva or Photopea.

Rules:
- keep it simple
- make it readable
- avoid copyrighted logos, celebrities, sports teams, brands, or trademarked phrases
- export transparent PNG when possible
- keep source files organized

Save files under:

```txt
assets/designs/
```

### Step 4: Create Mockups

Use Printify or Printful mockup generator.

Create mockups for:
- front shirt image
- lifestyle image if available
- close-up image

Save mockups under:

```txt
assets/mockups/
```

### Step 5: Choose Fulfillment Provider

Pick one:

- Printify if you want more provider options and potentially lower costs
- Printful if you want a more polished all-in-one experience

Create an account.

Create one test product.

Do not add too many products yet.

### Step 6: Set Up Storefront

Recommended first real storefront:

Shopify + Printify or Shopify + Printful.

Basic Shopify setup:

1. Create Shopify account.
2. Choose a simple free theme.
3. Add store name.
4. Add logo or simple text brand.
5. Add About page.
6. Add Contact page.
7. Add Shipping/Returns policy.
8. Connect Printify or Printful app.
9. Create first product.
10. Review product page manually before publishing.

If you are not ready to pay for Shopify yet, keep everything in draft and use social posts to test interest first.

### Step 7: Price the Shirt

Basic pricing formula:

```txt
Retail Price - Product Cost - Shipping/Fees = Estimated Profit
```

Example:

```txt
Shirt sells for: $24.99
Production cost: $10.00
Shipping/fees estimate: $5.00
Estimated profit: $9.99
```

Do not price too low just to get sales.
You need margin for ads, mistakes, refunds, and discounts.

### Step 8: Draft Product Listing

Use:

```txt
templates/product_listing_template.md
```

Product listing should include:
- product title
- target buyer
- short description
- why someone would wear it
- size/color notes
- shipping note
- return note

### Step 9: Post Product Content

Start with organic posts.

Post formats:
- mockup image
- short video showing the shirt
- meme-style post related to the niche
- "would you wear this?" post
- behind-the-scenes design post

Use:

```txt
templates/tiktok_post_template.md
templates/instagram_caption_template.md
```

Track posts in:

```txt
trackers/content_calendar.csv
```

### Step 10: When Someone Buys

If Shopify is connected to Printify/Printful correctly:

1. Customer places order.
2. Payment goes through Shopify.
3. Order is sent to print-on-demand provider.
4. Provider prints the shirt.
5. Provider ships to customer.
6. Tracking updates are sent back.
7. You monitor the order and handle customer questions.

You should still review the first few orders carefully.

### Step 11: Track Sales

Use:

```txt
trackers/sales_pipeline.csv
```

Track:
- order date
- product
- sale price
- cost
- estimated profit
- source of sale
- customer issue if any
- notes

### Step 12: Improve Weekly

Each week, review:
- which designs got attention
- which posts got views
- which products got clicks
- which products sold
- what customers asked about

Then decide:
- make more designs in that style
- improve the listing
- change mockups
- make more posts
- test a new niche

## First 7-Day Plan

### Day 1

Pick niche and business name.
Create `docs/BRAND_IDENTITY.md`.

### Day 2

Create 10 design ideas.
Fill `trackers/design_backlog.csv`.

### Day 3

Create first 1 to 3 shirt designs.
Save files to `assets/designs/`.

### Day 4

Create mockups.
Save files to `assets/mockups/`.

### Day 5

Create Printify or Printful account.
Create one product draft.

### Day 6

Draft Shopify product page and social posts.
Do not overbuild the store yet.

### Day 7

Post first product content manually.
Track results.

## Rules For Starting

- Start with one niche.
- Start with one fulfillment provider.
- Start with one storefront path.
- Start with 1 to 3 products.
- Post manually first.
- Track everything simply.
- Do not automate until the business process works manually.

## What Not To Do First

Do not start with:
- paid ads
- bulk inventory
- complicated automation
- dozens of products
- multiple niches
- custom apps
- autonomous posting
- expensive software stack

First goal:

Prove that people care about one design enough to click, comment, share, or buy.
