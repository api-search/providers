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
source_yaml: "aid: artifact-hub\nname: Artifact Hub\ndescription: >-\n  Artifact Hub is a CNCF incubating web-based application that enables finding,\n  installing, and publishing cloud-native packages. Built primarily in TypeScript\n  and Go, it addresses fragmentation in the cloud-native ecosystem by providing\n  a single discovery experience for consumers. It supports 27+ artifact types\n  including Helm charts, OPA policies, Falco rules, OLM operators, Tinkerbell\n  actions, kubectl plugins, Tekton tasks, KEDA scalers, CoreDNS plugins, and more.\n  Artifact Hub provides a searchable catalog with versioning, security reports via\n  Trivy and Snyk, changelog tracking, and webhook notification support. Licensed\n  under Apache 2.0 and governed by the CNCF.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/artifact-hub/refs/heads/main/apis.yml\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - CNCF\n  - Helm Charts\n\
  \  - Package Registry\n  - Discovery\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: artifact-hub:artifact-hub-api\n    name: Artifact Hub API\n    description: >-\n      The Artifact Hub REST API provides endpoints for searching and retrieving\n      cloud-native packages across all supported artifact types, managing\n      repositories, handling user authentication and sessions, managing\n      organization memberships, configuring webhooks for release notifications,\n      and administering package security reports. The API is the backend\n      service powering artifacthub.io and is available for self-hosted instances.\n    humanURL: https://artifacthub.io/docs/api/\n    baseURL: https://artifacthub.io/api/v1\n    tags:\n      - Package Search\n      - Registry\n      - REST API\n      - Cloud Native\n    properties:\n      - type: Documentation\n        url: https://artifacthub.io/docs/api/\n      - type:\
  \ GitHubRepository\n        url: https://github.com/artifacthub/hub\ncommon:\n  - type: Documentation\n    url: https://artifacthub.io/docs/\n    title: Artifact Hub Documentation\n  - type: GitHubOrganization\n    url: https://github.com/artifacthub\n    title: Artifact Hub GitHub Organization\n  - type: GitHubRepository\n    url: https://github.com/artifacthub/hub\n    title: Artifact Hub Source Repository\n  - type: Portal\n    url: https://artifacthub.io/\n    title: Artifact Hub\n  - type: Compliance\n    url: https://www.cncf.io/projects/artifact-hub/\n    title: CNCF Project Page\n  - type: ReleaseNotes\n    url: https://github.com/artifacthub/hub/releases\n    title: Release Notes\n  - type: Features\n    data:\n      - name: Package Discovery\n        description: >-\n          Unified search across 27+ cloud-native artifact types including Helm\n          charts, Kubernetes operators, OPA policies, Falco rules, and Tekton\n          tasks from a single interface.\n      - name:\
  \ Security Reports\n        description: >-\n          Automated security scanning of Helm chart images using Trivy and Snyk,\n          with visualized vulnerability reports and severity ratings.\n      - name: Webhook Notifications\n        description: >-\n          Configurable webhooks for receiving notifications when new package\n          versions are published or security issues are discovered.\n      - name: Repository Management\n        description: >-\n          Publishers add and manage their Helm chart repositories, OCI registries,\n          and other sources via the Artifact Hub API.\n      - name: Schema and Template Explorer\n        description: >-\n          Interactive exploration of Helm chart values schemas and template\n          structures directly in the browser.\n      - name: Self-Hosting Support\n        description: >-\n          Artifact Hub can be deployed on-premise using the official Helm chart,\n          enabling organizations to run their own private\
  \ artifact registry.\n  - type: UseCases\n    data:\n      - name: Helm Chart Discovery\n        description: >-\n          Platform engineers discover and evaluate Helm charts across multiple\n          repositories from a single searchable interface with version history\n          and security report data.\n      - name: Package Publishing\n        description: >-\n          Open source maintainers publish their Helm charts, operators, and\n          other cloud-native packages to Artifact Hub for discoverability.\n      - name: Security Auditing\n        description: >-\n          Security teams review Artifact Hub security reports to identify\n          vulnerable container images used in Helm charts before deployment.\n      - name: Release Monitoring\n        description: >-\n          Development teams configure webhooks to receive notifications when\n          new versions of dependencies like Helm charts are published.\n  - type: Integrations\n    data:\n      - name: Helm\n \
  \       description: >-\n          Native integration with Helm chart repositories including support for\n          OCI-based chart distribution via container registries.\n      - name: Trivy\n        description: >-\n          Integration with Aqua Security's Trivy for container image vulnerability\n          scanning in Helm chart security reports.\n      - name: Snyk\n        description: >-\n          Integration with Snyk for additional container security scanning\n          capabilities in Artifact Hub security reports.\n      - name: CNCF Landscape\n        description: >-\n          Artifact Hub is an official CNCF incubating project integrated into\n          the Cloud Native Computing Foundation's ecosystem.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/artifact-hub/refs/heads/main/apis.yml
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
