---
api_count: 5
api_specs:
- filename: datafiniti-api.yml
  format: yaml
  label: Datafiniti API
  slug: datafiniti-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datafiniti/refs/heads/main/openapi/datafiniti-api.yml
apis:
- description: Unified Datafiniti REST API exposing search and download endpoints for businesses, products, properties, and people datasets, plus the bearer token authentication endpoint.
  name: Datafiniti API
  slug: datafiniti-api
- description: Access a large catalog of business listings aggregated from hundreds of online directories and review websites, integrated with firmographics and reviews. Over 131 million business records available.
  name: Datafiniti Business Data API
  slug: business-data-api
- description: Access millions of product records spanning major retailers, brands, and categories including detailed product information, pricing data, and reviews. Over 506 million product records available.
  name: Datafiniti Product Data API
  slug: product-data-api
- description: Access a large catalog of real estate listings from dozens of websites, integrated with pricing data, amenities, and reviews. Over 205 million property records available.
  name: Datafiniti Property Data API
  slug: property-data-api
- description: Access people data records aggregated from public web sources. Over 4 million people records available.
  name: Datafiniti People Data API
  slug: people-data-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.datafiniti.co
- title: ''
  type: Documentation
  url: https://docs.datafiniti.co/docs/api-introduction
- title: ''
  type: Developer Portal
  url: https://developer.datafiniti.co
- title: ''
  type: Sign Up
  url: https://portal.datafiniti.co/sign-up
- title: ''
  type: Login
  url: https://portal.datafiniti.co
- title: ''
  type: Blog
  url: https://blog.datafiniti.co
- title: ''
  type: JSON-LD
  url: json-ld/datafiniti-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/datafiniti-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/datafiniti-capabilities.yml
- title: ''
  type: Rules
  url: rules/datafiniti-rules.yml
created: '2026-03-26'
description: Datafiniti is a Data as a Service (DaaS) provider that collects, organizes, and standardizes large-scale data from the public web, delivering ready-to-use datasets for property, people, business, and product data through their API, web portal, and bulk downloads.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Datafiniti Context
  property_count: 5
  slug: datafiniti-context
layout: provider
modified: '2026-04-28'
name: Datafiniti
rules:
- name: Datafiniti API Rules
  rule_count: 5
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 1
  slug: datafiniti-rules
skills: []
slug: datafiniti
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: datafiniti\nname: Datafiniti\ndescription: >-\n  Datafiniti is a Data as a Service (DaaS) provider that collects, organizes,\n  and standardizes large-scale data from the public web, delivering\n  ready-to-use datasets for property, people, business, and product data\n  through their API, web portal, and bulk downloads.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Business Data\n  - Data Aggregation\n  - Data as a Service\n  - People Data\n  - Product Data\n  - Property Data\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/datafiniti/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: company\nposition: Consumer\naccess: 3rd-Party\napis:\n  - aid: datafiniti:datafiniti-api\n    name: Datafiniti API\n    description: >-\n      Unified Datafiniti REST API exposing search and download endpoints for\n      businesses, products, properties, and\
  \ people datasets, plus the bearer\n      token authentication endpoint.\n    humanURL: https://docs.datafiniti.co/docs/api-introduction\n    baseURL: https://api.datafiniti.co/v4\n    tags:\n      - Authentication\n      - Bulk Downloads\n      - Search\n    properties:\n      - type: Documentation\n        url: https://docs.datafiniti.co/docs/api-introduction\n      - type: OpenAPI\n        url: openapi/datafiniti-api.yml\n      - type: JSONSchema\n        url: json-schema/search-request.json\n  - aid: datafiniti:business-data-api\n    name: Datafiniti Business Data API\n    description: >-\n      Access a large catalog of business listings aggregated from hundreds of\n      online directories and review websites, integrated with firmographics\n      and reviews. Over 131 million business records available.\n    humanURL: https://www.datafiniti.co/data/business-data\n    tags:\n      - Business Data\n      - Business Listings\n      - Firmographics\n    properties:\n      - type: Documentation\n\
  \        url: https://developer.datafiniti.co\n  - aid: datafiniti:product-data-api\n    name: Datafiniti Product Data API\n    description: >-\n      Access millions of product records spanning major retailers, brands,\n      and categories including detailed product information, pricing data,\n      and reviews. Over 506 million product records available.\n    humanURL: https://www.datafiniti.co/data/product-data\n    tags:\n      - E-Commerce\n      - Pricing Data\n      - Product Data\n    properties:\n      - type: Documentation\n        url: https://developer.datafiniti.co/docs/getting-started-with-product-data\n  - aid: datafiniti:property-data-api\n    name: Datafiniti Property Data API\n    description: >-\n      Access a large catalog of real estate listings from dozens of websites,\n      integrated with pricing data, amenities, and reviews. Over 205 million\n      property records available.\n    humanURL: https://www.datafiniti.co/data/property-data\n    tags:\n      - Listings\n\
  \      - Property Data\n      - Real Estate\n    properties:\n      - type: Documentation\n        url: https://docs.datafiniti.co/docs/constructing-property-queries\n  - aid: datafiniti:people-data-api\n    name: Datafiniti People Data API\n    description: >-\n      Access people data records aggregated from public web sources. Over\n      4 million people records available.\n    humanURL: https://www.datafiniti.co/data/people-data\n    tags:\n      - Contact Data\n      - People Data\n    properties:\n      - type: Documentation\n        url: https://developer.datafiniti.co\ncommon:\n  - type: Website\n    url: https://www.datafiniti.co\n  - type: Documentation\n    url: https://docs.datafiniti.co/docs/api-introduction\n  - type: Developer Portal\n    url: https://developer.datafiniti.co\n  - type: Sign Up\n    url: https://portal.datafiniti.co/sign-up\n  - type: Login\n    url: https://portal.datafiniti.co\n  - type: Blog\n    url: https://blog.datafiniti.co\n  - type: JSON-LD\n  \
  \  url: json-ld/datafiniti-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/datafiniti-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/datafiniti-capabilities.yml\n  - type: Rules\n    url: rules/datafiniti-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/datafiniti/refs/heads/main/apis.yml
tags:
- Business Data
- Data Aggregation
- Data as a Service
- People Data
- Product Data
- Property Data
url: https://raw.githubusercontent.com/api-evangelist/datafiniti/refs/heads/main/apis.yml
use_cases: []
---
