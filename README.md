# Aster & Orbit

Aster & Orbit is a fictional jewelry storefront concept for a Shopify theme-development portfolio. Its visual direction is celestial and editorial: **“Wear a little wonder.”**

## Storefront concept

- Editorial homepage hero with a link to the featured pieces collection.
- Featured products followed by collection cards for necklaces, earrings, and charms and gifts.
- Brand-story section describing celestial-inspired jewelry for everyday wear.
- Cream and lavender surfaces with deep violet and gold accents; EB Garamond headings and Assistant body text.
- Demo-only announcement and product copy. Products and prices are illustrative and are not available to order.

## What this project demonstrates

This is a later learning/design iteration based on [Shopify Dawn](https://github.com/Shopify/dawn). The current project configures Dawn's existing theme sections, product template, announcement bar, typography, and color schemes through Shopify theme settings.

The product template includes a disclosures section that uses Shopify's product disclosure metafields and Dawn's disclosure rendering. This project does not claim that feature as custom Liquid written for this store. No Shopify app or external integration is included.

The main theme-editor configuration is stored in:

- `config/settings_data.json`
- `sections/header-group.json`
- `templates/index.json`
- `templates/product.json`

Some images and catalog references point to media and products in Shopify Admin. Those store-managed resources are not necessarily included in this Git repository and may need to be added again when previewing with another development store.

## Preview locally

Requirements: Node.js 22.12 or newer, Git 2.28.0 or newer, Shopify CLI, and access to a Shopify development store.

From this theme directory, run:

```powershell
shopify theme dev --store your-store.myshopify.com
```

Sign in in the browser if the CLI requests it. Open the local preview URL printed by the command (usually `http://127.0.0.1:9292`) in Google Chrome while the command remains running. The command creates a temporary development theme; it does not publish the theme.

## Demo and attribution

This is a fictional learning/demo storefront, not client or production work. Checkout and fulfillment are for testing only; do not treat demo products or prices as real offers. The base Dawn theme is distributed under the MIT License; see [`LICENSE.md`](LICENSE.md).

Never commit Shopify passwords, access tokens, `.env` files, or CLI login data.
