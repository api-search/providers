---
api_count: 1
apis:
- description: The ADM Commodity Data API represents data integration capabilities for agricultural commodity pricing, supply chain logistics, and product information for partner integrations.
  name: Archer Daniels Midland Commodity Data API
  slug: commodity-data-api
common:
- title: ''
  type: Portal
  url: https://www.adm.com/en-us/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/archer-daniels-midland/refs/heads/main/rules/archer-daniels-midland-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/archer-daniels-midland/refs/heads/main/vocabulary/archer-daniels-midland-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/archer-daniels-midland/refs/heads/main/json-ld/archer-daniels-midland-commodity-data-api-context.jsonld
created: '2026-03-23'
description: Archer Daniels Midland (ADM) is a Fortune 100 global leader in agricultural processing and food ingredient manufacturing, providing nutrition solutions for food, beverage, health, and industrial markets worldwide.
features:
- description: Agricultural commodity pricing, market trends, and availability data for corn, soybeans, wheat, and other grains.
  name: Commodity Data
- description: API integrations for supply chain visibility, logistics, and sourcing of agricultural raw materials.
  name: Supply Chain Integration
- description: ADM processed food ingredients and agricultural product specifications, nutritional data, and documentation.
  name: Product Catalog
- description: Global network of processing facilities, grain elevators, and distribution centers.
  name: Facility Locations
- description: B2B API integrations for key customers and supply chain partners.
  name: Partner Integration
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with SAP ERP for procurement, supply chain, and financial management.
  name: SAP
- description: Oracle ERP integration for commodity trading and logistics management.
  name: Oracle
- description: Integration with commodity futures and options data from CME Group.
  name: CME Group
- description: Commodity market data integration with Bloomberg terminal services.
  name: Bloomberg
jsonld:
- class_count: 7
  name: Archer Daniels Midland Commodity Data Api Context
  property_count: 22
  slug: archer-daniels-midland-commodity-data-api-context
layout: provider
modified: '2026-04-19'
name: Archer Daniels Midland
rules:
- name: Archer Daniels Midland API Rules
  rule_count: 13
  severity_counts:
    error: 10
    hint: 0
    info: 0
    warn: 3
  slug: archer-daniels-midland-spectral-rules
skills: []
slug: archer-daniels-midland
solutions: []
source_yaml: "aid: archer-daniels-midland\nname: Archer Daniels Midland\ndescription: Archer Daniels Midland (ADM) is a Fortune 100 global leader in agricultural processing and food ingredient manufacturing, providing nutrition solutions for food, beverage, health, and \n  industrial markets worldwide.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Agriculture\n- Food Processing\n- Commodities\n- Supply Chain\n- Fortune 100\n- Nutrition\nurl: https://raw.githubusercontent.com/api-evangelist/archer-daniels-midland/refs/heads/main/apis.yml\ncreated: '2026-03-23'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: archer-daniels-midland:commodity-data-api\n  name: Archer Daniels Midland Commodity Data API\n  description: The ADM Commodity Data API represents data integration capabilities for agricultural commodity pricing, supply chain logistics, and product information for partner integrations.\n  humanURL: https://www.adm.com/en-us/\n\
  \  baseURL: https://api.adm.com\n  tags:\n  - Agriculture\n  - Commodities\n  - Food Processing\n  - Supply Chain\n  - Grain\n  - Nutrition\n  properties:\n  - type: Documentation\n    url: https://www.adm.com/en-us/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/archer-daniels-midland/refs/heads/main/openapi/archer-daniels-midland-commodity-data-api-openapi.yml\ncommon:\n- type: Portal\n  url: https://www.adm.com/en-us/\n- type: Features\n  data:\n  - name: Commodity Data\n    description: Agricultural commodity pricing, market trends, and availability data for corn, soybeans, wheat, and other grains.\n  - name: Supply Chain Integration\n    description: API integrations for supply chain visibility, logistics, and sourcing of agricultural raw materials.\n  - name: Product Catalog\n    description: ADM processed food ingredients and agricultural product specifications, nutritional data, and documentation.\n  - name: Facility Locations\n    description: Global\
  \ network of processing facilities, grain elevators, and distribution centers.\n  - name: Partner Integration\n    description: B2B API integrations for key customers and supply chain partners.\n- type: UseCases\n  data:\n  - name: Commodity Procurement\n    description: Automate commodity price tracking and procurement workflows for food manufacturers.\n  - name: Supply Chain Visibility\n    description: Integrate ADM supply chain data with enterprise ERP and logistics systems.\n  - name: Food Ingredient Sourcing\n    description: Search and source ADM processed food ingredients for product development.\n  - name: Risk Management\n    description: Access commodity pricing and market trend data for agricultural commodity risk management.\n- type: Integrations\n  data:\n  - name: SAP\n    description: Integration with SAP ERP for procurement, supply chain, and financial management.\n  - name: Oracle\n    description: Oracle ERP integration for commodity trading and logistics management.\n\
  \  - name: CME Group\n    description: Integration with commodity futures and options data from CME Group.\n  - name: Bloomberg\n    description: Commodity market data integration with Bloomberg terminal services.\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/archer-daniels-midland/refs/heads/main/rules/archer-daniels-midland-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/archer-daniels-midland/refs/heads/main/vocabulary/archer-daniels-midland-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/archer-daniels-midland/refs/heads/main/json-ld/archer-daniels-midland-commodity-data-api-context.jsonld\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/archer-daniels-midland/refs/heads/main/apis.yml
tags:
- Agriculture
- Food Processing
- Commodities
- Supply Chain
- Fortune 100
- Nutrition
url: https://raw.githubusercontent.com/api-evangelist/archer-daniels-midland/refs/heads/main/apis.yml
use_cases:
- description: Automate commodity price tracking and procurement workflows for food manufacturers.
  name: Commodity Procurement
- description: Integrate ADM supply chain data with enterprise ERP and logistics systems.
  name: Supply Chain Visibility
- description: Search and source ADM processed food ingredients for product development.
  name: Food Ingredient Sourcing
- description: Access commodity pricing and market trend data for agricultural commodity risk management.
  name: Risk Management
---
