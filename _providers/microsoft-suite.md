---
api_count: 7
api_specs:
- filename: openapi
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.microsoft.com/graph/openapi
apis:
- description: Unified API endpoint for accessing Microsoft 365 services including users, groups, mail, calendars, contacts, files, and more.
  name: Microsoft Graph API
  slug: ''
- description: API for integrating with Microsoft Teams to create bots, tabs, messaging extensions, and connectors.
  name: Microsoft Teams API
  slug: ''
- description: REST API for accessing files stored in OneDrive and SharePoint document libraries.
  name: OneDrive API
  slug: ''
- description: Access to Outlook mail, calendar, contacts, and tasks via Microsoft Graph.
  name: Outlook Mail API
  slug: ''
- description: Access SharePoint sites, lists, and content via REST and Microsoft Graph APIs.
  name: SharePoint API
  slug: ''
- description: Identity and access management API for authentication and authorization.
  name: Azure Active Directory API
  slug: ''
- description: Embed Power BI reports and dashboards, and manage Power BI resources programmatically.
  name: Power BI API
  slug: ''
common:
- title: ''
  type: Terms of Service
  url: https://docs.microsoft.com/legal/termsofuse
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/
- title: ''
  type: Support
  url: https://developer.microsoft.com/support
- title: ''
  type: Status
  url: https://status.dev.microsoft.com/
- title: ''
  type: Blog
  url: https://developer.microsoft.com/blog
created: '2024'
description: Collection of APIs for Microsoft's productivity and cloud services suite.
features: []
image: https://www.microsoft.com/favicon.ico
integrations: []
layout: provider
modified: '2026-04-28'
name: Microsoft Suite
skills: []
slug: microsoft-suite
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-suite\nname: Microsoft Suite\ndescription: >-\n  Collection of APIs for Microsoft's productivity and cloud services suite.\nimage: https://www.microsoft.com/favicon.ico\nurl: https://developer.microsoft.com\ntags:\n  - Cloud\n  - Enterprise\n  - Productivity\n  - SaaS\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - name: Microsoft Graph API\n    description: >-\n      Unified API endpoint for accessing Microsoft 365 services including users, groups,\n      mail, calendars, contacts, files, and more.\n    image: https://docs.microsoft.com/graph/images/microsoft-graph.png\n    humanUrl: https://developer.microsoft.com/graph\n    baseUrl: https://graph.microsoft.com/v1.0\n    tags:\n      - Collaboration\n      - Identity\n      - Microsoft-365\n      - Unified-Api\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/graph/api/overview\n      - type: OpenAPI\n        url: https://developer.microsoft.com/graph/openapi\n\
  \      - type: Authentication\n        url: https://docs.microsoft.com/graph/auth/\n      - type: SDKs\n        url: https://docs.microsoft.com/graph/sdks/sdks-overview\n      - type: Pricing\n        url: https://azure.microsoft.com/pricing/details/active-directory/\n  - name: Microsoft Teams API\n    description: >-\n      API for integrating with Microsoft Teams to create bots, tabs, messaging extensions,\n      and connectors.\n    humanUrl: https://developer.microsoft.com/microsoft-teams\n    baseUrl: https://graph.microsoft.com/v1.0/teams\n    tags:\n      - Bots\n      - Chat\n      - Collaboration\n      - Meetings\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/microsoftteams/platform/\n      - type: Getting Started\n        url: https://docs.microsoft.com/microsoftteams/platform/get-started/get-started-overview\n      - type: Webhooks\n        url: https://docs.microsoft.com/microsoftteams/platform/webhooks-and-connectors/what-are-webhooks-and-connectors\n\
  \  - name: OneDrive API\n    description: >-\n      REST API for accessing files stored in OneDrive and SharePoint document libraries.\n    humanUrl: https://developer.microsoft.com/onedrive\n    baseUrl: https://graph.microsoft.com/v1.0/me/drive\n    tags:\n      - Cloud-Storage\n      - Files\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/onedrive/developer/\n      - type: REST API Reference\n        url: https://docs.microsoft.com/onedrive/developer/rest-api/\n      - type: SDKs\n        url: https://docs.microsoft.com/onedrive/developer/sdks/\n  - name: Outlook Mail API\n    description: >-\n      Access to Outlook mail, calendar, contacts, and tasks via Microsoft Graph.\n    humanUrl: https://developer.microsoft.com/outlook\n    baseUrl: https://graph.microsoft.com/v1.0/me/messages\n    tags:\n      - Calendar\n      - Contacts\n      - Email\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/graph/outlook-mail-concept-overview\n\
  \      - type: REST API Reference\n        url: https://docs.microsoft.com/graph/api/resources/mail-api-overview\n  - name: SharePoint API\n    description: >-\n      Access SharePoint sites, lists, and content via REST and Microsoft Graph APIs.\n    humanUrl: https://developer.microsoft.com/sharepoint\n    baseUrl: https://graph.microsoft.com/v1.0/sites\n    tags:\n      - Collaboration\n      - Content-Management\n      - Intranet\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/sharepoint/dev/\n      - type: REST API\n        url: https://docs.microsoft.com/sharepoint/dev/sp-add-ins/get-to-know-the-sharepoint-rest-service\n      - type: Graph API\n        url: https://docs.microsoft.com/graph/api/resources/sharepoint\n  - name: Azure Active Directory API\n    description: >-\n      Identity and access management API for authentication and authorization.\n    humanUrl: https://developer.microsoft.com/identity\n    baseUrl: https://graph.microsoft.com/v1.0/users\n\
  \    tags:\n      - Authentication\n      - Authorization\n      - Identity\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/azure/active-directory/develop/\n      - type: Authentication Flows\n        url: https://docs.microsoft.com/azure/active-directory/develop/authentication-flows-app-scenarios\n      - type: Microsoft Identity Platform\n        url: https://docs.microsoft.com/azure/active-directory/develop/v2-overview\n  - name: Power BI API\n    description: >-\n      Embed Power BI reports and dashboards, and manage Power BI resources programmatically.\n    humanUrl: https://developer.microsoft.com/power-bi\n    baseUrl: https://api.powerbi.com/v1.0\n    tags:\n      - Analytics\n      - Business-Intelligence\n      - Visualization\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/power-bi/developer/\n      - type: REST API Reference\n        url: https://docs.microsoft.com/rest/api/power-bi/\n\
  \      - type: Embedding\n        url: https://docs.microsoft.com/power-bi/developer/embedded/embedding\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Terms of Service\n    url: https://docs.microsoft.com/legal/termsofuse\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/\n  - type: Support\n    url: https://developer.microsoft.com/support\n  - type: Status\n    url: https://status.dev.microsoft.com/\n  - type: Blog\n    url: https://developer.microsoft.com/blog\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-suite/refs/heads/main/apis.yml
tags:
- Cloud
- Enterprise
- Productivity
- SaaS
url: https://developer.microsoft.com
use_cases: []
---
