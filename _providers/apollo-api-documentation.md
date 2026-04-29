---
api_count: 1
apis:
- description: Apollo's REST API provides programmatic access to Apollo's sales intelligence database of 210M+ contacts and 35M+ companies. The API supports people enrichment, organization enrichment, people search,
  name: Apollo REST API
  slug: apollo-rest-api
common:
- title: ''
  type: Documentation
  url: https://docs.apollo.io/
- title: ''
  type: GettingStarted
  url: https://docs.apollo.io/docs
- title: ''
  type: APIReference
  url: https://docs.apollo.io/reference
- title: ''
  type: Authentication
  url: https://docs.apollo.io/reference/authentication
- title: ''
  type: RateLimits
  url: https://docs.apollo.io/reference/rate-limits
created: '2025-07-10'
description: Apollo.io provides a comprehensive REST API for sales intelligence with over 210 million contacts and 35 million companies. The Apollo API enables data enrichment, people and organization search, CRM management, sequences, deals, analytics, and integrations. Authentication is via API keys or OAuth 2.0 for partner integrations. This repository profiles Apollo.io's API documentation as an example of API documentation best practices.
features:
- description: Enrich contact records with data from Apollo's 210M+ contact database.
  name: People Enrichment
- description: Enrich company records with data from Apollo's 35M+ company database.
  name: Organization Enrichment
- description: Search Apollo's contact database to find and identify sales prospects.
  name: People Search
- description: Search Apollo's company database for target accounts and job postings.
  name: Organization Search
- description: Manage accounts, contacts, deals, and sequences via the REST API.
  name: CRM Integration
- description: Partners use OAuth 2.0 to build integrations accessing Apollo data on behalf of customers.
  name: OAuth 2.0 Partner Integration
- description: Interactive API testing capability built directly into the documentation.
  name: Interactive Try It
- description: Query analytics reports for performance metrics via the API.
  name: Analytics Reporting
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Partner integration protocol for accessing Apollo data on behalf of customers.
  name: OAuth 2.0
- description: Direct API key access for customers building internal integrations.
  name: API Key Authentication
layout: provider
modified: '2026-04-19'
name: Apollo API Documentation
skills: []
slug: apollo-api-documentation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apollo-api-documentation\nname: Apollo API Documentation\ndescription: >-\n  Apollo.io provides a comprehensive REST API for sales intelligence with over 210\n  million contacts and 35 million companies. The Apollo API enables data enrichment,\n  people and organization search, CRM management, sequences, deals, analytics, and\n  integrations. Authentication is via API keys or OAuth 2.0 for partner integrations.\n  This repository profiles Apollo.io's API documentation as an example of API\n  documentation best practices.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Documentation\n  - Best Practices\n  - Data Enrichment\n  - People Search\n  - Sales Intelligence\ncreated: '2025-07-10'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apollo-api-documentation/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apollo-api-documentation:apollo-rest-api\n\
  \    name: Apollo REST API\n    description: >-\n      Apollo's REST API provides programmatic access to Apollo's sales intelligence\n      database of 210M+ contacts and 35M+ companies. The API supports people enrichment,\n      organization enrichment, people search, accounts and contacts management, deals,\n      sequences, tasks, analytics reporting, and calls management. Access is controlled\n      by the customer's Apollo plan tier.\n    humanURL: https://docs.apollo.io/\n    tags:\n      - Analytics\n      - CRM\n      - Data Enrichment\n      - Organization Search\n      - People Search\n      - REST\n      - Sales Intelligence\n      - Sequences\n    properties:\n      - type: Documentation\n        url: https://docs.apollo.io/\n      - type: GettingStarted\n        url: https://docs.apollo.io/docs\n      - type: APIReference\n        url: https://docs.apollo.io/reference\n      - type: Authentication\n        url: https://docs.apollo.io/reference/authentication\n      - type:\
  \ RateLimits\n        url: https://docs.apollo.io/reference/rate-limits\n      - type: Tutorials\n        url: https://docs.apollo.io/docs/overview-apollo-api-tutorials\n      - type: FAQ\n        url: https://docs.apollo.io/docs/apollo-api-faqs\ncommon:\n  - type: Documentation\n    url: https://docs.apollo.io/\n  - type: GettingStarted\n    url: https://docs.apollo.io/docs\n  - type: APIReference\n    url: https://docs.apollo.io/reference\n  - type: Authentication\n    url: https://docs.apollo.io/reference/authentication\n  - type: RateLimits\n    url: https://docs.apollo.io/reference/rate-limits\n  - type: Features\n    data:\n      - name: People Enrichment\n        description: Enrich contact records with data from Apollo's 210M+ contact database.\n      - name: Organization Enrichment\n        description: Enrich company records with data from Apollo's 35M+ company database.\n      - name: People Search\n        description: Search Apollo's contact database to find and identify sales\
  \ prospects.\n      - name: Organization Search\n        description: Search Apollo's company database for target accounts and job postings.\n      - name: CRM Integration\n        description: Manage accounts, contacts, deals, and sequences via the REST API.\n      - name: OAuth 2.0 Partner Integration\n        description: Partners use OAuth 2.0 to build integrations accessing Apollo data on behalf of customers.\n      - name: Interactive Try It\n        description: Interactive API testing capability built directly into the documentation.\n      - name: Analytics Reporting\n        description: Query analytics reports for performance metrics via the API.\n  - type: UseCases\n    data:\n      - name: Sales Intelligence\n        description: Access Apollo's contact and company database for prospecting and outreach.\n      - name: Data Enrichment Pipelines\n        description: Enrich CRM records with contact and organization data at scale.\n      - name: Partner Integrations\n       \
  \ description: Build third-party integrations using OAuth 2.0 to access Apollo data for mutual customers.\n      - name: Workflow Automation\n        description: Automate sales workflows including sequences, tasks, and deal management.\n  - type: Integrations\n    data:\n      - name: OAuth 2.0\n        description: Partner integration protocol for accessing Apollo data on behalf of customers.\n      - name: API Key Authentication\n        description: Direct API key access for customers building internal integrations.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apollo-api-documentation/refs/heads/main/apis.yml
tags:
- API Documentation
- Best Practices
- Data Enrichment
- People Search
- Sales Intelligence
url: https://raw.githubusercontent.com/api-evangelist/apollo-api-documentation/refs/heads/main/apis.yml
use_cases:
- description: Access Apollo's contact and company database for prospecting and outreach.
  name: Sales Intelligence
- description: Enrich CRM records with contact and organization data at scale.
  name: Data Enrichment Pipelines
- description: Build third-party integrations using OAuth 2.0 to access Apollo data for mutual customers.
  name: Partner Integrations
- description: Automate sales workflows including sequences, tasks, and deal management.
  name: Workflow Automation
---
