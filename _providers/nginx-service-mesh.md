---
api_count: 1
apis:
- description: The NGINX Service Mesh control plane exposes a REST API used by the `nginx-meshctl` CLI to manage mesh configuration, sidecar injection, certificate authority operations, traffic policies, and resourc
  name: NGINX Service Mesh Control Plane API
  slug: control-plane-api
common:
- title: ''
  type: Website
  url: https://docs.nginx.com/nginx-service-mesh/
- title: ''
  type: Documentation
  url: https://docs.nginx.com/nginx-service-mesh/
- title: ''
  type: GettingStarted
  url: https://docs.nginx.com/nginx-service-mesh/get-started/
- title: ''
  type: Architecture
  url: https://docs.nginx.com/nginx-service-mesh/about/architecture/
- title: ''
  type: GitHub
  url: https://github.com/nginxinc/nginx-service-mesh
- title: ''
  type: Successor
  url: https://docs.nginx.com/nginx-gateway-fabric/
- title: ''
  type: Blog
  url: https://www.f5.com/company/blog/nginx
created: '2026-04-28'
description: NGINX Service Mesh (NSM) is a service mesh from F5 NGINX powered by NGINX Plus, designed to manage container-to-container traffic in Kubernetes environments. It provides mTLS, traffic policies via the Service Mesh Interface (SMI), traffic splitting, rate limiting, observability (Prometheus, Grafana, Jaeger), and integration with NGINX Plus Ingress Controller. NGINX Service Mesh exposes a control-plane REST API and a `nginx-meshctl` CLI for installation, sidecar injection, certificate management, and policy configuration. The upstream GitHub repository is archived; F5 announced End of Sale (EoS) for the NGINX Microservices Bundle as of July 1, 2023, and the project's successor for ingress and L7 routing is NGINX Gateway Fabric.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: NGINX Service Mesh
skills: []
slug: nginx-service-mesh
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nginx-service-mesh\nname: NGINX Service Mesh\ndescription: >-\n  NGINX Service Mesh (NSM) is a service mesh from F5 NGINX powered by NGINX Plus,\n  designed to manage container-to-container traffic in Kubernetes environments.\n  It provides mTLS, traffic policies via the Service Mesh Interface (SMI),\n  traffic splitting, rate limiting, observability (Prometheus, Grafana, Jaeger),\n  and integration with NGINX Plus Ingress Controller. NGINX Service Mesh exposes\n  a control-plane REST API and a `nginx-meshctl` CLI for installation, sidecar\n  injection, certificate management, and policy configuration. The upstream\n  GitHub repository is archived; F5 announced End of Sale (EoS) for the NGINX\n  Microservices Bundle as of July 1, 2023, and the project's successor for\n  ingress and L7 routing is NGINX Gateway Fabric.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Container Networking\n  - End of Sale\n  - F5\n\
  \  - Kubernetes\n  - mTLS\n  - NGINX\n  - Observability\n  - Service Mesh\n  - SMI\n  - Traffic Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/nginx-service-mesh/refs/heads/main/apis.yml\ncreated: '2026-04-28'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: nginx-service-mesh:control-plane-api\n    name: NGINX Service Mesh Control Plane API\n    description: >-\n      The NGINX Service Mesh control plane exposes a REST API used by the\n      `nginx-meshctl` CLI to manage mesh configuration, sidecar injection,\n      certificate authority operations, traffic policies, and resource lookups.\n      The API is internal to the cluster and is not published as a public\n      OpenAPI document; its surface is documented through the API Usage guide\n      and the `nginx-meshctl` reference.\n    humanURL: https://docs.nginx.com/nginx-service-mesh/reference/api-usage/\n    tags:\n      - API\n      - Control Plane\n      - Kubernetes\n      - REST\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.nginx.com/nginx-service-mesh/reference/api-usage/\n      - type: CLIReference\n        url: https://docs.nginx.com/nginx-service-mesh/reference/nginx-meshctl/\n      - type: GitHub\n        url: https://github.com/nginxinc/nginx-service-mesh\ncommon:\n  - type: Website\n    url: https://docs.nginx.com/nginx-service-mesh/\n  - type: Documentation\n    url: https://docs.nginx.com/nginx-service-mesh/\n  - type: GettingStarted\n    url: https://docs.nginx.com/nginx-service-mesh/get-started/\n  - type: Architecture\n    url: https://docs.nginx.com/nginx-service-mesh/about/architecture/\n  - type: GitHub\n    url: https://github.com/nginxinc/nginx-service-mesh\n  - type: Successor\n    url: https://docs.nginx.com/nginx-gateway-fabric/\n  - type: Blog\n    url: https://www.f5.com/company/blog/nginx\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nginx-service-mesh/refs/heads/main/apis.yml
tags:
- Container Networking
- End of Sale
- F5
- Kubernetes
- mTLS
- NGINX
- Observability
- Service Mesh
- SMI
- Traffic Management
url: https://raw.githubusercontent.com/api-evangelist/nginx-service-mesh/refs/heads/main/apis.yml
use_cases: []
---
