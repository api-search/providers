---
api_count: 9
api_specs:
- filename: v1
  format: yaml
  label: Power Apps API
  slug: ''
  spec_type: OpenAPI
  url: https://api.powerapps.com/openapi/v1
- filename: v1
  format: yaml
  label: Power Automate API
  slug: ''
  spec_type: OpenAPI
  url: https://api.flow.microsoft.com/openapi/v1
- filename: swagger.json
  format: json
  label: Power BI REST API
  slug: ''
  spec_type: OpenAPI
  url: https://api.powerbi.com/v1.0/myorg/swagger.json
- filename: power-platform-api-openapi.json
  format: json
  label: Power Platform Unified API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/power-platform/refs/heads/main/openapi/power-platform-api-openapi.json
apis:
- description: REST API for creating, managing, and deploying Power Apps applications including canvas apps and model-driven apps.
  name: Power Apps API
  slug: ''
- description: OData v4.0 compliant Web API for Microsoft Dataverse, providing RESTful data storage, business logic, and entity management capabilities across the Power Platform.
  name: Dataverse API (Common Data Service)
  slug: ''
- description: API for creating, managing, and running automated cloud flows and desktop flows. Cloud flows are stored in Dataverse and can be managed via the Dataverse Web API.
  name: Power Automate API
  slug: ''
- description: REST API for embedding, managing, and interacting with Power BI reports, datasets, dashboards, and workspaces for embedded analytics and automation.
  name: Power BI REST API
  slug: ''
- description: API for building, managing, and deploying AI agents and conversational chatbots. Power Virtual Agents has been rebranded to Microsoft Copilot Studio with expanded AI agent capabilities.
  name: Microsoft Copilot Studio API (formerly Power Virtual Agents)
  slug: ''
- description: API for administrative operations across Power Platform environments including environment management, governance, capacity, and licensing via the BAP (Business Application Platform) endpoint.
  name: Power Platform Admin API
  slug: ''
- description: API for custom and certified connectors that extend Power Platform capabilities across Power Apps, Power Automate, Logic Apps, and Copilot Studio.
  name: Power Platform Connectors API
  slug: ''
- description: Unified RESTful API surface for all Power Platform administrative capabilities including licensing, app management, environment management, and governance. Provides a single endpoint at api.powerplatf
  name: Power Platform Unified API
  slug: ''
- description: Web API for Power Pages (formerly Power Apps Portals) enabling CRUD operations on Microsoft Dataverse tables from portal webpages for richer user experiences.
  name: Power Pages Web API
  slug: ''
capabilities:
- description: Unified workflow for Power Platform administrators to manage environments, deploy applications, monitor flow runs, and govern licensing across the tenant.
  name: Microsoft Power Platform Administration
  slug: platform-administration
common:
- title: ''
  type: DeveloperPortal
  url: https://learn.microsoft.com/en-us/power-platform/developer/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/power-platform/
- title: ''
  type: Blog
  url: https://www.microsoft.com/en-us/power-platform/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/microsoft/powerplatform
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/powerplatform/
- title: ''
  type: StatusPage
  url: https://status.cloud.microsoft/
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/privacystatement
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/licensing/terms/
- title: ''
  type: APIReference
  url: https://learn.microsoft.com/en-us/rest/api/power-platform/
- title: ''
  type: Support
  url: https://admin.powerplatform.microsoft.com/
- title: ''
  type: NaftikoCapability
  url: capabilities/platform-administration.yaml
created: '2024-01-15'
description: Collection of APIs for Microsoft Power Platform services including Power Apps, Power Automate, Power BI, Copilot Studio, Power Pages, and Dataverse.
features:
- description: Build custom business applications with drag-and-drop canvas and model-driven app builders without writing code.
  name: Low-Code App Development
- description: Automate repetitive business processes with cloud flows, desktop flows, and AI-powered process mining.
  name: Workflow Automation
- description: Create interactive dashboards and reports with Power BI for data-driven decision making across the organization.
  name: Business Intelligence
- description: Build conversational AI agents with Copilot Studio that integrate with Teams, websites, and other channels.
  name: AI-Powered Chatbots
- description: Extend platform capabilities by creating custom connectors to any REST API or third-party service.
  name: Custom Connectors
- description: Store and manage business data in a secure, scalable cloud database with built-in business logic and security.
  name: Dataverse Data Platform
- description: Manage isolated environments for development, testing, and production with governance policies and access controls.
  name: Environment Management
- description: Embed Power BI reports and dashboards directly into custom applications and portals.
  name: Embedded Analytics
image: https://powerplatform.microsoft.com/images/power-platform-logo.png
integrations:
- description: Deep integration with Outlook, Teams, SharePoint, OneDrive, and Excel for seamless productivity workflows.
  name: Microsoft 365
- description: Connect to Azure services including Azure Active Directory, Azure SQL, Azure Functions, and Cognitive Services.
  name: Microsoft Azure
- description: Extend Dynamics 365 CRM and ERP applications with custom Power Apps and automated workflows.
  name: Dynamics 365
- description: Connect to SAP ERP and S/4HANA through certified connectors for enterprise data integration.
  name: SAP
- description: Integrate with Salesforce CRM data and workflows through the Salesforce connector.
  name: Salesforce
- description: Connect Power Platform workflows with ServiceNow ITSM and service management processes.
  name: ServiceNow
jsonld:
- class_count: 0
  name: Power Platform Context
  property_count: 0
  slug: power-platform-context
layout: provider
modified: '2026-04-19'
name: Microsoft Power Platform APIs
rules:
- name: Microsoft Power Platform APIs API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: power-platform-spectral-rules
skills: []
slug: power-platform
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Microsoft Power Platform APIs\ndescription: Collection of APIs for Microsoft Power Platform services including Power Apps, Power Automate, Power BI, Copilot Studio, Power Pages, and Dataverse.\nimage: https://powerplatform.microsoft.com/images/power-platform-logo.png\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.18'\nurl: https://powerplatform.microsoft.com/apis.json\ntags:\n  - Business Applications\n  - Copilot Studio\n  - Dataverse\n  - Low-Code\n  - Microsoft\n  - No-Code\n  - Power Pages\n  - Power Platform\napis:\n  - name: Power Apps API\n    description: REST API for creating, managing, and deploying Power Apps applications including canvas apps and model-driven apps.\n    image: https://powerplatform.microsoft.com/images/powerapps-logo.png\n    baseURL: https://api.powerapps.com\n    humanURL: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n    tags:\n      - Applications\n      - Canvas Apps\n\
  \      - Model-Driven Apps\n      - Power Apps\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n      - type: OpenAPI\n        url: https://api.powerapps.com/openapi/v1\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/authenticate-oauth\n      - type: RateLimits\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/api-limits\n      - type: Pricing\n        url: https://powerapps.microsoft.com/pricing/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/power-platform/powerapps/apps\n    contact:\n      - type: Support\n        url: https://powerapps.microsoft.com/support/\n  - name: Dataverse API (Common Data Service)\n    description: OData v4.0 compliant Web API for Microsoft Dataverse, providing RESTful data storage, business logic, and entity management capabilities\
  \ across the Power Platform.\n    image: https://powerplatform.microsoft.com/images/dataverse-logo.png\n    baseURL: https://[org].api.crm.dynamics.com/api/data/v9.2\n    humanURL: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n    tags:\n      - CDS\n      - Data Platform\n      - Database\n      - Dataverse\n      - OData\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/about\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/web-api-types-operations\n        title: OData Types and Operations\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/authenticate-web-api\n      - type: SDK\n       \
  \ url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/developer-tools\n    contact:\n      - type: Support\n        url: https://powerapps.microsoft.com/support/\n  - name: Power Automate API\n    description: API for creating, managing, and running automated cloud flows and desktop flows. Cloud flows are stored in Dataverse and can be managed via the Dataverse Web API.\n    image: https://powerplatform.microsoft.com/images/powerautomate-logo.png\n    baseURL: https://api.flow.microsoft.com\n    humanURL: https://learn.microsoft.com/en-us/power-automate/web-api\n    tags:\n      - Automation\n      - Desktop Flows\n      - Flow\n      - Power Automate\n      - RPA\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-automate/web-api\n      - type: OpenAPI\n        url: https://api.flow.microsoft.com/openapi/v1\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-automate/web-api\n\
  \      - type: Integrations\n        url: https://learn.microsoft.com/en-us/connectors/\n        title: Connectors\n      - type: Pricing\n        url: https://powerautomate.microsoft.com/pricing/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/power-platform/powerautomate/flow-runs/list-flow-runs\n    contact:\n      - type: Support\n        url: https://powerautomate.microsoft.com/support/\n  - name: Power BI REST API\n    description: REST API for embedding, managing, and interacting with Power BI reports, datasets, dashboards, and workspaces for embedded analytics and automation.\n    image: https://powerplatform.microsoft.com/images/powerbi-logo.png\n    baseURL: https://api.powerbi.com\n    humanURL: https://learn.microsoft.com/en-us/rest/api/power-bi/\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Dashboards\n      - Embedded Analytics\n      - Power BI\n      - Reporting\n    properties:\n      - type: Documentation\n\
  \        url: https://learn.microsoft.com/en-us/rest/api/power-bi/\n      - type: OpenAPI\n        url: https://api.powerbi.com/v1.0/myorg/swagger.json\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-bi/developer/embedded/embed-tokens\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/javascript/api/overview/powerbi/\n      - type: Pricing\n        url: https://powerbi.microsoft.com/pricing/\n    contact:\n      - type: Support\n        url: https://powerbi.microsoft.com/support/\n  - name: Microsoft Copilot Studio API (formerly Power Virtual Agents)\n    description: API for building, managing, and deploying AI agents and conversational chatbots. Power Virtual Agents has been rebranded to Microsoft Copilot Studio with expanded AI agent capabilities.\n    image: https://powerplatform.microsoft.com/images/pva-logo.png\n    baseURL: https://api.powerva.microsoft.com\n    humanURL: https://learn.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-what-is-copilot-studio\n\
  \    tags:\n      - AI Agents\n      - Chatbots\n      - Conversational AI\n      - Copilot Studio\n      - Power Virtual Agents\n      - Virtual Agents\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-what-is-copilot-studio\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/microsoft-copilot-studio/configuration-end-user-authentication\n      - type: Pricing\n        url: https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio#pricing\n      - type: Console\n        url: https://copilotstudio.microsoft.com\n    contact:\n      - type: Support\n        url: https://learn.microsoft.com/en-us/microsoft-copilot-studio/\n  - name: Power Platform Admin API\n    description: API for administrative operations across Power Platform environments including environment management, governance, capacity, and licensing via the BAP (Business Application Platform) endpoint.\n\
  \    image: https://powerplatform.microsoft.com/images/admin-logo.png\n    baseURL: https://api.bap.microsoft.com\n    humanURL: https://learn.microsoft.com/en-us/power-platform/admin/admin-documentation\n    tags:\n      - Administration\n      - Environments\n      - Governance\n      - Licensing\n      - Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-platform/admin/admin-documentation\n      - type: CLI\n        url: https://learn.microsoft.com/en-us/power-platform/developer/cli/introduction\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-platform/admin/powerplatform-api-getting-started\n    contact:\n      - type: Support\n        url: https://admin.powerplatform.microsoft.com/support\n  - name: Power Platform Connectors API\n    description: API for custom and certified connectors that extend Power Platform capabilities across Power Apps, Power Automate, Logic Apps, and Copilot Studio.\n\
  \    image: https://powerplatform.microsoft.com/images/connectors-logo.png\n    baseURL: https://api.connectors.microsoft.com\n    humanURL: https://learn.microsoft.com/en-us/connectors/\n    tags:\n      - Connectors\n      - Custom Connectors\n      - Integration\n      - OpenAPI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/connectors/\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/connectors/custom-connectors/\n        title: Custom Connectors\n      - type: CLI\n        url: https://learn.microsoft.com/en-us/connectors/custom-connectors/paconn-cli\n      - type: GitHubRepository\n        url: https://github.com/microsoft/PowerPlatformConnectors\n    contact:\n      - type: Support\n        url: https://powerapps.microsoft.com/support/\n  - name: Power Platform Unified API\n    description: Unified RESTful API surface for all Power Platform administrative capabilities including licensing, app management,\
  \ environment management, and governance. Provides a single endpoint at api.powerplatform.com.\n    image: https://powerplatform.microsoft.com/images/power-platform-logo.png\n    baseURL: https://api.powerplatform.com\n    humanURL: https://learn.microsoft.com/en-us/rest/api/power-platform/\n    tags:\n      - Administration\n      - App Management\n      - Governance\n      - Licensing\n      - Power Platform API\n      - Unified API\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/power-platform/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-platform/admin/powerplatform-api-getting-started\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-platform/admin/programmability-authentication-v2\n      - type: Versioning\n        url: https://learn.microsoft.com/en-us/power-platform/admin/programmability-versioning-support\n      - type: OpenAPI\n        url: openapi/power-platform-api-openapi.json\n\
  \      - type: SDK\n        url: https://www.nuget.org/packages/Microsoft.PowerPlatform.Management\n        title: .NET SDK\n    contact:\n      - type: Support\n        url: https://admin.powerplatform.microsoft.com/support\n  - name: Power Pages Web API\n    description: Web API for Power Pages (formerly Power Apps Portals) enabling CRUD operations on Microsoft Dataverse tables from portal webpages for richer user experiences.\n    image: https://powerplatform.microsoft.com/images/power-platform-logo.png\n    baseURL: https://[site].powerappsportals.com/_api\n    humanURL: https://learn.microsoft.com/en-us/power-pages/configure/web-api-overview\n    tags:\n      - Dataverse\n      - Portals\n      - Power Pages\n      - Web API\n      - Websites\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-pages/configure/web-api-overview\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/power-pages/configure/webapi-how-to\n\
  \    contact:\n      - type: Support\n        url: https://powerapps.microsoft.com/support/\ncommon:\n  - type: DeveloperPortal\n    url: https://learn.microsoft.com/en-us/power-platform/developer/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/power-platform/\n  - type: Blog\n    url: https://www.microsoft.com/en-us/power-platform/blog/\n  - type: GitHubOrganization\n    url: https://github.com/microsoft/powerplatform\n  - type: Training\n    url: https://learn.microsoft.com/en-us/training/powerplatform/\n  - type: StatusPage\n    url: https://status.cloud.microsoft/\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/privacystatement\n  - type: TermsOfService\n    url: https://www.microsoft.com/licensing/terms/\n  - type: APIReference\n    url: https://learn.microsoft.com/en-us/rest/api/power-platform/\n  - type: Support\n    url: https://admin.powerplatform.microsoft.com/\n  - type: Features\n    data:\n      - name: Low-Code App Development\n    \
  \    description: Build custom business applications with drag-and-drop canvas and model-driven app builders without writing code.\n      - name: Workflow Automation\n        description: Automate repetitive business processes with cloud flows, desktop flows, and AI-powered process mining.\n      - name: Business Intelligence\n        description: Create interactive dashboards and reports with Power BI for data-driven decision making across the organization.\n      - name: AI-Powered Chatbots\n        description: Build conversational AI agents with Copilot Studio that integrate with Teams, websites, and other channels.\n      - name: Custom Connectors\n        description: Extend platform capabilities by creating custom connectors to any REST API or third-party service.\n      - name: Dataverse Data Platform\n        description: Store and manage business data in a secure, scalable cloud database with built-in business logic and security.\n      - name: Environment Management\n      \
  \  description: Manage isolated environments for development, testing, and production with governance policies and access controls.\n      - name: Embedded Analytics\n        description: Embed Power BI reports and dashboards directly into custom applications and portals.\n  - type: UseCases\n    data:\n      - name: Citizen Developer Apps\n        description: Enable business users to build departmental applications without IT involvement using low-code tools.\n      - name: Process Automation\n        description: Automate approval workflows, data collection, notifications, and integrations across Microsoft 365 and third-party services.\n      - name: Enterprise Reporting\n        description: Consolidate data from multiple sources into unified dashboards and self-service analytics for executive decision-making.\n      - name: Customer Service Bots\n        description: Deploy AI-powered virtual agents for customer support, HR inquiries, and IT helpdesk automation.\n      - name: Data\
  \ Integration\n        description: Connect and synchronize data across SaaS applications, on-premises systems, and cloud databases using connectors and Dataverse.\n  - type: Integrations\n    data:\n      - name: Microsoft 365\n        description: Deep integration with Outlook, Teams, SharePoint, OneDrive, and Excel for seamless productivity workflows.\n      - name: Microsoft Azure\n        description: Connect to Azure services including Azure Active Directory, Azure SQL, Azure Functions, and Cognitive Services.\n      - name: Dynamics 365\n        description: Extend Dynamics 365 CRM and ERP applications with custom Power Apps and automated workflows.\n      - name: SAP\n        description: Connect to SAP ERP and S/4HANA through certified connectors for enterprise data integration.\n      - name: Salesforce\n        description: Integrate with Salesforce CRM data and workflows through the Salesforce connector.\n      - name: ServiceNow\n        description: Connect Power Platform\
  \ workflows with ServiceNow ITSM and service management processes.\n  - type: NaftikoCapability\n    url: capabilities/platform-administration.yaml\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/power-platform/refs/heads/main/apis.yml
tags:
- Business Applications
- Copilot Studio
- Dataverse
- Low-Code
- Microsoft
- No-Code
- Power Pages
- Power Platform
url: https://powerplatform.microsoft.com/apis.json
use_cases:
- description: Enable business users to build departmental applications without IT involvement using low-code tools.
  name: Citizen Developer Apps
- description: Automate approval workflows, data collection, notifications, and integrations across Microsoft 365 and third-party services.
  name: Process Automation
- description: Consolidate data from multiple sources into unified dashboards and self-service analytics for executive decision-making.
  name: Enterprise Reporting
- description: Deploy AI-powered virtual agents for customer support, HR inquiries, and IT helpdesk automation.
  name: Customer Service Bots
- description: Connect and synchronize data across SaaS applications, on-premises systems, and cloud databases using connectors and Dataverse.
  name: Data Integration
---
