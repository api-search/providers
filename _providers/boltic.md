---
api_count: 5
api_specs:
- filename: boltic-gateway-api-openapi.yml
  format: yaml
  label: Boltic Gateway API
  slug: gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/openapi/boltic-gateway-api-openapi.yml
- filename: boltic-workflow-api-openapi.yml
  format: yaml
  label: Boltic Workflow API
  slug: workflow-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/openapi/boltic-workflow-api-openapi.yml
- filename: boltic-tables-api-openapi.yml
  format: yaml
  label: Boltic Tables API
  slug: tables-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/openapi/boltic-tables-api-openapi.yml
- filename: boltic-pipes-api-openapi.yml
  format: yaml
  label: Boltic Pipes API
  slug: pipes-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/openapi/boltic-pipes-api-openapi.yml
- filename: boltic-streams-api-openapi.yml
  format: yaml
  label: Boltic Streams API
  slug: streams-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/openapi/boltic-streams-api-openapi.yml
apis:
- description: The Boltic Gateway API provides a developer-friendly API gateway designed to simplify and secure how services interact across your platform. It enables seamless request routing, payload transformation
  name: Boltic Gateway API
  slug: gateway-api
- description: The Boltic Workflow API enables programmatic creation, management, and execution of automation workflows. Workflows are visual, no-code automation sequences that connect triggers with actions across 5
  name: Boltic Workflow API
  slug: workflow-api
- description: 'The Boltic Tables API provides programmatic access to Boltic Tables, a no-code database for teams to organize, manage, and automate structured data workflows. The API supports full CRUD operations on '
  name: Boltic Tables API
  slug: tables-api
- description: The Boltic Pipes API provides programmatic access to data synchronization pipelines that connect data sources to destinations. Pipes enable real-time data syncing across systems via automated pipeline
  name: Boltic Pipes API
  slug: pipes-api
- description: The Boltic Streams API provides real-time event streaming capabilities for tracking custom events and streaming data from websites, mobile apps, and servers. It includes source debugger tools for conf
  name: Boltic Streams API
  slug: streams-api
common:
- title: ''
  type: Website
  url: https://www.boltic.io/
- title: ''
  type: Documentation
  url: https://docs.boltic.io/
- title: ''
  type: Templates
  url: https://www.boltic.io/templates
- title: ''
  type: Pricing
  url: https://www.boltic.io/pricing
- title: ''
  type: About
  url: https://www.boltic.io/about-us
- title: ''
  type: Partners
  url: https://www.boltic.io/partners
- title: ''
  type: Blog
  url: https://www.boltic.io/blog
- title: ''
  type: ChangeLog
  url: https://www.boltic.io/changelog
- title: ''
  type: JSONLDContext
  url: json-ld/boltic-context.jsonld
created: '2026-01-02'
description: Boltic is an AI workflow automation platform that helps businesses streamline operations across customer support, finance, product, and marketing functions. The platform enables companies to build autonomous AI agents, create no-code workflows with drag-and-drop functionality, and connect with over 500 integrations including major tools like Salesforce, HubSpot, Shopify, and Google BigQuery.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 36
  name: Boltic Context
  property_count: 9
  slug: boltic-context
layout: provider
modified: '2026-04-19'
name: Boltic
skills: []
slug: boltic
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: boltic\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/apis.yml\napis:\n  - aid: boltic:gateway-api\n    name: Boltic Gateway API\n    tags:\n      - Gateways\n      - Plugins\n      - Routing\n      - Security\n    humanURL: https://docs.boltic.io/gateway/intro/\n    properties:\n      - url: https://docs.boltic.io/gateway/intro/\n        type: Documentation\n      - url: openapi/boltic-gateway-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/boltic-route.json\n        type: JSONSchema\n    description: >-\n      The Boltic Gateway API provides a developer-friendly API gateway designed\n      to simplify and secure how services interact across your platform. It\n      enables seamless request routing, payload transformation, and enforcement\n      of security policies across diverse integration types including serverless\n      functions, workflows, tables, and proxy endpoints. The Gateway supports\n      dynamic URL\
  \ rewriting, path parameter injection, fine-grained\n      authentication, and real-time observability.\n  - aid: boltic:workflow-api\n    name: Boltic Workflow API\n    tags:\n      - Automation\n      - Integrations\n      - Triggers\n      - Workflows\n    humanURL: https://www.boltic.io/products/workflow\n    properties:\n      - url: https://docs.boltic.io/\n        type: Documentation\n      - url: openapi/boltic-workflow-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/boltic-workflow.json\n        type: JSONSchema\n    description: >-\n      The Boltic Workflow API enables programmatic creation, management, and\n      execution of automation workflows. Workflows are visual, no-code\n      automation sequences that connect triggers with actions across 500+\n      integrations. The API supports HTTP-triggered workflows with customizable\n      responses, scheduled executions, webhook-based triggers, and integration\n      with AI providers including Perplexity, Hugging\
  \ Face, Meta, and DeepSeek.\n  - aid: boltic:tables-api\n    name: Boltic Tables API\n    tags:\n      - CRUD\n      - Databases\n      - NoCode\n      - Tables\n    humanURL: https://www.boltic.io/products/boltic-tables\n    properties:\n      - url: https://docs.boltic.io/docs/workflow-builder/activities/tables/\n        type: Documentation\n      - url: openapi/boltic-tables-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/boltic-table.json\n        type: JSONSchema\n    description: >-\n      The Boltic Tables API provides programmatic access to Boltic Tables, a\n      no-code database for teams to organize, manage, and automate structured\n      data workflows. The API supports full CRUD operations on tables and rows,\n      SQL query execution via a built-in SQL editor with AI-powered query\n      generation, and integration with workflows for automated data processing\n      triggered by table changes.\n  - aid: boltic:pipes-api\n    name: Boltic Pipes API\n    tags:\n\
  \      - DataSync\n      - ETL\n      - Integration\n      - Pipelines\n    humanURL: https://docs.boltic.io/docs/pipes/pipe-creation/\n    properties:\n      - url: https://docs.boltic.io/docs/pipes/pipe-creation/\n        type: Documentation\n      - url: openapi/boltic-pipes-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/boltic-pipe.json\n        type: JSONSchema\n    description: >-\n      The Boltic Pipes API provides programmatic access to data synchronization\n      pipelines that connect data sources to destinations. Pipes enable\n      real-time data syncing across systems via automated pipelines with zero\n      maintenance. Sources include databases such as MongoDB, MySQL, and\n      PostgreSQL, SaaS applications via API endpoints, and file storage. The\n      API supports configurable sync frequencies including minutely, hourly,\n      and daily schedules.\n  - aid: boltic:streams-api\n    name: Boltic Streams API\n    tags:\n      - Analytics\n      - Events\n\
  \      - RealTime\n      - Streaming\n    humanURL: https://www.boltic.io/products/streams\n    properties:\n      - url: https://docs.boltic.io/docs/streams/intro/\n        type: Documentation\n      - url: openapi/boltic-streams-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/boltic-stream-event.json\n        type: JSONSchema\n    description: >-\n      The Boltic Streams API provides real-time event streaming capabilities\n      for tracking custom events and streaming data from websites, mobile apps,\n      and servers. It includes source debugger tools for confirming API call\n      delivery, an event analysis dashboard for monitoring event flows, and\n      real-time data processing for actionable insights.\nname: Boltic\ntags:\n  - Automation\n  - DataSync\n  - Gateways\n  - NoCode\n  - Streaming\n  - Workflows\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - name: Website\n    description:\
  \ 'null'\n    url: https://www.boltic.io/\n    type: Website\n  - name: Documentation\n    description: 'null'\n    url: https://docs.boltic.io/\n    type: Documentation\n  - name: Templates\n    description: 'null'\n    url: https://www.boltic.io/templates\n    type: Templates\n  - name: Integrations\n    description: 'null'\n    url: https://www.boltic.io/integrations\n    type: Integrations\n  - name: Pricing\n    description: 'null'\n    url: https://www.boltic.io/pricing\n    type: Pricing\n  - name: About\n    description: 'null'\n    url: https://www.boltic.io/about-us\n    type: About\n  - name: Partners\n    description: 'null'\n    url: https://www.boltic.io/partners\n    type: Partners\n  - name: Blog\n    description: 'null'\n    url: https://www.boltic.io/blog\n    type: Blog\n  - name: ChangeLog\n    description: 'null'\n    url: https://www.boltic.io/changelog\n    type: ChangeLog\n  - name: JSON-LD Context\n    description: 'null'\n    url: json-ld/boltic-context.jsonld\n\
  \    type: JSONLDContext\ncreated: '2026-01-02'\nmodified: '2026-04-19'\nposition: Consuming\ndescription: >-\n  Boltic is an AI workflow automation platform that helps businesses streamline operations\n  across customer support, finance, product, and marketing functions. The platform\n  enables companies to build autonomous AI agents, create no-code workflows with drag-and-drop\n  functionality, and connect with over 500 integrations including major tools like\n  Salesforce, HubSpot, Shopify, and Google BigQuery.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/apis.yml
tags:
- Automation
- DataSync
- Gateways
- NoCode
- Streaming
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/apis.yml
use_cases: []
---
