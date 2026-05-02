---
api_count: 6
api_specs:
- filename: magento-rest-api-openapi.yml
  format: yaml
  label: Magento REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/openapi/magento-rest-api-openapi.yml
- filename: magento-webhooks-asyncapi.yml
  format: yaml
  label: Adobe Commerce Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/asyncapi/magento-webhooks-asyncapi.yml
- filename: magento-events-asyncapi.yml
  format: yaml
  label: Adobe Commerce Eventing
  slug: events
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/asyncapi/magento-events-asyncapi.yml
apis:
- description: The Adobe Commerce (Magento) REST API provides a comprehensive set of endpoints for interacting with all major aspects of an e-commerce store, including catalog management, orders, customers, inventor
  name: Magento REST API
  slug: rest-api
- description: 'The Adobe Commerce GraphQL API offers a flexible, query-driven interface designed primarily for building headless storefronts and progressive web applications. It exposes a single endpoint and allows '
  name: Magento GraphQL API
  slug: graphql-api
- description: 'The Adobe Commerce SOAP API exposes the same service contracts as the REST API through a WSDL 1.2 interface compliant with WS-I 2.0 Basic Profile. It allows enterprise systems and legacy integrations '
  name: Magento SOAP API
  slug: soap-api
- description: Adobe Commerce Webhooks enable developers to configure synchronous HTTP callbacks that fire when specific events occur within a Commerce instance, allowing external systems to react in real time to st
  name: Adobe Commerce Webhooks
  slug: webhooks
- description: The Adobe Commerce Admin UI SDK enables App Builder developers to extend the Commerce Admin panel with custom menus, pages, and UI components built as out-of-process applications. Rather than modifyin
  name: Adobe Commerce Admin UI SDK
  slug: admin-ui-sdk
- description: Adobe Commerce Eventing provides an asynchronous event-driven integration framework that publishes Commerce business events to Adobe I/O Events, enabling App Builder applications and other Adobe Exper
  name: Adobe Commerce Eventing
  slug: events
asyncapis:
- description: Adobe Commerce Eventing provides an asynchronous event-driven integration framework that publishes Commerce business events to Adobe I/O Events, enabling App Builder applications and other Adobe Exper
  name: Adobe Commerce Eventing
  slug: magento-events-asyncapi
- description: Adobe Commerce Webhooks enable developers to configure synchronous HTTP callbacks that fire when specific events occur within a Commerce instance, allowing external systems to react in real time to st
  name: Adobe Commerce Webhooks
  slug: magento-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/magento-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/magento-order-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/magento-product-schema.json
created: ''
description: Overview of the Adobe Commerce and Magento Open Source REST API documentation.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Magento Context
  property_count: 8
  slug: magento-context
layout: provider
modified: '2026-03-21'
name: magento
skills: []
slug: magento
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: magento\nurl: https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/apis.yml\nmodified: '2026-03-21'\napis:\n  - aid: magento:rest-api\n    name: Magento REST API\n    tags:\n      - Catalog\n      - Customers\n      - E-Commerce\n      - Orders\n      - Products\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://your-store.example.com/rest\n    humanURL: https://developer.adobe.com/commerce/webapi/rest/\n    properties:\n      - url: https://developer.adobe.com/commerce/webapi/rest/\n        type: Documentation\n      - url: https://developer.adobe.com/commerce/webapi/rest/reference/\n        type: Documentation\n      - url: openapi/magento-rest-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Adobe Commerce (Magento) REST API provides a comprehensive set of endpoints\n      for interacting with all major aspects of an e-commerce store, including catalog\n\
  \      management, orders, customers, inventory, shipping, and payments. It supports\n      three authentication mechanisms: OAuth 1.0a for third-party integrations, token-based\n      authentication for mobile apps and administrators, and guest access for select\n      public endpoints.\n\n  - aid: magento:graphql-api\n    name: Magento GraphQL API\n    tags:\n      - Cart\n      - Catalog\n      - E-Commerce\n      - GraphQL\n      - Headless Commerce\n      - Storefront\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://your-store.example.com/graphql\n    humanURL: https://developer.adobe.com/commerce/webapi/graphql/\n    properties:\n      - url: https://developer.adobe.com/commerce/webapi/graphql/\n        type: Documentation\n      - url: https://developer.adobe.com/commerce/webapi/graphql/reference/\n        type: Documentation\n    description: >-\n      The Adobe Commerce GraphQL API offers a flexible, query-driven interface\
  \ designed\n      primarily for building headless storefronts and progressive web applications.\n      It exposes a single endpoint and allows clients to request exactly the data\n      they need through queries and mutations covering catalog browsing, product search,\n      cart management, checkout, customer accounts, and order history.\n\n  - aid: magento:soap-api\n    name: Magento SOAP API\n    tags:\n      - E-Commerce\n      - Integration\n      - SOAP\n      - Web Services\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://your-store.example.com/soap\n    humanURL: https://developer.adobe.com/commerce/webapi/get-started/soap-web-api-calls/\n    properties:\n      - url: https://developer.adobe.com/commerce/webapi/get-started/soap-web-api-calls/\n        type: Documentation\n      - url: wsdl/magento-soap.wsdl\n        type: WSDL\n    description: >-\n      The Adobe Commerce SOAP API exposes the same service contracts as\
  \ the REST API\n      through a WSDL 1.2 interface compliant with WS-I 2.0 Basic Profile. It allows\n      enterprise systems and legacy integrations to interact with Adobe Commerce store\n      data using standard SOAP tooling. Developers can retrieve the WSDL for any service\n      or combination of services by appending query parameters to the SOAP endpoint\n      URL.\n\n  - aid: magento:webhooks\n    name: Adobe Commerce Webhooks\n    tags:\n      - E-Commerce\n      - Events\n      - Extensibility\n      - Real-Time\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.adobe.com/commerce/extensibility/webhooks/\n    properties:\n      - url: https://developer.adobe.com/commerce/extensibility/webhooks/\n        type: Documentation\n      - url: asyncapi/magento-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      Adobe Commerce Webhooks enable\
  \ developers to configure synchronous HTTP callbacks\n      that fire when specific events occur within a Commerce instance, allowing external\n      systems to react in real time to store activity. Webhooks can intercept and\n      modify request data before Commerce processes it, or trigger outbound notifications\n      after an event completes.\n\n  - aid: magento:admin-ui-sdk\n    name: Adobe Commerce Admin UI SDK\n    tags:\n      - Admin Panel\n      - App Builder\n      - E-Commerce\n      - Extensibility\n      - UI Extensions\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.adobe.com/commerce/extensibility/admin-ui-sdk/\n    properties:\n      - url: https://developer.adobe.com/commerce/extensibility/admin-ui-sdk/\n        type: Documentation\n    description: >-\n      The Adobe Commerce Admin UI SDK enables App Builder developers to extend the\n      Commerce Admin panel\
  \ with custom menus, pages, and UI components built as out-of-process\n      applications. Rather than modifying the Commerce codebase directly, developers\n      build React-based UIs hosted on Adobe App Builder infrastructure and surface\n      them inside the Admin through the SDK's extension point mechanism.\n\n  - aid: magento:events\n    name: Adobe Commerce Eventing\n    tags:\n      - Adobe I/O\n      - App Builder\n      - E-Commerce\n      - Events\n      - Extensibility\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://developer.adobe.com/commerce/extensibility/events/\n    properties:\n      - url: https://developer.adobe.com/commerce/extensibility/events/\n        type: Documentation\n      - url: asyncapi/magento-events-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      Adobe Commerce Eventing provides an asynchronous event-driven integration framework\n      that\
  \ publishes Commerce business events to Adobe I/O Events, enabling App Builder\n      applications and other Adobe Experience Cloud services to subscribe and react\n      to store activity. Supported event types cover the full commerce lifecycle including\n      order placement, customer registration, product updates, inventory changes,\n      and payment processing.\n\ncommon:\n  - url: json-ld/magento-context.jsonld\n    type: JSON-LD\n  - url: json-schema/magento-order-schema.json\n    type: JSONSchema\n  - url: json-schema/magento-product-schema.json\n    type: JSONSchema\ndescription: >-\n  Overview of the Adobe Commerce and Magento Open Source REST API documentation.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/magento/refs/heads/main/apis.yml
use_cases: []
---
