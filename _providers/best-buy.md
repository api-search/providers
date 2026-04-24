---
api_count: 6
apis:
- description: Access over one million current and historical Best Buy products with real-time pricing, availability, specifications, images, customer reviews, and categorization data. Supports detailed queries by S
  name: Best Buy Products API
  slug: products-api
- description: Retrieve comprehensive store location and operational data for 1,587+ Best Buy locations across the United States and Puerto Rico. Supports area-based searches by postal code or latitude/longitude, st
  name: Best Buy Stores API
  slug: stores-api
- description: Navigate Best Buy's product taxonomy with access to 4,328+ product categories. Browse hierarchical category paths from root to specific categories and integrate with product searches for category-spec
  name: Best Buy Categories API
  slug: categories-api
- description: Leverage customer behavior data to surface relevant products through trending products, most viewed, also viewed, also bought, and viewed-ultimately-bought recommendation types. Supports queries by ca
  name: Best Buy Recommendations API
  slug: recommendations-api
- description: Access discounted open box and Geek Squad certified refurbished merchandise with ship-from-store fulfillment. Supports single SKU, batch queries up to 100 SKUs, and category-based discovery with condi
  name: Best Buy Buying Options (Open Box) API
  slug: buying-options-api
- description: Enable integrated shopping experiences for authorized partners with product availability lookups, shipping cost calculations, and order creation supporting store pickup, ship-to-home, and home deliver
  name: Best Buy Commerce API
  slug: commerce-api
capabilities:
- description: Unified retail discovery workflow combining product search, store locator, and personalized recommendations. Designed for developers and partners building retail integrations, shopping apps, and e-com
  name: Best Buy Retail Discovery
  slug: retail-discovery
common:
- title: ''
  type: Website
  url: https://www.bestbuy.com
- title: ''
  type: DeveloperPortal
  url: https://developer.bestbuy.com
- title: ''
  type: Documentation
  url: https://bestbuyapis.github.io/api-documentation/
- title: ''
  type: GettingStarted
  url: https://bestbuyapis.github.io/api-documentation/#user-guide
- title: ''
  type: Authentication
  url: https://bestbuyapis.github.io/api-documentation/#authorization
- title: ''
  type: SignUp
  url: https://developer.bestbuy.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/BestBuyAPIs
- title: ''
  type: GitHubRepository
  url: https://github.com/BestBuyAPIs/api-documentation
- title: ''
  type: RateLimits
  url: https://bestbuyapis.github.io/api-documentation/#rate-limiting
- title: ''
  type: SpectralRules
  url: rules/best-buy-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/retail-discovery.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/best-buy-vocabulary.yaml
created: '2026-04-19'
description: Best Buy is a multinational consumer electronics retailer offering technology products, services, and solutions through stores, online, and in-home consultations. Best Buy provides a developer API giving access to product data, store locations, categories, recommendations, open box offers, and commerce capabilities for partners and developers building retail integrations and applications.
features:
- description: Access to over one million products with real-time pricing, availability, and specifications.
  name: Products API
- description: Comprehensive data for 1,587+ US Best Buy locations including hours, services, and proximity search.
  name: Stores API
- description: Navigate 4,328+ product categories with hierarchical taxonomy browsing.
  name: Categories API
- description: Customer behavior-powered recommendations including trending, most viewed, also viewed, and also bought.
  name: Recommendations API
- description: Discounted open box and certified refurbished merchandise with condition ratings and availability.
  name: Open Box API
- description: Partner-level shopping integration with order creation and fulfillment management.
  name: Commerce API
- description: Interactive tool for constructing API queries without starting from scratch.
  name: Query Builder
- description: Flexible response format support with JSON and XML output options.
  name: JSON and XML Responses
- description: Page-based and cursor-mark pagination for large product datasets.
  name: Pagination and Cursors
- description: Summary aggregations by specified attributes with count limits for faceted browsing.
  name: Faceted Search
image: ''
integrations:
- description: Pre-built Postman collection available for testing and exploring Best Buy APIs.
  name: Postman
- description: Affiliate commission integration using Impact Partner ID for revenue attribution.
  name: Impact Affiliate Network
jsonld:
- class_count: 6
  name: Best Buy Products Api Context
  property_count: 38
  slug: best-buy-products-api-context
- class_count: 3
  name: Best Buy Recommendations Api Context
  property_count: 20
  slug: best-buy-recommendations-api-context
- class_count: 5
  name: Best Buy Stores Api Context
  property_count: 27
  slug: best-buy-stores-api-context
layout: provider
modified: '2026-04-19'
name: Best Buy
rules:
- name: Best Buy API Rules
  rule_count: 32
  severity_counts:
    error: 15
    hint: 0
    info: 4
    warn: 13
  slug: best-buy-spectral-rules
skills: []
slug: best-buy
solutions: []
tags:
- Retail
- Consumer Electronics
- E-Commerce
- Products
- Stores
url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/apis.yml
use_cases:
- description: Full-text search and filtering across product descriptions, specifications, and reviews.
  name: Product Discovery
- description: Real-time in-store availability checking by postal code or store ID.
  name: Inventory Management
- description: Display trending, most-viewed, and also-bought products on product detail pages.
  name: Recommendation Widgets
- description: Proximity-based store search with hours verification and service availability.
  name: Store Locator
- description: Identify discounted alternatives with transparent condition ratings.
  name: Open Box Sourcing
- description: Track product price changes and availability updates.
  name: Price Monitoring
- description: Build shopping experiences integrated with Best Buy's product catalog and fulfillment.
  name: Retail Integration
- description: Commission-based product recommendations with affiliate partner integration.
  name: Affiliate Commerce
---
