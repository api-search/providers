---
api_count: 7
api_specs:
- filename: overview
  format: yaml
  label: SAP Convergent Charging API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/convergent_charging/overview
- filename: overview
  format: yaml
  label: SAP Convergent Invoicing API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/convergent_invoicing/overview
- filename: overview
  format: yaml
  label: SAP Subscription Billing API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/subscription_billing/overview
- filename: overview
  format: yaml
  label: SAP Contract Accounts Receivable and Payable API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/fica/overview
- filename: overview
  format: yaml
  label: SAP BRIM Usage Data Intake API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/usage_data_intake/overview
- filename: overview
  format: yaml
  label: SAP Revenue Accounting and Reporting API
  slug: ''
  spec_type: OpenAPI
  url: https://api.sap.com/api/revenue_accounting/overview
apis:
- description: API for real-time charging and rating of usage-based services. Supports complex pricing models, prepaid and postpaid scenarios.
  name: SAP Convergent Charging API
  slug: ''
- description: API for creating, managing, and processing invoices from multiple sources. Supports complex billing scenarios, invoice consolidation, and flexible output formats.
  name: SAP Convergent Invoicing API
  slug: ''
- description: API for managing subscription lifecycle, including creation, modification, renewal, and cancellation. Supports various billing frequencies and subscription models.
  name: SAP Subscription Billing API
  slug: ''
- description: API for managing customer accounts, payment processing, dunning, and dispute management. Core component for financial customer relationship management.
  name: SAP Contract Accounts Receivable and Payable API
  slug: ''
- description: API for ingesting high-volume usage data from various sources. Supports batch and real-time processing of usage events for rating and billing.
  name: SAP BRIM Usage Data Intake API
  slug: ''
- description: API for revenue recognition according to IFRS 15 and ASC 606 standards. Manages performance obligations, revenue allocation, and compliance reporting.
  name: SAP Revenue Accounting and Reporting API
  slug: ''
- description: API for managing subscription-based orders within the SAP BRIM suite, supporting complex offerings that combine physical products, services, and usage-based fees with full lifecycle management.
  name: SAP Subscription Order Management API
  slug: ''
capabilities:
- description: Workflow capability for end-to-end subscription management within the SAP BRIM suite. Covers subscriber onboarding, plan management, lifecycle transitions (activate, suspend, renew, cancel), and billi
  name: SAP BRIM Subscription Lifecycle Management
  slug: subscription-lifecycle-management
- description: Workflow capability for real-time usage rating, charging, and balance management in SAP BRIM Convergent Charging. Enables usage event submission, real-time rating against pricing plans, prepaid balanc
  name: SAP BRIM Usage-Based Charging
  slug: usage-based-charging
common:
- title: ''
  type: Portal
  url: https://api.sap.com
- title: ''
  type: OpenAPI
  url: openapi/sap-brim-convergent-charging-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/sap-brim-subscription-billing-openapi.yml
- title: ''
  type: JSON-LD
  url: json-ld/sap-brim-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/sap-brim-subscription-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/sap-brim-subscription-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/sap-brim-rating-request-structure.json
- title: ''
  type: SpectralRules
  url: rules/sap-brim-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/subscription-lifecycle-management.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/usage-based-charging.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/sap-brim-vocabulary.yml
- title: ''
  type: Getting Started
  url: https://help.sap.com/docs/SAP_BRIM/getting-started
- title: ''
  type: Authentication
  url: https://help.sap.com/docs/SAP_BRIM/authentication
- title: ''
  type: Support
  url: https://support.sap.com
- title: ''
  type: Terms of Service
  url: https://www.sap.com/about/legal/terms-of-use.html
- title: ''
  type: Privacy Policy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: Status Page
  url: https://www.sap.com/about/trust-center/cloud-service-status.html
- title: ''
  type: Community
  url: https://community.sap.com
- title: ''
  type: Blog
  url: https://blogs.sap.com
- title: ''
  type: Website
  url: https://www.sap.com/products/financial-management/billing-revenue-innovation-management.html
- title: ''
  type: Documentation
  url: https://help.sap.com/docs/BRIM
- title: ''
  type: SDKs
  url: https://developers.sap.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/SAP
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/sap
- title: ''
  type: Sign Up
  url: https://developers.sap.com/
- title: ''
  type: YouTube
  url: https://www.youtube.com/@sapdevs
- title: ''
  type: Learning
  url: https://learning.sap.com/
- title: ''
  type: Onboarding
  url: https://support.sap.com/en/product/onboarding-resource-center/brim.html
created: '2024-01-15'
description: SAP BRIM (Billing and Revenue Innovation Management) is a comprehensive solution for order-to-cash processes, subscription management, usage-based pricing, and revenue management. It enables businesses to manage complex billing scenarios, subscription lifecycle, and revenue recognition.
features: []
image: https://www.sap.com/dam/application/shared/logos/sap-logo-svg.svg
integrations: []
jsonld:
- class_count: 0
  name: Sap Brim Context
  property_count: 26
  slug: sap-brim-context
layout: provider
modified: '2026-05-02'
name: SAP BRIM (Billing and Revenue Innovation Management)
rules:
- name: SAP BRIM (Billing and Revenue Innovation Management) API Rules
  rule_count: 10
  severity_counts:
    error: 0
    hint: 0
    info: 2
    warn: 8
  slug: sap-brim-rules
skills: []
slug: sap-brim-billing-and-revenue-innovation-management
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SAP BRIM (Billing and Revenue Innovation Management)\ndescription: >-\n  SAP BRIM (Billing and Revenue Innovation Management) is a comprehensive solution\n  for order-to-cash processes, subscription management, usage-based pricing, and revenue\n  management. It enables businesses to manage complex billing scenarios, subscription\n  lifecycle, and revenue recognition.\nimage: https://www.sap.com/dam/application/shared/logos/sap-logo-svg.svg\nurl: https://www.sap.com/products/financial-management/billing-revenue-innovation-mgmt.html\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\ntags:\n  - Billing\n  - Enterprise\n  - Order to Cash\n  - Revenue Management\n  - SAP\n  - Subscription Management\n  - Usage-Based Pricing\napis:\n  - name: SAP Convergent Charging API\n    description: >-\n      API for real-time charging and rating of usage-based services. Supports complex\n      pricing models, prepaid and postpaid scenarios.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo-svg.svg\n\
  \    humanURL: https://help.sap.com/docs/SAP_CONVERGENT_CHARGING\n    baseURL: https://api.sap.com/convergent-charging\n    tags:\n      - Charging\n      - Rating\n      - Real-Time\n      - Usage-Based Pricing\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_CONVERGENT_CHARGING\n      - type: OpenAPI\n        url: https://api.sap.com/api/convergent_charging/overview\n      - type: OpenAPI\n        url: openapi/sap-brim-convergent-charging-openapi.yml\n      - type: Authentication\n        url: https://help.sap.com/docs/SAP_CONVERGENT_CHARGING/authentication\n    contact:\n      - FN: SAP Support\n        email: support@sap.com\n        url: https://support.sap.com\n  - name: SAP Convergent Invoicing API\n    description: >-\n      API for creating, managing, and processing invoices from multiple sources. Supports\n      complex billing scenarios, invoice consolidation, and flexible output formats.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo-svg.svg\n\
  \    humanURL: https://help.sap.com/docs/SAP_CONVERGENT_INVOICING\n    baseURL: https://api.sap.com/convergent-invoicing\n    tags:\n      - Billing\n      - Invoice Management\n      - Invoicing\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_CONVERGENT_INVOICING\n      - type: OpenAPI\n        url: https://api.sap.com/api/convergent_invoicing/overview\n      - type: Sandbox\n        url: https://api.sap.com/api/convergent_invoicing/tryout\n    contact:\n      - FN: SAP Support\n        email: support@sap.com\n        url: https://support.sap.com\n  - name: SAP Subscription Billing API\n    description: >-\n      API for managing subscription lifecycle, including creation, modification, renewal,\n      and cancellation. Supports various billing frequencies and subscription models.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/SAP_SUBSCRIPTION_BILLING\n    baseURL: https://api.sap.com/subscription-billing\n\
  \    tags:\n      - Lifecycle Management\n      - Recurring Billing\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_SUBSCRIPTION_BILLING\n      - type: OpenAPI\n        url: https://api.sap.com/api/subscription_billing/overview\n      - type: OpenAPI\n        url: openapi/sap-brim-subscription-billing-openapi.yml\n      - type: API Console\n        url: https://api.sap.com/api/subscription_billing/console\n      - type: Reference\n        url: https://api.sap.com/package/SAPHybrisRevenueCloud/rest\n      - type: Getting Started\n        url: https://help.sap.com/doc/13f339973aee49e4a59f153b3c8299d8/2025-12-15/en-US/SAP_Subscription_Billing_API_Guide.pdf\n      - type: JSONSchema\n        url: json-schema/sap-brim-subscription-schema.json\n    contact:\n      - FN: SAP Support\n        email: support@sap.com\n        url: https://support.sap.com\n  - name: SAP Contract Accounts Receivable and Payable API\n    description:\
  \ >-\n      API for managing customer accounts, payment processing, dunning, and dispute\n      management. Core component for financial customer relationship management.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/SAP_CONTRACT_ACCOUNTS_RECEIVABLE_PAYABLE\n    baseURL: https://api.sap.com/fica\n    tags:\n      - Accounts Receivable\n      - Dunning\n      - Financial Accounting\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_CONTRACT_ACCOUNTS_RECEIVABLE_PAYABLE\n      - type: OpenAPI\n        url: https://api.sap.com/api/fica/overview\n      - type: Integration Guide\n        url: https://help.sap.com/docs/SAP_FICA/integration\n    contact:\n      - FN: SAP Support\n        email: support@sap.com\n        url: https://support.sap.com\n  - name: SAP BRIM Usage Data Intake API\n    description: >-\n      API for ingesting high-volume usage data from various\
  \ sources. Supports batch\n      and real-time processing of usage events for rating and billing.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/SAP_BRIM_USAGE_DATA_INTAKE\n    baseURL: https://api.sap.com/usage-data-intake\n    tags:\n      - Data Ingestion\n      - Mediation\n      - Usage Data\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_BRIM_USAGE_DATA_INTAKE\n      - type: OpenAPI\n        url: https://api.sap.com/api/usage_data_intake/overview\n      - type: Technical Specifications\n        url: https://help.sap.com/docs/SAP_BRIM_USAGE_DATA_INTAKE/specs\n    contact:\n      - FN: SAP Support\n        email: support@sap.com\n        url: https://support.sap.com\n  - name: SAP Revenue Accounting and Reporting API\n    description: >-\n      API for revenue recognition according to IFRS 15 and ASC 606 standards. Manages\n      performance obligations, revenue allocation,\
  \ and compliance reporting.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/SAP_REVENUE_ACCOUNTING_REPORTING\n    baseURL: https://api.sap.com/revenue-accounting\n    tags:\n      - ASC 606\n      - Compliance\n      - IFRS 15\n      - Revenue Recognition\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/SAP_REVENUE_ACCOUNTING_REPORTING\n      - type: OpenAPI\n        url: https://api.sap.com/api/revenue_accounting/overview\n      - type: Compliance Guide\n        url: https://help.sap.com/docs/SAP_REVENUE_ACCOUNTING_REPORTING/compliance\n    contact:\n      - FN: SAP Support\n        email: support@sap.com\n        url: https://support.sap.com\n  - name: SAP Subscription Order Management API\n    description: >-\n      API for managing subscription-based orders within the SAP BRIM suite,\n      supporting complex offerings that combine physical products, services,\n      and usage-based\
  \ fees with full lifecycle management.\n    image: https://www.sap.com/dam/application/shared/logos/sap-logo-svg.svg\n    humanURL: https://help.sap.com/docs/BRIM\n    baseURL: https://api.sap.com/subscription-order-management\n    tags:\n      - Lifecycle Management\n      - Order Management\n      - Subscription Orders\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/docs/BRIM\n    contact:\n      - FN: SAP Support\n        email: support@sap.com\n        url: https://support.sap.com\ncommon:\n  - type: Portal\n    url: https://api.sap.com\n  - type: OpenAPI\n    url: openapi/sap-brim-convergent-charging-openapi.yml\n  - type: OpenAPI\n    url: openapi/sap-brim-subscription-billing-openapi.yml\n  - type: JSON-LD\n    url: json-ld/sap-brim-context.jsonld\n  - type: JSONSchema\n    url: json-schema/sap-brim-subscription-schema.json\n  - type: JSONStructure\n    url: json-structure/sap-brim-subscription-structure.json\n  - type: JSONStructure\n    url: json-structure/sap-brim-rating-request-structure.json\n\
  \  - type: SpectralRules\n    url: rules/sap-brim-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/subscription-lifecycle-management.yaml\n  - type: NaftikoCapability\n    url: capabilities/usage-based-charging.yaml\n  - type: Vocabulary\n    url: vocabulary/sap-brim-vocabulary.yml\n  - type: Getting Started\n    url: https://help.sap.com/docs/SAP_BRIM/getting-started\n  - type: Authentication\n    url: https://help.sap.com/docs/SAP_BRIM/authentication\n  - type: Support\n    url: https://support.sap.com\n  - type: Terms of Service\n    url: https://www.sap.com/about/legal/terms-of-use.html\n  - type: Privacy Policy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: Status Page\n    url: https://www.sap.com/about/trust-center/cloud-service-status.html\n  - type: Community\n    url: https://community.sap.com\n  - type: Blog\n    url: https://blogs.sap.com\n  - type: Website\n    url: https://www.sap.com/products/financial-management/billing-revenue-innovation-management.html\n\
  \  - type: Documentation\n    url: https://help.sap.com/docs/BRIM\n  - type: SDKs\n    url: https://developers.sap.com/\n  - type: GitHub Organization\n    url: https://github.com/SAP\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/sap\n  - type: Sign Up\n    url: https://developers.sap.com/\n  - type: YouTube\n    url: https://www.youtube.com/@sapdevs\n  - type: Learning\n    url: https://learning.sap.com/\n  - type: Onboarding\n    url: https://support.sap.com/en/product/onboarding-resource-center/brim.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sap-brim-billing-and-revenue-innovation-management/refs/heads/main/apis.yml
tags:
- Billing
- Enterprise
- Order to Cash
- Revenue Management
- SAP
- Subscription Management
- Usage-Based Pricing
url: https://www.sap.com/products/financial-management/billing-revenue-innovation-mgmt.html
use_cases: []
---
