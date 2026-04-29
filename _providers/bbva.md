---
api_count: 4
apis:
- description: PSD2-compliant account information service (AIS) API for Spain. Allows authorized third parties to access customer payment account information including account lists, balances, transaction history, a
  name: BBVA Accounts PSD2 API
  slug: accounts-psd2
- description: PSD2-compliant payment initiation service (PIS) API for Spain. Allows authorized third parties to initiate payments on behalf of customers including SEPA transfers, immediate payments, Bank of Spain F
  name: BBVA Payments PSD2 API
  slug: payments-psd2
- description: 'Business payment processing API for Mexico enabling bulk payments, payroll disbursements, and supplier payments through BBVA Mexico''s banking infrastructure. Supports SPEI transfers and other Mexican '
  name: BBVA Mexico Business Payments API
  slug: mexico-business-payments
- description: Open data API providing access to BBVA branch and ATM location data. Available for Spain and Mexico, this API returns geolocation data, operating hours, services available, and accessibility informati
  name: BBVA Locations API
  slug: locations
capabilities:
- description: ''
  name: Open Banking
  slug: open-banking
common:
- title: ''
  type: Portal
  url: https://www.bbvaapimarket.com/en/
- title: ''
  type: Website
  url: https://www.bbva.com/
- title: ''
  type: Documentation
  url: https://www.bbvaapimarket.com/en/api-developers/
- title: ''
  type: GettingStarted
  url: https://www.bbvaapimarket.com/en/api-developers/
- title: ''
  type: Sandbox
  url: https://www.bbvaapimarket.com/en/api-developers/
- title: ''
  type: TermsOfService
  url: https://www.bbva.com/en/legal-notice/
- title: ''
  type: PrivacyPolicy
  url: https://www.bbva.com/en/privacy-policy/
- title: ''
  type: Blog
  url: https://www.bbvaapimarket.com/en/api-world/
- title: ''
  type: SpectralRules
  url: rules/bbva-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/bbva-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/open-banking.yaml
- title: ''
  type: JSON-LD
  url: json-ld/bbva-context.jsonld
created: '2025-02-08'
description: BBVA is a multinational Spanish financial services group operating in over 30 countries. The BBVA API Market provides a comprehensive catalog of banking APIs covering accounts, payments, collections, financing, identity, and open data across Spain, Mexico, Latin America, and other global markets. BBVA is a recognized open banking leader offering PSD2-compliant APIs, treasury management solutions, and digital ecosystem integrations.
features:
- description: All European banking APIs are fully compliant with the PSD2 Payment Services Directive, including AIS and PIS services.
  name: PSD2 Compliance
- description: APIs available across 15+ countries including Spain, Mexico, Peru, Colombia, Argentina, Belgium, France, UK, Turkey, and USA.
  name: Multi-Country Coverage
- description: Multi-country treasury APIs for global enterprises to manage payments, collections, and cash positions.
  name: Treasury Management
- description: APIs enabling businesses to embed BBVA banking services into their own digital platforms and applications.
  name: Digital Ecosystems
- description: Developer sandbox environment for testing and validating API integrations before production deployment.
  name: Sandbox Environment
- description: Publicly accessible location and branch data APIs available without authentication for branch/ATM locators.
  name: Open Data APIs
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Spanish payment gateway and PSD2 infrastructure through which BBVA PSD2 APIs are registered and deployed.
  name: Redsys
- description: Single Euro Payments Area integration for European payment transfers in Spain and EU markets.
  name: SEPA
- description: Mexican interbank payment system integration for Mexico business payment APIs.
  name: SPEI
- description: ERP integration for treasury management customers connecting SAP financial systems with BBVA APIs.
  name: SAP
jsonld:
- class_count: 0
  name: Bbva Context
  property_count: 10
  slug: bbva-context
layout: provider
modified: '2026-04-21'
name: BBVA
rules:
- name: BBVA API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 3
  slug: bbva-spectral-rules
skills: []
slug: bbva
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bbva\nurl: https://raw.githubusercontent.com/api-evangelist/bbva/refs/heads/main/apis.yml\nname: BBVA\ndescription: >-\n  BBVA is a multinational Spanish financial services group operating in over 30 countries.\n  The BBVA API Market provides a comprehensive catalog of banking APIs covering accounts,\n  payments, collections, financing, identity, and open data across Spain, Mexico, Latin\n  America, and other global markets. BBVA is a recognized open banking leader offering\n  PSD2-compliant APIs, treasury management solutions, and digital ecosystem integrations.\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Banking\n  - Financial Services\n  - Open Banking\n  - PSD2\n  - Spain\n  - Mexico\naccess: 3rd-Party\ncreated: '2025-02-08'\nmodified: '2026-04-21'\nposition: Consumer\nspecificationVersion: '0.19'\napis:\n  - aid: bbva:accounts-psd2\n    name: BBVA Accounts PSD2 API\n    description: >-\n\
  \      PSD2-compliant account information service (AIS) API for Spain. Allows\n      authorized third parties to access customer payment account information\n      including account lists, balances, transaction history, and account holder\n      details. Requires a PSD2 AIS license and registration through the Redsys platform.\n    humanURL: https://www.bbvaapimarket.com/en/banking-apis/es-account-information-psd2/\n    tags:\n      - Banking\n      - Accounts\n      - PSD2\n      - Spain\n      - Open Banking\n    properties:\n      - type: Documentation\n        url: https://www.bbvaapimarket.com/en/banking-apis/es-account-information-psd2/\n\n  - aid: bbva:payments-psd2\n    name: BBVA Payments PSD2 API\n    description: >-\n      PSD2-compliant payment initiation service (PIS) API for Spain. Allows authorized\n      third parties to initiate payments on behalf of customers including SEPA transfers,\n      immediate payments, Bank of Spain FMO payments, and international transfers.\n\
  \      Requires a PSD2 PIS license and registration through the Redsys platform.\n    humanURL: https://www.bbvaapimarket.com/en/banking-apis/es-payments-psd2/\n    tags:\n      - Banking\n      - Payments\n      - PSD2\n      - Spain\n      - Open Banking\n    properties:\n      - type: Documentation\n        url: https://www.bbvaapimarket.com/en/banking-apis/es-payments-psd2/\n\n  - aid: bbva:mexico-business-payments\n    name: BBVA Mexico Business Payments API\n    description: >-\n      Business payment processing API for Mexico enabling bulk payments, payroll\n      disbursements, and supplier payments through BBVA Mexico's banking infrastructure.\n      Supports SPEI transfers and other Mexican payment systems.\n    humanURL: https://www.bbvaapimarket.com/en/banking-apis/\n    tags:\n      - Banking\n      - Payments\n      - Mexico\n      - Business Banking\n    properties:\n      - type: Documentation\n        url: https://www.bbvaapimarket.com/en/banking-apis/\n\n  - aid: bbva:locations\n\
  \    name: BBVA Locations API\n    description: >-\n      Open data API providing access to BBVA branch and ATM location data.\n      Available for Spain and Mexico, this API returns geolocation data, operating\n      hours, services available, and accessibility information for all BBVA branches\n      and ATMs.\n    humanURL: https://www.bbvaapimarket.com/en/banking-apis/\n    tags:\n      - Banking\n      - Open Data\n      - Locations\n    properties:\n      - type: Documentation\n        url: https://www.bbvaapimarket.com/en/banking-apis/\n\ncommon:\n  - type: Portal\n    url: https://www.bbvaapimarket.com/en/\n  - type: Website\n    url: https://www.bbva.com/\n  - type: Documentation\n    url: https://www.bbvaapimarket.com/en/api-developers/\n  - type: GettingStarted\n    url: https://www.bbvaapimarket.com/en/api-developers/\n  - type: Sandbox\n    url: https://www.bbvaapimarket.com/en/api-developers/\n  - type: TermsOfService\n    url: https://www.bbva.com/en/legal-notice/\n  - type:\
  \ PrivacyPolicy\n    url: https://www.bbva.com/en/privacy-policy/\n  - type: Blog\n    url: https://www.bbvaapimarket.com/en/api-world/\n  - type: SpectralRules\n    url: rules/bbva-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/bbva-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/open-banking.yaml\n  - type: JSON-LD\n    url: json-ld/bbva-context.jsonld\n  - type: Features\n    data:\n      - name: PSD2 Compliance\n        description: All European banking APIs are fully compliant with the PSD2 Payment Services Directive, including AIS and PIS services.\n      - name: Multi-Country Coverage\n        description: APIs available across 15+ countries including Spain, Mexico, Peru, Colombia, Argentina, Belgium, France, UK, Turkey, and USA.\n      - name: Treasury Management\n        description: Multi-country treasury APIs for global enterprises to manage payments, collections, and cash positions.\n      - name: Digital Ecosystems\n        description: APIs\
  \ enabling businesses to embed BBVA banking services into their own digital platforms and applications.\n      - name: Sandbox Environment\n        description: Developer sandbox environment for testing and validating API integrations before production deployment.\n      - name: Open Data APIs\n        description: Publicly accessible location and branch data APIs available without authentication for branch/ATM locators.\n  - type: UseCases\n    data:\n      - name: Account Aggregation\n        description: Build personal finance and wealth management apps that aggregate BBVA account data across accounts.\n      - name: Payment Initiation\n        description: Enable one-click checkout and payment initiation from customer bank accounts in Spain and other PSD2 markets.\n      - name: Treasury Automation\n        description: Automate corporate treasury operations including bulk payments, collections, and cash management across BBVA markets.\n      - name: Financial Data Analytics\n    \
  \    description: Access transaction and account data to power credit scoring, risk analysis, and financial advisory services.\n      - name: Branch Locator\n        description: Integrate BBVA branch and ATM location data into customer-facing applications using the open locations API.\n  - type: Integrations\n    data:\n      - name: Redsys\n        description: Spanish payment gateway and PSD2 infrastructure through which BBVA PSD2 APIs are registered and deployed.\n      - name: SEPA\n        description: Single Euro Payments Area integration for European payment transfers in Spain and EU markets.\n      - name: SPEI\n        description: Mexican interbank payment system integration for Mexico business payment APIs.\n      - name: SAP\n        description: ERP integration for treasury management customers connecting SAP financial systems with BBVA APIs.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bbva/refs/heads/main/apis.yml
tags:
- Banking
- Financial Services
- Open Banking
- PSD2
- Spain
- Mexico
url: https://raw.githubusercontent.com/api-evangelist/bbva/refs/heads/main/apis.yml
use_cases:
- description: Build personal finance and wealth management apps that aggregate BBVA account data across accounts.
  name: Account Aggregation
- description: Enable one-click checkout and payment initiation from customer bank accounts in Spain and other PSD2 markets.
  name: Payment Initiation
- description: Automate corporate treasury operations including bulk payments, collections, and cash management across BBVA markets.
  name: Treasury Automation
- description: Access transaction and account data to power credit scoring, risk analysis, and financial advisory services.
  name: Financial Data Analytics
- description: Integrate BBVA branch and ATM location data into customer-facing applications using the open locations API.
  name: Branch Locator
---
