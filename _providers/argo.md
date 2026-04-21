---
api_count: 4
apis:
- description: REST API for managing Argo Workflows, workflow templates, cron workflows, archived workflow records, events, and sensors on Kubernetes clusters. Authentication uses JWT bearer tokens from Kubernetes s
  name: Argo Workflows API
  slug: argo-workflows-api
- description: REST API for managing Argo CD GitOps applications, projects, repositories, clusters, and sync operations for Kubernetes declarative continuous delivery. Authentication uses JWT bearer tokens.
  name: Argo CD API
  slug: argo-cd-api
- description: Kubernetes-native API for the Argo Events event-driven automation framework. Exposes CRD-based resources including EventSource, EventBus, and Sensor for triggering Argo Workflows and Kubernetes action
  name: Argo Events API
  slug: argo-events-api
- description: Kubernetes CRD-based API for Argo Rollouts progressive delivery controller. Provides Rollout and AnalysisTemplate resources for managing canary and blue-green deployment strategies with automated anal
  name: Argo Rollouts API
  slug: argo-rollouts-api
asyncapis:
- description: Argo Events is a Kubernetes-native event-driven automation framework that listens to over 20 event sources and triggers Argo Workflows, Kubernetes objects, HTTP requests, and other actions in response
  name: Argo Events
  slug: argo-events-asyncapi
capabilities:
- description: Unified capability combining all Argo Project tools — Workflows, CD, Events, and Rollouts — for a complete Kubernetes-native DevOps and ML platform. Serves Platform Engineers and DevOps teams.
  name: Argo Platform
  slug: argo-platform
common:
- title: ''
  type: Website
  url: https://argoproj.github.io/
- title: ''
  type: Documentation
  url: https://argoproj.github.io/
- title: ''
  type: GitHubOrganization
  url: https://github.com/argoproj
- title: ''
  type: GitHubRepository
  url: https://github.com/argoproj/argoproj
- title: ''
  type: Blog
  url: https://blog.argoproj.io/
- title: ''
  type: Support
  url: https://github.com/argoproj/argo-workflows/issues
- title: ''
  type: JSONLD
  url: json-ld/argo-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/argo-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/argo-platform.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/argo-vocabulary.yaml
created: '2025-01-01'
description: Argo is a collection of open-source Kubernetes-native tools for workflows, events, CI/CD, and progressive delivery. The project includes Argo Workflows (container-native workflow engine), Argo CD (declarative GitOps continuous delivery), Argo Events (event-driven automation framework), and Argo Rollouts (progressive delivery with canary and blue-green strategies). Argo is a CNCF graduated project governed by the Linux Foundation.
features:
- description: Container-native workflow engine for orchestrating parallel jobs and ML pipelines on Kubernetes.
  name: Argo Workflows
- description: Declarative GitOps continuous delivery tool that syncs Kubernetes application state from Git.
  name: Argo CD
- description: Event-driven automation framework supporting 20+ event sources to trigger Kubernetes workflows.
  name: Argo Events
- description: Progressive delivery controller with canary, blue-green, and experiment strategies for Kubernetes.
  name: Argo Rollouts
- description: All four Argo projects are CNCF graduated, ensuring production-quality governance and stability.
  name: CNCF Graduated
- description: All tools are implemented as Kubernetes CRDs and controllers, integrating natively with the platform.
  name: Kubernetes-Native
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Argo CD natively renders Helm charts; Argo Workflows can execute Helm operations as steps.
  name: Helm
- description: Argo CD supports Kustomize overlays for environment-specific application configuration.
  name: Kustomize
- description: All Argo tools expose Prometheus metrics for monitoring workflow and deployment health.
  name: Prometheus
- description: Argo CD and Argo Workflows support Slack notifications for deployment and workflow events.
  name: Slack
- description: Deep integration with GitHub webhooks for triggering workflows and CD syncs.
  name: GitHub
- description: Argo Workflows uses S3 as an artifact repository for passing data between workflow steps.
  name: Amazon S3
jsonld:
- class_count: 4
  name: Argo Context
  property_count: 37
  slug: argo-context
layout: provider
modified: '2026-04-19'
name: Argo
rules:
- name: Argo API Rules
  rule_count: 9
  severity_counts:
    error: 6
    hint: 0
    info: 1
    warn: 2
  slug: argo-spectral-rules
skills: []
slug: argo
solutions: []
tags:
- CNCF
- CI/CD
- GitOps
- Kubernetes
- Open Source
- Progressive Delivery
- Workflow Engine
url: https://raw.githubusercontent.com/api-evangelist/argo/refs/heads/main/apis.yml
use_cases:
- description: Combine Argo CD and Argo Workflows for a complete Git-driven DevOps platform on Kubernetes.
  name: GitOps Platform
- description: Use Argo Workflows to orchestrate multi-step ML training, evaluation, and deployment pipelines.
  name: Machine Learning Pipelines
- description: Use Argo Events to trigger workflows based on webhooks, schedules, messaging, and cloud events.
  name: Event-Driven Automation
- description: Use Argo Rollouts for safe canary and blue-green deployments with automated analysis and rollback.
  name: Progressive Delivery
- description: Build complete CI/CD pipelines natively on Kubernetes using Argo Workflows and Argo CD together.
  name: CI/CD on Kubernetes
---
