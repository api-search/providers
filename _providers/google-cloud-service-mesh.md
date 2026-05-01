---
api_count: 3
apis:
- description: 'The Network Services API provides programmatic configuration of application networking infrastructure for Cloud Service Mesh. It manages gateways, meshes, HTTP/gRPC/TCP/TLS routes, endpoint policies, '
  name: Google Cloud Network Services API
  slug: network-services-api
- description: The Network Security API manages security policies for Cloud Service Mesh, including authorization policies, client TLS policies, and server TLS policies. It provides REST endpoints for creating and m
  name: Google Cloud Network Security API
  slug: network-security-api
- description: Cloud Service Mesh uses the open-source xDS v3 control plane API to distribute configuration to Envoy sidecar proxies and proxyless gRPC clients. Configurations defined via the Network Services and Ne
  name: Google Cloud Service Mesh xDS Control Plane API
  slug: xds-control-plane-api
common:
- title: ''
  type: Website
  url: https://cloud.google.com/service-mesh
- title: ''
  type: Documentation
  url: https://cloud.google.com/service-mesh/docs
- title: ''
  type: Getting Started
  url: https://cloud.google.com/service-mesh/docs/onboarding/provision-control-plane
- title: ''
  type: Reference
  url: https://cloud.google.com/service-mesh/docs/reference/network-services/rest
- title: ''
  type: Pricing
  url: https://cloud.google.com/service-mesh/pricing
- title: ''
  type: Change Log
  url: https://cloud.google.com/service-mesh/docs/release-notes
- title: ''
  type: Support
  url: https://cloud.google.com/service-mesh/docs/getting-support
- title: ''
  type: Security
  url: https://cloud.google.com/service-mesh/docs/security-bulletins
created: '2026-03-16'
description: Google Cloud Service Mesh is Google's managed service mesh solution for GKE and supported GKE Enterprise environments, enabling secure, observable, and reliable communication between microservices. It provides a managed Istio control plane, Google Cloud-native service routing APIs, mTLS security, and built-in telemetry for distributed applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Google Cloud Service Mesh
skills: []
slug: google-cloud-service-mesh
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: google-cloud-service-mesh\nname: Google Cloud Service Mesh\ndescription: >-\n  Google Cloud Service Mesh is Google's managed service mesh solution for GKE\n  and supported GKE Enterprise environments, enabling secure, observable, and\n  reliable communication between microservices. It provides a managed Istio\n  control plane, Google Cloud-native service routing APIs, mTLS security,\n  and built-in telemetry for distributed applications.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Google Cloud\n  - Istio\n  - Kubernetes\n  - Microservices\n  - Service Mesh\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/google-cloud-service-mesh/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: google-cloud-service-mesh:network-services-api\n    name: Google Cloud Network Services API\n    description: >-\n      The Network Services API provides\
  \ programmatic configuration of application\n      networking infrastructure for Cloud Service Mesh. It manages gateways,\n      meshes, HTTP/gRPC/TCP/TLS routes, endpoint policies, service load\n      balancing policies, WebAssembly plugins, and authorization extensions\n      through a REST interface backed by the networkservices.googleapis.com\n      service endpoint.\n    humanURL: https://cloud.google.com/service-mesh/docs/reference/network-services/rest\n    baseURL: https://networkservices.googleapis.com/\n    tags:\n      - Networking\n      - REST\n      - Service Mesh\n      - Traffic Management\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/service-mesh/docs/reference/network-services/rest\n      - type: Reference\n        url: https://cloud.google.com/service-mesh/docs/reference/network-services/rest/v1/projects.locations.meshes\n      - type: Discovery\n        url: https://networkservices.googleapis.com/$discovery/rest?version=v1\n  -\
  \ aid: google-cloud-service-mesh:network-security-api\n    name: Google Cloud Network Security API\n    description: >-\n      The Network Security API manages security policies for Cloud Service Mesh,\n      including authorization policies, client TLS policies, and server TLS\n      policies. It provides REST endpoints for creating and managing mTLS\n      configuration and fine-grained access control across projects and locations,\n      served from the networksecurity.googleapis.com service endpoint.\n    humanURL: https://cloud.google.com/service-mesh/docs/reference/network-security/rest\n    baseURL: https://networksecurity.googleapis.com/\n    tags:\n      - Authorization\n      - mTLS\n      - Security\n      - Service Mesh\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/service-mesh/docs/reference/network-security/rest\n      - type: Reference\n        url: https://cloud.google.com/service-mesh/docs/reference/network-security/rest/v1/projects.locations.authorizationPolicies\n\
  \      - type: Discovery\n        url: https://networksecurity.googleapis.com/$discovery/rest?version=v1\n  - aid: google-cloud-service-mesh:xds-control-plane-api\n    name: Google Cloud Service Mesh xDS Control Plane API\n    description: >-\n      Cloud Service Mesh uses the open-source xDS v3 control plane API to\n      distribute configuration to Envoy sidecar proxies and proxyless gRPC\n      clients. Configurations defined via the Network Services and Network\n      Security REST APIs are translated and pushed to connected clients through\n      the xDS protocol, supporting Listener Discovery Service (LDS), Route\n      Discovery Service (RDS), Cluster Discovery Service (CDS), and Endpoint\n      Discovery Service (EDS).\n    humanURL: https://cloud.google.com/service-mesh/docs/service-routing/xds-control-plane-apis\n    baseURL: https://trafficdirector.googleapis.com/\n    tags:\n      - Control Plane\n      - Envoy\n      - Service Mesh\n      - xDS\n    properties:\n      - type:\
  \ Documentation\n        url: https://cloud.google.com/service-mesh/docs/service-routing/xds-control-plane-apis\ncommon:\n  - type: Website\n    url: https://cloud.google.com/service-mesh\n  - type: Documentation\n    url: https://cloud.google.com/service-mesh/docs\n  - type: Getting Started\n    url: https://cloud.google.com/service-mesh/docs/onboarding/provision-control-plane\n  - type: Reference\n    url: https://cloud.google.com/service-mesh/docs/reference/network-services/rest\n  - type: Pricing\n    url: https://cloud.google.com/service-mesh/pricing\n  - type: Change Log\n    url: https://cloud.google.com/service-mesh/docs/release-notes\n  - type: Support\n    url: https://cloud.google.com/service-mesh/docs/getting-support\n  - type: Security\n    url: https://cloud.google.com/service-mesh/docs/security-bulletins\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-service-mesh/refs/heads/main/apis.yml
tags:
- Google Cloud
- Istio
- Kubernetes
- Microservices
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/google-cloud-service-mesh/refs/heads/main/apis.yml
use_cases: []
---
