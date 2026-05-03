---
api_count: 3
api_specs:
- filename: prefect-openapi.json
  format: json
  label: Prefect Cloud REST API
  slug: prefect-cloud-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/prefect/refs/heads/main/openapi/prefect-openapi.json
apis:
- description: The Prefect Cloud REST API provides programmatic access to Prefect Cloud for orchestrating and managing workflows, deployments, flow runs, task runs, artifacts, and automations. The API follows RESTfu
  name: Prefect Cloud REST API
  slug: prefect-cloud-rest-api
- description: 'The Prefect Server REST API is the self-hosted variant of the Prefect orchestration API for managing workflows, flow runs, task runs, deployments, and work pools. When running Prefect server locally, '
  name: Prefect Server REST API
  slug: prefect-server-rest-api
- description: 'The Prefect Python SDK is used to build, test, and execute workflows against the Prefect API. It provides decorators such as @flow and @task for defining workflows, along with programmatic interfaces '
  name: Prefect Python SDK
  slug: prefect-python-sdk
common:
- title: ''
  type: Portal
  url: https://www.prefect.io
- title: ''
  type: Getting Started
  url: https://docs.prefect.io/v3/get-started/quickstart
- title: ''
  type: Blog
  url: https://www.prefect.io/blog
- title: ''
  type: Pricing
  url: https://www.prefect.io/pricing
- title: ''
  type: Sign Up
  url: https://app.prefect.cloud/
- title: ''
  type: Support
  url: https://www.prefect.io/support
- title: ''
  type: Community
  url: https://www.prefect.io/community
- title: ''
  type: Change Log
  url: https://www.prefect.io/changelog
- title: ''
  type: Status
  url: https://status.prefect.io/
- title: ''
  type: Security
  url: https://www.prefect.io/security
- title: ''
  type: Terms of Service
  url: https://www.prefect.io/legal/terms
- title: ''
  type: Privacy Policy
  url: https://www.prefect.io/privacy-policy
- title: ''
  type: GitHub Organization
  url: https://github.com/PrefectHQ
- title: ''
  type: Login
  url: https://app.prefect.cloud/
created: '2026-03-03'
description: Prefect is a Python-native workflow orchestration tool for building, scheduling, and monitoring data pipelines with fault tolerance. Prefect provides a hybrid execution model where the cloud control plane coordinates workflows while code and data remain in customer infrastructure, offering both a managed cloud platform and a self-hosted open-source server.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Prefect
skills: []
slug: prefect
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: prefect\nname: Prefect\nsegments:\n  - Workflows\ndescription: >-\n  Prefect is a Python-native workflow orchestration tool for building,\n  scheduling, and monitoring data pipelines with fault tolerance. Prefect\n  provides a hybrid execution model where the cloud control plane coordinates\n  workflows while code and data remain in customer infrastructure, offering\n  both a managed cloud platform and a self-hosted open-source server.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - Data Pipelines\n  - Orchestration\n  - Python\n  - Workflows\ncreated: '2026-03-03'\nmodified: '2026-04-28'\nurl: https://raw.githubusercontent.com/api-evangelist/prefect/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: prefect:prefect-cloud-rest-api\n    name: Prefect Cloud REST API\n    description: >-\n      The Prefect Cloud REST API provides programmatic\
  \ access to Prefect Cloud\n      for orchestrating and managing workflows, deployments, flow runs, task\n      runs, artifacts, and automations. The API follows RESTful conventions\n      with pluralized collection names, snake_case route names, and supports\n      an OpenAPI 3.0 compliant specification. Clients authenticate using API\n      keys passed as Bearer tokens in request headers.\n    humanURL: https://docs.prefect.io/v3/api-ref/rest-api\n    tags:\n      - Automations\n      - Deployments\n      - Flow Runs\n      - Orchestration\n      - REST API\n      - Task Runs\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.prefect.io/v3/api-ref/rest-api\n      - type: API Reference\n        url: https://app.prefect.cloud/api/docs\n      - type: Authentication\n        url: https://docs.prefect.io/v3/manage/cloud/manage-users/api-keys\n      - type: Getting Started\n        url: https://docs.prefect.io/v3/get-started/quickstart\n      - type:\
  \ OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/prefect/refs/heads/main/openapi/prefect-openapi.json\n  - aid: prefect:prefect-server-rest-api\n    name: Prefect Server REST API\n    description: >-\n      The Prefect Server REST API is the self-hosted variant of the Prefect\n      orchestration API for managing workflows, flow runs, task runs,\n      deployments, and work pools. When running Prefect server locally, the\n      API is available at http://localhost:4200/api and interactive\n      documentation is served at the /docs endpoint. The API can be fully\n      described with an OpenAPI 3.0 compliant document generated from the\n      running server.\n    humanURL: https://docs.prefect.io/v3/api-ref/rest-api\n    tags:\n      - Open Source\n      - Orchestration\n      - REST API\n      - Self-Hosted\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.prefect.io/v3/api-ref/rest-api\n      - type: API\
  \ Reference\n        url: https://docs.prefect.io/latest/api-ref/rest-api-reference/\n      - type: Getting Started\n        url: https://docs.prefect.io/v3/get-started/quickstart\n      - type: GitHub Repository\n        url: https://github.com/PrefectHQ/prefect\n  - aid: prefect:prefect-python-sdk\n    name: Prefect Python SDK\n    description: >-\n      The Prefect Python SDK is used to build, test, and execute workflows\n      against the Prefect API. It provides decorators such as @flow and @task\n      for defining workflows, along with programmatic interfaces for\n      deployments, scheduling, state management, concurrency, caching, and\n      retries. The SDK requires Python 3.10 or higher and includes a\n      PrefectClient class for direct interaction with the REST API.\n    humanURL: https://docs.prefect.io/v3/api-ref/python\n    tags:\n      - Orchestration\n      - Python\n      - SDK\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://docs.prefect.io/v3/api-ref/python\n\
  \      - type: Getting Started\n        url: https://docs.prefect.io/v3/get-started/quickstart\n      - type: GitHub Repository\n        url: https://github.com/PrefectHQ/prefect\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://www.prefect.io\n  - type: Getting Started\n    url: https://docs.prefect.io/v3/get-started/quickstart\n  - type: Blog\n    url: https://www.prefect.io/blog\n  - type: Pricing\n    url: https://www.prefect.io/pricing\n  - type: Sign Up\n    url: https://app.prefect.cloud/\n  - type: Support\n    url: https://www.prefect.io/support\n  - type: Community\n    url: https://www.prefect.io/community\n  - type: Change Log\n    url: https://www.prefect.io/changelog\n  - type: Status\n    url: https://status.prefect.io/\n  - type: Security\n    url: https://www.prefect.io/security\n  - type: Terms of Service\n    url: https://www.prefect.io/legal/terms\n  - type: Privacy Policy\n    url: https://www.prefect.io/privacy-policy\n\
  \  - type: GitHub Organization\n    url: https://github.com/PrefectHQ\n  - type: Integrations\n    url: https://docs.prefect.io/integrations/integrations\n  - type: Login\n    url: https://app.prefect.cloud/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/prefect/refs/heads/main/apis.yml
tags:
- Automation
- Data Pipelines
- Orchestration
- Python
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/prefect/refs/heads/main/apis.yml
use_cases: []
---
