---
api_count: 4
api_specs:
- filename: coredns-health-openapi.yml
  format: yaml
  label: CoreDNS Health API
  slug: coredns-health-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coredns/refs/heads/main/openapi/coredns-health-openapi.yml
- filename: coredns-metrics-openapi.yml
  format: yaml
  label: CoreDNS Metrics API
  slug: coredns-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/coredns/refs/heads/main/openapi/coredns-metrics-openapi.yml
apis:
- description: CoreDNS implements the standard DNS protocol (RFC 1035) serving both UDP and TCP queries. In Kubernetes, it resolves service names to cluster IPs, headless services to pod IPs, and supports SRV record
  name: CoreDNS DNS Interface
  slug: coredns-dns-api
- description: 'The CoreDNS plugin framework allows extending DNS server functionality through a chain of plugins defined in the Corefile configuration. External plugins can be written in Go to add custom DNS record '
  name: CoreDNS Plugin API
  slug: coredns-plugin-api
- description: The CoreDNS health plugin exposes HTTP /health and /ready endpoints on port 8080 by default. It reports the overall health and readiness of the CoreDNS process and is used by Kubernetes liveness and r
  name: CoreDNS Health API
  slug: coredns-health-api
- description: The CoreDNS prometheus plugin exposes a Prometheus-compatible metrics endpoint at /metrics on port 9153. It provides DNS request counters, response size histograms, latency distributions, and build in
  name: CoreDNS Metrics API
  slug: coredns-metrics-api
capabilities: []
common:
- title: ''
  type: JSONSchema
  url: json-schema/coredns-corefile-schema.json
- title: ''
  type: JSONLD
  url: json-ld/coredns-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/coredns-vocabulary.yml
- title: ''
  type: Website
  url: https://coredns.io/
- title: ''
  type: Documentation
  url: https://coredns.io/manual/toc/
- title: ''
  type: GettingStarted
  url: https://coredns.io/2017/07/24/quick-start/
- title: ''
  type: GitHubOrganization
  url: https://github.com/coredns
- title: ''
  type: GitHubRepository
  url: https://github.com/coredns/coredns
- title: ''
  type: Plugins
  url: https://coredns.io/plugins/
- title: ''
  type: ExternalPlugins
  url: https://coredns.io/explugins/
- title: ''
  type: Blog
  url: https://coredns.io/blog/
- title: ''
  type: ChangeLog
  url: https://github.com/coredns/coredns/releases
- title: ''
  type: Community
  url: https://slack.cncf.io/
- title: ''
  type: License
  url: https://github.com/coredns/coredns/blob/master/LICENSE
- title: ''
  type: CNCF
  url: https://www.cncf.io/projects/coredns/
created: '2026-03-16'
description: CoreDNS is a CNCF graduated DNS server written in Go that serves as the default DNS service for Kubernetes clusters. It is flexible and extensible through a plugin architecture, supporting DNS-based service discovery, forwarding, caching, and integration with etcd, Kubernetes, and other backends. CoreDNS can serve as an authoritative DNS server or a recursive resolver, with HTTP plugins exposing health, readiness, and Prometheus metrics endpoints for Kubernetes operations.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Coredns Context
  property_count: 8
  slug: coredns-context
layout: provider
modified: '2026-04-28'
name: CoreDNS
rules:
- name: CoreDNS API Rules
  rule_count: 8
  severity_counts:
    error: 6
    hint: 0
    info: 0
    warn: 2
  slug: coredns-health-rules
- name: CoreDNS API Rules
  rule_count: 8
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 2
  slug: coredns-metrics-rules
skills: []
slug: coredns
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: coredns\nname: CoreDNS\nx-type: opensource\ndescription: >-\n  CoreDNS is a CNCF graduated DNS server written in Go that serves as the\n  default DNS service for Kubernetes clusters. It is flexible and extensible\n  through a plugin architecture, supporting DNS-based service discovery,\n  forwarding, caching, and integration with etcd, Kubernetes, and other\n  backends. CoreDNS can serve as an authoritative DNS server or a recursive\n  resolver, with HTTP plugins exposing health, readiness, and Prometheus\n  metrics endpoints for Kubernetes operations.\nurl: https://coredns.io\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Apache 2.0\n  - Cloud Native\n  - CNCF\n  - DNS\n  - Go\n  - Graduated\n  - Kubernetes\n  - Networking\n  - Open Source\n  - Plugins\n  - Prometheus\n  - Service Discovery\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.20'\ntype: Index\naccess: Public\nposition: Provider\napis:\n\
  \  - aid: coredns:coredns-dns-api\n    name: CoreDNS DNS Interface\n    description: >-\n      CoreDNS implements the standard DNS protocol (RFC 1035) serving both\n      UDP and TCP queries. In Kubernetes, it resolves service names to cluster\n      IPs, headless services to pod IPs, and supports SRV records for port\n      discovery. The Kubernetes plugin watches the API server for service and\n      endpoint changes to keep DNS records current. Additional protocol\n      bindings include DNS-over-TLS (DoT), DNS-over-HTTPS (DoH), DNS-over-QUIC\n      (DoQ), and gRPC.\n    humanURL: https://coredns.io/manual/toc/\n    properties:\n      - type: Documentation\n        url: https://coredns.io/manual/toc/\n    tags:\n      - DNS\n      - DoH\n      - DoQ\n      - DoT\n      - Kubernetes\n      - Service Discovery\n  - aid: coredns:coredns-plugin-api\n    name: CoreDNS Plugin API\n    description: >-\n      The CoreDNS plugin framework allows extending DNS server functionality\n      through\
  \ a chain of plugins defined in the Corefile configuration.\n      External plugins can be written in Go to add custom DNS record sources,\n      filtering, metrics, and middleware. Each plugin implements the Handler\n      interface to process DNS requests.\n    humanURL: https://coredns.io/explugins/\n    properties:\n      - type: Documentation\n        url: https://coredns.io/explugins/\n      - type: Reference\n        url: https://coredns.io/manual/plugins/\n    tags:\n      - Extensibility\n      - Plugins\n  - aid: coredns:coredns-health-api\n    name: CoreDNS Health API\n    description: >-\n      The CoreDNS health plugin exposes HTTP /health and /ready endpoints on\n      port 8080 by default. It reports the overall health and readiness of\n      the CoreDNS process and is used by Kubernetes liveness and readiness\n      probes to determine if the DNS server is operational.\n    humanURL: https://coredns.io/plugins/health/\n    baseURL: http://localhost:8080\n    properties:\n\
  \      - type: Documentation\n        url: https://coredns.io/plugins/health/\n      - type: ReadyDocumentation\n        url: https://coredns.io/plugins/ready/\n      - type: OpenAPI\n        url: openapi/coredns-health-openapi.yml\n      - type: Rules\n        url: rules/coredns-health-rules.yml\n      - type: Capabilities\n        url: capabilities/coredns-health-capabilities.yml\n    tags:\n      - Health Check\n      - Kubernetes\n      - Observability\n      - Readiness\n  - aid: coredns:coredns-metrics-api\n    name: CoreDNS Metrics API\n    description: >-\n      The CoreDNS prometheus plugin exposes a Prometheus-compatible metrics\n      endpoint at /metrics on port 9153. It provides DNS request counters,\n      response size histograms, latency distributions, and build information\n      metrics for monitoring CoreDNS performance and behavior.\n    humanURL: https://coredns.io/plugins/metrics/\n    baseURL: http://localhost:9153\n    properties:\n      - type: Documentation\n\
  \        url: https://coredns.io/plugins/metrics/\n      - type: OpenAPI\n        url: openapi/coredns-metrics-openapi.yml\n      - type: Rules\n        url: rules/coredns-metrics-rules.yml\n      - type: Capabilities\n        url: capabilities/coredns-metrics-capabilities.yml\n    tags:\n      - Metrics\n      - Monitoring\n      - Observability\n      - Prometheus\ncommon:\n  - type: JSONSchema\n    url: json-schema/coredns-corefile-schema.json\n  - type: JSONLD\n    url: json-ld/coredns-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/coredns-vocabulary.yml\n  - type: Website\n    url: https://coredns.io/\n  - type: Documentation\n    url: https://coredns.io/manual/toc/\n  - type: GettingStarted\n    url: https://coredns.io/2017/07/24/quick-start/\n  - type: GitHubOrganization\n    url: https://github.com/coredns\n  - type: GitHubRepository\n    url: https://github.com/coredns/coredns\n  - type: Plugins\n    url: https://coredns.io/plugins/\n  - type: ExternalPlugins\n    url:\
  \ https://coredns.io/explugins/\n  - type: Blog\n    url: https://coredns.io/blog/\n  - type: ChangeLog\n    url: https://github.com/coredns/coredns/releases\n  - type: Community\n    url: https://slack.cncf.io/\n  - type: License\n    url: https://github.com/coredns/coredns/blob/master/LICENSE\n  - type: CNCF\n    url: https://www.cncf.io/projects/coredns/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/coredns/refs/heads/main/apis.yml
tags:
- Apache 2.0
- Cloud Native
- CNCF
- DNS
- Go
- Graduated
- Kubernetes
- Networking
- Open Source
- Plugins
- Prometheus
- Service Discovery
url: https://coredns.io
use_cases: []
---
