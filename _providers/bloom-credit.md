---
api_count: 1
api_specs:
- filename: bloom-credit-api-openapi.yaml
  format: yaml
  label: Bloom Credit API
  slug: bloom-credit-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bloom-credit/refs/heads/main/openapi/bloom-credit-api-openapi.yaml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bloom-credit\nurl: https://raw.githubusercontent.com/api-evangelist/bloom-credit/refs/heads/main/apis.yml\nname: Bloom Credit\ndescription: >-\n  Bloom Credit is a fintech infrastructure company providing API access to consumer\n  credit data from all three major credit bureaus (Equifax, Experian, TransUnion).\n  The platform enables fintechs, lenders, and financial services applications to\n  retrieve credit reports, credit scores, trade line data, and enroll consumers in\n  real-time credit monitoring. Bloom Credit provides multi-language SDKs (Python,\n  Ruby, TypeScript, R, Go) and supports the Metro 2 credit reporting format.\ntags:\n  - Credit Bureau\n  - Credit Reports\n  - Credit Scores\n  - Fintech\n  - Lending\n  - Personal Finance\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-24'\nmodified: '2026-04-19'\nposition: Consuming\nspecificationVersion: '0.19'\napis:\n  - aid: bloom-credit:bloom-credit-api\n\
  \    name: Bloom Credit API\n    description: >-\n      RESTful API providing access to consumer credit data from Equifax, Experian,\n      and TransUnion. Supports consumer registration with consent, tri-bureau credit\n      report retrieval, FICO and VantageScore credit scores, trade line data, and\n      real-time credit monitoring with webhook alerts. Requires API key authentication.\n    humanURL: https://bloomcredit.io/\n    tags:\n      - Credit Bureau\n      - Credit Reports\n      - Credit Scores\n      - Fintech\n      - Lending\n    properties:\n      - type: Documentation\n        url: https://bloomcredit.io/\n      - type: OpenAPI\n        url: openapi/bloom-credit-api-openapi.yaml\n      - type: NaftikoCapability\n        url: capabilities/bloom-credit-credit-intelligence.yaml\n      - type: SpectralRules\n        url: rules/bloom-credit-spectral-rules.yml\n      - type: Vocabulary\n        url: vocabulary/bloom-credit-vocabulary.yaml\ncommon:\n  - type: Website\n    url:\
  \ https://bloomcredit.io/\n  - type: Documentation\n    url: https://bloomcredit.io/\n  - type: GettingStarted\n    url: https://bloomcredit.io/\n  - type: GitHubOrganization\n    url: https://github.com/bloomcredit\n  - type: SDK\n    url: https://github.com/bloomcredit/bloomPy\n    title: Python SDK\n  - type: SDK\n    url: https://github.com/bloomcredit/bloomTypescript\n    title: TypeScript SDK\n  - type: TermsOfService\n    url: https://bloomcredit.io/terms\n  - type: PrivacyPolicy\n    url: https://bloomcredit.io/privacy\n  - type: SpectralRules\n    url: rules/bloom-credit-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/bloom-credit-credit-intelligence.yaml\n  - type: Vocabulary\n    url: vocabulary/bloom-credit-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Tri-Bureau Credit Reports\n        description: >-\n          Pull full credit reports from Equifax, Experian, and TransUnion in a\n          single API call with structured trade line,\
  \ inquiry, and public record data.\n      - name: Credit Score Retrieval\n        description: >-\n          Access FICO 8, VantageScore 3.0, and other scoring models from all\n          three major credit bureaus for comprehensive creditworthiness assessment.\n      - name: Trade Line Data\n        description: >-\n          Retrieve individual account and trade line records including payment\n          history, balances, credit limits, and account status across bureaus.\n      - name: Real-Time Credit Monitoring\n        description: >-\n          Enroll consumers in monitoring subscriptions that trigger webhook alerts\n          for new accounts, inquiries, derogatory marks, and score changes.\n      - name: Consumer Consent Management\n        description: >-\n          Built-in consumer registration and consent workflow ensuring FCRA-compliant\n          access to credit bureau data with auditable consent records.\n      - name: Multi-Language SDKs\n        description: >-\n     \
  \     Official SDKs for Python, TypeScript, Ruby, R, and Go enabling rapid\n          integration into existing fintech and data science workflows.\n  - type: UseCases\n    data:\n      - name: Loan Underwriting\n        description: >-\n          Lenders pull tri-bureau credit reports and scores during loan origination\n          to assess creditworthiness and determine loan terms.\n      - name: Credit Building Apps\n        description: >-\n          Consumer fintech applications provide users with free credit score monitoring\n          and personalized recommendations to improve their credit profiles.\n      - name: Tenant Screening\n        description: >-\n          Property management platforms use Bloom Credit to run credit checks\n          during rental application processing.\n      - name: Credit Counseling\n        description: >-\n          Financial advisors and credit counselors access full credit reports and\n          trade line data to create personalized debt management\
  \ plans.\n      - name: Account Origination\n        description: >-\n          Financial institutions use credit data during account opening to verify\n          identity and assess risk for credit card and deposit products.\n  - type: Integrations\n    data:\n      - name: Equifax\n        description: >-\n          Direct integration with Equifax for credit report and score data including\n          FICO 8 and other proprietary scoring models.\n      - name: Experian\n        description: >-\n          Direct integration with Experian for credit reports, FICO scores, and\n          VantageScore data with real-time data freshness.\n      - name: TransUnion\n        description: >-\n          Direct integration with TransUnion for credit reports and scores with\n          support for TransUnion-specific data attributes.\n      - name: Plaid\n        description: >-\n          Complementary integration where Bloom Credit's credit data can be combined\n          with Plaid's bank account\
  \ and income verification for full financial profiles.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloom-credit/refs/heads/main/apis.yml
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
