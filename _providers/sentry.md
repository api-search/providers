---
api_count: 3
api_specs:
- filename: sentry-api-openapi.yml
  format: yaml
  label: Sentry Error Monitoring API
  slug: sentry-error-monitoring-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sentry/refs/heads/main/openapi/sentry-api-openapi.yml
- filename: sentry-webhooks-asyncapi.yml
  format: yaml
  label: Sentry Integration Platform API
  slug: sentry-integration-platform-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/sentry/refs/heads/main/asyncapi/sentry-webhooks-asyncapi.yml
apis:
- description: Sentry provides error monitoring and performance tracking REST APIs for software applications. APIs enable issue management, event retrieval, release tracking, alert configuration, and project adminis
  name: Sentry Error Monitoring API
  slug: sentry-error-monitoring-api
- description: 'Sentry provides official SDKs for 22+ platforms including JavaScript, Python, PHP, .NET, Java, Go, Ruby, Rust, Android, Apple, React Native, Unity, and Unreal Engine. Each SDK provides error capture, '
  name: Sentry SDK API
  slug: sentry-sdk-api
- description: 'The Sentry Integration Platform API enables building public and internal integrations with Sentry. Supports OAuth2 with PKCE, device authorization flow for CLI/CI environments, webhook notifications, '
  name: Sentry Integration Platform API
  slug: sentry-integration-platform-api
asyncapis:
- description: Sentry Integration Platform delivers webhook notifications to registered integrations when events occur in Sentry. Webhooks are sent as HTTP POST requests signed with HMAC-SHA256 using the client secr
  name: Sentry Integration Platform Webhooks
  slug: sentry-webhooks-asyncapi
capabilities:
- description: Unified capability for error monitoring, issue triage, release management, and alerting workflows using the Sentry API. Enables DevOps engineers and SREs to investigate production errors, triage and a
  name: Sentry Error Monitoring
  slug: error-monitoring
common:
- title: ''
  type: Website
  url: https://sentry.io/
- title: ''
  type: Portal
  url: https://docs.sentry.io/api/
- title: ''
  type: Documentation
  url: https://docs.sentry.io/api/
- title: ''
  type: Authentication
  url: https://docs.sentry.io/api/auth/
- title: ''
  type: RateLimits
  url: https://docs.sentry.io/api/ratelimits/
- title: ''
  type: GettingStarted
  url: https://docs.sentry.io/api/guides/create-auth-token/
- title: ''
  type: ChangeLog
  url: https://sentry.io/changelog/
- title: ''
  type: Status
  url: https://status.sentry.io/
- title: ''
  type: TermsOfService
  url: https://sentry.io/terms/
- title: ''
  type: PrivacyPolicy
  url: https://sentry.io/legal/privacy/
- title: ''
  type: Blog
  url: https://sentry.io/blog/
- title: ''
  type: SDKs
  url: https://docs.sentry.io/platforms/
- title: ''
  type: GitHubOrganization
  url: https://github.com/getsentry
- title: ''
  type: DeveloperTools
  url: https://sandbox.sentry.io/
- title: ''
  type: Pricing
  url: https://sentry.io/pricing/
- title: ''
  type: SignUp
  url: https://sentry.io/signup/
- title: ''
  type: Login
  url: https://sentry.io/auth/login/
- title: ''
  type: JSONSchema
  url: json-schema/sentry-issue-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/sentry-context.jsonld
- title: ''
  type: JSONStructure
  url: json-structure/sentry-issue-structure.json
- title: ''
  type: Vocabulary
  url: vocabulary/sentry-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/sentry-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/error-monitoring.yaml
created: '2026-03-18'
description: Sentry is a developer-first application monitoring platform that helps software teams discover, triage, and prioritize errors and performance issues in production. Sentry provides real-time error monitoring, performance tracing, session replay, profiling, and release tracking for web, mobile, and backend applications across 22+ platforms and languages.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Sentry Context
  property_count: 8
  slug: sentry-context
layout: provider
modified: '2026-05-02'
name: Sentry
rules:
- name: Sentry API Rules
  rule_count: 13
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 7
  slug: sentry-rules
skills: []
slug: sentry
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sentry\nname: Sentry\ndescription: >-\n  Sentry is a developer-first application monitoring platform that helps software\n  teams discover, triage, and prioritize errors and performance issues in production.\n  Sentry provides real-time error monitoring, performance tracing, session replay,\n  profiling, and release tracking for web, mobile, and backend applications across\n  22+ platforms and languages.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Error Monitoring\n  - Debugging\n  - Observability\n  - Application Performance Management\n  - Developer Tools\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sentry/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: sentry:sentry-error-monitoring-api\n    name: Sentry Error Monitoring API\n    description: >-\n      Sentry provides error monitoring and performance tracking REST APIs\
  \ for\n      software applications. APIs enable issue management, event retrieval,\n      release tracking, alert configuration, and project administration. All\n      endpoints are scoped to an organization. Current API version is v0.\n    humanURL: https://docs.sentry.io/api/\n    baseURL: https://sentry.io/api/0\n    tags:\n      - Error Monitoring\n      - Debugging\n      - Observability\n      - Application Performance Management\n    properties:\n      - type: Documentation\n        url: https://docs.sentry.io/api/\n      - type: Reference\n        url: https://docs.sentry.io/api/\n      - type: Authentication\n        url: https://docs.sentry.io/api/auth/\n      - type: RateLimits\n        url: https://docs.sentry.io/api/ratelimits/\n      - type: GettingStarted\n        url: https://docs.sentry.io/api/guides/create-auth-token/\n      - type: OpenAPI\n        url: openapi/sentry-api-openapi.yml\n    contact:\n      - FN: Sentry Support\n        url: https://sentry.io/support/\n\
  \        email: support@sentry.io\n\n  - aid: sentry:sentry-sdk-api\n    name: Sentry SDK API\n    description: >-\n      Sentry provides official SDKs for 22+ platforms including JavaScript,\n      Python, PHP, .NET, Java, Go, Ruby, Rust, Android, Apple, React Native,\n      Unity, and Unreal Engine. Each SDK provides error capture, performance\n      monitoring, session replay, and profiling capabilities.\n    humanURL: https://docs.sentry.io/platforms/\n    tags:\n      - Error Monitoring\n      - Debugging\n      - Observability\n      - Application Performance Management\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.sentry.io/platforms/\n      - type: Reference\n        url: https://develop.sentry.dev/sdk/overview/\n\n  - aid: sentry:sentry-integration-platform-api\n    name: Sentry Integration Platform API\n    description: >-\n      The Sentry Integration Platform API enables building public and internal\n      integrations with Sentry. Supports\
  \ OAuth2 with PKCE, device authorization\n      flow for CLI/CI environments, webhook notifications, and custom alert\n      actions for third-party applications.\n    humanURL: https://docs.sentry.io/api/integration/\n    tags:\n      - Error Monitoring\n      - Integrations\n      - Webhooks\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://docs.sentry.io/api/integration/\n      - type: Authentication\n        url: https://docs.sentry.io/api/auth/\n      - type: AsyncAPI\n        url: asyncapi/sentry-webhooks-asyncapi.yml\n\ncommon:\n  - type: Website\n    url: https://sentry.io/\n  - type: Portal\n    url: https://docs.sentry.io/api/\n  - type: Documentation\n    url: https://docs.sentry.io/api/\n  - type: Authentication\n    url: https://docs.sentry.io/api/auth/\n  - type: RateLimits\n    url: https://docs.sentry.io/api/ratelimits/\n  - type: GettingStarted\n    url: https://docs.sentry.io/api/guides/create-auth-token/\n  - type: ChangeLog\n    url:\
  \ https://sentry.io/changelog/\n  - type: Status\n    url: https://status.sentry.io/\n  - type: TermsOfService\n    url: https://sentry.io/terms/\n  - type: PrivacyPolicy\n    url: https://sentry.io/legal/privacy/\n  - type: Blog\n    url: https://sentry.io/blog/\n  - type: SDKs\n    url: https://docs.sentry.io/platforms/\n  - type: GitHubOrganization\n    url: https://github.com/getsentry\n  - type: DeveloperTools\n    url: https://sandbox.sentry.io/\n  - type: Pricing\n    url: https://sentry.io/pricing/\n  - type: SignUp\n    url: https://sentry.io/signup/\n  - type: Login\n    url: https://sentry.io/auth/login/\n  - type: JSONSchema\n    url: json-schema/sentry-issue-schema.json\n  - type: JSONLDContext\n    url: json-ld/sentry-context.jsonld\n  - type: JSONStructure\n    url: json-structure/sentry-issue-structure.json\n  - type: Vocabulary\n    url: vocabulary/sentry-vocabulary.yml\n  - type: SpectralRules\n    url: rules/sentry-rules.yml\n  - type: Capabilities\n    url: capabilities/error-monitoring.yaml\n\
  \nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sentry/refs/heads/main/apis.yml
tags:
- Error Monitoring
- Debugging
- Observability
- Application Performance Management
- Developer Tools
url: https://raw.githubusercontent.com/api-evangelist/sentry/refs/heads/main/apis.yml
use_cases: []
---
