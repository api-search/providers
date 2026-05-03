---
api_count: 2
api_specs:
- filename: Recruiting_OpenAPI.yaml
  format: yaml
  label: Workday Recruiting REST API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v41.2/Recruiting_OpenAPI.yaml
apis:
- description: 'RESTful API for managing recruiting operations including job requisitions, candidates, applications, and hiring processes in Workday. Supports OAuth 2.0 authentication and returns data in JSON format '
  name: Workday Recruiting REST API
  slug: ''
- description: SOAP-based web service providing comprehensive access to Workday Recruiting business services data for integration with talent management and applicant tracking systems. Includes over 120 operations c
  name: Workday Recruiting SOAP Web Services API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://community.workday.com
- title: ''
  type: Getting Started
  url: https://community.workday.com/api-start
- title: ''
  type: Documentation
  url: https://community.workday.com/api
- title: ''
  type: Authentication
  url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication
- title: ''
  type: Console
  url: https://developer.workday.com/about
- title: ''
  type: Blog
  url: https://blog.workday.com/en-us/application-development.html
- title: ''
  type: Status
  url: https://community.workday.com/trust/status
- title: ''
  type: Support
  url: https://www.workday.com/en-us/services/support.html
- title: ''
  type: Sign Up
  url: https://resourcecenter.workday.com/
- title: ''
  type: Terms of Service
  url: https://www.workday.com/en-us/legal.html
- title: ''
  type: Privacy Policy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: Rate Limits
  url: https://community.workday.com/articles/16827
- title: ''
  type: Change Log
  url: https://community.workday.com/api-versions
- title: ''
  type: GitHub Organization
  url: https://github.com/Workday
- title: ''
  type: Marketplace
  url: https://marketplace.workday.com/en-US/home
- title: ''
  type: Partners
  url: https://www.workday.com/en-us/company/partners/overview.html
- title: ''
  type: Website
  url: https://www.workday.com
created: '2024-01-01'
description: APIs for Workday's cloud-based recruiting and talent acquisition solution, providing programmatic access to job requisitions, candidate management, applications, interviews, job postings, and hiring workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-16'
name: Workday Recruiting
skills: []
slug: workday-recruiting
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-recruiting\nname: Workday Recruiting\ndescription: >-\n  APIs for Workday's cloud-based recruiting and talent acquisition solution,\n  providing programmatic access to job requisitions, candidate management,\n  applications, interviews, job postings, and hiring workflows.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-recruiting/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\ntags:\n  - HCM\n  - Human Resources\n  - Recruiting\n  - SaaS\n  - Talent Acquisition\napis:\n  - name: Workday Recruiting REST API\n    description: >-\n      RESTful API for managing recruiting operations including job requisitions,\n      candidates, applications, and hiring processes in Workday. Supports OAuth\n      2.0 authentication and returns data in JSON format for integration with\n      talent management and applicant tracking\
  \ systems.\n    image: https://www.workday.com/content/dam/web/images/logos/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/api/recruiting/\n    tags:\n      - Applications\n      - Candidates\n      - Job Requisitions\n      - Recruiting\n      - Talent Acquisition\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v41.2/Recruiting_OpenAPI.yaml\n      - type: Authentication\n        url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication\n      - type: Rate Limits\n        url: https://community.workday.com/articles/16827\n  - name: Workday Recruiting SOAP Web Services API\n    description: >-\n      SOAP-based\
  \ web service providing comprehensive access to Workday Recruiting\n      business services data for integration with talent management and applicant\n      tracking systems. Includes over 120 operations covering candidate\n      management, job requisitions, evergreen requisitions, job postings,\n      interviews, background checks, recruiting agencies, and self-schedule\n      calendars.\n    image: https://www.workday.com/content/dam/web/images/logos/workday-logo.svg\n    humanURL: https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.html\n    baseURL: https://wd2-impl-services1.workday.com/ccx/service/\n    tags:\n      - Candidates\n      - Job Requisitions\n      - Recruiting\n      - SOAP API\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Recruiting/v45.2/Recruiting.html\n      - type: Reference\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html\n\
  \      - type: Change Log\n        url: https://community.workday.com/api-versions\ncommon:\n  - type: Portal\n    url: https://community.workday.com\n  - type: Getting Started\n    url: https://community.workday.com/api-start\n  - type: Documentation\n    url: https://community.workday.com/api\n  - type: Authentication\n    url: https://community.workday.com/sites/default/files/file-hosting/restapi/index.html#authentication\n  - type: Console\n    url: https://developer.workday.com/about\n  - type: Blog\n    url: https://blog.workday.com/en-us/application-development.html\n  - type: Status\n    url: https://community.workday.com/trust/status\n  - type: Support\n    url: https://www.workday.com/en-us/services/support.html\n  - type: Sign Up\n    url: https://resourcecenter.workday.com/\n  - type: Terms of Service\n    url: https://www.workday.com/en-us/legal.html\n  - type: Privacy Policy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: Rate Limits\n    url: https://community.workday.com/articles/16827\n\
  \  - type: Change Log\n    url: https://community.workday.com/api-versions\n  - type: GitHub Organization\n    url: https://github.com/Workday\n  - type: Marketplace\n    url: https://marketplace.workday.com/en-US/home\n  - type: Partners\n    url: https://www.workday.com/en-us/company/partners/overview.html\n  - type: Website\n    url: https://www.workday.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-recruiting/refs/heads/main/apis.yml
tags:
- HCM
- Human Resources
- Recruiting
- SaaS
- Talent Acquisition
url: https://raw.githubusercontent.com/api-evangelist/workday-recruiting/refs/heads/main/apis.yml
use_cases: []
---
