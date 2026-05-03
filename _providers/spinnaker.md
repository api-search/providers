---
api_count: 1
api_specs:
- filename: spinnaker-gate-openapi.yml
  format: yaml
  label: Spinnaker Gate API
  slug: spinnaker-gate-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spinnaker/refs/heads/main/openapi/spinnaker-gate-openapi.yml
apis:
- description: Gate is the Spinnaker API Gateway — the primary REST interface for all Spinnaker operations including application management, pipeline execution, cluster management, and infrastructure discovery. Gate
  name: Spinnaker Gate API
  slug: spinnaker-gate-api
capabilities:
- description: Workflow capability for managing continuous delivery pipelines and deployments using the Spinnaker Gate API. Enables DevOps engineers and platform teams to manage application deployment lifecycles, tr
  name: Spinnaker Continuous Delivery
  slug: continuous-delivery
common:
- title: ''
  type: Website
  url: https://spinnaker.io/
- title: ''
  type: Documentation
  url: https://spinnaker.io/docs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/spinnaker
- title: ''
  type: GitHubRepository
  url: https://github.com/spinnaker/spinnaker
- title: ''
  type: Community
  url: https://spinnaker.io/community/
- title: ''
  type: Slack
  url: https://join.spinnaker.io/
- title: ''
  type: Blog
  url: https://spinnaker.io/blog/
- title: ''
  type: RoadMap
  url: https://github.com/spinnaker/governance/tree/master/rfc
- title: ''
  type: ChangeLog
  url: https://spinnaker.io/changelogs/
- title: ''
  type: OpenAPI
  url: openapi/spinnaker-gate-openapi.yml
- title: ''
  type: SpectralRules
  url: rules/spinnaker-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/spinnaker-vocabulary.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/continuous-delivery.yaml
created: '2026-03-26'
description: Spinnaker is an open source multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence. Originally developed at Netflix and Google, Spinnaker provides a deployment platform supporting AWS, GCP, Azure, Kubernetes, and other cloud providers. The Gate API is the primary REST interface for all Spinnaker operations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 8
  name: Spinnaker Context
  property_count: 12
  slug: spinnaker-context
layout: provider
modified: '2026-05-02'
name: Spinnaker
rules:
- name: Spinnaker API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: spinnaker-rules
skills: []
slug: spinnaker
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spinnaker\nname: Spinnaker\ndescription: >-\n  Spinnaker is an open source multi-cloud continuous delivery platform for releasing\n  software changes with high velocity and confidence. Originally developed at Netflix\n  and Google, Spinnaker provides a deployment platform supporting AWS, GCP, Azure,\n  Kubernetes, and other cloud providers. The Gate API is the primary REST interface\n  for all Spinnaker operations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Continuous Delivery\n  - Containers\n  - DevOps\n  - Multi-Cloud\n  - Pipelines\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/spinnaker/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: spinnaker:spinnaker-gate-api\n    name: Spinnaker Gate API\n    description: >-\n      Gate is the Spinnaker API Gateway — the primary REST interface for all Spinnaker\n      operations including\
  \ application management, pipeline execution, cluster management,\n      and infrastructure discovery. Gate runs on port 8084 and is used by the Spinnaker UI\n      (Deck) as well as external automation scripts and integrations. Supports OAuth 2.0,\n      SAML, LDAP, and X.509 certificate authentication.\n    humanURL: https://spinnaker.io/docs/reference/api/\n    tags:\n      - Applications\n      - Clusters\n      - Continuous Delivery\n      - Deployments\n      - Pipelines\n    properties:\n      - type: Documentation\n        url: https://spinnaker.io/docs/reference/api/\n      - type: SwaggerUI\n        url: https://spinnaker.io/docs/reference/api/docs.html\n      - type: GitHubRepository\n        url: https://github.com/spinnaker/gate\n      - type: OpenAPI\n        url: openapi/spinnaker-gate-openapi.yml\n      - type: SpectralRules\n        url: rules/spinnaker-rules.yml\n      - type: NaftikoCapabilities\n        url: capabilities/continuous-delivery.yaml\ncommon:\n  - type:\
  \ Website\n    url: https://spinnaker.io/\n  - type: Documentation\n    url: https://spinnaker.io/docs/\n  - type: GitHubOrganization\n    url: https://github.com/spinnaker\n  - type: GitHubRepository\n    url: https://github.com/spinnaker/spinnaker\n  - type: Community\n    url: https://spinnaker.io/community/\n  - type: Slack\n    url: https://join.spinnaker.io/\n  - type: Blog\n    url: https://spinnaker.io/blog/\n  - type: RoadMap\n    url: https://github.com/spinnaker/governance/tree/master/rfc\n  - type: ChangeLog\n    url: https://spinnaker.io/changelogs/\n  - type: OpenAPI\n    url: openapi/spinnaker-gate-openapi.yml\n  - type: SpectralRules\n    url: rules/spinnaker-rules.yml\n  - type: Vocabulary\n    url: vocabulary/spinnaker-vocabulary.yml\n  - type: NaftikoCapabilities\n    url: capabilities/continuous-delivery.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spinnaker/refs/heads/main/apis.yml
tags:
- Continuous Delivery
- Containers
- DevOps
- Multi-Cloud
- Pipelines
url: https://raw.githubusercontent.com/api-evangelist/spinnaker/refs/heads/main/apis.yml
use_cases: []
---
