---
api_count: 3
apis:
- description: Aqua Security provides cloud-native security for the full application lifecycle, protecting containers, serverless functions, and cloud workloads with vulnerability scanning, runtime protection, and c
  name: Aqua Security
  slug: aqua-security
- description: Trivy is a comprehensive open source security scanner for containers, Kubernetes, code repositories, clouds, and more — finding vulnerabilities, misconfigurations, secrets, and SBOMs.
  name: Trivy
  slug: trivy
- description: Tracee is a runtime security and forensics tool for Linux that uses eBPF technology to trace system events and detect suspicious behavioral patterns.
  name: Tracee
  slug: tracee
common:
- title: ''
  type: Portal
  url: https://www.aquasec.com/
- title: ''
  type: Documentation
  url: https://docs.aquasec.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aquasecurity
- title: ''
  type: Blog
  url: https://www.aquasec.com/blog/
- title: ''
  type: Pricing
  url: https://www.aquasec.com/aqua-cloud/
- title: ''
  type: SignUp
  url: https://www.aquasec.com/demo/
- title: ''
  type: Support
  url: https://support.aquasec.com/
- title: ''
  type: StatusPage
  url: https://status.aquasec.com/
- title: ''
  type: TermsOfService
  url: https://www.aquasec.com/aqua-cloud/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://www.aquasec.com/privacy-policy/
- title: ''
  type: ReleaseNotes
  url: https://docs.aquasec.com/docs/release-notes
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/rules/aqua-security-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/vocabulary/aqua-security-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/json-ld/aqua-security-api-context.jsonld
created: '2026-03-26'
description: Aqua Security provides cloud-native security for the full application lifecycle, protecting containers, serverless functions, and cloud workloads with vulnerability scanning, runtime protection, and compliance enforcement.
features:
- description: Comprehensive scanning of container images, VM workloads, and serverless functions for known CVEs and misconfigurations.
  name: Vulnerability Scanning
- description: Real-time protection of running containers and cloud workloads using behavioral analysis and policy enforcement.
  name: Runtime Protection
- description: Cloud Security Posture Management to identify and remediate misconfigurations across AWS, Azure, and GCP.
  name: CSPM
- description: Protect the software supply chain by scanning code, open source dependencies, and CI/CD pipelines.
  name: Supply Chain Security
- description: Native Kubernetes security including admission control, runtime policies, and compliance benchmarks.
  name: Kubernetes Security
- description: Automated compliance checks against CIS, PCI-DSS, HIPAA, NIST, and other regulatory frameworks.
  name: Compliance Enforcement
- description: Detect and prevent secrets and credentials from being embedded in container images and code repositories.
  name: Secrets Detection
- description: Visualize and enforce container network connectivity and micro-segmentation policies.
  name: Network Policy
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integrations with AWS ECS, EKS, Lambda, ECR, Security Hub, and other AWS services.
  name: AWS
- description: Integrations with Azure Kubernetes Service, Azure Container Registry, and Azure Security Center.
  name: Azure
- description: Support for GKE, Google Container Registry, and Cloud Run on Google Cloud Platform.
  name: Google Cloud
- description: Trivy GitHub Action for automated vulnerability scanning in CI/CD workflows.
  name: GitHub Actions
- description: Jenkins plugin for container image scanning and policy enforcement in pipelines.
  name: Jenkins
- description: Terraform provider for declarative management of Aqua Security platform configuration.
  name: Terraform
- description: Official Helm charts for deploying Aqua Security components on Kubernetes.
  name: Helm
- description: Integration with Splunk for centralized security event logging and SIEM.
  name: Splunk
- description: Alert routing to PagerDuty for runtime security event notifications.
  name: PagerDuty
- description: Security alert notifications delivered to Slack channels.
  name: Slack
jsonld:
- class_count: 20
  name: Aqua Security Api Context
  property_count: 28
  slug: aqua-security-api-context
layout: provider
modified: '2026-04-19'
name: Aqua Security
rules:
- name: Aqua Security API Rules
  rule_count: 30
  severity_counts:
    error: 12
    hint: 0
    info: 3
    warn: 15
  slug: aqua-security-spectral-rules
skills: []
slug: aqua-security
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: aqua-security\nname: Aqua Security\ndescription: >-\n  Aqua Security provides cloud-native security for the full application lifecycle, protecting containers, serverless functions, and cloud workloads with vulnerability scanning, runtime protection, and compliance\n  enforcement.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Cloud Native\n- Containers\n- Kubernetes\n- Runtime Protection\n- Security\n- Vulnerability Scanning\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: aqua-security:aqua-security\n  name: Aqua Security\n  description: Aqua Security provides cloud-native security for the full application lifecycle, protecting containers, serverless functions, and cloud workloads with vulnerability scanning, runtime \n    protection, and compliance enforcement.\n  humanURL:\
  \ https://www.aquasec.com/\n  tags:\n  - Cloud Native Security\n  - Container Security\n  - Kubernetes\n  - Runtime Protection\n  - Security\n  - Vulnerability Scanning\n  - CSPM\n  - DevSecOps\n  properties:\n  - type: Documentation\n    url: https://docs.aquasec.com/\n  - type: GettingStarted\n    url: https://docs.aquasec.com/docs/getting-started\n  - type: APIReference\n    url: https://docs.aquasec.com/reference/api-overview\n  - type: Authentication\n    url: https://docs.aquasec.com/reference/authentication\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/openapi/aqua-security-api.yaml\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/json-schema/aqua-security-api-container-list-schema.json\n- aid: aqua-security:trivy\n  name: Trivy\n  description: Trivy is a comprehensive open source security scanner for containers, Kubernetes, code repositories, clouds, and more\
  \ — finding vulnerabilities, misconfigurations, secrets, and SBOMs.\n  humanURL: https://trivy.dev/\n  tags:\n  - Container Scanning\n  - Open Source\n  - Vulnerability Scanner\n  - SBOM\n  - Kubernetes Security\n  properties:\n  - type: Documentation\n    url: https://aquasecurity.github.io/trivy/\n  - type: GettingStarted\n    url: https://aquasecurity.github.io/trivy/latest/getting-started/installation/\n  - type: GitHubRepository\n    url: https://github.com/aquasecurity/trivy\n- aid: aqua-security:tracee\n  name: Tracee\n  description: Tracee is a runtime security and forensics tool for Linux that uses eBPF technology to trace system events and detect suspicious behavioral patterns.\n  humanURL: https://aquasecurity.github.io/tracee/\n  tags:\n  - eBPF\n  - Runtime Security\n  - Linux Security\n  - Forensics\n  - Open Source\n  properties:\n  - type: Documentation\n    url: https://aquasecurity.github.io/tracee/\n  - type: GitHubRepository\n    url: https://github.com/aquasecurity/tracee\n\
  common:\n- type: Portal\n  url: https://www.aquasec.com/\n- type: Documentation\n  url: https://docs.aquasec.com/\n- type: GitHubOrganization\n  url: https://github.com/aquasecurity\n- type: Blog\n  url: https://www.aquasec.com/blog/\n- type: Pricing\n  url: https://www.aquasec.com/aqua-cloud/\n- type: SignUp\n  url: https://www.aquasec.com/demo/\n- type: Support\n  url: https://support.aquasec.com/\n- type: StatusPage\n  url: https://status.aquasec.com/\n- type: TermsOfService\n  url: https://www.aquasec.com/aqua-cloud/terms-of-service/\n- type: PrivacyPolicy\n  url: https://www.aquasec.com/privacy-policy/\n- type: ReleaseNotes\n  url: https://docs.aquasec.com/docs/release-notes\n- type: Features\n  data:\n  - name: Vulnerability Scanning\n    description: Comprehensive scanning of container images, VM workloads, and serverless functions for known CVEs and misconfigurations.\n  - name: Runtime Protection\n    description: Real-time protection of running containers and cloud workloads\
  \ using behavioral analysis and policy enforcement.\n  - name: CSPM\n    description: Cloud Security Posture Management to identify and remediate misconfigurations across AWS, Azure, and GCP.\n  - name: Supply Chain Security\n    description: Protect the software supply chain by scanning code, open source dependencies, and CI/CD pipelines.\n  - name: Kubernetes Security\n    description: Native Kubernetes security including admission control, runtime policies, and compliance benchmarks.\n  - name: Compliance Enforcement\n    description: Automated compliance checks against CIS, PCI-DSS, HIPAA, NIST, and other regulatory frameworks.\n  - name: Secrets Detection\n    description: Detect and prevent secrets and credentials from being embedded in container images and code repositories.\n  - name: Network Policy\n    description: Visualize and enforce container network connectivity and micro-segmentation policies.\n- type: UseCases\n  data:\n  - name: Container Security\n    description: Secure\
  \ Docker and OCI containers throughout the build-to-runtime lifecycle.\n  - name: Kubernetes Security\n    description: Enforce security policies, runtime protection, and compliance for Kubernetes clusters.\n  - name: Serverless Security\n    description: Protect AWS Lambda, Azure Functions, and Google Cloud Functions from vulnerabilities and runtime attacks.\n  - name: DevSecOps\n    description: Integrate security scanning into CI/CD pipelines to shift security left and prevent vulnerabilities from reaching production.\n  - name: Cloud Workload Protection\n    description: Protect VMs and cloud workloads across multi-cloud environments from threats and misconfigurations.\n  - name: SBOM Generation\n    description: Generate Software Bill of Materials (SBOM) for container images and code repositories to understand component risk.\n- type: Integrations\n  data:\n  - name: AWS\n    description: Native integrations with AWS ECS, EKS, Lambda, ECR, Security Hub, and other AWS services.\n \
  \ - name: Azure\n    description: Integrations with Azure Kubernetes Service, Azure Container Registry, and Azure Security Center.\n  - name: Google Cloud\n    description: Support for GKE, Google Container Registry, and Cloud Run on Google Cloud Platform.\n  - name: GitHub Actions\n    description: Trivy GitHub Action for automated vulnerability scanning in CI/CD workflows.\n  - name: Jenkins\n    description: Jenkins plugin for container image scanning and policy enforcement in pipelines.\n  - name: Terraform\n    description: Terraform provider for declarative management of Aqua Security platform configuration.\n  - name: Helm\n    description: Official Helm charts for deploying Aqua Security components on Kubernetes.\n  - name: Splunk\n    description: Integration with Splunk for centralized security event logging and SIEM.\n  - name: PagerDuty\n    description: Alert routing to PagerDuty for runtime security event notifications.\n  - name: Slack\n    description: Security alert notifications\
  \ delivered to Slack channels.\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/rules/aqua-security-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/vocabulary/aqua-security-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/json-ld/aqua-security-api-context.jsonld\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/apis.yml
tags:
- Cloud Native
- Containers
- Kubernetes
- Runtime Protection
- Security
- Vulnerability Scanning
url: https://raw.githubusercontent.com/api-evangelist/aqua-security/refs/heads/main/apis.yml
use_cases:
- description: Secure Docker and OCI containers throughout the build-to-runtime lifecycle.
  name: Container Security
- description: Enforce security policies, runtime protection, and compliance for Kubernetes clusters.
  name: Kubernetes Security
- description: Protect AWS Lambda, Azure Functions, and Google Cloud Functions from vulnerabilities and runtime attacks.
  name: Serverless Security
- description: Integrate security scanning into CI/CD pipelines to shift security left and prevent vulnerabilities from reaching production.
  name: DevSecOps
- description: Protect VMs and cloud workloads across multi-cloud environments from threats and misconfigurations.
  name: Cloud Workload Protection
- description: Generate Software Bill of Materials (SBOM) for container images and code repositories to understand component risk.
  name: SBOM Generation
---
