---
api_count: 2
api_specs:
- filename: soax-web-data-api-openapi.yml
  format: yaml
  label: SOAX Web Data API
  slug: soax-web-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/soax/refs/heads/main/openapi/soax-web-data-api-openapi.yml
- filename: soax-proxy-management-api-openapi.yml
  format: yaml
  label: SOAX Proxy Management API
  slug: soax-proxy-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/soax/refs/heads/main/openapi/soax-proxy-management-api-openapi.yml
apis:
- description: 'The SOAX Web Data API extracts fully rendered HTML, screenshots, XHR responses, and structured data from any public website. It handles JavaScript rendering, CAPTCHA solving, fingerprinting, headless '
  name: SOAX Web Data API
  slug: soax-web-data-api
- description: The SOAX Proxy Management API enables programmatic control of proxy packages including IP whitelisting, endpoint generation, and proxy configuration for residential, mobile, and datacenter proxy pools
  name: SOAX Proxy Management API
  slug: soax-proxy-management-api
capabilities:
- description: 'Unified web data collection workflow combining SOAX''s Web Data API and Proxy Management API. Enables data engineers, analysts, and developers to scrape public web data at scale with automatic CAPTCHA '
  name: SOAX Data Collection
  slug: data-collection
common:
- title: ''
  type: Website
  url: https://soax.com/
- title: ''
  type: Documentation
  url: https://docs.soax.com/
- title: ''
  type: Help Center
  url: https://helpcenter.soax.com/
- title: ''
  type: Pricing
  url: https://soax.com/pricing
- title: ''
  type: Sign Up
  url: https://soax.com/get-started
- title: ''
  type: Blog
  url: https://soax.com/blog/
- title: ''
  type: Spectral Rules
  url: rules/soax-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/data-collection.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/soax-vocabulary.yml
- title: ''
  type: JSON-LD Context
  url: json-ld/soax-context.jsonld
- title: ''
  type: Examples
  url: examples/soax-fetch-content-example.json
created: '2025-02-21'
description: SOAX provides enterprise-grade proxy infrastructure and web data extraction APIs for developers and data teams. With 155M+ residential IPs, 33M+ mobile IPs, and 300K+ datacenter IPs across 195+ countries, SOAX enables web scraping, CAPTCHA bypass, geo-targeted data collection, and anti-bot circumvention at scale. The Web Data API handles JavaScript rendering, session management, and headless browser automation automatically.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 39
  name: Soax Context
  property_count: 0
  slug: soax-context
layout: provider
modified: '2026-05-02'
name: SOAX
rules:
- name: SOAX API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 5
  slug: soax-rules
skills: []
slug: soax
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: soax\nname: SOAX\ndescription: >-\n  SOAX provides enterprise-grade proxy infrastructure and web data extraction APIs for developers and data teams. With 155M+ residential IPs, 33M+ mobile IPs, and 300K+ datacenter IPs across 195+ countries, SOAX enables web scraping, CAPTCHA bypass, geo-targeted data collection, and anti-bot circumvention at scale. The Web Data API handles JavaScript rendering, session management, and headless browser automation automatically.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Proxy\n  - Web Scraping\n  - Residential Proxies\n  - Mobile Proxies\n  - Datacenter Proxies\n  - Data Extraction\n  - Anti-Bot Bypass\nurl: https://raw.githubusercontent.com/api-evangelist/soax/refs/heads/main/apis.yml\ncreated: '2025-02-21'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: soax:soax-web-data-api\n    name: SOAX Web Data API\n   \
  \ description: >-\n      The SOAX Web Data API extracts fully rendered HTML, screenshots, XHR responses, and structured data from any public website. It handles JavaScript rendering, CAPTCHA solving, fingerprinting, headless browsers, and anti-bot bypass automatically.\n    humanURL: https://soax.com/web-data-api\n    tags:\n      - Web Scraping\n      - Data Extraction\n      - Anti-Bot Bypass\n      - JavaScript Rendering\n    properties:\n      - type: Documentation\n        url: https://docs.soax.com/\n      - type: Getting Started\n        url: https://helpcenter.soax.com/en/articles/11297318-getting-started-with-soax-web-data-api\n      - type: OpenAPI\n        url: openapi/soax-web-data-api-openapi.yml\n      - type: JSON Schema\n        url: json-schema/soax-fetch-request-schema.json\n      - type: JSON Structure\n        url: json-structure/soax-fetch-request-structure.json\n\n  - aid: soax:soax-proxy-management-api\n    name: SOAX Proxy Management API\n    description: >-\n \
  \     The SOAX Proxy Management API enables programmatic control of proxy packages including IP whitelisting, endpoint generation, and proxy configuration for residential, mobile, and datacenter proxy pools.\n    humanURL: https://soax.com/proxies\n    tags:\n      - Proxy Management\n      - Whitelist\n      - IP Rotation\n      - Residential Proxies\n    properties:\n      - type: Documentation\n        url: https://helpcenter.soax.com/en/collections/3470979-api\n      - type: OpenAPI\n        url: openapi/soax-proxy-management-api-openapi.yml\n\ncommon:\n  - type: Website\n    url: https://soax.com/\n  - type: Documentation\n    url: https://docs.soax.com/\n  - type: Help Center\n    url: https://helpcenter.soax.com/\n  - type: Pricing\n    url: https://soax.com/pricing\n  - type: Sign Up\n    url: https://soax.com/get-started\n  - type: Blog\n    url: https://soax.com/blog/\n  - type: Spectral Rules\n    url: rules/soax-rules.yml\n  - type: Capabilities\n    url: capabilities/data-collection.yaml\n\
  \  - type: Vocabulary\n    url: vocabulary/soax-vocabulary.yml\n  - type: JSON-LD Context\n    url: json-ld/soax-context.jsonld\n  - type: Examples\n    url: examples/soax-fetch-content-example.json\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/soax/refs/heads/main/apis.yml
tags:
- Proxy
- Web Scraping
- Residential Proxies
- Mobile Proxies
- Datacenter Proxies
- Data Extraction
- Anti-Bot Bypass
url: https://raw.githubusercontent.com/api-evangelist/soax/refs/heads/main/apis.yml
use_cases: []
---
