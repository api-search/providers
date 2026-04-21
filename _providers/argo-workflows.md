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
