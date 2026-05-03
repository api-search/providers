---
api_count: 4
api_specs:
- filename: tiaa-fdx-openapi.yml
  format: yaml
  label: TIAA Financial Data Exchange API
  slug: tiaa-fdx-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiaa/refs/heads/main/openapi/tiaa-fdx-openapi.yml
- filename: tiaa-sia-openapi.yml
  format: yaml
  label: TIAA Secure Income Account API
  slug: tiaa-sia-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiaa/refs/heads/main/openapi/tiaa-sia-openapi.yml
apis:
- description: The TIAA Financial Data Exchange (FDX) API provides customer account details to authorized fintechs and financial aggregators with customer consent. Built on the FDX open-standard (OAuth 2.0), it offe
  name: TIAA Financial Data Exchange API
  slug: tiaa-fdx-api
- description: The TIAA Secure Income Account (SIA) API enables recordkeepers and plan administrators to integrate TIAA's guaranteed lifetime income product into custom target-date model portfolios and managed accou
  name: TIAA Secure Income Account API
  slug: tiaa-sia-api
- description: The TIAA Gateway is a cloud-based API layer enabling product portability and interoperability across retirement ecosystem partners. It allows banking institutions, financial aggregators, and plan spon
  name: TIAA Gateway API
  slug: tiaa-gateway-api
- description: TIAA Payroll360 enables direct API connections between HR and payroll systems and TIAA's plan administration platform, automating deductions management, employer onboarding, and payroll data integrity
  name: TIAA Payroll360 API
  slug: tiaa-payroll360-api
capabilities:
- description: Unified capability for fintech developers, financial aggregators, and plan administration platforms to access TIAA retirement account data. Combines the FDX API for customer-consented data sharing and
  name: TIAA Retirement Data Access
  slug: retirement-data-access
common:
- title: ''
  type: Portal
  url: https://developer.tiaa.org
- title: ''
  type: Website
  url: https://www.tiaa.org
- title: ''
  type: Documentation
  url: https://developer.tiaa.org/public/fdx
- title: ''
  type: Blog
  url: https://www.tiaa.org/public/learn
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/tiaa
- title: ''
  type: Twitter
  url: https://twitter.com/tiaa
- title: ''
  type: Privacy Policy
  url: https://www.tiaa.org/public/pdf/t/privacy_notice.pdf
- title: ''
  type: Terms of Service
  url: https://www.tiaa.org/public/pdf/t/tiaa_website_terms_of_use.pdf
- title: ''
  type: JSON-LD
  url: json-ld/tiaa-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/tiaa-account-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tiaa-participant-schema.json
created: '2024'
description: TIAA (Teachers Insurance and Annuity Association of America) is a leading provider of financial services in the academic, research, medical, cultural, and government fields. Originally founded to provide retirement security for educators, TIAA now offers retirement services, insurance, brokerage, and investment management products to individuals and institutions. TIAA operates a developer portal at developer.tiaa.org exposing APIs for financial data aggregation (FDX standard), secure income account management, and gateway integrations enabling plan portability and fintech connectivity.
features: []
image: https://www.tiaa.org/content/dam/prod/tiaa/images/tiaa-logo.svg
integrations: []
jsonld:
- class_count: 16
  name: Tiaa Context
  property_count: 15
  slug: tiaa-context
layout: provider
modified: '2026-05-03'
name: TIAA
rules:
- name: TIAA API Rules
  rule_count: 13
  severity_counts:
    error: 5
    hint: 0
    info: 2
    warn: 6
  slug: tiaa-rules
skills: []
slug: tiaa
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tiaa\nurl: https://raw.githubusercontent.com/api-evangelist/tiaa/refs/heads/main/apis.yml\nname: TIAA\ndescription: >-\n  TIAA (Teachers Insurance and Annuity Association of America) is a leading\n  provider of financial services in the academic, research, medical, cultural,\n  and government fields. Originally founded to provide retirement security for\n  educators, TIAA now offers retirement services, insurance, brokerage, and\n  investment management products to individuals and institutions. TIAA operates\n  a developer portal at developer.tiaa.org exposing APIs for financial data\n  aggregation (FDX standard), secure income account management, and gateway\n  integrations enabling plan portability and fintech connectivity.\nimage: https://www.tiaa.org/content/dam/prod/tiaa/images/tiaa-logo.svg\ntags:\n  - Finance\n  - Financial Data\n  - Fintech\n  - Insurance\n  - Investment Management\n  - Retirement\n  - Wealth Management\ncreated: '2024'\nmodified: '2026-05-03'\n\
  specificationVersion: '0.19'\napis:\n  - aid: tiaa:tiaa-fdx-api\n    name: TIAA Financial Data Exchange API\n    description: >-\n      The TIAA Financial Data Exchange (FDX) API provides customer account\n      details to authorized fintechs and financial aggregators with customer\n      consent. Built on the FDX open-standard (OAuth 2.0), it offers a secure\n      alternative to screen scraping and enables third-party apps to retrieve\n      account balances, transactions, investment positions, and income data\n      from TIAA retirement and brokerage accounts.\n    image: https://www.tiaa.org/content/dam/prod/tiaa/images/tiaa-logo.svg\n    humanURL: https://developer.tiaa.org/public/fdx\n    baseURL: https://api.tiaa.org/fdx/v6\n    tags:\n      - Account Aggregation\n      - Financial Data\n      - FDX\n      - Open Finance\n      - Retirement\n    properties:\n      - type: Documentation\n        url: https://developer.tiaa.org/public/fdx\n      - type: Authentication\n        url:\
  \ https://developer.tiaa.org/public/fdx#authentication\n      - type: OpenAPI\n        url: openapi/tiaa-fdx-openapi.yml\n\n  - aid: tiaa:tiaa-sia-api\n    name: TIAA Secure Income Account API\n    description: >-\n      The TIAA Secure Income Account (SIA) API enables recordkeepers and plan\n      administrators to integrate TIAA's guaranteed lifetime income product into\n      custom target-date model portfolios and managed account solutions. Built\n      using the OpenAPI Specification (OAS) and authenticated via OAuth 2.0\n      Client Credentials Flow, the SIA API supports account setup, contribution\n      management, and participant income projections for defined contribution\n      plan participants.\n    image: https://www.tiaa.org/content/dam/prod/tiaa/images/tiaa-logo.svg\n    humanURL: https://developer.tiaa.org/public/sia\n    baseURL: https://api.tiaa.org/sia/v1\n    tags:\n      - Annuity\n      - Guaranteed Income\n      - Plan Administration\n      - Recordkeeping\n  \
  \    - Retirement\n      - Secure Income\n    properties:\n      - type: Documentation\n        url: https://developer.tiaa.org/public/sia\n      - type: Authentication\n        url: https://developer.tiaa.org/public/sia#authentication\n      - type: OpenAPI\n        url: openapi/tiaa-sia-openapi.yml\n\n  - aid: tiaa:tiaa-gateway-api\n    name: TIAA Gateway API\n    description: >-\n      The TIAA Gateway is a cloud-based API layer enabling product portability\n      and interoperability across retirement ecosystem partners. It allows\n      banking institutions, financial aggregators, and plan sponsor platforms\n      to expose TIAA retirement account data within their own apps and\n      experiences. The Gateway supports FDX, ACORD, and SPARK standards and\n      has more than 10 external partners connected.\n    image: https://www.tiaa.org/content/dam/prod/tiaa/images/tiaa-logo.svg\n    humanURL: https://www.tiaa.org/public/pdf/t/tiaa-gateway-drives-product-portability.pdf\n    baseURL:\
  \ https://api.tiaa.org/gateway/v1\n    tags:\n      - Financial Data\n      - Integration\n      - Open Finance\n      - Plan Portability\n      - Retirement\n    properties:\n      - type: Documentation\n        url: https://www.tiaa.org/public/pdf/t/tiaa-gateway-drives-product-portability.pdf\n      - type: Portal\n        url: https://developer.tiaa.org\n\n  - aid: tiaa:tiaa-payroll360-api\n    name: TIAA Payroll360 API\n    description: >-\n      TIAA Payroll360 enables direct API connections between HR and payroll\n      systems and TIAA's plan administration platform, automating deductions\n      management, employer onboarding, and payroll data integrity. Supports\n      SPARK 2.0 CR and TIAA-specific FLEX and OPS formats.\n    image: https://www.tiaa.org/content/dam/prod/tiaa/images/tiaa-logo.svg\n    humanURL: https://developer.tiaa.org/public/payroll360\n    baseURL: https://api.tiaa.org/payroll360/v1\n    tags:\n      - HR\n      - Payroll\n      - Plan Administration\n    \
  \  - Retirement\n      - SPARK\n    properties:\n      - type: Documentation\n        url: https://developer.tiaa.org/public/payroll360\n\ncommon:\n  - type: Portal\n    url: https://developer.tiaa.org\n  - type: Website\n    url: https://www.tiaa.org\n  - type: Documentation\n    url: https://developer.tiaa.org/public/fdx\n  - type: Blog\n    url: https://www.tiaa.org/public/learn\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/tiaa\n  - type: Twitter\n    url: https://twitter.com/tiaa\n  - type: Privacy Policy\n    url: https://www.tiaa.org/public/pdf/t/privacy_notice.pdf\n  - type: Terms of Service\n    url: https://www.tiaa.org/public/pdf/t/tiaa_website_terms_of_use.pdf\n  - type: JSON-LD\n    url: json-ld/tiaa-context.jsonld\n  - type: JSONSchema\n    url: json-schema/tiaa-account-schema.json\n  - type: JSONSchema\n    url: json-schema/tiaa-participant-schema.json\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tiaa/refs/heads/main/apis.yml
tags:
- Finance
- Financial Data
- Fintech
- Insurance
- Investment Management
- Retirement
- Wealth Management
url: https://raw.githubusercontent.com/api-evangelist/tiaa/refs/heads/main/apis.yml
use_cases: []
---
