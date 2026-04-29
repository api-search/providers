---
api_count: 1
api_specs:
- filename: chaos-mesh-dashboard-api-openapi.yml
  format: yaml
  label: Chaos Mesh API
  slug: chaos-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chaos-mesh/refs/heads/main/openapi/chaos-mesh-dashboard-api-openapi.yml
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
source_filename: apis.yml
source_yaml: "aid: chaos-mesh\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/chaos-mesh/refs/heads/main/apis.yml\nname: Chaos Mesh\nx-type: opensource\ntags:\n  - Chaos Engineering\n  - Cloud Native\n  - CNCF\n  - Fault Injection\n  - Kubernetes\n  - Observability\n  - Open Source\n  - Reliability\n  - Resilience\n  - Testing\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: Open Source\ncreated: '2025-01-01'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  Chaos Mesh is a CNCF graduated cloud-native chaos engineering platform\n  that orchestrates chaos experiments on Kubernetes to test system\n  resilience and reliability. It exposes Kubernetes Custom Resource\n  Definitions (CRDs) for a wide range of chaos kinds (network, pod, IO,\n  stress, DNS, time, kernel, JVM, HTTP), along with a Chaos Dashboard web\n  UI backed by a REST API for creating, managing, and monitoring chaos\n  experiments and workflows.\
  \ Chaos Mesh integrates with Kubernetes, Argo\n  Workflows, Prometheus, Grafana, and CI/CD pipelines to run experiments\n  safely in staging and production environments.\napis:\n  - aid: chaos-mesh:chaos-mesh-api\n    name: Chaos Mesh API\n    tags:\n      - Chaos Engineering\n      - CRDs\n      - Dashboard\n      - Experiments\n      - Fault Injection\n      - Kubernetes\n      - Workflows\n    humanURL: https://chaos-mesh.org/docs/\n    properties:\n      - url: https://chaos-mesh.org/docs/\n        type: Documentation\n      - type: Getting Started\n        url: https://chaos-mesh.org/docs/quick-start/\n      - type: GitHubRepository\n        url: https://github.com/chaos-mesh/chaos-mesh\n      - type: OpenAPI\n        url: openapi/chaos-mesh-dashboard-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/chaos-mesh-experiment-schema.json\n      - type: JSONLD\n        url: json-ld/chaos-mesh-context.jsonld\n    description: >-\n      Chaos Mesh provides Kubernetes Custom\
  \ Resources and a REST API for\n      orchestrating chaos experiments including network faults, pod\n      failures, IO chaos, stress testing, kernel chaos, DNS chaos, time\n      chaos, JVM chaos, and HTTP request injection. The Chaos Dashboard\n      exposes a REST API for creating, running, scheduling, and observing\n      experiments and multi-step workflows, with RBAC and event auditing.\ncommon:\n  - type: Website\n    url: https://chaos-mesh.org/\n  - type: Documentation\n    url: https://chaos-mesh.org/docs/\n  - type: GettingStarted\n    url: https://chaos-mesh.org/docs/quick-start/\n  - type: Blog\n    url: https://chaos-mesh.org/blog/\n  - type: ChangeLog\n    url: https://github.com/chaos-mesh/chaos-mesh/blob/master/CHANGELOG.md\n  - type: GitHub\n    url: https://github.com/chaos-mesh\n  - type: GitHubRepository\n    url: https://github.com/chaos-mesh/chaos-mesh\n  - type: Community\n    url: https://chaos-mesh.org/community/\n  - type: License\n    url: https://github.com/chaos-mesh/chaos-mesh/blob/master/LICENSE\n\
  \  - type: CNCF\n    url: https://www.cncf.io/projects/chaos-mesh/\n  - type: Slack\n    url: https://slack.cncf.io/\n  - type: X\n    url: https://x.com/chaos_mesh\n  - type: JSONLD\n    url: json-ld/chaos-mesh-context.jsonld\n    name: Chaos Mesh JSON-LD Context\n    description: Linked data context mapping Chaos Mesh resources to standard vocabularies.\n  - type: JSONSchema\n    url: json-schema/chaos-mesh-experiment-schema.json\n    name: Chaos Mesh Experiment JSON Schema\n    description: JSON Schema for Chaos Mesh experiment custom resources covering all supported chaos kinds.\n  - name: Features\n    type: Features\n    data:\n      - name: Pod Chaos\n      - name: Network Chaos\n      - name: IO Chaos\n      - name: Stress Chaos\n      - name: Kernel Chaos\n      - name: Time Chaos\n      - name: DNS Chaos\n      - name: JVM Chaos\n      - name: HTTP Chaos\n      - name: AWS Chaos\n      - name: GCP Chaos\n      - name: Azure Chaos\n      - name: Block Chaos\n      - name: Physical\
  \ Machine Chaos\n      - name: Workflows\n      - name: Schedules\n      - name: Chaos Dashboard\n      - name: Kubernetes CRDs\n      - name: REST API\n      - name: RBAC\n      - name: Audit Events\n      - name: Safe Mode\n      - name: Status Monitoring\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Resilience Testing\n      - name: Disaster Recovery Drills\n      - name: SRE Game Days\n      - name: Canary Validation\n      - name: Production Reliability Testing\n      - name: Multi-Region Failover Testing\n      - name: Performance Bottleneck Discovery\n      - name: Observability Validation\n      - name: Continuous Chaos in CI/CD\n      - name: Microservices Dependency Testing\n      - name: Database Fault Tolerance Testing\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Kubernetes\n      - name: EKS\n      - name: GKE\n      - name: AKS\n      - name: OpenShift\n      - name: Rancher\n      - name: Argo Workflows\n      - name: Argo\
  \ CD\n      - name: Prometheus\n      - name: Grafana\n      - name: OpenTelemetry\n      - name: Jaeger\n      - name: Datadog\n      - name: Litmus\n      - name: GitHub Actions\n      - name: GitLab CI\n      - name: Jenkins\n      - name: Tekton\n      - name: Helm\n      - name: AWS\n      - name: Google Cloud\n      - name: Azure\n  - name: ChaosKinds\n    type: ChaosKinds\n    data:\n      - name: PodChaos\n      - name: NetworkChaos\n      - name: IOChaos\n      - name: TimeChaos\n      - name: KernelChaos\n      - name: StressChaos\n      - name: DNSChaos\n      - name: HTTPChaos\n      - name: JVMChaos\n      - name: AWSChaos\n      - name: GCPChaos\n      - name: AzureChaos\n      - name: BlockChaos\n      - name: PhysicalMachineChaos\n      - name: Schedule\n      - name: Workflow\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chaos-mesh/refs/heads/main/apis.yml
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
