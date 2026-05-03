---
api_count: 4
api_specs:
- filename: openssf-osv-openapi.yml
  format: yaml
  label: OSV (Open Source Vulnerabilities) API
  slug: osv-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/openapi/openssf-osv-openapi.yml
- filename: openssf-scorecard-openapi.yml
  format: yaml
  label: OpenSSF Scorecard API
  slug: scorecard-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/openapi/openssf-scorecard-openapi.yml
apis:
- description: OSV is an OpenSSF-hosted distributed vulnerability database and query infrastructure. The OSV API at api.osv.dev exposes vulnerability records keyed to specific package versions or commits across mult
  name: OSV (Open Source Vulnerabilities) API
  slug: osv-api
- description: The OpenSSF Scorecard API returns automated security health metrics for public open source repositories. Scorecard runs a series of checks (e.g., Branch-Protection, Code-Review, Pinned-Dependencies, S
  name: OpenSSF Scorecard API
  slug: scorecard-api
- description: Sigstore is an OpenSSF-hosted standard and service for signing, verifying, and protecting software. The public-good Sigstore instance exposes Fulcio (code-signing certificate authority) and Rekor (tra
  name: Sigstore Public Good APIs
  slug: sigstore-api
- description: GUAC aggregates software supply-chain security metadata (SBOMs, attestations, vulnerabilities, signatures) into a queryable graph. GUAC exposes a GraphQL API for supply-chain queries when self-hosted.
  name: GUAC (Graph for Understanding Artifact Composition)
  slug: guac-api
common:
- title: ''
  type: Website
  url: https://openssf.org/
- title: ''
  type: Documentation
  url: https://openssf.org/resources/
- title: ''
  type: Portal
  url: https://openssf.org/projects/
- title: ''
  type: Blog
  url: https://openssf.org/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/ossf
- title: ''
  type: GitHubRepository
  url: https://github.com/ossf/osv-schema
- title: ''
  type: GitHubRepository
  url: https://github.com/ossf/scorecard
- title: ''
  type: GitHubOrganization
  url: https://github.com/sigstore
- title: ''
  type: License
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Community
  url: https://openssf.org/community/
- title: ''
  type: Slack
  url: https://slack.openssf.org/
created: '2026-03-16'
description: The Open Source Security Foundation (OpenSSF) is a collaborative initiative under the Linux Foundation dedicated to improving the security of open source software. It brings together industry leaders, developers, and security experts to address vulnerabilities, enhance supply chain security, and develop security tools and best practices. OpenSSF stewards a number of projects with public REST APIs, including the OSV (Open Source Vulnerabilities) database, the Scorecard automated security health-check service, and Sigstore signing infrastructure.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 7
  name: Openssf Context
  property_count: 0
  slug: openssf-context
layout: provider
modified: '2026-04-28'
name: OpenSSF
skills: []
slug: openssf
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: openssf\nname: OpenSSF\ndescription: >-\n  The Open Source Security Foundation (OpenSSF) is a collaborative initiative\n  under the Linux Foundation dedicated to improving the security of open\n  source software. It brings together industry leaders, developers, and\n  security experts to address vulnerabilities, enhance supply chain\n  security, and develop security tools and best practices. OpenSSF stewards\n  a number of projects with public REST APIs, including the OSV (Open\n  Source Vulnerabilities) database, the Scorecard automated security\n  health-check service, and Sigstore signing infrastructure.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Linux Foundation\n  - Open Source\n  - Security\n  - Supply Chain\n  - Vulnerabilities\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: openssf:osv-api\n    name: OSV (Open Source Vulnerabilities) API\n    description: >-\n      OSV is an OpenSSF-hosted distributed vulnerability database and\n      query infrastructure. The OSV API at api.osv.dev exposes\n      vulnerability records keyed to specific package versions or commits\n      across multiple ecosystems including npm, PyPI, Maven, Go, NuGet,\n      RubyGems, Cargo, Packagist, Hex, OSS-Fuzz, Linux, Android, and\n      GitHub Actions.\n    humanURL: https://osv.dev/\n    baseURL: https://api.osv.dev\n    tags:\n      - Vulnerabilities\n      - Supply Chain\n      - Database\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://google.github.io/osv.dev/api/\n      - type: Documentation\n        url: https://osv.dev/\n      - type: GitHubRepository\n        url: https://github.com/google/osv.dev\n      - type: GitHubRepository\n        url: https://github.com/ossf/osv-schema\n      - type:\
  \ OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/openapi/openssf-osv-openapi.yml\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/json-schema/openssf-osv-vulnerability-schema.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/json-ld/openssf-context.jsonld\n  - aid: openssf:scorecard-api\n    name: OpenSSF Scorecard API\n    description: >-\n      The OpenSSF Scorecard API returns automated security health metrics\n      for public open source repositories. Scorecard runs a series of\n      checks (e.g., Branch-Protection, Code-Review, Pinned-Dependencies,\n      Signed-Releases, Token-Permissions, Vulnerabilities) and exposes\n      per-check scores plus an aggregate 0-10 score via api.securityscorecards.dev.\n    humanURL: https://scorecard.dev/\n    baseURL: https://api.securityscorecards.dev\n    tags:\n\
  \      - Security Health\n      - Repositories\n      - Supply Chain\n    properties:\n      - type: Documentation\n        url: https://github.com/ossf/scorecard\n      - type: Documentation\n        url: https://scorecard.dev/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/openapi/openssf-scorecard-openapi.yml\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/json-ld/openssf-context.jsonld\n  - aid: openssf:sigstore-api\n    name: Sigstore Public Good APIs\n    description: >-\n      Sigstore is an OpenSSF-hosted standard and service for signing,\n      verifying, and protecting software. The public-good Sigstore\n      instance exposes Fulcio (code-signing certificate authority) and\n      Rekor (transparency log) APIs that can be queried programmatically\n      to inspect signing certificates and transparency log entries.\n    humanURL: https://www.sigstore.dev/\n\
  \    baseURL: https://rekor.sigstore.dev\n    tags:\n      - Signing\n      - Transparency Log\n      - Supply Chain\n    properties:\n      - type: Documentation\n        url: https://docs.sigstore.dev/\n      - type: Documentation\n        url: https://docs.sigstore.dev/logging/overview/\n      - type: GitHubOrganization\n        url: https://github.com/sigstore\n  - aid: openssf:guac-api\n    name: GUAC (Graph for Understanding Artifact Composition)\n    description: >-\n      GUAC aggregates software supply-chain security metadata (SBOMs,\n      attestations, vulnerabilities, signatures) into a queryable graph.\n      GUAC exposes a GraphQL API for supply-chain queries when self-hosted.\n    humanURL: https://guac.sh/\n    baseURL: https://guac.sh\n    tags:\n      - SBOM\n      - Supply Chain\n      - GraphQL\n    properties:\n      - type: Documentation\n        url: https://docs.guac.sh/\n      - type: GitHubRepository\n        url: https://github.com/guacsec/guac\ncommon:\n  -\
  \ type: Website\n    name: OpenSSF\n    url: https://openssf.org/\n  - type: Documentation\n    name: OpenSSF Documentation\n    url: https://openssf.org/resources/\n  - type: Portal\n    name: Projects Directory\n    url: https://openssf.org/projects/\n  - type: Blog\n    name: OpenSSF Blog\n    url: https://openssf.org/blog/\n  - type: GitHubOrganization\n    name: OpenSSF GitHub\n    url: https://github.com/ossf\n  - type: GitHubRepository\n    name: OSV Schema\n    url: https://github.com/ossf/osv-schema\n  - type: GitHubRepository\n    name: Scorecard\n    url: https://github.com/ossf/scorecard\n  - type: GitHubOrganization\n    name: Sigstore GitHub\n    url: https://github.com/sigstore\n  - type: License\n    name: Apache 2.0\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Community\n    name: OpenSSF Community\n    url: https://openssf.org/community/\n  - type: Slack\n    name: OpenSSF Slack\n    url: https://slack.openssf.org/\nmaintainers:\n  - FN: Kin Lane\n\
  \    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/apis.yml
tags:
- Linux Foundation
- Open Source
- Security
- Supply Chain
- Vulnerabilities
url: https://raw.githubusercontent.com/api-evangelist/openssf/refs/heads/main/apis.yml
use_cases: []
---
