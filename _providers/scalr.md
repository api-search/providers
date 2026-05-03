---
api_count: 4
api_specs:
- filename: scalr-user-openapi.yml
  format: yaml
  label: Scalr User API
  slug: scalr-user-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/openapi/scalr-user-openapi.yml
- filename: scalr-account-openapi.yml
  format: yaml
  label: Scalr Account API
  slug: scalr-account-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/openapi/scalr-account-openapi.yml
- filename: scalr-global-openapi.yml
  format: yaml
  label: Scalr Global API
  slug: scalr-global-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/openapi/scalr-global-openapi.yml
apis:
- description: The Scalr User API provides programmatic access to user-level resources including farms, farm roles, servers, events, cloud locations, cost centers, and scaling metrics. This is the legacy cloud manag
  name: Scalr User API
  slug: scalr-user-api
- description: The Scalr Account API provides programmatic access to account-level resources including environments, roles, images, orchestration rules, and account-wide configuration. This is the legacy cloud manag
  name: Scalr Account API
  slug: scalr-account-api
- description: The Scalr Global API provides programmatic access to global-level resources including images and roles that span the entire Scalr installation.
  name: Scalr Global API
  slug: scalr-global-api
- description: The Scalr IaC Management API (TFC-compatible) provides programmatic control over workspaces, environments, runs, state, variables, policies, and provider configurations. Fully compatible with Terrafor
  name: Scalr IaC Management API
  slug: scalr-iac-api
capabilities:
- description: 'Unified workflow capability for managing Terraform and OpenTofu infrastructure as code operations through Scalr''s remote execution platform. Combines workspace management, environment management, run '
  name: Scalr Infrastructure as Code
  slug: infrastructure-as-code
common:
- title: ''
  type: Website
  url: https://scalr.com/
- title: ''
  type: Documentation
  url: https://docs.scalr.io/
- title: ''
  type: API Reference
  url: https://docs.scalr.io/reference/overview-1
- title: ''
  type: API Explorer
  url: https://api-explorer.scalr.com/
- title: ''
  type: GitHub
  url: https://github.com/scalr
- title: ''
  type: Blog
  url: https://scalr.com/blog/
- title: ''
  type: Changelog
  url: https://updates.scalr.io/
- title: ''
  type: MCP Server
  url: https://docs.scalr.io/docs/mcp-server
- title: ''
  type: Terraform Provider
  url: https://registry.terraform.io/providers/Scalr/scalr/latest/docs
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/vocabulary/scalr-vocabulary.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/json-schema/scalr-workspace-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/json-schema/scalr-run-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/json-ld/scalr-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/rules/scalr-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/capabilities/infrastructure-as-code.yaml
created: '2026-05-02'
description: Scalr is an enterprise-grade, drop-in replacement for Terraform Cloud and a remote Terraform operations backend that provides cost estimation, policy enforcement, and collaborative infrastructure management. Scalr features a hierarchical account-environment-workspace model, full compatibility with the TFC API and Terraform/OpenTofu CLI, OIDC authentication, GitOps workflows, OPA policy enforcement, and a comprehensive REST API for managing infrastructure as code operations at scale.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 1
  name: Scalr Context
  property_count: 27
  slug: scalr-context
layout: provider
modified: '2026-05-02'
name: Scalr
rules:
- name: Scalr API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 2
    info: 2
    warn: 4
  slug: scalr-rules
skills: []
slug: scalr
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scalr\nname: Scalr\ndescription: >-\n  Scalr is an enterprise-grade, drop-in replacement for Terraform Cloud and a remote\n  Terraform operations backend that provides cost estimation, policy enforcement, and\n  collaborative infrastructure management. Scalr features a hierarchical account-environment-workspace\n  model, full compatibility with the TFC API and Terraform/OpenTofu CLI, OIDC authentication,\n  GitOps workflows, OPA policy enforcement, and a comprehensive REST API for managing\n  infrastructure as code operations at scale.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - FinOps\n  - GitOps\n  - Infrastructure as Code\n  - Kubernetes\n  - OPA\n  - OpenTofu\n  - Policy\n  - Terraform\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/apis.yml\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: scalr:scalr-user-api\n    name: Scalr\
  \ User API\n    description: >-\n      The Scalr User API provides programmatic access to user-level resources including\n      farms, farm roles, servers, events, cloud locations, cost centers, and scaling\n      metrics. This is the legacy cloud management API (v1beta0) for managing cloud\n      infrastructure resources across multiple cloud providers.\n    humanURL: https://api-explorer.scalr.com/\n    tags:\n      - Cloud Management\n      - Farms\n      - Infrastructure\n      - Scalr\n      - Servers\n    properties:\n      - type: Documentation\n        url: https://api-explorer.scalr.com/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/openapi/scalr-user-openapi.yml\n  - aid: scalr:scalr-account-api\n    name: Scalr Account API\n    description: >-\n      The Scalr Account API provides programmatic access to account-level resources\n      including environments, roles, images, orchestration rules, and account-wide\n\
  \      configuration. This is the legacy cloud management API (v1beta0).\n    humanURL: https://api-explorer.scalr.com/\n    tags:\n      - Account Management\n      - Cloud Management\n      - Environments\n      - Roles\n      - Scalr\n    properties:\n      - type: Documentation\n        url: https://api-explorer.scalr.com/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/openapi/scalr-account-openapi.yml\n  - aid: scalr:scalr-global-api\n    name: Scalr Global API\n    description: >-\n      The Scalr Global API provides programmatic access to global-level resources\n      including images and roles that span the entire Scalr installation.\n    humanURL: https://api-explorer.scalr.com/\n    tags:\n      - Cloud Management\n      - Global\n      - Images\n      - Roles\n      - Scalr\n    properties:\n      - type: Documentation\n        url: https://api-explorer.scalr.com/\n      - type: OpenAPI\n        url:\
  \ >-\n          https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/openapi/scalr-global-openapi.yml\n  - aid: scalr:scalr-iac-api\n    name: Scalr IaC Management API\n    description: >-\n      The Scalr IaC Management API (TFC-compatible) provides programmatic control over\n      workspaces, environments, runs, state, variables, policies, and provider configurations.\n      Fully compatible with Terraform Cloud API and Terraform/OpenTofu CLI. Authenticates\n      using Bearer tokens (personal or service account). Supports OIDC for GitHub, GitLab,\n      AWS, Azure, and other identity providers.\n    humanURL: https://docs.scalr.io/reference/overview-1\n    tags:\n      - Infrastructure as Code\n      - OpenTofu\n      - Policy\n      - Runs\n      - Scalr\n      - Terraform\n      - Workspaces\n    properties:\n      - type: Documentation\n        url: https://docs.scalr.io/reference/overview-1\n      - type: Getting Started\n        url: https://docs.scalr.io/docs/introduction\n\
  \      - type: Authentication\n        url: https://docs.scalr.io/reference/api-tokens\ncommon:\n  - type: Website\n    url: https://scalr.com/\n  - type: Documentation\n    url: https://docs.scalr.io/\n  - type: API Reference\n    url: https://docs.scalr.io/reference/overview-1\n  - type: API Explorer\n    url: https://api-explorer.scalr.com/\n  - type: GitHub\n    url: https://github.com/scalr\n  - type: Blog\n    url: https://scalr.com/blog/\n  - type: Changelog\n    url: https://updates.scalr.io/\n  - type: MCP Server\n    url: https://docs.scalr.io/docs/mcp-server\n  - type: Terraform Provider\n    url: https://registry.terraform.io/providers/Scalr/scalr/latest/docs\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/vocabulary/scalr-vocabulary.yml\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/json-schema/scalr-workspace-schema.json\n  - type: JSONSchema\n\
  \    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/json-schema/scalr-run-schema.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/json-ld/scalr-context.jsonld\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/rules/scalr-rules.yml\n  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/capabilities/infrastructure-as-code.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/apis.yml
tags:
- FinOps
- GitOps
- Infrastructure as Code
- Kubernetes
- OPA
- OpenTofu
- Policy
- Terraform
url: https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/apis.yml
use_cases: []
---
