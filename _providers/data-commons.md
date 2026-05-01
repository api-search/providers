---
api_count: 6
apis:
- description: HTTP REST interface for retrieving statistical observations, exploring the Data Commons knowledge graph, and resolving entities to Data Commons IDs (DCIDs). Returns structured JSON data covering varia
  name: Data Commons REST API V2
  slug: rest-v2
- description: Official Python client library that wraps the Data Commons REST API with native Pandas DataFrame support for analytical workflows and notebook integration.
  name: Data Commons Python Client
  slug: python
- description: Custom Google Sheets functions that pull Data Commons statistical data directly into spreadsheets without requiring an API key.
  name: Data Commons Google Sheets
  slug: sheets
- description: Drop-in JavaScript/HTML web components for embedding Data Commons charts, maps, rankings, and visualizations in any website.
  name: Data Commons Web Components
  slug: web-components
- description: SQL access to Data Commons through Google BigQuery enabling complex analytical queries and joins with private datasets.
  name: Data Commons BigQuery
  slug: bigquery
- description: Model Context Protocol server that lets AI agents query Data Commons conversationally, surfacing variables, places, and observations through natural language tools.
  name: Data Commons MCP Server
  slug: mcp
common:
- title: ''
  type: Website
  url: https://datacommons.org/
- title: ''
  type: Documentation
  url: https://docs.datacommons.org/
- title: ''
  type: API Documentation
  url: https://docs.datacommons.org/api/
- title: ''
  type: API Keys
  url: https://apikeys.datacommons.org
- title: ''
  type: GitHub Organization
  url: https://github.com/datacommonsorg
- title: ''
  type: Blog
  url: https://blog.datacommons.org/
- title: ''
  type: Vocabulary
  url: vocabulary/data-commons-vocabulary.yml
- title: ''
  type: JSON-LD
  url: json-ld/data-commons-context.jsonld
created: '2026-01-02'
description: Data Commons is an open knowledge graph initiative led by Google that aggregates and harmonizes the world's public data into a single graph, making global statistical data simple to explore, query, and integrate through REST, Python, BigQuery, web component, and MCP interfaces.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Data Commons Context
  property_count: 4
  slug: data-commons-context
layout: provider
modified: '2026-04-30'
name: Data Commons
skills: []
slug: data-commons
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: data-commons\nname: Data Commons\ndescription: >-\n  Data Commons is an open knowledge graph initiative led by Google that\n  aggregates and harmonizes the world's public data into a single graph,\n  making global statistical data simple to explore, query, and integrate\n  through REST, Python, BigQuery, web component, and MCP interfaces.\ntype: Topic\nxType: topic\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Commons\n  - Knowledge Graph\n  - Open Data\n  - Public Data\n  - Statistics\ncreated: '2026-01-02'\nmodified: '2026-04-30'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/data-commons/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: data-commons:rest-v2\n    name: Data Commons REST API V2\n    description: >-\n      HTTP REST interface for retrieving statistical observations, exploring\n      the Data Commons knowledge graph, and resolving\
  \ entities to Data Commons\n      IDs (DCIDs). Returns structured JSON data covering variables, places,\n      and observations.\n    humanURL: https://docs.datacommons.org/api/rest/v2/\n    tags:\n      - Knowledge Graph\n      - REST\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://docs.datacommons.org/api/rest/v2/\n      - type: API Keys\n        url: https://apikeys.datacommons.org\n      - type: Reference\n        url: https://docs.datacommons.org/api/\n  - aid: data-commons:python\n    name: Data Commons Python Client\n    description: >-\n      Official Python client library that wraps the Data Commons REST API\n      with native Pandas DataFrame support for analytical workflows and\n      notebook integration.\n    humanURL: https://docs.datacommons.org/api/python/v2/\n    tags:\n      - Pandas\n      - Python\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.datacommons.org/api/python/v2/\n      - type:\
  \ PyPI\n        url: https://pypi.org/project/datacommons-client/\n  - aid: data-commons:sheets\n    name: Data Commons Google Sheets\n    description: >-\n      Custom Google Sheets functions that pull Data Commons statistical data\n      directly into spreadsheets without requiring an API key.\n    humanURL: https://docs.datacommons.org/api/sheets/\n    tags:\n      - Google Sheets\n      - Spreadsheets\n    properties:\n      - type: Documentation\n        url: https://docs.datacommons.org/api/sheets/\n  - aid: data-commons:web-components\n    name: Data Commons Web Components\n    description: >-\n      Drop-in JavaScript/HTML web components for embedding Data Commons charts,\n      maps, rankings, and visualizations in any website.\n    humanURL: https://docs.datacommons.org/api/web_components/\n    tags:\n      - JavaScript\n      - Visualization\n      - Web Components\n    properties:\n      - type: Documentation\n        url: https://docs.datacommons.org/api/web_components/\n\
  \  - aid: data-commons:bigquery\n    name: Data Commons BigQuery\n    description: >-\n      SQL access to Data Commons through Google BigQuery enabling complex\n      analytical queries and joins with private datasets.\n    humanURL: https://docs.datacommons.org/api/bigquery.html\n    tags:\n      - BigQuery\n      - SQL\n    properties:\n      - type: Documentation\n        url: https://docs.datacommons.org/api/bigquery.html\n  - aid: data-commons:mcp\n    name: Data Commons MCP Server\n    description: >-\n      Model Context Protocol server that lets AI agents query Data Commons\n      conversationally, surfacing variables, places, and observations through\n      natural language tools.\n    humanURL: https://docs.datacommons.org/api/mcp/\n    tags:\n      - AI Agents\n      - MCP\n      - Natural Language\n    properties:\n      - type: Documentation\n        url: https://docs.datacommons.org/api/mcp/\n      - type: API Keys\n        url: https://apikeys.datacommons.org\ncommon:\n\
  \  - url: https://datacommons.org/\n    name: Website\n    type: Website\n    description: Official Data Commons project website.\n  - url: https://docs.datacommons.org/\n    name: Documentation\n    type: Documentation\n    description: Full Data Commons documentation portal.\n  - url: https://docs.datacommons.org/api/\n    name: API Documentation\n    type: API Documentation\n    description: Programmatic access reference for all Data Commons APIs.\n  - url: https://apikeys.datacommons.org\n    name: API Keys\n    type: API Keys\n    description: Self-service portal for requesting Data Commons API keys.\n  - url: https://github.com/datacommonsorg\n    name: GitHub Organization\n    type: GitHub Organization\n    description: Data Commons open source organization on GitHub.\n  - url: https://blog.datacommons.org/\n    name: Blog\n    type: Blog\n    description: Data Commons project blog with announcements and tutorials.\n  - url: vocabulary/data-commons-vocabulary.yml\n    name: Vocabulary\n\
  \    type: Vocabulary\n    description: Vocabulary of Data Commons knowledge graph concepts.\n  - url: json-ld/data-commons-context.jsonld\n    name: JSON-LD Context\n    type: JSON-LD\n    description: JSON-LD context mapping Data Commons concepts to Schema.org.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/data-commons/refs/heads/main/apis.yml
tags:
- Data Commons
- Knowledge Graph
- Open Data
- Public Data
- Statistics
url: https://raw.githubusercontent.com/api-evangelist/data-commons/refs/heads/main/apis.yml
use_cases: []
---
