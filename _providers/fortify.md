---
api_count: 3
api_specs:
- filename: fortify-on-demand-openapi.yml
  format: yaml
  label: Fortify on Demand API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fortify/refs/heads/main/openapi/fortify-on-demand-openapi.yml
- filename: fortify-software-security-center-openapi.yml
  format: yaml
  label: Fortify Software Security Center API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fortify/refs/heads/main/openapi/fortify-software-security-center-openapi.yml
- filename: fortify-scancentral-dast-openapi.yml
  format: yaml
  label: Fortify ScanCentral DAST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fortify/refs/heads/main/openapi/fortify-scancentral-dast-openapi.yml
apis:
- description: REST API for Fortify on Demand (FoD), the cloud-based application security testing service from OpenText. Provides programmatic access to manage applications, initiate scans, and retrieve vulnerabilit
  name: Fortify on Demand API
  slug: ''
- description: REST API for the on-premise Fortify Software Security Center (SSC), which provides centralized management and reporting of security assessment data across an organization's application portfolio.
  name: Fortify Software Security Center API
  slug: ''
- description: REST API for Fortify ScanCentral DAST, which provides centralized dynamic application security testing management. Enables orchestration of DAST scans across distributed sensors and integration with C
  name: Fortify ScanCentral DAST API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://ams.fortify.com/
- title: ''
  type: Documentation
  url: https://www.microfocus.com/documentation/fortify-on-demand/
- title: ''
  type: Getting Started
  url: https://www.microfocus.com/documentation/fortify-on-demand/
- title: ''
  type: Authentication
  url: https://api.ams.fortify.com/swagger/ui/index
- title: ''
  type: Blog
  url: https://community.opentext.com/cyberres/b/cybersecurity-blog
- title: ''
  type: Status
  url: https://status.fortify.com/
- title: ''
  type: Support
  url: https://www.opentext.com/support
- title: ''
  type: Terms of Service
  url: https://www.opentext.com/about/legal/website-terms-of-use
- title: ''
  type: Privacy Policy
  url: https://www.opentext.com/about/privacy
- title: ''
  type: GitHub Organization
  url: https://github.com/fortify
- title: ''
  type: Community
  url: https://community.opentext.com/cybersec/fortify
- title: ''
  type: Website
  url: https://www.opentext.com/products/fortify-on-demand
- title: ''
  type: Login
  url: https://ams.fortify.com/
- title: ''
  type: Sign Up
  url: https://www.opentext.com/products/fortify-on-demand/trial
- title: ''
  type: Change Log
  url: https://community.opentext.com/cybersec/fortify/w/tips
- title: ''
  type: SDKs
  url: https://github.com/fortify/fortify-client-api
- title: ''
  type: JSON-LD Context
  url: json-ld/fortify-context.jsonld
- title: ''
  type: JSON Schema
  url: json-schema/fortify-application-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/fortify-vulnerability-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/fortify-scan-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/fortify-release-schema.json
- title: ''
  type: JSON Schema
  url: json-schema/fortify-project-version-schema.json
created: '2024-01-15'
description: Fortify is a comprehensive application security platform from OpenText that provides static application security testing (SAST), dynamic application security testing (DAST), and software composition analysis (SCA) capabilities. It helps organizations identify and remediate vulnerabilities across the software development lifecycle.
features: []
image: https://www.microfocus.com/brand/fortify-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Fortify Context
  property_count: 11
  slug: fortify-context
layout: provider
modified: '2026-04-28'
name: Fortify
skills: []
slug: fortify
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Fortify\ndescription: >-\n  Fortify is a comprehensive application security platform from OpenText that\n  provides static application security testing (SAST), dynamic application\n  security testing (DAST), and software composition analysis (SCA) capabilities.\n  It helps organizations identify and remediate vulnerabilities across the\n  software development lifecycle.\nimage: https://www.microfocus.com/brand/fortify-logo.png\nurl: https://www.opentext.com/products/fortify-on-demand\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\napis:\n  - name: Fortify on Demand API\n    description: >-\n      REST API for Fortify on Demand (FoD), the cloud-based application security\n      testing service from OpenText. Provides programmatic access to manage\n      applications, initiate scans, and retrieve vulnerability results.\n    image: https://www.microfocus.com/brand/fortify-logo.png\n    baseURL: https://api.ams.fortify.com\n    humanURL: https://www.opentext.com/products/fortify-on-demand\n\
  \    tags:\n      - Application Security\n      - DAST\n      - SAST\n      - Security Testing\n      - Vulnerability Management\n    properties:\n      - type: Documentation\n        url: https://www.microfocus.com/documentation/fortify-on-demand/\n      - type: OpenAPI\n        url: https://api.ams.fortify.com/swagger/docs/v3\n      - type: OpenAPI\n        url: openapi/fortify-on-demand-openapi.yml\n      - type: API Reference\n        url: https://api.ams.fortify.com/swagger/ui/index\n      - type: Authentication\n        url: https://api.ams.fortify.com/oauth/token\n      - type: Getting Started\n        url: https://www.microfocus.com/documentation/fortify-on-demand/251/Fortify_on_Demand_Guide_25.1_EN.pdf\n    contact:\n      - type: Support\n        url: https://www.opentext.com/support\n      - type: Email\n        url: fortify-support@microfocus.com\n  - name: Fortify Software Security Center API\n    description: >-\n      REST API for the on-premise Fortify Software Security\
  \ Center (SSC), which\n      provides centralized management and reporting of security assessment data\n      across an organization's application portfolio.\n    image: https://www.microfocus.com/brand/fortify-logo.png\n    baseURL: https://your-ssc-server/ssc/api/v1\n    humanURL: https://www.microfocus.com/documentation/fortify-software-security-center/\n    tags:\n      - Application Security\n      - Compliance\n      - On-Premise\n      - Security Analytics\n      - Vulnerability Management\n    properties:\n      - type: Documentation\n        url: https://www.microfocus.com/documentation/fortify-software-security-center/2520/\n      - type: OpenAPI\n        url: openapi/fortify-software-security-center-openapi.yml\n      - type: API Reference\n        url: https://your-ssc-server/ssc/html/docs/api-reference/\n      - type: Authentication\n        url: https://your-ssc-server/ssc/api/v1/auth\n      - type: Getting Started\n        url: https://www.microfocus.com/documentation/fortify-software-security-center/\n\
  \      - type: SDKs\n        url: https://github.com/fortify/ssc-restapi-client\n  - name: Fortify ScanCentral DAST API\n    description: >-\n      REST API for Fortify ScanCentral DAST, which provides centralized dynamic\n      application security testing management. Enables orchestration of DAST scans\n      across distributed sensors and integration with CI/CD pipelines.\n    image: https://www.microfocus.com/brand/fortify-logo.png\n    baseURL: https://your-scancentral-dast-server/api/\n    humanURL: https://www.microfocus.com/documentation/fortify-ScanCentral-DAST/\n    tags:\n      - CI/CD\n      - DAST\n      - Dynamic Analysis\n      - Security Testing\n      - Web Application Security\n    properties:\n      - type: Documentation\n        url: https://www.microfocus.com/documentation/fortify-ScanCentral-DAST/2520/\n      - type: OpenAPI\n        url: openapi/fortify-scancentral-dast-openapi.yml\n      - type: Getting Started\n        url: https://www.microfocus.com/documentation/fortify-ScanCentral-DAST/2520/sc-dast-ugd-25.2.0.pdf\n\
  maintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - Application Security\n  - DAST\n  - DevSecOps\n  - SAST\n  - SCA\n  - Security Testing\n  - Vulnerability Scanning\ncommon:\n  - type: Portal\n    url: https://ams.fortify.com/\n  - type: Documentation\n    url: https://www.microfocus.com/documentation/fortify-on-demand/\n  - type: Getting Started\n    url: https://www.microfocus.com/documentation/fortify-on-demand/\n  - type: Authentication\n    url: https://api.ams.fortify.com/swagger/ui/index\n  - type: Blog\n    url: https://community.opentext.com/cyberres/b/cybersecurity-blog\n  - type: Status\n    url: https://status.fortify.com/\n  - type: Support\n    url: https://www.opentext.com/support\n  - type: Terms of Service\n    url: https://www.opentext.com/about/legal/website-terms-of-use\n  - type: Privacy Policy\n    url: https://www.opentext.com/about/privacy\n  - type: GitHub Organization\n    url: https://github.com/fortify\n\
  \  - type: Community\n    url: https://community.opentext.com/cybersec/fortify\n  - type: Website\n    url: https://www.opentext.com/products/fortify-on-demand\n  - type: Login\n    url: https://ams.fortify.com/\n  - type: Sign Up\n    url: https://www.opentext.com/products/fortify-on-demand/trial\n  - type: Change Log\n    url: https://community.opentext.com/cybersec/fortify/w/tips\n  - type: SDKs\n    url: https://github.com/fortify/fortify-client-api\n  - type: JSON-LD Context\n    url: json-ld/fortify-context.jsonld\n  - type: JSON Schema\n    url: json-schema/fortify-application-schema.json\n  - type: JSON Schema\n    url: json-schema/fortify-vulnerability-schema.json\n  - type: JSON Schema\n    url: json-schema/fortify-scan-schema.json\n  - type: JSON Schema\n    url: json-schema/fortify-release-schema.json\n  - type: JSON Schema\n    url: json-schema/fortify-project-version-schema.json\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fortify/refs/heads/main/apis.yml
tags:
- Application Security
- DAST
- DevSecOps
- SAST
- SCA
- Security Testing
- Vulnerability Scanning
url: https://www.opentext.com/products/fortify-on-demand
use_cases: []
---
