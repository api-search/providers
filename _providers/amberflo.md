---
api_count: 4
apis:
- description: The Amberflo Metering API provides meter definition management, high-throughput event ingestion, usage queries, raw event queries, and filtering rules. It supports real-time metering for API calls, to
  name: Amberflo Metering API
  slug: metering-api
- description: The Amberflo Billing API manages customers, pricing plans, invoices, prepaid orders, promotions, commitments, and billing analysis. It supports usage-based monetization workflows including revenue rec
  name: Amberflo Billing API
  slug: billing-api
- description: The Amberflo Cost Tracking API provides AI and cloud cost management capabilities including cloud provider integrations, business unit management, cost allocation rules, budget management, and cost qu
  name: Amberflo Cost Tracking API
  slug: cost-tracking-api
- description: The Amberflo AI Gateway provides a unified API for routing requests to 1,500+ LLM models with intelligent model routing, cost optimization, built-in fallbacks, and MCP server traffic monitoring. It tr
  name: Amberflo AI Gateway API
  slug: ai-gateway-api
capabilities:
- description: Unified workflow for API monetization teams combining metering and billing APIs. Enables end-to-end usage tracking, customer management, and billing automation for product and finance teams.
  name: Amberflo Usage-Based Monetization
  slug: usage-based-monetization
common:
- title: ''
  type: Website
  url: https://www.amberflo.io/
- title: ''
  type: Documentation
  url: https://docs.amberflo.io/
- title: ''
  type: DeveloperPortal
  url: https://docs.amberflo.io/
- title: ''
  type: GettingStarted
  url: https://docs.amberflo.io/docs/quick-start
- title: ''
  type: APIReference
  url: https://docs.amberflo.io/reference/
- title: ''
  type: SignUp
  url: https://ui.amberflo.io/cGxnLXNpZ251cA==
- title: ''
  type: Login
  url: https://ui.amberflo.io/login
- title: ''
  type: Pricing
  url: https://www.amberflo.io/pricing
- title: ''
  type: Blog
  url: https://www.amberflo.io/resources/blog
- title: ''
  type: TermsOfService
  url: https://www.amberflo.io/legal/terms-and-condition
- title: ''
  type: PrivacyPolicy
  url: https://www.amberflo.io/legal/privacy-policy
- title: ''
  type: Compliance
  url: https://trust.amberflo.io/
- title: ''
  type: TrustCenter
  url: https://trust.amberflo.io/
- title: ''
  type: GitHubOrganization
  url: https://github.com/amberflo
- title: Python SDK
  type: SDK
  url: https://pypi.org/project/amberflo-metering-python/
- title: TypeScript SDK
  type: SDK
  url: https://github.com/amberflo/metering-typescript
- title: Go SDK
  type: SDK
  url: https://github.com/amberflo/metering-go
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/rules/amberflo-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/capabilities/usage-based-monetization.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/vocabulary/amberflo-vocabulary.yaml
created: '2026-03-27'
description: Amberflo is a cloud metering, usage-based billing, and AI cost management platform. It provides real-time event ingestion, customer billing automation, AI gateway capabilities, and FinOps visibility for API-driven and AI-powered businesses. The platform supports usage-based, token-based, seat-based, and outcome-based pricing models with automated invoicing and embeddable billing dashboards.
features:
- description: Ingest millions to billions of high-cardinality usage events in real time with idempotency, deduplication, and automatic aggregation.
  name: Real-Time Event Ingestion
- description: Unified LLM access and control across 1,500+ models with per-unit costs, rollups, budgets, Cost Guards, and margin analysis per customer.
  name: AI Cost Management
- description: Single API for multiple LLM providers with intelligent cost optimization, automatic retries, fallbacks, and MCP server traffic monitoring.
  name: AI Gateway and Model Routing
- description: Flexible billing models including usage-based, token-based, seat-based, fixed fee, and outcome-based pricing with multi-currency support and automated invoicing.
  name: Usage-Based Billing
- description: Customer-facing billing portals and dashboards via a React.js UI Kit with custom domain support and SSO integration.
  name: Embeddable Billing Dashboards
- description: Revenue recognition automation, RevRec ledger tracking, tax management, and integrations with Stripe and NetSuite.
  name: Revenue Operations
- description: Spending limits, threshold alerts, Cost Guards, and automated notifications for cloud and AI cost governance.
  name: Budget Management
- description: Chargeback rates, quotes, and invoices for internal cost allocation and showback reporting across business units.
  name: Chargeback and Showback
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with Stripe for payment processing and revenue operations workflows.
  name: Stripe
- description: Integration with NetSuite for revenue recognition and financial reporting.
  name: NetSuite
- description: Official Kong plugin for metering API requests handled by Kong instances and monetizing APIs.
  name: Kong
- description: Integration with AWS SaaS Builder Toolkit for SaaS billing and metering best practices on AWS.
  name: AWS SaaS Builder Toolkit
- description: Logging callback for LiteLLM to meter LLM usage and monitor AI costs.
  name: LiteLLM
- description: Examples and utilities for metering AWS Lambda function invocations.
  name: AWS Lambda
jsonld:
- class_count: 1
  name: Amberflo Billing Address Context
  property_count: 6
  slug: amberflo-billing-address-context
- class_count: 5
  name: Amberflo Billing Customer Context
  property_count: 10
  slug: amberflo-billing-customer-context
- class_count: 1
  name: Amberflo Billing Invoice Context
  property_count: 7
  slug: amberflo-billing-invoice-context
- class_count: 3
  name: Amberflo Billing Prepaid Context
  property_count: 5
  slug: amberflo-billing-prepaid-context
- class_count: 1
  name: Amberflo Billing Pricing Context
  property_count: 3
  slug: amberflo-billing-pricing-context
- class_count: 1
  name: Amberflo Metering Filtering Context
  property_count: 5
  slug: amberflo-metering-filtering-context
- class_count: 3
  name: Amberflo Metering Meter Context
  property_count: 10
  slug: amberflo-metering-meter-context
- class_count: 3
  name: Amberflo Metering Usage Context
  property_count: 11
  slug: amberflo-metering-usage-context
layout: provider
modified: '2026-04-19'
name: Amberflo
skills: []
slug: amberflo
solutions: []
source_yaml: "aid: amberflo\nname: Amberflo\ndescription: >-\n  Amberflo is a cloud metering, usage-based billing, and AI cost management\n  platform. It provides real-time event ingestion, customer billing\n  automation, AI gateway capabilities, and FinOps visibility for API-driven\n  and AI-powered businesses. The platform supports usage-based, token-based,\n  seat-based, and outcome-based pricing models with automated invoicing and\n  embeddable billing dashboards.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Usage-Based Billing\n  - Metering\n  - FinOps\n  - AI Cost Management\n  - Billing\n  - Monetization\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amberflo:metering-api\n    name: Amberflo Metering API\n    description: >-\n      The Amberflo Metering API provides meter definition\
  \ management, high-throughput\n      event ingestion, usage queries, raw event queries, and filtering rules. It\n      supports real-time metering for API calls, tokens, and custom events with\n      automatic aggregation and deduplication.\n    humanURL: https://docs.amberflo.io/reference/ingest-meters\n    baseURL: https://app.amberflo.io\n    tags:\n      - Metering\n      - Event Ingestion\n      - Usage Tracking\n    properties:\n      - type: Documentation\n        url: https://docs.amberflo.io/reference/ingest-meters\n      - type: APIReference\n        url: https://docs.amberflo.io/reference/ingest-meters\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/openapi/amberflo-metering-openapi.yaml\n\n  - aid: amberflo:billing-api\n    name: Amberflo Billing API\n    description: >-\n      The Amberflo Billing API manages customers, pricing plans, invoices,\n      prepaid orders, promotions, commitments, and billing\
  \ analysis. It\n      supports usage-based monetization workflows including revenue recognition,\n      chargeback management, and customer cost visibility.\n    humanURL: https://docs.amberflo.io/reference/customers\n    baseURL: https://app.amberflo.io\n    tags:\n      - Billing\n      - Customers\n      - Invoicing\n      - Pricing Plans\n    properties:\n      - type: Documentation\n        url: https://docs.amberflo.io/reference/customers\n      - type: APIReference\n        url: https://docs.amberflo.io/reference/customers\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/openapi/amberflo-billing-openapi.yaml\n\n  - aid: amberflo:cost-tracking-api\n    name: Amberflo Cost Tracking API\n    description: >-\n      The Amberflo Cost Tracking API provides AI and cloud cost management\n      capabilities including cloud provider integrations, business unit management,\n      cost allocation rules, budget management,\
  \ and cost query analytics. It\n      enables FinOps workflows with per-unit costs, showbacks, chargebacks, and\n      margin analysis per customer.\n    humanURL: https://docs.amberflo.io/reference/cloud-cost-tracking\n    baseURL: https://app.amberflo.io\n    tags:\n      - Cost Tracking\n      - FinOps\n      - Cloud Cost Management\n      - Budgets\n    properties:\n      - type: Documentation\n        url: https://docs.amberflo.io/reference/cloud-cost-tracking\n      - type: APIReference\n        url: https://docs.amberflo.io/reference/cloud-cost-tracking\n\n  - aid: amberflo:ai-gateway-api\n    name: Amberflo AI Gateway API\n    description: >-\n      The Amberflo AI Gateway provides a unified API for routing requests to\n      1,500+ LLM models with intelligent model routing, cost optimization,\n      built-in fallbacks, and MCP server traffic monitoring. It tracks LLM\n      model rates and metrics for AI cost governance.\n    humanURL: https://docs.amberflo.io/docs/ai-gateway\n\
  \    baseURL: https://app.amberflo.io\n    tags:\n      - AI Gateway\n      - LLM\n      - Model Routing\n      - AI Cost Management\n    properties:\n      - type: Documentation\n        url: https://docs.amberflo.io/docs/ai-gateway\n\ncommon:\n  - type: Website\n    url: https://www.amberflo.io/\n  - type: Documentation\n    url: https://docs.amberflo.io/\n  - type: DeveloperPortal\n    url: https://docs.amberflo.io/\n  - type: GettingStarted\n    url: https://docs.amberflo.io/docs/quick-start\n  - type: APIReference\n    url: https://docs.amberflo.io/reference/\n  - type: SignUp\n    url: https://ui.amberflo.io/cGxnLXNpZ251cA==\n  - type: Login\n    url: https://ui.amberflo.io/login\n  - type: Pricing\n    url: https://www.amberflo.io/pricing\n  - type: Blog\n    url: https://www.amberflo.io/resources/blog\n  - type: TermsOfService\n    url: https://www.amberflo.io/legal/terms-and-condition\n  - type: PrivacyPolicy\n    url: https://www.amberflo.io/legal/privacy-policy\n  - type: Compliance\n\
  \    url: https://trust.amberflo.io/\n  - type: TrustCenter\n    url: https://trust.amberflo.io/\n  - type: GitHubOrganization\n    url: https://github.com/amberflo\n  - type: SDK\n    url: https://pypi.org/project/amberflo-metering-python/\n    title: Python SDK\n  - type: SDK\n    url: https://github.com/amberflo/metering-typescript\n    title: TypeScript SDK\n  - type: SDK\n    url: https://github.com/amberflo/metering-go\n    title: Go SDK\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/rules/amberflo-spectral-rules.yml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/capabilities/usage-based-monetization.yaml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/vocabulary/amberflo-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Real-Time Event Ingestion\n       \
  \ description: >-\n          Ingest millions to billions of high-cardinality usage events in real\n          time with idempotency, deduplication, and automatic aggregation.\n      - name: AI Cost Management\n        description: >-\n          Unified LLM access and control across 1,500+ models with per-unit\n          costs, rollups, budgets, Cost Guards, and margin analysis per customer.\n      - name: AI Gateway and Model Routing\n        description: >-\n          Single API for multiple LLM providers with intelligent cost\n          optimization, automatic retries, fallbacks, and MCP server traffic\n          monitoring.\n      - name: Usage-Based Billing\n        description: >-\n          Flexible billing models including usage-based, token-based, seat-based,\n          fixed fee, and outcome-based pricing with multi-currency support and\n          automated invoicing.\n      - name: Embeddable Billing Dashboards\n        description: >-\n          Customer-facing billing portals\
  \ and dashboards via a React.js UI Kit\n          with custom domain support and SSO integration.\n      - name: Revenue Operations\n        description: >-\n          Revenue recognition automation, RevRec ledger tracking, tax management,\n          and integrations with Stripe and NetSuite.\n      - name: Budget Management\n        description: >-\n          Spending limits, threshold alerts, Cost Guards, and automated\n          notifications for cloud and AI cost governance.\n      - name: Chargeback and Showback\n        description: >-\n          Chargeback rates, quotes, and invoices for internal cost allocation\n          and showback reporting across business units.\n  - type: UseCases\n    data:\n      - name: API Monetization\n        description: >-\n          Meter API usage and automatically bill customers based on calls,\n          tokens, or custom events with flexible pricing models.\n      - name: AI Cost Governance\n        description: >-\n          Track and govern\
  \ LLM spending across teams and customers with budgets,\n          alerts, and per-customer cost attribution.\n      - name: SaaS Billing Automation\n        description: >-\n          Automate end-to-end billing for SaaS products with usage-based pricing\n          plans, invoicing, and customer portals.\n      - name: Cloud FinOps\n        description: >-\n          Allocate and showback cloud costs to business units and customers using\n          automated cost allocation rules and chargeback workflows.\n      - name: Customer Cost Transparency\n        description: >-\n          Provide customers with real-time visibility into their usage and costs\n          via embedded dashboards and billing portals.\n      - name: Usage Analytics and Reporting\n        description: >-\n          Query and analyze usage data in real time with batch and sparse query\n          modes, raw event queries, and revenue calculation analytics.\n  - type: Integrations\n    data:\n      - name: Stripe\n \
  \       description: >-\n          Native integration with Stripe for payment processing and revenue\n          operations workflows.\n      - name: NetSuite\n        description: >-\n          Integration with NetSuite for revenue recognition and financial\n          reporting.\n      - name: Kong\n        description: >-\n          Official Kong plugin for metering API requests handled by Kong\n          instances and monetizing APIs.\n      - name: AWS SaaS Builder Toolkit\n        description: >-\n          Integration with AWS SaaS Builder Toolkit for SaaS billing and\n          metering best practices on AWS.\n      - name: LiteLLM\n        description: >-\n          Logging callback for LiteLLM to meter LLM usage and monitor AI costs.\n      - name: AWS Lambda\n        description: >-\n          Examples and utilities for metering AWS Lambda function invocations.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/apis.yml
tags:
- Usage-Based Billing
- Metering
- FinOps
- AI Cost Management
- Billing
- Monetization
url: https://raw.githubusercontent.com/api-evangelist/amberflo/refs/heads/main/apis.yml
use_cases:
- description: Meter API usage and automatically bill customers based on calls, tokens, or custom events with flexible pricing models.
  name: API Monetization
- description: Track and govern LLM spending across teams and customers with budgets, alerts, and per-customer cost attribution.
  name: AI Cost Governance
- description: Automate end-to-end billing for SaaS products with usage-based pricing plans, invoicing, and customer portals.
  name: SaaS Billing Automation
- description: Allocate and showback cloud costs to business units and customers using automated cost allocation rules and chargeback workflows.
  name: Cloud FinOps
- description: Provide customers with real-time visibility into their usage and costs via embedded dashboards and billing portals.
  name: Customer Cost Transparency
- description: Query and analyze usage data in real time with batch and sparse query modes, raw event queries, and revenue calculation analytics.
  name: Usage Analytics and Reporting
---
