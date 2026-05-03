---
api_count: 3
api_specs:
- filename: rekor-openapi.yaml
  format: yaml
  label: Rekor Transparency Log API
  slug: rekor
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/openapi/rekor-openapi.yaml
- filename: fulcio-openapi.json
  format: json
  label: Fulcio Certificate Authority API
  slug: fulcio
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/openapi/fulcio-openapi.json
apis:
- description: Rekor is a cryptographically secure, immutable transparency log for signed software releases. The Rekor API enables searching the transparency log, retrieving log entries, checking proofs, and queryin
  name: Rekor Transparency Log API
  slug: rekor
- description: Fulcio is Sigstore's free Root Certificate Authority for code signing certificates. It issues short-lived signing certificates to software producers based on OIDC authentication. The API provides endp
  name: Fulcio Certificate Authority API
  slug: fulcio
- description: Cosign is the Sigstore tool for signing and verifying container images and other OCI artifacts. It enables keyless signing using OIDC identity, hardware token signing, and policy enforcement for conta
  name: Cosign
  slug: cosign
capabilities:
- description: Unified software supply chain security workflow combining Sigstore's Rekor transparency log and Fulcio certificate authority. Enables artifact signing, verification, certificate issuance, and transpar
  name: Sigstore Software Supply Chain Security
  slug: software-supply-chain-security
common:
- title: ''
  type: Website
  url: https://www.sigstore.dev/
- title: ''
  type: Documentation
  url: https://docs.sigstore.dev/
- title: ''
  type: Getting Started
  url: https://docs.sigstore.dev/quickstart/quickstart-cosign/
- title: ''
  type: GitHub Organization
  url: https://github.com/sigstore
- title: ''
  type: Blog
  url: https://blog.sigstore.dev/
- title: ''
  type: Community
  url: https://sigstore.dev/community/
- title: ''
  type: Policy Controller
  url: https://docs.sigstore.dev/policy-controller/overview/
- title: ''
  type: Security
  url: https://docs.sigstore.dev/about/security/
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/vocabulary/sigstore-vocabulary.yml
created: '2026-03-26'
description: Sigstore is a set of free-to-use open source tools for signing, verifying, and protecting software supply chain artifacts. It provides a transparent and auditable signing infrastructure that eliminates the need for managing signing keys, making software supply chain security more accessible. The Sigstore ecosystem includes Cosign for artifact signing, Fulcio as the certificate authority, and Rekor as the cryptographically secure transparency log.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 30
  name: Sigstore Context
  property_count: 2
  slug: sigstore-context
layout: provider
modified: '2026-05-02'
name: Sigstore
rules:
- name: Sigstore API Rules
  rule_count: 6
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 5
  slug: sigstore-rules
skills: []
slug: sigstore
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sigstore\nname: Sigstore\ndescription: >-\n  Sigstore is a set of free-to-use open source tools for signing, verifying,\n  and protecting software supply chain artifacts. It provides a transparent\n  and auditable signing infrastructure that eliminates the need for managing\n  signing keys, making software supply chain security more accessible.\n  The Sigstore ecosystem includes Cosign for artifact signing, Fulcio as\n  the certificate authority, and Rekor as the cryptographically secure\n  transparency log.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Certificate Authority\n  - Code Signing\n  - Containers\n  - Cryptography\n  - Open Source\n  - PKI\n  - Security\n  - Software Supply Chain\n  - Transparency Log\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: sigstore:rekor\n\
  \    name: Rekor Transparency Log API\n    description: >-\n      Rekor is a cryptographically secure, immutable transparency log for signed\n      software releases. The Rekor API enables searching the transparency log,\n      retrieving log entries, checking proofs, and querying the log's public key.\n      The public-good instance runs at rekor.sigstore.dev.\n    humanURL: https://docs.sigstore.dev/logging/overview/\n    baseURL: https://rekor.sigstore.dev\n    tags:\n      - Cryptography\n      - Security\n      - Software Supply Chain\n      - Transparency Log\n    properties:\n      - type: Documentation\n        url: https://docs.sigstore.dev/logging/overview/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/openapi/rekor-openapi.yaml\n      - type: GitHub Repository\n        url: https://github.com/sigstore/rekor\n      - type: Rules\n        url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/rules/sigstore-rules.yml\n\
  \n  - aid: sigstore:fulcio\n    name: Fulcio Certificate Authority API\n    description: >-\n      Fulcio is Sigstore's free Root Certificate Authority for code signing certificates.\n      It issues short-lived signing certificates to software producers based on OIDC\n      authentication. The API provides endpoints for obtaining signing certificates,\n      retrieving trust bundles, and querying CA configuration. The public instance\n      runs at fulcio.sigstore.dev.\n    humanURL: https://docs.sigstore.dev/certificate_authority/overview/\n    baseURL: https://fulcio.sigstore.dev\n    tags:\n      - Certificate Authority\n      - Code Signing\n      - Cryptography\n      - OIDC\n      - PKI\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.sigstore.dev/certificate_authority/overview/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/openapi/fulcio-openapi.json\n      - type: GitHub\
  \ Repository\n        url: https://github.com/sigstore/fulcio\n\n  - aid: sigstore:cosign\n    name: Cosign\n    description: >-\n      Cosign is the Sigstore tool for signing and verifying container images and\n      other OCI artifacts. It enables keyless signing using OIDC identity, hardware\n      token signing, and policy enforcement for container supply chain security.\n    humanURL: https://docs.sigstore.dev/cosign/signing/overview/\n    tags:\n      - Code Signing\n      - Containers\n      - OCI\n      - Security\n      - Software Supply Chain\n    properties:\n      - type: Documentation\n        url: https://docs.sigstore.dev/cosign/signing/overview/\n      - type: GitHub Repository\n        url: https://github.com/sigstore/cosign\n\ncommon:\n  - type: Website\n    url: https://www.sigstore.dev/\n  - type: Documentation\n    url: https://docs.sigstore.dev/\n  - type: Getting Started\n    url: https://docs.sigstore.dev/quickstart/quickstart-cosign/\n  - type: GitHub Organization\n\
  \    url: https://github.com/sigstore\n  - type: Blog\n    url: https://blog.sigstore.dev/\n  - type: Community\n    url: https://sigstore.dev/community/\n  - type: Policy Controller\n    url: https://docs.sigstore.dev/policy-controller/overview/\n  - type: Security\n    url: https://docs.sigstore.dev/about/security/\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/vocabulary/sigstore-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/apis.yml
tags:
- Certificate Authority
- Code Signing
- Containers
- Cryptography
- Open Source
- PKI
- Security
- Software Supply Chain
- Transparency Log
url: https://raw.githubusercontent.com/api-evangelist/sigstore/refs/heads/main/apis.yml
use_cases: []
---
