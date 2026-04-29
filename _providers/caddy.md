---
api_count: 2
apis:
- description: 'Caddy is an open-source HTTP/2 and HTTP/3 web server and reverse proxy that obtains TLS certificates automatically via Let''s Encrypt and ZeroSSL. Configured via a native JSON config, a human-friendly '
  name: Caddy Web Server
  slug: caddy-web-server
- description: Caddy exposes a RESTful administration API on localhost:2019 by default for dynamically loading and modifying server configuration at runtime without restarts. Endpoints support loading full JSON conf
  name: Caddy Admin API
  slug: caddy-admin-api
common:
- title: ''
  type: Website
  url: https://caddyserver.com/
- title: ''
  type: Documentation
  url: https://caddyserver.com/docs/
- title: ''
  type: GitHub Organization
  url: https://github.com/caddyserver
- title: ''
  type: Community Forum
  url: https://caddy.community/
- title: ''
  type: Download
  url: https://caddyserver.com/download
- title: ''
  type: Sponsors
  url: https://github.com/sponsors/mholt
created: '2026-03-27'
description: Caddy is a modern, extensible, open-source web server and reverse proxy written in Go that provides automatic HTTPS via Let's Encrypt, a dynamic JSON-based admin API, a human-friendly Caddyfile configuration format, and a modular architecture with a rich ecosystem of plugins for authentication, observability, and custom behavior.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Caddy
skills: []
slug: caddy
solutions: []
source_yaml: "aid: caddy\nname: Caddy\ndescription: >-\n  Caddy is a modern, extensible, open-source web server and reverse proxy\n  written in Go that provides automatic HTTPS via Let's Encrypt, a dynamic\n  JSON-based admin API, a human-friendly Caddyfile configuration format, and a\n  modular architecture with a rich ecosystem of plugins for authentication,\n  observability, and custom behavior.\ntype: Index\nx-type: opensource\nposition: Consumer\naccess: Open Source\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automatic HTTPS\n  - Go\n  - Load Balancer\n  - Reverse Proxy\n  - TLS\n  - Web Server\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/caddy/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: caddy:caddy-web-server\n    name: Caddy Web Server\n    description: >-\n      Caddy is an open-source HTTP/2 and HTTP/3 web server and reverse proxy\n      that\
  \ obtains TLS certificates automatically via Let's Encrypt and ZeroSSL.\n      Configured via a native JSON config, a human-friendly Caddyfile, or\n      dynamically via the admin API. Built on a modular architecture that\n      supports custom modules for virtually any HTTP behavior.\n    humanURL: https://caddyserver.com/\n    tags:\n      - Automatic HTTPS\n      - Go\n      - Reverse Proxy\n      - TLS\n      - Web Server\n    properties:\n      - type: Documentation\n        url: https://caddyserver.com/docs/\n      - type: Getting Started\n        url: https://caddyserver.com/docs/getting-started\n      - type: GitHub Repository\n        url: https://github.com/caddyserver/caddy\n      - type: Download\n        url: https://caddyserver.com/download\n    x-features:\n      - Automatic HTTPS via Let's Encrypt and ZeroSSL\n      - HTTP/1.1, HTTP/2, HTTP/3 (QUIC) support\n      - Dynamic JSON configuration\n      - Human-friendly Caddyfile format\n      - Reverse proxy with load balancing\n\
  \      - Static file serving with automatic compression\n      - Modular architecture with plugins\n      - On-demand TLS certificates\n      - Wildcard and DNS-01 challenge support\n    x-use-cases:\n      - Production web and API hosting\n      - Zero-config HTTPS reverse proxy\n      - Multi-tenant platforms with on-demand TLS\n      - Static website hosting with SSL\n      - Edge routing for microservices\n  - aid: caddy:caddy-admin-api\n    name: Caddy Admin API\n    description: >-\n      Caddy exposes a RESTful administration API on localhost:2019 by default\n      for dynamically loading and modifying server configuration at runtime\n      without restarts. Endpoints support loading full JSON configs, traversing\n      and mutating specific config paths, adapting Caddyfile to JSON, and\n      querying PKI and reverse proxy state.\n    humanURL: https://caddyserver.com/docs/api\n    baseURL: http://localhost:2019\n    tags:\n      - Admin API\n      - Configuration\n      - REST\n\
  \    properties:\n      - type: Documentation\n        url: https://caddyserver.com/docs/api\n      - type: JSON Config Structure\n        url: https://caddyserver.com/docs/json/\n      - type: Modules Reference\n        url: https://caddyserver.com/docs/modules/\n      - type: API Tutorial\n        url: https://caddyserver.com/docs/api-tutorial\n    x-features:\n      - POST /load for full config replacement\n      - GET/POST/PUT/PATCH/DELETE /config/[path] for granular updates\n      - POST /adapt to convert Caddyfile to JSON without loading\n      - POST /stop for graceful shutdown\n      - GET /pki/ca/{id} for internal CA inspection\n      - GET /reverse_proxy/upstreams for upstream status\n      - ETag and If-Match concurrency control\n    x-use-cases:\n      - Dynamic configuration in orchestrated environments\n      - Multi-tenant SaaS with per-tenant routes\n      - Zero-downtime config changes\n      - Integration with service discovery\n      - Observability of upstream health\n\
  common:\n  - type: Website\n    url: https://caddyserver.com/\n  - type: Documentation\n    url: https://caddyserver.com/docs/\n  - type: GitHub Organization\n    url: https://github.com/caddyserver\n  - type: Community Forum\n    url: https://caddy.community/\n  - type: Download\n    url: https://caddyserver.com/download\n  - type: Sponsors\n    url: https://github.com/sponsors/mholt\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/caddy/refs/heads/main/apis.yml
tags:
- Automatic HTTPS
- Go
- Load Balancer
- Reverse Proxy
- TLS
- Web Server
url: https://raw.githubusercontent.com/api-evangelist/caddy/refs/heads/main/apis.yml
use_cases: []
---
