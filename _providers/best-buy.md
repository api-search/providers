---
api_count: 6
api_specs:
- filename: best-buy-products-api.yaml
  format: yaml
  label: Best Buy Products API
  slug: products-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/openapi/best-buy-products-api.yaml
- filename: best-buy-stores-api.yaml
  format: yaml
  label: Best Buy Stores API
  slug: stores-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/openapi/best-buy-stores-api.yaml
- filename: best-buy-recommendations-api.yaml
  format: yaml
  label: Best Buy Recommendations API
  slug: recommendations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/openapi/best-buy-recommendations-api.yaml
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
source_filename: apis.yml
source_yaml: "aid: best-buy\nurl: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/apis.yml\nname: Best Buy\ntags:\n  - Retail\n  - Consumer Electronics\n  - E-Commerce\n  - Products\n  - Stores\nx-type: company\ncreated: '2026-04-19'\nmodified: '2026-04-19'\ndescription: >-\n  Best Buy is a multinational consumer electronics retailer offering technology products,\n  services, and solutions through stores, online, and in-home consultations. Best Buy\n  provides a developer API giving access to product data, store locations, categories,\n  recommendations, open box offers, and commerce capabilities for partners and developers\n  building retail integrations and applications.\napis:\n  - aid: best-buy:products-api\n    name: Best Buy Products API\n    tags:\n      - Products\n      - Retail\n      - Electronics\n      - Pricing\n      - Inventory\n    humanURL: https://bestbuyapis.github.io/api-documentation/#products-api\n    properties:\n      - type: Documentation\n\
  \        url: https://bestbuyapis.github.io/api-documentation/#products-api\n      - type: OpenAPI\n        url: openapi/best-buy-products-api.yaml\n    description: >-\n      Access over one million current and historical Best Buy products with real-time\n      pricing, availability, specifications, images, customer reviews, and categorization\n      data. Supports detailed queries by SKU, keyword search, and filtering across\n      all product attributes.\n\n  - aid: best-buy:stores-api\n    name: Best Buy Stores API\n    tags:\n      - Stores\n      - Locations\n      - Retail\n      - Geolocation\n    humanURL: https://bestbuyapis.github.io/api-documentation/#stores-api\n    properties:\n      - type: Documentation\n        url: https://bestbuyapis.github.io/api-documentation/#stores-api\n      - type: OpenAPI\n        url: openapi/best-buy-stores-api.yaml\n    description: >-\n      Retrieve comprehensive store location and operational data for 1,587+ Best Buy\n      locations across\
  \ the United States and Puerto Rico. Supports area-based searches\n      by postal code or latitude/longitude, store hours, services, and in-store product\n      availability.\n\n  - aid: best-buy:categories-api\n    name: Best Buy Categories API\n    tags:\n      - Categories\n      - Taxonomy\n      - Products\n    humanURL: https://bestbuyapis.github.io/api-documentation/#categories-api\n    properties:\n      - type: Documentation\n        url: https://bestbuyapis.github.io/api-documentation/#categories-api\n    description: >-\n      Navigate Best Buy's product taxonomy with access to 4,328+ product categories.\n      Browse hierarchical category paths from root to specific categories and integrate\n      with product searches for category-specific filtering.\n\n  - aid: best-buy:recommendations-api\n    name: Best Buy Recommendations API\n    tags:\n      - Recommendations\n      - Personalization\n      - Products\n    humanURL: https://bestbuyapis.github.io/api-documentation/#recommendations-api\n\
  \    properties:\n      - type: Documentation\n        url: https://bestbuyapis.github.io/api-documentation/#recommendations-api\n      - type: OpenAPI\n        url: openapi/best-buy-recommendations-api.yaml\n    description: >-\n      Leverage customer behavior data to surface relevant products through trending\n      products, most viewed, also viewed, also bought, and viewed-ultimately-bought\n      recommendation types. Supports queries by category ID or specific SKU.\n\n  - aid: best-buy:buying-options-api\n    name: Best Buy Buying Options (Open Box) API\n    tags:\n      - Open Box\n      - Refurbished\n      - Discounts\n      - Products\n    humanURL: https://bestbuyapis.github.io/api-documentation/#buying-options-api\n    properties:\n      - type: Documentation\n        url: https://bestbuyapis.github.io/api-documentation/#buying-options-api\n    description: >-\n      Access discounted open box and Geek Squad certified refurbished merchandise with\n      ship-from-store fulfillment.\
  \ Supports single SKU, batch queries up to 100 SKUs,\n      and category-based discovery with condition ratings updated every 5 minutes.\n\n  - aid: best-buy:commerce-api\n    name: Best Buy Commerce API\n    tags:\n      - Commerce\n      - Orders\n      - Fulfillment\n      - Partners\n    humanURL: https://bestbuyapis.github.io/api-documentation/#commerce-api\n    properties:\n      - type: Documentation\n        url: https://bestbuyapis.github.io/api-documentation/#commerce-api\n    description: >-\n      Enable integrated shopping experiences for authorized partners with product\n      availability lookups, shipping cost calculations, and order creation supporting\n      store pickup, ship-to-home, and home delivery fulfillment options.\n\ncommon:\n  - type: Website\n    url: https://www.bestbuy.com\n  - type: DeveloperPortal\n    url: https://developer.bestbuy.com\n  - type: Documentation\n    url: https://bestbuyapis.github.io/api-documentation/\n  - type: GettingStarted\n    url:\
  \ https://bestbuyapis.github.io/api-documentation/#user-guide\n  - type: Authentication\n    url: https://bestbuyapis.github.io/api-documentation/#authorization\n  - type: SignUp\n    url: https://developer.bestbuy.com\n  - type: GitHubOrganization\n    url: https://github.com/BestBuyAPIs\n  - type: GitHubRepository\n    url: https://github.com/BestBuyAPIs/api-documentation\n  - type: Features\n    data:\n      - name: Products API\n        description: Access to over one million products with real-time pricing, availability, and specifications.\n      - name: Stores API\n        description: Comprehensive data for 1,587+ US Best Buy locations including hours, services, and proximity search.\n      - name: Categories API\n        description: Navigate 4,328+ product categories with hierarchical taxonomy browsing.\n      - name: Recommendations API\n        description: Customer behavior-powered recommendations including trending, most viewed, also viewed, and also bought.\n      - name:\
  \ Open Box API\n        description: Discounted open box and certified refurbished merchandise with condition ratings and availability.\n      - name: Commerce API\n        description: Partner-level shopping integration with order creation and fulfillment management.\n      - name: Query Builder\n        description: Interactive tool for constructing API queries without starting from scratch.\n      - name: JSON and XML Responses\n        description: Flexible response format support with JSON and XML output options.\n      - name: Pagination and Cursors\n        description: Page-based and cursor-mark pagination for large product datasets.\n      - name: Faceted Search\n        description: Summary aggregations by specified attributes with count limits for faceted browsing.\n  - type: UseCases\n    data:\n      - name: Product Discovery\n        description: Full-text search and filtering across product descriptions, specifications, and reviews.\n      - name: Inventory Management\n\
  \        description: Real-time in-store availability checking by postal code or store ID.\n      - name: Recommendation Widgets\n        description: Display trending, most-viewed, and also-bought products on product detail pages.\n      - name: Store Locator\n        description: Proximity-based store search with hours verification and service availability.\n      - name: Open Box Sourcing\n        description: Identify discounted alternatives with transparent condition ratings.\n      - name: Price Monitoring\n        description: Track product price changes and availability updates.\n      - name: Retail Integration\n        description: Build shopping experiences integrated with Best Buy's product catalog and fulfillment.\n      - name: Affiliate Commerce\n        description: Commission-based product recommendations with affiliate partner integration.\n  - type: Integrations\n    data:\n      - name: Postman\n        description: Pre-built Postman collection available for testing\
  \ and exploring Best Buy APIs.\n      - name: Impact Affiliate Network\n        description: Affiliate commission integration using Impact Partner ID for revenue attribution.\n  - type: RateLimits\n    url: https://bestbuyapis.github.io/api-documentation/#rate-limiting\n  - type: SpectralRules\n    url: rules/best-buy-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/retail-discovery.yaml\n  - type: Vocabulary\n    url: vocabulary/best-buy-vocabulary.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/best-buy/refs/heads/main/apis.yml
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
