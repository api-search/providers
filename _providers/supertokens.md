---
api_count: 1
api_specs:
- filename: supertokens-core-driver-interface-openapi.yml
  format: yaml
  label: SuperTokens Core Driver Interface
  slug: core-driver-interface
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/openapi/supertokens-core-driver-interface-openapi.yml
apis:
- description: The Core Driver Interface (CDI) is the REST API exposed by the supertokens-core HTTP service. Backend SDKs (Node.js, Python, Go) communicate with the core via this API to perform authentication operat
  name: SuperTokens Core Driver Interface
  slug: core-driver-interface
capabilities:
- description: Unified authentication workflow combining all SuperTokens Core authentication capabilities. Covers session management, email/password auth, passwordless OTP and magic links, third-party OAuth (Google,
  name: SuperTokens Authentication
  slug: authentication
common:
- title: ''
  type: Website
  url: https://supertokens.com
- title: ''
  type: Documentation
  url: https://supertokens.com/docs
- title: ''
  type: GitHub Organization
  url: https://github.com/supertokens
- title: ''
  type: GitHub Repository
  url: https://github.com/supertokens/supertokens-core
- title: ''
  type: SDK Node.js
  url: https://github.com/supertokens/supertokens-node
- title: ''
  type: SDK Python
  url: https://github.com/supertokens/supertokens-python
- title: ''
  type: SDK Go
  url: https://github.com/supertokens/supertokens-golang
- title: ''
  type: SDK React
  url: https://github.com/supertokens/supertokens-web-js
- title: ''
  type: SDK Flutter
  url: https://github.com/supertokens/supertokens-flutter
- title: ''
  type: Changelog
  url: https://github.com/supertokens/supertokens-core/blob/master/CHANGELOG.md
- title: ''
  type: Issues
  url: https://github.com/supertokens/supertokens-core/issues
created: '2026-03-25'
description: SuperTokens is an open source authentication solution providing session management, social login, email/password auth, and passwordless flows for web and mobile apps. It is an open source alternative to Auth0, Firebase Auth, and AWS Cognito. SuperTokens exposes a Core Driver Interface (CDI) HTTP API for backend SDKs to communicate with the supertokens-core service, as well as a Frontend Driver Interface (FDI) for frontend SDK interaction. Available SDKs cover Node.js, Python, Go, Java, React, Flutter, iOS, and Android.
features: []
image: ''
integrations: []
jsonld:
- class_count: 7
  name: Supertokens Context
  property_count: 11
  slug: supertokens-context
layout: provider
modified: '2026-05-02'
name: SuperTokens
rules:
- name: SuperTokens API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 5
  slug: supertokens-cdi-rules
skills: []
slug: supertokens
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: supertokens\nname: SuperTokens\ndescription: >-\n  SuperTokens is an open source authentication solution providing session management,\n  social login, email/password auth, and passwordless flows for web and mobile apps.\n  It is an open source alternative to Auth0, Firebase Auth, and AWS Cognito. SuperTokens\n  exposes a Core Driver Interface (CDI) HTTP API for backend SDKs to communicate with\n  the supertokens-core service, as well as a Frontend Driver Interface (FDI) for frontend\n  SDK interaction. Available SDKs cover Node.js, Python, Go, Java, React, Flutter,\n  iOS, and Android.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Authentication\n  - Open Source\n  - Session Management\n  - Social Login\n  - Passwordless\n  - Identity\n  - Authorization\n  - Multi-Tenancy\n  - Node.js\n  - Self-Hosted\napis:\n  - aid: supertokens:core-driver-interface\n\
  \    name: SuperTokens Core Driver Interface\n    description: >-\n      The Core Driver Interface (CDI) is the REST API exposed by the supertokens-core\n      HTTP service. Backend SDKs (Node.js, Python, Go) communicate with the core via\n      this API to perform authentication operations including session creation, verification,\n      refresh, user sign-up/sign-in, email verification, password reset, multi-tenancy,\n      and user metadata management.\n    humanURL: https://github.com/supertokens/core-driver-interface\n    baseURL: https://{supertokens-core-host}:{port}\n    tags:\n      - Authentication\n      - Session Management\n      - Core API\n      - Identity\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://supertokens.com/docs\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/openapi/supertokens-core-driver-interface-openapi.yml\n      - type: GitHub Repository\n       \
  \ url: https://github.com/supertokens/supertokens-core\n      - type: API Specification\n        url: https://github.com/supertokens/core-driver-interface\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/json-schema/supertokens-session-schema.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/json-structure/supertokens-session-structure.json\n      - type: JSONLD\n        url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/json-ld/supertokens-context.jsonld\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/rules/supertokens-cdi-rules.yml\n      - type: NaftikoCapabilities\n        url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/capabilities/authentication.yaml\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/vocabulary/supertokens-vocabulary.yml\n\
  common:\n  - type: Website\n    url: https://supertokens.com\n  - type: Documentation\n    url: https://supertokens.com/docs\n  - type: GitHub Organization\n    url: https://github.com/supertokens\n  - type: GitHub Repository\n    url: https://github.com/supertokens/supertokens-core\n  - type: SDK Node.js\n    url: https://github.com/supertokens/supertokens-node\n  - type: SDK Python\n    url: https://github.com/supertokens/supertokens-python\n  - type: SDK Go\n    url: https://github.com/supertokens/supertokens-golang\n  - type: SDK React\n    url: https://github.com/supertokens/supertokens-web-js\n  - type: SDK Flutter\n    url: https://github.com/supertokens/supertokens-flutter\n  - type: Changelog\n    url: https://github.com/supertokens/supertokens-core/blob/master/CHANGELOG.md\n  - type: Issues\n    url: https://github.com/supertokens/supertokens-core/issues\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/apis.yml
tags:
- Authentication
- Open Source
- Session Management
- Social Login
- Passwordless
- Identity
- Authorization
- Multi-Tenancy
- Node.js
- Self-Hosted
url: https://raw.githubusercontent.com/api-evangelist/supertokens/refs/heads/main/apis.yml
use_cases: []
---
