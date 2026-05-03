---
api_count: 2
api_specs:
- filename: pipedream-openapi.yml
  format: yaml
  label: Pipedream REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pipedream/refs/heads/master/openapi/pipedream-openapi.yml
- filename: pipedream-openapi.yml
  format: yaml
  label: Pipedream Connect API
  slug: connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pipedream/refs/heads/master/openapi/pipedream-openapi.yml
apis:
- description: The Pipedream REST API allows developers to programmatically create and manage workflows, event sources, subscriptions, and user resources. The API supports Bearer token authentication via OAuth acces
  name: Pipedream REST API
  slug: rest-api
- description: The Pipedream Connect API is the end-to-end developer toolkit for adding customer-facing integrations to applications and AI agents. It provides managed authentication for 3,000+ APIs, pre-built compo
  name: Pipedream Connect API
  slug: connect-api
common:
- title: ''
  type: Portal
  url: https://pipedream.com/
- title: ''
  type: Documentation
  url: https://pipedream.com/docs
- title: ''
  type: GettingStarted
  url: https://pipedream.com/docs/quickstart/
- title: ''
  type: Authentication
  url: https://pipedream.com/docs/rest-api/auth
- title: ''
  type: Blog
  url: https://pipedream.com/blog/
- title: ''
  type: Changelog
  url: https://pipedream.com/docs/changelog
- title: ''
  type: Status
  url: https://status.pipedream.com/
- title: ''
  type: Support
  url: https://pipedream.com/support
- title: ''
  type: Forum
  url: https://pipedream.com/community/
- title: ''
  type: Pricing
  url: https://pipedream.com/pricing/
- title: ''
  type: SignUp
  url: https://pipedream.com/auth/signup
- title: ''
  type: Login
  url: https://pipedream.com/auth/login
- title: ''
  type: TermsOfService
  url: https://pipedream.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://pipedream.com/privacy
- title: ''
  type: Security
  url: https://pipedream.com/docs/privacy-and-security
- title: ''
  type: GitHubOrg
  url: https://github.com/PipedreamHQ/pipedream
created: '2026-03-03'
description: Pipedream is a developer-centric integration platform allowing custom code and API connections embedded directly into production workflows. Trusted by over one million developers, Pipedream provides 3,000+ integrations, pre-built actions, and support for Node.js, Python, Golang, and Bash, enabling teams to connect APIs, AI, databases, and more.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Pipedream
skills: []
slug: pipedream
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: pipedream\nname: Pipedream\nsegments:\n  - ProCode_API_Composition\n  - Workflows\ndescription: >-\n  Pipedream is a developer-centric integration platform allowing custom code and\n  API connections embedded directly into production workflows. Trusted by over\n  one million developers, Pipedream provides 3,000+ integrations, pre-built\n  actions, and support for Node.js, Python, Golang, and Bash, enabling teams to\n  connect APIs, AI, databases, and more.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - ProCode_API_Composition\n  - Workflows\ncreated: '2026-03-03'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/pipedream/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: pipedream:rest-api\n    name: Pipedream REST API\n    description: >-\n      The Pipedream REST API allows developers to programmatically create and\n  \
  \    manage workflows, event sources, subscriptions, and user resources. The\n      API supports Bearer token authentication via OAuth access tokens or user\n      API keys, pagination with cursors, and filtering with include and exclude\n      parameters.\n    humanURL: https://pipedream.com/docs/rest-api/\n    baseURL: https://api.pipedream.com/v1\n    tags:\n      - Automation\n      - Event Sources\n      - Subscriptions\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://pipedream.com/docs/rest-api/\n      - type: Authentication\n        url: https://pipedream.com/docs/rest-api/auth\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/pipedream/refs/heads/master/openapi/pipedream-openapi.yml\n  - aid: pipedream:connect-api\n    name: Pipedream Connect API\n    description: >-\n      The Pipedream Connect API is the end-to-end developer toolkit for adding\n      customer-facing integrations to applications and AI agents.\
  \ It provides\n      managed authentication for 3,000+ APIs, pre-built components and triggers,\n      a Connect proxy for custom API requests, and usage tracking. Resources are\n      scoped to projects and the API supports production and development\n      environments.\n    humanURL: https://pipedream.com/docs/connect\n    baseURL: https://api.pipedream.com/v1/connect\n    tags:\n      - AI Agents\n      - Connect\n      - Integrations\n      - Managed Auth\n    properties:\n      - type: Documentation\n        url: https://pipedream.com/docs/connect/api-ref\n      - type: GettingStarted\n        url: https://pipedream.com/docs/connect/quickstart\n      - type: SDKs\n        url: https://pipedream.com/docs/connect/api-reference/sdks\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/pipedream/refs/heads/master/openapi/pipedream-openapi.yml\ncommon:\n  - type: Portal\n    url: https://pipedream.com/\n    name: Pipedream Platform\n    description: 'null'\n\
  \  - type: Documentation\n    url: https://pipedream.com/docs\n    name: Pipedream Documentation\n    description: 'null'\n  - type: GettingStarted\n    url: https://pipedream.com/docs/quickstart/\n    name: Workflow Development Quickstart\n    description: 'null'\n  - type: Authentication\n    url: https://pipedream.com/docs/rest-api/auth\n    name: API Authentication\n    description: 'null'\n  - type: Blog\n    url: https://pipedream.com/blog/\n    name: Pipedream Blog\n    description: 'null'\n  - type: Changelog\n    url: https://pipedream.com/docs/changelog\n    name: Product Changelog\n    description: 'null'\n  - type: Status\n    url: https://status.pipedream.com/\n    name: Pipedream Status\n    description: 'null'\n  - type: Support\n    url: https://pipedream.com/support\n    name: Pipedream Support\n    description: 'null'\n  - type: Forum\n    url: https://pipedream.com/community/\n    name: Pipedream Community Forum\n    description: 'null'\n  - type: Pricing\n    url: https://pipedream.com/pricing/\n\
  \    name: Pipedream Pricing\n    description: 'null'\n  - type: SignUp\n    url: https://pipedream.com/auth/signup\n    name: Sign Up\n    description: 'null'\n  - type: Login\n    url: https://pipedream.com/auth/login\n    name: Log In\n    description: 'null'\n  - type: TermsOfService\n    url: https://pipedream.com/terms\n    name: Terms of Service\n    description: 'null'\n  - type: PrivacyPolicy\n    url: https://pipedream.com/privacy\n    name: Privacy Statement\n    description: 'null'\n  - type: Security\n    url: https://pipedream.com/docs/privacy-and-security\n    name: Privacy and Security\n    description: 'null'\n  - type: GitHubOrg\n    url: https://github.com/PipedreamHQ/pipedream\n    name: Pipedream GitHub Repository\n    description: 'null'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/pipedream/refs/heads/main/apis.yml
tags:
- ProCode_API_Composition
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/pipedream/refs/heads/main/apis.yml
use_cases: []
---
