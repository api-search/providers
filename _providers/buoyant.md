---
api_count: 2
apis:
- description: Linkerd is a CNCF-graduated service mesh for Kubernetes that transparently adds mutual TLS encryption, latency-aware load balancing, retries, timeouts, circuit breaking, and observability to any Kuber
  name: Linkerd Service Mesh
  slug: linkerd
- description: Buoyant Enterprise Linkerd is the enterprise-supported distribution of Linkerd with additional features including FIPS-validated cryptography, lifecycle automation, multi-cluster networking, and enter
  name: Buoyant Enterprise Linkerd (BEL)
  slug: buoyant-enterprise-linkerd
common:
- title: ''
  type: Portal
  url: https://buoyant.io/
- title: ''
  type: Documentation
  url: https://linkerd.io/2.x/overview/
- title: ''
  type: GitHub Organization
  url: https://github.com/linkerd
- title: ''
  type: Blog
  url: https://buoyant.io/blog/
- title: ''
  type: Pricing
  url: https://buoyant.io/pricing/
- title: ''
  type: Slack
  url: https://slack.linkerd.io/
- title: ''
  type: Community
  url: https://linkerd.io/community/
created: '2026-01-02'
description: Buoyant is the creator of Linkerd, the CNCF-graduated service mesh for Kubernetes. Linkerd provides zero-trust security via mutual TLS, ultra-high availability with automated failover, and observability for microservices including AI/LLM workloads. Buoyant Enterprise Linkerd adds enterprise features including FIPS 140-2/140-3 validated encryption and multi-cluster support.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Buoyant
skills: []
slug: buoyant
solutions: []
source_yaml: "aid: buoyant\nname: Buoyant\ndescription: >-\n  Buoyant is the creator of Linkerd, the CNCF-graduated service mesh for\n  Kubernetes. Linkerd provides zero-trust security via mutual TLS, ultra-high\n  availability with automated failover, and observability for microservices\n  including AI/LLM workloads. Buoyant Enterprise Linkerd adds enterprise\n  features including FIPS 140-2/140-3 validated encryption and multi-cluster\n  support.\ntype: Index\nx-type: company\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI Observability\n  - Kubernetes\n  - Linkerd\n  - mTLS\n  - Observability\n  - Service Mesh\n  - Zero Trust\ncreated: '2026-01-02'\nmodified: '2026-04-21'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/buoyant/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: buoyant:linkerd\n    name: Linkerd Service Mesh\n    description: >-\n      Linkerd is a\
  \ CNCF-graduated service mesh for Kubernetes that transparently\n      adds mutual TLS encryption, latency-aware load balancing, retries, timeouts,\n      circuit breaking, and observability to any Kubernetes workload without code\n      changes. Supports HTTP, HTTP/2, gRPC, and TCP traffic.\n    humanURL: https://linkerd.io/\n    tags:\n      - Kubernetes\n      - mTLS\n      - Observability\n      - Service Mesh\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url: https://linkerd.io/2.x/overview/\n      - type: Website\n        url: https://linkerd.io/\n      - type: Reference\n        url: https://linkerd.io/2.x/reference/\n      - type: GitHub Repository\n        url: https://github.com/linkerd/linkerd2\n    x-features:\n      - Mutual TLS for transparent encryption and authentication\n      - Cryptographic workload identity\n      - Latency-aware load balancing\n      - Automated retries, timeouts, and circuit breaking\n      - Zone-aware routing (HAZL)\
  \ to reduce cross-zone costs\n      - Canary and blue-green deployment support\n      - AI/LLM observability for resource, tool, and prompt usage metrics\n      - Multi-cluster failover\n      - FIPS 140-2/140-3 validated encryption (Enterprise)\n    x-use-cases:\n      - Zero-trust Kubernetes networking\n      - Service-to-service mutual TLS without code changes\n      - Observability for microservices and AI workloads\n      - Multi-cluster Kubernetes deployments\n      - Migration between cloud providers\n  - aid: buoyant:buoyant-enterprise-linkerd\n    name: Buoyant Enterprise Linkerd (BEL)\n    description: >-\n      Buoyant Enterprise Linkerd is the enterprise-supported distribution of\n      Linkerd with additional features including FIPS-validated cryptography,\n      lifecycle automation, multi-cluster networking, and enterprise SLA support.\n    humanURL: https://buoyant.io/linkerd-enterprise\n    tags:\n      - Enterprise\n      - FIPS\n      - Kubernetes\n      - Service Mesh\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.buoyant.io/buoyant-enterprise-linkerd/latest/overview/\n      - type: Website\n        url: https://buoyant.io/linkerd-enterprise\ncommon:\n  - type: Portal\n    url: https://buoyant.io/\n  - type: Documentation\n    url: https://linkerd.io/2.x/overview/\n  - type: GitHub Organization\n    url: https://github.com/linkerd\n  - type: Blog\n    url: https://buoyant.io/blog/\n  - type: Pricing\n    url: https://buoyant.io/pricing/\n  - type: Slack\n    url: https://slack.linkerd.io/\n  - type: Community\n    url: https://linkerd.io/community/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/buoyant/refs/heads/main/apis.yml
tags:
- AI Observability
- Kubernetes
- Linkerd
- mTLS
- Observability
- Service Mesh
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/buoyant/refs/heads/main/apis.yml
use_cases: []
---
