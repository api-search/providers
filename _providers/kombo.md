---
api_count: 5
api_specs:
- filename: openapi.json
  format: json
  label: Kombo Unified API
  slug: unified-api
  spec_type: OpenAPI
  url: https://api.kombo.dev/openapi.json
- filename: openapi.json
  format: json
  label: Kombo Unified HRIS API
  slug: hris-api
  spec_type: OpenAPI
  url: https://api.kombo.dev/openapi.json
- filename: openapi.json
  format: json
  label: Kombo Unified ATS API
  slug: ats-api
  spec_type: OpenAPI
  url: https://api.kombo.dev/openapi.json
- filename: openapi.json
  format: json
  label: Kombo Unified ATS-Assessment API
  slug: ats-assessment-api
  spec_type: OpenAPI
  url: https://api.kombo.dev/openapi.json
- filename: openapi.json
  format: json
  label: Kombo Unified LMS API
  slug: lms-api
  spec_type: OpenAPI
  url: https://api.kombo.dev/openapi.json
apis:
- description: Kombo provides a unified API that connects B2B SaaS products with HR, payroll, applicant tracking, and learning management systems through a single integration point, handling data normalization and a
  name: Kombo Unified API
  slug: unified-api
- description: Unified HRIS API for accessing employee data, absence management, time-off tracking, document management, and provisioning workflows across HR systems.
  name: Kombo Unified HRIS API
  slug: hris-api
- description: Unified ATS API for managing job postings, candidates, applications, and recruitment pipelines across applicant tracking systems.
  name: Kombo Unified ATS API
  slug: ats-api
- description: Unified ATS-Assessment API for assessment writing, notifications, and result submission across ATS platforms.
  name: Kombo Unified ATS-Assessment API
  slug: ats-assessment-api
- description: Unified LMS API for user management, courses, and learning progress tracking across learning management systems.
  name: Kombo Unified LMS API
  slug: lms-api
common:
- title: ''
  type: Website
  url: https://www.kombo.dev
- title: ''
  type: Documentation
  url: https://docs.kombo.dev
- title: ''
  type: OpenAPI
  url: https://api.kombo.dev/openapi.json
- title: ''
  type: SDKs
  url: https://kombo.dev/libraries-and-sdks
- title: ''
  type: Security
  url: https://security.kombo.dev
- title: ''
  type: Support
  url: mailto:support@kombo.dev
- title: ''
  type: GitHub Organization
  url: https://github.com/kombo-api
created: '2026-03-16'
description: Kombo is a unified API for HR and ATS integrations, enabling B2B SaaS companies to connect with HRIS, payroll, recruiting, and learning systems through a single integration.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Kombo
skills: []
slug: kombo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kombo\nname: Kombo\ndescription: >-\n  Kombo is a unified API for HR and ATS integrations, enabling B2B SaaS\n  companies to connect with HRIS, payroll, recruiting, and learning systems\n  through a single integration.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - ATS\n  - Embedded iPaaS\n  - HRIS\n  - LMS\n  - Payroll\n  - Unified API\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/kombo/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: kombo:unified-api\n    name: Kombo Unified API\n    description: >-\n      Kombo provides a unified API that connects B2B SaaS products with HR,\n      payroll, applicant tracking, and learning management systems through a\n      single integration point, handling data normalization and authentication\n      across 300+ HR and ATS tools.\n    humanURL: https://www.kombo.dev\n    baseURL: https://api.kombo.dev\n\
  \    tags:\n      - ATS\n      - HRIS\n      - Payroll\n      - Unified API\n    properties:\n      - type: Documentation\n        url: https://docs.kombo.dev\n      - type: Getting Started\n        url: https://docs.kombo.dev/getting-started\n      - type: OpenAPI\n        url: https://api.kombo.dev/openapi.json\n      - type: SDKs\n        url: https://kombo.dev/libraries-and-sdks\n      - type: Integrations\n        url: https://www.kombo.dev/categories/all\n      - type: Security\n        url: https://security.kombo.dev\n  - aid: kombo:hris-api\n    name: Kombo Unified HRIS API\n    description: >-\n      Unified HRIS API for accessing employee data, absence management,\n      time-off tracking, document management, and provisioning workflows\n      across HR systems.\n    humanURL: https://docs.kombo.dev\n    tags:\n      - HRIS\n      - Employees\n      - Time Off\n    properties:\n      - type: Documentation\n        url: https://docs.kombo.dev\n      - type: OpenAPI\n        url:\
  \ https://api.kombo.dev/openapi.json\n  - aid: kombo:ats-api\n    name: Kombo Unified ATS API\n    description: >-\n      Unified ATS API for managing job postings, candidates, applications,\n      and recruitment pipelines across applicant tracking systems.\n    humanURL: https://docs.kombo.dev\n    tags:\n      - ATS\n      - Recruiting\n    properties:\n      - type: Documentation\n        url: https://docs.kombo.dev\n      - type: OpenAPI\n        url: https://api.kombo.dev/openapi.json\n  - aid: kombo:ats-assessment-api\n    name: Kombo Unified ATS-Assessment API\n    description: >-\n      Unified ATS-Assessment API for assessment writing, notifications, and\n      result submission across ATS platforms.\n    humanURL: https://docs.kombo.dev\n    tags:\n      - ATS\n      - Assessments\n    properties:\n      - type: Documentation\n        url: https://docs.kombo.dev\n      - type: OpenAPI\n        url: https://api.kombo.dev/openapi.json\n  - aid: kombo:lms-api\n    name: Kombo Unified\
  \ LMS API\n    description: >-\n      Unified LMS API for user management, courses, and learning progress\n      tracking across learning management systems.\n    humanURL: https://docs.kombo.dev\n    tags:\n      - LMS\n      - Learning\n    properties:\n      - type: Documentation\n        url: https://docs.kombo.dev\n      - type: OpenAPI\n        url: https://api.kombo.dev/openapi.json\ncommon:\n  - type: Website\n    url: https://www.kombo.dev\n  - type: Documentation\n    url: https://docs.kombo.dev\n  - type: OpenAPI\n    url: https://api.kombo.dev/openapi.json\n  - type: SDKs\n    url: https://kombo.dev/libraries-and-sdks\n  - type: Security\n    url: https://security.kombo.dev\n  - type: Support\n    url: mailto:support@kombo.dev\n  - type: GitHub Organization\n    url: https://github.com/kombo-api\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kombo/refs/heads/main/apis.yml
tags:
- ATS
- Embedded iPaaS
- HRIS
- LMS
- Payroll
- Unified API
url: https://raw.githubusercontent.com/api-evangelist/kombo/refs/heads/main/apis.yml
use_cases: []
---
