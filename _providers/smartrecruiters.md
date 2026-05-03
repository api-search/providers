---
api_count: 8
api_specs:
- filename: smartrecruiters-posting-openapi.yml
  format: yaml
  label: SmartRecruiters Posting API
  slug: posting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/openapi/smartrecruiters-posting-openapi.yml
- filename: smartrecruiters-jobs-openapi.yml
  format: yaml
  label: SmartRecruiters Job API
  slug: job-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/openapi/smartrecruiters-jobs-openapi.yml
- filename: smartrecruiters-candidates-openapi.yml
  format: yaml
  label: SmartRecruiters Candidate API
  slug: candidate-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/openapi/smartrecruiters-candidates-openapi.yml
apis:
- description: The Posting API enables customers to build fully customizable career sites by providing access to published job postings. It supports searching and filtering postings by keyword, location, department,
  name: SmartRecruiters Posting API
  slug: posting-api
- description: The Job API enables customers to extract and import jobs data, supporting full job lifecycle management including creation, updates, and status management.
  name: SmartRecruiters Job API
  slug: job-api
- description: The Candidate API enables customers to import, export, read, and update candidate data. Supports full candidate profile management, application tracking, and status updates.
  name: SmartRecruiters Candidate API
  slug: candidate-api
- description: The Application API enables integration of the full candidate application including screening questions, and allows new applications to be submitted through partner systems and career sites.
  name: SmartRecruiters Application API
  slug: application-api
- description: The Assessment API allows customers to order assessment services available through the SmartRecruiters Marketplace and allows partners to interface with the marketplace to provide and manage assessmen
  name: SmartRecruiters Assessment API
  slug: assessment-api
- description: The Interview API provides self-scheduling capabilities and interview template management for streamlining the interview process between recruiters and candidates.
  name: SmartRecruiters Interview API
  slug: interview-api
- description: The Reporting API provides access to custom reports in CSV format, enabling analytics and data export capabilities for HR metrics and recruiting performance.
  name: SmartRecruiters Reporting API
  slug: reporting-api
- description: The Job Board API enables job board partners to integrate SmartRecruiters job postings directly into their platforms with real-time synchronization.
  name: SmartRecruiters Job Board API
  slug: job-board-api
capabilities:
- description: Unified workflow for end-to-end talent acquisition combining job management, candidate tracking, and application processing. Used by recruiters and hiring managers to manage the full recruiting lifecy
  name: SmartRecruiters Talent Acquisition
  slug: talent-acquisition
common:
- title: ''
  type: Website
  url: https://www.smartrecruiters.com/
- title: ''
  type: Developer Portal
  url: https://developers.smartrecruiters.com/
- title: ''
  type: Documentation
  url: https://developers.smartrecruiters.com/docs/the-smartrecruiters-platform
- title: ''
  type: Authentication
  url: https://developers.smartrecruiters.com/docs/authentication
- title: ''
  type: GitHub Organization
  url: https://github.com/smartrecruiters
- title: ''
  type: Blog
  url: https://www.smartrecruiters.com/blog/
- title: ''
  type: Marketplace
  url: https://www.smartrecruiters.com/marketplace/
created: '2025-01-07'
description: SmartRecruiters is a talent acquisition platform that provides a comprehensive suite of APIs for recruiting, hiring, and workforce management. The platform enables organizations to manage job postings, candidate applications, assessments, interviews, and offers through a unified REST API ecosystem.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 37
  name: Smartrecruiters Context
  property_count: 0
  slug: smartrecruiters-context
layout: provider
modified: '2026-05-02'
name: SmartRecruiters
rules:
- name: SmartRecruiters API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: smartrecruiters-rules
skills: []
slug: smartrecruiters
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: smartrecruiters\nname: SmartRecruiters\ndescription: >-\n  SmartRecruiters is a talent acquisition platform that provides a comprehensive\n  suite of APIs for recruiting, hiring, and workforce management. The platform\n  enables organizations to manage job postings, candidate applications, assessments,\n  interviews, and offers through a unified REST API ecosystem.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Human Resources\n  - Recruiting\n  - Talent Acquisition\n  - Applicant Tracking\n  - HR Technology\ncreated: '2025-01-07'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: smartrecruiters:posting-api\n    name: SmartRecruiters Posting API\n    description: >-\n      The Posting API enables customers to build fully customizable career sites\n  \
  \    by providing access to published job postings. It supports searching and\n      filtering postings by keyword, location, department, and custom fields.\n    humanURL: https://developers.smartrecruiters.com/docs/posting-api\n    baseURL: https://api.smartrecruiters.com\n    tags:\n      - Jobs\n      - Postings\n      - Career Sites\n    properties:\n      - type: Documentation\n        url: https://developers.smartrecruiters.com/docs/posting-api\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/openapi/smartrecruiters-posting-openapi.yml\n\n  - aid: smartrecruiters:job-api\n    name: SmartRecruiters Job API\n    description: >-\n      The Job API enables customers to extract and import jobs data, supporting\n      full job lifecycle management including creation, updates, and status management.\n    humanURL: https://developers.smartrecruiters.com/docs/api-reference\n    baseURL: https://api.smartrecruiters.com\n\
  \    tags:\n      - Jobs\n      - Hiring\n    properties:\n      - type: Documentation\n        url: https://developers.smartrecruiters.com/docs/api-reference\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/openapi/smartrecruiters-jobs-openapi.yml\n\n  - aid: smartrecruiters:candidate-api\n    name: SmartRecruiters Candidate API\n    description: >-\n      The Candidate API enables customers to import, export, read, and update\n      candidate data. Supports full candidate profile management, application\n      tracking, and status updates.\n    humanURL: https://developers.smartrecruiters.com/docs/api-reference\n    baseURL: https://api.smartrecruiters.com\n    tags:\n      - Candidates\n      - Applicants\n      - Talent\n    properties:\n      - type: Documentation\n        url: https://developers.smartrecruiters.com/docs/api-reference\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/openapi/smartrecruiters-candidates-openapi.yml\n\
  \n  - aid: smartrecruiters:application-api\n    name: SmartRecruiters Application API\n    description: >-\n      The Application API enables integration of the full candidate application\n      including screening questions, and allows new applications to be submitted\n      through partner systems and career sites.\n    humanURL: https://developers.smartrecruiters.com/docs/application-api-1\n    baseURL: https://api.smartrecruiters.com\n    tags:\n      - Applications\n      - Candidates\n      - Screening\n    properties:\n      - type: Documentation\n        url: https://developers.smartrecruiters.com/docs/application-api-1\n\n  - aid: smartrecruiters:assessment-api\n    name: SmartRecruiters Assessment API\n    description: >-\n      The Assessment API allows customers to order assessment services available\n      through the SmartRecruiters Marketplace and allows partners to interface\n      with the marketplace to provide and manage assessment services.\n    humanURL: https://developers.smartrecruiters.com/docs/partners-assessment-api\n\
  \    baseURL: https://api.smartrecruiters.com\n    tags:\n      - Assessments\n      - Marketplace\n      - Partners\n    properties:\n      - type: Documentation\n        url: https://developers.smartrecruiters.com/docs/partners-assessment-api\n\n  - aid: smartrecruiters:interview-api\n    name: SmartRecruiters Interview API\n    description: >-\n      The Interview API provides self-scheduling capabilities and interview template\n      management for streamlining the interview process between recruiters and candidates.\n    humanURL: https://developers.smartrecruiters.com/docs/api-reference\n    baseURL: https://api.smartrecruiters.com\n    tags:\n      - Interviews\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://developers.smartrecruiters.com/docs/api-reference\n\n  - aid: smartrecruiters:reporting-api\n    name: SmartRecruiters Reporting API\n    description: >-\n      The Reporting API provides access to custom reports in CSV format, enabling\n\
  \      analytics and data export capabilities for HR metrics and recruiting performance.\n    humanURL: https://developers.smartrecruiters.com/docs/api-reference\n    baseURL: https://api.smartrecruiters.com\n    tags:\n      - Reporting\n      - Analytics\n      - Data Export\n    properties:\n      - type: Documentation\n        url: https://developers.smartrecruiters.com/docs/api-reference\n\n  - aid: smartrecruiters:job-board-api\n    name: SmartRecruiters Job Board API\n    description: >-\n      The Job Board API enables job board partners to integrate SmartRecruiters\n      job postings directly into their platforms with real-time synchronization.\n    humanURL: https://developers.smartrecruiters.com/docs/partners-job-board-api\n    baseURL: https://api.smartrecruiters.com\n    tags:\n      - Job Boards\n      - Partners\n      - Jobs\n    properties:\n      - type: Documentation\n        url: https://developers.smartrecruiters.com/docs/partners-job-board-api\n\ncommon:\n  - type:\
  \ Website\n    url: https://www.smartrecruiters.com/\n  - type: Developer Portal\n    url: https://developers.smartrecruiters.com/\n  - type: Documentation\n    url: https://developers.smartrecruiters.com/docs/the-smartrecruiters-platform\n  - type: Authentication\n    url: https://developers.smartrecruiters.com/docs/authentication\n  - type: GitHub Organization\n    url: https://github.com/smartrecruiters\n  - type: Blog\n    url: https://www.smartrecruiters.com/blog/\n  - type: Marketplace\n    url: https://www.smartrecruiters.com/marketplace/\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/apis.yml
tags:
- Human Resources
- Recruiting
- Talent Acquisition
- Applicant Tracking
- HR Technology
url: https://raw.githubusercontent.com/api-evangelist/smartrecruiters/refs/heads/main/apis.yml
use_cases: []
---
