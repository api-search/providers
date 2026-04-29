---
api_count: 3
apis:
- description: The copa command line interface used to patch container images. The core subcommand `copa patch` accepts an image reference and an optional vulnerability report and produces a new tagged image with OS
  name: Copa CLI
  slug: cli
- description: 'Copa exposes a plugin interface that allows third-party vulnerability scanners to feed reports into the patcher. Out of the box, Copa supports Trivy JSON reports and provides documentation for adding '
  name: Copa Scanner Plugin Interface
  slug: scanner-plugins
- description: 'Copa can emit a Vulnerability Exchange (VEX) document describing which CVEs were patched. VEX documents help security teams and downstream consumers verify that an image has been remediated and track '
  name: Copa VEX Output
  slug: vex
common:
- title: ''
  type: Website
  url: https://project-copacetic.github.io/copacetic/website/
- title: ''
  type: Documentation
  url: https://project-copacetic.github.io/copacetic/website/quick-start/
- title: ''
  type: GitHubRepository
  url: https://github.com/project-copacetic/copacetic
- title: ''
  type: GitHub Organization
  url: https://github.com/project-copacetic
- title: ''
  type: Issue Tracker
  url: https://github.com/project-copacetic/copacetic/issues
- title: ''
  type: Change Log
  url: https://github.com/project-copacetic/copacetic/releases
- title: ''
  type: License
  url: https://github.com/project-copacetic/copacetic/blob/main/LICENSE
- title: ''
  type: Community
  url: https://github.com/project-copacetic/copacetic/blob/main/CONTRIBUTING.md
created: '2025-01-01'
description: Project Copacetic (Copa) is an open source command line tool that patches container images directly using BuildKit, without requiring a full image rebuild. Copa parses vulnerability scan reports from Trivy and other scanners, applies the corresponding OS package updates via the appropriate package manager (apt, apk, dnf, tdnf, yum, zypper), and produces a new container image with a patched layer. Copa supports multi-platform images, distroless images, and custom scanner plugins through the Vulnerability Exchange (VEX) and pluggable scanner interface.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Copa (Project Copacetic)
skills: []
slug: copa
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: copa\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/copa/refs/heads/main/apis.yml\nname: Copa (Project Copacetic)\nx-type: opensource\ndescription: >-\n  Project Copacetic (Copa) is an open source command line tool that patches\n  container images directly using BuildKit, without requiring a full image\n  rebuild. Copa parses vulnerability scan reports from Trivy and other\n  scanners, applies the corresponding OS package updates via the appropriate\n  package manager (apt, apk, dnf, tdnf, yum, zypper), and produces a new\n  container image with a patched layer. Copa supports multi-platform\n  images, distroless images, and custom scanner plugins through the\n  Vulnerability Exchange (VEX) and pluggable scanner interface.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - BuildKit\n  - CLI\n  - CNCF Sandbox\n  - Container Patching\n  - Containers\n  - Open Source\n  - Security\n  - Trivy\n  - Vulnerability Management\n\
  created: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: copa:cli\n    name: Copa CLI\n    description: >-\n      The copa command line interface used to patch container images. The\n      core subcommand `copa patch` accepts an image reference and an\n      optional vulnerability report and produces a new tagged image with\n      OS-level package vulnerabilities remediated via BuildKit.\n    humanURL: https://project-copacetic.github.io/copacetic/website/\n    baseURL: https://project-copacetic.github.io\n    tags:\n      - CLI\n      - Patching\n    properties:\n      - type: Documentation\n        url: https://project-copacetic.github.io/copacetic/website/\n      - type: Reference\n        url: https://project-copacetic.github.io/copacetic/website/quick-start/\n      - type: GitHubRepository\n        url: https://github.com/project-copacetic/copacetic\n      - type: License\n        url: https://github.com/project-copacetic/copacetic/blob/main/LICENSE\n\
  \      - type: Issue Tracker\n        url: https://github.com/project-copacetic/copacetic/issues\n    x-features:\n      - \"`copa patch -i IMAGE` patches all outdated OS packages\"\n      - \"`copa patch -r REPORT.json -i IMAGE` patches based on a Trivy report\"\n      - Multi-platform image patching\n      - Distroless image support\n      - Pluggable scanner plugins\n      - VEX (Vulnerability Exchange) document generation\n    x-useCases:\n      - Remediating OS-level CVEs in third-party container images\n      - Continuously patching base images during security incidents\n      - Inserting Copa into CI/CD pipelines after Trivy scans\n  - aid: copa:scanner-plugins\n    name: Copa Scanner Plugin Interface\n    description: >-\n      Copa exposes a plugin interface that allows third-party vulnerability\n      scanners to feed reports into the patcher. Out of the box, Copa\n      supports Trivy JSON reports and provides documentation for adding\n      new scanner plugins.\n    humanURL:\
  \ https://project-copacetic.github.io/copacetic/website/scanner-plugins/\n    baseURL: https://project-copacetic.github.io\n    tags:\n      - Plugins\n      - Scanners\n      - Trivy\n    properties:\n      - type: Documentation\n        url: https://project-copacetic.github.io/copacetic/website/scanner-plugins/\n      - type: Reference\n        url: https://github.com/project-copacetic/copacetic/tree/main/pkg/vex\n    x-features:\n      - Trivy JSON parser built in\n      - Pluggable interface for additional scanners\n      - Standardized intermediate representation of vulnerability reports\n    x-useCases:\n      - Integrating internal vulnerability scanners with Copa\n      - Using Grype, Snyk, or Anchore reports as Copa input\n  - aid: copa:vex\n    name: Copa VEX Output\n    description: >-\n      Copa can emit a Vulnerability Exchange (VEX) document describing\n      which CVEs were patched. VEX documents help security teams and\n      downstream consumers verify that an image has\
  \ been remediated and\n      track residual risk.\n    humanURL: https://project-copacetic.github.io/copacetic/website/output/\n    baseURL: https://project-copacetic.github.io\n    tags:\n      - OpenVEX\n      - SBOM\n      - VEX\n    properties:\n      - type: Documentation\n        url: https://project-copacetic.github.io/copacetic/website/output/\n      - type: Reference\n        url: https://github.com/openvex/spec\n    x-features:\n      - Emits OpenVEX-compatible documents\n      - Records patched CVE identifiers and statuses\n      - Pairs with SBOMs for supply chain transparency\n    x-useCases:\n      - Communicating remediation status downstream\n      - Reducing scanner noise from CVEs already patched in place\ncommon:\n  - type: Website\n    url: https://project-copacetic.github.io/copacetic/website/\n  - type: Documentation\n    url: https://project-copacetic.github.io/copacetic/website/quick-start/\n  - type: GitHubRepository\n    url: https://github.com/project-copacetic/copacetic\n\
  \  - type: GitHub Organization\n    url: https://github.com/project-copacetic\n  - type: Issue Tracker\n    url: https://github.com/project-copacetic/copacetic/issues\n  - type: Change Log\n    url: https://github.com/project-copacetic/copacetic/releases\n  - type: License\n    url: https://github.com/project-copacetic/copacetic/blob/main/LICENSE\n  - type: Community\n    url: https://github.com/project-copacetic/copacetic/blob/main/CONTRIBUTING.md\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/copa/refs/heads/main/apis.yml
tags:
- BuildKit
- CLI
- CNCF Sandbox
- Container Patching
- Containers
- Open Source
- Security
- Trivy
- Vulnerability Management
url: https://raw.githubusercontent.com/api-evangelist/copa/refs/heads/main/apis.yml
use_cases: []
---
