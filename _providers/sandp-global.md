---
api_count: 3
api_specs:
- filename: sandp-global-capital-iq-openapi.yml
  format: yaml
  label: S&P Capital IQ API
  slug: sandp-global-capital-iq-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/openapi/sandp-global-capital-iq-openapi.yml
- filename: sandp-global-commodity-insights-openapi.yml
  format: yaml
  label: S&P Global Commodity Insights API
  slug: sandp-global-commodity-insights-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/openapi/sandp-global-commodity-insights-openapi.yml
apis:
- description: 'The S&P Capital IQ API provides programmatic access to one of the industry''s most comprehensive sets of global financial data, including fundamental financials, industry-specific data, valuations and '
  name: S&P Capital IQ API
  slug: sandp-global-capital-iq-api
- description: The S&P Global Commodity Insights API (formerly Platts API) provides HTTP-based RESTful access to commodity price assessments, market data, and analytics across energy, metals, agriculture, and petroc
  name: S&P Global Commodity Insights API
  slug: sandp-global-commodity-insights-api
- description: The S&P Global Marketplace Catalog API provides programmatic access to the S&P Global data marketplace, enabling discovery and consumption of available data products, datasets, and API solutions acros
  name: S&P Global Marketplace Catalog API
  slug: sandp-global-marketplace-catalog-api
capabilities:
- description: Unified capability combining S&P Capital IQ financial data and Commodity Insights price assessments for comprehensive market intelligence workflows. Used by financial analysts, portfolio managers, and
  name: S&P Global Market Intelligence
  slug: market-intelligence
common:
- title: ''
  type: Website
  url: https://www.spglobal.com
- title: ''
  type: Developer Portal
  url: https://developer.spglobal.com
- title: ''
  type: Marketplace
  url: https://www.marketplace.spglobal.com
- title: ''
  type: Documentation
  url: https://www.support.marketplace.spglobal.com
- title: ''
  type: Authentication
  url: https://developer.spglobal.com/getting-started/Auth.html
- title: ''
  type: Python SDK
  url: https://pypi.org/project/spgci/
- title: ''
  type: Python SDK
  url: https://pypi.org/project/SPGMICIQ/
- title: ''
  type: FAQ
  url: https://developer.spglobal.com/support/faq
- title: ''
  type: Support
  url: https://commodityinsightssupport.spglobal.com
- title: ''
  type: Vocabulary
  url: vocabulary/sandp-global-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/sandp-global-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/market-intelligence.yaml
- title: ''
  type: JSONLD
  url: json-ld/sandp-global-context.jsonld
created: '2026-05-02'
description: 'S&P Global is a leading provider of credit ratings, benchmarks, analytics, and workflow solutions in the global capital, commodity, and automotive markets. S&P Global offers multiple API product lines across its business divisions: the Capital IQ API provides comprehensive financial and market intelligence data; the Commodity Insights API provides price assessments, market data, and analytics for energy and commodities markets; and the Marketplace API enables programmatic access to the S&P Global data marketplace catalog.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Sandp Global Context
  property_count: 13
  slug: sandp-global-context
layout: provider
modified: '2026-05-02'
name: S&P Global
rules:
- name: S&P Global API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: sandp-global-rules
skills: []
slug: sandp-global
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sandp-global\nname: S&P Global\ndescription: >-\n  S&P Global is a leading provider of credit ratings, benchmarks, analytics,\n  and workflow solutions in the global capital, commodity, and automotive\n  markets. S&P Global offers multiple API product lines across its business\n  divisions: the Capital IQ API provides comprehensive financial and market\n  intelligence data; the Commodity Insights API provides price assessments,\n  market data, and analytics for energy and commodities markets; and the\n  Marketplace API enables programmatic access to the S&P Global data\n  marketplace catalog.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Financial Data\n  - Market Intelligence\n  - Commodity Insights\n  - Credit Ratings\n  - Analytics\n  - Fortune 500\n  - Enterprise\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nx-profiled: '2026-05'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: sandp-global:sandp-global-capital-iq-api\n    name: S&P Capital IQ API\n    description: >-\n      The S&P Capital IQ API provides programmatic access to one of the\n      industry's most comprehensive sets of global financial data, including\n      fundamental financials, industry-specific data, valuations and pricing,\n      S&P Global Credit Ratings and Research, capital structure data, and\n      reference data. The API uses REST with JSON responses and Bearer token\n      authentication. The primary endpoint is\n      https://api-ciq.marketintelligence.spglobal.com/gdsapi/rest/v3/clientservice.json.\n    humanURL: https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-826a-feb7f846c2be)\n    tags:\n      - Financial Data\n      - Fundamentals\n      - Credit Ratings\n      - Market Intelligence\n      - REST\n    properties:\n      - type: Documentation\n        url: https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-826a-feb7f846c2be)\n\
  \      - type: Developer Guide\n        url: https://www.support.marketplace.spglobal.com/content/dam/spglobal/mi/en/documents/marketplace/api/guides/spglobalapidevelopersguide.pdf\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/openapi/sandp-global-capital-iq-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sandp-global-financial-data-request-schema.json\n\n  - aid: sandp-global:sandp-global-commodity-insights-api\n    name: S&P Global Commodity Insights API\n    description: >-\n      The S&P Global Commodity Insights API (formerly Platts API) provides\n      HTTP-based RESTful access to commodity price assessments, market data,\n      and analytics across energy, metals, agriculture, and petrochemicals\n      markets. Authentication uses Bearer token generated via the Token\n      Generation API endpoint at https://developer.spglobal.com. The base\n      domain for API requests is https://api.platts.com.\n\
  \    humanURL: https://developer.spglobal.com/commodityinsights/\n    tags:\n      - Commodity Data\n      - Energy\n      - Metals\n      - Platts\n      - Price Assessments\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.spglobal.com/commodityinsights/api/getting-started\n      - type: Developer Portal\n        url: https://developer.spglobal.com\n      - type: Service Catalog\n        url: https://developer.spglobal.com/commodityinsights/servicecatalog\n      - type: Authentication\n        url: https://developer.spglobal.com/Token_Generation_API.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/openapi/sandp-global-commodity-insights-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sandp-global-price-assessment-schema.json\n\n  - aid: sandp-global:sandp-global-marketplace-catalog-api\n    name: S&P Global Marketplace Catalog API\n    description:\
  \ >-\n      The S&P Global Marketplace Catalog API provides programmatic access to\n      the S&P Global data marketplace, enabling discovery and consumption of\n      available data products, datasets, and API solutions across all S&P\n      Global business units.\n    humanURL: https://www.marketplace.spglobal.com/en/solutions/s-p-global-marketplace-catalog-api-(03f3c047-dcac-4fa7-a1ef-fb48a4d9b75d)\n    tags:\n      - Data Catalog\n      - Marketplace\n      - Discovery\n      - REST\n    properties:\n      - type: Documentation\n        url: https://www.marketplace.spglobal.com/en/solutions/s-p-global-marketplace-catalog-api-(03f3c047-dcac-4fa7-a1ef-fb48a4d9b75d)\n\ncommon:\n  - type: Website\n    url: https://www.spglobal.com\n  - type: Developer Portal\n    url: https://developer.spglobal.com\n  - type: Marketplace\n    url: https://www.marketplace.spglobal.com\n  - type: Documentation\n    url: https://www.support.marketplace.spglobal.com\n  - type: Authentication\n    url: https://developer.spglobal.com/getting-started/Auth.html\n\
  \  - type: Python SDK\n    url: https://pypi.org/project/spgci/\n  - type: Python SDK\n    url: https://pypi.org/project/SPGMICIQ/\n  - type: FAQ\n    url: https://developer.spglobal.com/support/faq\n  - type: Support\n    url: https://commodityinsightssupport.spglobal.com\n  - type: Vocabulary\n    url: vocabulary/sandp-global-vocabulary.yml\n  - type: SpectralRules\n    url: rules/sandp-global-rules.yml\n  - type: Capabilities\n    url: capabilities/market-intelligence.yaml\n  - type: JSONLD\n    url: json-ld/sandp-global-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/apis.yml
tags:
- Financial Data
- Market Intelligence
- Commodity Insights
- Credit Ratings
- Analytics
- Fortune 500
- Enterprise
url: https://raw.githubusercontent.com/api-evangelist/sandp-global/refs/heads/main/apis.yml
use_cases: []
---
