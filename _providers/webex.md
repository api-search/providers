---
api_count: 9
api_specs:
- filename: webex-messaging-openapi.json
  format: json
  label: Webex Messaging
  slug: messaging
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-messaging-openapi.json
- filename: webex-meeting-openapi.json
  format: json
  label: Webex Meetings
  slug: meetings
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-meeting-openapi.json
- filename: webex-admin-openapi.json
  format: json
  label: Webex Admin
  slug: admin
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-admin-openapi.json
- filename: webex-cloud-calling-openapi.json
  format: json
  label: Webex Cloud Calling
  slug: cloud-calling
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-cloud-calling-openapi.json
- filename: webex-contact-center-openapi.json
  format: json
  label: Webex Contact Center
  slug: contact-center
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-contact-center-openapi.json
- filename: webex-device-openapi.json
  format: json
  label: Webex Devices
  slug: devices
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-device-openapi.json
- filename: webex-broadworks-openapi.json
  format: json
  label: Webex Broadworks Calling
  slug: broadworks
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-broadworks-openapi.json
- filename: webex-ucm-openapi.json
  format: json
  label: Webex for UCM
  slug: ucm
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-ucm-openapi.json
- filename: webex-wholesale-openapi.json
  format: json
  label: Webex Wholesale
  slug: wholesale
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/openapi/webex-wholesale-openapi.json
apis:
- description: Webex Messaging API for creating and managing rooms, messages, attachments, teams, memberships, and real-time collaboration. Supports text, markdown, file sharing, and webhook event subscriptions.
  name: Webex Messaging
  slug: messaging
- description: Webex Meetings API for scheduling, managing, and reporting on video meetings. Provides endpoints for meeting lifecycle management, invitees, participants, recordings, transcripts, and meeting template
  name: Webex Meetings
  slug: meetings
- description: Webex Admin API for managing organizations, users, licenses, locations, workspaces, devices, and organization settings. Provides administrative control over Webex deployments including PSTN settings a
  name: Webex Admin
  slug: admin
- description: Webex Cloud Calling API with 633 endpoints for managing users, locations, call settings, hunt groups, auto-attendants, voicemail, call queues, and PSTN configurations for cloud-based telephony.
  name: Webex Cloud Calling
  slug: cloud-calling
- description: Webex Contact Center API for managing customer service operations including agents, queues, routing strategies, skills, and reporting. Enables programmatic control of contact center configurations and
  name: Webex Contact Center
  slug: contact-center
- description: Webex Device API for managing Webex hardware devices, workspaces, and device configurations. Includes endpoints for device inventory, activation, workspace assignments, and device-specific settings.
  name: Webex Devices
  slug: devices
- description: Webex Broadworks Calling API for managing BroadWorks subscriber provisioning and migration to Webex. Enables service providers to integrate BroadWorks telephony infrastructure with Webex cloud service
  name: Webex Broadworks Calling
  slug: broadworks
- description: Webex for Unified CM (UCM) API for managing on-premises Cisco Unified Communications Manager integration with Webex cloud services. Supports hybrid calling configurations.
  name: Webex for UCM
  slug: ucm
- description: Webex Wholesale API for service provider partners to provision and manage Webex Wholesale (RTM) customers and subscriptions at scale. Enables white-label Webex deployment workflows.
  name: Webex Wholesale
  slug: wholesale
capabilities:
- description: Unified capability for team collaboration workflows combining Webex Messaging and Webex Meetings APIs. Enables teams to communicate via rooms and messages, schedule and manage video meetings, and auto
  name: Webex Team Collaboration
  slug: team-collaboration
common:
- title: ''
  type: Portal
  url: https://developer.webex.com/
- title: ''
  type: GettingStarted
  url: https://developer.webex.com/docs/getting-started
- title: ''
  type: Authentication
  url: https://developer.webex.com/docs/authentication
- title: ''
  type: SDK
  url: https://developer.webex.com/docs/sdks
- title: JavaScript SDK
  type: SDK
  url: https://github.com/webex/webex-js-sdk
- title: iOS SDK
  type: SDK
  url: https://github.com/webex/webex-ios-sdk
- title: Android SDK
  type: SDK
  url: https://github.com/webex/webex-android-sdk
- title: ''
  type: Blog
  url: https://developer.webex.com/blog
- title: ''
  type: StatusPage
  url: https://status.webex.com
- title: ''
  type: Support
  url: https://developer.webex.com/support
- title: ''
  type: TermsOfService
  url: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html
- title: ''
  type: PrivacyPolicy
  url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html
- title: ''
  type: RateLimits
  url: https://developer.webex.com/docs/rate-limiting
- title: ''
  type: GitHubOrganization
  url: https://github.com/webex
- title: ''
  type: GitHubRepository
  url: https://github.com/webex/webex-openapi-specs
- title: ''
  type: SpectralRules
  url: rules/webex-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/webex-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/team-collaboration.yaml
- title: ''
  type: JSONLD
  url: json-ld/webex-messaging-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/webex-meeting-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/webex-admin-context.jsonld
- title: ''
  type: JSONLD
  url: json-ld/webex-device-context.jsonld
created: '2025-02-06'
description: Cisco Webex is a comprehensive collaboration platform offering APIs for messaging, meetings, calling, devices, and contact center workflows. The Webex Developer Platform enables developers to build integrations, bots, embedded apps, and automations using REST APIs, SDKs, and webhooks. Webex supports OAuth 2.0 authentication and provides separate API surfaces for messaging, video conferencing, cloud calling, admin management, and more.
features:
- description: Comprehensive REST APIs for messaging, meetings, calling, devices, admin, and contact center.
  name: REST APIs
- description: Secure authentication via OAuth 2.0 authorization code flow for integrations and personal access tokens for development.
  name: OAuth 2.0 Authentication
- description: Real-time event notifications via HTTP webhooks for messages, memberships, meetings, and more.
  name: Webhooks
- description: Build apps that run directly inside Webex meetings and spaces using the Embedded App Framework.
  name: Embedded Apps
- description: Create chatbots that post content, respond to commands, and automate workflows in Webex rooms.
  name: Bots
- description: Embed Webex messaging and calling functionality directly in external web applications.
  name: Widgets
- description: Generate guest tokens to add external users to Webex spaces without requiring a Webex account.
  name: Guest Issuer
- description: Full programmatic control over Webex organizations, users, licenses, locations, and policies.
  name: Admin API
image: https://developer.webex.com/images/webex-logo.png
integrations:
- description: Webex for Salesforce integration for CRM-embedded collaboration.
  name: Salesforce
- description: Interoperability integration between Webex and Microsoft Teams.
  name: Microsoft Teams
- description: Webex integration with Slack for cross-platform notifications and workflows.
  name: Slack
- description: Webex App Hub integration with Atlassian Jira for project tracking.
  name: Jira
- description: Webex integration with ServiceNow for IT service management workflows.
  name: ServiceNow
- description: Webex integration with Google Calendar and Gmail.
  name: Google Workspace
jsonld:
- class_count: 5
  name: Webex Admin Context
  property_count: 9
  slug: webex-admin-context
- class_count: 5
  name: Webex Broadworks Context
  property_count: 9
  slug: webex-broadworks-context
- class_count: 5
  name: Webex Cloud Context
  property_count: 9
  slug: webex-cloud-context
- class_count: 5
  name: Webex Contact Context
  property_count: 9
  slug: webex-contact-context
- class_count: 5
  name: Webex Device Context
  property_count: 9
  slug: webex-device-context
- class_count: 5
  name: Webex Meeting Context
  property_count: 9
  slug: webex-meeting-context
- class_count: 5
  name: Webex Messaging Context
  property_count: 9
  slug: webex-messaging-context
- class_count: 5
  name: Webex Ucm Context
  property_count: 9
  slug: webex-ucm-context
- class_count: 5
  name: Webex Wholesale Context
  property_count: 9
  slug: webex-wholesale-context
layout: provider
modified: '2026-05-03'
name: Webex
rules:
- name: Webex API Rules
  rule_count: 29
  severity_counts:
    error: 9
    hint: 0
    info: 6
    warn: 14
  slug: webex-spectral-rules
skills: []
slug: webex
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: webex\nname: Webex\ndescription: >-\n  Cisco Webex is a comprehensive collaboration platform offering APIs for\n  messaging, meetings, calling, devices, and contact center workflows. The\n  Webex Developer Platform enables developers to build integrations, bots,\n  embedded apps, and automations using REST APIs, SDKs, and webhooks. Webex\n  supports OAuth 2.0 authentication and provides separate API surfaces for\n  messaging, video conferencing, cloud calling, admin management, and more.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://developer.webex.com/images/webex-logo.png\ntags:\n  - Calling\n  - Collaboration\n  - Communication\n  - Enterprise\n  - Messaging\n  - Video Conferencing\nurl: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/apis.yml\ncreated: '2025-02-06'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: webex:messaging\n    name: Webex Messaging\n    description: >-\n      Webex Messaging\
  \ API for creating and managing rooms, messages, attachments,\n      teams, memberships, and real-time collaboration. Supports text, markdown,\n      file sharing, and webhook event subscriptions.\n    humanURL: https://developer.webex.com/docs/messaging\n    tags:\n      - Bots\n      - Collaboration\n      - Messaging\n      - Rooms\n      - Teams\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/messaging\n      - type: OpenAPI\n        url: openapi/webex-messaging-openapi.json\n\n  - aid: webex:meetings\n    name: Webex Meetings\n    description: >-\n      Webex Meetings API for scheduling, managing, and reporting on video meetings.\n      Provides endpoints for meeting lifecycle management, invitees, participants,\n      recordings, transcripts, and meeting templates.\n    humanURL: https://developer.webex.com/docs/meetings\n    tags:\n      - Meetings\n      - Recordings\n      - Scheduling\n      - Video Conferencing\n\
  \    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/meetings\n      - type: OpenAPI\n        url: openapi/webex-meeting-openapi.json\n\n  - aid: webex:admin\n    name: Webex Admin\n    description: >-\n      Webex Admin API for managing organizations, users, licenses, locations,\n      workspaces, devices, and organization settings. Provides administrative\n      control over Webex deployments including PSTN settings and call policies.\n    humanURL: https://developer.webex.com/docs/admin\n    tags:\n      - Administration\n      - Devices\n      - Licenses\n      - Organizations\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/admin\n      - type: OpenAPI\n        url: openapi/webex-admin-openapi.json\n\n  - aid: webex:cloud-calling\n    name: Webex Cloud Calling\n    description: >-\n      Webex Cloud Calling API with 633 endpoints for managing users, locations,\n      call settings, hunt\
  \ groups, auto-attendants, voicemail, call queues,\n      and PSTN configurations for cloud-based telephony.\n    humanURL: https://developer.webex.com/docs/cloud-calling\n    tags:\n      - Auto Attendant\n      - Call Management\n      - Calling\n      - Cloud Telephony\n      - PSTN\n      - Voicemail\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/cloud-calling\n      - type: OpenAPI\n        url: openapi/webex-cloud-calling-openapi.json\n\n  - aid: webex:contact-center\n    name: Webex Contact Center\n    description: >-\n      Webex Contact Center API for managing customer service operations including\n      agents, queues, routing strategies, skills, and reporting. Enables\n      programmatic control of contact center configurations and workflows.\n    humanURL: https://developer.webex.com/docs/contact-center\n    tags:\n      - Agents\n      - Contact Center\n      - Customer Service\n      - Queues\n      - Routing\n    properties:\n\
  \      - type: Documentation\n        url: https://developer.webex.com/docs/contact-center\n      - type: OpenAPI\n        url: openapi/webex-contact-center-openapi.json\n\n  - aid: webex:devices\n    name: Webex Devices\n    description: >-\n      Webex Device API for managing Webex hardware devices, workspaces, and\n      device configurations. Includes endpoints for device inventory, activation,\n      workspace assignments, and device-specific settings.\n    humanURL: https://developer.webex.com/docs/devices\n    tags:\n      - Devices\n      - Hardware\n      - Workspaces\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/devices\n      - type: OpenAPI\n        url: openapi/webex-device-openapi.json\n\n  - aid: webex:broadworks\n    name: Webex Broadworks Calling\n    description: >-\n      Webex Broadworks Calling API for managing BroadWorks subscriber provisioning\n      and migration to Webex. Enables service providers to integrate BroadWorks\n\
  \      telephony infrastructure with Webex cloud services.\n    humanURL: https://developer.webex.com/docs/broadworks\n    tags:\n      - BroadWorks\n      - Calling\n      - Service Provider\n      - Telephony\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/broadworks\n      - type: OpenAPI\n        url: openapi/webex-broadworks-openapi.json\n\n  - aid: webex:ucm\n    name: Webex for UCM\n    description: >-\n      Webex for Unified CM (UCM) API for managing on-premises Cisco Unified\n      Communications Manager integration with Webex cloud services. Supports\n      hybrid calling configurations.\n    humanURL: https://developer.webex.com/docs/ucm\n    tags:\n      - Calling\n      - On-Premises\n      - Unified CM\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/ucm\n      - type: OpenAPI\n        url: openapi/webex-ucm-openapi.json\n\n  - aid: webex:wholesale\n    name: Webex Wholesale\n    description:\
  \ >-\n      Webex Wholesale API for service provider partners to provision and manage\n      Webex Wholesale (RTM) customers and subscriptions at scale. Enables\n      white-label Webex deployment workflows.\n    humanURL: https://developer.webex.com/docs/wholesale\n    tags:\n      - Partner\n      - Provisioning\n      - Service Provider\n      - Wholesale\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/wholesale\n      - type: OpenAPI\n        url: openapi/webex-wholesale-openapi.json\n\ncommon:\n  - url: https://developer.webex.com/\n    name: Webex Developer Portal\n    type: Portal\n    description: Main developer portal for Webex APIs, documentation, and sandbox.\n  - url: https://developer.webex.com/docs/getting-started\n    name: Getting Started with Webex APIs\n    type: GettingStarted\n    description: Quick start guide for authenticating and making your first Webex API call.\n  - url: https://developer.webex.com/docs/authentication\n\
  \    name: Webex Authentication\n    type: Authentication\n    description: OAuth 2.0 authentication flows and personal access tokens for Webex APIs.\n  - url: https://developer.webex.com/docs/sdks\n    name: Webex SDKs\n    type: SDK\n    description: Official Webex SDKs for JavaScript, iOS, Android, and other platforms.\n  - url: https://github.com/webex/webex-js-sdk\n    name: Webex JavaScript SDK\n    type: SDK\n    title: JavaScript SDK\n    description: Official JavaScript SDK for Webex APIs.\n  - url: https://github.com/webex/webex-ios-sdk\n    name: Webex iOS SDK\n    type: SDK\n    title: iOS SDK\n    description: Official iOS SDK for Webex APIs.\n  - url: https://github.com/webex/webex-android-sdk\n    name: Webex Android SDK\n    type: SDK\n    title: Android SDK\n    description: Official Android SDK for Webex APIs.\n  - url: https://developer.webex.com/blog\n    name: Webex Developer Blog\n    type: Blog\n    description: Updates, tutorials, and announcements from the Webex\
  \ developer team.\n  - url: https://status.webex.com\n    name: Webex Status\n    type: StatusPage\n    description: Real-time status and incident reports for Webex services.\n  - url: https://developer.webex.com/support\n    name: Webex Developer Support\n    type: Support\n    description: Developer community and support resources.\n  - url: https://www.cisco.com/c/en/us/about/legal/terms-conditions.html\n    name: Webex Terms of Service\n    type: TermsOfService\n    description: Terms and conditions for Cisco Webex services.\n  - url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html\n    name: Webex Privacy Policy\n    type: PrivacyPolicy\n    description: Privacy policy for Cisco Webex services.\n  - url: https://developer.webex.com/docs/rate-limiting\n    name: Webex Rate Limits\n    type: RateLimits\n    description: API rate limiting policies for Webex developer APIs.\n  - url: https://github.com/webex\n    name: Webex GitHub Organization\n    type: GitHubOrganization\n\
  \    description: Official Webex GitHub organization with SDKs, samples, and specs.\n  - url: https://github.com/webex/webex-openapi-specs\n    name: Webex OpenAPI Specifications\n    type: GitHubRepository\n    description: Official repository of all public Webex API OpenAPI specifications.\n  - type: SpectralRules\n    url: rules/webex-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/webex-vocabulary.yml\n  - type: NaftikoCapability\n    url: capabilities/team-collaboration.yaml\n  - type: JSONLD\n    url: json-ld/webex-messaging-context.jsonld\n  - type: JSONLD\n    url: json-ld/webex-meeting-context.jsonld\n  - type: JSONLD\n    url: json-ld/webex-admin-context.jsonld\n  - type: JSONLD\n    url: json-ld/webex-device-context.jsonld\n  - name: Webex Features\n    type: Features\n    data:\n      - name: REST APIs\n        description: Comprehensive REST APIs for messaging, meetings, calling, devices, admin, and contact center.\n      - name: OAuth 2.0 Authentication\n  \
  \      description: Secure authentication via OAuth 2.0 authorization code flow for integrations and personal access tokens for development.\n      - name: Webhooks\n        description: Real-time event notifications via HTTP webhooks for messages, memberships, meetings, and more.\n      - name: Embedded Apps\n        description: Build apps that run directly inside Webex meetings and spaces using the Embedded App Framework.\n      - name: Bots\n        description: Create chatbots that post content, respond to commands, and automate workflows in Webex rooms.\n      - name: Widgets\n        description: Embed Webex messaging and calling functionality directly in external web applications.\n      - name: Guest Issuer\n        description: Generate guest tokens to add external users to Webex spaces without requiring a Webex account.\n      - name: Admin API\n        description: Full programmatic control over Webex organizations, users, licenses, locations, and policies.\n  - name: Webex\
  \ Use Cases\n    type: UseCases\n    data:\n      - name: Collaboration Automation\n        description: Automate room creation, messaging workflows, and team management using the Messaging API.\n      - name: Meeting Scheduling Integration\n        description: Integrate Webex meeting scheduling into CRM, calendar, or project management applications.\n      - name: Custom Bot Development\n        description: Build intelligent chatbots that respond to user commands and integrate with business systems.\n      - name: Contact Center Automation\n        description: Programmatically configure contact center queues, routing strategies, and agent assignments.\n      - name: Unified Communications Administration\n        description: Automate user provisioning, license assignment, and calling configuration at scale.\n      - name: Event-Driven Workflows\n        description: Use webhooks to trigger business workflows when messages are sent, meetings start, or rooms change.\n  - name: Webex\
  \ Integrations\n    type: Integrations\n    data:\n      - name: Salesforce\n        description: Webex for Salesforce integration for CRM-embedded collaboration.\n      - name: Microsoft Teams\n        description: Interoperability integration between Webex and Microsoft Teams.\n      - name: Slack\n        description: Webex integration with Slack for cross-platform notifications and workflows.\n      - name: Jira\n        description: Webex App Hub integration with Atlassian Jira for project tracking.\n      - name: ServiceNow\n        description: Webex integration with ServiceNow for IT service management workflows.\n      - name: Google Workspace\n        description: Webex integration with Google Calendar and Gmail.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/apis.yml
tags:
- Calling
- Collaboration
- Communication
- Enterprise
- Messaging
- Video Conferencing
url: https://raw.githubusercontent.com/api-evangelist/webex/refs/heads/main/apis.yml
use_cases:
- description: Automate room creation, messaging workflows, and team management using the Messaging API.
  name: Collaboration Automation
- description: Integrate Webex meeting scheduling into CRM, calendar, or project management applications.
  name: Meeting Scheduling Integration
- description: Build intelligent chatbots that respond to user commands and integrate with business systems.
  name: Custom Bot Development
- description: Programmatically configure contact center queues, routing strategies, and agent assignments.
  name: Contact Center Automation
- description: Automate user provisioning, license assignment, and calling configuration at scale.
  name: Unified Communications Administration
- description: Use webhooks to trigger business workflows when messages are sent, meetings start, or rooms change.
  name: Event-Driven Workflows
---
