---
api_count: 1
api_specs:
- filename: microsoft-power-automate-management-api.yaml
  format: yaml
  label: Power Automate Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-automate/refs/heads/main/openapi/microsoft-power-automate-management-api.yaml
apis:
- description: REST API for managing flows, environments, connections, connectors, and flow permissions in Power Automate. Enables programmatic creation, update, deletion, and lifecycle management of cloud flows.
  name: Power Automate Management API
  slug: ''
capabilities:
- description: Workflow capability for managing Power Automate flows, environments, and connectors. Used by automation engineers and platform administrators.
  name: Microsoft Power Automate Flow Automation
  slug: flow-automation
common:
- title: ''
  type: Portal
  url: https://make.powerautomate.com
- title: ''
  type: DeveloperPortal
  url: https://learn.microsoft.com/en-us/power-automate/
- title: ''
  type: Blog
  url: https://powerautomate.microsoft.com/en-us/blog/
- title: ''
  type: Support
  url: https://powerautomate.microsoft.com/en-us/support/
- title: ''
  type: StatusPage
  url: https://status.powerplatform.microsoft.com/
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/powerplatform/power-automate
- title: ''
  type: Pricing
  url: https://powerautomate.microsoft.com/en-us/pricing/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/servicesagreement
- title: ''
  type: GitHubRepository
  url: https://github.com/microsoft/PowerApps-Samples
- title: ''
  type: JSON-LD
  url: json-ld/microsoft-power-automate-management-api-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/microsoft-power-automate-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/flow-automation.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/microsoft-power-automate-vocabulary.yaml
created: '2024'
description: Microsoft Power Automate is a cloud-based service that helps you create automated workflows between your favorite apps and services to synchronize files, get notifications, collect data, and automate business processes. It supports automated, instant, and scheduled cloud flows, as well as desktop flows for robotic process automation.
features:
- description: Create event-triggered automations that run when specific events occur.
  name: Automated Cloud Flows
- description: Start automations on demand with the push of a button.
  name: Instant Cloud Flows
- description: Run automations on a recurring schedule.
  name: Scheduled Cloud Flows
- description: Automate desktop and legacy application tasks using robotic process automation.
  name: Desktop Flows (RPA)
- description: Create flows using natural language descriptions powered by AI.
  name: Copilot Integration
- description: Connect to over 1000 pre-built connectors for Microsoft and third-party services.
  name: 1000+ Connectors
- description: Build custom connectors using OpenAPI definitions.
  name: Custom Connectors
- description: Start from pre-built templates for common automation scenarios.
  name: Flow Templates
- description: Build approval workflows with built-in support for multi-stage approvals.
  name: Approval Workflows
- description: Configure error handling, retry policies, and notifications for flow failures.
  name: Error Handling
image: https://powerautomate.microsoft.com/images/application-logos/svg/powerautomate.svg
integrations:
- description: Deep integration with SharePoint, Outlook, Teams, and other Microsoft 365 apps.
  name: Microsoft 365
- description: Native integration with Dataverse for data storage and management.
  name: Microsoft Dataverse
- description: Connect to Azure Logic Apps, Functions, and other Azure services.
  name: Azure Services
- description: Automate business processes within Dynamics 365 CRM and ERP.
  name: Dynamics 365
- description: Connect to SAP systems for enterprise process automation.
  name: SAP
- description: Integrate with Salesforce for CRM automation workflows.
  name: Salesforce
jsonld:
- class_count: 6
  name: Microsoft Power Automate Management Api Context
  property_count: 17
  slug: microsoft-power-automate-management-api-context
layout: provider
modified: '2026-04-18'
name: Microsoft Power Automate
rules:
- name: Microsoft Power Automate API Rules
  rule_count: 23
  severity_counts:
    error: 15
    hint: 0
    info: 1
    warn: 7
  slug: microsoft-power-automate-spectral-rules
skills: []
slug: microsoft-power-automate
solutions:
- description: Premium plan with advanced connectors, AI Builder, and process mining.
  name: Power Automate Premium
- description: Per-process licensing for unattended RPA and hosted machines.
  name: Power Automate Process
- description: Hosted machine groups for scaling desktop automation.
  name: Power Automate Hosted
source_filename: apis.yml
source_yaml: "aid: microsoft-power-automate\nname: Microsoft Power Automate\ndescription: >-\n  Microsoft Power Automate is a cloud-based service that helps you create\n  automated workflows between your favorite apps and services to synchronize\n  files, get notifications, collect data, and automate business processes. It\n  supports automated, instant, and scheduled cloud flows, as well as desktop\n  flows for robotic process automation.\nimage: https://powerautomate.microsoft.com/images/application-logos/svg/powerautomate.svg\nurl: https://powerautomate.microsoft.com\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Automation\n  - Business Process\n  - Integration\n  - Low-Code\n  - Microsoft\n  - Power Platform\n  - RPA\n  - Workflow\napis:\n  - name: Power Automate Management API\n    description: >-\n      REST API for managing flows, environments, connections, connectors, and\n      flow permissions in Power Automate. Enables programmatic creation,\
  \ update,\n      deletion, and lifecycle management of cloud flows.\n    image: https://powerautomate.microsoft.com/images/application-logos/svg/powerautomate.svg\n    humanURL: https://learn.microsoft.com/en-us/power-automate/web-api\n    baseURL: https://api.flow.microsoft.com\n    tags:\n      - Automation\n      - Connectors\n      - Environments\n      - Flow Management\n      - Flows\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-automate/web-api\n      - type: OpenAPI\n        url: openapi/microsoft-power-automate-management-api.yaml\n      - type: JSONSchema\n        url: json-schema/power-automate-management-api-flow-schema.json\n      - type: JSONSchema\n        url: json-schema/power-automate-management-api-environment-schema.json\n      - type: JSONSchema\n        url: json-schema/power-automate-management-api-flow-run-schema.json\n      - type: JSONSchema\n        url: json-schema/power-automate-management-api-connector-schema.json\n\
  \      - type: JSONStructure\n        url: json-structure/power-automate-management-api-flow-structure.json\n      - type: JSONStructure\n        url: json-structure/power-automate-management-api-environment-structure.json\n      - type: JSONStructure\n        url: json-structure/power-automate-management-api-flow-run-structure.json\n      - type: JSONStructure\n        url: json-structure/power-automate-management-api-connector-structure.json\n      - type: Example\n        url: examples/power-automate-management-api-flow-example.json\n      - type: Example\n        url: examples/power-automate-management-api-environment-example.json\n      - type: Example\n        url: examples/power-automate-management-api-flow-run-example.json\n      - type: Example\n        url: examples/power-automate-management-api-connector-example.json\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-automate/web-api#authentication\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/connectors/flowmanagement/\n\
  common:\n  - type: Portal\n    url: https://make.powerautomate.com\n  - type: DeveloperPortal\n    url: https://learn.microsoft.com/en-us/power-automate/\n  - type: Blog\n    url: https://powerautomate.microsoft.com/en-us/blog/\n  - type: Support\n    url: https://powerautomate.microsoft.com/en-us/support/\n  - type: StatusPage\n    url: https://status.powerplatform.microsoft.com/\n  - type: Training\n    url: https://learn.microsoft.com/en-us/training/powerplatform/power-automate\n  - type: Pricing\n    url: https://powerautomate.microsoft.com/en-us/pricing/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: TermsOfService\n    url: https://www.microsoft.com/en-us/servicesagreement\n  - type: GitHubRepository\n    url: https://github.com/microsoft/PowerApps-Samples\n  - type: JSON-LD\n    url: json-ld/microsoft-power-automate-management-api-context.jsonld\n  - type: SpectralRules\n    url: rules/microsoft-power-automate-spectral-rules.yml\n\
  \  - type: NaftikoCapability\n    url: capabilities/flow-automation.yaml\n  - type: Vocabulary\n    url: vocabulary/microsoft-power-automate-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Automated Cloud Flows\n        description: Create event-triggered automations that run when specific events occur.\n      - name: Instant Cloud Flows\n        description: Start automations on demand with the push of a button.\n      - name: Scheduled Cloud Flows\n        description: Run automations on a recurring schedule.\n      - name: Desktop Flows (RPA)\n        description: Automate desktop and legacy application tasks using robotic process automation.\n      - name: Copilot Integration\n        description: Create flows using natural language descriptions powered by AI.\n      - name: 1000+ Connectors\n        description: Connect to over 1000 pre-built connectors for Microsoft and third-party services.\n      - name: Custom Connectors\n        description: Build custom connectors\
  \ using OpenAPI definitions.\n      - name: Flow Templates\n        description: Start from pre-built templates for common automation scenarios.\n      - name: Approval Workflows\n        description: Build approval workflows with built-in support for multi-stage approvals.\n      - name: Error Handling\n        description: Configure error handling, retry policies, and notifications for flow failures.\n  - type: UseCases\n    data:\n      - name: Email Automation\n        description: Automatically process, route, and respond to emails based on content or sender.\n      - name: Data Synchronization\n        description: Keep data synchronized across multiple systems and applications.\n      - name: Approval Processes\n        description: Automate business approval workflows across teams and departments.\n      - name: Document Processing\n        description: Automate document creation, routing, and archival workflows.\n      - name: IT Process Automation\n        description: Automate\
  \ IT helpdesk tickets, provisioning, and monitoring workflows.\n      - name: Social Media Monitoring\n        description: Track brand mentions and automatically respond or alert teams.\n  - type: Integrations\n    data:\n      - name: Microsoft 365\n        description: Deep integration with SharePoint, Outlook, Teams, and other Microsoft 365 apps.\n      - name: Microsoft Dataverse\n        description: Native integration with Dataverse for data storage and management.\n      - name: Azure Services\n        description: Connect to Azure Logic Apps, Functions, and other Azure services.\n      - name: Dynamics 365\n        description: Automate business processes within Dynamics 365 CRM and ERP.\n      - name: SAP\n        description: Connect to SAP systems for enterprise process automation.\n      - name: Salesforce\n        description: Integrate with Salesforce for CRM automation workflows.\n  - type: Solutions\n    data:\n      - name: Power Automate Premium\n        description:\
  \ Premium plan with advanced connectors, AI Builder, and process mining.\n      - name: Power Automate Process\n        description: Per-process licensing for unattended RPA and hosted machines.\n      - name: Power Automate Hosted\n        description: Hosted machine groups for scaling desktop automation.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-automate/refs/heads/main/apis.yml
tags:
- Automation
- Business Process
- Integration
- Low-Code
- Microsoft
- Power Platform
- RPA
- Workflow
url: https://powerautomate.microsoft.com
use_cases:
- description: Automatically process, route, and respond to emails based on content or sender.
  name: Email Automation
- description: Keep data synchronized across multiple systems and applications.
  name: Data Synchronization
- description: Automate business approval workflows across teams and departments.
  name: Approval Processes
- description: Automate document creation, routing, and archival workflows.
  name: Document Processing
- description: Automate IT helpdesk tickets, provisioning, and monitoring workflows.
  name: IT Process Automation
- description: Track brand mentions and automatically respond or alert teams.
  name: Social Media Monitoring
---
