---
api_count: 4
api_specs:
- filename: servicecatalog
  format: yaml
  label: S&P Global Commodity Insights API
  slug: commodity-insights
  spec_type: OpenAPI
  url: https://developer.spglobal.com/commodityinsights/servicecatalog
- filename: s-and-p-global-kensho-link-openapi.yml
  format: yaml
  label: Kensho Link API
  slug: kensho-link
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/openapi/s-and-p-global-kensho-link-openapi.yml
apis:
- description: HTTP-based RESTful API providing access to energy market data, commodity prices, assessments, and market intelligence across the Platts and S&P Global Commodity Insights business lines. Supports marke
  name: S&P Global Commodity Insights API
  slug: commodity-insights
- description: Comprehensive financial data API providing access to fundamental data, industry-specific and segment data, valuations and pricing, S&P Global Credit Ratings and Research, and reference and terms and c
  name: S&P Capital IQ Market Intelligence API
  slug: market-intelligence
- description: API providing programmatic access to the S&P Global Marketplace catalog of premium fundamental and alternative datasets. Enables discovery and integration of datasets available on the marketplace plat
  name: S&P Global Marketplace Catalog API
  slug: marketplace-catalog
- description: S&P Global Kensho Link REST API for entity resolution and linking across financial instruments, companies, and other entities. Provides a canonical entity identifier layer across S&P Global data asset
  name: Kensho Link API
  slug: kensho-link
capabilities:
- description: Commodity market data workflow combining real-time and historical price assessments, symbol discovery, and incremental data sync from S&P Global Commodity Insights (Platts). Used by energy traders, an
  name: S&P Global Commodity Market Data
  slug: commodity-market-data
- description: Unified financial data analytics workflow combining S&P Global Commodity Insights market data with Kensho entity resolution. Used by financial analysts, quant teams, energy traders, and data scientist
  name: S&P Global Financial Data Analytics
  slug: financial-data-analytics
common:
- title: ''
  type: Website
  url: https://www.spglobal.com
- title: ''
  type: Developer
  url: https://developer.spglobal.com/
- title: ''
  type: Marketplace
  url: https://www.marketplace.spglobal.com
- title: ''
  type: Documentation
  url: https://developer.spglobal.com/commodityinsights/api/getting-started
- title: ''
  type: Authentication
  url: https://developer.spglobal.com/commodityinsights/api/getting-started?tab=authentication
- title: ''
  type: Blog
  url: https://www.spglobal.com/en/research-insights/articles
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/spglobal/
- title: ''
  type: X
  url: https://twitter.com/SPGlobal
- title: ''
  type: Pricing
  url: https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-926a-feb7f846c2be)
- title: ''
  type: SDKs
  url: https://pypi.org/project/spgci/
created: '2026-03-21'
description: S&P Global is a leading provider of credit ratings, benchmarks, analytics, and workflow solutions in the global capital, commodity, and automotive markets. Through its divisions — S&P Global Market Intelligence, S&P Global Ratings, S&P Global Commodity Insights, S&P Global Mobility, and S&P Dow Jones Indices — the company delivers data, analytics, and decisioning capabilities to financial institutions, corporations, governments, and individuals worldwide. S&P Global APIs enable programmatic access to financial data, market prices, energy market data, credit ratings, and geospatial intelligence.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 2
  name: S And P Global Context
  property_count: 8
  slug: s-and-p-global-context
layout: provider
modified: '2026-05-02'
name: S&P Global
rules:
- name: S&P Global API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 7
  slug: s-and-p-global-spectral-rules
skills: []
slug: s-and-p-global
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: s-and-p-global\nname: S&P Global\ndescription: >-\n  S&P Global is a leading provider of credit ratings, benchmarks, analytics,\n  and workflow solutions in the global capital, commodity, and automotive\n  markets. Through its divisions — S&P Global Market Intelligence, S&P Global\n  Ratings, S&P Global Commodity Insights, S&P Global Mobility, and S&P Dow\n  Jones Indices — the company delivers data, analytics, and decisioning\n  capabilities to financial institutions, corporations, governments, and\n  individuals worldwide. S&P Global APIs enable programmatic access to\n  financial data, market prices, energy market data, credit ratings, and\n  geospatial intelligence.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/apis.yml\ntags:\n  - Financial Data\n  - Credit Ratings\n  - Market Intelligence\n  - Commodity Insights\n  - Energy Markets\n\
  \  - Capital Markets\n  - Fortune 500\ncreated: '2026-03-21'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: s-and-p-global:commodity-insights\n    name: S&P Global Commodity Insights API\n    description: >-\n      HTTP-based RESTful API providing access to energy market data, commodity\n      prices, assessments, and market intelligence across the Platts and S&P\n      Global Commodity Insights business lines. Supports market data, reference\n      data, and historical prices for oil, gas, petrochemicals, power,\n      shipping, and metals.\n    humanURL: https://developer.spglobal.com/commodityinsights/\n    baseURL: https://api.platts.com\n    tags:\n      - Commodity Insights\n      - Energy Markets\n      - Market Data\n      - Platts\n    properties:\n      - type: Documentation\n        url: https://developer.spglobal.com/commodityinsights/api/getting-started\n      - type: OpenAPI\n        url: https://developer.spglobal.com/commodityinsights/servicecatalog\n\
  \      - type: Authentication\n        url: https://developer.spglobal.com/commodityinsights/api/getting-started?tab=authentication\n      - type: SDKs\n        url: https://pypi.org/project/spgci/\n  - aid: s-and-p-global:market-intelligence\n    name: S&P Capital IQ Market Intelligence API\n    description: >-\n      Comprehensive financial data API providing access to fundamental data,\n      industry-specific and segment data, valuations and pricing, S&P Global\n      Credit Ratings and Research, and reference and terms and conditions data.\n      Uses Bearer token authentication with tokens valid for 60 minutes.\n    humanURL: https://developer.marketintelligence.spglobal.com/\n    baseURL: https://api-ciq.marketintelligence.spglobal.com\n    tags:\n      - Market Intelligence\n      - Capital IQ\n      - Financial Data\n      - Credit Ratings\n    properties:\n      - type: Documentation\n        url: https://developer.marketintelligence.spglobal.com/catalog-service/\n      - type:\
  \ Authentication\n        url: https://developer.marketintelligence.spglobal.com/catalog-service/\n  - aid: s-and-p-global:marketplace-catalog\n    name: S&P Global Marketplace Catalog API\n    description: >-\n      API providing programmatic access to the S&P Global Marketplace catalog\n      of premium fundamental and alternative datasets. Enables discovery and\n      integration of datasets available on the marketplace platform.\n    humanURL: https://www.marketplace.spglobal.com/en/solutions/s-p-global-marketplace-catalog-api-(03f3c047-dcac-4fa7-a1ef-fb48a4d9b75d)\n    baseURL: https://marketplace.spglobal.com\n    tags:\n      - Marketplace\n      - Catalog\n      - Datasets\n    properties:\n      - type: Documentation\n        url: https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-926a-feb7f846c2be)\n  - aid: s-and-p-global:kensho-link\n    name: Kensho Link API\n    description: >-\n      S&P Global Kensho Link REST API for entity resolution and\
  \ linking across\n      financial instruments, companies, and other entities. Provides a\n      canonical entity identifier layer across S&P Global data assets.\n    humanURL: https://api.link.kensho.com/docs/guides/rest-api/\n    baseURL: https://api.link.kensho.com\n    tags:\n      - Kensho\n      - Entity Resolution\n      - Data Linking\n    properties:\n      - type: Documentation\n        url: https://api.link.kensho.com/docs/guides/rest-api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/openapi/s-and-p-global-kensho-link-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.spglobal.com\n  - type: Developer\n    url: https://developer.spglobal.com/\n  - type: Marketplace\n    url: https://www.marketplace.spglobal.com\n  - type: Documentation\n    url: https://developer.spglobal.com/commodityinsights/api/getting-started\n  - type: Authentication\n    url: https://developer.spglobal.com/commodityinsights/api/getting-started?tab=authentication\n\
  \  - type: Blog\n    url: https://www.spglobal.com/en/research-insights/articles\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/spglobal/\n  - type: X\n    url: https://twitter.com/SPGlobal\n  - type: Pricing\n    url: https://www.marketplace.spglobal.com/en/solutions/api-solutions-(61953ac7-ea64-4fac-926a-feb7f846c2be)\n  - type: SDKs\n    url: https://pypi.org/project/spgci/\nfeatures:\n  - Credit Ratings\n  - Market Data\n  - Commodity Prices\n  - Financial Analytics\n  - Entity Resolution\n  - ESG Data\n  - Alternative Data\n  - Fixed Income Analytics\nsolutions:\n  - Financial Risk Management\n  - Investment Research\n  - Energy Trading\n  - Regulatory Compliance\n  - ESG Reporting\n  - Credit Analysis\nintegrations:\n  - Bloomberg\n  - FactSet\n  - Refinitiv\n  - Python SDK\n  - R SDK\n  - Excel Add-in\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/apis.yml
tags:
- Financial Data
- Credit Ratings
- Market Intelligence
- Commodity Insights
- Energy Markets
- Capital Markets
- Fortune 500
url: https://raw.githubusercontent.com/api-evangelist/s-and-p-global/refs/heads/main/apis.yml
use_cases: []
---
