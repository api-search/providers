---
api_count: 6
api_specs:
- filename: symphony-pod-api-openapi.yml
  format: yaml
  label: Symphony Pod API
  slug: symphony-pod-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/openapi/symphony-pod-api-openapi.yml
- filename: agent-openapi-original.yml
  format: yaml
  label: Symphony Agent API
  slug: symphony-agent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/openapi/agent-openapi-original.yml
- filename: authenticator-openapi-original.yml
  format: yaml
  label: Symphony Authenticator API
  slug: symphony-authenticator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/openapi/authenticator-openapi-original.yml
- filename: login-openapi-original.yml
  format: yaml
  label: Symphony Login API
  slug: symphony-login-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/openapi/login-openapi-original.yml
- filename: profile-manager-openapi-original.yml
  format: yaml
  label: Symphony Profile Manager API
  slug: symphony-profile-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/openapi/profile-manager-openapi-original.yml
- filename: community-connect-openapi-original.yml
  format: yaml
  label: Symphony Community Connect API
  slug: symphony-community-connect-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/openapi/community-connect-openapi-original.yml
apis:
- description: The Symphony Pod API provides core platform services including user management, stream (room) management, content export, connection management, security certificates, and presence. Used to build tool
  name: Symphony Pod API
  slug: symphony-pod-api
- description: The Symphony Agent API handles encryption and decryption of messages and content sent to and from bots. Provides message sending, datafeed (real-time event stream), signal management, DLP (Data Loss P
  name: Symphony Agent API
  slug: symphony-agent-api
- description: 'The Symphony Authenticator API enables bots and on-premise processes to authenticate via mutual TLS certificate. Returns session tokens required for all subsequent API calls. Runs on both the Pod and '
  name: Symphony Authenticator API
  slug: symphony-authenticator-api
- description: 'The Symphony Login API enables bots and applications to authenticate using RSA public/private key pairs, producing session tokens and OAuth2-compatible JWT access tokens. Supports bot authentication, '
  name: Symphony Login API
  slug: symphony-login-api
- description: Profile Manager is a microservice to manage user profiles and groups in Symphony. Supports group creation, membership management, and profile retrieval for enterprise directory use cases.
  name: Symphony Profile Manager API
  slug: symphony-profile-manager-api
- description: The Symphony Community Connect API enables cross-company secure messaging and collaboration. Provides onboarding and tenant lookup for users joining Symphony Community Connect (formerly known as Chann
  name: Symphony Community Connect API
  slug: symphony-community-connect-api
capabilities:
- description: 'Workflow capability for Symphony bot automation: authenticate bots, send and receive messages, manage rooms and streams, handle real-time events via datafeed, and monitor signals. Composes the Agent A'
  name: Symphony Bot Messaging
  slug: bot-messaging
common:
- title: ''
  type: Website
  url: https://symphony.com
- title: ''
  type: Developer Documentation
  url: https://docs.developers.symphony.com
- title: ''
  type: API Reference
  url: https://rest-api.symphony.com
- title: ''
  type: Developer Center
  url: https://symphony.com/support/developers/
- title: ''
  type: GitHub
  url: https://github.com/finos/symphony-api-spec
- title: ''
  type: GitHub Organization
  url: https://github.com/SymphonyPlatformSolutions
- title: ''
  type: Authentication
  url: https://docs.developers.symphony.com/bots/authentication
- title: ''
  type: Sandbox
  url: https://developers.symphony.com/
- title: ''
  type: Developer Certification
  url: https://developers.symphony.com/
- title: ''
  type: SDK
  url: https://docs.developers.symphony.com/developer-tools/developer-tools/bdk-2.0
- title: ''
  type: Changelog
  url: https://docs.developers.symphony.com/admin-guide/release-notes
created: '2026-05-03'
description: Symphony is a secure collaboration platform designed for professional teams, particularly in financial services. It provides end-to-end encrypted messaging, voice, video, and workflows for regulated industries. Symphony's developer platform enables bot automation, workflow integrations, and extension apps through a suite of REST APIs including the Pod API, Agent API, Authenticator API, Login API, Profile Manager API, and Community Connect API.
features: []
image: https://symphony.com/favicon.ico
integrations: []
jsonld:
- class_count: 0
  name: Symphony Context
  property_count: 25
  slug: symphony-context
layout: provider
modified: '2026-05-03'
name: Symphony
rules:
- name: Symphony API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 1
    info: 0
    warn: 7
  slug: symphony-rules
skills: []
slug: symphony
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: symphony\nurl: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/apis.yml\nname: Symphony\ndescription: >-\n  Symphony is a secure collaboration platform designed for professional teams,\n  particularly in financial services. It provides end-to-end encrypted messaging,\n  voice, video, and workflows for regulated industries. Symphony's developer\n  platform enables bot automation, workflow integrations, and extension apps\n  through a suite of REST APIs including the Pod API, Agent API, Authenticator API,\n  Login API, Profile Manager API, and Community Connect API.\nimage: https://symphony.com/favicon.ico\ntags:\n  - Collaboration\n  - Communication\n  - Financial Services\n  - Messaging\n  - Secure Communication\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: symphony:symphony-pod-api\n    name: Symphony Pod API\n    description: >-\n      The Symphony Pod API provides core platform services including\
  \ user\n      management, stream (room) management, content export, connection\n      management, security certificates, and presence. Used to build tools that\n      manage and administer Symphony for an organization.\n    humanURL: https://developers.symphony.com/\n    baseURL: https://acme.symphony.com\n    tags:\n      - Certificates\n      - Connections\n      - Messaging\n      - Presence\n      - Rooms\n      - Streams\n      - User Management\n      - Users\n    properties:\n      - type: Documentation\n        url: https://docs.developers.symphony.com/bots/overview-of-rest-api\n      - type: OpenAPI\n        url: openapi/symphony-pod-api-openapi.yml\n  - aid: symphony:symphony-agent-api\n    name: Symphony Agent API\n    description: >-\n      The Symphony Agent API handles encryption and decryption of messages and\n      content sent to and from bots. Provides message sending, datafeed (real-time\n      event stream), signal management, DLP (Data Loss Prevention), and content\n\
  \      sharing operations. Requires the on-premise Agent server to be deployed.\n    humanURL: https://docs.developers.symphony.com/bots/overview-of-rest-api/agent-api\n    baseURL: https://acme.symphony.com\n    tags:\n      - Attachment\n      - Bots\n      - Data Loss Prevention\n      - Datafeed\n      - Encryption\n      - Messaging\n      - Real-Time\n      - Signals\n      - Streams\n    properties:\n      - type: Documentation\n        url: https://docs.developers.symphony.com/bots/overview-of-rest-api/agent-api\n      - type: OpenAPI\n        url: openapi/agent-openapi-original.yml\n  - aid: symphony:symphony-authenticator-api\n    name: Symphony Authenticator API\n    description: >-\n      The Symphony Authenticator API enables bots and on-premise processes to\n      authenticate via mutual TLS certificate. Returns session tokens required for\n      all subsequent API calls. Runs on both the Pod and the Key Manager, and both\n      tokens are needed for full authentication.\n\
  \    humanURL: https://docs.developers.symphony.com/bots/authentication\n    baseURL: https://acme.symphony.com\n    tags:\n      - Authentication\n      - Bots\n      - Certificates\n      - Session\n      - TLS\n    properties:\n      - type: Documentation\n        url: https://docs.developers.symphony.com/bots/authentication\n      - type: OpenAPI\n        url: openapi/authenticator-openapi-original.yml\n  - aid: symphony:symphony-login-api\n    name: Symphony Login API\n    description: >-\n      The Symphony Login API enables bots and applications to authenticate using\n      RSA public/private key pairs, producing session tokens and OAuth2-compatible\n      JWT access tokens. Supports bot authentication, extension app authentication,\n      and delegated user context authentication.\n    humanURL: https://docs.developers.symphony.com/bots/authentication/rsa-authentication\n    baseURL: https://acme.symphony.com\n    tags:\n      - Authentication\n      - Bots\n      - JWT\n     \
  \ - OAuth2\n      - Public Key\n      - RSA\n      - Session\n    properties:\n      - type: Documentation\n        url: https://docs.developers.symphony.com/bots/authentication/rsa-authentication\n      - type: OpenAPI\n        url: openapi/login-openapi-original.yml\n  - aid: symphony:symphony-profile-manager-api\n    name: Symphony Profile Manager API\n    description: >-\n      Profile Manager is a microservice to manage user profiles and groups in\n      Symphony. Supports group creation, membership management, and profile\n      retrieval for enterprise directory use cases.\n    humanURL: https://developers.symphony.com/\n    baseURL: https://acme.symphony.com/profile-manager\n    tags:\n      - Directory\n      - Groups\n      - Profiles\n      - User Management\n      - Users\n    properties:\n      - type: Documentation\n        url: https://developers.symphony.com/\n      - type: OpenAPI\n        url: openapi/profile-manager-openapi-original.yml\n  - aid: symphony:symphony-community-connect-api\n\
  \    name: Symphony Community Connect API\n    description: >-\n      The Symphony Community Connect API enables cross-company secure messaging\n      and collaboration. Provides onboarding and tenant lookup for users joining\n      Symphony Community Connect (formerly known as Channel Connect), enabling\n      organizations to communicate with external partners over encrypted Symphony\n      channels.\n    humanURL: https://docs.developers.symphony.com/symphony-rest-api/connect-api\n    baseURL: https://acme.symphony.com\n    tags:\n      - Collaboration\n      - Community\n      - Onboarding\n      - Tenants\n      - Users\n    properties:\n      - type: Documentation\n        url: https://docs.developers.symphony.com/symphony-rest-api/connect-api\n      - type: OpenAPI\n        url: openapi/community-connect-openapi-original.yml\ncommon:\n  - type: Website\n    url: https://symphony.com\n  - type: Developer Documentation\n    url: https://docs.developers.symphony.com\n  - type: API\
  \ Reference\n    url: https://rest-api.symphony.com\n  - type: Developer Center\n    url: https://symphony.com/support/developers/\n  - type: GitHub\n    url: https://github.com/finos/symphony-api-spec\n  - type: GitHub Organization\n    url: https://github.com/SymphonyPlatformSolutions\n  - type: Authentication\n    url: https://docs.developers.symphony.com/bots/authentication\n  - type: Sandbox\n    url: https://developers.symphony.com/\n  - type: Developer Certification\n    url: https://developers.symphony.com/\n  - type: SDK\n    url: https://docs.developers.symphony.com/developer-tools/developer-tools/bdk-2.0\n  - type: Changelog\n    url: https://docs.developers.symphony.com/admin-guide/release-notes\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/apis.yml
tags:
- Collaboration
- Communication
- Financial Services
- Messaging
- Secure Communication
url: https://raw.githubusercontent.com/api-evangelist/symphony/refs/heads/main/apis.yml
use_cases: []
---
