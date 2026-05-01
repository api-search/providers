---
api_count: 2
api_specs:
- filename: datocms-content-management-api.yml
  format: yaml
  label: DatoCMS Content Management API
  slug: datocms
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datocms/refs/heads/main/openapi/datocms-content-management-api.yml
apis:
- description: The DatoCMS Content Management API (CMA) is a JSON:API REST API for managing items, item types, fields, uploads, environments, webhooks, plugins, workflows, and roles on a DatoCMS site. It exposes 150
  name: DatoCMS Content Management API
  slug: datocms
- description: The DatoCMS Content Delivery API is a CDN-fronted GraphQL endpoint optimized for low-latency reads of published content from client applications such as Jamstack and SSR sites.
  name: DatoCMS Content Delivery API
  slug: datocms-content-delivery-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.datocms.com
- title: ''
  type: Documentation
  url: https://www.datocms.com/docs
- title: ''
  type: Pricing
  url: https://www.datocms.com/pricing
- title: ''
  type: Sign Up
  url: https://dashboard.datocms.com/signup
- title: ''
  type: Login
  url: https://dashboard.datocms.com/login
- title: ''
  type: Blog
  url: https://www.datocms.com/blog
- title: ''
  type: GitHub
  url: https://github.com/datocms
- title: ''
  type: Status
  url: https://status.datocms.com
- title: ''
  type: Support
  url: https://www.datocms.com/support
- title: ''
  type: JSON-LD
  url: json-ld/datocms-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/datocms-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/datocms-capabilities.yml
- title: ''
  type: Rules
  url: rules/datocms-rules.yml
created: '2025-01-08'
description: DatoCMS is a headless content management system that enables users to create, manage, and deliver digital content across websites, mobile apps, and other digital experiences. The platform exposes a JSON:API-based Content Management API for content and schema, and a CDN-fronted GraphQL Content Delivery API for read-heavy client applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Datocms Context
  property_count: 7
  slug: datocms-context
layout: provider
modified: '2026-04-28'
name: DatoCMS
rules:
- name: DatoCMS API Rules
  rule_count: 5
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 2
  slug: datocms-rules
skills: []
slug: datocms
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: datocms\nname: DatoCMS\ndescription: >-\n  DatoCMS is a headless content management system that enables users to\n  create, manage, and deliver digital content across websites, mobile apps,\n  and other digital experiences. The platform exposes a JSON:API-based\n  Content Management API for content and schema, and a CDN-fronted GraphQL\n  Content Delivery API for read-heavy client applications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CMS\n  - Content Delivery\n  - Content Management\n  - GraphQL\n  - Headless CMS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/datocms/refs/heads/main/apis.yml\ncreated: '2025-01-08'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: company\nposition: Consumer\naccess: 3rd-Party\napis:\n  - aid: datocms:datocms\n    name: DatoCMS Content Management API\n    description: >-\n      The DatoCMS Content Management API (CMA) is a JSON:API REST API for\n\
  \      managing items, item types, fields, uploads, environments, webhooks,\n      plugins, workflows, and roles on a DatoCMS site. It exposes 150+\n      endpoints across 40+ resources, authenticated with API tokens.\n    humanURL: https://www.datocms.com/docs/content-management-api\n    baseURL: https://site-api.datocms.com\n    tags:\n      - CMA\n      - CMS\n      - Content Management\n      - Headless CMS\n      - JSON:API\n    properties:\n      - type: Documentation\n        url: https://www.datocms.com/docs/content-management-api\n      - type: Authentication\n        url: https://www.datocms.com/docs/content-management-api/authentication\n      - type: Hyperschema\n        url: https://site-api.datocms.com/docs/site-api-hyperschema.json\n      - type: OpenAPI\n        url: openapi/datocms-content-management-api.yml\n      - type: JSONSchema\n        url: json-schema/item.json\n  - aid: datocms:datocms-content-delivery-api\n    name: DatoCMS Content Delivery API\n    description:\
  \ >-\n      The DatoCMS Content Delivery API is a CDN-fronted GraphQL endpoint\n      optimized for low-latency reads of published content from client\n      applications such as Jamstack and SSR sites.\n    humanURL: https://www.datocms.com/docs/content-delivery-api\n    baseURL: https://graphql.datocms.com\n    tags:\n      - CDN\n      - Content Delivery\n      - GraphQL\n      - Read API\n    properties:\n      - type: Documentation\n        url: https://www.datocms.com/docs/content-delivery-api\ncommon:\n  - type: Website\n    url: https://www.datocms.com\n  - type: Documentation\n    url: https://www.datocms.com/docs\n  - type: Pricing\n    url: https://www.datocms.com/pricing\n  - type: Sign Up\n    url: https://dashboard.datocms.com/signup\n  - type: Login\n    url: https://dashboard.datocms.com/login\n  - type: Blog\n    url: https://www.datocms.com/blog\n  - type: GitHub\n    url: https://github.com/datocms\n  - type: Status\n    url: https://status.datocms.com\n  - type: Support\n\
  \    url: https://www.datocms.com/support\n  - type: JSON-LD\n    url: json-ld/datocms-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/datocms-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/datocms-capabilities.yml\n  - type: Rules\n    url: rules/datocms-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/datocms/refs/heads/main/apis.yml
tags:
- CMS
- Content Delivery
- Content Management
- GraphQL
- Headless CMS
url: https://raw.githubusercontent.com/api-evangelist/datocms/refs/heads/main/apis.yml
use_cases: []
---
