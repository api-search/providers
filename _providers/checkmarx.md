---
api_count: 3
api_specs:
- filename: checkmarx-sast-openapi.yml
  format: yaml
  label: Checkmarx SAST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/checkmarx/refs/heads/main/openapi/checkmarx-sast-openapi.yml
- filename: checkmarx-sca-openapi.yml
  format: yaml
  label: Checkmarx SCA API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/checkmarx/refs/heads/main/openapi/checkmarx-sca-openapi.yml
- filename: checkmarx-one-openapi.yml
  format: yaml
  label: Checkmarx One API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/checkmarx/refs/heads/main/openapi/checkmarx-one-openapi.yml
apis:
- description: API for Checkmarx Static Application Security Testing (SAST) to scan source code for security vulnerabilities.
  name: Checkmarx SAST API
  slug: ''
- description: API for Software Composition Analysis to identify open source vulnerabilities and license compliance issues.
  name: Checkmarx SCA API
  slug: ''
- description: Unified API for Checkmarx One cloud-native application security platform.
  name: Checkmarx One API
  slug: ''
common:
- title: ''
  type: Website
  url: https://www.checkmarx.com
- title: ''
  type: Documentation
  url: https://checkmarx.com/resource/documents/
- title: ''
  type: Support
  url: https://support.checkmarx.com/
- title: ''
  type: Login
  url: https://checkmarx.com/login/
- title: ''
  type: Blog
  url: https://checkmarx.com/blog/
- title: ''
  type: News
  url: https://checkmarx.com/news/
- title: ''
  type: GitHub
  url: https://github.com/checkmarx
- title: ''
  type: Status
  url: https://status.checkmarx.com/
- title: ''
  type: Privacy Policy
  url: https://checkmarx.com/privacy-policy/
- title: ''
  type: Terms of Service
  url: https://checkmarx.com/terms-of-use/
- title: ''
  type: JSON-LD
  url: json-ld/checkmarx-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/checkmarx-scan-result-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/checkmarx-vulnerability-schema.json
- title: ''
  type: Spectral
  url: spectral/checkmarx-spectral.yml
- title: ''
  type: NaftikoCapabilities
  url: naftiko/checkmarx-capabilities.yml
created: '2024'
description: Checkmarx is a leading application security testing solution provider, offering static application security testing (SAST), software composition analysis (SCA), and other security tools to help organizations identify and remediate vulnerabilities in their code.
features: []
image: https://www.checkmarx.com/wp-content/uploads/2022/03/checkmarx-logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Checkmarx Context
  property_count: 10
  slug: checkmarx-context
layout: provider
modified: '2026-04-23'
name: Checkmarx
skills: []
slug: checkmarx
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Checkmarx\ndescription: Checkmarx is a leading application security testing solution provider, offering static application security testing (SAST), software composition analysis (SCA), and other security tools to help organizations identify and remediate vulnerabilities in their code.\nimage: https://www.checkmarx.com/wp-content/uploads/2022/03/checkmarx-logo.svg\ntags:\n  - Application Security\n  - Code Analysis\n  - DevSecOps\n  - SAST\n  - Security Testing\n  - Vulnerability Scanning\ncreated: '2024'\nmodified: '2026-04-23'\nurl: https://www.checkmarx.com\nspecificationVersion: '0.20'\napis:\n  - name: Checkmarx SAST API\n    description: >-\n      API for Checkmarx Static Application Security Testing (SAST) to scan source\n      code for security vulnerabilities.\n    image: https://www.checkmarx.com/wp-content/uploads/2022/03/checkmarx-logo.svg\n    humanURL: https://checkmarx.com/resource/documents/en/34965-8158-rest-api.html\n    baseURL: https://your-checkmarx-instance.com/cxrestapi\n\
  \    tags:\n      - SAST\n      - Security Scanning\n      - Static Analysis\n      - Vulnerability Detection\n    properties:\n      - type: Documentation\n        url: https://checkmarx.com/resource/documents/en/34965-8158-rest-api.html\n      - type: OpenAPI\n        url: https://checkmarx.com/resource/documents/en/34965-8158-rest-api.html\n      - type: Authentication\n        url: https://checkmarx.com/resource/documents/en/34965-8158-authentication.html\n      - type: OpenAPI\n        url: openapi/checkmarx-sast-openapi.yml\n  - name: Checkmarx SCA API\n    description: >-\n      API for Software Composition Analysis to identify open source vulnerabilities\n      and license compliance issues.\n    image: https://www.checkmarx.com/wp-content/uploads/2022/03/checkmarx-logo.svg\n    humanURL: https://checkmarx.com/resource/documents/en/34965-68617-api.html\n    baseURL: https://api-sca.checkmarx.net\n    tags:\n      - Dependency Scanning\n      - License Compliance\n      - Open Source\
  \ Security\n      - SCA\n    properties:\n      - type: Documentation\n        url: https://checkmarx.com/resource/documents/en/34965-68617-api.html\n      - type: Authentication\n        url: https://checkmarx.com/resource/documents/en/34965-68617-authentication.html\n      - type: OpenAPI\n        url: openapi/checkmarx-sca-openapi.yml\n  - name: Checkmarx One API\n    description: >-\n      Unified API for Checkmarx One cloud-native application security platform.\n    image: https://www.checkmarx.com/wp-content/uploads/2022/03/checkmarx-logo.svg\n    humanURL: https://checkmarx.com/resource/documents/en/34965-128036-checkmarx-one-api.html\n    baseURL: https://ast.checkmarx.net/api\n    tags:\n      - Application Security\n      - Cloud Security\n      - DevSecOps\n      - Unified Platform\n    properties:\n      - type: Documentation\n        url: https://checkmarx.com/resource/documents/en/34965-128036-checkmarx-one-api.html\n      - type: API Reference\n        url: https://checkmarx.com/resource/documents/en/34965-128036-api-reference.html\n\
  \      - type: OpenAPI\n        url: openapi/checkmarx-one-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.checkmarx.com\n  - type: Documentation\n    url: https://checkmarx.com/resource/documents/\n  - type: Support\n    url: https://support.checkmarx.com/\n  - type: Login\n    url: https://checkmarx.com/login/\n  - type: Blog\n    url: https://checkmarx.com/blog/\n  - type: News\n    url: https://checkmarx.com/news/\n  - type: GitHub\n    url: https://github.com/checkmarx\n  - type: Status\n    url: https://status.checkmarx.com/\n  - type: Privacy Policy\n    url: https://checkmarx.com/privacy-policy/\n  - type: Terms of Service\n    url: https://checkmarx.com/terms-of-use/\n  - type: JSON-LD\n    url: json-ld/checkmarx-context.jsonld\n  - type: JSONSchema\n    url: json-schema/checkmarx-scan-result-schema.json\n  - type: JSONSchema\n    url: json-schema/checkmarx-vulnerability-schema.json\n  - type: Spectral\n    url: spectral/checkmarx-spectral.yml\n  - type: NaftikoCapabilities\n\
  \    url: naftiko/checkmarx-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/checkmarx/refs/heads/main/apis.yml
tags:
- Application Security
- Code Analysis
- DevSecOps
- SAST
- Security Testing
- Vulnerability Scanning
url: https://www.checkmarx.com
use_cases: []
---
