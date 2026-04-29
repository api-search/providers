---
api_count: 2
apis:
- description: 'The Bubble Data API allows external services to read, create, update, and delete data stored in Bubble apps via REST endpoints. The API supports authentication via API keys and exposes app data types '
  name: Bubble Data API
  slug: bubble-data-api
- description: The Bubble Workflow API enables external systems to trigger backend workflows in a Bubble app via HTTP requests. Workflows can receive data, execute business logic, and return results, supporting inte
  name: Bubble Workflow API
  slug: bubble-workflow-api
common:
- title: ''
  type: Website
  url: https://bubble.io
- title: ''
  type: Portal
  url: https://manual.bubble.io/core-resources/api
- title: ''
  type: Documentation
  url: https://manual.bubble.io
- title: ''
  type: GettingStarted
  url: https://manual.bubble.io/core-resources/api
- title: ''
  type: Pricing
  url: https://bubble.io/pricing
- title: ''
  type: TermsOfService
  url: https://bubble.io/terms
- title: ''
  type: PrivacyPolicy
  url: https://bubble.io/privacy
- title: ''
  type: SignUp
  url: https://bubble.io/signup
- title: ''
  type: Login
  url: https://bubble.io/login
- title: ''
  type: Forum
  url: https://forum.bubble.io
- title: ''
  type: Blog
  url: https://bubble.io/blog
created: '2024-11-13'
description: Bubble is an AI-powered no-code development platform that enables individuals and teams to design and launch scalable web applications without writing code. Bubble provides a visual programming environment for building database-backed applications, marketplaces, SaaS tools, and enterprise applications. The platform includes API connector capabilities for integrating with external services via REST APIs, webhooks, and data APIs to expose app data programmatically.
features: []
image: ''
integrations: []
layout: provider
modified: '2026-04-21'
name: Bubble
skills: []
slug: bubbles
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bubbles\nname: Bubble\nurl: https://raw.githubusercontent.com/api-evangelist/bubbles/refs/heads/main/apis.yml\ndescription: >-\n  Bubble is an AI-powered no-code development platform that enables individuals and teams\n  to design and launch scalable web applications without writing code. Bubble provides a\n  visual programming environment for building database-backed applications, marketplaces,\n  SaaS tools, and enterprise applications. The platform includes API connector capabilities\n  for integrating with external services via REST APIs, webhooks, and data APIs to expose\n  app data programmatically.\ntags:\n  - Applications\n  - Low Code\n  - No Code\n  - Visual Programming\n  - Webhooks\n  - Web Apps\nx-type: company\ntype: Contract\naccess: 3rd-Party\nposition: Consuming\nspecificationVersion: '0.19'\napis:\n  - aid: bubbles:bubble-data-api\n    name: Bubble Data API\n    description: >-\n      The Bubble Data API allows external services to read, create, update,\
  \ and delete\n      data stored in Bubble apps via REST endpoints. The API supports authentication via\n      API keys and exposes app data types as addressable resources for integration with\n      third-party tools and services.\n    humanURL: https://manual.bubble.io/core-resources/api/the-bubble-api/the-data-api\n    baseURL: https://{app-name}.bubbleapps.io/api/1.1\n    tags:\n      - Data\n      - REST\n    properties:\n      - type: Documentation\n        url: https://manual.bubble.io/core-resources/api/the-bubble-api/the-data-api\n      - type: Authentication\n        url: https://manual.bubble.io/core-resources/api/the-bubble-api/authentication\n\n  - aid: bubbles:bubble-workflow-api\n    name: Bubble Workflow API\n    description: >-\n      The Bubble Workflow API enables external systems to trigger backend workflows in a\n      Bubble app via HTTP requests. Workflows can receive data, execute business logic,\n      and return results, supporting integration scenarios such as\
  \ webhooks, automation\n      triggers, and server-to-server communication.\n    humanURL: https://manual.bubble.io/core-resources/api/the-bubble-api/the-workflow-api\n    baseURL: https://{app-name}.bubbleapps.io/api/1.1/wf\n    tags:\n      - Automation\n      - Triggers\n      - Webhooks\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://manual.bubble.io/core-resources/api/the-bubble-api/the-workflow-api\n\ncommon:\n  - type: Website\n    url: https://bubble.io\n  - type: Portal\n    url: https://manual.bubble.io/core-resources/api\n  - type: Documentation\n    url: https://manual.bubble.io\n  - type: GettingStarted\n    url: https://manual.bubble.io/core-resources/api\n  - type: Pricing\n    url: https://bubble.io/pricing\n  - type: TermsOfService\n    url: https://bubble.io/terms\n  - type: PrivacyPolicy\n    url: https://bubble.io/privacy\n  - type: SignUp\n    url: https://bubble.io/signup\n  - type: Login\n    url: https://bubble.io/login\n \
  \ - type: Forum\n    url: https://forum.bubble.io\n  - type: Blog\n    url: https://bubble.io/blog\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n\ncreated: '2024-11-13'\nmodified: '2026-04-21'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bubbles/refs/heads/main/apis.yml
tags:
- Applications
- Low Code
- No Code
- Visual Programming
- Webhooks
- Web Apps
url: https://raw.githubusercontent.com/api-evangelist/bubbles/refs/heads/main/apis.yml
use_cases: []
---
