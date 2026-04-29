---
api_count: 13
api_specs:
- filename: contentstack-content-delivery-api-openapi.yml
  format: yaml
  label: Contentstack Content Delivery API
  slug: content-delivery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-content-delivery-api-openapi.yml
- filename: contentstack-content-management-api-openapi.yml
  format: yaml
  label: Contentstack Content Management API
  slug: content-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-content-management-api-openapi.yml
- filename: contentstack-personalize-management-api-openapi.yml
  format: yaml
  label: Contentstack Personalize Management API
  slug: personalize-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-personalize-management-api-openapi.yml
- filename: contentstack-personalize-edge-api-openapi.yml
  format: yaml
  label: Contentstack Personalize Edge API
  slug: personalize-edge-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-personalize-edge-api-openapi.yml
- filename: contentstack-automate-management-api-openapi.yml
  format: yaml
  label: Contentstack Automate Management API
  slug: automate-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-automate-management-api-openapi.yml
- filename: contentstack-analytics-api-openapi.yml
  format: yaml
  label: Contentstack Analytics API
  slug: analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-analytics-api-openapi.yml
- filename: contentstack-scim-api-openapi.yml
  format: yaml
  label: Contentstack SCIM API
  slug: scim-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-scim-api-openapi.yml
- filename: contentstack-brand-kit-management-api-openapi.yml
  format: yaml
  label: Contentstack Brand Kit Management API
  slug: brand-kit-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-brand-kit-management-api-openapi.yml
- filename: contentstack-knowledge-vault-api-openapi.yml
  format: yaml
  label: Contentstack Knowledge Vault API
  slug: knowledge-vault-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-knowledge-vault-api-openapi.yml
- filename: contentstack-generative-ai-api-openapi.yml
  format: yaml
  label: Contentstack Generative AI API
  slug: generative-ai-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-generative-ai-api-openapi.yml
- filename: contentstack-launch-api-openapi.yml
  format: yaml
  label: Contentstack Launch API
  slug: launch-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/openapi/contentstack-launch-api-openapi.yml
apis:
- description: The Contentstack Content Delivery API (CDA) allows developers to retrieve published content from their Contentstack stacks and deliver it to web or mobile applications. It supports fetching entries, a
  name: Contentstack Content Delivery API
  slug: content-delivery-api
- description: 'The Contentstack Content Management API (CMA) provides programmatic access to manage all aspects of a Contentstack stack, including content types, entries, assets, environments, workflows, and users. '
  name: Contentstack Content Management API
  slug: content-management-api
- description: The Contentstack GraphQL Content Delivery API enables developers to query content from their Contentstack stack using GraphQL syntax, allowing precise retrieval of only the fields and relationships ne
  name: Contentstack GraphQL Content Delivery API
  slug: graphql-content-delivery-api
- description: The Contentstack Image Delivery API allows developers to retrieve and transform images stored as assets in their Contentstack stacks. It supports on-the-fly image manipulation operations including res
  name: Contentstack Image Delivery API
  slug: image-delivery-api
- description: The Contentstack Personalize Management API provides programmatic control over the resources in a Contentstack Personalize project, including Attributes, Audiences, Events, and Experiences. Developers
  name: Contentstack Personalize Management API
  slug: personalize-management-api
- description: The Contentstack Personalize Edge API enables real-time, dynamic personalization interactions using edge computing to retrieve personalized content experiences. It allows applications to retrieve pers
  name: Contentstack Personalize Edge API
  slug: personalize-edge-api
- description: 'The Contentstack Automate Management API allows developers to programmatically manage automation projects and workflows within a Contentstack organization. It supports creating, updating, retrieving, '
  name: Contentstack Automate Management API
  slug: automate-management-api
- description: The Contentstack Analytics API provides access to usage and performance metrics for CMS, Launch, and Automate products within a Contentstack organization. Developers can retrieve analytics data progra
  name: Contentstack Analytics API
  slug: analytics-api
- description: The Contentstack SCIM API implements the System for Cross-domain Identity Management (SCIM 2.0) standard to enable automated user lifecycle management within a Contentstack organization. It allows Ide
  name: Contentstack SCIM API
  slug: scim-api
- description: The Contentstack Brand Kit Management API provides programmatic control over Brand Kit resources within a Contentstack organization. Brand Kits serve as centralized hubs for an organization's brand id
  name: Contentstack Brand Kit Management API
  slug: brand-kit-management-api
- description: The Contentstack Knowledge Vault API provides endpoints for ingesting, updating, and deleting content items stored in a Brand Kit's Knowledge Vault. The Knowledge Vault is a vector database that store
  name: Contentstack Knowledge Vault API
  slug: knowledge-vault-api
- description: 'The Contentstack Generative AI API provides an endpoint for generating AI-powered content using a Brand Kit''s knowledge vault and voice profiles. It acts as a communication channel between the vector '
  name: Contentstack Generative AI API
  slug: generative-ai-api
- description: The Contentstack Launch API allows developers to programmatically manage web application deployments within Contentstack Launch. It supports full lifecycle management of Launch projects, environments,
  name: Contentstack Launch API
  slug: launch-api
asyncapis:
- description: Contentstack Webhooks provide event-driven notifications for content lifecycle events within a stack. When configured, Contentstack sends HTTP POST requests to your specified endpoint URL whenever mat
  name: Contentstack Webhooks
  slug: contentstack-webhooks-asyncapi
capabilities: []
common:
- title: ''
  type: AsyncAPI
  url: asyncapi/contentstack-webhooks-asyncapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/contentstack-entry-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/contentstack-stack-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/contentstack-webhook-payload-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/contentstack-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/contentstack-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/contentstack-rules.yml
- title: ''
  type: Capability
  url: capabilities/deliver-headless-content.yml
- title: ''
  type: Capability
  url: capabilities/manage-stack-content.yml
- title: ''
  type: Capability
  url: capabilities/personalize-experiences.yml
- title: ''
  type: Capability
  url: capabilities/automate-content-workflows.yml
- title: ''
  type: Capability
  url: capabilities/generate-brand-aligned-ai-content.yml
- title: ''
  type: Capability
  url: capabilities/deploy-launch-frontends.yml
- title: ''
  type: Capability
  url: capabilities/provision-users-via-scim.yml
created: ''
description: This document is a detailed reference to Contentstack’s Content Delivery API. Retrieve content from your account and deliver it to web and mobile properties.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Contentstack Context
  property_count: 13
  slug: contentstack-context
layout: provider
modified: '2026-04-28'
name: contentstack
rules:
- name: contentstack API Rules
  rule_count: 8
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 3
  slug: contentstack-rules
skills: []
slug: contentstack
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: contentstack\nurl: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/apis.yml\nmodified: '2026-04-28'\napis:\n  - aid: contentstack:content-delivery-api\n    name: Contentstack Content Delivery API\n    tags:\n      - Content Delivery\n      - Content Management\n      - Headless CMS\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://cdn.contentstack.io\n    humanURL: https://www.contentstack.com/docs/developers/apis/content-delivery-api\n    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/content-delivery-api\n        type: Documentation\n      - url: openapi/contentstack-content-delivery-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Contentstack Content Delivery API (CDA) allows developers to retrieve published\n      content from their Contentstack stacks and deliver it to web or mobile applications.\n      It supports\
  \ fetching entries, assets, and content types through REST endpoints\n      using stack API keys and delivery tokens for authentication. The API is read-only\n      and optimized for high-performance content retrieval at scale.\n\n  - aid: contentstack:content-management-api\n    name: Contentstack Content Management API\n    tags:\n      - Content Management\n      - CRUD\n      - Headless CMS\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.contentstack.io\n    humanURL: https://www.contentstack.com/docs/developers/apis/content-management-api\n    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/content-management-api\n        type: Documentation\n      - url: openapi/contentstack-content-management-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Contentstack Content Management API (CMA) provides programmatic access to\n      manage all aspects of a Contentstack\
  \ stack, including content types, entries,\n      assets, environments, workflows, and users. It supports full CRUD operations\n      using standard HTTP verbs (GET, POST, PUT, DELETE) and authenticates via management\n      tokens or user session tokens.\n\n  - aid: contentstack:graphql-content-delivery-api\n    name: Contentstack GraphQL Content Delivery API\n    tags:\n      - Content Delivery\n      - GraphQL\n      - Headless CMS\n      - Query Language\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://graphql.contentstack.com\n    humanURL: https://www.contentstack.com/docs/developers/apis/graphql-content-delivery-api\n    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/graphql-content-delivery-api\n        type: Documentation\n    description: >-\n      The Contentstack GraphQL Content Delivery API enables developers to query content\n      from their Contentstack stack using GraphQL syntax, allowing\
  \ precise retrieval\n      of only the fields and relationships needed in a single request. It is built\n      on top of the Content Delivery API and supports querying entries, assets, and\n      nested references across content types. The GraphQL API does not support mutations\n      or subscriptions; it is strictly read-only and intended for front-end and application\n      data fetching.\n\n  - aid: contentstack:image-delivery-api\n    name: Contentstack Image Delivery API\n    tags:\n      - Asset Delivery\n      - Images\n      - Media\n      - Transformation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://images.contentstack.io\n    humanURL: https://www.contentstack.com/docs/developers/apis/image-delivery-api\n    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/image-delivery-api\n        type: Documentation\n    description: >-\n      The Contentstack Image Delivery API allows developers to\
  \ retrieve and transform\n      images stored as assets in their Contentstack stacks. It supports on-the-fly\n      image manipulation operations including resizing, cropping, format conversion,\n      quality adjustment, and overlay compositing via URL query parameters. Images\n      are served from a CDN for fast delivery, and transformations are applied at\n      request time without creating additional stored copies.\n\n  - aid: contentstack:personalize-management-api\n    name: Contentstack Personalize Management API\n    tags:\n      - Audiences\n      - Content Management\n      - Experiences\n      - Personalization\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://personalize-api.contentstack.com\n    humanURL: https://www.contentstack.com/docs/developers/apis/personalize-management-api\n    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/personalize-management-api\n        type: Documentation\n\
  \      - url: openapi/contentstack-personalize-management-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Contentstack Personalize Management API provides programmatic control over\n      the resources in a Contentstack Personalize project, including Attributes, Audiences,\n      Events, and Experiences. Developers can use this API to create and manage audience\n      segments based on user attributes and behavioral events, and to configure personalized\n      content experiences for those segments.\n\n  - aid: contentstack:personalize-edge-api\n    name: Contentstack Personalize Edge API\n    tags:\n      - Edge Computing\n      - Events\n      - Personalization\n      - User Attributes\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://personalize-edge.contentstack.com\n    humanURL: https://www.contentstack.com/docs/developers/apis/personalize-edge-api\n    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/personalize-edge-api\n\
  \        type: Documentation\n      - url: openapi/contentstack-personalize-edge-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Contentstack Personalize Edge API enables real-time, dynamic personalization\n      interactions using edge computing to retrieve personalized content experiences.\n      It allows applications to retrieve personalization manifests of active experiences,\n      set and update user attributes for audience matching, merge user identity records,\n      and track behavioral events.\n\n  - aid: contentstack:automate-management-api\n    name: Contentstack Automate Management API\n    tags:\n      - Automation\n      - Content Management\n      - Integration\n      - Workflows\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://automations-api.contentstack.com\n    humanURL: https://www.contentstack.com/docs/developers/apis/automation-hub-management-api\n    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/automation-hub-management-api\n\
  \        type: Documentation\n      - url: openapi/contentstack-automate-management-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Contentstack Automate Management API allows developers to programmatically\n      manage automation projects and workflows within a Contentstack organization.\n      It supports creating, updating, retrieving, and deleting automations that connect\n      Contentstack content events to third-party services and internal processes.\n      This API is part of the Contentstack Automate (formerly Automation Hub) product,\n      which provides a no-code/low-code automation layer built on top of the CMS.\n\n  - aid: contentstack:analytics-api\n    name: Contentstack Analytics API\n    tags:\n      - Analytics\n      - Metrics\n      - Monitoring\n      - Reporting\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.contentstack.io\n    humanURL: https://www.contentstack.com/docs/developers/apis/analytics-api\n\
  \    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/analytics-api\n        type: Documentation\n      - url: openapi/contentstack-analytics-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Contentstack Analytics API provides access to usage and performance metrics\n      for CMS, Launch, and Automate products within a Contentstack organization. Developers\n      can retrieve analytics data programmatically to build custom dashboards, monitor\n      content delivery performance, and track platform usage against plan limits.\n\n  - aid: contentstack:scim-api\n    name: Contentstack SCIM API\n    tags:\n      - Identity Management\n      - SCIM\n      - Security\n      - User Provisioning\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://auth-api.contentstack.com\n    humanURL: https://www.contentstack.com/docs/developers/apis/scim-api\n    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/scim-api\n\
  \        type: Documentation\n      - url: openapi/contentstack-scim-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Contentstack SCIM API implements the System for Cross-domain Identity Management\n      (SCIM 2.0) standard to enable automated user lifecycle management within a Contentstack\n      organization. It allows Identity Providers (IdPs) to provision and deprovision\n      users, manage group memberships, and synchronize user attributes between the\n      IdP and Contentstack.\n\n  - aid: contentstack:brand-kit-management-api\n    name: Contentstack Brand Kit Management API\n    tags:\n      - AI\n      - Brand Management\n      - Content Generation\n      - Voice Profiles\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://brand-kits-api.contentstack.com\n    humanURL: https://www.contentstack.com/docs/developers/apis/brand-kit-management-api\n    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/brand-kit-management-api\n\
  \        type: Documentation\n      - url: openapi/contentstack-brand-kit-management-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Contentstack Brand Kit Management API provides programmatic control over\n      Brand Kit resources within a Contentstack organization. Brand Kits serve as\n      centralized hubs for an organization's brand identity, encompassing detailed\n      brand information, writing guidelines, and persona configurations.\n\n  - aid: contentstack:knowledge-vault-api\n    name: Contentstack Knowledge Vault API\n    tags:\n      - AI\n      - Knowledge Management\n      - RAG\n      - Vector Database\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://ai.contentstack.com\n    humanURL: https://www.contentstack.com/docs/developers/apis/knowledge-vault-api\n    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/knowledge-vault-api\n        type: Documentation\n    \
  \  - url: openapi/contentstack-knowledge-vault-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Contentstack Knowledge Vault API provides endpoints for ingesting,\n      updating, and deleting content items stored in a Brand Kit's Knowledge\n      Vault. The Knowledge Vault is a vector database that stores brand-specific\n      knowledge content which is retrieved during AI content generation to\n      provide accurate, brand-aligned responses. Content ingested via this API\n      is vectorized and made available to the Generative AI API for retrieval\n      augmented generation (RAG) workflows.\n\n  - aid: contentstack:generative-ai-api\n    name: Contentstack Generative AI API\n    tags:\n      - AI\n      - Brand Kit\n      - Content Generation\n      - Generative AI\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://ai.contentstack.com/brand-kits\n    humanURL: https://www.contentstack.com/docs/developers/apis/generative-ai-api\n\
  \    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/generative-ai-api\n        type: Documentation\n      - url: openapi/contentstack-generative-ai-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Contentstack Generative AI API provides an endpoint for generating AI-powered\n      content using a Brand Kit's knowledge vault and voice profiles. It acts as a\n      communication channel between the vector database and large language models,\n      processing prompts with retrieval augmented generation (RAG) to produce brand-aligned\n      content.\n\n  - aid: contentstack:launch-api\n    name: Contentstack Launch API\n    tags:\n      - CI/CD\n      - Deployment\n      - Frontend\n      - Hosting\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://launch-api.contentstack.com\n    humanURL: https://www.contentstack.com/docs/developers/apis/launch-api\n    properties:\n      - url: https://www.contentstack.com/docs/developers/apis/launch-api\n\
  \        type: Documentation\n      - url: openapi/contentstack-launch-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Contentstack Launch API allows developers to programmatically manage web\n      application deployments within Contentstack Launch. It supports full lifecycle\n      management of Launch projects, environments, and deployments, including creating\n      deployments from uploaded build artifacts, monitoring deployment logs, revalidating\n      CDN caches, and retrieving signed upload URLs for build file transfers.\n\ncommon:\n  - url: asyncapi/contentstack-webhooks-asyncapi.yml\n    type: AsyncAPI\n  - url: json-schema/contentstack-entry-schema.json\n    type: JSONSchema\n  - url: json-schema/contentstack-stack-schema.json\n    type: JSONSchema\n  - url: json-schema/contentstack-webhook-payload-schema.json\n    type: JSONSchema\n  - url: json-ld/contentstack-context.jsonld\n    type: JSON-LD\n  - url: vocabulary/contentstack-vocabulary.yml\n    type:\
  \ Vocabulary\n  - url: rules/contentstack-rules.yml\n    type: SpectralRules\n  - url: capabilities/deliver-headless-content.yml\n    type: Capability\n  - url: capabilities/manage-stack-content.yml\n    type: Capability\n  - url: capabilities/personalize-experiences.yml\n    type: Capability\n  - url: capabilities/automate-content-workflows.yml\n    type: Capability\n  - url: capabilities/generate-brand-aligned-ai-content.yml\n    type: Capability\n  - url: capabilities/deploy-launch-frontends.yml\n    type: Capability\n  - url: capabilities/provision-users-via-scim.yml\n    type: Capability\ndescription: >-\n  This document is a detailed reference to Contentstack’s Content Delivery API. Retrieve\n  content from your account and deliver it to web and mobile properties.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/contentstack/refs/heads/main/apis.yml
use_cases: []
---
