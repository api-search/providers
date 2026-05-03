---
api_count: 4
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Vercel REST API
  slug: vercel-rest-api
  spec_type: OpenAPI
  url: https://openapi.vercel.sh/
- filename: vercel-ai-gateway-openapi.yml
  format: yaml
  label: Vercel AI Gateway API
  slug: vercel-ai-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/openapi/vercel-ai-gateway-openapi.yml
- filename: vercel-v0-platform-openapi.yml
  format: yaml
  label: V0 Platform API
  slug: v0-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/openapi/vercel-v0-platform-openapi.yml
apis:
- description: Vercel is a developer cloud to build and deploy web applications.
  name: Vercel
  slug: vercel
- description: The Vercel REST API provides programmatic access to the Vercel platform. All endpoints live under https://api.vercel.com and follow REST architecture over SSL. The API covers deployments, domains, pro
  name: Vercel REST API
  slug: vercel-rest-api
- description: The Vercel AI Gateway provides a unified API to access hundreds of AI models from multiple providers through a single endpoint at https://ai-gateway.vercel.sh/v1. It offers one key for hundreds of mod
  name: Vercel AI Gateway API
  slug: vercel-ai-gateway-api
- description: 'The v0 Platform API provides programmatic access to v0''s AI-powered app generation pipeline. It is a REST interface that wraps v0''s full code generation lifecycle from prompt to project to code files '
  name: V0 Platform API
  slug: v0-platform-api
capabilities:
- description: Unified workflow capability for AI-powered application development using Vercel's AI platform. Enables developers and AI agents to generate full-stack web applications via v0, query and compare AI mod
  name: Vercel AI Development Platform
  slug: ai-development
common:
- title: ''
  type: Guide
  url: https://vercel.com/guides
- title: ''
  type: Blog
  url: https://vercel.com/blog
- title: ''
  type: PressReleases
  url: https://vercel.com/press
- title: ''
  type: ChangeLog
  url: https://vercel.com/changelog
- title: ''
  type: Documentation
  url: https://vercel.com/docs
- title: ''
  type: RateLimits
  url: https://vercel.com/docs/rest-api/reference#rate-limits
- title: ''
  type: Versioning
  url: https://vercel.com/docs/rest-api/reference#versioning
- title: ''
  type: Pagination
  url: https://vercel.com/docs/rest-api/reference#pagination
- title: ''
  type: Support
  url: https://vercel.com/help
- title: ''
  type: Pricing
  url: https://vercel.com/pricing
- title: ''
  type: Templates
  url: https://vercel.com/templates
- title: ''
  type: Login
  url: https://vercel.com/login
- title: ''
  type: SignUp
  url: https://vercel.com/signup
- title: ''
  type: GitHubOrganization
  url: https://github.com/vercel/vercel
- title: ''
  type: Forum
  url: https://community.vercel.com/
- title: ''
  type: StatusPage
  url: https://www.vercel-status.com
- title: ''
  type: TermsOfService
  url: https://vercel.com/legal/terms
- title: ''
  type: PrivacyPolicy
  url: https://vercel.com/legal/privacy-policy
- title: ''
  type: Security
  url: https://security.vercel.com
- title: ''
  type: CLI
  url: https://vercel.com/docs/cli
- title: ''
  type: SDK
  url: https://vercel.com/docs/ai-sdk
- title: ''
  type: Security
  url: https://vercel.com/docs/vercel-firewall
- title: ''
  type: Documentation
  url: https://vercel.com/docs/vercel-firewall/firewall-api
- title: ''
  type: OpenAPI
  url: https://openapi.vercel.sh/
- title: ''
  type: Security
  url: https://vercel.com/security
- title: ''
  type: APIReference
  url: https://vercel.com/docs/rest-api/reference
created: '2025-02-08'
description: Vercel is a cloud platform that helps developers build, deploy, and scale modern web applications quickly and efficiently. It provides an optimized hosting environment for frontend frameworks like Next.js (which it created), as well as other React, Vue, Angular, and static site projects. Vercel automates workflows for continuous deployment, edge caching, and serverless functions, so developers can push code changes and see them live almost instantly.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 30
  name: Vercel Context
  property_count: 2
  slug: vercel-context
layout: provider
modified: '2026-05-03'
name: Vercel
rules:
- name: Vercel API Rules
  rule_count: 11
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 6
  slug: vercel-rules
skills: []
slug: vercel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vercel\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/apis.yml\napis:\n  - aid: vercel:vercel\n    name: Vercel\n    tags: []\n    humanURL: ' https://vercel.com/docs'\n    properties:\n      - url: ' https://vercel.com/docs'\n        type: Documentation\n    description: >-\n      Vercel is a developer cloud to build and deploy web applications.\n  - aid: vercel:vercel-rest-api\n    name: Vercel REST API\n    tags:\n      - Access Groups\n      - Billing\n      - Certificates\n      - Deployments\n      - DNS\n      - Domains\n      - Edge Config\n      - Environment Variables\n      - Projects\n      - Teams\n      - Webhooks\n    humanURL: https://vercel.com/docs/rest-api/reference\n    properties:\n      - url: https://vercel.com/docs/rest-api/reference\n        type: Documentation\n      - url: https://openapi.vercel.sh/\n        type: OpenAPI\n      - url: https://vercel.com/docs/rest-api/reference#rate-limits\n        type: RateLimits\n\
  \      - url: https://vercel.com/docs/rest-api/reference#pagination\n        type: Pagination\n      - url: https://vercel.com/docs/rest-api/reference#versioning\n        type: Versioning\n    description: >-\n      The Vercel REST API provides programmatic access to the Vercel platform.\n      All endpoints live under https://api.vercel.com and follow REST\n      architecture over SSL. The API covers deployments, domains, projects,\n      teams, DNS, certificates, edge config, environment variables, access\n      groups, billing, security, webhooks, and more. Authentication uses Bearer\n      tokens via the Authorization header.\n  - aid: vercel:vercel-ai-gateway-api\n    name: Vercel AI Gateway API\n    tags:\n      - AI\n      - AI Gateway\n      - LLM\n      - Machine Learning\n      - Models\n    humanURL: https://vercel.com/docs/ai-gateway\n    properties:\n      - url: https://vercel.com/docs/ai-gateway\n        type: Documentation\n      - url: https://vercel.com/docs/ai-gateway/getting-started\n\
  \        type: GettingStarted\n      - url: https://vercel.com/docs/ai-gateway/models-and-providers\n        type: Documentation\n      - url: https://vercel.com/docs/ai-gateway/sdks-and-apis/openai-compat\n        type: Documentation\n      - url: https://vercel.com/docs/ai-gateway/usage\n        type: UsageBilling\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/openapi/vercel-ai-gateway-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Vercel AI Gateway provides a unified API to access hundreds of AI\n      models from multiple providers through a single endpoint at\n      https://ai-gateway.vercel.sh/v1. It offers one key for hundreds of models,\n      spend monitoring, automatic retries and fallbacks, embeddings support, and\n      zero markup on token pricing. Compatible with the AI SDK, OpenAI SDK, and\n      Anthropic SDK.\n  - aid: vercel:v0-platform-api\n    name: V0 Platform API\n    tags:\n      - AI\n    \
  \  - App Builder\n      - Code Generation\n    humanURL: https://v0.dev/docs\n    properties:\n      - url: https://v0.dev/docs\n        type: Documentation\n      - url: https://github.com/vercel/v0-sdk\n        type: GitHubOrganization\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/openapi/vercel-v0-platform-openapi.yml\n        type: OpenAPI\n    description: >-\n      The v0 Platform API provides programmatic access to v0's AI-powered app\n      generation pipeline. It is a REST interface that wraps v0's full code\n      generation lifecycle from prompt to project to code files to deployment.\n      Capabilities include generating full-stack web apps from natural language\n      prompts, structured parsing of generated code, automatic error fixing, and\n      linking with rendered previews. A TypeScript SDK is available.\nname: Vercel\ntags:\n  - AI Gateways\n  - Gateways\n  - Observability\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: 3rd-Party\ncommon:\n  - url: https://vercel.com/marketplace\n    name: Vercel Marketplace\n    type: Integrations\n    description: 'null'\n  - url: https://vercel.com/guides\n    name: Guides\n    type: Guide\n    description: 'null'\n  - url: https://vercel.com/blog\n    name: Blog - Vercel\n    type: Blog\n    description: 'null'\n  - url: https://vercel.com/press\n    name: Press - Vercel\n    type: PressReleases\n    description: 'null'\n  - url: https://vercel.com/changelog\n    name: Changelog - Vercel\n    type: ChangeLog\n    description: 'null'\n  - url: https://vercel.com/docs\n    name: Vercel Documentation\n    type: Documentation\n    description: 'null'\n  - url: https://vercel.com/docs/rest-api/reference#rate-limits\n    name: Using the REST API - Vercel API Docs\n    type: RateLimits\n    description: 'null'\n  - url: https://vercel.com/docs/rest-api/reference#versioning\n    name: Using the REST API - Vercel API Docs\n    type: Versioning\n    description: 'null'\n\
  \  - url: https://vercel.com/docs/rest-api/reference#pagination\n    name: Using the REST API - Vercel API Docs\n    type: Pagination\n    description: 'null'\n  - url: https://vercel.com/help\n    name: Help\n    type: Support\n    description: 'null'\n  - url: https://vercel.com/pricing\n    name: Find a plan to power your projects.\n    type: Pricing\n    description: 'null'\n  - url: https://vercel.com/templates\n    name: Find your Template\n    type: Templates\n    description: 'null'\n  - url: https://vercel.com/login\n    name: Login  Vercel\n    type: Login\n    description: 'null'\n  - url: https://vercel.com/signup\n    name: Sign Up  Vercel\n    type: SignUp\n    description: 'null'\n  - url: https://github.com/vercel/vercel\n    name: Vercel GitHub Repository\n    type: GitHubOrganization\n    description: >-\n      The main open-source Vercel repository, configured as a monorepo\n      containing the CLI and multiple packages.\n  - url: https://community.vercel.com/\n   \
  \ name: Vercel Community Forum\n    type: Forum\n    description: >-\n      The online community space for Vercel discussions, including help,\n      feedback, showcase, and announcements.\n  - url: https://www.vercel-status.com\n    name: Vercel Status\n    type: StatusPage\n    description: >-\n      Real-time and historical status information for Vercel platform services\n      including build, deploy, API, and edge network.\n  - url: https://vercel.com/legal/terms\n    name: Vercel Terms of Service\n    type: TermsOfService\n    description: >-\n      The legal terms of service governing use of the Vercel platform and\n      services.\n  - url: https://vercel.com/legal/privacy-policy\n    name: Vercel Privacy Policy\n    type: PrivacyPolicy\n    description: >-\n      The privacy policy covering data collection and processing practices\n      across Vercel platforms.\n  - url: https://security.vercel.com\n    name: Vercel Trust Center\n    type: Security\n    description: >-\n    \
  \  Security and compliance documentation portal covering SOC 2, ISO 27001,\n      PCI DSS, HIPAA, and GDPR certifications.\n  - url: https://vercel.com/docs/cli\n    name: Vercel CLI\n    type: CLI\n    description: >-\n      Command-line interface for managing and configuring Vercel projects,\n      deployments, domains, DNS, and environment variables from the terminal.\n  - url: https://vercel.com/docs/ai-sdk\n    name: Vercel AI SDK\n    type: SDK\n    description: >-\n      TypeScript toolkit for building AI-powered applications with Next.js, Vue,\n      Svelte, and Node.js, providing a unified API to call any LLM.\n  - url: https://vercel.com/docs/vercel-firewall\n    name: Vercel Firewall\n    type: Security\n    description: >-\n      Web Application Firewall embedded in the Vercel Edge Network to protect\n      applications from malicious attacks and unauthorized access.\n  - url: https://vercel.com/docs/vercel-firewall/firewall-api\n    name: Vercel Firewall API\n    type: Documentation\n\
  \    description: >-\n      Documentation for interacting with the security endpoints of the Vercel\n      REST API programmatically.\n  - url: https://openapi.vercel.sh/\n    name: Vercel REST API OpenAPI Specification\n    type: OpenAPI\n    description: >-\n      The OpenAPI 3.0.3 specification for the Vercel REST API, automatically\n      generated from the API repository.\n  - url: https://vercel.com/security\n    name: Vercel Security\n    type: Security\n    description: >-\n      Overview of Vercel security practices, governance program, and compliance\n      certifications.\n  - url: https://vercel.com/docs/rest-api/reference\n    name: Vercel REST API Reference\n    type: APIReference\n    description: >-\n      Complete reference documentation for the Vercel REST API covering all\n      endpoint categories.\ncreated: '2025-02-08'\nmodified: '2026-05-03'\nposition: Consuming\nsegments:\n  - Gateways\ndescription: >-\n  Vercel is a cloud platform that helps developers build, deploy,\
  \ and scale modern\n  web applications quickly and efficiently. It provides an optimized hosting environment\n  for frontend frameworks like Next.js (which it created), as well as other React,\n  Vue, Angular, and static site projects. Vercel automates workflows for continuous\n  deployment, edge caching, and serverless functions, so developers can push code\n  changes and see them live almost instantly.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/apis.yml
tags:
- AI Gateways
- Gateways
- Observability
url: https://raw.githubusercontent.com/api-evangelist/vercel/refs/heads/main/apis.yml
use_cases: []
---
