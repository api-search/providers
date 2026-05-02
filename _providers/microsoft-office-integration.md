---
api_count: 2
api_specs:
- filename: microsoft-office-management-activity-api-openapi.yml
  format: yaml
  label: Microsoft Office 365 Management Activity API
  slug: management-activity-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-integration/refs/heads/main/openapi/microsoft-office-management-activity-api-openapi.yml
- filename: microsoft-office-service-communications-api-openapi.yml
  format: yaml
  label: Microsoft Office 365 Service Communications API
  slug: service-communications-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-integration/refs/heads/main/openapi/microsoft-office-service-communications-api-openapi.yml
apis:
- description: The Office 365 Management Activity API provides information about various user, admin, system, and policy actions and events from Office 365 and Microsoft Entra activity logs. It enables customers and
  name: Microsoft Office 365 Management Activity API
  slug: management-activity-api
- description: The Office 365 Service Communications API provides tenant administrators and partners with real-time service health information and Message Center communications. It enables access to the list of subs
  name: Microsoft Office 365 Service Communications API
  slug: service-communications-api
common:
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/office/office-365-management-api/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/graph/overview
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/office/office-365-management-api/get-started-with-office-365-management-apis
- title: ''
  type: Portal
  url: https://developer.microsoft.com/en-us/graph
created: '2025-01-01'
description: APIs for Microsoft Office Integration, connecting Microsoft Office components and systems for seamless data exchange and end-to-end workflows across multiple technologies and platforms. The Office 365 Management APIs provide a single extensibility platform for management tasks including service communications, security, compliance, reporting, and auditing, using common industry-standard approaches including OAuth v2, OData v4, and JSON.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Microsoft Office Integration Context
  property_count: 6
  slug: microsoft-office-integration-context
layout: provider
modified: '2026-04-28'
name: Microsoft Office Integration
skills: []
slug: microsoft-office-integration
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-office-integration\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/microsoft-office-integration/refs/heads/main/apis.yml\napis:\n  - aid: microsoft-office-integration:management-activity-api\n    name: Microsoft Office 365 Management Activity API\n    tags:\n      - Auditing\n      - Compliance\n      - Office 365\n      - Security\n    humanURL: https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-management-activity-api-reference\n    properties:\n      - url: https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-management-activity-api-reference\n        type: Documentation\n      - url: openapi/microsoft-office-management-activity-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/subscription.json\n        type: JSONSchema\n      - url: json-schema/activity-record.json\n        type: JSONSchema\n      - url: json-schema/content-blob.json\n        type: JSONSchema\n      - url: json-ld/microsoft-office-integration-context.jsonld\n\
  \        type: JSONLD\n    description: >-\n      The Office 365 Management Activity API provides information about various\n      user, admin, system, and policy actions and events from Office 365 and\n      Microsoft Entra activity logs. It enables customers and partners to create\n      or enhance operations, security, and compliance-monitoring solutions.\n      The API supports subscription management, content retrieval, webhook\n      notifications, and DLP sensitive type lookups across content types\n      including Azure AD, Exchange, SharePoint, and General audit logs.\n  - aid: microsoft-office-integration:service-communications-api\n    name: Microsoft Office 365 Service Communications API\n    tags:\n      - Incidents\n      - Monitoring\n      - Office 365\n      - Service Health\n    humanURL: https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-service-communications-api-reference\n    properties:\n      - url: https://learn.microsoft.com/en-us/office/office-365-management-api/office-365-service-communications-api-reference\n\
  \        type: Documentation\n      - url: openapi/microsoft-office-service-communications-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/service.json\n        type: JSONSchema\n      - url: json-schema/workload-status.json\n        type: JSONSchema\n      - url: json-schema/message.json\n        type: JSONSchema\n      - url: json-ld/microsoft-office-integration-context.jsonld\n        type: JSONLD\n    description: >-\n      The Office 365 Service Communications API provides tenant administrators\n      and partners with real-time service health information and Message Center\n      communications. It enables access to the list of subscribed services,\n      current and historical service status, incident details, and planned\n      maintenance notifications for Office 365, Yammer, Dynamics CRM, and\n      Microsoft Intune cloud services.\nname: Microsoft Office Integration\ntags:\n  - Microsoft 365\n  - Microsoft Office Integration\n  - Office 365\ntype: Index\nimage:\
  \ https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://learn.microsoft.com/en-us/office/office-365-management-api/\n    name: Office 365 Management APIs Documentation\n    type: Documentation\n    description: 'null'\n  - url: https://learn.microsoft.com/en-us/graph/overview\n    name: Microsoft Graph Overview\n    type: Documentation\n    description: 'null'\n  - url: https://learn.microsoft.com/en-us/office/office-365-management-api/get-started-with-office-365-management-apis\n    name: Getting Started with Office 365 Management APIs\n    type: GettingStarted\n    description: 'null'\n  - url: https://developer.microsoft.com/en-us/graph\n    name: Microsoft Graph Dev Center\n    type: Portal\n    description: 'null'\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  APIs for Microsoft Office Integration, connecting Microsoft Office components\n  and systems for seamless data exchange\
  \ and end-to-end workflows across\n  multiple technologies and platforms. The Office 365 Management APIs provide a\n  single extensibility platform for management tasks including service\n  communications, security, compliance, reporting, and auditing, using common\n  industry-standard approaches including OAuth v2, OData v4, and JSON.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-integration/refs/heads/main/apis.yml
tags:
- Microsoft 365
- Microsoft Office Integration
- Office 365
url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-integration/refs/heads/main/apis.yml
use_cases: []
---
