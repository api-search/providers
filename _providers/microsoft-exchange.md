---
api_count: 9
api_specs:
- filename: microsoft-exchange-graph-mail-openapi.yml
  format: yaml
  label: Microsoft Graph Mail API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/openapi/microsoft-exchange-graph-mail-openapi.yml
- filename: microsoft-exchange-graph-calendar-openapi.yml
  format: yaml
  label: Microsoft Graph Calendar API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/openapi/microsoft-exchange-graph-calendar-openapi.yml
- filename: microsoft-exchange-graph-contacts-openapi.yml
  format: yaml
  label: Microsoft Graph Contacts API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/openapi/microsoft-exchange-graph-contacts-openapi.yml
- filename: microsoft-exchange-graph-people-openapi.yml
  format: yaml
  label: Microsoft Graph People API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/openapi/microsoft-exchange-graph-people-openapi.yml
- filename: microsoft-exchange-admin-api-openapi.yml
  format: yaml
  label: Exchange Online Admin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/openapi/microsoft-exchange-admin-api-openapi.yml
- filename: microsoft-exchange-graph-import-export-openapi.yml
  format: yaml
  label: Microsoft Graph Mailbox Import Export API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/openapi/microsoft-exchange-graph-import-export-openapi.yml
apis:
- description: Access Exchange Online mailboxes through the Microsoft Graph API, providing modern REST endpoints for reading, sending, and managing email messages, drafts, attachments, and mail folders.
  name: Microsoft Graph Mail API
  slug: ''
- description: Manage calendar events, meetings, and scheduling for Exchange Online users. Provides endpoints for creating, updating, and deleting events, managing attendees, and handling recurring meetings.
  name: Microsoft Graph Calendar API
  slug: ''
- description: Manage Outlook personal contacts and contact folders for Exchange Online users. Supports creating, reading, updating, and deleting contacts, organizing them into folders, and assigning categories.
  name: Microsoft Graph Contacts API
  slug: ''
- description: Retrieve people most relevant to a user based on communication and collaboration patterns, business relationships, and contacts. Useful for people-picking scenarios and social intelligence features.
  name: Microsoft Graph People API
  slug: ''
- description: Legacy SOAP-based API for Exchange Server providing comprehensive access to mailbox data and operations. Planned for deprecation in Exchange Online in October 2026, with Microsoft Graph recommended fo
  name: Exchange Web Services (EWS)
  slug: ''
- description: PowerShell module for managing Exchange Online through REST-based cmdlets. Provides the complete Exchange management surface for administrative tasks including mailbox management, mail flow rules, and
  name: Exchange Online PowerShell API
  slug: ''
- description: Service that enables client applications to automatically configure themselves for Exchange connectivity using minimal user input. Supports SOAP and POX protocols for discovering EWS endpoint URLs and
  name: Exchange Autodiscover API
  slug: ''
- description: REST-based administrative API that provides cmdlet-style endpoints for Exchange Online management tasks previously available through EWS. Supports organization configuration, mailbox folder permission
  name: Exchange Online Admin API
  slug: ''
- description: APIs for discovering, importing, and exporting content from Exchange Online mailboxes in full fidelity. Enables mailbox migration scenarios and content copying as a replacement for EWS-based approache
  name: Microsoft Graph Mailbox Import Export API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/en-us/graph
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/exchange/client-developer/exchange-server-development
- title: ''
  type: Getting Started
  url: https://developer.microsoft.com/en-us/graph/quick-start
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/graph/auth/
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/microsoft365dev/tag/exchange/
- title: ''
  type: Status
  url: https://status.office365.com/
- title: ''
  type: Support
  url: https://support.microsoft.com/en-us/office
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: GitHub Organization
  url: https://github.com/OfficeDev
- title: ''
  type: Community
  url: https://techcommunity.microsoft.com/category/exchange
- title: ''
  type: Website
  url: https://www.microsoft.com/en-us/microsoft-365/exchange/email
- title: ''
  type: Login
  url: https://admin.exchange.microsoft.com
- title: ''
  type: Sign Up
  url: https://signup.azure.com/
- title: ''
  type: Change Log
  url: https://developer.microsoft.com/en-us/graph/changelog
- title: ''
  type: SDKs
  url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/microsoft-365/exchange/compare-microsoft-exchange-online-plans
- title: ''
  type: Graph Explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- title: ''
  type: JSON-LD Context
  url: json-ld/microsoft-exchange-context.jsonld
- title: ''
  type: JSON Schema
  url: json-schema/microsoft-exchange-message-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/microsoft-exchange-event-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/microsoft-exchange-contact-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/microsoft-exchange-calendar-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/microsoft-exchange-mail-folder-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/microsoft-exchange-person-schema.json
created: '2024-01-01'
description: A comprehensive API collection for Microsoft Exchange Server and Exchange Online, providing programmatic access to email, calendars, contacts, and other mailbox resources through Microsoft Graph, EWS, PowerShell, Autodiscover, and the Exchange Online Admin API.
features: []
image: https://learn.microsoft.com/en-us/media/logos/logo-ms-social.png
integrations: []
jsonld:
- class_count: 0
  name: Microsoft Exchange Context
  property_count: 13
  slug: microsoft-exchange-context
layout: provider
modified: '2026-04-28'
name: Microsoft Exchange
skills: []
slug: microsoft-exchange
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-exchange\nname: Microsoft Exchange\ndescription: A comprehensive API collection for Microsoft Exchange Server and Exchange Online, providing programmatic access to email, calendars, contacts, and other mailbox resources through Microsoft Graph, EWS, PowerShell, Autodiscover, and the Exchange Online Admin API.\ntype: Index\nimage: https://learn.microsoft.com/en-us/media/logos/logo-ms-social.png\ntags:\n  - Calendar\n  - Collaboration\n  - Contacts\n  - Email\n  - Enterprise\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - name: Microsoft Graph Mail API\n    description: Access Exchange Online mailboxes through the Microsoft Graph API, providing modern REST endpoints for reading, sending, and managing email messages, drafts, attachments, and mail folders.\n    image: https://learn.microsoft.com/en-us/media/logos/logo-ms-social.png\n\
  \    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Email\n      - Mail\n      - Messaging\n      - Microsoft Graph\n      - REST\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview\n      - type: OpenAPI\n        url: openapi/microsoft-exchange-graph-mail-openapi.yml\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: Getting Started\n        url: https://developer.microsoft.com/en-us/graph/quick-start\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: Change Log\n        url: https://developer.microsoft.com/en-us/graph/changelog\n    contact:\n      - FN: Microsoft\
  \ Support\n        email: support@microsoft.com\n        url: https://support.microsoft.com\n  - name: Microsoft Graph Calendar API\n    description: Manage calendar events, meetings, and scheduling for Exchange Online users. Provides endpoints for creating, updating, and deleting events, managing attendees, and handling recurring meetings.\n    image: https://learn.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/calendar\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Calendar\n      - Events\n      - Meetings\n      - Microsoft Graph\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/calendar\n      - type: OpenAPI\n        url: openapi/microsoft-exchange-graph-calendar-openapi.yml\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n\
  \      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: Getting Started\n        url: https://developer.microsoft.com/en-us/graph/quick-start\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: Change Log\n        url: https://developer.microsoft.com/en-us/graph/changelog\n  - name: Microsoft Graph Contacts API\n    description: Manage Outlook personal contacts and contact folders for Exchange Online users. Supports creating, reading, updating, and deleting contacts, organizing them into folders, and assigning categories.\n    image: https://learn.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/graph/outlook-contacts-concept-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Address Book\n      - Contacts\n      - Microsoft Graph\n      - Outlook\n      - People\n    properties:\n      - type: Documentation\n\
  \        url: https://learn.microsoft.com/en-us/graph/outlook-contacts-concept-overview\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/contact?view=graph-rest-1.0\n      - type: OpenAPI\n        url: openapi/microsoft-exchange-graph-contacts-openapi.yml\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - name: Microsoft Graph People API\n    description: Retrieve people most relevant to a user based on communication and collaboration patterns, business relationships, and contacts. Useful for people-picking scenarios and social intelligence features.\n    image: https://learn.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/graph/people-insights-overview\n\
  \    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Collaboration\n      - Contacts\n      - Microsoft Graph\n      - People\n      - Social Intelligence\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/people-insights-overview\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/graph/api/user-list-people?view=graph-rest-1.0\n      - type: OpenAPI\n        url: openapi/microsoft-exchange-graph-people-openapi.yml\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - name: Exchange Web Services (EWS)\n    description: Legacy SOAP-based API for Exchange Server providing comprehensive access to mailbox data and operations. Planned for deprecation\
  \ in Exchange Online in October 2026, with Microsoft Graph recommended for new development.\n    image: https://learn.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange\n    baseURL: https://outlook.office365.com/EWS/Exchange.asmx\n    tags:\n      - Exchange Server\n      - Legacy\n      - Mailbox\n      - SOAP\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/exchange/client-developer/web-service-reference/web-services-reference-for-exchange\n      - type: WSDL\n        url: https://outlook.office365.com/EWS/Exchange.asmx?wsdl\n      - type: SDK\n        url: https://github.com/officedev/ews-managed-api\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/exchange/client-developer/exchange-web-services/explore-the-ews-managed-api-ews-and-web-services-in-exchange\n\
  \      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/exchange/client-developer/exchange-server-development\n  - name: Exchange Online PowerShell API\n    description: PowerShell module for managing Exchange Online through REST-based cmdlets. Provides the complete Exchange management surface for administrative tasks including mailbox management, mail flow rules, and organization configuration.\n    image: https://learn.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/powershell/exchange/exchange-online-powershell\n    baseURL: https://outlook.office365.com/powershell-liveid/\n    tags:\n      - Administration\n      - Automation\n      - Exchange Online\n      - Management\n      - PowerShell\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/powershell/exchange/exchange-online-powershell-v2\n      - type: Installation Guide\n        url: https://learn.microsoft.com/en-us/powershell/exchange/exchange-online-powershell-v2#install-and-maintain-the-exchange-online-powershell-module\n\
  \      - type: Authentication\n        url: https://learn.microsoft.com/en-us/powershell/exchange/connect-to-exchange-online-powershell\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/powershell/exchange/exchange-online-powershell\n  - name: Exchange Autodiscover API\n    description: Service that enables client applications to automatically configure themselves for Exchange connectivity using minimal user input. Supports SOAP and POX protocols for discovering EWS endpoint URLs and other Exchange service settings.\n    image: https://learn.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/exchange/client-developer/exchange-web-services/autodiscover-for-exchange\n    baseURL: https://outlook.office365.com/autodiscover/autodiscover.svc\n    tags:\n      - Autodiscover\n      - Configuration\n      - Exchange Server\n      - Service Discovery\n      - SOAP\n    properties:\n      - type: Documentation\n        url:\
  \ https://learn.microsoft.com/en-us/exchange/client-developer/exchange-web-services/autodiscover-for-exchange\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/exchange/client-developer/web-service-reference/soap-autodiscover-web-service-reference-for-exchange\n      - type: SDK\n        url: https://github.com/officedev/ews-managed-api\n  - name: Exchange Online Admin API\n    description: REST-based administrative API that provides cmdlet-style endpoints for Exchange Online management tasks previously available through EWS. Supports organization configuration, mailbox folder permissions, distribution group membership, and delegation management.\n    image: https://learn.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/exchange/reference/admin-api-overview\n    baseURL: https://outlook.office365.com/adminapi/v2.0\n    tags:\n      - Administration\n      - Exchange Online\n      - Management\n      - Permissions\n\
  \      - REST\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/exchange/reference/admin-api-overview\n      - type: OpenAPI\n        url: openapi/microsoft-exchange-admin-api-openapi.yml\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/exchange/reference/admin-api-get-started\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/exchange/reference/admin-api-authentication\n  - name: Microsoft Graph Mailbox Import Export API\n    description: APIs for discovering, importing, and exporting content from Exchange Online mailboxes in full fidelity. Enables mailbox migration scenarios and content copying as a replacement for EWS-based approaches.\n    image: https://learn.microsoft.com/en-us/media/logos/logo-ms-social.png\n    humanURL: https://learn.microsoft.com/en-us/graph/mailbox-import-export-concept-overview\n    baseURL: https://graph.microsoft.com/beta\n    tags:\n      - Export\n     \
  \ - Import\n      - Mailbox\n      - Microsoft Graph\n      - Migration\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/mailbox-import-export-concept-overview\n      - type: OpenAPI\n        url: openapi/microsoft-exchange-graph-import-export-openapi.yml\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/mailbox-import-export-api-overview?view=graph-rest-beta\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/en-us/graph\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/exchange/client-developer/exchange-server-development\n  - type: Getting Started\n    url: https://developer.microsoft.com/en-us/graph/quick-start\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/graph/auth/\n\
  \  - type: Blog\n    url: https://devblogs.microsoft.com/microsoft365dev/tag/exchange/\n  - type: Status\n    url: https://status.office365.com/\n  - type: Support\n    url: https://support.microsoft.com/en-us/office\n  - type: Terms of Service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: GitHub Organization\n    url: https://github.com/OfficeDev\n  - type: Community\n    url: https://techcommunity.microsoft.com/category/exchange\n  - type: Website\n    url: https://www.microsoft.com/en-us/microsoft-365/exchange/email\n  - type: Login\n    url: https://admin.exchange.microsoft.com\n  - type: Sign Up\n    url: https://signup.azure.com/\n  - type: Change Log\n    url: https://developer.microsoft.com/en-us/graph/changelog\n  - type: SDKs\n    url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - type: Pricing\n    url: https://www.microsoft.com/en-us/microsoft-365/exchange/compare-microsoft-exchange-online-plans\n\
  \  - type: Graph Explorer\n    url: https://developer.microsoft.com/en-us/graph/graph-explorer\n  - type: JSON-LD Context\n    url: json-ld/microsoft-exchange-context.jsonld\n  - type: JSON Schema\n    url: json-schema/microsoft-exchange-message-schema.json\n  - type: JSON Schema\n    url: json-schema/microsoft-exchange-event-schema.json\n  - type: JSON Schema\n    url: json-schema/microsoft-exchange-contact-schema.json\n  - type: JSON Schema\n    url: json-schema/microsoft-exchange-calendar-schema.json\n  - type: JSON Schema\n    url: json-schema/microsoft-exchange-mail-folder-schema.json\n  - type: JSON Schema\n    url: json-schema/microsoft-exchange-person-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/apis.yml
tags:
- Calendar
- Collaboration
- Contacts
- Email
- Enterprise
url: https://raw.githubusercontent.com/api-evangelist/microsoft-exchange/refs/heads/main/apis.yml
use_cases: []
---
