---
api_count: 2
apis:
- description: Azure Service Bus REST API provides operations for sending and receiving messages through queues and topics with support for sessions, dead-lettering, scheduled delivery, duplicate detection, and tran
  name: Azure Service Bus REST API
  slug: rest-api
- description: The management REST API enables namespace, queue, topic, and subscription configuration through Azure Resource Manager, including SKU, network rules, authorization rules, and disaster recovery configu
  name: Azure Service Bus Management REST API
  slug: management-api
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/service-bus/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/service-bus-messaging/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-quickstart-portal
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-dotnet-get-started-with-queues
- title: ''
  type: Status
  url: https://azure.status.microsoft/en-us/status
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://support.microsoft.com/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/product/service-bus/
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/azureservicebus
created: '2026-03-13'
description: Azure Service Bus is a fully managed enterprise message broker with message queues and publish-subscribe topics. It enables decoupling applications and services with reliable asynchronous messaging, supporting sessions, dead-lettering, scheduled delivery, duplicate detection, and transactions.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Azure Service Bus
skills: []
slug: microsoft-azure-service-bus
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-azure-service-bus\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-service-bus/refs/heads/main/apis.yml\nname: Azure Service Bus\ndescription: >-\n  Azure Service Bus is a fully managed enterprise message broker with message\n  queues and publish-subscribe topics. It enables decoupling applications and\n  services with reliable asynchronous messaging, supporting sessions, dead-lettering,\n  scheduled delivery, duplicate detection, and transactions.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Enterprise Messaging\n  - Message Broker\n  - Messaging\n  - Publish Subscribe\n  - Queues\n  - Topics\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\napis:\n  - aid: microsoft-azure-service-bus:rest-api\n    name: Azure Service Bus REST API\n    description: >-\n      Azure Service Bus REST API provides operations for sending and receiving\n      messages through queues\
  \ and topics with support for sessions, dead-lettering,\n      scheduled delivery, duplicate detection, and transactions.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/rest/api/servicebus/\n    baseURL: https://{namespace}.servicebus.windows.net/\n    tags:\n      - Messaging\n      - Queues\n      - Subscriptions\n      - Topics\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/servicebus/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/rest/api/eventhub/authenticate-shared-access-signature\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/rest/api/servicebus/resourceprovider\n  - aid: microsoft-azure-service-bus:management-api\n    name: Azure Service Bus Management REST API\n    description: >-\n      The management REST API enables namespace, queue, topic, and subscription\n      configuration\
  \ through Azure Resource Manager, including SKU, network rules,\n      authorization rules, and disaster recovery configuration.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/rest/api/servicebus/controlplane-stable/\n    baseURL: https://management.azure.com/\n    tags:\n      - Management\n      - Namespaces\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/servicebus/controlplane-stable/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/active-directory/develop/authentication-flows-app-scenarios\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/service-bus/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/service-bus-messaging/\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-quickstart-portal\n\
  \  - type: SDKs\n    url: https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-dotnet-get-started-with-queues\n  - type: Status\n    url: https://azure.status.microsoft/en-us/status\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Support\n    url: https://support.microsoft.com/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/product/service-bus/\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/azureservicebus\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-service-bus/refs/heads/main/apis.yml
tags:
- Enterprise Messaging
- Message Broker
- Messaging
- Publish Subscribe
- Queues
- Topics
url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-service-bus/refs/heads/main/apis.yml
use_cases: []
---
