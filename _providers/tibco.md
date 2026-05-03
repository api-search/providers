---
api_count: 5
api_specs:
- filename: openapi.json
  format: json
  label: TIBCO Cloud Integration API
  slug: ''
  spec_type: OpenAPI
  url: https://integration.cloud.tibco.com/docs/api/openapi.json
- filename: io-docs
  format: yaml
  label: TIBCO Mashery API Management
  slug: ''
  spec_type: OpenAPI
  url: https://developer.mashery.com/io-docs
- filename: tibco-businessevents-openapi.yml
  format: yaml
  label: TIBCO BusinessEvents API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tibco/refs/heads/main/openapi/tibco-businessevents-openapi.yml
- filename: tibco-messaging-asyncapi.yml
  format: yaml
  label: TIBCO Messaging API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/tibco/refs/heads/main/asyncapi/tibco-messaging-asyncapi.yml
- filename: tibco-spotfire-openapi.yml
  format: yaml
  label: TIBCO Spotfire Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tibco/refs/heads/main/openapi/tibco-spotfire-openapi.yml
apis:
- description: API for TIBCO Cloud Integration platform enabling application integration, API management, and business process automation.
  name: TIBCO Cloud Integration API
  slug: ''
- description: API management platform for designing, building, securing, and analyzing APIs.
  name: TIBCO Mashery API Management
  slug: ''
- description: Complex event processing and decision management API for real-time business operations.
  name: TIBCO BusinessEvents API
  slug: ''
- description: Enterprise messaging API supporting EMS (Enterprise Message Service) and FTL (Fast Transport Layer).
  name: TIBCO Messaging API
  slug: ''
- description: Analytics and data visualization API for embedded analytics and automated workflows.
  name: TIBCO Spotfire Analytics API
  slug: ''
asyncapis:
- description: Enterprise messaging API supporting TIBCO Enterprise Message Service (EMS) and FTL (TIBCO FTL) for reliable, high-performance messaging. Supports JMS-compatible publish-subscribe and point-to-point me
  name: TIBCO Messaging API
  slug: tibco-messaging-asyncapi
common:
- title: ''
  type: Portal
  url: https://developer.tibco.com
- title: ''
  type: Documentation
  url: https://docs.tibco.com
- title: ''
  type: Support
  url: https://support.tibco.com
- title: ''
  type: Status
  url: https://status.tibco.com
- title: ''
  type: Blog
  url: https://www.tibco.com/blog
- title: ''
  type: GitHub
  url: https://github.com/tibco
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/tibco
- title: ''
  type: Twitter
  url: https://twitter.com/tibco
- title: ''
  type: Terms of Service
  url: https://www.tibco.com/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://www.tibco.com/legal/privacy
- title: ''
  type: JSON-LD
  url: json-ld/tibco-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/tibco-integration-app-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tibco-api-service-schema.json
created: '2024'
description: APIs and services provided by TIBCO Software Inc., a global leader in integration, API management, and analytics software.
features: []
image: https://www.tibco.com/sites/tibco/files/media_entity/2021-04/TIBCO-logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Tibco Context
  property_count: 13
  slug: tibco-context
layout: provider
modified: '2026-03-16'
name: TIBCO
skills: []
slug: tibco
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: TIBCO\nsegments:\n  - iPaaS\ndescription: >-\n  APIs and services provided by TIBCO Software Inc., a global leader in integration,\n  API management, and analytics software.\nimage: https://www.tibco.com/sites/tibco/files/media_entity/2021-04/TIBCO-logo.svg\nurl: https://www.tibco.com\ncreated: '2024'\nmodified: '2026-03-16'\nspecificationVersion: '0.18'\ntags:\n  - Analytics\n  - API Management\n  - Cloud\n  - Enterprise Software\n  - Integration\n  - Messaging\n  - Real-Time Data\napis:\n  - name: TIBCO Cloud Integration API\n    description: >-\n      API for TIBCO Cloud Integration platform enabling application integration, API\n      management, and business process automation.\n    image: https://www.tibco.com/sites/tibco/files/media_entity/2021-04/TIBCO-logo.svg\n    humanURL: https://integration.cloud.tibco.com/\n    baseURL: https://integration.cloud.tibco.com/api/v1\n    tags:\n      - Cloud\n      - Integration\n      - iPaaS\n    properties:\n      - type:\
  \ Documentation\n        url: https://integration.cloud.tibco.com/docs/\n      - type: OpenAPI\n        url: https://integration.cloud.tibco.com/docs/api/openapi.json\n      - type: Authentication\n        url: https://integration.cloud.tibco.com/docs/authentication\n      - type: OpenAPI\n        url: openapi/tibco-cloud-integration-openapi.yml\n  - name: TIBCO Mashery API Management\n    description: >-\n      API management platform for designing, building, securing, and analyzing APIs.\n    image: https://www.tibco.com/sites/tibco/files/media_entity/2021-04/TIBCO-logo.svg\n    humanURL: https://www.tibco.com/products/api-management\n    baseURL: https://api.mashery.com\n    tags:\n      - Analytics\n      - API Management\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developer.mashery.com/docs\n      - type: OpenAPI\n        url: https://developer.mashery.com/io-docs\n      - type: Portal\n        url: https://developer.mashery.com\n      - type:\
  \ OpenAPI\n        url: openapi/tibco-mashery-openapi.yml\n  - name: TIBCO BusinessEvents API\n    description: >-\n      Complex event processing and decision management API for real-time business\n      operations.\n    image: https://www.tibco.com/sites/tibco/files/media_entity/2021-04/TIBCO-logo.svg\n    humanURL: https://www.tibco.com/products/tibco-businessevents\n    baseURL: https://api.tibco.com/businessevents/v1\n    tags:\n      - Decision Management\n      - Event Processing\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://docs.tibco.com/products/tibco-businessevents\n      - type: SDK\n        url: https://docs.tibco.com/products/tibco-businessevents/sdk\n      - type: OpenAPI\n        url: openapi/tibco-businessevents-openapi.yml\n  - name: TIBCO Messaging API\n    description: >-\n      Enterprise messaging API supporting EMS (Enterprise Message Service) and FTL\n      (Fast Transport Layer).\n    image: https://www.tibco.com/sites/tibco/files/media_entity/2021-04/TIBCO-logo.svg\n\
  \    humanURL: https://www.tibco.com/products/tibco-enterprise-message-service\n    baseURL: https://messaging.cloud.tibco.com/api/v1\n    tags:\n      - JMS\n      - Messaging\n      - Publish-Subscribe\n    properties:\n      - type: Documentation\n        url: https://docs.tibco.com/products/tibco-enterprise-message-service\n      - type: Protocol\n        url: https://docs.tibco.com/products/tibco-enterprise-message-service/protocol-reference\n      - type: AsyncAPI\n        url: asyncapi/tibco-messaging-asyncapi.yml\n  - name: TIBCO Spotfire Analytics API\n    description: >-\n      Analytics and data visualization API for embedded analytics and automated workflows.\n    image: https://www.tibco.com/sites/tibco/files/media_entity/2021-04/TIBCO-logo.svg\n    humanURL: https://www.tibco.com/products/tibco-spotfire\n    baseURL: https://spotfire.cloud.tibco.com/api/rest/v1\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Visualization\n    properties:\n      - type:\
  \ Documentation\n        url: https://docs.tibco.com/products/tibco-spotfire/latest\n      - type: API Reference\n        url: https://docs.tibco.com/pub/spotfire_server/latest/doc/api/TIB_sfire_server_tsas_admin_api/index.html\n      - type: JavaScript API\n        url: https://docs.tibco.com/pub/spotfire/latest/doc/api/TIB_sfire-jsapi/index.html\n      - type: OpenAPI\n        url: openapi/tibco-spotfire-openapi.yml\ncommon:\n  - type: Portal\n    url: https://developer.tibco.com\n  - type: Documentation\n    url: https://docs.tibco.com\n  - type: Support\n    url: https://support.tibco.com\n  - type: Status\n    url: https://status.tibco.com\n  - type: Blog\n    url: https://www.tibco.com/blog\n  - type: GitHub\n    url: https://github.com/tibco\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/tibco\n  - type: Twitter\n    url: https://twitter.com/tibco\n  - type: Terms of Service\n    url: https://www.tibco.com/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://www.tibco.com/legal/privacy\n\
  \  - type: JSON-LD\n    url: json-ld/tibco-context.jsonld\n  - type: JSONSchema\n    url: json-schema/tibco-integration-app-schema.json\n  - type: JSONSchema\n    url: json-schema/tibco-api-service-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tibco/refs/heads/main/apis.yml
tags:
- Analytics
- API Management
- Cloud
- Enterprise Software
- Integration
- Messaging
- Real-Time Data
url: https://www.tibco.com
use_cases: []
---
