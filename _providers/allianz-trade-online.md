---
api_count: 4
apis:
- description: 'Report payment overdues, request extension periods, and manage debt rescheduling for trade credit insurance policies. Supports three overdue category types: OVD (report default), EXP (extension period'
  name: Allianz Trade Payment Overdues API
  slug: payment-overdues-api
- description: Retrieve the creditworthiness grade of clients after a cover request. Supports bulk operations for grading multiple companies simultaneously, enabling automated credit risk assessment within ERP syste
  name: Allianz Trade Company Grade API
  slug: company-grade-api
- description: Access and manage all insurance claims declared to Allianz Trade from within your ERP system. Retrieve claim status, submit new claims, and track claim progression for trade credit insurance policies.
  name: Allianz Trade Claims API
  slug: claims-api
- description: Manage your trade credit insurance policy portfolio. Retrieve policy details, create joint insured policies, and manage policy configurations directly from your ERP or credit management system.
  name: Allianz Trade Policy API
  slug: policy-api
capabilities:
- description: ''
  name: Trade Credit Management
  slug: trade-credit-management
common:
- title: ''
  type: Website
  url: https://www.allianz-trade.com/
- title: ''
  type: Portal
  url: https://developers.allianz-trade.com/
- title: ''
  type: GettingStarted
  url: https://developers.allianz-trade.com/docs/getting-started
- title: ''
  type: Documentation
  url: https://developers.allianz-trade.com/docs/api-design-guidelines
- title: ''
  type: ChangeLog
  url: https://developers.allianz-trade.com/whatsnew
- title: ''
  type: Support
  url: mailto:api@allianz-trade.com
- title: ''
  type: SpectralRules
  url: rules/allianz-trade-online-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/allianz-trade-online-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/trade-credit-management.yaml
created: '2024-01-01'
description: 'Allianz Trade APIs enable businesses to automate trade credit insurance management including cover requests, credit limit monitoring, payment overdue reporting, claims management, and company credit grading. Built on secure REST architecture with OAuth2, the APIs support three business lines: Trade Credit Insurance, E-Commerce B2B, and Surety/Guarantee.'
features:
- description: Automate credit limit and cover information importing from Allianz Trade into ERP systems for real-time credit risk management.
  name: Credit Limit Management
- description: Retrieve creditworthiness grades for clients and prospects with bulk operations supporting large portfolio risk assessments.
  name: Company Credit Grading
- description: Report payment defaults, request extension periods, and manage debt rescheduling through standardized overdue category codes.
  name: Payment Overdue Reporting
- description: Integrate claims declaration and tracking directly into ERP systems for streamlined insurance claim management.
  name: Claims Management
- description: Manage trade credit insurance policy portfolios including joint insured policies and policy configuration from enterprise systems.
  name: Policy Portfolio Management
- description: Real-time credit evaluation on a per-transaction basis for B2B e-commerce platforms enabling buy-now-pay-later type scenarios.
  name: E-Commerce B2B Credit
- description: Secure OAuth2 authentication for all API endpoints with client credentials flow for machine-to-machine ERP integrations.
  name: OAuth2 Security
- description: Webhook-based notifications for technical events (job completion) and functional events (business decisions) with HTTPS and IP whitelisting.
  name: Webhook Notifications
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: ERP integration with SAP for automated trade credit management, policy data synchronization, and claims processing.
  name: SAP
- description: Oracle ERP integration for credit limit monitoring and automated policy data synchronization.
  name: Oracle
- description: OpenAPI collections downloadable from the developer portal for Postman, Insomnia, and HTTPie testing.
  name: Postman
- description: CRM integration for combining Allianz Trade risk data with customer relationship management workflows.
  name: Salesforce
jsonld:
- class_count: 0
  name: Allianz Trade Claims Context
  property_count: 22
  slug: allianz-trade-claims-context
- class_count: 0
  name: Allianz Trade Company Grade Context
  property_count: 21
  slug: allianz-trade-company-grade-context
- class_count: 0
  name: Allianz Trade Payment Overdues Context
  property_count: 19
  slug: allianz-trade-payment-overdues-context
- class_count: 0
  name: Allianz Trade Policy Context
  property_count: 23
  slug: allianz-trade-policy-context
layout: provider
modified: '2026-04-19'
name: Allianz Trade
rules:
- name: Allianz Trade API Rules
  rule_count: 22
  severity_counts:
    error: 5
    hint: 0
    info: 3
    warn: 14
  slug: allianz-trade-online-spectral-rules
skills: []
slug: allianz-trade-online
solutions: []
source_yaml: "aid: allianz-trade-online\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/apis.yml\nname: Allianz Trade\ntags:\n  - Credit Insurance\n  - Insurance\n  - Risk Management\n  - Trade Credit\n  - E-Commerce\n  - Surety\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Allianz Trade APIs enable businesses to automate trade credit insurance\n  management including cover requests, credit limit monitoring, payment overdue\n  reporting, claims management, and company credit grading. Built on secure\n  REST architecture with OAuth2, the APIs support three business lines: Trade\n  Credit Insurance, E-Commerce B2B, and Surety/Guarantee.\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: allianz-trade-online:payment-overdues-api\n    name: Allianz Trade Payment Overdues API\n    tags:\n      - Trade Credit\n      - Payment\n      -\
  \ Overdues\n      - Risk Management\n    properties:\n      - url: https://developers.allianz-trade.com/welcome-trade-credit-insurance-api-world/payment-overdues\n        type: Documentation\n      - url: https://developers.allianz-trade.com/\n        type: Portal\n      - url: openapi/allianz-trade-payment-overdues.yaml\n        type: OpenAPI\n      - url: json-schema/trade-payment-overdues-overdue-schema.json\n        type: JSONSchema\n      - url: json-structure/trade-payment-overdues-overdue-structure.json\n        type: JSONStructure\n      - url: json-ld/allianz-trade-payment-overdues-context.jsonld\n        type: JSONLD\n      - url: examples/trade-payment-overdues-overdue-example.json\n        type: Example\n      - url: examples/trade-payment-overdues-job_response-example.json\n        type: Example\n      - url: capabilities/shared/payment-overdues.yaml\n        type: NaftikoCapability\n    description: >-\n      Report payment overdues, request extension periods, and manage\
  \ debt\n      rescheduling for trade credit insurance policies. Supports three overdue\n      category types: OVD (report default), EXP (extension period), and RES\n      (rescheduling/repayment plan).\n    humanURL: https://developers.allianz-trade.com/welcome-trade-credit-insurance-api-world/payment-overdues\n    baseURL: https://api.allianz-trade.com/v1\n\n  - aid: allianz-trade-online:company-grade-api\n    name: Allianz Trade Company Grade API\n    tags:\n      - Credit Rating\n      - Risk Assessment\n      - Trade Credit\n    properties:\n      - url: https://developers.allianz-trade.com/api-catalogue\n        type: Documentation\n      - url: openapi/allianz-trade-company-grade.yaml\n        type: OpenAPI\n      - url: json-schema/trade-company-grade-company_grade-schema.json\n        type: JSONSchema\n      - url: json-structure/trade-company-grade-company_grade-structure.json\n        type: JSONStructure\n      - url: json-ld/allianz-trade-company-grade-context.jsonld\n     \
  \   type: JSONLD\n      - url: examples/trade-company-grade-company_grade-example.json\n        type: Example\n      - url: capabilities/shared/company-grade.yaml\n        type: NaftikoCapability\n    description: >-\n      Retrieve the creditworthiness grade of clients after a cover request.\n      Supports bulk operations for grading multiple companies simultaneously,\n      enabling automated credit risk assessment within ERP systems.\n    humanURL: https://developers.allianz-trade.com/api-catalogue\n    baseURL: https://api.allianz-trade.com/v1\n\n  - aid: allianz-trade-online:claims-api\n    name: Allianz Trade Claims API\n    tags:\n      - Claims\n      - Insurance\n      - Trade Credit\n    properties:\n      - url: https://developers.allianz-trade.com/api-catalogue\n        type: Documentation\n      - url: openapi/allianz-trade-claims.yaml\n        type: OpenAPI\n      - url: json-schema/trade-claims-claim-schema.json\n        type: JSONSchema\n      - url: json-structure/trade-claims-claim-structure.json\n\
  \        type: JSONStructure\n      - url: json-ld/allianz-trade-claims-context.jsonld\n        type: JSONLD\n      - url: examples/trade-claims-claim-example.json\n        type: Example\n      - url: capabilities/shared/claims.yaml\n        type: NaftikoCapability\n    description: >-\n      Access and manage all insurance claims declared to Allianz Trade from\n      within your ERP system. Retrieve claim status, submit new claims, and\n      track claim progression for trade credit insurance policies.\n    humanURL: https://developers.allianz-trade.com/api-catalogue\n    baseURL: https://api.allianz-trade.com/v1\n\n  - aid: allianz-trade-online:policy-api\n    name: Allianz Trade Policy API\n    tags:\n      - Policy Management\n      - Insurance\n      - Trade Credit\n    properties:\n      - url: https://developers.allianz-trade.com/api-catalogue\n        type: Documentation\n      - url: openapi/allianz-trade-policy.yaml\n        type: OpenAPI\n      - url: json-schema/trade-policy-policy-schema.json\n\
  \        type: JSONSchema\n      - url: json-structure/trade-policy-policy-structure.json\n        type: JSONStructure\n      - url: json-ld/allianz-trade-policy-context.jsonld\n        type: JSONLD\n      - url: examples/trade-policy-policy-example.json\n        type: Example\n      - url: capabilities/shared/policy.yaml\n        type: NaftikoCapability\n    description: >-\n      Manage your trade credit insurance policy portfolio. Retrieve policy\n      details, create joint insured policies, and manage policy configurations\n      directly from your ERP or credit management system.\n    humanURL: https://developers.allianz-trade.com/api-catalogue\n    baseURL: https://api.allianz-trade.com/v1\n\ncommon:\n  - url: https://www.allianz-trade.com/\n    type: Website\n  - url: https://developers.allianz-trade.com/\n    type: Portal\n  - url: https://developers.allianz-trade.com/docs/getting-started\n    type: GettingStarted\n  - url: https://developers.allianz-trade.com/docs/api-design-guidelines\n\
  \    type: Documentation\n  - url: https://developers.allianz-trade.com/whatsnew\n    type: ChangeLog\n  - url: mailto:api@allianz-trade.com\n    type: Support\n  - url: rules/allianz-trade-online-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/allianz-trade-online-vocabulary.yaml\n    type: Vocabulary\n  - url: capabilities/trade-credit-management.yaml\n    type: NaftikoCapability\n  - type: Features\n    data:\n      - name: Credit Limit Management\n        description: >-\n          Automate credit limit and cover information importing from Allianz Trade\n          into ERP systems for real-time credit risk management.\n      - name: Company Credit Grading\n        description: >-\n          Retrieve creditworthiness grades for clients and prospects with bulk\n          operations supporting large portfolio risk assessments.\n      - name: Payment Overdue Reporting\n        description: >-\n          Report payment defaults, request extension periods, and manage debt\n\
  \          rescheduling through standardized overdue category codes.\n      - name: Claims Management\n        description: >-\n          Integrate claims declaration and tracking directly into ERP systems\n          for streamlined insurance claim management.\n      - name: Policy Portfolio Management\n        description: >-\n          Manage trade credit insurance policy portfolios including joint insured\n          policies and policy configuration from enterprise systems.\n      - name: E-Commerce B2B Credit\n        description: >-\n          Real-time credit evaluation on a per-transaction basis for B2B\n          e-commerce platforms enabling buy-now-pay-later type scenarios.\n      - name: OAuth2 Security\n        description: >-\n          Secure OAuth2 authentication for all API endpoints with client\n          credentials flow for machine-to-machine ERP integrations.\n      - name: Webhook Notifications\n        description: >-\n          Webhook-based notifications for technical\
  \ events (job completion)\n          and functional events (business decisions) with HTTPS and IP whitelisting.\n  - type: UseCases\n    data:\n      - name: ERP Credit Management Integration\n        description: >-\n          Integrate Allianz Trade APIs into SAP, Oracle, or other ERP systems\n          to automate credit risk management and policy administration.\n      - name: Automated Credit Risk Dashboard\n        description: >-\n          Build custom credit management dashboards pulling live credit grades,\n          cover status, and claim data from Allianz Trade APIs.\n      - name: B2B E-Commerce Credit Evaluation\n        description: >-\n          Enable real-time per-transaction credit underwriting for B2B online\n          marketplaces and trade platforms using the E-Commerce APIs.\n      - name: Payment Monitoring and Overdue Automation\n        description: >-\n          Automate payment overdue reporting to Allianz Trade when customers\n          miss payment deadlines,\
  \ triggering insurance coverage workflows.\n  - type: Integrations\n    data:\n      - name: SAP\n        description: >-\n          ERP integration with SAP for automated trade credit management,\n          policy data synchronization, and claims processing.\n      - name: Oracle\n        description: >-\n          Oracle ERP integration for credit limit monitoring and automated\n          policy data synchronization.\n      - name: Postman\n        description: >-\n          OpenAPI collections downloadable from the developer portal for\n          Postman, Insomnia, and HTTPie testing.\n      - name: Salesforce\n        description: >-\n          CRM integration for combining Allianz Trade risk data with customer\n          relationship management workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/apis.yml
tags:
- Credit Insurance
- Insurance
- Risk Management
- Trade Credit
- E-Commerce
- Surety
url: https://raw.githubusercontent.com/api-evangelist/allianz-trade-online/refs/heads/main/apis.yml
use_cases:
- description: Integrate Allianz Trade APIs into SAP, Oracle, or other ERP systems to automate credit risk management and policy administration.
  name: ERP Credit Management Integration
- description: Build custom credit management dashboards pulling live credit grades, cover status, and claim data from Allianz Trade APIs.
  name: Automated Credit Risk Dashboard
- description: Enable real-time per-transaction credit underwriting for B2B online marketplaces and trade platforms using the E-Commerce APIs.
  name: B2B E-Commerce Credit Evaluation
- description: Automate payment overdue reporting to Allianz Trade when customers miss payment deadlines, triggering insurance coverage workflows.
  name: Payment Monitoring and Overdue Automation
---
