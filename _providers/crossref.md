---
api_count: 1
api_specs:
- filename: crossref-openapi.yml
  format: yaml
  label: Crossref REST API
  slug: crossref-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/crossref/refs/heads/main/openapi/crossref-openapi.yml
apis:
- description: The Crossref REST API is a public, read-only metadata API that provides programmatic access to Crossref's database of scholarly content. Endpoints expose works, journals, members, funders, types, lice
  name: Crossref REST API
  slug: crossref-rest-api
capabilities: []
common:
- title: ''
  type: Vocabulary
  url: vocabulary/crossref-vocabulary.yml
- title: ''
  type: JSONLD
  url: json-ld/crossref-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/crossref-work-schema.json
- title: ''
  type: Website
  url: https://www.crossref.org/
- title: ''
  type: Documentation
  url: https://www.crossref.org/documentation/
- title: ''
  type: APIDocumentation
  url: https://www.crossref.org/documentation/retrieve-metadata/rest-api/
- title: ''
  type: Blog
  url: https://www.crossref.org/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/CrossRef
- title: ''
  type: StatusPage
  url: https://status.crossref.org/
- title: ''
  type: Community
  url: https://community.crossref.org/
- title: ''
  type: TermsOfService
  url: https://www.crossref.org/operations-and-sustainability/terms/
created: '2024-07-02'
description: Crossref is a non-profit organization that provides digital infrastructure for scholarly communications. Best known for Digital Object Identifier (DOI) registration, Crossref also operates a public REST API offering searchable, filterable access to metadata for tens of millions of scholarly works, journals, members, funders, prefixes, types, licenses, and DOI registration agency information. The Crossref REST API supports free-form queries, field queries, filters, facets, deep-paging cursors, and selection of specific elements, and is used by reference managers, repositories, discovery layers, and analytics platforms.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 36
  name: Crossref Context
  property_count: 12
  slug: crossref-context
layout: provider
modified: '2026-04-28'
name: Crossref
rules:
- name: Crossref API Rules
  rule_count: 6
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 1
  slug: crossref-rules
skills: []
slug: crossref
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: crossref\nname: Crossref\nx-type: company\ndescription: >-\n  Crossref is a non-profit organization that provides digital infrastructure\n  for scholarly communications. Best known for Digital Object Identifier\n  (DOI) registration, Crossref also operates a public REST API offering\n  searchable, filterable access to metadata for tens of millions of\n  scholarly works, journals, members, funders, prefixes, types, licenses,\n  and DOI registration agency information. The Crossref REST API supports\n  free-form queries, field queries, filters, facets, deep-paging cursors,\n  and selection of specific elements, and is used by reference managers,\n  repositories, discovery layers, and analytics platforms.\nurl: https://raw.githubusercontent.com/api-evangelist/crossref/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Citations\n  - DOI\n  - Funders\n  - Identifiers\n  - Journals\n  - Licenses\n  - Members\n\
  \  - Metadata\n  - Open Access\n  - ORCID\n  - Prefixes\n  - Publishers\n  - Reference Linking\n  - ROR\n  - Scholarly\ncreated: '2024-07-02'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntype: Index\naccess: Public\nposition: Provider\napis:\n  - aid: crossref:crossref-rest-api\n    name: Crossref REST API\n    description: >-\n      The Crossref REST API is a public, read-only metadata API that\n      provides programmatic access to Crossref's database of scholarly\n      content. Endpoints expose works, journals, members, funders, types,\n      licenses, prefixes, and DOI registration agency lookups, with rich\n      query, filter, facet, sort, select, and cursor-based deep paging\n      capabilities. No sign-up is required, but consumers are encouraged\n      to use the polite pool by including a mailto query parameter or\n      User-Agent contact for higher reliability.\n    humanURL: https://www.crossref.org/documentation/retrieve-metadata/rest-api/\n    baseURL: https://api.crossref.org\n\
  \    properties:\n      - type: Documentation\n        url: https://www.crossref.org/documentation/retrieve-metadata/rest-api/\n      - type: SwaggerUI\n        url: https://api.crossref.org/swagger-ui/\n      - type: PolitePool\n        url: https://www.crossref.org/documentation/retrieve-metadata/rest-api/tips-for-using-the-crossref-rest-api/#etiquette\n      - type: Tips\n        url: https://www.crossref.org/documentation/retrieve-metadata/rest-api/tips-for-using-the-crossref-rest-api/\n      - type: OpenAPI\n        url: openapi/crossref-openapi.yml\n      - type: Rules\n        url: rules/crossref-rules.yml\n      - type: Capabilities\n        url: capabilities/crossref-capabilities.yml\n      - type: JSONSchema\n        url: json-schema/crossref-work-schema.json\n      - type: JSONLD\n        url: json-ld/crossref-context.jsonld\n    tags:\n      - Agency\n      - Funders\n      - Journals\n      - Licenses\n      - Members\n      - Metadata\n      - Prefixes\n      - Types\n  \
  \    - Works\ncommon:\n  - type: Vocabulary\n    url: vocabulary/crossref-vocabulary.yml\n  - type: JSONLD\n    url: json-ld/crossref-context.jsonld\n  - type: JSONSchema\n    url: json-schema/crossref-work-schema.json\n  - type: Website\n    url: https://www.crossref.org/\n  - type: Documentation\n    url: https://www.crossref.org/documentation/\n  - type: APIDocumentation\n    url: https://www.crossref.org/documentation/retrieve-metadata/rest-api/\n  - type: Blog\n    url: https://www.crossref.org/blog/\n  - type: GitHubOrganization\n    url: https://github.com/CrossRef\n  - type: StatusPage\n    url: https://status.crossref.org/\n  - type: Community\n    url: https://community.crossref.org/\n  - type: TermsOfService\n    url: https://www.crossref.org/operations-and-sustainability/terms/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/crossref/refs/heads/main/apis.yml
tags:
- Citations
- DOI
- Funders
- Identifiers
- Journals
- Licenses
- Members
- Metadata
- Open Access
- ORCID
- Prefixes
- Publishers
- Reference Linking
- ROR
- Scholarly
url: https://raw.githubusercontent.com/api-evangelist/crossref/refs/heads/main/apis.yml
use_cases: []
---
