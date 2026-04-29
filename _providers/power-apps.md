---
api_count: 7
apis:
- description: The Power Apps REST API provides a unified endpoint to work with environments, apps, and related resources.
  name: Power Apps REST API
  slug: ''
- description: The Web API for Dataverse provides a development experience that can be used across a wide variety of programming languages, platforms, and devices.
  name: Microsoft Dataverse Web API
  slug: ''
- description: REST API for managing Power Apps environments, apps, flows, and connectors.
  name: Power Apps Management API
  slug: ''
- description: APIs for building custom components using the Power Apps Component Framework (PCF).
  name: Power Apps Component Framework API
  slug: ''
- description: The Power Platform API provides a unified REST endpoint at api.powerplatform.com for managing environments, licensing, app management, and tenant-level governance across the entire Power Platform.
  name: Microsoft Power Platform API
  slug: ''
- description: Client API reference for model-driven apps providing JavaScript libraries for form scripting, UI manipulation, data access, and the Xrm object model including Xrm.WebApi for data operations.
  name: Model-Driven Apps Client API
  slug: ''
- description: Custom connectors allow you to create wrappers around REST or SOAP APIs for use in Power Apps, Power Automate, Logic Apps, and Copilot Studio, enabling integration with services not available as prebu
  name: Custom Connectors API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://make.powerapps.com
- title: ''
  type: DeveloperPortal
  url: https://powerapps.microsoft.com/en-us/developers/
- title: ''
  type: Support
  url: https://powerusers.microsoft.com/
- title: ''
  type: Blog
  url: https://powerapps.microsoft.com/en-us/blog/
- title: ''
  type: Pricing
  url: https://powerapps.microsoft.com/en-us/pricing/
- title: ''
  type: Support
  url: https://powerapps.microsoft.com/en-us/support/
- title: ''
  type: Training
  url: https://docs.microsoft.com/en-us/learn/powerplatform/power-apps
- title: ''
  type: GitHubOrganization
  url: https://github.com/microsoft/PowerApps-Samples
- title: ''
  type: StatusPage
  url: https://status.powerplatform.microsoft.com/
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/power-platform/developer/get-started
- title: ''
  type: Resources
  url: https://learn.microsoft.com/en-us/power-platform/alm/overview-alm
- title: ''
  type: CLI
  url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/powerapps-cli
- title: ''
  type: Resources
  url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/developer-tools
- title: ''
  type: Resources
  url: https://learn.microsoft.com/en-us/power-platform/alm/devops-github-actions
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/authentication
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/power-platform/admin/programmability-whats-new-changed
- title: ''
  type: Resources
  url: https://learn.microsoft.com/en-us/connectors/connector-reference/
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/powerplatform/
created: '2024'
description: Microsoft Power Apps is a suite of apps, services, and connectors, as well as a data platform, that provides a rapid development environment to build custom apps for your business needs.
features:
- Low-code and no-code app development
- Microsoft Dataverse data platform
- Power Apps Component Framework (PCF)
- Model-driven and canvas app types
- Custom connectors for REST and SOAP APIs
- Power Platform unified administration API
- Client-side scripting with Xrm object model
- AI Builder integration for intelligent apps
image: https://powerusers.microsoft.com/t5/image/serverpage/image-id/98171i62B0C7ECED0A0B8B/image-size/large
integrations:
- Microsoft 365
- Microsoft Teams
- Microsoft Azure
- Power Automate
- Power BI
- Dynamics 365
- SharePoint
- SQL Server
layout: provider
modified: '2026-04-18'
name: Microsoft Power Apps
skills: []
slug: power-apps
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Microsoft Power Apps\ndescription: Microsoft Power Apps is a suite of apps, services, and connectors, as well as a data platform, that provides a rapid development environment to build custom apps for your business needs.\nimage: https://powerusers.microsoft.com/t5/image/serverpage/image-id/98171i62B0C7ECED0A0B8B/image-size/large\nurl: https://powerapps.microsoft.com/\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntags:\n  - App Development\n  - Business Applications\n  - Cloud Platform\n  - Low-Code\n  - Microsoft\n  - No-Code\napis:\n  - name: Power Apps REST API\n    description: The Power Apps REST API provides a unified endpoint to work with environments, apps, and related resources.\n    image: https://powerusers.microsoft.com/t5/image/serverpage/image-id/98171i62B0C7ECED0A0B8B/image-size/large\n    humanURL: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n    baseURL: https://api.powerapps.com\n    tags:\n\
  \      - Apps\n      - Connections\n      - Environments\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n      - type: OpenAPI\n        url: https://learn.microsoft.com/en-us/connectors/powerappsforappmakers/\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/authenticate-oauth\n  - name: Microsoft Dataverse Web API\n    description: The Web API for Dataverse provides a development experience that can be used across a wide variety of programming languages, platforms, and devices.\n    image: https://powerusers.microsoft.com/t5/image/serverpage/image-id/98171i62B0C7ECED0A0B8B/image-size/large\n    humanURL: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n    baseURL: https://[org].api.crm.dynamics.com/api/data/v9.2\n    tags:\n      - CRUD Operations\n      - Data Platform\n      - Dataverse\n \
  \     - OData\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n      - type: OpenAPI\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/openapi\n      - type: Quickstart\n        url: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/quick-start-console-app-csharp\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/about\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/web-api-types-operations\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/org-service/overview\n      - type: DeveloperPortal\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/\n  - name: Power Apps Management API\n    description: REST\
  \ API for managing Power Apps environments, apps, flows, and connectors.\n    image: https://powerusers.microsoft.com/t5/image/serverpage/image-id/98171i62B0C7ECED0A0B8B/image-size/large\n    humanURL: https://docs.microsoft.com/en-us/powershell/module/microsoft.powerapps.administration.powershell/\n    baseURL: https://api.bap.microsoft.com\n    tags:\n      - Administration\n      - Governance\n      - Management\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-platform/admin/programmability-authentication\n      - type: SDK\n        url: https://docs.microsoft.com/en-us/powershell/module/microsoft.powerapps.administration.powershell/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-platform/admin/powerplatform-api-getting-started\n  - name: Power Apps Component Framework API\n    description: APIs for building custom components using the Power Apps Component Framework (PCF).\n    image: https://powerusers.microsoft.com/t5/image/serverpage/image-id/98171i62B0C7ECED0A0B8B/image-size/large\n\
  \    humanURL: https://docs.microsoft.com/en-us/power-apps/developer/component-framework/overview\n    baseURL: https://pcf.tools\n    tags:\n      - Components\n      - Custom Controls\n      - PCF\n      - UI Framework\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-apps/developer/component-framework/reference/\n      - type: CodeExamples\n        url: https://github.com/microsoft/PowerApps-Samples/tree/master/component-framework\n      - type: Tutorials\n        url: https://docs.microsoft.com/en-us/power-apps/developer/component-framework/create-custom-controls-using-pcf\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/component-framework/component-framework-for-canvas-apps\n  - name: Microsoft Power Platform API\n    description: The Power Platform API provides a unified REST endpoint at api.powerplatform.com for managing environments, licensing, app management, and tenant-level governance\
  \ across the entire Power Platform.\n    image: https://powerusers.microsoft.com/t5/image/serverpage/image-id/98171i62B0C7ECED0A0B8B/image-size/large\n    humanURL: https://learn.microsoft.com/en-us/rest/api/power-platform/\n    baseURL: https://api.powerplatform.com\n    tags:\n      - App Management\n      - Environments\n      - Governance\n      - Licensing\n      - Platform API\n      - Tenant Administration\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/power-platform/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-platform/admin/powerplatform-api-getting-started\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-platform/admin/programmability-authentication-v2\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-platform/admin/programmability-extensibility-overview\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/connectors/powerplatformadminv2/\n\
  \      - type: SDK\n        url: https://www.nuget.org/packages/Microsoft.PowerPlatform.Management\n  - name: Model-Driven Apps Client API\n    description: Client API reference for model-driven apps providing JavaScript libraries for form scripting, UI manipulation, data access, and the Xrm object model including Xrm.WebApi for data operations.\n    image: https://powerusers.microsoft.com/t5/image/serverpage/image-id/98171i62B0C7ECED0A0B8B/image-size/large\n    humanURL: https://learn.microsoft.com/en-us/power-apps/developer/model-driven-apps/clientapi/reference\n    baseURL: https://[org].api.crm.dynamics.com\n    tags:\n      - Client API\n      - Form Scripting\n      - JavaScript\n      - Model-Driven Apps\n      - Xrm Object Model\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/model-driven-apps/clientapi/reference\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-apps/developer/model-driven-apps/clientapi/walkthrough-write-your-first-client-script\n\
  \      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/model-driven-apps/client-scripting\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/get-started-web-api-client-side-javascript\n  - name: Custom Connectors API\n    description: Custom connectors allow you to create wrappers around REST or SOAP APIs for use in Power Apps, Power Automate, Logic Apps, and Copilot Studio, enabling integration with services not available as prebuilt connectors.\n    image: https://powerusers.microsoft.com/t5/image/serverpage/image-id/98171i62B0C7ECED0A0B8B/image-size/large\n    humanURL: https://learn.microsoft.com/en-us/connectors/custom-connectors/\n    baseURL: https://[environment].api.powerapps.com\n    tags:\n      - Connectors\n      - Custom Connectors\n      - Integration\n      - OpenAPI\n      - REST\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/connectors/custom-connectors/\n\
  \      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/connectors/custom-connectors/define-blank\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/connectors/custom-connectors/use-custom-connector-powerapps\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/connectors/connector-reference/\ncommon:\n  - type: Portal\n    url: https://make.powerapps.com\n  - type: DeveloperPortal\n    url: https://powerapps.microsoft.com/en-us/developers/\n  - type: Support\n    url: https://powerusers.microsoft.com/\n  - type: Blog\n    url: https://powerapps.microsoft.com/en-us/blog/\n  - type: Pricing\n    url: https://powerapps.microsoft.com/en-us/pricing/\n  - type: Support\n    url: https://powerapps.microsoft.com/en-us/support/\n  - type: Training\n    url: https://docs.microsoft.com/en-us/learn/powerplatform/power-apps\n  - type: GitHubOrganization\n    url: https://github.com/microsoft/PowerApps-Samples\n  - type: StatusPage\n\
  \    url: https://status.powerplatform.microsoft.com/\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/power-platform/developer/get-started\n  - type: Resources\n    url: https://learn.microsoft.com/en-us/power-platform/alm/overview-alm\n  - type: CLI\n    url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/powerapps-cli\n  - type: Resources\n    url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/developer-tools\n  - type: Resources\n    url: https://learn.microsoft.com/en-us/power-platform/alm/devops-github-actions\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/authentication\n  - type: ChangeLog\n    url: https://learn.microsoft.com/en-us/power-platform/admin/programmability-whats-new-changed\n  - type: Resources\n    url: https://learn.microsoft.com/en-us/connectors/connector-reference/\n  - type: Training\n    url: https://learn.microsoft.com/en-us/training/powerplatform/\n\
  \  - type: Features\n    data:\n      - Low-code and no-code app development\n      - Microsoft Dataverse data platform\n      - Power Apps Component Framework (PCF)\n      - Model-driven and canvas app types\n      - Custom connectors for REST and SOAP APIs\n      - Power Platform unified administration API\n      - Client-side scripting with Xrm object model\n      - AI Builder integration for intelligent apps\n  - type: UseCases\n    data:\n      - Custom business application development\n      - Data-driven enterprise app creation\n      - Legacy system modernization\n      - Citizen developer enablement\n      - Mobile workforce applications\n      - Process automation with Power Automate integration\n  - type: Integrations\n    data:\n      - Microsoft 365\n      - Microsoft Teams\n      - Microsoft Azure\n      - Power Automate\n      - Power BI\n      - Dynamics 365\n      - SharePoint\n      - SQL Server\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url:\
  \ https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/power-apps/refs/heads/main/apis.yml
tags:
- App Development
- Business Applications
- Cloud Platform
- Low-Code
- Microsoft
- No-Code
url: https://powerapps.microsoft.com/
use_cases:
- Custom business application development
- Data-driven enterprise app creation
- Legacy system modernization
- Citizen developer enablement
- Mobile workforce applications
- Process automation with Power Automate integration
---
