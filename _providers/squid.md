---
api_count: 2
api_specs:
- filename: squid-cache-manager-openapi.yml
  format: yaml
  label: Squid Cache Manager API
  slug: squid-cache-manager
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/openapi/squid-cache-manager-openapi.yml
apis:
- description: The Squid Cache Manager is a built-in HTTP management interface that exposes internal statistics, cache operations, and runtime configuration via HTTP requests. It provides endpoints for retrieving ca
  name: Squid Cache Manager API
  slug: squid-cache-manager
- description: Squid provides extensive access control configuration through its squid.conf file and runtime reload capabilities. The access control system supports ACLs for IP addresses, domain names, URL patterns,
  name: Squid Access Control Configuration API
  slug: squid-access-control
capabilities:
- description: Unified workflow capability for managing and monitoring a Squid caching proxy. Combines cache statistics, connection monitoring, configuration management, and operational commands into a single workfl
  name: Squid Proxy Management
  slug: proxy-management
common:
- title: ''
  type: Website
  url: http://www.squid-cache.org/
- title: ''
  type: Documentation
  url: http://www.squid-cache.org/Doc/
- title: ''
  type: GitHub Organization
  url: https://github.com/squid-cache
- title: ''
  type: Changelog
  url: http://www.squid-cache.org/Versions/
- title: ''
  type: FAQ
  url: http://wiki.squid-cache.org/SquidFaq
- title: ''
  type: Mailing List
  url: http://www.squid-cache.org/Support/mailing-lists.html
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/openapi/squid-cache-manager-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-schema/squid-cache-stats-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-structure/squid-cache-stats-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-ld/squid-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/rules/squid-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/capabilities/proxy-management.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/vocabulary/squid-vocabulary.yml
created: '2026-03-27'
description: Squid is a high-performance caching and forwarding HTTP web proxy used for content caching, access control, and bandwidth management. It supports HTTP, HTTPS, FTP, and other protocols, providing caching proxy features, access control lists, SSL/TLS inspection, and web content filtering for enterprises and internet service providers.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 28
  name: Squid Context
  property_count: 4
  slug: squid-context
layout: provider
modified: '2026-05-02'
name: Squid
rules:
- name: Squid API Rules
  rule_count: 6
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 4
  slug: squid-rules
skills: []
slug: squid
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: squid\nname: Squid\ndescription: >-\n  Squid is a high-performance caching and forwarding HTTP web proxy used for\n  content caching, access control, and bandwidth management. It supports HTTP,\n  HTTPS, FTP, and other protocols, providing caching proxy features, access\n  control lists, SSL/TLS inspection, and web content filtering for enterprises\n  and internet service providers.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Caching Proxy\n  - Proxy\n  - HTTP Proxy\n  - Web Cache\n  - Access Control\n  - Content Filtering\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: squid:squid-cache-manager\n    name: Squid Cache Manager API\n    description: >-\n      The Squid Cache Manager is a built-in HTTP management interface that\n      exposes internal statistics, cache operations,\
  \ and runtime configuration\n      via HTTP requests. It provides endpoints for retrieving cache statistics,\n      managing active connections, viewing access control lists, and performing\n      cache operations such as reconfigure and log rotation.\n    humanURL: http://www.squid-cache.org/Doc/config/cachemgr_passwd/\n    baseURL: http://localhost:3128/squid-internal-mgr\n    tags:\n      - Caching Proxy\n      - Cache Manager\n      - HTTP Proxy\n      - Web Cache\n    properties:\n      - type: Documentation\n        url: http://www.squid-cache.org/Doc/\n      - type: Getting Started\n        url: http://www.squid-cache.org/Doc/config/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/openapi/squid-cache-manager-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-schema/squid-cache-stats-schema.json\n    contact:\n      -\
  \ FN: Squid Project\n        url: http://www.squid-cache.org/Support/\n  - aid: squid:squid-access-control\n    name: Squid Access Control Configuration API\n    description: >-\n      Squid provides extensive access control configuration through its squid.conf\n      file and runtime reload capabilities. The access control system supports ACLs\n      for IP addresses, domain names, URL patterns, user authentication, time-of-day\n      restrictions, and MIME type filtering.\n    humanURL: http://www.squid-cache.org/Doc/config/acl/\n    baseURL: http://localhost:3128/squid-internal-mgr\n    tags:\n      - Access Control\n      - Configuration\n      - HTTP Proxy\n    properties:\n      - type: Documentation\n        url: http://www.squid-cache.org/Doc/config/acl/\n      - type: Getting Started\n        url: http://www.squid-cache.org/Doc/config/\ncommon:\n  - type: Website\n    url: http://www.squid-cache.org/\n  - type: Documentation\n    url: http://www.squid-cache.org/Doc/\n  - type:\
  \ GitHub Organization\n    url: https://github.com/squid-cache\n  - type: Changelog\n    url: http://www.squid-cache.org/Versions/\n  - type: FAQ\n    url: http://wiki.squid-cache.org/SquidFaq\n  - type: Mailing List\n    url: http://www.squid-cache.org/Support/mailing-lists.html\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/openapi/squid-cache-manager-openapi.yml\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-schema/squid-cache-stats-schema.json\n  - type: JSONStructure\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-structure/squid-cache-stats-structure.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/json-ld/squid-context.jsonld\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/rules/squid-rules.yml\n\
  \  - type: NaftikoCapabilities\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/capabilities/proxy-management.yaml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/vocabulary/squid-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/apis.yml
tags:
- Caching Proxy
- Proxy
- HTTP Proxy
- Web Cache
- Access Control
- Content Filtering
url: https://raw.githubusercontent.com/api-evangelist/squid/refs/heads/main/apis.yml
use_cases: []
---
