---
api_count: 4
api_specs:
- filename: microsoft-teams-graph-api.yaml
  format: yaml
  label: Microsoft Graph Teams API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-teams/refs/heads/main/openapi/microsoft-teams-graph-api.yaml
apis:
- description: Core REST API for accessing Teams data including teams, channels, messages, tabs, apps, members, online meetings, and calls through Microsoft Graph.
  name: Microsoft Graph Teams API
  slug: ''
- description: API for building conversational bots that interact with users in Microsoft Teams through the Bot Framework.
  name: Microsoft Teams Bot Framework API
  slug: ''
- description: APIs for creating incoming webhooks and Office 365 connectors to post messages and notifications to Teams channels.
  name: Microsoft Teams Webhook and Connector API
  slug: ''
- description: APIs for building calling and meeting experiences in Teams including VoIP calls, group calls, IVR flows, and online meetings.
  name: Microsoft Teams Real-Time Communication APIs
  slug: ''
capabilities:
- description: Workflow capability for team collaboration including managing teams, channels, messaging, members, meetings, and calls. Used by IT administrators, team leads, and developers building Teams integration
  name: Microsoft Teams Collaboration
  slug: team-collaboration
common:
- title: ''
  type: DeveloperPortal
  url: https://developer.microsoft.com/en-us/microsoft-teams
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/microsoftteams/platform/get-started/get-started-overview
- title: Teams Toolkit
  type: SDK
  url: https://learn.microsoft.com/en-us/microsoftteams/platform/toolkit/teams-toolkit-fundamentals
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/microsoft-teams-blog/bg-p/MicrosoftTeamsBlog
- title: ''
  type: Support
  url: https://learn.microsoft.com/en-us/answers/products/office-teams
- title: ''
  type: GitHubOrganization
  url: https://github.com/OfficeDev/Microsoft-Teams-Samples
- title: ''
  type: StatusPage
  url: https://status.teams.microsoft.com/
- title: ''
  type: TermsOfService
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://privacy.microsoft.com/en-us/privacystatement
- title: ''
  type: SpectralRules
  url: rules/microsoft-teams-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/team-collaboration.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/microsoft-teams-vocabulary.yaml
created: '2024'
description: Microsoft Teams is a collaboration platform that combines workplace chat, meetings, file storage, and application integration. It provides APIs for building custom integrations, managing teams and channels, sending messages, scheduling meetings, and initiating calls through Microsoft Graph.
features:
- description: Create, archive, and delete teams programmatically.
  name: Team Lifecycle Management
- description: Create and manage standard, private, and shared channels.
  name: Channel Management
- description: Send and receive chat messages in channels and chats.
  name: Messaging
- description: Add, remove, and update team members and roles.
  name: Member Management
- description: Create and manage online meetings with join URLs.
  name: Online Meetings
- description: Initiate calls, answer, reject, transfer, and manage IVR flows.
  name: Calling
- description: Install and manage apps in teams and channels.
  name: App Installation
- description: Send activity feed notifications to engage users.
  name: Activity Feed Notifications
image: https://learn.microsoft.com/en-us/graph/images/teams-logo.png
integrations:
- description: Automate Teams workflows with Power Automate connectors.
  name: Microsoft Power Automate
- description: Teams channels with SharePoint document libraries.
  name: SharePoint
- description: Share and collaborate on files in Teams via OneDrive.
  name: OneDrive
- description: Build and deploy bots using Azure Bot Service.
  name: Azure Bot Service
- description: Rich interactive cards for messaging and notifications.
  name: Adaptive Cards
jsonld:
- class_count: 9
  name: Microsoft Teams Graph Api Context
  property_count: 22
  slug: microsoft-teams-graph-api-context
layout: provider
modified: '2026-04-18'
name: Microsoft Teams
rules:
- name: Microsoft Teams API Rules
  rule_count: 23
  severity_counts:
    error: 15
    hint: 0
    info: 2
    warn: 6
  slug: microsoft-teams-spectral-rules
skills: []
slug: microsoft-teams
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-teams\nname: Microsoft Teams\ndescription: >-\n  Microsoft Teams is a collaboration platform that combines workplace chat,\n  meetings, file storage, and application integration. It provides APIs for\n  building custom integrations, managing teams and channels, sending messages,\n  scheduling meetings, and initiating calls through Microsoft Graph.\nimage: https://learn.microsoft.com/en-us/graph/images/teams-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/microsoft-teams/refs/heads/main/apis.yml\nhumanURL: https://www.microsoft.com/en-us/microsoft-teams\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Chat\n  - Collaboration\n  - Communication\n  - Microsoft 365\n  - Productivity\n  - Video Conferencing\napis:\n  - name: Microsoft Graph Teams API\n    description: >-\n      Core REST API for accessing Teams data including teams, channels, messages,\n      tabs, apps, members, online meetings, and calls\
  \ through Microsoft Graph.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/teams-api-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Channels\n      - Messages\n      - Microsoft Graph\n      - REST API\n      - Teams\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/teams-api-overview\n      - type: OpenAPI\n        url: openapi/microsoft-teams-graph-api.yaml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/graph/auth/\n      - type: SDK\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: RateLimits\n        url: https://learn.microsoft.com/en-us/graph/throttling\n      - type: JSONSchema\n        url: json-schema/teams-graph-api-team-schema.json\n      - type: JSONSchema\n        url: json-schema/teams-graph-api-channel-schema.json\n      - type: JSONSchema\n        url: json-schema/teams-graph-api-chat-message-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/teams-graph-api-conversation-member-schema.json\n      - type: JSONSchema\n        url: json-schema/teams-graph-api-online-meeting-schema.json\n      - type: JSONSchema\n        url: json-schema/teams-graph-api-call-schema.json\n      - type: JSONStructure\n        url: json-structure/teams-graph-api-team-structure.json\n      - type: JSON-LD\n        url: json-ld/microsoft-teams-graph-api-context.jsonld\n      - type: Example\n        url: examples/teams-graph-api-team-example.json\n      - type: Example\n        url: examples/teams-graph-api-channel-example.json\n      - type: Example\n        url: examples/teams-graph-api-chat-message-example.json\n  - name: Microsoft Teams Bot Framework API\n    description: >-\n      API for building conversational bots that interact with users in\n      Microsoft Teams through the Bot Framework.\n    humanURL: https://learn.microsoft.com/en-us/microsoftteams/platform/bots/what-are-bots\n    baseURL:\
  \ https://smba.trafficmanager.net/teams/\n    tags:\n      - Bot Framework\n      - Bots\n      - Conversational AI\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoftteams/platform/bots/how-to/conversations/conversation-basics\n      - type: Quickstart\n        url: https://learn.microsoft.com/en-us/microsoftteams/platform/build-your-first-app/build-bot\n      - type: CodeExamples\n        url: https://github.com/microsoft/BotBuilder-Samples\n        title: Bot Builder Samples\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-connector-api-reference\n  - name: Microsoft Teams Webhook and Connector API\n    description: >-\n      APIs for creating incoming webhooks and Office 365 connectors to post\n      messages and notifications to Teams channels.\n    humanURL: https://learn.microsoft.com/en-us/microsoftteams/platform/webhooks-and-connectors/what-are-webhooks-and-connectors\n\
  \    baseURL: https://outlook.office.com/webhook/\n    tags:\n      - Connectors\n      - Incoming Webhooks\n      - Notifications\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/microsoftteams/platform/webhooks-and-connectors/how-to/add-incoming-webhook\n  - name: Microsoft Teams Real-Time Communication APIs\n    description: >-\n      APIs for building calling and meeting experiences in Teams including\n      VoIP calls, group calls, IVR flows, and online meetings.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/communications-api-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Audio\n      - Calling\n      - Meetings\n      - Real-Time\n      - Video\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/communications-api-overview\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/resources/call\n\
  common:\n  - type: DeveloperPortal\n    url: https://developer.microsoft.com/en-us/microsoft-teams\n  - type: GettingStarted\n    url: https://learn.microsoft.com/en-us/microsoftteams/platform/get-started/get-started-overview\n  - type: SDK\n    url: https://learn.microsoft.com/en-us/microsoftteams/platform/toolkit/teams-toolkit-fundamentals\n    title: Teams Toolkit\n  - type: Blog\n    url: https://techcommunity.microsoft.com/t5/microsoft-teams-blog/bg-p/MicrosoftTeamsBlog\n  - type: Support\n    url: https://learn.microsoft.com/en-us/answers/products/office-teams\n  - type: GitHubOrganization\n    url: https://github.com/OfficeDev/Microsoft-Teams-Samples\n  - type: StatusPage\n    url: https://status.teams.microsoft.com/\n  - type: TermsOfService\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://privacy.microsoft.com/en-us/privacystatement\n  - type: SpectralRules\n    url: rules/microsoft-teams-spectral-rules.yml\n  - type: NaftikoCapability\n\
  \    url: capabilities/team-collaboration.yaml\n  - type: Vocabulary\n    url: vocabulary/microsoft-teams-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Team Lifecycle Management\n        description: Create, archive, and delete teams programmatically.\n      - name: Channel Management\n        description: Create and manage standard, private, and shared channels.\n      - name: Messaging\n        description: Send and receive chat messages in channels and chats.\n      - name: Member Management\n        description: Add, remove, and update team members and roles.\n      - name: Online Meetings\n        description: Create and manage online meetings with join URLs.\n      - name: Calling\n        description: Initiate calls, answer, reject, transfer, and manage IVR flows.\n      - name: App Installation\n        description: Install and manage apps in teams and channels.\n      - name: Activity Feed Notifications\n        description: Send activity feed notifications to\
  \ engage users.\n  - type: UseCases\n    data:\n      - name: Team Provisioning\n        description: Automate creation and configuration of teams for projects.\n      - name: Messaging Automation\n        description: Send automated notifications and updates to channels.\n      - name: Meeting Scheduling\n        description: Programmatically create and manage online meetings.\n      - name: Customer Service Bots\n        description: Build conversational bots for customer support in Teams.\n      - name: Workforce Management\n        description: Manage shifts and schedules for frontline workers.\n  - type: Integrations\n    data:\n      - name: Microsoft Power Automate\n        description: Automate Teams workflows with Power Automate connectors.\n      - name: SharePoint\n        description: Teams channels with SharePoint document libraries.\n      - name: OneDrive\n        description: Share and collaborate on files in Teams via OneDrive.\n      - name: Azure Bot Service\n      \
  \  description: Build and deploy bots using Azure Bot Service.\n      - name: Adaptive Cards\n        description: Rich interactive cards for messaging and notifications.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-teams/refs/heads/main/apis.yml
tags:
- Chat
- Collaboration
- Communication
- Microsoft 365
- Productivity
- Video Conferencing
url: https://raw.githubusercontent.com/api-evangelist/microsoft-teams/refs/heads/main/apis.yml
use_cases:
- description: Automate creation and configuration of teams for projects.
  name: Team Provisioning
- description: Send automated notifications and updates to channels.
  name: Messaging Automation
- description: Programmatically create and manage online meetings.
  name: Meeting Scheduling
- description: Build conversational bots for customer support in Teams.
  name: Customer Service Bots
- description: Manage shifts and schedules for frontline workers.
  name: Workforce Management
---
