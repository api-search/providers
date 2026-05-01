---
api_count: 3
api_specs:
- filename: debian-sources-api-openapi.yml
  format: yaml
  label: Debian Sources API
  slug: debian-sources-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/openapi/debian-sources-api-openapi.yml
- filename: debian-bts-api-openapi.yml
  format: yaml
  label: Debian Bug Tracking System
  slug: debian-bts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/openapi/debian-bts-api-openapi.yml
- filename: debian-udd-api-openapi.yml
  format: yaml
  label: Debian Ultimate Database (UDD)
  slug: debian-udd
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/openapi/debian-udd-api-openapi.yml
apis:
- description: The Debian Sources API at sources.debian.org provides programmatic access to source code, package metadata, copyright records, and Debian patches for every source package in the archive.
  name: Debian Sources API
  slug: debian-sources-api
- description: The Debian BTS at bugs.debian.org tracks bugs against packages and pseudo-packages. Bug reports are accessible as machine-readable mbox files and structured CGI views, with email serving as the canoni
  name: Debian Bug Tracking System
  slug: debian-bts-api
- description: The Ultimate Debian Database aggregates Debian-wide data into a single Postgres database and exposes web tools for bugs, maintainer dashboards, Lintian results, reproducibility, and more.
  name: Debian Ultimate Database (UDD)
  slug: debian-udd
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.debian.org/
- title: ''
  type: Wiki
  url: https://wiki.debian.org/
- title: ''
  type: Documentation
  url: https://www.debian.org/doc/
- title: ''
  type: GitLab
  url: https://salsa.debian.org/
- title: ''
  type: Mailing Lists
  url: https://lists.debian.org/
- title: ''
  type: Privacy Policy
  url: https://www.debian.org/legal/privacy
- title: ''
  type: License
  url: https://www.debian.org/social_contract
- title: ''
  type: JSON-LD
  url: json-ld/debian-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/debian-vocabulary.yml
created: '2025-01-01'
description: Debian is a free operating system distribution maintained by the Debian Project, a community of more than a thousand volunteers worldwide. Debian provides a number of developer-facing services including a source-code browsing API at sources.debian.org, the Bug Tracking System (BTS) at bugs.debian.org, and the Ultimate Debian Database (UDD) - a single Postgres database aggregating package, bug, Lintian, popcon, and reproducibility data for cross-cutting queries.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Debian Context
  property_count: 12
  slug: debian-context
layout: provider
modified: '2026-04-28'
name: Debian
rules:
- name: Debian API Rules
  rule_count: 5
  severity_counts:
    error: 0
    hint: 0
    info: 0
    warn: 5
  slug: debian-sources-api-rules
skills: []
slug: debian
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: debian\nname: Debian\nurl: https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/apis.yml\ntype: Index\nposition: Provider\naccess: Public\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Bug Tracker\n  - Debian\n  - Linux\n  - Open Source\n  - Operating System\n  - Package Management\n  - Source Code\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: opensource\ndescription: >-\n  Debian is a free operating system distribution maintained by the Debian\n  Project, a community of more than a thousand volunteers worldwide.\n  Debian provides a number of developer-facing services including a\n  source-code browsing API at sources.debian.org, the Bug Tracking\n  System (BTS) at bugs.debian.org, and the Ultimate Debian Database\n  (UDD) - a single Postgres database aggregating package, bug, Lintian,\n  popcon, and reproducibility data for cross-cutting queries.\napis:\n  - aid:\
  \ debian:debian-sources-api\n    name: Debian Sources API\n    description: >-\n      The Debian Sources API at sources.debian.org provides programmatic\n      access to source code, package metadata, copyright records, and\n      Debian patches for every source package in the archive.\n    humanURL: https://sources.debian.org/doc/api/\n    baseURL: https://sources.debian.org/api\n    tags:\n      - Copyright\n      - Packages\n      - Patches\n      - Source Code\n    properties:\n      - type: Documentation\n        url: https://sources.debian.org/doc/api/\n      - type: OpenAPI\n        url: openapi/debian-sources-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/debian-package.json\n      - type: Rules\n        url: rules/debian-sources-api-rules.yml\n      - type: Capabilities\n        url: capabilities/debian-sources-api-capabilities.yml\n  - aid: debian:debian-bts-api\n    name: Debian Bug Tracking System\n    description: >-\n      The Debian BTS at bugs.debian.org\
  \ tracks bugs against packages and\n      pseudo-packages. Bug reports are accessible as machine-readable\n      mbox files and structured CGI views, with email serving as the\n      canonical interaction surface.\n    humanURL: https://www.debian.org/Bugs/\n    baseURL: https://bugs.debian.org\n    tags:\n      - Bugs\n      - Maintainers\n      - Severity\n    properties:\n      - type: Documentation\n        url: https://www.debian.org/Bugs/\n      - type: OpenAPI\n        url: openapi/debian-bts-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/debian-bug.json\n  - aid: debian:debian-udd\n    name: Debian Ultimate Database (UDD)\n    description: >-\n      The Ultimate Debian Database aggregates Debian-wide data into a\n      single Postgres database and exposes web tools for bugs,\n      maintainer dashboards, Lintian results, reproducibility, and more.\n    humanURL: https://wiki.debian.org/UltimateDebianDatabase\n    baseURL: https://udd.debian.org\n    tags:\n\
  \      - Aggregated Data\n      - Lintian\n      - Reproducibility\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://wiki.debian.org/UltimateDebianDatabase\n      - type: OpenAPI\n        url: openapi/debian-udd-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.debian.org/\n  - type: Wiki\n    url: https://wiki.debian.org/\n  - type: Documentation\n    url: https://www.debian.org/doc/\n  - type: GitLab\n    url: https://salsa.debian.org/\n  - type: Mailing Lists\n    url: https://lists.debian.org/\n  - type: Privacy Policy\n    url: https://www.debian.org/legal/privacy\n  - type: License\n    url: https://www.debian.org/social_contract\n  - type: JSON-LD\n    url: json-ld/debian-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/debian-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/apis.yml
tags:
- Bug Tracker
- Debian
- Linux
- Open Source
- Operating System
- Package Management
- Source Code
url: https://raw.githubusercontent.com/api-evangelist/debian/refs/heads/main/apis.yml
use_cases: []
---
