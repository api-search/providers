---
api_count: 5
api_specs:
- filename: circleci-rest-api-v2-openapi.yml
  format: yaml
  label: CircleCI REST API V2
  slug: rest-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/openapi/circleci-rest-api-v2-openapi.yml
- filename: circleci-rest-api-v1-openapi.yml
  format: yaml
  label: CircleCI REST API V1
  slug: rest-api-v1
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/openapi/circleci-rest-api-v1-openapi.yml
- filename: circleci-runner-api-openapi.yml
  format: yaml
  label: CircleCI Self-Hosted Runner API
  slug: runner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/openapi/circleci-runner-api-openapi.yml
- filename: circleci-webhooks-asyncapi.yml
  format: yaml
  label: CircleCI Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/asyncapi/circleci-webhooks-asyncapi.yml
apis:
- description: The CircleCI REST API v2 provides programmatic access to CircleCI services for managing pipelines, projects, workflows, jobs, and users. Developers can trigger pipelines, retrieve build status, manage
  name: CircleCI REST API V2
  slug: rest-api-v2
- description: The CircleCI REST API v1 is the legacy API that provides access to build information, project details, and user data. While still available, CircleCI recommends migrating to the v2 API for newer featu
  name: CircleCI REST API V1
  slug: rest-api-v1
- description: The CircleCI Self-Hosted Runner API enables management and execution of jobs on self-hosted runner infrastructure. It provides endpoints for listing available runners, managing runner tasks, and query
  name: CircleCI Self-Hosted Runner API
  slug: runner-api
- description: CircleCI Webhooks allow developers to receive real-time notifications about events in their CI/CD pipelines by configuring HTTP callbacks. Webhooks can be set up through project settings to notify ext
  name: CircleCI Webhooks
  slug: webhooks
- description: CircleCI Orbs are shareable, reusable packages of CircleCI configuration that simplify build setup and integration with third-party tools. The Orbs Registry on the CircleCI Developer Hub provides a se
  name: CircleCI Orbs Registry
  slug: orbs
asyncapis:
- description: CircleCI Webhooks allow developers to receive real-time notifications about events in their CI/CD pipelines by configuring HTTP callbacks. Webhooks can be set up through project settings or the API to
  name: CircleCI Webhooks
  slug: circleci-webhooks-asyncapi
capabilities: []
common:
- title: ''
  type: Website
  url: https://circleci.com/
- title: ''
  type: Portal
  url: https://circleci.com/developer
- title: ''
  type: Documentation
  url: https://circleci.com/docs/
- title: ''
  type: Status
  url: https://status.circleci.com/
- title: ''
  type: Support
  url: https://support.circleci.com/
- title: ''
  type: Blog
  url: https://circleci.com/blog/
- title: ''
  type: Privacy Policy
  url: https://circleci.com/privacy/
- title: ''
  type: Terms of Service
  url: https://circleci.com/terms-of-service/
- title: ''
  type: Login
  url: https://app.circleci.com/
- title: ''
  type: JSON-LD
  url: json-ld/circleci-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/circleci-pipeline-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/circleci-workflow-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/circleci-webhook-event-schema.json
- title: ''
  type: Spectral
  url: rules/circleci-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/circleci-capabilities.yml
created: '2025-03-05'
description: CircleCI is a continuous integration and continuous delivery (CI/CD) platform that automates software build, test, and deployment pipelines. Their developer surface includes the REST API v2 (the recommended modern interface), the legacy v1 REST API, a Self-Hosted Runner API, webhooks for real-time event notifications, and the Orbs Registry of reusable configuration packages. Authentication is via a personal or project Circle-Token sent in the Circle-Token header; responses are JSON.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Circleci Context
  property_count: 10
  slug: circleci-context
layout: provider
modified: '2026-04-23'
name: CircleCI
rules:
- name: CircleCI API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: circleci-rules
skills: []
slug: circleci
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: circleci\nname: CircleCI\nurl: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/apis.yml\ncreated: '2025-03-05'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\ntags:\n  - CI/CD\n  - Continuous Integration\n  - Continuous Deployment\n  - DevOps\n  - Pipelines\n  - Workflows\ndescription: >-\n  CircleCI is a continuous integration and continuous delivery (CI/CD)\n  platform that automates software build, test, and deployment pipelines.\n  Their developer surface includes the REST API v2 (the recommended modern\n  interface), the legacy v1 REST API, a Self-Hosted Runner API, webhooks\n  for real-time event notifications, and the Orbs Registry of reusable\n  configuration packages. Authentication is via a personal or project\n  Circle-Token sent in the Circle-Token header; responses are JSON.\napis:\n  - aid: circleci:rest-api-v2\n    name: CircleCI REST API V2\n    tags:\n      - CI/CD\n \
  \     - Continuous Integration\n      - DevOps\n      - Pipelines\n      - Workflows\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://circleci.com/api/v2\n    humanURL: https://circleci.com/docs/api/v2/\n    properties:\n      - url: https://circleci.com/docs/api/v2/\n        type: Documentation\n      - url: openapi/circleci-rest-api-v2-openapi.yml\n        type: OpenAPI\n    description: >-\n      The CircleCI REST API v2 provides programmatic access to CircleCI\n      services for managing pipelines, projects, workflows, jobs, and users.\n      Developers can trigger pipelines, retrieve build status, manage\n      contexts and environment variables, and access usage reports. The API\n      uses token-based authentication via a Circle-Token header and returns\n      JSON responses. It supports operations for project configuration,\n      workflow management, artifact retrieval, and insights into build\n      performance.\n \
  \ - aid: circleci:rest-api-v1\n    name: CircleCI REST API V1\n    tags:\n      - Builds\n      - CI/CD\n      - Continuous Integration\n      - Legacy\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://circleci.com/api/v1.1\n    humanURL: https://circleci.com/docs/api/v1/\n    properties:\n      - url: https://circleci.com/docs/api/v1/\n        type: Documentation\n      - url: openapi/circleci-rest-api-v1-openapi.yml\n        type: OpenAPI\n    description: >-\n      The CircleCI REST API v1 is the legacy API that provides access to\n      build information, project details, and user data. While still\n      available, CircleCI recommends migrating to the v2 API for newer\n      features and improved functionality. The v1 API supports operations\n      for retrieving build details, triggering builds, managing SSH keys,\n      and accessing test metadata. Authentication is handled through API\n      tokens passed as query parameters\
  \ or HTTP headers.\n  - aid: circleci:runner-api\n    name: CircleCI Self-Hosted Runner API\n    tags:\n      - CI/CD\n      - Infrastructure\n      - Runners\n      - Self-Hosted\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://runner.circleci.com\n    humanURL: https://circleci.com/docs/runner-api/\n    properties:\n      - url: https://circleci.com/docs/runner-api/\n        type: Documentation\n      - url: openapi/circleci-runner-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The CircleCI Self-Hosted Runner API enables management and execution\n      of jobs on self-hosted runner infrastructure. It provides endpoints\n      for listing available runners, managing runner tasks, and querying\n      resource classes. The API is hosted separately from the main CircleCI\n      API at runner.circleci.com and supports multiple authentication\n      methods depending on the endpoint. Developers can use this API\
  \ to\n      integrate self-hosted runner management into their infrastructure\n      automation workflows.\n  - aid: circleci:webhooks\n    name: CircleCI Webhooks\n    tags:\n      - CI/CD\n      - Events\n      - Notifications\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://circleci.com/docs/webhooks/\n    properties:\n      - url: https://circleci.com/docs/webhooks/\n        type: Documentation\n      - url: asyncapi/circleci-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      CircleCI Webhooks allow developers to receive real-time notifications\n      about events in their CI/CD pipelines by configuring HTTP callbacks.\n      Webhooks can be set up through project settings to notify external\n      services when workflows and jobs complete, fail, or change status.\n      This enables integration with monitoring systems, chat platforms, and\n  \
  \    custom automation workflows. Webhooks deliver JSON payloads containing\n      event details to configured endpoint URLs.\n  - aid: circleci:orbs\n    name: CircleCI Orbs Registry\n    tags:\n      - CI/CD\n      - Configuration\n      - Packages\n      - Reusable\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://circleci.com/developer/orbs\n    properties:\n      - url: https://circleci.com/developer/orbs\n        type: Documentation\n    description: >-\n      CircleCI Orbs are shareable, reusable packages of CircleCI\n      configuration that simplify build setup and integration with\n      third-party tools. The Orbs Registry on the CircleCI Developer Hub\n      provides a searchable catalog of community and certified orbs.\n      Developers can browse, publish, and consume orbs to automate repeated\n      processes, speed up project configuration, and integrate services like\n   \
  \   AWS, Docker, Slack, and Kubernetes into their CI/CD pipelines.\ncommon:\n  - type: Website\n    url: https://circleci.com/\n  - type: Portal\n    url: https://circleci.com/developer\n  - type: Documentation\n    url: https://circleci.com/docs/\n  - type: Status\n    url: https://status.circleci.com/\n  - type: Support\n    url: https://support.circleci.com/\n  - type: Blog\n    url: https://circleci.com/blog/\n  - type: Privacy Policy\n    url: https://circleci.com/privacy/\n  - type: Terms of Service\n    url: https://circleci.com/terms-of-service/\n  - type: Login\n    url: https://app.circleci.com/\n  - type: JSON-LD\n    url: json-ld/circleci-context.jsonld\n  - type: JSONSchema\n    url: json-schema/circleci-pipeline-schema.json\n  - type: JSONSchema\n    url: json-schema/circleci-workflow-schema.json\n  - type: JSONSchema\n    url: json-schema/circleci-webhook-event-schema.json\n  - type: Spectral\n    url: rules/circleci-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/circleci-capabilities.yml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/apis.yml
tags:
- CI/CD
- Continuous Integration
- Continuous Deployment
- DevOps
- Pipelines
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/circleci/refs/heads/main/apis.yml
use_cases: []
---
