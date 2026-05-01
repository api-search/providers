---
api_count: 3
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Sigstore Rekor API (consumed)
  slug: rekor-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/sigstore/rekor/main/openapi.yaml
apis:
- description: Cosign is a command-line tool for signing, verifying, and storing container images and OCI artifacts. It supports keyless signing, hardware-backed keys, KMS providers, in-toto and SLSA attestations, a
  name: Cosign CLI
  slug: cosign-cli
- description: Rekor is the Sigstore transparency log that cosign writes to and reads from when recording and verifying signing events. The public Rekor service exposes a REST API at rekor.sigstore.dev with operatio
  name: Sigstore Rekor API (consumed)
  slug: rekor-api
- description: Fulcio is the Sigstore certificate authority that issues short-lived X.509 code-signing certificates bound to OIDC identities. Cosign calls the Fulcio public CA at fulcio.sigstore.dev during keyless s
  name: Sigstore Fulcio API (consumed)
  slug: fulcio-api
common:
- title: ''
  type: Website
  url: https://www.sigstore.dev/
- title: ''
  type: Documentation
  url: https://docs.sigstore.dev/cosign/
- title: ''
  type: GettingStarted
  url: https://docs.sigstore.dev/quickstart/quickstart-cosign/
- title: ''
  type: Installation
  url: https://docs.sigstore.dev/cosign/system_config/installation/
- title: ''
  type: GitHubOrganization
  url: https://github.com/sigstore
- title: ''
  type: GitHubRepository
  url: https://github.com/sigstore/cosign
- title: ''
  type: Releases
  url: https://github.com/sigstore/cosign/releases
- title: ''
  type: Blog
  url: https://blog.sigstore.dev/
- title: ''
  type: Community
  url: https://docs.sigstore.dev/about/community/
- title: ''
  type: Slack
  url: https://sigstore.slack.com/
- title: ''
  type: License
  url: https://github.com/sigstore/cosign/blob/main/LICENSE
- title: ''
  type: Security
  url: https://github.com/sigstore/cosign/security
- title: ''
  type: Roadmap
  url: https://github.com/sigstore/cosign/blob/main/ROADMAP.md
created: '2026-03-26'
description: Cosign is the command-line client of the Sigstore project for signing, verifying, and storing container images, OCI artifacts, blobs, and in-toto attestations. Cosign supports keyless signing using OpenID Connect identity providers (Google, GitHub, Microsoft) by obtaining short-lived certificates from the Fulcio certificate authority and recording signing events in the Rekor transparency log. Signatures and attestations are stored alongside the signed artifact in any OCI-compliant registry, and cosign integrates with policy controllers, KMS providers, hardware tokens, and SBOM workflows for software supply chain security.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Cosign
skills: []
slug: cosign
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cosign\nname: Cosign\nx-type: opensource\ndescription: >-\n  Cosign is the command-line client of the Sigstore project for signing,\n  verifying, and storing container images, OCI artifacts, blobs, and\n  in-toto attestations. Cosign supports keyless signing using OpenID Connect\n  identity providers (Google, GitHub, Microsoft) by obtaining short-lived\n  certificates from the Fulcio certificate authority and recording signing\n  events in the Rekor transparency log. Signatures and attestations are\n  stored alongside the signed artifact in any OCI-compliant registry, and\n  cosign integrates with policy controllers, KMS providers, hardware tokens,\n  and SBOM workflows for software supply chain security.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cosign/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess: Public\nposition: Provider\ntags:\n  - Apache 2.0\n  - Attestations\n\
  \  - CLI\n  - Code Signing\n  - Containers\n  - Fulcio\n  - Go\n  - Keyless\n  - OCI\n  - OIDC\n  - Open Source\n  - Rekor\n  - Sigstore\n  - Supply Chain\n  - Transparency Log\n  - Verification\ncreated: '2026-03-26'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\napis:\n  - aid: cosign:cosign-cli\n    name: Cosign CLI\n    description: >-\n      Cosign is a command-line tool for signing, verifying, and storing\n      container images and OCI artifacts. It supports keyless signing,\n      hardware-backed keys, KMS providers, in-toto and SLSA attestations, and\n      transparency log inclusion. The CLI is the primary user interface and\n      does not expose its own HTTP API.\n    humanURL: https://docs.sigstore.dev/cosign/\n    properties:\n      - type: Documentation\n        url: https://docs.sigstore.dev/cosign/\n      - type: GettingStarted\n        url: https://docs.sigstore.dev/quickstart/quickstart-cosign/\n      - type: Installation\n        url: https://docs.sigstore.dev/cosign/system_config/installation/\n\
  \      - type: GitHubRepository\n        url: https://github.com/sigstore/cosign\n      - type: Reference\n        url: https://docs.sigstore.dev/cosign/reference/cosign/\n    tags:\n      - CLI\n      - Containers\n      - Keyless\n      - OCI\n      - Signing\n  - aid: cosign:rekor-api\n    name: Sigstore Rekor API (consumed)\n    description: >-\n      Rekor is the Sigstore transparency log that cosign writes to and reads\n      from when recording and verifying signing events. The public Rekor\n      service exposes a REST API at rekor.sigstore.dev with operations for\n      creating log entries, retrieving entries by index or UUID, fetching\n      log info and proofs, and searching the index.\n    humanURL: https://docs.sigstore.dev/logging/overview/\n    baseURL: https://rekor.sigstore.dev\n    properties:\n      - type: Documentation\n        url: https://docs.sigstore.dev/logging/overview/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/sigstore/rekor/main/openapi.yaml\n\
  \      - type: GitHubRepository\n        url: https://github.com/sigstore/rekor\n    tags:\n      - Rekor\n      - REST\n      - Sigstore\n      - Transparency Log\n  - aid: cosign:fulcio-api\n    name: Sigstore Fulcio API (consumed)\n    description: >-\n      Fulcio is the Sigstore certificate authority that issues short-lived\n      X.509 code-signing certificates bound to OIDC identities. Cosign calls\n      the Fulcio public CA at fulcio.sigstore.dev during keyless signing to\n      obtain a certificate for a verified identity.\n    humanURL: https://docs.sigstore.dev/certificate_authority/overview/\n    baseURL: https://fulcio.sigstore.dev\n    properties:\n      - type: Documentation\n        url: https://docs.sigstore.dev/certificate_authority/overview/\n      - type: GitHubRepository\n        url: https://github.com/sigstore/fulcio\n    tags:\n      - CA\n      - Certificates\n      - Fulcio\n      - OIDC\n      - Sigstore\ncommon:\n  - type: Website\n    url: https://www.sigstore.dev/\n\
  \  - type: Documentation\n    url: https://docs.sigstore.dev/cosign/\n  - type: GettingStarted\n    url: https://docs.sigstore.dev/quickstart/quickstart-cosign/\n  - type: Installation\n    url: https://docs.sigstore.dev/cosign/system_config/installation/\n  - type: GitHubOrganization\n    url: https://github.com/sigstore\n  - type: GitHubRepository\n    url: https://github.com/sigstore/cosign\n  - type: Releases\n    url: https://github.com/sigstore/cosign/releases\n  - type: Blog\n    url: https://blog.sigstore.dev/\n  - type: Community\n    url: https://docs.sigstore.dev/about/community/\n  - type: Slack\n    url: https://sigstore.slack.com/\n  - type: License\n    url: https://github.com/sigstore/cosign/blob/main/LICENSE\n  - type: Security\n    url: https://github.com/sigstore/cosign/security\n  - type: Roadmap\n    url: https://github.com/sigstore/cosign/blob/main/ROADMAP.md\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cosign/refs/heads/main/apis.yml
tags:
- Apache 2.0
- Attestations
- CLI
- Code Signing
- Containers
- Fulcio
- Go
- Keyless
- OCI
- OIDC
- Open Source
- Rekor
- Sigstore
- Supply Chain
- Transparency Log
- Verification
url: https://raw.githubusercontent.com/api-evangelist/cosign/refs/heads/main/apis.yml
use_cases: []
---
