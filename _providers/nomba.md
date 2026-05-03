---
api_count: 9
api_specs:
- filename: nomba-authentication-openapi.yml
  format: yaml
  label: Nomba Authentication API
  slug: authentication
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-authentication-openapi.yml
- filename: nomba-accounts-openapi.yml
  format: yaml
  label: Nomba Accounts API
  slug: accounts
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-accounts-openapi.yml
- filename: nomba-virtual-accounts-openapi.yml
  format: yaml
  label: Nomba Virtual Accounts API
  slug: virtual-accounts
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-virtual-accounts-openapi.yml
- filename: nomba-transfers-openapi.yml
  format: yaml
  label: Nomba Transfers API
  slug: transfers
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-transfers-openapi.yml
- filename: nomba-online-checkout-openapi.yml
  format: yaml
  label: Nomba Online Checkout API
  slug: online-checkout
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-online-checkout-openapi.yml
- filename: nomba-charge-openapi.yml
  format: yaml
  label: Nomba Charge API
  slug: charge
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-charge-openapi.yml
- filename: nomba-transactions-openapi.yml
  format: yaml
  label: Nomba Transactions API
  slug: transactions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-transactions-openapi.yml
- filename: nomba-global-payout-openapi.yml
  format: yaml
  label: Nomba Global Payout API
  slug: global-payout
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/openapi/nomba-global-payout-openapi.yml
apis:
- description: 'The Nomba Authentication API provides OAuth2-based authentication for accessing all Nomba API endpoints. It supports two authentication methods: Client-Credentials for server-to-server integrations an'
  name: Nomba Authentication API
  slug: authentication
- description: The Nomba Accounts API enables developers to manage business accounts on the Nomba platform. It provides endpoints for retrieving account details, fetching terminals assigned to an account, and managi
  name: Nomba Accounts API
  slug: accounts
- description: The Nomba Virtual Accounts API allows developers to create and manage virtual bank accounts for receiving payments. There is no fixed limit to the number of virtual accounts that can be created for cu
  name: Nomba Virtual Accounts API
  slug: virtual-accounts
- description: The Nomba Transfers API provides endpoints for initiating and managing fund transfers. Developers can look up bank codes and names, verify account details, and initiate transfers to Nigerian bank acco
  name: Nomba Transfers API
  slug: transfers
- description: The Nomba Online Checkout API enables developers to create checkout orders and process payments through multiple channels. It supports Visa, Verve, and Mastercard payments, as well as USSD, bank trans
  name: Nomba Online Checkout API
  slug: online-checkout
- description: The Nomba Charge API provides direct card charging capabilities for developers building payment solutions. It supports OTP submission for card transactions, retrieval of user saved cards, and tokenize
  name: Nomba Charge API
  slug: charge
- description: The Nomba Transactions API allows developers to retrieve and manage transaction records. It provides endpoints for fetching account transaction history, querying transaction details, and processing re
  name: Nomba Transactions API
  slug: transactions
- description: 'The Nomba Global Payout API is a single integration point that enables cross-border payment operators, remittance platforms, and fintechs to collect funds in Nigerian Naira or stablecoins (USDT/USDC) '
  name: Nomba Global Payout API
  slug: global-payout
- description: The Nomba Checkout SDK provides pre-built plugins and client libraries for integrating Nomba payment acceptance into websites and mobile applications. It includes an iOS SDK and e-commerce plugins suc
  name: Nomba Checkout SDK
  slug: checkout-sdk
asyncapis:
- description: The Nomba Webhooks system delivers real-time event notifications via HTTP POST callbacks when activities occur within a customer account. Events include payment successes and failures, payout completi
  name: Nomba Webhook Events
  slug: nomba-webhooks-asyncapi
common:
- title: ''
  type: Website
  url: https://nomba.com
- title: ''
  type: Developer Portal
  url: https://developer.nomba.com
- title: ''
  type: Blog
  url: https://nomba-developers.hashnode.dev
- title: ''
  type: AsyncAPI
  url: asyncapi/nomba-webhooks-asyncapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/nomba-webhook-event-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/nomba-virtual-account-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/nomba-transaction-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/nomba-checkout-order-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/nomba-context.jsonld
created: '2026-03-24'
description: Nomba is a Nigerian fintech platform that provides payment infrastructure for businesses, offering APIs for payment acceptance, transfers, virtual accounts, and cross-border payouts. Their developer platform enables merchants and platforms to integrate card payments, bank transfers, USSD, and QR code payments into applications.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Nomba Context
  property_count: 9
  slug: nomba-context
layout: provider
modified: '2026-04-28'
name: Nomba
skills: []
slug: nomba
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nomba\nname: Nomba\ndescription: >-\n  Nomba is a Nigerian fintech platform that provides payment infrastructure for\n  businesses, offering APIs for payment acceptance, transfers, virtual accounts,\n  and cross-border payouts. Their developer platform enables merchants and\n  platforms to integrate card payments, bank transfers, USSD, and QR code\n  payments into applications.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Payments\n  - Fintech\n  - Banking\n  - Transfers\n  - Virtual Accounts\n  - Checkout\n  - Cross-Border Payments\n  - Cards\napis:\n  - aid: nomba:authentication\n    name: Nomba Authentication API\n    description: >-\n      The Nomba Authentication API provides OAuth2-based authentication for\n      accessing all Nomba API endpoints. It supports\
  \ two authentication methods:\n      Client-Credentials for server-to-server integrations and PKCE (Proof Key\n      for Code Exchange) for client-side applications. Developers obtain HTTP\n      bearer tokens that are used to authorize subsequent API calls across the\n      Nomba platform.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.nomba.com/nomba-api-reference/authenticate/obtain-access-token\n    baseURL: https://api.nomba.com\n    tags:\n      - Authentication\n      - OAuth2\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developer.nomba.com/nomba-api-reference/authenticate/obtain-access-token\n      - type: OpenAPI\n        url: openapi/nomba-authentication-openapi.yml\n  - aid: nomba:accounts\n    name: Nomba Accounts API\n    description: >-\n      The Nomba Accounts API enables developers to manage business accounts on\n      the Nomba platform. It provides endpoints\
  \ for retrieving account details,\n      fetching terminals assigned to an account, and managing account-level\n      configurations. This API serves as the foundation for account management\n      operations within the Nomba ecosystem.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.nomba.com/nomba-api-reference/accounts/fetch-terminals-assigned-to-an-account\n    baseURL: https://api.nomba.com\n    tags:\n      - Accounts\n      - Financial Services\n      - Terminals\n    properties:\n      - type: Documentation\n        url: https://developer.nomba.com/nomba-api-reference/accounts/fetch-terminals-assigned-to-an-account\n      - type: OpenAPI\n        url: openapi/nomba-accounts-openapi.yml\n  - aid: nomba:virtual-accounts\n    name: Nomba Virtual Accounts API\n    description: >-\n      The Nomba Virtual Accounts API allows developers to create and manage\n      virtual bank accounts for receiving payments. There\
  \ is no fixed limit to\n      the number of virtual accounts that can be created for customers. The API\n      supports creating, expiring, and managing virtual accounts, enabling\n      businesses to collect payments via bank transfers with unique account\n      numbers assigned to individual customers or transactions.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.nomba.com/nomba-api-reference/virtual-accounts/create-virtual-account\n    baseURL: https://api.nomba.com\n    tags:\n      - Virtual Accounts\n      - Payments\n      - Collections\n    properties:\n      - type: Documentation\n        url: https://developer.nomba.com/nomba-api-reference/virtual-accounts/create-virtual-account\n      - type: OpenAPI\n        url: openapi/nomba-virtual-accounts-openapi.yml\n  - aid: nomba:transfers\n    name: Nomba Transfers API\n    description: >-\n      The Nomba Transfers API provides endpoints for initiating and managing\n\
  \      fund transfers. Developers can look up bank codes and names, verify\n      account details, and initiate transfers to Nigerian bank accounts. The\n      API supports domestic money transfers and provides the necessary bank\n      metadata for building payment flows within applications.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.nomba.com/nomba-api-reference/transfers/fetch-bank-codes-and-names\n    baseURL: https://api.nomba.com\n    tags:\n      - Transfers\n      - Payments\n      - Banking\n    properties:\n      - type: Documentation\n        url: https://developer.nomba.com/nomba-api-reference/transfers/fetch-bank-codes-and-names\n      - type: OpenAPI\n        url: openapi/nomba-transfers-openapi.yml\n  - aid: nomba:online-checkout\n    name: Nomba Online Checkout API\n    description: >-\n      The Nomba Online Checkout API enables developers to create checkout\n      orders and process payments\
  \ through multiple channels. It supports Visa,\n      Verve, and Mastercard payments, as well as USSD, bank transfers, and\n      Nomba QR payments. The API includes tokenized card payment capabilities,\n      allowing merchants to charge returning customers without requiring them\n      to re-enter card details.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.nomba.com/nomba-api-reference/online-checkout/create-an-online-checkout-order\n    baseURL: https://api.nomba.com\n    tags:\n      - Checkout\n      - Payments\n      - E-Commerce\n      - Cards\n    properties:\n      - type: Documentation\n        url: https://developer.nomba.com/nomba-api-reference/online-checkout/create-an-online-checkout-order\n      - type: OpenAPI\n        url: openapi/nomba-online-checkout-openapi.yml\n  - aid: nomba:charge\n    name: Nomba Charge API\n    description: >-\n      The Nomba Charge API provides direct card charging capabilities\
  \ for\n      developers building payment solutions. It supports OTP submission for\n      card transactions, retrieval of user saved cards, and tokenized card\n      charging. This API is designed for merchants and platforms that need\n      programmatic control over the card payment flow, including handling\n      3D Secure authentication steps.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.nomba.com/nomba-api-reference/charge/submit-customer-card-otp\n    baseURL: https://api.nomba.com\n    tags:\n      - Payments\n      - Cards\n      - Tokenization\n    properties:\n      - type: Documentation\n        url: https://developer.nomba.com/nomba-api-reference/charge/submit-customer-card-otp\n      - type: OpenAPI\n        url: openapi/nomba-charge-openapi.yml\n  - aid: nomba:transactions\n    name: Nomba Transactions API\n    description: >-\n      The Nomba Transactions API allows developers to retrieve and manage\n\
  \      transaction records. It provides endpoints for fetching account\n      transaction history, querying transaction details, and processing\n      refunds. This API is essential for building reporting dashboards,\n      reconciliation tools, and transaction monitoring systems on top of\n      the Nomba platform.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.nomba.com/products/transactions/fetch-account-transactions\n    baseURL: https://api.nomba.com\n    tags:\n      - Transactions\n      - Reporting\n      - Financial Data\n    properties:\n      - type: Documentation\n        url: https://developer.nomba.com/products/transactions/fetch-account-transactions\n      - type: OpenAPI\n        url: openapi/nomba-transactions-openapi.yml\n  - aid: nomba:global-payout\n    name: Nomba Global Payout API\n    description: >-\n      The Nomba Global Payout API is a single integration point that enables\n      cross-border\
  \ payment operators, remittance platforms, and fintechs to\n      collect funds in Nigerian Naira or stablecoins (USDT/USDC) and trigger\n      instant disbursements to the United Kingdom via Faster Payments, Europe\n      via SEPA, Canada via Interac and bank transfer, and the Democratic\n      Republic of Congo via Mobile Money. The API embeds FX sourcing and\n      compliance directly into the technical layer, eliminating the need for\n      operators to manage foreign exchange processes. It solves capital lockups\n      in cross-border trade by handling currency conversion automatically when\n      funds land in a virtual account.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.nomba.com/docs/products/global-payout/introduction\n    baseURL: https://api.nomba.com\n    tags:\n      - Cross-Border Payments\n      - Payouts\n      - Foreign Exchange\n      - Stablecoins\n      - Remittance\n    properties:\n     \
  \ - type: Documentation\n        url: https://developer.nomba.com/docs/products/global-payout/introduction\n      - type: OpenAPI\n        url: openapi/nomba-global-payout-openapi.yml\n  - aid: nomba:checkout-sdk\n    name: Nomba Checkout SDK\n    description: >-\n      The Nomba Checkout SDK provides pre-built plugins and client libraries\n      for integrating Nomba payment acceptance into websites and mobile\n      applications. It includes an iOS SDK and e-commerce plugins such as a\n      WooCommerce gateway for WordPress. The SDK supports Visa, Verve, and\n      Mastercard payments along with USSD, bank transfers, and Nomba QR,\n      enabling merchants to quickly add payment capabilities without building\n      a custom checkout flow.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.nomba.com/plugins-and-sdk/overview\n    baseURL: https://api.nomba.com\n    tags:\n      - SDK\n      - Checkout\n      - Plugins\n\
  \      - E-Commerce\n    properties:\n      - type: Documentation\n        url: https://developer.nomba.com/plugins-and-sdk/overview\ncommon:\n  - type: Website\n    url: https://nomba.com\n  - type: Developer Portal\n    url: https://developer.nomba.com\n  - type: Blog\n    url: https://nomba-developers.hashnode.dev\n  - type: AsyncAPI\n    url: asyncapi/nomba-webhooks-asyncapi.yml\n  - type: JSONSchema\n    url: json-schema/nomba-webhook-event-schema.json\n  - type: JSONSchema\n    url: json-schema/nomba-virtual-account-schema.json\n  - type: JSONSchema\n    url: json-schema/nomba-transaction-schema.json\n  - type: JSONSchema\n    url: json-schema/nomba-checkout-order-schema.json\n  - type: JSON-LD\n    url: json-ld/nomba-context.jsonld\nmaintainers:\n  - FN: API Evangelist\n    url: https://apievangelist.com\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/apis.yml
tags:
- Payments
- Fintech
- Banking
- Transfers
- Virtual Accounts
- Checkout
- Cross-Border Payments
- Cards
url: https://raw.githubusercontent.com/api-evangelist/nomba/refs/heads/main/apis.yml
use_cases: []
---
