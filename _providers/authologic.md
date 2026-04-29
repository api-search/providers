---
api_count: 4
apis:
- description: The Authologic Identity API enables businesses to initiate identity verification processes and receive results programmatically. Supports document verification, eID, Bank ID, and biometric liveness ch
  name: Authologic Identity API
  slug: authologic-identity-api
- description: The Authologic AML API enables Anti-Money Laundering screening combined with identity verification in a single integrated flow for KYC/AML compliance.
  name: Authologic AML API
  slug: authologic-aml-api
- description: The Authologic Data Verification API enables verification of personal data against authoritative sources including government databases and credit bureaus.
  name: Authologic Data Verification API
  slug: authologic-data-verification-api
- description: The Authologic Enquiry API enables background checks and identity enquiries against national and international data sources for enhanced due diligence.
  name: Authologic Enquiry API
  slug: authologic-enquiry-api
common:
- title: ''
  type: Website
  url: https://authologic.com/
- title: ''
  type: Portal
  url: https://developer.authologic.com/
- title: ''
  type: Documentation
  url: https://developer.authologic.com/docs/developer-documentation/integration-overview
- title: ''
  type: GettingStarted
  url: https://developer.authologic.com/docs/developer-documentation/integration-overview
- title: ''
  type: Blog
  url: https://authologic.com/blog/
- title: ''
  type: SignUp
  url: https://authologic.com/
- title: ''
  type: PrivacyPolicy
  url: https://authologic.com/privacy-policy/
created: '2025-05-02'
description: Authologic is an identity verification platform providing businesses with a single API to aggregate multiple ID verification methods including government-issued digital IDs, Bank IDs, document OCR, liveness checks, and AML screening. It supports seamless KYC/KYB workflow integration for businesses across multiple countries.
features:
- description: One API integration provides access to multiple identity verification methods without separate integrations per provider.
  name: Single API Integration
- description: Native support for government-issued digital IDs and Bank IDs across multiple European countries for high-trust verification.
  name: eID and Bank ID Support
- description: Automated document scanning with OCR and biometric liveness detection to prevent spoofing and fraud.
  name: Document OCR and Liveness
- description: Integrated anti-money laundering screening against sanctions lists, PEP databases, and adverse media sources.
  name: AML Screening
- description: No-integration verification flow using a hosted link for simple verification without technical implementation.
  name: OmniLink
- description: Compose verification workflows from modular steps combining document, biometric, data, and AML checks.
  name: Modular Workflows
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with national eID infrastructures across multiple European countries for government-backed identity verification.
  name: European eID Networks
- description: Connection to Bank ID systems in Poland, Sweden, Norway, and other markets for bank-verified identity assurance.
  name: Bank ID Systems
- description: Designed to integrate alongside existing KYC/AML infrastructure as modular workflow components.
  name: Existing KYC Workflows
layout: provider
modified: '2026-04-19'
name: Authologic
skills: []
slug: authologic
solutions:
- description: Complete KYC solution for banks, fintechs, and payment providers with AML screening and document verification.
  name: Financial Services KYC
- description: Aggregate multiple ID verification methods via single API for flexible identity assurance across user populations.
  name: Digital Identity Verification
source_yaml: "aid: authologic\nname: Authologic\ndescription: |\n  Authologic is an identity verification platform providing businesses with a single API to aggregate multiple ID verification methods including government-issued digital IDs, Bank IDs, document OCR, liveness checks, and AML screening. It supports seamless KYC/KYB workflow integration for businesses across multiple countries.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AML\n- Digital Identity\n- eID\n- Identity Verification\n- KYB\n- KYC\n- Liveness Check\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/authologic/refs/heads/main/apis.yml\ncreated: '2025-05-02'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: authologic:authologic-identity-api\n  name: Authologic Identity API\n  description: |\n    The Authologic Identity API enables businesses to initiate identity verification processes and receive results programmatically. Supports\
  \ document verification, eID, Bank ID, and biometric liveness check methods via a single integration.\n  humanURL: https://developer.authologic.com/docs/developer-documentation/product-identity-api-integration\n  baseURL: https://api.authologic.com\n  tags:\n  - eID\n  - Identity Verification\n  - KYC\n  - Liveness\n  properties:\n  - type: Documentation\n    url: https://developer.authologic.com/docs/developer-documentation/product-identity-api-integration\n  - type: GettingStarted\n    url: https://developer.authologic.com/docs/developer-documentation/integration-overview\n- aid: authologic:authologic-aml-api\n  name: Authologic AML API\n  description: |\n    The Authologic AML API enables Anti-Money Laundering screening combined with identity verification in a single integrated flow for KYC/AML compliance.\n  humanURL: https://developer.authologic.com/docs/developer-documentation/product-aml-api-integration-with-identity\n  baseURL: https://api.authologic.com\n  tags:\n  - AML\n  -\
  \ Compliance\n  - Identity Verification\n  - KYC\n  properties:\n  - type: Documentation\n    url: https://developer.authologic.com/docs/developer-documentation/product-aml-api-integration-with-identity\n- aid: authologic:authologic-data-verification-api\n  name: Authologic Data Verification API\n  description: |\n    The Authologic Data Verification API enables verification of personal data against authoritative sources including government databases and credit bureaus.\n  humanURL: https://developer.authologic.com/docs/developer-documentation/product-data-verification-api-integration\n  baseURL: https://api.authologic.com\n  tags:\n  - Data Verification\n  - Identity\n  - KYC\n  properties:\n  - type: Documentation\n    url: https://developer.authologic.com/docs/developer-documentation/product-data-verification-api-integration\n- aid: authologic:authologic-enquiry-api\n  name: Authologic Enquiry API\n  description: |\n    The Authologic Enquiry API enables background checks and identity\
  \ enquiries against national and international data sources for enhanced due diligence.\n  humanURL: https://developer.authologic.com/docs/developer-documentation/product-enquiry-api-integration\n  baseURL: https://api.authologic.com\n  tags:\n  - Background Check\n  - Identity\n  - KYB\n  properties:\n  - type: Documentation\n    url: https://developer.authologic.com/docs/developer-documentation/product-enquiry-api-integration\ncommon:\n- type: Website\n  url: https://authologic.com/\n- type: Portal\n  url: https://developer.authologic.com/\n- type: Documentation\n  url: https://developer.authologic.com/docs/developer-documentation/integration-overview\n- type: GettingStarted\n  url: https://developer.authologic.com/docs/developer-documentation/integration-overview\n- type: Blog\n  url: https://authologic.com/blog/\n- type: SignUp\n  url: https://authologic.com/\n- type: PrivacyPolicy\n  url: https://authologic.com/privacy-policy/\n- type: Features\n  data:\n  - name: Single API Integration\n\
  \    description: One API integration provides access to multiple identity verification methods without separate integrations per provider.\n  - name: eID and Bank ID Support\n    description: Native support for government-issued digital IDs and Bank IDs across multiple European countries for high-trust verification.\n  - name: Document OCR and Liveness\n    description: Automated document scanning with OCR and biometric liveness detection to prevent spoofing and fraud.\n  - name: AML Screening\n    description: Integrated anti-money laundering screening against sanctions lists, PEP databases, and adverse media sources.\n  - name: OmniLink\n    description: No-integration verification flow using a hosted link for simple verification without technical implementation.\n  - name: Modular Workflows\n    description: Compose verification workflows from modular steps combining document, biometric, data, and AML checks.\n- type: UseCases\n  data:\n  - name: Customer Onboarding KYC\n    description:\
  \ Verify customer identities during registration and onboarding for financial services, fintech, and regulated industries.\n  - name: AML Compliance\n    description: Combine identity verification with AML screening to meet financial institution compliance requirements.\n  - name: Business Verification (KYB)\n    description: Verify business identities and beneficial owners for B2B onboarding and corporate due diligence.\n  - name: Age Verification\n    description: Verify user ages using official ID documents for age-restricted products and services.\n- type: Integrations\n  data:\n  - name: European eID Networks\n    description: Integration with national eID infrastructures across multiple European countries for government-backed identity verification.\n  - name: Bank ID Systems\n    description: Connection to Bank ID systems in Poland, Sweden, Norway, and other markets for bank-verified identity assurance.\n  - name: Existing KYC Workflows\n    description: Designed to integrate alongside\
  \ existing KYC/AML infrastructure as modular workflow components.\n- type: Solutions\n  data:\n  - name: Financial Services KYC\n    description: Complete KYC solution for banks, fintechs, and payment providers with AML screening and document verification.\n  - name: Digital Identity Verification\n    description: Aggregate multiple ID verification methods via single API for flexible identity assurance across user populations.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/authologic/refs/heads/main/apis.yml
tags:
- AML
- Digital Identity
- eID
- Identity Verification
- KYB
- KYC
- Liveness Check
url: https://raw.githubusercontent.com/api-evangelist/authologic/refs/heads/main/apis.yml
use_cases:
- description: Verify customer identities during registration and onboarding for financial services, fintech, and regulated industries.
  name: Customer Onboarding KYC
- description: Combine identity verification with AML screening to meet financial institution compliance requirements.
  name: AML Compliance
- description: Verify business identities and beneficial owners for B2B onboarding and corporate due diligence.
  name: Business Verification (KYB)
- description: Verify user ages using official ID documents for age-restricted products and services.
  name: Age Verification
---
