---
api_count: 2
api_specs:
- filename: seamless-ai-contacts-openapi.yml
  format: yaml
  label: Seamless.AI Contacts API
  slug: seamless-ai-contacts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seamless-ai/refs/heads/main/openapi/seamless-ai-contacts-openapi.yml
- filename: seamless-ai-companies-openapi.yml
  format: yaml
  label: Seamless.AI Companies API
  slug: seamless-ai-companies-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/seamless-ai/refs/heads/main/openapi/seamless-ai-companies-openapi.yml
apis:
- description: The Seamless.AI Contacts API provides programmatic access to contact search, enrichment, and research capabilities. Search for B2B contacts by name, company, title, and location. Enrich existing conta
  name: Seamless.AI Contacts API
  slug: seamless-ai-contacts-api
- description: 'The Seamless.AI Companies API enables programmatic search and research of company data including firmographics, revenue, employee count, technology stack, and company intelligence. Use company search '
  name: Seamless.AI Companies API
  slug: seamless-ai-companies-api
capabilities:
- description: Unified sales prospecting capability combining Seamless.AI contact and company APIs for end-to-end B2B prospecting workflows. Enables sales teams to search and discover target contacts, enrich CRM rec
  name: Seamless.AI Sales Prospecting
  slug: sales-prospecting
common:
- title: ''
  type: Website
  url: https://seamless.ai
- title: ''
  type: Documentation
  url: https://docs.seamless.ai/
- title: ''
  type: Overview
  url: https://seamless.ai/products/api
- title: ''
  type: GettingStarted
  url: https://seamless.ai/customers/education/articles/seamless-ai-api-overview
- title: ''
  type: Glossary
  url: https://seamless.ai/customers/education/articles/api-terms-glossary
- title: ''
  type: Blog
  url: https://seamless.ai/news/releases/api
- title: ''
  type: JSONSchema
  url: json-schema/seamless-ai-contact-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/seamless-ai-company-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/seamless-ai-contact-structure.json
- title: ''
  type: JSONLDContext
  url: json-ld/seamless-ai-context.jsonld
- title: ''
  type: Example
  url: examples/seamless-ai-search-contacts-example.json
- title: ''
  type: SpectralRuleset
  url: rules/seamless-ai-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/sales-prospecting.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/seamless-ai-vocabulary.yml
created: '2026-05-02'
description: Seamless.AI is a B2B sales intelligence platform that provides real-time contact and company data to help sales teams find and connect with their ideal customers. The platform uses artificial intelligence to continuously verify and update contact information including emails, direct dials, and mobile numbers. Seamless.AI offers a RESTful API secured with OAuth 2.0 and API key authentication, enabling developers to integrate contact search, company search, enrichment, and job-change intelligence directly into CRM systems, marketing platforms, and internal sales tools.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 19
  name: Seamless Ai Context
  property_count: 4
  slug: seamless-ai-context
layout: provider
modified: '2026-05-02'
name: Seamless.AI
rules:
- name: Seamless.AI API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 4
  slug: seamless-ai-rules
skills: []
slug: seamless-ai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: seamless-ai\nurl: https://raw.githubusercontent.com/api-evangelist/seamless-ai/refs/heads/main/apis.yml\napis:\n  - aid: seamless-ai:seamless-ai-contacts-api\n    name: Seamless.AI Contacts API\n    tags:\n      - Contacts\n      - Sales Intelligence\n      - B2B\n      - Prospecting\n    humanURL: https://docs.seamless.ai/\n    baseURL: https://api.seamless.ai\n    properties:\n      - url: openapi/seamless-ai-contacts-openapi.yml\n        type: OpenAPI\n      - url: https://docs.seamless.ai/\n        type: Documentation\n    description: >-\n      The Seamless.AI Contacts API provides programmatic access to contact search,\n      enrichment, and research capabilities. Search for B2B contacts by name, company,\n      title, and location. Enrich existing contact records with emails, phone numbers,\n      and job history. Access job-change intelligence to identify contacts that have\n      recently changed roles.\n\n  - aid: seamless-ai:seamless-ai-companies-api\n    name:\
  \ Seamless.AI Companies API\n    tags:\n      - Companies\n      - Firmographics\n      - Sales Intelligence\n      - B2B\n    humanURL: https://docs.seamless.ai/\n    baseURL: https://api.seamless.ai\n    properties:\n      - url: openapi/seamless-ai-companies-openapi.yml\n        type: OpenAPI\n      - url: https://docs.seamless.ai/\n        type: Documentation\n    description: >-\n      The Seamless.AI Companies API enables programmatic search and research of company\n      data including firmographics, revenue, employee count, technology stack, and\n      company intelligence. Use company search result IDs or direct identifiers such\n      as domain or company name to retrieve comprehensive company profiles.\n\nname: Seamless.AI\ntags:\n  - B2B\n  - Contact Data\n  - Sales Intelligence\n  - Prospecting\n  - Lead Generation\n  - CRM Enrichment\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-05-02'\nmodified:\
  \ '2026-05-02'\nposition: Consuming\ndescription: >-\n  Seamless.AI is a B2B sales intelligence platform that provides real-time contact\n  and company data to help sales teams find and connect with their ideal customers.\n  The platform uses artificial intelligence to continuously verify and update contact\n  information including emails, direct dials, and mobile numbers. Seamless.AI offers\n  a RESTful API secured with OAuth 2.0 and API key authentication, enabling developers\n  to integrate contact search, company search, enrichment, and job-change intelligence\n  directly into CRM systems, marketing platforms, and internal sales tools.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: Website\n    url: https://seamless.ai\n    type: Website\n  - name: API Documentation\n    url: https://docs.seamless.ai/\n    type: Documentation\n  - name: API Overview\n    url: https://seamless.ai/products/api\n    type: Overview\n\
  \  - name: Getting Started\n    url: https://seamless.ai/customers/education/articles/seamless-ai-api-overview\n    type: GettingStarted\n  - name: API Terms Glossary\n    url: https://seamless.ai/customers/education/articles/api-terms-glossary\n    type: Glossary\n  - name: CRM Enrichment\n    url: https://seamless.ai/news/releases/api\n    type: Blog\n  - url: json-schema/seamless-ai-contact-schema.json\n    type: JSONSchema\n  - url: json-schema/seamless-ai-company-schema.json\n    type: JSONSchema\n  - url: json-structure/seamless-ai-contact-structure.json\n    type: JSONStructure\n  - url: json-ld/seamless-ai-context.jsonld\n    type: JSONLDContext\n  - url: examples/seamless-ai-search-contacts-example.json\n    type: Example\n  - url: rules/seamless-ai-rules.yml\n    type: SpectralRuleset\n  - url: capabilities/sales-prospecting.yaml\n    type: NaftikoCapability\n  - url: vocabulary/seamless-ai-vocabulary.yml\n    type: Vocabulary\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/seamless-ai/refs/heads/main/apis.yml
tags:
- B2B
- Contact Data
- Sales Intelligence
- Prospecting
- Lead Generation
- CRM Enrichment
url: https://raw.githubusercontent.com/api-evangelist/seamless-ai/refs/heads/main/apis.yml
use_cases: []
---
