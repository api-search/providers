---
api_count: 5
api_specs:
- filename: coresignal-multi-source-company-api-openapi.yml
  format: yaml
  label: Coresignal Multi-source Company API
  slug: multi-source-company-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coresignal/refs/heads/main/openapi/coresignal-multi-source-company-api-openapi.yml
- filename: coresignal-multi-source-employee-api-openapi.yml
  format: yaml
  label: Coresignal Multi-source Employee API
  slug: multi-source-employee-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coresignal/refs/heads/main/openapi/coresignal-multi-source-employee-api-openapi.yml
- filename: coresignal-multi-source-jobs-api-openapi.yml
  format: yaml
  label: Coresignal Multi-source Jobs API
  slug: multi-source-jobs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coresignal/refs/heads/main/openapi/coresignal-multi-source-jobs-api-openapi.yml
apis:
- description: The Multi-source Company API returns enriched company records combining data from multiple public web sources, deduplicated and standardized with 500+ data fields covering firmographics, technographic
  name: Coresignal Multi-source Company API
  slug: multi-source-company-api
- description: 'The Multi-source Employee API returns enriched employee profiles aggregated from multiple public sources with 300+ data fields covering experience, education, skills, certifications, and connections. '
  name: Coresignal Multi-source Employee API
  slug: multi-source-employee-api
- description: The Multi-source Jobs API returns enriched job posting records aggregated from multiple public sources with 85+ data fields covering title, location, company, salary, posted date, source URLs, and ful
  name: Coresignal Multi-source Jobs API
  slug: multi-source-jobs-api
- description: 'The Agentic Search API enables natural language search across Coresignal''s company, employee, and jobs datasets, returning relevant records based on conversational queries. Designed for AI agents and '
  name: Coresignal Agentic Search API
  slug: agentic-search-api
- description: 'The Company Enrichment API takes a company domain or name and returns a fully-enriched company record. Designed for sales and marketing systems that need to enrich CRM records or web form submissions '
  name: Coresignal Company Enrichment API
  slug: company-enrichment-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://coresignal.com
- title: ''
  type: DeveloperPortal
  url: https://docs.coresignal.com/
- title: ''
  type: Documentation
  url: https://docs.coresignal.com/
- title: ''
  type: APIsOverview
  url: https://docs.coresignal.com/api-introduction/apis-overview
- title: ''
  type: Authorization
  url: https://docs.coresignal.com/api-introduction/authorization
- title: ''
  type: GettingStarted
  url: https://docs.coresignal.com/api-introduction/getting-started
- title: ''
  type: RateLimits
  url: https://docs.coresignal.com/api-introduction/rate-limits
- title: ''
  type: ResponseCodes
  url: https://docs.coresignal.com/api-introduction/response-codes
- title: ''
  type: Credits
  url: https://docs.coresignal.com/api-introduction/credits
- title: ''
  type: Webhooks
  url: https://docs.coresignal.com/api-introduction/webhooks
- title: ''
  type: Dashboard
  url: https://dashboard.coresignal.com/sign-in
- title: ''
  type: SignUp
  url: https://dashboard.coresignal.com/sign-up
- title: ''
  type: Pricing
  url: https://coresignal.com/pricing/
- title: ''
  type: Blog
  url: https://coresignal.com/blog/
- title: ''
  type: Vocabulary
  url: vocabulary/coresignal-vocabulary.yml
- title: ''
  type: JSONLD
  url: json-ld/coresignal-context.jsonld
- title: ''
  type: PrivacyPolicy
  url: https://coresignal.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://coresignal.com/terms-and-conditions/
- title: ''
  type: Status
  url: https://status.coresignal.com/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/coresignal
- title: ''
  type: Twitter
  url: https://twitter.com/coresignal
created: '2025-02-12'
description: Coresignal is a data-as-a-service company providing access to public web data on companies, employees, and jobs through a suite of REST APIs. The platform aggregates and refines more than 4.5 billion data records covering 75M+ companies (with 500+ data fields), 865M+ employee profiles (300+ fields), and 461M+ job postings (85+ fields). Coresignal offers Multi-source, Clean, and Base data tiers across Company, Employee, and Jobs APIs, plus specialized real-time, employee posts, agentic search, and company enrichment endpoints. Authentication uses a single apikey HTTP header.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 42
  name: Coresignal Context
  property_count: 0
  slug: coresignal-context
layout: provider
modified: '2026-04-28'
name: Coresignal
rules:
- name: Coresignal API Rules
  rule_count: 9
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 3
  slug: coresignal-multi-source-company-api-rules
- name: Coresignal API Rules
  rule_count: 7
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 1
  slug: coresignal-multi-source-employee-api-rules
- name: Coresignal API Rules
  rule_count: 7
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 2
  slug: coresignal-multi-source-jobs-api-rules
skills: []
slug: coresignal
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: coresignal\nname: Coresignal\nx-type: company\ndescription: >-\n  Coresignal is a data-as-a-service company providing access to public web\n  data on companies, employees, and jobs through a suite of REST APIs. The\n  platform aggregates and refines more than 4.5 billion data records covering\n  75M+ companies (with 500+ data fields), 865M+ employee profiles (300+\n  fields), and 461M+ job postings (85+ fields). Coresignal offers Multi-source,\n  Clean, and Base data tiers across Company, Employee, and Jobs APIs, plus\n  specialized real-time, employee posts, agentic search, and company\n  enrichment endpoints. Authentication uses a single apikey HTTP header.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/coresignal/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - Agentic Search\n  - B2B Data\n  - Companies\n  - Company Data\n  - Data\
  \ as a Service\n  - Elasticsearch\n  - Employee Data\n  - Employees\n  - Enrichment\n  - Firmographics\n  - Job Postings\n  - Jobs\n  - Lead Generation\n  - People Data\n  - Sales Intelligence\n  - Talent Intelligence\n  - Web Data\ncreated: '2025-02-12'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\napis:\n  - aid: coresignal:multi-source-company-api\n    name: Coresignal Multi-source Company API\n    description: >-\n      The Multi-source Company API returns enriched company records combining\n      data from multiple public web sources, deduplicated and standardized\n      with 500+ data fields covering firmographics, technographics, headcount,\n      revenue, and locations. Search uses Elasticsearch DSL. Results are\n      paginated and credits-priced per response.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.coresignal.com/multi-source-company-api/\n    baseURL: https://api.coresignal.com/cdapi/v2/multi_source_company\n\
  \    tags:\n      - Companies\n      - Firmographics\n      - Multi-source\n    properties:\n      - type: Documentation\n        url: https://docs.coresignal.com/multi-source-company-api/\n      - type: DataDictionary\n        url: https://docs.coresignal.com/multi-source-company-api/data-dictionary\n      - type: Sample\n        url: https://docs.coresignal.com/multi-source-company-api/sample\n      - type: SearchFilters\n        url: https://docs.coresignal.com/multi-source-company-api/search-filters\n      - type: ElasticsearchDSL\n        url: https://docs.coresignal.com/multi-source-company-api/search-with-es-dsl\n      - type: Collect\n        url: https://docs.coresignal.com/multi-source-company-api/collect\n      - type: BulkCollect\n        url: https://docs.coresignal.com/multi-source-company-api/bulk-collect\n      - type: Webhooks\n        url: https://docs.coresignal.com/multi-source-company-api/subscriptions\n      - type: OpenAPI\n        url: openapi/coresignal-multi-source-company-api-openapi.yml\n\
  \      - type: Rules\n        url: rules/coresignal-multi-source-company-api-rules.yml\n      - type: Capabilities\n        url: capabilities/coresignal-company-data-collection-capabilities.yml\n  - aid: coresignal:multi-source-employee-api\n    name: Coresignal Multi-source Employee API\n    description: >-\n      The Multi-source Employee API returns enriched employee profiles\n      aggregated from multiple public sources with 300+ data fields covering\n      experience, education, skills, certifications, and connections. Search\n      uses Elasticsearch DSL with rich filter support, pagination, and\n      collect/bulk_collect endpoints for retrieving full records by ID.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.coresignal.com/multi-source-employee-api/\n    baseURL: https://api.coresignal.com/cdapi/v2/multi_source_employee\n    tags:\n      - Employees\n      - Multi-source\n      - People Data\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.coresignal.com/multi-source-employee-api/\n      - type: DataDictionary\n        url: https://docs.coresignal.com/multi-source-employee-api/data-dictionary\n      - type: Sample\n        url: https://docs.coresignal.com/multi-source-employee-api/sample\n      - type: SearchFilters\n        url: https://docs.coresignal.com/multi-source-employee-api/search-filters\n      - type: ElasticsearchDSL\n        url: https://docs.coresignal.com/multi-source-employee-api/search-with-es-dsl\n      - type: Collect\n        url: https://docs.coresignal.com/multi-source-employee-api/collect\n      - type: BulkCollect\n        url: https://docs.coresignal.com/multi-source-employee-api/bulk-collect\n      - type: Webhooks\n        url: https://docs.coresignal.com/multi-source-employee-api/subscriptions\n      - type: OpenAPI\n        url: openapi/coresignal-multi-source-employee-api-openapi.yml\n      - type: Rules\n        url: rules/coresignal-multi-source-employee-api-rules.yml\n\
  \      - type: Capabilities\n        url: capabilities/coresignal-employee-data-collection-capabilities.yml\n  - aid: coresignal:multi-source-jobs-api\n    name: Coresignal Multi-source Jobs API\n    description: >-\n      The Multi-source Jobs API returns enriched job posting records\n      aggregated from multiple public sources with 85+ data fields covering\n      title, location, company, salary, posted date, source URLs, and full\n      job descriptions. Search uses Elasticsearch DSL with collect endpoints\n      for retrieving full records by ID.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.coresignal.com/multi-source-jobs-api/\n    baseURL: https://api.coresignal.com/cdapi/v2/multi_source_jobs\n    tags:\n      - Jobs\n      - Multi-source\n      - Recruiting\n    properties:\n      - type: Documentation\n        url: https://docs.coresignal.com/multi-source-jobs-api/\n      - type: DataDictionary\n        url:\
  \ https://docs.coresignal.com/multi-source-jobs-api/data-dictionary\n      - type: Sample\n        url: https://docs.coresignal.com/multi-source-jobs-api/sample\n      - type: SearchFilters\n        url: https://docs.coresignal.com/multi-source-jobs-api/search-filters\n      - type: ElasticsearchDSL\n        url: https://docs.coresignal.com/multi-source-jobs-api/search-with-es-dsl\n      - type: Collect\n        url: https://docs.coresignal.com/multi-source-jobs-api/collect\n      - type: OpenAPI\n        url: openapi/coresignal-multi-source-jobs-api-openapi.yml\n      - type: Rules\n        url: rules/coresignal-multi-source-jobs-api-rules.yml\n      - type: Capabilities\n        url: capabilities/coresignal-jobs-data-collection-capabilities.yml\n  - aid: coresignal:agentic-search-api\n    name: Coresignal Agentic Search API\n    description: >-\n      The Agentic Search API enables natural language search across\n      Coresignal's company, employee, and jobs datasets, returning relevant\n\
  \      records based on conversational queries. Designed for AI agents and\n      automated workflows that need quick B2B data lookups without crafting\n      Elasticsearch queries.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.coresignal.com/agentic-search-api/\n    baseURL: https://api.coresignal.com/cdapi/v2/agentic_search\n    tags:\n      - Agentic Search\n      - AI Agents\n      - Natural Language\n    properties:\n      - type: Documentation\n        url: https://docs.coresignal.com/agentic-search-api/\n  - aid: coresignal:company-enrichment-api\n    name: Coresignal Company Enrichment API\n    description: >-\n      The Company Enrichment API takes a company domain or name and returns\n      a fully-enriched company record. Designed for sales and marketing\n      systems that need to enrich CRM records or web form submissions in real\n      time.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://docs.coresignal.com/company-enrichment-api/\n    baseURL: https://api.coresignal.com/cdapi/v2/company_enrichment\n    tags:\n      - Companies\n      - Enrichment\n      - CRM\n    properties:\n      - type: Documentation\n        url: https://docs.coresignal.com/company-enrichment-api/\ncommon:\n  - type: Website\n    url: https://coresignal.com\n  - type: DeveloperPortal\n    url: https://docs.coresignal.com/\n  - type: Documentation\n    url: https://docs.coresignal.com/\n  - type: APIsOverview\n    url: https://docs.coresignal.com/api-introduction/apis-overview\n  - type: Authorization\n    url: https://docs.coresignal.com/api-introduction/authorization\n  - type: GettingStarted\n    url: https://docs.coresignal.com/api-introduction/getting-started\n  - type: RateLimits\n    url: https://docs.coresignal.com/api-introduction/rate-limits\n  - type: ResponseCodes\n    url: https://docs.coresignal.com/api-introduction/response-codes\n  - type: Credits\n    url: https://docs.coresignal.com/api-introduction/credits\n\
  \  - type: Webhooks\n    url: https://docs.coresignal.com/api-introduction/webhooks\n  - type: Dashboard\n    url: https://dashboard.coresignal.com/sign-in\n  - type: SignUp\n    url: https://dashboard.coresignal.com/sign-up\n  - type: Pricing\n    url: https://coresignal.com/pricing/\n  - type: Solutions\n    url: https://coresignal.com/solutions/\n  - type: UseCases\n    url: https://coresignal.com/use-cases/\n  - type: Blog\n    url: https://coresignal.com/blog/\n  - type: Vocabulary\n    url: vocabulary/coresignal-vocabulary.yml\n  - type: JSONLD\n    url: json-ld/coresignal-context.jsonld\n  - type: PrivacyPolicy\n    url: https://coresignal.com/privacy-policy/\n  - type: TermsOfService\n    url: https://coresignal.com/terms-and-conditions/\n  - type: Status\n    url: https://status.coresignal.com/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/coresignal\n  - type: Twitter\n    url: https://twitter.com/coresignal\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/coresignal/refs/heads/main/apis.yml
tags:
- Agentic Search
- B2B Data
- Companies
- Company Data
- Data as a Service
- Elasticsearch
- Employee Data
- Employees
- Enrichment
- Firmographics
- Job Postings
- Jobs
- Lead Generation
- People Data
- Sales Intelligence
- Talent Intelligence
- Web Data
url: https://raw.githubusercontent.com/api-evangelist/coresignal/refs/heads/main/apis.yml
use_cases: []
---
