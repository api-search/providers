---
api_count: 1
apis:
- description: The APIs.json specification defines a machine-readable JSON or YAML format for describing API operations. Unlike OpenAPI which describes the technical interface of a single API, APIs.json describes th
  name: APIs.json Specification
  slug: apis-json-specification
common:
- title: ''
  type: Website
  url: https://apisjson.org
- title: ''
  type: Properties
  url: https://apisjson.org/properties/
- title: ''
  type: Blog
  url: https://apisjson.org/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apis-json
- title: Specification Repository
  type: GitHubRepository
  url: https://github.com/apis-json/api-json
- title: Website
  type: GitHubRepository
  url: https://github.com/apis-json/apis-json-website
- title: Artisanal APIs.json Examples
  type: GitHubRepository
  url: https://github.com/apis-json/artisanal
- title: Backstage Integration
  type: GitHubRepository
  url: https://github.com/apis-json/backstage
- title: ''
  type: Support
  url: https://github.com/apis-json/api-json/issues
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/rules/apis-json-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/vocabulary/apis-json-vocabulary.yaml
created: '2026-03-26'
description: APIs.json is an open, machine-readable specification that API providers can use to describe their API operations, similar to how websites use sitemap.xml. The format provides a lightweight means for individuals and organizations to document the location of their APIs, associated descriptions, human and machine-readable specifications, and ancillary information such as licensing, maintainers, and terms of service. It was created by Kin Lane and Steven Willmott in May 2014 and is maintained as an open IETF-style draft. The current stable version is 0.19, published in November 2024. APIs.json files can be placed at the root of any domain as /apis.json or /apis.yml for automated discovery. The specification defines root-level fields (name, description, url, apis, common), API-level fields (aid, humanURL, baseURL, tags, properties), and a comprehensive list of property types covering documentation, authentication, licensing, support, and governance. It is the foundation for the APIs.io
  search engine and API Commons initiative.
features:
- description: Provides a machine-readable format for documenting API operations beyond just the technical interface, covering documentation, pricing, authentication, terms of service, support, and governance.
  name: Machine-Readable API Operations
- description: APIs.json files can be placed at /apis.json or /apis.yml at the root of any domain, enabling automated discovery by search engines and robots without prior knowledge of the API provider.
  name: Domain Root Discovery
- description: Defines a comprehensive enumerated set of property types (OpenAPI, Documentation, Authentication, Pricing, Support, etc.) enabling consistent machine-readable indexing of API operations.
  name: Property Type System
- description: Supports federated API directories through include references, allowing a root APIs.json to reference other APIs.json files on different servers or domains.
  name: Federation via Include
- description: A single APIs.json file can document multiple APIs in the apis array, with shared properties in the common section, enabling organization-wide API catalogs.
  name: Multiple API Collections
- description: Defines authoritative (same DNS domain) and non-authoritative entries, with conflict resolution rules giving priority to the most specific authoritative entry.
  name: Authority and Non-Authority
- description: Supports overlay specifications that can modify or extend existing APIs.json entries, enabling provider-agnostic enrichment of API metadata.
  name: Overlay Support
- description: Maintained as a versioned specification from 0.11 through current 0.19, with full version history and diff comparisons available on GitHub and apisjson.org.
  name: Version History
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: The APIs.io search engine is built entirely on the APIs.json specification, indexing submitted APIs.json files to power its API discovery and search capabilities.
  name: APIs.io
- description: API Commons uses APIs.json as its core metadata format for documenting API operations across the open API ecosystem.
  name: API Commons
- description: APIs.json references OpenAPI specifications as a core property type, linking machine-readable API interface descriptions to their operations metadata.
  name: OpenAPI
- description: APIs.json files can be imported into Spotify Backstage using the apis-json/backstage integration tool for enterprise developer portal use.
  name: Backstage
- description: Spectral rulesets can validate APIs.json files against the specification schema and enforce organizational governance rules for API operations.
  name: Spectral
- description: APIs.json supports AsyncAPI as a property type, allowing event-driven and message-based APIs to be documented alongside REST APIs in a single APIs.json file.
  name: AsyncAPI
jsonld:
- class_count: 9
  name: Apis Json Context
  property_count: 26
  slug: apis-json-context
layout: provider
modified: '2026-04-19'
name: APIs.json
rules:
- name: APIs.json API Rules
  rule_count: 34
  severity_counts:
    error: 15
    hint: 0
    info: 7
    warn: 12
  slug: apis-json-spectral-rules
skills: []
slug: apis-json
solutions: []
source_filename: apis.yml
source_yaml: "aid: apis-json\nname: APIs.json\ndescription: >-\n  APIs.json is an open, machine-readable specification that API providers can\n  use to describe their API operations, similar to how websites use sitemap.xml.\n  The format provides a lightweight means for individuals and organizations to\n  document the location of their APIs, associated descriptions, human and\n  machine-readable specifications, and ancillary information such as licensing,\n  maintainers, and terms of service. It was created by Kin Lane and Steven\n  Willmott in May 2014 and is maintained as an open IETF-style draft. The\n  current stable version is 0.19, published in November 2024. APIs.json files\n  can be placed at the root of any domain as /apis.json or /apis.yml for\n  automated discovery. The specification defines root-level fields (name,\n  description, url, apis, common), API-level fields (aid, humanURL, baseURL,\n  tags, properties), and a comprehensive list of property types covering\n  documentation,\
  \ authentication, licensing, support, and governance. It is the\n  foundation for the APIs.io search engine and API Commons initiative.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Aggregation\n  - API Cataloging\n  - API Commons\n  - API Discovery\n  - API Governance\n  - API Operations\n  - Machine Readable\n  - Specification\n  - Standard\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apis-json:apis-json-specification\n    name: APIs.json Specification\n    description: >-\n      The APIs.json specification defines a machine-readable JSON or YAML format\n      for describing API operations. Unlike OpenAPI which describes the technical\n      interface of a single API, APIs.json describes the surrounding operations\n      of one or more APIs — documentation, authentication, pricing,\
  \ terms of\n      service, support, and other properties. Created by Kin Lane and Steven\n      Willmott in May 2014, the specification is maintained as an informal IETF\n      draft at apisjson.org. The current stable version is 0.19, published\n      November 6, 2024. APIs.json files are placed at the domain root as\n      /apis.json or /apis.yml for automated discovery by robots and search\n      engines.\n    humanURL: https://apisjson.org\n    tags:\n      - API Description\n      - API Discovery\n      - API Operations\n      - Machine Readable\n      - Specification\n      - Standard\n    properties:\n      - type: Documentation\n        url: https://apisjson.org/schema/\n      - type: Specification\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/spec/apisjson_0.19.txt\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/json-schema/apis-json-schema-0.19.yaml\n\
  \        title: Schema v0.19\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/json-schema/apis-json-schema-0.18.yaml\n        title: Schema v0.18\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/json-schema/apis-json-schema-0.17.yaml\n        title: Schema v0.17\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/json-schema/apis-json-schema-0.20.yaml\n        title: Schema v0.20 (Draft)\ncommon:\n  - type: Website\n    url: https://apisjson.org\n  - type: Properties\n    url: https://apisjson.org/properties/\n  - type: Blog\n    url: https://apisjson.org/blog/\n  - type: GitHubOrganization\n    url: https://github.com/apis-json\n  - type: GitHubRepository\n    url: https://github.com/apis-json/api-json\n    title: Specification Repository\n  - type: GitHubRepository\n\
  \    url: https://github.com/apis-json/apis-json-website\n    title: Website\n  - type: GitHubRepository\n    url: https://github.com/apis-json/artisanal\n    title: Artisanal APIs.json Examples\n  - type: GitHubRepository\n    url: https://github.com/apis-json/backstage\n    title: Backstage Integration\n  - type: Support\n    url: https://github.com/apis-json/api-json/issues\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/rules/apis-json-spectral-rules.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/vocabulary/apis-json-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Machine-Readable API Operations\n        description: >-\n          Provides a machine-readable format for documenting API operations\n          beyond just the technical interface, covering documentation, pricing,\n          authentication, terms of service, support,\
  \ and governance.\n      - name: Domain Root Discovery\n        description: >-\n          APIs.json files can be placed at /apis.json or /apis.yml at the root\n          of any domain, enabling automated discovery by search engines and\n          robots without prior knowledge of the API provider.\n      - name: Property Type System\n        description: >-\n          Defines a comprehensive enumerated set of property types (OpenAPI,\n          Documentation, Authentication, Pricing, Support, etc.) enabling\n          consistent machine-readable indexing of API operations.\n      - name: Federation via Include\n        description: >-\n          Supports federated API directories through include references, allowing\n          a root APIs.json to reference other APIs.json files on different\n          servers or domains.\n      - name: Multiple API Collections\n        description: >-\n          A single APIs.json file can document multiple APIs in the apis array,\n          with shared\
  \ properties in the common section, enabling organization-wide\n          API catalogs.\n      - name: Authority and Non-Authority\n        description: >-\n          Defines authoritative (same DNS domain) and non-authoritative entries,\n          with conflict resolution rules giving priority to the most specific\n          authoritative entry.\n      - name: Overlay Support\n        description: >-\n          Supports overlay specifications that can modify or extend existing\n          APIs.json entries, enabling provider-agnostic enrichment of API metadata.\n      - name: Version History\n        description: >-\n          Maintained as a versioned specification from 0.11 through current 0.19,\n          with full version history and diff comparisons available on GitHub and\n          apisjson.org.\n  - type: UseCases\n    data:\n      - name: API Discovery\n        description: >-\n          API providers publish APIs.json files at their domain root so that\n          search engines\
  \ like APIs.io can automatically discover and index all\n          their APIs without manual submission.\n      - name: API Governance\n        description: >-\n          Platform teams use APIs.json as a canonical machine-readable index\n          of their API portfolio, enabling automated compliance checking of\n          required operational properties like terms of service and authentication.\n      - name: API Portal Generation\n        description: >-\n          Developer portals can be automatically generated from APIs.json files\n          by reading the properties array and presenting documentation, OpenAPI\n          specs, getting started guides, and other resources.\n      - name: API Commons Participation\n        description: >-\n          Organizations publish APIs.json files to participate in the API Commons\n          initiative, making their APIs discoverable and accessible to a wider\n          developer community.\n      - name: Internal API Catalog\n        description:\
  \ >-\n          Enterprises use APIs.json as the foundation for internal API catalogs,\n          enabling discoverability of internal, partner, and public APIs using\n          a consistent machine-readable format.\n      - name: Backstage Integration\n        description: >-\n          Teams use the APIs.json Backstage integration to import API metadata\n          from APIs.json files into Spotify Backstage for internal developer\n          portal use.\n  - type: Integrations\n    data:\n      - name: APIs.io\n        description: >-\n          The APIs.io search engine is built entirely on the APIs.json\n          specification, indexing submitted APIs.json files to power its\n          API discovery and search capabilities.\n      - name: API Commons\n        description: >-\n          API Commons uses APIs.json as its core metadata format for documenting\n          API operations across the open API ecosystem.\n      - name: OpenAPI\n        description: >-\n          APIs.json references\
  \ OpenAPI specifications as a core property type,\n          linking machine-readable API interface descriptions to their operations\n          metadata.\n      - name: Backstage\n        description: >-\n          APIs.json files can be imported into Spotify Backstage using the\n          apis-json/backstage integration tool for enterprise developer portal use.\n      - name: Spectral\n        description: >-\n          Spectral rulesets can validate APIs.json files against the specification\n          schema and enforce organizational governance rules for API operations.\n      - name: AsyncAPI\n        description: >-\n          APIs.json supports AsyncAPI as a property type, allowing event-driven\n          and message-based APIs to be documented alongside REST APIs in a single\n          APIs.json file.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/apis.yml
tags:
- API Aggregation
- API Cataloging
- API Commons
- API Discovery
- API Governance
- API Operations
- Machine Readable
- Specification
- Standard
url: https://raw.githubusercontent.com/api-evangelist/apis-json/refs/heads/main/apis.yml
use_cases:
- description: API providers publish APIs.json files at their domain root so that search engines like APIs.io can automatically discover and index all their APIs without manual submission.
  name: API Discovery
- description: Platform teams use APIs.json as a canonical machine-readable index of their API portfolio, enabling automated compliance checking of required operational properties like terms of service and authentication.
  name: API Governance
- description: Developer portals can be automatically generated from APIs.json files by reading the properties array and presenting documentation, OpenAPI specs, getting started guides, and other resources.
  name: API Portal Generation
- description: Organizations publish APIs.json files to participate in the API Commons initiative, making their APIs discoverable and accessible to a wider developer community.
  name: API Commons Participation
- description: Enterprises use APIs.json as the foundation for internal API catalogs, enabling discoverability of internal, partner, and public APIs using a consistent machine-readable format.
  name: Internal API Catalog
- description: Teams use the APIs.json Backstage integration to import API metadata from APIs.json files into Spotify Backstage for internal developer portal use.
  name: Backstage Integration
---
