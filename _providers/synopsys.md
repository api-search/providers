---
api_count: 4
api_specs:
- filename: synopsys-polaris-openapi.yml
  format: yaml
  label: Synopsys Polaris API
  slug: polaris
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/synopsys/refs/heads/main/openapi/synopsys-polaris-openapi.yml
- filename: synopsys-cloud-openlink-openapi.yml
  format: yaml
  label: Synopsys Cloud OpenLink API
  slug: cloud-openlink
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/synopsys/refs/heads/main/openapi/synopsys-cloud-openlink-openapi.yml
apis:
- description: The Polaris Software Integrity Platform API provides programmatic access to application security testing orchestration, project management, scan configuration, and issue tracking. Polaris integrates w
  name: Synopsys Polaris API
  slug: polaris
- description: 'The Coverity Platform REST API provides programmatic access to Coverity static analysis results, project and stream management, defect management, and security findings. Coverity performs deep source '
  name: Synopsys Coverity REST API
  slug: coverity
- description: The Synopsys Cloud OpenLink API enables semiconductor vendors to interoperate with Synopsys Cloud for managing product entitlements and license distribution. The API supports API key and OAuth2 authen
  name: Synopsys Cloud OpenLink API
  slug: cloud-openlink
- description: The Seeker REST API provides programmatic access to Seeker IAST (Interactive Application Security Testing) functionality including project management, vulnerability export, compliance reporting, and a
  name: Synopsys Seeker REST API
  slug: seeker
capabilities:
- description: Unified application security testing capability combining Synopsys Polaris platform APIs for project management, scan orchestration, security issue tracking, and report generation. Enables DevSecOps t
  name: Synopsys Application Security Testing
  slug: application-security-testing
- description: Cloud EDA license management capability using the Synopsys Cloud OpenLink API. Enables semiconductor vendors and customers to query product entitlements and generate license files for EDA tools, suppo
  name: Synopsys EDA License Management
  slug: eda-license-management
common:
- title: ''
  type: Website
  url: https://www.synopsys.com
- title: ''
  type: DeveloperPortal
  url: https://polaris.synopsys.com/developer/
- title: ''
  type: Community
  url: https://community.synopsys.com/
- title: ''
  type: GitHubOrg
  url: https://github.com/synopsys-sig
- title: ''
  type: JSONLDContext
  url: json-ld/synopsys-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/synopsys-vocabulary.yml
created: '2026-05-03'
description: Synopsys is a global leader in semiconductor design EDA tools and software security testing. The company's Software Integrity Group (now rebranded as Black Duck) provides application security testing products including Polaris, Coverity (SAST), Black Duck (SCA), and Seeker (IAST). Synopsys also offers cloud-based EDA and semiconductor design services through the Synopsys Cloud platform with the OpenLink API for license entitlement management.
features: []
image: ''
integrations: []
jsonld:
- class_count: 25
  name: Synopsys Context
  property_count: 3
  slug: synopsys-context
layout: provider
modified: '2026-05-03'
name: Synopsys
rules:
- name: Synopsys API Rules
  rule_count: 12
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 7
  slug: synopsys-rules
skills: []
slug: synopsys
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: synopsys\nname: Synopsys\ndescription: >-\n  Synopsys is a global leader in semiconductor design EDA tools and software\n  security testing. The company's Software Integrity Group (now rebranded as\n  Black Duck) provides application security testing products including Polaris,\n  Coverity (SAST), Black Duck (SCA), and Seeker (IAST). Synopsys also offers\n  cloud-based EDA and semiconductor design services through the Synopsys Cloud\n  platform with the OpenLink API for license entitlement management.\nurl: https://raw.githubusercontent.com/api-evangelist/synopsys/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\ntags:\n  - Software Security\n  - Application Security Testing\n  - Static Analysis\n  - Software Composition Analysis\n  - EDA Tools\n  - Semiconductor Design\napis:\n  - aid: synopsys:polaris\n    name: Synopsys Polaris API\n    description: >-\n      The Polaris Software Integrity Platform API provides programmatic access\n      to application\
  \ security testing orchestration, project management, scan\n      configuration, and issue tracking. Polaris integrates with GitHub,\n      GitLab, Bitbucket, and Azure DevOps for event-driven security scanning\n      automation across SAST, SCA, and IAST testing.\n    humanURL: https://polaris.synopsys.com/developer/default/documentation\n    baseURL: https://polaris.synopsys.com/api\n    tags:\n      - Application Security\n      - Static Analysis\n      - Software Composition Analysis\n      - DevSecOps\n      - CI/CD Integration\n    properties:\n      - type: Documentation\n        url: https://polaris.synopsys.com/developer/default/documentation\n      - type: APIQuickstart\n        url: https://polaris.synopsys.com/developer/default/documentation/t_api-quickstart\n      - type: OpenAPI\n        url: openapi/synopsys-polaris-openapi.yml\n      - type: SpectralRules\n        url: rules/synopsys-rules.yml\n\n  - aid: synopsys:coverity\n    name: Synopsys Coverity REST API\n    description:\
  \ >-\n      The Coverity Platform REST API provides programmatic access to Coverity\n      static analysis results, project and stream management, defect management,\n      and security findings. Coverity performs deep source code examination across\n      20+ programming languages and 70+ frameworks to detect critical quality\n      and security defects.\n    humanURL: https://community.synopsys.com/s/topic/0TO34000000LmwWGAS/rest-api\n    baseURL: https://coverity.synopsys.com/api\n    tags:\n      - Static Analysis\n      - SAST\n      - Code Quality\n      - Defect Management\n      - Security Testing\n    properties:\n      - type: Documentation\n        url: https://community.synopsys.com/s/topic/0TO34000000LmwWGAS/rest-api\n      - type: OpenAPISpec\n        url: https://documentation.blackduck.com/bundle/coverity-docs/page/cim-api-docs/openapi/cim-openapi.html\n\n  - aid: synopsys:cloud-openlink\n    name: Synopsys Cloud OpenLink API\n    description: >-\n      The Synopsys Cloud\
  \ OpenLink API enables semiconductor vendors to interoperate\n      with Synopsys Cloud for managing product entitlements and license distribution.\n      The API supports API key and OAuth2 authentication with JSON payloads over\n      HTTPS. It exposes vendor entitlement endpoints and license request endpoints\n      for both synchronous and asynchronous license delivery.\n    humanURL: https://www.synopsys.com/cloud/openlink/api.html\n    baseURL: https://api.synopsys.com/openlink\n    tags:\n      - EDA Tools\n      - License Management\n      - Semiconductor Design\n      - Cloud Platform\n    properties:\n      - type: Documentation\n        url: https://www.synopsys.com/cloud/openlink/api.html\n      - type: OpenAPI\n        url: openapi/synopsys-cloud-openlink-openapi.yml\n\n  - aid: synopsys:seeker\n    name: Synopsys Seeker REST API\n    description: >-\n      The Seeker REST API provides programmatic access to Seeker IAST (Interactive\n      Application Security Testing) functionality\
  \ including project management,\n      vulnerability export, compliance reporting, and administration automation.\n    humanURL: https://demo.seeker.synopsys.com/internal/help/en/topics/r_using_apis.html\n    baseURL: https://seeker.synopsys.com/api\n    tags:\n      - IAST\n      - Interactive Testing\n      - Vulnerability Management\n      - Application Security\n    properties:\n      - type: Documentation\n        url: https://demo.seeker.synopsys.com/internal/help/en/topics/r_using_apis.html\n\ncommon:\n  - type: Website\n    url: https://www.synopsys.com\n  - type: DeveloperPortal\n    url: https://polaris.synopsys.com/developer/\n  - type: Community\n    url: https://community.synopsys.com/\n  - type: GitHubOrg\n    url: https://github.com/synopsys-sig\n  - type: JSONLDContext\n    url: json-ld/synopsys-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/synopsys-vocabulary.yml\nfeatures:\n  - Static Application Security Testing (SAST)\n  - Software Composition Analysis (SCA)\n\
  \  - Interactive Application Security Testing (IAST)\n  - Dynamic Application Security Testing (DAST)\n  - License Compliance\n  - DevSecOps Pipeline Integration\n  - CI/CD Plugin Support\n  - Multi-Language Support (20+ Languages)\n  - EDA Cloud Platform\n  - License Entitlement Management\nuseCases:\n  - Application Security Testing Automation\n  - DevSecOps Integration\n  - Open Source Risk Management\n  - Code Quality and Security Analysis\n  - Compliance Reporting\n  - Semiconductor Design Tool Licensing\nintegrations:\n  - type: GitHub\n    description: GitHub Actions and App integration\n  - type: GitLab\n    description: GitLab CI/CD integration\n  - type: AzureDevOps\n    description: Azure DevOps pipeline integration\n  - type: Jenkins\n    description: Jenkins plugin for CI/CD\nsolutions:\n  - Secure Software Development Lifecycle (SSDLC)\n  - Cloud-Native Application Security\n  - Enterprise Code Security Platform\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/synopsys/refs/heads/main/apis.yml
tags:
- Software Security
- Application Security Testing
- Static Analysis
- Software Composition Analysis
- EDA Tools
- Semiconductor Design
url: https://raw.githubusercontent.com/api-evangelist/synopsys/refs/heads/main/apis.yml
use_cases: []
---
