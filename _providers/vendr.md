---
api_count: 2
api_specs:
- filename: vendr-openapi.yml
  format: yaml
  label: Vendr OpenPrice API
  slug: vendr-openapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/openapi/vendr-openapi.yml
apis:
- description: The Vendr OpenPrice API provides access to real SaaS pricing intelligence derived from 200,000+ verified software contracts across 20,000+ products. It enables applications to retrieve structured cata
  name: Vendr OpenPrice API
  slug: vendr-openapi
- description: The Vendr Model Context Protocol (MCP) server exposes Vendr pricing intelligence to AI agents via the MCP standard. It provides tools for searching the product catalog, retrieving custom price estimat
  name: Vendr MCP Server
  slug: vendr-mcp
capabilities:
- description: Unified workflow capability for SaaS procurement intelligence, enabling procurement teams, finance analysts, and software buyers to research products, benchmark fair pricing from 200,000+ real contrac
  name: Vendr SaaS Procurement Intelligence
  slug: saas-procurement-intelligence
common:
- title: ''
  type: Website
  url: https://www.vendr.com/
- title: ''
  type: Documentation
  url: https://developers.vendr.com/docs/introduction
- title: ''
  type: PricingPage
  url: https://www.vendr.com/pricing-api
- title: ''
  type: GitHubOrganization
  url: https://github.com/vendrinc
- title: ''
  type: Support
  url: mailto:developers@vendr.com
- title: ''
  type: RateLimits
  url: https://developers.vendr.com/docs/introduction
- title: ''
  type: Authentication
  url: https://developers.vendr.com/docs/introduction
created: '2026-03-16'
description: Vendr is a SaaS procurement intelligence platform that helps businesses manage software spending through data-driven pricing insights and negotiation guidance. The Vendr API (OpenPrice API) provides access to real contract pricing data from 200,000+ verified software agreements across 20,000+ products, enabling developers to embed fair pricing estimates, negotiation insights, product catalog data, and purchase scope management into their applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 32
  name: Vendr Context
  property_count: 1
  slug: vendr-context
layout: provider
modified: '2026-05-03'
name: Vendr
rules:
- name: Vendr API Rules
  rule_count: 11
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 7
  slug: vendr-rules
skills: []
slug: vendr
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vendr\nname: Vendr\ndescription: >-\n  Vendr is a SaaS procurement intelligence platform that helps businesses manage\n  software spending through data-driven pricing insights and negotiation guidance.\n  The Vendr API (OpenPrice API) provides access to real contract pricing data from\n  200,000+ verified software agreements across 20,000+ products, enabling developers\n  to embed fair pricing estimates, negotiation insights, product catalog data, and\n  purchase scope management into their applications.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Pricing\n  - Procurement\n  - SaaS\n  - Software Spend Management\n  - Negotiation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: vendr:vendr-openapi\n    name: Vendr OpenPrice API\n    description:\
  \ >-\n      The Vendr OpenPrice API provides access to real SaaS pricing intelligence\n      derived from 200,000+ verified software contracts across 20,000+ products.\n      It enables applications to retrieve structured catalog data, generate fair\n      price estimates with confidence scoring, define purchase scope requirements,\n      and subscribe to webhook events. Authentication uses API key via the\n      X-API-Key header. Rate limits are 250 requests per minute and 150,000\n      requests per day.\n    humanURL: https://developers.vendr.com/docs/introduction\n    baseURL: https://api.vendr.com\n    tags:\n      - Pricing\n      - Procurement\n      - SaaS\n      - Catalog\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developers.vendr.com/docs/introduction\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/openapi/vendr-openapi.yml\n      - type: JSONSchema\n        url:\
  \ >-\n          https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/json-schema/vendr-pricing-response-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/json-schema/vendr-catalog-product-schema.json\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/rules/vendr-rules.yml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/vocabulary/vendr-vocabulary.yml\n    contact:\n      - FN: Vendr Developer Support\n        email: developers@vendr.com\n  - aid: vendr:vendr-mcp\n    name: Vendr MCP Server\n    description: >-\n      The Vendr Model Context Protocol (MCP) server exposes Vendr pricing\n      intelligence to AI agents via the MCP standard. It provides tools for\n      searching the product catalog, retrieving custom price estimates,\
  \ and\n      obtaining negotiation insights. Requires a Vendr API key.\n    humanURL: https://github.com/vendrinc/vendr-mcp\n    baseURL: https://api.vendr.com\n    tags:\n      - MCP\n      - AI Agents\n      - Pricing\n      - Procurement\n    properties:\n      - type: Documentation\n        url: https://github.com/vendrinc/vendr-mcp\n      - type: GitHubRepository\n        url: https://github.com/vendrinc/vendr-mcp\n\ncommon:\n  - type: Website\n    url: https://www.vendr.com/\n  - type: Documentation\n    url: https://developers.vendr.com/docs/introduction\n  - type: PricingPage\n    url: https://www.vendr.com/pricing-api\n  - type: GitHubOrganization\n    url: https://github.com/vendrinc\n  - type: Support\n    url: mailto:developers@vendr.com\n  - type: RateLimits\n    url: https://developers.vendr.com/docs/introduction\n  - type: Authentication\n    url: https://developers.vendr.com/docs/introduction\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/apis.yml
tags:
- Pricing
- Procurement
- SaaS
- Software Spend Management
- Negotiation
url: https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/apis.yml
use_cases: []
---
