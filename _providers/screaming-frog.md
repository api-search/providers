---
api_count: 2
apis:
- description: The Screaming Frog SEO Spider is a desktop website crawler for Windows, macOS, and Ubuntu that performs comprehensive technical SEO audits. It crawls websites to find broken links, analyze page titles
  name: Screaming Frog SEO Spider
  slug: seo-spider
- description: The Screaming Frog Log File Analyser is a free desktop tool that allows SEO professionals to upload and analyze server log files to understand how search bots are crawling a website. It identifies whi
  name: Screaming Frog Log File Analyser
  slug: log-file-analyser
common:
- title: ''
  type: Website
  url: https://www.screamingfrog.co.uk/
- title: ''
  type: Blog
  url: https://www.screamingfrog.co.uk/blog/
- title: ''
  type: Contact
  url: https://www.screamingfrog.co.uk/contact/
- title: ''
  type: Pricing
  url: https://www.screamingfrog.co.uk/seo-spider/pricing/
- title: ''
  type: Support
  url: https://www.screamingfrog.co.uk/seo-spider/faq/
created: '2026-05-02'
description: Screaming Frog is a UK-based SEO software company and search marketing agency, best known for the SEO Spider website crawler tool used by SEO professionals worldwide to perform technical SEO audits, crawl analysis, and integrations with third-party APIs. The SEO Spider integrates with Google Analytics (GA4), Google Search Console, PageSpeed Insights, Ahrefs, Majestic, Moz, OpenAI, Gemini, Ollama, and Anthropic. Screaming Frog also offers a free Log File Analyser for analyzing server log files to understand search bot behavior.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Screaming Frog Context
  property_count: 0
  slug: screaming-frog-context
layout: provider
modified: '2026-05-02'
name: Screaming Frog
skills: []
slug: screaming-frog
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: screaming-frog\nname: Screaming Frog\ndescription: >-\n  Screaming Frog is a UK-based SEO software company and search marketing agency,\n  best known for the SEO Spider website crawler tool used by SEO professionals\n  worldwide to perform technical SEO audits, crawl analysis, and integrations\n  with third-party APIs. The SEO Spider integrates with Google Analytics (GA4),\n  Google Search Console, PageSpeed Insights, Ahrefs, Majestic, Moz, OpenAI,\n  Gemini, Ollama, and Anthropic. Screaming Frog also offers a free Log File\n  Analyser for analyzing server log files to understand search bot behavior.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - SEO\n  - Search Engine Optimization\n  - Website Crawler\n  - Technical Audit\n  - Marketing\n  - Analytics\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/screaming-frog/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: screaming-frog:seo-spider\n    name: Screaming Frog SEO Spider\n    description: >-\n      The Screaming Frog SEO Spider is a desktop website crawler for Windows,\n      macOS, and Ubuntu that performs comprehensive technical SEO audits. It\n      crawls websites to find broken links, analyze page titles and meta data,\n      discover duplicate content, generate XML sitemaps, and integrate with\n      third-party APIs including Google Analytics, Google Search Console,\n      PageSpeed Insights, Ahrefs, Majestic, Moz, and AI services (OpenAI,\n      Gemini, Ollama, Anthropic). The Spider acts as an API consumer, pulling\n      external metrics and data into crawl reports.\n    humanURL: https://www.screamingfrog.co.uk/seo-spider/\n    tags:\n      - SEO\n      - Crawler\n      - Technical Audit\n      - Analytics Integration\n    properties:\n      - type: Documentation\n        url: https://www.screamingfrog.co.uk/seo-spider/user-guide/\n \
  \     - type: Pricing\n        url: https://www.screamingfrog.co.uk/seo-spider/pricing/\n      - type: ReleaseHistory\n        url: https://www.screamingfrog.co.uk/seo-spider/release-history/\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/screaming-frog/refs/heads/main/json-schema/screaming-frog-crawl-result-schema.json\n      - type: JSONStructure\n        url: https://raw.githubusercontent.com/api-evangelist/screaming-frog/refs/heads/main/json-structure/screaming-frog-crawl-result-structure.json\n      - type: JSONLDContext\n        url: https://raw.githubusercontent.com/api-evangelist/screaming-frog/refs/heads/main/json-ld/screaming-frog-context.jsonld\n      - type: Vocabulary\n        url: https://raw.githubusercontent.com/api-evangelist/screaming-frog/refs/heads/main/vocabulary/screaming-frog-vocabulary.yml\n      - type: Example\n        url: https://raw.githubusercontent.com/api-evangelist/screaming-frog/refs/heads/main/examples/screaming-frog-crawl-result-example.json\n\
  \  - aid: screaming-frog:log-file-analyser\n    name: Screaming Frog Log File Analyser\n    description: >-\n      The Screaming Frog Log File Analyser is a free desktop tool that allows\n      SEO professionals to upload and analyze server log files to understand\n      how search bots are crawling a website. It identifies which pages bots\n      visit, how frequently they crawl them, and highlights crawl budget\n      inefficiencies. Available for Windows, macOS, and Ubuntu with a paid\n      license removing crawl limits.\n    humanURL: https://www.screamingfrog.co.uk/log-file-analyser/\n    tags:\n      - SEO\n      - Log Analysis\n      - Bot Detection\n      - Crawl Analysis\n      - Crawl Budget\n    properties:\n      - type: Documentation\n        url: https://www.screamingfrog.co.uk/log-file-analyser/user-guide/\ncommon:\n  - type: Website\n    url: https://www.screamingfrog.co.uk/\n  - type: Blog\n    url: https://www.screamingfrog.co.uk/blog/\n  - type: Contact\n    url: https://www.screamingfrog.co.uk/contact/\n\
  \  - type: Pricing\n    url: https://www.screamingfrog.co.uk/seo-spider/pricing/\n  - type: Support\n    url: https://www.screamingfrog.co.uk/seo-spider/faq/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/screaming-frog/refs/heads/main/apis.yml
tags:
- SEO
- Search Engine Optimization
- Website Crawler
- Technical Audit
- Marketing
- Analytics
url: https://raw.githubusercontent.com/api-evangelist/screaming-frog/refs/heads/main/apis.yml
use_cases: []
---
