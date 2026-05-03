---
api_count: 1
api_specs:
- filename: sonatype-lifecycle-openapi.yml
  format: yaml
  label: Sonatype Lifecycle API
  slug: sonatype-lifecycle-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/openapi/sonatype-lifecycle-openapi.yml
apis:
- description: 'The Sonatype Lifecycle Public REST API (v1.201.0) provides 188 endpoints for managing applications, organizations, policies, policy violations, waivers, vulnerability analysis, SBOM generation (SPDX, '
  name: Sonatype Lifecycle API
  slug: sonatype-lifecycle-api
capabilities:
- description: Workflow capability for software supply chain security using Sonatype Lifecycle. Covers application portfolio management, policy violation monitoring, vulnerability intelligence, component analysis, S
  name: Sonatype Software Supply Chain Security
  slug: software-supply-chain-security
common:
- title: ''
  type: Portal
  url: https://www.sonatype.com/
- title: ''
  type: Documentation
  url: https://help.sonatype.com/
- title: ''
  type: Website
  url: https://www.sonatype.com/
- title: ''
  type: GitHub
  url: https://github.com/sonatype-nexus-community
- title: ''
  type: Blog
  url: https://www.sonatype.com/blog
- title: ''
  type: Changelog
  url: https://help.sonatype.com/en/sonatype-iq-server-2025-release-notes.html
- title: ''
  type: Support
  url: https://support.sonatype.com/
- title: ''
  type: Pricing
  url: https://www.sonatype.com/products/pricing
created: '2025-02-12'
description: Sonatype provides software supply chain management solutions including Sonatype Lifecycle (IQ Server), Sonatype Repository Firewall, SBOM Manager, and Nexus Repository. The Lifecycle Public REST API provides 188 endpoints for application portfolio management, policy enforcement, vulnerability reporting, component analysis, SBOM generation, source control integration, and software composition analysis across the SDLC.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 2
  name: Sonatype Context
  property_count: 12
  slug: sonatype-context
layout: provider
modified: '2026-05-02'
name: Sonatype
rules:
- name: Sonatype API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 6
  slug: sonatype-rules
skills: []
slug: sonatype
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sonatype\nname: Sonatype\ndescription: >-\n  Sonatype provides software supply chain management solutions including Sonatype Lifecycle\n  (IQ Server), Sonatype Repository Firewall, SBOM Manager, and Nexus Repository. The\n  Lifecycle Public REST API provides 188 endpoints for application portfolio management,\n  policy enforcement, vulnerability reporting, component analysis, SBOM generation,\n  source control integration, and software composition analysis across the SDLC.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Software Supply Chain\n  - Security\n  - Vulnerability Management\n  - SBOM\n  - Software Composition Analysis\n  - DevSecOps\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/apis.yml\ncreated: '2025-02-12'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: sonatype:sonatype-lifecycle-api\n    name: Sonatype\
  \ Lifecycle API\n    description: >-\n      The Sonatype Lifecycle Public REST API (v1.201.0) provides 188 endpoints for\n      managing applications, organizations, policies, policy violations, waivers,\n      vulnerability analysis, SBOM generation (SPDX, CycloneDX), scan management,\n      component search, reports, source control integration, users, roles, and\n      user tokens. Used by DevSecOps teams to automate software supply chain\n      security and compliance workflows.\n    humanURL: https://help.sonatype.com/en/iq-api-reference.html\n    baseURL: https://{iq-server-host}/\n    tags:\n      - Software Supply Chain\n      - Security\n      - Policy\n      - Vulnerability Management\n      - SBOM\n      - Software Composition Analysis\n      - Applications\n      - Organizations\n    properties:\n      - type: Documentation\n        url: https://help.sonatype.com/en/iq-api-reference.html\n      - type: Reference\n        url: https://help.sonatype.com/en/rest-apis.html\n   \
  \   - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/openapi/sonatype-lifecycle-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/json-schema/sonatype-application-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/json-schema/sonatype-policy-violation-schema.json\n    contact:\n      - FN: Sonatype Support\n        url: https://support.sonatype.com/\ncommon:\n  - type: Portal\n    url: https://www.sonatype.com/\n  - type: Documentation\n    url: https://help.sonatype.com/\n  - type: Website\n    url: https://www.sonatype.com/\n  - type: GitHub\n    url: https://github.com/sonatype-nexus-community\n  - type: Blog\n    url: https://www.sonatype.com/blog\n  - type: Changelog\n    url: https://help.sonatype.com/en/sonatype-iq-server-2025-release-notes.html\n\
  \  - type: Support\n    url: https://support.sonatype.com/\n  - type: Pricing\n    url: https://www.sonatype.com/products/pricing\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/apis.yml
tags:
- Software Supply Chain
- Security
- Vulnerability Management
- SBOM
- Software Composition Analysis
- DevSecOps
url: https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/apis.yml
use_cases: []
---
