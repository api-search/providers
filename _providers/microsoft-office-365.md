---
api_count: 17
api_specs:
- filename: microsoft-graph-api-openapi.yml
  format: yaml
  label: Microsoft Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-365/refs/heads/main/openapi/microsoft-graph-api-openapi.yml
- filename: microsoft-graph-api-openapi.yml
  format: yaml
  label: Outlook Mail API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-365/refs/heads/main/openapi/microsoft-graph-api-openapi.yml
- filename: microsoft-graph-api-openapi.yml
  format: yaml
  label: Outlook Calendar API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-365/refs/heads/main/openapi/microsoft-graph-api-openapi.yml
- filename: microsoft-graph-api-openapi.yml
  format: yaml
  label: Office 365 Groups API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-365/refs/heads/main/openapi/microsoft-graph-api-openapi.yml
apis:
- description: Unified API endpoint to access data, intelligence, and insights from Microsoft 365, Windows, and Enterprise Mobility + Security.
  name: Microsoft Graph API
  slug: ''
- description: Access to Outlook email, including reading, sending, and managing messages.
  name: Outlook Mail API
  slug: ''
- description: Access to Outlook calendar events, scheduling, and meeting management.
  name: Outlook Calendar API
  slug: ''
- description: Access to Outlook personal contacts for managing contact information, creating contact folders, and organizing people data.
  name: Outlook Contacts API
  slug: ''
- description: Access to OneDrive file storage, sharing, and collaboration features.
  name: OneDrive API
  slug: ''
- description: Access to SharePoint sites, lists, and document libraries.
  name: SharePoint API
  slug: ''
- description: Access to Microsoft Teams channels, messages, and collaboration features.
  name: Microsoft Teams API
  slug: ''
- description: Manage Office 365 users, profiles, and organizational information.
  name: Office 365 Users API
  slug: ''
- description: Access to Microsoft Planner tasks, plans, and project management features.
  name: Planner API
  slug: ''
- description: Access to OneNote notebooks, sections, and pages for creating and managing notes and structured content.
  name: OneNote API
  slug: ''
- description: Read and modify Excel workbooks stored in OneDrive and SharePoint, including managing worksheets, tables, charts, ranges, and sessions.
  name: Excel Workbooks and Charts API
  slug: ''
- description: Manage tasks and task lists across To Do clients, Outlook, and Teams for personal task management and day planning.
  name: Microsoft To Do API
  slug: ''
- description: Manage customer bookings, appointment scheduling, business services, and staff information for enterprise and small business owners.
  name: Microsoft Bookings API
  slug: ''
- description: Manage Microsoft 365 groups, group membership, conversations, and group-related resources for collaboration.
  name: Office 365 Groups API
  slug: ''
- description: Connect security products, services, and partners to streamline security operations and improve threat protection, detection, and response.
  name: Microsoft Graph Security API
  slug: ''
- description: Create and join online meetings, manage call records, and enable cloud communications capabilities for applications.
  name: Microsoft Graph Communications API
  slug: ''
- description: Platform for building solutions that extend Office applications including Excel, Outlook, Word, PowerPoint, and OneNote using web technologies and the Office JavaScript API.
  name: Office Add-ins Platform
  slug: ''
capabilities:
- description: Unified productivity workflow combining mail, calendar, user management, and group collaboration for enterprise users and IT administrators.
  name: Microsoft Office 365 Productivity and Collaboration
  slug: productivity-and-collaboration
common:
- title: ''
  type: DeveloperPortal
  url: https://developer.microsoft.com/en-us/microsoft-365
- title: ''
  type: StatusPage
  url: https://status.office365.com/
- title: ''
  type: Support
  url: https://developer.microsoft.com/en-us/graph/support
- title: ''
  type: Blog
  url: https://developer.microsoft.com/en-us/graph/blogs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/microsoftgraph
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: Graph Explorer
  type: Console
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- title: ''
  type: SDK
  url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview
- title: ''
  type: ChangeLog
  url: https://developer.microsoft.com/en-us/graph/changelog
- title: What's New
  type: ReleaseNotes
  url: https://learn.microsoft.com/en-us/graph/whats-new-overview
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/graph/auth/
- title: ''
  type: TermsOfService
  url: https://docs.microsoft.com/en-us/legal/microsoft-apis/terms-of-use
- title: ''
  type: RateLimits
  url: https://learn.microsoft.com/en-us/graph/throttling
- title: Webhooks
  type: Documentation
  url: https://learn.microsoft.com/en-us/graph/change-notifications-delivery-webhooks
- title: ''
  type: Quickstart
  url: https://developer.microsoft.com/en-us/graph/quick-start
- title: ''
  type: APIReference
  url: https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0
- title: ''
  type: Compliance
  url: https://learn.microsoft.com/en-us/graph/compliance-concept-overview
- title: ''
  type: SpectralRules
  url: rules/microsoft-office-365-spectral-rules.yml
- title: Microsoft Graph API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/graph-api.yaml
- title: Productivity and Collaboration Workflow
  type: NaftikoCapability
  url: capabilities/productivity-and-collaboration.yaml
created: '2024-01-15'
description: A collection of APIs provided by Microsoft Office 365 for productivity, collaboration, and enterprise services.
features:
- description: Access Microsoft 365 data through a single REST endpoint at graph.microsoft.com covering mail, calendar, files, users, and groups.
  name: Unified API Endpoint
- description: Subscribe to change notifications via webhooks to receive real-time updates when data changes across Microsoft 365 services.
  name: Real-Time Notifications
- description: Combine multiple API requests into a single HTTP call to reduce network overhead and improve performance.
  name: Batch Requests
- description: Track incremental changes to resources efficiently using delta links without polling entire datasets.
  name: Delta Queries
- description: Read, send, reply, forward, and organize email messages with full attachment and folder support.
  name: Rich Mail Management
- description: Create events, manage calendars, check free/busy availability, and handle meeting responses programmatically.
  name: Calendar and Scheduling
- description: Access OneDrive and SharePoint files with upload, download, sharing, and real-time collaboration capabilities.
  name: File Storage and Sharing
- description: Manage Microsoft Teams channels, messages, tabs, and apps for team communication and collaboration.
  name: Team Collaboration
- description: Create, update, and manage users, groups, and organizational directory resources.
  name: User and Group Management
image: https://www.microsoft.com/en-us/microsoft-365/blog/wp-content/uploads/sites/2/2020/04/Microsoft-365.png
integrations:
- description: Integrate with Azure AD for user authentication, authorization, and directory management.
  name: Azure Active Directory
- description: Build bots, tabs, and messaging extensions that integrate with Microsoft Teams collaboration platform.
  name: Microsoft Teams
- description: Connect Microsoft Graph data to Power Automate flows for no-code/low-code automation.
  name: Power Automate
- description: Feed Microsoft 365 data into Power BI dashboards for business intelligence and reporting.
  name: Power BI
- description: Access SharePoint sites, lists, and document libraries for enterprise content management.
  name: SharePoint
- description: Integrate with Outlook mail, calendar, and contacts for personal and shared mailbox management.
  name: Outlook
jsonld:
- class_count: 0
  name: Microsoft Graph Context
  property_count: 0
  slug: microsoft-graph-context
- class_count: 0
  name: Microsoft Office 365 Context
  property_count: 10
  slug: microsoft-office-365-context
layout: provider
modified: '2026-04-18'
name: Microsoft Office 365
rules:
- name: Microsoft Office 365 API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: microsoft-office-365-spectral-rules
skills: []
slug: microsoft-office-365
solutions: []
source_filename: apis.yml
source_yaml: "aid: microsoft-office-365\nname: Microsoft Office 365\ndescription: >-\n  A collection of APIs provided by Microsoft Office 365 for productivity, collaboration,\n  and enterprise services.\nimage: https://www.microsoft.com/en-us/microsoft-365/blog/wp-content/uploads/sites/2/2020/04/Microsoft-365.png\nurl: https://www.microsoft.com/en-us/microsoft-365\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Cloud\n  - Collaboration\n  - Enterprise\n  - Microsoft\n  - Productivity\napis:\n  - name: Microsoft Graph API\n    description: >-\n      Unified API endpoint to access data, intelligence, and insights from Microsoft\n      365, Windows, and Enterprise Mobility + Security.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://developer.microsoft.com/en-us/graph\n    baseURL: https://graph.microsoft.com\n    tags:\n      - Calendar\n      - Graph\n      - Groups\n      - Mail\n      - Unified\n\
  \      - Users\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/openapi.yaml\n      - type: OpenAPI\n        url: openapi/microsoft-graph-api-openapi.yml\n      - type: JSONLD\n        url: json-ld/microsoft-office-365-context.jsonld\n      - type: Pricing\n        url: https://azure.microsoft.com/en-us/pricing/details/active-directory/\n      - type: Authentication\n        url: https://docs.microsoft.com/en-us/graph/auth/\n      - type: Documentation\n        url: https://www.postman.com/microsoftgraph/workspace/microsoft-graph/overview\n        title: Postman Collection\n      - type: TermsOfService\n        url: https://docs.microsoft.com/en-us/legal/microsoft-apis/terms-of-use\n      - type: RateLimits\n        url: https://docs.microsoft.com/en-us/graph/throttling\n      - type: GettingStarted\n\
  \        url: https://learn.microsoft.com/en-us/graph/use-the-api\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/change-notifications-overview\n        title: Change Notifications\n      - type: Versioning\n        url: https://learn.microsoft.com/en-us/graph/versioning-and-support\n      - type: Console\n        url: https://developer.microsoft.com/en-us/graph/graph-explorer\n        title: Graph Explorer\n  - name: Outlook Mail API\n    description: >-\n      Access to Outlook email, including reading, sending, and managing messages.\n    humanURL: https://docs.microsoft.com/en-us/graph/api/resources/mail-api-overview\n    baseURL: https://graph.microsoft.com/v1.0/me/messages\n    tags:\n      - Email\n      - Mail\n      - Messages\n      - Outlook\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/api/resources/message\n\
  \      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/mail.yaml\n      - type: OpenAPI\n        url: openapi/microsoft-graph-api-openapi.yml\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/outlook-change-notifications-overview\n        title: Change Notifications\n  - name: Outlook Calendar API\n    description: >-\n      Access to Outlook calendar events, scheduling, and meeting management.\n    humanURL: https://docs.microsoft.com/en-us/graph/api/resources/calendar\n    baseURL: https://graph.microsoft.com/v1.0/me/calendar\n    tags:\n      - Calendar\n      - Events\n      - Meetings\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/api/resources/event\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/calendar.yaml\n      - type:\
  \ OpenAPI\n        url: openapi/microsoft-graph-api-openapi.yml\n  - name: Outlook Contacts API\n    description: >-\n      Access to Outlook personal contacts for managing contact information, creating\n      contact folders, and organizing people data.\n    humanURL: https://learn.microsoft.com/en-us/graph/outlook-contacts-concept-overview\n    baseURL: https://graph.microsoft.com/v1.0/me/contacts\n    tags:\n      - Address-Book\n      - Contacts\n      - Outlook\n      - People\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/contact?view=graph-rest-1.0\n  - name: OneDrive API\n    description: >-\n      Access to OneDrive file storage, sharing, and collaboration features.\n    humanURL: https://docs.microsoft.com/en-us/graph/api/resources/onedrive\n    baseURL: https://graph.microsoft.com/v1.0/me/drive\n    tags:\n      - Files\n      - Onedrive\n      - Sharing\n      - Storage\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.microsoft.com/en-us/graph/api/resources/driveitem\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/files.yaml\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/onedrive/developer/rest-api/?view=odsp-graph-online\n  - name: SharePoint API\n    description: >-\n      Access to SharePoint sites, lists, and document libraries.\n    humanURL: https://docs.microsoft.com/en-us/graph/api/resources/sharepoint\n    baseURL: https://graph.microsoft.com/v1.0/sites\n    tags:\n      - Collaboration\n      - Lists\n      - Sharepoint\n      - Sites\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/api/resources/site\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/sites.yaml\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/sharepoint/dev/apis/sharepoint-rest-graph\n\
  \        title: SharePoint REST v2\n  - name: Microsoft Teams API\n    description: >-\n      Access to Microsoft Teams channels, messages, and collaboration features.\n    humanURL: https://docs.microsoft.com/en-us/graph/api/resources/teams-api-overview\n    baseURL: https://graph.microsoft.com/v1.0/teams\n    tags:\n      - Channels\n      - Chat\n      - Collaboration\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/api/resources/team\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/teams.yaml\n  - name: Office 365 Users API\n    description: >-\n      Manage Office 365 users, profiles, and organizational information.\n    humanURL: https://docs.microsoft.com/en-us/graph/api/resources/user\n    baseURL: https://graph.microsoft.com/v1.0/users\n    tags:\n      - Directory\n      - Identity\n      - Profiles\n      - Users\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/api/resources/user\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/users.yaml\n      - type: JSONSchema\n        url: json-schema/microsoft-office-365-user-schema.json\n  - name: Planner API\n    description: >-\n      Access to Microsoft Planner tasks, plans, and project management features.\n    humanURL: https://docs.microsoft.com/en-us/graph/api/resources/planner-overview\n    baseURL: https://graph.microsoft.com/v1.0/planner\n    tags:\n      - Planner\n      - Planning\n      - Projects\n      - Tasks\n    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/graph/api/resources/planner-overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/microsoft-graph-openapi/master/openapi/v1.0/planner.yaml\n  - name: OneNote API\n    description: >-\n    \
  \  Access to OneNote notebooks, sections, and pages for creating and managing notes\n      and structured content.\n    humanURL: https://learn.microsoft.com/en-us/graph/integrate-with-onenote\n    baseURL: https://graph.microsoft.com/v1.0/me/onenote\n    tags:\n      - Notebooks\n      - Notes\n      - Onenote\n      - Pages\n      - Sections\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/onenote-api-overview?view=graph-rest-1.0\n  - name: Excel Workbooks and Charts API\n    description: >-\n      Read and modify Excel workbooks stored in OneDrive and SharePoint, including\n      managing worksheets, tables, charts, ranges, and sessions.\n    humanURL: https://learn.microsoft.com/en-us/graph/excel-concept-overview\n    baseURL: https://graph.microsoft.com/v1.0/me/drive/items/{id}/workbook\n    tags:\n      - Charts\n      - Excel\n      - Spreadsheets\n      - Tables\n      - Workbooks\n    properties:\n      - type: Documentation\n\
  \        url: https://learn.microsoft.com/en-us/graph/api/resources/excel?view=graph-rest-1.0\n      - type: BestPractices\n        url: https://learn.microsoft.com/en-us/graph/workbook-best-practice\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/excel-manage-sessions\n        title: Session Management\n  - name: Microsoft To Do API\n    description: >-\n      Manage tasks and task lists across To Do clients, Outlook, and Teams for personal\n      task management and day planning.\n    humanURL: https://learn.microsoft.com/en-us/graph/todo-concept-overview\n    baseURL: https://graph.microsoft.com/v1.0/me/todo\n    tags:\n      - Productivity\n      - Task-Lists\n      - Tasks\n      - Todo\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/todo-concept-overview\n  - name: Microsoft Bookings API\n    description: >-\n      Manage customer bookings, appointment scheduling, business services, and staff\n\
  \      information for enterprise and small business owners.\n    humanURL: https://learn.microsoft.com/en-us/graph/booking-concept-overview\n    baseURL: https://graph.microsoft.com/v1.0/solutions/bookingBusinesses\n    tags:\n      - Appointments\n      - Bookings\n      - Business\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/booking-api-overview?view=graph-rest-1.0\n  - name: Office 365 Groups API\n    description: >-\n      Manage Microsoft 365 groups, group membership, conversations, and group-related\n      resources for collaboration.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/groups-overview?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0/groups\n    tags:\n      - Collaboration\n      - Groups\n      - Membership\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/group?view=graph-rest-1.0\n\
  \      - type: OpenAPI\n        url: openapi/microsoft-graph-api-openapi.yml\n  - name: Microsoft Graph Security API\n    description: >-\n      Connect security products, services, and partners to streamline security operations\n      and improve threat protection, detection, and response.\n    humanURL: https://learn.microsoft.com/en-us/graph/security-concept-overview\n    baseURL: https://graph.microsoft.com/v1.0/security\n    tags:\n      - Alerts\n      - Compliance\n      - Security\n      - Threats\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/security-api-overview?view=graph-rest-1.0\n  - name: Microsoft Graph Communications API\n    description: >-\n      Create and join online meetings, manage call records, and enable cloud communications\n      capabilities for applications.\n    humanURL: https://learn.microsoft.com/en-us/graph/cloud-communications-online-meetings\n    baseURL: https://graph.microsoft.com/v1.0/communications\n\
  \    tags:\n      - Calls\n      - Communications\n      - Meetings\n      - Online-Meetings\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/cloud-communications-online-meetings\n  - name: Office Add-ins Platform\n    description: >-\n      Platform for building solutions that extend Office applications including Excel,\n      Outlook, Word, PowerPoint, and OneNote using web technologies and the Office\n      JavaScript API.\n    humanURL: https://learn.microsoft.com/en-us/office/dev/add-ins/overview/office-add-ins\n    tags:\n      - Add-Ins\n      - Excel\n      - Extensions\n      - Office-Js\n      - Outlook\n      - Powerpoint\n      - Word\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/javascript-api-for-office\n        title: JavaScript API Reference\n      -\
  \ type: GettingStarted\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/overview/learning-path-beginner\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/develop/develop-overview\n        title: Development Guide\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ncommon:\n  - type: DeveloperPortal\n    url: https://developer.microsoft.com/en-us/microsoft-365\n  - type: StatusPage\n    url: https://status.office365.com/\n  - type: Support\n    url: https://developer.microsoft.com/en-us/graph/support\n  - type: Blog\n    url: https://developer.microsoft.com/en-us/graph/blogs/\n  - type: GitHubOrganization\n    url: https://github.com/microsoftgraph\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Console\n    url: https://developer.microsoft.com/en-us/graph/graph-explorer\n    title: Graph Explorer\n  - type: SDK\n    url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n\
  \  - type: ChangeLog\n    url: https://developer.microsoft.com/en-us/graph/changelog\n  - type: ReleaseNotes\n    url: https://learn.microsoft.com/en-us/graph/whats-new-overview\n    title: What's New\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/graph/auth/\n  - type: TermsOfService\n    url: https://docs.microsoft.com/en-us/legal/microsoft-apis/terms-of-use\n  - type: RateLimits\n    url: https://learn.microsoft.com/en-us/graph/throttling\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/graph/change-notifications-delivery-webhooks\n    title: Webhooks\n  - type: Quickstart\n    url: https://developer.microsoft.com/en-us/graph/quick-start\n  - type: APIReference\n    url: https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0\n  - type: Compliance\n    url: https://learn.microsoft.com/en-us/graph/compliance-concept-overview\n  - type: SpectralRules\n    url: rules/microsoft-office-365-spectral-rules.yml\n  - type: NaftikoCapability\n\
  \    url: capabilities/shared/graph-api.yaml\n    title: Microsoft Graph API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/productivity-and-collaboration.yaml\n    title: Productivity and Collaboration Workflow\n  - type: Features\n    url: https://developer.microsoft.com/en-us/graph\n    data:\n      - name: Unified API Endpoint\n        description: Access Microsoft 365 data through a single REST endpoint at graph.microsoft.com covering mail, calendar, files, users, and groups.\n      - name: Real-Time Notifications\n        description: Subscribe to change notifications via webhooks to receive real-time updates when data changes across Microsoft 365 services.\n      - name: Batch Requests\n        description: Combine multiple API requests into a single HTTP call to reduce network overhead and improve performance.\n      - name: Delta Queries\n        description: Track incremental changes to resources efficiently using delta links without polling entire datasets.\n\
  \      - name: Rich Mail Management\n        description: Read, send, reply, forward, and organize email messages with full attachment and folder support.\n      - name: Calendar and Scheduling\n        description: Create events, manage calendars, check free/busy availability, and handle meeting responses programmatically.\n      - name: File Storage and Sharing\n        description: Access OneDrive and SharePoint files with upload, download, sharing, and real-time collaboration capabilities.\n      - name: Team Collaboration\n        description: Manage Microsoft Teams channels, messages, tabs, and apps for team communication and collaboration.\n      - name: User and Group Management\n        description: Create, update, and manage users, groups, and organizational directory resources.\n  - type: UseCases\n    url: https://developer.microsoft.com/en-us/graph\n    data:\n      - name: Enterprise Productivity Integration\n        description: Build applications that integrate email, calendar,\
  \ and file management into unified productivity workflows.\n      - name: Automated Reporting\n        description: Generate automated reports by pulling data from mail, calendar, and user profiles across the organization.\n      - name: Identity and Access Management\n        description: Manage user provisioning, group membership, and directory synchronization for enterprise identity workflows.\n      - name: Team Communication Automation\n        description: Automate team notifications, channel management, and messaging workflows across Microsoft Teams.\n      - name: Document Collaboration\n        description: Enable multi-user document editing, sharing, and version tracking through OneDrive and SharePoint APIs.\n  - type: Integrations\n    url: https://developer.microsoft.com/en-us/graph\n    data:\n      - name: Azure Active Directory\n        description: Integrate with Azure AD for user authentication, authorization, and directory management.\n      - name: Microsoft Teams\n\
  \        description: Build bots, tabs, and messaging extensions that integrate with Microsoft Teams collaboration platform.\n      - name: Power Automate\n        description: Connect Microsoft Graph data to Power Automate flows for no-code/low-code automation.\n      - name: Power BI\n        description: Feed Microsoft 365 data into Power BI dashboards for business intelligence and reporting.\n      - name: SharePoint\n        description: Access SharePoint sites, lists, and document libraries for enterprise content management.\n      - name: Outlook\n        description: Integrate with Outlook mail, calendar, and contacts for personal and shared mailbox management.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-office-365/refs/heads/main/apis.yml
tags:
- Cloud
- Collaboration
- Enterprise
- Microsoft
- Productivity
url: https://www.microsoft.com/en-us/microsoft-365
use_cases:
- description: Build applications that integrate email, calendar, and file management into unified productivity workflows.
  name: Enterprise Productivity Integration
- description: Generate automated reports by pulling data from mail, calendar, and user profiles across the organization.
  name: Automated Reporting
- description: Manage user provisioning, group membership, and directory synchronization for enterprise identity workflows.
  name: Identity and Access Management
- description: Automate team notifications, channel management, and messaging workflows across Microsoft Teams.
  name: Team Communication Automation
- description: Enable multi-user document editing, sharing, and version tracking through OneDrive and SharePoint APIs.
  name: Document Collaboration
---
