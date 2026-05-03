---
api_count: 1
api_specs:
- filename: upvest-investment-api-openapi.yml
  format: yaml
  label: Upvest Investment API
  slug: investment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/openapi/upvest-investment-api-openapi.yml
apis:
- description: The Upvest Investment API provides a unified interface for building embedded investment experiences. It supports placing and managing orders, creating portfolios, configuring savings plans, handling s
  name: Upvest Investment API
  slug: investment-api
asyncapis:
- description: The Upvest Investment API uses an asynchronous, event-driven architecture where events represent state changes within the system. Webhook subscriptions allow your application to receive real-time noti
  name: Upvest Investment Events
  slug: upvest-investment-events-asyncapi
capabilities:
- description: Unified workflow capability for building and managing investment experiences on the Upvest platform. Covers user onboarding, account management, order placement, portfolio management, savings plans, a
  name: Upvest Investment Operations
  slug: investment-operations
common:
- title: ''
  type: Website
  url: https://upvest.co/
- title: ''
  type: Portal
  url: https://upvest.co/developers
- title: ''
  type: Documentation
  url: https://docs.upvest.co/
- title: ''
  type: GettingStarted
  url: https://docs.upvest.co/documentation/guides
- title: ''
  type: Blog
  url: https://upvest.co/blog
- title: Engineering Blog
  type: Blog
  url: https://engineering.upvest.co/
- title: ''
  type: SignUp
  url: https://upvest.co/contact
- title: ''
  type: PrivacyPolicy
  url: https://upvest.co/legal/privacy-policy
- title: ''
  type: GitHubOrganization
  url: https://github.com/upvestco
- title: HTTP Signature Proxy CLI
  type: GitHubRepository
  url: https://github.com/upvestco/httpsignature-proxy
- title: HTTP Signature Examples
  type: GitHubRepository
  url: https://github.com/upvestco/http-signature-examples
- title: Documentation Assets
  type: GitHubRepository
  url: https://github.com/upvestco/documentation_assets
- title: ''
  type: JSONLD
  url: json-ld/upvest-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/upvest-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/upvest-vocabulary.yaml
- title: Investment Operations
  type: NaftikoCapability
  url: capabilities/investment-operations.yaml
- title: Investment API (Shared)
  type: NaftikoCapability
  url: capabilities/shared/investment-api.yaml
created: '2026-03-24'
description: Upvest is a Berlin-based API-first investment infrastructure provider that enables banks, brokers, and wealth managers to build and launch investment experiences through a single modular API. Founded in 2017, Upvest is a regulated securities institution in Europe and the UK, covering trading, custody, and back-office operations. The platform supports fractional investing, portfolios, savings plans, roundups, and direct debit, enabling clients like Bunq, DKB, N26, Revolut, and Raisin to offer investment products to their customers.
features:
- description: Enable customers to invest in stocks and ETFs starting at 1 EUR with fractional share support.
  name: Fractional Investing
- description: Build customized portfolios of stocks, ETFs, and upcoming crypto assets with automated rebalancing.
  name: Portfolio Management
- description: Configure recurring automated investment plans with direct debit integration.
  name: Savings Plans
- description: Micro-investing through spending-based roundups that automatically invest spare change.
  name: Roundups
- description: Enable customers to open investment accounts in seconds through the API.
  name: Instant Account Creation
- description: Regulated custody services with digital reports and securities safeguarding.
  name: Custody Management
- description: Track and manage cash balances across multiple currencies with virtual bank accounts.
  name: Multi-Currency Cash Management
- description: Automated tax wrapper support including ISA, tax exemptions, and compliance reporting.
  name: Tax and Compliance
- description: Real-time asynchronous event notifications for orders, payments, accounts, and compliance events.
  name: Webhook Events
- description: Full-featured sandbox at sandbox.upvest.co for testing with simulated bank transactions.
  name: Sandbox Environment
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Localhost proxy for handling HTTP request signing required by the Upvest Investment API.
  name: HTTP Signature Proxy
- description: Automated recurring payment integration for savings plans and top-ups.
  name: Direct Debit
- description: Event-driven integration pattern via Upvest webhook subscriptions for real-time processing.
  name: Webhook Integration
- description: Client credentials flow for API authentication and token management.
  name: OAuth 2.0
jsonld:
- class_count: 63
  name: Upvest Context
  property_count: 68
  slug: upvest-context
layout: provider
modified: '2026-05-03'
name: Upvest
rules:
- name: Upvest API Rules
  rule_count: 39
  severity_counts:
    error: 17
    hint: 0
    info: 3
    warn: 19
  slug: upvest-spectral-rules
skills: []
slug: upvest
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: upvest\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/apis.yml\nname: Upvest\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Banking Infrastructure\n  - Fintech\n  - Investments\n  - Securities\n  - Fractional Investing\n  - Custody\n  - Wealth Management\ndescription: >-\n  Upvest is a Berlin-based API-first investment infrastructure provider that enables\n  banks, brokers, and wealth managers to build and launch investment experiences through\n  a single modular API. Founded in 2017, Upvest is a regulated securities institution\n  in Europe and the UK, covering trading, custody, and back-office operations. The\n  platform supports fractional investing, portfolios, savings plans, roundups, and\n  direct debit, enabling clients like Bunq, DKB, N26, Revolut, and Raisin to offer\n  investment products to their customers.\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: upvest:investment-api\n    name: Upvest Investment API\n    tags:\n      - Custody\n      - Investments\n      - Orders\n      - Portfolios\n      - Securities\n      - Trading\n      - Fractional Investing\n      - Savings Plans\n      - Payments\n      - Webhooks\n    humanURL: https://docs.upvest.co/\n    baseURL: https://api.upvest.co\n    properties:\n      - url: https://docs.upvest.co/api\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/upvest-investment-api-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/upvest-investment-events-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/upvest-webhook-event-schema.json\n      - type: JSONSchema\n        url: json-schema/upvest-order-schema.json\n      - type: JSONSchema\n        url: json-schema/investment-api-user-schema.json\n      - type: JSONSchema\n        url: json-schema/investment-api-account-schema.json\n      - type: JSONSchema\n        url: json-schema/investment-api-order-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/investment-api-portfolio-schema.json\n      - type: JSONSchema\n        url: json-schema/investment-api-savings-plan-schema.json\n      - type: JSONSchema\n        url: json-schema/investment-api-instrument-schema.json\n      - type: JSONSchema\n        url: json-schema/investment-api-transaction-schema.json\n      - type: JSONSchema\n        url: json-schema/investment-api-position-schema.json\n    description: >-\n      The Upvest Investment API provides a unified interface for building embedded\n      investment experiences. It supports placing and managing orders, creating portfolios,\n      configuring savings plans, handling securities transfers, and managing user\n      accounts and positions. The API covers the full order lifecycle with asynchronous\n      processing and webhook notifications for real-time event handling. Key resource\n      groups include users and businesses, accounts, orders and executions, instruments\n  \
  \    and price data, portfolios, savings plans, payments (top-ups, withdrawals, direct\n      debits), tax and compliance, webhooks, and reporting.\ncommon:\n  - type: Website\n    url: https://upvest.co/\n  - type: Portal\n    url: https://upvest.co/developers\n  - type: Documentation\n    url: https://docs.upvest.co/\n  - type: GettingStarted\n    url: https://docs.upvest.co/documentation/guides\n  - type: Blog\n    url: https://upvest.co/blog\n  - type: Blog\n    url: https://engineering.upvest.co/\n    title: Engineering Blog\n  - type: SignUp\n    url: https://upvest.co/contact\n  - type: PrivacyPolicy\n    url: https://upvest.co/legal/privacy-policy\n  - type: GitHubOrganization\n    url: https://github.com/upvestco\n  - type: GitHubRepository\n    url: https://github.com/upvestco/httpsignature-proxy\n    title: HTTP Signature Proxy CLI\n  - type: GitHubRepository\n    url: https://github.com/upvestco/http-signature-examples\n    title: HTTP Signature Examples\n  - type: GitHubRepository\n\
  \    url: https://github.com/upvestco/documentation_assets\n    title: Documentation Assets\n  - type: JSONLD\n    url: json-ld/upvest-context.jsonld\n  - type: SpectralRules\n    url: rules/upvest-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/upvest-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/investment-operations.yaml\n    title: Investment Operations\n  - type: NaftikoCapability\n    url: capabilities/shared/investment-api.yaml\n    title: Investment API (Shared)\n  - type: Features\n    data:\n      - name: Fractional Investing\n        description: Enable customers to invest in stocks and ETFs starting at 1 EUR with fractional share support.\n      - name: Portfolio Management\n        description: Build customized portfolios of stocks, ETFs, and upcoming crypto assets with automated rebalancing.\n      - name: Savings Plans\n        description: Configure recurring automated investment plans with direct debit integration.\n      - name: Roundups\n\
  \        description: Micro-investing through spending-based roundups that automatically invest spare change.\n      - name: Instant Account Creation\n        description: Enable customers to open investment accounts in seconds through the API.\n      - name: Custody Management\n        description: Regulated custody services with digital reports and securities safeguarding.\n      - name: Multi-Currency Cash Management\n        description: Track and manage cash balances across multiple currencies with virtual bank accounts.\n      - name: Tax and Compliance\n        description: Automated tax wrapper support including ISA, tax exemptions, and compliance reporting.\n      - name: Webhook Events\n        description: Real-time asynchronous event notifications for orders, payments, accounts, and compliance events.\n      - name: Sandbox Environment\n        description: Full-featured sandbox at sandbox.upvest.co for testing with simulated bank transactions.\n  - type: UseCases\n    data:\n\
  \      - name: Embedded Brokerage\n        description: Banks and fintechs embedding fractional stock and ETF trading into existing financial products.\n      - name: Digital Wealth Management\n        description: Wealth managers building automated portfolio and savings plan products for retail clients.\n      - name: Neobank Investment Features\n        description: Neobanks adding investment capabilities to checking and savings account offerings.\n      - name: White-Label Investment Platform\n        description: Third-party platforms building fully branded investment experiences using Upvest infrastructure.\n      - name: Roundup Investing\n        description: Platforms enabling micro-investing by rounding up purchases and investing the difference.\n  - type: Integrations\n    data:\n      - name: HTTP Signature Proxy\n        description: Localhost proxy for handling HTTP request signing required by the Upvest Investment API.\n      - name: Direct Debit\n        description: Automated\
  \ recurring payment integration for savings plans and top-ups.\n      - name: Webhook Integration\n        description: Event-driven integration pattern via Upvest webhook subscriptions for real-time processing.\n      - name: OAuth 2.0\n        description: Client credentials flow for API authentication and token management.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/apis.yml
tags:
- Banking Infrastructure
- Fintech
- Investments
- Securities
- Fractional Investing
- Custody
- Wealth Management
url: https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/apis.yml
use_cases:
- description: Banks and fintechs embedding fractional stock and ETF trading into existing financial products.
  name: Embedded Brokerage
- description: Wealth managers building automated portfolio and savings plan products for retail clients.
  name: Digital Wealth Management
- description: Neobanks adding investment capabilities to checking and savings account offerings.
  name: Neobank Investment Features
- description: Third-party platforms building fully branded investment experiences using Upvest infrastructure.
  name: White-Label Investment Platform
- description: Platforms enabling micro-investing by rounding up purchases and investing the difference.
  name: Roundup Investing
---
