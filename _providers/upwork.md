---
api_count: 2
api_specs:
- filename: upwork-graphql-api-openapi.yml
  format: yaml
  label: Upwork GraphQL API
  slug: graphql-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/upwork/refs/heads/main/openapi/upwork-graphql-api-openapi.yml
- filename: upwork-rest-api-openapi.yml
  format: yaml
  label: Upwork REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/upwork/refs/heads/main/openapi/upwork-rest-api-openapi.yml
apis:
- description: The primary Upwork API surface, providing GraphQL queries and mutations for job search, profile access, contract management, and messaging. Authentication uses OAuth 2.0 authorization code flow. The A
  name: Upwork GraphQL API
  slug: graphql-api
- description: The legacy REST API surface for Upwork, covering job search, contracts, reporting, organization management, and freelancer profiles. OAuth 2.0 authentication is required. Many endpoints have been migr
  name: Upwork REST API
  slug: rest-api
capabilities:
- description: Unified workflow capability for finding, evaluating, and engaging freelancers on Upwork. Combines job search, freelancer profile access, contract management, and messaging into a single talent acquisi
  name: Upwork Talent Marketplace
  slug: talent-marketplace
common:
- title: ''
  type: Website
  url: https://www.upwork.com/
- title: ''
  type: Documentation
  url: https://www.upwork.com/developer/documentation/graphql/api/docs/index.html
- title: ''
  type: Portal
  url: https://www.upwork.com/developer
- title: ''
  type: Support
  url: https://support.upwork.com/hc/en-us/sections/17976982721555-Upwork-API
- title: ''
  type: Authentication
  url: https://support.upwork.com/hc/en-us/articles/115015933448-API-authentication-and-security
- title: ''
  type: GitHubOrganization
  url: https://github.com/upwork
- title: Python SDK (OAuth2)
  type: GitHubRepository
  url: https://github.com/upwork/python-upwork-oauth2
- title: Node.js SDK (OAuth2)
  type: GitHubRepository
  url: https://github.com/upwork/node-upwork-oauth2
- title: Java SDK (OAuth2)
  type: GitHubRepository
  url: https://github.com/upwork/java-upwork-oauth2
- title: Go SDK (OAuth2)
  type: GitHubRepository
  url: https://github.com/upwork/golang-upwork-oauth2
- title: Ruby SDK (OAuth2)
  type: GitHubRepository
  url: https://github.com/upwork/ruby-upwork-oauth2
- title: PHP SDK (OAuth2)
  type: GitHubRepository
  url: https://github.com/upwork/php-upwork-oauth2
- title: Perl SDK (OAuth2)
  type: GitHubRepository
  url: https://github.com/upwork/perl-upwork-oauth2
- title: ''
  type: JSONLD
  url: json-ld/upwork-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/upwork-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/upwork-vocabulary.yaml
- title: Talent Marketplace
  type: NaftikoCapability
  url: capabilities/talent-marketplace.yaml
- title: GraphQL API (Shared)
  type: NaftikoCapability
  url: capabilities/shared/graphql-api.yaml
created: '2026-03-16'
description: Upwork is a global freelancing platform that connects businesses with independent professionals through a talent marketplace. The Upwork API enables developers to integrate Upwork features into their applications, including job search, contract management, messaging, profile access, and webhook event subscriptions. The API is primarily GraphQL-based at api.upwork.com/graphql, with OAuth 2.0 authentication. Key resources include job postings, contracts, user profiles, messages, and freelancer search. The platform serves over 800,000 clients and 18 million freelancers across 180+ countries.
features:
- description: Search and filter job postings using marketplaceJobPostingsSearch GraphQL query with full-text and faceted search.
  name: Job Search
- description: Access active and completed contracts, contract terms, milestones, and time entries.
  name: Contract Management
- description: Read and send messages within active contracts using GraphQL mutations.
  name: Messaging
- description: Query freelancer and client profiles, skills, portfolios, and ratings.
  name: Profile Access
- description: Subscribe to events for real-time notifications when contracts, jobs, or messages change.
  name: Webhook Subscriptions
- description: Secure API access using OAuth 2.0 authorization code grant flow with refresh token support.
  name: OAuth 2.0 Authentication
- description: Official SDKs for Python, Node.js, Java, Go, Ruby, PHP, and Perl with OAuth2 support.
  name: Multi-Language SDKs
- description: Interactive GraphQL API explorer at upwork.com/developer/explorer for testing queries.
  name: GraphQL Explorer
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Official Power BI connector for importing Upwork data into business intelligence dashboards.
  name: PowerBI Connector
- description: Standard OAuth 2.0 integration with any identity provider supporting authorization code flow.
  name: OAuth 2.0 Providers
- description: Real-time event streaming to external systems via Upwork subscription webhooks.
  name: Webhook Integration
jsonld:
- class_count: 24
  name: Upwork Context
  property_count: 61
  slug: upwork-context
layout: provider
modified: '2026-05-03'
name: Upwork
rules:
- name: Upwork API Rules
  rule_count: 21
  severity_counts:
    error: 13
    hint: 0
    info: 0
    warn: 8
  slug: upwork-spectral-rules
skills: []
slug: upwork
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: upwork\nname: Upwork\ndescription: >-\n  Upwork is a global freelancing platform that connects businesses with\n  independent professionals through a talent marketplace. The Upwork API\n  enables developers to integrate Upwork features into their applications,\n  including job search, contract management, messaging, profile access,\n  and webhook event subscriptions. The API is primarily GraphQL-based\n  at api.upwork.com/graphql, with OAuth 2.0 authentication. Key resources\n  include job postings, contracts, user profiles, messages, and freelancer\n  search. The platform serves over 800,000 clients and 18 million freelancers\n  across 180+ countries.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Freelancing\n  - Jobs\n  - Talent\n  - Marketplace\n  - Contracts\n  - Hiring\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/upwork/refs/heads/main/apis.yml\ncreated:\
  \ '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: upwork:graphql-api\n    name: Upwork GraphQL API\n    description: >-\n      The primary Upwork API surface, providing GraphQL queries and mutations\n      for job search, profile access, contract management, and messaging.\n      Authentication uses OAuth 2.0 authorization code flow. The API supports\n      subscriptions for real-time event notifications via webhooks.\n    humanURL: https://www.upwork.com/developer/documentation/graphql/api/docs/index.html\n    baseURL: https://api.upwork.com/graphql\n    tags:\n      - GraphQL\n      - Jobs\n      - Contracts\n      - Profiles\n      - Messages\n      - Freelancing\n    properties:\n      - type: Documentation\n        url: https://www.upwork.com/developer/documentation/graphql/api/docs/index.html\n      - type: OpenAPI\n        url: openapi/upwork-graphql-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/graphql-api-job-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/graphql-api-contract-schema.json\n      - type: JSONSchema\n        url: json-schema/graphql-api-freelancer-profile-schema.json\n      - type: JSONSchema\n        url: json-schema/graphql-api-message-schema.json\n  - aid: upwork:rest-api\n    name: Upwork REST API\n    description: >-\n      The legacy REST API surface for Upwork, covering job search, contracts,\n      reporting, organization management, and freelancer profiles. OAuth 2.0\n      authentication is required. Many endpoints have been migrated to GraphQL.\n    humanURL: https://developers.upwork.com/\n    baseURL: https://www.upwork.com/api\n    tags:\n      - REST\n      - Jobs\n      - Contracts\n      - Profiles\n      - Reports\n    properties:\n      - type: Documentation\n        url: https://developers.upwork.com/\n      - type: GettingStarted\n        url: https://developers.upwork.com/#get-started\n      - type: OpenAPI\n        url: openapi/upwork-rest-api-openapi.yml\n\
  \      - type: JSONSchema\n        url: json-schema/rest-api-report-response-schema.json\n      - type: JSONSchema\n        url: json-schema/rest-api-engagement-schema.json\ncommon:\n  - type: Website\n    url: https://www.upwork.com/\n  - type: Documentation\n    url: https://www.upwork.com/developer/documentation/graphql/api/docs/index.html\n  - type: Portal\n    url: https://www.upwork.com/developer\n  - type: Support\n    url: https://support.upwork.com/hc/en-us/sections/17976982721555-Upwork-API\n  - type: Authentication\n    url: https://support.upwork.com/hc/en-us/articles/115015933448-API-authentication-and-security\n  - type: GitHubOrganization\n    url: https://github.com/upwork\n  - type: GitHubRepository\n    url: https://github.com/upwork/python-upwork-oauth2\n    title: Python SDK (OAuth2)\n  - type: GitHubRepository\n    url: https://github.com/upwork/node-upwork-oauth2\n    title: Node.js SDK (OAuth2)\n  - type: GitHubRepository\n    url: https://github.com/upwork/java-upwork-oauth2\n\
  \    title: Java SDK (OAuth2)\n  - type: GitHubRepository\n    url: https://github.com/upwork/golang-upwork-oauth2\n    title: Go SDK (OAuth2)\n  - type: GitHubRepository\n    url: https://github.com/upwork/ruby-upwork-oauth2\n    title: Ruby SDK (OAuth2)\n  - type: GitHubRepository\n    url: https://github.com/upwork/php-upwork-oauth2\n    title: PHP SDK (OAuth2)\n  - type: GitHubRepository\n    url: https://github.com/upwork/perl-upwork-oauth2\n    title: Perl SDK (OAuth2)\n  - type: JSONLD\n    url: json-ld/upwork-context.jsonld\n  - type: SpectralRules\n    url: rules/upwork-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/upwork-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/talent-marketplace.yaml\n    title: Talent Marketplace\n  - type: NaftikoCapability\n    url: capabilities/shared/graphql-api.yaml\n    title: GraphQL API (Shared)\n  - type: Features\n    data:\n      - name: Job Search\n        description: Search and filter job postings using\
  \ marketplaceJobPostingsSearch GraphQL query with full-text and faceted search.\n      - name: Contract Management\n        description: Access active and completed contracts, contract terms, milestones, and time entries.\n      - name: Messaging\n        description: Read and send messages within active contracts using GraphQL mutations.\n      - name: Profile Access\n        description: Query freelancer and client profiles, skills, portfolios, and ratings.\n      - name: Webhook Subscriptions\n        description: Subscribe to events for real-time notifications when contracts, jobs, or messages change.\n      - name: OAuth 2.0 Authentication\n        description: Secure API access using OAuth 2.0 authorization code grant flow with refresh token support.\n      - name: Multi-Language SDKs\n        description: Official SDKs for Python, Node.js, Java, Go, Ruby, PHP, and Perl with OAuth2 support.\n      - name: GraphQL Explorer\n        description: Interactive GraphQL API explorer at\
  \ upwork.com/developer/explorer for testing queries.\n  - type: UseCases\n    data:\n      - name: Freelancer Management\n        description: Agencies and businesses managing a distributed freelancer workforce through programmatic contract and message access.\n      - name: Job Monitoring\n        description: Applications tracking new job postings matching specific criteria using scheduled search queries.\n      - name: Talent Analytics\n        description: Platforms building talent scoring, profile analysis, and market intelligence on freelancers.\n      - name: CRM Integration\n        description: Connecting Upwork client and contract data to CRM systems for unified client management.\n      - name: Automated Reporting\n        description: Building custom dashboards and reports from Upwork contract, billing, and engagement data.\n  - type: Integrations\n    data:\n      - name: PowerBI Connector\n        description: Official Power BI connector for importing Upwork data into business\
  \ intelligence dashboards.\n      - name: OAuth 2.0 Providers\n        description: Standard OAuth 2.0 integration with any identity provider supporting authorization code flow.\n      - name: Webhook Integration\n        description: Real-time event streaming to external systems via Upwork subscription webhooks.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/upwork/refs/heads/main/apis.yml
tags:
- Freelancing
- Jobs
- Talent
- Marketplace
- Contracts
- Hiring
url: https://raw.githubusercontent.com/api-evangelist/upwork/refs/heads/main/apis.yml
use_cases:
- description: Agencies and businesses managing a distributed freelancer workforce through programmatic contract and message access.
  name: Freelancer Management
- description: Applications tracking new job postings matching specific criteria using scheduled search queries.
  name: Job Monitoring
- description: Platforms building talent scoring, profile analysis, and market intelligence on freelancers.
  name: Talent Analytics
- description: Connecting Upwork client and contract data to CRM systems for unified client management.
  name: CRM Integration
- description: Building custom dashboards and reports from Upwork contract, billing, and engagement data.
  name: Automated Reporting
---
