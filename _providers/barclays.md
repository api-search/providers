---
api_count: 23
apis:
- description: Barclays Smartpay Web Payment API enables businesses to accept payments on their website with real-time processing, secure encryption, and fraud prevention.
  name: Barclays Smartpay Web Payment API
  slug: barclaycard-smartpay-web-payment-api
- description: Verify the availability of funds in a Barclays Bank Ireland account in real-time.
  name: Barclays Bank Ireland Confirmation of Funds API
  slug: barclays-bank-ireland-confirmation-of-funds-api
- description: Access and manage account information and transaction history through UK Open Banking standards.
  name: Barclays Account and Transactions API
  slug: account-and-transactions-api
- description: Securely access and retrieve account information from Barclays Bank Ireland accounts.
  name: Barclays Bank Ireland Account Information API
  slug: barclays-bank-ireland-account-information-api
- description: Initiate payments from Barclays Bank Ireland accounts via PSD2-compliant API.
  name: Barclays Bank Ireland Payment Initiation API
  slug: barclays-bank-ireland-payment-initiation-api
- description: Verify the availability of funds in a Barclays account in real-time.
  name: Barclays Confirmation of Funds API
  slug: confirmation-of-funds-api
- description: Manage customer consent for third-party access to Barclays account data.
  name: Barclays Consent API
  slug: consent-api
- description: Programmatically register TPP client applications with Barclays for Open Banking access.
  name: Barclays Dynamic Client Registration API
  slug: dynamic-client-registration-api
- description: Receive real-time webhook notifications for account and transaction events.
  name: Barclays Event Notification API
  slug: event-notification-api
- description: Securely initiate and authorize payments from Barclays accounts via Open Banking.
  name: Barclays Payment Initiation API
  slug: payment-initiation-api
- description: Find the nearest Barclays ATMs with details on available services and operating hours.
  name: Barclays ATM Locator API
  slug: atm-locator-api
- description: Find Barclays bank branches with addresses, phone numbers, and operating hours.
  name: Barclays Branch Locator API
  slug: branch-locator-api
- description: Access Barclays FCA-mandated service performance metrics data.
  name: Barclays FCA Service Metrics API
  slug: fca-service-metrics-api
- description: Access detailed information about Barclays banking products including rates, fees, and eligibility.
  name: Barclays Product Details API
  slug: product-details-api
- description: Access and manage Barclays account information via Open Banking standards.
  name: Barclays Accounts API
  slug: accounts-api
- description: Secure OAuth2 authentication for accessing Barclays Open Banking APIs.
  name: Barclays Authentication API
  slug: authentication-api
- description: Integrate credit card application functionality with real-time status updates.
  name: Barclays Card Application API
  slug: card-application-api
- description: Secure cryptographic key exchange for encrypted API communication with Barclays.
  name: Barclays Cryptography Key Exchange API
  slug: cryptography-key-exchange-api
- description: Integrate digital wallet functionality for mobile payments and account management.
  name: Barclays Digital Wallet API
  slug: digital-wallet-api
- description: Securely make and receive payments with fraud detection and real-time tracking.
  name: Barclays Payments API
  slug: payments-api
- description: Integrate loyalty programs and sync rewards data with Barclays customer accounts.
  name: Barclays Rewards Loyalty Sync API
  slug: rewards-loyalty-sync-api
- description: Enable customers to pay with Barclays Rewards points at merchant point-of-sale.
  name: Barclays Rewards Pay with Points API
  slug: rewards-pay-with-points-api
- description: Access detailed transaction history and spending analytics for Barclays accounts.
  name: Barclays Transactions API
  slug: transactions-api
capabilities:
- description: ''
  name: Open Banking
  slug: open-banking
common:
- title: ''
  type: Portal
  url: https://developer.barclays.com/
- title: ''
  type: Documentation
  url: https://developer.barclays.com/catalogue
- title: ''
  type: Support
  url: https://developer.barclays.com/support/help-guides
- title: ''
  type: Login
  url: https://developer.barclays.com/login
- title: ''
  type: SignUp
  url: https://drm.developer.barclays.com/s/registration
- title: ''
  type: Knowledgebase
  url: https://developer.barclays.com/support/knowledge-base
- title: ''
  type: TermsOfService
  url: https://developer.barclays.com/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://developer.barclays.com/privacy-policy
- title: ''
  type: SpectralRules
  url: rules/barclays-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/barclays-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/open-banking.yaml
- title: ''
  type: JSON-LD
  url: json-ld/barclays-context.jsonld
created: '2025-02-21'
description: Barclays is a multinational financial services company providing retail and commercial banking, investment banking, wealth management, and credit cards. The Barclays API Exchange (developer.barclays.com) offers 22+ APIs covering open banking account information, payment initiation, confirmation of funds, ATM/branch location, rewards, digital wallet, and more, compliant with UK Open Banking and EU PSD2 standards.
features:
- description: PSD2 and UK Open Banking compliant account balance and transaction access.
  name: Open Banking Account Information
- description: Secure third-party payment initiation from customer accounts.
  name: Payment Initiation
- description: Real-time verification of available funds for payment authorization.
  name: Confirmation of Funds
- description: Location services for Barclays ATMs and branches worldwide.
  name: ATM and Branch Locator
- description: Real-time webhook notifications for account and transaction events.
  name: Event Notifications
- description: Automated TPP registration for Open Banking API access.
  name: Dynamic Client Registration
- description: Loyalty program integration and pay-with-points capabilities.
  name: Rewards and Loyalty
- description: Mobile payment and digital wallet integration.
  name: Digital Wallet
- description: Credit card application submission and status tracking.
  name: Card Applications
- description: Mandated service performance metrics for regulatory reporting.
  name: FCA Compliance Metrics
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 2
  name: Barclays Context
  property_count: 17
  slug: barclays-context
layout: provider
modified: '2026-04-21'
name: Barclays
rules:
- name: Barclays API Rules
  rule_count: 7
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 1
  slug: barclays-spectral-rules
skills: []
slug: barclays
solutions: []
source_filename: apis.yml
source_yaml: "aid: barclays\nurl: https://raw.githubusercontent.com/api-evangelist/barclays/refs/heads/main/apis.yml\nname: Barclays\ntags:\n  - Banking\n  - Credit Cards\n  - Finance\n  - Open Banking\n  - Payments\n  - PSD2\n  - UK Banking\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-21'\nmodified: '2026-04-21'\nposition: Consumer\ndescription: >-\n  Barclays is a multinational financial services company providing retail and commercial\n  banking, investment banking, wealth management, and credit cards. The Barclays API Exchange\n  (developer.barclays.com) offers 22+ APIs covering open banking account information, payment\n  initiation, confirmation of funds, ATM/branch location, rewards, digital wallet, and more,\n  compliant with UK Open Banking and EU PSD2 standards.\napis:\n  - aid: barclays:barclaycard-smartpay-web-payment-api\n    name: Barclays Smartpay Web Payment API\n    tags:\n      - E-Commerce\n\
  \      - Payments\n      - Smartpay\n    humanURL: https://developer.barclays.com/apis/barclaycard-smartpay-web-payment/b82fda37-a434-4cc3-abde-0c6ba126fd2e.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/barclaycard-smartpay-web-payment/b82fda37-a434-4cc3-abde-0c6ba126fd2e.bdn/documentation\n        type: Documentation\n    description: >-\n      Barclays Smartpay Web Payment API enables businesses to accept payments on their\n      website with real-time processing, secure encryption, and fraud prevention.\n  - aid: barclays:barclays-bank-ireland-confirmation-of-funds-api\n    name: Barclays Bank Ireland Confirmation of Funds API\n    tags:\n      - Confirmation of Funds\n      - Ireland\n      - Open Banking\n      - PSD2\n    humanURL: https://developer.barclays.com/apis/barclays-bank-ireland-confirmation-of-funds/8cd8be1f-4bdc-45fe-8fef-c7a569cfe603.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/barclays-bank-ireland-confirmation-of-funds/8cd8be1f-4bdc-45fe-8fef-c7a569cfe603.bdn/documentation\n\
  \        type: Documentation\n    description: Verify the availability of funds in a Barclays Bank Ireland account in real-time.\n  - aid: barclays:account-and-transactions-api\n    name: Barclays Account and Transactions API\n    tags:\n      - Accounts\n      - Open Banking\n      - Transactions\n    humanURL: https://developer.barclays.com/apis/account-and-transactions/20e74071-13fb-44eb-b98f-2c89d6251ad8.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/account-and-transactions/20e74071-13fb-44eb-b98f-2c89d6251ad8.bdn/documentation\n        type: Documentation\n    description: Access and manage account information and transaction history through UK Open Banking standards.\n  - aid: barclays:barclays-bank-ireland-account-information-api\n    name: Barclays Bank Ireland Account Information API\n    tags:\n      - Accounts\n      - Ireland\n      - Open Banking\n      - PSD2\n    humanURL: https://developer.barclays.com/apis/barclays-bank-ireland-account-information/696e2ef6-255f-481c-9546-4b5bda44b2e4.bdn/documentation\n\
  \    properties:\n      - url: https://developer.barclays.com/apis/barclays-bank-ireland-account-information/696e2ef6-255f-481c-9546-4b5bda44b2e4.bdn/documentation\n        type: Documentation\n    description: Securely access and retrieve account information from Barclays Bank Ireland accounts.\n  - aid: barclays:barclays-bank-ireland-payment-initiation-api\n    name: Barclays Bank Ireland Payment Initiation API\n    tags:\n      - Ireland\n      - Open Banking\n      - Payment Initiation\n      - PSD2\n    humanURL: https://developer.barclays.com/apis/barclays-bank-ireland-payment-initiation/d41f070a-3b3b-4f2d-b28a-6afdc690a42d.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/barclays-bank-ireland-payment-initiation/d41f070a-3b3b-4f2d-b28a-6afdc690a42d.bdn/documentation\n        type: Documentation\n    description: Initiate payments from Barclays Bank Ireland accounts via PSD2-compliant API.\n  - aid: barclays:confirmation-of-funds-api\n    name:\
  \ Barclays Confirmation of Funds API\n    tags:\n      - Confirmation of Funds\n      - Open Banking\n    humanURL: https://developer.barclays.com/apis/confirmation-of-funds/1c914db2-e592-4e5c-89c8-7b9e76d53303.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/confirmation-of-funds/1c914db2-e592-4e5c-89c8-7b9e76d53303.bdn/documentation\n        type: Documentation\n    description: Verify the availability of funds in a Barclays account in real-time.\n  - aid: barclays:consent-api\n    name: Barclays Consent API\n    tags:\n      - Consent\n      - Open Banking\n      - Privacy\n    humanURL: https://developer.barclays.com/apis/consent/41fde785-67a0-47e6-9a34-263d22a08028.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/consent/41fde785-67a0-47e6-9a34-263d22a08028.bdn/documentation\n        type: Documentation\n    description: Manage customer consent for third-party access to Barclays account data.\n  - aid: barclays:dynamic-client-registration-api\n\
  \    name: Barclays Dynamic Client Registration API\n    tags:\n      - Client Registration\n      - Open Banking\n      - Security\n    humanURL: https://developer.barclays.com/apis/dynamic-client-registration/ace18310-2523-49f0-a66d-4c6e37aae59f.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/dynamic-client-registration/ace18310-2523-49f0-a66d-4c6e37aae59f.bdn/documentation\n        type: Documentation\n    description: Programmatically register TPP client applications with Barclays for Open Banking access.\n  - aid: barclays:event-notification-api\n    name: Barclays Event Notification API\n    tags:\n      - Events\n      - Notifications\n      - Open Banking\n      - Webhooks\n    humanURL: https://developer.barclays.com/apis/event-notification/d71a398f-620b-4a65-8b85-382ca1eb7ede.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/event-notification/d71a398f-620b-4a65-8b85-382ca1eb7ede.bdn/documentation\n     \
  \   type: Documentation\n    description: Receive real-time webhook notifications for account and transaction events.\n  - aid: barclays:payment-initiation-api\n    name: Barclays Payment Initiation API\n    tags:\n      - Open Banking\n      - Payment Initiation\n      - Payments\n    humanURL: https://developer.barclays.com/apis/payment-initiation/1f6ad5c5-e397-41c0-8d3b-c35446491402.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/payment-initiation/1f6ad5c5-e397-41c0-8d3b-c35446491402.bdn/documentation\n        type: Documentation\n    description: Securely initiate and authorize payments from Barclays accounts via Open Banking.\n  - aid: barclays:atm-locator-api\n    name: Barclays ATM Locator API\n    tags:\n      - ATM\n      - Location\n      - Branch Finder\n    humanURL: https://developer.barclays.com/apis/atm-locator/c9e28aaa-51a1-4c9b-b8d4-f2b7ac090aa7.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/atm-locator/c9e28aaa-51a1-4c9b-b8d4-f2b7ac090aa7.bdn/documentation\n\
  \        type: Documentation\n    description: Find the nearest Barclays ATMs with details on available services and operating hours.\n  - aid: barclays:branch-locator-api\n    name: Barclays Branch Locator API\n    tags:\n      - Branch Finder\n      - Location\n    humanURL: https://developer.barclays.com/apis/branch-locator/d9b83b29-42e2-4cb3-ad8f-100d2c9a6314.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/branch-locator/d9b83b29-42e2-4cb3-ad8f-100d2c9a6314.bdn/documentation\n        type: Documentation\n    description: Find Barclays bank branches with addresses, phone numbers, and operating hours.\n  - aid: barclays:fca-service-metrics-api\n    name: Barclays FCA Service Metrics API\n    tags:\n      - Compliance\n      - FCA\n      - Metrics\n      - Regulatory\n    humanURL: https://developer.barclays.com/apis/fca-service-metrics/59f96026-03d6-4c4e-9567-c3db4dd83e3a.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/fca-service-metrics/59f96026-03d6-4c4e-9567-c3db4dd83e3a.bdn/documentation\n\
  \        type: Documentation\n    description: Access Barclays FCA-mandated service performance metrics data.\n  - aid: barclays:product-details-api\n    name: Barclays Product Details API\n    tags:\n      - Open Banking\n      - Products\n    humanURL: https://developer.barclays.com/apis/product-details/436bee89-6e7e-4f54-9cd9-e9dc6cb90d8f.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/product-details/436bee89-6e7e-4f54-9cd9-e9dc6cb90d8f.bdn/documentation\n        type: Documentation\n    description: Access detailed information about Barclays banking products including rates, fees, and eligibility.\n  - aid: barclays:accounts-api\n    name: Barclays Accounts API\n    tags:\n      - Accounts\n      - Open Banking\n    humanURL: https://developer.barclays.com/apis/accounts/097976bb-311e-4bb1-89b1-c81e2f1de572.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/accounts/097976bb-311e-4bb1-89b1-c81e2f1de572.bdn/documentation\n\
  \        type: Documentation\n    description: Access and manage Barclays account information via Open Banking standards.\n  - aid: barclays:authentication-api\n    name: Barclays Authentication API\n    tags:\n      - Authentication\n      - OAuth\n      - Security\n    humanURL: https://developer.barclays.com/apis/authentication/4f4800dd-6a0f-42fe-b6da-5cb2ba8891f5.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/authentication/4f4800dd-6a0f-42fe-b6da-5cb2ba8891f5.bdn/documentation\n        type: Documentation\n    description: Secure OAuth2 authentication for accessing Barclays Open Banking APIs.\n  - aid: barclays:card-application-api\n    name: Barclays Card Application API\n    tags:\n      - Card Applications\n      - Credit Cards\n    humanURL: https://developer.barclays.com/apis/card-application/372df8da-72cb-4fe5-b4fb-7e0bcaac7d20.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/card-application/372df8da-72cb-4fe5-b4fb-7e0bcaac7d20.bdn/documentation\n\
  \        type: Documentation\n    description: Integrate credit card application functionality with real-time status updates.\n  - aid: barclays:cryptography-key-exchange-api\n    name: Barclays Cryptography Key Exchange API\n    tags:\n      - Cryptography\n      - Security\n    humanURL: https://developer.barclays.com/apis/cryptography-key-exchange/15f2194b-7bda-4e81-b90e-f671efbc28c1.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/cryptography-key-exchange/15f2194b-7bda-4e81-b90e-f671efbc28c1.bdn/documentation\n        type: Documentation\n    description: Secure cryptographic key exchange for encrypted API communication with Barclays.\n  - aid: barclays:digital-wallet-api\n    name: Barclays Digital Wallet API\n    tags:\n      - Digital Wallet\n      - Mobile Payments\n      - Payments\n    humanURL: https://developer.barclays.com/apis/digital-wallet/b55293c3-316f-4932-8ac6-b4e94641382a.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/digital-wallet/b55293c3-316f-4932-8ac6-b4e94641382a.bdn/documentation\n\
  \        type: Documentation\n    description: Integrate digital wallet functionality for mobile payments and account management.\n  - aid: barclays:payments-api\n    name: Barclays Payments API\n    tags:\n      - Payments\n    humanURL: https://developer.barclays.com/apis/payments/5286713c-e65f-4c16-aceb-493115142bea.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/payments/5286713c-e65f-4c16-aceb-493115142bea.bdn/documentation\n        type: Documentation\n    description: Securely make and receive payments with fraud detection and real-time tracking.\n  - aid: barclays:rewards-loyalty-sync-api\n    name: Barclays Rewards Loyalty Sync API\n    tags:\n      - Loyalty\n      - Rewards\n    humanURL: https://developer.barclays.com/apis/rewards-loyalty-sync/52e2b51b-9937-4f12-901b-3275b0aeb2a8.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/rewards-loyalty-sync/52e2b51b-9937-4f12-901b-3275b0aeb2a8.bdn/documentation\n\
  \        type: Documentation\n    description: Integrate loyalty programs and sync rewards data with Barclays customer accounts.\n  - aid: barclays:rewards-pay-with-points-api\n    name: Barclays Rewards Pay with Points API\n    tags:\n      - Loyalty\n      - Rewards\n    humanURL: https://developer.barclays.com/apis/rewards-pay-with-points/1941d4a3-35e3-462c-a209-34101c518b7f.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/rewards-pay-with-points/1941d4a3-35e3-462c-a209-34101c518b7f.bdn/documentation\n        type: Documentation\n    description: Enable customers to pay with Barclays Rewards points at merchant point-of-sale.\n  - aid: barclays:transactions-api\n    name: Barclays Transactions API\n    tags:\n      - Open Banking\n      - Transactions\n    humanURL: https://developer.barclays.com/apis/transactions/b3b4410d-56a7-403c-863c-3af1e939f1c2.bdn/documentation\n    properties:\n      - url: https://developer.barclays.com/apis/transactions/b3b4410d-56a7-403c-863c-3af1e939f1c2.bdn/documentation\n\
  \        type: Documentation\n    description: Access detailed transaction history and spending analytics for Barclays accounts.\ncommon:\n  - url: https://developer.barclays.com/\n    name: Barclays API Exchange\n    type: Portal\n  - url: https://developer.barclays.com/catalogue\n    name: API Catalogue\n    type: Documentation\n  - url: https://developer.barclays.com/support/help-guides\n    name: Help Guides\n    type: Support\n  - url: https://developer.barclays.com/login\n    name: Login\n    type: Login\n  - url: https://drm.developer.barclays.com/s/registration\n    name: Registration\n    type: SignUp\n  - url: https://developer.barclays.com/support/knowledge-base\n    name: Knowledge Base\n    type: Knowledgebase\n  - url: https://developer.barclays.com/terms-of-use\n    name: Terms of Use\n    type: TermsOfService\n  - url: https://developer.barclays.com/privacy-policy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - type: SpectralRules\n    url: rules/barclays-spectral-rules.yml\n\
  \  - type: Vocabulary\n    url: vocabulary/barclays-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/open-banking.yaml\n  - type: JSON-LD\n    url: json-ld/barclays-context.jsonld\n  - name: Features\n    type: Features\n    data:\n      - name: Open Banking Account Information\n        description: PSD2 and UK Open Banking compliant account balance and transaction access.\n      - name: Payment Initiation\n        description: Secure third-party payment initiation from customer accounts.\n      - name: Confirmation of Funds\n        description: Real-time verification of available funds for payment authorization.\n      - name: ATM and Branch Locator\n        description: Location services for Barclays ATMs and branches worldwide.\n      - name: Event Notifications\n        description: Real-time webhook notifications for account and transaction events.\n      - name: Dynamic Client Registration\n        description: Automated TPP registration for Open Banking API access.\n\
  \      - name: Rewards and Loyalty\n        description: Loyalty program integration and pay-with-points capabilities.\n      - name: Digital Wallet\n        description: Mobile payment and digital wallet integration.\n      - name: Card Applications\n        description: Credit card application submission and status tracking.\n      - name: FCA Compliance Metrics\n        description: Mandated service performance metrics for regulatory reporting.\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: Personal Finance Management\n        description: Aggregate Barclays account data in budgeting and financial planning apps.\n      - name: Open Banking Payments\n        description: Initiate payments directly from customer bank accounts via PSD2.\n      - name: E-Commerce Checkout\n        description: Accept Barclays-branded payments via Smartpay Web Payment API.\n      - name: Branch and ATM Finder\n        description: Embed ATM and branch location search in apps and websites.\n\
  \      - name: Loyalty Integration\n        description: Integrate Barclays Rewards with merchant loyalty programs.\n      - name: Credit Card Origination\n        description: Enable online credit card applications through partner platforms.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/barclays/refs/heads/main/apis.yml
tags:
- Banking
- Credit Cards
- Finance
- Open Banking
- Payments
- PSD2
- UK Banking
url: https://raw.githubusercontent.com/api-evangelist/barclays/refs/heads/main/apis.yml
use_cases:
- description: Aggregate Barclays account data in budgeting and financial planning apps.
  name: Personal Finance Management
- description: Initiate payments directly from customer bank accounts via PSD2.
  name: Open Banking Payments
- description: Accept Barclays-branded payments via Smartpay Web Payment API.
  name: E-Commerce Checkout
- description: Embed ATM and branch location search in apps and websites.
  name: Branch and ATM Finder
- description: Integrate Barclays Rewards with merchant loyalty programs.
  name: Loyalty Integration
- description: Enable online credit card applications through partner platforms.
  name: Credit Card Origination
---
