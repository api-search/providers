---
api_count: 2
apis:
- description: The Cortex REST API exposes the service catalog, scorecards, initiatives, entity relationships and dependencies, on-call assignments, custom data, and deployments managed in a Cortex workspace. Authen
  name: Cortex REST API
  slug: cortex-rest-api
- description: Cortex exposes a Model Context Protocol (MCP) server that lets AI coding assistants and IDE agents query the service catalog, look up ownership, check scorecard scores, and run workflows directly from
  name: Cortex MCP Server
  slug: cortex-mcp
common:
- title: ''
  type: Website
  url: https://www.cortex.io/
- title: ''
  type: Documentation
  url: https://docs.cortex.io/
- title: ''
  type: Product
  url: https://www.cortex.io/product
- title: ''
  type: ServiceCatalog
  url: https://www.cortex.io/product/service-catalog
- title: ''
  type: Scorecards
  url: https://www.cortex.io/product/scorecards
- title: ''
  type: Workflows
  url: https://www.cortex.io/product/workflows
- title: ''
  type: Pricing
  url: https://www.cortex.io/pricing
- title: ''
  type: Customers
  url: https://www.cortex.io/customers
- title: ''
  type: Blog
  url: https://www.cortex.io/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/cortexapps
- title: ''
  type: ChangeLog
  url: https://docs.cortex.io/changelog
- title: ''
  type: Status
  url: https://status.cortex.io/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/cortexapp/
- title: ''
  type: Twitter
  url: https://twitter.com/cortexapp
- title: ''
  type: Contact
  url: https://www.cortex.io/contact
created: '2026-03-16'
description: Cortex is an Engineering Operations (EngOps) platform and internal developer portal that helps engineering teams catalog services, enforce production readiness with scorecards, automate self-service workflows, and surface engineering intelligence across their organization. Cortex centralizes data from observability, CI/CD, source control, on-call, and SaaS tooling and exposes it through a REST API used to integrate the catalog with platform engineering and SRE workflows.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Cortex
skills: []
slug: cortex
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cortex\nname: Cortex\nx-type: company\ndescription: >-\n  Cortex is an Engineering Operations (EngOps) platform and internal developer\n  portal that helps engineering teams catalog services, enforce production\n  readiness with scorecards, automate self-service workflows, and surface\n  engineering intelligence across their organization. Cortex centralizes data\n  from observability, CI/CD, source control, on-call, and SaaS tooling and\n  exposes it through a REST API used to integrate the catalog with platform\n  engineering and SRE workflows.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cortex/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess: Public\nposition: Provider\ntags:\n  - Catalog\n  - Custom Data\n  - Dependencies\n  - Deploys\n  - Developer Experience\n  - EngOps\n  - Engineering Intelligence\n  - Initiatives\n  - Internal Developer Portal\n  - On-call\n  - Platform\
  \ Engineering\n  - Scorecards\n  - Service Catalog\n  - SRE\n  - Workflows\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\napis:\n  - aid: cortex:cortex-rest-api\n    name: Cortex REST API\n    description: >-\n      The Cortex REST API exposes the service catalog, scorecards, initiatives,\n      entity relationships and dependencies, on-call assignments, custom data,\n      and deployments managed in a Cortex workspace. Authentication is via\n      personal or service access tokens, and entity descriptors can be\n      retrieved as OpenAPI documents through a per-entity endpoint.\n    humanURL: https://docs.cortex.io/\n    properties:\n      - type: Documentation\n        url: https://docs.cortex.io/\n      - type: GettingStarted\n        url: https://docs.cortex.io/docs/getting-started\n      - type: APIReference\n        url: https://docs.cortex.io/reference\n    tags:\n      - Catalog\n      - Dependencies\n      - Deploys\n      - REST\n      - Scorecards\n\
  \  - aid: cortex:cortex-mcp\n    name: Cortex MCP Server\n    description: >-\n      Cortex exposes a Model Context Protocol (MCP) server that lets AI coding\n      assistants and IDE agents query the service catalog, look up ownership,\n      check scorecard scores, and run workflows directly from developer tools.\n    humanURL: https://docs.cortex.io/\n    properties:\n      - type: Documentation\n        url: https://docs.cortex.io/\n    tags:\n      - AI\n      - IDE\n      - MCP\ncommon:\n  - type: Website\n    url: https://www.cortex.io/\n  - type: Documentation\n    url: https://docs.cortex.io/\n  - type: Product\n    url: https://www.cortex.io/product\n  - type: ServiceCatalog\n    url: https://www.cortex.io/product/service-catalog\n  - type: Scorecards\n    url: https://www.cortex.io/product/scorecards\n  - type: Workflows\n    url: https://www.cortex.io/product/workflows\n  - type: Pricing\n    url: https://www.cortex.io/pricing\n  - type: Customers\n    url: https://www.cortex.io/customers\n\
  \  - type: Blog\n    url: https://www.cortex.io/blog\n  - type: GitHubOrganization\n    url: https://github.com/cortexapps\n  - type: Integrations\n    url: https://docs.cortex.io/docs/integrations\n  - type: ChangeLog\n    url: https://docs.cortex.io/changelog\n  - type: Status\n    url: https://status.cortex.io/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/cortexapp/\n  - type: Twitter\n    url: https://twitter.com/cortexapp\n  - type: Contact\n    url: https://www.cortex.io/contact\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cortex/refs/heads/main/apis.yml
tags:
- Catalog
- Custom Data
- Dependencies
- Deploys
- Developer Experience
- EngOps
- Engineering Intelligence
- Initiatives
- Internal Developer Portal
- On-call
- Platform Engineering
- Scorecards
- Service Catalog
- SRE
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/cortex/refs/heads/main/apis.yml
use_cases: []
---
