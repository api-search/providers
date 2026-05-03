---
api_count: 3
apis:
- description: The Varnish Cache CLI management interface provides programmatic control over a running Varnish instance. It is accessible via varnishadm or TCP socket and supports configuration management (VCL load/
  name: Varnish Cache CLI API
  slug: varnish-cache
- description: Varnish ships with a suite of log-analysis tools that read from the Varnish Shared Log (VSL). Tools include varnishlog (raw log streaming), varnishncsa (NCSA/Apache log format), varnishstat (live coun
  name: Varnish Logging Tools
  slug: varnish-logging
- description: VMODs are extensions written for Varnish Cache that extend VCL capabilities. Bundled modules include blob (binary data handling), cookie (HTTP cookie parsing), directors (load balancing strategies), h
  name: Varnish Modules (VMODs)
  slug: varnish-vmods
common:
- title: ''
  type: Website
  url: https://varnish-cache.org/
- title: ''
  type: Documentation
  url: https://varnish-cache.org/docs/
- title: ''
  type: GitHub Organization
  url: https://github.com/varnishcache
- title: ''
  type: GitHub Repository
  url: https://github.com/varnishcache/varnish-cache
- title: ''
  type: ReleaseNotes
  url: https://varnish-cache.org/docs/trunk/whatsNew/
- title: ''
  type: Blog
  url: https://info.varnish-software.com/blog
- title: ''
  type: Forum
  url: https://discourse.varnish-cache.org/
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/varnish
created: '2026-03-27'
description: Varnish Cache is a high-performance HTTP accelerator and reverse proxy designed for content-heavy dynamic websites and APIs. It sits in front of web servers and caches HTTP responses to serve repeated requests without hitting the backend, dramatically reducing load and latency. Varnish is configured via VCL (Varnish Configuration Language), a domain-specific language for request/response policy, and managed through a CLI interface (varnishadm) and a set of command-line tools for logging, statistics, and monitoring.
features:
- description: Caches HTTP responses to reduce backend load and improve response times for repeated requests.
  name: HTTP Caching
- description: Domain-specific language for defining request/response handling policies with full programmability.
  name: VCL Configuration Language
- description: TCP-based management interface for runtime configuration, VCL deployment, and cache control.
  name: CLI Management Interface
- description: Configurable health checks for backends with automatic failover to healthy backends.
  name: Backend Health Probes
- description: Flexible cache invalidation via ban expressions matching any request/response attribute.
  name: Cache Invalidation (Bans)
- description: CLI commands support -j flag for structured JSON output, enabling programmatic management.
  name: JSON Output
- description: Loadable modules (VMODs) extend VCL with cookie parsing, load balancing, digest, auth, and more.
  name: VMOD Extension System
- description: Native HTTP/2 support via the h2 VMOD for modern protocol acceleration.
  name: HTTP/2 Support
- description: High-speed shared memory logging with rich request/response attributes for analysis tools.
  name: Shared Memory Log (VSL)
- description: Worker thread pool for high-throughput concurrent request handling with configurable threading.
  name: Multi-threaded Architecture
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Common deployment pairing with Nginx as backend web server behind Varnish.
  name: Nginx
- description: Classic deployment with Apache as origin server behind Varnish Cache.
  name: Apache HTTP Server
- description: Deployable as a sidecar or DaemonSet in Kubernetes clusters for service-level caching.
  name: Kubernetes
- description: Varnish statistics exportable via varnish_exporter for Prometheus scraping.
  name: Prometheus
- description: Community dashboards available for Varnish Cache statistics via Prometheus/Grafana.
  name: Grafana
- description: Deep integration with Drupal Cache Tags for efficient purging of cached pages.
  name: Drupal
- description: VCL configurations and plugins available for WordPress caching integration.
  name: WordPress
- description: Fastly CDN is built on Varnish Cache; Fastly VCL is a fork of Varnish VCL.
  name: Fastly
layout: provider
modified: '2026-05-03'
name: Varnish Cache
skills: []
slug: varnish
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: varnish\nname: Varnish Cache\ndescription: >-\n  Varnish Cache is a high-performance HTTP accelerator and reverse proxy designed\n  for content-heavy dynamic websites and APIs. It sits in front of web servers and\n  caches HTTP responses to serve repeated requests without hitting the backend,\n  dramatically reducing load and latency. Varnish is configured via VCL (Varnish\n  Configuration Language), a domain-specific language for request/response policy,\n  and managed through a CLI interface (varnishadm) and a set of command-line tools\n  for logging, statistics, and monitoring.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Caching\n  - Caching Proxy\n  - Content Delivery\n  - HTTP Accelerator\n  - Open Source\n  - Proxy\n  - Reverse Proxy\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/varnish/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\n\
  apis:\n  - aid: varnish:varnish-cache\n    name: Varnish Cache CLI API\n    description: >-\n      The Varnish Cache CLI management interface provides programmatic control\n      over a running Varnish instance. It is accessible via varnishadm or TCP\n      socket and supports configuration management (VCL load/use/discard),\n      backend health control, cache ban/invalidation, parameter tuning, and\n      process management. Commands can return JSON output with the -j flag.\n    humanURL: https://varnish-cache.org/docs/trunk/reference/varnish-cli.html\n    tags:\n      - Cache Management\n      - Caching\n      - CLI\n      - Configuration\n      - Reverse Proxy\n    properties:\n      - type: Documentation\n        url: https://varnish-cache.org/docs/trunk/reference/varnish-cli.html\n      - type: GettingStarted\n        url: https://varnish-cache.org/docs/trunk/users-guide/run_cli.html\n      - type: APIReference\n        url: https://varnish-cache.org/docs/trunk/reference/varnishadm.html\n\
  \  - aid: varnish:varnish-logging\n    name: Varnish Logging Tools\n    description: >-\n      Varnish ships with a suite of log-analysis tools that read from the Varnish\n      Shared Log (VSL). Tools include varnishlog (raw log streaming), varnishncsa\n      (NCSA/Apache log format), varnishstat (live counters), varnishtop\n      (real-time activity display), and varnishhist (response time histogram).\n    humanURL: https://varnish-cache.org/docs/trunk/reference/\n    tags:\n      - Logging\n      - Monitoring\n      - Observability\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://varnish-cache.org/docs/trunk/reference/varnishlog.html\n      - type: APIReference\n        url: https://varnish-cache.org/docs/trunk/reference/varnishstat.html\n  - aid: varnish:varnish-vmods\n    name: Varnish Modules (VMODs)\n    description: >-\n      VMODs are extensions written for Varnish Cache that extend VCL capabilities.\n      Bundled modules include blob (binary\
  \ data handling), cookie (HTTP cookie\n      parsing), directors (load balancing strategies), h2 (HTTP/2 control),\n      proxy (PROXY protocol support), purge (cache purging), std (standard utility\n      functions), and unix (Unix socket support). Additional community VMODs are\n      available for headers, digest, auth, and more.\n    humanURL: https://varnish-cache.org/docs/trunk/reference/vmod.html\n    tags:\n      - Extensions\n      - Modules\n      - Plugins\n      - VMODs\n    properties:\n      - type: Documentation\n        url: https://varnish-cache.org/docs/trunk/reference/vmod.html\n      - type: GitHub Repository\n        url: https://github.com/varnishcache/varnish-cache\ncommon:\n  - type: Website\n    url: https://varnish-cache.org/\n  - type: Documentation\n    url: https://varnish-cache.org/docs/\n  - type: GitHub Organization\n    url: https://github.com/varnishcache\n  - type: GitHub Repository\n    url: https://github.com/varnishcache/varnish-cache\n  - type: ReleaseNotes\n\
  \    url: https://varnish-cache.org/docs/trunk/whatsNew/\n  - type: Blog\n    url: https://info.varnish-software.com/blog\n  - type: Forum\n    url: https://discourse.varnish-cache.org/\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/varnish\n  - type: Features\n    data:\n      - name: HTTP Caching\n        description: Caches HTTP responses to reduce backend load and improve response times for repeated requests.\n      - name: VCL Configuration Language\n        description: Domain-specific language for defining request/response handling policies with full programmability.\n      - name: CLI Management Interface\n        description: TCP-based management interface for runtime configuration, VCL deployment, and cache control.\n      - name: Backend Health Probes\n        description: Configurable health checks for backends with automatic failover to healthy backends.\n      - name: Cache Invalidation (Bans)\n        description: Flexible cache invalidation\
  \ via ban expressions matching any request/response attribute.\n      - name: JSON Output\n        description: CLI commands support -j flag for structured JSON output, enabling programmatic management.\n      - name: VMOD Extension System\n        description: Loadable modules (VMODs) extend VCL with cookie parsing, load balancing, digest, auth, and more.\n      - name: HTTP/2 Support\n        description: Native HTTP/2 support via the h2 VMOD for modern protocol acceleration.\n      - name: Shared Memory Log (VSL)\n        description: High-speed shared memory logging with rich request/response attributes for analysis tools.\n      - name: Multi-threaded Architecture\n        description: Worker thread pool for high-throughput concurrent request handling with configurable threading.\n  - type: UseCases\n    data:\n      - name: API Gateway Caching\n        description: Cache REST API responses at the edge to reduce database and application server load.\n      - name: CDN Origin Shield\n\
  \        description: Act as origin shield between CDN edge nodes and web/application servers.\n      - name: Static Asset Acceleration\n        description: Cache and serve static assets (images, JS, CSS) with long TTLs.\n      - name: A/B Testing\n        description: Use VCL to route traffic fractions to different backends for controlled experiments.\n      - name: DDoS Mitigation\n        description: Absorb traffic spikes and rate-limit abusive clients via VCL policies.\n      - name: Authentication Offloading\n        description: Offload token validation and session checks to VCL logic at the cache layer.\n      - name: Request Routing\n        description: Route requests to different backend pools based on URL patterns, headers, or cookies.\n  - type: Integrations\n    data:\n      - name: Nginx\n        description: Common deployment pairing with Nginx as backend web server behind Varnish.\n      - name: Apache HTTP Server\n        description: Classic deployment with Apache as\
  \ origin server behind Varnish Cache.\n      - name: Kubernetes\n        description: Deployable as a sidecar or DaemonSet in Kubernetes clusters for service-level caching.\n      - name: Prometheus\n        description: Varnish statistics exportable via varnish_exporter for Prometheus scraping.\n      - name: Grafana\n        description: Community dashboards available for Varnish Cache statistics via Prometheus/Grafana.\n      - name: Drupal\n        description: Deep integration with Drupal Cache Tags for efficient purging of cached pages.\n      - name: WordPress\n        description: VCL configurations and plugins available for WordPress caching integration.\n      - name: Fastly\n        description: Fastly CDN is built on Varnish Cache; Fastly VCL is a fork of Varnish VCL.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/varnish/refs/heads/main/apis.yml
tags:
- Caching
- Caching Proxy
- Content Delivery
- HTTP Accelerator
- Open Source
- Proxy
- Reverse Proxy
url: https://raw.githubusercontent.com/api-evangelist/varnish/refs/heads/main/apis.yml
use_cases:
- description: Cache REST API responses at the edge to reduce database and application server load.
  name: API Gateway Caching
- description: Act as origin shield between CDN edge nodes and web/application servers.
  name: CDN Origin Shield
- description: Cache and serve static assets (images, JS, CSS) with long TTLs.
  name: Static Asset Acceleration
- description: Use VCL to route traffic fractions to different backends for controlled experiments.
  name: A/B Testing
- description: Absorb traffic spikes and rate-limit abusive clients via VCL policies.
  name: DDoS Mitigation
- description: Offload token validation and session checks to VCL logic at the cache layer.
  name: Authentication Offloading
- description: Route requests to different backend pools based on URL patterns, headers, or cookies.
  name: Request Routing
---
