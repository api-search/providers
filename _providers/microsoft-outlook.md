---
api_count: 10
api_specs:
- filename: microsoft-graph-mail-api-openapi.yml
  format: yaml
  label: Microsoft Graph Mail API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-outlook/refs/heads/main/openapi/microsoft-graph-mail-api-openapi.yml
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph Calendar API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph Contacts API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph Tasks API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph People API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph Change Notifications API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph Focused Inbox API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph Mail Rules API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
- filename: openapi.yaml
  format: yaml
  label: Microsoft Graph Categories API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml
apis:
- description: API for accessing Outlook email messages, folders, and mail settings through Microsoft Graph.
  name: Microsoft Graph Mail API
  slug: ''
- description: API for accessing Outlook calendar events, calendars, and meeting scheduling through Microsoft Graph.
  name: Microsoft Graph Calendar API
  slug: ''
- description: API for accessing Outlook contacts and contact folders through Microsoft Graph.
  name: Microsoft Graph Contacts API
  slug: ''
- description: API for accessing Outlook tasks and to-do items through Microsoft Graph.
  name: Microsoft Graph Tasks API
  slug: ''
- description: JavaScript API for building Outlook add-ins that extend Outlook functionality with custom features, using the Office.js library and the Mailbox requirement set.
  name: Outlook Add-ins API
  slug: ''
- description: API for accessing people data relevant to the user, aggregating information from contacts, social networks, organization directory, and recent communications.
  name: Microsoft Graph People API
  slug: ''
- description: API for subscribing to changes in Outlook resources including mail, calendar events, and contacts via webhooks, enabling real-time notifications.
  name: Microsoft Graph Change Notifications API
  slug: ''
- description: API for managing Focused Inbox overrides and message classification, allowing applications to control how incoming messages are categorized between Focused and Other tabs.
  name: Microsoft Graph Focused Inbox API
  slug: ''
- description: API for managing Outlook inbox rules that automatically process incoming messages based on conditions, enabling actions like moving messages to folders, assigning categories, and forwarding.
  name: Microsoft Graph Mail Rules API
  slug: ''
- description: API for managing Outlook categories, allowing applications to create, read, update, and delete categories in a user's master category list for organizing messages, events, and contacts.
  name: Microsoft Graph Categories API
  slug: ''
asyncapis:
- description: 'AsyncAPI specification for Microsoft Graph change notifications (webhooks) for Outlook mail resources. Enables real-time event-driven architecture by subscribing to changes in messages, mail folders, '
  name: Microsoft Outlook Change Notifications
  slug: microsoft-outlook-change-notifications-asyncapi
capabilities:
- description: Unified capability for Microsoft Outlook email productivity combining mail operations, folder management, and attachment handling via Microsoft Graph. Used by productivity teams, IT administrators, an
  name: Microsoft Outlook Email Productivity
  slug: email-productivity
common:
- title: ''
  type: Portal
  url: https://developer.microsoft.com/en-us/graph
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/graph/overview
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/outlook/
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/graph/auth/
- title: ''
  type: SDK
  url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview
- title: ''
  type: ChangeLog
  url: https://developer.microsoft.com/en-us/graph/changelog
- title: ''
  type: APIReference
  url: https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/microsoft365dev/tag/outlook/
- title: ''
  type: GitHubOrganization
  url: https://github.com/microsoftgraph
- title: ''
  type: SignUp
  url: https://developer.microsoft.com/en-us/microsoft-365/dev-program
- title: ''
  type: Login
  url: https://portal.azure.com
- title: ''
  type: TermsOfService
  url: https://learn.microsoft.com/en-us/legal/microsoft-apis/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: Support
  url: https://developer.microsoft.com/en-us/graph/support
- title: ''
  type: StatusPage
  url: https://status.cloud.microsoft/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/microsoft-graph
- title: ''
  type: Quickstart
  url: https://developer.microsoft.com/en-us/graph/quick-start
- title: ''
  type: Training
  url: https://learn.microsoft.com/en-us/training/paths/m365-msgraph-fundamentals/
created: '2024'
description: Microsoft Outlook is a personal information manager and email client that is part of the Microsoft Office suite. It provides email, calendar, contact management, task management, and other productivity features.
features:
- Email management with full CRUD operations on messages
- Calendar scheduling with meeting invitations and RSVPs
- Contact management across personal and organizational directories
- Task and to-do list management
- Focused Inbox classification and mail rules
- Real-time change notifications via webhooks
- Rich attachment handling with large file support
- Categories for organizing messages, events, and contacts
- People insights aggregated across multiple sources
- Outlook add-in extensibility via Office.js
image: https://www.microsoft.com/en-us/microsoft-365/blog/wp-content/uploads/sites/2/2019/11/Outlook-logo.png
integrations:
- Microsoft Teams
- Microsoft Power Automate
- Microsoft Power Apps
- SharePoint
- OneDrive
- Azure Active Directory
- Microsoft To Do
jsonld:
- class_count: 0
  name: Microsoft Graph Mail Context
  property_count: 0
  slug: microsoft-graph-mail-context
- class_count: 0
  name: Microsoft Outlook Context
  property_count: 13
  slug: microsoft-outlook-context
layout: provider
modified: '2026-04-18'
name: Microsoft Outlook
rules:
- name: Microsoft Outlook API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: microsoft-outlook-spectral-rules
skills: []
slug: microsoft-outlook
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-outlook\nname: Microsoft Outlook\ndescription: Microsoft Outlook is a personal information manager and email client that is part of the Microsoft Office suite. It provides email, calendar, contact management, task management, and other productivity features.\nimage: https://www.microsoft.com/en-us/microsoft-365/blog/wp-content/uploads/sites/2/2019/11/Outlook-logo.png\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\nurl: https://outlook.office.com\napis:\n  - name: Microsoft Graph Mail API\n    description: >-\n      API for accessing Outlook email messages, folders, and mail settings through\n      Microsoft Graph.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Email\n      - Folders\n      - Mail\n      - Messages\n    properties:\n \
  \     - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/mail-api-overview?view=graph-rest-1.0\n      - type: OpenAPI\n        url: openapi/microsoft-graph-mail-api-openapi.yml\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: JSONSchema\n        url: json-schema/microsoft-outlook-message-schema.json\n      - type: JSONLD\n        url: json-ld/microsoft-outlook-context.jsonld\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/outlook-mail-concept-overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: ChangeLog\n        url: https://developer.microsoft.com/en-us/graph/changelog\n\
  \  - name: Microsoft Graph Calendar API\n    description: >-\n      API for accessing Outlook calendar events, calendars, and meeting scheduling\n      through Microsoft Graph.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/calendar?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Calendar\n      - Events\n      - Meetings\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/calendar?view=graph-rest-1.0\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: CodeExamples\n        url: https://learn.microsoft.com/en-us/graph/api/resources/calendar?view=graph-rest-1.0#code-samples\n      - type:\
  \ GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/outlook-calendar-concept-overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/calendar-overview?view=graph-rest-1.0\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: ChangeLog\n        url: https://developer.microsoft.com/en-us/graph/changelog\n  - name: Microsoft Graph Contacts API\n    description: >-\n      API for accessing Outlook contacts and contact folders through Microsoft Graph.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/contact?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Address Book\n      - Contacts\n      - People\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/contact?view=graph-rest-1.0\n\
  \      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/outlook-contacts-concept-overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: ChangeLog\n        url: https://developer.microsoft.com/en-us/graph/changelog\n  - name: Microsoft Graph Tasks API\n    description: >-\n      API for accessing Outlook tasks and to-do items through Microsoft Graph.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/todo-overview?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0\n\
  \    tags:\n      - Task Management\n      - Tasks\n      - To-Do\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/todo-overview?view=graph-rest-1.0\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/todo-concept-overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: ChangeLog\n        url: https://developer.microsoft.com/en-us/graph/changelog\n  - name: Outlook Add-ins API\n    description: >-\n      JavaScript API for building Outlook add-ins that extend Outlook functionality\n      with custom\
  \ features, using the Office.js library and the Mailbox requirement\n      set.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/\n    baseURL: https://appsforoffice.microsoft.com/lib/1/hosted/office.js\n    tags:\n      - Add-Ins\n      - Extensions\n      - Office.js\n      - Plugins\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/quickstarts/outlook-quickstart-yo\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/reference/javascript-api-for-office\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/microsoft-graph\n      - type: GitHubOrganization\n        url: https://github.com/OfficeDev/office-js\n  - name: Microsoft\
  \ Graph People API\n    description: >-\n      API for accessing people data relevant to the user, aggregating information\n      from contacts, social networks, organization directory, and recent communications.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://learn.microsoft.com/en-us/graph/people-insights-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Contacts\n      - Directory\n      - People\n      - Social\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/people-insights-overview\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: ChangeLog\n        url: https://developer.microsoft.com/en-us/graph/changelog\n\
  \  - name: Microsoft Graph Change Notifications API\n    description: >-\n      API for subscribing to changes in Outlook resources including mail, calendar\n      events, and contacts via webhooks, enabling real-time notifications.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://learn.microsoft.com/en-us/graph/outlook-change-notifications-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Events\n      - Notifications\n      - Subscriptions\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/outlook-change-notifications-overview\n      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/change-notifications-delivery-webhooks\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/change-notifications-api-overview?view=graph-rest-1.0\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n\
  \      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: ChangeLog\n        url: https://developer.microsoft.com/en-us/graph/changelog\n  - name: Microsoft Graph Focused Inbox API\n    description: >-\n      API for managing Focused Inbox overrides and message classification, allowing\n      applications to control how incoming messages are categorized between Focused\n      and Other tabs.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/manage-focused-inbox?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Classification\n      - Email Organization\n      - Focused Inbox\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/manage-focused-inbox?view=graph-rest-1.0\n\
  \      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - name: Microsoft Graph Mail Rules API\n    description: >-\n      API for managing Outlook inbox rules that automatically process incoming messages\n      based on conditions, enabling actions like moving messages to folders, assigning\n      categories, and forwarding.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/messagerule?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Email Automation\n      - Filters\n      - Inbox Rules\n      - Rules\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/messagerule?view=graph-rest-1.0\n\
  \      - type: GettingStarted\n        url: https://learn.microsoft.com/en-us/graph/outlook-organize-messages\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - name: Microsoft Graph Categories API\n    description: >-\n      API for managing Outlook categories, allowing applications to create, read,\n      update, and delete categories in a user's master category list for organizing\n      messages, events, and contacts.\n    image: https://docs.microsoft.com/en-us/graph/images/microsoft-graph.png\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/outlookcategory?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Categories\n      - Labels\n      - Organization\n \
  \   properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/outlookcategory?view=graph-rest-1.0\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\ncommon:\n  - type: Portal\n    url: https://developer.microsoft.com/en-us/graph\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/graph/overview\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/outlook/\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/graph/auth/\n  - type: SDK\n    url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n  - type: ChangeLog\n    url: https://developer.microsoft.com/en-us/graph/changelog\n  - type: APIReference\n    url: https://learn.microsoft.com/en-us/graph/api/overview?view=graph-rest-1.0\n\
  \  - type: Blog\n    url: https://devblogs.microsoft.com/microsoft365dev/tag/outlook/\n  - type: GitHubOrganization\n    url: https://github.com/microsoftgraph\n  - type: SignUp\n    url: https://developer.microsoft.com/en-us/microsoft-365/dev-program\n  - type: Login\n    url: https://portal.azure.com\n  - type: TermsOfService\n    url: https://learn.microsoft.com/en-us/legal/microsoft-apis/terms-of-use\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: Support\n    url: https://developer.microsoft.com/en-us/graph/support\n  - type: StatusPage\n    url: https://status.cloud.microsoft/\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/microsoft-graph\n  - type: Quickstart\n    url: https://developer.microsoft.com/en-us/graph/quick-start\n  - type: Training\n    url: https://learn.microsoft.com/en-us/training/paths/m365-msgraph-fundamentals/\n  - type: Features\n    data:\n      - Email management with full CRUD\
  \ operations on messages\n      - Calendar scheduling with meeting invitations and RSVPs\n      - Contact management across personal and organizational directories\n      - Task and to-do list management\n      - Focused Inbox classification and mail rules\n      - Real-time change notifications via webhooks\n      - Rich attachment handling with large file support\n      - Categories for organizing messages, events, and contacts\n      - People insights aggregated across multiple sources\n      - Outlook add-in extensibility via Office.js\n  - type: UseCases\n    data:\n      - Building email client integrations and automation workflows\n      - Scheduling meetings and managing calendars programmatically\n      - Syncing contacts between systems\n      - Creating automated email processing pipelines\n      - Building productivity dashboards with mail and calendar data\n      - Extending Outlook with custom add-ins\n  - type: Integrations\n    data:\n      - Microsoft Teams\n      - Microsoft\
  \ Power Automate\n      - Microsoft Power Apps\n      - SharePoint\n      - OneDrive\n      - Azure Active Directory\n      - Microsoft To Do\nproperties:\n  - type: Capabilities\n    url: capabilities/email-productivity.yaml\n    title: Email Productivity Capability\n  - type: Capabilities\n    url: capabilities/shared/graph-mail.yaml\n    title: Graph Mail API Shared Definition\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Calendar\n  - Contacts\n  - Email\n  - Enterprise\n  - Microsoft\n  - Office 365\n  - Productivity\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-outlook/refs/heads/main/apis.yml
tags:
- Calendar
- Contacts
- Email
- Enterprise
- Microsoft
- Office 365
- Productivity
url: https://outlook.office.com
use_cases:
- Building email client integrations and automation workflows
- Scheduling meetings and managing calendars programmatically
- Syncing contacts between systems
- Creating automated email processing pipelines
- Building productivity dashboards with mail and calendar data
- Extending Outlook with custom add-ins
---
