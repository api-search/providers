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
