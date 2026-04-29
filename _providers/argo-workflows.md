---
api_count: 1
apis:
- description: The Argo Workflows REST API provides programmatic access to workflow lifecycle management, workflow templates, cron scheduling, archived workflow history, events, and cluster workflow templates. Authe
  name: Argo Workflows API
  slug: argo-workflows
capabilities:
- description: Unified capability for container-native workflow orchestration on Kubernetes using Argo Workflows. Combines workflow lifecycle management, template reuse, cron scheduling, and workflow history for Dat
  name: Argo Workflows Orchestration
  slug: workflow-orchestration
common:
- title: ''
  type: Website
  url: https://argoproj.github.io/workflows/
- title: ''
  type: Documentation
  url: https://argo-workflows.readthedocs.io/en/latest/
- title: ''
  type: GettingStarted
  url: https://argo-workflows.readthedocs.io/en/latest/quick-start/
- title: ''
  type: GitHubOrganization
  url: https://github.com/argoproj
- title: ''
  type: GitHubRepository
  url: https://github.com/argoproj/argo-workflows
- title: ''
  type: ReleaseNotes
  url: https://github.com/argoproj/argo-workflows/releases
- title: ''
  type: ChangeLog
  url: https://argo-workflows.readthedocs.io/en/latest/new-features/
- title: ''
  type: CLI
  url: https://argo-workflows.readthedocs.io/en/latest/cli/
- title: ''
  type: SDK
  url: https://hera.readthedocs.io/en/stable/
- title: ''
  type: Support
  url: https://github.com/argoproj/argo-workflows/issues
- title: ''
  type: SpectralRules
  url: rules/argo-workflows-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/workflow-orchestration.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/argo-workflows-vocabulary.yaml
created: '2026-03-27'
description: Argo Workflows is an open-source, container-native workflow engine for orchestrating parallel jobs on Kubernetes. It is a CNCF graduated project that allows you to define workflows where each step is a container, model multi-step workflows as sequences of tasks or DAGs, and run compute-intensive jobs for machine learning, data processing, and CI/CD pipelines natively on Kubernetes. Governed by the Linux Foundation and the CNCF.
features:
- description: Every workflow step runs as a Kubernetes container, providing complete isolation and reproducibility.
  name: Container-Native Workflows
- description: Define multi-step workflows as sequential steps or directed acyclic graphs (DAGs) with dependencies.
  name: DAG and Step-Based Orchestration
- description: Run multiple workflow steps in parallel to maximize compute utilization and reduce execution time.
  name: Parallel Execution
- description: Store and reuse workflow definitions as templates across the cluster.
  name: Workflow Templates
- description: Schedule workflows to run on cron schedules directly on Kubernetes.
  name: Cron Workflows
- description: Pass artifacts between workflow steps via S3, GCS, Azure Blob, Artifactory, and more.
  name: Artifact Support
- description: Persist workflow history to a database for long-term retention and querying.
  name: Workflow Archive
- description: Monitor and manage workflows through a rich graphical interface.
  name: Web UI
- description: Namespace-based isolation with RBAC for multi-team environments.
  name: Multi-Tenancy
- description: Trigger workflows from Kubernetes events, webhooks, and custom event sources.
  name: Event-Driven Triggers
- description: Define workflows in Python using the Hera SDK, the official Python SDK.
  name: Python SDK (Hera)
- description: Extend with custom executor plugins and artifact driver plugins.
  name: Plugin Architecture
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Official Python SDK for defining and submitting workflows programmatically.
  name: Python Hera SDK
- description: Use Argo CD to deploy and manage Argo Workflows resources via GitOps.
  name: Argo CD
- description: Expose workflow metrics for Prometheus monitoring and alerting.
  name: Prometheus
- description: Visualize workflow performance metrics in Grafana dashboards.
  name: Grafana
- description: Inject secrets into workflow containers securely via Vault integration.
  name: HashiCorp Vault
- description: Use S3 as artifact storage for passing data between workflow steps.
  name: Amazon S3
- description: Use Google Cloud Storage as artifact backend.
  name: Google GCS
- description: Use Azure Blob Storage for artifact persistence.
  name: Azure Blob Storage
- description: Run Kubeflow ML pipelines using Argo Workflows as the underlying engine.
  name: Kubeflow
- description: Orchestrate Apache Spark jobs as Argo Workflow steps.
  name: Apache Spark
jsonld:
- class_count: 6
  name: Argo Workflows Eventsource Context
  property_count: 10
  slug: argo-workflows-eventsource-context
- class_count: 122
  name: Argo Workflows Github Context
  property_count: 361
  slug: argo-workflows-github-context
- class_count: 1
  name: Argo Workflows Google Context
  property_count: 2
  slug: argo-workflows-google-context
- class_count: 2
  name: Argo Workflows Grpc Context
  property_count: 7
  slug: argo-workflows-grpc-context
- class_count: 281
  name: Argo Workflows Io Context
  property_count: 611
  slug: argo-workflows-io-context
- class_count: 6
  name: Argo Workflows Sensor Context
  property_count: 12
  slug: argo-workflows-sensor-context
- class_count: 4
  name: Argo Workflows Sync Context
  property_count: 5
  slug: argo-workflows-sync-context
layout: provider
modified: '2026-04-19'
name: Argo Workflows
rules:
- name: Argo Workflows API Rules
  rule_count: 13
  severity_counts:
    error: 5
    hint: 0
    info: 2
    warn: 6
  slug: argo-workflows-spectral-rules
skills: []
slug: argo-workflows
solutions: []
source_yaml: "aid: argo-workflows\nname: Argo Workflows\ndescription: >-\n  Argo Workflows is an open-source, container-native workflow engine for orchestrating parallel\n  jobs on Kubernetes. It is a CNCF graduated project that allows you to define workflows where\n  each step is a container, model multi-step workflows as sequences of tasks or DAGs, and run\n  compute-intensive jobs for machine learning, data processing, and CI/CD pipelines natively\n  on Kubernetes. Governed by the Linux Foundation and the CNCF.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CNCF\n  - Containers\n  - Data Processing\n  - Kubernetes\n  - Machine Learning\n  - Open Source\n  - Workflow Engine\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: argo-workflows:argo-workflows\n    name: Argo Workflows API\n\
  \    description: >-\n      The Argo Workflows REST API provides programmatic access to workflow lifecycle management,\n      workflow templates, cron scheduling, archived workflow history, events, and cluster\n      workflow templates. Authentication uses JWT bearer tokens from service account secrets.\n    humanURL: https://argo-workflows.readthedocs.io/en/latest/swagger/\n    tags:\n      - Kubernetes\n      - REST API\n      - Workflow Engine\n    properties:\n      - type: Documentation\n        url: https://argo-workflows.readthedocs.io/en/latest/\n      - type: OpenAPI\n        url: openapi/argo-workflows-openapi.json\n      - type: GettingStarted\n        url: https://argo-workflows.readthedocs.io/en/latest/quick-start/\n      - type: APIReference\n        url: https://argo-workflows.readthedocs.io/en/latest/swagger/\n      - type: Authentication\n        url: https://argo-workflows.readthedocs.io/en/latest/access-token/\ncommon:\n  - type: Website\n    url: https://argoproj.github.io/workflows/\n\
  \  - type: Documentation\n    url: https://argo-workflows.readthedocs.io/en/latest/\n  - type: GettingStarted\n    url: https://argo-workflows.readthedocs.io/en/latest/quick-start/\n  - type: GitHubOrganization\n    url: https://github.com/argoproj\n  - type: GitHubRepository\n    url: https://github.com/argoproj/argo-workflows\n  - type: ReleaseNotes\n    url: https://github.com/argoproj/argo-workflows/releases\n  - type: ChangeLog\n    url: https://argo-workflows.readthedocs.io/en/latest/new-features/\n  - type: CLI\n    url: https://argo-workflows.readthedocs.io/en/latest/cli/\n  - type: SDK\n    url: https://hera.readthedocs.io/en/stable/\n  - type: Support\n    url: https://github.com/argoproj/argo-workflows/issues\n  - type: SpectralRules\n    url: rules/argo-workflows-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/workflow-orchestration.yaml\n  - type: Vocabulary\n    url: vocabulary/argo-workflows-vocabulary.yaml\n  - type: Features\n    data:\n      - name:\
  \ Container-Native Workflows\n        description: Every workflow step runs as a Kubernetes container, providing complete isolation and reproducibility.\n      - name: DAG and Step-Based Orchestration\n        description: Define multi-step workflows as sequential steps or directed acyclic graphs (DAGs) with dependencies.\n      - name: Parallel Execution\n        description: Run multiple workflow steps in parallel to maximize compute utilization and reduce execution time.\n      - name: Workflow Templates\n        description: Store and reuse workflow definitions as templates across the cluster.\n      - name: Cron Workflows\n        description: Schedule workflows to run on cron schedules directly on Kubernetes.\n      - name: Artifact Support\n        description: Pass artifacts between workflow steps via S3, GCS, Azure Blob, Artifactory, and more.\n      - name: Workflow Archive\n        description: Persist workflow history to a database for long-term retention and querying.\n  \
  \    - name: Web UI\n        description: Monitor and manage workflows through a rich graphical interface.\n      - name: Multi-Tenancy\n        description: Namespace-based isolation with RBAC for multi-team environments.\n      - name: Event-Driven Triggers\n        description: Trigger workflows from Kubernetes events, webhooks, and custom event sources.\n      - name: Python SDK (Hera)\n        description: Define workflows in Python using the Hera SDK, the official Python SDK.\n      - name: Plugin Architecture\n        description: Extend with custom executor plugins and artifact driver plugins.\n  - type: UseCases\n    data:\n      - name: Machine Learning Pipelines\n        description: Orchestrate data preparation, model training, evaluation, and deployment as containerized steps.\n      - name: Data Processing and ETL\n        description: Run parallel data transformation and ETL jobs at scale on Kubernetes.\n      - name: CI/CD on Kubernetes\n        description: Run CI/CD pipelines\
  \ natively on Kubernetes without external CI tools.\n      - name: Batch Processing\n        description: Process large datasets in parallel with automatic resource management.\n      - name: Infrastructure Automation\n        description: Automate infrastructure provisioning, testing, and validation workflows.\n      - name: Scientific Computing\n        description: Orchestrate complex scientific computation and simulation jobs with dependencies.\n  - type: Integrations\n    data:\n      - name: Python Hera SDK\n        description: Official Python SDK for defining and submitting workflows programmatically.\n      - name: Argo CD\n        description: Use Argo CD to deploy and manage Argo Workflows resources via GitOps.\n      - name: Prometheus\n        description: Expose workflow metrics for Prometheus monitoring and alerting.\n      - name: Grafana\n        description: Visualize workflow performance metrics in Grafana dashboards.\n      - name: HashiCorp Vault\n        description:\
  \ Inject secrets into workflow containers securely via Vault integration.\n      - name: Amazon S3\n        description: Use S3 as artifact storage for passing data between workflow steps.\n      - name: Google GCS\n        description: Use Google Cloud Storage as artifact backend.\n      - name: Azure Blob Storage\n        description: Use Azure Blob Storage for artifact persistence.\n      - name: Kubeflow\n        description: Run Kubeflow ML pipelines using Argo Workflows as the underlying engine.\n      - name: Apache Spark\n        description: Orchestrate Apache Spark jobs as Argo Workflow steps.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/apis.yml
tags:
- CNCF
- Containers
- Data Processing
- Kubernetes
- Machine Learning
- Open Source
- Workflow Engine
url: https://raw.githubusercontent.com/api-evangelist/argo-workflows/refs/heads/main/apis.yml
use_cases:
- description: Orchestrate data preparation, model training, evaluation, and deployment as containerized steps.
  name: Machine Learning Pipelines
- description: Run parallel data transformation and ETL jobs at scale on Kubernetes.
  name: Data Processing and ETL
- description: Run CI/CD pipelines natively on Kubernetes without external CI tools.
  name: CI/CD on Kubernetes
- description: Process large datasets in parallel with automatic resource management.
  name: Batch Processing
- description: Automate infrastructure provisioning, testing, and validation workflows.
  name: Infrastructure Automation
- description: Orchestrate complex scientific computation and simulation jobs with dependencies.
  name: Scientific Computing
---
