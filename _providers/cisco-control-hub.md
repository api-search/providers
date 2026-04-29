---
api_count: 9
apis:
- description: Manage users, licenses, organization settings, and admin audit events for a Webex organization.
  name: Webex Admin API
  slug: webex-admin-api
- description: Manage Webex Calling features, phone numbers, dial plans, voice portals, and other organization-wide voice settings.
  name: Webex Calling API
  slug: webex-calling-api
- description: Manage Webex Room and Desk Devices, MPP phones, and headsets; query device status and push configuration.
  name: Webex Devices API
  slug: webex-devices-api
- description: Manage physical and virtual workspaces, meeting rooms, and shared-mode devices.
  name: Webex Workspaces API
  slug: webex-workspaces-api
- description: Manage user profiles, status, presence, and directory information.
  name: Webex People API
  slug: webex-people-api
- description: Inspect and manage Webex organization metadata and global settings.
  name: Webex Organizations API
  slug: webex-organizations-api
- description: List and assign Webex licenses and subscription entitlements to users.
  name: Webex Licenses API
  slug: webex-licenses-api
- description: Manage geographic locations used by Webex Calling for emergency services routing, time zones, and number assignments.
  name: Webex Locations API
  slug: webex-locations-api
- description: Generate and download analytics and usage reports for Webex services.
  name: Webex Reports API
  slug: webex-reports-api
common:
- title: ''
  type: Portal
  url: https://developer.webex.com
- title: ''
  type: Console
  url: https://admin.webex.com
- title: ''
  type: Authentication
  url: https://developer.webex.com/docs/getting-started#accounts-and-authentication
- title: ''
  type: Rate Limits
  url: https://developer.webex.com/docs/api-guidelines#rate-limiting
- title: ''
  type: Status
  url: https://status.webex.com
- title: ''
  type: Support
  url: https://developer.webex.com/support
- title: ''
  type: Change Log
  url: https://developer.webex.com/changelog
- title: ''
  type: GitHub Organization
  url: https://github.com/WebexSamples
- title: ''
  type: Terms of Service
  url: https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end-user-license-agreement.html
- title: ''
  type: Privacy Policy
  url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html
- title: ''
  type: JSON-LD
  url: json-ld/cisco-control-hub-context.jsonld
- title: ''
  type: Spectral
  url: rules/cisco-control-hub-rules.yml
created: '2024-01-01'
description: Cisco Control Hub is the administration console for Webex services. Programmatic access is delivered through the Webex Admin and adjacent REST APIs at webexapis.com — covering people, organizations, locations, workspaces, devices, licenses, calling configuration, audit events, and analytics reports. Authentication uses OAuth 2.0 access tokens or service-app tokens scoped to the organization.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cisco Control Hub Context
  property_count: 7
  slug: cisco-control-hub-context
layout: provider
modified: '2026-04-23'
name: Cisco Control Hub
rules:
- name: Cisco Control Hub API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: cisco-control-hub-rules
skills: []
slug: cisco-control-hub
solutions: []
source_filename: apis.yml
source_yaml: "aid: cisco-control-hub\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cisco-control-hub/refs/heads/main/apis.yml\nname: Cisco Control Hub\ntags:\n  - Administration\n  - Calling\n  - Collaboration\n  - Communications\n  - Device Management\n  - Identity Management\n  - Licenses\n  - Reporting\n  - Webex\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-01-01'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  Cisco Control Hub is the administration console for Webex services.\n  Programmatic access is delivered through the Webex Admin and adjacent\n  REST APIs at webexapis.com — covering people, organizations, locations,\n  workspaces, devices, licenses, calling configuration, audit events, and\n  analytics reports. Authentication uses OAuth 2.0 access tokens or\n  service-app tokens scoped to the organization.\napis:\n  - aid: cisco-control-hub:webex-admin-api\n\
  \    name: Webex Admin API\n    tags:\n      - Administration\n      - Audit\n      - Organizations\n      - Users\n    humanURL: https://developer.webex.com/docs/api/v1/admin-audit-events\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/admin-audit-events\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/openapi.json\n        type: OpenAPI\n      - url: https://developer.webex.com/docs/getting-started#accounts-and-authentication\n        type: Authentication\n    description: >-\n      Manage users, licenses, organization settings, and admin audit\n      events for a Webex organization.\n  - aid: cisco-control-hub:webex-calling-api\n    name: Webex Calling API\n    tags:\n      - Calling\n      - Phone Numbers\n      - Telephony\n      - Voice\n    humanURL: https://developer.webex.com/docs/api/v1/webex-calling-organization-settings\n    baseURL: https://webexapis.com/v1\n    properties:\n  \
  \    - url: https://developer.webex.com/docs/api/v1/webex-calling-organization-settings\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/openapi.json\n        type: OpenAPI\n    description: >-\n      Manage Webex Calling features, phone numbers, dial plans, voice\n      portals, and other organization-wide voice settings.\n  - aid: cisco-control-hub:webex-devices-api\n    name: Webex Devices API\n    tags:\n      - Configuration\n      - Devices\n      - Endpoints\n      - Room Systems\n    humanURL: https://developer.webex.com/docs/api/v1/devices\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/devices\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/openapi.json\n        type: OpenAPI\n    description: >-\n      Manage Webex Room and Desk Devices, MPP phones, and headsets;\n      query device status and push configuration.\n  - aid: cisco-control-hub:webex-workspaces-api\n\
  \    name: Webex Workspaces API\n    tags:\n      - Locations\n      - Meeting Rooms\n      - Workspaces\n    humanURL: https://developer.webex.com/docs/api/v1/workspaces\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/workspaces\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/openapi.json\n        type: OpenAPI\n    description: >-\n      Manage physical and virtual workspaces, meeting rooms, and\n      shared-mode devices.\n  - aid: cisco-control-hub:webex-people-api\n    name: Webex People API\n    tags:\n      - Directory\n      - People\n      - Profiles\n      - Users\n    humanURL: https://developer.webex.com/docs/api/v1/people\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/people\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/openapi.json\n        type: OpenAPI\n    description: >-\n \
  \     Manage user profiles, status, presence, and directory information.\n  - aid: cisco-control-hub:webex-organizations-api\n    name: Webex Organizations API\n    tags:\n      - Configuration\n      - Organizations\n      - Settings\n    humanURL: https://developer.webex.com/docs/api/v1/organizations\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/organizations\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/openapi.json\n        type: OpenAPI\n    description: >-\n      Inspect and manage Webex organization metadata and global settings.\n  - aid: cisco-control-hub:webex-licenses-api\n    name: Webex Licenses API\n    tags:\n      - Entitlements\n      - Licenses\n      - Subscriptions\n    humanURL: https://developer.webex.com/docs/api/v1/licenses\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/licenses\n        type: Documentation\n\
  \      - url: https://developer.webex.com/docs/api/v1/openapi.json\n        type: OpenAPI\n    description: >-\n      List and assign Webex licenses and subscription entitlements to\n      users.\n  - aid: cisco-control-hub:webex-locations-api\n    name: Webex Locations API\n    tags:\n      - Calling\n      - Geography\n      - Locations\n    humanURL: https://developer.webex.com/docs/api/v1/locations\n    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/locations\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/openapi.json\n        type: OpenAPI\n    description: >-\n      Manage geographic locations used by Webex Calling for emergency\n      services routing, time zones, and number assignments.\n  - aid: cisco-control-hub:webex-reports-api\n    name: Webex Reports API\n    tags:\n      - Analytics\n      - Metrics\n      - Reports\n      - Usage\n    humanURL: https://developer.webex.com/docs/api/v1/reports\n\
  \    baseURL: https://webexapis.com/v1\n    properties:\n      - url: https://developer.webex.com/docs/api/v1/reports\n        type: Documentation\n      - url: https://developer.webex.com/docs/api/v1/openapi.json\n        type: OpenAPI\n    description: >-\n      Generate and download analytics and usage reports for Webex\n      services.\ncommon:\n  - type: Portal\n    url: https://developer.webex.com\n  - type: Console\n    url: https://admin.webex.com\n  - type: Authentication\n    url: https://developer.webex.com/docs/getting-started#accounts-and-authentication\n  - type: Rate Limits\n    url: https://developer.webex.com/docs/api-guidelines#rate-limiting\n  - type: Status\n    url: https://status.webex.com\n  - type: Support\n    url: https://developer.webex.com/support\n  - type: Change Log\n    url: https://developer.webex.com/changelog\n  - type: GitHub Organization\n    url: https://github.com/WebexSamples\n  - type: Terms of Service\n    url: https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end-user-license-agreement.html\n\
  \  - type: Privacy Policy\n    url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html\n  - type: JSON-LD\n    url: json-ld/cisco-control-hub-context.jsonld\n  - type: Spectral\n    url: rules/cisco-control-hub-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco-control-hub/refs/heads/main/apis.yml
tags:
- Administration
- Calling
- Collaboration
- Communications
- Device Management
- Identity Management
- Licenses
- Reporting
- Webex
url: https://raw.githubusercontent.com/api-evangelist/cisco-control-hub/refs/heads/main/apis.yml
use_cases: []
---
