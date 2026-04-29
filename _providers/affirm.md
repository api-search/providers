---
api_count: 10
api_specs:
- filename: affirm-direct-api-openapi.yml
  format: yaml
  label: Affirm Direct API
  slug: direct-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-direct-api-openapi.yml
- filename: affirm-checkout-openapi.yml
  format: yaml
  label: Affirm Checkout API
  slug: checkout-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-checkout-openapi.yml
- filename: affirm-transactions-openapi.yml
  format: yaml
  label: Affirm Transactions API
  slug: transactions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-transactions-openapi.yml
- filename: affirm-promos-openapi.yml
  format: yaml
  label: Affirm Promos API
  slug: promos-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-promos-openapi.yml
- filename: affirm-disputes-openapi.yml
  format: yaml
  label: Affirm Disputes API
  slug: disputes-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/openapi/affirm-disputes-openapi.yml
apis:
- description: The Affirm Direct API is a flexible integration that allows merchants to embed the full Affirm checkout and payment authorization flow directly into their website, giving complete control over the fro
  name: Affirm Direct API
  slug: direct-api
- description: The Affirm Checkout API enables merchants to initiate and manage the Affirm buy now pay later checkout flow for customers at the point of purchase. It provides endpoints to create checkout sessions, r
  name: Affirm Checkout API
  slug: checkout-api
- description: The Affirm Transactions API provides server-side endpoints for managing the full lifecycle of Affirm payment transactions after a customer completes checkout. It supports authorization, capture, void,
  name: Affirm Transactions API
  slug: transactions-api
- description: The Affirm Promos API is a server-side endpoint that enables merchants to render dynamic promotional pricing text and present Affirm-hosted educational modals on their website. It accepts a purchase a
  name: Affirm Promos API
  slug: promos-api
- description: The Affirm Disputes API (V3) provides merchants with programmatic access to manage payment disputes initiated by customers. It supports listing and retrieving individual dispute records, submitting ev
  name: Affirm Disputes API
  slug: disputes-api
- description: The Affirm Cards API enables merchants to create and manage virtual card (VCN) transactions for Affirm Lite integrations. It supports creating, reading, finalizing, and canceling virtual cards that ca
  name: Affirm Cards API
  slug: cards-api
- description: 'The Affirm Files API provides endpoints for uploading supporting documentation that can be attached as evidence when responding to payment disputes. It is used in conjunction with the Disputes API to '
  name: Affirm Files API
  slug: files-api
- description: The Affirm Prequalification API allows merchants to check whether a customer is prequalified for Affirm financing before they reach checkout. This enables merchants to surface Affirm messaging and fin
  name: Affirm Prequalification API
  slug: prequal-api
- description: The Affirm iOS SDK provides a native library for integrating Affirm buy now pay later checkout into iOS applications. It handles presenting the Affirm checkout flow within a mobile webview and returni
  name: Affirm iOS SDK
  slug: mobile-sdk-ios
- description: The Affirm Android SDK provides a native library for embedding the Affirm buy now pay later checkout experience into Android applications. It manages the checkout webview flow, handles deep link callb
  name: Affirm Android SDK
  slug: mobile-sdk-android
asyncapis:
- description: Affirm uses webhooks to notify merchant endpoints in real time when events occur during the customer checkout and prequalification flows. Webhooks are available to Key and Enterprise merchants. Affirm
  name: Affirm Webhooks
  slug: affirm-webhooks-asyncapi
capabilities:
- description: 'Unified workflow capability for managing the full Affirm BNPL payment lifecycle — from initiating checkout sessions through transaction authorization, capture, refund, and dispute resolution. Used by '
  name: Affirm Payment Management
  slug: payment-management
common:
- title: ''
  type: AsyncAPI
  url: asyncapi/affirm-webhooks-asyncapi.yml
- title: ''
  type: JSON-LD
  url: json-ld/affirm-context.jsonld
- title: ''
  type: Portal
  url: https://docs.affirm.com
- title: ''
  type: GettingStarted
  url: https://docs.affirm.com/developers/docs/home-introduction
- title: ''
  type: Authentication
  url: https://docs.affirm.com/developers/docs/authentication
- title: ''
  type: RateLimits
  url: https://docs.affirm.com/developers/docs/rate-limits
- title: ''
  type: SignUp
  url: https://www.affirm.com/business
- title: ''
  type: StatusPage
  url: https://status.affirm.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/Affirm
- title: ''
  type: TermsOfService
  url: https://www.affirm.com/merchant-tos
- title: ''
  type: PrivacyPolicy
  url: https://www.affirm.com/privacy
- title: ''
  type: Support
  url: https://docs.affirm.com/developers/docs/get-support
- title: ''
  type: JSONSchema
  url: json-schema/affirm-checkout-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/affirm-dispute-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/affirm-transaction-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/checkout-address-object-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/checkout-checkout-request-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/checkout-checkout-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/checkout-contact-object-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/checkout-discount-object-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/checkout-item-object-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/checkout-merchant-object-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/checkout-name-object-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/checkout-store-object-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/direct-api-card-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/direct-api-file-object-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/direct-api-transaction-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/disputes-dispute-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/disputes-evidence-item-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/disputes-evidence-request-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/promos-financing-term-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/promos-offer-content-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/promos-promo-config-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/promos-promo-content-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/promos-promo-response-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/transactions-settlement-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/transactions-settlement-event-summary-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/transactions-transaction-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/transactions-transaction-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/affirm-checkout-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/affirm-dispute-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/affirm-transaction-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/checkout-address-object-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/checkout-checkout-request-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/checkout-checkout-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/checkout-contact-object-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/checkout-discount-object-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/checkout-item-object-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/checkout-merchant-object-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/checkout-name-object-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/checkout-store-object-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/direct-api-card-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/direct-api-file-object-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/direct-api-transaction-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/disputes-dispute-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/disputes-evidence-item-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/disputes-evidence-request-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/promos-financing-term-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/promos-offer-content-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/promos-promo-config-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/promos-promo-content-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/promos-promo-response-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/transactions-settlement-event-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/transactions-settlement-event-summary-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/transactions-transaction-event-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/transactions-transaction-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/affirm-checkout-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/affirm-direct-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/affirm-disputes-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/affirm-promos-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/affirm-transactions-context.jsonld
- title: ''
  type: Example
  url: examples/affirm-checkout-example.json
- title: ''
  type: Example
  url: examples/affirm-dispute-example.json
- title: ''
  type: Example
  url: examples/affirm-transaction-example.json
- title: ''
  type: Example
  url: examples/checkout-address-object-example.json
- title: ''
  type: Example
  url: examples/checkout-checkout-example.json
- title: ''
  type: Example
  url: examples/checkout-checkout-request-example.json
- title: ''
  type: Example
  url: examples/checkout-contact-object-example.json
- title: ''
  type: Example
  url: examples/checkout-discount-object-example.json
- title: ''
  type: Example
  url: examples/checkout-item-object-example.json
- title: ''
  type: Example
  url: examples/checkout-merchant-object-example.json
- title: ''
  type: Example
  url: examples/checkout-name-object-example.json
- title: ''
  type: Example
  url: examples/checkout-store-object-example.json
- title: ''
  type: Example
  url: examples/direct-api-card-example.json
- title: ''
  type: Example
  url: examples/direct-api-file-object-example.json
- title: ''
  type: Example
  url: examples/direct-api-transaction-example.json
- title: ''
  type: Example
  url: examples/disputes-dispute-example.json
- title: ''
  type: Example
  url: examples/disputes-evidence-item-example.json
- title: ''
  type: Example
  url: examples/disputes-evidence-request-example.json
- title: ''
  type: Example
  url: examples/promos-financing-term-example.json
- title: ''
  type: Example
  url: examples/promos-offer-content-example.json
- title: ''
  type: Example
  url: examples/promos-promo-config-example.json
- title: ''
  type: Example
  url: examples/promos-promo-content-example.json
- title: ''
  type: Example
  url: examples/promos-promo-response-example.json
- title: ''
  type: Example
  url: examples/transactions-settlement-event-example.json
- title: ''
  type: Example
  url: examples/transactions-settlement-event-summary-example.json
- title: ''
  type: Example
  url: examples/transactions-transaction-event-example.json
- title: ''
  type: Example
  url: examples/transactions-transaction-example.json
- title: ''
  type: SpectralRules
  url: rules/affirm-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/affirm-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/payment-management.yaml
created: ''
description: Affirm is a financial technology company that provides buy now, pay later financing for consumers at the point of sale across thousands of online and in-store merchants. Affirm offers a suite of developer APIs and SDKs enabling merchants to embed flexible installment payment options directly into their checkout flows, mobile apps, and marketing experiences.
features:
- description: Enable customers to split purchases into installments with 0% APR options and flexible financing terms at checkout.
  name: Buy Now Pay Later
- description: Dynamically present the best financing option (Installments, Pay in 4, etc.) to each customer based on eligibility.
  name: Adaptive Checkout
- description: Issue virtual cards via Affirm Lite so customers can use BNPL anywhere major credit cards are accepted without direct API integration.
  name: Virtual Card Network
- description: Capture funds from a single Affirm transaction across multiple shipments or fulfillment events.
  name: Split Capture
- description: Display "as low as" monthly payment messaging on product, cart, and homepage views to increase conversion.
  name: Promotional Messaging
- description: Check customer eligibility for Affirm financing before checkout to surface relevant offers and improve conversion.
  name: Prequalification
- description: Receive real-time event notifications for key transaction lifecycle events including authorization, capture, void, and refund.
  name: Webhook Notifications
- description: Programmatically manage payment disputes by submitting evidence and tracking dispute status via API.
  name: Dispute Management
- description: Support for merchants in the USA, Canada, and UK with international market configuration.
  name: Global Integration
image: ''
integrations:
- description: Affirm is available as a payment provider plugin for Shopify merchants, enabling BNPL at Shopify-powered checkouts.
  name: Shopify
- description: Native Affirm integration for BigCommerce stores, providing BNPL checkout without custom API development.
  name: BigCommerce
- description: Affirm plugin for WooCommerce-powered WordPress stores enables BNPL payment options.
  name: WooCommerce
- description: Affirm integration for Salesforce Commerce Cloud (SFCC) enterprise e-commerce deployments.
  name: Salesforce Commerce Cloud
- description: Affirm integration for Magento (Adobe Commerce) merchants to enable BNPL checkout.
  name: Magento
- description: Affirm is available as a payment method through the Stripe payment platform.
  name: Stripe
- description: Affirm BNPL is accessible via the Braintree payment gateway for merchants using PayPal infrastructure.
  name: Braintree
jsonld:
- class_count: 11
  name: Affirm Checkout Context
  property_count: 50
  slug: affirm-checkout-context
- class_count: 0
  name: Affirm Context
  property_count: 9
  slug: affirm-context
- class_count: 3
  name: Affirm Direct Context
  property_count: 23
  slug: affirm-direct-context
- class_count: 3
  name: Affirm Disputes Context
  property_count: 21
  slug: affirm-disputes-context
- class_count: 6
  name: Affirm Promos Context
  property_count: 30
  slug: affirm-promos-context
- class_count: 4
  name: Affirm Transactions Context
  property_count: 22
  slug: affirm-transactions-context
layout: provider
modified: '2026-04-19'
name: affirm
rules:
- name: affirm API Rules
  rule_count: 35
  severity_counts:
    error: 16
    hint: 0
    info: 2
    warn: 17
  slug: affirm-spectral-rules
skills: []
slug: affirm
solutions: []
source_filename: apis.yml
source_yaml: "aid: affirm\nurl: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/apis.yml\nmodified: '2026-04-19'\napis:\n- aid: affirm:direct-api\n  name: Affirm Direct API\n  tags:\n  - Buy Now Pay Later\n  - Checkout\n  - Fintech\n  - Merchant\n  - Payments\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.affirm.com\n  humanURL: https://docs.affirm.com/payments/docs/direct-api-overview\n  properties:\n  - url: https://docs.affirm.com/payments/docs/direct-api-overview\n    type: Documentation\n  - url: openapi/affirm-direct-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Affirm Direct API is a flexible integration that allows merchants to embed\n    the full Affirm checkout and payment authorization flow directly into their\n    website, giving complete control over the front-end user experience and back-end\n    transaction processing logic. It supports inline checkout via modal or redirect\n\
  \    to affirm.com, and handles the full transaction lifecycle including authorization,\n    capture, void, and refund operations.\n\n- aid: affirm:checkout-api\n  name: Affirm Checkout API\n  tags:\n  - Buy Now Pay Later\n  - Checkout\n  - Fintech\n  - Merchant\n  - Payments\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.affirm.com\n  humanURL: https://docs.affirm.com/developers/docs/home-introduction\n  properties:\n  - url: https://docs.affirm.com/developers/docs/home-introduction\n    type: Documentation\n  - url: openapi/affirm-checkout-openapi.yml\n    type: OpenAPI\n  - url: json-schema/affirm-checkout-schema.json\n    type: JSONSchema\n  description: >-\n    The Affirm Checkout API enables merchants to initiate and manage the Affirm\n    buy now pay later checkout flow for customers at the point of purchase. It provides\n    endpoints to create checkout sessions, read and update checkout objects, and\n    store checkout\
  \ tokens returned after a customer completes the Affirm financing\n    application. The API supports both redirect and direct checkout integration\n    patterns, and includes endpoints for resending checkout links via email or SMS.\n\n- aid: affirm:transactions-api\n  name: Affirm Transactions API\n  tags:\n  - Authorization\n  - Capture\n  - Fintech\n  - Payments\n  - Refunds\n  - Transactions\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.affirm.com\n  humanURL: https://docs.affirm.com/developers/reference/introduction\n  properties:\n  - url: https://docs.affirm.com/developers/reference/introduction\n    type: Documentation\n  - url: openapi/affirm-transactions-openapi.yml\n    type: OpenAPI\n  - url: json-schema/affirm-transaction-schema.json\n    type: JSONSchema\n  description: >-\n    The Affirm Transactions API provides server-side endpoints for managing the\n    full lifecycle of Affirm payment transactions after a\
  \ customer completes checkout.\n    It supports authorization, capture, void, and refund operations, as well as\n    listing and retrieving transaction details and associated settlement events.\n    Merchants use this API to reconcile charges, process partial or full refunds,\n    and track disbursement activity.\n\n- aid: affirm:promos-api\n  name: Affirm Promos API\n  tags:\n  - Buy Now Pay Later\n  - Marketing\n  - Merchant\n  - Messaging\n  - Promotions\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://www.affirm.com/api/promos/v2\n  humanURL: https://docs.affirm.com/developers/docs/promos-api-integration-overview\n  properties:\n  - url: https://docs.affirm.com/developers/docs/promos-api-integration-overview\n    type: Documentation\n  - url: openapi/affirm-promos-openapi.yml\n    type: OpenAPI\n  description: >-\n    The Affirm Promos API is a server-side endpoint that enables merchants to render\n    dynamic promotional pricing\
  \ text and present Affirm-hosted educational modals\n    on their website. It accepts a purchase amount and returns financing terms,\n    \"as low as\" monthly payment messaging, APR rates, and modal content including\n    headlines, descriptions, and legal disclosures. The API supports multiple installment\n    term options and page-type context (product, cart, homepage) to customize the\n    displayed messaging.\n\n- aid: affirm:disputes-api\n  name: Affirm Disputes API\n  tags:\n  - Chargebacks\n  - Disputes\n  - Fintech\n  - Merchant\n  - Payments\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.affirm.com\n  humanURL: https://docs.affirm.com/developers/reference/introduction\n  properties:\n  - url: https://docs.affirm.com/developers/reference/introduction\n    type: Documentation\n  - url: openapi/affirm-disputes-openapi.yml\n    type: OpenAPI\n  - url: json-schema/affirm-dispute-schema.json\n    type: JSONSchema\n  description:\
  \ >-\n    The Affirm Disputes API (V3) provides merchants with programmatic access to\n    manage payment disputes initiated by customers. It supports listing and retrieving\n    individual dispute records, submitting evidence to contest a dispute, and closing\n    disputes. The API integrates with the file upload capability so merchants can\n    attach supporting documentation as evidence when responding to disputes.\n\n- aid: affirm:cards-api\n  name: Affirm Cards API\n  tags:\n  - Cards\n  - Fintech\n  - Payments\n  - Virtual Card\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.affirm.com\n  humanURL: https://docs.affirm.com/developers/reference/introduction\n  properties:\n  - url: https://docs.affirm.com/developers/reference/introduction\n    type: Documentation\n  description: >-\n    The Affirm Cards API enables merchants to create and manage virtual card (VCN)\n    transactions for Affirm Lite integrations. It supports\
  \ creating, reading, finalizing,\n    and canceling virtual cards that can be used anywhere major credit cards are accepted,\n    providing a seamless buy now pay later experience without requiring direct API integration\n    for the merchant's payment processor.\n\n- aid: affirm:files-api\n  name: Affirm Files API\n  tags:\n  - Disputes\n  - Files\n  - Fintech\n  - Uploads\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.affirm.com\n  humanURL: https://docs.affirm.com/developers/reference/introduction\n  properties:\n  - url: https://docs.affirm.com/developers/reference/introduction\n    type: Documentation\n  description: >-\n    The Affirm Files API provides endpoints for uploading supporting documentation\n    that can be attached as evidence when responding to payment disputes. It is used\n    in conjunction with the Disputes API to submit files such as receipts, order\n    confirmations, shipping records, or customer communications.\n\
  \n- aid: affirm:prequal-api\n  name: Affirm Prequalification API\n  tags:\n  - Buy Now Pay Later\n  - Credit\n  - Fintech\n  - Prequalification\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.affirm.com\n  humanURL: https://docs.affirm.com/developers/reference/introduction\n  properties:\n  - url: https://docs.affirm.com/developers/reference/introduction\n    type: Documentation\n  description: >-\n    The Affirm Prequalification API allows merchants to check whether a customer\n    is prequalified for Affirm financing before they reach checkout. This enables\n    merchants to surface Affirm messaging and financing options only to eligible\n    customers, improving conversion rates and customer experience across the shopping\n    journey.\n\n- aid: affirm:mobile-sdk-ios\n  name: Affirm iOS SDK\n  tags:\n  - Buy Now Pay Later\n  - iOS\n  - Mobile\n  - Objective-C\n  - SDK\n  - Swift\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \  baseURL: https://api.example.com\n  humanURL: https://docs.affirm.com/developers/docs/ios-sdk-overview\n  properties:\n  - url: https://docs.affirm.com/developers/docs/ios-sdk-overview\n    type: Documentation\n  - url: https://github.com/Affirm/affirm-merchant-sdk-ios\n    type: SDK\n  description: >-\n    The Affirm iOS SDK provides a native library for integrating Affirm buy now\n    pay later checkout into iOS applications. It handles presenting the Affirm checkout\n    flow within a mobile webview and returning the checkout token to the host app\n    upon customer authorization. The SDK supports Swift and Objective-C and includes\n    components for rendering Affirm promotional messaging within native iOS UI.\n\n- aid: affirm:mobile-sdk-android\n  name: Affirm Android SDK\n  tags:\n  - Android\n  - Buy Now Pay Later\n  - Java\n  - Kotlin\n  - Mobile\n  - SDK\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.example.com\n\
  \  humanURL: https://docs.affirm.com/developers/docs/android-sdk-overview\n  properties:\n  - url: https://docs.affirm.com/developers/docs/android-sdk-overview\n    type: Documentation\n  - url: https://github.com/Affirm/affirm-merchant-sdk-android\n    type: SDK\n  description: >-\n    The Affirm Android SDK provides a native library for embedding the Affirm buy\n    now pay later checkout experience into Android applications. It manages the\n    checkout webview flow, handles deep link callbacks, and returns a checkout token\n    to the host application upon successful customer authorization. The SDK supports\n    Java and Kotlin and includes components for displaying Affirm promotional messaging\n    within native Android UI.\n\ncommon:\n- type: AsyncAPI\n  url: asyncapi/affirm-webhooks-asyncapi.yml\n- type: JSON-LD\n  url: json-ld/affirm-context.jsonld\n- type: Portal\n  url: https://docs.affirm.com\n- type: GettingStarted\n  url: https://docs.affirm.com/developers/docs/home-introduction\n\
  - type: Authentication\n  url: https://docs.affirm.com/developers/docs/authentication\n- type: RateLimits\n  url: https://docs.affirm.com/developers/docs/rate-limits\n- type: SignUp\n  url: https://www.affirm.com/business\n- type: StatusPage\n  url: https://status.affirm.com\n- type: GitHubOrganization\n  url: https://github.com/Affirm\n- type: TermsOfService\n  url: https://www.affirm.com/merchant-tos\n- type: PrivacyPolicy\n  url: https://www.affirm.com/privacy\n- type: Support\n  url: https://docs.affirm.com/developers/docs/get-support\n- type: Features\n  data:\n  - name: Buy Now Pay Later\n    description: Enable customers to split purchases into installments with 0% APR options and flexible financing terms at checkout.\n  - name: Adaptive Checkout\n    description: Dynamically present the best financing option (Installments, Pay in 4, etc.) to each customer based on eligibility.\n  - name: Virtual Card Network\n    description: Issue virtual cards via Affirm Lite so customers can\
  \ use BNPL anywhere major credit cards are accepted without direct API integration.\n  - name: Split Capture\n    description: Capture funds from a single Affirm transaction across multiple shipments or fulfillment events.\n  - name: Promotional Messaging\n    description: Display \"as low as\" monthly payment messaging on product, cart, and homepage views to increase conversion.\n  - name: Prequalification\n    description: Check customer eligibility for Affirm financing before checkout to surface relevant offers and improve conversion.\n  - name: Webhook Notifications\n    description: Receive real-time event notifications for key transaction lifecycle events including authorization, capture, void, and refund.\n  - name: Dispute Management\n    description: Programmatically manage payment disputes by submitting evidence and tracking dispute status via API.\n  - name: Global Integration\n    description: Support for merchants in the USA, Canada, and UK with international market configuration.\n\
  - type: UseCases\n  data:\n  - name: E-Commerce Checkout\n    description: Embed Affirm BNPL directly in the checkout flow of an online store to offer customers flexible payment options at the point of purchase.\n  - name: Mobile Commerce\n    description: Integrate Affirm financing into iOS and Android apps using native mobile SDKs for a seamless in-app BNPL experience.\n  - name: Telesales and Assisted Selling\n    description: Send checkout links via SMS or email to allow customers to complete Affirm-financed purchases over the phone or remotely.\n  - name: In-Store Retail\n    description: Enable Affirm BNPL in physical retail environments using virtual card or POS integration flows.\n  - name: Transaction Reconciliation\n    description: Use the Transactions API to retrieve settlement events and reconcile captured payments against disbursements.\n  - name: Dispute Resolution\n    description: Automate dispute response workflows by programmatically fetching dispute records and submitting\
  \ evidence via the Disputes API.\n  - name: Promotional Marketing\n    description: Use the Promos API to display dynamic financing terms on product pages to increase cart size and conversion.\n- type: Integrations\n  data:\n  - name: Shopify\n    description: Affirm is available as a payment provider plugin for Shopify merchants, enabling BNPL at Shopify-powered checkouts.\n  - name: BigCommerce\n    description: Native Affirm integration for BigCommerce stores, providing BNPL checkout without custom API development.\n  - name: WooCommerce\n    description: Affirm plugin for WooCommerce-powered WordPress stores enables BNPL payment options.\n  - name: Salesforce Commerce Cloud\n    description: Affirm integration for Salesforce Commerce Cloud (SFCC) enterprise e-commerce deployments.\n  - name: Magento\n    description: Affirm integration for Magento (Adobe Commerce) merchants to enable BNPL checkout.\n  - name: Stripe\n    description: Affirm is available as a payment method through\
  \ the Stripe payment platform.\n  - name: Braintree\n    description: Affirm BNPL is accessible via the Braintree payment gateway for merchants using PayPal infrastructure.\n- type: JSONSchema\n  url: json-schema/affirm-checkout-schema.json\n- type: JSONSchema\n  url: json-schema/affirm-dispute-schema.json\n- type: JSONSchema\n  url: json-schema/affirm-transaction-schema.json\n- type: JSONSchema\n  url: json-schema/checkout-address-object-schema.json\n- type: JSONSchema\n  url: json-schema/checkout-checkout-request-schema.json\n- type: JSONSchema\n  url: json-schema/checkout-checkout-schema.json\n- type: JSONSchema\n  url: json-schema/checkout-contact-object-schema.json\n- type: JSONSchema\n  url: json-schema/checkout-discount-object-schema.json\n- type: JSONSchema\n  url: json-schema/checkout-item-object-schema.json\n- type: JSONSchema\n  url: json-schema/checkout-merchant-object-schema.json\n- type: JSONSchema\n  url: json-schema/checkout-name-object-schema.json\n- type: JSONSchema\n\
  \  url: json-schema/checkout-store-object-schema.json\n- type: JSONSchema\n  url: json-schema/direct-api-card-schema.json\n- type: JSONSchema\n  url: json-schema/direct-api-file-object-schema.json\n- type: JSONSchema\n  url: json-schema/direct-api-transaction-schema.json\n- type: JSONSchema\n  url: json-schema/disputes-dispute-schema.json\n- type: JSONSchema\n  url: json-schema/disputes-evidence-item-schema.json\n- type: JSONSchema\n  url: json-schema/disputes-evidence-request-schema.json\n- type: JSONSchema\n  url: json-schema/promos-financing-term-schema.json\n- type: JSONSchema\n  url: json-schema/promos-offer-content-schema.json\n- type: JSONSchema\n  url: json-schema/promos-promo-config-schema.json\n- type: JSONSchema\n  url: json-schema/promos-promo-content-schema.json\n- type: JSONSchema\n  url: json-schema/promos-promo-response-schema.json\n- type: JSONSchema\n  url: json-schema/transactions-settlement-event-schema.json\n- type: JSONSchema\n  url: json-schema/transactions-settlement-event-summary-schema.json\n\
  - type: JSONSchema\n  url: json-schema/transactions-transaction-event-schema.json\n- type: JSONSchema\n  url: json-schema/transactions-transaction-schema.json\n- type: JSONStructure\n  url: json-structure/affirm-checkout-structure.json\n- type: JSONStructure\n  url: json-structure/affirm-dispute-structure.json\n- type: JSONStructure\n  url: json-structure/affirm-transaction-structure.json\n- type: JSONStructure\n  url: json-structure/checkout-address-object-structure.json\n- type: JSONStructure\n  url: json-structure/checkout-checkout-request-structure.json\n- type: JSONStructure\n  url: json-structure/checkout-checkout-structure.json\n- type: JSONStructure\n  url: json-structure/checkout-contact-object-structure.json\n- type: JSONStructure\n  url: json-structure/checkout-discount-object-structure.json\n- type: JSONStructure\n  url: json-structure/checkout-item-object-structure.json\n- type: JSONStructure\n  url: json-structure/checkout-merchant-object-structure.json\n- type: JSONStructure\n\
  \  url: json-structure/checkout-name-object-structure.json\n- type: JSONStructure\n  url: json-structure/checkout-store-object-structure.json\n- type: JSONStructure\n  url: json-structure/direct-api-card-structure.json\n- type: JSONStructure\n  url: json-structure/direct-api-file-object-structure.json\n- type: JSONStructure\n  url: json-structure/direct-api-transaction-structure.json\n- type: JSONStructure\n  url: json-structure/disputes-dispute-structure.json\n- type: JSONStructure\n  url: json-structure/disputes-evidence-item-structure.json\n- type: JSONStructure\n  url: json-structure/disputes-evidence-request-structure.json\n- type: JSONStructure\n  url: json-structure/promos-financing-term-structure.json\n- type: JSONStructure\n  url: json-structure/promos-offer-content-structure.json\n- type: JSONStructure\n  url: json-structure/promos-promo-config-structure.json\n- type: JSONStructure\n  url: json-structure/promos-promo-content-structure.json\n- type: JSONStructure\n  url: json-structure/promos-promo-response-structure.json\n\
  - type: JSONStructure\n  url: json-structure/transactions-settlement-event-structure.json\n- type: JSONStructure\n  url: json-structure/transactions-settlement-event-summary-structure.json\n- type: JSONStructure\n  url: json-structure/transactions-transaction-event-structure.json\n- type: JSONStructure\n  url: json-structure/transactions-transaction-structure.json\n- type: JSON-LD\n  url: json-ld/affirm-checkout-context.jsonld\n- type: JSON-LD\n  url: json-ld/affirm-direct-context.jsonld\n- type: JSON-LD\n  url: json-ld/affirm-disputes-context.jsonld\n- type: JSON-LD\n  url: json-ld/affirm-promos-context.jsonld\n- type: JSON-LD\n  url: json-ld/affirm-transactions-context.jsonld\n- type: Example\n  url: examples/affirm-checkout-example.json\n- type: Example\n  url: examples/affirm-dispute-example.json\n- type: Example\n  url: examples/affirm-transaction-example.json\n- type: Example\n  url: examples/checkout-address-object-example.json\n- type: Example\n  url: examples/checkout-checkout-example.json\n\
  - type: Example\n  url: examples/checkout-checkout-request-example.json\n- type: Example\n  url: examples/checkout-contact-object-example.json\n- type: Example\n  url: examples/checkout-discount-object-example.json\n- type: Example\n  url: examples/checkout-item-object-example.json\n- type: Example\n  url: examples/checkout-merchant-object-example.json\n- type: Example\n  url: examples/checkout-name-object-example.json\n- type: Example\n  url: examples/checkout-store-object-example.json\n- type: Example\n  url: examples/direct-api-card-example.json\n- type: Example\n  url: examples/direct-api-file-object-example.json\n- type: Example\n  url: examples/direct-api-transaction-example.json\n- type: Example\n  url: examples/disputes-dispute-example.json\n- type: Example\n  url: examples/disputes-evidence-item-example.json\n- type: Example\n  url: examples/disputes-evidence-request-example.json\n- type: Example\n  url: examples/promos-financing-term-example.json\n- type: Example\n  url: examples/promos-offer-content-example.json\n\
  - type: Example\n  url: examples/promos-promo-config-example.json\n- type: Example\n  url: examples/promos-promo-content-example.json\n- type: Example\n  url: examples/promos-promo-response-example.json\n- type: Example\n  url: examples/transactions-settlement-event-example.json\n- type: Example\n  url: examples/transactions-settlement-event-summary-example.json\n- type: Example\n  url: examples/transactions-transaction-event-example.json\n- type: Example\n  url: examples/transactions-transaction-example.json\n- type: SpectralRules\n  url: rules/affirm-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/affirm-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/payment-management.yaml\ndescription: >-\n  Affirm is a financial technology company that provides buy now, pay later financing\n  for consumers at the point of sale across thousands of online and in-store merchants.\n  Affirm offers a suite of developer APIs and SDKs enabling merchants to embed flexible\n  installment\
  \ payment options directly into their checkout flows, mobile apps, and\n  marketing experiences.\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/affirm/refs/heads/main/apis.yml
use_cases:
- description: Embed Affirm BNPL directly in the checkout flow of an online store to offer customers flexible payment options at the point of purchase.
  name: E-Commerce Checkout
- description: Integrate Affirm financing into iOS and Android apps using native mobile SDKs for a seamless in-app BNPL experience.
  name: Mobile Commerce
- description: Send checkout links via SMS or email to allow customers to complete Affirm-financed purchases over the phone or remotely.
  name: Telesales and Assisted Selling
- description: Enable Affirm BNPL in physical retail environments using virtual card or POS integration flows.
  name: In-Store Retail
- description: Use the Transactions API to retrieve settlement events and reconcile captured payments against disbursements.
  name: Transaction Reconciliation
- description: Automate dispute response workflows by programmatically fetching dispute records and submitting evidence via the Disputes API.
  name: Dispute Resolution
- description: Use the Promos API to display dynamic financing terms on product pages to increase cart size and conversion.
  name: Promotional Marketing
---
