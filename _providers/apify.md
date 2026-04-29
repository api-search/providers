---
api_count: 1
apis:
- description: The Apify REST API (v2) provides programmatic access to the Apify platform, allowing you to manage actors, run scraping tasks, access datasets, key-value stores, and request queues. Authentication use
  name: Apify API
  slug: apify-api
capabilities:
- description: Unified workflow for running web scraping actors, monitoring execution, and retrieving structured data from the Apify platform.
  name: Apify Web Scraping and Automation
  slug: web-scraping-automation
common:
- title: ''
  type: Website
  url: https://apify.com
- title: ''
  type: Documentation
  url: https://docs.apify.com
- title: ''
  type: GettingStarted
  url: https://docs.apify.com/api/v2/getting-started
- title: ''
  type: Pricing
  url: https://apify.com/pricing
- title: ''
  type: Blog
  url: https://blog.apify.com
- title: ''
  type: SignUp
  url: https://console.apify.com/sign-up
- title: ''
  type: Login
  url: https://console.apify.com/sign-in
- title: ''
  type: Academy
  url: https://docs.apify.com/academy
- title: ''
  type: Support
  url: https://help.apify.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/apify
- title: ''
  type: CLI
  url: https://www.npmjs.com/package/apify-cli
created: '2026-03-26'
description: Apify is a full-stack web scraping and browser automation platform that enables developers to build, run, and scale web scrapers, crawlers, and data extraction tools using a cloud-based infrastructure with built-in proxy management, scheduling, and storage. The platform hosts thousands of ready-made Actors for scraping social media, search engines, maps, e-commerce sites, and more.
features:
- description: Store of thousands of pre-built web scrapers and automation tools ready to run with zero configuration.
  name: Actors Marketplace
- description: Run Actors on Apify's scalable cloud infrastructure with built-in proxy rotation, scheduling, and storage.
  name: Cloud Infrastructure
- description: Structured storage for Actor output with multi-format export (JSON, CSV, XML, XLSX, etc.).
  name: Datasets
- description: Persistent key-value storage for arbitrary data including files, screenshots, and configuration.
  name: Key-Value Stores
- description: URL queue management for large-scale distributed web crawling.
  name: Request Queues
- description: Built-in datacenter and residential proxy pools with automatic rotation.
  name: Proxy Management
- description: Schedule Actors to run automatically on cron schedules.
  name: Scheduled Runs
- description: Apify MCP server enabling AI agents to use thousands of web scraping and automation tools.
  name: MCP Server
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Open-source web crawling library for Node.js and Python built by Apify.
  name: Crawlee
- description: Zapier integration for connecting Apify Actors with 5000+ apps.
  name: Zapier
- description: No-code automation platform integration for Apify.
  name: Make (Integromat)
- description: LangChain integration for using Apify data loaders in AI applications.
  name: LangChain
jsonld:
- class_count: 7
  name: Apify Context
  property_count: 6
  slug: apify-context
layout: provider
modified: '2026-04-19'
name: Apify
rules:
- name: Apify API Rules
  rule_count: 11
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 5
  slug: apify-spectral-rules
skills: []
slug: apify
solutions: []
source_yaml: "aid: apify\nname: Apify\ndescription: >-\n  Apify is a full-stack web scraping and browser automation platform that\n  enables developers to build, run, and scale web scrapers, crawlers, and\n  data extraction tools using a cloud-based infrastructure with built-in\n  proxy management, scheduling, and storage. The platform hosts thousands\n  of ready-made Actors for scraping social media, search engines, maps,\n  e-commerce sites, and more.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Actors\n  - Browser Automation\n  - Crawling\n  - Data Aggregation\n  - Data Extraction\n  - Web Automation\n  - Web Scraping\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apify/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apify:apify-api\n    name: Apify API\n    description: >-\n      The Apify REST API (v2) provides programmatic access to the\
  \ Apify\n      platform, allowing you to manage actors, run scraping tasks, access\n      datasets, key-value stores, and request queues. Authentication uses\n      Bearer tokens. Rate limits: 250,000 requests/minute globally, 60-400\n      requests/second per resource.\n    humanURL: https://apify.com\n    baseURL: https://api.apify.com/v2\n    tags:\n      - Actors\n      - Automation\n      - Crawling\n      - Data Extraction\n      - Datasets\n      - Web Scraping\n    properties:\n      - type: Documentation\n        url: https://docs.apify.com/api/v2\n      - type: OpenAPI\n        url: openapi/apify-api.yaml\n      - type: GettingStarted\n        url: https://docs.apify.com/api/v2/getting-started\n      - type: Authentication\n        url: https://docs.apify.com/api/v2#authentication\n      - type: RateLimits\n        url: https://docs.apify.com/api/v2#rate-limiting-and-scaling\n      - type: JSONSchema\n        url: json-schema/apify-actor-schema.json\n      - type: JSONSchema\n\
  \        url: json-schema/apify-run-schema.json\n      - type: JSONSchema\n        url: json-schema/apify-dataset-schema.json\n      - type: JSONSchema\n        url: json-schema/apify-key-value-store-schema.json\n      - type: JSON-LD\n        url: json-ld/apify-context.jsonld\n      - type: SDK\n        url: https://www.npmjs.com/package/apify-client\n        title: Node.js Client\n      - type: SDK\n        url: https://pypi.org/project/apify-client/\n        title: Python Client\ncommon:\n  - type: Website\n    url: https://apify.com\n  - type: Documentation\n    url: https://docs.apify.com\n  - type: GettingStarted\n    url: https://docs.apify.com/api/v2/getting-started\n  - type: Pricing\n    url: https://apify.com/pricing\n  - type: Blog\n    url: https://blog.apify.com\n  - type: SignUp\n    url: https://console.apify.com/sign-up\n  - type: Login\n    url: https://console.apify.com/sign-in\n  - type: Academy\n    url: https://docs.apify.com/academy\n  - type: Support\n    url: https://help.apify.com\n\
  \  - type: GitHubOrganization\n    url: https://github.com/apify\n  - type: CLI\n    url: https://www.npmjs.com/package/apify-cli\n  - type: Features\n    data:\n      - name: Actors Marketplace\n        description: Store of thousands of pre-built web scrapers and automation tools ready to run with zero configuration.\n      - name: Cloud Infrastructure\n        description: Run Actors on Apify's scalable cloud infrastructure with built-in proxy rotation, scheduling, and storage.\n      - name: Datasets\n        description: Structured storage for Actor output with multi-format export (JSON, CSV, XML, XLSX, etc.).\n      - name: Key-Value Stores\n        description: Persistent key-value storage for arbitrary data including files, screenshots, and configuration.\n      - name: Request Queues\n        description: URL queue management for large-scale distributed web crawling.\n      - name: Proxy Management\n        description: Built-in datacenter and residential proxy pools with automatic\
  \ rotation.\n      - name: Scheduled Runs\n        description: Schedule Actors to run automatically on cron schedules.\n      - name: MCP Server\n        description: Apify MCP server enabling AI agents to use thousands of web scraping and automation tools.\n  - type: UseCases\n    data:\n      - name: AI Training Data Collection\n        description: Extract structured data from websites for LLM training datasets, RAG pipelines, and AI applications.\n      - name: E-commerce Price Monitoring\n        description: Scrape product prices, availability, and reviews from e-commerce websites for competitive intelligence.\n      - name: Social Media Data Extraction\n        description: Extract posts, profiles, and engagement data from social media platforms.\n      - name: Search Engine Data\n        description: Scrape search engine results, SERP data, and web listings for SEO and market research.\n      - name: Lead Generation\n        description: Extract business data from directories,\
  \ LinkedIn, and other professional platforms.\n  - type: Integrations\n    data:\n      - name: Crawlee\n        description: Open-source web crawling library for Node.js and Python built by Apify.\n      - name: Zapier\n        description: Zapier integration for connecting Apify Actors with 5000+ apps.\n      - name: Make (Integromat)\n        description: No-code automation platform integration for Apify.\n      - name: LangChain\n        description: LangChain integration for using Apify data loaders in AI applications.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apify/refs/heads/main/apis.yml
tags:
- Actors
- Browser Automation
- Crawling
- Data Aggregation
- Data Extraction
- Web Automation
- Web Scraping
url: https://raw.githubusercontent.com/api-evangelist/apify/refs/heads/main/apis.yml
use_cases:
- description: Extract structured data from websites for LLM training datasets, RAG pipelines, and AI applications.
  name: AI Training Data Collection
- description: Scrape product prices, availability, and reviews from e-commerce websites for competitive intelligence.
  name: E-commerce Price Monitoring
- description: Extract posts, profiles, and engagement data from social media platforms.
  name: Social Media Data Extraction
- description: Scrape search engine results, SERP data, and web listings for SEO and market research.
  name: Search Engine Data
- description: Extract business data from directories, LinkedIn, and other professional platforms.
  name: Lead Generation
---
