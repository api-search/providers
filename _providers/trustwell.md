---
api_count: 3
api_specs:
- filename: trustwell-foodlogiq-openapi.yml
  format: yaml
  label: Trustwell FoodLogiQ API
  slug: trustwell-foodlogiq-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/openapi/trustwell-foodlogiq-openapi.yml
apis:
- description: The Trustwell Genesis Foods GraphQL API provides programmatic access to food formulation, nutrition analysis, and label generation capabilities. The GraphQL endpoint at api.trustwell.com/genesis suppo
  name: Trustwell Genesis Foods GraphQL API
  slug: trustwell-genesis-foods-graphql-api
- description: The Trustwell FoodLogiQ API is an open REST API that enables enterprise food brands to integrate supply chain data with their existing systems. The API supports supplier relationship management, compl
  name: Trustwell FoodLogiQ API
  slug: trustwell-foodlogiq-api
- description: The Trustwell Genesis Supplements API provides formulation and regulatory compliance capabilities for dietary supplement manufacturers. Built on the same Genesis Foods GraphQL endpoint, it supports Su
  name: Trustwell Genesis Supplements API
  slug: trustwell-genesis-supplements-api
capabilities:
- description: Unified food safety management capability combining Genesis Foods nutrition analysis and FoodLogiQ supply chain operations. Used by food manufacturers, quality managers, and regulatory compliance team
  name: Trustwell Food Safety Management
  slug: food-safety-management
common:
- title: ''
  type: Website
  url: https://www.trustwell.com/
- title: ''
  type: Documentation
  url: https://docs.trustwell.com/
- title: ''
  type: Documentation
  url: https://docs.trustwell.com/genesis/api/
- title: ''
  type: Portal
  url: https://www.trustwell.com/platform/
- title: ''
  type: Products
  url: https://www.trustwell.com/products/
- title: ''
  type: Blog
  url: https://blog.trustwell.com/
- title: ''
  type: News
  url: https://www.trustwell.com/news-and-press/
- title: ''
  type: PrivacyPolicy
  url: https://www.trustwell.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://www.trustwell.com/terms-of-service/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/trustwell-llc
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/rules/trustwell-rules.yml
created: '2026-03-16'
description: 'Trustwell is a food industry software company formed from the merger of ESHA Research and FoodLogiQ in 2023, providing the food and beverage industry with an integrated platform covering product formulation, nutrition labeling, regulatory compliance, supply chain management, traceability, quality assurance, and recall management. The Trustwell Connect Platform offers two primary APIs: the Genesis Foods GraphQL API for nutrition analysis, food formulation, and label generation (with support for US, Canadian, EU, Mexican, and Australian regulatory standards), and the FoodLogiQ API for supply chain visibility, compliance management, supplier relationships, and FSMA 204-compliant traceability. Both APIs require X-API-KEY authentication. The platform serves food manufacturers, retailers, restaurants, and distributors across the global food supply chain.'
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 46
  name: Trustwell Context
  property_count: 6
  slug: trustwell-context
layout: provider
modified: '2026-05-03'
name: Trustwell
rules:
- name: Trustwell API Rules
  rule_count: 10
  severity_counts:
    error: 1
    hint: 0
    info: 3
    warn: 6
  slug: trustwell-rules
skills: []
slug: trustwell
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trustwell\nurl: https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/apis.yml\nname: Trustwell\ndescription: >-\n  Trustwell is a food industry software company formed from the merger of ESHA Research\n  and FoodLogiQ in 2023, providing the food and beverage industry with an integrated\n  platform covering product formulation, nutrition labeling, regulatory compliance,\n  supply chain management, traceability, quality assurance, and recall management.\n  The Trustwell Connect Platform offers two primary APIs: the Genesis Foods GraphQL API\n  for nutrition analysis, food formulation, and label generation (with support for\n  US, Canadian, EU, Mexican, and Australian regulatory standards), and the FoodLogiQ\n  API for supply chain visibility, compliance management, supplier relationships,\n  and FSMA 204-compliant traceability. Both APIs require X-API-KEY authentication.\n  The platform serves food manufacturers, retailers, restaurants, and distributors\n\
  \  across the global food supply chain.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Food Industry\n  - Food Safety\n  - Nutrition\n  - Supply Chain\n  - Food Labeling\n  - Traceability\n  - Compliance\n  - Food Technology\naccess: 3rd-Party\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trustwell:trustwell-genesis-foods-graphql-api\n    name: Trustwell Genesis Foods GraphQL API\n    tags:\n      - Food Formulation\n      - Nutrition Labeling\n      - Regulatory Compliance\n      - Food Industry\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustwell.com/genesis\n    humanURL: https://docs.trustwell.com/genesis/api/\n    properties:\n      - url: https://docs.trustwell.com/genesis/api/\n        type: Documentation\n      - url: https://www.trustwell.com/products/genesis/food-formulation-and-labeling/\n        type:\
  \ Documentation\n    description: >-\n      The Trustwell Genesis Foods GraphQL API provides programmatic access to food\n      formulation, nutrition analysis, and label generation capabilities. The GraphQL\n      endpoint at api.trustwell.com/genesis supports 16 query types (foods, labels,\n      nutrients, allergens, products, suppliers, regulations, documents, and more),\n      6 mutation categories (foods with 50+ sub-operations, label, documents, products,\n      suppliers, tags), and 2 subscription types (documentEvents, tenantEvents) for\n      real-time monitoring. The API supports 600+ schema types covering US, Canadian,\n      EU, Mexican, and Australian/New Zealand regulatory standards for nutrition labeling.\n      Authentication uses the X-API-KEY header. The API connects nutrition analysis data\n      to ERP, PLM, POS, and website systems.\n  - aid: trustwell:trustwell-foodlogiq-api\n    name: Trustwell FoodLogiQ API\n    tags:\n      - Food Safety\n      - Supply Chain\n\
  \      - Traceability\n      - Compliance\n      - Quality Management\n      - Recall Management\n      - Food Industry\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustwell.com/foodlogiq\n    humanURL: https://www.trustwell.com/products/foodlogiq/\n    properties:\n      - url: https://www.trustwell.com/products/foodlogiq/\n        type: Documentation\n      - url: https://www.trustwell.com/products/foodlogiq/product-management/\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/openapi/trustwell-foodlogiq-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Trustwell FoodLogiQ API is an open REST API that enables enterprise food\n      brands to integrate supply chain data with their existing systems. The API supports\n      supplier relationship management, compliance documentation, quality incident\n      management, product specification\
  \ management, FSMA 204-compliant traceability\n      (farm-to-fork tracking), and recall management workflows. The Q3 2025 release\n      introduced role-based API tokens with scoped permissions for fine-grained access\n      control. The API is documented within the FoodLogiQ Connect platform Resource\n      Center and supports integration with ERP, WMS, and third-party food safety systems.\n  - aid: trustwell:trustwell-genesis-supplements-api\n    name: Trustwell Genesis Supplements API\n    tags:\n      - Supplement Formulation\n      - Nutrition Labeling\n      - Regulatory Compliance\n      - Food Industry\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.trustwell.com/genesis\n    humanURL: https://www.trustwell.com/products/genesis/\n    properties:\n      - url: https://www.trustwell.com/products/genesis/\n        type: Documentation\n      - url: https://docs.trustwell.com/genesis/api/\n        type: Documentation\n\
  \    description: >-\n      The Trustwell Genesis Supplements API provides formulation and regulatory\n      compliance capabilities for dietary supplement manufacturers. Built on the same\n      Genesis Foods GraphQL endpoint, it supports Supplement Facts label generation,\n      ingredient declaration, allergen statements, and compliance with FDA dietary\n      supplement regulations. The API enables integration of supplement formulation\n      data into ERP and PLM systems.\ncommon:\n  - url: https://www.trustwell.com/\n    name: Trustwell Website\n    type: Website\n  - url: https://docs.trustwell.com/\n    name: Developer Documentation\n    type: Documentation\n  - url: https://docs.trustwell.com/genesis/api/\n    name: Genesis API Documentation\n    type: Documentation\n  - url: https://www.trustwell.com/platform/\n    name: Trustwell Connect Platform\n    type: Portal\n  - url: https://www.trustwell.com/products/\n    name: Products\n    type: Products\n  - url: https://blog.trustwell.com/\n\
  \    name: Trustwell Blog\n    type: Blog\n  - url: https://www.trustwell.com/news-and-press/\n    name: News and Press\n    type: News\n  - url: https://www.trustwell.com/privacy-policy/\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://www.trustwell.com/terms-of-service/\n    name: Terms of Service\n    type: TermsOfService\n  - url: https://www.linkedin.com/company/trustwell-llc\n    name: Trustwell on LinkedIn\n    type: LinkedIn\n  - url: https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/rules/trustwell-rules.yml\n    name: Spectral Rules\n    type: SpectralRules\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/apis.yml
tags:
- Food Industry
- Food Safety
- Nutrition
- Supply Chain
- Food Labeling
- Traceability
- Compliance
- Food Technology
url: https://raw.githubusercontent.com/api-evangelist/trustwell/refs/heads/main/apis.yml
use_cases: []
---
