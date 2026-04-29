---
api_count: 19
apis:
- description: Enables scheduling, managing, and controlling Webex meetings programmatically. Provides endpoints for creating meetings, managing attendees, preferences, and retrieving meeting details.
  name: Webex Meetings API
  slug: webex-meetings-api
- description: Send and receive messages, manage spaces and teams, and share files within the Webex messaging platform. Supports rich text, file attachments, and adaptive cards.
  name: Webex Messaging API
  slug: webex-messaging-api
- description: Access user profile information, manage contacts, and administer user accounts within an organization. Supports listing, creating, updating, and deleting people records.
  name: Webex People API
  slug: webex-people-api
- description: Create and manage teams and team memberships within Webex. Teams group people and spaces together for organized collaboration across projects and departments.
  name: Webex Teams API
  slug: webex-teams-api
- description: Create and manage Webex spaces (rooms) for collaboration. Rooms are virtual meeting places where people post messages and collaborate, and can be organized within teams.
  name: Webex Rooms API
  slug: webex-rooms-api
- description: Register webhooks to receive real-time HTTP callbacks when specific events occur in Webex. Supports filtering by resource type, event type, and other criteria for efficient event-driven integrations.
  name: Webex Webhooks API
  slug: webex-webhooks-api
- description: Manage and control Webex devices and room systems. Provides endpoints for listing, creating, and managing device configurations, activations, and workspace assignments.
  name: Webex Devices API
  slug: webex-devices-api
- description: Manage room memberships representing a person's relationship to a room. Use this API to list members of any room, create memberships to invite users, and update or remove memberships.
  name: Webex Memberships API
  slug: webex-memberships-api
- description: Manage team memberships representing a person's relationship to a team. Use this API to add and remove people from teams and manage team membership roles.
  name: Webex Team Memberships API
  slug: webex-team-memberships-api
- description: Access events representing activities within a Webex organization such as message posts, file shares, and membership changes. Provides a historical log of activities for compliance and auditing purpos
  name: Webex Events API
  slug: webex-events-api
- description: List and manage meeting recordings. Provides access to recording details, download links, and metadata. Includes separate endpoints for admin and compliance officer access with extended filtering capa
  name: Webex Recordings API
  slug: webex-recordings-api
- description: Control active calls in Webex Calling including dial, answer, hold, transfer, and pickup operations. Supports third-party call control for building custom calling experiences and integrations.
  name: Webex Call Controls API
  slug: webex-call-controls-api
- description: Create and retrieve attachment actions for adaptive card interactions. Used with Buttons and Cards to capture user input from interactive card elements submitted in Webex messaging spaces.
  name: Webex Attachment Actions API
  slug: webex-attachment-actions-api
- description: Retrieve organization details for Webex administration. Provides access to organization-level information and settings, available only to organization administrators.
  name: Webex Organizations API
  slug: webex-organizations-api
- description: Manage and retrieve Webex licenses for an organization. Provides endpoints to list available licenses, view license details, and assign or modify license allocations for users.
  name: Webex Licenses API
  slug: webex-licenses-api
- description: Retrieve roles available within a Webex organization. Roles define the level of access and permissions granted to users, such as full administrator or read-only administrator.
  name: Webex Roles API
  slug: webex-roles-api
- description: Manage workspaces representing physical locations with Webex devices. Provides endpoints to create, list, update, and delete workspaces and manage their associated device configurations.
  name: Webex Workspaces API
  slug: webex-workspaces-api
- description: Access admin audit events for tracking administrative actions performed in Webex Control Hub. Available to full administrators for compliance monitoring and security auditing purposes.
  name: Webex Admin Audit Events API
  slug: webex-admin-audit-events-api
- description: Access converged recording capabilities across Webex Meetings and Webex Calling. Provides unified endpoints for listing, retrieving, and managing recordings from multiple Webex services.
  name: Webex Converged Recordings API
  slug: webex-converged-recordings-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://developer.webex.com
- title: ''
  type: Documentation
  url: https://developer.webex.com/docs/basics
- title: ''
  type: Getting Started
  url: https://developer.webex.com/docs/getting-started
- title: ''
  type: Authentication
  url: https://developer.webex.com/docs/getting-started#authentication
- title: ''
  type: SDKs
  url: https://developer.webex.com/docs/sdks
- title: ''
  type: Change Log
  url: https://developer.webex.com/docs/api/changelog
- title: ''
  type: Blog
  url: https://developer.webex.com/blog
- title: ''
  type: Support
  url: https://developer.webex.com/support
- title: ''
  type: Status
  url: https://status.webex.com
- title: ''
  type: Rate Limits
  url: https://developer.webex.com/docs/api-rate-limits
- title: ''
  type: Community
  url: https://community.cisco.com/t5/webex-developers/bd-p/4416j-disc-dev-webex
- title: ''
  type: Terms of Service
  url: https://developer.webex.com/terms-of-service
- title: ''
  type: Privacy Policy
  url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html
- title: ''
  type: GitHub Organization
  url: https://github.com/webex
- title: ''
  type: Website
  url: https://www.webex.com
- title: ''
  type: Login
  url: https://developer.webex.com/login
- title: ''
  type: Sign Up
  url: https://developer.webex.com/signup
- title: ''
  type: JSON-LD Context
  url: json-ld/cisco-webex-context.jsonld
- title: ''
  type: JSON Schema
  url: json-schema/
- title: ''
  type: Spectral
  url: rules/cisco-webex-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cisco-webex-capabilities.yml
created: '2024-01-01'
description: Cisco Webex is a comprehensive collaboration platform that provides video conferencing, team messaging, file sharing, and calling capabilities for businesses and teams. The Webex developer platform offers REST APIs, SDKs, and integrations for extending and automating collaboration workflows across meetings, messaging, calling, devices, administration, and contact center scenarios. Authentication uses OAuth 2.0 access tokens, personal access tokens, or service apps and all endpoints are served from the webexapis.com base.
features: []
image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Cisco Webex Context
  property_count: 14
  slug: cisco-webex-context
layout: provider
modified: '2026-04-23'
name: Cisco Webex
rules:
- name: Cisco Webex API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 4
  slug: cisco-webex-rules
skills: []
slug: cisco-webex
solutions: []
source_yaml: "aid: cisco-webex\nname: Cisco Webex\ndescription: >-\n  Cisco Webex is a comprehensive collaboration platform that provides video\n  conferencing, team messaging, file sharing, and calling capabilities for\n  businesses and teams. The Webex developer platform offers REST APIs, SDKs,\n  and integrations for extending and automating collaboration workflows\n  across meetings, messaging, calling, devices, administration, and contact\n  center scenarios. Authentication uses OAuth 2.0 access tokens, personal\n  access tokens, or service apps and all endpoints are served from the\n  webexapis.com base.\nimage: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\nurl: https://raw.githubusercontent.com/api-evangelist/cisco-webex/refs/heads/main/apis.yml\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ncreated: '2024-01-01'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\ntags:\n  - Collaboration\n  - Communications\n  - Meetings\n  - Messaging\n  - Teams\n  - Video\
  \ Conferencing\napis:\n  - aid: cisco-webex:webex-meetings-api\n    name: Webex Meetings API\n    description: >-\n      Enables scheduling, managing, and controlling Webex meetings\n      programmatically. Provides endpoints for creating meetings, managing\n      attendees, preferences, and retrieving meeting details.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/meetings\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Attendees\n      - Conferencing\n      - Meetings\n      - Scheduling\n      - Video\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/meetings\n      - type: OpenAPI\n        url: openapi/cisco-webex-meetings-openapi.yml\n      - type: Authentication\n        url: https://developer.webex.com/docs/getting-started#authentication\n  - aid: cisco-webex:webex-messaging-api\n    name: Webex Messaging API\n    description: >-\n      Send and receive\
  \ messages, manage spaces and teams, and share files within\n      the Webex messaging platform. Supports rich text, file attachments, and\n      adaptive cards.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/messaging\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Chat\n      - Collaboration\n      - Messaging\n      - Spaces\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/messaging\n      - type: OpenAPI\n        url: openapi/cisco-webex-messaging-openapi.yml\n      - type: Webhooks\n        url: https://developer.webex.com/docs/webhooks\n      - type: Getting Started\n        url: https://developer.webex.com/messaging/docs/getting-started\n  - aid: cisco-webex:webex-people-api\n    name: Webex People API\n    description: >-\n      Access user profile information, manage contacts, and administer user\n      accounts within an organization.\
  \ Supports listing, creating, updating,\n      and deleting people records.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/people\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Contacts\n      - Directory\n      - People\n      - Profiles\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/people\n      - type: OpenAPI\n        url: openapi/cisco-webex-people-openapi.yml\n  - aid: cisco-webex:webex-teams-api\n    name: Webex Teams API\n    description: >-\n      Create and manage teams and team memberships within Webex. Teams group\n      people and spaces together for organized collaboration across projects\n      and departments.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/teams\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Collaboration\n\
  \      - Groups\n      - Membership\n      - Organization\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/teams\n      - type: OpenAPI\n        url: openapi/cisco-webex-teams-openapi.yml\n  - aid: cisco-webex:webex-rooms-api\n    name: Webex Rooms API\n    description: >-\n      Create and manage Webex spaces (rooms) for collaboration. Rooms are\n      virtual meeting places where people post messages and collaborate, and\n      can be organized within teams.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/rooms\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Channels\n      - Collaboration\n      - Messaging\n      - Rooms\n      - Spaces\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/rooms\n      - type: OpenAPI\n        url: openapi/cisco-webex-rooms-openapi.yml\n  - aid: cisco-webex:webex-webhooks-api\n\
  \    name: Webex Webhooks API\n    description: >-\n      Register webhooks to receive real-time HTTP callbacks when specific events\n      occur in Webex. Supports filtering by resource type, event type, and\n      other criteria for efficient event-driven integrations.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/webhooks\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Callbacks\n      - Events\n      - Notifications\n      - Real-Time\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/webhooks\n      - type: OpenAPI\n        url: openapi/cisco-webex-webhooks-openapi.yml\n  - aid: cisco-webex:webex-devices-api\n    name: Webex Devices API\n    description: >-\n      Manage and control Webex devices and room systems. Provides endpoints\n      for listing, creating, and managing device configurations, activations,\n      and workspace assignments.\n\
  \    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/devices\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Devices\n      - Hardware\n      - Management\n      - Room Systems\n      - Workspaces\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/devices\n      - type: OpenAPI\n        url: openapi/cisco-webex-devices-openapi.yml\n  - aid: cisco-webex:webex-memberships-api\n    name: Webex Memberships API\n    description: >-\n      Manage room memberships representing a person's relationship to a room.\n      Use this API to list members of any room, create memberships to invite\n      users, and update or remove memberships.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/memberships\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Access Control\n      - Memberships\n\
  \      - Permissions\n      - Rooms\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/memberships\n      - type: OpenAPI\n        url: openapi/cisco-webex-memberships-openapi.yml\n  - aid: cisco-webex:webex-team-memberships-api\n    name: Webex Team Memberships API\n    description: >-\n      Manage team memberships representing a person's relationship to a team.\n      Use this API to add and remove people from teams and manage team\n      membership roles.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/team-memberships\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Access Control\n      - Collaboration\n      - Roles\n      - Team Memberships\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/team-memberships\n      - type: OpenAPI\n        url: openapi/cisco-webex-team-memberships-openapi.yml\n\
  \  - aid: cisco-webex:webex-events-api\n    name: Webex Events API\n    description: >-\n      Access events representing activities within a Webex organization such\n      as message posts, file shares, and membership changes. Provides a\n      historical log of activities for compliance and auditing purposes.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/events\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Activity\n      - Auditing\n      - Compliance\n      - Events\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/events\n      - type: OpenAPI\n        url: openapi/cisco-webex-events-openapi.yml\n  - aid: cisco-webex:webex-recordings-api\n    name: Webex Recordings API\n    description: >-\n      List and manage meeting recordings. Provides access to recording details,\n      download links, and metadata. Includes separate\
  \ endpoints for admin and\n      compliance officer access with extended filtering capabilities.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/recordings\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Compliance\n      - Media\n      - Meetings\n      - Recordings\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/recordings\n      - type: OpenAPI\n        url: openapi/cisco-webex-recordings-openapi.yml\n  - aid: cisco-webex:webex-call-controls-api\n    name: Webex Call Controls API\n    description: >-\n      Control active calls in Webex Calling including dial, answer, hold,\n      transfer, and pickup operations. Supports third-party call control for\n      building custom calling experiences and integrations.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/call-controls\n\
  \    baseURL: https://webexapis.com/v1\n    tags:\n      - Call Control\n      - Calling\n      - Communications\n      - Telephony\n      - Voice\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/call-controls\n      - type: OpenAPI\n        url: openapi/cisco-webex-call-controls-openapi.yml\n  - aid: cisco-webex:webex-attachment-actions-api\n    name: Webex Attachment Actions API\n    description: >-\n      Create and retrieve attachment actions for adaptive card interactions.\n      Used with Buttons and Cards to capture user input from interactive card\n      elements submitted in Webex messaging spaces.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/attachment-actions\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Attachment Actions\n      - Buttons\n      - Cards\n      - Interactive\n      - Messaging\n    properties:\n      - type: Documentation\n\
  \        url: https://developer.webex.com/docs/api/v1/attachment-actions\n      - type: OpenAPI\n        url: openapi/cisco-webex-attachment-actions-openapi.yml\n  - aid: cisco-webex:webex-organizations-api\n    name: Webex Organizations API\n    description: >-\n      Retrieve organization details for Webex administration. Provides access\n      to organization-level information and settings, available only to\n      organization administrators.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/organizations\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Administration\n      - Enterprise\n      - Management\n      - Organizations\n      - Settings\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/organizations\n      - type: OpenAPI\n        url: openapi/cisco-webex-organizations-openapi.yml\n  - aid: cisco-webex:webex-licenses-api\n    name: Webex\
  \ Licenses API\n    description: >-\n      Manage and retrieve Webex licenses for an organization. Provides\n      endpoints to list available licenses, view license details, and assign\n      or modify license allocations for users.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/licenses\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Administration\n      - Entitlements\n      - Licenses\n      - Management\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/licenses\n      - type: OpenAPI\n        url: openapi/cisco-webex-licenses-openapi.yml\n  - aid: cisco-webex:webex-roles-api\n    name: Webex Roles API\n    description: >-\n      Retrieve roles available within a Webex organization. Roles define the\n      level of access and permissions granted to users, such as full\n      administrator or read-only administrator.\n\
  \    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/roles\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Access Control\n      - Administration\n      - Permissions\n      - Roles\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/roles\n      - type: OpenAPI\n        url: openapi/cisco-webex-roles-openapi.yml\n  - aid: cisco-webex:webex-workspaces-api\n    name: Webex Workspaces API\n    description: >-\n      Manage workspaces representing physical locations with Webex devices.\n      Provides endpoints to create, list, update, and delete workspaces and\n      manage their associated device configurations.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/workspaces\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Devices\n      - Facilities\n\
  \      - Locations\n      - Management\n      - Workspaces\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/workspaces\n      - type: OpenAPI\n        url: openapi/cisco-webex-workspaces-openapi.yml\n  - aid: cisco-webex:webex-admin-audit-events-api\n    name: Webex Admin Audit Events API\n    description: >-\n      Access admin audit events for tracking administrative actions performed\n      in Webex Control Hub. Available to full administrators for compliance\n      monitoring and security auditing purposes.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/admin-audit-events\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Administration\n      - Audit\n      - Compliance\n      - Events\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/admin-audit-events\n      - type: OpenAPI\n\
  \        url: openapi/cisco-webex-admin-audit-events-openapi.yml\n  - aid: cisco-webex:webex-converged-recordings-api\n    name: Webex Converged Recordings API\n    description: >-\n      Access converged recording capabilities across Webex Meetings and Webex\n      Calling. Provides unified endpoints for listing, retrieving, and managing\n      recordings from multiple Webex services.\n    image: https://www.webex.com/content/dam/wbx/us/images/webex-logo.svg\n    humanURL: https://developer.webex.com/docs/api/v1/converged-recordings\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Calling\n      - Compliance\n      - Media\n      - Meetings\n      - Recordings\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/api/v1/converged-recordings\n      - type: OpenAPI\n        url: openapi/cisco-webex-converged-recordings-openapi.yml\ncommon:\n  - type: Portal\n    url: https://developer.webex.com\n  - type: Documentation\n    url: https://developer.webex.com/docs/basics\n\
  \  - type: Getting Started\n    url: https://developer.webex.com/docs/getting-started\n  - type: Authentication\n    url: https://developer.webex.com/docs/getting-started#authentication\n  - type: SDKs\n    url: https://developer.webex.com/docs/sdks\n  - type: Change Log\n    url: https://developer.webex.com/docs/api/changelog\n  - type: Blog\n    url: https://developer.webex.com/blog\n  - type: Support\n    url: https://developer.webex.com/support\n  - type: Status\n    url: https://status.webex.com\n  - type: Rate Limits\n    url: https://developer.webex.com/docs/api-rate-limits\n  - type: Community\n    url: https://community.cisco.com/t5/webex-developers/bd-p/4416j-disc-dev-webex\n  - type: Terms of Service\n    url: https://developer.webex.com/terms-of-service\n  - type: Privacy Policy\n    url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html\n  - type: GitHub Organization\n    url: https://github.com/webex\n  - type: Website\n    url: https://www.webex.com\n  - type:\
  \ Login\n    url: https://developer.webex.com/login\n  - type: Sign Up\n    url: https://developer.webex.com/signup\n  - type: JSON-LD Context\n    url: json-ld/cisco-webex-context.jsonld\n  - type: JSON Schema\n    url: json-schema/\n  - type: Spectral\n    url: rules/cisco-webex-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cisco-webex-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://developer.webex.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco-webex/refs/heads/main/apis.yml
tags:
- Collaboration
- Communications
- Meetings
- Messaging
- Teams
- Video Conferencing
url: https://raw.githubusercontent.com/api-evangelist/cisco-webex/refs/heads/main/apis.yml
use_cases: []
---
