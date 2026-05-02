---
api_count: 3
api_specs:
- filename: swagger.yaml
  format: yaml
  label: HAProxy Data Plane API
  slug: haproxy-data-plane-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/haproxytech/dataplaneapi/master/swagger.yaml
apis:
- description: The HAProxy Data Plane API is a REST API for managing HAProxy configuration dynamically. It allows runtime configuration of frontends, backends, servers, ACLs, and other HAProxy objects without requir
  name: HAProxy Data Plane API
  slug: haproxy-data-plane-api
- description: 'The HAProxy Runtime API (formerly known as the stats socket) is a socket-based interface for dynamically managing HAProxy at runtime. It allows operators to enable or disable servers, adjust weights, '
  name: HAProxy Runtime API
  slug: haproxy-runtime-api
- description: The HAProxy Kubernetes Ingress Controller implements routing rules defined in Kubernetes Ingress resources, dynamically updating HAProxy configuration as pods are added or removed from the cluster. It
  name: HAProxy Kubernetes Ingress Controller
  slug: haproxy-kubernetes-ingress-controller
common:
- title: ''
  type: Website
  url: https://www.haproxy.org/
- title: ''
  type: Documentation
  url: https://docs.haproxy.org/
- title: ''
  type: GitHub Organization
  url: https://github.com/haproxy
- title: ''
  type: GitHub Organization
  url: https://github.com/haproxytech
- title: ''
  type: Community
  url: https://discourse.haproxy.org/
- title: ''
  type: Blog
  url: https://www.haproxy.com/blog/
- title: ''
  type: Support
  url: https://www.haproxy.com/support/support-options
- title: ''
  type: Terms of Service
  url: https://www.haproxy.com/legal
created: '2026-03-16'
description: HAProxy is a free, very fast and reliable reverse-proxy offering high availability, load balancing, and proxying for TCP and HTTP-based applications. It exposes a Data Plane API for dynamic configuration management and a stats socket for runtime management.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-18'
name: HAProxy
skills: []
slug: haproxy
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: haproxy\nname: HAProxy\ndescription: >-\n  HAProxy is a free, very fast and reliable reverse-proxy offering high\n  availability, load balancing, and proxying for TCP and HTTP-based\n  applications. It exposes a Data Plane API for dynamic configuration\n  management and a stats socket for runtime management.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - High Availability\n  - Load Balancing\n  - Networking\n  - Reverse Proxy\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/haproxy/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-03-18'\nspecificationVersion: '0.19'\napis:\n  - aid: haproxy:haproxy-data-plane-api\n    name: HAProxy Data Plane API\n    description: >-\n      The HAProxy Data Plane API is a REST API for managing HAProxy\n      configuration dynamically. It allows runtime configuration of\n      frontends, backends, servers, ACLs, and other HAProxy objects\n      without\
  \ requiring configuration file changes or restarts.\n    humanURL: https://www.haproxy.com/documentation/dataplaneapi/latest/\n    baseURL: https://localhost:5555/v2\n    tags:\n      - Configuration\n      - Load Balancing\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://www.haproxy.com/documentation/dataplaneapi/latest/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/haproxytech/dataplaneapi/master/swagger.yaml\n      - type: Getting Started\n        url: https://www.haproxy.com/documentation/dataplaneapi/latest/#getting-started\n      - type: GitHubRepository\n        url: https://github.com/haproxytech/dataplaneapi\n      - type: Change Log\n        url: https://github.com/haproxytech/dataplaneapi/releases\n  - aid: haproxy:haproxy-runtime-api\n    name: HAProxy Runtime API\n    description: >-\n      The HAProxy Runtime API (formerly known as the stats socket) is a\n      socket-based interface for dynamically managing HAProxy\
  \ at runtime. It\n      allows operators to enable or disable servers, adjust weights, inspect\n      stick tables, view statistics, and perform other live configuration\n      changes without reloading the process.\n    humanURL: https://www.haproxy.com/documentation/haproxy-runtime-api/\n    baseURL: https://localhost\n    tags:\n      - Load Balancing\n      - Runtime Management\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://www.haproxy.com/documentation/haproxy-runtime-api/\n      - type: Reference\n        url: https://www.haproxy.com/documentation/haproxy-runtime-api/reference/\n  - aid: haproxy:haproxy-kubernetes-ingress-controller\n    name: HAProxy Kubernetes Ingress Controller\n    description: >-\n      The HAProxy Kubernetes Ingress Controller implements routing rules defined\n      in Kubernetes Ingress resources, dynamically updating HAProxy configuration\n      as pods are added or removed from the cluster. It supports the Gateway\
  \ API,\n      custom resources, and certificate management via the HAProxy Runtime API.\n    humanURL: https://www.haproxy.com/documentation/kubernetes-ingress/\n    baseURL: https://localhost\n    tags:\n      - Ingress Controller\n      - Kubernetes\n      - Load Balancing\n    properties:\n      - type: Documentation\n        url: https://www.haproxy.com/documentation/kubernetes-ingress/\n      - type: Getting Started\n        url: https://www.haproxy.com/documentation/kubernetes-ingress/overview/\n      - type: Change Log\n        url: https://www.haproxy.com/documentation/kubernetes-ingress/community/release-notes/\n      - type: GitHubRepository\n        url: https://github.com/haproxytech/kubernetes-ingress\ncommon:\n  - type: Website\n    url: https://www.haproxy.org/\n  - type: Documentation\n    url: https://docs.haproxy.org/\n  - type: GitHub Organization\n    url: https://github.com/haproxy\n  - type: GitHub Organization\n    url: https://github.com/haproxytech\n  - type: Community\n\
  \    url: https://discourse.haproxy.org/\n  - type: Blog\n    url: https://www.haproxy.com/blog/\n  - type: Support\n    url: https://www.haproxy.com/support/support-options\n  - type: Terms of Service\n    url: https://www.haproxy.com/legal\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/haproxy/refs/heads/main/apis.yml
tags:
- High Availability
- Load Balancing
- Networking
- Reverse Proxy
url: https://raw.githubusercontent.com/api-evangelist/haproxy/refs/heads/main/apis.yml
use_cases: []
---
