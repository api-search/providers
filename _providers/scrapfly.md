---
api_count: 6
api_specs:
- filename: scrapfly-scrape-openapi.yml
  format: yaml
  label: Scrapfly Scrape API
  slug: scrape-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/openapi/scrapfly-scrape-openapi.yml
apis:
- description: 'The core web scraping API that fetches any URL with anti-bot bypass, proxy rotation, and JavaScript rendering. Supports GET, POST, PUT, PATCH, HEAD, and OPTIONS methods. Returns clean HTML, markdown, '
  name: Scrapfly Scrape API
  slug: scrape-api
- description: 'Capture screenshots of web pages with full-page or element-specific capture using CSS selectors. Supports JavaScript rendering, viewport configuration, and screenshot of dynamic content. The base URL '
  name: Scrapfly Screenshot API
  slug: screenshot-api
- description: AI-powered structured data extraction from HTML content. Supports template-based extraction, LLM prompt-driven extraction, and auto-extraction using predefined models for common content types.
  name: Scrapfly Extraction API
  slug: extraction-api
- description: Web crawling API (currently in early access) that enables crawling entire websites with advanced configuration for depth control and content filtering. Outputs in WARC format for comprehensive web arc
  name: Scrapfly Crawler API
  slug: crawler-api
- description: Headless browser automation API (currently in beta) compatible with Playwright, Puppeteer, and Selenium frameworks. Enables complex browser interactions, JavaScript execution, and file download captur
  name: Scrapfly Cloud Browser API
  slug: cloud-browser-api
- description: Official SDKs for Python, TypeScript, Go, Rust, and Scrapy with full feature coverage across every language including scrape, screenshot, extract, and crawl capabilities.
  name: Scrapfly SDKs
  slug: sdks
capabilities:
- description: Unified capability for web data collection workflows using Scrapfly's scraping, screenshot, and extraction APIs. Enables data engineers and researchers to collect, extract, and transform web content a
  name: Web Data Collection
  slug: web-data-collection
common: []
created: '2025-02-08'
description: 'Scrapfly is a web scraping API platform that enables effortless collection of web data with battle-tested APIs that scale. It provides capabilities for scraping web pages, capturing screenshots, and extracting structured data with AI assistance to handle anti-bot measures and JavaScript rendering. One API key unlocks five APIs: Web Scraping (anti-bot unblocker), Cloud Browser (CDP), Screenshot, Extraction, and Crawler. Scrapfly operates globally with proxies across 190+ countries.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Scrapfly Context
  property_count: 15
  slug: scrapfly-context
layout: provider
modified: '2026-05-02'
name: Scrapfly
rules:
- name: Scrapfly API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 5
  slug: scrapfly-rules
skills: []
slug: scrapfly
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: scrapfly\nname: Scrapfly\ndescription: >-\n  Scrapfly is a web scraping API platform that enables effortless collection of\n  web data with battle-tested APIs that scale. It provides capabilities for\n  scraping web pages, capturing screenshots, and extracting structured data\n  with AI assistance to handle anti-bot measures and JavaScript rendering.\n  One API key unlocks five APIs: Web Scraping (anti-bot unblocker), Cloud\n  Browser (CDP), Screenshot, Extraction, and Crawler. Scrapfly operates globally\n  with proxies across 190+ countries.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - Data Extraction\n  - Screenshots\n  - Web Scraping\n  - Proxies\n  - Browser Automation\ncreated: '2025-02-08'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: scrapfly:scrape-api\n\
  \    name: Scrapfly Scrape API\n    description: >-\n      The core web scraping API that fetches any URL with anti-bot bypass,\n      proxy rotation, and JavaScript rendering. Supports GET, POST, PUT,\n      PATCH, HEAD, and OPTIONS methods. Returns clean HTML, markdown, JSON,\n      or raw content. Features include session management, caching, custom\n      headers, DNS customization, SSL info retrieval, webhooks, and\n      structured data extraction with LLM assistance.\n    humanURL: https://scrapfly.io/docs/scrape-api/getting-started\n    tags:\n      - Web Scraping\n      - Anti-Bot\n      - Proxies\n      - JavaScript Rendering\n    properties:\n      - type: Documentation\n        url: https://scrapfly.io/docs/scrape-api\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/openapi/scrapfly-scrape-openapi.yml\n      - type: SpectralRules\n        url: https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/rules/scrapfly-rules.yml\n\
  \      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/json-schema/scrapfly-scrape-response-schema.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/json-ld/scrapfly-context.jsonld\n  - aid: scrapfly:screenshot-api\n    name: Scrapfly Screenshot API\n    description: >-\n      Capture screenshots of web pages with full-page or element-specific\n      capture using CSS selectors. Supports JavaScript rendering, viewport\n      configuration, and screenshot of dynamic content. The base URL for\n      screenshots is https://api.scrapfly.io/screenshot.\n    humanURL: https://scrapfly.io/docs/screenshot-api/getting-started\n    tags:\n      - Screenshots\n      - Web Scraping\n      - Browser Automation\n    properties:\n      - type: Documentation\n        url: https://scrapfly.io/docs/screenshot-api/getting-started\n  - aid: scrapfly:extraction-api\n    name: Scrapfly\
  \ Extraction API\n    description: >-\n      AI-powered structured data extraction from HTML content. Supports\n      template-based extraction, LLM prompt-driven extraction, and\n      auto-extraction using predefined models for common content types.\n    humanURL: https://scrapfly.io/docs/scrape-api/extraction\n    tags:\n      - Data Extraction\n      - AI\n      - Structured Data\n    properties:\n      - type: Documentation\n        url: https://scrapfly.io/docs/scrape-api/extraction\n  - aid: scrapfly:crawler-api\n    name: Scrapfly Crawler API\n    description: >-\n      Web crawling API (currently in early access) that enables crawling\n      entire websites with advanced configuration for depth control and\n      content filtering. Outputs in WARC format for comprehensive web\n      archive support.\n    humanURL: https://scrapfly.io/docs\n    tags:\n      - Web Crawling\n      - Data Collection\n      - WARC\n    properties:\n      - type: Documentation\n        url: https://scrapfly.io/docs\n\
  \  - aid: scrapfly:cloud-browser-api\n    name: Scrapfly Cloud Browser API\n    description: >-\n      Headless browser automation API (currently in beta) compatible with\n      Playwright, Puppeteer, and Selenium frameworks. Enables complex browser\n      interactions, JavaScript execution, and file download capture.\n    humanURL: https://scrapfly.io/docs\n    tags:\n      - Browser Automation\n      - Playwright\n      - Puppeteer\n      - Selenium\n    properties:\n      - type: Documentation\n        url: https://scrapfly.io/docs\n  - aid: scrapfly:sdks\n    name: Scrapfly SDKs\n    description: >-\n      Official SDKs for Python, TypeScript, Go, Rust, and Scrapy with full\n      feature coverage across every language including scrape, screenshot,\n      extract, and crawl capabilities.\n    humanURL: https://scrapfly.io/docs/sdk\n    tags:\n      - SDK\n      - Python\n      - TypeScript\n      - Go\n      - Rust\n    properties:\n      - type: Documentation\n        url: https://scrapfly.io/docs/sdk\n\
  \      - type: PythonSDK\n        url: https://scrapfly.io/docs/sdk/python\n      - type: GitHubOrg\n        url: https://github.com/scrapfly\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/apis.yml
tags:
- AI
- Data Extraction
- Screenshots
- Web Scraping
- Proxies
- Browser Automation
url: https://raw.githubusercontent.com/api-evangelist/scrapfly/refs/heads/main/apis.yml
use_cases: []
---
