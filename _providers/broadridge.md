---
api_count: 4
apis:
- description: The Broadridge Wealth Management API provides access to account activity, balances, positions, and transaction data for wealth management platforms. REST APIs enable broker-dealers and RIAs to integra
  name: Broadridge Wealth Management API
  slug: broadridge-wealth-api
- description: The Broadridge Galaxia Fund Data API enables access to and distribution of global fund data for regulatory reporting and investor communications. APIs provide fund data dissemination for UCITS, PRIIPS
  name: Broadridge Fund Data Distribution (Galaxia) API
  slug: broadridge-fund-data-api
- description: The Broadridge Investor Communications API provides access to proxy distribution, shareholder vote management, and corporate action communications. APIs support electronic proxy delivery, vote tabulat
  name: Broadridge Investor Communications API
  slug: broadridge-investor-communications-api
- description: The Broadridge Post-Trade Processing API provides access to trade settlement, reconciliation, and regulatory reporting functions. APIs and SFTP interfaces enable post-trade processing automation, fail
  name: Broadridge Post-Trade Processing API
  slug: broadridge-post-trade-api
common:
- title: ''
  type: Website
  url: https://www.broadridge.com
- title: ''
  type: Portal
  url: https://www.broadridge.com/client-access/
- title: ''
  type: Support
  url: https://www.broadridge.com/resource/developer-api-contact
- title: ''
  type: PrivacyPolicy
  url: https://www.broadridge.com/legal/privacy-statement-english
- title: ''
  type: TermsOfService
  url: https://www.broadridge.com/legal/terms-of-use
- title: ''
  type: Documentation
  url: https://github.com/wealthapiconnector/Broadridge-Wealth-API-Docs
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/openapi/broadridge-wealth-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/json-schema/broadridge-position-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/json-schema/broadridge-transaction-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/json-ld/broadridge-context.jsonld
created: ''
description: Best-in-class API components meet expert support to create the ideal wealth management operations environment. Optimize productivity, client experiences, and more.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Broadridge Context
  property_count: 4
  slug: broadridge-context
layout: provider
modified: '2026-04-21'
name: broadridge
skills: []
slug: broadridge
solutions: []
source_filename: apis.yml
source_yaml: "aid: broadridge\nurl: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/apis.yml\napis:\n  - aid: broadridge:broadridge-wealth-api\n    name: Broadridge Wealth Management API\n    tags:\n      - Account Data\n      - Financial Services\n      - Positions\n      - Transactions\n      - Wealth Management\n    image: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/image.png\n    humanURL: https://www.broadridge.com/capability/middle-and-back-office-solutions/wealth-operations/\n    baseURL: https://api.broadridge.example.com\n    properties:\n      - url: https://www.broadridge.com/capability/middle-and-back-office-solutions/wealth-operations/\n        type: Documentation\n      - url: https://github.com/wealthapiconnector/Broadridge-Wealth-API-Docs\n        type: Reference\n      - url: https://www.broadridge.com/resource/developer-api-contact\n        type: GettingStarted\n      - url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/openapi/broadridge-wealth-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The Broadridge Wealth Management API provides access to account activity, balances,\n      positions, and transaction data for wealth management platforms. REST APIs enable\n      broker-dealers and RIAs to integrate Broadridge back-office clearing and custody\n      data into front-office wealth management applications.\n\n  - aid: broadridge:broadridge-fund-data-api\n    name: Broadridge Fund Data Distribution (Galaxia) API\n    tags:\n      - Asset Management\n      - Financial Services\n      - Fund Data\n      - Regulatory Reporting\n      - UCITS\n    image: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/image.png\n    humanURL: https://www.broadridge.com/financial-services/asset-management/global-funds/simplify-financial-and-regulatory-reporting/fund-data-distribution-with-the-galaxia-data-api\n    baseURL: https://dataapi-web.fundslibrary.net\n    properties:\n      - url: https://www.broadridge.com/financial-services/asset-management/global-funds/simplify-financial-and-regulatory-reporting/fund-data-distribution-with-the-galaxia-data-api\n\
  \        type: Documentation\n      - url: https://dataapi-web.fundslibrary.net/\n        type: Reference\n    description: >-\n      The Broadridge Galaxia Fund Data API enables access to and distribution of global\n      fund data for regulatory reporting and investor communications. APIs provide\n      fund data dissemination for UCITS, PRIIPS, MiFID II, and other regulatory requirements\n      across asset managers and distributors.\n\n  - aid: broadridge:broadridge-investor-communications-api\n    name: Broadridge Investor Communications API\n    tags:\n      - Corporate Actions\n      - Financial Services\n      - Investor Communications\n      - Proxy\n      - Shareholder Services\n    image: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/image.png\n    humanURL: https://www.broadridge.com/\n    baseURL: https://api.broadridge.example.com\n    properties:\n      - url: https://www.broadridge.com/\n        type: Documentation\n      - url: https://www.broadridge.com/resource/developer-api-contact\n\
  \        type: Support\n    description: >-\n      The Broadridge Investor Communications API provides access to proxy distribution,\n      shareholder vote management, and corporate action communications. APIs support\n      electronic proxy delivery, vote tabulation, and regulatory compliance reporting\n      for issuers, broker-dealers, and transfer agents.\n\n  - aid: broadridge:broadridge-post-trade-api\n    name: Broadridge Post-Trade Processing API\n    tags:\n      - Financial Services\n      - Post-Trade\n      - Reconciliation\n      - Settlement\n      - SFTP\n    image: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/image.png\n    humanURL: https://www.broadridge.com/\n    baseURL: https://api.broadridge.example.com\n    properties:\n      - url: https://www.broadridge.com/\n        type: Documentation\n      - url: https://www.broadridge.com/resource/developer-api-contact\n        type: Support\n    description: >-\n      The Broadridge Post-Trade\
  \ Processing API provides access to trade settlement,\n      reconciliation, and regulatory reporting functions. APIs and SFTP interfaces\n      enable post-trade processing automation, fail management, and securities operations\n      for broker-dealers and asset managers.\n\ncommon:\n  - url: https://www.broadridge.com\n    type: Website\n  - url: https://www.broadridge.com/client-access/\n    type: Portal\n  - url: https://www.broadridge.com/resource/developer-api-contact\n    type: Support\n  - url: https://www.broadridge.com/legal/privacy-statement-english\n    type: PrivacyPolicy\n  - url: https://www.broadridge.com/legal/terms-of-use\n    type: TermsOfService\n  - url: https://github.com/wealthapiconnector/Broadridge-Wealth-API-Docs\n    type: Documentation\n  - url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/openapi/broadridge-wealth-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/json-schema/broadridge-position-schema.json\n\
  \    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/json-schema/broadridge-transaction-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/json-ld/broadridge-context.jsonld\n    type: JSONLDContext\n\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n\nmodified: '2026-04-21'\ndescription: >-\n  Best-in-class API components meet expert support to create the ideal wealth management\n  operations environment. Optimize productivity, client experiences, and more.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/broadridge/refs/heads/main/apis.yml
use_cases: []
---
