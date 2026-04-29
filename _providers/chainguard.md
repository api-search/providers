---
api_count: 6
apis:
- description: Chainguard API v2 is the current REST API for the Chainguard platform. Endpoints cover Identity and Access Management (IAM), image registry operations, and vulnerability data under /iam/v2beta1/, /reg
  name: Chainguard API v2
  slug: api-v2
- description: Chainguard API v1 is the legacy REST API for the Chainguard platform, covering the same broad surface as v2 (IAM, registry, vulnerabilities) and remaining available for existing integrations while cus
  name: Chainguard API v1
  slug: api-v1
- description: The unified Chainguard API specification combines API v1 and v2 definitions in a single reference, useful for tool builders and readers who need a consolidated view of the platform surface.
  name: Chainguard Unified API Spec
  slug: unified-api-spec
- description: chainctl is the official command-line interface for the Chainguard platform. It provides commands for authentication, IAM, image management, registry operations, event subscriptions, packages, librari
  name: Chainguard chainctl CLI
  slug: chainctl
- description: The chainguard-dev/chainguard Terraform provider lets platform engineers provision and manage Chainguard resources (organizations, groups, identities, roles, subscriptions, and more) as infrastructure
  name: Chainguard Terraform Provider
  slug: terraform-provider
- description: cgr.dev is the OCI-compliant distribution endpoint for Chainguard Images. Standard OCI and Docker tooling (docker pull, cosign verify, oras, crane, etc.) can authenticate with a pull token or IAM cred
  name: Chainguard Images Registry (cgr.dev)
  slug: images-registry
common:
- title: ''
  type: Website
  url: https://www.chainguard.dev/
- title: ''
  type: Documentation
  url: https://edu.chainguard.dev/
- title: ''
  type: DeveloperPortal
  url: https://edu.chainguard.dev/chainguard/api/
- title: ''
  type: Academy
  url: https://edu.chainguard.dev/
- title: ''
  type: Blog
  url: https://www.chainguard.dev/unchained
- title: ''
  type: GitHub
  url: https://github.com/chainguard-dev
- title: ''
  type: Pricing
  url: https://www.chainguard.dev/pricing
- title: ''
  type: SignUp
  url: https://console.chainguard.dev/
- title: ''
  type: Console
  url: https://console.chainguard.dev/
- title: ''
  type: Contact
  url: https://www.chainguard.dev/contact
- title: ''
  type: Careers
  url: https://www.chainguard.dev/careers
- title: ''
  type: Security
  url: https://www.chainguard.dev/trust
- title: ''
  type: StatusPage
  url: https://status.chainguard.dev/
- title: ''
  type: TermsOfService
  url: https://www.chainguard.dev/legal/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.chainguard.dev/legal/privacy
- title: ''
  type: X
  url: https://x.com/chainguard_dev
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/chainguard/
- title: ''
  type: YouTube
  url: https://www.youtube.com/@chainguard_dev
- title: ''
  type: Products
  url: ''
created: '2026-03-26'
description: Chainguard builds, secures, and maintains a catalog of hardened, minimal container images and software supply chain security tools. Its flagship Chainguard Images rebuild open source software from source daily on a zero-known-CVE promise, signed with Sigstore, and distributed through the cgr.dev registry. The Chainguard platform exposes REST APIs, a command- line tool (chainctl), a Terraform provider, and an SDK for managing organizations, IAM, image repositories, registries, vulnerabilities, and event subscriptions. Chainguard Libraries extends the model to language ecosystems (Java, Python, Go, Node.js).
features:
- name: Hardened Images
- name: Minimal Images
- name: Distroless
- name: Zero-Known-CVE
- name: SBOMs
- name: SLSA Attestations
- name: Sigstore Signatures
- name: Cosign Verification
- name: Daily Rebuilds
- name: Wolfi OS Base
- name: OCI Registry
- name: IAM
- name: RBAC
- name: Audit Logs
- name: Event Subscriptions
- name: Vulnerability Feed
- name: Custom Assembly
- name: FIPS Images
- name: STIG Hardening
- name: Libraries for Java
- name: Libraries for Python
- name: Libraries for Go
- name: Libraries for Node.js
- name: Terraform Provider
- name: CLI (chainctl)
- name: REST API
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Kubernetes
- name: Docker
- name: OCI
- name: Sigstore
- name: Cosign
- name: SLSA
- name: Terraform
- name: GitHub Actions
- name: GitLab CI
- name: Jenkins
- name: Argo CD
- name: Tekton
- name: Harbor
- name: Quay
- name: Amazon ECR
- name: Google Artifact Registry
- name: Azure Container Registry
- name: Snyk
- name: Prisma Cloud
- name: Wiz
- name: Trivy
- name: Grype
- name: Syft
- name: AWS
- name: Google Cloud
- name: Azure
layout: provider
modified: '2026-04-23'
name: Chainguard
skills: []
slug: chainguard
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: chainguard\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/chainguard/refs/heads/main/apis.yml\nname: Chainguard\nx-type: company\ndescription: >-\n  Chainguard builds, secures, and maintains a catalog of hardened, minimal\n  container images and software supply chain security tools. Its flagship\n  Chainguard Images rebuild open source software from source daily on a\n  zero-known-CVE promise, signed with Sigstore, and distributed through the\n  cgr.dev registry. The Chainguard platform exposes REST APIs, a command-\n  line tool (chainctl), a Terraform provider, and an SDK for managing\n  organizations, IAM, image repositories, registries, vulnerabilities, and\n  event subscriptions. Chainguard Libraries extends the model to language\n  ecosystems (Java, Python, Go, Node.js).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ntags:\n  - Cloud Native\n  - Container Images\n  - Containers\n  -\
  \ DevSecOps\n  - Kubernetes\n  - Registry\n  - Security\n  - Software Supply Chain\n  - Vulnerability Management\ncreated: '2026-03-26'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\napis:\n  - aid: chainguard:api-v2\n    name: Chainguard API v2\n    description: >-\n      Chainguard API v2 is the current REST API for the Chainguard platform.\n      Endpoints cover Identity and Access Management (IAM), image registry\n      operations, and vulnerability data under /iam/v2beta1/,\n      /registry/v2beta1/, and /vulnerabilities/v2beta1/. v2 introduces\n      cursor-based pagination, server-side ordering, consistent resource\n      patterns, and structured error responses.\n    humanURL: https://edu.chainguard.dev/chainguard/api/spec-api-v2/\n    baseURL: https://console-api.enforce.dev\n    tags:\n      - IAM\n      - REST\n      - Registry\n      - Vulnerabilities\n    properties:\n      - type: Documentation\n        url: https://edu.chainguard.dev/chainguard/api/spec-api-v2/\n\
  \      - type: Tutorial\n        url: https://edu.chainguard.dev/chainguard/api/api-v2-tutorial/\n      - type: Authentication\n        url: https://edu.chainguard.dev/chainguard/api/authentication/\n  - aid: chainguard:api-v1\n    name: Chainguard API v1\n    description: >-\n      Chainguard API v1 is the legacy REST API for the Chainguard platform,\n      covering the same broad surface as v2 (IAM, registry, vulnerabilities)\n      and remaining available for existing integrations while customers\n      migrate to v2.\n    humanURL: https://edu.chainguard.dev/chainguard/api/spec-api-v1/\n    baseURL: https://console-api.enforce.dev\n    tags:\n      - IAM\n      - Legacy\n      - REST\n      - Registry\n      - Vulnerabilities\n    properties:\n      - type: Documentation\n        url: https://edu.chainguard.dev/chainguard/api/spec-api-v1/\n      - type: Authentication\n        url: https://edu.chainguard.dev/chainguard/api/authentication/\n  - aid: chainguard:unified-api-spec\n   \
  \ name: Chainguard Unified API Spec\n    description: >-\n      The unified Chainguard API specification combines API v1 and v2\n      definitions in a single reference, useful for tool builders and\n      readers who need a consolidated view of the platform surface.\n    humanURL: https://edu.chainguard.dev/chainguard/api/spec/\n    tags:\n      - OpenAPI\n      - Reference\n    properties:\n      - type: Documentation\n        url: https://edu.chainguard.dev/chainguard/api/spec/\n  - aid: chainguard:chainctl\n    name: Chainguard chainctl CLI\n    description: >-\n      chainctl is the official command-line interface for the Chainguard\n      platform. It provides commands for authentication, IAM, image\n      management, registry operations, event subscriptions, packages,\n      libraries, and configuration. chainctl uses the same underlying APIs\n      (v1 and v2) and is often the fastest path to automating Chainguard\n      workflows.\n    humanURL: https://edu.chainguard.dev/chainguard/chainctl/chainctl-docs/chainctl/\n\
  \    tags:\n      - Automation\n      - CLI\n      - Tooling\n    properties:\n      - type: Documentation\n        url: https://edu.chainguard.dev/chainguard/chainctl/chainctl-docs/chainctl/\n      - type: Authentication\n        url: https://edu.chainguard.dev/chainguard/chainctl/chainctl-docs/chainctl_auth/\n      - type: GitHubRepository\n        url: https://github.com/chainguard-dev/chainctl-releases\n  - aid: chainguard:terraform-provider\n    name: Chainguard Terraform Provider\n    description: >-\n      The chainguard-dev/chainguard Terraform provider lets platform\n      engineers provision and manage Chainguard resources (organizations,\n      groups, identities, roles, subscriptions, and more) as\n      infrastructure-as-code through the Chainguard API.\n    humanURL: >-\n      https://registry.terraform.io/providers/chainguard-dev/chainguard/latest/docs\n    tags:\n      - IaC\n      - Provisioning\n      - Terraform\n    properties:\n      - type: Documentation\n       \
  \ url: >-\n          https://registry.terraform.io/providers/chainguard-dev/chainguard/latest/docs\n      - type: GitHubRepository\n        url: https://github.com/chainguard-dev/terraform-provider-chainguard\n  - aid: chainguard:images-registry\n    name: Chainguard Images Registry (cgr.dev)\n    description: >-\n      cgr.dev is the OCI-compliant distribution endpoint for Chainguard\n      Images. Standard OCI and Docker tooling (docker pull, cosign verify,\n      oras, crane, etc.) can authenticate with a pull token or IAM\n      credentials to list tags, fetch images, and verify signatures and\n      attestations.\n    humanURL: https://edu.chainguard.dev/chainguard/chainguard-images/\n    baseURL: https://cgr.dev\n    tags:\n      - Cosign\n      - Distribution\n      - OCI\n      - Registry\n      - Sigstore\n    properties:\n      - type: Documentation\n        url: https://edu.chainguard.dev/chainguard/chainguard-images/\n      - type: Overview\n        url: https://edu.chainguard.dev/chainguard/chainguard-images/overview/\n\
  common:\n  - type: Website\n    url: https://www.chainguard.dev/\n  - type: Documentation\n    url: https://edu.chainguard.dev/\n  - type: DeveloperPortal\n    url: https://edu.chainguard.dev/chainguard/api/\n  - type: Academy\n    url: https://edu.chainguard.dev/\n  - type: Blog\n    url: https://www.chainguard.dev/unchained\n  - type: GitHub\n    url: https://github.com/chainguard-dev\n  - type: Pricing\n    url: https://www.chainguard.dev/pricing\n  - type: SignUp\n    url: https://console.chainguard.dev/\n  - type: Console\n    url: https://console.chainguard.dev/\n  - type: Contact\n    url: https://www.chainguard.dev/contact\n  - type: Careers\n    url: https://www.chainguard.dev/careers\n  - type: Security\n    url: https://www.chainguard.dev/trust\n  - type: StatusPage\n    url: https://status.chainguard.dev/\n  - type: TermsOfService\n    url: https://www.chainguard.dev/legal/terms\n  - type: PrivacyPolicy\n    url: https://www.chainguard.dev/legal/privacy\n  - type: X\n    url:\
  \ https://x.com/chainguard_dev\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/chainguard/\n  - type: YouTube\n    url: https://www.youtube.com/@chainguard_dev\n  - name: Features\n    type: Features\n    data:\n      - name: Hardened Images\n      - name: Minimal Images\n      - name: Distroless\n      - name: Zero-Known-CVE\n      - name: SBOMs\n      - name: SLSA Attestations\n      - name: Sigstore Signatures\n      - name: Cosign Verification\n      - name: Daily Rebuilds\n      - name: Wolfi OS Base\n      - name: OCI Registry\n      - name: IAM\n      - name: RBAC\n      - name: Audit Logs\n      - name: Event Subscriptions\n      - name: Vulnerability Feed\n      - name: Custom Assembly\n      - name: FIPS Images\n      - name: STIG Hardening\n      - name: Libraries for Java\n      - name: Libraries for Python\n      - name: Libraries for Go\n      - name: Libraries for Node.js\n      - name: Terraform Provider\n      - name: CLI (chainctl)\n      - name: REST API\n\
  \  - name: UseCases\n    type: UseCases\n    data:\n      - name: Software Supply Chain Security\n      - name: Container Hardening\n      - name: CVE Remediation\n      - name: Compliance (FedRAMP, FIPS, PCI, HIPAA)\n      - name: Open Source Dependency Security\n      - name: Secure Base Images\n      - name: Air-Gapped Distribution\n      - name: Kubernetes Workload Security\n      - name: CI/CD Integration\n      - name: Image Signing and Verification\n      - name: Vulnerability Scanning Reduction\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Kubernetes\n      - name: Docker\n      - name: OCI\n      - name: Sigstore\n      - name: Cosign\n      - name: SLSA\n      - name: Terraform\n      - name: GitHub Actions\n      - name: GitLab CI\n      - name: Jenkins\n      - name: Argo CD\n      - name: Tekton\n      - name: Harbor\n      - name: Quay\n      - name: Amazon ECR\n      - name: Google Artifact Registry\n      - name: Azure Container Registry\n  \
  \    - name: Snyk\n      - name: Prisma Cloud\n      - name: Wiz\n      - name: Trivy\n      - name: Grype\n      - name: Syft\n      - name: AWS\n      - name: Google Cloud\n      - name: Azure\n  - name: Products\n    type: Products\n    data:\n      - name: Chainguard Images\n      - name: Chainguard Libraries\n      - name: Chainguard Enforce\n      - name: Chainguard VMs\n      - name: Chainguard Containers\n      - name: Wolfi OS\n      - name: Custom Assembly\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chainguard/refs/heads/main/apis.yml
tags:
- Cloud Native
- Container Images
- Containers
- DevSecOps
- Kubernetes
- Registry
- Security
- Software Supply Chain
- Vulnerability Management
url: https://raw.githubusercontent.com/api-evangelist/chainguard/refs/heads/main/apis.yml
use_cases:
- name: Software Supply Chain Security
- name: Container Hardening
- name: CVE Remediation
- name: Compliance (FedRAMP, FIPS, PCI, HIPAA)
- name: Open Source Dependency Security
- name: Secure Base Images
- name: Air-Gapped Distribution
- name: Kubernetes Workload Security
- name: CI/CD Integration
- name: Image Signing and Verification
- name: Vulnerability Scanning Reduction
---
