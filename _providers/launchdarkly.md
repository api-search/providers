---
api_count: 3
api_specs:
- filename: launchdarkly-rest-api-openapi.yml
  format: yaml
  label: LaunchDarkly REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/launchdarkly/refs/heads/main/openapi/launchdarkly-rest-api-openapi.yml
- filename: launchdarkly-webhooks-asyncapi.yml
  format: yaml
  label: LaunchDarkly Webhooks API
  slug: webhooks-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/launchdarkly/refs/heads/main/asyncapi/launchdarkly-webhooks-asyncapi.yml
- filename: launchdarkly-relay-proxy-openapi.yml
  format: yaml
  label: LaunchDarkly Relay Proxy
  slug: relay-proxy
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/launchdarkly/refs/heads/main/openapi/launchdarkly-relay-proxy-openapi.yml
apis:
- description: The LaunchDarkly REST API provides programmatic access to the full LaunchDarkly feature management platform. Developers can create, update, and manage feature flags, targeting rules, user segments, pr
  name: LaunchDarkly REST API
  slug: rest-api
- description: The LaunchDarkly Webhooks API allows developers to build custom integrations that subscribe to activity events within LaunchDarkly. When actions occur such as flag changes, project creation, or enviro
  name: LaunchDarkly Webhooks API
  slug: webhooks-api
- description: The LaunchDarkly Relay Proxy is a small Go application that connects to the LaunchDarkly streaming API and proxies that connection to SDK clients within an organization's network. Instead of each serv
  name: LaunchDarkly Relay Proxy
  slug: relay-proxy
asyncapis:
- description: LaunchDarkly sends webhook notifications as HTTP POST requests when changes occur within the platform. The webhook payload format is identical to audit log entries and includes details about what chan
  name: LaunchDarkly Webhooks Events
  slug: launchdarkly-webhooks-asyncapi
common:
- title: ''
  type: JSONSchema
  url: json-schema/launchdarkly-feature-flag-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/launchdarkly-webhook-event-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/launchdarkly-context.jsonld
created: ''
description: LaunchDarkly is a feature management platform that enables development teams to deliver and control software through feature flags, allowing them to test in production and roll out features safely.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Launchdarkly Context
  property_count: 15
  slug: launchdarkly-context
layout: provider
modified: '2026-04-28'
name: launchdarkly
skills: []
slug: launchdarkly
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: launchdarkly\nurl: https://raw.githubusercontent.com/api-evangelist/launchdarkly/refs/heads/main/apis.yml\napis:\n  - aid: launchdarkly:rest-api\n    name: LaunchDarkly REST API\n    tags:\n      - Environments\n      - Experimentation\n      - Feature Flags\n      - Feature Management\n      - Segments\n      - Toggles\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://app.launchdarkly.com/api/v2\n    humanURL: https://apidocs.launchdarkly.com/\n    properties:\n      - url: https://apidocs.launchdarkly.com/\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/launchdarkly-rest-api-openapi.yml\n    description: >-\n      The LaunchDarkly REST API provides programmatic access to the full LaunchDarkly\n      feature management platform. Developers can create, update, and manage feature\n      flags, targeting rules, user segments, projects, environments, and team members.\n      The API also\
  \ supports scheduled flag changes, release pipelines, experimentation,\n      approval workflows, and webhook integrations.\n  - aid: launchdarkly:webhooks-api\n    name: LaunchDarkly Webhooks API\n    tags:\n      - Events\n      - Integrations\n      - Notifications\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://app.launchdarkly.com/api/v2\n    humanURL: https://launchdarkly.com/docs/api/webhooks\n    properties:\n      - url: https://launchdarkly.com/docs/api/webhooks\n        type: Documentation\n      - type: AsyncAPI\n        url: asyncapi/launchdarkly-webhooks-asyncapi.yml\n    description: >-\n      The LaunchDarkly Webhooks API allows developers to build custom\n      integrations that subscribe to activity events within LaunchDarkly.\n      When actions occur such as flag changes, project creation, or\n      environment modifications, LaunchDarkly sends HTTP POST payloads to\n      configured webhook\
  \ URLs. This enables use cases like updating external\n      issue trackers, notifying support systems of feature rollouts, and\n      triggering downstream automation workflows based on feature flag\n      lifecycle events.\n  - aid: launchdarkly:relay-proxy\n    name: LaunchDarkly Relay Proxy\n    tags:\n      - Edge\n      - Infrastructure\n      - Performance\n      - Proxy\n      - Streaming\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://launchdarkly.com/docs/sdk/relay-proxy\n    properties:\n      - url: https://launchdarkly.com/docs/sdk/relay-proxy\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/launchdarkly-relay-proxy-openapi.yml\n    description: >-\n      The LaunchDarkly Relay Proxy is a small Go application that connects to the\n      LaunchDarkly streaming API and proxies that connection to SDK clients within\n      an organization's network. Instead\
  \ of each server making outbound connections\n      to LaunchDarkly's streaming service, multiple servers connect to the local Relay\n      Proxy which maintains a single connection upstream.\ncommon:\n  - type: JSONSchema\n    url: json-schema/launchdarkly-feature-flag-schema.json\n  - type: JSONSchema\n    url: json-schema/launchdarkly-webhook-event-schema.json\n  - type: JSON-LD\n    url: json-ld/launchdarkly-context.jsonld\nmodified: '2026-04-28'\ndescription: >-\n  LaunchDarkly is a feature management platform that enables development teams to\n  deliver and control software through feature flags, allowing them to test in production\n  and roll out features safely.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/launchdarkly/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/launchdarkly/refs/heads/main/apis.yml
use_cases: []
---
