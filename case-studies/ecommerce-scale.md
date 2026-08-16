---
layout: content
permalink: /case-studies/ecommerce-scale/
title: Scaling an eCommerce Portfolio from $400K to $8.5M
description: "The Magento, AWS, catalog, marketplace, SEO, and conversion systems David Gitman used to scale an eCommerce portfolio from $400K to $8.5M ARR."
last_modified_at: "2026-08-16"
date: "2026-08-16"
date_published: "2026-08-16"
schema_type: Article
seo:
  type: Article
breadcrumb_parent: Case Studies
breadcrumb_parent_url: /case-studies/
eyebrow: eCommerce Growth & Architecture Case Study
lede: "A decade of catalog, infrastructure, marketplace, SEO, conversion, and operational work across automotive aftermarket and plumbing businesses."
schema_about:
  - Magento
  - Amazon Web Services
  - eCommerce growth
  - Catalog systems
  - Technical SEO
---

<div class="metric-grid">
  <div class="metric"><strong>$400K → $8.5M</strong><span>annual recurring revenue</span></div>
  <div class="metric"><strong>130K+</strong><span>monthly organic visitors</span></div>
  <div class="metric"><strong>~165%</strong><span>conversion-rate improvement</span></div>
  <div class="metric"><strong>1.5M+</strong><span>products supported</span></div>
</div>

## Context

At Cooper Square Ventures, I co-founded and served as Chief Technology Officer for a portfolio that included Next Day Auto Parts, Auto Parts Nerd, Woodbury Automotive Warehouse, Car Part Kings, Plumburs, and ChannelReply.

The businesses combined complex supplier catalogs, automotive fitment, large product volumes, marketplace distribution, and fulfillment requirements. Growth depended on improving the entire operating system rather than replacing only the storefront.

## Catalog and data foundation

Supplier feeds arrived with inconsistent identifiers, attributes, categories, prices, and availability. Automotive products added fitment relationships that had to connect parts to compatible vehicles.

I built and led systems for:

- Supplier ingestion and repeatable ETL workflows.
- Product normalization, taxonomy, and attribute mapping.
- Automotive fitment data and catalog relationships.
- Price, inventory, and availability updates.
- Amazon and eBay marketplace feed management.
- Migration and expansion of Magento product catalogs.

These systems supported a Magento footprint of more than 1.5 million products and a very large set of programmatically generated landing-page combinations.

## Infrastructure and performance

The platform ran across distributed AWS infrastructure using PHP, MySQL, Apache, Nginx, Redis, Memcached, Varnish, HHVM, Linux, Pentaho ETL, and Symfony. The work included caching, database and application performance, deployment automation, production reliability, and capacity for high-volume catalog processing.

Performance engineering was connected to conversion and crawlability. Faster, more reliable pages improved the shopper experience while helping search engines process a large catalog efficiently.

## SEO, conversion, and distribution

Growth came from coordinated platform and marketing work:

- Technical SEO and scalable category, product, and fitment landing pages.
- Catalog expansion based on available supplier and fitment data.
- Conversion-rate optimization across discovery, product, cart, and checkout flows.
- Amazon and eBay marketplace distribution.
- Analytics and operational feedback used to prioritize platform improvements.

## Outcome

Across the portfolio, revenue grew from approximately $400K to $8.5M ARR, organic traffic reached more than 130,000 monthly visitors, and conversion rates improved by approximately 165%. The durable advantage was the combination of normalized product data, scalable infrastructure, marketplace reach, and an experimentation loop tied to customer behavior.

<div class="callout">
  <p><strong>Architecture lesson:</strong> for catalog-driven commerce, product data quality, infrastructure, SEO, merchandising, and fulfillment are one connected growth system.</p>
</div>

<div class="next-links">
  <a href="{{ '/expertise/ecommerce-platforms/' | relative_url }}">eCommerce platform expertise →</a>
  <a href="{{ '/expertise/cloud-devops/' | relative_url }}">Cloud &amp; DevOps expertise →</a>
</div>
