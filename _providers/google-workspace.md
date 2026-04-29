---
api_count: 27
apis:
- description: Send and read email, manage drafts and labels, and handle mailbox settings.
  name: Gmail API
  slug: gmail
- description: Store and synchronize files across devices, manage file metadata and permissions.
  name: Google Drive API
  slug: drive
- description: Create and manage calendars, events, and attendees.
  name: Google Calendar API
  slug: calendar
- description: Create and manage video conferencing meetings, spaces, recordings, and transcripts.
  name: Google Meet REST API
  slug: meet
- description: Create and edit documents programmatically.
  name: Google Docs API
  slug: docs
- description: Read and write data in Google Sheets.
  name: Google Sheets API
  slug: sheets
- description: Create and modify presentations.
  name: Google Slides API
  slug: slides
- description: Manage users, groups, organizational units, and devices in a Google Workspace domain.
  name: Admin SDK Directory API
  slug: admin-directory
- description: Build bots and integrations for Google Chat.
  name: Google Chat API
  slug: chat
- description: View audit and usage reports for a Google Workspace domain including user activity and admin actions.
  name: Admin SDK Reports API
  slug: admin-reports
- description: Create and modify forms and quizzes, retrieve form responses and quiz grades.
  name: Google Forms API
  slug: forms
- description: Search, read, and update Google Tasks content and metadata.
  name: Google Tasks API
  slug: tasks
- description: Manage Google Keep notes including creating, listing, and deleting notes and managing permissions.
  name: Google Keep API
  slug: keep
- description: Manage eDiscovery for your organization including matters, holds, and exports across Google Workspace services.
  name: Google Vault API
  slug: vault
- description: Manage classes, rosters, invitations, and coursework in Google Classroom.
  name: Google Classroom API
  slug: classroom
- description: Read and manage the authenticated user contacts and profiles, and search the directory.
  name: People API
  slug: people
- description: Index non-Google Workspace data and search across all organizational data sources.
  name: Google Cloud Search API
  slug: cloud-search
- description: Retrieve information about changes made to objects within a user Google Drive.
  name: Drive Activity API
  slug: drive-activity
- description: Create and manage labels to organize and classify files in Google Drive.
  name: Drive Labels API
  slug: drive-labels
- description: Manage alerts on issues affecting your Google Workspace domain including security and compliance warnings.
  name: Alert Center API
  slug: alert-center
- description: Update and retrieve settings for existing Google Groups including permissions and access controls.
  name: Groups Settings API
  slug: groups-settings
- description: Migrate shared emails from public folders and distribution lists to Google Groups discussion archives.
  name: Groups Migration API
  slug: groups-migration
- description: Transfer ownership of user data from one user to another within a domain.
  name: Admin SDK Data Transfer API
  slug: data-transfer
- description: Manage Google Workspace and related product licenses for all users of a customer.
  name: Enterprise License Manager API
  slug: license-manager
- description: Perform common reseller functions at scale including placing orders and managing customer subscriptions.
  name: Google Workspace Reseller API
  slug: reseller
- description: Gather statistics on bulk emails sent to Gmail users including spam reports and delivery errors.
  name: Gmail Postmaster Tools API
  slug: postmaster
- description: Manage customer and user license status for Google Workspace Marketplace applications.
  name: Google Workspace Marketplace API
  slug: marketplace
capabilities:
- description: Unified workflow for managing Google Workspace domain resources including users, groups, and organizational units. Used by IT administrators and workspace domain managers.
  name: Google Workspace Domain Administration
  slug: domain-administration
common:
- title: ''
  type: Console
  url: https://console.cloud.google.com
- title: ''
  type: Authentication
  url: https://developers.google.com/identity/protocols/oauth2
- title: ''
  type: TermsOfService
  url: https://workspace.google.com/terms/service-terms/
- title: ''
  type: Support
  url: https://support.google.com/workspace
- title: ''
  type: StatusPage
  url: https://www.google.com/appsstatus/dashboard/
- title: ''
  type: DeveloperPortal
  url: https://developers.google.com/workspace
- title: ''
  type: Pricing
  url: https://workspace.google.com/pricing
- title: ''
  type: Blog
  url: https://workspaceupdates.googleblog.com
- title: ''
  type: ReleaseNotes
  url: https://developers.google.com/workspace/release-notes
- title: ''
  type: GettingStarted
  url: https://developers.google.com/workspace/guides/get-started
- title: ''
  type: SDK
  url: https://developers.google.com/workspace/guides/libraries
- title: Admin SDK Directory API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/admin-directory.yaml
- title: Domain Administration Workflow
  type: NaftikoCapability
  url: capabilities/domain-administration.yaml
created: '2024-01-01'
description: A collection of productivity and collaboration tools from Google including Gmail, Drive, Calendar, Meet, and more.
features:
- description: Send, receive, and manage email with Gmail API, build chat bots with Chat API, and host video meetings with Meet API.
  name: Email and Communication
- description: Create and edit documents, spreadsheets, presentations, and forms programmatically across Google Workspace apps.
  name: Document Collaboration
- description: Store, sync, and manage files with Drive API including permissions, metadata, labels, and activity tracking.
  name: File Storage and Management
- description: Manage users, groups, organizational units, and devices across a Google Workspace domain with Admin SDK.
  name: Directory and User Management
- description: Create and manage calendars, events, and attendees with automatic conflict detection and resource booking.
  name: Calendar and Scheduling
- description: Monitor security alerts, manage eDiscovery holds, and generate audit reports for compliance requirements.
  name: Security and Compliance
- description: Index and search across Google Workspace and external data sources with Cloud Search API.
  name: Enterprise Search
- description: Manage tasks and notes programmatically with Tasks API and Keep API for productivity workflows.
  name: Task and Note Management
image: https://workspace.google.com/static/img/logo.svg
integrations:
- description: Sync contacts, calendar events, and emails between Google Workspace and Salesforce CRM.
  name: Salesforce
- description: Bridge Google Workspace content and notifications with Slack channels for unified collaboration.
  name: Slack
- description: Interoperability support for document sharing and calendar synchronization with Microsoft Office apps.
  name: Microsoft 365
- description: Link Google Drive files, create documents from Jira issues, and sync calendar events with project timelines.
  name: Jira
- description: Connect Google Workspace apps with thousands of services through Zapier automation workflows.
  name: Zapier
- description: Integrate Google Drive attachments, Calendar events, and Gmail notifications with Asana project management.
  name: Asana
jsonld:
- class_count: 0
  name: Admin Sdk Directory Context
  property_count: 0
  slug: admin-sdk-directory-context
- class_count: 0
  name: Google Workspace Context
  property_count: 3
  slug: google-workspace-context
layout: provider
modified: '2026-04-18'
name: Google Workspace
rules:
- name: Google Workspace API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: google-workspace-spectral-rules
skills: []
slug: google-workspace
solutions: []
source_yaml: "aid: google-workspace\nname: Google Workspace\ndescription: >-\n  A collection of productivity and collaboration tools from Google including Gmail,\n  Drive, Calendar, Meet, and more.\nimage: https://workspace.google.com/static/img/logo.svg\nurl: https://raw.githubusercontent.com/api-evangelist/google-workspace/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\ntags:\n  - Calendar\n  - Collaboration\n  - Email\n  - Productivity\n  - Storage\n  - Video Conferencing\napis:\n  - aid: google-workspace:gmail\n    name: Gmail API\n    description: >-\n      Send and read email, manage drafts and labels, and handle mailbox settings.\n    image: https://www.gstatic.com/images/branding/product/2x/gmail_2020q4_48dp.png\n    humanURL: https://developers.google.com/gmail/api\n    baseURL: https://gmail.googleapis.com\n    tags:\n      - Email\n      - Messaging\n    properties:\n      - type: Documentation\n\
  \        url: https://developers.google.com/gmail/api/guides\n      - type: Authentication\n        url: https://developers.google.com/gmail/api/auth/about-auth\n      - type: Pricing\n        url: https://workspace.google.com/pricing\n      - type: APIReference\n        url: https://developers.google.com/workspace/gmail/api/reference/rest\n      - type: Quickstart\n        url: https://developers.google.com/gmail/api/quickstart/python\n  - aid: google-workspace:drive\n    name: Google Drive API\n    description: >-\n      Store and synchronize files across devices, manage file metadata and permissions.\n    image: https://www.gstatic.com/images/branding/product/2x/drive_2020q4_48dp.png\n    humanURL: https://developers.google.com/drive/api\n    baseURL: https://www.googleapis.com/drive/v3\n    tags:\n      - Cloud\n      - Files\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/drive/api/guides/about-sdk\n      - type: Quickstart\n\
  \        url: https://developers.google.com/drive/api/quickstart/python\n      - type: Authentication\n        url: https://developers.google.com/drive/api/guides/about-auth\n      - type: APIReference\n        url: https://developers.google.com/workspace/drive/api/reference/rest/v3\n  - aid: google-workspace:calendar\n    name: Google Calendar API\n    description: >-\n      Create and manage calendars, events, and attendees.\n    image: https://www.gstatic.com/images/branding/product/2x/calendar_2020q4_48dp.png\n    humanURL: https://developers.google.com/calendar/api\n    baseURL: https://www.googleapis.com/calendar/v3\n    tags:\n      - Calendar\n      - Events\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/calendar/api/guides/overview\n      - type: CodeExamples\n        url: https://developers.google.com/calendar/api/samples\n      - type: APIReference\n        url: https://developers.google.com/workspace/calendar/api/reference/rest\n\
  \      - type: Authentication\n        url: https://developers.google.com/calendar/api/auth\n  - aid: google-workspace:meet\n    name: Google Meet REST API\n    description: >-\n      Create and manage video conferencing meetings, spaces, recordings, and transcripts.\n    image: https://www.gstatic.com/images/branding/product/2x/meet_2020q4_48dp.png\n    humanURL: https://developers.google.com/meet\n    baseURL: https://meet.googleapis.com\n    tags:\n      - Conferencing\n      - Meetings\n      - Video\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/meet/api/guides/overview\n      - type: APIReference\n        url: https://developers.google.com/workspace/meet/api/reference/rest/v2\n  - aid: google-workspace:docs\n    name: Google Docs API\n    description: >-\n      Create and edit documents programmatically.\n    image: https://www.gstatic.com/images/branding/product/2x/docs_2020q4_48dp.png\n    humanURL: https://developers.google.com/docs/api\n\
  \    baseURL: https://docs.googleapis.com\n    tags:\n      - Collaboration\n      - Documents\n      - Word Processing\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/docs/api/how-tos/overview\n      - type: Quickstart\n        url: https://developers.google.com/docs/api/quickstart/python\n      - type: APIReference\n        url: https://developers.google.com/workspace/docs/api/reference/rest\n  - aid: google-workspace:sheets\n    name: Google Sheets API\n    description: >-\n      Read and write data in Google Sheets.\n    image: https://www.gstatic.com/images/branding/product/2x/sheets_2020q4_48dp.png\n    humanURL: https://developers.google.com/sheets/api\n    baseURL: https://sheets.googleapis.com\n    tags:\n      - Analytics\n      - Data\n      - Spreadsheets\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/sheets/api/guides/concepts\n      - type: CodeExamples\n        url: https://developers.google.com/sheets/api/samples\n\
  \      - type: Quickstart\n        url: https://developers.google.com/sheets/api/quickstart/python\n      - type: APIReference\n        url: https://developers.google.com/workspace/sheets/api/reference/rest\n  - aid: google-workspace:slides\n    name: Google Slides API\n    description: >-\n      Create and modify presentations.\n    image: https://www.gstatic.com/images/branding/product/2x/slides_2020q4_48dp.png\n    humanURL: https://developers.google.com/slides/api\n    baseURL: https://slides.googleapis.com\n    tags:\n      - Presentations\n      - Slides\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/slides/api/guides/concepts\n      - type: APIReference\n        url: https://developers.google.com/workspace/slides/api/reference/rest\n      - type: Quickstart\n        url: https://developers.google.com/slides/api/quickstart/python\n  - aid: google-workspace:admin-directory\n    name: Admin SDK Directory API\n    description: >-\n      Manage\
  \ users, groups, organizational units, and devices in a Google Workspace\n      domain.\n    humanURL: https://developers.google.com/admin-sdk/directory\n    baseURL: https://admin.googleapis.com\n    tags:\n      - Admin\n      - Groups\n      - Management\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/admin-sdk/directory/reference/rest\n      - type: OpenAPI\n        url: openapi/admin-sdk-directory-api.yml\n      - type: JSONSchema\n        url: json-schema/google-workspace-user-schema.json\n      - type: JSONLD\n        url: json-ld/google-workspace-context.jsonld\n      - type: APIReference\n        url: https://developers.google.com/workspace/admin/directory/reference/rest\n      - type: Quickstart\n        url: https://developers.google.com/admin-sdk/directory/v1/quickstart/python\n  - aid: google-workspace:chat\n    name: Google Chat API\n    description: >-\n      Build bots and integrations for Google Chat.\n    image:\
  \ https://www.gstatic.com/images/branding/product/2x/chat_2020q4_48dp.png\n    humanURL: https://developers.google.com/chat\n    baseURL: https://chat.googleapis.com\n    tags:\n      - Chat\n      - Collaboration\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/chat/api/guides/overview\n      - type: APIReference\n        url: https://developers.google.com/chat/api/reference/rest\n  - aid: google-workspace:admin-reports\n    name: Admin SDK Reports API\n    description: >-\n      View audit and usage reports for a Google Workspace domain including user activity\n      and admin actions.\n    humanURL: https://developers.google.com/admin-sdk/reports\n    baseURL: https://admin.googleapis.com\n    tags:\n      - Admin\n      - Audit\n      - Reports\n      - Usage\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/admin/reports/v1/get-start/overview\n      - type: APIReference\n\
  \        url: https://developers.google.com/workspace/admin/reports/reference/rest\n      - type: Authentication\n        url: https://developers.google.com/admin-sdk/reports/auth\n  - aid: google-workspace:forms\n    name: Google Forms API\n    description: >-\n      Create and modify forms and quizzes, retrieve form responses and quiz grades.\n    humanURL: https://developers.google.com/workspace/forms/api\n    baseURL: https://forms.googleapis.com\n    tags:\n      - Forms\n      - Quizzes\n      - Surveys\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/forms/api/guides\n      - type: APIReference\n        url: https://developers.google.com/workspace/forms/api/reference/rest\n      - type: Quickstart\n        url: https://developers.google.com/workspace/forms/api/quickstart/python\n  - aid: google-workspace:tasks\n    name: Google Tasks API\n    description: >-\n      Search, read, and update Google Tasks content and metadata.\n  \
  \  humanURL: https://developers.google.com/tasks\n    baseURL: https://tasks.googleapis.com\n    tags:\n      - Productivity\n      - Tasks\n      - To-Do\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/tasks/overview\n      - type: APIReference\n        url: https://developers.google.com/workspace/tasks/reference/rest\n      - type: Quickstart\n        url: https://developers.google.com/tasks/quickstart/js\n  - aid: google-workspace:keep\n    name: Google Keep API\n    description: >-\n      Manage Google Keep notes including creating, listing, and deleting notes and\n      managing permissions.\n    humanURL: https://developers.google.com/workspace/keep\n    baseURL: https://keep.googleapis.com\n    tags:\n      - Notes\n      - Productivity\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/keep/api/guides\n      - type: APIReference\n        url: https://developers.google.com/workspace/keep/api/reference/rest\n\
  \  - aid: google-workspace:vault\n    name: Google Vault API\n    description: >-\n      Manage eDiscovery for your organization including matters, holds, and exports\n      across Google Workspace services.\n    humanURL: https://developers.google.com/workspace/vault\n    baseURL: https://vault.googleapis.com\n    tags:\n      - Compliance\n      - Ediscovery\n      - Legal\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/vault/guides\n      - type: APIReference\n        url: https://developers.google.com/workspace/vault/reference/rest\n  - aid: google-workspace:classroom\n    name: Google Classroom API\n    description: >-\n      Manage classes, rosters, invitations, and coursework in Google Classroom.\n    humanURL: https://developers.google.com/workspace/classroom\n    baseURL: https://classroom.googleapis.com\n    tags:\n      - Classroom\n      - Education\n      - Learning\n    properties:\n      - type: Documentation\n        url:\
  \ https://developers.google.com/workspace/classroom/guides/get-started\n      - type: APIReference\n        url: https://developers.google.com/workspace/classroom/reference/rest\n  - aid: google-workspace:people\n    name: People API\n    description: >-\n      Read and manage the authenticated user contacts and profiles, and search the\n      directory.\n    humanURL: https://developers.google.com/people\n    baseURL: https://people.googleapis.com\n    tags:\n      - Contacts\n      - Directory\n      - People\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/people\n      - type: APIReference\n        url: https://developers.google.com/people/api/rest\n  - aid: google-workspace:cloud-search\n    name: Google Cloud Search API\n    description: >-\n      Index non-Google Workspace data and search across all organizational data sources.\n    humanURL: https://developers.google.com/workspace/cloud-search\n    baseURL: https://cloudsearch.googleapis.com\n\
  \    tags:\n      - Enterprise Search\n      - Indexing\n      - Search\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/cloud-search/docs/guides/project-setup\n      - type: APIReference\n        url: https://developers.google.com/workspace/cloud-search/docs/reference/rest\n  - aid: google-workspace:drive-activity\n    name: Drive Activity API\n    description: >-\n      Retrieve information about changes made to objects within a user Google Drive.\n    humanURL: https://developers.google.com/drive/activity/v2\n    baseURL: https://driveactivity.googleapis.com\n    tags:\n      - Activity\n      - Audit\n      - Drive\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/drive/activity/v2\n      - type: APIReference\n        url: https://developers.google.com/workspace/drive/activity/v2/reference/rest\n  - aid: google-workspace:drive-labels\n    name: Drive Labels API\n    description: >-\n      Create\
  \ and manage labels to organize and classify files in Google Drive.\n    humanURL: https://developers.google.com/workspace/drive/labels/guides/overview\n    baseURL: https://drivelabels.googleapis.com\n    tags:\n      - Drive\n      - Labels\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/drive/labels/guides/overview\n      - type: APIReference\n        url: https://developers.google.com/workspace/drive/labels/reference/rest/v2\n  - aid: google-workspace:alert-center\n    name: Alert Center API\n    description: >-\n      Manage alerts on issues affecting your Google Workspace domain including security\n      and compliance warnings.\n    humanURL: https://developers.google.com/workspace/admin/alertcenter/guides\n    baseURL: https://alertcenter.googleapis.com\n    tags:\n      - Admin\n      - Alerts\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/admin/alertcenter/guides\n\
  \      - type: APIReference\n        url: https://developers.google.com/workspace/admin/alertcenter/reference/rest\n      - type: Authentication\n        url: https://developers.google.com/workspace/admin/alertcenter/guides/auth\n  - aid: google-workspace:groups-settings\n    name: Groups Settings API\n    description: >-\n      Update and retrieve settings for existing Google Groups including permissions\n      and access controls.\n    humanURL: https://developers.google.com/admin-sdk/groups-settings/concepts\n    baseURL: https://www.googleapis.com/groups/v1\n    tags:\n      - Admin\n      - Groups\n      - Settings\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/admin-sdk/groups-settings/concepts\n      - type: APIReference\n        url: https://developers.google.com/admin-sdk/groups-settings/v1/reference\n  - aid: google-workspace:groups-migration\n    name: Groups Migration API\n    description: >-\n      Migrate shared emails from public\
  \ folders and distribution lists to Google Groups\n      discussion archives.\n    humanURL: https://developers.google.com/workspace/admin/groups-migration/v1/guides/overview\n    baseURL: https://groupsmigration.googleapis.com\n    tags:\n      - Admin\n      - Groups\n      - Migration\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/admin/groups-migration/v1/guides/overview\n      - type: Authentication\n        url: https://developers.google.com/workspace/admin/groups-migration/v1/guides/authorizing\n  - aid: google-workspace:data-transfer\n    name: Admin SDK Data Transfer API\n    description: >-\n      Transfer ownership of user data from one user to another within a domain.\n    humanURL: https://developers.google.com/workspace/admin/data-transfer\n    baseURL: https://admin.googleapis.com\n    tags:\n      - Admin\n      - Data Transfer\n      - Migration\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/admin/data-transfer\n\
  \      - type: APIReference\n        url: https://developers.google.com/workspace/admin/data-transfer/reference/rest\n  - aid: google-workspace:license-manager\n    name: Enterprise License Manager API\n    description: >-\n      Manage Google Workspace and related product licenses for all users of a customer.\n    humanURL: https://developers.google.com/admin-sdk/licensing\n    baseURL: https://licensing.googleapis.com\n    tags:\n      - Admin\n      - Licensing\n      - Management\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/admin-sdk/licensing/v1/how-tos/using\n      - type: APIReference\n        url: https://developers.google.com/workspace/admin/licensing/reference/rest\n      - type: Authentication\n        url: https://developers.google.com/admin-sdk/licensing/v1/how-tos/authorizing\n  - aid: google-workspace:reseller\n    name: Google Workspace Reseller API\n    description: >-\n      Perform common reseller functions at scale including\
  \ placing orders and managing\n      customer subscriptions.\n    humanURL: https://developers.google.com/workspace/admin/reseller/v1/how-tos/concepts\n    baseURL: https://reseller.googleapis.com\n    tags:\n      - Admin\n      - Reseller\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/admin/reseller/v1/how-tos/concepts\n      - type: APIReference\n        url: https://developers.google.com/workspace/admin/reseller/reference/rest\n      - type: Authentication\n        url: https://developers.google.com/workspace/admin/reseller/v1/how-tos/authorize\n  - aid: google-workspace:postmaster\n    name: Gmail Postmaster Tools API\n    description: >-\n      Gather statistics on bulk emails sent to Gmail users including spam reports\n      and delivery errors.\n    humanURL: https://developers.google.com/workspace/gmail/postmaster\n    baseURL: https://gmailpostmastertools.googleapis.com\n    tags:\n      - Deliverability\n\
  \      - Email\n      - Postmaster\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/gmail/postmaster\n      - type: APIReference\n        url: https://developers.google.com/workspace/gmail/postmaster/reference/rest\n  - aid: google-workspace:marketplace\n    name: Google Workspace Marketplace API\n    description: >-\n      Manage customer and user license status for Google Workspace Marketplace applications.\n    humanURL: https://developers.google.com/workspace/marketplace/overview\n    baseURL: https://appsmarket.googleapis.com\n    tags:\n      - Apps\n      - Licensing\n      - Marketplace\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/workspace/marketplace/overview\n      - type: APIReference\n        url: https://developers.google.com/workspace/marketplace/reference/rest\n      - type: Authentication\n        url: https://developers.google.com/workspace/marketplace/authorizing\ncommon:\n\
  \  - type: Console\n    url: https://console.cloud.google.com\n  - type: Authentication\n    url: https://developers.google.com/identity/protocols/oauth2\n  - type: TermsOfService\n    url: https://workspace.google.com/terms/service-terms/\n  - type: Support\n    url: https://support.google.com/workspace\n  - type: StatusPage\n    url: https://www.google.com/appsstatus/dashboard/\n  - type: DeveloperPortal\n    url: https://developers.google.com/workspace\n  - type: Pricing\n    url: https://workspace.google.com/pricing\n  - type: Blog\n    url: https://workspaceupdates.googleblog.com\n  - type: ReleaseNotes\n    url: https://developers.google.com/workspace/release-notes\n  - type: GettingStarted\n    url: https://developers.google.com/workspace/guides/get-started\n  - type: SDK\n    url: https://developers.google.com/workspace/guides/libraries\n  - type: NaftikoCapability\n    url: capabilities/shared/admin-directory.yaml\n    title: Admin SDK Directory API Shared Definition\n  - type:\
  \ NaftikoCapability\n    url: capabilities/domain-administration.yaml\n    title: Domain Administration Workflow\n  - type: Features\n    data:\n      - name: Email and Communication\n        description: Send, receive, and manage email with Gmail API, build chat bots with Chat API, and host video meetings with Meet API.\n      - name: Document Collaboration\n        description: Create and edit documents, spreadsheets, presentations, and forms programmatically across Google Workspace apps.\n      - name: File Storage and Management\n        description: Store, sync, and manage files with Drive API including permissions, metadata, labels, and activity tracking.\n      - name: Directory and User Management\n        description: Manage users, groups, organizational units, and devices across a Google Workspace domain with Admin SDK.\n      - name: Calendar and Scheduling\n        description: Create and manage calendars, events, and attendees with automatic conflict detection and resource\
  \ booking.\n      - name: Security and Compliance\n        description: Monitor security alerts, manage eDiscovery holds, and generate audit reports for compliance requirements.\n      - name: Enterprise Search\n        description: Index and search across Google Workspace and external data sources with Cloud Search API.\n      - name: Task and Note Management\n        description: Manage tasks and notes programmatically with Tasks API and Keep API for productivity workflows.\n  - type: UseCases\n    data:\n      - name: Automated Onboarding\n        description: Provision user accounts, assign groups and licenses, and configure organizational units for new employee onboarding.\n      - name: Document Workflow Automation\n        description: Automate document creation, approval workflows, and distribution using Docs, Sheets, and Drive APIs.\n      - name: Meeting Management\n        description: Schedule meetings, manage recordings and transcripts, and integrate video conferencing into\
  \ custom applications.\n      - name: Security Monitoring\n        description: Monitor security alerts, audit user activity, and enforce compliance policies across the Google Workspace domain.\n      - name: Customer Communication\n        description: Automate email campaigns, manage support inboxes, and integrate Gmail with CRM and helpdesk systems.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: Sync contacts, calendar events, and emails between Google Workspace and Salesforce CRM.\n      - name: Slack\n        description: Bridge Google Workspace content and notifications with Slack channels for unified collaboration.\n      - name: Microsoft 365\n        description: Interoperability support for document sharing and calendar synchronization with Microsoft Office apps.\n      - name: Jira\n        description: Link Google Drive files, create documents from Jira issues, and sync calendar events with project timelines.\n      - name: Zapier\n     \
  \   description: Connect Google Workspace apps with thousands of services through Zapier automation workflows.\n      - name: Asana\n        description: Integrate Google Drive attachments, Calendar events, and Gmail notifications with Asana project management.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-workspace/refs/heads/main/apis.yml
tags:
- Calendar
- Collaboration
- Email
- Productivity
- Storage
- Video Conferencing
url: https://raw.githubusercontent.com/api-evangelist/google-workspace/refs/heads/main/apis.yml
use_cases:
- description: Provision user accounts, assign groups and licenses, and configure organizational units for new employee onboarding.
  name: Automated Onboarding
- description: Automate document creation, approval workflows, and distribution using Docs, Sheets, and Drive APIs.
  name: Document Workflow Automation
- description: Schedule meetings, manage recordings and transcripts, and integrate video conferencing into custom applications.
  name: Meeting Management
- description: Monitor security alerts, audit user activity, and enforce compliance policies across the Google Workspace domain.
  name: Security Monitoring
- description: Automate email campaigns, manage support inboxes, and integrate Gmail with CRM and helpdesk systems.
  name: Customer Communication
---
