---
api_count: 1
apis:
- description: Cheerio implements a subset of core jQuery designed for the server. It parses markup into a traversable, manipulable DOM-like data structure and exposes a familiar jQuery-style API for selecting eleme
  name: Cheerio
  slug: cheerio
common:
- title: ''
  type: Website
  url: https://cheerio.js.org/
- title: ''
  type: Documentation
  url: https://cheerio.js.org/docs/intro
- title: ''
  type: APIReference
  url: https://cheerio.js.org/docs/api
- title: ''
  type: GitHubOrganization
  url: https://github.com/cheeriojs
- title: ''
  type: GitHubRepository
  url: https://github.com/cheeriojs/cheerio
- title: ''
  type: NPMPackage
  url: https://www.npmjs.com/package/cheerio
- title: ''
  type: License
  url: https://github.com/cheeriojs/cheerio/blob/main/LICENSE
- title: ''
  type: Issues
  url: https://github.com/cheeriojs/cheerio/issues
- title: ''
  type: JSONLD
  url: json-ld/cheerio-context.jsonld
- title: ''
  type: Tools
  url: ''
created: '2026-03-29'
description: Cheerio is a fast, flexible, and elegant Node.js library for parsing and manipulating HTML and XML using a jQuery-compatible API. It is widely used for server-side web scraping, HTML transformation, data extraction, and static site generation. Cheerio is MIT licensed and distributed as the cheerio npm package, maintained under the cheeriojs GitHub organization.
features:
- name: jQuery-Compatible API
- name: Server-Side HTML Parsing
- name: XML Parsing
- name: DOM Traversal
- name: DOM Manipulation
- name: CSS Selector Engine
- name: parse5 Integration
- name: htmlparser2 Integration
- name: Streaming Parser
- name: TypeScript Types
- name: Browser-Compatible Builds
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: Node.js
- name: npm
- name: TypeScript
- name: Bun
- name: Deno
- name: Puppeteer
- name: Playwright
- name: Axios
- name: node-fetch
- name: Got
jsonld:
- class_count: 0
  name: Cheerio Context
  property_count: 3
  slug: cheerio-context
layout: provider
modified: '2026-04-23'
name: Cheerio
skills: []
slug: cheerio
solutions: []
source_yaml: "aid: cheerio\nname: Cheerio\nx-type: opensource\ndescription: >-\n  Cheerio is a fast, flexible, and elegant Node.js library for parsing and\n  manipulating HTML and XML using a jQuery-compatible API. It is widely used\n  for server-side web scraping, HTML transformation, data extraction, and\n  static site generation. Cheerio is MIT licensed and distributed as the\n  cheerio npm package, maintained under the cheeriojs GitHub organization.\ntype: Index\nposition: Producer\naccess: Open Source\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cheerio/refs/heads/main/apis.yml\ntags:\n  - Data Extraction\n  - DOM\n  - HTML\n  - HTML Parsing\n  - jQuery\n  - MIT License\n  - Node.js\n  - npm\n  - Open Source\n  - Parser\n  - Scraping\n  - Server-side\n  - Web Scraping\n  - XML\ncreated: '2026-03-29'\nmodified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid: cheerio:cheerio\n\
  \    name: Cheerio\n    description: >-\n      Cheerio implements a subset of core jQuery designed for the server.\n      It parses markup into a traversable, manipulable DOM-like data\n      structure and exposes a familiar jQuery-style API for selecting\n      elements, traversing the tree, modifying attributes, extracting\n      text, and rendering HTML. It is commonly used in scraping\n      pipelines, build tools, static site generators, and tests that need\n      to operate over HTML content without launching a browser.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cheerio.js.org/\n    tags:\n      - Data Extraction\n      - HTML Parsing\n      - jQuery\n      - Node.js\n      - Scraping\n    properties:\n      - type: Documentation\n        url: https://cheerio.js.org/docs/intro\n      - type: GettingStarted\n        url: https://cheerio.js.org/docs/intro\n      - type: APIReference\n        url: https://cheerio.js.org/docs/api\n\
  \      - type: Blog\n        url: https://cheerio.js.org/blog\n      - type: GitHubRepository\n        url: https://github.com/cheeriojs/cheerio\n      - type: NPMPackage\n        url: https://www.npmjs.com/package/cheerio\n      - type: License\n        url: https://github.com/cheeriojs/cheerio/blob/main/LICENSE\n      - type: ContributionGuide\n        url: https://github.com/cheeriojs/cheerio/blob/main/CONTRIBUTING.md\n      - type: Issues\n        url: https://github.com/cheeriojs/cheerio/issues\n      - type: Releases\n        url: https://github.com/cheeriojs/cheerio/releases\ncommon:\n  - type: Website\n    url: https://cheerio.js.org/\n  - type: Documentation\n    url: https://cheerio.js.org/docs/intro\n  - type: APIReference\n    url: https://cheerio.js.org/docs/api\n  - type: GitHubOrganization\n    url: https://github.com/cheeriojs\n  - type: GitHubRepository\n    url: https://github.com/cheeriojs/cheerio\n  - type: NPMPackage\n    url: https://www.npmjs.com/package/cheerio\n\
  \  - type: License\n    name: MIT\n    url: https://github.com/cheeriojs/cheerio/blob/main/LICENSE\n  - type: Issues\n    url: https://github.com/cheeriojs/cheerio/issues\n  - type: JSONLD\n    url: json-ld/cheerio-context.jsonld\n  - name: Features\n    type: Features\n    data:\n      - name: jQuery-Compatible API\n      - name: Server-Side HTML Parsing\n      - name: XML Parsing\n      - name: DOM Traversal\n      - name: DOM Manipulation\n      - name: CSS Selector Engine\n      - name: parse5 Integration\n      - name: htmlparser2 Integration\n      - name: Streaming Parser\n      - name: TypeScript Types\n      - name: Browser-Compatible Builds\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Web Scraping\n      - name: Server-Side HTML Manipulation\n      - name: Static Site Generation\n      - name: Data Extraction Pipelines\n      - name: HTML Email Templating\n      - name: SEO Auditing Tools\n      - name: Content Migration\n      - name: Test HTML Assertions\n\
  \      - name: RSS and Atom Feed Generation\n      - name: HTML Sanitization Tooling\n  - name: Tools\n    type: Tools\n    data:\n      - name: cheerio\n      - name: parse5\n      - name: htmlparser2\n      - name: domhandler\n      - name: domutils\n      - name: css-select\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Node.js\n      - name: npm\n      - name: TypeScript\n      - name: Bun\n      - name: Deno\n      - name: Puppeteer\n      - name: Playwright\n      - name: Axios\n      - name: node-fetch\n      - name: Got\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cheerio/refs/heads/main/apis.yml
tags:
- Data Extraction
- DOM
- HTML
- HTML Parsing
- jQuery
- MIT License
- Node.js
- npm
- Open Source
- Parser
- Scraping
- Server-side
- Web Scraping
- XML
url: https://raw.githubusercontent.com/api-evangelist/cheerio/refs/heads/main/apis.yml
use_cases:
- name: Web Scraping
- name: Server-Side HTML Manipulation
- name: Static Site Generation
- name: Data Extraction Pipelines
- name: HTML Email Templating
- name: SEO Auditing Tools
- name: Content Migration
- name: Test HTML Assertions
- name: RSS and Atom Feed Generation
- name: HTML Sanitization Tooling
---
