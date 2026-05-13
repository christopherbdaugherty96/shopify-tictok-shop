# Shopify Website Integration

Yes, Shopify can be integrated with a separate website.

For Auralis, the recommended setup is:

```txt
Auralis website = brand, collections, art, discovery, storytelling
Shopify = checkout, payments, orders, customer emails, product backend
Printify/Printful = production and shipping
```

## Best Starting Architecture

Do not build custom checkout first.

Use the Auralis website as the front-facing brand layer and send buyers to Shopify for purchase.

Recommended flow:

```txt
Auralis website
→ collection page
→ product page or buy button
→ Shopify product page / Shopify checkout
→ Printify or Printful fulfillment
```

## Integration Options

## Option 1: Link To Shopify Product Pages

This is the simplest option.

How it works:

1. Product is created in Shopify.
2. Product page gets a Shopify URL.
3. Auralis website has a button like `Buy Now` or `Shop This Piece`.
4. Button links to the Shopify product page.

Best for:
- fastest launch
- lowest technical complexity
- testing products
- manual-first workflow

Pros:
- easy
- reliable checkout
- no custom code required
- Shopify handles payments and orders

Cons:
- buyer leaves the main website for Shopify
- less seamless brand experience

Recommended starting choice: yes.

## Option 2: Shopify Buy Button

Shopify offers buy buttons that can be embedded into another website.

How it works:

1. Product is created in Shopify.
2. Shopify generates a Buy Button embed.
3. The code is pasted into the Auralis website.
4. Customer can start checkout from the Auralis page.

Best for:
- simple websites
- product landing pages
- keeping the brand site as the main experience

Pros:
- cleaner than plain links
- still uses Shopify checkout
- avoids building custom payment systems

Cons:
- requires website platform/code support
- styling may need adjustment

Good second step after basic product links work.

## Option 3: Headless Shopify

Headless Shopify means using Shopify as the backend while building a fully custom frontend.

How it works:

```txt
Custom website frontend
→ Shopify Storefront API
→ Shopify checkout
→ fulfillment provider
```

Best for:
- advanced custom websites
- stronger brand control
- developers
- later-stage business

Pros:
- maximum design flexibility
- strong brand experience
- Shopify still handles commerce backend

Cons:
- more technical
- more maintenance
- slower to launch
- not needed for early validation

Do not start here.

## Recommended Starting Path For Auralis

Start with Option 1.

```txt
Auralis website pages
→ buttons linking to Shopify product pages
```

Then move to Option 2 if the brand site gets traction.

Only consider Option 3 later.

## Website Platforms That Can Work

Free/low-cost starting options:

- Carrd
- Framer
- Webflow
- WordPress
- GitHub Pages
- Vercel / Next.js if coding custom

Simplest non-code path:

```txt
Carrd or Framer + Shopify product links
```

More advanced custom path:

```txt
Next.js/Vercel + Shopify Storefront API later
```

## Auralis Website Structure

Recommended first version:

```txt
Home
Collections
Abstract Works
Geometric Works
Tie-Dye Colorways
Artwork
About
Contact
```

Each collection page should include:
- collection mood
- artwork/design images
- product mockups
- short descriptions
- buy buttons linking to Shopify

## Button Language

Use:

```txt
Shop This Piece
Buy This Design
View Product
Shop The Collection
```

Avoid language that overexplains fulfillment.

Customer-facing language should focus on:
- artwork
- collection
- product quality
- made-to-order timing
- shipping expectations

## Payment Handling

Do not process payments on the Auralis website directly at first.

Let Shopify handle:
- secure checkout
- card payments
- PayPal if enabled
- tax settings
- customer emails
- refunds
- order records

## Fulfillment Handling

Printify or Printful can connect to Shopify.

Order flow:

```txt
Customer buys through Shopify
→ order appears in Shopify
→ order syncs to Printify/Printful
→ provider produces item
→ provider ships item
→ tracking updates in Shopify
```

## Tracking

Use tracking links and UTMs later.

Example:

```txt
https://yourshop.myshopify.com/products/product-name?utm_source=auralis_site&utm_medium=collection_page&utm_campaign=abstract_works
```

Track performance in:

```txt
trackers/content_calendar.csv
trackers/products.csv
trackers/sales_pipeline.csv
```

## What Not To Build First

Do not start with:
- custom checkout
- custom cart
- custom payment processing
- custom fulfillment system
- large product catalog
- complex API integration

First goal:

```txt
prove that people click and buy from the Auralis brand site
```

## Final Recommendation

For the first real version of Auralis:

```txt
Auralis website on Carrd/Framer/Webflow
+ Shopify product pages for checkout
+ Printify or Printful for fulfillment
+ TikTok/Instagram/Facebook for traffic
```

This gives brand control without rebuilding ecommerce infrastructure.
