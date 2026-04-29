---
api_count: 3
apis:
- description: Server-side REST API for Apple Pay on the Web, enabling merchants to validate their identity with Apple and obtain payment sessions used by the ApplePaySession JavaScript API in Safari. Supports Touch
  name: Apple Pay JS API
  slug: ''
- description: Native iOS, watchOS, and macOS framework for integrating Apple Pay into mobile and desktop applications. Provides PKPaymentRequest and PKPaymentAuthorizationViewController for in-app Apple Pay checkou
  name: PassKit Framework (Apple Pay)
  slug: ''
- description: Server-side specification for processing and decrypting Apple Pay payment tokens received from client applications. Tokens use EC_v1 or RSA_v1 encryption and contain the payment authorization data for
  name: Apple Pay Payment Token API
  slug: ''
capabilities:
- description: Workflow capability for integrating Apple Pay into e-commerce and mobile payment flows. Combines merchant validation, payment session management, and payment token processing into a unified workflow f
  name: Apple Pay Payment Processing
  slug: payment-processing
common:
- title: ''
  type: Portal
  url: https://developer.apple.com/account/
- title: ''
  type: Support
  url: https://developer.apple.com/support/apple-pay/
- title: ''
  type: TermsOfService
  url: https://developer.apple.com/apple-pay/acceptable-use-guidelines/
- title: ''
  type: GettingStarted
  url: https://developer.apple.com/apple-pay/get-started/
- title: ''
  type: Branding
  url: https://developer.apple.com/apple-pay/marketing/
- title: ''
  type: StatusPage
  url: https://developer.apple.com/system-status/
- title: ''
  type: JSONLD
  url: json-ld/apple-pay-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/apple-pay-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apple-pay-vocabulary.yaml
- title: Apple Pay JS Shared Capability
  type: NaftikoCapability
  url: capabilities/shared/apple-pay-js.yaml
- title: Payment Processing Workflow
  type: NaftikoCapability
  url: capabilities/payment-processing.yaml
created: '2024-01-01'
description: Apple Pay enables secure, frictionless payments in apps and on the web using the payment cards stored in users' Apple Wallet. It supports Touch ID, Face ID, and Apple Watch authentication for both in-person and online payments. Apple Pay is available on iOS, watchOS, macOS, and via Safari on the web through the Apple Pay JS API, with a PassKit native framework for iOS/watchOS app integration.
features:
- description: Users authorize payments using biometric authentication on Apple devices
  name: Touch ID and Face ID Authentication
- description: Native iOS and watchOS integration via PassKit framework
  name: In-App Payments
- description: Safari-based Apple Pay checkout via the ApplePaySession JavaScript API
  name: Web Payments
- description: Contactless payments from Apple Watch without needing iPhone
  name: Apple Watch Support
- description: Supports Visa, Mastercard, Amex, Discover, JCB, UnionPay, and more
  name: Multiple Card Networks
- description: Domain verification ensures only registered merchants can use Apple Pay
  name: Merchant Domain Verification
- description: Subscription and automatic payment support via automatic payment requests
  name: Recurring Payments
- description: Support for deferred billing like hotel deposits and pre-orders
  name: Deferred Payments
image: https://developer.apple.com/assets/elements/icons/apple-pay/apple-pay-96x96.png
integrations:
- description: Stripe Elements and Stripe.js support Apple Pay via the Payment Request Button
  name: Stripe
- description: PayPal's Braintree SDK provides Apple Pay integration for iOS and web
  name: Braintree
- description: Square's iOS SDK supports Apple Pay for in-app and contactless payments
  name: Square
- description: Adyen payment platform supports Apple Pay for web and mobile checkout
  name: Adyen
- description: Shopify natively supports Apple Pay for accelerated checkout
  name: Shopify
- description: WooCommerce Stripe plugin enables Apple Pay on WordPress stores
  name: WooCommerce
jsonld:
- class_count: 0
  name: Apple Pay Context
  property_count: 10
  slug: apple-pay-context
layout: provider
modified: '2026-04-19'
name: Apple Pay
rules:
- name: Apple Pay API Rules
  rule_count: 24
  severity_counts:
    error: 10
    hint: 0
    info: 2
    warn: 12
  slug: apple-pay-spectral-rules
skills: []
slug: apple-pay
solutions: []
source_yaml: "name: Apple Pay\ndescription: >-\n  Apple Pay enables secure, frictionless payments in apps and on the web using the\n  payment cards stored in users' Apple Wallet. It supports Touch ID, Face ID, and\n  Apple Watch authentication for both in-person and online payments. Apple Pay is\n  available on iOS, watchOS, macOS, and via Safari on the web through the Apple Pay\n  JS API, with a PassKit native framework for iOS/watchOS app integration.\nimage: https://developer.apple.com/assets/elements/icons/apple-pay/apple-pay-96x96.png\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nurl: https://developer.apple.com/apple-pay/\nspecificationVersion: '0.18'\ntags:\n  - Apple\n  - Contactless Payments\n  - Digital Wallet\n  - E-Commerce\n  - Mobile Payments\n  - Payments\napis:\n  - name: Apple Pay JS API\n    description: >-\n      Server-side REST API for Apple Pay on the Web, enabling merchants to validate\n      their identity with Apple and obtain payment sessions used by the ApplePaySession\n\
  \      JavaScript API in Safari. Supports Touch ID and Face ID for frictionless web checkout.\n    image: https://developer.apple.com/assets/elements/icons/apple-pay/apple-pay-96x96.png\n    humanURL: https://developer.apple.com/documentation/apple_pay_on_the_web\n    baseURL: https://apple-pay-gateway.apple.com\n    tags:\n      - Javascript\n      - Safari\n      - Web Payments\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/apple_pay_on_the_web\n      - type: GettingStarted\n        url: https://developer.apple.com/apple-pay/implementation/\n      - type: APIReference\n        url: https://developer.apple.com/documentation/apple_pay_on_the_web/applepaypaymentrequest\n      - type: Sandbox\n        url: https://developer.apple.com/apple-pay/sandbox-testing/\n      - type: OpenAPI\n        url: openapi/apple-pay-js-openapi.yml\n      - type: JSONSchema\n        url: json-schema/apple-pay-payment-request-schema.json\n        title:\
  \ Payment Request Schema\n    contact:\n      - FN: Apple Developer Support\n        email: developer@apple.com\n        url: https://developer.apple.com/contact/\n  - name: PassKit Framework (Apple Pay)\n    description: >-\n      Native iOS, watchOS, and macOS framework for integrating Apple Pay into mobile\n      and desktop applications. Provides PKPaymentRequest and PKPaymentAuthorizationViewController\n      for in-app Apple Pay checkout.\n    image: https://developer.apple.com/assets/elements/icons/apple-pay/apple-pay-96x96.png\n    humanURL: https://developer.apple.com/documentation/passkit\n    baseURL: Native Framework\n    tags:\n      - iOS\n      - Mobile\n      - Native\n      - Swift\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/passkit/apple_pay\n      - type: APIReference\n        url: https://developer.apple.com/documentation/passkit/pkpaymentrequest\n      - type: CodeExamples\n        url: https://developer.apple.com/documentation/passkit/apple_pay/offering_apple_pay\n\
  \        title: Sample Code\n      - type: YouTube\n        url: https://developer.apple.com/videos/frameworks/wallet-and-apple-pay\n  - name: Apple Pay Payment Token API\n    description: >-\n      Server-side specification for processing and decrypting Apple Pay payment tokens\n      received from client applications. Tokens use EC_v1 or RSA_v1 encryption and\n      contain the payment authorization data for charge processing.\n    image: https://developer.apple.com/assets/elements/icons/apple-pay/apple-pay-96x96.png\n    humanURL: https://developer.apple.com/documentation/passkit/apple_pay/payment_token_format_reference\n    baseURL: Merchant Server\n    tags:\n      - Encryption\n      - Payment Processing\n      - Server-Side\n    properties:\n      - type: Documentation\n        url: https://developer.apple.com/documentation/passkit/apple_pay/payment_token_format_reference\n      - type: OpenAPI\n        url: openapi/apple-pay-payment-token-openapi.yml\n      - type: JSONSchema\n\
  \        url: json-schema/apple-pay-payment-token-schema.json\n        title: Payment Token Schema\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://developer.apple.com/account/\n  - type: Support\n    url: https://developer.apple.com/support/apple-pay/\n  - type: TermsOfService\n    url: https://developer.apple.com/apple-pay/acceptable-use-guidelines/\n  - type: GettingStarted\n    url: https://developer.apple.com/apple-pay/get-started/\n  - type: Branding\n    url: https://developer.apple.com/apple-pay/marketing/\n  - type: StatusPage\n    url: https://developer.apple.com/system-status/\n  - type: JSONLD\n    url: json-ld/apple-pay-context.jsonld\n  - type: SpectralRules\n    url: rules/apple-pay-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apple-pay-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/apple-pay-js.yaml\n    title: Apple Pay JS Shared Capability\n  - type: NaftikoCapability\n\
  \    url: capabilities/payment-processing.yaml\n    title: Payment Processing Workflow\n  - type: Features\n    data:\n      - name: Touch ID and Face ID Authentication\n        description: Users authorize payments using biometric authentication on Apple devices\n      - name: In-App Payments\n        description: Native iOS and watchOS integration via PassKit framework\n      - name: Web Payments\n        description: Safari-based Apple Pay checkout via the ApplePaySession JavaScript API\n      - name: Apple Watch Support\n        description: Contactless payments from Apple Watch without needing iPhone\n      - name: Multiple Card Networks\n        description: Supports Visa, Mastercard, Amex, Discover, JCB, UnionPay, and more\n      - name: Merchant Domain Verification\n        description: Domain verification ensures only registered merchants can use Apple Pay\n      - name: Recurring Payments\n        description: Subscription and automatic payment support via automatic payment requests\n\
  \      - name: Deferred Payments\n        description: Support for deferred billing like hotel deposits and pre-orders\n  - type: UseCases\n    data:\n      - name: E-Commerce Checkout\n        description: One-tap checkout on web and mobile using saved payment cards\n      - name: In-App Purchases\n        description: Native iOS app purchases with Face ID or Touch ID authentication\n      - name: Subscription Billing\n        description: Setting up recurring subscription payments authorized by the user\n      - name: Contactless In-Store Payments\n        description: Tap-to-pay at point-of-sale terminals using iPhone or Apple Watch\n      - name: Transit Payments\n        description: Paying for transit and transportation with Express Mode\n  - type: Integrations\n    data:\n      - name: Stripe\n        description: Stripe Elements and Stripe.js support Apple Pay via the Payment Request Button\n      - name: Braintree\n        description: PayPal's Braintree SDK provides Apple Pay\
  \ integration for iOS and web\n      - name: Square\n        description: Square's iOS SDK supports Apple Pay for in-app and contactless payments\n      - name: Adyen\n        description: Adyen payment platform supports Apple Pay for web and mobile checkout\n      - name: Shopify\n        description: Shopify natively supports Apple Pay for accelerated checkout\n      - name: WooCommerce\n        description: WooCommerce Stripe plugin enables Apple Pay on WordPress stores\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apple-pay/refs/heads/main/apis.yml
tags:
- Apple
- Contactless Payments
- Digital Wallet
- E-Commerce
- Mobile Payments
- Payments
url: https://developer.apple.com/apple-pay/
use_cases:
- description: One-tap checkout on web and mobile using saved payment cards
  name: E-Commerce Checkout
- description: Native iOS app purchases with Face ID or Touch ID authentication
  name: In-App Purchases
- description: Setting up recurring subscription payments authorized by the user
  name: Subscription Billing
- description: Tap-to-pay at point-of-sale terminals using iPhone or Apple Watch
  name: Contactless In-Store Payments
- description: Paying for transit and transportation with Express Mode
  name: Transit Payments
---
