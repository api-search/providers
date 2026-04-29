---
api_count: 4
apis:
- description: REST API for managing nodes, cookbooks, roles, environments, data bags, clients, and users on the Chef Infra Server. Authentication uses Chef signed-header authentication with an RSA client key.
  name: Chef Infra Server API
  slug: chef-infra-server-api
- description: 'REST API for Chef Automate providing visibility into infrastructure convergence, compliance scans, and application deployment. Includes compliance profiles, scan jobs, reports, IAM, and configuration '
  name: Chef Automate API
  slug: chef-automate-api
- description: REST API for Chef Habitat Builder, the package management service for Habitat application packages. Manages origins, packages, channels, and deployment events.
  name: Chef Habitat Builder API
  slug: chef-habitat-builder-api
- description: InSpec is an open-source language and runner for security and compliance testing. It is consumed via the InSpec CLI and Ruby DSL, and surfaced inside Chef Automate as compliance profiles, scan jobs, a
  name: Chef InSpec
  slug: chef-inspec
common:
- title: ''
  type: Website
  url: https://www.chef.io/
- title: ''
  type: Documentation
  url: https://docs.chef.io/
- title: ''
  type: GettingStarted
  url: https://docs.chef.io/
- title: ''
  type: Blog
  url: https://www.chef.io/blog
- title: ''
  type: GitHub
  url: https://github.com/chef
- title: ''
  type: Support
  url: https://www.chef.io/support
- title: ''
  type: Training
  url: https://training.chef.io/
- title: ''
  type: Community
  url: https://community.chef.io/
- title: ''
  type: Status
  url: https://status.chef.io/
- title: ''
  type: TermsOfService
  url: https://www.chef.io/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.chef.io/privacy-policy
- title: ''
  type: JSONLD
  url: json-ld/chef-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/chef-node-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/chef-role-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/chef-compliance-profile-schema.json
- title: ''
  type: Spectral
  url: spectral/chef-spectral.yml
- title: ''
  type: NaftikoCapabilities
  url: naftiko/chef-capabilities.yml
created: '2024-01-15'
description: Chef (Progress Chef) provides infrastructure automation, compliance, and application delivery tooling. Chef exposes REST APIs for the Infra Server (managing nodes, cookbooks, roles, environments, and data bags), Chef Automate (visibility into convergence, compliance, and deployment), Habitat Builder (application packaging and delivery), and InSpec (a language and runner for security and compliance testing).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Chef Context
  property_count: 7
  slug: chef-context
layout: provider
modified: '2026-04-23'
name: Chef
skills: []
slug: chef
solutions: []
source_yaml: "aid: chef\nname: Chef\ndescription: >-\n  Chef (Progress Chef) provides infrastructure automation, compliance, and\n  application delivery tooling. Chef exposes REST APIs for the Infra Server\n  (managing nodes, cookbooks, roles, environments, and data bags), Chef\n  Automate (visibility into convergence, compliance, and deployment),\n  Habitat Builder (application packaging and delivery), and InSpec (a\n  language and runner for security and compliance testing).\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/chef/refs/heads/main/apis.yml\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - Application Delivery\n  - Automation\n  - Compliance\n  - Configuration Management\n  - DevOps\n  - DevSecOps\n  - Habitat\n  - Infrastructure as Code\n  - InSpec\ncreated: '2024-01-15'\nmodified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid: chef:chef-infra-server-api\n\
  \    name: Chef Infra Server API\n    description: >-\n      REST API for managing nodes, cookbooks, roles, environments, data bags,\n      clients, and users on the Chef Infra Server. Authentication uses Chef\n      signed-header authentication with an RSA client key.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.chef.io/server/api_chef_server/\n    baseURL: https://chef.example.com/organizations/example\n    tags:\n      - Configuration Management\n      - Infrastructure\n    properties:\n      - type: Documentation\n        url: https://docs.chef.io/server/api_chef_server/\n      - type: Authentication\n        url: https://docs.chef.io/server/server_security/\n      - type: OpenAPI\n        url: openapi/chef-infra-server-api-openapi.yml\n  - aid: chef:chef-automate-api\n    name: Chef Automate API\n    description: >-\n      REST API for Chef Automate providing visibility into infrastructure\n      convergence, compliance\
  \ scans, and application deployment. Includes\n      compliance profiles, scan jobs, reports, IAM, and configuration\n      management endpoints.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.chef.io/automate/api/\n    baseURL: https://automate.example.com/api/v0\n    tags:\n      - Automation\n      - Compliance\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://docs.chef.io/automate/api/\n      - type: Reference\n        url: https://docs.chef.io/automate/api_swagger/\n      - type: Authentication\n        url: https://docs.chef.io/automate/api_tokens/\n      - type: OpenAPI\n        url: openapi/chef-automate-api-openapi.yml\n  - aid: chef:chef-habitat-builder-api\n    name: Chef Habitat Builder API\n    description: >-\n      REST API for Chef Habitat Builder, the package management service\n      for Habitat application packages. Manages origins, packages,\n      channels, and\
  \ deployment events.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.habitat.sh/docs/using-builder/\n    baseURL: https://bldr.habitat.sh/v1\n    tags:\n      - Application Packaging\n      - Deployment\n      - Habitat\n    properties:\n      - type: Documentation\n        url: https://docs.habitat.sh/docs/using-builder/\n      - type: Authentication\n        url: https://docs.habitat.sh/docs/using-builder/\n      - type: OpenAPI\n        url: openapi/chef-habitat-builder-api-openapi.yml\n  - aid: chef:chef-inspec\n    name: Chef InSpec\n    description: >-\n      InSpec is an open-source language and runner for security and\n      compliance testing. It is consumed via the InSpec CLI and Ruby DSL,\n      and surfaced inside Chef Automate as compliance profiles, scan jobs,\n      and reports.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.chef.io/inspec/\n\
  \    tags:\n      - Compliance\n      - Security\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://docs.chef.io/inspec/\n      - type: GitHub\n        url: https://github.com/inspec/inspec\ncommon:\n  - type: Website\n    url: https://www.chef.io/\n  - type: Documentation\n    url: https://docs.chef.io/\n  - type: GettingStarted\n    url: https://docs.chef.io/\n  - type: Blog\n    url: https://www.chef.io/blog\n  - type: GitHub\n    url: https://github.com/chef\n  - type: Support\n    url: https://www.chef.io/support\n  - type: Training\n    url: https://training.chef.io/\n  - type: Community\n    url: https://community.chef.io/\n  - type: Status\n    url: https://status.chef.io/\n  - type: TermsOfService\n    url: https://www.chef.io/terms-of-service\n  - type: PrivacyPolicy\n    url: https://www.chef.io/privacy-policy\n  - type: JSONLD\n    url: json-ld/chef-context.jsonld\n  - type: JSONSchema\n    url: json-schema/chef-node-schema.json\n  - type:\
  \ JSONSchema\n    url: json-schema/chef-role-schema.json\n  - type: JSONSchema\n    url: json-schema/chef-compliance-profile-schema.json\n  - type: Spectral\n    url: spectral/chef-spectral.yml\n  - type: NaftikoCapabilities\n    url: naftiko/chef-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chef/refs/heads/main/apis.yml
tags:
- Application Delivery
- Automation
- Compliance
- Configuration Management
- DevOps
- DevSecOps
- Habitat
- Infrastructure as Code
- InSpec
url: https://raw.githubusercontent.com/api-evangelist/chef/refs/heads/main/apis.yml
use_cases: []
---
