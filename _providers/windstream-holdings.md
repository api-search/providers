---
api_count: 2
api_specs:
- filename: windstream-voice-openapi.yml
  format: yaml
  label: Windstream Enterprise Voice API
  slug: windstream-voice-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/openapi/windstream-voice-openapi.yml
- filename: windstream-contact-center-openapi.yml
  format: yaml
  label: Windstream Enterprise Contact Center Services API
  slug: windstream-contact-center-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/openapi/windstream-contact-center-openapi.yml
apis:
- description: The Windstream Enterprise Voice API (silhouette) is a REST-based web service with WebSocket support for real-time events. It enables developers to make and receive calls, manage auto-attendants, contr
  name: Windstream Enterprise Voice API
  slug: windstream-voice-api
- description: The Windstream Enterprise Contact Center Services (CCS) API provides programmatic access to contact center operations, enabling developers to route calls, web chats, and text messages, manage agent st
  name: Windstream Enterprise Contact Center Services API
  slug: windstream-contact-center-api
capabilities:
- description: Unified Communications capability for Windstream Enterprise, combining Voice and Contact Center APIs to enable end-to-end call management, agent operations, auto-attendant configuration, and contact c
  name: Windstream Unified Communications
  slug: unified-communications
common:
- title: ''
  type: Website
  url: https://www.windstreamenterprise.com/
- title: ''
  type: Portal
  url: https://api.solutions.uniti.com/
- title: ''
  type: DeveloperHub
  url: https://solutions.uniti.com/developer-hub
- title: ''
  type: APIMarketplace
  url: https://api.solutions.uniti.com/
- title: ''
  type: Documentation
  url: https://api.solutions.uniti.com/
- title: ''
  type: SalesforcIntegration
  url: https://solutions.uniti.com/developer-hub/app-gallery/salesforce-api
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/windstream-enterprise
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/json-ld/windstream-holdings-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/vocabulary/windstream-holdings-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/capabilities/unified-communications.yaml
created: '2026-05-03'
description: Windstream Holdings is a leading provider of advanced network communications and technology solutions including managed services, cloud computing, and broadband to consumers and businesses across the United States. The company operates the Kinetic broadband brand for consumer and small business customers and Windstream Enterprise (now Uniti Solutions) for business customers, offering SD-WAN, UCaaS, OfficeSuite UC, contact center services, and high-capacity network transport. Windstream delivers voice, data, and managed networking solutions to more than 18 states with over 2.1 million fiber-to-the-premise passings.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 14
  name: Windstream Holdings Context
  property_count: 13
  slug: windstream-holdings-context
layout: provider
modified: '2026-05-03'
name: Windstream Holdings
rules:
- name: Windstream Holdings API Rules
  rule_count: 9
  severity_counts:
    error: 5
    hint: 0
    info: 2
    warn: 2
  slug: windstream-holdings-rules
skills: []
slug: windstream-holdings
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: windstream-holdings\nname: Windstream Holdings\ndescription: >-\n  Windstream Holdings is a leading provider of advanced network communications and\n  technology solutions including managed services, cloud computing, and broadband\n  to consumers and businesses across the United States. The company operates the\n  Kinetic broadband brand for consumer and small business customers and Windstream\n  Enterprise (now Uniti Solutions) for business customers, offering SD-WAN, UCaaS,\n  OfficeSuite UC, contact center services, and high-capacity network transport.\n  Windstream delivers voice, data, and managed networking solutions to more than\n  18 states with over 2.1 million fiber-to-the-premise passings.\ntype: Index\nposition: Producer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Broadband\n  - Contact Center\n  - Managed Services\n  - Network Communications\n  - SD-WAN\n  - Telecom\n  - UCaaS\n  - Unified\
  \ Communications\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: windstream-holdings:windstream-voice-api\n    name: Windstream Enterprise Voice API\n    description: >-\n      The Windstream Enterprise Voice API (silhouette) is a REST-based web service\n      with WebSocket support for real-time events. It enables developers to make and\n      receive calls, manage auto-attendants, control call routing, and configure\n      Unified Communications settings for OfficeSuite UC deployments. The API\n      accepts and delivers content in JSON format following HAL specifications.\n    humanURL: https://api.solutions.uniti.com/voice.html\n    baseURL: https://webadmin.windstreamenterprise.com/api\n    tags:\n      - Voice\n      - UC\n      - Calls\n      - Auto-attendants\n      - OfficeSuite\n    properties:\n      - type: Documentation\n       \
  \ url: https://api.solutions.uniti.com/voice.html\n      - type: Portal\n        url: https://api.solutions.uniti.com/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/openapi/windstream-voice-openapi.yml\n  - aid: windstream-holdings:windstream-contact-center-api\n    name: Windstream Enterprise Contact Center Services API\n    description: >-\n      The Windstream Enterprise Contact Center Services (CCS) API provides programmatic\n      access to contact center operations, enabling developers to route calls, web chats,\n      and text messages, manage agent states, configure tenants, and monitor queue\n      activity. The REST API is complemented by a WebSocket interface for real-time\n      event streaming.\n    humanURL: https://api.solutions.uniti.com/ccs.html\n    baseURL: https://ccs.windstreamenterprise.com/6/v2/api\n    tags:\n      - Contact Center\n      - Calls\n      - Agents\n      - Queues\n      -\
  \ UCaaS\n    properties:\n      - type: Documentation\n        url: https://api.solutions.uniti.com/ccs.html\n      - type: Portal\n        url: https://api.solutions.uniti.com/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/openapi/windstream-contact-center-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.windstreamenterprise.com/\n  - type: Portal\n    url: https://api.solutions.uniti.com/\n  - type: DeveloperHub\n    url: https://solutions.uniti.com/developer-hub\n  - type: APIMarketplace\n    url: https://api.solutions.uniti.com/\n  - type: Documentation\n    url: https://api.solutions.uniti.com/\n  - type: SalesforcIntegration\n    url: https://solutions.uniti.com/developer-hub/app-gallery/salesforce-api\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/windstream-enterprise\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/json-ld/windstream-holdings-context.jsonld\n\
  \  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/vocabulary/windstream-holdings-vocabulary.yml\n  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/capabilities/unified-communications.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/apis.yml
tags:
- Broadband
- Contact Center
- Managed Services
- Network Communications
- SD-WAN
- Telecom
- UCaaS
- Unified Communications
url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/apis.yml
use_cases: []
---
