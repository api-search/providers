---
api_count: 8
api_specs:
- filename: commercetools-http-api-openapi.yml
  format: yaml
  label: Commercetools HTTP API
  slug: http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/openapi/commercetools-http-api-openapi.yml
- filename: commercetools-import-api-openapi.yml
  format: yaml
  label: Commercetools Import API
  slug: import-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/openapi/commercetools-import-api-openapi.yml
- filename: commercetools-change-history-api-openapi.yml
  format: yaml
  label: Commercetools Change History API
  slug: change-history-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/openapi/commercetools-change-history-api-openapi.yml
apis:
- description: The commercetools HTTP API is the core REST interface for programmatic access to all data and functionality within a Composable Commerce project. It covers a broad range of commerce resources includin
  name: Commercetools HTTP API
  slug: http-api
- description: The commercetools GraphQL API provides a flexible, network-efficient alternative to the HTTP API for querying and mutating Composable Commerce resources. It exposes a single endpoint and allows client
  name: Commercetools GraphQL API
  slug: graphql-api
- description: 'The commercetools Import API enables bulk importing of commerce data into a Composable Commerce project. It supports importing categories, product types, products, product variants, prices, inventory '
  name: Commercetools Import API
  slug: import-api
- description: The commercetools Change History API provides a queryable audit log of all changes made to resources within a Composable Commerce project. It records mutations applied to resources such as products, o
  name: Commercetools Change History API
  slug: change-history-api
- description: The commercetools TypeScript SDK is the official client library for interacting with the Composable Commerce HTTP API, Import API, and GraphQL API from JavaScript and TypeScript applications. It provi
  name: Commercetools TypeScript SDK
  slug: typescript-sdk
- description: The commercetools Java SDK is the official client library for accessing the Composable Commerce APIs from Java applications. It provides strongly typed request builders, automatic OAuth 2.0 token mana
  name: Commercetools Java SDK
  slug: java-sdk
- description: The commercetools Checkout API provides programmatic control over Checkout application configurations within Composable Commerce. The Checkout Applications API allows developers to create, update, and
  name: Commercetools Checkout API
  slug: checkout-api
- description: The commercetools Merchant Center Customizations API provides the programmatic interface for building custom applications and UI extensions within the Merchant Center. It exposes proxy endpoints to un
  name: Commercetools Merchant Center Customizations API
  slug: merchant-center-customizations-api
asyncapis:
- description: The commercetools Subscriptions system delivers real-time change notifications and domain messages to external message queue destinations when resources are created, updated, or deleted within a Compo
  name: commercetools Subscriptions Events
  slug: commercetools-subscriptions-asyncapi
capabilities: []
common:
- title: ''
  type: Website
  url: https://commercetools.com/
- title: ''
  type: Documentation
  url: https://docs.commercetools.com/
- title: ''
  type: Pricing
  url: https://commercetools.com/pricing
- title: ''
  type: Status
  url: https://status.commercetools.com/
- title: ''
  type: GitHub
  url: https://github.com/commercetools
- title: ''
  type: JSON-LD
  url: json-ld/commercetools-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/commercetools-order-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/commercetools-product-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/commercetools-subscription-message-schema.json
- title: ''
  type: Spectral
  url: rules/commercetools-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/commercetools-composable-commerce-capabilities.yml
created: '2025-09-15'
description: commercetools is the leading composable, headless, API-first Commerce platform powering large-scale B2C, B2B, and marketplace digital commerce for enterprise brands. The platform exposes a broad API surface organized into the HTTP API (core REST interface), GraphQL API (flexible query and mutation alternative), Import API (bulk data ingestion), Change History API (audit log), Checkout API (managed checkout configuration), and Merchant Center Customizations API (custom UI extensions). It is complemented by official SDKs (TypeScript, Java, PHP, .NET, Python) and AsyncAPI-based subscriptions for event-driven integrations.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Commercetools Context
  property_count: 13
  slug: commercetools-context
layout: provider
modified: '2026-04-26'
name: commercetools
rules:
- name: commercetools API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 4
  slug: commercetools-rules
skills: []
slug: commercetools
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: commercetools\nurl: https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/apis.yml\nname: commercetools\ntags:\n  - Commerce\n  - Composable Commerce\n  - E-Commerce\n  - GraphQL\n  - REST\n  - SDK\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nposition: Consumer\nx-type: company\ncreated: '2025-09-15'\nmodified: '2026-04-26'\napis:\n  - aid: commercetools:http-api\n    name: Commercetools HTTP API\n    tags:\n      - Commerce\n      - Composable Commerce\n      - E-Commerce\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.{region}.commercetools.com\n    humanURL: https://docs.commercetools.com/api\n    properties:\n      - url: https://docs.commercetools.com/api\n        type: Documentation\n      - url: openapi/commercetools-http-api-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/commercetools-subscriptions-asyncapi.yml\n\
  \        type: AsyncAPI\n    description: >-\n      The commercetools HTTP API is the core REST interface for programmatic access\n      to all data and functionality within a Composable Commerce project. It covers\n      a broad range of commerce resources including products, product types, categories,\n      carts, orders, customers, payments, discounts, inventory, shipping methods,\n      stores, and business units. All resources follow RESTful conventions using standard\n      HTTP verbs and return JSON responses.\n\n  - aid: commercetools:graphql-api\n    name: Commercetools GraphQL API\n    tags:\n      - Commerce\n      - Composable Commerce\n      - E-Commerce\n      - GraphQL\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.{region}.commercetools.com\n    humanURL: https://docs.commercetools.com/api/graphql\n    properties:\n      - url: https://docs.commercetools.com/api/graphql\n        type: Documentation\n   \
  \ description: >-\n      The commercetools GraphQL API provides a flexible, network-efficient alternative\n      to the HTTP API for querying and mutating Composable Commerce resources. It\n      exposes a single endpoint and allows clients to request exactly the data they\n      need, reducing over-fetching and minimizing round trips. The GraphQL API uses\n      the same API clients, authentication tokens, and project scopes as the HTTP\n      API.\n\n  - aid: commercetools:import-api\n    name: Commercetools Import API\n    tags:\n      - Bulk Operations\n      - Commerce\n      - Data Migration\n      - Import\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://import.{region}.commercetools.com\n    humanURL: https://docs.commercetools.com/api/import-export/overview\n    properties:\n      - url: https://docs.commercetools.com/api/import-export/overview\n        type: Documentation\n      - url: openapi/commercetools-import-api-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The commercetools Import API enables bulk importing of commerce data into a\n      Composable Commerce project. It supports importing categories, product types,\n      products, product variants, prices, inventory entries, orders, and customers.\n      Imports are processed asynchronously through import containers, and the API\n      provides endpoints for monitoring import operation status and handling validation\n      errors.\n\n  - aid: commercetools:change-history-api\n    name: Commercetools Change History API\n    tags:\n      - Audit Log\n      - Change History\n      - Commerce\n      - Compliance\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://history.{region}.commercetools.com\n    humanURL: https://docs.commercetools.com/api/history/overview\n    properties:\n      - url: https://docs.commercetools.com/api/history/overview\n        type: Documentation\n      - url:\
  \ openapi/commercetools-change-history-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The commercetools Change History API provides a queryable audit log of all changes\n      made to resources within a Composable Commerce project. It records mutations\n      applied to resources such as products, orders, customers, discounts, and carts,\n      along with metadata about who made the change and when. The API is hosted on\n      separate regional endpoints and supports filtering by resource type, date range,\n      user, and client.\n\n  - aid: commercetools:typescript-sdk\n    name: Commercetools TypeScript SDK\n    tags:\n      - Commerce\n      - JavaScript\n      - SDK\n      - TypeScript\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://docs.commercetools.com/sdk/typescript-sdk\n    properties:\n      - url: https://docs.commercetools.com/sdk/typescript-sdk\n       \
  \ type: Documentation\n    description: >-\n      The commercetools TypeScript SDK is the official client library for interacting\n      with the Composable Commerce HTTP API, Import API, and GraphQL API from JavaScript\n      and TypeScript applications. It provides full type safety, IDE autocompletion,\n      and a fluent domain-specific language for constructing valid API requests. The\n      SDK handles OAuth 2.0 token management, request building, and response deserialization.\n\n  - aid: commercetools:java-sdk\n    name: Commercetools Java SDK\n    tags:\n      - Commerce\n      - Java\n      - JVM\n      - SDK\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://docs.commercetools.com/sdk/java-sdk\n    properties:\n      - url: https://docs.commercetools.com/sdk/java-sdk\n        type: Documentation\n    description: >-\n      The commercetools Java SDK is the official client library for\
  \ accessing\n      the Composable Commerce APIs from Java applications. It provides strongly\n      typed request builders, automatic OAuth 2.0 token management, and support\n      for all HTTP API and Import API endpoints. The SDK is compatible with\n      standard Java development toolchains and is distributed via Maven\n      Central. It is commonly used in enterprise backend systems and\n      microservices that require JVM-based integration with the commercetools\n      platform.\n\n  - aid: commercetools:checkout-api\n    name: Commercetools Checkout API\n    tags:\n      - Checkout\n      - Commerce\n      - Embedded Components\n      - Payments\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://docs.commercetools.com/checkout\n    properties:\n      - url: https://docs.commercetools.com/checkout\n        type: Documentation\n    description: >-\n      The commercetools Checkout API\
  \ provides programmatic control over Checkout application\n      configurations within Composable Commerce. The Checkout Applications API allows\n      developers to create, update, and manage Checkout applications without manual\n      setup in the Merchant Center, enabling automated deployment and configuration\n      across multiple stores, regions, and business units. Checkout integrates with\n      payment connectors available through the Connect marketplace.\n\n  - aid: commercetools:merchant-center-customizations-api\n    name: Commercetools Merchant Center Customizations API\n    tags:\n      - Commerce\n      - Customizations\n      - Extensions\n      - Merchant Center\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://docs.commercetools.com/merchant-center-customizations/concepts/merchant-center-api\n    properties:\n      - url: https://docs.commercetools.com/merchant-center-customizations/concepts/merchant-center-api\n\
  \        type: Documentation\n    description: >-\n      The commercetools Merchant Center Customizations API provides the programmatic\n      interface for building custom applications and UI extensions within the Merchant\n      Center. It exposes proxy endpoints to underlying REST and GraphQL APIs, allowing\n      custom UIs to interact with Composable Commerce resources in a secure, scoped\n      manner. Developers use this API when creating Custom Applications that extend\n      the Merchant Center with business-specific tooling.\n\ncommon:\n  - type: Website\n    url: https://commercetools.com/\n  - type: Documentation\n    url: https://docs.commercetools.com/\n  - type: Pricing\n    url: https://commercetools.com/pricing\n  - type: Status\n    url: https://status.commercetools.com/\n  - type: GitHub\n    url: https://github.com/commercetools\n  - url: json-ld/commercetools-context.jsonld\n    type: JSON-LD\n  - url: json-schema/commercetools-order-schema.json\n    type: JSONSchema\n\
  \  - url: json-schema/commercetools-product-schema.json\n    type: JSONSchema\n  - url: json-schema/commercetools-subscription-message-schema.json\n    type: JSONSchema\n  - url: rules/commercetools-rules.yml\n    type: Spectral\n  - url: capabilities/commercetools-composable-commerce-capabilities.yml\n    type: NaftikoCapabilities\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ndescription: >-\n  commercetools is the leading composable, headless, API-first Commerce\n  platform powering large-scale B2C, B2B, and marketplace digital commerce\n  for enterprise brands. The platform exposes a broad API surface organized\n  into the HTTP API (core REST interface), GraphQL API (flexible query and\n  mutation alternative), Import API (bulk data ingestion), Change History\n  API (audit log), Checkout API (managed checkout configuration), and\n  Merchant Center Customizations API (custom UI extensions). It is\n  complemented by official SDKs (TypeScript,\
  \ Java, PHP, .NET, Python) and\n  AsyncAPI-based subscriptions for event-driven integrations.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/apis.yml
tags:
- Commerce
- Composable Commerce
- E-Commerce
- GraphQL
- REST
- SDK
url: https://raw.githubusercontent.com/api-evangelist/commercetools/refs/heads/main/apis.yml
use_cases: []
---
