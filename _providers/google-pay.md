---
api_count: 9
api_specs:
- filename: rest
  format: yaml
  label: Google Pay API
  slug: ''
  spec_type: OpenAPI
  url: https://developers.google.com/pay/api/web/reference/rest
- filename: v1
  format: yaml
  label: Google Wallet API
  slug: ''
  spec_type: OpenAPI
  url: https://developers.google.com/wallet/generic/rest/v1
apis:
- description: Enables integration of the Google Pay payment method into web applications, allowing merchants to accept payments from cards saved to Google Accounts. The API provides JavaScript client methods for im
  name: Google Pay API
  slug: ''
- description: Enables integration of Google Pay into Android applications, allowing users to pay with cards saved to their Google Account. The API provides methods to check payment readiness and load payment data f
  name: Google Pay API for Android
  slug: ''
- description: APIs for creating and managing digital passes for Google Wallet, including loyalty cards, event tickets, boarding passes, transit tickets, gift cards, offers, and generic passes. Issuers can define pa
  name: Google Wallet API
  slug: ''
- description: Provides services hosted by Google for processing facilitated payment events as part of Google Standard Payments. Payment integrators use this API to report and manage transaction events within the Go
  name: Google Pay Facilitated Transaction Event API
  slug: ''
- description: Enables payment integrators to enroll cards, retrieve virtual card numbers, manage transactions, and handle authentication challenges for virtual card payments. Used by issuers and payment service pro
  name: Google Pay Virtual Cards API
  slug: ''
- description: Allows card issuers to provision payment cards directly into Google Pay and Google Wallet from their own applications. Issuers can set default payment tokens, manage token lifecycle, and enable push p
  name: Google Pay Push Provisioning API
  slug: ''
- description: Enables Android applications to scan credit and debit cards using the device camera to extract card number and expiration date through on-device optical character recognition. Processing occurs entire
  name: Google Pay Payment Card Recognition API
  slug: ''
- description: A toolkit for developers in India to integrate their Android, iOS, and web applications with Google Pay for accepting UPI and card-based payments. Supports merchant onboarding, payment initiation, and
  name: Google Pay India Merchant SDK
  slug: ''
- description: A standard for securely and efficiently exchanging commerce data between merchant and platform systems to enable checkout experiences directly on Google surfaces including Search and Gemini. Merchants
  name: Google Universal Commerce Protocol
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developers.google.com/pay
- title: ''
  type: Brand Guidelines
  url: https://developers.google.com/pay/api/web/guides/brand-guidelines
- title: ''
  type: Terms of Service
  url: https://payments.developers.google.com/terms/sellertos
- title: ''
  type: Privacy Policy
  url: https://policies.google.com/privacy
- title: ''
  type: Getting Started
  url: https://developers.google.com/pay/api/web/guides/tutorial
- title: ''
  type: SDK
  url: https://developers.google.com/pay/api/web/guides/resources
- title: ''
  type: Console
  url: https://pay.google.com/business/console/
- title: ''
  type: Status
  url: https://developers.google.com/pay/api/status
- title: ''
  type: Support
  url: https://developers.google.com/pay/api/web/support
- title: ''
  type: Blog
  url: https://developers.googleblog.com/
- title: ''
  type: Change Log
  url: https://developers.google.com/pay/api/web/support/release-notes
- title: ''
  type: GitHub Organization
  url: https://github.com/google-pay
- title: ''
  type: FAQ
  url: https://developers.google.com/pay/api/web/support/faq
created: '2024-01-01'
description: Google Pay APIs enable payment processing and digital wallet functionality for apps and websites.
features: []
image: https://developers.google.com/pay/api/images/brand-guidelines/google-pay-mark.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Google Pay
skills: []
slug: google-pay
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-pay\nname: Google Pay\ndescription: >-\n  Google Pay APIs enable payment processing and digital wallet functionality for apps\n  and websites.\nimage: https://developers.google.com/pay/api/images/brand-guidelines/google-pay-mark.png\nurl: https://developers.google.com/pay/api\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Contactless Payments\n  - Digital Wallet\n  - Mobile Payments\n  - Payments\napis:\n  - name: Google Pay API\n    description: >-\n      Enables integration of the Google Pay payment method into web applications,\n      allowing merchants to accept payments from cards saved to Google Accounts.\n      The API provides JavaScript client methods for implementing a seamless\n      checkout experience on websites.\n    image: https://developers.google.com/pay/api/images/brand-guidelines/google-pay-mark.png\n    humanURL: https://developers.google.com/pay\n    baseURL: https://pay.google.com/gp/v/\n\
  \    tags:\n      - Checkout\n      - Payments\n      - Web\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/pay/api/web\n      - type: OpenAPI\n        url: https://developers.google.com/pay/api/web/reference/rest\n      - type: Authentication\n        url: https://developers.google.com/pay/api/web/guides/setup\n      - type: Errors\n        url: https://developers.google.com/pay/api/web/reference/error-codes\n      - type: Sandbox\n        url: https://developers.google.com/pay/api/web/guides/test-and-deploy/integration-checklist\n      - type: Reference\n        url: https://developers.google.com/pay/api/web/reference/client\n      - type: Getting Started\n        url: https://developers.google.com/pay/api/web/guides/tutorial\n      - type: Change Log\n        url: https://developers.google.com/pay/api/web/support/release-notes\n    contact:\n      - type: Support\n        url: https://developers.google.com/pay/api/web/support\n      - type:\
  \ Twitter\n        url: https://twitter.com/googlepay\n  - name: Google Pay API for Android\n    description: >-\n      Enables integration of Google Pay into Android applications, allowing users\n      to pay with cards saved to their Google Account. The API provides methods\n      to check payment readiness and load payment data for seamless in-app\n      checkout experiences.\n    image: https://developers.google.com/pay/api/images/brand-guidelines/google-pay-mark.png\n    humanURL: https://developers.google.com/pay/api/android/overview\n    baseURL: https://pay.google.com/gp/v/\n    tags:\n      - Android\n      - Checkout\n      - Mobile\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/pay/api/android/overview\n      - type: Reference\n        url: https://developers.google.com/pay/api/android/reference/client\n      - type: Getting Started\n        url: https://developers.google.com/pay/api/android/guides/tutorial\n     \
  \ - type: Authentication\n        url: https://developers.google.com/pay/api/android/guides/setup\n      - type: Change Log\n        url: https://developers.google.com/pay/api/android/support/release-notes\n      - type: Sandbox\n        url: https://developers.google.com/pay/api/android/guides/test-and-deploy/integration-checklist\n  - name: Google Wallet API\n    description: >-\n      APIs for creating and managing digital passes for Google Wallet, including\n      loyalty cards, event tickets, boarding passes, transit tickets, gift cards,\n      offers, and generic passes. Issuers can define pass classes and objects\n      via REST API or the Google Wallet Business Console.\n    image: https://developers.google.com/pay/api/images/brand-guidelines/google-pay-mark.png\n    humanURL: https://developers.google.com/wallet\n    baseURL: https://walletobjects.googleapis.com/\n    tags:\n      - Loyalty\n      - Passes\n      - Tickets\n      - Wallet\n    properties:\n      - type: Documentation\n\
  \        url: https://developers.google.com/wallet/generic/rest\n      - type: OpenAPI\n        url: https://developers.google.com/wallet/generic/rest/v1\n      - type: Authentication\n        url: https://developers.google.com/wallet/generic/rest/prerequisites\n      - type: Reference\n        url: https://developers.google.com/wallet/reference/rest\n      - type: Getting Started\n        url: https://developers.google.com/wallet/generic/getting-started/auth/rest\n      - type: Change Log\n        url: https://developers.google.com/wallet/docs/release-notes\n      - type: Client Libraries\n        url: https://developers.google.com/wallet/generic/resources/libraries\n  - name: Google Pay Facilitated Transaction Event API\n    description: >-\n      Provides services hosted by Google for processing facilitated payment\n      events as part of Google Standard Payments. Payment integrators use this\n      API to report and manage transaction events within the Google payments\n      ecosystem.\n\
  \    image: https://developers.google.com/pay/api/images/brand-guidelines/google-pay-mark.png\n    humanURL: https://developers.google.com/pay/facilitated-transaction-event-v2/concepts/intro\n    baseURL: https://pay.google.com/\n    tags:\n      - Payment Integrators\n      - Payments\n      - Transactions\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/pay/facilitated-transaction-event-v2/concepts/intro\n      - type: Reference\n        url: https://developers.google.com/pay/facilitated-transaction-event-v2/google-facilitated-transaction-event-api\n  - name: Google Pay Virtual Cards API\n    description: >-\n      Enables payment integrators to enroll cards, retrieve virtual card numbers,\n      manage transactions, and handle authentication challenges for virtual card\n      payments. Used by issuers and payment service providers to support virtual\n      card number generation and lifecycle management.\n    image: https://developers.google.com/pay/api/images/brand-guidelines/google-pay-mark.png\n\
  \    humanURL: https://developers.google.com/pay/virtual-cards-v1/payment-integrator-virtual-cards-api\n    baseURL: https://pay.google.com/\n    tags:\n      - Card Issuance\n      - Payments\n      - Virtual Cards\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/pay/virtual-cards-v1/payment-integrator-virtual-cards-api\n      - type: Reference\n        url: https://developers.google.com/pay/virtual-cards-v1/google-virtual-cards-api\n  - name: Google Pay Push Provisioning API\n    description: >-\n      Allows card issuers to provision payment cards directly into Google Pay\n      and Google Wallet from their own applications. Issuers can set default\n      payment tokens, manage token lifecycle, and enable push provisioning\n      flows for their cardholders.\n    image: https://developers.google.com/pay/api/images/brand-guidelines/google-pay-mark.png\n    humanURL: https://developers.google.com/pay/issuers/apis/push-provisioning/server\n    baseURL:\
  \ https://pay.google.com/\n    tags:\n      - Card Provisioning\n      - Issuers\n      - Payments\n      - Tokenization\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/pay/issuers/apis/push-provisioning/server\n      - type: Getting Started\n        url: https://developers.google.com/pay/issuers/overview/get-started\n  - name: Google Pay Payment Card Recognition API\n    description: >-\n      Enables Android applications to scan credit and debit cards using the\n      device camera to extract card number and expiration date through on-device\n      optical character recognition. Processing occurs entirely on-device via\n      Google Play Services without requiring camera permissions in the app.\n    image: https://developers.google.com/pay/api/images/brand-guidelines/google-pay-mark.png\n    humanURL: https://developers.google.com/pay/payment-card-recognition/debit-credit-card-recognition\n    baseURL: https://pay.google.com/\n    tags:\n   \
  \   - Android\n      - Card Recognition\n      - OCR\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/pay/payment-card-recognition/debit-credit-card-recognition\n  - name: Google Pay India Merchant SDK\n    description: >-\n      A toolkit for developers in India to integrate their Android, iOS, and web\n      applications with Google Pay for accepting UPI and card-based payments.\n      Supports merchant onboarding, payment initiation, and transaction status\n      verification through the Google Pay for Business program.\n    image: https://developers.google.com/pay/api/images/brand-guidelines/google-pay-mark.png\n    humanURL: https://developers.google.com/pay/india/api\n    baseURL: https://pay.google.com/\n    tags:\n      - India\n      - Merchant SDK\n      - Payments\n      - UPI\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/pay/india/api/merchant-sdk/guides/overview\n      -\
  \ type: Reference\n        url: https://developers.google.com/pay/india/api/merchant-sdk/reference/api\n      - type: Getting Started\n        url: https://developers.google.com/pay/india/api/merchant-sdk/guides/integration\n      - type: Authentication\n        url: https://developers.google.com/pay/india/api/merchant-sdk/guides/setup\n  - name: Google Universal Commerce Protocol\n    description: >-\n      A standard for securely and efficiently exchanging commerce data between\n      merchant and platform systems to enable checkout experiences directly on\n      Google surfaces including Search and Gemini. Merchants implement REST\n      endpoints for session creation, updates, and completion.\n    image: https://developers.google.com/pay/api/images/brand-guidelines/google-pay-mark.png\n    humanURL: https://developers.google.com/merchant/ucp\n    baseURL: https://pay.google.com/\n    tags:\n      - Agentic Commerce\n      - Checkout\n      - Commerce\n      - Merchants\n    properties:\n\
  \      - type: Documentation\n        url: https://developers.google.com/merchant/ucp/guides\n      - type: Getting Started\n        url: https://developers.google.com/pay/api/universal-commerce-protocol/overview\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://developers.google.com/pay\n  - type: Brand Guidelines\n    url: https://developers.google.com/pay/api/web/guides/brand-guidelines\n  - type: Terms of Service\n    url: https://payments.developers.google.com/terms/sellertos\n  - type: Privacy Policy\n    url: https://policies.google.com/privacy\n  - type: Getting Started\n    url: https://developers.google.com/pay/api/web/guides/tutorial\n  - type: SDK\n    url: https://developers.google.com/pay/api/web/guides/resources\n  - type: Console\n    url: https://pay.google.com/business/console/\n  - type: Status\n    url: https://developers.google.com/pay/api/status\n  - type: Support\n    url: https://developers.google.com/pay/api/web/support\n\
  \  - type: Blog\n    url: https://developers.googleblog.com/\n  - type: Change Log\n    url: https://developers.google.com/pay/api/web/support/release-notes\n  - type: GitHub Organization\n    url: https://github.com/google-pay\n  - type: FAQ\n    url: https://developers.google.com/pay/api/web/support/faq\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-pay/refs/heads/main/apis.yml
tags:
- Contactless Payments
- Digital Wallet
- Mobile Payments
- Payments
url: https://developers.google.com/pay/api
use_cases: []
---
