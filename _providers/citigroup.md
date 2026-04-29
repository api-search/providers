---
api_count: 8
apis:
- description: 'The Citi Accounts and Transactions API provides authorized access to retail customer accounts, balances, and transaction histories. Authentication uses OAuth 2.0 access tokens issued through the Citi '
  name: Citi Accounts and Transactions API
  slug: citi-accounts-transactions-api
- description: The Citi Money Movement API enables authorized payment initiation from Citi accounts including domestic ACH, wire, and book transfers. Authentication uses OAuth 2.0 with strong customer authentication
  name: Citi Money Movement API
  slug: citi-money-movement-api
- description: The Citi Authorize API handles the OAuth 2.0 authorization-code and consent flows required for third-party applications to access a customer's Citi account data and initiate payments.
  name: Citi Authorize API
  slug: citi-authorize-api
- description: The Citi Customers API provides authorized access to customer profile information including contact details and demographic data for use in onboarding and KYC workflows.
  name: Citi Customers API
  slug: citi-customers-api
- description: The Citi Onboarding API enables digital account opening, document submission, and KYC workflows for onboarding new retail customers to Citi products.
  name: Citi Onboarding API
  slug: citi-onboarding-api
- description: The Citi Pay with Points API enables Citi cardholders to redeem ThankYou points and other rewards for purchases at merchant checkouts and inside partner applications.
  name: Citi Pay with Points API
  slug: citi-pay-with-points-api
- description: The Citi Utilities API provides reference data such as FX rates, branch and ATM locators, and cut-off times used to support transactional workflows across Citi's retail and commercial offerings.
  name: Citi Utilities API
  slug: citi-utilities-api
- description: CitiConnect is the corporate treasury and trade integration channel that exposes APIs for real-time payments, FX, statements, direct debits, faster payments, and proof-of-payment for enterprise client
  name: CitiConnect API
  slug: citiconnect-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.citigroup.com
- title: ''
  type: Portal
  url: https://developer.citi.com/
- title: ''
  type: Sandbox
  url: https://sandbox.developerhub.citi.com/
- title: ''
  type: API Catalog
  url: https://sandbox.developerhub.citi.com/api-catalog-list
- title: ''
  type: CitiConnect
  url: https://www.citigroup.com/global/insights/citiconnect-api-portal
- title: ''
  type: Documentation
  url: https://developer.citi.com/
- title: ''
  type: Investor Relations
  url: https://www.citigroup.com/global/investors
- title: ''
  type: Privacy Policy
  url: https://online.citi.com/US/JRS/pands/detail.do?ID=PrivacyTerms
- title: ''
  type: Terms of Service
  url: https://online.citi.com/US/JRS/pands/detail.do?ID=Terms
- title: ''
  type: Security
  url: https://online.citi.com/US/JRS/pands/detail.do?ID=PrivacyTerms
- title: ''
  type: Support
  url: https://online.citi.com/US/contactus.htm
- title: ''
  type: JSON-LD
  url: json-ld/citigroup-context.jsonld
- title: ''
  type: Spectral
  url: rules/citigroup-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/citigroup-capabilities.yml
created: '2026-03-23'
description: Citigroup is a global diversified financial services holding company providing consumers, corporations, governments, and institutions with a broad range of financial products and services. Citi exposes its API surface through the Citi Developer Hub, a unified developer portal spanning the bank's retail, commercial, and Treasury and Trade Solutions (TTS) lines of business. Major API domains include CitiConnect for corporate treasury, Accounts and Transactions for retail, Money Movement for payment initiation, Customer Onboarding, Authorization, and utilities for FX rates and reference data. Authentication uses OAuth 2.0 with mutual TLS for production endpoints.
features: []
image: ''
integrations: []
jsonld:
- class_count: 17
  name: Citigroup Context
  property_count: 0
  slug: citigroup-context
layout: provider
modified: '2026-04-23'
name: Citigroup
rules:
- name: Citigroup API Rules
  rule_count: 6
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 3
  slug: citigroup-rules
skills: []
slug: citigroup
solutions: []
source_filename: apis.yml
source_yaml: "aid: citigroup\nname: Citigroup\nurl: https://raw.githubusercontent.com/api-evangelist/citigroup/refs/heads/main/apis.yml\ncreated: '2026-03-23'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\ntags:\n  - Banking\n  - Financial Services\n  - FX\n  - Open Banking\n  - Payments\n  - Treasury\ndescription: >-\n  Citigroup is a global diversified financial services holding company\n  providing consumers, corporations, governments, and institutions with a\n  broad range of financial products and services. Citi exposes its API\n  surface through the Citi Developer Hub, a unified developer portal\n  spanning the bank's retail, commercial, and Treasury and Trade Solutions\n  (TTS) lines of business. Major API domains include CitiConnect for\n  corporate treasury, Accounts and Transactions for retail, Money Movement\n  for payment initiation, Customer Onboarding, Authorization, and\n  utilities for FX rates and reference data.\
  \ Authentication uses OAuth\n  2.0 with mutual TLS for production endpoints.\napis:\n  - aid: citigroup:citi-accounts-transactions-api\n    name: Citi Accounts and Transactions API\n    tags:\n      - Accounts\n      - Balances\n      - Banking\n      - Statements\n      - Transactions\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://sandbox.developerhub.citi.com/api/united-states/retail-bank/accounts/accounts-and-transactions/documentation\n    properties:\n      - url: https://sandbox.developerhub.citi.com/api/united-states/retail-bank/accounts/accounts-and-transactions/documentation\n        type: Documentation\n    description: >-\n      The Citi Accounts and Transactions API provides authorized access\n      to retail customer accounts, balances, and transaction histories.\n      Authentication uses OAuth 2.0 access tokens issued through the Citi\n      Developer Hub authorization flow.\n  - aid: citigroup:citi-money-movement-api\n\
  \    name: Citi Money Movement API\n    tags:\n      - ACH\n      - Money Movement\n      - Payment Initiation\n      - Payments\n      - Wire Transfer\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://sandbox.developerhub.citi.com/api-catalog-list\n    properties:\n      - url: https://sandbox.developerhub.citi.com/api-catalog-list\n        type: Documentation\n    description: >-\n      The Citi Money Movement API enables authorized payment initiation\n      from Citi accounts including domestic ACH, wire, and book transfers.\n      Authentication uses OAuth 2.0 with strong customer authentication\n      flows.\n  - aid: citigroup:citi-authorize-api\n    name: Citi Authorize API\n    tags:\n      - Authorization\n      - Consent\n      - OAuth\n      - SCA\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.citi.com/\n    properties:\n      - url: https://developer.citi.com/\n\
  \        type: Documentation\n    description: >-\n      The Citi Authorize API handles the OAuth 2.0 authorization-code\n      and consent flows required for third-party applications to access\n      a customer's Citi account data and initiate payments.\n  - aid: citigroup:citi-customers-api\n    name: Citi Customers API\n    tags:\n      - Customers\n      - Identity\n      - KYC\n      - Profiles\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.citi.com/\n    properties:\n      - url: https://developer.citi.com/\n        type: Documentation\n    description: >-\n      The Citi Customers API provides authorized access to customer\n      profile information including contact details and demographic\n      data for use in onboarding and KYC workflows.\n  - aid: citigroup:citi-onboarding-api\n    name: Citi Onboarding API\n    tags:\n      - Account Opening\n      - Customer Onboarding\n      - KYC\n      - Origination\n\
  \    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.citi.com/\n    properties:\n      - url: https://developer.citi.com/\n        type: Documentation\n    description: >-\n      The Citi Onboarding API enables digital account opening, document\n      submission, and KYC workflows for onboarding new retail customers\n      to Citi products.\n  - aid: citigroup:citi-pay-with-points-api\n    name: Citi Pay with Points API\n    tags:\n      - Loyalty\n      - Pay with Points\n      - Rewards\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.citi.com/\n    properties:\n      - url: https://developer.citi.com/\n        type: Documentation\n    description: >-\n      The Citi Pay with Points API enables Citi cardholders to redeem\n      ThankYou points and other rewards for purchases at merchant\n      checkouts and inside partner applications.\n  - aid: citigroup:citi-utilities-api\n\
  \    name: Citi Utilities API\n    tags:\n      - FX Rates\n      - Locator\n      - Reference Data\n      - Utilities\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.citi.com/\n    properties:\n      - url: https://developer.citi.com/\n        type: Documentation\n    description: >-\n      The Citi Utilities API provides reference data such as FX rates,\n      branch and ATM locators, and cut-off times used to support\n      transactional workflows across Citi's retail and commercial\n      offerings.\n  - aid: citigroup:citiconnect-api\n    name: CitiConnect API\n    tags:\n      - CitiConnect\n      - Corporate Banking\n      - ERP Integration\n      - Treasury\n      - TTS\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.citigroup.com/global/insights/citiconnect-api-portal\n    properties:\n      - url: https://www.citigroup.com/global/insights/citiconnect-api-portal\n\
  \        type: Documentation\n    description: >-\n      CitiConnect is the corporate treasury and trade integration\n      channel that exposes APIs for real-time payments, FX, statements,\n      direct debits, faster payments, and proof-of-payment for\n      enterprise clients connecting through ERP and TMS systems.\ncommon:\n  - type: Website\n    url: https://www.citigroup.com\n  - type: Portal\n    url: https://developer.citi.com/\n  - type: Sandbox\n    url: https://sandbox.developerhub.citi.com/\n  - type: API Catalog\n    url: https://sandbox.developerhub.citi.com/api-catalog-list\n  - type: CitiConnect\n    url: https://www.citigroup.com/global/insights/citiconnect-api-portal\n  - type: Documentation\n    url: https://developer.citi.com/\n  - type: Investor Relations\n    url: https://www.citigroup.com/global/investors\n  - type: Privacy Policy\n    url: https://online.citi.com/US/JRS/pands/detail.do?ID=PrivacyTerms\n  - type: Terms of Service\n    url: https://online.citi.com/US/JRS/pands/detail.do?ID=Terms\n\
  \  - type: Security\n    url: https://online.citi.com/US/JRS/pands/detail.do?ID=PrivacyTerms\n  - type: Support\n    url: https://online.citi.com/US/contactus.htm\n  - type: JSON-LD\n    url: json-ld/citigroup-context.jsonld\n  - type: Spectral\n    url: rules/citigroup-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/citigroup-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/citigroup/refs/heads/main/apis.yml
tags:
- Banking
- Financial Services
- FX
- Open Banking
- Payments
- Treasury
url: https://raw.githubusercontent.com/api-evangelist/citigroup/refs/heads/main/apis.yml
use_cases: []
---
