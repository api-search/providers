---
api_count: 4
api_specs:
- filename: sharepoint-rest-openapi.json
  format: json
  label: SharePoint REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://example.com/sharepoint-rest-openapi.json
- filename: graph-sharepoint-openapi.json
  format: json
  label: Microsoft Graph API (SharePoint)
  slug: graph-api-sharepoint
  spec_type: OpenAPI
  url: https://example.com/graph-sharepoint-openapi.json
apis:
- description: The SharePoint REST API enables developers to interact remotely with SharePoint data using any technology that supports REST web requests.
  name: SharePoint REST API
  slug: rest-api
- description: Access SharePoint sites, lists, and documents through the Microsoft Graph unified API endpoint.
  name: Microsoft Graph API (SharePoint)
  slug: graph-api-sharepoint
- description: Client-side object model for SharePoint that provides access to SharePoint objects through .NET managed or JavaScript libraries.
  name: SharePoint CSOM (Client-Side Object Model)
  slug: csom-client-side-object-model
- description: SharePoint webhooks provide a way to get notified about changes to SharePoint lists and document libraries.
  name: SharePoint Webhooks API
  slug: webhooks-api
capabilities:
- description: Unified workflow for managing SharePoint content including sites, lists, items, files, and search. Used by content managers, site admins, and collaboration teams.
  name: SharePoint Content Management
  slug: content-management
common:
- title: ''
  type: Developer Portal
  url: https://developer.microsoft.com/en-us/sharepoint
- title: ''
  type: Code Samples
  url: https://pnp.github.io/
- title: ''
  type: Community
  url: https://techcommunity.microsoft.com/t5/sharepoint/ct-p/SharePoint
- title: ''
  type: Support
  url: https://support.microsoft.com/en-us/sharepoint
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/microsoft-365/sharepoint/compare-sharepoint-plans
- title: ''
  type: StatusPage
  url: https://status.cloud.microsoft/
created: '2024'
description: Microsoft SharePoint is a web-based collaborative platform that integrates with Microsoft Office. It provides enterprise content management, document management, and collaboration capabilities.
features:
- description: Create, read, update, and delete SharePoint sites and subsites.
  name: Sites and Webs
- description: Full CRUD operations on lists, document libraries, and list items.
  name: Lists and Libraries
- description: Upload, download, check in/out, and manage documents and file versions.
  name: Document Management
- description: Create folder hierarchies and manage files within document libraries.
  name: Folders and Files
- description: Manage site, list, and item-level permissions with role assignments.
  name: Permissions and Security
- description: Full-text search across sites, documents, and content using the Search REST API.
  name: Search
- description: Access user profile properties, people search, and organizational data.
  name: User Profiles
- description: Manage content types, site columns, and metadata schemas.
  name: Content Types
- description: Subscribe to change notifications for lists and libraries via webhooks.
  name: Webhooks
- description: Access SharePoint data through Microsoft Graph API for unified Microsoft 365 integration.
  name: Microsoft Graph Integration
- description: Combine multiple REST operations into a single batch request.
  name: Batch Requests
- description: Filter, select, expand, and order data using OData query operators.
  name: OData Query Support
image: /assets/icons/sharepoint.png
integrations:
- description: Native integration with Teams, OneDrive, Outlook, and other Microsoft 365 apps.
  name: Microsoft 365
- description: Unified API access to SharePoint alongside all Microsoft 365 services.
  name: Microsoft Graph
- description: Power Apps, Power Automate, and Power BI integration for low-code solutions.
  name: Power Platform
- description: Azure AD for authentication, Azure Functions for serverless processing.
  name: Azure
- description: SharePoint powers file storage and document collaboration in Microsoft Teams.
  name: Teams
jsonld:
- class_count: 11
  name: Sharepoint Context
  property_count: 35
  slug: sharepoint-context
layout: provider
modified: '2026-04-17'
name: Microsoft SharePoint
rules:
- name: Microsoft SharePoint API Rules
  rule_count: 17
  severity_counts:
    error: 14
    hint: 0
    info: 1
    warn: 2
  slug: sharepoint-spectral-rules
skills: []
slug: sharepoint
solutions:
- description: Cloud-hosted SharePoint as part of Microsoft 365 with REST and Graph APIs.
  name: SharePoint Online
- description: On-premises SharePoint with REST, CSOM, and server-side object model.
  name: SharePoint Server
- description: Modern client-side development framework for building web parts and extensions.
  name: SharePoint Framework (SPFx)
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Microsoft SharePoint\ndescription: Microsoft SharePoint is a web-based collaborative platform that integrates\n  with Microsoft Office. It provides enterprise content management, document management,\n  and collaboration capabilities.\nimage: https://example.com/sharepoint-logo.png\ntags:\n- Collaboration\n- Document Management\n- Enterprise Content Management\n- Intranet\n- Microsoft\ncreated: '2024'\nmodified: '2026-04-17'\nurl: https://raw.githubusercontent.com/api-evangelist/sharepoint/refs/heads/main/apis.yml\napis:\n- name: SharePoint REST API\n  description: The SharePoint REST API enables developers to interact remotely with\n    SharePoint data using any technology that supports REST web requests.\n  image: https://example.com/sharepoint-rest-api.png\n  humanUrl: https://docs.microsoft.com/en-us/sharepoint/dev/sp-add-ins/get-to-know-the-sharepoint-rest-service\n  baseUrl: https://{site_url}/_api\n  tags:\n  - Documents\n  - Lists\n  - REST\n  - Sites\n  properties:\n\
  \  - type: Documentation\n    url: https://docs.microsoft.com/en-us/sharepoint/dev/sp-add-ins/complete-basic-operations-using-sharepoint-rest-endpoints\n  - type: OpenAPI\n    url: https://example.com/sharepoint-rest-openapi.json\n  - type: Authentication\n    url: https://docs.microsoft.com/en-us/sharepoint/dev/sp-add-ins/authorization-and-authentication-of-sharepoint-add-ins\n  aid: sharepoint:rest-api\n- name: Microsoft Graph API (SharePoint)\n  description: Access SharePoint sites, lists, and documents through the Microsoft\n    Graph unified API endpoint.\n  image: https://example.com/microsoft-graph.png\n  humanUrl: https://docs.microsoft.com/en-us/graph/api/resources/sharepoint\n  baseUrl: https://graph.microsoft.com/v1.0\n  tags:\n  - Drive\n  - Graph\n  - Lists\n  - Modern\n  - Sites\n  properties:\n  - type: Documentation\n    url: https://docs.microsoft.com/en-us/graph/api/resources/sharepoint\n  - type: OpenAPI\n    url: https://example.com/graph-sharepoint-openapi.json\n \
  \ - type: SDK\n    url: https://docs.microsoft.com/en-us/graph/sdks/sdks-overview\n  - type: Authentication\n    url: https://docs.microsoft.com/en-us/graph/auth/\n  aid: sharepoint:graph-api-sharepoint\n- name: SharePoint CSOM (Client-Side Object Model)\n  description: Client-side object model for SharePoint that provides access to SharePoint\n    objects through .NET managed or JavaScript libraries.\n  image: https://example.com/sharepoint-csom.png\n  humanUrl: https://docs.microsoft.com/en-us/sharepoint/dev/sp-add-ins/complete-basic-operations-using-sharepoint-client-library-code\n  baseUrl: N/A\n  tags:\n  - .NET\n  - Client Library\n  - CSOM\n  - JavaScript\n  properties:\n  - type: Documentation\n    url: https://docs.microsoft.com/en-us/sharepoint/dev/sp-add-ins/complete-basic-operations-using-sharepoint-client-library-code\n  - type: NuGet Package\n    url: https://www.nuget.org/packages/Microsoft.SharePointOnline.CSOM/\n  - type: JavaScript Reference\n    url: https://docs.microsoft.com/en-us/sharepoint/dev/sp-add-ins/complete-basic-operations-using-javascript-library-code-in-sharepoint\n\
  \  aid: sharepoint:csom-client-side-object-model\n- name: SharePoint Webhooks API\n  description: SharePoint webhooks provide a way to get notified about changes to\n    SharePoint lists and document libraries.\n  image: https://example.com/sharepoint-webhooks.png\n  humanUrl: https://docs.microsoft.com/en-us/sharepoint/dev/apis/webhooks/overview-sharepoint-webhooks\n  baseUrl: https://{site_url}/_api/web/lists('{list-id}')/subscriptions\n  tags:\n  - Events\n  - Notifications\n  - Real-Time\n  - Webhooks\n  properties:\n  - type: Documentation\n    url: https://docs.microsoft.com/en-us/sharepoint/dev/apis/webhooks/overview-sharepoint-webhooks\n  - type: GettingStarted\n    url: https://docs.microsoft.com/en-us/sharepoint/dev/apis/webhooks/get-started-webhooks\n  aid: sharepoint:webhooks-api\ncommon:\n- type: Developer Portal\n  url: https://developer.microsoft.com/en-us/sharepoint\n- type: Code Samples\n  url: https://pnp.github.io/\n- type: Community\n  url: https://techcommunity.microsoft.com/t5/sharepoint/ct-p/SharePoint\n\
  - type: Support\n  url: https://support.microsoft.com/en-us/sharepoint\n- type: Pricing\n  url: https://www.microsoft.com/en-us/microsoft-365/sharepoint/compare-sharepoint-plans\n- type: StatusPage\n  url: https://status.cloud.microsoft/\n- type: Features\n  data:\n  - name: Sites and Webs\n    description: Create, read, update, and delete SharePoint sites and subsites.\n  - name: Lists and Libraries\n    description: Full CRUD operations on lists, document libraries, and list items.\n  - name: Document Management\n    description: Upload, download, check in/out, and manage documents and file versions.\n  - name: Folders and Files\n    description: Create folder hierarchies and manage files within document libraries.\n  - name: Permissions and Security\n    description: Manage site, list, and item-level permissions with role assignments.\n  - name: Search\n    description: Full-text search across sites, documents, and content using the Search\n      REST API.\n  - name: User Profiles\n\
  \    description: Access user profile properties, people search, and organizational\n      data.\n  - name: Content Types\n    description: Manage content types, site columns, and metadata schemas.\n  - name: Webhooks\n    description: Subscribe to change notifications for lists and libraries via webhooks.\n  - name: Microsoft Graph Integration\n    description: Access SharePoint data through Microsoft Graph API for unified Microsoft\n      365 integration.\n  - name: Batch Requests\n    description: Combine multiple REST operations into a single batch request.\n  - name: OData Query Support\n    description: Filter, select, expand, and order data using OData query operators.\n- type: UseCases\n  data:\n  - name: Document Automation\n    description: Automate document upload, metadata tagging, and approval workflows.\n  - name: Intranet Content Management\n    description: Programmatically manage site pages, news posts, and navigation.\n  - name: Data Integration\n    description: Sync\
  \ SharePoint list data with external databases and applications.\n  - name: Migration\n    description: Migrate content between SharePoint sites or from file shares to SharePoint.\n  - name: Custom Applications\n    description: Build SPFx web parts and extensions with SharePoint Framework.\n  - name: Compliance and Governance\n    description: Manage retention policies, sensitivity labels, and audit logs.\n  - name: Search Integration\n    description: Build custom search experiences with facets, refiners, and result\n      types.\n  - name: Power Automate Flows\n    description: Trigger and manage automated workflows based on SharePoint events.\n- type: Integrations\n  data:\n  - name: Microsoft 365\n    description: Native integration with Teams, OneDrive, Outlook, and other Microsoft\n      365 apps.\n  - name: Microsoft Graph\n    description: Unified API access to SharePoint alongside all Microsoft 365 services.\n  - name: Power Platform\n    description: Power Apps, Power Automate,\
  \ and Power BI integration for low-code\n      solutions.\n  - name: Azure\n    description: Azure AD for authentication, Azure Functions for serverless processing.\n  - name: Teams\n    description: SharePoint powers file storage and document collaboration in Microsoft\n      Teams.\n- type: Solutions\n  data:\n  - name: SharePoint Online\n    description: Cloud-hosted SharePoint as part of Microsoft 365 with REST and Graph\n      APIs.\n  - name: SharePoint Server\n    description: On-premises SharePoint with REST, CSOM, and server-side object model.\n  - name: SharePoint Framework (SPFx)\n    description: Modern client-side development framework for building web parts and\n      extensions.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\naid: sharepoint\ntype: Index\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sharepoint/refs/heads/main/apis.yml
tags:
- Collaboration
- Document Management
- Enterprise Content Management
- Intranet
- Microsoft
url: https://raw.githubusercontent.com/api-evangelist/sharepoint/refs/heads/main/apis.yml
use_cases:
- description: Automate document upload, metadata tagging, and approval workflows.
  name: Document Automation
- description: Programmatically manage site pages, news posts, and navigation.
  name: Intranet Content Management
- description: Sync SharePoint list data with external databases and applications.
  name: Data Integration
- description: Migrate content between SharePoint sites or from file shares to SharePoint.
  name: Migration
- description: Build SPFx web parts and extensions with SharePoint Framework.
  name: Custom Applications
- description: Manage retention policies, sensitivity labels, and audit logs.
  name: Compliance and Governance
- description: Build custom search experiences with facets, refiners, and result types.
  name: Search Integration
- description: Trigger and manage automated workflows based on SharePoint events.
  name: Power Automate Flows
---
