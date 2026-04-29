---
api_count: 1
api_specs:
- filename: crunchbase-openapi.yml
  format: yaml
  label: Crunchbase API
  slug: crunchbase-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/crunchbase/refs/heads/main/openapi/crunchbase-openapi.yml
apis:
- description: The Crunchbase v4 REST API provides programmatic access to Crunchbase's business data covering organizations, people, investors, funding rounds, acquisitions, and IPOs. Supports entity lookups, struct
  name: Crunchbase API
  slug: crunchbase-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.crunchbase.com/
- title: ''
  type: Documentation
  url: https://data.crunchbase.com/docs
- title: ''
  type: SignUp
  url: https://www.crunchbase.com/register
- title: ''
  type: Login
  url: https://www.crunchbase.com/login
- title: ''
  type: Pricing
  url: https://www.crunchbase.com/pricing
- title: ''
  type: Authentication
  url: https://data.crunchbase.com/docs/authentication
- title: ''
  type: RateLimits
  url: https://data.crunchbase.com/docs/rate-limiting
- title: ''
  type: ChangeLog
  url: https://data.crunchbase.com/docs/changelog
- title: ''
  type: Support
  url: https://support.crunchbase.com/
- title: ''
  type: TermsOfService
  url: https://www.crunchbase.com/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.crunchbase.com/privacy-policy
- title: ''
  type: Blog
  url: https://www.crunchbase.com/blog
- title: ''
  type: X
  url: https://twitter.com/crunchbase
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/crunchbase
- title: ''
  type: Facebook
  url: https://www.facebook.com/crunchbase
- title: ''
  type: GitHub
  url: https://github.com/crunchbase
- title: ''
  type: OpenAPI
  url: openapi/crunchbase-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/crunchbase-organization-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/crunchbase-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/crunchbase-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/crunchbase-vocabulary.yml
created: '2026-03-24'
description: Crunchbase is a business data platform tracking companies, investors, funding rounds, acquisitions, and IPOs across the global startup and private market ecosystem. Its REST API (v4) provides programmatic access to over 600 endpoints powering customer-facing products, workflow enrichment, and AI training data.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 18
  name: Crunchbase Context
  property_count: 9
  slug: crunchbase-context
layout: provider
modified: '2026-04-28'
name: Crunchbase
rules:
- name: Crunchbase API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 5
  slug: crunchbase-rules
skills: []
slug: crunchbase
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: crunchbase\nurl: https://raw.githubusercontent.com/api-evangelist/crunchbase/refs/heads/main/apis.yml\nx-type: company\nname: Crunchbase\ndescription: >-\n  Crunchbase is a business data platform tracking companies, investors, funding\n  rounds, acquisitions, and IPOs across the global startup and private market\n  ecosystem. Its REST API (v4) provides programmatic access to over 600\n  endpoints powering customer-facing products, workflow enrichment, and AI\n  training data.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Business Data\n  - Funding\n  - Investments\n  - Startups\n  - Private Markets\n  - Firmographics\ntype: Index\naccess: 3rd-Party\nspecificationVersion: '0.19'\ncreated: '2026-03-24'\nmodified: '2026-04-28'\napis:\n  - aid: crunchbase:crunchbase-api\n    name: Crunchbase API\n    description: >-\n      The Crunchbase v4 REST API provides programmatic access to Crunchbase's\n      business data covering organizations,\
  \ people, investors, funding rounds,\n      acquisitions, and IPOs. Supports entity lookups, structured search,\n      autocomplete, and deleted entity feeds. Authentication is by API key\n      (X-cb-user-key header).\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.crunchbase.com/api/v4\n    humanURL: https://data.crunchbase.com/docs\n    tags:\n      - Business Data\n      - Funding\n      - Investments\n      - Startups\n      - REST\n    properties:\n      - url: https://data.crunchbase.com/docs\n        type: Documentation\n      - url: https://data.crunchbase.com/docs/authentication\n        type: Authentication\n      - url: https://data.crunchbase.com/docs/rate-limiting\n        type: RateLimits\n      - url: https://data.crunchbase.com/docs/changelog\n        type: ChangeLog\n      - url: openapi/crunchbase-openapi.yml\n        type: OpenAPI\n      - url: json-schema/crunchbase-organization-schema.json\n        type:\
  \ JSONSchema\n      - url: json-ld/crunchbase-context.jsonld\n        type: JSONLDContext\nfeatures:\n  - name: Entity Lookups\n    description: Retrieve organizations, people, funding rounds, acquisitions, and IPOs by UUID or permalink.\n  - name: Structured Search\n    description: POST-based search with field, operator, and value clauses across all entity types.\n  - name: Autocomplete\n    description: Type-ahead lookups for entities by name across collections.\n  - name: Deleted Entity Feeds\n    description: Track removed entities for incremental data synchronization.\n  - name: Field Selection\n    description: Request specific fields and related cards (founders, investments, headquarters) per entity.\n  - name: 600+ Endpoints\n    description: Round-by-round funding data, firmographics, and predictive intelligence covering private markets.\n  - name: API Key Authentication\n    description: Header-based API key auth using X-cb-user-key.\n  - name: Rate Limited\n    description:\
  \ Per-key rate limits documented at data.crunchbase.com/docs/rate-limiting.\nuseCases:\n  - name: Market Intelligence\n    description: Analysts track competitor funding, growth, and acquisition activity.\n  - name: Investor Research\n    description: VCs and PE firms research portfolio companies, comparable rounds, and lead investors.\n  - name: Sales Intelligence and ABM\n    description: Sales teams enrich CRM records with firmographics, funding, and headcount data.\n  - name: Startup Discovery\n    description: Accelerators and corp-dev teams search for organizations matching specific criteria.\n  - name: AI Model Training\n    description: Foundation model and analytics teams use Crunchbase data to train and evaluate models.\n  - name: Customer-Facing Products\n    description: SaaS products embed Crunchbase data into dashboards, lead lists, and signals.\ncommon:\n  - url: https://www.crunchbase.com/\n    name: Crunchbase Website\n    type: Website\n  - url: https://data.crunchbase.com/docs\n\
  \    name: API Documentation\n    type: Documentation\n  - url: https://www.crunchbase.com/register\n    name: Sign Up\n    type: SignUp\n  - url: https://www.crunchbase.com/login\n    name: Login\n    type: Login\n  - url: https://www.crunchbase.com/pricing\n    name: Pricing\n    type: Pricing\n  - url: https://data.crunchbase.com/docs/authentication\n    name: Authentication\n    type: Authentication\n  - url: https://data.crunchbase.com/docs/rate-limiting\n    name: Rate Limiting\n    type: RateLimits\n  - url: https://data.crunchbase.com/docs/changelog\n    name: Changelog\n    type: ChangeLog\n  - url: https://support.crunchbase.com/\n    name: Support\n    type: Support\n  - url: https://www.crunchbase.com/terms-of-service\n    name: Terms of Service\n    type: TermsOfService\n  - url: https://www.crunchbase.com/privacy-policy\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://www.crunchbase.com/blog\n    name: Crunchbase Blog\n    type: Blog\n  - url: https://twitter.com/crunchbase\n\
  \    name: Crunchbase on X (Twitter)\n    type: X\n  - url: https://www.linkedin.com/company/crunchbase\n    name: Crunchbase on LinkedIn\n    type: LinkedIn\n  - url: https://www.facebook.com/crunchbase\n    name: Crunchbase on Facebook\n    type: Facebook\n  - url: https://github.com/crunchbase\n    name: Crunchbase on GitHub\n    type: GitHub\n  - url: openapi/crunchbase-openapi.yml\n    type: OpenAPI\n  - url: json-schema/crunchbase-organization-schema.json\n    type: JSONSchema\n  - url: json-ld/crunchbase-context.jsonld\n    type: JSONLDContext\n  - url: rules/crunchbase-rules.yml\n    type: SpectralRules\n  - url: vocabulary/crunchbase-vocabulary.yml\n    type: Vocabulary\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/crunchbase/refs/heads/main/apis.yml
tags:
- Business Data
- Funding
- Investments
- Startups
- Private Markets
- Firmographics
url: https://raw.githubusercontent.com/api-evangelist/crunchbase/refs/heads/main/apis.yml
use_cases: []
---
