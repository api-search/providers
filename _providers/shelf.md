---
api_count: 3
apis:
- description: The Shelf REST API enables developers to programmatically interact with the Shelf knowledge management platform. Access, search, create, and manage knowledge articles, gems (curated content), decision
  name: Shelf REST API
  slug: shelf-rest-api
- description: The Shelf Content Intelligence API provides AI-powered knowledge retrieval, semantic search, and content quality analysis capabilities. Enables applications to query Shelf's knowledge base with natura
  name: Shelf Content Intelligence API
  slug: shelf-content-intelligence-api
- description: 'Shelf Webhooks enable real-time event notifications when knowledge content is created, updated, archived, or reviewed. Supports integration with external workflow automation tools, content management '
  name: Shelf Webhooks
  slug: shelf-webhooks
common:
- title: ''
  type: Website
  url: https://shelf.io
- title: ''
  type: Developer Portal
  url: https://shelf.io/technology/
- title: ''
  type: Documentation
  url: https://help.shelf.io/technical-guidelines-10162c4f
- title: ''
  type: Partner Integrations
  url: https://shelf.io/partners/integrations/
- title: ''
  type: GitHub Organization
  url: https://github.com/shelfio
- title: ''
  type: API Tracker
  url: https://apitracker.io/a/shelf-io
created: '2025-01-01'
description: Shelf.io is the first knowledge automation platform and next-generation AI agentic platform for knowledge management. The platform serves as a knowledge hub for brands with contact centers and large customer bases, enabling organizations to manage, improve, and deploy unstructured knowledge for accurate AI-generated answers and self-service experiences. Shelf provides developer-friendly REST APIs, SDKs (Python and JavaScript), webhooks, and 100+ integrations with platforms including Salesforce, Zendesk, ServiceNow, and Microsoft Teams. The platform offers Content Connectors, Decision Trees, multilingual support for 100+ languages, and analytics dashboards.
features:
- description: Programmatic access to all Shelf knowledge resources via REST API with regional endpoints for US, Canada, and Europe.
  name: REST API Access
- description: AI-powered semantic search and knowledge retrieval for building intelligent knowledge experiences.
  name: Content Intelligence API
- description: Secure API access via token-based authentication with standard and full admin access levels.
  name: API Token Authentication
- description: Real-time event notifications for knowledge content lifecycle events.
  name: Webhooks
- description: Official Python SDK for integrating Shelf knowledge management into Python applications.
  name: Python SDK
- description: Official JavaScript SDK for integrating Shelf into web and Node.js applications.
  name: JavaScript SDK
- description: Pre-built connectors to sync knowledge from SharePoint, Confluence, Google Drive, Zendesk, and 100+ sources.
  name: Content Connectors
- description: Interactive decision tree builder for guided troubleshooting and self-service content.
  name: Decision Trees
- description: Knowledge management and AI responses in 100+ languages.
  name: Multilingual Support
image: https://shelf.io/wp-content/uploads/2021/07/shelf-logo.svg
integrations:
- description: Sync Shelf knowledge with Salesforce Service Cloud for agent and customer knowledge access.
  name: Salesforce
- description: Embed Shelf knowledge into Zendesk for agent assist and self-service ticket deflection.
  name: Zendesk
- description: Integrate Shelf with ServiceNow for IT service management knowledge automation.
  name: ServiceNow
- description: Surface Shelf knowledge directly within Microsoft Teams for employee self-service.
  name: Microsoft Teams
- description: Integrate Shelf with Genesys contact center platform for agent assist.
  name: Genesys
- description: Content Connector to sync and manage knowledge from Google Drive documents.
  name: Google Drive
- description: Content Connector to sync Confluence wiki content into Shelf knowledge base.
  name: Confluence
jsonld:
- class_count: 4
  name: Shelf Context
  property_count: 23
  slug: shelf-context
layout: provider
modified: '2026-05-02'
name: Shelf.io
skills: []
slug: shelf
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: shelf\nurl: https://raw.githubusercontent.com/api-evangelist/shelf/refs/heads/main/apis.yml\napis:\n  - aid: shelf:shelf-rest-api\n    name: Shelf REST API\n    tags:\n      - Artificial Intelligence\n      - Knowledge Management\n      - REST\n      - Search\n    humanURL: https://shelf.io/technology/\n    properties:\n      - url: https://shelf.io/technology/\n        type: Documentation\n      - url: https://help.shelf.io/technical-guidelines-10162c4f\n        type: GettingStarted\n      - url: https://help.shelf.io/technical-guidelines-10162c4f/shelf-api-token-feature-introductory-guide-aac2ec62\n        type: Authentication\n    description: >-\n      The Shelf REST API enables developers to programmatically interact with\n      the Shelf knowledge management platform. Access, search, create, and\n      manage knowledge articles, gems (curated content), decision trees, and\n      user permissions. Supports regional endpoints for US (api.shelf.io),\n      Canada (api.shelf-ca.com),\
  \ and Europe (api.shelf-eu.com).\n  - aid: shelf:shelf-content-intelligence-api\n    name: Shelf Content Intelligence API\n    tags:\n      - Artificial Intelligence\n      - Content\n      - Knowledge Management\n      - Search\n    humanURL: https://shelf.io/integrations/\n    properties:\n      - url: https://shelf.io/integrations/\n        type: Documentation\n    description: >-\n      The Shelf Content Intelligence API provides AI-powered knowledge\n      retrieval, semantic search, and content quality analysis capabilities.\n      Enables applications to query Shelf's knowledge base with natural language,\n      retrieve contextually relevant answers, and integrate Shelf's AI knowledge\n      engine into contact centers, chatbots, and enterprise applications.\n  - aid: shelf:shelf-webhooks\n    name: Shelf Webhooks\n    tags:\n      - Events\n      - Knowledge Management\n      - Webhooks\n    humanURL: https://shelf.io/integrations/\n    properties:\n      - url: https://shelf.io/integrations/\n\
  \        type: Documentation\n    description: >-\n      Shelf Webhooks enable real-time event notifications when knowledge content\n      is created, updated, archived, or reviewed. Supports integration with\n      external workflow automation tools, content management systems, and\n      third-party applications via HTTP event payloads.\nname: Shelf.io\ntags:\n  - Artificial Intelligence\n  - Contact Center\n  - Knowledge Management\n  - SaaS\n  - Search\ntype: Contract\nimage: https://shelf.io/wp-content/uploads/2021/07/shelf-logo.svg\naccess: 3rd-Party\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nposition: Consumer\ndescription: >-\n  Shelf.io is the first knowledge automation platform and next-generation AI\n  agentic platform for knowledge management. The platform serves as a knowledge\n  hub for brands with contact centers and large customer bases, enabling\n  organizations to manage, improve, and deploy unstructured knowledge for\n  accurate AI-generated answers and self-service\
  \ experiences. Shelf provides\n  developer-friendly REST APIs, SDKs (Python and JavaScript), webhooks,\n  and 100+ integrations with platforms including Salesforce, Zendesk, ServiceNow,\n  and Microsoft Teams. The platform offers Content Connectors, Decision Trees,\n  multilingual support for 100+ languages, and analytics dashboards.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - url: https://shelf.io\n    type: Website\n  - url: https://shelf.io/technology/\n    type: Developer Portal\n  - url: https://help.shelf.io/technical-guidelines-10162c4f\n    type: Documentation\n  - url: https://shelf.io/integrations/\n    type: Integrations\n  - url: https://shelf.io/partners/integrations/\n    type: Partner Integrations\n  - url: https://github.com/shelfio\n    type: GitHub Organization\n  - url: https://apitracker.io/a/shelf-io\n    type: API Tracker\n  - type: Features\n    data:\n      - name: REST API Access\n        description:\
  \ Programmatic access to all Shelf knowledge resources via REST API with regional endpoints for US, Canada, and Europe.\n      - name: Content Intelligence API\n        description: AI-powered semantic search and knowledge retrieval for building intelligent knowledge experiences.\n      - name: API Token Authentication\n        description: Secure API access via token-based authentication with standard and full admin access levels.\n      - name: Webhooks\n        description: Real-time event notifications for knowledge content lifecycle events.\n      - name: Python SDK\n        description: Official Python SDK for integrating Shelf knowledge management into Python applications.\n      - name: JavaScript SDK\n        description: Official JavaScript SDK for integrating Shelf into web and Node.js applications.\n      - name: Content Connectors\n        description: Pre-built connectors to sync knowledge from SharePoint, Confluence, Google Drive, Zendesk, and 100+ sources.\n      - name:\
  \ Decision Trees\n        description: Interactive decision tree builder for guided troubleshooting and self-service content.\n      - name: Multilingual Support\n        description: Knowledge management and AI responses in 100+ languages.\n  - type: UseCases\n    data:\n      - name: Contact Center Knowledge\n        description: Equip contact center agents with instant access to accurate, up-to-date knowledge during customer interactions.\n      - name: AI Chatbot Grounding\n        description: Ground AI chatbots and virtual assistants with verified organizational knowledge via the Content Intelligence API.\n      - name: Self-Service Portal\n        description: Build customer self-service portals backed by Shelf's knowledge base and semantic search.\n      - name: Knowledge Automation\n        description: Automate knowledge curation, quality checks, and content lifecycle management via APIs.\n      - name: Enterprise Search\n        description: Integrate Shelf search into enterprise\
  \ portals for unified access to distributed knowledge.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: Sync Shelf knowledge with Salesforce Service Cloud for agent and customer knowledge access.\n      - name: Zendesk\n        description: Embed Shelf knowledge into Zendesk for agent assist and self-service ticket deflection.\n      - name: ServiceNow\n        description: Integrate Shelf with ServiceNow for IT service management knowledge automation.\n      - name: Microsoft Teams\n        description: Surface Shelf knowledge directly within Microsoft Teams for employee self-service.\n      - name: Genesys\n        description: Integrate Shelf with Genesys contact center platform for agent assist.\n      - name: Google Drive\n        description: Content Connector to sync and manage knowledge from Google Drive documents.\n      - name: Confluence\n        description: Content Connector to sync Confluence wiki content into Shelf knowledge base.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/shelf/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Contact Center
- Knowledge Management
- SaaS
- Search
url: https://raw.githubusercontent.com/api-evangelist/shelf/refs/heads/main/apis.yml
use_cases:
- description: Equip contact center agents with instant access to accurate, up-to-date knowledge during customer interactions.
  name: Contact Center Knowledge
- description: Ground AI chatbots and virtual assistants with verified organizational knowledge via the Content Intelligence API.
  name: AI Chatbot Grounding
- description: Build customer self-service portals backed by Shelf's knowledge base and semantic search.
  name: Self-Service Portal
- description: Automate knowledge curation, quality checks, and content lifecycle management via APIs.
  name: Knowledge Automation
- description: Integrate Shelf search into enterprise portals for unified access to distributed knowledge.
  name: Enterprise Search
---
