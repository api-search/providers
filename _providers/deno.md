---
api_count: 6
api_specs:
- filename: deno-deploy-rest-api-openapi.yml
  format: yaml
  label: Deno Deploy REST API
  slug: deploy-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deno/refs/heads/main/openapi/deno-deploy-rest-api-openapi.yml
- filename: deno-deploy-v2-api-openapi.yml
  format: yaml
  label: Deno Deploy API V2
  slug: deploy-v2-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deno/refs/heads/main/openapi/deno-deploy-v2-api-openapi.yml
- filename: deno-subhosting-api-openapi.yml
  format: yaml
  label: Deno Subhosting API
  slug: subhosting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/deno/refs/heads/main/openapi/deno-subhosting-api-openapi.yml
apis:
- description: The Deno Runtime API is the built-in namespace of globals and modules available to all programs running on the Deno JavaScript and TypeScript runtime. It provides access to filesystem operations, netw
  name: Deno Runtime API
  slug: runtime-api
- description: Deno KV is a key-value database built directly into the Deno runtime and available as a globally distributed store on Deno Deploy. It is accessed via the Deno.Kv namespace and supports get, set, delet
  name: Deno KV API
  slug: kv-api
- description: The Deno Deploy REST API provides programmatic access to manage projects and deployments on the Deno Deploy serverless edge platform. It exposes endpoints for creating and managing organizations, proj
  name: Deno Deploy REST API
  slug: deploy-rest-api
- description: The Deno Deploy API v2 is the current generation REST API for managing applications, revisions, layers, and configuration on the Deno Deploy serverless edge platform. It replaces the v1 API (sunsettin
  name: Deno Deploy API V2
  slug: deploy-v2-api
- description: The Deno Subhosting API enables platforms and SaaS products to run untrusted, user-submitted JavaScript and TypeScript code securely on Deno Deploy infrastructure. It shares the same base URL (https:/
  name: Deno Subhosting API
  slug: subhosting-api
- description: The Deno Standard Library is a collection of audited TypeScript modules maintained by the Deno core team and published on JSR under the @std scope. It provides common utilities including HTTP server h
  name: Deno Standard Library
  slug: standard-library
capabilities: []
common:
- title: ''
  type: Website
  url: https://deno.com
- title: ''
  type: Portal
  url: https://dash.deno.com
- title: ''
  type: Documentation
  url: https://docs.deno.com
- title: ''
  type: Blog
  url: https://deno.com/blog
- title: ''
  type: GitHub Organization
  url: https://github.com/denoland
- title: ''
  type: Login
  url: https://dash.deno.com/signin
- title: ''
  type: JSON-LD
  url: json-ld/deno-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/deno-deployment-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/deno-kv-database-schema.json
- title: ''
  type: Vocabulary
  url: vocabulary/deno-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/deno-capabilities.yml
- title: ''
  type: Rules
  url: rules/deno-rules.yml
created: '2026-03-21'
description: Deno is a modern JavaScript and TypeScript runtime built on V8 that emphasizes security, simplicity, and developer productivity. It provides a comprehensive developer platform including the Deno Deploy serverless edge network, a built-in key-value store, and a standard library of audited modules, all designed to run TypeScript natively without additional tooling.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Deno Context
  property_count: 9
  slug: deno-context
layout: provider
modified: '2026-04-28'
name: Deno
rules:
- name: Deno API Rules
  rule_count: 5
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 3
  slug: deno-rules
skills: []
slug: deno
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: deno\nname: Deno\ndescription: >-\n  Deno is a modern JavaScript and TypeScript runtime built on V8 that\n  emphasizes security, simplicity, and developer productivity. It provides a\n  comprehensive developer platform including the Deno Deploy serverless edge\n  network, a built-in key-value store, and a standard library of audited\n  modules, all designed to run TypeScript natively without additional tooling.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Deployment\n  - Edge\n  - JavaScript\n  - Runtime\n  - Serverless\n  - TypeScript\nurl: https://raw.githubusercontent.com/api-evangelist/deno/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: opensource\nposition: Producer\naccess: 3rd-Party\napis:\n  - aid: deno:runtime-api\n    name: Deno Runtime API\n    tags:\n      - JavaScript\n      - Runtime\n      - TypeScript\n      - WebAssembly\n    image:\
  \ https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://docs.deno.com/api/deno/\n    properties:\n      - url: https://docs.deno.com/api/deno/\n        type: Documentation\n      - url: json-schema/deno-deployment-schema.json\n        type: JSONSchema\n    description: >-\n      The Deno Runtime API is the built-in namespace of globals and modules available\n      to all programs running on the Deno JavaScript and TypeScript runtime. It provides\n      access to filesystem operations, networking, process management, cryptography,\n      subprocesses, permissions, and environment variables via the Deno.* namespace.\n      The runtime natively supports TypeScript without additional tooling and implements\n      Web Platform APIs such as fetch, WebSocket, URL, and Web Crypto.\n  - aid: deno:kv-api\n    name: Deno KV API\n    tags:\n      - Database\n      - Edge\n      - Key-Value\n      - Storage\n    image:\
  \ https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.deno.com\n    humanURL: https://docs.deno.com/deploy/kv/\n    properties:\n      - url: https://docs.deno.com/deploy/kv/\n        type: Documentation\n      - url: https://docs.deno.com/api/deno/~/Deno.Kv\n        type: Documentation\n      - url: json-schema/deno-kv-database-schema.json\n        type: JSONSchema\n    description: >-\n      Deno KV is a key-value database built directly into the Deno runtime and available\n      as a globally distributed store on Deno Deploy. It is accessed via the Deno.Kv\n      namespace and supports get, set, delete, list, and atomic transaction operations.\n      Keys are ordered tuples that support hierarchical data modeling, and values\n      can be any structured-serializable JavaScript value including the special Deno.KvU64\n      type for 64-bit unsigned integers.\n  - aid: deno:deploy-rest-api\n    name: Deno Deploy REST API\n    tags:\n   \
  \   - Deployment\n      - Edge\n      - Management\n      - Serverless\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.deno.com/v1\n    humanURL: https://docs.deno.com/deploy/api/rest/\n    properties:\n      - url: https://docs.deno.com/deploy/api/rest/\n        type: Documentation\n      - url: https://apidocs.deno.com/\n        type: Documentation\n      - url: openapi/deno-deploy-rest-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Deno Deploy REST API provides programmatic access to manage projects and\n      deployments on the Deno Deploy serverless edge platform. It exposes endpoints\n      for creating and managing organizations, projects, deployments, domains, and\n      KV databases, as well as retrieving analytics and usage metrics. The API base\n      URL is https://api.deno.com/v1 and uses HTTP Bearer token authentication. An\n      OpenAPI specification is published and can be used with\
  \ OpenAPI-compatible tooling.\n  - aid: deno:deploy-v2-api\n    name: Deno Deploy API V2\n    tags:\n      - Deployment\n      - Edge\n      - Management\n      - Serverless\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.deno.com/v2\n    humanURL: https://api.deno.com/v2/docs\n    properties:\n      - url: https://api.deno.com/v2/docs\n        type: Documentation\n      - url: openapi/deno-deploy-v2-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Deno Deploy API v2 is the current generation REST API for managing applications,\n      revisions, layers, and configuration on the Deno Deploy serverless edge platform.\n      It replaces the v1 API (sunsetting July 20, 2026) with a revised resource model:\n      Apps replace Projects, Revisions replace Deployments, and Layers provide reusable\n      shared configuration across many apps.\n  - aid: deno:subhosting-api\n    name: Deno Subhosting API\n    tags:\n\
  \      - Deployment\n      - Multi-Tenant\n      - Serverless\n      - Subhosting\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.deno.com/v1\n    humanURL: https://docs.deno.com/subhosting/api/\n    properties:\n      - url: https://docs.deno.com/subhosting/api/\n        type: Documentation\n      - url: https://docs.deno.com/subhosting/manual/\n        type: Documentation\n      - url: openapi/deno-subhosting-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Deno Subhosting API enables platforms and SaaS products to run untrusted,\n      user-submitted JavaScript and TypeScript code securely on Deno Deploy infrastructure.\n      It shares the same base URL (https://api.deno.com/v1) and Bearer token authentication\n      as the Deploy REST API but is scoped to subhosting use cases such as provisioning\n      isolated projects per tenant, creating deployments, and managing custom domains\n      and KV\
  \ databases on behalf of end users.\n  - aid: deno:standard-library\n    name: Deno Standard Library\n    tags:\n      - Modules\n      - Standard Library\n      - TypeScript\n      - Utilities\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://docs.deno.com/runtime/fundamentals/standard_library/\n    properties:\n      - url: https://docs.deno.com/runtime/fundamentals/standard_library/\n        type: Documentation\n      - url: https://jsr.io/@std\n        type: Documentation\n    description: >-\n      The Deno Standard Library is a collection of audited TypeScript modules maintained\n      by the Deno core team and published on JSR under the @std scope. It provides\n      common utilities including HTTP server helpers, path manipulation, assertions,\n      CSV and JSON parsing, hashing, encoding, streams, date formatting, and more.\n      All modules are guaranteed to work with the current\
  \ stable Deno release and\n      do not rely on third-party dependencies.\ncommon:\n  - type: Website\n    url: https://deno.com\n  - type: Portal\n    url: https://dash.deno.com\n  - type: Documentation\n    url: https://docs.deno.com\n  - type: Blog\n    url: https://deno.com/blog\n  - type: GitHub Organization\n    url: https://github.com/denoland\n  - type: Login\n    url: https://dash.deno.com/signin\n  - type: JSON-LD\n    url: json-ld/deno-context.jsonld\n  - type: JSONSchema\n    url: json-schema/deno-deployment-schema.json\n  - type: JSONSchema\n    url: json-schema/deno-kv-database-schema.json\n  - type: Vocabulary\n    url: vocabulary/deno-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/deno-capabilities.yml\n  - type: Rules\n    url: rules/deno-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/deno/refs/heads/main/apis.yml
tags:
- Deployment
- Edge
- JavaScript
- Runtime
- Serverless
- TypeScript
url: https://raw.githubusercontent.com/api-evangelist/deno/refs/heads/main/apis.yml
use_cases: []
---
