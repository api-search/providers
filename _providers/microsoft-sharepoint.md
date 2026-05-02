---
api_count: 5
apis:
- description: The SharePoint REST API provides direct access to SharePoint sites, lists, libraries, items, and other resources using OData endpoints. Developers can perform CRUD operations on SharePoint content, ma
  name: SharePoint REST API
  slug: rest-api
- description: 'The Microsoft Graph SharePoint Sites API provides access to SharePoint sites, lists, and document libraries through the unified Microsoft Graph endpoint. It enables developers to manage site content, '
  name: Microsoft Graph SharePoint Sites API
  slug: graph-sites-api
- description: 'The SharePoint Webhooks API enables applications to subscribe to change notifications on SharePoint lists and libraries. When items are created, updated, or deleted, SharePoint sends notifications to '
  name: SharePoint Webhooks API
  slug: webhooks-api
- description: 'The SharePoint Search REST API provides full-text search capabilities across SharePoint content including sites, lists, libraries, and documents. It supports keyword query language, query refinement, '
  name: SharePoint Search REST API
  slug: search-api
- description: 'The SharePoint Framework (SPFx) is a development model for building client-side web parts, extensions, and adaptive card extensions for SharePoint and Microsoft Teams. It uses modern web technologies '
  name: SharePoint Framework (SPFx)
  slug: framework
common:
- title: ''
  type: Portal
  url: https://portal.azure.com/
- title: ''
  type: Website
  url: https://www.microsoft.com/en-us/microsoft-365/sharepoint/collaboration
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/sharepoint/dev/
- title: ''
  type: Developer Portal
  url: https://developer.microsoft.com/en-us/sharepoint
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/sharepoint/dev/solution-guidance/security-apponly-azureacs
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/complete-basic-operations-using-sharepoint-rest-endpoints
- title: ''
  type: GitHub Organization
  url: https://github.com/SharePoint
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://support.microsoft.com/
created: '2024-01-01'
description: Microsoft SharePoint is a web-based collaboration platform that provides document management, content management, and team collaboration capabilities. It offers REST APIs, Microsoft Graph integration, and the SharePoint Framework for customization and extension.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft SharePoint
skills: []
slug: microsoft-sharepoint
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-sharepoint\nname: Microsoft SharePoint\ndescription: >-\n  Microsoft SharePoint is a web-based collaboration platform that provides\n  document management, content management, and team collaboration capabilities.\n  It offers REST APIs, Microsoft Graph integration, and the SharePoint Framework\n  for customization and extension.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Collaboration\n  - Content Management\n  - Microsoft\n  - Microsoft 365\n  - SharePoint\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-sharepoint/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: microsoft-sharepoint:rest-api\n    name: SharePoint REST API\n    tags:\n      - Collaboration\n      - Content Management\n      - SharePoint\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://{tenant}.sharepoint.com/_api/\n\
  \    humanURL: https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/get-to-know-the-sharepoint-rest-service\n    properties:\n      - url: https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/get-to-know-the-sharepoint-rest-service\n        type: Documentation\n      - url: https://learn.microsoft.com/en-us/sharepoint/dev/apis/sharepoint-rest-graph\n        type: Reference\n    description: >-\n      The SharePoint REST API provides direct access to SharePoint sites,\n      lists, libraries, items, and other resources using OData endpoints.\n      Developers can perform CRUD operations on SharePoint content, manage\n      site structures, work with content types, and interact with search\n      and taxonomy services.\n  - aid: microsoft-sharepoint:graph-sites-api\n    name: Microsoft Graph SharePoint Sites API\n    tags:\n      - Microsoft Graph\n      - SharePoint\n      - Sites\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL:\
  \ https://graph.microsoft.com/v1.0/\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/sharepoint\n    properties:\n      - url: https://learn.microsoft.com/en-us/graph/api/resources/sharepoint\n        type: Documentation\n    description: >-\n      The Microsoft Graph SharePoint Sites API provides access to SharePoint\n      sites, lists, and document libraries through the unified Microsoft\n      Graph endpoint. It enables developers to manage site content, list\n      items, drive items, and site permissions using a consistent REST\n      interface alongside other Microsoft 365 services.\n  - aid: microsoft-sharepoint:webhooks-api\n    name: SharePoint Webhooks API\n    tags:\n      - Events\n      - SharePoint\n      - Webhooks\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://{tenant}.sharepoint.com/_api/\n    humanURL: https://learn.microsoft.com/en-us/sharepoint/dev/apis/webhooks/overview-sharepoint-webhooks\n\
  \    properties:\n      - url: https://learn.microsoft.com/en-us/sharepoint/dev/apis/webhooks/overview-sharepoint-webhooks\n        type: Documentation\n    description: >-\n      The SharePoint Webhooks API enables applications to subscribe to\n      change notifications on SharePoint lists and libraries. When items\n      are created, updated, or deleted, SharePoint sends notifications to\n      registered webhook endpoints, enabling real-time event-driven\n      integrations without polling.\n  - aid: microsoft-sharepoint:search-api\n    name: SharePoint Search REST API\n    tags:\n      - Content Discovery\n      - Search\n      - SharePoint\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://{tenant}.sharepoint.com/_api/search/\n    humanURL: https://learn.microsoft.com/en-us/sharepoint/dev/general-development/sharepoint-search-rest-api-overview\n    properties:\n      - url: https://learn.microsoft.com/en-us/sharepoint/dev/general-development/sharepoint-search-rest-api-overview\n\
  \        type: Documentation\n    description: >-\n      The SharePoint Search REST API provides full-text search capabilities\n      across SharePoint content including sites, lists, libraries, and\n      documents. It supports keyword query language, query refinement,\n      result sorting, and content source targeting for comprehensive\n      enterprise search scenarios.\n  - aid: microsoft-sharepoint:framework\n    name: SharePoint Framework (SPFx)\n    tags:\n      - Extensions\n      - Framework\n      - SharePoint\n      - Web Parts\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://learn.microsoft.com/en-us/sharepoint/dev/spfx/sharepoint-framework-overview\n    properties:\n      - url: https://learn.microsoft.com/en-us/sharepoint/dev/spfx/sharepoint-framework-overview\n        type: Documentation\n    description: >-\n      The SharePoint Framework (SPFx) is a development model for building\n      client-side web parts,\
  \ extensions, and adaptive card extensions for\n      SharePoint and Microsoft Teams. It uses modern web technologies\n      including TypeScript, React, and Node.js to create customizations\n      that run in the context of SharePoint pages.\ncommon:\n  - type: Portal\n    url: https://portal.azure.com/\n  - type: Website\n    url: https://www.microsoft.com/en-us/microsoft-365/sharepoint/collaboration\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/sharepoint/dev/\n  - type: Developer Portal\n    url: https://developer.microsoft.com/en-us/sharepoint\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/sharepoint/dev/solution-guidance/security-apponly-azureacs\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/sharepoint/dev/sp-add-ins/complete-basic-operations-using-sharepoint-rest-endpoints\n  - type: GitHub Organization\n    url: https://github.com/SharePoint\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n\
  \  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Support\n    url: https://support.microsoft.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-sharepoint/refs/heads/main/apis.yml
tags:
- Collaboration
- Content Management
- Microsoft
- Microsoft 365
- SharePoint
url: https://raw.githubusercontent.com/api-evangelist/microsoft-sharepoint/refs/heads/main/apis.yml
use_cases: []
---
