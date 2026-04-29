---
api_count: 6
api_specs:
- filename: chase-account-and-customer-information-api-openapi.yml
  format: yaml
  label: Chase Account and Customer Information API
  slug: account-and-customer-information-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/openapi/chase-account-and-customer-information-api-openapi.yml
- filename: chase-account-aggregation-user-consent-api-openapi.yml
  format: yaml
  label: Chase Account Aggregation User Consent API
  slug: account-aggregation-user-consent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/openapi/chase-account-aggregation-user-consent-api-openapi.yml
- filename: chase-rewards-balance-api-openapi.yml
  format: yaml
  label: Chase Rewards Balance API
  slug: rewards-balance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/openapi/chase-rewards-balance-api-openapi.yml
- filename: chase-loyalty-pay-with-points-order-service-api-openapi.yml
  format: yaml
  label: Chase Loyalty Pay with Points Order Service API
  slug: loyalty-pay-with-points-order-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/openapi/chase-loyalty-pay-with-points-order-service-api-openapi.yml
- filename: chase-loyalty-pay-with-points-enrollment-service-api-openapi.yml
  format: yaml
  label: Chase Loyalty Pay with Points Enrollment Service API
  slug: loyalty-pay-with-points-enrollment-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/openapi/chase-loyalty-pay-with-points-enrollment-service-api-openapi.yml
- filename: chase-loyalty-pci-merchant-relationship-manager-api-openapi.yml
  format: yaml
  label: Chase Loyalty PCI Merchant Relationship Manager API
  slug: loyalty-pci-merchant-relationship-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/openapi/chase-loyalty-pci-merchant-relationship-manager-api-openapi.yml
apis:
- description: FDX-aligned API that allows authorized data recipients to securely retrieve account and customer information for Chase customers. Supports account profiles, balances, transactions, statements, and cus
  name: Chase Account and Customer Information API
  slug: account-and-customer-information-api
- description: Consent management API used to obtain, store, and revoke customer consent for sharing account information with authorized third-party data recipients. Implements the FDX consent model.
  name: Chase Account Aggregation User Consent API
  slug: account-aggregation-user-consent-api
- description: API that allows merchant and partner systems to retrieve a Chase cardholder's current rewards points balance for use in loyalty experiences and Pay with Points checkouts.
  name: Chase Rewards Balance API
  slug: rewards-balance-api
- description: API that lets merchants accept Chase Ultimate Rewards points as payment at checkout. Supports order creation, redemption, capture, refund, and reversal flows for the Pay with Points program.
  name: Chase Loyalty Pay with Points Order Service API
  slug: loyalty-pay-with-points-order-service-api
- description: API that allows merchants and partners to enroll customer payment cards in the Chase Pay with Points program so points can be redeemed against future purchases.
  name: Chase Loyalty Pay with Points Enrollment Service API
  slug: loyalty-pay-with-points-enrollment-service-api
- description: API for managing PCI-compliant merchant relationships for the Chase loyalty platform, supporting onboarding, profile updates, and configuration of merchant integrations.
  name: Chase Loyalty PCI Merchant Relationship Manager API
  slug: loyalty-pci-merchant-relationship-manager-api
common:
- title: ''
  type: Website
  url: https://www.chase.com/
- title: ''
  type: DeveloperPortal
  url: https://developer.chase.com/
- title: ''
  type: Portal
  url: https://developer.chase.com/
- title: ''
  type: Demo
  url: https://apidemo.chase.com/
- title: ''
  type: FAQ
  url: https://developer.chase.com/support/faqs
- title: ''
  type: Glossary
  url: https://developer.chase.com/support/glossary/
- title: ''
  type: Support
  url: https://developer.chase.com/support
- title: ''
  type: TermsOfService
  url: https://developer.chase.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.chase.com/digital/resources/privacy-security
- title: ''
  type: JSONLD
  url: json-ld/chase-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/chase-account-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/chase-rewards-balance-schema.json
- title: ''
  type: Spectral
  url: spectral/chase-spectral.yml
- title: ''
  type: NaftikoCapabilities
  url: naftiko/chase-capabilities.yml
created: '2025-02-21'
description: JPMorgan Chase Bank, N.A. is a leading US financial institution providing consumer and commercial banking, credit cards, mortgages, and merchant services. The Chase Developer Portal exposes APIs for FDX-aligned account aggregation, customer consent, rewards balances, and the Loyalty Pay with Points platform that lets enrolled merchants and partners enable customers to redeem Ultimate Rewards points at checkout.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Chase Context
  property_count: 5
  slug: chase-context
layout: provider
modified: '2026-04-23'
name: Chase
skills: []
slug: chase
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: chase\nname: Chase\ndescription: >-\n  JPMorgan Chase Bank, N.A. is a leading US financial institution providing\n  consumer and commercial banking, credit cards, mortgages, and merchant\n  services. The Chase Developer Portal exposes APIs for FDX-aligned account\n  aggregation, customer consent, rewards balances, and the Loyalty Pay with\n  Points platform that lets enrolled merchants and partners enable customers\n  to redeem Ultimate Rewards points at checkout.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/apis.yml\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - Account Aggregation\n  - Banking\n  - Consent\n  - Credit Cards\n  - FDX\n  - Financial Services\n  - Loyalty\n  - Open Banking\n  - Pay with Points\n  - Rewards\ncreated: '2025-02-21'\nmodified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid: chase:account-and-customer-information-api\n\
  \    name: Chase Account and Customer Information API\n    description: >-\n      FDX-aligned API that allows authorized data recipients to securely\n      retrieve account and customer information for Chase customers.\n      Supports account profiles, balances, transactions, statements, and\n      customer details using OAuth 2.0 with FDX consent flows.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.chase.com/products/aggregation-fdx/\n    baseURL: https://api.chase.com/aggregation/fdx\n    tags:\n      - Account Aggregation\n      - FDX\n      - Open Banking\n    properties:\n      - type: Documentation\n        url: https://developer.chase.com/products/aggregation-fdx/guides/using-the-account-and-customer-information-api/\n      - type: OpenAPI\n        url: openapi/chase-account-and-customer-information-api-openapi.yml\n  - aid: chase:account-aggregation-user-consent-api\n    name: Chase Account Aggregation User\
  \ Consent API\n    description: >-\n      Consent management API used to obtain, store, and revoke customer\n      consent for sharing account information with authorized third-party\n      data recipients. Implements the FDX consent model.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.chase.com/products/aggregation-consent/\n    baseURL: https://api.chase.com/aggregation/consent\n    tags:\n      - Consent\n      - FDX\n      - Open Banking\n    properties:\n      - type: Documentation\n        url: https://developer.chase.com/products/aggregation-consent/\n      - type: OpenAPI\n        url: openapi/chase-account-aggregation-user-consent-api-openapi.yml\n  - aid: chase:rewards-balance-api\n    name: Chase Rewards Balance API\n    description: >-\n      API that allows merchant and partner systems to retrieve a Chase\n      cardholder's current rewards points balance for use in loyalty\n      experiences and Pay\
  \ with Points checkouts.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.chase.com/products/rewards-balance-api/\n    baseURL: https://api.chase.com/loyalty/rewards-balance\n    tags:\n      - Loyalty\n      - Rewards\n    properties:\n      - type: Documentation\n        url: https://developer.chase.com/products/rewards-balance-api/specification\n      - type: OpenAPI\n        url: openapi/chase-rewards-balance-api-openapi.yml\n  - aid: chase:loyalty-pay-with-points-order-service-api\n    name: Chase Loyalty Pay with Points Order Service API\n    description: >-\n      API that lets merchants accept Chase Ultimate Rewards points as\n      payment at checkout. Supports order creation, redemption, capture,\n      refund, and reversal flows for the Pay with Points program.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.chase.com/products/loyalty-pay-with-points-order-service/\n\
  \    baseURL: https://api.chase.com/loyalty/pay-with-points/orders\n    tags:\n      - Loyalty\n      - Payments\n      - Rewards\n    properties:\n      - type: Documentation\n        url: https://developer.chase.com/products/loyalty-pay-with-points-order-service/\n      - type: OpenAPI\n        url: openapi/chase-loyalty-pay-with-points-order-service-api-openapi.yml\n  - aid: chase:loyalty-pay-with-points-enrollment-service-api\n    name: Chase Loyalty Pay with Points Enrollment Service API\n    description: >-\n      API that allows merchants and partners to enroll customer payment\n      cards in the Chase Pay with Points program so points can be redeemed\n      against future purchases.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.chase.com/products/loyalty-pay-with-points-enrollment-service/\n    baseURL: https://api.chase.com/loyalty/pay-with-points/enrollment\n    tags:\n      - Loyalty\n      - Payments\n\
  \      - Rewards\n    properties:\n      - type: Documentation\n        url: https://developer.chase.com/products/loyalty-pay-with-points-enrollment-service/\n      - type: OpenAPI\n        url: openapi/chase-loyalty-pay-with-points-enrollment-service-api-openapi.yml\n  - aid: chase:loyalty-pci-merchant-relationship-manager-api\n    name: Chase Loyalty PCI Merchant Relationship Manager API\n    description: >-\n      API for managing PCI-compliant merchant relationships for the Chase\n      loyalty platform, supporting onboarding, profile updates, and\n      configuration of merchant integrations.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.chase.com/products/loyalty-pci-merchant-relation-manager/\n    baseURL: https://api.chase.com/loyalty/merchant-relationship-manager\n    tags:\n      - Loyalty\n      - Merchants\n      - PCI\n    properties:\n      - type: Documentation\n        url: https://developer.chase.com/products/loyalty-pci-merchant-relation-manager/\n\
  \      - type: OpenAPI\n        url: openapi/chase-loyalty-pci-merchant-relationship-manager-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.chase.com/\n  - type: DeveloperPortal\n    url: https://developer.chase.com/\n  - type: Portal\n    url: https://developer.chase.com/\n  - type: Demo\n    url: https://apidemo.chase.com/\n  - type: FAQ\n    url: https://developer.chase.com/support/faqs\n  - type: Glossary\n    url: https://developer.chase.com/support/glossary/\n  - type: Support\n    url: https://developer.chase.com/support\n  - type: TermsOfService\n    url: https://developer.chase.com/terms\n  - type: PrivacyPolicy\n    url: https://www.chase.com/digital/resources/privacy-security\n  - type: JSONLD\n    url: json-ld/chase-context.jsonld\n  - type: JSONSchema\n    url: json-schema/chase-account-schema.json\n  - type: JSONSchema\n    url: json-schema/chase-rewards-balance-schema.json\n  - type: Spectral\n    url: spectral/chase-spectral.yml\n  - type: NaftikoCapabilities\n\
  \    url: naftiko/chase-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/apis.yml
tags:
- Account Aggregation
- Banking
- Consent
- Credit Cards
- FDX
- Financial Services
- Loyalty
- Open Banking
- Pay with Points
- Rewards
url: https://raw.githubusercontent.com/api-evangelist/chase/refs/heads/main/apis.yml
use_cases: []
---
