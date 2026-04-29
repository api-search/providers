---
api_count: 2
apis:
- description: The Crawlee JavaScript SDK is a Node.js/TypeScript library for building reliable web scrapers and crawlers. It provides a family of crawler classes - BasicCrawler, HttpCrawler, CheerioCrawler, JSDOMCr
  name: Crawlee JavaScript SDK
  slug: crawlee-javascript-sdk
- description: The Crawlee Python SDK is a Python library for building reliable web scrapers and crawlers. It offers BasicCrawler, HttpCrawler, BeautifulSoupCrawler, ParselCrawler, PlaywrightCrawler, and Adaptive cr
  name: Crawlee Python SDK
  slug: crawlee-python-sdk
common:
- title: ''
  type: Website
  url: https://crawlee.dev/
- title: ''
  type: Documentation
  url: https://crawlee.dev/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apify
- title: ''
  type: GitHubRepository
  url: https://github.com/apify/crawlee
- title: ''
  type: Blog
  url: https://crawlee.dev/blog
- title: ''
  type: ChangeLog
  url: https://github.com/apify/crawlee/releases
- title: ''
  type: Discord
  url: https://discord.gg/jyEM2PRvMU
- title: ''
  type: Community
  url: https://crawlee.dev/discord
- title: ''
  type: License
  url: https://github.com/apify/crawlee/blob/master/LICENSE.md
- title: ''
  type: Apify
  url: https://apify.com/
created: '2025-02-08'
description: Crawlee is an open-source web scraping and crawling library maintained by Apify, providing a unified set of crawler classes, request queues, datasets, and key-value stores for building reliable scrapers. It is available for both JavaScript/TypeScript (Node.js) and Python, offering HTTP, Cheerio, JSDOM, LinkeDOM, Puppeteer, Playwright, and Stagehand crawler implementations along with proxy and session management utilities for production-grade scraping.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Crawlee
skills: []
slug: crawlee
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: crawlee\nname: Crawlee\nx-type: opensource\ndescription: >-\n  Crawlee is an open-source web scraping and crawling library maintained by\n  Apify, providing a unified set of crawler classes, request queues,\n  datasets, and key-value stores for building reliable scrapers. It is\n  available for both JavaScript/TypeScript (Node.js) and Python, offering\n  HTTP, Cheerio, JSDOM, LinkeDOM, Puppeteer, Playwright, and Stagehand\n  crawler implementations along with proxy and session management\n  utilities for production-grade scraping.\nurl: https://raw.githubusercontent.com/api-evangelist/crawlee/refs/heads/main/apis.yml\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache 2.0\n  - Apify\n  - Browser Automation\n  - Crawlers\n  - Harvesting\n  - JavaScript\n  - Node.js\n  - Open Source\n  - Playwright\n  - Puppeteer\n  - Python\n  - Scraping\n  - Web\ncreated: '2025-02-08'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\n\
  type: Index\naccess: Public\nposition: Provider\napis:\n  - aid: crawlee:crawlee-javascript-sdk\n    name: Crawlee JavaScript SDK\n    description: >-\n      The Crawlee JavaScript SDK is a Node.js/TypeScript library for building\n      reliable web scrapers and crawlers. It provides a family of crawler\n      classes - BasicCrawler, HttpCrawler, CheerioCrawler, JSDOMCrawler,\n      LinkeDOMCrawler, PuppeteerCrawler, PlaywrightCrawler, and\n      AdaptivePlaywrightCrawler - along with shared infrastructure for\n      AutoscaledPool resource management, proxy rotation, session pooling,\n      RequestQueue task queuing, Dataset result storage, and KeyValueStore\n      unstructured data persistence. Crawlee handles retries, error\n      recovery, request fingerprinting, and statistics tracking out of the\n      box, allowing developers to focus on extraction logic.\n    humanURL: https://crawlee.dev/js\n    properties:\n      - type: Documentation\n        url: https://crawlee.dev/js\n  \
  \    - type: Reference\n        url: https://crawlee.dev/js/api\n      - type: GettingStarted\n        url: https://crawlee.dev/js/docs/quick-start\n      - type: GitHubRepository\n        url: https://github.com/apify/crawlee\n      - type: NpmPackage\n        url: https://www.npmjs.com/package/crawlee\n    tags:\n      - Browser Automation\n      - Cheerio\n      - JavaScript\n      - Node.js\n      - Playwright\n      - Puppeteer\n      - Scraping\n      - TypeScript\n  - aid: crawlee:crawlee-python-sdk\n    name: Crawlee Python SDK\n    description: >-\n      The Crawlee Python SDK is a Python library for building reliable web\n      scrapers and crawlers. It offers BasicCrawler, HttpCrawler,\n      BeautifulSoupCrawler, ParselCrawler, PlaywrightCrawler, and Adaptive\n      crawlers built on top of asyncio, along with shared infrastructure\n      for proxy rotation, session pooling, RequestQueue, Dataset, and\n      KeyValueStore. The Python SDK targets data engineers and Python\n\
  \      developers who want the same crawler ergonomics as the JavaScript\n      version but inside the Python ecosystem.\n    humanURL: https://crawlee.dev/python\n    properties:\n      - type: Documentation\n        url: https://crawlee.dev/python\n      - type: Reference\n        url: https://crawlee.dev/python/api\n      - type: GettingStarted\n        url: https://crawlee.dev/python/docs/quick-start\n      - type: GitHubRepository\n        url: https://github.com/apify/crawlee-python\n      - type: PyPiPackage\n        url: https://pypi.org/project/crawlee/\n    tags:\n      - Asyncio\n      - BeautifulSoup\n      - Browser Automation\n      - Parsel\n      - Playwright\n      - Python\n      - Scraping\ncommon:\n  - type: Website\n    url: https://crawlee.dev/\n  - type: Documentation\n    url: https://crawlee.dev/\n  - type: GitHubOrganization\n    url: https://github.com/apify\n  - type: GitHubRepository\n    url: https://github.com/apify/crawlee\n  - type: Blog\n    url: https://crawlee.dev/blog\n\
  \  - type: ChangeLog\n    url: https://github.com/apify/crawlee/releases\n  - type: Discord\n    url: https://discord.gg/jyEM2PRvMU\n  - type: Community\n    url: https://crawlee.dev/discord\n  - type: License\n    url: https://github.com/apify/crawlee/blob/master/LICENSE.md\n  - type: Apify\n    url: https://apify.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/crawlee/refs/heads/main/apis.yml
tags:
- Apache 2.0
- Apify
- Browser Automation
- Crawlers
- Harvesting
- JavaScript
- Node.js
- Open Source
- Playwright
- Puppeteer
- Python
- Scraping
- Web
url: https://raw.githubusercontent.com/api-evangelist/crawlee/refs/heads/main/apis.yml
use_cases: []
---
