---
api_count: 1
api_specs:
- filename: unpaywall-openapi.yml
  format: yaml
  label: Unpaywall API
  slug: unpaywall
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/openapi/unpaywall-openapi.yml
apis:
- description: Free REST API providing open access status and full-text links for 120M+ scholarly articles. Look up any article by DOI to get its OA status, best open access location (publisher or repository), licen
  name: Unpaywall API
  slug: unpaywall
capabilities:
- description: 'Workflow capability for discovering free, legal full-text versions of scholarly articles using Unpaywall. Enables researchers, librarians, and developers to check open access status by DOI and search '
  name: Unpaywall Open Access Discovery
  slug: open-access-discovery
common:
- title: ''
  type: Website
  url: https://unpaywall.org
- title: ''
  type: Documentation
  url: https://unpaywall.org/products/api
- title: ''
  type: DataFormat
  url: https://unpaywall.org/data-format
- title: ''
  type: Support
  url: https://support.unpaywall.org
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/vocabulary/unpaywall-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/json-ld/unpaywall-context.jsonld
created: '2025-02-06'
description: The Unpaywall REST API gives anyone free, programmatic access to the Unpaywall database of open access scholarly articles. The database covers over 120 million articles with Crossref DOIs and provides free, legal full-text links where available, with metadata on OA status (gold, hybrid, bronze, green), host type (publisher, repository), version (published, accepted, submitted), and license information.
features: []
image: ''
integrations: []
jsonld:
- class_count: 8
  name: Unpaywall Context
  property_count: 37
  slug: unpaywall-context
layout: provider
modified: '2026-05-03'
name: Unpaywall
rules:
- name: Unpaywall API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 3
  slug: unpaywall-rules
skills: []
slug: unpaywall
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: unpaywall\nname: Unpaywall\ndescription: >-\n  The Unpaywall REST API gives anyone free, programmatic access to the Unpaywall\n  database of open access scholarly articles. The database covers over 120 million\n  articles with Crossref DOIs and provides free, legal full-text links where available,\n  with metadata on OA status (gold, hybrid, bronze, green), host type (publisher,\n  repository), version (published, accepted, submitted), and license information.\nurl: https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/apis.yml\ncreated: '2025-02-06'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Open Access\n  - Scholarly Articles\n  - Research\n  - Academic\n  - Libraries\n  - DOI\n  - Science\napis:\n  - aid: unpaywall:unpaywall\n    name: Unpaywall API\n    description: >-\n      Free REST API providing open access status and full-text links for 120M+ scholarly\n      articles. Look up any article by DOI to get its\
  \ OA status, best open access location\n      (publisher or repository), license, version, and all available free copies. Also\n      supports title-based search across the full database. No API key required — just\n      include your email address in requests. Rate limit: 100,000 calls per day.\n    humanURL: https://unpaywall.org/products/api\n    baseURL: https://api.unpaywall.org/v2\n    tags:\n      - Open Access\n      - DOI\n      - Scholarly Articles\n      - Search\n    properties:\n      - type: Documentation\n        url: https://unpaywall.org/products/api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/openapi/unpaywall-openapi.yml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/rules/unpaywall-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/capabilities/open-access-discovery.yaml\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/json-schema/unpaywall-article-schema.json\n\ncommon:\n  - type: Website\n    url: https://unpaywall.org\n  - type: Documentation\n    url: https://unpaywall.org/products/api\n  - type: DataFormat\n    url: https://unpaywall.org/data-format\n  - type: Support\n    url: https://support.unpaywall.org\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/vocabulary/unpaywall-vocabulary.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/json-ld/unpaywall-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/apis.yml
tags:
- Open Access
- Scholarly Articles
- Research
- Academic
- Libraries
- DOI
- Science
url: https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/apis.yml
use_cases: []
---
