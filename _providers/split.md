---
api_count: 8
api_specs:
- filename: split-admin-api-openapi.yml
  format: yaml
  label: Split Admin API
  slug: split-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/openapi/split-admin-api-openapi.yml
- filename: split-feature-flag-api-openapi.yml
  format: yaml
  label: Split Feature Flag API
  slug: split-feature-flag-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/openapi/split-feature-flag-api-openapi.yml
- filename: split-evaluator-api-openapi.yml
  format: yaml
  label: Split Evaluator API
  slug: split-evaluator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/openapi/split-evaluator-api-openapi.yml
apis:
- description: 'The Split Admin API is a REST API that enables programmatic management of workspaces (projects), environments, traffic types, attributes, users, groups, API keys, and change requests within the Split '
  name: Split Admin API
  slug: split-admin-api
- description: The Split Feature Flag API provides endpoints for creating, editing, and deleting feature flags (splits) and their definitions within specific environments. Developers can use this API to define treat
  name: Split Feature Flag API
  slug: split-feature-flag-api
- description: The Split Evaluator is an HTTP service that wraps Split SDKs to provide feature flag evaluation via a REST API. It enables applications that cannot directly embed an SDK to request treatment evaluatio
  name: Split Evaluator API
  slug: split-evaluator-api
- description: The Split JavaScript SDK provides client-side integration for feature flag evaluation in browser-based applications. It handles real-time feature flag synchronization, treatment evaluation, event trac
  name: Split JavaScript SDK
  slug: split-javascript-sdk
- description: The Split Node.js SDK enables server-side feature flag evaluation for Node.js applications with local evaluation, automatic synchronization, event tracking, and impression logging.
  name: Split Node.js SDK
  slug: split-nodejs-sdk
- description: The Split Java SDK provides server-side feature flag evaluation for Java and JVM-based applications with local treatment evaluation and streaming updates.
  name: Split Java SDK
  slug: split-java-sdk
- description: The Split Python SDK enables server-side feature flag evaluation for Python applications, suitable for Django, Flask, and other frameworks.
  name: Split Python SDK
  slug: split-python-sdk
- description: The Split React SDK provides React-specific components and hooks for integrating feature flags including a SplitProvider context, useTreatments hooks, and conditional rendering components.
  name: Split React SDK
  slug: split-react-sdk
capabilities:
- description: 'Unified capability for managing Split feature flags across the full lifecycle: creating and configuring flags, managing targeting rules and segments, controlling environments, administering users and '
  name: Split Feature Flag Management
  slug: feature-flag-management
common:
- title: ''
  type: Portal
  url: https://docs.split.io/reference/introduction
- title: ''
  type: Documentation
  url: https://help.split.io/hc/en-us
- title: ''
  type: Website
  url: https://www.split.io/
- title: ''
  type: PrivacyPolicy
  url: https://www.harness.io/legal/privacy
- title: ''
  type: TermsOfService
  url: https://www.harness.io/legal/terms-of-use
- title: ''
  type: Blog
  url: https://www.split.io/blog/
- title: ''
  type: Login
  url: https://app.split.io/login
- title: ''
  type: JSONSchema
  url: json-schema/split-feature-flag-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/split-feature-flag-definition-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/split-segment-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/split-feature-flag-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/split-feature-flag-definition-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/split-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/split-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/feature-flag-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/split-vocabulary.yml
created: '2026-03-20'
description: Split, now part of Harness Feature Management and Experimentation, is a feature flag and experimentation platform that enables teams to safely release features with controlled rollouts and measure their impact. Their developer platform provides REST APIs for managing feature flags, environments, segments, and workspaces, along with SDKs for evaluating feature flags across multiple languages and platforms.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Split Context
  property_count: 11
  slug: split-context
layout: provider
modified: '2026-05-02'
name: Split
rules:
- name: Split API Rules
  rule_count: 11
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 5
  slug: split-rules
skills: []
slug: split
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: split\nname: Split\ndescription: >-\n  Split, now part of Harness Feature Management and Experimentation, is a feature\n  flag and experimentation platform that enables teams to safely release features\n  with controlled rollouts and measure their impact. Their developer platform\n  provides REST APIs for managing feature flags, environments, segments, and\n  workspaces, along with SDKs for evaluating feature flags across multiple\n  languages and platforms.\nurl: https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/apis.yml\ncreated: '2026-03-20'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Experimentation\n  - Feature Flags\n  - Feature Management\n  - Rollouts\n  - SDKs\napis:\n  - aid: split:split-admin-api\n    name: Split Admin API\n    description: >-\n      The Split Admin API is a REST API that enables programmatic management of\n      workspaces (projects), environments, traffic types, attributes, users,\n \
  \     groups, API keys, and change requests within the Split platform (now Harness\n      Feature Management and Experimentation). The API uses resource-oriented URLs,\n      returns JSON responses, and requires Admin API keys for authentication.\n      All endpoints are prefixed with /internal/api/v2 on the api.split.io host.\n    humanURL: https://docs.split.io/reference/introduction\n    tags:\n      - Administration\n      - Experimentation\n      - Feature Flags\n      - Feature Management\n    properties:\n      - type: Documentation\n        url: https://docs.split.io/reference/introduction\n      - type: OpenAPI\n        url: openapi/split-admin-api-openapi.yml\n      - type: JSONStructure\n        url: json-structure/split-feature-flag-structure.json\n\n  - aid: split:split-feature-flag-api\n    name: Split Feature Flag API\n    description: >-\n      The Split Feature Flag API provides endpoints for creating, editing, and\n      deleting feature flags (splits) and their definitions\
  \ within specific\n      environments. Developers can use this API to define treatments, configure\n      targeting rules, set percentage-based rollouts, and manage feature flag\n      lifecycles programmatically.\n    humanURL: https://docs.split.io/reference/feature-flag-overview\n    tags:\n      - Feature Flags\n      - Rollouts\n      - Targeting\n      - Treatments\n    properties:\n      - type: Documentation\n        url: https://docs.split.io/reference/feature-flag-overview\n      - type: OpenAPI\n        url: openapi/split-feature-flag-api-openapi.yml\n      - type: JSONStructure\n        url: json-structure/split-feature-flag-definition-structure.json\n\n  - aid: split:split-evaluator-api\n    name: Split Evaluator API\n    description: >-\n      The Split Evaluator is an HTTP service that wraps Split SDKs to provide\n      feature flag evaluation via a REST API. It enables applications that cannot\n      directly embed an SDK to request treatment evaluations over HTTP, making\
  \ it\n      suitable for architectures where a centralized evaluation service is preferred.\n    humanURL: https://help.split.io/hc/en-us/articles/360020037072-Split-Evaluator\n    tags:\n      - Evaluation\n      - Feature Flags\n      - Microservices\n      - Treatments\n    properties:\n      - type: Documentation\n        url: https://help.split.io/hc/en-us/articles/360020037072-Split-Evaluator\n      - type: OpenAPI\n        url: openapi/split-evaluator-api-openapi.yml\n\n  - aid: split:split-javascript-sdk\n    name: Split JavaScript SDK\n    description: >-\n      The Split JavaScript SDK provides client-side integration for feature flag\n      evaluation in browser-based applications. It handles real-time feature flag\n      synchronization, treatment evaluation, event tracking, and impression management.\n    humanURL: https://help.split.io/hc/en-us/articles/360020448791-JavaScript-SDK\n    tags:\n      - Browser\n      - Feature Flags\n      - JavaScript\n      - SDK\n    properties:\n\
  \      - type: Documentation\n        url: https://help.split.io/hc/en-us/articles/360020448791-JavaScript-SDK\n\n  - aid: split:split-nodejs-sdk\n    name: Split Node.js SDK\n    description: >-\n      The Split Node.js SDK enables server-side feature flag evaluation for Node.js\n      applications with local evaluation, automatic synchronization, event tracking,\n      and impression logging.\n    humanURL: https://help.split.io/hc/en-us/articles/360020564931-Node-js-SDK\n    tags:\n      - Feature Flags\n      - Node.js\n      - SDK\n      - Server Side\n    properties:\n      - type: Documentation\n        url: https://help.split.io/hc/en-us/articles/360020564931-Node-js-SDK\n\n  - aid: split:split-java-sdk\n    name: Split Java SDK\n    description: >-\n      The Split Java SDK provides server-side feature flag evaluation for Java and\n      JVM-based applications with local treatment evaluation and streaming updates.\n    humanURL: https://help.split.io/hc/en-us/articles/360020405151-Java-SDK\n\
  \    tags:\n      - Feature Flags\n      - Java\n      - SDK\n      - Server Side\n    properties:\n      - type: Documentation\n        url: https://help.split.io/hc/en-us/articles/360020405151-Java-SDK\n\n  - aid: split:split-python-sdk\n    name: Split Python SDK\n    description: >-\n      The Split Python SDK enables server-side feature flag evaluation for Python\n      applications, suitable for Django, Flask, and other frameworks.\n    humanURL: https://help.split.io/hc/en-us/articles/360020359652-Python-SDK\n    tags:\n      - Feature Flags\n      - Python\n      - SDK\n      - Server Side\n    properties:\n      - type: Documentation\n        url: https://help.split.io/hc/en-us/articles/360020359652-Python-SDK\n\n  - aid: split:split-react-sdk\n    name: Split React SDK\n    description: >-\n      The Split React SDK provides React-specific components and hooks for integrating\n      feature flags including a SplitProvider context, useTreatments hooks, and\n      conditional rendering\
  \ components.\n    humanURL: https://help.split.io/hc/en-us/articles/360038825091-React-SDK\n    tags:\n      - Feature Flags\n      - Frontend\n      - JavaScript\n      - React\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://help.split.io/hc/en-us/articles/360038825091-React-SDK\n\ncommon:\n  - type: Portal\n    url: https://docs.split.io/reference/introduction\n  - type: Documentation\n    url: https://help.split.io/hc/en-us\n  - type: Website\n    url: https://www.split.io/\n  - type: PrivacyPolicy\n    url: https://www.harness.io/legal/privacy\n  - type: TermsOfService\n    url: https://www.harness.io/legal/terms-of-use\n  - type: Blog\n    url: https://www.split.io/blog/\n  - type: Login\n    url: https://app.split.io/login\n  - type: JSONSchema\n    url: json-schema/split-feature-flag-schema.json\n  - type: JSONSchema\n    url: json-schema/split-feature-flag-definition-schema.json\n  - type: JSONSchema\n    url: json-schema/split-segment-schema.json\n\
  \  - type: JSONStructure\n    url: json-structure/split-feature-flag-structure.json\n  - type: JSONStructure\n    url: json-structure/split-feature-flag-definition-structure.json\n  - type: JSON-LD\n    url: json-ld/split-context.jsonld\n  - type: SpectralRules\n    url: rules/split-rules.yml\n  - type: Capabilities\n    url: capabilities/feature-flag-management.yaml\n  - type: Vocabulary\n    url: vocabulary/split-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/apis.yml
tags:
- Experimentation
- Feature Flags
- Feature Management
- Rollouts
- SDKs
url: https://raw.githubusercontent.com/api-evangelist/split/refs/heads/main/apis.yml
use_cases: []
---
