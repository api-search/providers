---
api_count: 7
apis:
- description: Core banking API providing access to account management, transactions, and customer data for wealth management and digital banking solutions. Supports over 7,500 REST API endpoints for comprehensive b
  name: Avaloq Banking API
  slug: avaloq-banking-api
- description: Wealth management API providing investment portfolio management, client advisory, and asset management capabilities. Integrates with BlackRock Aladdin for institutional-grade investment management and
  name: Avaloq Wealth Management API
  slug: avaloq-wealth-management-api
- description: Payments processing API supporting domestic and international payment instructions, SEPA transfers, SWIFT messaging, and real-time payment rails for banking clients.
  name: Avaloq Payments API
  slug: avaloq-payments-api
- description: Client onboarding, KYC, and relationship management API for banking and wealth management institutions. Provides customer data management, document collection, and compliance screening for financial s
  name: Avaloq Client Management API
  slug: avaloq-client-management-api
- description: Order management and trading API for executing equity, fixed income, and multi-asset trades through the Avaloq banking platform. Supports order lifecycle management, execution, and settlement.
  name: Avaloq Trading API
  slug: avaloq-trading-api
- description: Regulatory compliance and risk management API covering AML monitoring, sanctions screening, regulatory reporting, and treasury risk for banking institutions. Supports FINMA, MiFID II, and other regula
  name: Avaloq Compliance & Risk API
  slug: avaloq-compliance-api
- description: Community APIs for fintech integration providing simplified REST endpoints for connecting third-party applications with the Avaloq banking platform. Pre-vetted by Avaloq for secure, standards-based in
  name: Avaloq Community API
  slug: avaloq-community-api
capabilities:
- description: ''
  name: Avaloq Wealth Management
  slug: avaloq-wealth-management
common:
- title: ''
  type: Portal
  url: https://developer.avaloq.com/
- title: ''
  type: Website
  url: https://www.avaloq.com/
- title: ''
  type: GettingStarted
  url: https://developer.avaloq.com/web/developer-portal/getting-started/developing
- title: ''
  type: Ecosystem
  url: https://www.avaloq.com/platform/ecosystem
- title: ''
  type: Academy
  url: https://avaloq.academy/
- title: ''
  type: Support
  url: https://www.avaloq.com/en/for-developers
- title: ''
  type: GitHubOrganization
  url: https://github.com/avaloq
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/avaloq/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/openapi/avaloq-banking-openapi.yml
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/rules/avaloq-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/vocabulary/avaloq-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/capabilities/avaloq-wealth-management.yaml
created: '2024-01-20'
description: Avaloq is a leading provider of wealth management technology and digital banking solutions, offering over 7,500 REST API endpoints for financial services integration. The platform connects more than 170 financial institutions with 200+ fintech partners through Community APIs, Standard Adapters, and certified integrations for banking, wealth management, payments, and compliance.
features:
- description: Over 7,500 REST API endpoints for comprehensive banking and wealth management operations.
  name: 7500+ REST API Endpoints
- description: Pre-vetted REST APIs for seamless fintech integration with the Avaloq platform.
  name: Community APIs
- description: Three adapter types (Standard, Certified, Project) enabling ecosystem connectivity.
  name: Standard and Certified Adapters
- description: Sandbox access to Avaloq products in the cloud for integration testing.
  name: Cloud Sandbox
- description: Event-driven integration via Apache Kafka for real-time data streaming alongside REST APIs.
  name: Kafka Integration
- description: Dual protocol support for SOAP and REST through the AMI Web Services Framework.
  name: SOAP and REST Support
- description: Built-in integration with BlackRock Aladdin for institutional investment management.
  name: BlackRock Aladdin Integration
- description: Support for FINMA, MiFID II, GDPR, and other regulatory frameworks.
  name: Multi-Jurisdiction Regulatory Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with Aladdin by BlackRock for institutional investment management.
  name: BlackRock Aladdin
- description: Market data integration with Bloomberg for pricing and analytics.
  name: Bloomberg
- description: SWIFT messaging network integration for international payment processing.
  name: SWIFT
- description: SEPA credit transfer and direct debit support for European payments.
  name: SEPA
- description: Avaloq Model Bank available on AWS for simplified cloud deployment and testing.
  name: AWS
- description: CRM integration with Salesforce for client relationship management.
  name: Salesforce
- description: FIX protocol support for electronic trading and order routing.
  name: FIX Protocol
jsonld:
- class_count: 0
  name: Avaloq Banking Context
  property_count: 17
  slug: avaloq-banking-context
- class_count: 0
  name: Avaloq Payments Context
  property_count: 8
  slug: avaloq-payments-context
layout: provider
modified: '2026-04-19'
name: Avaloq
rules:
- name: Avaloq API Rules
  rule_count: 25
  severity_counts:
    error: 9
    hint: 0
    info: 1
    warn: 15
  slug: avaloq-spectral-rules
skills: []
slug: avaloq
solutions: []
tags:
- Banking
- Digital Banking
- Financial Services
- Fintech
- Payments
- Wealth Management
url: https://raw.githubusercontent.com/api-evangelist/avaloq/refs/heads/main/apis.yml
use_cases:
- description: Connect advisory tools and portfolio management applications with core banking data.
  name: Wealth Management Platform Integration
- description: Build mobile and web banking experiences on top of Avaloq account and transaction APIs.
  name: Digital Banking Channels
- description: Onboard fintech partners into the banking ecosystem through Community APIs.
  name: Fintech Partner Integration
- description: Automate MiFID II, FINMA, and other regulatory report generation and submission.
  name: Regulatory Reporting Automation
- description: Integrate domestic SEPA and international SWIFT payment processing.
  name: Payment Processing
- description: Digitize client onboarding with KYC checks, document collection, and compliance screening.
  name: KYC and Client Onboarding
- description: Build robo-advisory and portfolio management tools using investment APIs.
  name: Investment Portfolio Management
- description: Execute and manage multi-asset trade orders through the Avaloq OMS.
  name: Trade Order Management
---
