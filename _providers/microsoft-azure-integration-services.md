---
api_count: 5
apis:
- description: Azure API Management is a fully managed service that enables organizations to publish, secure, transform, maintain, and monitor APIs. It provides a gateway for routing API calls, enforcing usage polic
  name: Azure API Management
  slug: azure-api-management
- description: Azure Logic Apps is a cloud-based platform for creating and running automated workflows that integrate apps, data, services, and systems. It provides a visual designer and hundreds of pre-built connec
  name: Azure Logic Apps
  slug: azure-logic-apps
- description: Azure Service Bus is a fully managed enterprise message broker with message queues and publish-subscribe topics. It decouples applications and services from each other, providing reliable asynchronous
  name: Azure Service Bus
  slug: azure-service-bus
- description: Azure Event Grid is a highly scalable, fully managed publish-subscribe event distribution service. It enables event-driven architectures by routing events from Azure services and custom sources to eve
  name: Azure Event Grid
  slug: azure-event-grid
- description: Azure Event Hubs is a big data streaming platform and event ingestion service capable of receiving and processing millions of events per second. It is used for telemetry ingestion, application logging
  name: Azure Event Hubs
  slug: azure-event-hubs
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Website
  url: https://azure.microsoft.com/en-us/products/category/integration
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/?product=integration
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/integration-services/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/category/azure/blog/integrationsonazureblog
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: Status
  url: https://azure.status.microsoft/en-us/status
- title: ''
  type: Terms of Service
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: YouTube
  url: https://www.youtube.com/@MicrosoftAzure
- title: ''
  type: Community
  url: https://techcommunity.microsoft.com/category/azure
- title: ''
  type: Console
  url: https://portal.azure.com/
- title: ''
  type: Login
  url: https://portal.azure.com/
- title: ''
  type: Sign Up
  url: https://azure.microsoft.com/en-us/free/
created: '2026-03-16'
description: Microsoft Azure Integration Services is a collection of cloud-based integration capabilities that connect applications, data, and processes across cloud and on-premises environments. It includes API Management, Logic Apps, Service Bus, Event Grid, and Event Hubs to enable enterprise integration, messaging, and event-driven architectures.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Azure Integration Services
skills: []
slug: microsoft-azure-integration-services
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-azure-integration-services\nname: Microsoft Azure Integration Services\ndescription: >-\n  Microsoft Azure Integration Services is a collection of cloud-based integration\n  capabilities that connect applications, data, and processes across cloud and\n  on-premises environments. It includes API Management, Logic Apps, Service Bus,\n  Event Grid, and Event Hubs to enable enterprise integration, messaging, and\n  event-driven architectures.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Management\n  - Enterprise\n  - Event-Driven\n  - Integration\n  - Messaging\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/microsoft-azure-integration-services/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: microsoft-azure-integration-services:azure-api-management\n    name: Azure API Management\n    description: >-\n      Azure API\
  \ Management is a fully managed service that enables organizations\n      to publish, secure, transform, maintain, and monitor APIs. It provides a\n      gateway for routing API calls, enforcing usage policies, and providing\n      developer portal capabilities for API consumers.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/azure/api-management/\n    baseURL: https://management.azure.com/\n    tags:\n      - API Gateway\n      - API Management\n      - Azure\n      - Developer Portal\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/api-management/\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/apimanagement/\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/api-management/get-started-create-service-instance\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/api-management/\n\
  \      - type: Change Log\n        url: https://learn.microsoft.com/en-us/azure/api-management/release-notes\n  - aid: microsoft-azure-integration-services:azure-logic-apps\n    name: Azure Logic Apps\n    description: >-\n      Azure Logic Apps is a cloud-based platform for creating and running automated\n      workflows that integrate apps, data, services, and systems. It provides a\n      visual designer and hundreds of pre-built connectors to build workflows\n      without writing code, enabling business process automation and enterprise\n      integration scenarios.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/azure/logic-apps/\n    baseURL: https://management.azure.com/\n    tags:\n      - Azure\n      - Integration\n      - Low-Code\n      - Workflow Automation\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/logic-apps/\n      - type: Reference\n\
  \        url: https://learn.microsoft.com/en-us/rest/api/logic/\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/logic-apps/quickstart-create-example-consumption-workflow\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/logic-apps/\n      - type: Change Log\n        url: https://learn.microsoft.com/en-us/azure/logic-apps/logic-apps-release-notes\n  - aid: microsoft-azure-integration-services:azure-service-bus\n    name: Azure Service Bus\n    description: >-\n      Azure Service Bus is a fully managed enterprise message broker with message\n      queues and publish-subscribe topics. It decouples applications and services\n      from each other, providing reliable asynchronous message delivery, ordered\n      messaging, dead-lettering, and session support for complex integration\n      workflows.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/azure/service-bus-messaging/\n\
  \    baseURL: https://management.azure.com/\n    tags:\n      - Azure\n      - Message Queue\n      - Messaging\n      - Publish-Subscribe\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/service-bus-messaging/\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/servicebus/\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-quickstart-portal\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/service-bus/\n      - type: Client Libraries\n        url: https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-messaging-overview#client-libraries\n  - aid: microsoft-azure-integration-services:azure-event-grid\n    name: Azure Event Grid\n    description: >-\n      Azure Event Grid is a highly scalable, fully managed publish-subscribe event\n      distribution service. It enables event-driven architectures\
  \ by routing events\n      from Azure services and custom sources to event handlers such as Azure\n      Functions, Logic Apps, and webhooks, with support for filtering and fanout.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/azure/event-grid/\n    baseURL: https://management.azure.com/\n    tags:\n      - Azure\n      - Event-Driven\n      - Eventing\n      - Pub-Sub\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/event-grid/\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/eventgrid/\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/event-grid/custom-event-quickstart-portal\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/event-grid/\n  - aid: microsoft-azure-integration-services:azure-event-hubs\n    name: Azure Event Hubs\n    description:\
  \ >-\n      Azure Event Hubs is a big data streaming platform and event ingestion service\n      capable of receiving and processing millions of events per second. It is used\n      for telemetry ingestion, application logging, and real-time analytics pipelines,\n      with support for Apache Kafka protocol, AMQP, and HTTPS.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/azure/event-hubs/\n    baseURL: https://management.azure.com/\n    tags:\n      - Azure\n      - Big Data\n      - Event Streaming\n      - Kafka\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/event-hubs/\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/eventhub/\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/azure/event-hubs/event-hubs-create\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/event-hubs/\n\
  \      - type: Client Libraries\n        url: https://learn.microsoft.com/en-us/azure/event-hubs/sdks\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Website\n    url: https://azure.microsoft.com/en-us/products/category/integration\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/?product=integration\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/integration-services/\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/\n  - type: Blog\n    url: https://techcommunity.microsoft.com/category/azure/blog/integrationsonazureblog\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/\n  - type: Status\n    url: https://azure.status.microsoft/en-us/status\n  - type: Terms of Service\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: GitHub Organization\n    url: https://github.com/Azure\n\
  \  - type: YouTube\n    url: https://www.youtube.com/@MicrosoftAzure\n  - type: Community\n    url: https://techcommunity.microsoft.com/category/azure\n  - type: Console\n    url: https://portal.azure.com/\n  - type: Login\n    url: https://portal.azure.com/\n  - type: Sign Up\n    url: https://azure.microsoft.com/en-us/free/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-integration-services/refs/heads/main/apis.yml
tags:
- API Management
- Enterprise
- Event-Driven
- Integration
- Messaging
url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-integration-services/refs/heads/main/apis.yml
use_cases: []
---
