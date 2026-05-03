---
api_count: 1
apis:
- description: Spacelift exposes a GraphQL API for programmatic control of all platform resources including stacks, runs, policies, contexts, worker pools, modules, and blueprints. Authentication uses JWT tokens obt
  name: Spacelift GraphQL API
  slug: spacelift-graphql
capabilities:
- description: 'Workflow capability for orchestrating infrastructure deployments through Spacelift. Enables platform engineers and DevOps teams to manage IaC stacks, trigger deployments, enforce governance policies, '
  name: Spacelift Infrastructure Orchestration
  slug: infrastructure-orchestration
common:
- title: ''
  type: Website
  url: https://spacelift.io/
- title: ''
  type: Documentation
  url: https://docs.spacelift.io/
- title: ''
  type: GraphQL
  url: https://docs.spacelift.io/integrations/api
- title: ''
  type: GitHub
  url: https://github.com/spacelift-io
- title: ''
  type: Pricing
  url: https://spacelift.io/pricing
- title: ''
  type: Blog
  url: https://spacelift.io/blog
- title: ''
  type: Changelog
  url: https://spacelift.io/changelog
created: '2026-03-27'
description: Spacelift is an infrastructure-as-code (IaC) orchestration platform that combines AI-assisted deployments, GitOps pipelines, and policy-as-code governance. It supports Terraform, OpenTofu, Pulumi, CloudFormation, Kubernetes, and Ansible. Key features include drift detection, OPA-based policies, self-service blueprints, dynamic credentials, and multi-tenancy. Available as fully managed SaaS and FedRAMP-authorized self-hosted.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 10
  name: Spacelift Context
  property_count: 15
  slug: spacelift-context
layout: provider
modified: '2026-05-02'
name: Spacelift
skills: []
slug: spacelift
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spacelift\nname: Spacelift\ndescription: >-\n  Spacelift is an infrastructure-as-code (IaC) orchestration platform that combines\n  AI-assisted deployments, GitOps pipelines, and policy-as-code governance. It supports\n  Terraform, OpenTofu, Pulumi, CloudFormation, Kubernetes, and Ansible. Key features\n  include drift detection, OPA-based policies, self-service blueprints, dynamic credentials,\n  and multi-tenancy. Available as fully managed SaaS and FedRAMP-authorized self-hosted.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Infrastructure as Code\n  - FinOps\n  - DevOps\n  - Platform Engineering\n  - Terraform\n  - GitOps\nurl: https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: spacelift:spacelift-graphql\n    name: Spacelift GraphQL API\n    description: >-\n      Spacelift exposes\
  \ a GraphQL API for programmatic control of all platform resources\n      including stacks, runs, policies, contexts, worker pools, modules, and blueprints.\n      Authentication uses JWT tokens obtained by exchanging a Spacelift API key ID and secret\n      via the apiKeyUser mutation. The endpoint is account-specific at\n      https://{account}.app.spacelift.io/graphql.\n    humanURL: https://spacelift.io/\n    baseURL: https://{account}.app.spacelift.io/graphql\n    tags:\n      - Infrastructure as Code\n      - DevOps\n      - Platform Engineering\n      - Terraform\n      - GraphQL\n    properties:\n      - type: Documentation\n        url: https://docs.spacelift.io/\n      - type: GraphQL\n        url: https://docs.spacelift.io/integrations/api\n      - type: Getting Started\n        url: https://docs.spacelift.io/\n      - type: GitHubRepository\n        url: https://github.com/spacelift-io/spacectl\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/json-schema/spacelift-stack-schema.json\n\
  \      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/json-structure/spacelift-stack-structure.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/json-ld/spacelift-context.jsonld\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/vocabulary/spacelift-vocabulary.yml\ncommon:\n  - type: Website\n    url: https://spacelift.io/\n  - type: Documentation\n    url: https://docs.spacelift.io/\n  - type: GraphQL\n    url: https://docs.spacelift.io/integrations/api\n  - type: GitHub\n    url: https://github.com/spacelift-io\n  - type: Pricing\n    url: https://spacelift.io/pricing\n  - type: Blog\n    url: https://spacelift.io/blog\n  - type: Changelog\n    url: https://spacelift.io/changelog\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/apis.yml
tags:
- Infrastructure as Code
- FinOps
- DevOps
- Platform Engineering
- Terraform
- GitOps
url: https://raw.githubusercontent.com/api-evangelist/spacelift/refs/heads/main/apis.yml
use_cases: []
---
