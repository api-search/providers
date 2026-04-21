---
api_count: 1
apis:
- description: The Artifact Hub REST API provides endpoints for searching and retrieving cloud-native packages across all supported artifact types, managing repositories, handling user authentication and sessions, m
  name: Artifact Hub API
  slug: artifact-hub-api
common:
- title: Artifact Hub Documentation
  type: Documentation
  url: https://artifacthub.io/docs/
- title: Artifact Hub GitHub Organization
  type: GitHubOrganization
  url: https://github.com/artifacthub
- title: Artifact Hub Source Repository
  type: GitHubRepository
  url: https://github.com/artifacthub/hub
- title: Artifact Hub
  type: Portal
  url: https://artifacthub.io/
- title: CNCF Project Page
  type: Compliance
  url: https://www.cncf.io/projects/artifact-hub/
- title: Release Notes
  type: ReleaseNotes
  url: https://github.com/artifacthub/hub/releases
created: '2026-03-16'
description: Artifact Hub is a CNCF incubating web-based application that enables finding, installing, and publishing cloud-native packages. Built primarily in TypeScript and Go, it addresses fragmentation in the cloud-native ecosystem by providing a single discovery experience for consumers. It supports 27+ artifact types including Helm charts, OPA policies, Falco rules, OLM operators, Tinkerbell actions, kubectl plugins, Tekton tasks, KEDA scalers, CoreDNS plugins, and more. Artifact Hub provides a searchable catalog with versioning, security reports via Trivy and Snyk, changelog tracking, and webhook notification support. Licensed under Apache 2.0 and governed by the CNCF.
features:
- description: Unified search across 27+ cloud-native artifact types including Helm charts, Kubernetes operators, OPA policies, Falco rules, and Tekton tasks from a single interface.
  name: Package Discovery
- description: Automated security scanning of Helm chart images using Trivy and Snyk, with visualized vulnerability reports and severity ratings.
  name: Security Reports
- description: Configurable webhooks for receiving notifications when new package versions are published or security issues are discovered.
  name: Webhook Notifications
- description: Publishers add and manage their Helm chart repositories, OCI registries, and other sources via the Artifact Hub API.
  name: Repository Management
- description: Interactive exploration of Helm chart values schemas and template structures directly in the browser.
  name: Schema and Template Explorer
- description: Artifact Hub can be deployed on-premise using the official Helm chart, enabling organizations to run their own private artifact registry.
  name: Self-Hosting Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with Helm chart repositories including support for OCI-based chart distribution via container registries.
  name: Helm
- description: Integration with Aqua Security's Trivy for container image vulnerability scanning in Helm chart security reports.
  name: Trivy
- description: Integration with Snyk for additional container security scanning capabilities in Artifact Hub security reports.
  name: Snyk
- description: Artifact Hub is an official CNCF incubating project integrated into the Cloud Native Computing Foundation's ecosystem.
  name: CNCF Landscape
layout: provider
modified: '2026-04-19'
name: Artifact Hub
skills: []
slug: artifact-hub
solutions: []
tags:
- Cloud Native
- CNCF
- Helm Charts
- Package Registry
- Discovery
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/artifact-hub/refs/heads/main/apis.yml
use_cases:
- description: Platform engineers discover and evaluate Helm charts across multiple repositories from a single searchable interface with version history and security report data.
  name: Helm Chart Discovery
- description: Open source maintainers publish their Helm charts, operators, and other cloud-native packages to Artifact Hub for discoverability.
  name: Package Publishing
- description: Security teams review Artifact Hub security reports to identify vulnerable container images used in Helm charts before deployment.
  name: Security Auditing
- description: Development teams configure webhooks to receive notifications when new versions of dependencies like Helm charts are published.
  name: Release Monitoring
---
