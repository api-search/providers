---
api_count: 1
api_specs:
- filename: bjs-wholesale-club-openapi.yaml
  format: yaml
  label: BJ's Wholesale Club API
  slug: bjs-wholesale-club
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bjs-wholesale-club/refs/heads/main/openapi/bjs-wholesale-club-openapi.yaml
apis:
- description: BJ's Wholesale Club provides partner and affiliate integrations enabling access to product catalog, pricing, inventory availability, membership verification, and order management capabilities. Integra
  name: BJ's Wholesale Club API
  slug: bjs-wholesale-club
capabilities:
- description: ''
  name: Bjs Wholesale Club
  slug: bjs-wholesale-club
common:
- title: ''
  type: Website
  url: https://www.bjs.com
- title: ''
  type: PrivacyPolicy
  url: https://www.bjs.com/content/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.bjs.com/content/terms-and-conditions
- title: ''
  type: SignUp
  url: https://www.bjs.com/content/membership
- title: ''
  type: Support
  url: https://www.bjs.com/content/help-center
- title: ''
  type: SpectralRules
  url: rules/bjs-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/bjs-wholesale-club.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/bjs-vocabulary.yaml
created: '2026-03-21'
description: BJ's Wholesale Club is a leading operator of membership warehouse clubs concentrated primarily on the eastern half of the United States. BJ's offers its members significant savings on a wide assortment of merchandise, including fresh foods, groceries, household essentials, and general merchandise. The company operates over 230 clubs and is focused on digital transformation, offering APIs to partners for product data, inventory, pricing, and order management integrations.
features:
- description: Supports membership-based access model for in-club and online purchasing, including membership verification and renewal.
  name: Membership Management
- description: Broad product assortment including fresh foods, groceries, household essentials, electronics, and general merchandise available via digital commerce integrations.
  name: Product Catalog
- description: Online ordering and delivery capabilities integrating with BJ's digital platform for partner fulfillment and affiliate programs.
  name: Digital Commerce
- description: Buy Online, Pick Up In Club capabilities available through BJ's digital platform for member convenience.
  name: Curbside Pickup
- description: Real-time inventory status across BJ's club locations, supporting in-club and curbside pickup fulfillment routing.
  name: Inventory Availability
- description: Find BJ's club locations by ZIP code with hours, services, and amenities including gas stations, optical, and tire centers.
  name: Club Locator
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: BJ's affiliate program is managed through CJ Affiliate (Commission Junction) for tracking and payments.
  name: Commission Junction
- description: Product feeds integrated with Google Shopping for product discovery and advertising.
  name: Google Shopping
- description: BJ's grocery delivery is available through the Instacart platform for same-day delivery to members.
  name: Instacart
jsonld:
- class_count: 5
  name: Bjs Context
  property_count: 0
  slug: bjs-context
layout: provider
modified: '2026-04-21'
name: BJ's Wholesale Club
rules:
- name: BJ's Wholesale Club API Rules
  rule_count: 5
  severity_counts:
    error: 0
    hint: 0
    info: 0
    warn: 5
  slug: bjs-spectral-rules
skills: []
slug: bjs-wholesale-club
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bjs-wholesale-club\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bjs-wholesale-club/refs/heads/main/apis.yml\nname: BJ's Wholesale Club\ndescription: >-\n  BJ's Wholesale Club is a leading operator of membership warehouse clubs concentrated\n  primarily on the eastern half of the United States. BJ's offers its members significant\n  savings on a wide assortment of merchandise, including fresh foods, groceries, household\n  essentials, and general merchandise. The company operates over 230 clubs and is focused\n  on digital transformation, offering APIs to partners for product data, inventory, pricing,\n  and order management integrations.\ntags:\n  - Ecommerce\n  - Membership\n  - Retail\n  - Wholesale\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: '2026-03-21'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\napis:\n  - aid: bjs-wholesale-club:bjs-wholesale-club\n    name: BJ's Wholesale Club\
  \ API\n    description: >-\n      BJ's Wholesale Club provides partner and affiliate integrations enabling access\n      to product catalog, pricing, inventory availability, membership verification,\n      and order management capabilities. Integrations are available through their\n      partner program and digital commerce platform.\n    humanURL: https://www.bjs.com\n    tags:\n      - Ecommerce\n      - Membership\n      - Retail\n      - Wholesale\n    properties:\n      - type: Documentation\n        url: https://www.bjs.com\n      - type: OpenAPI\n        url: openapi/bjs-wholesale-club-openapi.yaml\n      - type: JSONSchema\n        url: json-schema/bjs-product-schema.json\n      - type: JSONSchema\n        url: json-schema/bjs-membership-schema.json\n      - type: JSONSchema\n        url: json-schema/bjs-order-schema.json\n      - type: JSONStructure\n        url: json-structure/bjs-product-structure.json\n      - type: JSONStructure\n        url: json-structure/bjs-membership-structure.json\n\
  \      - type: JSONStructure\n        url: json-structure/bjs-order-structure.json\n      - type: JSONLD\n        url: json-ld/bjs-context.jsonld\n      - type: Example\n        url: examples/bjs-product-example.json\n      - type: Example\n        url: examples/bjs-membership-example.json\n      - type: Example\n        url: examples/bjs-order-example.json\n      - type: PrivacyPolicy\n        url: https://www.bjs.com/content/privacy-policy\n      - type: TermsOfService\n        url: https://www.bjs.com/content/terms-and-conditions\ncommon:\n  - type: Website\n    url: https://www.bjs.com\n  - type: PrivacyPolicy\n    url: https://www.bjs.com/content/privacy-policy\n  - type: TermsOfService\n    url: https://www.bjs.com/content/terms-and-conditions\n  - type: SignUp\n    url: https://www.bjs.com/content/membership\n  - type: Support\n    url: https://www.bjs.com/content/help-center\n  - type: SpectralRules\n    url: rules/bjs-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/bjs-wholesale-club.yaml\n\
  \  - type: Vocabulary\n    url: vocabulary/bjs-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Membership Management\n        description: >-\n          Supports membership-based access model for in-club and online purchasing,\n          including membership verification and renewal.\n      - name: Product Catalog\n        description: >-\n          Broad product assortment including fresh foods, groceries, household\n          essentials, electronics, and general merchandise available via digital\n          commerce integrations.\n      - name: Digital Commerce\n        description: >-\n          Online ordering and delivery capabilities integrating with BJ's digital\n          platform for partner fulfillment and affiliate programs.\n      - name: Curbside Pickup\n        description: >-\n          Buy Online, Pick Up In Club capabilities available through BJ's digital\n          platform for member convenience.\n      - name: Inventory Availability\n        description:\
  \ >-\n          Real-time inventory status across BJ's club locations, supporting\n          in-club and curbside pickup fulfillment routing.\n      - name: Club Locator\n        description: >-\n          Find BJ's club locations by ZIP code with hours, services, and amenities\n          including gas stations, optical, and tire centers.\n  - type: UseCases\n    data:\n      - name: Affiliate Marketing\n        description: >-\n          Partner programs enabling affiliate marketers to promote BJ's membership\n          and products with commission-based compensation.\n      - name: Product Data Integration\n        description: >-\n          Access product catalog and pricing data to enable comparison shopping\n          and product listing integrations.\n      - name: Membership Verification\n        description: >-\n          Verify BJ's membership status for partner benefits and co-branded\n          programs.\n      - name: Order Management\n        description: >-\n          Manage\
  \ orders through BJ's digital commerce platform for dropship\n          and fulfillment partnerships.\n      - name: Inventory Routing\n        description: >-\n          Route orders to the nearest club with available inventory for\n          curbside pickup or local delivery fulfillment.\n  - type: Integrations\n    data:\n      - name: Commission Junction\n        description: >-\n          BJ's affiliate program is managed through CJ Affiliate (Commission Junction)\n          for tracking and payments.\n      - name: Google Shopping\n        description: >-\n          Product feeds integrated with Google Shopping for product discovery\n          and advertising.\n      - name: Instacart\n        description: >-\n          BJ's grocery delivery is available through the Instacart platform\n          for same-day delivery to members.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bjs-wholesale-club/refs/heads/main/apis.yml
tags:
- Ecommerce
- Membership
- Retail
- Wholesale
url: https://raw.githubusercontent.com/api-evangelist/bjs-wholesale-club/refs/heads/main/apis.yml
use_cases:
- description: Partner programs enabling affiliate marketers to promote BJ's membership and products with commission-based compensation.
  name: Affiliate Marketing
- description: Access product catalog and pricing data to enable comparison shopping and product listing integrations.
  name: Product Data Integration
- description: Verify BJ's membership status for partner benefits and co-branded programs.
  name: Membership Verification
- description: Manage orders through BJ's digital commerce platform for dropship and fulfillment partnerships.
  name: Order Management
- description: Route orders to the nearest club with available inventory for curbside pickup or local delivery fulfillment.
  name: Inventory Routing
---
