---
api_count: 1
apis:
- description: RESTful API providing access to consumer credit data from Equifax, Experian, and TransUnion. Supports consumer registration with consent, tri-bureau credit report retrieval, FICO and VantageScore cred
  name: Bloom Credit API
  slug: bloom-credit-api
capabilities:
- description: ''
  name: Bloom Credit Credit Intelligence
  slug: bloom-credit-credit-intelligence
common:
- title: ''
  type: Website
  url: https://bloomcredit.io/
- title: ''
  type: Documentation
  url: https://bloomcredit.io/
- title: ''
  type: GettingStarted
  url: https://bloomcredit.io/
- title: ''
  type: GitHubOrganization
  url: https://github.com/bloomcredit
- title: Python SDK
  type: SDK
  url: https://github.com/bloomcredit/bloomPy
- title: TypeScript SDK
  type: SDK
  url: https://github.com/bloomcredit/bloomTypescript
- title: ''
  type: TermsOfService
  url: https://bloomcredit.io/terms
- title: ''
  type: PrivacyPolicy
  url: https://bloomcredit.io/privacy
- title: ''
  type: SpectralRules
  url: rules/bloom-credit-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/bloom-credit-credit-intelligence.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/bloom-credit-vocabulary.yaml
created: '2025-02-24'
description: Bloom Credit is a fintech infrastructure company providing API access to consumer credit data from all three major credit bureaus (Equifax, Experian, TransUnion). The platform enables fintechs, lenders, and financial services applications to retrieve credit reports, credit scores, trade line data, and enroll consumers in real-time credit monitoring. Bloom Credit provides multi-language SDKs (Python, Ruby, TypeScript, R, Go) and supports the Metro 2 credit reporting format.
features:
- description: Pull full credit reports from Equifax, Experian, and TransUnion in a single API call with structured trade line, inquiry, and public record data.
  name: Tri-Bureau Credit Reports
- description: Access FICO 8, VantageScore 3.0, and other scoring models from all three major credit bureaus for comprehensive creditworthiness assessment.
  name: Credit Score Retrieval
- description: Retrieve individual account and trade line records including payment history, balances, credit limits, and account status across bureaus.
  name: Trade Line Data
- description: Enroll consumers in monitoring subscriptions that trigger webhook alerts for new accounts, inquiries, derogatory marks, and score changes.
  name: Real-Time Credit Monitoring
- description: Built-in consumer registration and consent workflow ensuring FCRA-compliant access to credit bureau data with auditable consent records.
  name: Consumer Consent Management
- description: Official SDKs for Python, TypeScript, Ruby, R, and Go enabling rapid integration into existing fintech and data science workflows.
  name: Multi-Language SDKs
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Direct integration with Equifax for credit report and score data including FICO 8 and other proprietary scoring models.
  name: Equifax
- description: Direct integration with Experian for credit reports, FICO scores, and VantageScore data with real-time data freshness.
  name: Experian
- description: Direct integration with TransUnion for credit reports and scores with support for TransUnion-specific data attributes.
  name: TransUnion
- description: Complementary integration where Bloom Credit's credit data can be combined with Plaid's bank account and income verification for full financial profiles.
  name: Plaid
jsonld:
- class_count: 48
  name: Bloom Credit Context
  property_count: 0
  slug: bloom-credit-context
layout: provider
modified: '2026-04-19'
name: Bloom Credit
rules:
- name: Bloom Credit API Rules
  rule_count: 30
  severity_counts:
    error: 11
    hint: 0
    info: 5
    warn: 14
  slug: bloom-credit-spectral-rules
skills: []
slug: bloom-credit
solutions: []
tags:
- Credit Bureau
- Credit Reports
- Credit Scores
- Fintech
- Lending
- Personal Finance
url: https://raw.githubusercontent.com/api-evangelist/bloom-credit/refs/heads/main/apis.yml
use_cases:
- description: Lenders pull tri-bureau credit reports and scores during loan origination to assess creditworthiness and determine loan terms.
  name: Loan Underwriting
- description: Consumer fintech applications provide users with free credit score monitoring and personalized recommendations to improve their credit profiles.
  name: Credit Building Apps
- description: Property management platforms use Bloom Credit to run credit checks during rental application processing.
  name: Tenant Screening
- description: Financial advisors and credit counselors access full credit reports and trade line data to create personalized debt management plans.
  name: Credit Counseling
- description: Financial institutions use credit data during account opening to verify identity and assess risk for credit card and deposit products.
  name: Account Origination
---
