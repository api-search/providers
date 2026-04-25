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
