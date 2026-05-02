---
api_count: 13
api_specs:
- filename: $metadata
  format: yaml
  label: Dynamics 365 Sales API
  slug: ''
  spec_type: OpenAPI
  url: https://[org].api.crm.dynamics.com/api/data/v9.2/$metadata
- filename: $metadata
  format: yaml
  label: Dynamics 365 Customer Service API
  slug: ''
  spec_type: OpenAPI
  url: https://[org].api.crm.dynamics.com/api/data/v9.2/$metadata
- filename: openapi
  format: yaml
  label: Dynamics 365 Business Central API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.microsoft.com/dynamics365/business-central/dev-itpro/api-reference/v2.0/openapi
- filename: microsoft-dynamics-365-dataverse-web-api-openapi.yml
  format: yaml
  label: Microsoft Dataverse Web API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics-365/refs/heads/main/openapi/microsoft-dynamics-365-dataverse-web-api-openapi.yml
apis:
- description: API for managing sales processes, leads, opportunities, accounts, and contacts in Dynamics 365 Sales.
  name: Dynamics 365 Sales API
  slug: ''
- description: API for managing customer service cases, knowledge articles, queues, and service level agreements.
  name: Dynamics 365 Customer Service API
  slug: ''
- description: API for managing financial operations, accounting, budgeting, and enterprise resource planning.
  name: Dynamics 365 Finance & Operations API
  slug: ''
- description: API for managing marketing campaigns, customer journeys, email marketing, and lead scoring.
  name: Dynamics 365 Marketing API
  slug: ''
- description: API for managing inventory, warehouse operations, procurement, and supply chain processes.
  name: Dynamics 365 Supply Chain Management API
  slug: ''
- description: API for managing small to medium business operations including finance, sales, service, and operations.
  name: Dynamics 365 Business Central API
  slug: ''
- description: API for managing e-commerce operations, retail stores, omnichannel commerce, and customer experiences.
  name: Dynamics 365 Commerce API
  slug: ''
- description: RESTful web service API implementing OData v4.0 for interacting with data in Microsoft Dataverse, the underlying data platform for Dynamics 365 and Power Platform applications.
  name: Microsoft Dataverse Web API
  slug: ''
- description: API for building applications based on unified customer data, enabling customer data unification, segmentation, and enrichment through programmatic access.
  name: Dynamics 365 Customer Insights Data API
  slug: ''
- description: API for managing real-time customer journeys, segments, and event-driven marketing interactions programmatically.
  name: Dynamics 365 Customer Insights Journeys API
  slug: ''
- description: API for managing field service operations including work orders, scheduling, resource availability, and work hour calendars.
  name: Dynamics 365 Field Service API
  slug: ''
- description: API for managing human resources operations including employee data, payroll integration, applicant tracking, and benefits administration.
  name: Dynamics 365 Human Resources API
  slug: ''
- description: API for managing project operations including project scheduling, resource management, time and expense tracking, and project financials.
  name: Dynamics 365 Project Operations API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Authentication
  url: https://docs.microsoft.com/azure/active-directory/develop/
- title: ''
  type: SDKs
  url: https://docs.microsoft.com/powerapps/developer/data-platform/sdk/
- title: ''
  type: Status Page
  url: https://status.dynamics.com/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/licensing/terms/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/
- title: ''
  type: Support
  url: https://dynamics.microsoft.com/support/
- title: ''
  type: REST API Reference
  url: https://learn.microsoft.com/en-us/rest/dynamics365/
- title: ''
  type: Release Plans
  url: https://learn.microsoft.com/en-us/dynamics365/release-plans/
- title: ''
  type: Community Forums
  url: https://community.dynamics.com/
- title: ''
  type: Power Platform Admin Center
  url: https://learn.microsoft.com/en-us/power-platform/admin/admin-documentation
- title: ''
  type: API Limits Overview
  url: https://learn.microsoft.com/en-us/power-apps/maker/data-platform/api-limits-overview
created: '2025-01-20'
description: Microsoft Dynamics 365 is a cloud-based suite of business applications that unify CRM and ERP capabilities to help organizations manage sales, marketing, customer service, finance, operations, and commerce.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Microsoft Dynamics 365 Context
  property_count: 3
  slug: microsoft-dynamics-365-context
layout: provider
modified: '2026-04-28'
name: Microsoft Dynamics 365
skills: []
slug: microsoft-dynamics-365
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Microsoft Dynamics 365\ndescription: Microsoft Dynamics 365 is a cloud-based suite of business applications that unify CRM and ERP capabilities to help organizations manage sales, marketing, customer service, finance, operations, and commerce.\nurl: https://dynamics.microsoft.com/\ncreated: '2025-01-20'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\napis:\n  - name: Dynamics 365 Sales API\n    description: API for managing sales processes, leads, opportunities, accounts, and contacts in Dynamics 365 Sales.\n    image: https://dynamics.microsoft.com/assets/sales-icon.png\n    humanURL: https://docs.microsoft.com/dynamics365/sales/\n    baseURL: https://[org].api.crm.dynamics.com/api/data/v9.2\n    tags:\n      - CRM\n      - Leads\n      - Opportunities\n      - Sales\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/dynamics365/sales/developer/developer-guide\n      - type: OpenAPI\n        url: https://[org].api.crm.dynamics.com/api/data/v9.2/$metadata\n\
  \      - type: Authentication\n        url: https://docs.microsoft.com/powerapps/developer/data-platform/authenticate\n      - type: Rate Limits\n        url: https://docs.microsoft.com/powerapps/developer/data-platform/api-limits\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n        url: https://support.microsoft.com/dynamics365\n  - name: Dynamics 365 Customer Service API\n    description: API for managing customer service cases, knowledge articles, queues, and service level agreements.\n    image: https://dynamics.microsoft.com/assets/service-icon.png\n    humanURL: https://docs.microsoft.com/dynamics365/customer-service/\n    baseURL: https://[org].api.crm.dynamics.com/api/data/v9.2\n    tags:\n      - Cases\n      - Customer Service\n      - Knowledge Base\n      - Support\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/dynamics365/customer-service/developer/developer-guide\n      - type: OpenAPI\n      \
  \  url: https://[org].api.crm.dynamics.com/api/data/v9.2/$metadata\n      - type: Webhooks\n        url: https://docs.microsoft.com/powerapps/developer/data-platform/use-webhooks\n  - name: Dynamics 365 Finance & Operations API\n    description: API for managing financial operations, accounting, budgeting, and enterprise resource planning.\n    image: https://dynamics.microsoft.com/assets/finance-icon.png\n    humanURL: https://docs.microsoft.com/dynamics365/finance/\n    baseURL: https://[org].operations.dynamics.com/data\n    tags:\n      - Accounting\n      - ERP\n      - Finance\n      - Operations\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/data-entities\n      - type: OData\n        url: https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/odata\n      - type: Authentication\n        url: https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/services-home-page\n\
  \      - type: API Reference\n        url: https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/dev-ref/api-reference\n      - type: Data Management REST API\n        url: https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/data-entities/data-management-api\n  - name: Dynamics 365 Marketing API\n    description: API for managing marketing campaigns, customer journeys, email marketing, and lead scoring.\n    image: https://dynamics.microsoft.com/assets/marketing-icon.png\n    humanURL: https://docs.microsoft.com/dynamics365/marketing/\n    baseURL: https://[org].api.crm.dynamics.com/api/data/v9.2\n    tags:\n      - Campaigns\n      - Email Marketing\n      - Lead Scoring\n      - Marketing\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/dynamics365/marketing/developer/marketing-developer-guide\n      - type: API Reference\n        url: https://docs.microsoft.com/dynamics365/marketing/developer/extend-marketing-api\n\
  \  - name: Dynamics 365 Supply Chain Management API\n    description: API for managing inventory, warehouse operations, procurement, and supply chain processes.\n    image: https://dynamics.microsoft.com/assets/supply-chain-icon.png\n    humanURL: https://docs.microsoft.com/dynamics365/supply-chain/\n    baseURL: https://[org].operations.dynamics.com/data\n    tags:\n      - Inventory\n      - Procurement\n      - Supply Chain\n      - Warehouse\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/dynamics365/supply-chain/dev-itpro/\n      - type: Data Entities\n        url: https://docs.microsoft.com/dynamics365/fin-ops-core/dev-itpro/data-entities/data-entities-data-packages\n  - name: Dynamics 365 Business Central API\n    description: API for managing small to medium business operations including finance, sales, service, and operations.\n    image: https://dynamics.microsoft.com/assets/business-central-icon.png\n    humanURL: https://docs.microsoft.com/dynamics365/business-central/\n\
  \    baseURL: https://api.businesscentral.dynamics.com/v2.0/[tenant]/[environment]/api/v2.0\n    tags:\n      - Business Management\n      - Finance\n      - Operations\n      - SMB\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/dynamics365/business-central/dev-itpro/api-reference/v2.0/\n      - type: OpenAPI\n        url: https://docs.microsoft.com/dynamics365/business-central/dev-itpro/api-reference/v2.0/openapi\n      - type: Getting Started\n        url: https://docs.microsoft.com/dynamics365/business-central/dev-itpro/api-reference/v2.0/enabling-apis-for-dynamics-nav\n      - type: Webhooks\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/dynamics-subscriptions\n      - type: Custom API Development\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-develop-custom-api\n      - type: API Endpoints\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/endpoints-apis-for-dynamics\n\
  \      - type: REST API Overview\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/api-overview\n  - name: Dynamics 365 Commerce API\n    description: API for managing e-commerce operations, retail stores, omnichannel commerce, and customer experiences.\n    image: https://dynamics.microsoft.com/assets/commerce-icon.png\n    humanURL: https://docs.microsoft.com/dynamics365/commerce/\n    baseURL: https://[org].commerce.dynamics.com/api\n    tags:\n      - E-Commerce\n      - Omnichannel\n      - POS\n      - Retail\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/dynamics365/commerce/e-commerce-extensibility/overview\n      - type: Retail Server API\n        url: https://docs.microsoft.com/dynamics365/commerce/dev-itpro/retail-server-architecture\n  - name: Microsoft Dataverse Web API\n    description: RESTful web service API implementing OData v4.0 for interacting with data in Microsoft Dataverse, the\
  \ underlying data platform for Dynamics 365 and Power Platform applications.\n    humanURL: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n    baseURL: https://[org].api.crm.dynamics.com/api/data/v9.2\n    tags:\n      - Data Platform\n      - Dataverse\n      - OData\n      - Power Platform\n      - REST\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n      - type: API Reference\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/about\n      - type: OpenAPI\n        url: openapi/microsoft-dynamics-365-dataverse-web-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/microsoft-dynamics-365-account-schema.json\n      - type: JSONLD\n        url: json-ld/microsoft-dynamics-365-context.jsonld\n      - type: Web API Types and Operations\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/web-api-types-operations\n\
  \      - type: Web API Service Documents\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/web-api-service-documents\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/authenticate-oauth\n      - type: Rate Limits\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/api-limits\n      - type: Developer Guide\n        url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/overview\n  - name: Dynamics 365 Customer Insights Data API\n    description: API for building applications based on unified customer data, enabling customer data unification, segmentation, and enrichment through programmatic access.\n    humanURL: https://learn.microsoft.com/en-us/dynamics365/customer-insights/\n    baseURL: https://api.ci.ai.dynamics.com/\n    tags:\n      - Analytics\n      - CDP\n      - Customer Data\n      - Customer Insights\n      - Segmentation\n\
  \    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics365/customer-insights/data/apis\n      - type: API Management\n        url: https://learn.microsoft.com/en-us/dynamics365/customer-insights/data/apis-manage\n      - type: Dataverse APIs\n        url: https://learn.microsoft.com/en-us/dynamics365/customer-insights/data/dv-odata\n      - type: Developer Portal\n        url: https://developer.ci.ai.dynamics.com/\n  - name: Dynamics 365 Customer Insights Journeys API\n    description: API for managing real-time customer journeys, segments, and event-driven marketing interactions programmatically.\n    humanURL: https://learn.microsoft.com/en-us/dynamics365/customer-insights/journeys/\n    baseURL: https://[org].api.crm.dynamics.com/api/data/v9.2\n    tags:\n      - Events\n      - Journeys\n      - Marketing Automation\n      - Real-Time Marketing\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics365/customer-insights/journeys/\n\
  \      - type: Segment API\n        url: https://learn.microsoft.com/en-us/dynamics365/customer-insights/journeys/real-time-marketing-api-segment\n      - type: Events API\n        url: https://learn.microsoft.com/en-us/dynamics365/customer-insights/journeys/developer/using-rtm-events-api\n  - name: Dynamics 365 Field Service API\n    description: API for managing field service operations including work orders, scheduling, resource availability, and work hour calendars.\n    humanURL: https://learn.microsoft.com/en-us/dynamics365/field-service/\n    baseURL: https://[org].api.crm.dynamics.com/api/data/v9.2\n    tags:\n      - Field Service\n      - Resource Management\n      - Scheduling\n      - Work Orders\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics365/field-service/\n      - type: Resource Availability API\n        url: https://learn.microsoft.com/en-us/dynamics365/field-service/search-resource-availability-api\n      - type:\
  \ Work Hours Calendar API\n        url: https://learn.microsoft.com/en-us/dynamics365/field-service/field-service-work-hours-calendar-api\n      - type: Entity Reference\n        url: https://learn.microsoft.com/en-us/dynamics365/field-service/developer/reference/about-entity-reference\n  - name: Dynamics 365 Human Resources API\n    description: API for managing human resources operations including employee data, payroll integration, applicant tracking, and benefits administration.\n    humanURL: https://learn.microsoft.com/en-us/dynamics365/human-resources/\n    baseURL: https://[org].operations.dynamics.com/data\n    tags:\n      - HR\n      - Human Resources\n      - Payroll\n      - Recruiting\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics365/human-resources/hr-developer-overview\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/dynamics365/human-resources/hr-developer-api-authentication\n      - type:\
  \ Payroll Integration API\n        url: https://learn.microsoft.com/en-us/dynamics365/human-resources/hr-admin-integration-payroll-api-introduction\n      - type: Applicant Tracking API\n        url: https://learn.microsoft.com/en-us/dynamics365/human-resources/hr-admin-integration-ats-api-introduction\n  - name: Dynamics 365 Project Operations API\n    description: API for managing project operations including project scheduling, resource management, time and expense tracking, and project financials.\n    humanURL: https://learn.microsoft.com/en-us/dynamics365/project-operations/\n    baseURL: https://[org].api.crm.dynamics.com/api/data/v9.2\n    tags:\n      - Project Accounting\n      - Project Management\n      - Resource Management\n      - Time Tracking\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics365/project-operations/\n      - type: Schedule API\n        url: https://learn.microsoft.com/en-us/dynamics365/project-operations/project-management/schedule-api-preview\n\
  \      - type: Schedule API with Power Automate\n        url: https://learn.microsoft.com/en-us/dynamics365/project-operations/project-management/scheduling-apis-powerautomate\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Authentication\n    url: https://docs.microsoft.com/azure/active-directory/develop/\n  - type: SDKs\n    url: https://docs.microsoft.com/powerapps/developer/data-platform/sdk/\n  - type: Status Page\n    url: https://status.dynamics.com/\n  - type: Terms of Service\n    url: https://www.microsoft.com/licensing/terms/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/\n  - type: Support\n    url: https://dynamics.microsoft.com/support/\n  - type: REST API Reference\n    url: https://learn.microsoft.com/en-us/rest/dynamics365/\n  - type: Release Plans\n    url: https://learn.microsoft.com/en-us/dynamics365/release-plans/\n  - type: Community Forums\n    url: https://community.dynamics.com/\n  - type: Power Platform Admin Center\n\
  \    url: https://learn.microsoft.com/en-us/power-platform/admin/admin-documentation\n  - type: API Limits Overview\n    url: https://learn.microsoft.com/en-us/power-apps/maker/data-platform/api-limits-overview\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com/\ntags:\n  - Business Applications\n  - Cloud\n  - CRM\n  - Enterprise\n  - ERP\n  - Microsoft\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics-365/refs/heads/main/apis.yml
tags:
- Business Applications
- Cloud
- CRM
- Enterprise
- ERP
- Microsoft
url: https://dynamics.microsoft.com/
use_cases: []
---
