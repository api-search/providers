---
api_count: 5
apis:
- description: Score is a platform-agnostic workload specification that enables developers to define their workloads once and deploy them across multiple platforms including Kubernetes, Docker, and Helm. The API man
  name: Score Workload Specification API
  slug: ''
- description: CNAB (Cloud Native Application Bundle) is a specification for packaging and distributing cloud-native applications. The API manages bundle lifecycle including installation, upgrading, and uninstalling
  name: Cloud Native Application Bundle API
  slug: ''
- description: Open Component Model (OCM) provides a standard for describing software components in a supply chain, enabling teams to track, reference, and verify software artifacts.
  name: Open Component Model API
  slug: ''
- description: Open Resource Discovery (ORD) is a protocol for machine-readable resource and capability discovery, enabling API management platforms to automatically discover what services and APIs an application ex
  name: Open Resource Discovery API
  slug: ''
- description: Radius is an open-source, cloud-agnostic application platform that enables developers to define and deploy applications with their dependencies in a portable, declarative way across cloud providers.
  name: Radius Application Platform API
  slug: ''
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/api-evangelist
- title: ''
  type: JSONLD
  url: json-ld/application-research-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/application-research-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/application-research-vocabulary.yaml
created: '2026-03-16'
description: 'Application Research is a topic collection focused on specifications for declaring application service integration dependencies. It covers five specification formats: Score (platform-agnostic workload specs), Cloud Native Application Bundle (CNAB), Open Component Model (OCM), Open Resource Discovery (ORD), and Radius — all aimed at enabling deployment teams to understand what services (APIs, databases, caches, message buses, blob stores) an application requires.'
features:
- description: Score enables defining workloads once and deploying across multiple platforms
  name: Platform-Agnostic Workload Specs
- description: CNAB provides standardized packaging and distribution of cloud-native applications
  name: Application Bundle Packaging
- description: OCM enables tracking and verifying software components through delivery pipelines
  name: Software Supply Chain Tracking
- description: ORD enables machines to discover what resources and APIs an application exposes
  name: Automatic API Discovery
- description: Radius enables portable application definitions with dependency declarations across clouds
  name: Cloud-Agnostic Dependency Declarations
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Primary deployment target for Score, CNAB, OCM, and Radius specs
  name: Kubernetes
- description: Score and CNAB support Helm-based deployment and chart generation
  name: Helm
- description: Score workloads can be compiled to Docker Compose files
  name: Docker
- description: Radius integrates with Terraform for infrastructure provisioning
  name: Terraform
- description: GitOps-based deployment of Score and CNAB bundles via ArgoCD
  name: ArgoCD
- description: ORD integrations enable Backstage service catalog population
  name: Backstage
jsonld:
- class_count: 9
  name: Application Research Context
  property_count: 16
  slug: application-research-context
layout: provider
modified: '2026-04-19'
name: Application Research
rules:
- name: Application Research API Rules
  rule_count: 19
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 10
  slug: application-research-spectral-rules
skills: []
slug: application-research
solutions: []
tags:
- Application Dependencies
- Cloud Native
- Integration
- Research
- Specifications
- Workload Specifications
url: https://raw.githubusercontent.com/api-evangelist/application-research/refs/heads/main/apis.yml
use_cases:
- description: Define an application once and deploy it across Kubernetes, Docker, or cloud platforms
  name: Multi-Platform Deployment
- description: Explicitly declare all required services (databases, caches, queues) for an application
  name: Dependency Documentation
- description: Track and verify software component provenance and integrity
  name: Software Supply Chain Security
- description: Enable API management platforms to automatically discover application capabilities
  name: API Landscape Discovery
- description: Move applications between cloud providers without rewriting configuration
  name: Cloud Migration
---
