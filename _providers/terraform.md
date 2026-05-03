---
api_count: 2
api_specs:
- filename: hcp-terraform-openapi.yml
  format: yaml
  label: HCP Terraform API
  slug: hcp-terraform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/openapi/hcp-terraform-openapi.yml
- filename: terraform-registry-openapi.yml
  format: yaml
  label: Terraform Registry API
  slug: terraform-registry-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/openapi/terraform-registry-openapi.yml
apis:
- description: The HCP Terraform API provides programmatic access to all HCP Terraform features including workspace management, runs, state versions, policies, teams, organizations, VCS integrations, and the private
  name: HCP Terraform API
  slug: hcp-terraform-api
- description: The Terraform Registry API enables discovery, listing, versioning, and downloading of modules from the public Terraform Registry. It supports searching by keyword, filtering by provider and namespace,
  name: Terraform Registry API
  slug: terraform-registry-api
capabilities:
- description: Unified workflow capability for infrastructure automation with Terraform. Combines HCP Terraform workspace management and run orchestration with module discovery from the Terraform Registry. Enables p
  name: Terraform Infrastructure Automation
  slug: infrastructure-automation
common:
- title: ''
  type: Portal
  url: https://developer.hashicorp.com/terraform
- title: ''
  type: Repository
  url: https://github.com/hashicorp/terraform
- title: ''
  type: Portal
  url: https://registry.terraform.io
- title: ''
  type: Portal
  url: https://app.terraform.io
- title: ''
  type: ChangeLog
  url: https://github.com/hashicorp/terraform/blob/main/CHANGELOG.md
- title: ''
  type: Forum
  url: https://discuss.hashicorp.com/c/terraform-core
- title: ''
  type: Repository
  url: https://github.com/hashicorp/terraform
- title: ''
  type: SDK
  url: https://github.com/hashicorp/terraform-cdk
- title: ''
  type: SDK
  url: https://github.com/hashicorp/go-tfe
created: '2026-03-16'
description: HashiCorp Terraform is an open-source infrastructure-as-code tool that enables teams to define, provision, and manage cloud infrastructure using a declarative configuration language (HCL). HCP Terraform and Terraform Enterprise expose a comprehensive REST API for automating workspace management, runs, state, policies, and access control.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 33
  name: Terraform Context
  property_count: 0
  slug: terraform-context
layout: provider
modified: '2026-05-03'
name: Terraform
rules:
- name: Terraform API Rules
  rule_count: 10
  severity_counts:
    error: 1
    hint: 0
    info: 1
    warn: 8
  slug: hcp-terraform-rules
skills: []
slug: terraform
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: terraform\nname: Terraform\ndescription: >-\n  HashiCorp Terraform is an open-source infrastructure-as-code tool that enables\n  teams to define, provision, and manage cloud infrastructure using a declarative\n  configuration language (HCL). HCP Terraform and Terraform Enterprise expose a\n  comprehensive REST API for automating workspace management, runs, state, policies,\n  and access control.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Infrastructure As Code\n  - Cloud Infrastructure\n  - DevOps\n  - Open Source\n  - HashiCorp\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: terraform:hcp-terraform-api\n    name: HCP Terraform API\n    description: >-\n      The HCP Terraform API provides programmatic access to all HCP Terraform\n      features including workspace management,\
  \ runs, state versions, policies,\n      teams, organizations, VCS integrations, and the private module registry.\n      The API follows the JSON API specification and uses bearer token authentication.\n    humanURL: https://developer.hashicorp.com/terraform/cloud-docs/api-docs\n    baseURL: https://app.terraform.io/api/v2\n    tags:\n      - Infrastructure As Code\n      - Workspaces\n      - Runs\n      - State Management\n      - Policy\n    properties:\n      - url: https://developer.hashicorp.com/terraform/cloud-docs/api-docs\n        type: Documentation\n      - url: https://developer.hashicorp.com/terraform/cloud-docs/api-docs/workspaces\n        type: Documentation\n      - url: https://developer.hashicorp.com/terraform/cloud-docs/api-docs/run\n        type: Documentation\n      - url: https://developer.hashicorp.com/terraform/cloud-docs/api-docs/state-versions\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/openapi/hcp-terraform-openapi.yml\n\
  \        type: OpenAPI\n  - aid: terraform:terraform-registry-api\n    name: Terraform Registry API\n    description: >-\n      The Terraform Registry API enables discovery, listing, versioning, and\n      downloading of modules from the public Terraform Registry. It supports\n      searching by keyword, filtering by provider and namespace, and retrieving\n      download metrics.\n    humanURL: https://developer.hashicorp.com/terraform/registry/api-docs\n    baseURL: https://registry.terraform.io\n    tags:\n      - Registry\n      - Modules\n      - Providers\n      - Discovery\n    properties:\n      - url: https://developer.hashicorp.com/terraform/registry/api-docs\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/openapi/terraform-registry-openapi.yml\n        type: OpenAPI\ncommon:\n  - name: HashiCorp Developer Portal\n    url: https://developer.hashicorp.com/terraform\n    type: Portal\n  - name: Terraform GitHub\
  \ Organization\n    url: https://github.com/hashicorp/terraform\n    type: Repository\n  - name: Terraform Registry\n    url: https://registry.terraform.io\n    type: Portal\n  - name: HCP Terraform\n    url: https://app.terraform.io\n    type: Portal\n  - name: Terraform Changelog\n    url: https://github.com/hashicorp/terraform/blob/main/CHANGELOG.md\n    type: ChangeLog\n  - name: Terraform Community Forum\n    url: https://discuss.hashicorp.com/c/terraform-core\n    type: Forum\n  - name: Terraform GitHub CLI\n    url: https://github.com/hashicorp/terraform\n    type: Repository\n  - name: Terraform CDK\n    url: https://github.com/hashicorp/terraform-cdk\n    type: SDK\n  - name: Terraform Go SDK\n    url: https://github.com/hashicorp/go-tfe\n    type: SDK\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/apis.yml
tags:
- Infrastructure As Code
- Cloud Infrastructure
- DevOps
- Open Source
- HashiCorp
url: https://raw.githubusercontent.com/api-evangelist/terraform/refs/heads/main/apis.yml
use_cases: []
---
