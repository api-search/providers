---
api_count: 3
api_specs:
- filename: trivy-server-openapi.yml
  format: yaml
  label: Trivy Server API
  slug: trivy-server
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trivy/refs/heads/main/openapi/trivy-server-openapi.yml
apis:
- description: Trivy can run in client/server mode where the server maintains vulnerability databases and clients submit scan requests. The server exposes HTTP endpoints including /healthz for liveness checks and /v
  name: Trivy Server API
  slug: trivy-server
- description: The Trivy Operator is a Kubernetes-native security toolkit that automatically scans clusters and generates security reports as Kubernetes Custom Resources. It defines 12 CRDs covering vulnerability re
  name: Trivy Operator
  slug: trivy-operator
- description: 'The primary interface for Trivy is its command-line tool, which scans container images, filesystems, Git repositories, Kubernetes clusters, virtual machine images, and SBOMs. Supports multiple output '
  name: Trivy CLI
  slug: trivy-cli
capabilities:
- description: Workflow capability for container and Kubernetes security scanning using Trivy. Covers vulnerability detection in container images and packages, Kubernetes CRD-based security reports via Trivy Operato
  name: Trivy Security Scanning
  slug: security-scanning
common:
- title: ''
  type: Website
  url: https://trivy.dev/
- title: ''
  type: Documentation
  url: https://aquasecurity.github.io/trivy/
- title: ''
  type: Getting Started
  url: https://aquasecurity.github.io/trivy/latest/getting-started/installation/
- title: ''
  type: GitHub Organization
  url: https://github.com/aquasecurity
- title: ''
  type: GitHub Repository
  url: https://github.com/aquasecurity/trivy
- title: ''
  type: Trivy Operator
  url: https://github.com/aquasecurity/trivy-operator
- title: ''
  type: GitHub Action
  url: https://github.com/aquasecurity/trivy-action
- title: ''
  type: VS Code Extension
  url: https://github.com/aquasecurity/trivy-vscode-extension
- title: ''
  type: Helm Chart
  url: https://artifacthub.io/packages/helm/aqua/trivy-operator
- title: ''
  type: Docker Image
  url: https://hub.docker.com/r/aquasec/trivy
- title: ''
  type: Releases
  url: https://github.com/aquasecurity/trivy/releases
- title: ''
  type: OpenAPI
  url: openapi/trivy-server-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/trivy-vulnerability-report-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/trivy-scan-result-schema.json
- title: ''
  type: JSON Structure
  url: json-structure/trivy-scan-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/trivy-context.jsonld
- title: ''
  type: Spectral Rules
  url: rules/trivy-rules.yml
- title: ''
  type: Naftiko Capability
  url: capabilities/security-scanning.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/trivy-vocabulary.yml
- title: ''
  type: x-profiled
  url: 2026-05
created: '2026-03-26'
description: Trivy is a comprehensive and versatile open-source security scanner from Aqua Security that finds vulnerabilities, misconfigurations, secrets, and SBOM in containers, Kubernetes, code repositories, clouds, and more. Trivy runs as a CLI tool, in client/server mode with an HTTP API, and as a Kubernetes Operator (trivy-operator) that continuously scans clusters and generates security reports as native Kubernetes Custom Resources.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 25
  name: Trivy Context
  property_count: 0
  slug: trivy-context
layout: provider
modified: '2026-05-03'
name: Trivy
rules:
- name: Trivy API Rules
  rule_count: 6
  severity_counts:
    error: 0
    hint: 0
    info: 1
    warn: 5
  slug: trivy-rules
skills: []
slug: trivy
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trivy\nname: Trivy\ndescription: >-\n  Trivy is a comprehensive and versatile open-source security scanner from Aqua Security\n  that finds vulnerabilities, misconfigurations, secrets, and SBOM in containers,\n  Kubernetes, code repositories, clouds, and more. Trivy runs as a CLI tool, in client/server\n  mode with an HTTP API, and as a Kubernetes Operator (trivy-operator) that continuously\n  scans clusters and generates security reports as native Kubernetes Custom Resources.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Containers\n  - Kubernetes\n  - SBOM\n  - Security\n  - Vulnerability Scanning\n  - Open Source\n  - DevSecOps\n  - Cloud Security\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/trivy/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trivy:trivy-server\n    name: Trivy Server API\n    description: >-\n      Trivy\
  \ can run in client/server mode where the server maintains vulnerability\n      databases and clients submit scan requests. The server exposes HTTP endpoints\n      including /healthz for liveness checks and /version for server version information.\n      Authentication is via token-based header (Trivy-Token).\n    humanURL: https://trivy.dev/latest/docs/references/modes/client-server/\n    baseURL: http://localhost:4954\n    tags:\n      - Security\n      - Vulnerability Scanning\n      - Server Mode\n      - HTTP API\n    properties:\n      - type: Documentation\n        url: https://trivy.dev/latest/docs/references/modes/client-server/\n      - type: GitHub Repository\n        url: https://github.com/aquasecurity/trivy\n      - type: OpenAPI\n        url: openapi/trivy-server-openapi.yml\n\n  - aid: trivy:trivy-operator\n    name: Trivy Operator\n    description: >-\n      The Trivy Operator is a Kubernetes-native security toolkit that automatically\n      scans clusters and generates\
  \ security reports as Kubernetes Custom Resources.\n      It defines 12 CRDs covering vulnerability reports, config audit reports, exposed\n      secret reports, SBOM reports, RBAC assessment reports, infrastructure assessment\n      reports, and compliance reports.\n    humanURL: https://github.com/aquasecurity/trivy-operator\n    baseURL: https://kubernetes.default.svc\n    tags:\n      - Kubernetes\n      - Security\n      - CRD\n      - Operator\n      - Vulnerability Scanning\n    properties:\n      - type: Documentation\n        url: https://aquasecurity.github.io/trivy-operator/\n      - type: GitHub Repository\n        url: https://github.com/aquasecurity/trivy-operator\n      - type: KubernetesCRD\n        url: crd/aquasecurity.github.io_vulnerabilityreports.yaml\n      - type: KubernetesCRD\n        url: crd/aquasecurity.github.io_configauditreports.yaml\n      - type: KubernetesCRD\n        url: crd/aquasecurity.github.io_exposedsecretreports.yaml\n      - type: KubernetesCRD\n\
  \        url: crd/aquasecurity.github.io_sbomreports.yaml\n      - type: KubernetesCRD\n        url: crd/aquasecurity.github.io_clustercompliancereports.yaml\n      - type: KubernetesCRD\n        url: crd/aquasecurity.github.io_clusterconfigauditreports.yaml\n      - type: KubernetesCRD\n        url: crd/aquasecurity.github.io_clusterinfraassessmentreports.yaml\n      - type: KubernetesCRD\n        url: crd/aquasecurity.github.io_clusterrbacassessmentreports.yaml\n      - type: KubernetesCRD\n        url: crd/aquasecurity.github.io_clustersbomreports.yaml\n      - type: KubernetesCRD\n        url: crd/aquasecurity.github.io_clustervulnerabilityreports.yaml\n      - type: KubernetesCRD\n        url: crd/aquasecurity.github.io_infraassessmentreports.yaml\n      - type: KubernetesCRD\n        url: crd/aquasecurity.github.io_rbacassessmentreports.yaml\n\n  - aid: trivy:trivy-cli\n    name: Trivy CLI\n    description: >-\n      The primary interface for Trivy is its command-line tool, which\
  \ scans container\n      images, filesystems, Git repositories, Kubernetes clusters, virtual machine images,\n      and SBOMs. Supports multiple output formats including JSON, SARIF, CycloneDX,\n      SPDX, and table output for CI/CD integration.\n    humanURL: https://trivy.dev/latest/docs/\n    baseURL: https://trivy.dev\n    tags:\n      - CLI\n      - Security\n      - DevSecOps\n      - Containers\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://trivy.dev/latest/docs/\n      - type: Getting Started\n        url: https://trivy.dev/latest/getting-started/installation/\n      - type: GitHub Repository\n        url: https://github.com/aquasecurity/trivy\n\ncommon:\n  - type: Website\n    url: https://trivy.dev/\n  - type: Documentation\n    url: https://aquasecurity.github.io/trivy/\n  - type: Getting Started\n    url: https://aquasecurity.github.io/trivy/latest/getting-started/installation/\n  - type: GitHub Organization\n    url: https://github.com/aquasecurity\n\
  \  - type: GitHub Repository\n    url: https://github.com/aquasecurity/trivy\n  - type: Trivy Operator\n    url: https://github.com/aquasecurity/trivy-operator\n  - type: GitHub Action\n    url: https://github.com/aquasecurity/trivy-action\n  - type: VS Code Extension\n    url: https://github.com/aquasecurity/trivy-vscode-extension\n  - type: Helm Chart\n    url: https://artifacthub.io/packages/helm/aqua/trivy-operator\n  - type: Docker Image\n    url: https://hub.docker.com/r/aquasec/trivy\n  - type: Releases\n    url: https://github.com/aquasecurity/trivy/releases\n  - type: OpenAPI\n    url: openapi/trivy-server-openapi.yml\n  - type: JSONSchema\n    url: json-schema/trivy-vulnerability-report-schema.json\n  - type: JSONSchema\n    url: json-schema/trivy-scan-result-schema.json\n  - type: JSON Structure\n    url: json-structure/trivy-scan-structure.json\n  - type: JSON-LD\n    url: json-ld/trivy-context.jsonld\n  - type: Spectral Rules\n    url: rules/trivy-rules.yml\n  - type: Naftiko\
  \ Capability\n    url: capabilities/security-scanning.yaml\n  - type: Vocabulary\n    url: vocabulary/trivy-vocabulary.yml\n  - type: x-profiled\n    url: '2026-05'\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trivy/refs/heads/main/apis.yml
tags:
- Containers
- Kubernetes
- SBOM
- Security
- Vulnerability Scanning
- Open Source
- DevSecOps
- Cloud Security
url: https://raw.githubusercontent.com/api-evangelist/trivy/refs/heads/main/apis.yml
use_cases: []
---
