---
api_count: 2
apis:
- description: The Zulip REST API powers the Zulip web and mobile apps. It provides programmatic access to messages, streams, users, organizations, and all other Zulip functionality. Anything you can do in Zulip, yo
  name: Zulip REST API
  slug: rest-api
- description: Zulip supports both incoming webhooks (allowing third-party services to push data to Zulip) and outgoing webhooks (allowing Zulip to send HTTP POST payloads to external services when messages are sent
  name: Zulip Webhooks
  slug: webhooks
capabilities: []
common:
- title: ''
  type: Website
  url: https://zulip.com/
- title: ''
  type: Documentation
  url: https://zulip.com/api/
- title: ''
  type: GitHubOrganization
  url: https://github.com/zulip
created: '2026-01-02'
description: Zulip is an open-source team chat application with a unique topic-based threading model. Zulip's APIs power the web and mobile apps and provide REST endpoints, incoming webhooks, outgoing webhooks, and event-driven integrations to connect Zulip with external services.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-16'
name: Zulip
skills: []
slug: zulip
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zulip\nname: Zulip\ndescription: >-\n  Zulip is an open-source team chat application with a unique topic-based\n  threading model. Zulip's APIs power the web and mobile apps and provide\n  REST endpoints, incoming webhooks, outgoing webhooks, and event-driven\n  integrations to connect Zulip with external services.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Collaboration\n  - Messaging\n  - Team Chat\n  - Webhooks\ncreated: '2026-01-02'\nmodified: '2026-03-16'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zulip/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: zulip:rest-api\n    name: Zulip REST API\n    description: >-\n      The Zulip REST API powers the Zulip web and mobile apps. It provides\n      programmatic access to messages, streams, users, organizations, and\n      all other Zulip functionality. Anything you can do in Zulip,\
  \ you can\n      do with the REST API.\n    humanURL: https://zulip.com/api/rest\n    tags:\n      - Messaging\n      - REST\n      - Team Chat\n    properties:\n      - type: Documentation\n        url: https://zulip.com/api/rest\n      - type: Reference\n        url: https://zulip.com/api/\n  - aid: zulip:webhooks\n    name: Zulip Webhooks\n    description: >-\n      Zulip supports both incoming webhooks (allowing third-party services to\n      push data to Zulip) and outgoing webhooks (allowing Zulip to send HTTP\n      POST payloads to external services when messages are sent).\n    humanURL: https://zulip.com/api/incoming-webhooks-overview\n    tags:\n      - Events\n      - Integrations\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://zulip.com/api/incoming-webhooks-overview\n      - type: Reference\n        url: https://zulip.com/api/outgoing-webhooks\ncommon:\n  - url: https://zulip.com/\n    name: Zulip - Team Chat\n    type: Website\n    description:\
  \ 'null'\n  - url: https://zulip.com/api/\n    name: Zulip API Documentation\n    type: Documentation\n    description: 'null'\n  - url: https://zulip.com/api/integrations-overview\n    name: Zulip Integrations Overview\n    type: Integrations\n    description: 'null'\n  - url: https://github.com/zulip\n    name: Zulip GitHub Organization\n    type: GitHubOrganization\n    description: 'null'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zulip/refs/heads/main/apis.yml
tags:
- Collaboration
- Messaging
- Team Chat
- Webhooks
url: https://raw.githubusercontent.com/api-evangelist/zulip/refs/heads/main/apis.yml
use_cases: []
---
