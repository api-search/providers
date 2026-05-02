---
api_count: 1
apis:
- description: Programmatic management of Azure Logic Apps automated workflows including workflow definitions, triggers, actions, runs, integration accounts, and connectors.
  name: Azure Logic Apps REST API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/azure/logic-apps/
- title: ''
  type: Pricing
  url: https://azure.microsoft.com/en-us/pricing/details/logic-apps/
- title: ''
  type: StatusPage
  url: https://status.azure.com/
- title: ''
  type: Blog
  url: https://azure.microsoft.com/en-us/blog/
- title: ''
  type: Support
  url: https://azure.microsoft.com/en-us/support/
- title: ''
  type: TermsOfService
  url: https://azure.microsoft.com/en-us/support/legal/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
created: '2026-03-13'
description: Azure Logic Apps is a cloud platform for creating and running automated workflows that integrate apps, data, services, and systems. It provides a visual designer and over 400 connectors to build event-driven, scheduled, and on-demand integrations.
features:
- description: Build workflows visually using a drag-and-drop designer in the Azure portal or Visual Studio Code.
  name: Visual Workflow Designer
- description: Connect to hundreds of SaaS apps, databases, file systems, and Azure services with prebuilt connectors.
  name: 400+ Connectors
- description: Start workflows from HTTP requests, scheduled timers, file changes, or events from connected services.
  name: Event-Driven Triggers
- description: Process EDI, AS2, X12, and EDIFACT messages with integration accounts for partner-to-partner workflows.
  name: B2B Integration
- description: Run long-running stateful workflows or short-lived stateless workflows for low-latency scenarios.
  name: Stateful and Stateless Workflows
- description: Connect to on-premises data sources using on-premises data gateways and integration service environments.
  name: Hybrid Connectivity
image: https://azure.microsoft.com/svghandler/logic-apps/
integrations:
- description: Invoke Azure Functions from workflows for custom code execution.
  name: Azure Functions
- description: Send and receive messages through Azure Service Bus queues and topics.
  name: Azure Service Bus
- description: Integrate with Outlook, SharePoint, OneDrive, and Teams using Office 365 connectors.
  name: Office 365
- description: Connect to Salesforce CRM for record creation, updates, and event-driven workflows.
  name: Salesforce
- description: Expose and manage workflow endpoints through Azure API Management.
  name: Azure API Management
layout: provider
modified: '2026-04-28'
name: Azure Logic Apps
skills: []
slug: microsoft-azure-logic-apps
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Azure Logic Apps\ndescription: >-\n  Azure Logic Apps is a cloud platform for creating and running automated\n  workflows that integrate apps, data, services, and systems. It provides a\n  visual designer and over 400 connectors to build event-driven, scheduled, and\n  on-demand integrations.\nimage: https://azure.microsoft.com/svghandler/logic-apps/\nurl: https://azure.microsoft.com/en-us/services/logic-apps/\ncreated: '2026-03-13'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\ntags:\n  - Automation\n  - Azure\n  - Integration\n  - iPaaS\n  - Workflow\napis:\n  - name: Azure Logic Apps REST API\n    description: >-\n      Programmatic management of Azure Logic Apps automated workflows including\n      workflow definitions, triggers, actions, runs, integration accounts, and\n      connectors.\n    image: https://azure.microsoft.com/svghandler/logic-apps/\n    humanURL: https://learn.microsoft.com/en-us/rest/api/logic/\n    baseURL: https://management.azure.com\n\
  \    tags:\n      - Automation\n      - Integration\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/logic-apps/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/logic/\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/rest/api/azure/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/azure/logic-apps/quickstart-create-first-logic-app-workflow\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/logic-apps/\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/python/api/overview/azure/mgmt-logic-readme\n        title: Python SDK\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/dotnet/api/overview/azure/resourcemanager.logic-readme\n        title: .NET SDK\n    contact:\n      - type: Support\n        url: https://azure.microsoft.com/en-us/support/\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/azure/logic-apps/\n  - type: Pricing\n    url: https://azure.microsoft.com/en-us/pricing/details/logic-apps/\n  - type: StatusPage\n    url: https://status.azure.com/\n  - type: Blog\n    url: https://azure.microsoft.com/en-us/blog/\n  - type: Support\n    url: https://azure.microsoft.com/en-us/support/\n  - type: TermsOfService\n    url: https://azure.microsoft.com/en-us/support/legal/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Features\n    data:\n      - name: Visual Workflow Designer\n        description: Build workflows visually using a drag-and-drop designer in the Azure portal or Visual Studio Code.\n      - name: 400+ Connectors\n        description: Connect to hundreds of SaaS apps, databases, file systems, and Azure services with prebuilt connectors.\n\
  \      - name: Event-Driven Triggers\n        description: Start workflows from HTTP requests, scheduled timers, file changes, or events from connected services.\n      - name: B2B Integration\n        description: Process EDI, AS2, X12, and EDIFACT messages with integration accounts for partner-to-partner workflows.\n      - name: Stateful and Stateless Workflows\n        description: Run long-running stateful workflows or short-lived stateless workflows for low-latency scenarios.\n      - name: Hybrid Connectivity\n        description: Connect to on-premises data sources using on-premises data gateways and integration service environments.\n  - type: UseCases\n    data:\n      - name: Enterprise Application Integration\n        description: Connect SaaS apps, databases, and on-premises systems for end-to-end business process automation.\n      - name: B2B and EDI Processing\n        description: Exchange business documents with partners using industry-standard EDI protocols.\n      -\
  \ name: Event-Driven Automation\n        description: Trigger workflows based on events from Azure services, third-party APIs, or scheduled timers.\n      - name: Data Transformation\n        description: Transform and route data between systems using built-in mapping and conversion capabilities.\n  - type: Integrations\n    data:\n      - name: Azure Functions\n        description: Invoke Azure Functions from workflows for custom code execution.\n      - name: Azure Service Bus\n        description: Send and receive messages through Azure Service Bus queues and topics.\n      - name: Office 365\n        description: Integrate with Outlook, SharePoint, OneDrive, and Teams using Office 365 connectors.\n      - name: Salesforce\n        description: Connect to Salesforce CRM for record creation, updates, and event-driven workflows.\n      - name: Azure API Management\n        description: Expose and manage workflow endpoints through Azure API Management.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-logic-apps/refs/heads/main/apis.yml
tags:
- Automation
- Azure
- Integration
- iPaaS
- Workflow
url: https://azure.microsoft.com/en-us/services/logic-apps/
use_cases:
- description: Connect SaaS apps, databases, and on-premises systems for end-to-end business process automation.
  name: Enterprise Application Integration
- description: Exchange business documents with partners using industry-standard EDI protocols.
  name: B2B and EDI Processing
- description: Trigger workflows based on events from Azure services, third-party APIs, or scheduled timers.
  name: Event-Driven Automation
- description: Transform and route data between systems using built-in mapping and conversion capabilities.
  name: Data Transformation
---
