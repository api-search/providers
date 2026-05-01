---
api_count: 3
api_specs:
- filename: decision-api-openapi.yml
  format: yaml
  label: AB Tasty Decision API
  slug: ab-tasty-decision-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/openapi/decision-api-openapi.yml
apis:
- description: 'The AB Tasty Decision API is a server-side service that evaluates a visitors context against your active experiments, personalizations, and feature flags, then returns a deterministic decision: which '
  name: AB Tasty Decision API
  slug: ab-tasty-decision-api
- description: AB Tastys Remote Control API is a developer and QA tool that lets you programmatically drive the AB Tasty SDK from outside your app or page, so you can precisely control and observe experiments withou
  name: AB Tasty Remote Control API
  slug: ab-tasty-remote-control-api
- description: The AB Tasty Public API provides programmatic access to manage campaigns, monitor and control experiments, manage account users, and integrate AB Tasty with third-party tools. It uses OAuth-style cred
  name: AB Tasty Public API
  slug: ab-tasty-public-api
capabilities:
- description: Unified workflow for server-side feature experimentation, A/B testing, and feature flag management. Enables developers and product teams to evaluate campaigns, retrieve flag values, and track activati
  name: AB Tasty Feature Experimentation
  slug: feature-experimentation
common:
- title: ''
  type: Website
  url: https://www.abtasty.com/
- title: ''
  type: Portal
  url: https://developers.abtasty.com/
- title: ''
  type: Documentation
  url: https://docs.abtasty.com/
- title: ''
  type: Pricing
  url: https://www.abtasty.com/pricing/
- title: ''
  type: Support
  url: https://support.abtasty.com/hc/en-us
- title: ''
  type: Legal
  url: https://www.abtasty.com/legal-notices/
- title: ''
  type: PrivacyPolicy
  url: https://www.abtasty.com/privacy-policy/
- title: ''
  type: GitHubOrganization
  url: https://github.com/flagship-io
- title: ''
  type: CLI
  url: https://github.com/flagship-io/abtasty-cli
- title: MCP Server
  type: Tools
  url: https://github.com/flagship-io/mcp-server
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/rules/ab-tasty-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/vocabulary/ab-tasty-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/capabilities/feature-experimentation.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-ld/ab-tasty-decision-api-context.jsonld
created: '2025-06-05'
description: At AB Tasty, we are your partner for pushing great ideas even further through optimization. We achieve this by empowering brands to build better experiences using personalization, experimentation, recommendations, merchandising, and the market's only emotions-based segmentation solution.
features:
- description: Advanced A/B testing with conversion safety mechanisms and unlimited variations
  name: A/B Testing
- description: Server-side feature flags with targeting and gradual rollouts
  name: Feature Flags
- description: Experience customization based on emotional needs and engagement segmentation
  name: Personalization
- description: Unified search, recommendations, and product visibility control
  name: E-Merchandising
- description: Progressive feature release with automatic KPI-triggered rollbacks
  name: Progressive Rollouts
- description: AI-powered prompt-based visual modifications for experiments
  name: AI Visual Editor
- description: Real-time predictive AI for anonymous visitor personalization targeting 90% of visitors
  name: AdaptiveCX
- description: Test multiple variables simultaneously across web and mobile
  name: Multivariate Testing
image: /assets/icons/ab-tasty.png
integrations:
- description: Partnership with Google Cloud for infrastructure and analytics integration
  name: Google Cloud
- description: Connect with analytics platforms via the integration hub for data sharing
  name: Analytics Tools
- description: Customer Data Platform integrations for enhanced visitor profiling
  name: CDPs
- description: OpenFeature provider integration for standardized feature flag management
  name: OpenFeature
- description: Edge function integration with Vercel for server-side experimentation
  name: Vercel
- description: Cloudflare Worker integration for edge-based feature experimentation
  name: Cloudflare
- description: AWS Lambda integration for serverless feature experimentation
  name: AWS Lambda
- description: Fastly worker integration for CDN-level feature experimentation
  name: Fastly
- description: Akamai worker integration for CDN-level feature experimentation
  name: Akamai
- description: Shopify Hydrogen framework integration for headless commerce experimentation
  name: Shopify Hydrogen
jsonld:
- class_count: 13
  name: Ab Tasty Decision Api Context
  property_count: 29
  slug: ab-tasty-decision-api-context
layout: provider
modified: '2026-04-19'
name: AB Tasty
rules:
- name: AB Tasty API Rules
  rule_count: 40
  severity_counts:
    error: 13
    hint: 0
    info: 5
    warn: 22
  slug: ab-tasty-spectral-rules
skills: []
slug: ab-tasty
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ab-tasty\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/apis.yml\napis:\n  - aid: ab-tasty:ab-tasty-decision-api\n    name: AB Tasty Decision API\n    humanURL: https://docs.abtasty.com/server-side/decision-api/decision-api\n    properties:\n      - url: https://docs.abtasty.com/server-side/decision-api/decision-api\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/openapi/decision-api-openapi.yml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-campaign-request-schema.json\n        type: JSONSchema\n        title: Campaign Request\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-campaign-schema.json\n        type: JSONSchema\n        title: Campaign\n      - url: >-\n      \
  \    https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-flag-schema.json\n        type: JSONSchema\n        title: Flag\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-flags-response-schema.json\n        type: JSONSchema\n        title: Flags Response\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-activation-request-schema.json\n        type: JSONSchema\n        title: Activation Request\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-flag-metadata-schema.json\n        type: JSONSchema\n        title: Flag Metadata\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-campaign-response-normal-schema.json\n        type: JSONSchema\n \
  \       title: Campaign Response Normal\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-campaign-response-simple-schema.json\n        type: JSONSchema\n        title: Campaign Response Simple\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-campaign-response-full-schema.json\n        type: JSONSchema\n        title: Campaign Response Full\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-batch-activation-request-schema.json\n        type: JSONSchema\n        title: Batch Activation Request\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-batch-activation-item-schema.json\n        type: JSONSchema\n        title: Batch Activation Item\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-campaign-variation-schema.json\n\
  \        type: JSONSchema\n        title: Campaign Variation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-schema/decision-api-single-campaign-request-schema.json\n        type: JSONSchema\n        title: Single Campaign Request\n      - url: https://github.com/flagship-io/flagship-ts-sdk\n        type: SDK\n        title: TypeScript SDK\n      - url: https://github.com/flagship-io/flagship-react-sdk\n        type: SDK\n        title: React SDK\n      - url: https://github.com/flagship-io/flagship-react-native-sdk\n        type: SDK\n        title: React Native SDK\n      - url: https://github.com/flagship-io/flagship-flutter-sdk\n        type: SDK\n        title: Flutter SDK\n      - url: https://github.com/flagship-io/flagship-php-sdk\n        type: SDK\n        title: PHP SDK\n      - url: https://github.com/flagship-io/flagship-dotnet-sdk\n        type: SDK\n        title: .NET SDK\n      - url: https://github.com/flagship-io/flagship-android\n\
  \        type: SDK\n        title: Android SDK\n      - url: https://github.com/flagship-io/flagship-ios\n        type: SDK\n        title: iOS SDK\n      - url: https://github.com/flagship-io/flagship-python-sdk\n        type: SDK\n        title: Python SDK\n      - url: https://github.com/flagship-io/flagship-java\n        type: SDK\n        title: Java SDK\n      - url: https://github.com/flagship-io/flagship-go-sdk\n        type: SDK\n        title: Go SDK\n      - url: https://github.com/flagship-io/code-samples\n        type: CodeExamples\n        title: Code Samples\n    tags:\n      - Decision\n      - Experimentation\n      - Feature Flags\n      - Server Side\n    description: >-\n      The AB Tasty Decision API is a server-side service that evaluates a visitors\n      context against your active experiments, personalizations, and feature flags,\n      then returns a deterministic decision: which campaigns the user qualifies for,\n      the selected variation, and any variables\
  \ or content to render.\n  - aid: ab-tasty:ab-tasty-remote-control-api\n    name: AB Tasty Remote Control API\n    humanURL: https://docs.abtasty.com/server-side/remote-control-api\n    properties:\n      - url: https://docs.abtasty.com/server-side/remote-control-api\n        type: Documentation\n    tags:\n      - Remote Control\n      - Campaigns\n      - Experimentation\n    description: >-\n      AB Tastys Remote Control API is a developer and QA tool that lets you programmatically\n      drive the AB Tasty SDK from outside your app or page, so you can precisely control\n      and observe experiments without changing production targeting. With it, you\n      can preview or force specific campaigns and variations for a visitor, toggle\n      or pause experiences, set visitor/context attributes, trigger goals and custom\n      events, refresh decisions, and clear caches to reproduce clean states.\n  - aid: ab-tasty:ab-tasty-public-api\n    name: AB Tasty Public API\n    humanURL: https://docs.abtasty.com/integrations/custom-integrations/ab-tasty-public-api\n\
  \    properties:\n      - url: https://docs.abtasty.com/integrations/custom-integrations/ab-tasty-public-api\n        type: Documentation\n    tags:\n      - Campaigns\n      - Integrations\n      - Management\n    description: >-\n      The AB Tasty Public API provides programmatic access to manage campaigns,\n      monitor and control experiments, manage account users, and integrate AB Tasty\n      with third-party tools. It uses OAuth-style credentials (ClientID and ClientSecret)\n      to generate access tokens for authentication.\nname: AB Tasty\ntags:\n  - Aggregation\n  - Experimentation\n  - Feature Flags\n  - Personalization\n  - A/B Testing\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://www.abtasty.com/\n    name: Website\n    type: Website\n  - url: https://developers.abtasty.com/\n    name: Developer Portal\n    type: Portal\n  - url: https://docs.abtasty.com/\n    name: Documentation\n\
  \    type: Documentation\n  - url: https://www.abtasty.com/pricing/\n    name: Pricing\n    type: Pricing\n  - url: https://support.abtasty.com/hc/en-us\n    name: Support\n    type: Support\n  - url: https://www.abtasty.com/legal-notices/\n    name: Legal Notices\n    type: Legal\n  - url: https://www.abtasty.com/privacy-policy/\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://github.com/flagship-io\n    name: GitHub Organization\n    type: GitHubOrganization\n  - url: https://github.com/flagship-io/abtasty-cli\n    name: AB Tasty CLI\n    type: CLI\n  - url: https://github.com/flagship-io/mcp-server\n    name: MCP Server\n    type: Tools\n    title: MCP Server\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/rules/ab-tasty-spectral-rules.yml\n    name: AB Tasty Spectral Rules\n    type: SpectralRules\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/vocabulary/ab-tasty-vocabulary.yaml\n\
  \    name: AB Tasty Vocabulary\n    type: Vocabulary\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/capabilities/feature-experimentation.yaml\n    name: Feature Experimentation Capability\n    type: NaftikoCapability\n  - url: >-\n      https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-ld/ab-tasty-decision-api-context.jsonld\n    name: Decision API JSON-LD Context\n    type: JSONLD\n  - type: Features\n    data:\n      - name: A/B Testing\n        description: Advanced A/B testing with conversion safety mechanisms and unlimited variations\n      - name: Feature Flags\n        description: Server-side feature flags with targeting and gradual rollouts\n      - name: Personalization\n        description: Experience customization based on emotional needs and engagement segmentation\n      - name: E-Merchandising\n        description: Unified search, recommendations, and product visibility control\n      - name: Progressive\
  \ Rollouts\n        description: Progressive feature release with automatic KPI-triggered rollbacks\n      - name: AI Visual Editor\n        description: AI-powered prompt-based visual modifications for experiments\n      - name: AdaptiveCX\n        description: Real-time predictive AI for anonymous visitor personalization targeting 90% of visitors\n      - name: Multivariate Testing\n        description: Test multiple variables simultaneously across web and mobile\n  - type: UseCases\n    data:\n      - name: Web Experimentation\n        description: Run A/B tests and multivariate experiments on websites to optimize conversion rates\n      - name: Feature Experimentation\n        description: Multi-channel feature testing across devices via API or SDK implementation\n      - name: Server-Side Testing\n        description: Backend and edge worker experiments using the Decision API\n      - name: E-commerce Optimization\n        description: Merchandising, recommendations, and personalized\
  \ product experiences\n      - name: Progressive Deployment\n        description: Gradual feature rollouts with automated rollback based on KPI monitoring\n      - name: Anonymous Personalization\n        description: AI-driven real-time personalization for anonymous visitors\n  - type: Integrations\n    data:\n      - name: Google Cloud\n        description: Partnership with Google Cloud for infrastructure and analytics integration\n      - name: Analytics Tools\n        description: Connect with analytics platforms via the integration hub for data sharing\n      - name: CDPs\n        description: Customer Data Platform integrations for enhanced visitor profiling\n      - name: OpenFeature\n        description: OpenFeature provider integration for standardized feature flag management\n      - name: Vercel\n        description: Edge function integration with Vercel for server-side experimentation\n      - name: Cloudflare\n        description: Cloudflare Worker integration for edge-based\
  \ feature experimentation\n      - name: AWS Lambda\n        description: AWS Lambda integration for serverless feature experimentation\n      - name: Fastly\n        description: Fastly worker integration for CDN-level feature experimentation\n      - name: Akamai\n        description: Akamai worker integration for CDN-level feature experimentation\n      - name: Shopify Hydrogen\n        description: Shopify Hydrogen framework integration for headless commerce experimentation\ncreated: '2025-06-05'\nmodified: '2026-04-19'\nposition: Consuming\ndescription: >-\n  At AB Tasty, we are your partner for pushing great ideas even further through\n  optimization. We achieve this by empowering brands to build better experiences\n  using personalization, experimentation, recommendations, merchandising, and\n  the market's only emotions-based segmentation solution.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/apis.yml
tags:
- Aggregation
- Experimentation
- Feature Flags
- Personalization
- A/B Testing
url: https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/apis.yml
use_cases:
- description: Run A/B tests and multivariate experiments on websites to optimize conversion rates
  name: Web Experimentation
- description: Multi-channel feature testing across devices via API or SDK implementation
  name: Feature Experimentation
- description: Backend and edge worker experiments using the Decision API
  name: Server-Side Testing
- description: Merchandising, recommendations, and personalized product experiences
  name: E-commerce Optimization
- description: Gradual feature rollouts with automated rollback based on KPI monitoring
  name: Progressive Deployment
- description: AI-driven real-time personalization for anonymous visitors
  name: Anonymous Personalization
---
