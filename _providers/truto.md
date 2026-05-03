---
api_count: 4
api_specs:
- filename: truto-admin-openapi.yml
  format: yaml
  label: Truto Admin API
  slug: truto-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/openapi/truto-admin-openapi.yml
- filename: truto-unified-hris-openapi.yml
  format: yaml
  label: Truto Unified HRIS API
  slug: truto-unified-hris-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/openapi/truto-unified-hris-openapi.yml
- filename: truto-unified-ats-openapi.yml
  format: yaml
  label: Truto Unified ATS API
  slug: truto-unified-ats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/openapi/truto-unified-ats-openapi.yml
- filename: truto-unified-crm-openapi.yml
  format: yaml
  label: Truto Unified CRM API
  slug: truto-unified-crm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/openapi/truto-unified-crm-openapi.yml
apis:
- description: The Truto Admin API enables programmatic management of the Truto platform, including creating and managing integrated accounts, generating link tokens for customer-initiated OAuth flows, running post-
  name: Truto Admin API
  slug: truto-admin-api
- description: The Truto Unified HRIS API provides a single normalized interface for accessing HR data across 41 HRIS providers including BambooHR, Workday, Rippling, Gusto, HiBob, Personio, and more. Offers 20 unif
  name: Truto Unified HRIS API
  slug: truto-unified-hris-api
- description: The Truto Unified ATS API provides a single normalized interface for accessing applicant tracking system data across 27 ATS providers including Greenhouse, Lever, Workable, SmartRecruiters, Ashby, Tea
  name: Truto Unified ATS API
  slug: truto-unified-ats-api
- description: The Truto Unified CRM API provides a single normalized interface for accessing CRM data across 27 CRM providers including Salesforce, HubSpot, Pipedrive, Attio, Outreach, and more. Offers 17 unified r
  name: Truto Unified CRM API
  slug: truto-unified-crm-api
capabilities:
- description: Unified integration platform capability combining Truto Admin API, HRIS, ATS, and CRM unified APIs. Used by B2B SaaS engineering teams and AI agents to manage connected third-party accounts, access no
  name: Truto Unified Integrations
  slug: unified-integrations
common:
- title: ''
  type: Website
  url: https://truto.one/
- title: ''
  type: Documentation
  url: https://truto.one/docs/
- title: ''
  type: Documentation
  url: https://truto.one/docs/api-reference/overview/introduction
- title: ''
  type: GettingStarted
  url: https://truto.one/docs/getting-started
- title: ''
  type: Documentation
  url: https://truto.one/unified-apis/
- title: ''
  type: Blog
  url: https://truto.one/blog/
- title: ''
  type: GitHub
  url: https://github.com/trutohq
- title: ''
  type: PrivacyPolicy
  url: https://truto.one/docs/api-reference/overview/introduction
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/rules/truto-rules.yml
created: '2026-03-16'
description: Truto is a unified API and embedded integration platform that enables B2B SaaS companies to ship native integrations without writing integration-specific code. Founded in 2023, Truto uses a declarative, config-driven architecture where every connector is data, not code. The platform provides Unified APIs across four major categories — HRIS (41 providers, 20 resources), ATS (27 providers, 17 resources), CRM (27 providers, 17 resources), and an expanding set of additional categories — plus an Admin API for managing integrated accounts, generating link tokens, and programmatic MCP server provisioning. Truto supports real-time pass-through (no data stored in between), full schema customization via JSONata, and one-API-call MCP server generation for AI agent access. Authentication uses Bearer tokens. Truto supports over 250 integrations and is available as Truto Cloud or on-premise.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 50
  name: Truto Context
  property_count: 16
  slug: truto-context
layout: provider
modified: '2026-05-03'
name: Truto
rules:
- name: Truto API Rules
  rule_count: 10
  severity_counts:
    error: 1
    hint: 0
    info: 3
    warn: 6
  slug: truto-rules
skills: []
slug: truto
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: truto\nurl: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/apis.yml\nname: Truto\ndescription: >-\n  Truto is a unified API and embedded integration platform that enables B2B SaaS companies\n  to ship native integrations without writing integration-specific code. Founded in 2023,\n  Truto uses a declarative, config-driven architecture where every connector is data, not\n  code. The platform provides Unified APIs across four major categories — HRIS (41 providers,\n  20 resources), ATS (27 providers, 17 resources), CRM (27 providers, 17 resources), and\n  an expanding set of additional categories — plus an Admin API for managing integrated\n  accounts, generating link tokens, and programmatic MCP server provisioning. Truto supports\n  real-time pass-through (no data stored in between), full schema customization via JSONata,\n  and one-API-call MCP server generation for AI agent access. Authentication uses Bearer\n  tokens. Truto supports over 250\
  \ integrations and is available as Truto Cloud or on-premise.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Unified API\n  - Integration Platform\n  - HRIS\n  - ATS\n  - CRM\n  - Embedded Integrations\n  - MCP\n  - AI Agents\n  - SaaS\naccess: 3rd-Party\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: truto:truto-admin-api\n    name: Truto Admin API\n    tags:\n      - Administration\n      - Integrated Accounts\n      - Link Tokens\n      - MCP\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.truto.one\n    humanURL: https://truto.one/docs/api-reference/admin\n    properties:\n      - url: https://truto.one/docs/api-reference/admin\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/openapi/truto-admin-openapi.yml\n        type: OpenAPI\n    description: >-\n\
  \      The Truto Admin API enables programmatic management of the Truto platform, including\n      creating and managing integrated accounts, generating link tokens for customer-initiated\n      OAuth flows, running post-install actions, and provisioning MCP servers. Integrated\n      accounts represent a connection between your Truto account and a customer's connected\n      app. Link tokens initiate the Truto linking process from within your application.\n      The Admin API uses Bearer token authentication with the tenant API token.\n  - aid: truto:truto-unified-hris-api\n    name: Truto Unified HRIS API\n    tags:\n      - HRIS\n      - Human Resources\n      - Employees\n      - Payroll\n      - Unified API\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.truto.one/unified/hris\n    humanURL: https://truto.one/docs/api-reference/unified-hris-api\n    properties:\n      - url: https://truto.one/docs/api-reference/unified-hris-api\n\
  \        type: Documentation\n      - url: https://truto.one/unified-apis/hris/\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/openapi/truto-unified-hris-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Truto Unified HRIS API provides a single normalized interface for accessing HR\n      data across 41 HRIS providers including BambooHR, Workday, Rippling, Gusto, HiBob,\n      Personio, and more. Offers 20 unified resources including employees, employments,\n      companies, groups (departments and roles), timeoff requests, and more. Data is\n      accessed in real-time with no caching. Schema can be extended using JSONata mappings.\n      Authentication uses Bearer token with integrated_account_id query parameter to specify\n      the target connected account.\n  - aid: truto:truto-unified-ats-api\n    name: Truto Unified ATS API\n    tags:\n      - ATS\n      - Applicant Tracking\n      - Recruiting\n\
  \      - Jobs\n      - Candidates\n      - Unified API\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.truto.one/unified/ats\n    humanURL: https://truto.one/docs/api-reference/unified-ats-api\n    properties:\n      - url: https://truto.one/docs/api-reference/unified-ats-api\n        type: Documentation\n      - url: https://truto.one/unified-apis/ats/\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/openapi/truto-unified-ats-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Truto Unified ATS API provides a single normalized interface for accessing\n      applicant tracking system data across 27 ATS providers including Greenhouse, Lever,\n      Workable, SmartRecruiters, Ashby, Teamtailor, and more. Offers 17 unified resources\n      covering the full recruiting lifecycle: jobs, candidates, applications, interview\n      stages, interviews,\
  \ scorecards, offers, EEOC data, departments, offices, reject\n      reasons, activities, attachments, tags, and users. Authentication uses Bearer token\n      with integrated_account_id query parameter.\n  - aid: truto:truto-unified-crm-api\n    name: Truto Unified CRM API\n    tags:\n      - CRM\n      - Customer Relationship Management\n      - Contacts\n      - Opportunities\n      - Unified API\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.truto.one/unified/crm\n    humanURL: https://truto.one/docs/api-reference/unified-crm-api\n    properties:\n      - url: https://truto.one/docs/api-reference/unified-crm-api\n        type: Documentation\n      - url: https://truto.one/unified-apis/crm/\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/openapi/truto-unified-crm-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Truto Unified CRM API provides\
  \ a single normalized interface for accessing CRM\n      data across 27 CRM providers including Salesforce, HubSpot, Pipedrive, Attio,\n      Outreach, and more. Offers 17 unified resources including accounts, contacts,\n      opportunities, tasks, users, stages, engagements, notes, fields, associations, and\n      more. Data is accessed in real-time via pass-through to underlying CRM APIs.\n      Authentication uses Bearer token with integrated_account_id query parameter.\ncommon:\n  - url: https://truto.one/\n    name: Truto Website\n    type: Website\n  - url: https://truto.one/docs/\n    name: Developer Documentation\n    type: Documentation\n  - url: https://truto.one/docs/api-reference/overview/introduction\n    name: API Reference Introduction\n    type: Documentation\n  - url: https://truto.one/docs/getting-started\n    name: Getting Started\n    type: GettingStarted\n  - url: https://truto.one/integrations/\n    name: Integration Directory\n    type: Integrations\n  - url: https://truto.one/unified-apis/\n\
  \    name: Unified APIs\n    type: Documentation\n  - url: https://truto.one/blog/\n    name: Truto Blog\n    type: Blog\n  - url: https://github.com/trutohq\n    name: Truto on GitHub\n    type: GitHub\n  - url: https://truto.one/docs/api-reference/overview/introduction\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/rules/truto-rules.yml\n    name: Spectral Rules\n    type: SpectralRules\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/apis.yml
tags:
- Unified API
- Integration Platform
- HRIS
- ATS
- CRM
- Embedded Integrations
- MCP
- AI Agents
- SaaS
url: https://raw.githubusercontent.com/api-evangelist/truto/refs/heads/main/apis.yml
use_cases: []
---
