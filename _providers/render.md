---
api_count: 1
api_specs:
- filename: render-openapi.json
  format: json
  label: Render API
  slug: render-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/render/refs/heads/main/openapi/render-openapi.json
apis:
- description: The Render Public API enables full programmatic management of Render services, databases, and infrastructure. It supports deploying web services, static sites, background workers, cron jobs, and priva
  name: Render API
  slug: render-api
capabilities:
- description: 'Unified workflow for managing the full lifecycle of Render services: deploying web services and background workers, managing PostgreSQL and Key-Value databases, configuring environments and blueprints'
  name: Render Service Deployment
  slug: service-deployment
common:
- title: ''
  type: Website
  url: https://render.com
- title: ''
  type: Documentation
  url: https://render.com/docs
- title: ''
  type: Documentation
  url: https://render.com/docs/api
- title: ''
  type: Portal
  url: https://dashboard.render.com
- title: ''
  type: Forum
  url: https://community.render.com
- title: ''
  type: Pricing
  url: https://render.com/pricing
- title: ''
  type: Status
  url: https://status.render.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/renderinc
- title: ''
  type: Blog
  url: https://render.com/blog
created: '2026-03-16'
description: Render is a cloud platform for building and running applications and websites with automatic Git-based deployments. It provides managed infrastructure for web services, static sites, background workers, cron jobs, private services, PostgreSQL databases, Redis/Key-Value stores, and persistent disks. The Render API enables programmatic control of all platform resources including service deployments, scaling, environment configuration, custom domains, blueprints, logging, metrics, and workflow automation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 31
  name: Render Context
  property_count: 4
  slug: render-context
layout: provider
modified: '2026-05-02'
name: Render
rules:
- name: Render API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 2
    info: 0
    warn: 3
  slug: render-rules
skills: []
slug: render
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: render\nname: Render\ndescription: >-\n  Render is a cloud platform for building and running applications and websites\n  with automatic Git-based deployments. It provides managed infrastructure for\n  web services, static sites, background workers, cron jobs, private services,\n  PostgreSQL databases, Redis/Key-Value stores, and persistent disks. The Render\n  API enables programmatic control of all platform resources including service\n  deployments, scaling, environment configuration, custom domains, blueprints,\n  logging, metrics, and workflow automation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud\n  - Platform\n  - Deployment\n  - Infrastructure\n  - DevOps\n  - Web Services\n  - Databases\n  - Hosting\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/render/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: render:render-api\n\
  \    name: Render API\n    description: >-\n      The Render Public API enables full programmatic management of Render\n      services, databases, and infrastructure. It supports deploying web\n      services, static sites, background workers, cron jobs, and private\n      services; managing PostgreSQL and Key-Value databases; configuring\n      environment variables, secret files, custom domains, and blueprints;\n      scaling and autoscaling services; streaming logs and metrics; and\n      orchestrating multi-service workflows. Authentication uses a Bearer API\n      key from the Render Dashboard.\n    humanURL: https://render.com/docs/api\n    baseURL: https://api.render.com/v1\n    tags:\n      - Cloud\n      - Platform\n      - Deployment\n      - Infrastructure\n      - DevOps\n    properties:\n      - type: Documentation\n        url: https://render.com/docs/api\n      - type: OpenAPI\n        url: openapi/render-openapi.json\n      - type: OpenAPISpec\n        url: https://api-docs.render.com/v1.0/openapi/render-public-api-1.json\n\
  \      - type: ReferenceDocumentation\n        url: https://api-docs.render.com\n      - type: Rules\n        url: rules/render-rules.yml\n      - type: Capabilities\n        url: capabilities/service-deployment.yaml\n      - type: JSONSchema\n        url: json-schema/render-service-schema.json\n      - type: JSONSchema\n        url: json-schema/render-deploy-schema.json\n      - type: JSONStructure\n        url: json-structure/render-service-structure.json\n      - type: JSONLD\n        url: json-ld/render-context.jsonld\n      - type: Example\n        url: examples/render-create-service-example.json\n      - type: Example\n        url: examples/render-trigger-deploy-example.json\n      - type: Vocabulary\n        url: vocabulary/render-vocabulary.yml\ncommon:\n  - url: https://render.com\n    name: Render\n    type: Website\n    description: Render cloud platform homepage\n  - url: https://render.com/docs\n    name: Render Documentation\n    type: Documentation\n    description: Full\
  \ documentation for Render services and platform features\n  - url: https://render.com/docs/api\n    name: Render API Documentation\n    type: Documentation\n    description: REST API reference for managing Render services programmatically\n  - url: https://dashboard.render.com\n    name: Render Dashboard\n    type: Portal\n    description: Web dashboard for managing Render services and API keys\n  - url: https://community.render.com\n    name: Render Community\n    type: Forum\n    description: Community forum for Render users and developers\n  - url: https://render.com/pricing\n    name: Render Pricing\n    type: Pricing\n    description: Pricing plans for Render services\n  - url: https://status.render.com\n    name: Render Status\n    type: Status\n    description: Real-time status page for Render services\n  - url: https://github.com/renderinc\n    name: Render GitHub\n    type: GitHubOrganization\n    description: Render open-source projects and tools\n  - url: https://render.com/blog\n\
  \    name: Render Blog\n    type: Blog\n    description: Engineering blog and product announcements\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/render/refs/heads/main/apis.yml
tags:
- Cloud
- Platform
- Deployment
- Infrastructure
- DevOps
- Web Services
- Databases
- Hosting
url: https://raw.githubusercontent.com/api-evangelist/render/refs/heads/main/apis.yml
use_cases: []
---
