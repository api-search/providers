---
api_count: 6
apis:
- description: The cert-manager API extends the Kubernetes API with custom resources including Certificate, Issuer, ClusterIssuer, CertificateRequest, and Order. These resources allow declarative management of TLS c
  name: cert-manager Kubernetes API
  slug: cert-manager-api
- description: cmctl is the command-line tool for managing cert-manager resources. It provides commands for checking certificate status, manually triggering renewals, approving or denying certificate requests, and c
  name: cert-manager CLI (cmctl)
  slug: cmctl-cli
- description: trust-manager is a cert-manager companion project for managing TLS trust bundles in Kubernetes and OpenShift clusters. It distributes CA bundles via a Bundle custom resource to namespaces and workload
  name: trust-manager
  slug: trust-manager
- description: 'approver-policy is a cert-manager policy plugin that automatically approves or denies CertificateRequest resources based on defined CertificateRequestPolicy custom resources. It provides fine-grained '
  name: cert-manager approver-policy
  slug: approver-policy
- description: csi-driver is a Kubernetes Container Storage Interface plugin that works alongside cert-manager to seamlessly request and mount certificate key pairs as ephemeral volumes directly into pods. It enable
  name: cert-manager csi-driver
  slug: csi-driver
- description: csi-driver-spiffe is a Kubernetes CSI plugin that works alongside cert-manager to transparently deliver SPIFFE SVIDs as X.509 certificate key pairs to mounted pods using ephemeral volumes. It allows a
  name: cert-manager csi-driver-spiffe
  slug: csi-driver-spiffe
common:
- title: ''
  type: Website
  url: https://cert-manager.io
- title: ''
  type: Documentation
  url: https://cert-manager.io/docs/
- title: ''
  type: Getting Started
  url: https://cert-manager.io/docs/getting-started/
- title: ''
  type: Reference
  url: https://cert-manager.io/docs/reference/
- title: ''
  type: Community
  url: https://cert-manager.io/docs/contributing/
- title: ''
  type: GitHubOrganization
  url: https://github.com/cert-manager
- title: ''
  type: GitHubRepository
  url: https://github.com/cert-manager/cert-manager
- title: ''
  type: Change Log
  url: https://github.com/cert-manager/cert-manager/releases
- title: ''
  type: JSONSchema
  url: json-schema/cert-manager-certificate-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/cert-manager-issuer-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/cert-manager-context.jsonld
created: '2026-03-16'
description: cert-manager is a powerful and extensible X.509 certificate controller for Kubernetes and OpenShift workloads. It obtains certificates from a variety of issuers, including Let's Encrypt, HashiCorp Vault, and Venafi, and ensures certificates are valid and up-to-date, attempting to renew them before expiry. It supports certificate issuance for Ingress, Gateway API, and arbitrary workloads via Certificate resources.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cert Manager Context
  property_count: 12
  slug: cert-manager-context
layout: provider
modified: '2026-04-23'
name: Cert-Manager
skills: []
slug: cert-manager
solutions: []
tags:
- Certificates
- Cloud Native
- Graduated
- Kubernetes
- Security
- TLS
url: https://cert-manager.io
use_cases: []
---
