---
api_count: 8
api_specs:
- filename: greenhouse-harvest-openapi.yml
  format: yaml
  label: Greenhouse Harvest API
  slug: harvest
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/openapi/greenhouse-harvest-openapi.yml
- filename: greenhouse-job-board-openapi.yml
  format: yaml
  label: Greenhouse Job Board API
  slug: job-board
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/openapi/greenhouse-job-board-openapi.yml
- filename: greenhouse-ingestion-openapi.yml
  format: yaml
  label: Greenhouse Candidate Ingestion API
  slug: ingestion
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/openapi/greenhouse-ingestion-openapi.yml
- filename: greenhouse-onboarding-openapi.yml
  format: yaml
  label: Greenhouse Onboarding API
  slug: onboarding
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/openapi/greenhouse-onboarding-openapi.yml
apis:
- description: The Harvest API provides programmatic access to Greenhouse Recruiting data, including candidates, applications, jobs, departments, offices, and users.
  name: Greenhouse Harvest API
  slug: harvest
- description: The Job Board API enables building careers pages with custom look and feel, retrieving jobs, offices, departments, sections, education reference data, and submitting applications.
  name: Greenhouse Job Board API
  slug: job-board
- description: The Ingestion API enables sourcing partners to submit prospects and candidates to Greenhouse and to retrieve job and prospect pool information.
  name: Greenhouse Candidate Ingestion API
  slug: ingestion
- description: A GraphQL API for Greenhouse Onboarding. Provides queries and mutations for employees, departments, locations, custom fields, teams, and pending hires.
  name: Greenhouse Onboarding API
  slug: onboarding
- description: The Assessment Partner API enables assessment platforms (code testing, video interviewing, personality testing) to seamlessly integrate with the Greenhouse interview workflow.
  name: Greenhouse Assessment API
  slug: assessment
- description: The Audit Log API offers a record of important events, providing insight into who accessed or edited information in Greenhouse.
  name: Greenhouse Audit Log API
  slug: audit-log
- description: Recruiting Webhooks deliver event notifications for Greenhouse Recruiting activities such as candidate updates, application stage changes, and offers.
  name: Greenhouse Recruiting Webhooks
  slug: recruiting-webhooks
- description: Onboarding Webhooks deliver event notifications for Greenhouse Onboarding activities such as new hires and employee updates.
  name: Greenhouse Onboarding Webhooks
  slug: onboarding-webhooks
common:
- title: ''
  type: Documentation
  url: https://developers.greenhouse.io
- title: ''
  type: GitHubOrg
  url: https://github.com/grnhse
created: '2025-01-07'
description: Greenhouse is an applicant tracking system (ATS) and recruiting software platform. It exposes a family of APIs and webhooks that let partners and customers manage candidates, jobs, applications, onboarding, audit logs, and assessment integrations.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Greenhouse
rules:
- name: Greenhouse API Rules
  rule_count: 13
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 7
  slug: greenhouse-spectral-rules
skills: []
slug: greenhouse
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: greenhouse\nname: Greenhouse\ndescription: >-\n  Greenhouse is an applicant tracking system (ATS) and recruiting software platform. It exposes a family of APIs and webhooks that let partners and customers manage candidates, jobs, applications, onboarding, audit logs, and assessment integrations.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - ATS\n  - Recruiting\n  - Candidates\n  - Jobs\n  - Onboarding\n  - HR\ncreated: '2025-01-07'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: greenhouse:harvest\n    name: Greenhouse Harvest API\n    description: >-\n      The Harvest API provides programmatic access to Greenhouse Recruiting data, including candidates, applications, jobs, departments, offices, and users.\n    humanURL: https://developers.greenhouse.io/harvest.html\n\
  \    baseURL: https://harvest.greenhouse.io/v1\n    tags:\n      - Harvest\n      - Candidates\n      - Jobs\n      - Applications\n    properties:\n      - type: Documentation\n        url: https://developers.greenhouse.io/harvest.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/openapi/greenhouse-harvest-openapi.yml\n  - aid: greenhouse:job-board\n    name: Greenhouse Job Board API\n    description: >-\n      The Job Board API enables building careers pages with custom look and feel, retrieving jobs, offices, departments, sections, education reference data, and submitting applications.\n    humanURL: https://developers.greenhouse.io/job-board.html\n    baseURL: https://boards-api.greenhouse.io/v1/boards\n    tags:\n      - Job Board\n      - Careers\n      - Jobs\n    properties:\n      - type: Documentation\n        url: https://developers.greenhouse.io/job-board.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/openapi/greenhouse-job-board-openapi.yml\n\
  \  - aid: greenhouse:ingestion\n    name: Greenhouse Candidate Ingestion API\n    description: >-\n      The Ingestion API enables sourcing partners to submit prospects and candidates to Greenhouse and to retrieve job and prospect pool information.\n    humanURL: https://developers.greenhouse.io/candidate-ingestion.html\n    baseURL: https://api.greenhouse.io/v1/partner\n    tags:\n      - Ingestion\n      - Candidates\n      - Sourcing\n    properties:\n      - type: Documentation\n        url: https://developers.greenhouse.io/candidate-ingestion.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/openapi/greenhouse-ingestion-openapi.yml\n  - aid: greenhouse:onboarding\n    name: Greenhouse Onboarding API\n    description: >-\n      A GraphQL API for Greenhouse Onboarding. Provides queries and mutations for employees, departments, locations, custom fields, teams, and pending hires.\n    humanURL: https://developers.greenhouse.io/gho.html\n\
  \    baseURL: https://onboarding-api.greenhouse.io/graphql\n    tags:\n      - Onboarding\n      - GraphQL\n      - Employees\n    properties:\n      - type: Documentation\n        url: https://developers.greenhouse.io/gho.html\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/openapi/greenhouse-onboarding-openapi.yml\n  - aid: greenhouse:assessment\n    name: Greenhouse Assessment API\n    description: >-\n      The Assessment Partner API enables assessment platforms (code testing, video interviewing, personality testing) to seamlessly integrate with the Greenhouse interview workflow.\n    humanURL: https://developers.greenhouse.io/assessment.html\n    tags:\n      - Assessment\n      - Testing\n      - Candidates\n    properties:\n      - type: Documentation\n        url: https://developers.greenhouse.io/assessment.html\n  - aid: greenhouse:audit-log\n    name: Greenhouse Audit Log API\n    description: >-\n      The Audit\
  \ Log API offers a record of important events, providing insight into who accessed or edited information in Greenhouse.\n    humanURL: https://developers.greenhouse.io/audit-log.html\n    tags:\n      - Audit\n      - Compliance\n      - Logging\n    properties:\n      - type: Documentation\n        url: https://developers.greenhouse.io/audit-log.html\n  - aid: greenhouse:recruiting-webhooks\n    name: Greenhouse Recruiting Webhooks\n    description: >-\n      Recruiting Webhooks deliver event notifications for Greenhouse Recruiting activities such as candidate updates, application stage changes, and offers.\n    humanURL: https://developers.greenhouse.io/webhooks.html\n    tags:\n      - Webhooks\n      - Recruiting\n      - Events\n    properties:\n      - type: Documentation\n        url: https://developers.greenhouse.io/webhooks.html\n  - aid: greenhouse:onboarding-webhooks\n    name: Greenhouse Onboarding Webhooks\n    description: >-\n      Onboarding Webhooks deliver event notifications\
  \ for Greenhouse Onboarding activities such as new hires and employee updates.\n    humanURL: https://developers.greenhouse.io/onboarding_webhooks.html\n    tags:\n      - Webhooks\n      - Onboarding\n      - Events\n    properties:\n      - type: Documentation\n        url: https://developers.greenhouse.io/onboarding_webhooks.html\ncommon:\n  - type: Documentation\n    name: Greenhouse Developer Docs\n    description: Top-level developer documentation hub for Greenhouse.\n    url: https://developers.greenhouse.io\n  - type: GitHubOrg\n    name: Greenhouse GitHub\n    description: Greenhouse open source repositories, including API docs.\n    url: https://github.com/grnhse\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/apis.yml
tags:
- ATS
- Recruiting
- Candidates
- Jobs
- Onboarding
- HR
url: https://raw.githubusercontent.com/api-evangelist/greenhouse/refs/heads/main/apis.yml
use_cases: []
---
