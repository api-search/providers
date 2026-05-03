---
api_count: 2
api_specs:
- filename: zenml-openapi.yml
  format: yaml
  label: ZenML OSS REST API
  slug: zenml-oss-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zenml/refs/heads/main/openapi/zenml-openapi.yml
apis:
- description: The ZenML open-source REST API exposes endpoints for managing ML pipelines, stacks, components, artifacts, models, deployments, runs, schedules, secrets, users, and projects in a self-hosted ZenML ser
  name: ZenML OSS REST API
  slug: zenml-oss-api
- description: The ZenML Pro REST API extends the OSS API with managed control-plane features for teams, including organization and tenant management, role-based access control, audit logs, and enterprise governance
  name: ZenML Pro REST API
  slug: zenml-pro-api
capabilities:
- description: ''
  name: Model Promotion
  slug: model-promotion
- description: ''
  name: Pipeline Lifecycle
  slug: pipeline-lifecycle
common:
- title: ''
  type: Portal
  url: https://www.zenml.io/
- title: ''
  type: Documentation
  url: https://docs.zenml.io/
- title: ''
  type: GettingStarted
  url: https://docs.zenml.io/getting-started/installation
- title: ''
  type: ChangeLog
  url: https://docs.zenml.io/changelog/server-sdk
- title: ''
  type: GitHubRepository
  url: https://github.com/zenml-io/zenml
- title: ''
  type: GitHubOrganization
  url: https://github.com/zenml-io
- title: ''
  type: Pricing
  url: https://www.zenml.io/pro
- title: ''
  type: Blog
  url: https://www.zenml.io/blog
- title: ''
  type: StatusPage
  url: https://status.zenml.io/
- title: ''
  type: Resources
  url: https://www.zenml.io/careers
- title: ''
  type: TermsOfService
  url: https://www.zenml.io/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.zenml.io/privacy-policy
- title: ''
  type: SDK
  url: https://pypi.org/project/zenml/
- title: ''
  type: SDK
  url: https://docs.zenml.io/sdk-reference
- title: ''
  type: ReleaseNotes
  url: https://github.com/zenml-io/zenml/releases
- title: ''
  type: JSONLD
  url: json-ld/zenml-context.jsonld
- title: ''
  type: Resources
  url: vocabulary/zenml-vocabulary.yml
- title: ''
  type: Resources
  url: rules/zenml-rules.yml
- title: ''
  type: Resources
  url: capabilities/pipeline-lifecycle.yaml
- title: ''
  type: Resources
  url: capabilities/model-promotion.yaml
created: '2025-02-08'
description: ZenML is an open-source MLOps and LLMOps framework that unifies machine learning and generative AI workflows through a single orchestration, versioning, and governance layer. It provides a Python SDK, CLI, REST API, and server for managing pipelines, stacks, artifacts, models, and deployments across any infrastructure backend, with 60+ integrations spanning orchestrators, ML frameworks, GenAI tools, cloud storage, and experiment tracking platforms.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 23
  name: Zenml Context
  property_count: 3
  slug: zenml-context
layout: provider
modified: '2026-05-03'
name: ZenML
rules:
- name: ZenML API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 3
  slug: zenml-rules
skills: []
slug: zenml
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zenml\nname: ZenML\ndescription: >-\n  ZenML is an open-source MLOps and LLMOps framework that unifies machine\n  learning and generative AI workflows through a single orchestration,\n  versioning, and governance layer. It provides a Python SDK, CLI, REST API,\n  and server for managing pipelines, stacks, artifacts, models, and\n  deployments across any infrastructure backend, with 60+ integrations\n  spanning orchestrators, ML frameworks, GenAI tools, cloud storage, and\n  experiment tracking platforms.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Machine Learning\n  - MLOps\n  - LLMOps\n  - Pipelines\n  - Open Source\n  - Python\ncreated: '2025-02-08'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zenml/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: zenml:zenml-oss-api\n    name: ZenML OSS REST API\n\
  \    description: >-\n      The ZenML open-source REST API exposes endpoints for managing ML\n      pipelines, stacks, components, artifacts, models, deployments, runs,\n      schedules, secrets, users, and projects in a self-hosted ZenML server.\n      It is consumed by the Python SDK and CLI and can be called directly for\n      automation and integration with CI/CD systems and MLOps workflows.\n    humanURL: https://docs.zenml.io/api-reference/oss-api\n    tags:\n      - MLOps\n      - Pipelines\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://docs.zenml.io/api-reference/oss-api\n      - type: APIReference\n        url: https://docs.zenml.io/api-reference/oss-api\n      - type: OpenAPI\n        url: openapi/zenml-openapi.yml\n      - type: GettingStarted\n        url: https://docs.zenml.io/getting-started/installation\n      - type: Authentication\n        url: https://docs.zenml.io/getting-started/deploying-zenml\n      - type: SDK\n        url:\
  \ https://docs.zenml.io/sdk-reference\n      - type: GitHubRepository\n        url: https://github.com/zenml-io/zenml\n      - type: JSONSchema\n        url: json-schema/zenml-pipeline-schema.json\n      - type: JSONSchema\n        url: json-schema/zenml-pipeline-run-schema.json\n      - type: JSONSchema\n        url: json-schema/zenml-stack-schema.json\n      - type: JSONSchema\n        url: json-schema/zenml-model-schema.json\n      - type: JSONSchema\n        url: json-schema/zenml-artifact-schema.json\n      - type: CodeExamples\n        url: examples/zenml-list-pipelines-example.json\n      - type: CodeExamples\n        url: examples/zenml-get-pipeline-run-example.json\n      - type: CodeExamples\n        url: examples/zenml-create-stack-example.json\n  - aid: zenml:zenml-pro-api\n    name: ZenML Pro REST API\n    description: >-\n      The ZenML Pro REST API extends the OSS API with managed control-plane\n      features for teams, including organization and tenant management,\n \
  \     role-based access control, audit logs, and enterprise governance.\n    humanURL: https://docs.zenml.io/api-reference/pro-api\n    tags:\n      - MLOps\n      - Enterprise\n      - Governance\n    properties:\n      - type: Documentation\n        url: https://docs.zenml.io/api-reference/pro-api\n      - type: APIReference\n        url: https://docs.zenml.io/api-reference/pro-api\n      - type: Authentication\n        url: https://docs.zenml.io/pro/core-concepts/access-control\ncommon:\n  - url: https://www.zenml.io/\n    name: ZenML - The AI Control Plane\n    type: Portal\n  - url: https://docs.zenml.io/\n    name: ZenML Documentation\n    type: Documentation\n  - url: https://docs.zenml.io/getting-started/installation\n    name: Get Started with ZenML\n    type: GettingStarted\n  - url: https://docs.zenml.io/changelog/server-sdk\n    name: ZenML Server & SDK Changelog\n    type: ChangeLog\n  - url: https://github.com/zenml-io/zenml\n    name: ZenML GitHub Repository\n    type: GitHubRepository\n\
  \  - url: https://github.com/zenml-io\n    name: ZenML GitHub Organization\n    type: GitHubOrganization\n  - url: https://www.zenml.io/pro\n    name: ZenML Pro - Managed MLOps\n    type: Pricing\n  - url: https://www.zenml.io/integrations\n    name: ZenML Integrations\n    type: Integrations\n  - url: https://www.zenml.io/blog\n    name: ZenML Blog\n    type: Blog\n  - url: https://status.zenml.io/\n    name: ZenML Status Page\n    type: StatusPage\n  - url: https://www.zenml.io/careers\n    name: ZenML Careers\n    type: Resources\n  - url: https://www.zenml.io/terms-of-service\n    name: ZenML Terms of Service\n    type: TermsOfService\n  - url: https://www.zenml.io/privacy-policy\n    name: ZenML Privacy Policy\n    type: PrivacyPolicy\n  - url: https://pypi.org/project/zenml/\n    name: ZenML on PyPI\n    type: SDK\n  - url: https://docs.zenml.io/sdk-reference\n    name: ZenML Python SDK Reference\n    type: SDK\n  - url: https://github.com/zenml-io/zenml/releases\n    name: ZenML\
  \ Releases\n    type: ReleaseNotes\n  - url: json-ld/zenml-context.jsonld\n    name: ZenML JSON-LD Context\n    type: JSONLD\n  - url: vocabulary/zenml-vocabulary.yml\n    name: ZenML Vocabulary\n    type: Resources\n  - url: rules/zenml-rules.yml\n    name: ZenML Spectral Rules\n    type: Resources\n  - url: capabilities/pipeline-lifecycle.yaml\n    name: ZenML Pipeline Lifecycle Capability\n    type: Resources\n  - url: capabilities/model-promotion.yaml\n    name: ZenML Model Promotion Capability\n    type: Resources\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zenml/refs/heads/main/apis.yml
tags:
- AI
- Machine Learning
- MLOps
- LLMOps
- Pipelines
- Open Source
- Python
url: https://raw.githubusercontent.com/api-evangelist/zenml/refs/heads/main/apis.yml
use_cases: []
---
