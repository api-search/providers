---
api_count: 11
api_specs:
- filename: microsoft-power-apps-dataverse-web-api-openapi.yml
  format: yaml
  label: Dataverse API (Common Data Service)
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-apps/refs/heads/main/openapi/microsoft-power-apps-dataverse-web-api-openapi.yml
apis:
- description: Core API for managing Power Apps applications, including creating, updating, and deleting apps.
  name: Power Apps API
  slug: ''
- description: RESTful API for interacting with Microsoft Dataverse (formerly Common Data Service) for data storage and management.
  name: Dataverse API (Common Data Service)
  slug: ''
- description: API for administrative tasks including environment management, app sharing, and user permissions.
  name: Power Apps Management API
  slug: ''
- description: API for working with custom and standard connectors to integrate external services and data sources.
  name: Power Apps Connectors API
  slug: ''
- description: API specific to Canvas Apps for creating pixel-perfect user interfaces with drag-and-drop functionality.
  name: Power Apps Canvas Apps API
  slug: ''
- description: API for Model-driven Apps that automatically generate UI based on data model and business logic.
  name: Power Apps Model-driven Apps API
  slug: ''
- description: Framework API for professional developers to create reusable code components for model-driven and canvas apps using TypeScript and web technologies.
  name: Power Apps Component Framework (PCF) API
  slug: ''
- description: Unified RESTful API for Power Platform administration including environment management, governance, licensing, app management, and capacity reporting.
  name: Power Platform REST API
  slug: ''
- description: Web API for Power Pages (formerly Power Apps Portals) enabling CRUD operations on Dataverse tables from external-facing portal web pages.
  name: Power Pages Web API
  slug: ''
- description: .NET SDK providing strongly-typed access to Microsoft Dataverse through the IOrganizationService interface for server-side development and plugins.
  name: Dataverse Organization Service SDK
  slug: ''
- description: API and SDK for building code-first Power Apps using popular frameworks like React and Vue, developed in any code-first IDE and deployed to Power Apps.
  name: Power Apps Code Apps API
  slug: ''
capabilities:
- description: Unified data platform capability combining Dataverse account, contact, and entity management with OData query support. Used by Power Platform developers and CRM integration teams.
  name: Microsoft Power Apps Data Platform
  slug: data-platform
common:
- title: ''
  type: DeveloperPortal
  url: https://docs.microsoft.com/en-us/power-apps/developer/
- title: ''
  type: Community
  url: https://powerusers.microsoft.com/
- title: ''
  type: Blog
  url: https://powerapps.microsoft.com/blog/
- title: ''
  type: Pricing
  url: https://powerapps.microsoft.com/pricing/
- title: ''
  type: StatusPage
  url: https://status.powerplatform.microsoft.com/
- title: ''
  type: Support
  url: https://powerapps.microsoft.com/support/
- title: ''
  type: Training
  url: https://docs.microsoft.com/en-us/learn/powerplatform/power-apps
- title: ''
  type: GitHubRepository
  url: https://github.com/microsoft/PowerApps-Samples
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/licensing/terms/productoffering/MicrosoftPowerApps
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/
- title: ALM Documentation
  type: Documentation
  url: https://learn.microsoft.com/en-us/power-platform/alm/
- title: Pipelines
  type: Documentation
  url: https://learn.microsoft.com/en-us/power-platform/alm/pipelines
- title: Power Platform Developer Documentation
  type: Documentation
  url: https://learn.microsoft.com/en-us/power-platform/developer/
- title: ''
  type: CLI
  url: https://learn.microsoft.com/en-us/power-platform/developer/cli/reference/pipeline
- title: ''
  type: Security
  url: https://learn.microsoft.com/en-us/power-platform/admin/wp-security
- title: Power Fx Overview
  type: Documentation
  url: https://learn.microsoft.com/en-us/power-platform/power-fx/overview
- title: Power Fx Formula Reference
  type: Documentation
  url: https://learn.microsoft.com/en-us/power-platform/power-fx/formula-reference-overview
- title: Deployment Training
  type: Training
  url: https://learn.microsoft.com/en-us/training/paths/simplify-power-platform-deployments/
- title: ''
  type: ReleaseNotes
  url: https://learn.microsoft.com/en-us/power-platform/release-plan/2025wave1/power-apps/planned-features
created: '2024'
description: Collection of APIs for Microsoft Power Apps platform enabling low-code application development, automation, and data connectivity.
features:
- description: Visual drag-and-drop app building with Power Fx formulas and pre-built templates.
  name: Low-Code Development
- description: Built-in data platform with security, business logic, and integration capabilities.
  name: Microsoft Dataverse
- description: Connect to any external API through standard and custom connector definitions.
  name: Custom Connectors
- description: Automatically generated UIs based on data model and business logic configuration.
  name: Model-Driven Apps
- description: Professional code components using TypeScript for custom controls in canvas and model-driven apps.
  name: Component Framework
image: https://powerplatform.microsoft.com/images/power-apps-logo.png
integrations:
- description: Native integration with Teams, SharePoint, Outlook, and Excel for productivity workflows.
  name: Microsoft 365
- description: Shared Dataverse platform with Dynamics 365 CRM and ERP modules for unified data.
  name: Dynamics 365
- description: Trigger automated flows from Power Apps for cross-system process automation.
  name: Power Automate
jsonld:
- class_count: 0
  name: Microsoft Power Apps Context
  property_count: 5
  slug: microsoft-power-apps-context
- class_count: 0
  name: Microsoft Power Apps Dataverse Web Context
  property_count: 0
  slug: microsoft-power-apps-dataverse-web-context
layout: provider
modified: '2026-04-18'
name: Microsoft Power Apps
rules:
- name: Microsoft Power Apps API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: microsoft-power-apps-spectral-rules
skills: []
slug: microsoft-power-apps
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-power-apps\nname: Microsoft Power Apps\ndescription: >-\n  Collection of APIs for Microsoft Power Apps platform enabling low-code application\n  development, automation, and data connectivity.\nimage: https://powerplatform.microsoft.com/images/power-apps-logo.png\ncreated: '2024'\nmodified: '2026-04-18'\nartifacts:\n  openapi:\n    - name: Microsoft Dataverse Web API OpenAPI Specification\n      path: openapi/microsoft-power-apps-dataverse-web-api-openapi.yml\n      version: 3.1.0\n      description: OpenAPI 3.1.0 specification for the Dataverse Web API v9.2 covering accounts, contacts, and entity definitions with full CRUD operations and OData query support\n  jsonSchema:\n    - name: Microsoft Power Apps Dataverse Entity Schema\n      path: json-schema/microsoft-power-apps-entity-schema.json\n      version: draft/2020-12\n      description: JSON Schema defining core Dataverse entity types (Account, Contact, Entity) with property types, constraints, and enum\
  \ values based on the Microsoft.Dynamics.CRM namespace\n  jsonLd:\n    - name: Microsoft Power Apps JSON-LD Context\n      path: json-ld/microsoft-power-apps-context.jsonld\n      version: '1.1'\n      description: JSON-LD context mapping Dataverse entity properties to Schema.org, Dublin Core, OData, and vCard vocabularies for semantic interoperability\nspecificationVersion: '0.19'\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-power-apps/refs/heads/main/apis.yml\napis:\n  - name: Power Apps API\n    description: >-\n      Core API for managing Power Apps applications, including creating, updating,\n      and deleting apps.\n    image: https://powerplatform.microsoft.com/images/power-apps-icon.png\n    humanURL: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n    baseURL: https://api.powerapps.com\n    tags:\n      - Applications\n      - Development\n      - Low-Code\n      - Power Platform\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference\n      - type: OpenAPI\n        url: https://docs.microsoft.com/en-us/connectors/powerappsforappmakers/\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/authenticate\n      - type: RateLimits\n        url: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/api-limits\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/power-platform/powerapps/apps\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-platform/admin/powerplatform-api-getting-started\n  - name: Dataverse API (Common Data Service)\n    description: >-\n      RESTful API for interacting with Microsoft Dataverse (formerly Common Data Service)\n      for data storage and management.\n    image: https://powerplatform.microsoft.com/images/dataverse-icon.png\n    humanURL: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n\
  \    baseURL: https://[organization].api.crm.dynamics.com/api/data/v9.2\n    tags:\n      - CRM\n      - Data Platform\n      - Database\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n      - type: OpenAPI\n        url: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/openapi\n      - type: OData\n        url: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/webapi/query-data-web-api\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/power-apps/developer/data-platform/authenticate-oauth\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/about\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/perform-operations-web-api\n      - type: Documentation\n        url:\
  \ https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/web-api-types-operations\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/custom-api\n      - type: OpenAPI\n        url: openapi/microsoft-power-apps-dataverse-web-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/microsoft-power-apps-entity-schema.json\n      - type: JSONLD\n        url: json-ld/microsoft-power-apps-context.jsonld\n      - type: Security\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/security-roles\n      - type: Training\n        url: https://learn.microsoft.com/en-us/training/modules/dataverse-web-api/\n  - name: Power Apps Management API\n    description: >-\n      API for administrative tasks including environment management, app sharing,\n      and user permissions.\n    image: https://powerplatform.microsoft.com/images/admin-icon.png\n    humanURL: https://docs.microsoft.com/en-us/power-platform/admin/programmability-admin-center\n\
  \    baseURL: https://api.bap.microsoft.com\n    tags:\n      - Administration\n      - Environments\n      - Governance\n      - Management\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-platform/admin/programmability-admin-center\n      - type: SDK\n        url: https://docs.microsoft.com/en-us/power-platform/admin/powershell-getting-started\n      - type: CLI\n        url: https://docs.microsoft.com/en-us/power-platform/developer/cli/introduction\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-platform/admin/programmability-authentication-v2\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/power-platform/environmentmanagement/environment-management-settings\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/power-platform/environmentmanagement/environment-managed-governance/enable-managed-environment\n  - name: Power Apps Connectors\
  \ API\n    description: >-\n      API for working with custom and standard connectors to integrate external services\n      and data sources.\n    image: https://powerplatform.microsoft.com/images/connectors-icon.png\n    humanURL: https://docs.microsoft.com/en-us/connectors/custom-connectors/\n    baseURL: https://api.powerapps.com/providers/Microsoft.PowerApps\n    tags:\n      - Connectors\n      - Custom Connectors\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/connectors/custom-connectors/create-web-api-connector\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/connectors/connector-reference/\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/connectors/custom-connectors/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/power-platform/connectivity/connectors/list-connectors\n  - name: Power Apps Canvas Apps API\n    description:\
  \ >-\n      API specific to Canvas Apps for creating pixel-perfect user interfaces with\n      drag-and-drop functionality.\n    image: https://powerplatform.microsoft.com/images/canvas-apps-icon.png\n    humanURL: https://docs.microsoft.com/en-us/power-apps/maker/canvas-apps/\n    baseURL: https://api.powerapps.com\n    tags:\n      - Canvas Apps\n      - Low-Code\n      - Mobile\n      - UI\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-apps/maker/canvas-apps/dev-enterprise-intro\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-platform/power-fx/formula-reference\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-apps/maker/canvas-apps/application-lifecycle-management\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-platform/power-fx/overview\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-platform/power-fx/formula-reference-canvas-apps\n\
  \  - name: Power Apps Model-driven Apps API\n    description: >-\n      API for Model-driven Apps that automatically generate UI based on data model\n      and business logic.\n    image: https://powerplatform.microsoft.com/images/model-driven-icon.png\n    humanURL: https://docs.microsoft.com/en-us/power-apps/developer/model-driven-apps/\n    baseURL: https://[organization].crm.dynamics.com\n    tags:\n      - Business Logic\n      - Forms\n      - Model-Driven Apps\n      - Views\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-apps/developer/model-driven-apps/overview\n      - type: APIReference\n        url: https://docs.microsoft.com/en-us/power-apps/developer/model-driven-apps/clientapi/reference\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/power-apps/developer/model-driven-apps/customize-entity-forms\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-platform/power-fx/formula-reference-model-driven-apps\n\
  \  - name: Power Apps Component Framework (PCF) API\n    description: >-\n      Framework API for professional developers to create reusable code components\n      for model-driven and canvas apps using TypeScript and web technologies.\n    image: https://powerplatform.microsoft.com/images/power-apps-icon.png\n    humanURL: https://learn.microsoft.com/en-us/power-apps/developer/component-framework/overview\n    baseURL: https://api.powerapps.com\n    tags:\n      - Code Components\n      - Component Framework\n      - Custom Controls\n      - PCF\n      - TypeScript\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/component-framework/overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/power-apps/developer/component-framework/reference/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-apps/developer/component-framework/implementing-controls-using-typescript\n\
  \      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/component-framework/create-custom-controls-using-pcf\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/component-framework/bring-intelligence-using-agent-apis\n  - name: Power Platform REST API\n    description: >-\n      Unified RESTful API for Power Platform administration including environment\n      management, governance, licensing, app management, and capacity reporting.\n    image: https://powerplatform.microsoft.com/images/power-apps-icon.png\n    humanURL: https://learn.microsoft.com/en-us/rest/api/power-platform/\n    baseURL: https://api.powerplatform.com\n    tags:\n      - Administration\n      - Environments\n      - Governance\n      - Licensing\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/power-platform/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-platform/admin/powerplatform-api-getting-started\n\
  \      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-platform/admin/programmability-authentication-v2\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/power-platform/appmanagement/applications\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/power-platform/environmentmanagement/environment-management-settings\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/power-platform/connectivity/connectors/list-connectors\n  - name: Power Pages Web API\n    description: >-\n      Web API for Power Pages (formerly Power Apps Portals) enabling CRUD operations\n      on Dataverse tables from external-facing portal web pages.\n    image: https://powerplatform.microsoft.com/images/power-apps-icon.png\n    humanURL: https://learn.microsoft.com/en-us/power-pages/configure/web-api-overview\n    baseURL: https://[site-url]/_api\n    tags:\n      - CRUD\n      - External\
  \ Users\n      - Portals\n      - Power Pages\n      - Web API\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-pages/configure/web-api-overview\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-pages/configure/read-operations\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-pages/configure/write-update-delete-operations\n      - type: Tutorials\n        url: https://learn.microsoft.com/en-us/power-apps/maker/portals/webapi-tutorial\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-platform/power-fx/formula-reference-power-pages\n  - name: Dataverse Organization Service SDK\n    description: >-\n      .NET SDK providing strongly-typed access to Microsoft Dataverse through the\n      IOrganizationService interface for server-side development and plugins.\n    image: https://powerplatform.microsoft.com/images/dataverse-icon.png\n    humanURL:\
  \ https://learn.microsoft.com/en-us/power-apps/developer/data-platform/org-service/overview\n    baseURL: https://[organization].api.crm.dynamics.com\n    tags:\n      - .NET\n      - Organization Service\n      - Plugins\n      - SDK\n      - Server-Side\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/org-service/overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/org-service/iorganizationservice-interface\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/org-service/use-messages\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/dotnet/api/microsoft.powerplatform.dataverse.client.serviceclient\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/\n  - name: Power Apps Code Apps API\n    description:\
  \ >-\n      API and SDK for building code-first Power Apps using popular frameworks like\n      React and Vue, developed in any code-first IDE and deployed to Power Apps.\n    image: https://powerplatform.microsoft.com/images/power-apps-icon.png\n    humanURL: https://learn.microsoft.com/en-us/power-apps/developer/code-apps/overview\n    baseURL: https://api.powerapps.com\n    tags:\n      - Code Apps\n      - Code-First\n      - Pro Developer\n      - React\n      - Vue\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/code-apps/\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/code-apps/overview\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/code-apps/architecture\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/code-apps/how-to/alm\n      - type: Security\n        url: https://learn.microsoft.com/en-us/power-apps/developer/code-apps/how-to/content-security-policy\n\
  common:\n  - type: DeveloperPortal\n    url: https://docs.microsoft.com/en-us/power-apps/developer/\n  - type: Community\n    url: https://powerusers.microsoft.com/\n  - type: Blog\n    url: https://powerapps.microsoft.com/blog/\n  - type: Pricing\n    url: https://powerapps.microsoft.com/pricing/\n  - type: StatusPage\n    url: https://status.powerplatform.microsoft.com/\n  - type: Support\n    url: https://powerapps.microsoft.com/support/\n  - type: Training\n    url: https://docs.microsoft.com/en-us/learn/powerplatform/power-apps\n  - type: GitHubRepository\n    url: https://github.com/microsoft/PowerApps-Samples\n  - type: TermsOfService\n    url: https://www.microsoft.com/licensing/terms/productoffering/MicrosoftPowerApps\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/power-platform/alm/\n    title: ALM Documentation\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/power-platform/alm/pipelines\n\
  \    title: Pipelines\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/power-platform/developer/\n    title: Power Platform Developer Documentation\n  - type: CLI\n    url: https://learn.microsoft.com/en-us/power-platform/developer/cli/reference/pipeline\n  - type: Security\n    url: https://learn.microsoft.com/en-us/power-platform/admin/wp-security\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/power-platform/power-fx/overview\n    title: Power Fx Overview\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/power-platform/power-fx/formula-reference-overview\n    title: Power Fx Formula Reference\n  - type: Training\n    url: https://learn.microsoft.com/en-us/training/paths/simplify-power-platform-deployments/\n    title: Deployment Training\n  - type: ReleaseNotes\n    url: https://learn.microsoft.com/en-us/power-platform/release-plan/2025wave1/power-apps/planned-features\n  - type: Features\n    data:\n      - name: Low-Code\
  \ Development\n        description: Visual drag-and-drop app building with Power Fx formulas and pre-built templates.\n      - name: Microsoft Dataverse\n        description: Built-in data platform with security, business logic, and integration capabilities.\n      - name: Custom Connectors\n        description: Connect to any external API through standard and custom connector definitions.\n      - name: Model-Driven Apps\n        description: Automatically generated UIs based on data model and business logic configuration.\n      - name: Component Framework\n        description: Professional code components using TypeScript for custom controls in canvas and model-driven apps.\n  - type: UseCases\n    data:\n      - name: Business Process Automation\n        description: Digitize paper-based processes and manual workflows with custom business applications.\n      - name: Customer Portal\n        description: Build external-facing portals using Power Pages with Dataverse Web API integration.\n\
  \      - name: Field Service Apps\n        description: Create mobile applications for field workers with offline capabilities and data sync.\n      - name: Data Management\n        description: Build CRUD applications on Dataverse for managing business data with role-based security.\n  - type: Integrations\n    data:\n      - name: Microsoft 365\n        description: Native integration with Teams, SharePoint, Outlook, and Excel for productivity workflows.\n      - name: Dynamics 365\n        description: Shared Dataverse platform with Dynamics 365 CRM and ERP modules for unified data.\n      - name: Power Automate\n        description: Trigger automated flows from Power Apps for cross-system process automation.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Business Applications\n  - Cloud\n  - Enterprise\n  - Low-Code\n  - Microsoft\n  - No-Code\n  - Power Platform\n  - SaaS\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-apps/refs/heads/main/apis.yml
tags:
- Business Applications
- Cloud
- Enterprise
- Low-Code
- Microsoft
- No-Code
- Power Platform
- SaaS
url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-apps/refs/heads/main/apis.yml
use_cases:
- description: Digitize paper-based processes and manual workflows with custom business applications.
  name: Business Process Automation
- description: Build external-facing portals using Power Pages with Dataverse Web API integration.
  name: Customer Portal
- description: Create mobile applications for field workers with offline capabilities and data sync.
  name: Field Service Apps
- description: Build CRUD applications on Dataverse for managing business data with role-based security.
  name: Data Management
---
