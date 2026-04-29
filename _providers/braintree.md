---
api_count: 8
api_specs:
- filename: braintree-payments-openapi.yml
  format: yaml
  label: Braintree Payments API
  slug: payments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/openapi/braintree-payments-openapi.yml
- filename: braintree-webhooks-asyncapi.yml
  format: yaml
  label: Braintree Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/asyncapi/braintree-webhooks-asyncapi.yml
- filename: braintree-payments-openapi.yml
  format: yaml
  label: Braintree Vault API
  slug: vault-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/openapi/braintree-payments-openapi.yml
- filename: braintree-subscriptions-openapi.yml
  format: yaml
  label: Braintree Subscriptions API
  slug: subscriptions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/openapi/braintree-subscriptions-openapi.yml
apis:
- description: The Braintree Payments API is the core server-side interface for accepting and processing payments through Braintree's gateway. It enables developers to create and manage transactions, handle authoriz
  name: Braintree Payments API
  slug: payments-api
- description: The Braintree GraphQL API provides a modern, flexible interface for interacting with the Braintree payment gateway. It exposes a single HTTP endpoint that handles all queries and mutations, allowing d
  name: Braintree GraphQL API
  slug: graphql-api
- description: 'The Braintree JavaScript Client SDK enables secure collection of payment information directly in the browser without sensitive card data touching your servers. It is organized into standalone modules '
  name: Braintree JavaScript Client SDK
  slug: javascript-client-sdk
- description: The Braintree iOS SDK is a native library for accepting card and alternative payments within iOS applications. It supports Swift and Objective-C and provides modules for credit and debit card processi
  name: Braintree iOS SDK
  slug: ios-sdk
- description: The Braintree Android SDK provides a native library for integrating payment acceptance into Android applications. It supports Java and Kotlin and includes modules for card payments, PayPal, Venmo, Goo
  name: Braintree Android SDK
  slug: android-sdk
- description: Braintree Webhooks deliver automated HTTP POST notifications to your server when specific events occur within the payment gateway. Supported event types include subscription status changes, transactio
  name: Braintree Webhooks
  slug: webhooks
- description: The Braintree Vault API provides secure, PCI-compliant long-term storage of customer payment method data. It allows merchants to store credit card numbers, PayPal accounts, and other payment methods s
  name: Braintree Vault API
  slug: vault-api
- description: The Braintree Subscriptions API enables merchants to manage recurring billing plans and customer subscriptions. Merchants define billing plans with configurable pricing, billing cycles, and trial peri
  name: Braintree Subscriptions API
  slug: subscriptions-api
asyncapis:
- description: Braintree Webhooks deliver automated HTTP POST notifications to a merchant-configured destination URL when specific events occur within the payment gateway. Webhook notifications are triggered by tran
  name: Braintree Webhooks
  slug: braintree-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/braintree-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/braintree-transaction-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/braintree-customer-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/braintree-subscription-schema.json
created: ''
description: Our mission is to empower developers with the tools, resources, and simple-to-use SDKs and APIs to build on one platform, so they can serve merchants from around the world.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Braintree Context
  property_count: 8
  slug: braintree-context
layout: provider
modified: '2026-03-21'
name: braintree
skills: []
slug: braintree
solutions: []
source_filename: apis.yml
source_yaml: "aid: braintree\nurl: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/apis.yml\napis:\n  - aid: braintree:payments-api\n    name: Braintree Payments API\n    tags:\n      - Credit Cards\n      - Payments\n      - PayPal\n      - Transactions\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.braintreegateway.com\n    humanURL: https://developer.paypal.com/braintree/docs/\n    properties:\n      - url: https://developer.paypal.com/braintree/docs/guides/overview\n        type: Documentation\n      - url: openapi/braintree-payments-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Braintree Payments API is the core server-side interface for accepting\n      and processing payments through Braintree's gateway. It enables developers\n      to create and manage transactions, handle authorizations and captures, and\n      process refunds and voids. The API supports a wide range\
  \ of payment methods\n      including credit and debit cards, PayPal, Apple Pay, Google Pay, and Venmo.\n      Server SDKs are available for Ruby, Python, PHP, Java, Node.js, and .NET\n      to simplify integration with the REST-based API.\n\n  - aid: braintree:graphql-api\n    name: Braintree GraphQL API\n    tags:\n      - GraphQL\n      - Payment Methods\n      - Payments\n      - Transactions\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://payments.braintree-api.com/graphql\n    humanURL: https://developer.paypal.com/braintree/graphql/\n    properties:\n      - url: https://developer.paypal.com/braintree/graphql/guides/concepts/\n        type: Documentation\n    description: >-\n      The Braintree GraphQL API provides a modern, flexible interface for\n      interacting with the Braintree payment gateway. It exposes a single HTTP\n      endpoint that handles all queries and mutations, allowing developers to\n      request\
  \ only the data they need. The API supports tokenizing payment\n      methods, creating transactions, managing customer vaults, and handling\n      disputes. A sandbox environment is available at\n      payments.sandbox.braintree-api.com/graphql for testing integrations before\n      going live.\n\n  - aid: braintree:javascript-client-sdk\n    name: Braintree JavaScript Client SDK\n    tags:\n      - Browser\n      - Client SDK\n      - Drop-In UI\n      - JavaScript\n      - Payments\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/javascript/v3/\n    properties:\n      - url: https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/javascript/v3/\n        type: Documentation\n    description: >-\n      The Braintree JavaScript Client SDK enables secure collection of payment information\n      directly in the browser\
  \ without sensitive card data touching your servers. It\n      is organized into standalone modules for different payment methods including\n      hosted fields, PayPal, Apple Pay, Google Pay, and three-D Secure. The SDK provides\n      both a Drop-In UI component for rapid integration and lower-level APIs for fully\n      customized payment forms.\n\n  - aid: braintree:ios-sdk\n    name: Braintree iOS SDK\n    tags:\n      - iOS\n      - Mobile\n      - Objective-C\n      - Payments\n      - Swift\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/ios/v6\n    properties:\n      - url: https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/ios/v6\n        type: Documentation\n    description: >-\n      The Braintree iOS SDK is a native library for accepting card and\n      alternative payments within iOS applications.\
  \ It supports Swift and\n      Objective-C and provides modules for credit and debit card processing,\n      PayPal, Venmo, Apple Pay, and three-D Secure authentication. The SDK\n      tokenizes payment information collected from users and returns a payment\n      method nonce that your server uses to complete the transaction. It is\n      distributed via CocoaPods, Carthage, and Swift Package Manager.\n\n  - aid: braintree:android-sdk\n    name: Braintree Android SDK\n    tags:\n      - Android\n      - Java\n      - Kotlin\n      - Mobile\n      - Payments\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/android/v4\n    properties:\n      - url: https://developer.paypal.com/braintree/docs/guides/client-sdk/setup/android/v4\n        type: Documentation\n    description: >-\n      The Braintree Android SDK provides a native library\
  \ for integrating payment\n      acceptance into Android applications. It supports Java and Kotlin and\n      includes modules for card payments, PayPal, Venmo, Google Pay, and three-D\n      Secure verification. Like the iOS counterpart, the Android SDK tokenizes\n      payment data on the client side and returns a payment method nonce for\n      server-side transaction processing. The SDK is distributed through Maven\n      Central and supports Android API level 21 and above.\n\n  - aid: braintree:webhooks\n    name: Braintree Webhooks\n    tags:\n      - Disputes\n      - Events\n      - Notifications\n      - Subscriptions\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.paypal.com/braintree/docs/guides/webhooks/overview\n    properties:\n      - url: https://developer.paypal.com/braintree/docs/guides/webhooks/overview\n        type: Documentation\n      -\
  \ url: asyncapi/braintree-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      Braintree Webhooks deliver automated HTTP POST notifications to your server\n      when specific events occur within the payment gateway. Supported event types\n      include subscription status changes, transaction settlements, disbursements,\n      dispute openings and resolutions, and sub-merchant account status updates for\n      Braintree Marketplace. Each webhook notification contains the event kind and\n      the full Braintree object associated with the triggering event.\n\n  - aid: braintree:vault-api\n    name: Braintree Vault API\n    tags:\n      - Customers\n      - Payment Methods\n      - PCI Compliance\n      - Storage\n      - Vault\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.braintreegateway.com\n    humanURL: https://developer.paypal.com/braintree/docs/guides/customers/overview\n    properties:\n    \
  \  - url: https://developer.paypal.com/braintree/docs/guides/customers/overview\n        type: Documentation\n      - url: openapi/braintree-payments-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Braintree Vault API provides secure, PCI-compliant long-term storage of\n      customer payment method data. It allows merchants to store credit card numbers,\n      PayPal accounts, and other payment methods so that returning customers do not\n      need to re-enter their information. The Vault supports customer records that\n      can hold multiple payment methods, billing addresses, and associated transaction\n      history.\n\n  - aid: braintree:subscriptions-api\n    name: Braintree Subscriptions API\n    tags:\n      - Payments\n      - Plans\n      - Recurring Billing\n      - Subscriptions\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.braintreegateway.com\n    humanURL: https://developer.paypal.com/braintree/docs/guides/recurring-billing/overview\n\
  \    properties:\n      - url: https://developer.paypal.com/braintree/docs/guides/recurring-billing/overview\n        type: Documentation\n      - url: openapi/braintree-subscriptions-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Braintree Subscriptions API enables merchants to manage recurring billing\n      plans and customer subscriptions. Merchants define billing plans with configurable\n      pricing, billing cycles, and trial periods, then subscribe customers using vaulted\n      payment methods. The API handles automatic charge retries, prorated billing\n      for mid-cycle changes, add-ons and discounts, and subscription lifecycle events.\n\ncommon:\n  - type: JSON-LD\n    url: json-ld/braintree-context.jsonld\n  - type: JSONSchema\n    url: json-schema/braintree-transaction-schema.json\n  - type: JSONSchema\n    url: json-schema/braintree-customer-schema.json\n  - type: JSONSchema\n    url: json-schema/braintree-subscription-schema.json\n\nmodified: '2026-03-21'\n\
  description: >-\n  Our mission is to empower developers with the tools, resources, and simple-to-use\n  SDKs and APIs to build on one platform, so they can serve merchants from around\n  the world.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/braintree/refs/heads/main/apis.yml
use_cases: []
---
