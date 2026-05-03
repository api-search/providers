---
api_count: 4
api_specs:
- filename: swift-swiftref-api-openapi.yml
  format: yaml
  label: SwiftRef API
  slug: swiftref-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swift/refs/heads/main/openapi/swift-swiftref-api-openapi.yml
apis:
- description: The SwiftRef API provides automated real-time lookup and validation of payments reference data including BICs, IBANs, LEIs, National IDs, country codes, and currency codes. Enables straight-through pr
  name: SwiftRef API
  slug: swiftref-api
- description: The SWIFT GPI (Global Payments Innovation) API enables financial institutions to track cross-border payment transactions in real time, update payment statuses, and manage stop-and-recall requests. Use
  name: SWIFT GPI API
  slug: swift-gpi-api
- description: The SWIFT Payment Pre-validation API allows financial institutions and PSPs to verify payment instruction data against reference data and counterparty information before executing a payment. Checks ac
  name: Payment Pre-validation API
  slug: payment-pre-validation-api
- description: The SWIFT Transaction Screening API enables financial institutions to submit transactions to the SWIFT Transaction Screening Service (TSS) for sanctions and compliance screening before processing. Ret
  name: Transaction Screening API
  slug: transaction-screening-api
capabilities:
- description: Unified payment validation capability combining the SWIFT SwiftRef reference data API. Enables payment operations teams and fintech developers to validate BICs, IBANs, LEIs, and routing codes before p
  name: SWIFT Payment Validation
  slug: payment-validation
common:
- title: ''
  type: Website
  url: https://www.swift.com
- title: ''
  type: DeveloperPortal
  url: https://developer.swift.com
- title: ''
  type: APIDocumentation
  url: https://developer.swift.com/apis
- title: ''
  type: APIReference
  url: https://developer.swift.com/reference
- title: ''
  type: GitHubOrganization
  url: https://github.com/swiftinc
- title: ''
  type: Sandbox
  url: https://sandbox.swift.com
- title: ''
  type: ProductPage
  url: https://www.swift.com/products/swift-apis
- title: ''
  type: Support
  url: https://www.swift.com/contact-us
- title: ''
  type: TermsOfService
  url: https://developer.swift.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.swift.com/privacy-legal
- title: ''
  type: ISO20022
  url: https://www.swift.com/standards/iso-20022
- title: ''
  type: SwiftRef
  url: https://www.swift.com/products/swiftref
- title: ''
  type: GPI
  url: https://www.swift.com/products/swift-gpi
- title: ''
  type: PostmanCollection
  url: https://www.postman.com/swift-developer-support/swift-api-sandbox-collections
- title: ''
  type: Login
  url: https://developer.swift.com/login
created: '2025-02-06'
description: SWIFT (Society for Worldwide Interbank Financial Telecommunication) is a global member-owned cooperative providing secure financial messaging services and reference data to financial institutions worldwide. SWIFT offers REST APIs for cross-border payment tracking (GPI), payment pre-validation, reference data lookup (SwiftRef), transaction screening, instant payments, and more. APIs use OAuth 2.0 authentication and are documented using OpenAPI 3.0.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 19
  name: Swift Context
  property_count: 1
  slug: swift-context
layout: provider
modified: '2026-05-03'
name: SWIFT
rules:
- name: SWIFT API Rules
  rule_count: 8
  severity_counts:
    error: 0
    hint: 1
    info: 0
    warn: 7
  slug: swift-rules
skills: []
slug: swift
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: swift\nname: SWIFT\ndescription: >-\n  SWIFT (Society for Worldwide Interbank Financial Telecommunication) is a\n  global member-owned cooperative providing secure financial messaging services\n  and reference data to financial institutions worldwide. SWIFT offers REST APIs\n  for cross-border payment tracking (GPI), payment pre-validation, reference\n  data lookup (SwiftRef), transaction screening, instant payments, and more.\n  APIs use OAuth 2.0 authentication and are documented using OpenAPI 3.0.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Banking\n  - Cross-Border Payments\n  - Financial Messaging\n  - Financial Services\n  - GPI\n  - ISO 20022\n  - Payments\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/swift/refs/heads/main/apis.yml\ncreated: '2025-02-06'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: swift:swiftref-api\n    name: SwiftRef API\n    description: >-\n\
  \      The SwiftRef API provides automated real-time lookup and validation of\n      payments reference data including BICs, IBANs, LEIs, National IDs,\n      country codes, and currency codes. Enables straight-through processing\n      by validating financial identifiers before payment execution.\n    humanURL: https://developer.swift.com/apis/swiftref-api\n    baseURL: https://api.swift.com/swiftrefdata\n    properties:\n      - type: Documentation\n        url: https://developer.swift.com/apis/swiftref-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/swift/refs/heads/main/openapi/swift-swiftref-api-openapi.yml\n    tags:\n      - BIC Validation\n      - Financial Reference Data\n      - IBAN Validation\n      - LEI Validation\n      - Reference Data\n      - SwiftRef\n\n  - aid: swift:swift-gpi-api\n    name: SWIFT GPI API\n    description: >-\n      The SWIFT GPI (Global Payments Innovation) API enables financial\n      institutions\
  \ to track cross-border payment transactions in real time,\n      update payment statuses, and manage stop-and-recall requests. Uses\n      Unique End-to-End Transaction Reference (UETR) for tracking. Requires\n      OAuth 2.0 authentication via JWT-Bearer grant type (RFC 7523).\n    humanURL: https://developer.swift.com/apis/gpi-apis\n    baseURL: https://api.swift.com/swift-apigateway\n    properties:\n      - type: Documentation\n        url: https://developer.swift.com/apis/gpi-apis\n    tags:\n      - Cross-Border Payments\n      - GPI\n      - ISO 20022\n      - Payment Tracking\n      - Payments\n      - UETR\n\n  - aid: swift:payment-pre-validation-api\n    name: Payment Pre-validation API\n    description: >-\n      The SWIFT Payment Pre-validation API allows financial institutions and\n      PSPs to verify payment instruction data against reference data and\n      counterparty information before executing a payment. Checks account\n      numbers, country codes, routing information,\
  \ and beneficiary account\n      validity to reduce failed payments.\n    humanURL: https://developer.swift.com/apis/payment-pre-validation-api\n    tags:\n      - Compliance\n      - Payment Pre-validation\n      - Payments\n      - Risk Management\n      - Straight-Through Processing\n    properties:\n      - type: Documentation\n        url: https://developer.swift.com/apis/payment-pre-validation-api\n      - type: ProductPage\n        url: https://www.swift.com/products/payment-pre-validation\n\n  - aid: swift:transaction-screening-api\n    name: Transaction Screening API\n    description: >-\n      The SWIFT Transaction Screening API enables financial institutions to\n      submit transactions to the SWIFT Transaction Screening Service (TSS)\n      for sanctions and compliance screening before processing. Returns\n      screening results with match details.\n    humanURL: https://developer.swift.com/\n    tags:\n      - AML\n      - Compliance\n      - Payments\n      - Sanctions\
  \ Screening\n      - Transaction Screening\n\ncommon:\n  - type: Website\n    url: https://www.swift.com\n  - type: DeveloperPortal\n    url: https://developer.swift.com\n  - type: APIDocumentation\n    url: https://developer.swift.com/apis\n  - type: APIReference\n    url: https://developer.swift.com/reference\n  - type: GitHubOrganization\n    url: https://github.com/swiftinc\n  - type: Sandbox\n    url: https://sandbox.swift.com\n  - type: ProductPage\n    url: https://www.swift.com/products/swift-apis\n  - type: Support\n    url: https://www.swift.com/contact-us\n  - type: TermsOfService\n    url: https://developer.swift.com/terms\n  - type: PrivacyPolicy\n    url: https://www.swift.com/privacy-legal\n  - type: ISO20022\n    url: https://www.swift.com/standards/iso-20022\n  - type: SwiftRef\n    url: https://www.swift.com/products/swiftref\n  - type: GPI\n    url: https://www.swift.com/products/swift-gpi\n  - type: PostmanCollection\n    url: https://www.postman.com/swift-developer-support/swift-api-sandbox-collections\n\
  \  - type: Login\n    url: https://developer.swift.com/login\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/swift/refs/heads/main/apis.yml
tags:
- Banking
- Cross-Border Payments
- Financial Messaging
- Financial Services
- GPI
- ISO 20022
- Payments
url: https://raw.githubusercontent.com/api-evangelist/swift/refs/heads/main/apis.yml
use_cases: []
---
