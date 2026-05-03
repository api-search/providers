---
api_count: 1
apis:
- description: The SOPS decrypt Go package provides programmatic access to SOPS-encrypted files from Go applications. It supports decryption of YAML, JSON, ENV, INI, and binary formats using configured key managemen
  name: SOPS Go Library
  slug: sops-go-library
common:
- title: ''
  type: Website
  url: https://getsops.io/
- title: ''
  type: Documentation
  url: https://getsops.io/docs/
- title: ''
  type: GitHub Org
  url: https://github.com/getsops
- title: ''
  type: GitHub Repository
  url: https://github.com/getsops/sops
- title: ''
  type: Releases
  url: https://github.com/getsops/sops/releases
- title: ''
  type: License
  url: https://github.com/getsops/sops/blob/main/LICENSE
- title: ''
  type: Changelog
  url: https://github.com/getsops/sops/blob/main/CHANGELOG.rst
- title: ''
  type: CNCF Sandbox
  url: https://www.cncf.io/projects/sops/
- title: ''
  type: Homebrew
  url: https://formulae.brew.sh/formula/sops
- title: ''
  type: Flux Integration
  url: https://fluxcd.io/flux/guides/mozilla-sops/
- title: ''
  type: Blog
  url: https://getsops.io/blog/
- title: ''
  type: Security
  url: https://github.com/getsops/sops/blob/main/SECURITY.md
created: '2025'
description: SOPS (Secrets OPerationS) is a CNCF Sandbox encrypted file editor that supports YAML, JSON, ENV, INI, and binary formats. SOPS encrypts file values while leaving keys in cleartext, enabling secure storage of secrets in version control systems. Supports AWS KMS, GCP KMS, Azure Key Vault, HuaweiCloud KMS, age, and PGP for key management. Originally created at Mozilla and donated to the CNCF in 2023.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: Sops Context
  property_count: 11
  slug: sops-context
layout: provider
modified: '2026-05-02'
name: SOPS
skills: []
slug: sops
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sops\nname: SOPS\ndescription: >-\n  SOPS (Secrets OPerationS) is a CNCF Sandbox encrypted file editor that supports\n  YAML, JSON, ENV, INI, and binary formats. SOPS encrypts file values while leaving\n  keys in cleartext, enabling secure storage of secrets in version control systems.\n  Supports AWS KMS, GCP KMS, Azure Key Vault, HuaweiCloud KMS, age, and PGP for\n  key management. Originally created at Mozilla and donated to the CNCF in 2023.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Secrets Management\n  - Encryption\n  - Configuration Management\n  - DevOps\n  - Security\n  - Kubernetes\n  - CNCF\ncreated: '2025'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sops/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: sops:sops-go-library\n    name: SOPS Go Library\n    description: >-\n      The SOPS decrypt\
  \ Go package provides programmatic access to SOPS-encrypted\n      files from Go applications. It supports decryption of YAML, JSON, ENV, INI,\n      and binary formats using configured key management services.\n    humanURL: https://getsops.io/docs/\n    baseURL: https://github.com/getsops/sops\n    tags:\n      - Go\n      - Secrets Management\n      - Encryption\n      - Library\n    properties:\n      - type: Documentation\n        url: https://getsops.io/docs/\n      - type: GitHub\n        url: https://github.com/getsops/sops\n      - type: Releases\n        url: https://github.com/getsops/sops/releases\ncommon:\n  - type: Website\n    url: https://getsops.io/\n  - type: Documentation\n    url: https://getsops.io/docs/\n  - type: GitHub Org\n    url: https://github.com/getsops\n  - type: GitHub Repository\n    url: https://github.com/getsops/sops\n  - type: Releases\n    url: https://github.com/getsops/sops/releases\n  - type: License\n    url: https://github.com/getsops/sops/blob/main/LICENSE\n\
  \  - type: Changelog\n    url: https://github.com/getsops/sops/blob/main/CHANGELOG.rst\n  - type: CNCF Sandbox\n    url: https://www.cncf.io/projects/sops/\n  - type: Homebrew\n    url: https://formulae.brew.sh/formula/sops\n  - type: Flux Integration\n    url: https://fluxcd.io/flux/guides/mozilla-sops/\n  - type: Blog\n    url: https://getsops.io/blog/\n  - type: Security\n    url: https://github.com/getsops/sops/blob/main/SECURITY.md\nfeatures:\n  - Encrypts file values while keeping keys in cleartext\n  - Supports AWS KMS, GCP KMS, Azure Key Vault, HuaweiCloud KMS, age, PGP\n  - Works with YAML, JSON, ENV, INI, and binary file formats\n  - Key groups using Shamir Secret Sharing for multi-factor access control\n  - Audit logging via PostgreSQL integration\n  - Git integration for transparent decryption in diffs\n  - Configuration file (.sops.yaml) for creation and destination rules\n  - exec-env and exec-file commands to avoid secret exposure to disk\n  - In-place encryption/decryption\
  \ for workflow integration\nintegrations:\n  - AWS KMS\n  - GCP KMS\n  - Azure Key Vault\n  - HuaweiCloud KMS\n  - age encryption\n  - PGP/GPG\n  - Kubernetes Secrets\n  - Flux CD\n  - ArgoCD\n  - Helm\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sops/refs/heads/main/apis.yml
tags:
- Secrets Management
- Encryption
- Configuration Management
- DevOps
- Security
- Kubernetes
- CNCF
url: https://raw.githubusercontent.com/api-evangelist/sops/refs/heads/main/apis.yml
use_cases: []
---
