# Shopify SEO Code helpers

## Meta Snippets

* [`head-meta.liquid`](https://github.com/digital-stronghold/seo-shopify/blob/master/theme/snippets/head-meta.liquid)
* [`head-meta-social.liquid`](https://github.com/digital-stronghold/seo-shopify/blob/master/theme/snippets/head-meta-social.liquid)
* [`structured-data.liquid`](https://github.com/digital-stronghold/seo-shopify/blob/master/theme/snippets/structured-data.liquid)

## Alternate Page Templates for Checking

### [[SEO] Empty Collections Checker](https://github.com/digital-stronghold/seo-shopify/blob/master/theme/templates/page.check.collections.liquid)

This template can be used to help identify empty Collections, which should either be unpublished (consider also creating a redirect) or hidden via Admin API*. [See here](https://www.taylorstitch.com/pages/seo-check-collections) for example output.

### [[SEO] Pages Checker](https://github.com/digital-stronghold/seo-shopify/blob/master/theme/templates/page.check.pages.liquid)

This template can be used to review published pages that are visible to sitemaps and published pages that are hidden via Admin API*, in case action is needed on either. [See here]()

(*) See [Manage SEO data with the Admin API](https://shopify.dev/api/examples/marketing-seo) for reference. **TL;DR** Add `seo.hidden` metafield, with value `1`.

Also see [Editing robots.txt.liquid ](https://help.shopify.com/en/manual/promoting-marketing/seo/editing-robots-txt)