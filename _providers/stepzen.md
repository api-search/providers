---
api_count: 2
apis:
- description: 'GraphQL API platform for connecting to REST, databases, and other backends, automatically generating a GraphQL schema and resolvers from your data sources. Supports authentication via API key, OAuth, '
  name: StepZen GraphQL API
  slug: stepzen-api
- description: REST API for managing StepZen accounts, deployed GraphQL endpoints, API keys, and usage metrics programmatically.
  name: StepZen Admin API
  slug: stepzen-admin-api
capabilities:
- description: GraphQL API lifecycle management workflow for StepZen/IBM API Connect. Covers deploying GraphQL APIs from REST, database, and GraphQL backends, managing endpoints, rotating API keys, and monitoring ac
  name: StepZen GraphQL API Management
  slug: graphql-api-management
common:
- title: ''
  type: Portal
  url: https://stepzen.com/
- title: ''
  type: Documentation
  url: https://stepzen.com/docs
- title: ''
  type: Website
  url: https://stepzen.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/stepzen-dev
- title: ''
  type: Dashboard
  url: https://dashboard.ibm.stepzen.com/
- title: ''
  type: IBM Product Page
  url: https://www.ibm.com/products/api-connect
created: '2026-03-16'
description: StepZen (now IBM API Connect Essentials) is a GraphQL-as-a-Service platform that enables developers to build, deploy, and manage GraphQL APIs by connecting to multiple backends including REST APIs, SQL databases, NoSQL databases, GraphQL endpoints, and SOAP services. APIs are defined declaratively using GraphQL SDL with custom directives like @rest and @dbquery. StepZen runs a high-performance in-memory Golang GraphQL engine deployed on Kubernetes, optimizing queries at runtime for low latency and high throughput.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 14
  name: Stepzen Context
  property_count: 3
  slug: stepzen-context
layout: provider
modified: '2026-05-02'
name: StepZen
rules:
- name: StepZen API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 4
  slug: stepzen-rules
skills: []
slug: stepzen
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: stepzen\nname: StepZen\ndescription: >-\n  StepZen (now IBM API Connect Essentials) is a GraphQL-as-a-Service platform\n  that enables developers to build, deploy, and manage GraphQL APIs by connecting\n  to multiple backends including REST APIs, SQL databases, NoSQL databases,\n  GraphQL endpoints, and SOAP services. APIs are defined declaratively using\n  GraphQL SDL with custom directives like @rest and @dbquery. StepZen runs a\n  high-performance in-memory Golang GraphQL engine deployed on Kubernetes,\n  optimizing queries at runtime for low latency and high throughput.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Backend Integration\n  - GraphQL\n  - API Gateway\n  - REST to GraphQL\n  - IBM\n  - Data Federation\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/stepzen/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: stepzen:stepzen-api\n\
  \    name: StepZen GraphQL API\n    description: >-\n      GraphQL API platform for connecting to REST, databases, and other backends,\n      automatically generating a GraphQL schema and resolvers from your data sources.\n      Supports authentication via API key, OAuth, and custom headers. Deployed\n      instances are accessible at account.stepzen.net endpoints.\n    humanURL: https://stepzen.com/\n    baseURL: https://{account}.stepzen.net/{folder}/{name}/__graphql\n    tags:\n      - GraphQL\n      - API Integration\n      - Data Federation\n      - REST\n      - Database\n    properties:\n      - type: Documentation\n        url: https://stepzen.com/docs\n      - type: GitHub Organization\n        url: https://github.com/stepzen-dev\n      - type: CLI Reference\n        url: https://stepzen.com/docs/cli/cli-commands\n      - type: Getting Started\n        url: https://stepzen.com/docs/quick-start/install-and-setup\n      - type: IBM Documentation\n        url: https://www.ibm.com/docs/en/stepzen\n\
  \  - aid: stepzen:stepzen-admin-api\n    name: StepZen Admin API\n    description: >-\n      REST API for managing StepZen accounts, deployed GraphQL endpoints,\n      API keys, and usage metrics programmatically.\n    humanURL: https://stepzen.com/docs\n    tags:\n      - Administration\n      - API Management\n      - GraphQL\n    properties:\n      - type: Documentation\n        url: https://stepzen.com/docs\ncommon:\n  - type: Portal\n    url: https://stepzen.com/\n  - type: Documentation\n    url: https://stepzen.com/docs\n  - type: Website\n    url: https://stepzen.com/\n  - type: GitHub Organization\n    url: https://github.com/stepzen-dev\n  - type: Dashboard\n    url: https://dashboard.ibm.stepzen.com/\n  - type: IBM Product Page\n    url: https://www.ibm.com/products/api-connect\nfeatures:\n  - name: REST to GraphQL\n    description: Import existing REST APIs and auto-generate GraphQL schemas using @rest directive\n  - name: Database to GraphQL\n    description: Connect SQL (MySQL,\
  \ PostgreSQL, MSSQL) and NoSQL databases using @dbquery directive\n  - name: GraphQL Federation\n    description: Import and stitch multiple GraphQL endpoints into a unified schema\n  - name: SOAP to GraphQL\n    description: Connect SOAP/WSDL services to GraphQL using @connector directive\n  - name: Declarative Schema\n    description: Define APIs with GraphQL SDL and custom directives, no resolver code needed\n  - name: Auto-Generated Resolvers\n    description: StepZen generates and optimizes resolvers at runtime from declarative schema\n  - name: Query Optimization\n    description: Runtime query planning and optimization for low latency and high throughput\n  - name: Schema Explorer\n    description: Built-in browser-based GraphQL schema explorer for testing deployed APIs\n  - name: CLI Import\n    description: stepci import curl/graphql/mysql commands to introspect and generate schemas\nuseCases:\n  - name: API Aggregation\n    description: Combine multiple REST and database sources\
  \ into a single unified GraphQL API\n  - name: Frontend BFF\n    description: Create tailored Backend-for-Frontend GraphQL layers for React, Next.js, Vue\n  - name: Data Federation\n    description: Federate data from multiple disparate sources into a single queryable schema\n  - name: Legacy API Modernization\n    description: Expose legacy REST and SOAP APIs as modern GraphQL endpoints\n  - name: Rapid Prototyping\n    description: Quickly build and deploy GraphQL APIs from existing data sources\nintegrations:\n  - name: MySQL\n    description: Connect MySQL databases using @dbquery directive\n  - name: PostgreSQL\n    description: Connect PostgreSQL databases using @dbquery directive\n  - name: REST APIs\n    description: Import any REST/HTTP API using @rest directive or stepzen import curl\n  - name: GraphQL\n    description: Import existing GraphQL schemas using stepzen import graphql\n  - name: Shopify\n    description: Pre-built Shopify GraphQL integration\n  - name: WordPress\n\
  \    description: Connect WordPress data via REST API import\n  - name: Next.js\n    description: Official Next.js starter template and integration guide\n  - name: Netlify\n    description: StepZen build plugin for Netlify deployments\n  - name: Apigee\n    description: GraphQL API management integration with Google Apigee\nsolutions:\n  - name: GraphQL as a Service\n    description: Fully managed GraphQL execution layer without infrastructure management\n  - name: IBM API Connect Essentials\n    description: StepZen functionality available as part of IBM API Connect platform\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/stepzen/refs/heads/main/apis.yml
tags:
- Backend Integration
- GraphQL
- API Gateway
- REST to GraphQL
- IBM
- Data Federation
url: https://raw.githubusercontent.com/api-evangelist/stepzen/refs/heads/main/apis.yml
use_cases: []
---
