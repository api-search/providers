---
api_count: 1
api_specs:
- filename: vehicle-api-openapi.yml
  format: yaml
  label: Vehicle API (Edmunds)
  slug: vehicle-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vehicle-api/refs/heads/main/openapi/vehicle-api-openapi.yml
apis:
- description: The Edmunds Vehicle API provides access to a comprehensive automotive data platform including vehicle makes, models, trims, configurations, specifications, media (photos and videos), True Market Value
  name: Vehicle API (Edmunds)
  slug: vehicle-api
capabilities:
- description: Customer workflow capability for automotive vehicle data research and shopping. Combines Edmunds vehicle catalog (makes, models, styles), TMV pricing, media assets, and dealer inventory into a unified
  name: Vehicle Data Workflow
  slug: vehicle-data
common:
- title: ''
  type: Website
  url: https://developer.edmunds.com/
- title: ''
  type: Portal
  url: https://developer.edmunds.com/
- title: ''
  type: Documentation
  url: https://developer.edmunds.com/api-documentation/vehicle/
- title: ''
  type: Authentication
  url: https://developer.edmunds.com/api-documentation/overview/
- title: ''
  type: GettingStarted
  url: https://developer.edmunds.com/api-documentation/overview/
- title: ''
  type: Support
  url: https://developer.edmunds.com/support/
- title: Vehicle API Spectral Rules
  type: SpectralRules
  url: rules/vehicle-api-spectral-rules.yml
- title: Vehicle API Vocabulary
  type: Vocabulary
  url: vocabulary/vehicle-api-vocabulary.yml
- title: Vehicle Data
  type: NaftikoCapability
  url: capabilities/vehicle-data.yaml
created: '2025-01-07'
description: The Vehicle API by Edmunds provides comprehensive access to automotive datasets covering vehicle makes, models, trims, specs, media, pricing (TMV), incentives, dealer information, and reviews. Enables developers to build automotive shopping tools, vehicle configurators, and consumer research applications.
features:
- description: Comprehensive database of vehicle makes, models, and trim levels with OEM specifications, features, and configuration options.
  name: Vehicle Make and Model Data
- description: Edmunds TMV pricing data including new vehicle suggested retail, invoice prices, and used vehicle values by condition and mileage.
  name: True Market Value Pricing
- description: Photo and video assets for vehicle makes, models, and trims including exterior, interior, color swatch, and 360-degree images.
  name: Vehicle Media
- description: Real-time dealer inventory search with make, model, year, zip code, radius, and price range filtering.
  name: Dealer Inventory
- description: Manufacturer incentives, rebates, financing offers, and lease programs by vehicle, region, and customer type.
  name: Incentives and Rebates
- description: Edmunds editorial reviews and consumer ratings for vehicle models including performance, comfort, value, and reliability scores.
  name: Vehicle Reviews and Ratings
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Cross-reference vehicle listings with AutoTrader inventory using Edmunds vehicle identifiers and specs for consistent data.
  name: AutoTrader
- description: Combine Edmunds vehicle data with Cars.com listings for enriched consumer shopping experiences.
  name: Cars.com
- description: Integrate vehicle specs and pricing into Salesforce, CDK, and Reynolds and Reynolds dealer management systems.
  name: Dealer CRM Systems
layout: provider
modified: '2026-05-03'
name: Vehicle API
rules:
- name: Vehicle API API Rules
  rule_count: 25
  severity_counts:
    error: 11
    hint: 0
    info: 4
    warn: 10
  slug: vehicle-api-spectral-rules
skills: []
slug: vehicle-api
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vehicle-api\nname: Vehicle API\ndescription: >-\n  The Vehicle API by Edmunds provides comprehensive access to automotive datasets\n  covering vehicle makes, models, trims, specs, media, pricing (TMV), incentives,\n  dealer information, and reviews. Enables developers to build automotive shopping\n  tools, vehicle configurators, and consumer research applications.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automotive\n  - Cars\n  - Edmunds\n  - Pricing\n  - Vehicles\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vehicle-api/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\ncreated: '2025-01-07'\nmodified: '2026-05-03'\napis:\n  - aid: vehicle-api:vehicle-api\n    name: Vehicle API (Edmunds)\n    description: >-\n      The Edmunds Vehicle API provides access to a comprehensive automotive data\n      platform including vehicle makes, models, trims, configurations,\
  \ specifications,\n      media (photos and videos), True Market Value (TMV) pricing, dealer inventories,\n      incentives, reviews, and consumer ratings. Ideal for building automotive\n      shopping tools, vehicle comparison engines, and dealer management systems.\n    humanURL: https://developer.edmunds.com/api-documentation/vehicle/\n    tags:\n      - Automotive\n      - Cars\n      - Edmunds\n      - Pricing\n      - Vehicles\n    properties:\n      - type: Documentation\n        url: https://developer.edmunds.com/api-documentation/vehicle/\n      - type: Portal\n        url: https://developer.edmunds.com/\n      - type: Reference\n        url: https://developer.edmunds.com/api-documentation/vehicle/\n      - type: Authentication\n        url: https://developer.edmunds.com/api-documentation/overview/\n      - type: OpenAPI\n        url: openapi/vehicle-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/vehicle-api-make-schema.json\n        title: Vehicle Make Schema\n\
  \      - type: JSONSchema\n        url: json-schema/vehicle-api-model-schema.json\n        title: Vehicle Model Schema\n      - type: JSONSchema\n        url: json-schema/vehicle-api-style-schema.json\n        title: Vehicle Style Schema\n      - type: JSONSchema\n        url: json-schema/vehicle-api-price-schema.json\n        title: Vehicle Price Schema\n      - type: JSONStructure\n        url: json-structure/vehicle-api-make-structure.json\n        title: Vehicle Make Structure\n      - type: JSONStructure\n        url: json-structure/vehicle-api-model-structure.json\n        title: Vehicle Model Structure\n      - type: Example\n        url: examples/vehicle-api-make-example.json\n        title: Vehicle Make Example\n      - type: Example\n        url: examples/vehicle-api-style-example.json\n        title: Vehicle Style Example\n\ncommon:\n  - type: Website\n    url: https://developer.edmunds.com/\n  - type: Portal\n    url: https://developer.edmunds.com/\n  - type: Documentation\n\
  \    url: https://developer.edmunds.com/api-documentation/vehicle/\n  - type: Authentication\n    url: https://developer.edmunds.com/api-documentation/overview/\n  - type: GettingStarted\n    url: https://developer.edmunds.com/api-documentation/overview/\n  - type: Support\n    url: https://developer.edmunds.com/support/\n  - type: SpectralRules\n    url: rules/vehicle-api-spectral-rules.yml\n    title: Vehicle API Spectral Rules\n  - type: Vocabulary\n    url: vocabulary/vehicle-api-vocabulary.yml\n    title: Vehicle API Vocabulary\n  - type: NaftikoCapability\n    url: capabilities/vehicle-data.yaml\n    title: Vehicle Data\n  - type: Features\n    data:\n      - name: Vehicle Make and Model Data\n        description: >-\n          Comprehensive database of vehicle makes, models, and trim levels with\n          OEM specifications, features, and configuration options.\n      - name: True Market Value Pricing\n        description: >-\n          Edmunds TMV pricing data including new vehicle\
  \ suggested retail, invoice\n          prices, and used vehicle values by condition and mileage.\n      - name: Vehicle Media\n        description: >-\n          Photo and video assets for vehicle makes, models, and trims including\n          exterior, interior, color swatch, and 360-degree images.\n      - name: Dealer Inventory\n        description: >-\n          Real-time dealer inventory search with make, model, year, zip code,\n          radius, and price range filtering.\n      - name: Incentives and Rebates\n        description: >-\n          Manufacturer incentives, rebates, financing offers, and lease programs\n          by vehicle, region, and customer type.\n      - name: Vehicle Reviews and Ratings\n        description: >-\n          Edmunds editorial reviews and consumer ratings for vehicle models\n          including performance, comfort, value, and reliability scores.\n  - type: UseCases\n    data:\n      - name: Automotive Shopping Tools\n        description: >-\n     \
  \     Build vehicle search and comparison tools that let consumers filter\n          by make, model, year, price, and features with TMV pricing guidance.\n      - name: Dealer Management Systems\n        description: >-\n          Power dealer websites and CRM systems with accurate vehicle specs,\n          pricing, and inventory data synced from Edmunds.\n      - name: Vehicle Configurator\n        description: >-\n          Enable consumers to build and price vehicles with available trims,\n          packages, options, and colors with live pricing calculations.\n      - name: Used Car Valuation\n        description: >-\n          Integrate used vehicle pricing into trade-in calculators, appraisal\n          tools, and consumer value estimators using TMV data.\n  - type: Integrations\n    data:\n      - name: AutoTrader\n        description: >-\n          Cross-reference vehicle listings with AutoTrader inventory using\n          Edmunds vehicle identifiers and specs for consistent data.\n\
  \      - name: Cars.com\n        description: >-\n          Combine Edmunds vehicle data with Cars.com listings for enriched\n          consumer shopping experiences.\n      - name: Dealer CRM Systems\n        description: >-\n          Integrate vehicle specs and pricing into Salesforce, CDK, and Reynolds\n          and Reynolds dealer management systems.\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vehicle-api/refs/heads/main/apis.yml
tags:
- Automotive
- Cars
- Edmunds
- Pricing
- Vehicles
url: https://raw.githubusercontent.com/api-evangelist/vehicle-api/refs/heads/main/apis.yml
use_cases:
- description: Build vehicle search and comparison tools that let consumers filter by make, model, year, price, and features with TMV pricing guidance.
  name: Automotive Shopping Tools
- description: Power dealer websites and CRM systems with accurate vehicle specs, pricing, and inventory data synced from Edmunds.
  name: Dealer Management Systems
- description: Enable consumers to build and price vehicles with available trims, packages, options, and colors with live pricing calculations.
  name: Vehicle Configurator
- description: Integrate used vehicle pricing into trade-in calculators, appraisal tools, and consumer value estimators using TMV data.
  name: Used Car Valuation
---
