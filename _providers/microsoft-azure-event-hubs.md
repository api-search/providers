---
api_count: 4
api_specs:
- filename: resource-manager
  format: yaml
  label: Azure Event Hubs REST API
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/eventhub/resource-manager
- filename: data-plane
  format: yaml
  label: Azure Event Hubs Data Plane API
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/eventhub/data-plane
- filename: azure-event-hubs-messaging-asyncapi.yml
  format: yaml
  label: Azure Event Hubs Messaging API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-event-hubs/refs/heads/main/asyncapi/azure-event-hubs-messaging-asyncapi.yml
apis:
- description: REST API for managing Event Hubs namespaces, event hubs, consumer groups, and sending/receiving events.
  name: Azure Event Hubs REST API
  slug: ''
- description: API for sending and receiving events from Event Hubs.
  name: Azure Event Hubs Data Plane API
  slug: ''
- description: Event-driven messaging API for publishing and consuming events via AMQP 1.0, Kafka, and HTTPS protocols. Supports partitioned event streams, consumer groups, and publisher policies.
  name: Azure Event Hubs Messaging API
  slug: ''
- description: Client libraries for various programming languages to interact with Event Hubs.
  name: Azure Event Hubs SDK
  slug: ''
asyncapis:
- description: Azure Event Hubs is a big data streaming platform and event ingestion service that can receive and process millions of events per second. This AsyncAPI specification describes the event-driven messagi
  name: Azure Event Hubs Messaging API
  slug: azure-event-hubs-messaging-asyncapi
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/#blade/HubsExtension/BrowseResource/resourceType/Microsoft.EventHub%2Fnamespaces
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-quickstart-portal
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/event-hubs/
- title: ''
  type: Service Level Agreement
  url: https://azure.microsoft.com/en-us/support/legal/sla/event-hubs/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/azure/event-hubs/authenticate-application
- title: ''
  type: Best Practices
  url: https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-best-practices
- title: ''
  type: Samples
  url: https://github.com/Azure/azure-event-hubs/tree/master/samples
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/messaging-on-azure-and-net/bg-p/MessagingonAzureBlog
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/event-hubs/
- title: ''
  type: Quotas
  url: https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-quotas
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/azure/event-hubs/sdks
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: Website
  url: https://azure.microsoft.com/en-us/services/event-hubs/
- title: ''
  type: Login
  url: https://portal.azure.com/
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free/
- title: ''
  type: Community
  url: https://learn.microsoft.com/en-us/answers/tags/165/azure-event-hubs/
- title: ''
  type: Security
  url: https://learn.microsoft.com/en-us/azure/event-hubs/network-security
- title: ''
  type: JSON Schema
  url: json-schema/azure-event-hubs-namespace.json
- title: ''
  type: JSON Schema
  url: json-schema/azure-event-hubs-eventhub.json
- title: ''
  type: JSON Schema
  url: json-schema/azure-event-hubs-consumer-group.json
- title: ''
  type: JSON Schema
  url: json-schema/azure-event-hubs-event-data.json
- title: ''
  type: JSON Schema
  url: json-schema/azure-event-hubs-schema-group.json
- title: ''
  type: JSON-LD Context
  url: json-ld/azure-event-hubs-context.jsonld
created: '2024-01-01'
description: Azure Event Hubs is a big data streaming platform and event ingestion service that can receive and process millions of events per second. It provides a distributed stream processing platform with low latency and seamless integration with Azure data and analytics services.
features: []
image: https://azure.microsoft.com/svghandler/event-hubs/
integrations: []
jsonld:
- class_count: 0
  name: Azure Event Hubs Context
  property_count: 15
  slug: azure-event-hubs-context
layout: provider
modified: '2026-04-28'
name: Azure Event Hubs
skills: []
slug: microsoft-azure-event-hubs
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Event Hubs\ndescription: Azure Event Hubs is a big data streaming platform and event ingestion service that can receive and process millions of events per second. It provides a distributed stream processing platform with low latency and seamless integration with Azure data and analytics services.\nimage: https://azure.microsoft.com/svghandler/event-hubs/\ntags:\n  - Big Data\n  - Event Streaming\n  - IoT\n  - Message Ingestion\n  - Real-Time Processing\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\nurl: https://azure.microsoft.com/en-us/services/event-hubs/\napis:\n  - name: Azure Event Hubs REST API\n    description: >-\n      REST API for managing Event Hubs namespaces, event hubs, consumer groups, and\n      sending/receiving events.\n    image: https://azure.microsoft.com/svghandler/event-hubs/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/eventhub/\n    baseURL: https://management.azure.com\n    tags:\n      - Events\n\
  \      - Management\n      - Streaming\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/eventhub/\n      - type: OpenAPI\n        url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/eventhub/resource-manager\n      - type: Swagger\n        url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/eventhub/resource-manager/Microsoft.EventHub/stable/2021-11-01/eventhub.json\n      - type: OpenAPI\n        url: openapi/azure-event-hubs-management-openapi.yml\n  - name: Azure Event Hubs Data Plane API\n    description: >-\n      API for sending and receiving events from Event Hubs.\n    image: https://azure.microsoft.com/svghandler/event-hubs/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/eventhub/event-hubs-runtime-rest\n    baseURL: https://{namespace}.servicebus.windows.net\n    tags:\n      - Data Plane\n      - Receive Events\n      - Send Events\n    properties:\n     \
  \ - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/eventhub/event-hubs-runtime-rest\n      - type: OpenAPI\n        url: https://github.com/Azure/azure-rest-api-specs/tree/main/specification/eventhub/data-plane\n      - type: OpenAPI\n        url: openapi/azure-event-hubs-data-plane-openapi.yml\n  - name: Azure Event Hubs Messaging API\n    description: Event-driven messaging API for publishing and consuming events via AMQP 1.0, Kafka, and HTTPS protocols. Supports partitioned event streams, consumer groups, and publisher policies.\n    image: https://azure.microsoft.com/svghandler/event-hubs/\n    humanURL: https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-features\n    baseURL: https://{namespace}.servicebus.windows.net\n    tags:\n      - AMQP\n      - AsyncAPI\n      - Event Streaming\n      - Kafka\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-features\n\
  \      - type: AsyncAPI\n        url: asyncapi/azure-event-hubs-messaging-asyncapi.yml\n  - name: Azure Event Hubs SDK\n    description: >-\n      Client libraries for various programming languages to interact with Event Hubs.\n    image: https://azure.microsoft.com/svghandler/event-hubs/\n    humanURL: https://learn.microsoft.com/en-us/azure/event-hubs/sdks\n    baseURL: https://{namespace}.servicebus.windows.net\n    tags:\n      - Client Library\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/event-hubs/sdks\n      - type: .NET SDK\n        url: https://www.nuget.org/packages/Azure.Messaging.EventHubs/\n      - type: Java SDK\n        url: https://mvnrepository.com/artifact/com.azure/azure-messaging-eventhubs\n      - type: Python SDK\n        url: https://pypi.org/project/azure-eventhub/\n      - type: JavaScript SDK\n        url: https://www.npmjs.com/package/@azure/event-hubs\n      - type: GitHub\n        url: https://github.com/Azure/azure-sdk-for-net/tree/main/sdk/eventhub\n\
  common:\n  - type: Portal\n    url: https://portal.azure.com/#blade/HubsExtension/BrowseResource/resourceType/Microsoft.EventHub%2Fnamespaces\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-quickstart-portal\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/event-hubs/\n  - type: Service Level Agreement\n    url: https://azure.microsoft.com/en-us/support/legal/sla/event-hubs/\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/azure/event-hubs/authenticate-application\n  - type: Best Practices\n    url: https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-best-practices\n  - type: Samples\n    url: https://github.com/Azure/azure-event-hubs/tree/master/samples\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/\n  - type: Status\n    url: https://status.azure.com/\n  - type: Blog\n    url: https://techcommunity.microsoft.com/t5/messaging-on-azure-and-net/bg-p/MessagingonAzureBlog\n\
  \  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/event-hubs/\n  - type: Quotas\n    url: https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-quotas\n  - type: Terms of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/azure/event-hubs/sdks\n  - type: GitHub Organization\n    url: https://github.com/Azure\n  - type: Website\n    url: https://azure.microsoft.com/en-us/services/event-hubs/\n  - type: Login\n    url: https://portal.azure.com/\n  - type: Sign Up\n    url: https://azure.microsoft.com/en-us/free/\n  - type: Community\n    url: https://learn.microsoft.com/en-us/answers/tags/165/azure-event-hubs/\n  - type: Security\n    url: https://learn.microsoft.com/en-us/azure/event-hubs/network-security\n  - type: JSON Schema\n    url: json-schema/azure-event-hubs-namespace.json\n  - type:\
  \ JSON Schema\n    url: json-schema/azure-event-hubs-eventhub.json\n  - type: JSON Schema\n    url: json-schema/azure-event-hubs-consumer-group.json\n  - type: JSON Schema\n    url: json-schema/azure-event-hubs-event-data.json\n  - type: JSON Schema\n    url: json-schema/azure-event-hubs-schema-group.json\n  - type: JSON-LD Context\n    url: json-ld/azure-event-hubs-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-event-hubs/refs/heads/main/apis.yml
tags:
- Big Data
- Event Streaming
- IoT
- Message Ingestion
- Real-Time Processing
url: https://azure.microsoft.com/en-us/services/event-hubs/
use_cases: []
---
