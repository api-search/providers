---
api_count: 6
api_specs:
- filename: uspto-patent-api-openapi.yml
  format: yaml
  label: USPTO Patent & Trademark API
  slug: patent-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uspto/refs/heads/main/openapi/uspto-patent-api-openapi.yml
- filename: index.html
  format: yaml
  label: USPTO Patent Trial and Appeal Board (PTAB) API
  slug: ptab-api
  spec_type: OpenAPI
  url: https://data.uspto.gov/swagger/index.html
- filename: tsdr-api-v1
  format: yaml
  label: USPTO Trademark Status and Document Retrieval (TSDR) API
  slug: tsdr-api
  spec_type: OpenAPI
  url: https://developer.uspto.gov/swagger/tsdr-api-v1
- filename: oa_actions.json
  format: json
  label: USPTO Office Action Text Retrieval API
  slug: office-actions-api
  spec_type: OpenAPI
  url: https://developer.uspto.gov/ds-api/swagger/docs/oa_actions.json
- filename: enriched_cited_reference_metadata.json
  format: json
  label: USPTO Enriched Citation API
  slug: enriched-citation-api
  spec_type: OpenAPI
  url: https://developer.uspto.gov/ds-api/swagger/docs/enriched_cited_reference_metadata.json
apis:
- description: The United States Patent and Trademark Office (USPTO) provides REST APIs for patent search, PTAB trial proceedings, trademark status lookup, and patent citation data. APIs are hosted at developer.uspt
  name: USPTO Patent & Trademark API
  slug: patent-api
- description: 'The USPTO PTAB API provides access to Patent Trial and Appeal Board proceedings data including inter partes reviews (IPR), post-grant reviews (PGR), and covered business method (CBM) reviews. Returns '
  name: USPTO Patent Trial and Appeal Board (PTAB) API
  slug: ptab-api
- description: The USPTO Trademark Status and Document Retrieval (TSDR) API enables programmatic access to trademark case status, filing history, and associated documents. Returns status information for trademark ap
  name: USPTO Trademark Status and Document Retrieval (TSDR) API
  slug: tsdr-api
- description: The USPTO Patent Assignment Search API retrieves patent assignment information including ownership transfers, recorded assignments, and assignment history for individual patents and patent portfolios.
  name: USPTO Patent Assignment Search API
  slug: assignment-search-api
- description: The USPTO Office Action Text Retrieval API provides access to the full text of USPTO patent examiner office actions. Returns rejection text, claims analysis, and prior art citations for patent applica
  name: USPTO Office Action Text Retrieval API
  slug: office-actions-api
- description: The USPTO Enriched Citation API provides enriched citation reference metadata for patent documents including non-patent literature and patent citations. Returns structured citation data for patent ana
  name: USPTO Enriched Citation API
  slug: enriched-citation-api
capabilities:
- description: Workflow capability for patent and trademark research using USPTO Open Data Portal APIs. Supports IP attorneys, patent engineers, researchers, and business analysts conducting prior art searches, pate
  name: USPTO Patent Research
  slug: patent-research
common:
- title: ''
  type: Portal
  url: https://developer.uspto.gov/
- title: ''
  type: Documentation
  url: https://developer.uspto.gov/
- title: ''
  type: GettingStarted
  url: https://developer.uspto.gov/api-catalog
- title: ''
  type: DeveloperTools
  url: https://data.uspto.gov/
- title: ''
  type: PrivacyPolicy
  url: https://www.uspto.gov/privacy-policy
- title: ''
  type: Website
  url: https://www.uspto.gov/
- title: ''
  type: JSONSchema
  url: json-schema/uspto-patent-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/uspto-context.jsonld
- title: ''
  type: JSONStructure
  url: json-structure/uspto-patent-structure.json
- title: ''
  type: SpectralRules
  url: rules/uspto-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/uspto-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/patent-research.yaml
created: '2025-01-01'
description: The United States Patent and Trademark Office (USPTO) is the federal agency responsible for granting U.S. patents and registering trademarks. USPTO provides a suite of developer APIs through the Open Data Portal (developer.uspto.gov) and data.uspto.gov for programmatic access to patent applications, granted patents, PTAB trial proceedings, trademark status, patent assignments, office actions, and citation data. All USPTO APIs are open government data and return JSON and XML responses. An ODP API key is required for most endpoints.
features: []
image: https://www.uspto.gov/sites/default/files/USPTO_Logo.png
integrations: []
jsonld:
- class_count: 24
  name: Uspto Context
  property_count: 7
  slug: uspto-context
layout: provider
modified: '2026-05-03'
name: USPTO
rules:
- name: USPTO API Rules
  rule_count: 20
  severity_counts:
    error: 8
    hint: 0
    info: 3
    warn: 9
  slug: uspto-rules
skills: []
slug: uspto
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: uspto\nname: USPTO\ndescription: >-\n  The United States Patent and Trademark Office (USPTO) is the federal agency\n  responsible for granting U.S. patents and registering trademarks. USPTO provides\n  a suite of developer APIs through the Open Data Portal (developer.uspto.gov) and\n  data.uspto.gov for programmatic access to patent applications, granted patents,\n  PTAB trial proceedings, trademark status, patent assignments, office actions, and\n  citation data. All USPTO APIs are open government data and return JSON and XML\n  responses. An ODP API key is required for most endpoints.\ntype: Index\nimage: https://www.uspto.gov/sites/default/files/USPTO_Logo.png\ntags:\n  - Government\n  - Intellectual Property\n  - Open Data\n  - Patents\n  - Regulatory\n  - Trademarks\n  - USPTO\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/uspto/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: uspto:patent-api\n\
  \    name: USPTO Patent & Trademark API\n    description: >-\n      The United States Patent and Trademark Office (USPTO) provides REST APIs for\n      patent search, PTAB trial proceedings, trademark status lookup, and patent\n      citation data. APIs are hosted at developer.uspto.gov and data.uspto.gov.\n      An ODP API key is required for most endpoints.\n    tags:\n      - Assignments\n      - Government\n      - Patents\n      - PTAB\n      - Regulatory\n      - Trademarks\n    humanURL: https://developer.uspto.gov/\n    baseURL: https://data.uspto.gov/api/v1\n    properties:\n      - type: Documentation\n        url: https://developer.uspto.gov/\n      - type: Reference\n        url: https://developer.uspto.gov/api-catalog\n      - type: OpenAPI\n        url: openapi/uspto-patent-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/uspto-patent-schema.json\n\n  - aid: uspto:ptab-api\n    name: USPTO Patent Trial and Appeal Board (PTAB) API\n    description: >-\n\
  \      The USPTO PTAB API provides access to Patent Trial and Appeal Board proceedings\n      data including inter partes reviews (IPR), post-grant reviews (PGR), and covered\n      business method (CBM) reviews. Returns trial status, petitions, decisions, and\n      related documents.\n    tags:\n      - Government\n      - PTAB\n      - Patents\n      - Regulatory\n    humanURL: https://data.uspto.gov/ptab\n    properties:\n      - type: Documentation\n        url: https://data.uspto.gov/ptab\n      - type: OpenAPI\n        url: https://data.uspto.gov/swagger/index.html\n\n  - aid: uspto:tsdr-api\n    name: USPTO Trademark Status and Document Retrieval (TSDR) API\n    description: >-\n      The USPTO Trademark Status and Document Retrieval (TSDR) API enables programmatic\n      access to trademark case status, filing history, and associated documents.\n      Returns status information for trademark applications and registrations.\n    tags:\n      - Government\n      - Regulatory\n \
  \     - Trademarks\n    humanURL: https://developer.uspto.gov/swagger/tsdr-api-v1\n    properties:\n      - type: Documentation\n        url: https://developer.uspto.gov/swagger/tsdr-api-v1\n      - type: OpenAPI\n        url: https://developer.uspto.gov/swagger/tsdr-api-v1\n\n  - aid: uspto:assignment-search-api\n    name: USPTO Patent Assignment Search API\n    description: >-\n      The USPTO Patent Assignment Search API retrieves patent assignment information\n      including ownership transfers, recorded assignments, and assignment history for\n      individual patents and patent portfolios.\n    tags:\n      - Assignments\n      - Government\n      - Patents\n      - Regulatory\n    humanURL: https://developer.uspto.gov/api-catalog\n    properties:\n      - type: Documentation\n        url: https://developer.uspto.gov/api-catalog\n\n  - aid: uspto:office-actions-api\n    name: USPTO Office Action Text Retrieval API\n    description: >-\n      The USPTO Office Action Text Retrieval\
  \ API provides access to the full text\n      of USPTO patent examiner office actions. Returns rejection text, claims analysis,\n      and prior art citations for patent applications under examination.\n    tags:\n      - Government\n      - Office Actions\n      - Patents\n      - Regulatory\n    humanURL: https://developer.uspto.gov/ds-api-docs/index.html?url=https%3A//developer.uspto.gov/ds-api/swagger/docs/oa_actions.json\n    properties:\n      - type: Documentation\n        url: https://developer.uspto.gov/ds-api-docs/index.html?url=https%3A//developer.uspto.gov/ds-api/swagger/docs/oa_actions.json\n      - type: OpenAPI\n        url: https://developer.uspto.gov/ds-api/swagger/docs/oa_actions.json\n\n  - aid: uspto:enriched-citation-api\n    name: USPTO Enriched Citation API\n    description: >-\n      The USPTO Enriched Citation API provides enriched citation reference metadata\n      for patent documents including non-patent literature and patent citations.\n      Returns structured\
  \ citation data for patent analysis, competitive intelligence,\n      and IP research.\n    tags:\n      - Citations\n      - Government\n      - Patents\n      - Regulatory\n    humanURL: https://developer.uspto.gov/ds-api-docs/index.html?url=https%3A//developer.uspto.gov/ds-api/swagger/docs/enriched_cited_reference_metadata.json/V3\n    properties:\n      - type: Documentation\n        url: https://developer.uspto.gov/ds-api-docs/index.html?url=https%3A//developer.uspto.gov/ds-api/swagger/docs/enriched_cited_reference_metadata.json/V3\n      - type: OpenAPI\n        url: https://developer.uspto.gov/ds-api/swagger/docs/enriched_cited_reference_metadata.json\n\ncommon:\n  - type: Portal\n    url: https://developer.uspto.gov/\n  - type: Documentation\n    url: https://developer.uspto.gov/\n  - type: GettingStarted\n    url: https://developer.uspto.gov/api-catalog\n  - type: DeveloperTools\n    url: https://data.uspto.gov/\n  - type: PrivacyPolicy\n    url: https://www.uspto.gov/privacy-policy\n\
  \  - type: Website\n    url: https://www.uspto.gov/\n  - type: JSONSchema\n    url: json-schema/uspto-patent-schema.json\n  - type: JSONLDContext\n    url: json-ld/uspto-context.jsonld\n  - type: JSONStructure\n    url: json-structure/uspto-patent-structure.json\n  - type: SpectralRules\n    url: rules/uspto-rules.yml\n  - type: Vocabulary\n    url: vocabulary/uspto-vocabulary.yml\n  - type: NaftikoCapability\n    url: capabilities/patent-research.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/uspto/refs/heads/main/apis.yml
tags:
- Government
- Intellectual Property
- Open Data
- Patents
- Regulatory
- Trademarks
- USPTO
url: https://raw.githubusercontent.com/api-evangelist/uspto/refs/heads/main/apis.yml
use_cases: []
---
