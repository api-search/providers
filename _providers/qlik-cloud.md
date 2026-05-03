---
api_count: 8
apis:
- description: Main REST API for Qlik Cloud providing access to apps, spaces, users, and resources.
  name: Qlik Cloud REST API
  slug: qlik-cloud-rest-api
- description: WebSocket-based JSON-RPC API for direct interaction with the Qlik Associative Engine.
  name: Qlik Engine JSON API
  slug: qlik-engine-json-api
- description: APIs for data integration, ETL processes, and data pipeline management.
  name: Qlik Data Integration
  slug: qlik-data-integration
- description: API for managing app reloads and data refresh operations.
  name: Qlik Reload
  slug: qlik-reload
- description: Manage users, groups, and access control in Qlik Cloud.
  name: Qlik Users and Groups
  slug: qlik-users-and-groups
- description: Manage shared and personal spaces for organizing Qlik content.
  name: Qlik Spaces
  slug: qlik-spaces
- description: Create, manage, and interact with Qlik Sense applications.
  name: Qlik Apps
  slug: qlik-apps
- description: Create and manage automated workflows in Qlik Cloud.
  name: Qlik Automations
  slug: qlik-automations
common:
- title: ''
  type: GettingStarted
  url: https://qlik.dev/get-started
- title: ''
  type: Authentication
  url: https://qlik.dev/authenticate
- title: ''
  type: Portal
  url: https://qlik.dev
- title: ''
  type: Community
  url: https://community.qlik.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/qlik-oss
- title: ''
  type: Status
  url: https://status.qlik.com
- title: ''
  type: TermsOfService
  url: https://www.qlik.com/us/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.qlik.com/us/legal/privacy
- title: ''
  type: Website
  url: https://www.qlik.com
created: '2024-01-01'
description: Collection of APIs for Qlik Cloud platform, providing data integration, analytics, and visualization capabilities.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Qlik Cloud
skills: []
slug: qlik-cloud
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: qlik-cloud\nname: Qlik Cloud\ndescription: >-\n  Collection of APIs for Qlik Cloud platform, providing data integration,\n  analytics, and visualization capabilities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Business Intelligence\n  - Cloud\n  - Data Integration\n  - SaaS\n  - Visualization\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/qlik-cloud/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: qlik-cloud:qlik-cloud-rest-api\n    name: Qlik Cloud REST API\n    description: >-\n      Main REST API for Qlik Cloud providing access to apps, spaces, users, and\n      resources.\n    humanURL: https://qlik.dev/apis/rest\n    tags:\n      - Analytics\n      - Data\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest\n      - type: Authentication\n        url: https://qlik.dev/authenticate\n\
  \  - aid: qlik-cloud:qlik-engine-json-api\n    name: Qlik Engine JSON API\n    description: >-\n      WebSocket-based JSON-RPC API for direct interaction with the Qlik\n      Associative Engine.\n    humanURL: https://qlik.dev/apis/json-rpc\n    tags:\n      - Engine\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/json-rpc\n      - type: SDK\n        url: https://github.com/qlik-oss/enigma.js\n  - aid: qlik-cloud:qlik-data-integration\n    name: Qlik Data Integration\n    description: >-\n      APIs for data integration, ETL processes, and data pipeline management.\n    humanURL: https://qlik.dev/apis/rest/data-integration\n    tags:\n      - Data Integration\n      - ETL\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/data-integration\n  - aid: qlik-cloud:qlik-reload\n    name: Qlik Reload\n    description: API for managing app reloads and data refresh operations.\n    humanURL: https://qlik.dev/apis/rest/reloads\n\
  \    tags:\n      - Reload\n      - Automation\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/reloads\n  - aid: qlik-cloud:qlik-users-and-groups\n    name: Qlik Users and Groups\n    description: Manage users, groups, and access control in Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/users\n    tags:\n      - Users\n      - IAM\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/users\n  - aid: qlik-cloud:qlik-spaces\n    name: Qlik Spaces\n    description: Manage shared and personal spaces for organizing Qlik content.\n    humanURL: https://qlik.dev/apis/rest/spaces\n    tags:\n      - Spaces\n      - Content Management\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/spaces\n  - aid: qlik-cloud:qlik-apps\n    name: Qlik Apps\n    description: Create, manage, and interact with Qlik Sense applications.\n    humanURL: https://qlik.dev/apis/rest/apps\n    tags:\n    \
  \  - Applications\n      - Analytics\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/apps\n  - aid: qlik-cloud:qlik-automations\n    name: Qlik Automations\n    description: Create and manage automated workflows in Qlik Cloud.\n    humanURL: https://qlik.dev/apis/rest/automations\n    tags:\n      - Automation\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://qlik.dev/apis/rest/automations\ncommon:\n  - type: GettingStarted\n    url: https://qlik.dev/get-started\n  - type: Authentication\n    url: https://qlik.dev/authenticate\n  - type: Portal\n    url: https://qlik.dev\n  - type: Community\n    url: https://community.qlik.com\n  - type: GitHubOrganization\n    url: https://github.com/qlik-oss\n  - type: Status\n    url: https://status.qlik.com\n  - type: TermsOfService\n    url: https://www.qlik.com/us/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.qlik.com/us/legal/privacy\n  - type: Website\n\
  \    url: https://www.qlik.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/qlik-cloud/refs/heads/main/apis.yml
tags:
- Analytics
- Business Intelligence
- Cloud
- Data Integration
- SaaS
- Visualization
url: https://raw.githubusercontent.com/api-evangelist/qlik-cloud/refs/heads/main/apis.yml
use_cases: []
---
