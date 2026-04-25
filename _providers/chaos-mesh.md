---
api_count: 1
apis:
- description: Chaos Mesh provides Kubernetes Custom Resources and a REST API for orchestrating chaos experiments including network faults, pod failures, IO chaos, stress testing, kernel chaos, DNS chaos, time chaos
  name: Chaos Mesh API
  slug: chaos-mesh-api
common:
- title: ''
  type: Website
  url: https://chaos-mesh.org/
- title: ''
  type: Documentation
  url: https://chaos-mesh.org/docs/
- title: ''
  type: GettingStarted
  url: https://chaos-mesh.org/docs/quick-start/
- title: ''
  type: Blog
  url: https://chaos-mesh.org/blog/
- title: ''
  type: ChangeLog
  url: https://github.com/chaos-mesh/chaos-mesh/blob/master/CHANGELOG.md
- title: ''
  type: GitHub
  url: https://github.com/chaos-mesh
- title: ''
  type: GitHubRepository
  url: https://github.com/chaos-mesh/chaos-mesh
- title: ''
  type: Community
  url: https://chaos-mesh.org/community/
- title: ''
  type: License
  url: https://github.com/chaos-mesh/chaos-mesh/blob/master/LICENSE
- title: ''
  type: CNCF
  url: https://www.cncf.io/projects/chaos-mesh/
- title: ''
  type: Slack
  url: https://slack.cncf.io/
- title: ''
  type: X
  url: https://x.com/chaos_mesh
- title: ''
  type: JSONLD
  url: json-ld/chaos-mesh-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/chaos-mesh-experiment-schema.json
- title: ''
  type: ChaosKinds
  url: ''
created: '2025-01-01'
description: Chaos Mesh is a CNCF graduated cloud-native chaos engineering platform that orchestrates chaos experiments on Kubernetes to test system resilience and reliability. It exposes Kubernetes Custom Resource Definitions (CRDs) for a wide range of chaos kinds (network, pod, IO, stress, DNS, time, kernel, JVM, HTTP), along with a Chaos Dashboard web UI backed by a REST API for creating, managing, and monitoring chaos experiments and workflows. Chaos Mesh integrates with Kubernetes, Argo Workflows, Prometheus, Grafana, and CI/CD pipelines to run experiments safely in staging and production environments.
features:
- name: Pod Chaos
- name: Network Chaos
- name: IO Chaos
- name: Stress Chaos
- name: Kernel Chaos
- name: Time Chaos
- name: DNS Chaos
- name: JVM Chaos
- name: HTTP Chaos
- name: AWS Chaos
- name: GCP Chaos
- name: Azure Chaos
- name: Block Chaos
- name: Physical Machine Chaos
- name: Workflows
- name: Schedules
- name: Chaos Dashboard
- name: Kubernetes CRDs
- name: REST API
- name: RBAC
- name: Audit Events
- name: Safe Mode
- name: Status Monitoring
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Kubernetes
- name: EKS
- name: GKE
- name: AKS
- name: OpenShift
- name: Rancher
- name: Argo Workflows
- name: Argo CD
- name: Prometheus
- name: Grafana
- name: OpenTelemetry
- name: Jaeger
- name: Datadog
- name: Litmus
- name: GitHub Actions
- name: GitLab CI
- name: Jenkins
- name: Tekton
- name: Helm
- name: AWS
- name: Google Cloud
- name: Azure
jsonld:
- class_count: 6
  name: Chaos Mesh Context
  property_count: 12
  slug: chaos-mesh-context
layout: provider
modified: '2026-04-23'
name: Chaos Mesh
skills: []
slug: chaos-mesh
solutions: []
tags:
- Chaos Engineering
- Cloud Native
- CNCF
- Fault Injection
- Kubernetes
- Observability
- Open Source
- Reliability
- Resilience
- Testing
url: https://raw.githubusercontent.com/api-evangelist/chaos-mesh/refs/heads/main/apis.yml
use_cases:
- name: Resilience Testing
- name: Disaster Recovery Drills
- name: SRE Game Days
- name: Canary Validation
- name: Production Reliability Testing
- name: Multi-Region Failover Testing
- name: Performance Bottleneck Discovery
- name: Observability Validation
- name: Continuous Chaos in CI/CD
- name: Microservices Dependency Testing
- name: Database Fault Tolerance Testing
---
