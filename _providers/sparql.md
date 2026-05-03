---
api_count: 1
apis:
- description: Standard SPARQL 1.1 Protocol HTTP endpoints for executing queries and updates against RDF datasets, plus the Graph Store HTTP Protocol for direct management of named graphs and the default graph, as d
  name: SPARQL Protocol API
  slug: ''
common: []
created: '2025'
description: SPARQL (SPARQL Protocol and RDF Query Language) is a W3C Recommendation that provides a standardized query language for retrieving and manipulating data stored in Resource Description Framework (RDF) format. It includes a protocol for submitting queries and updates over HTTP, a JSON results format for SELECT and ASK queries, and a Graph Store HTTP Protocol for managing RDF graphs.
features: []
image: ''
integrations: []
layout: provider
modified: '2026-03-16'
name: SPARQL
skills: []
slug: sparql
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: SPARQL\ndescription: >-\n  SPARQL (SPARQL Protocol and RDF Query Language) is a W3C Recommendation that provides\n  a standardized query language for retrieving and manipulating data stored in Resource\n  Description Framework (RDF) format. It includes a protocol for submitting queries\n  and updates over HTTP, a JSON results format for SELECT and ASK queries, and a Graph\n  Store HTTP Protocol for managing RDF graphs.\nurl: https://www.w3.org/TR/sparql11-overview/\ntags:\n  - Linked Data\n  - Query Language\n  - RDF\n  - Semantic Web\n  - SPARQL\n  - W3C\ncreated: '2025'\nmodified: '2026-03-16'\napis:\n  - name: SPARQL Protocol API\n    description: >-\n      Standard SPARQL 1.1 Protocol HTTP endpoints for executing queries and\n      updates against RDF datasets, plus the Graph Store HTTP Protocol for\n      direct management of named graphs and the default graph, as defined\n      by the W3C Recommendation.\n    humanURL: https://www.w3.org/TR/sparql11-protocol/\n\
  \    baseURL: https://dbpedia.org/sparql\n    version: '1.1'\n    tags:\n      - Graph Store\n      - Query\n      - RDF\n      - SPARQL\n      - Update\n    properties:\n      - type: x-openapi\n        url: openapi.yml\n      - type: x-json-schema\n        url: json-schema.json\n      - type: x-json-ld-context\n        url: json-ld-context.jsonld\n      - type: x-documentation\n        url: https://www.w3.org/TR/sparql11-overview/\n      - type: x-specification\n        url: https://www.w3.org/TR/sparql11-protocol/\n      - type: x-specification\n        url: https://www.w3.org/TR/sparql11-query/\n      - type: x-specification\n        url: https://www.w3.org/TR/sparql11-results-json/\n    contact:\n      - type: x-website\n        url: https://www.w3.org/\n      - type: x-github\n        url: https://github.com/w3c/sparql-query\ncommon: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sparql/refs/heads/main/apis.yml
tags:
- Linked Data
- Query Language
- RDF
- Semantic Web
- SPARQL
- W3C
url: https://www.w3.org/TR/sparql11-overview/
use_cases: []
---
