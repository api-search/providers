---
api_count: 4
api_specs:
- filename: pipeline.swagger.json
  format: json
  label: Kubeflow Pipelines REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/kubeflow/pipelines/master/backend/api/v2beta1/swagger/pipeline.swagger.json
apis:
- description: REST API for managing ML pipelines, experiments, runs, and artifacts. Provides programmatic access to create, execute, and monitor ML workflows on a Kubeflow Pipelines deployment.
  name: Kubeflow Pipelines REST API
  slug: rest-api
- description: Python SDK for building, compiling, and submitting ML pipelines. Provides decorators and utilities to define pipeline components and workflows using Python.
  name: Kubeflow Pipelines Python SDK
  slug: python-sdk
- description: Go client library for interacting with the Kubeflow Pipelines API programmatically from Go applications.
  name: Kubeflow Pipelines Go Client
  slug: go-client
- description: API for tracking and managing metadata about ML artifacts, executions, and lineage information throughout the ML pipeline lifecycle, backed by ML Metadata (MLMD).
  name: Kubeflow Pipelines Metadata API
  slug: metadata-api
common:
- title: ''
  type: Website
  url: https://www.kubeflow.org/docs/components/pipelines/
- title: ''
  type: Documentation
  url: https://www.kubeflow.org/docs/components/pipelines/
- title: ''
  type: Getting Started
  url: https://www.kubeflow.org/docs/components/pipelines/getting-started/
- title: ''
  type: GitHubOrg
  url: https://github.com/kubeflow
- title: ''
  type: GitHubRepository
  url: https://github.com/kubeflow/pipelines
- title: ''
  type: Blog
  url: https://blog.kubeflow.org/
- title: ''
  type: Community
  url: https://www.kubeflow.org/docs/about/community/
- title: ''
  type: Change Log
  url: https://github.com/kubeflow/pipelines/releases
created: '2024-01-01'
description: Kubeflow Pipelines is a platform for building and deploying portable, scalable machine learning workflows based on Docker containers. It provides a way to orchestrate complex ML workflows with dependencies, enabling data scientists and ML engineers to deploy production-ready ML systems on Kubernetes.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Kubeflow Pipelines
skills: []
slug: kubeflow-pipelines
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kubeflow-pipelines\nname: Kubeflow Pipelines\ndescription: >-\n  Kubeflow Pipelines is a platform for building and deploying portable,\n  scalable machine learning workflows based on Docker containers. It provides\n  a way to orchestrate complex ML workflows with dependencies, enabling data\n  scientists and ML engineers to deploy production-ready ML systems on\n  Kubernetes.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Science\n  - Kubernetes\n  - Machine Learning\n  - MLOps\n  - Orchestration\n  - Pipelines\n  - Workflows\nurl: https://raw.githubusercontent.com/api-evangelist/kubeflow-pipelines/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: kubeflow-pipelines:rest-api\n    name: Kubeflow Pipelines REST API\n    description: >-\n      REST API for managing ML pipelines, experiments, runs, and artifacts.\n      Provides programmatic\
  \ access to create, execute, and monitor ML workflows\n      on a Kubeflow Pipelines deployment.\n    humanURL: https://www.kubeflow.org/docs/components/pipelines/reference/api/kubeflow-pipeline-api-spec/\n    baseURL: https://your-kubeflow-host/pipeline\n    tags:\n      - Experiments\n      - Pipelines\n      - REST API\n      - Runs\n    properties:\n      - type: Documentation\n        url: https://www.kubeflow.org/docs/components/pipelines/reference/api/kubeflow-pipeline-api-spec/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/kubeflow/pipelines/master/backend/api/v2beta1/swagger/pipeline.swagger.json\n  - aid: kubeflow-pipelines:python-sdk\n    name: Kubeflow Pipelines Python SDK\n    description: >-\n      Python SDK for building, compiling, and submitting ML pipelines. Provides\n      decorators and utilities to define pipeline components and workflows\n      using Python.\n    humanURL: https://kubeflow-pipelines.readthedocs.io/\n    baseURL: https://pypi.org/project/kfp/\n\
  \    tags:\n      - Client Library\n      - DSL\n      - Python\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://kubeflow-pipelines.readthedocs.io/\n      - type: GitHubRepository\n        url: https://github.com/kubeflow/pipelines/tree/master/sdk/python\n      - type: Examples\n        url: https://github.com/kubeflow/pipelines/tree/master/samples\n  - aid: kubeflow-pipelines:go-client\n    name: Kubeflow Pipelines Go Client\n    description: >-\n      Go client library for interacting with the Kubeflow Pipelines API\n      programmatically from Go applications.\n    humanURL: https://github.com/kubeflow/pipelines/tree/master/backend/api/go_client\n    tags:\n      - Client Library\n      - Go\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://pkg.go.dev/github.com/kubeflow/pipelines/backend/api/go_client\n      - type: GitHubRepository\n        url: https://github.com/kubeflow/pipelines/tree/master/backend/api/go_client\n\
  \  - aid: kubeflow-pipelines:metadata-api\n    name: Kubeflow Pipelines Metadata API\n    description: >-\n      API for tracking and managing metadata about ML artifacts, executions,\n      and lineage information throughout the ML pipeline lifecycle, backed by\n      ML Metadata (MLMD).\n    humanURL: https://www.kubeflow.org/docs/components/pipelines/concepts/metadata/\n    tags:\n      - Artifacts\n      - Lineage\n      - Metadata\n      - ML Metadata\n    properties:\n      - type: Documentation\n        url: https://www.kubeflow.org/docs/components/pipelines/concepts/metadata/\n      - type: GitHubRepository\n        url: https://github.com/google/ml-metadata\ncommon:\n  - type: Website\n    url: https://www.kubeflow.org/docs/components/pipelines/\n  - type: Documentation\n    url: https://www.kubeflow.org/docs/components/pipelines/\n  - type: Getting Started\n    url: https://www.kubeflow.org/docs/components/pipelines/getting-started/\n  - type: GitHubOrg\n    url: https://github.com/kubeflow\n\
  \  - type: GitHubRepository\n    url: https://github.com/kubeflow/pipelines\n  - type: Blog\n    url: https://blog.kubeflow.org/\n  - type: Community\n    url: https://www.kubeflow.org/docs/about/community/\n  - type: Change Log\n    url: https://github.com/kubeflow/pipelines/releases\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kubeflow-pipelines/refs/heads/main/apis.yml
tags:
- Data Science
- Kubernetes
- Machine Learning
- MLOps
- Orchestration
- Pipelines
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/kubeflow-pipelines/refs/heads/main/apis.yml
use_cases: []
---
