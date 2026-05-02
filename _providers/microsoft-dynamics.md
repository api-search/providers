---
api_count: 3
api_specs:
- filename: microsoft-dynamics-business-central-openapi.yml
  format: yaml
  label: Microsoft Dynamics 365 Business Central API
  slug: business-central-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/openapi/microsoft-dynamics-business-central-openapi.yml
- filename: microsoft-dynamics-dataverse-openapi.yml
  format: yaml
  label: Microsoft Dynamics 365 Dataverse Web API
  slug: dataverse-web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/openapi/microsoft-dynamics-dataverse-openapi.yml
- filename: microsoft-dynamics-finance-operations-openapi.yml
  format: yaml
  label: Microsoft Dynamics 365 Finance & Operations Data API
  slug: finance-operations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/openapi/microsoft-dynamics-finance-operations-openapi.yml
apis:
- description: The Microsoft Dynamics 365 Business Central API (v2.0) provides a RESTful OData v4 interface for integrating with Business Central. It exposes standard business entities including companies, customers
  name: Microsoft Dynamics 365 Business Central API
  slug: business-central-api
- description: 'The Microsoft Dynamics 365 Dataverse Web API provides a RESTful OData v4 endpoint for Dynamics 365 Sales, Customer Service, Field Service, and other customer engagement applications. It supports CRUD '
  name: Microsoft Dynamics 365 Dataverse Web API
  slug: dataverse-web-api
- description: 'The Microsoft Dynamics 365 Finance & Operations Data API exposes business data entities via OData v4 RESTful endpoints. It provides access to finance, supply chain, manufacturing, and human resources '
  name: Microsoft Dynamics 365 Finance & Operations Data API
  slug: finance-operations-api
common:
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/dynamics365/
- title: ''
  type: Support
  url: https://community.dynamics.com/
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/dynamics365/get-started/
- title: ''
  type: Blog
  url: https://cloudblogs.microsoft.com/dynamics365/
created: '2025-01-01'
description: 'Microsoft Dynamics 365 is a suite of enterprise resource planning (ERP) and customer relationship management (CRM) applications. It provides APIs across three main platforms: Business Central for small and mid-sized business ERP, Dataverse Web API for CRM and customer engagement, and Finance & Operations for enterprise-grade ERP covering finance, supply chain, manufacturing, and human resources. All APIs use OData v4 conventions and authenticate via Microsoft Entra ID.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Microsoft Dynamics Context
  property_count: 10
  slug: microsoft-dynamics-context
layout: provider
modified: '2026-04-28'
name: Microsoft Dynamics
skills: []
slug: microsoft-dynamics
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-dynamics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/apis.yml\napis:\n  - aid: microsoft-dynamics:business-central-api\n    name: Microsoft Dynamics 365 Business Central API\n    tags:\n      - Business Central\n      - ERP\n      - Finance\n    humanURL: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/\n    properties:\n      - url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/\n        type: Documentation\n      - url: openapi/microsoft-dynamics-business-central-openapi.yml\n        type: OpenAPI\n      - url: json-schema/customer.json\n        type: JSONSchema\n      - url: json-schema/vendor.json\n        type: JSONSchema\n      - url: json-schema/item.json\n        type: JSONSchema\n      - url: json-schema/sales-order.json\n        type: JSONSchema\n      - url: json-schema/sales-invoice.json\n        type: JSONSchema\n\
  \      - url: json-schema/employee.json\n        type: JSONSchema\n      - url: json-ld/microsoft-dynamics-context.jsonld\n        type: JSONLD\n    description: >-\n      The Microsoft Dynamics 365 Business Central API (v2.0) provides a RESTful\n      OData v4 interface for integrating with Business Central. It exposes\n      standard business entities including companies, customers, vendors, items,\n      sales orders, sales invoices, purchase orders, purchase invoices, journals,\n      general ledger entries, accounts, and employees. The API supports both\n      cloud (SaaS) and on-premises deployments, authenticated via Microsoft\n      Entra ID.\n  - aid: microsoft-dynamics:dataverse-web-api\n    name: Microsoft Dynamics 365 Dataverse Web API\n    tags:\n      - CRM\n      - Customer Engagement\n      - Sales\n    humanURL: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n    properties:\n      - url: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/overview\n\
  \        type: Documentation\n      - url: openapi/microsoft-dynamics-dataverse-openapi.yml\n        type: OpenAPI\n      - url: json-schema/account.json\n        type: JSONSchema\n      - url: json-schema/contact.json\n        type: JSONSchema\n      - url: json-schema/lead.json\n        type: JSONSchema\n      - url: json-schema/opportunity.json\n        type: JSONSchema\n      - url: json-ld/microsoft-dynamics-context.jsonld\n        type: JSONLD\n    description: >-\n      The Microsoft Dynamics 365 Dataverse Web API provides a RESTful OData v4\n      endpoint for Dynamics 365 Sales, Customer Service, Field Service, and\n      other customer engagement applications. It supports CRUD operations on\n      core CRM entities such as accounts, contacts, leads, opportunities, cases\n      (incidents), and activities. Authentication is handled via Microsoft Entra\n      ID (Azure AD).\n  - aid: microsoft-dynamics:finance-operations-api\n    name: Microsoft Dynamics 365 Finance & Operations\
  \ Data API\n    tags:\n      - ERP\n      - Finance\n      - Supply Chain\n    humanURL: https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/data-entities/odata\n    properties:\n      - url: https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/data-entities/odata\n        type: Documentation\n      - url: openapi/microsoft-dynamics-finance-operations-openapi.yml\n        type: OpenAPI\n      - url: json-ld/microsoft-dynamics-context.jsonld\n        type: JSONLD\n    description: >-\n      The Microsoft Dynamics 365 Finance & Operations Data API exposes business\n      data entities via OData v4 RESTful endpoints. It provides access to\n      finance, supply chain, manufacturing, and human resources data including\n      customers, vendors, released products, sales order headers, purchase order\n      headers, general journal entries, and workers. The API supports cross-\n      company queries and is authenticated via Microsoft Entra ID.\nname: Microsoft\
  \ Dynamics\ntags:\n  - CRM\n  - ERP\n  - Microsoft Dynamics\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://learn.microsoft.com/en-us/dynamics365/\n    name: Microsoft Dynamics 365 Documentation\n    type: Documentation\n    description: 'null'\n  - url: https://community.dynamics.com/\n    name: Dynamics 365 Community\n    type: Support\n    description: 'null'\n  - url: https://learn.microsoft.com/en-us/dynamics365/get-started/\n    name: Getting Started with Dynamics 365\n    type: GettingStarted\n    description: 'null'\n  - url: https://cloudblogs.microsoft.com/dynamics365/\n    name: Dynamics 365 Blog\n    type: Blog\n    description: 'null'\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  Microsoft Dynamics 365 is a suite of enterprise resource planning (ERP) and\n  customer relationship management (CRM) applications. It provides APIs across\n  three\
  \ main platforms: Business Central for small and mid-sized business ERP,\n  Dataverse Web API for CRM and customer engagement, and Finance & Operations\n  for enterprise-grade ERP covering finance, supply chain, manufacturing, and\n  human resources. All APIs use OData v4 conventions and authenticate via\n  Microsoft Entra ID.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/apis.yml
tags:
- CRM
- ERP
- Microsoft Dynamics
url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/apis.yml
use_cases: []
---
