---
api_count: 5
api_specs:
- filename: state-street-alpha-data-platform-openapi.yml
  format: yaml
  label: Alpha Data Platform API
  slug: alpha-data-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/state-street/refs/heads/main/openapi/state-street-alpha-data-platform-openapi.yml
- filename: state-street-fund-connect-openapi.yml
  format: yaml
  label: Fund Connect API
  slug: fund-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/state-street/refs/heads/main/openapi/state-street-fund-connect-openapi.yml
apis:
- description: The State Street Alpha Data Platform API provides institutional investment managers with programmatic access to the front-to-back Alpha investment management platform. Clients can retrieve portfolio h
  name: Alpha Data Platform API
  slug: alpha-data-platform-api
- description: 'The State Street Fund Connect API enables authorized participants (APs), fund managers, and custodians to programmatically manage ETF creation and redemption orders through the Fund Connect platform. '
  name: Fund Connect API
  slug: fund-connect-api
- description: 'The State Street Investment Accounting API provides institutional clients with access to portfolio accounting data including net asset value (NAV) calculations, position valuations, corporate actions '
  name: Investment Accounting API
  slug: investment-accounting-api
- description: The State Street Performance Analytics API (TrueView) provides institutional investors and asset managers with access to investment risk analytics, performance attribution, scenario analysis, and repo
  name: Performance Analytics API
  slug: performance-analytics-api
- description: The State Street Sample Transactions API is a reference and onboarding API provided in the developer portal to help new integration teams understand the authentication flow, request structure, and res
  name: Sample Transactions API
  slug: sample-transactions-api
capabilities:
- description: Workflow capability combining State Street Alpha Data Platform and Fund Connect APIs for institutional investment portfolio management. Enables portfolio managers, analysts, and risk officers to acces
  name: State Street Portfolio Management
  slug: portfolio-management
common:
- title: ''
  type: Website
  url: https://www.statestreet.com
- title: ''
  type: Developer Portal
  url: https://developer.statestreet.com
- title: ''
  type: API Catalog
  url: https://developer.statestreet.com/apis-list
- title: ''
  type: API Overview
  url: https://developer.statestreet.com/api-overview
- title: ''
  type: Documentation
  url: https://developer.statestreet.com/documentation-usage
- title: ''
  type: API Standards
  url: https://developer.statestreet.com/api-platform-standards
- title: ''
  type: Getting Started
  url: https://developer.statestreet.com/get-started-browser
- title: ''
  type: Support
  url: mailto:api-support@statestreet.com
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/state-street-corporation
- title: ''
  type: Twitter
  url: https://twitter.com/StateStreet
- title: ''
  type: Alpha Platform
  url: https://www.statestreet.com/alpha
- title: ''
  type: Privacy Policy
  url: https://www.statestreet.com/us/en/individual-investor/tools-and-resources/privacy-notice
- title: ''
  type: Terms of Service
  url: https://www.statestreet.com/us/en/individual-investor/tools-and-resources/terms-and-conditions
- title: ''
  type: OpenAPI
  url: openapi/state-street-alpha-data-platform-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/state-street-fund-connect-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/state-street-portfolio-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/state-street-position-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/state-street-portfolio-structure.json
- title: ''
  type: JSONLD
  url: json-ld/state-street-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/state-street-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/state-street-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/portfolio-management.yaml
created: ''
description: State Street Corporation is one of the world's largest financial services companies, headquartered in Boston, Massachusetts. Founded in 1792, State Street provides investment servicing, investment management, investment research, and trading services to institutional investors including mutual funds, collective investment funds, corporate and public retirement plans, insurance companies, foundations, and endowments. State Street manages approximately $4.7 trillion in assets under management through State Street Global Advisors and services nearly $40 trillion in assets under custody. The company operates the State Street Alpha front-to-back investment management platform, Fund Connect for ETF creation and redemption, and Charles River Development for investment management technology. State Street's developer portal at developer.statestreet.com provides OAuth 2.0-secured APIs enabling institutional clients to programmatically access portfolio data, transaction history, NAV calculations,
  analytics, and ETF order management. APIs follow REST conventions with OpenAPI 3.0 specifications, JSON data format, and JSON Schema documentation.
features: []
image: ''
integrations: []
jsonld:
- class_count: 15
  name: State Street Context
  property_count: 20
  slug: state-street-context
layout: provider
modified: '2026-05-02'
name: State Street
rules:
- name: State Street API Rules
  rule_count: 16
  severity_counts:
    error: 10
    hint: 0
    info: 0
    warn: 6
  slug: state-street-rules
skills: []
slug: state-street
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: state-street\nurl: https://raw.githubusercontent.com/api-evangelist/state-street/refs/heads/main/apis.yml\nmodified: '2026-05-02'\nname: State Street\ndescription: >-\n  State Street Corporation is one of the world's largest financial services companies,\n  headquartered in Boston, Massachusetts. Founded in 1792, State Street provides investment\n  servicing, investment management, investment research, and trading services to institutional\n  investors including mutual funds, collective investment funds, corporate and public retirement\n  plans, insurance companies, foundations, and endowments. State Street manages approximately\n  $4.7 trillion in assets under management through State Street Global Advisors and services\n  nearly $40 trillion in assets under custody. The company operates the State Street Alpha\n  front-to-back investment management platform, Fund Connect for ETF creation and redemption,\n  and Charles River Development for investment management technology.\
  \ State Street's developer\n  portal at developer.statestreet.com provides OAuth 2.0-secured APIs enabling institutional\n  clients to programmatically access portfolio data, transaction history, NAV calculations,\n  analytics, and ETF order management. APIs follow REST conventions with OpenAPI 3.0 specifications,\n  JSON data format, and JSON Schema documentation.\napis:\n  - aid: state-street:alpha-data-platform-api\n    name: Alpha Data Platform API\n    description: >-\n      The State Street Alpha Data Platform API provides institutional investment managers\n      with programmatic access to the front-to-back Alpha investment management platform.\n      Clients can retrieve portfolio holdings, positions, investable cash, pledged collateral,\n      securities on loan, risk exposures, performance measurement, and transaction history in\n      near real-time. Built on Snowflake and Microsoft Azure, the Alpha Data Platform enables\n      intraday visibility across geographies, asset classes,\
  \ and counterparties.\n      Authentication uses OAuth 2.0 Client Credentials.\n    humanURL: https://developer.statestreet.com/api-overview\n    baseURL: https://api.statestreet.com/v1\n    tags:\n      - Financial Services\n      - Investment Management\n      - Portfolio\n      - Data Platform\n      - Institutional\n    properties:\n      - type: Documentation\n        url: https://developer.statestreet.com/documentation-usage\n      - type: OpenAPI\n        url: openapi/state-street-alpha-data-platform-openapi.yml\n\n  - aid: state-street:fund-connect-api\n    name: Fund Connect API\n    description: >-\n      The State Street Fund Connect API enables authorized participants (APs), fund managers,\n      and custodians to programmatically manage ETF creation and redemption orders through\n      the Fund Connect platform. The API supports FIX protocol and XML for order submission,\n      and has executed the first API-based ETF order in Australian-domiciled ETFs (2025).\n      Fund\
  \ Connect is a global online portal processing ETF transactions across major markets.\n    humanURL: https://developer.statestreet.com/\n    baseURL: https://api.statestreet.com/v1/fund-connect\n    tags:\n      - Financial Services\n      - ETF\n      - Fund Management\n      - Order Management\n      - Institutional\n    properties:\n      - type: Documentation\n        url: https://developer.statestreet.com/\n      - type: OpenAPI\n        url: openapi/state-street-fund-connect-openapi.yml\n\n  - aid: state-street:investment-accounting-api\n    name: Investment Accounting API\n    description: >-\n      The State Street Investment Accounting API provides institutional clients with access\n      to portfolio accounting data including net asset value (NAV) calculations, position\n      valuations, corporate actions processing, performance measurement, and attribution\n      analysis. State Street services over 70 types of portfolios including mutual funds,\n      insurance portfolios,\
  \ alternatives, and pension funds.\n    humanURL: https://www.statestreet.com/us/en/solutions/investment-accounting\n    baseURL: https://api.statestreet.com/v1/accounting\n    tags:\n      - Financial Services\n      - Accounting\n      - NAV\n      - Performance\n      - Institutional\n    properties:\n      - type: Documentation\n        url: https://developer.statestreet.com/documentation-usage\n\n  - aid: state-street:performance-analytics-api\n    name: Performance Analytics API\n    description: >-\n      The State Street Performance Analytics API (TrueView) provides institutional investors\n      and asset managers with access to investment risk analytics, performance attribution,\n      scenario analysis, and reporting. Enables portfolio managers to access benchmark-relative\n      attribution, risk factor decomposition, and regulatory reporting data across all asset\n      classes including fixed income, equities, derivatives, and alternatives.\n    humanURL: https://www.statestreet.com/us/en/asset-owner/solutions/performance-and-analytics\n\
  \    baseURL: https://api.statestreet.com/v1/analytics\n    tags:\n      - Financial Services\n      - Analytics\n      - Performance\n      - Risk\n      - Institutional\n    properties:\n      - type: Documentation\n        url: https://developer.statestreet.com/documentation-usage\n\n  - aid: state-street:sample-transactions-api\n    name: Sample Transactions API\n    description: >-\n      The State Street Sample Transactions API is a reference and onboarding API provided\n      in the developer portal to help new integration teams understand the authentication\n      flow, request structure, and response format of State Street's API platform. Developers\n      use this API to perform an initial successful API call and retrieve a sample dataset\n      before progressing to production APIs.\n    humanURL: https://developer.statestreet.com/get-started-browser\n    baseURL: https://api.statestreet.com/v1\n    tags:\n      - Financial Services\n      - Developer\n      - Reference\n  \
  \    - Onboarding\n      - Sample\n    properties:\n      - type: Documentation\n        url: https://developer.statestreet.com/get-started-browser\n\ncommon:\n  - type: Website\n    url: https://www.statestreet.com\n  - type: Developer Portal\n    url: https://developer.statestreet.com\n  - type: API Catalog\n    url: https://developer.statestreet.com/apis-list\n  - type: API Overview\n    url: https://developer.statestreet.com/api-overview\n  - type: Documentation\n    url: https://developer.statestreet.com/documentation-usage\n  - type: API Standards\n    url: https://developer.statestreet.com/api-platform-standards\n  - type: Getting Started\n    url: https://developer.statestreet.com/get-started-browser\n  - type: Support\n    url: mailto:api-support@statestreet.com\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/state-street-corporation\n  - type: Twitter\n    url: https://twitter.com/StateStreet\n  - type: Alpha Platform\n    url: https://www.statestreet.com/alpha\n\
  \  - type: Privacy Policy\n    url: https://www.statestreet.com/us/en/individual-investor/tools-and-resources/privacy-notice\n  - type: Terms of Service\n    url: https://www.statestreet.com/us/en/individual-investor/tools-and-resources/terms-and-conditions\n  - type: OpenAPI\n    url: openapi/state-street-alpha-data-platform-openapi.yml\n  - type: OpenAPI\n    url: openapi/state-street-fund-connect-openapi.yml\n  - type: JSONSchema\n    url: json-schema/state-street-portfolio-schema.json\n  - type: JSONSchema\n    url: json-schema/state-street-position-schema.json\n  - type: JSONStructure\n    url: json-structure/state-street-portfolio-structure.json\n  - type: JSONLD\n    url: json-ld/state-street-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/state-street-vocabulary.yml\n  - type: SpectralRules\n    url: rules/state-street-rules.yml\n  - type: NaftikoCapabilities\n    url: capabilities/portfolio-management.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/state-street/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/state-street/refs/heads/main/apis.yml
use_cases: []
---
