---
api_count: 1
api_specs:
- filename: sonatype-nexus-repository-openapi.yml
  format: yaml
  label: Nexus Repository API
  slug: nexus-repository-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/openapi/sonatype-nexus-repository-openapi.yml
apis:
- description: REST API for Sonatype Nexus Repository Manager (v3.91.0) providing 238 endpoints for managing repositories across many formats (Maven, npm, Docker, PyPI, NuGet, RubyGems, Go, Cargo, Helm, Terraform, R
  name: Nexus Repository API
  slug: nexus-repository-api
capabilities:
- description: Workflow capability for managing software artifacts, components, assets, and repositories in Sonatype Nexus Repository Manager. Supports DevOps engineers, build engineers, and platform teams performin
  name: Sonatype Nexus Artifact Management
  slug: artifact-management
- description: Workflow capability for managing Nexus Repository security including users, roles, privileges, LDAP, SAML, content selectors, and authentication realms. Used by platform administrators and security te
  name: Sonatype Nexus Security Administration
  slug: security-administration
common:
- title: ''
  type: Portal
  url: https://www.sonatype.com/products/sonatype-nexus-repository
- title: ''
  type: Documentation
  url: https://help.sonatype.com/en/sonatype-nexus-repository.html
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
  url: https://help.sonatype.com/en/release-notes.html
- title: ''
  type: Support
  url: https://support.sonatype.com/
- title: ''
  type: Pricing
  url: https://www.sonatype.com/products/sonatype-nexus-repository/pricing
created: '2026-03-16'
description: Sonatype Nexus Repository Manager provides a comprehensive REST API for managing software artifacts, repositories, and components across the software development lifecycle. It supports popular formats including Maven, npm, Docker, PyPI, NuGet, RubyGems, Go, Helm, APT, Yum, Cargo, Terraform, R, Swift, and more. The API covers repository configuration, component and asset management, security, blob stores, search, tasks, cleanup policies, staging, and system administration.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Sonatype Nexus Context
  property_count: 17
  slug: sonatype-nexus-context
layout: provider
modified: '2026-05-02'
name: Sonatype Nexus
rules:
- name: Sonatype Nexus API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 7
  slug: sonatype-nexus-rules
skills: []
slug: sonatype-nexus
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sonatype-nexus\nname: Sonatype Nexus\ndescription: >-\n  Sonatype Nexus Repository Manager provides a comprehensive REST API for managing\n  software artifacts, repositories, and components across the software development\n  lifecycle. It supports popular formats including Maven, npm, Docker, PyPI, NuGet,\n  RubyGems, Go, Helm, APT, Yum, Cargo, Terraform, R, Swift, and more. The API covers\n  repository configuration, component and asset management, security, blob stores,\n  search, tasks, cleanup policies, staging, and system administration.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Artifact Management\n  - DevOps\n  - Package Management\n  - Repository\n  - Maven\n  - npm\n  - Docker\n  - Software Supply Chain\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: sonatype-nexus:nexus-repository-api\n\
  \    name: Nexus Repository API\n    description: >-\n      REST API for Sonatype Nexus Repository Manager (v3.91.0) providing 238 endpoints\n      for managing repositories across many formats (Maven, npm, Docker, PyPI, NuGet,\n      RubyGems, Go, Cargo, Helm, Terraform, R, APT, Yum, Raw, Swift, and more),\n      components, assets, blob stores (file, S3, Azure, GCS), security (users, roles,\n      privileges, LDAP, SAML, Crowd), search, tasks, cleanup policies, staging, and\n      system administration. Authentication uses HTTP Basic Auth or User Tokens.\n    humanURL: https://help.sonatype.com/en/api-reference.html\n    baseURL: https://{nexus-host}/service/rest\n    tags:\n      - Artifact Management\n      - Components\n      - Repository\n      - Security\n      - Search\n      - Tasks\n      - Blob Store\n      - Maven\n      - npm\n      - Docker\n    properties:\n      - type: Documentation\n        url: https://help.sonatype.com/en/api-reference.html\n      - type: Reference\n\
  \        url: https://help.sonatype.com/en/rest-and-integration-api.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/openapi/sonatype-nexus-repository-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/json-schema/sonatype-nexus-component-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/json-schema/sonatype-nexus-repository-schema.json\n    contact:\n      - FN: Sonatype Support\n        url: https://support.sonatype.com/\ncommon:\n  - type: Portal\n    url: https://www.sonatype.com/products/sonatype-nexus-repository\n  - type: Documentation\n    url: https://help.sonatype.com/en/sonatype-nexus-repository.html\n  - type: Website\n    url: https://www.sonatype.com/\n  - type: GitHub\n    url: https://github.com/sonatype-nexus-community\n\
  \  - type: Blog\n    url: https://www.sonatype.com/blog\n  - type: Changelog\n    url: https://help.sonatype.com/en/release-notes.html\n  - type: Support\n    url: https://support.sonatype.com/\n  - type: Pricing\n    url: https://www.sonatype.com/products/sonatype-nexus-repository/pricing\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/apis.yml
tags:
- Artifact Management
- DevOps
- Package Management
- Repository
- Maven
- npm
- Docker
- Software Supply Chain
url: https://raw.githubusercontent.com/api-evangelist/sonatype-nexus/refs/heads/main/apis.yml
use_cases: []
---
