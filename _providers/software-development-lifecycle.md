---
api_count: 7
api_specs:
- filename: api.github.com.json
  format: json
  label: Code and Review APIs
  slug: code-and-review
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json
apis:
- description: APIs for agile planning, backlog management, sprint tracking, roadmapping, and team capacity planning tools used in the planning phase of the software development lifecycle.
  name: Planning and Tracking APIs
  slug: planning-and-tracking
- description: APIs for source control, code repositories, branching strategies, pull requests, and code review platforms that support collaborative development in the implementation phase.
  name: Code and Review APIs
  slug: code-and-review
- description: APIs for build automation, test frameworks, code coverage tools, and quality gates that verify software correctness and maintainability during the testing phase of the lifecycle.
  name: Build and Test APIs
  slug: build-and-test
- description: APIs for static application security testing (SAST), dynamic application security testing (DAST), software composition analysis (SCA), and container security scanning integrated into the development l
  name: Security Scanning APIs
  slug: security-scanning
- description: APIs for CI/CD pipelines, infrastructure provisioning, environment management, feature flags, and progressive delivery tools that support the deployment and release phase of the software development l
  name: Deployment and Release APIs
  slug: deployment-and-release
- description: APIs for application performance monitoring, error tracking, log management, and distributed tracing that support the operations and maintenance phase of the software development lifecycle.
  name: Monitoring and Observability APIs
  slug: monitoring-and-observability
- description: APIs for integrated developer experience (IDP) platforms that unify planning, coding, building, testing, and deployment into a single platform with internal developer portals, service catalogs, and se
  name: Developer Platform APIs
  slug: developer-platforms
common:
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Software_development_process
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Agile_software_development
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/DevOps
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/DevSecOps
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Platform_engineering
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Continuous_integration
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Continuous_delivery
- title: ''
  type: Documentation
  url: https://internaldeveloperplatform.org/
created: '2025-01-01'
description: The Software Development Lifecycle (SDLC) encompasses all processes, tools, and methodologies involved in planning, developing, testing, and delivering software from inception to retirement. Modern SDLC platforms integrate project planning, source control, code review, automated testing, security scanning, CI/CD pipelines, and release management into unified developer experience platforms. This profile covers the landscape of APIs, tools, and platforms that support each phase of the software development lifecycle.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 30
  name: Software Development Lifecycle Context
  property_count: 11
  slug: software-development-lifecycle-context
layout: provider
modified: '2026-05-02'
name: Software Development Lifecycle
skills: []
slug: software-development-lifecycle
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: software-development-lifecycle\nname: Software Development Lifecycle\ndescription: >-\n  The Software Development Lifecycle (SDLC) encompasses all processes, tools,\n  and methodologies involved in planning, developing, testing, and delivering\n  software from inception to retirement. Modern SDLC platforms integrate project\n  planning, source control, code review, automated testing, security scanning,\n  CI/CD pipelines, and release management into unified developer experience\n  platforms. This profile covers the landscape of APIs, tools, and platforms\n  that support each phase of the software development lifecycle.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Development Process\n  - Project Management\n  - Quality Assurance\n  - Software Engineering\n  - DevOps\n  - Platform Engineering\nurl: https://raw.githubusercontent.com/api-evangelist/software-development-lifecycle/refs/heads/main/apis.yml\ncreated:\
  \ '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: software-development-lifecycle:planning-and-tracking\n    name: Planning and Tracking APIs\n    description: >-\n      APIs for agile planning, backlog management, sprint tracking, roadmapping,\n      and team capacity planning tools used in the planning phase of the software\n      development lifecycle.\n    humanURL: https://en.wikipedia.org/wiki/Software_project_management\n    baseURL: https://en.wikipedia.org/wiki/Software_project_management\n    tags:\n      - Agile Planning\n      - Backlog Management\n      - Sprint Tracking\n      - Roadmapping\n    properties:\n      - type: Documentation\n        url: https://en.wikipedia.org/wiki/Software_project_management\n  - aid: software-development-lifecycle:code-and-review\n    name: Code and Review APIs\n    description: >-\n      APIs for source control, code repositories, branching strategies, pull\n      requests, and code review platforms that\
  \ support collaborative development\n      in the implementation phase.\n    humanURL: https://en.wikipedia.org/wiki/Version_control\n    baseURL: https://api.github.com\n    tags:\n      - Source Control\n      - Code Review\n      - Version Control\n      - Collaboration\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/rest\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json\n  - aid: software-development-lifecycle:build-and-test\n    name: Build and Test APIs\n    description: >-\n      APIs for build automation, test frameworks, code coverage tools, and\n      quality gates that verify software correctness and maintainability during\n      the testing phase of the lifecycle.\n    humanURL: https://en.wikipedia.org/wiki/Build_automation\n    baseURL: https://en.wikipedia.org/wiki/Build_automation\n    tags:\n      - Build Automation\n      - Testing\n\
  \      - Code Coverage\n      - Quality Gates\n    properties:\n      - type: Documentation\n        url: https://en.wikipedia.org/wiki/Build_automation\n  - aid: software-development-lifecycle:security-scanning\n    name: Security Scanning APIs\n    description: >-\n      APIs for static application security testing (SAST), dynamic application\n      security testing (DAST), software composition analysis (SCA), and\n      container security scanning integrated into the development lifecycle.\n    humanURL: https://en.wikipedia.org/wiki/Static_application_security_testing\n    baseURL: https://en.wikipedia.org/wiki/Static_application_security_testing\n    tags:\n      - SAST\n      - DAST\n      - Security Scanning\n      - DevSecOps\n      - SCA\n    properties:\n      - type: Documentation\n        url: https://en.wikipedia.org/wiki/Static_application_security_testing\n  - aid: software-development-lifecycle:deployment-and-release\n    name: Deployment and Release APIs\n    description:\
  \ >-\n      APIs for CI/CD pipelines, infrastructure provisioning, environment management,\n      feature flags, and progressive delivery tools that support the deployment\n      and release phase of the software development lifecycle.\n    humanURL: https://en.wikipedia.org/wiki/CI/CD\n    baseURL: https://en.wikipedia.org/wiki/CI/CD\n    tags:\n      - CI/CD\n      - Deployment\n      - Infrastructure as Code\n      - Feature Flags\n      - Progressive Delivery\n    properties:\n      - type: Documentation\n        url: https://en.wikipedia.org/wiki/CI/CD\n  - aid: software-development-lifecycle:monitoring-and-observability\n    name: Monitoring and Observability APIs\n    description: >-\n      APIs for application performance monitoring, error tracking, log management,\n      and distributed tracing that support the operations and maintenance phase\n      of the software development lifecycle.\n    humanURL: https://en.wikipedia.org/wiki/Observability_(software)\n    baseURL: https://en.wikipedia.org/wiki/Observability_(software)\n\
  \    tags:\n      - Monitoring\n      - Observability\n      - APM\n      - Log Management\n      - Tracing\n    properties:\n      - type: Documentation\n        url: https://en.wikipedia.org/wiki/Observability_(software)\n  - aid: software-development-lifecycle:developer-platforms\n    name: Developer Platform APIs\n    description: >-\n      APIs for integrated developer experience (IDP) platforms that unify planning,\n      coding, building, testing, and deployment into a single platform with\n      internal developer portals, service catalogs, and self-service infrastructure.\n    humanURL: https://internaldeveloperplatform.org/\n    baseURL: https://internaldeveloperplatform.org/\n    tags:\n      - Developer Platform\n      - Internal Developer Portal\n      - Service Catalog\n      - Platform Engineering\n    properties:\n      - type: Documentation\n        url: https://internaldeveloperplatform.org/\ncommon:\n  - url: https://en.wikipedia.org/wiki/Software_development_process\n\
  \    name: Software Development Process\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/Agile_software_development\n    name: Agile Software Development\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/DevOps\n    name: DevOps\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/DevSecOps\n    name: DevSecOps\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/Platform_engineering\n    name: Platform Engineering\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/Continuous_integration\n    name: Continuous Integration\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/Continuous_delivery\n    name: Continuous Delivery\n    type: Documentation\n  - url: https://internaldeveloperplatform.org/\n    name: Internal Developer Platform Guide\n    type: Documentation\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/software-development-lifecycle/refs/heads/main/apis.yml
tags:
- Development Process
- Project Management
- Quality Assurance
- Software Engineering
- DevOps
- Platform Engineering
url: https://raw.githubusercontent.com/api-evangelist/software-development-lifecycle/refs/heads/main/apis.yml
use_cases: []
---
