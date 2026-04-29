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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cert-manager\nname: Cert-Manager\ndescription: >-\n  cert-manager is a powerful and extensible X.509 certificate controller for\n  Kubernetes and OpenShift workloads. It obtains certificates from a variety\n  of issuers, including Let's Encrypt, HashiCorp Vault, and Venafi, and\n  ensures certificates are valid and up-to-date, attempting to renew them\n  before expiry. It supports certificate issuance for Ingress, Gateway API,\n  and arbitrary workloads via Certificate resources.\nurl: https://cert-manager.io\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Certificates\n  - Cloud Native\n  - Graduated\n  - Kubernetes\n  - Security\n  - TLS\ncreated: '2026-03-16'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: cert-manager:cert-manager-api\n    name: cert-manager Kubernetes API\n    description: >-\n      The cert-manager API extends the Kubernetes API with custom resources\n      including\
  \ Certificate, Issuer, ClusterIssuer, CertificateRequest, and\n      Order. These resources allow declarative management of TLS certificates,\n      automatic renewal, and integration with ACME and other certificate\n      authorities directly through kubectl and Kubernetes manifests.\n    humanURL: https://cert-manager.io/docs/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://cert-manager.io/docs/\n      - type: Reference\n        url: https://cert-manager.io/docs/reference/api-docs/\n      - type: Getting Started\n        url: https://cert-manager.io/docs/getting-started/\n      - type: GitHubRepository\n        url: https://github.com/cert-manager/cert-manager\n      - type: Change Log\n        url: https://github.com/cert-manager/cert-manager/releases\n      - type: JSONSchema\n        url: json-schema/cert-manager-certificate-schema.json\n      - type: JSONSchema\n        url:\
  \ json-schema/cert-manager-issuer-schema.json\n    tags:\n      - Certificates\n      - Kubernetes API\n      - TLS\n  - aid: cert-manager:cmctl-cli\n    name: cert-manager CLI (cmctl)\n    description: >-\n      cmctl is the command-line tool for managing cert-manager resources. It\n      provides commands for checking certificate status, manually triggering\n      renewals, approving or denying certificate requests, and converting\n      cert-manager resources between API versions.\n    humanURL: https://cert-manager.io/docs/reference/cmctl/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://cert-manager.io/docs/reference/cmctl/\n      - type: GitHubRepository\n        url: https://github.com/cert-manager/cmctl\n      - type: Change Log\n        url: https://github.com/cert-manager/cmctl/releases\n    tags:\n      - Certificate Management\n      - CLI\n  - aid: cert-manager:trust-manager\n\
  \    name: trust-manager\n    description: >-\n      trust-manager is a cert-manager companion project for managing TLS trust\n      bundles in Kubernetes and OpenShift clusters. It distributes CA bundles\n      via a Bundle custom resource to namespaces and workloads, ensuring that\n      applications have access to an up-to-date set of trusted CA certificates\n      without manual maintenance.\n    humanURL: https://cert-manager.io/docs/trust/trust-manager/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://cert-manager.io/docs/trust/trust-manager/\n      - type: Getting Started\n        url: https://cert-manager.io/docs/trust/trust-manager/installation/\n      - type: GitHubRepository\n        url: https://github.com/cert-manager/trust-manager\n      - type: Change Log\n        url: https://github.com/cert-manager/trust-manager/releases\n    tags:\n      - Kubernetes\n      - TLS\n\
  \      - Trust Bundles\n  - aid: cert-manager:approver-policy\n    name: cert-manager approver-policy\n    description: >-\n      approver-policy is a cert-manager policy plugin that automatically\n      approves or denies CertificateRequest resources based on defined\n      CertificateRequestPolicy custom resources. It provides fine-grained\n      control over which certificate requests are permitted, including\n      constraints on allowed DNS names, key usages, and issuers.\n    humanURL: https://cert-manager.io/docs/policy/approval/approver-policy/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://cert-manager.io/docs/policy/approval/approver-policy/\n      - type: GitHubRepository\n        url: https://github.com/cert-manager/approver-policy\n      - type: Change Log\n        url: https://github.com/cert-manager/approver-policy/releases\n    tags:\n      - Certificate Approval\n\
  \      - Policy\n      - Security\n  - aid: cert-manager:csi-driver\n    name: cert-manager csi-driver\n    description: >-\n      csi-driver is a Kubernetes Container Storage Interface plugin that\n      works alongside cert-manager to seamlessly request and mount certificate\n      key pairs as ephemeral volumes directly into pods. It enables workloads\n      to automatically obtain short-lived certificates at pod startup without\n      requiring manual secret management.\n    humanURL: https://cert-manager.io/docs/usage/csi-driver/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://cert-manager.io/docs/usage/csi-driver/\n    tags:\n      - Certificate Management\n      - CSI\n      - Kubernetes\n  - aid: cert-manager:csi-driver-spiffe\n    name: cert-manager csi-driver-spiffe\n    description: >-\n      csi-driver-spiffe is a Kubernetes CSI plugin that works alongside\n      cert-manager\
  \ to transparently deliver SPIFFE SVIDs as X.509 certificate\n      key pairs to mounted pods using ephemeral volumes. It allows all pods\n      running in a Kubernetes cluster to automatically receive SPIFFE identity\n      documents from a configured Trust Domain.\n    humanURL: https://cert-manager.io/docs/usage/csi-driver-spiffe/\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    properties:\n      - type: Documentation\n        url: https://cert-manager.io/docs/usage/csi-driver-spiffe/\n      - type: Getting Started\n        url: https://cert-manager.io/docs/usage/csi-driver-spiffe/installation/\n    tags:\n      - CSI\n      - Identity\n      - Kubernetes\n      - SPIFFE\ncommon:\n  - type: Website\n    url: https://cert-manager.io\n  - type: Documentation\n    url: https://cert-manager.io/docs/\n  - type: Getting Started\n    url: https://cert-manager.io/docs/getting-started/\n  - type: Reference\n    url: https://cert-manager.io/docs/reference/\n\
  \  - type: Community\n    url: https://cert-manager.io/docs/contributing/\n  - type: GitHubOrganization\n    url: https://github.com/cert-manager\n  - type: GitHubRepository\n    url: https://github.com/cert-manager/cert-manager\n  - type: Change Log\n    url: https://github.com/cert-manager/cert-manager/releases\n  - type: JSONSchema\n    url: json-schema/cert-manager-certificate-schema.json\n  - type: JSONSchema\n    url: json-schema/cert-manager-issuer-schema.json\n  - type: JSON-LD\n    url: json-ld/cert-manager-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cert-manager/refs/heads/main/apis.yml
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
