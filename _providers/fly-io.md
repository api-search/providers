---
api_count: 3
api_specs:
- filename: fly-io-machines-api-openapi.yml
  format: yaml
  label: Fly.io Machines API
  slug: machines-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fly-io/refs/heads/main/openapi/fly-io-machines-api-openapi.yml
- filename: fly-io-extensions-api-openapi.yml
  format: yaml
  label: Fly.io Extensions API
  slug: extensions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fly-io/refs/heads/main/openapi/fly-io-extensions-api-openapi.yml
apis:
- description: The Fly.io Machines API is a low-level REST interface for provisioning and managing Fly Machines, which are fast-booting virtual machines that run on Fly.io's global edge infrastructure. It provides e
  name: Fly.io Machines API
  slug: machines-api
- description: The Fly.io GraphQL API provides a programmatic interface for managing Fly.io platform resources including applications, IP address allocations, organizations, and networking configuration. The endpoin
  name: Fly.io GraphQL API
  slug: graphql-api
- description: The Fly.io Extensions API is a provider-facing HTTP interface that enables third-party services to integrate with the Fly.io platform as extension providers. When a Fly.io user provisions an extension
  name: Fly.io Extensions API
  slug: extensions-api
asyncapis:
- description: The Fly.io Extensions webhook system delivers real-time event notifications in both directions between Fly.io and extension providers. Fly.io sends CloudEvents-format payloads to the provider's regist
  name: Fly.io Extensions Webhook Events
  slug: fly-io-extensions-webhooks-asyncapi
common:
- title: ''
  type: JSONSchema
  url: json-schema/fly-io-machine-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fly-io-volume-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/fly-io-context.jsonld
created: ''
description: Documentation and guides from the team at Fly.io.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Fly Io Context
  property_count: 11
  slug: fly-io-context
layout: provider
modified: '2026-04-28'
name: fly-io
skills: []
slug: fly-io
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fly-io\nurl: https://raw.githubusercontent.com/api-evangelist/fly-io/refs/heads/main/apis.yml\napis:\n  - aid: fly-io:machines-api\n    name: Fly.io Machines API\n    tags:\n      - Deployment\n      - Edge Computing\n      - Infrastructure\n      - Platform\n      - Virtual Machines\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.machines.dev\n    humanURL: https://fly.io/docs/machines/api/\n    properties:\n      - url: https://fly.io/docs/machines/api/\n        type: Documentation\n      - url: https://fly.io/docs/machines/api/working-with-machines-api/\n        type: Documentation\n      - url: openapi/fly-io-machines-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fly.io Machines API is a low-level REST interface for provisioning and managing\n      Fly Machines, which are fast-booting virtual machines that run on Fly.io's global\n      edge infrastructure. It provides endpoints\
  \ for creating, starting, stopping,\n      and destroying Machines, as well as managing Fly Apps, Fly Volumes, and TLS\n      certificates. The API is accessible publicly at https://api.machines.dev or\n      internally within the Fly.io private WireGuard network at http://_api.internal:4280.\n\n  - aid: fly-io:graphql-api\n    name: Fly.io GraphQL API\n    tags:\n      - Deployment\n      - GraphQL\n      - Infrastructure\n      - Networking\n      - Platform\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.fly.io/graphql\n    humanURL: https://api.fly.io/graphql\n    properties:\n      - url: https://api.fly.io/graphql\n        type: Documentation\n    description: >-\n      The Fly.io GraphQL API provides a programmatic interface for managing Fly.io\n      platform resources including applications, IP address allocations, organizations,\n      and networking configuration. The endpoint is available at https://api.fly.io/graphql\n\
  \      and includes an interactive GraphiQL explorer with schema introspection and\n      documentation tabs accessible directly in the browser. Authentication requires\n      an Authorization Bearer token, which can be obtained by running `flyctl auth\n      token`.\n\n  - aid: fly-io:extensions-api\n    name: Fly.io Extensions API\n    tags:\n      - Extensions\n      - Integration\n      - Partner\n      - Platform\n      - Provisioning\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://fly.io/docs/reference/extensions_api/\n    properties:\n      - url: https://fly.io/docs/reference/extensions_api/\n        type: Documentation\n      - url: https://fly.io/docs/about/extensions/\n        type: Documentation\n      - url: openapi/fly-io-extensions-api-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/fly-io-extensions-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description:\
  \ >-\n      The Fly.io Extensions API is a provider-facing HTTP interface that enables third-party\n      services to integrate with the Fly.io platform as extension providers. When\n      a Fly.io user provisions an extension via the flyctl CLI, Fly.io forwards the\n      provisioning request to the provider's API with details about the requesting\n      organization, and the provider responds with environment variable configuration\n      that is attached to the target application.\n\ncommon:\n  - type: JSONSchema\n    url: json-schema/fly-io-machine-schema.json\n  - type: JSONSchema\n    url: json-schema/fly-io-volume-schema.json\n  - type: JSON-LD\n    url: json-ld/fly-io-context.jsonld\n\nmodified: '2026-04-28'\ndescription: >-\n  Documentation and guides from the team at Fly.io.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fly-io/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/fly-io/refs/heads/main/apis.yml
use_cases: []
---
