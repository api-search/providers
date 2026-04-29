---
api_count: 3
apis:
- description: The Microsoft Dataverse Web API provides OData v4 RESTful access to the Dataverse data platform that underpins Power Platform. Developers can perform CRUD operations on tables, execute actions and fun
  name: Microsoft Dataverse Web API
  slug: dataverse-api
- description: The Power Platform Admin API enables programmatic management of Power Platform environments, connectors, data loss prevention policies, and tenant settings. Administrators can create and manage enviro
  name: Power Platform Admin API
  slug: admin-api
- description: Power Platform Connectors provide pre-built integrations with hundreds of external services and enable developers to create custom connectors using OpenAPI definitions. Connectors abstract API authent
  name: Power Platform Connectors
  slug: connectors-api
common:
- title: ''
  type: Portal
  url: https://make.powerapps.com/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/power-platform/
- title: ''
  type: Pricing
  url: https://powerapps.microsoft.com/en-us/pricing/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/power-platform/admin/programmability-authentication-v2
- title: ''
  type: Blog
  url: https://powerplatform.microsoft.com/en-us/blog/
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://support.microsoft.com/
- title: ''
  type: StatusPage
  url: https://status.powerplatform.microsoft.com/
created: '2024-01-01'
description: Microsoft Power Platform is a suite of low-code development tools including Power Apps, Power Automate, Power BI, and Power Virtual Agents. It provides APIs for accessing Dataverse, managing environments, and integrating with external services through connectors.
features: []
image: /assets/icons/microsoft-power-platform.png
integrations: []
layout: provider
modified: '2026-04-19'
name: Microsoft Power Platform
skills: []
slug: microsoft-power-platform
solutions: []
source_yaml: "aid: microsoft-power-platform\nname: Microsoft Power Platform\ndescription: >-\n  Microsoft Power Platform is a suite of low-code development tools\n  including Power Apps, Power Automate, Power BI, and Power Virtual Agents.\n  It provides APIs for accessing Dataverse, managing environments, and\n  integrating with external services through connectors.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Dataverse\n  - Low-Code\n  - Microsoft\n  - Power Apps\n  - Power Automate\n  - Power BI\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-power-platform/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: microsoft-power-platform:dataverse-api\n    name: Microsoft Dataverse Web API\n    tags:\n      - Data Platform\n      - Dataverse\n      - OData\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL:\
  \ https://{org}.api.crm.dynamics.com/api/data/v9.2/\n    humanURL: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n    properties:\n      - url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n        type: Documentation\n    description: >-\n      The Microsoft Dataverse Web API provides OData v4 RESTful access to\n      the Dataverse data platform that underpins Power Platform. Developers\n      can perform CRUD operations on tables, execute actions and functions,\n      manage metadata, and query data using standard OData conventions.\n  - aid: microsoft-power-platform:admin-api\n    name: Power Platform Admin API\n    tags:\n      - Administration\n      - Environments\n      - Governance\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.bap.microsoft.com/\n    humanURL: https://learn.microsoft.com/en-us/power-platform/admin/programmability-extensibility-overview\n\
  \    properties:\n      - url: https://learn.microsoft.com/en-us/power-platform/admin/programmability-extensibility-overview\n        type: Documentation\n    description: >-\n      The Power Platform Admin API enables programmatic management of Power\n      Platform environments, connectors, data loss prevention policies, and\n      tenant settings. Administrators can create and manage environments,\n      configure security roles, and enforce governance policies across the\n      organization.\n  - aid: microsoft-power-platform:connectors-api\n    name: Power Platform Connectors\n    tags:\n      - Connectors\n      - Custom Connectors\n      - Integration\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/connectors/overview\n    properties:\n      - url: https://learn.microsoft.com/en-us/connectors/overview\n        type: Documentation\n      - url: https://learn.microsoft.com/en-us/connectors/custom-connectors/\n\
  \        type: GettingStarted\n    description: >-\n      Power Platform Connectors provide pre-built integrations with hundreds\n      of external services and enable developers to create custom connectors\n      using OpenAPI definitions. Connectors abstract API authentication and\n      data access, making external services available to Power Apps, Power\n      Automate, and Logic Apps.\ncommon:\n  - type: Portal\n    url: https://make.powerapps.com/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/power-platform/\n  - type: Pricing\n    url: https://powerapps.microsoft.com/en-us/pricing/\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/power-platform/admin/programmability-authentication-v2\n  - type: Blog\n    url: https://powerplatform.microsoft.com/en-us/blog/\n  - type: TermsOfService\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type:\
  \ Support\n    url: https://support.microsoft.com/\n  - type: StatusPage\n    url: https://status.powerplatform.microsoft.com/\n  - type: Features\n    url: https://powerplatform.microsoft.com/en-us/what-is-power-platform/\n  - type: UseCases\n    url: https://powerplatform.microsoft.com/en-us/customer-stories/\n  - type: Integrations\n    url: https://learn.microsoft.com/en-us/connectors/overview\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-platform/refs/heads/main/apis.yml
tags:
- Dataverse
- Low-Code
- Microsoft
- Power Apps
- Power Automate
- Power BI
url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-platform/refs/heads/main/apis.yml
use_cases: []
---
