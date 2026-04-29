---
api_count: 7
apis:
- description: SOAP and OData web services for interacting with Dynamics NAV business data. Supports publishing pages, codeunits, and queries as web services for external system integration.
  name: Dynamics NAV Web Services API
  slug: ''
- description: OData web services for querying and manipulating NAV business entities. Supports both OData v3 and v4 protocols for reading data and writing back to the Dynamics NAV database through exposed pages and
  name: Dynamics NAV OData API
  slug: ''
- description: SOAP-based web services for legacy integrations and business logic operations in Dynamics NAV. Exposes pages and codeunits with built-in CRUD operations and supports extension codeunits for custom ope
  name: Dynamics NAV SOAP Web Services
  slug: ''
- description: Modern RESTful API for Dynamics 365 Business Central, the cloud evolution of Dynamics NAV. Provides a comprehensive set of endpoints for managing customers, items, accounts, sales orders, and other bu
  name: Business Central API v2.0
  slug: ''
- description: REST API for programmatic administration of Business Central environments. Enables querying and managing production and sandbox environments, setting up notifications, and viewing tenant telemetry.
  name: Business Central Administration Center API
  slug: ''
- description: API for automating company setup and tenant management in Business Central. Supports creating companies, installing extensions, assigning permissions, and applying RapidStart packages programmatically
  name: Business Central Automation API
  slug: ''
- description: RESTful web services layer for Business Central that provides the preferred integration method. Includes built-in APIs, custom API pages and queries, and supports both on-premises and cloud deployment
  name: Business Central REST API Web Services
  slug: ''
capabilities:
- description: Unified workflow for day-to-day business operations in Dynamics 365 Business Central combining the Business Central API v2.0 for managing customers, vendors, items, orders, invoices, and financials. U
  name: Dynamics NAV Business Operations
  slug: business-operations
- description: Unified workflow for administering Dynamics 365 Business Central combining the Administration Center API for environment management with the Automation API for company setup, extensions, users, and pe
  name: Dynamics NAV Platform Administration
  slug: platform-administration
common:
- title: ''
  type: Portal
  url: https://dynamics.microsoft.com
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-get-started
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/users-credential-types
- title: ''
  type: Blog
  url: https://www.microsoft.com/en-us/dynamics-365/blog/product/dynamics-365-business-central/
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/whatsnew/overview
- title: ''
  type: Support
  url: https://support.microsoft.com/dynamics
- title: ''
  type: SignUp
  url: https://learn.microsoft.com/en-us/dynamics365/business-central/trial-signup
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/dynamics-365/products/business-central/pricing
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en/dynamics-365/business-applications/legal
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com
- title: ''
  type: StatusPage
  url: https://status.cloud.microsoft
- title: ''
  type: GitHubOrganization
  url: https://github.com/microsoft/BCApps
- title: ''
  type: GitHubRepository
  url: https://github.com/christianbraeunlich/d365bc-api-postman
- title: ''
  type: RateLimits
  url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/dynamics-rate-limits
- title: Laravel SDK
  type: SDK
  url: https://github.com/niclas-timm/laravel-dynamics-365-business-central
- title: Go REST Client
  type: SDK
  url: https://github.com/AgoraIO/agora-rest-client-go
- title: AL Language CLI
  type: CLI
  url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-command-line-tools
- title: Customer Schema
  type: JSONSchema
  url: json-schema/customer.json
- title: Vendor Schema
  type: JSONSchema
  url: json-schema/vendor.json
- title: Item Schema
  type: JSONSchema
  url: json-schema/item.json
- title: Sales Order Schema
  type: JSONSchema
  url: json-schema/sales-order.json
- title: Purchase Order Schema
  type: JSONSchema
  url: json-schema/purchase-order.json
- title: BC v2 Customer Schema
  type: JSONSchema
  url: json-schema/business-central-v2-customer-schema.json
- title: BC v2 Vendor Schema
  type: JSONSchema
  url: json-schema/business-central-v2-vendor-schema.json
- title: BC v2 Item Schema
  type: JSONSchema
  url: json-schema/business-central-v2-item-schema.json
- title: BC v2 Sales Order Schema
  type: JSONSchema
  url: json-schema/business-central-v2-sales-order-schema.json
- title: BC v2 Purchase Order Schema
  type: JSONSchema
  url: json-schema/business-central-v2-purchase-order-schema.json
- title: Admin Center Environment Schema
  type: JSONSchema
  url: json-schema/admin-center-environment-schema.json
- title: Admin Center Environment Operation Schema
  type: JSONSchema
  url: json-schema/admin-center-environment-operation-schema.json
- title: Automation Extension Schema
  type: JSONSchema
  url: json-schema/automation-extension-schema.json
- title: Automation User Schema
  type: JSONSchema
  url: json-schema/automation-user-schema.json
- title: Automation Company Schema
  type: JSONSchema
  url: json-schema/automation-automation-company-schema.json
- title: JSON-LD Context
  type: JSONLD
  url: json-ld/context.jsonld
- title: Business Central v2 JSON-LD Context
  type: JSONLD
  url: json-ld/business-central-v2-context.jsonld
- title: Admin Center JSON-LD Context
  type: JSONLD
  url: json-ld/admin-center-context.jsonld
- title: Automation JSON-LD Context
  type: JSONLD
  url: json-ld/automation-context.jsonld
- title: Navision Vocabulary
  type: Vocabulary
  url: vocabulary/navision-vocabulary.yaml
- title: Spectral Rules
  type: Rules
  url: rules/navision-spectral-rules.yml
- title: Business Operations Workflow
  type: Capabilities
  url: capabilities/business-operations.yaml
- title: Platform Administration Workflow
  type: Capabilities
  url: capabilities/platform-administration.yaml
- title: Business Central v2 Shared Capability
  type: Capabilities
  url: capabilities/shared/business-central-v2.yaml
- title: Admin Center Shared Capability
  type: Capabilities
  url: capabilities/shared/admin-center.yaml
- title: Automation Shared Capability
  type: Capabilities
  url: capabilities/shared/automation.yaml
created: '2024-01-20'
description: API collection for Microsoft Dynamics NAV (formerly Navision), an enterprise resource planning (ERP) solution for small and medium-sized businesses. Dynamics NAV has evolved into Dynamics 365 Business Central, which provides modern REST, OData, and SOAP web services for business data integration.
features:
- description: General ledger, accounts payable/receivable, bank reconciliation, and financial reporting
  name: Financial Management
- description: Create and manage sales orders, invoices, credit memos, and quotes
  name: Sales Order Management
- description: Manage purchase orders, invoices, and vendor relationships
  name: Purchase Order Management
- description: Track items, stock levels, and inventory valuations
  name: Inventory Management
- description: Programmatic management of production and sandbox environments
  name: Environment Administration
- description: Automate company setup, extension management, and user provisioning
  name: Tenant Automation
image: /assets/icons/navision.png
integrations:
- description: Deep integration with Excel, Outlook, and Teams for business workflows
  name: Microsoft 365
- description: Connect to Power BI, Power Automate, and Power Apps
  name: Power Platform
- description: Sync orders, customers, and inventory with Shopify stores
  name: Shopify
jsonld:
- class_count: 0
  name: Admin Center Context
  property_count: 0
  slug: admin-center-context
- class_count: 0
  name: Automation Context
  property_count: 0
  slug: automation-context
- class_count: 0
  name: Business Central V2 Context
  property_count: 0
  slug: business-central-v2-context
- class_count: 0
  name: context Context
  property_count: 9
  slug: context
layout: provider
modified: '2026-04-18'
name: Microsoft Dynamics NAV
rules:
- name: Microsoft Dynamics NAV API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: navision-spectral-rules
skills: []
slug: navision
solutions: []
source_yaml: "name: Microsoft Dynamics NAV\ndescription: >-\n  API collection for Microsoft Dynamics NAV (formerly Navision), an enterprise\n  resource planning (ERP) solution for small and medium-sized businesses. Dynamics\n  NAV has evolved into Dynamics 365 Business Central, which provides modern REST,\n  OData, and SOAP web services for business data integration.\nimage: https://example.com/navision-logo.png\ncreated: '2024-01-20'\nmodified: '2026-04-18'\nurl: https://dynamics.microsoft.com/nav-overview/\nspecificationVersion: '0.19'\ntags:\n  - Business Management\n  - Dynamics NAV\n  - ERP\n  - Finance\n  - Inventory\n  - Microsoft\n  - Navision\napis:\n  - name: Dynamics NAV Web Services API\n    description: >-\n      SOAP and OData web services for interacting with Dynamics NAV business data.\n      Supports publishing pages, codeunits, and queries as web services for\n      external system integration.\n    image: https://example.com/nav-webservices-icon.png\n    humanURL: https://learn.microsoft.com/en-us/dynamics-nav/web-services\n\
  \    baseURL: https://{server}:{port}/{instance}/api/{version}\n    tags:\n      - Enterprise Resource Planning\n      - OData\n      - SOAP\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics-nav/microsoft-dynamics-nav-web-services-overview\n      - type: OpenAPI\n        url: https://example.com/openapi/nav-webservices.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/dynamics-nav/web-services-authentication\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/dynamics-nav/walkthrough--creating-and-interacting-with-a-page-web-service--odata-\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n        url: https://support.microsoft.com/dynamics\n  - name: Dynamics NAV OData API\n    description: >-\n      OData web services for querying and manipulating NAV business entities.\n      Supports both OData v3 and v4 protocols for\
  \ reading data and writing back\n      to the Dynamics NAV database through exposed pages and queries.\n    image: https://example.com/odata-icon.png\n    humanURL: https://learn.microsoft.com/en-us/dynamics-nav/odata-web-services\n    baseURL: https://{server}:{port}/{instance}/OData/Company('{company}')\n    tags:\n      - Business Data\n      - Data Integration\n      - OData\n      - Queries\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics-nav/odata-web-services\n      - type: OpenAPI\n        url: https://example.com/openapi/nav-odata.yaml\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/dynamics-nav/walkthrough--creating-and-interacting-with-a-page-web-service--odata-\n    contact:\n      - FN: Microsoft Support\n        email: support@microsoft.com\n  - name: Dynamics NAV SOAP Web Services\n    description: >-\n      SOAP-based web services for legacy integrations and business logic\n      operations\
  \ in Dynamics NAV. Exposes pages and codeunits with built-in\n      CRUD operations and supports extension codeunits for custom operations.\n    image: https://example.com/soap-icon.png\n    humanURL: https://learn.microsoft.com/en-us/dynamics-nav/soap-web-services\n    baseURL: https://{server}:{port}/{instance}/WS/{company}/\n    tags:\n      - Business Logic\n      - Codeunits\n      - Legacy Integration\n      - SOAP\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics-nav/soap-web-service-uris\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/dynamics-nav/walkthrough--creating-and-using-a-codeunit-web-service--soap-\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/dynamics-nav/walkthrough--registering-and-using-a-page-web-service--soap-\n  - name: Business Central API v2.0\n    description: >-\n      Modern RESTful API for Dynamics 365 Business Central, the cloud evolution\n  \
  \    of Dynamics NAV. Provides a comprehensive set of endpoints for managing\n      customers, items, accounts, sales orders, and other business entities.\n    image: https://example.com/bc-api-icon.png\n    humanURL: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/\n    baseURL: https://api.businesscentral.dynamics.com/v2.0/{environment}/api/v2.0\n    tags:\n      - Business Central\n      - Business Data\n      - Cloud ERP\n      - Connect Apps\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/endpoints-apis-for-dynamics\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/authenticate-web-services-using-oauth\n   \
  \   - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-develop-connect-apps\n      - type: ChangeLog\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/whatsnew/overview\n      - type: OpenAPI\n        url: openapi/business-central-api-v2.yml\n    contact:\n      - FN: Microsoft Dynamics Support\n        email: bcsupport@microsoft.com\n        url: https://dynamics.microsoft.com/support/\n  - name: Business Central Administration Center API\n    description: >-\n      REST API for programmatic administration of Business Central environments.\n      Enables querying and managing production and sandbox environments, setting\n      up notifications, and viewing tenant telemetry.\n    image: https://example.com/bc-admin-icon.png\n    humanURL: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/administration-center-api\n    baseURL: https://api.businesscentral.dynamics.com/admin/v2.28\n\
  \    tags:\n      - Administration\n      - Cloud ERP\n      - Environment Management\n      - Tenant Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/administration-center-api\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/automation-apis-using-s2s-authentication\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/\n      - type: OpenAPI\n        url: openapi/admin-center-api.yml\n    contact:\n      - FN: Microsoft Dynamics Support\n        email: bcsupport@microsoft.com\n        url: https://dynamics.microsoft.com/support/\n  - name: Business Central Automation API\n    description: >-\n      API for automating company setup and tenant management in Business Central.\n      Supports creating companies, installing extensions, assigning\
  \ permissions,\n      and applying RapidStart packages programmatically.\n    image: https://example.com/bc-automation-icon.png\n    humanURL: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/itpro-introduction-to-automation-apis\n    baseURL: https://api.businesscentral.dynamics.com/v2.0/{environment}/api/microsoft/automation/v2.0\n    tags:\n      - Automation\n      - Extension Management\n      - Tenant Management\n      - User Management\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/itpro-introduction-to-automation-apis\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/automation-apis-using-s2s-authentication\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-develop-connect-apps\n\
  \      - type: OpenAPI\n        url: openapi/automation-api.yml\n    contact:\n      - FN: Microsoft Dynamics Support\n        email: bcsupport@microsoft.com\n        url: https://dynamics.microsoft.com/support/\n  - name: Business Central REST API Web Services\n    description: >-\n      RESTful web services layer for Business Central that provides the preferred\n      integration method. Includes built-in APIs, custom API pages and queries,\n      and supports both on-premises and cloud deployments.\n    image: https://example.com/bc-rest-icon.png\n    humanURL: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/api-overview\n    baseURL: https://api.businesscentral.dynamics.com/v2.0/{environment}/api\n    tags:\n      - Business Central\n      - Custom APIs\n      - Data Integration\n      - REST API\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/api-overview\n\
  \      - type: APIReference\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/endpoints-apis-for-dynamics\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/webservices/authenticate-web-services-using-oauth\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-get-started\n    contact:\n      - FN: Microsoft Dynamics Support\n        email: bcsupport@microsoft.com\n        url: https://dynamics.microsoft.com/support/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://dynamics.microsoft.com\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-get-started\n\
  \  - type: Authentication\n    url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/administration/users-credential-types\n  - type: Blog\n    url: https://www.microsoft.com/en-us/dynamics-365/blog/product/dynamics-365-business-central/\n  - type: ChangeLog\n    url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/whatsnew/overview\n  - type: Support\n    url: https://support.microsoft.com/dynamics\n  - type: SignUp\n    url: https://learn.microsoft.com/en-us/dynamics365/business-central/trial-signup\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/dynamics-365/products/business-central/pricing\n  - type: TermsOfService\n    url: https://www.microsoft.com/en/dynamics-365/business-applications/legal\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com\n  - type: StatusPage\n    url: https://status.cloud.microsoft\n  - type: GitHubOrganization\n    url: https://github.com/microsoft/BCApps\n  - type: GitHubRepository\n\
  \    url: https://github.com/christianbraeunlich/d365bc-api-postman\n  - type: RateLimits\n    url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/dynamics-rate-limits\n  - type: Features\n    data:\n      - name: Financial Management\n        description: General ledger, accounts payable/receivable, bank reconciliation, and financial reporting\n      - name: Sales Order Management\n        description: Create and manage sales orders, invoices, credit memos, and quotes\n      - name: Purchase Order Management\n        description: Manage purchase orders, invoices, and vendor relationships\n      - name: Inventory Management\n        description: Track items, stock levels, and inventory valuations\n      - name: Environment Administration\n        description: Programmatic management of production and sandbox environments\n      - name: Tenant Automation\n        description: Automate company setup, extension management, and user provisioning\n\
  \  - type: UseCases\n    data:\n      - name: ERP Integration\n        description: Connect external systems to Business Central for real-time business data sync\n      - name: Multi-Company Management\n        description: Automate company creation and configuration across Business Central tenants\n      - name: Financial Reporting\n        description: Extract general ledger entries and account data for custom reporting\n  - type: Integrations\n    data:\n      - name: Microsoft 365\n        description: Deep integration with Excel, Outlook, and Teams for business workflows\n      - name: Power Platform\n        description: Connect to Power BI, Power Automate, and Power Apps\n      - name: Shopify\n        description: Sync orders, customers, and inventory with Shopify stores\n  - type: SDK\n    url: https://github.com/niclas-timm/laravel-dynamics-365-business-central\n    title: Laravel SDK\n  - type: SDK\n    url: https://github.com/AgoraIO/agora-rest-client-go\n    title: Go REST\
  \ Client\n  - type: CLI\n    url: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/developer/devenv-command-line-tools\n    title: AL Language CLI\n  - type: JSONSchema\n    url: json-schema/customer.json\n    title: Customer Schema\n  - type: JSONSchema\n    url: json-schema/vendor.json\n    title: Vendor Schema\n  - type: JSONSchema\n    url: json-schema/item.json\n    title: Item Schema\n  - type: JSONSchema\n    url: json-schema/sales-order.json\n    title: Sales Order Schema\n  - type: JSONSchema\n    url: json-schema/purchase-order.json\n    title: Purchase Order Schema\n  - type: JSONSchema\n    url: json-schema/business-central-v2-customer-schema.json\n    title: BC v2 Customer Schema\n  - type: JSONSchema\n    url: json-schema/business-central-v2-vendor-schema.json\n    title: BC v2 Vendor Schema\n  - type: JSONSchema\n    url: json-schema/business-central-v2-item-schema.json\n    title: BC v2 Item Schema\n  - type: JSONSchema\n    url: json-schema/business-central-v2-sales-order-schema.json\n\
  \    title: BC v2 Sales Order Schema\n  - type: JSONSchema\n    url: json-schema/business-central-v2-purchase-order-schema.json\n    title: BC v2 Purchase Order Schema\n  - type: JSONSchema\n    url: json-schema/admin-center-environment-schema.json\n    title: Admin Center Environment Schema\n  - type: JSONSchema\n    url: json-schema/admin-center-environment-operation-schema.json\n    title: Admin Center Environment Operation Schema\n  - type: JSONSchema\n    url: json-schema/automation-extension-schema.json\n    title: Automation Extension Schema\n  - type: JSONSchema\n    url: json-schema/automation-user-schema.json\n    title: Automation User Schema\n  - type: JSONSchema\n    url: json-schema/automation-automation-company-schema.json\n    title: Automation Company Schema\n  - type: JSONLD\n    url: json-ld/context.jsonld\n    title: JSON-LD Context\n  - type: JSONLD\n    url: json-ld/business-central-v2-context.jsonld\n    title: Business Central v2 JSON-LD Context\n  - type: JSONLD\n\
  \    url: json-ld/admin-center-context.jsonld\n    title: Admin Center JSON-LD Context\n  - type: JSONLD\n    url: json-ld/automation-context.jsonld\n    title: Automation JSON-LD Context\n  - type: Vocabulary\n    url: vocabulary/navision-vocabulary.yaml\n    title: Navision Vocabulary\n  - type: Rules\n    url: rules/navision-spectral-rules.yml\n    title: Spectral Rules\n  - type: Capabilities\n    url: capabilities/business-operations.yaml\n    title: Business Operations Workflow\n  - type: Capabilities\n    url: capabilities/platform-administration.yaml\n    title: Platform Administration Workflow\n  - type: Capabilities\n    url: capabilities/shared/business-central-v2.yaml\n    title: Business Central v2 Shared Capability\n  - type: Capabilities\n    url: capabilities/shared/admin-center.yaml\n    title: Admin Center Shared Capability\n  - type: Capabilities\n    url: capabilities/shared/automation.yaml\n    title: Automation Shared Capability\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/navision/refs/heads/main/apis.yml
tags:
- Business Management
- Dynamics NAV
- ERP
- Finance
- Inventory
- Microsoft
- Navision
url: https://dynamics.microsoft.com/nav-overview/
use_cases:
- description: Connect external systems to Business Central for real-time business data sync
  name: ERP Integration
- description: Automate company creation and configuration across Business Central tenants
  name: Multi-Company Management
- description: Extract general ledger entries and account data for custom reporting
  name: Financial Reporting
---
