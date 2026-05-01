---
api_count: 2
api_specs:
- filename: dagster-external-assets-rest-api-openapi.yml
  format: yaml
  label: Dagster External Assets REST API
  slug: external-assets-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dagster/refs/heads/main/openapi/dagster-external-assets-rest-api-openapi.yml
apis:
- description: The Dagster GraphQL API allows clients to interact with Dagster programmatically. It can be used to query information about Dagster runs, retrieve metadata about repositories, jobs, and ops, and launc
  name: Dagster GraphQL API
  slug: graphql-api
- description: The Dagster External Assets REST API provides endpoints to report asset materializations, asset check evaluations, and asset observations for external assets back to Dagster. This allows you to notify
  name: Dagster External Assets REST API
  slug: external-assets-rest-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://dagster.cloud/
- title: ''
  type: Sign Up
  url: https://dagster.cloud/signup
- title: ''
  type: Documentation
  url: https://docs.dagster.io/
- title: ''
  type: API Reference
  url: https://docs.dagster.io/api
- title: ''
  type: Getting Started
  url: https://docs.dagster.io/getting-started/quickstart
- title: ''
  type: Blog
  url: https://dagster.io/blog
- title: ''
  type: Change Log
  url: https://docs.dagster.io/about/changelog
- title: ''
  type: Pricing
  url: https://dagster.io/pricing
- title: ''
  type: Support
  url: https://dagster.io/support
- title: ''
  type: Community
  url: https://dagster.io/community
- title: ''
  type: Slack
  url: https://dagster.io/slack
- title: ''
  type: GitHub Organization
  url: https://github.com/dagster-io
- title: ''
  type: GitHub Repository
  url: https://github.com/dagster-io/dagster
- title: ''
  type: Python SDK
  url: https://pypi.org/project/dagster/
- title: ''
  type: Privacy Policy
  url: https://dagster.io/privacy
- title: ''
  type: Terms of Service
  url: https://dagster.io/terms
- title: ''
  type: Security
  url: https://dagster.io/security
- title: ''
  type: About
  url: https://dagster.io/company/about-us
- title: ''
  type: Contact
  url: https://dagster.io/contact
- title: ''
  type: JSON-LD
  url: json-ld/dagster-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/dagster-vocabulary.yml
created: '2026-03-03'
description: Dagster is a data orchestration platform centered on software-defined assets with strong observability and testing support. It exposes a GraphQL API for programmatic interaction with Dagster instances and a REST API for reporting external asset materializations, checks, and observations from outside pipelines.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Dagster Context
  property_count: 8
  slug: dagster-context
layout: provider
modified: '2026-04-28'
name: Dagster
rules:
- name: Dagster API Rules
  rule_count: 5
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 3
  slug: dagster-external-assets-rest-api-rules
skills: []
slug: dagster
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dagster\nname: Dagster\nsegments:\n  - Workflows\ndescription: >-\n  Dagster is a data orchestration platform centered on software-defined assets\n  with strong observability and testing support. It exposes a GraphQL API for\n  programmatic interaction with Dagster instances and a REST API for reporting\n  external asset materializations, checks, and observations from outside\n  pipelines.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Engineering\n  - Data Orchestration\n  - Data Pipelines\n  - ETL\n  - Workflows\n  - Assets\n  - GraphQL\ncreated: '2026-03-03'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/dagster/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: dagster:graphql-api\n    name: Dagster GraphQL API\n    description: >-\n      The Dagster GraphQL API allows clients to interact with Dagster\n      programmatically.\
  \ It can be used to query information about Dagster runs,\n      retrieve metadata about repositories, jobs, and ops, and launch runs.\n      The GraphQL endpoint is served by the webserver at the /graphql route.\n    humanURL: https://docs.dagster.io/api/graphql\n    tags:\n      - Data Orchestration\n      - GraphQL\n      - Jobs\n      - Runs\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.dagster.io/api/graphql\n      - type: GraphQL Playground\n        url: https://docs.dagster.io/api/graphql\n  - aid: dagster:external-assets-rest-api\n    name: Dagster External Assets REST API\n    description: >-\n      The Dagster External Assets REST API provides endpoints to report asset\n      materializations, asset check evaluations, and asset observations for\n      external assets back to Dagster. This allows you to notify Dagster that\n      an external asset has been updated and include metadata about the event.\n    humanURL: https://docs.dagster.io/api/rest-apis/external-assets-rest-api\n\
  \    tags:\n      - Assets\n      - Data Orchestration\n      - Materializations\n      - Observations\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://docs.dagster.io/api/rest-apis/external-assets-rest-api\n      - type: OpenAPI\n        url: openapi/dagster-external-assets-rest-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/asset-materialization.json\n      - type: JSONSchema\n        url: json-schema/asset-check.json\n      - type: JSONSchema\n        url: json-schema/asset-observation.json\n      - type: Rules\n        url: rules/dagster-external-assets-rest-api-rules.yml\n      - type: Capabilities\n        url: capabilities/dagster-external-assets-rest-api-capabilities.yml\ncommon:\n  - type: Portal\n    url: https://dagster.cloud/\n  - type: Sign Up\n    url: https://dagster.cloud/signup\n  - type: Documentation\n    url: https://docs.dagster.io/\n  - type: API Reference\n    url: https://docs.dagster.io/api\n  - type: Getting\
  \ Started\n    url: https://docs.dagster.io/getting-started/quickstart\n  - type: Blog\n    url: https://dagster.io/blog\n  - type: Change Log\n    url: https://docs.dagster.io/about/changelog\n  - type: Pricing\n    url: https://dagster.io/pricing\n  - type: Support\n    url: https://dagster.io/support\n  - type: Community\n    url: https://dagster.io/community\n  - type: Slack\n    url: https://dagster.io/slack\n  - type: GitHub Organization\n    url: https://github.com/dagster-io\n  - type: GitHub Repository\n    url: https://github.com/dagster-io/dagster\n  - type: Integrations\n    url: https://docs.dagster.io/integrations/libraries\n  - type: Python SDK\n    url: https://pypi.org/project/dagster/\n  - type: Privacy Policy\n    url: https://dagster.io/privacy\n  - type: Terms of Service\n    url: https://dagster.io/terms\n  - type: Security\n    url: https://dagster.io/security\n  - type: About\n    url: https://dagster.io/company/about-us\n  - type: Contact\n    url: https://dagster.io/contact\n\
  \  - type: JSON-LD\n    url: json-ld/dagster-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/dagster-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nxType: opensource\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dagster/refs/heads/main/apis.yml
tags:
- Data Engineering
- Data Orchestration
- Data Pipelines
- ETL
- Workflows
- Assets
- GraphQL
url: https://raw.githubusercontent.com/api-evangelist/dagster/refs/heads/main/apis.yml
use_cases: []
---
