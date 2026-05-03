---
api_count: 1
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Cloudsmith API (v1)
  slug: v1
  spec_type: OpenAPI
  url: https://api.cloudsmith.io/?format=openapi
apis:
- description: The Cloudsmith REST API (v1) covers 217+ endpoints across 22 tag groups including repos, orgs, packages, entitlements, files, user, webhooks, quota, vulnerabilities, metrics, audit-log, distros, forma
  name: Cloudsmith API (v1)
  slug: v1
capabilities:
- description: ''
  name: Package Management
  slug: package-management
common:
- title: ''
  type: Website
  url: https://cloudsmith.com/
- title: ''
  type: Documentation
  url: https://docs.cloudsmith.com/
- title: ''
  type: API Reference
  url: https://docs.cloudsmith.com/api
- title: ''
  type: Getting Started
  url: https://help.cloudsmith.io/reference/getting-started-with-the-api
- title: ''
  type: Status
  url: https://status.cloudsmith.io/
- title: ''
  type: Privacy Policy
  url: https://cloudsmith.com/legal/privacy-notice/
- title: ''
  type: GitHub
  url: https://github.com/cloudsmith-io
- title: ''
  type: OpenAPI
  url: openapi/cloudsmith-openapi.json
- title: ''
  type: JSON-LD
  url: json-ld/cloudsmith-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloudsmith-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/package-management.yaml
created: '2024-01-01'
description: Cloudsmith is a cloud-native, universal package management platform providing fully managed, geo-replicated artifact repositories for over 30 package formats (Docker, npm, Maven, NuGet, PyPI, RubyGems, RPM, Deb, Helm, Cargo, Go, Composer, Conan, Conda, Vagrant, Raw, and more). The Cloudsmith REST API (v1) at api.cloudsmith.io exposes operations for organizations, repositories, packages, files, entitlements, vulnerabilities, webhooks, audit logs, metrics, quotas, deny policies, namespaces, distros, formats, recycle bin, storage regions, and broadcasts. Authentication is via API key passed in the Authorization header as "token YOUR_API_KEY".
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloudsmith Context
  property_count: 9
  slug: cloudsmith-context
layout: provider
modified: '2026-04-25'
name: Cloudsmith
rules:
- name: Cloudsmith API Rules
  rule_count: 14
  severity_counts:
    error: 4
    hint: 0
    info: 5
    warn: 5
  slug: cloudsmith-rules
skills: []
slug: cloudsmith
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloudsmith\nname: Cloudsmith\ndescription: >-\n  Cloudsmith is a cloud-native, universal package management platform\n  providing fully managed, geo-replicated artifact repositories for over 30\n  package formats (Docker, npm, Maven, NuGet, PyPI, RubyGems, RPM, Deb, Helm,\n  Cargo, Go, Composer, Conan, Conda, Vagrant, Raw, and more). The Cloudsmith\n  REST API (v1) at api.cloudsmith.io exposes operations for organizations,\n  repositories, packages, files, entitlements, vulnerabilities, webhooks,\n  audit logs, metrics, quotas, deny policies, namespaces, distros, formats,\n  recycle bin, storage regions, and broadcasts. Authentication is via API\n  key passed in the Authorization header as \"token YOUR_API_KEY\".\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/cloudsmith/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-25'\nspecificationVersion: '0.19'\n\
  x-type: company\ntags:\n  - Artifact Management\n  - DevOps\n  - DevSecOps\n  - Distribution\n  - Package Management\n  - Registry\n  - Repository\n  - Software Supply Chain\n  - Universal\n  - Vulnerability Scanning\napis:\n  - aid: cloudsmith:v1\n    name: Cloudsmith API (v1)\n    tags:\n      - REST\n      - Packages\n      - Repositories\n      - Entitlements\n      - Webhooks\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.cloudsmith.io\n    humanURL: https://docs.cloudsmith.com/api\n    properties:\n      - url: https://docs.cloudsmith.com/api\n        type: Documentation\n      - url: https://api.cloudsmith.io/?format=openapi\n        type: OpenAPI\n      - url: openapi/cloudsmith-openapi.json\n        type: OpenAPI\n      - url: https://help.cloudsmith.io/reference/getting-started-with-the-api\n        type: Getting Started\n    description: >-\n      The Cloudsmith REST API (v1) covers 217+ endpoints across 22 tag\n\
  \      groups including repos, orgs, packages, entitlements, files, user,\n      webhooks, quota, vulnerabilities, metrics, audit-log, distros,\n      formats, namespaces, recycle-bin, storage-regions, badges,\n      broadcasts, bulk-action, rates, status. Default page size is 30\n      items, max 500. Authentication is via personal or service-account\n      API key in the Authorization header.\ncommon:\n  - type: Website\n    url: https://cloudsmith.com/\n  - type: Documentation\n    url: https://docs.cloudsmith.com/\n  - type: API Reference\n    url: https://docs.cloudsmith.com/api\n  - type: Getting Started\n    url: https://help.cloudsmith.io/reference/getting-started-with-the-api\n  - type: Status\n    url: https://status.cloudsmith.io/\n  - type: Privacy Policy\n    url: https://cloudsmith.com/legal/privacy-notice/\n  - type: GitHub\n    url: https://github.com/cloudsmith-io\n  - type: OpenAPI\n    url: openapi/cloudsmith-openapi.json\n  - type: JSON-LD\n    url: json-ld/cloudsmith-context.jsonld\n\
  \  - type: Spectral\n    url: rules/cloudsmith-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/package-management.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudsmith/refs/heads/main/apis.yml
tags:
- Artifact Management
- DevOps
- DevSecOps
- Distribution
- Package Management
- Registry
- Repository
- Software Supply Chain
- Universal
- Vulnerability Scanning
url: https://raw.githubusercontent.com/api-evangelist/cloudsmith/refs/heads/main/apis.yml
use_cases: []
---
