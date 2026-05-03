---
api_count: 2
api_specs:
- filename: pulumi-spec.json
  format: json
  label: Pulumi Cloud REST API
  slug: pulumi-cloud
  spec_type: OpenAPI
  url: https://api.pulumi.com/api/openapi/pulumi-spec.json
apis:
- description: The Pulumi Cloud REST API exposes 446+ endpoints across 28 categories, including access tokens, AI/agents, audit logs, change gates and requests, deployments, environments (ESC), insights, OIDC issuer
  name: Pulumi Cloud REST API
  slug: pulumi-cloud
- description: The Automation API enables you to build custom cloud interfaces for your technical end users. Build self-service developer portals, CLIs, frameworks, and more, programmatically driving Pulumi from Go,
  name: Pulumi Automation API
  slug: automation-api
common:
- title: ''
  type: Website
  url: https://www.pulumi.com
- title: ''
  type: Documentation
  url: https://www.pulumi.com/docs/
- title: ''
  type: Blog
  url: https://www.pulumi.com/blog/
- title: ''
  type: GitHub Organization
  url: https://github.com/pulumi
- title: ''
  type: Sign Up
  url: https://app.pulumi.com/signup
- title: ''
  type: Login
  url: https://app.pulumi.com/signin
- title: ''
  type: Pricing
  url: https://www.pulumi.com/pricing/
- title: ''
  type: Status
  url: https://status.pulumi.com/
- title: ''
  type: Terms of Service
  url: https://www.pulumi.com/terms/
- title: ''
  type: Privacy Policy
  url: https://www.pulumi.com/privacy/
- title: ''
  type: Authentication
  url: https://app.pulumi.com/account/tokens
created: '2025-01-08'
description: Pulumi is a modern infrastructure as code platform that allows you to use familiar programming languages to build, deploy, and manage cloud infrastructure. The Pulumi Cloud REST API enables programmatic access to manage organizations, stacks, deployments, environments, policy packs, webhooks, and other Pulumi Cloud resources.
features: []
image: https://www.pulumi.com/logos/brand/logo-on-white.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Pulumi
skills: []
slug: pulumi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: pulumi\nname: Pulumi\ndescription: >-\n  Pulumi is a modern infrastructure as code platform that allows you to use\n  familiar programming languages to build, deploy, and manage cloud\n  infrastructure. The Pulumi Cloud REST API enables programmatic access to\n  manage organizations, stacks, deployments, environments, policy packs,\n  webhooks, and other Pulumi Cloud resources.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://www.pulumi.com/logos/brand/logo-on-white.png\ntags:\n  - Automation\n  - Cloud\n  - DevOps\n  - Infrastructure as Code\n  - Multi-Cloud\n  - Stacks\n  - Deployments\n  - Policy\ncreated: '2025-01-08'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/pulumi/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: pulumi:pulumi-cloud\n    name: Pulumi Cloud REST API\n    description: >-\n      The Pulumi Cloud REST API exposes 446+ endpoints across 28 categories,\n      including access\
  \ tokens, AI/agents, audit logs, change gates and\n      requests, deployments, environments (ESC), insights, OIDC issuers,\n      organizations, policy groups and packs, registry, resource search,\n      stacks, and webhooks. Authentication is via the `Authorization: token\n      {token}` header.\n    humanURL: https://www.pulumi.com/docs/pulumi-cloud/cloud-rest-api/\n    baseURL: https://api.pulumi.com\n    tags:\n      - Cloud\n      - DevOps\n      - Infrastructure as Code\n      - Stacks\n      - Deployments\n    properties:\n      - type: Documentation\n        url: https://www.pulumi.com/docs/pulumi-cloud/cloud-rest-api/\n      - type: OpenAPI\n        url: https://api.pulumi.com/api/openapi/pulumi-spec.json\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/pulumi/refs/heads/main/openapi/pulumi-openapi.json\n      - type: Authentication\n        url: https://www.pulumi.com/docs/pulumi-cloud/access-management/access-tokens/\n  - aid:\
  \ pulumi:automation-api\n    name: Pulumi Automation API\n    description: >-\n      The Automation API enables you to build custom cloud interfaces for your\n      technical end users. Build self-service developer portals, CLIs,\n      frameworks, and more, programmatically driving Pulumi from Go, Node.js,\n      Python, .NET, and Java.\n    humanURL: https://www.pulumi.com/automation/\n    tags:\n      - Automation\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://www.pulumi.com/automation/\n      - type: GitHub\n        url: https://github.com/pulumi/pulumi\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - url: https://www.pulumi.com\n    type: Website\n  - url: https://www.pulumi.com/docs/\n    type: Documentation\n  - url: https://www.pulumi.com/blog/\n    type: Blog\n  - url: https://github.com/pulumi\n    type: GitHub Organization\n  - url: https://app.pulumi.com/signup\n    type: Sign Up\n  - url: https://app.pulumi.com/signin\n\
  \    type: Login\n  - url: https://www.pulumi.com/pricing/\n    type: Pricing\n  - url: https://status.pulumi.com/\n    type: Status\n  - url: https://www.pulumi.com/terms/\n    type: Terms of Service\n  - url: https://www.pulumi.com/privacy/\n    type: Privacy Policy\n  - url: https://app.pulumi.com/account/tokens\n    type: Authentication\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/pulumi/refs/heads/main/apis.yml
tags:
- Automation
- Cloud
- DevOps
- Infrastructure as Code
- Multi-Cloud
- Stacks
- Deployments
- Policy
url: https://raw.githubusercontent.com/api-evangelist/pulumi/refs/heads/main/apis.yml
use_cases: []
---
