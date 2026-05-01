---
api_count: 5
api_specs:
- filename: doordash-drive-openapi.yml
  format: yaml
  label: DoorDash Drive API
  slug: drive-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/openapi/doordash-drive-openapi.yml
- filename: doordash-drive-classic-openapi.yml
  format: yaml
  label: DoorDash Drive Classic API
  slug: drive-classic-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/openapi/doordash-drive-classic-openapi.yml
- filename: doordash-marketplace-openapi.yml
  format: yaml
  label: DoorDash Marketplace API
  slug: marketplace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/openapi/doordash-marketplace-openapi.yml
- filename: doordash-item-management-openapi.yml
  format: yaml
  label: DoorDash Item Management API
  slug: marketplace-item-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/openapi/doordash-item-management-openapi.yml
- filename: doordash-reporting-openapi.yml
  format: yaml
  label: DoorDash Reporting API
  slug: reporting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/openapi/doordash-reporting-openapi.yml
apis:
- description: The DoorDash Drive API enables businesses to request on-demand deliveries fulfilled by DoorDash's fleet of Dashers. It provides endpoints for checking delivery serviceability, getting delivery quotes,
  name: DoorDash Drive API
  slug: drive-api
- description: The DoorDash Drive Classic API is the legacy version of the Drive API, designed for large enterprises and middleware providers who require extensive configuration and customizability for their deliver
  name: DoorDash Drive Classic API
  slug: drive-classic-api
- description: The DoorDash Marketplace API allows merchants and third-party providers to integrate directly with the DoorDash marketplace for order management, menu synchronization, and store operations. It support
  name: DoorDash Marketplace API
  slug: marketplace-api
- description: The DoorDash Item Management API enables merchants and integration partners to programmatically manage their item catalogs, inventory levels, pricing, and other product attributes on the DoorDash plat
  name: DoorDash Item Management API
  slug: marketplace-item-management-api
- description: The DoorDash Reporting API provides approved partners with access to standardized financial, operations, and menu reporting data. It offers a POST endpoint for creating report requests and a GET endpo
  name: DoorDash Reporting API
  slug: reporting-api
asyncapis:
- description: 'DoorDash Drive sends webhook notifications for delivery status updates, enabling near-real-time information flow from DoorDash and Dashers to partner applications. Webhooks support scenarios like map '
  name: DoorDash Drive Delivery Webhooks
  slug: doordash-drive-webhooks-asyncapi
- description: DoorDash Marketplace sends webhook notifications for order events, menu processing status, delivery status updates, and store onboarding events. Each environment (Sandbox and Production) supports only
  name: DoorDash Marketplace Webhooks
  slug: doordash-marketplace-webhooks-asyncapi
- description: DoorDash Reporting API sends webhook notifications when report generation is complete and the report is ready for download. Partners configure a webhook endpoint to receive these notifications instead
  name: DoorDash Reporting Webhooks
  slug: doordash-reporting-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/doordash-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/doordash-delivery-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/doordash-order-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/doordash-menu-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/doordash-report-schema.json
created: ''
description: Production access to the Drive API is currently restricted, and we cannot provide a timeline for certification following development. If you have not completed development and submitted a production access request, we recommend pausing development. Contact us here to record your interest.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Doordash Context
  property_count: 7
  slug: doordash-context
layout: provider
modified: '2026-04-28'
name: doordash
skills: []
slug: doordash
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: doordash\nurl: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/apis.yml\napis:\n  - aid: doordash:drive-api\n    name: DoorDash Drive API\n    tags:\n      - Delivery\n      - Food Delivery\n      - Last Mile\n      - Logistics\n      - On-Demand\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://openapi.doordash.com/drive/v2\n    humanURL: https://developer.doordash.com/en-US/docs/drive/overview/about_drive/\n    properties:\n      - url: https://developer.doordash.com/en-US/docs/drive/overview/about_drive/\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/doordash-drive-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/doordash-drive-webhooks-asyncapi.yml\n    description: >-\n      The DoorDash Drive API enables businesses to request on-demand deliveries\n      fulfilled by DoorDash's fleet of Dashers. It provides endpoints for\n      checking delivery\
  \ serviceability, getting delivery quotes, creating and\n      managing deliveries, and tracking delivery status in real time. The API\n      uses JWT-based authentication and is designed for businesses that want to\n      offer delivery from their own ordering experience while leveraging\n      DoorDash's logistics network.\n  - aid: doordash:drive-classic-api\n    name: DoorDash Drive Classic API\n    tags:\n      - Delivery\n      - Enterprise\n      - Food Delivery\n      - Last Mile\n      - Logistics\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://openapi.doordash.com/drive/v1\n    humanURL: https://developer.doordash.com/en-US/docs/drive_classic/overview/about_drive_classic/\n    properties:\n      - url: https://developer.doordash.com/en-US/docs/drive_classic/overview/about_drive_classic/\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/doordash-drive-classic-openapi.yml\n    description: >-\n\
  \      The DoorDash Drive Classic API is the legacy version of the Drive API, designed\n      for large enterprises and middleware providers who require extensive configuration\n      and customizability for their delivery integrations. It provides endpoints for\n      managing businesses, stores, and deliveries through DoorDash's logistics platform.\n      The API uses JWT-based Bearer token authentication and operates at the v1 endpoint\n      path.\n  - aid: doordash:marketplace-api\n    name: DoorDash Marketplace API\n    tags:\n      - Food Delivery\n      - Marketplace\n      - Orders\n      - Restaurants\n      - Retail\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://openapi.doordash.com/marketplace\n    humanURL: https://developer.doordash.com/en-US/docs/marketplace/overview/about_marketplace/\n    properties:\n      - url: https://developer.doordash.com/en-US/docs/marketplace/overview/about_marketplace/\n        type:\
  \ Documentation\n      - type: OpenAPI\n        url: openapi/doordash-marketplace-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/doordash-marketplace-webhooks-asyncapi.yml\n    description: >-\n      The DoorDash Marketplace API allows merchants and third-party providers\n      to integrate directly with the DoorDash marketplace for order management,\n      menu synchronization, and store operations. It supports receiving orders\n      from DoorDash, updating order statuses, and managing menu availability\n      in real time. The API is not generally available and access is granted\n      through a selective partner program where DoorDash evaluates integration\n      quality and business fit.\n  - aid: doordash:marketplace-item-management-api\n    name: DoorDash Item Management API\n    tags:\n      - Catalog\n      - Inventory\n      - Menus\n      - Pricing\n      - Retail\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL:\
  \ https://openapi.doordash.com/marketplace\n    humanURL: https://developer.doordash.com/en-US/api/marketplace_v2/\n    properties:\n      - url: https://developer.doordash.com/en-US/api/marketplace_v2/\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/doordash-item-management-openapi.yml\n    description: >-\n      The DoorDash Item Management API enables merchants and integration\n      partners to programmatically manage their item catalogs, inventory\n      levels, pricing, and other product attributes on the DoorDash platform.\n      It provides endpoints for creating, updating, and retrieving item data\n      across stores. This API is particularly useful for retail and grocery\n      partners who need to keep large catalogs synchronized between their\n      own systems and DoorDash's marketplace.\n  - aid: doordash:reporting-api\n    name: DoorDash Reporting API\n    tags:\n      - Analytics\n      - Data\n      - Financial\n      - Operations\n      - Reporting\n\
  \    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://openapi.doordash.com/dataexchange/v1\n    humanURL: https://developer.doordash.com/en-US/docs/reporting/overview/about_reporting/\n    properties:\n      - url: https://developer.doordash.com/en-US/docs/reporting/overview/about_reporting/\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/doordash-reporting-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/doordash-reporting-webhooks-asyncapi.yml\n    description: >-\n      The DoorDash Reporting API provides approved partners with access to standardized\n      financial, operations, and menu reporting data. It offers a POST endpoint for\n      creating report requests and a GET endpoint for retrieving report download links,\n      along with webhook notifications when reports are ready.\ncommon:\n  - type: JSON-LD\n    url: json-ld/doordash-context.jsonld\n  - type: JSONSchema\n    url: json-schema/doordash-delivery-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/doordash-order-schema.json\n  - type: JSONSchema\n    url: json-schema/doordash-menu-schema.json\n  - type: JSONSchema\n    url: json-schema/doordash-report-schema.json\nmodified: '2026-04-28'\ndescription: >-\n  Production access to the Drive API is currently restricted, and we cannot provide\n  a timeline for certification following development. If you have not completed development\n  and submitted a production access request, we recommend pausing development. Contact\n  us here to record your interest.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/doordash/refs/heads/main/apis.yml
use_cases: []
---
