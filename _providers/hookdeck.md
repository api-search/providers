---
api_count: 2
api_specs:
- filename: openapi
  format: yaml
  label: Hookdeck API
  slug: hookdeck-api
  spec_type: OpenAPI
  url: https://api.hookdeck.com/2025-07-01/openapi
apis:
- description: 'The Hookdeck REST API provides programmatic access to the Hookdeck Event Gateway platform. It enables management of sources, destinations, connections, transformations, events, attempts, metrics, and '
  name: Hookdeck API
  slug: hookdeck-api
- description: From webhooks to external event streams, Hookdeck ensures every event is received, processed, and monitored reliably at scale, giving you complete visibility and control.
  name: Hookdeck
  slug: hookdeck
common:
- title: ''
  type: Documentation
  url: https://hookdeck.com/docs
- title: ''
  type: APIReference
  url: https://hookdeck.com/docs/api
- title: ''
  type: OpenAPI
  url: https://api.hookdeck.com/2025-07-01/openapi
- title: ''
  type: GettingStarted
  url: https://hookdeck.com/docs/hookdeck-basics
- title: ''
  type: Authentication
  url: https://hookdeck.com/docs/authentication
- title: ''
  type: Pricing
  url: https://hookdeck.com/pricing
- title: ''
  type: Blog
  url: https://hookdeck.com/blog
- title: ''
  type: CLI
  url: https://hookdeck.com/docs/cli
- title: ''
  type: CLI
  url: https://github.com/hookdeck/hookdeck-cli
- title: ''
  type: SignUp
  url: https://dashboard.hookdeck.com/signup
- title: ''
  type: Login
  url: https://dashboard.hookdeck.com/signin
- title: ''
  type: StatusPage
  url: https://status.hookdeck.com/
- title: ''
  type: Contact
  url: https://hookdeck.com/contact
- title: ''
  type: About
  url: https://hookdeck.com/company
- title: ''
  type: Customers
  url: https://hookdeck.com/customers
- title: ''
  type: GitHubOrganization
  url: https://github.com/hookdeck
- title: ''
  type: GitHubRepository
  url: https://github.com/hookdeck/hookdeck-api-schema
- title: ''
  type: GitHubRepository
  url: https://github.com/hookdeck/hookdeck-typescript-sdk
- title: ''
  type: GitHubRepository
  url: https://github.com/hookdeck/hookdeck-go-sdk
- title: ''
  type: SDK
  url: https://www.npmjs.com/package/@hookdeck/sdk
- title: ''
  type: TerraformProvider
  url: https://registry.terraform.io/providers/hookdeck/hookdeck/latest/docs
- title: ''
  type: Quickstart
  url: https://hookdeck.com/docs/use-cases/receive-webhooks/quickstart
- title: ''
  type: Documentation
  url: https://hookdeck.com/docs/use-cases/send-webhooks
- title: ''
  type: TermsOfService
  url: https://hookdeck.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://hookdeck.com/privacy
- title: ''
  type: Security
  url: https://trust.hookdeck.com
- title: ''
  type: DataProcessingAddendum
  url: https://hookdeck.com/dpa
- title: ''
  type: X
  url: https://x.com/Hookdeck
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/hookdeck
- title: ''
  type: Slack
  url: https://join.slack.com/t/hookdeckdevelopers/shared_invite/zt-yw7hlyzp-EQuO3QvdiBlH9Tz2KZg5MQ
- title: ''
  type: Documentation
  url: https://hookdeck.com/event-gateway
- title: ''
  type: Documentation
  url: https://hookdeck.com/outpost
- title: ''
  type: Careers
  url: https://hookdeck.com/careers
created: '2025-08-19'
description: Hookdeck is a powerful tool that helps businesses streamline their webhook workflows. With Hookdeck, users can easily manage, monitor, and debug all of their webhooks in one centralized platform. By providing real-time notifications, detailed logs, and error handling capabilities, Hookdeck simplifies the process of integrating and testing webhooks.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Hookdeck
skills: []
slug: hookdeck
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: hookdeck\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/hookdeck/refs/heads/main/apis.yml\napis:\n  - aid: hookdeck:hookdeck-api\n    name: Hookdeck API\n    tags:\n      - Connections\n      - Destinations\n      - Event Gateways\n      - Events\n      - Gateways\n      - Metrics\n      - Sources\n      - Transformations\n      - Webhooks\n    baseURL: https://api.hookdeck.com\n    humanURL: https://hookdeck.com/docs/api\n    properties:\n      - url: https://hookdeck.com/docs/api\n        type: Documentation\n      - url: https://api.hookdeck.com/2025-07-01/openapi\n        type: OpenAPI\n      - url: https://hookdeck.com/docs/authentication\n        type: Authentication\n      - url: https://hookdeck.com/docs/hookdeck-basics\n        type: GettingStarted\n    description: >-\n      The Hookdeck REST API provides programmatic access to the Hookdeck Event\n      Gateway platform. It enables management of sources, destinations,\n      connections, transformations,\
  \ events, attempts, metrics, and more.\n      Authentication is via Bearer token or Basic auth using your project API\n      key. The API uses date-based versioning in the base URL path.\n  - aid: hookdeck:hookdeck\n    name: Hookdeck\n    tags:\n      - Event Gateways\n      - Gateways\n      - Webhooks\n    humanURL: ' https://hookdeck.com/'\n    properties:\n      - url: ' https://hookdeck.com/'\n        type: Documentation\n    description: >-\n      From webhooks to external event streams, Hookdeck ensures every event is\n      received, processed, and monitored reliably at scale, giving you complete\n      visibility and control.\nname: Hookdeck\ntags:\n  - Event Gateways\n  - Gateways\n  - Webhooks\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-08-19'\nmodified: '2026-04-28'\nposition: Consumer\nsegments:\n  - Gateways\ndescription: >-\n  Hookdeck is a powerful tool that helps businesses streamline\
  \ their webhook workflows.\n  With Hookdeck, users can easily manage, monitor, and debug all of their webhooks\n  in one centralized platform. By providing real-time notifications, detailed logs,\n  and error handling capabilities, Hookdeck simplifies the process of integrating\n  and testing webhooks.\ncommon:\n  - url: https://hookdeck.com/docs\n    type: Documentation\n  - url: https://hookdeck.com/docs/api\n    type: APIReference\n  - url: https://api.hookdeck.com/2025-07-01/openapi\n    type: OpenAPI\n  - url: https://hookdeck.com/docs/hookdeck-basics\n    type: GettingStarted\n  - url: https://hookdeck.com/docs/authentication\n    type: Authentication\n  - url: https://hookdeck.com/pricing\n    type: Pricing\n  - url: https://hookdeck.com/blog\n    type: Blog\n  - url: https://hookdeck.com/docs/cli\n    type: CLI\n  - url: https://github.com/hookdeck/hookdeck-cli\n    type: CLI\n  - url: https://dashboard.hookdeck.com/signup\n    type: SignUp\n  - url: https://dashboard.hookdeck.com/signin\n\
  \    type: Login\n  - url: https://status.hookdeck.com/\n    type: StatusPage\n  - url: https://hookdeck.com/contact\n    type: Contact\n  - url: https://hookdeck.com/company\n    type: About\n  - url: https://hookdeck.com/customers\n    type: Customers\n  - url: https://github.com/hookdeck\n    type: GitHubOrganization\n  - url: https://github.com/hookdeck/hookdeck-api-schema\n    type: GitHubRepository\n  - url: https://github.com/hookdeck/hookdeck-typescript-sdk\n    type: GitHubRepository\n  - url: https://github.com/hookdeck/hookdeck-go-sdk\n    type: GitHubRepository\n  - url: https://www.npmjs.com/package/@hookdeck/sdk\n    type: SDK\n  - url: https://registry.terraform.io/providers/hookdeck/hookdeck/latest/docs\n    type: TerraformProvider\n  - url: https://hookdeck.com/docs/use-cases/receive-webhooks/quickstart\n    type: Quickstart\n  - url: https://hookdeck.com/docs/use-cases/send-webhooks\n    type: Documentation\n  - url: https://hookdeck.com/terms\n    type: TermsOfService\n\
  \  - url: https://hookdeck.com/privacy\n    type: PrivacyPolicy\n  - url: https://trust.hookdeck.com\n    type: Security\n  - url: https://hookdeck.com/dpa\n    type: DataProcessingAddendum\n  - url: https://x.com/Hookdeck\n    type: X\n  - url: https://www.linkedin.com/company/hookdeck\n    type: LinkedIn\n  - url: https://join.slack.com/t/hookdeckdevelopers/shared_invite/zt-yw7hlyzp-EQuO3QvdiBlH9Tz2KZg5MQ\n    type: Slack\n  - url: https://hookdeck.com/event-gateway\n    type: Documentation\n  - url: https://hookdeck.com/outpost\n    type: Documentation\n  - url: https://hookdeck.com/careers\n    type: Careers\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hookdeck/refs/heads/main/apis.yml
tags:
- Event Gateways
- Gateways
- Webhooks
url: https://raw.githubusercontent.com/api-evangelist/hookdeck/refs/heads/main/apis.yml
use_cases: []
---
