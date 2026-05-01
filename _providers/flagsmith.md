---
api_count: 2
api_specs:
- filename: flagsmith-flags-api-openapi.yml
  format: yaml
  label: Flagsmith Flags API
  slug: flags-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/flagsmith/refs/heads/main/openapi/flagsmith-flags-api-openapi.yml
- filename: flagsmith-admin-api-openapi.yml
  format: yaml
  label: Flagsmith Admin API
  slug: admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/flagsmith/refs/heads/main/openapi/flagsmith-admin-api-openapi.yml
apis:
- description: The Flagsmith Flags API is the public-facing REST API that client-side and server-side SDKs use to retrieve feature flag values and remote configuration for environments and users. It uses a non-secre
  name: Flagsmith Flags API
  slug: flags-api
- description: The Flagsmith Admin API allows developers to programmatically manage all aspects of their Flagsmith projects. Anything that can be done through the Flagsmith dashboard can also be accomplished via thi
  name: Flagsmith Admin API
  slug: admin-api
asyncapis:
- description: Flagsmith provides two types of webhooks for receiving event notifications. Environment webhooks automatically send flag evaluations for identified users whenever an identity's flags are evaluated via
  name: Flagsmith Webhook Events
  slug: flagsmith-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/flagsmith-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/flagsmith-feature-flag-schema.json
created: ''
description: Flagsmith is an open-source feature flag and remote configuration platform that helps developers manage feature flags across web, mobile, and server-side applications.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Flagsmith Context
  property_count: 9
  slug: flagsmith-context
layout: provider
modified: '2026-04-28'
name: flagsmith
skills: []
slug: flagsmith
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: flagsmith\nurl: https://raw.githubusercontent.com/api-evangelist/flagsmith/refs/heads/main/apis.yml\napis:\n  - aid: flagsmith:flags-api\n    name: Flagsmith Flags API\n    tags:\n      - Edge\n      - Feature Flags\n      - Flags\n      - Remote Config\n      - SDKs\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://edge.api.flagsmith.com\n    humanURL: https://docs.flagsmith.com/clients/rest\n    properties:\n      - url: https://docs.flagsmith.com/clients/rest\n        type: Documentation\n      - url: openapi/flagsmith-flags-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Flagsmith Flags API is the public-facing REST API that client-side and\n      server-side SDKs use to retrieve feature flag values and remote\n      configuration for environments and users. It uses a non-secret Environment\n      Key for authentication and is designed to be fast, scalable, and publicly\n      accessible.\
  \ The Edge API endpoint at edge.api.flagsmith.com serves\n      requests from AWS Lambda functions running in data centers near the client,\n      providing low-latency global access to flag evaluations.\n  - aid: flagsmith:admin-api\n    name: Flagsmith Admin API\n    tags:\n      - Administration\n      - Environments\n      - Feature Flags\n      - Projects\n      - Segments\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.flagsmith.com/api/v1\n    humanURL: https://docs.flagsmith.com/integrating-with-flagsmith/flagsmith-api-overview/admin-api\n    properties:\n      - url: https://docs.flagsmith.com/integrating-with-flagsmith/flagsmith-api-overview/admin-api\n        type: Documentation\n      - url: openapi/flagsmith-admin-api-openapi.yml\n        type: OpenAPI\n      - url: asyncapi/flagsmith-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      The Flagsmith Admin API allows developers to programmatically\
  \ manage all\n      aspects of their Flagsmith projects. Anything that can be done through the\n      Flagsmith dashboard can also be accomplished via this API, including\n      creating, updating, and deleting projects, environments, feature flags,\n      segments, and users. It uses a secret Organisation API Token for\n      authentication and provides a Swagger interface at\n      api.flagsmith.com/api/v1/docs for interactive exploration.\ncommon:\n  - type: JSON-LD\n    url: json-ld/flagsmith-context.jsonld\n  - type: JSONSchema\n    url: json-schema/flagsmith-feature-flag-schema.json\nmodified: '2026-04-28'\ndescription: >-\n  Flagsmith is an open-source feature flag and remote configuration platform that\n  helps developers manage feature flags across web, mobile, and server-side applications.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/flagsmith/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/flagsmith/refs/heads/main/apis.yml
use_cases: []
---
