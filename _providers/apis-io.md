---
api_count: 1
api_specs:
- filename: apis-io-search-openapi.yaml
  format: yaml
  label: APIs.io Search API
  slug: search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/openapi/apis-io-search-openapi.yaml
apis:
- description: The APIs.io Search API allows developers to search for APIs across all indexed APIs.json files using keywords or phrases, and to submit new APIs to the index by providing a valid APIs.json document. T
  name: APIs.io Search API
  slug: search-api
capabilities:
- description: 'Workflow capability for searching, discovering, and submitting APIs using the APIs.io search engine. Enables developers and platform engineers to programmatically find APIs by keyword across the full '
  name: APIs.io API Discovery and Search
  slug: api-discovery-search
common:
- title: ''
  type: Website
  url: https://apis.io
- title: ''
  type: About
  url: https://apis.io/about/
- title: ''
  type: Blog
  url: https://apis.io/blog/
- title: ''
  type: DeveloperPortal
  url: https://developer.apis.io/
- title: Developer Blog
  type: Blog
  url: https://developer.apis.io/blog/
- title: ''
  type: GettingStarted
  url: https://developer.apis.io/getting-started/
- title: ''
  type: Authentication
  url: https://developer.apis.io/authentication/
- title: ''
  type: Plans
  url: https://developer.apis.io/plans/
- title: ''
  type: ChangeLog
  url: https://developer.apis.io/change-log/
- title: ''
  type: ReleaseNotes
  url: https://developer.apis.io/change-log/
- title: ''
  type: Versioning
  url: https://developer.apis.io/versioning/
- title: ''
  type: Support
  url: https://developer.apis.io/support/
- title: ''
  type: TermsOfService
  url: https://developer.apis.io/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://developer.apis.io/privacy-policy/
- title: ''
  type: GitHubOrganization
  url: https://github.com/api-search
- title: ''
  type: GitHubRepository
  url: https://github.com/apisio/apis.io
- title: Search API
  type: GitHubRepository
  url: https://github.com/api-search/apis-io-search
- title: Search Engine
  type: GitHubRepository
  url: https://github.com/api-search/apis-io-engine
- title: Authentication API
  type: GitHubRepository
  url: https://github.com/api-search/apis-io-authentication
- title: Ratings API
  type: GitHubRepository
  url: https://github.com/api-search/apis-io-ratings
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/rules/apis-io-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/vocabulary/apis-io-vocabulary.yaml
- title: API Discovery and Search Capability
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/capabilities/api-discovery-search.yaml
created: '2026-03-26'
description: APIs.io is an open source API search engine and directory that uses APIs.json files to discover, index, and catalog APIs across the web. Built on the APIs.json specification, it provides a searchable entry point for developers to find public APIs by keyword, resource, action, persona, domain, and schema. The platform indexes 779 providers, 3,188 APIs, 587 capabilities, 36,602 schemas, 49 event specs, 2,078 vocabularies, and 450 rulesets. It is maintained by Kin Lane, Nicolas Grenier, and Steven Willmott and supports both API producers (submitting APIs) and API consumers (discovering APIs). APIs.io uses a Spectral-powered rating system to evaluate API documentation quality.
features:
- description: Full-text search across 3,000+ indexed APIs by keyword, resource, action, persona, domain, and schema using a cloud search engine.
  name: API Search
- description: Automatically indexes APIs.json files submitted by API producers to build a comprehensive, machine-readable catalog of API operations.
  name: APIs.json Indexing
- description: API producers can submit their APIs to the index by providing a valid APIs.json document via the Search API POST endpoint or GitHub issues.
  name: API Submission
- description: Spectral-powered quality rating system that evaluates API documentation completeness and scores APIs to help consumers identify high-quality APIs.
  name: Spectral API Ratings
- description: Built as a set of microservices including Search, Engine, Authentication, Publishing, Tags, Rules, Properties, Maintainers, and Ratings APIs.
  name: Microservice Architecture
- description: Specialized search nodes for domain-specific API discovery including AI, Healthcare, Banking, Payments, Weather, CRM, Cloud, and many more topic areas.
  name: Topic Search Nodes
- description: The platform is open source, licensed under Apache-2.0, with all microservice APIs available on GitHub under the api-search organization.
  name: Open Source
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Core integration with the APIs.json specification for machine-readable API description and discovery across the web.
  name: APIs.json
- description: APIs indexed in APIs.io reference OpenAPI specifications as a key property, linking consumers to technical API contracts.
  name: OpenAPI
- description: Spectral ruleset integration powers the APIs.io rating system, evaluating API documentation quality against standardized rules.
  name: Spectral
- description: GitHub integration for API submission via issues, source of truth for indexed APIs.json files, and authentication via Personal Access Tokens.
  name: GitHub
- description: Postman public workspace integration for running and testing the APIs.io Search API via pre-built collections.
  name: Postman
- description: The APIs.io Search API is deployed and managed through AWS API Gateway for scalable, managed API access.
  name: AWS API Gateway
jsonld:
- class_count: 15
  name: Apis Io Context
  property_count: 34
  slug: apis-io-context
layout: provider
modified: '2026-04-19'
name: APIs.io
rules:
- name: APIs.io API Rules
  rule_count: 37
  severity_counts:
    error: 13
    hint: 0
    info: 6
    warn: 18
  slug: apis-io-spectral-rules
skills: []
slug: apis-io
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apis-io\nname: APIs.io\ndescription: >-\n  APIs.io is an open source API search engine and directory that uses APIs.json\n  files to discover, index, and catalog APIs across the web. Built on the\n  APIs.json specification, it provides a searchable entry point for developers\n  to find public APIs by keyword, resource, action, persona, domain, and schema.\n  The platform indexes 779 providers, 3,188 APIs, 587 capabilities, 36,602\n  schemas, 49 event specs, 2,078 vocabularies, and 450 rulesets. It is\n  maintained by Kin Lane, Nicolas Grenier, and Steven Willmott and supports\n  both API producers (submitting APIs) and API consumers (discovering APIs).\n  APIs.io uses a Spectral-powered rating system to evaluate API documentation\n  quality.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Aggregation\n  - API Directory\n  - API Discovery\n  - API Indexing\n  - API Rating\n  - API Search\n  - APIs.json\n  -\
  \ Search Engine\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apis-io:search-api\n    name: APIs.io Search API\n    description: >-\n      The APIs.io Search API allows developers to search for APIs across all\n      indexed APIs.json files using keywords or phrases, and to submit new APIs\n      to the index by providing a valid APIs.json document. The API supports\n      pagination, filtering, and returns results with name, description, tags,\n      score, and URLs. Authentication is handled via the separate Authentication\n      API which converts GitHub Personal Access Tokens into API keys.\n    humanURL: https://developer.apis.io/documentation/\n    baseURL: https://search-api.apis.io\n    tags:\n      - API Discovery\n      - API Indexing\n      - API Search\n      - APIs.json\n    properties:\n      - type: Documentation\n        url: https://developer.apis.io/documentation/\n\
  \      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/openapi/apis-io-search-openapi.yaml\n      - type: Postman Collection\n        url: >-\n          https://www.postman.com/api-evangelist/apis-io-api-evangelist-engine/collection/hn8xpmd/apis-io-search-api\n      - type: Authentication\n        url: https://developer.apis.io/authentication/\n      - type: RateLimits\n        url: https://developer.apis.io/plans/\n      - type: ChangeLog\n        url: https://developer.apis.io/change-log/\n      - type: StatusPage\n        url: >-\n          https://www.postman.com/api-evangelist/apis-io/monitor/APIs-io-Search---Status~1ef6bc29-9da9-4040-b98b-cef03be1155e\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/json-schema/apis-io-search-search-schema.json\n        title: Search Response Schema\n      - type: JSONSchema\n        url: >-\n        \
  \  https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/json-schema/apis-io-search-ap-is-json-schema.json\n        title: APIs.json Schema\ncommon:\n  - type: Website\n    url: https://apis.io\n  - type: About\n    url: https://apis.io/about/\n  - type: Blog\n    url: https://apis.io/blog/\n  - type: DeveloperPortal\n    url: https://developer.apis.io/\n  - type: Blog\n    url: https://developer.apis.io/blog/\n    title: Developer Blog\n  - type: GettingStarted\n    url: https://developer.apis.io/getting-started/\n  - type: Authentication\n    url: https://developer.apis.io/authentication/\n  - type: Plans\n    url: https://developer.apis.io/plans/\n  - type: ChangeLog\n    url: https://developer.apis.io/change-log/\n  - type: ReleaseNotes\n    url: https://developer.apis.io/change-log/\n  - type: Versioning\n    url: https://developer.apis.io/versioning/\n  - type: Support\n    url: https://developer.apis.io/support/\n  - type: TermsOfService\n    url: https://developer.apis.io/terms-of-service/\n\
  \  - type: PrivacyPolicy\n    url: https://developer.apis.io/privacy-policy/\n  - type: GitHubOrganization\n    url: https://github.com/api-search\n  - type: GitHubRepository\n    url: https://github.com/apisio/apis.io\n  - type: GitHubRepository\n    url: https://github.com/api-search/apis-io-search\n    title: Search API\n  - type: GitHubRepository\n    url: https://github.com/api-search/apis-io-engine\n    title: Search Engine\n  - type: GitHubRepository\n    url: https://github.com/api-search/apis-io-authentication\n    title: Authentication API\n  - type: GitHubRepository\n    url: https://github.com/api-search/apis-io-ratings\n    title: Ratings API\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/rules/apis-io-spectral-rules.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/vocabulary/apis-io-vocabulary.yaml\n  - type: NaftikoCapability\n    url:\
  \ >-\n      https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/capabilities/api-discovery-search.yaml\n    title: API Discovery and Search Capability\n  - type: Features\n    data:\n      - name: API Search\n        description: >-\n          Full-text search across 3,000+ indexed APIs by keyword, resource,\n          action, persona, domain, and schema using a cloud search engine.\n      - name: APIs.json Indexing\n        description: >-\n          Automatically indexes APIs.json files submitted by API producers to\n          build a comprehensive, machine-readable catalog of API operations.\n      - name: API Submission\n        description: >-\n          API producers can submit their APIs to the index by providing a valid\n          APIs.json document via the Search API POST endpoint or GitHub issues.\n      - name: Spectral API Ratings\n        description: >-\n          Spectral-powered quality rating system that evaluates API documentation\n          completeness\
  \ and scores APIs to help consumers identify high-quality\n          APIs.\n      - name: Microservice Architecture\n        description: >-\n          Built as a set of microservices including Search, Engine,\n          Authentication, Publishing, Tags, Rules, Properties, Maintainers, and\n          Ratings APIs.\n      - name: Topic Search Nodes\n        description: >-\n          Specialized search nodes for domain-specific API discovery including\n          AI, Healthcare, Banking, Payments, Weather, CRM, Cloud, and many more\n          topic areas.\n      - name: Open Source\n        description: >-\n          The platform is open source, licensed under Apache-2.0, with all\n          microservice APIs available on GitHub under the api-search organization.\n  - type: UseCases\n    data:\n      - name: API Discovery\n        description: >-\n          Developers can search for APIs relevant to their project by keyword,\n          discovering APIs across thousands of providers without\
  \ knowing where\n          to look.\n      - name: API Submission\n        description: >-\n          API producers can submit their APIs.json files to ensure their APIs\n          are discoverable in the index and properly cataloged with metadata.\n      - name: Quality Assessment\n        description: >-\n          Development teams use the Spectral ratings system to identify\n          high-quality APIs and avoid poorly documented or unmaintained options.\n      - name: Catalog Building\n        description: >-\n          Platform teams use APIs.io as a reference implementation for building\n          their own internal API catalogs using the APIs.json format.\n      - name: Domain-Specific Search\n        description: >-\n          Developers searching for APIs in specific domains (healthcare, finance,\n          AI) can use topic-specific search nodes for more targeted discovery.\n  - type: Integrations\n    data:\n      - name: APIs.json\n        description: >-\n          Core integration\
  \ with the APIs.json specification for machine-readable\n          API description and discovery across the web.\n      - name: OpenAPI\n        description: >-\n          APIs indexed in APIs.io reference OpenAPI specifications as a key\n          property, linking consumers to technical API contracts.\n      - name: Spectral\n        description: >-\n          Spectral ruleset integration powers the APIs.io rating system,\n          evaluating API documentation quality against standardized rules.\n      - name: GitHub\n        description: >-\n          GitHub integration for API submission via issues, source of truth for\n          indexed APIs.json files, and authentication via Personal Access Tokens.\n      - name: Postman\n        description: >-\n          Postman public workspace integration for running and testing the\n          APIs.io Search API via pre-built collections.\n      - name: AWS API Gateway\n        description: >-\n          The APIs.io Search API is deployed and\
  \ managed through AWS API Gateway\n          for scalable, managed API access.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/apis.yml
tags:
- API Aggregation
- API Directory
- API Discovery
- API Indexing
- API Rating
- API Search
- APIs.json
- Search Engine
url: https://raw.githubusercontent.com/api-evangelist/apis-io/refs/heads/main/apis.yml
use_cases:
- description: Developers can search for APIs relevant to their project by keyword, discovering APIs across thousands of providers without knowing where to look.
  name: API Discovery
- description: API producers can submit their APIs.json files to ensure their APIs are discoverable in the index and properly cataloged with metadata.
  name: API Submission
- description: Development teams use the Spectral ratings system to identify high-quality APIs and avoid poorly documented or unmaintained options.
  name: Quality Assessment
- description: Platform teams use APIs.io as a reference implementation for building their own internal API catalogs using the APIs.json format.
  name: Catalog Building
- description: Developers searching for APIs in specific domains (healthcare, finance, AI) can use topic-specific search nodes for more targeted discovery.
  name: Domain-Specific Search
---
