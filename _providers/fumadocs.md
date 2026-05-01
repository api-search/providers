---
api_count: 3
api_specs:
- filename: fumadocs-search-openapi.yml
  format: yaml
  label: Fumadocs Search API
  slug: search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fumadocs/refs/heads/main/openapi/fumadocs-search-openapi.yml
- filename: fumadocs-openapi-proxy-openapi.yml
  format: yaml
  label: Fumadocs OpenAPI Proxy API
  slug: openapi-proxy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fumadocs/refs/heads/main/openapi/fumadocs-openapi-proxy-openapi.yml
apis:
- description: Fumadocs is an open-source documentation framework built on Next.js and React for creating fast, modern developer documentation sites. It provides a full stack of composable packages including fumadoc
  name: Fumadocs
  slug: fumadocs
- description: The Fumadocs Search API is a server-side HTTP endpoint embedded in each Fumadocs documentation site that enables full-text search across all indexed documentation content. The endpoint (typically at /
  name: Fumadocs Search API
  slug: search-api
- description: The Fumadocs OpenAPI Proxy API is a server-side HTTP proxy included in the fumadocs-openapi package that enables the interactive API playground to make authenticated requests to external API servers f
  name: Fumadocs OpenAPI Proxy API
  slug: openapi-proxy-api
common:
- title: ''
  type: Website
  url: https://fumadocs.dev
- title: ''
  type: Documentation
  url: https://fumadocs.dev/docs
- title: ''
  type: GitHub
  url: https://github.com/fuma-nama/fumadocs
- title: ''
  type: Documentation
  url: https://fumadocs.dev/docs/ui/components
- title: ''
  type: Documentation
  url: https://fumadocs.dev/docs/headless/search/orama
- title: ''
  type: Documentation
  url: https://fumadocs.dev/docs/ui/openapi
- title: ''
  type: Distribution
  url: https://www.npmjs.com/package/fumadocs-core
- title: ''
  type: Distribution
  url: https://www.npmjs.com/package/fumadocs-ui
- title: ''
  type: Distribution
  url: https://www.npmjs.com/package/fumadocs-openapi
- title: ''
  type: License
  url: https://github.com/fuma-nama/fumadocs/blob/main/LICENSE
- title: ''
  type: JSONSchema
  url: json-schema/fumadocs-page-tree-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fumadocs-page-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/fumadocs-meta-schema.json
- title: ''
  type: JSONLD
  url: json-ld/fumadocs-context.jsonld
created: '2026-03-18'
description: Fumadocs is a modern documentation framework built on Next.js for building developer documentation sites. It provides a complete set of composable packages for content loading, navigation tree generation, full-text search, UI components, and interactive API reference generation from OpenAPI specifications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Fumadocs Context
  property_count: 7
  slug: fumadocs-context
layout: provider
modified: '2026-04-28'
name: Fumadocs
skills: []
slug: fumadocs
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: fumadocs\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/fumadocs/refs/heads/main/apis.yml\napis:\n  - aid: fumadocs:fumadocs\n    name: Fumadocs\n    tags:\n      - Documentation\n      - Framework\n      - Next.js\n    humanURL: https://fumadocs.dev\n    properties:\n      - url: https://fumadocs.dev/docs\n        type: Documentation\n      - url: https://github.com/fuma-nama/fumadocs\n        type: GitHub\n    description: >-\n      Fumadocs is an open-source documentation framework built on Next.js and React\n      for creating fast, modern developer documentation sites. It provides a full\n      stack of composable packages including fumadocs-core for source loading, page\n      tree generation, and search; fumadocs-ui for pre-built accessible React components,\n      themes, and layouts; fumadocs-openapi for generating interactive API reference\n      pages from OpenAPI specifications with a built-in playground; and a CLI for\n      scaffolding new projects.\n\
  \  - aid: fumadocs:search-api\n    name: Fumadocs Search API\n    tags:\n      - Documentation\n      - Search\n    humanURL: https://fumadocs.dev/docs/headless/search/orama\n    properties:\n      - url: https://fumadocs.dev/docs/headless/search/orama\n        type: Documentation\n      - url: openapi/fumadocs-search-openapi.yml\n        type: OpenAPI\n      - url: json-schema/fumadocs-search-result-schema.json\n        type: JSONSchema\n    description: >-\n      The Fumadocs Search API is a server-side HTTP endpoint embedded in each Fumadocs\n      documentation site that enables full-text search across all indexed documentation\n      content. The endpoint (typically at /api/search) accepts a query string along\n      with optional locale and tag filters, and returns a ranked list of matching\n      pages, headings, and text segments with highlighted content and breadcrumb trails.\n  - aid: fumadocs:openapi-proxy-api\n    name: Fumadocs OpenAPI Proxy API\n    tags:\n      - Documentation\n\
  \      - OpenAPI\n      - Proxy\n    humanURL: https://fumadocs.dev/docs/ui/openapi\n    properties:\n      - url: https://fumadocs.dev/docs/ui/openapi\n        type: Documentation\n      - url: openapi/fumadocs-openapi-proxy-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Fumadocs OpenAPI Proxy API is a server-side HTTP proxy included in the fumadocs-openapi\n      package that enables the interactive API playground to make authenticated requests\n      to external API servers from the browser without CORS restrictions. Documentation\n      sites mount the proxy at a route such as /api/proxy, where it accepts any HTTP\n      method, extracts the target URL from the url query parameter, and transparently\n      forwards the request to the upstream server.\nname: Fumadocs\ntags:\n  - Documentation\n  - Framework\n  - Next.js\n  - React\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-18'\n\
  modified: '2026-04-28'\nposition: Consumer\nsegments:\n  - Documentation\ndescription: >-\n  Fumadocs is a modern documentation framework built on Next.js for building developer\n  documentation sites. It provides a complete set of composable packages for content\n  loading, navigation tree generation, full-text search, UI components, and interactive\n  API reference generation from OpenAPI specifications.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - url: https://fumadocs.dev\n    name: Fumadocs\n    type: Website\n    description: The official Fumadocs documentation site and homepage.\n  - url: https://fumadocs.dev/docs\n    name: Fumadocs Documentation\n    type: Documentation\n    description: Full documentation for all Fumadocs packages and APIs.\n  - url: https://github.com/fuma-nama/fumadocs\n    name: Fumadocs GitHub Repository\n    type: GitHub\n    description: Source code, issues, and contributions for the Fumadocs\
  \ \n      monorepo.\n  - url: https://fumadocs.dev/docs/ui/components\n    name: Fumadocs UI Components\n    type: Documentation\n    description: Reference for all Fumadocs UI React components.\n  - url: https://fumadocs.dev/docs/headless/search/orama\n    name: Fumadocs Search Documentation\n    type: Documentation\n    description: Guide for configuring full-text search with Orama, Algolia, and\n      other backends.\n  - url: https://fumadocs.dev/docs/ui/openapi\n    name: Fumadocs OpenAPI Documentation\n    type: Documentation\n    description: Guide for generating interactive API reference pages from \n      OpenAPI specs.\n  - url: https://www.npmjs.com/package/fumadocs-core\n    name: fumadocs-core on npm\n    type: Distribution\n    description: npm package for the core Fumadocs library.\n  - url: https://www.npmjs.com/package/fumadocs-ui\n    name: fumadocs-ui on npm\n    type: Distribution\n    description: npm package for Fumadocs UI components and themes.\n  - url: https://www.npmjs.com/package/fumadocs-openapi\n\
  \    name: fumadocs-openapi on npm\n    type: Distribution\n    description: npm package for Fumadocs OpenAPI reference generation.\n  - url: https://github.com/fuma-nama/fumadocs/blob/main/LICENSE\n    name: Fumadocs License (MIT)\n    type: License\n    description: MIT open-source license for the Fumadocs project.\n  - url: json-schema/fumadocs-page-tree-schema.json\n    name: Fumadocs Page Tree Schema\n    type: JSONSchema\n    description: JSON Schema for the hierarchical navigation page tree \n      structure.\n  - url: json-schema/fumadocs-page-schema.json\n    name: Fumadocs Page Frontmatter Schema\n    type: JSONSchema\n    description: JSON Schema for MDX page frontmatter fields.\n  - url: json-schema/fumadocs-meta-schema.json\n    name: Fumadocs Meta Schema\n    type: JSONSchema\n    description: JSON Schema for meta.json folder configuration files.\n  - url: json-ld/fumadocs-context.jsonld\n    name: Fumadocs JSON-LD Context\n    type: JSONLD\n    description: JSON-LD context\
  \ mapping Fumadocs entities to schema.org and \n      standard vocabularies.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/fumadocs/refs/heads/main/apis.yml
tags:
- Documentation
- Framework
- Next.js
- React
url: https://raw.githubusercontent.com/api-evangelist/fumadocs/refs/heads/main/apis.yml
use_cases: []
---
