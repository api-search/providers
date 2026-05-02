---
api_count: 6
api_specs:
- filename: kubernetes-services-openapi.yml
  format: yaml
  label: Kubernetes Services
  slug: kubernetes-services
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/openapi/kubernetes-services-openapi.yml
- filename: kubernetes-ingress-openapi.yml
  format: yaml
  label: Kubernetes Ingress
  slug: kubernetes-ingress
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/openapi/kubernetes-ingress-openapi.yml
- filename: kubernetes-gateway-api-openapi.yml
  format: yaml
  label: Kubernetes Gateway API
  slug: kubernetes-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/openapi/kubernetes-gateway-api-openapi.yml
- filename: kubernetes-endpoint-slices-openapi.yml
  format: yaml
  label: Kubernetes EndpointSlices
  slug: kubernetes-endpoint-slices
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/openapi/kubernetes-endpoint-slices-openapi.yml
- filename: kubernetes-network-policies-openapi.yml
  format: yaml
  label: Kubernetes Network Policies
  slug: kubernetes-network-policies
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/openapi/kubernetes-network-policies-openapi.yml
apis:
- description: The Kubernetes Services API provides an abstraction for exposing groups of Pods over a network with a stable virtual IP address and DNS name. It supports ClusterIP, NodePort, LoadBalancer, and Externa
  name: Kubernetes Services
  slug: kubernetes-services
- description: The Kubernetes Ingress API manages external HTTP and HTTPS access to services within a cluster, providing load balancing, SSL termination, and name-based virtual hosting. Traffic routing is controlled
  name: Kubernetes Ingress
  slug: kubernetes-ingress
- description: The Kubernetes Gateway API is a role-oriented, extensible API for managing ingress and mesh traffic routing in Kubernetes. It supports advanced traffic management including header-based matching, traf
  name: Kubernetes Gateway API
  slug: kubernetes-gateway-api
- description: The Kubernetes EndpointSlices API tracks IP addresses, ports, readiness, and topology information for Pods backing a Service. EndpointSlices replaced the older Endpoints API to improve scalability for
  name: Kubernetes EndpointSlices
  slug: kubernetes-endpoint-slices
- description: The Kubernetes NetworkPolicy API controls how groups of Pods communicate with each other and with external network endpoints. Policies define ingress and egress rules based on Pod selectors, namespace
  name: Kubernetes Network Policies
  slug: kubernetes-network-policies
- description: Kubernetes provides DNS-based service discovery for Services and Pods within a cluster. DNS records are automatically created for Services, allowing workloads to locate services by name rather than by
  name: Kubernetes DNS for Services and Pods
  slug: kubernetes-dns
asyncapis:
- description: The Kubernetes Services watch API provides streaming event notifications for networking resources including Services, Ingresses, EndpointSlices, NetworkPolicies, and Gateway API resources. Clients sub
  name: Kubernetes Services Watch Events
  slug: kubernetes-services-watch-asyncapi
common:
- title: ''
  type: Website
  url: https://kubernetes.io
- title: ''
  type: Documentation
  url: https://kubernetes.io/docs/concepts/services-networking/
- title: ''
  type: Getting Started
  url: https://kubernetes.io/docs/tutorials/kubernetes-basics/expose/expose-intro/
- title: ''
  type: Reference
  url: https://kubernetes.io/docs/reference/kubernetes-api/service-resources/
- title: ''
  type: GitHub Organization
  url: https://github.com/kubernetes
- title: ''
  type: GitHubRepository
  url: https://github.com/kubernetes/kubernetes
- title: ''
  type: Blog
  url: https://kubernetes.io/blog/
- title: ''
  type: Community
  url: https://kubernetes.io/community/
- title: ''
  type: Change Log
  url: https://kubernetes.io/releases/
- title: ''
  type: JSONSchema
  url: json-schema/kubernetes-services-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/kubernetes-services-context.jsonld
created: '2025-01-01'
description: Kubernetes Services provide an abstract way to expose an application running on a set of Pods as a network service. They provide stable networking endpoints and load balancing across pod replicas in a Kubernetes cluster.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Kubernetes Services Context
  property_count: 28
  slug: kubernetes-services-context
layout: provider
modified: '2026-04-28'
name: Kubernetes Services
skills: []
slug: kubernetes-services
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: kubernetes-services\nname: Kubernetes Services\ndescription: >-\n  Kubernetes Services provide an abstract way to expose an application running\n  on a set of Pods as a network service. They provide stable networking\n  endpoints and load balancing across pod replicas in a Kubernetes cluster.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Container Orchestration\n  - Kubernetes\n  - Load Balancing\n  - Networking\n  - Service Discovery\nurl: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: kubernetes-services:kubernetes-services\n    name: Kubernetes Services\n    description: >-\n      The Kubernetes Services API provides an abstraction for exposing groups of\n      Pods over a network with a stable virtual IP address and DNS name. It\n      supports ClusterIP, NodePort, LoadBalancer,\
  \ and ExternalName service types\n      for internal and external connectivity within Kubernetes clusters.\n    humanURL: https://kubernetes.io/docs/concepts/services-networking/service/\n    tags:\n      - Kubernetes\n      - Load Balancing\n      - Networking\n      - Service Discovery\n    properties:\n      - type: Documentation\n        url: https://kubernetes.io/docs/concepts/services-networking/service/\n      - type: Reference\n        url: https://kubernetes.io/docs/reference/kubernetes-api/service-resources/service-v1/\n      - type: OpenAPI\n        url: openapi/kubernetes-services-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/kubernetes-services-watch-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/kubernetes-services-schema.json\n  - aid: kubernetes-services:kubernetes-ingress\n    name: Kubernetes Ingress\n    description: >-\n      The Kubernetes Ingress API manages external HTTP and HTTPS access to\n      services within a cluster, providing\
  \ load balancing, SSL termination, and\n      name-based virtual hosting. Traffic routing is controlled by rules defined\n      on the Ingress resource and fulfilled by an Ingress controller.\n    humanURL: https://kubernetes.io/docs/concepts/services-networking/ingress/\n    tags:\n      - HTTP\n      - Kubernetes\n      - Load Balancing\n      - Networking\n    properties:\n      - type: Documentation\n        url: https://kubernetes.io/docs/concepts/services-networking/ingress/\n      - type: Reference\n        url: https://kubernetes.io/docs/reference/kubernetes-api/service-resources/ingress-v1/\n      - type: OpenAPI\n        url: openapi/kubernetes-ingress-openapi.yml\n  - aid: kubernetes-services:kubernetes-gateway-api\n    name: Kubernetes Gateway API\n    description: >-\n      The Kubernetes Gateway API is a role-oriented, extensible API for managing\n      ingress and mesh traffic routing in Kubernetes. It supports advanced\n      traffic management including header-based matching,\
  \ traffic weighting, and\n      multi-protocol routing as a successor to the Ingress API.\n    humanURL: https://kubernetes.io/docs/concepts/services-networking/gateway/\n    tags:\n      - Gateway\n      - Kubernetes\n      - Networking\n      - Traffic Management\n    properties:\n      - type: Documentation\n        url: https://kubernetes.io/docs/concepts/services-networking/gateway/\n      - type: OpenAPI\n        url: openapi/kubernetes-gateway-api-openapi.yml\n  - aid: kubernetes-services:kubernetes-endpoint-slices\n    name: Kubernetes EndpointSlices\n    description: >-\n      The Kubernetes EndpointSlices API tracks IP addresses, ports, readiness,\n      and topology information for Pods backing a Service. EndpointSlices\n      replaced the older Endpoints API to improve scalability for large clusters\n      and enable topology-aware routing.\n    humanURL: https://kubernetes.io/docs/concepts/services-networking/endpoint-slices/\n    tags:\n      - Kubernetes\n      - Networking\n\
  \      - Service Discovery\n      - Topology\n    properties:\n      - type: Documentation\n        url: https://kubernetes.io/docs/concepts/services-networking/endpoint-slices/\n      - type: Reference\n        url: https://kubernetes.io/docs/reference/kubernetes-api/service-resources/endpoint-slice-v1/\n      - type: OpenAPI\n        url: openapi/kubernetes-endpoint-slices-openapi.yml\n  - aid: kubernetes-services:kubernetes-network-policies\n    name: Kubernetes Network Policies\n    description: >-\n      The Kubernetes NetworkPolicy API controls how groups of Pods communicate\n      with each other and with external network endpoints. Policies define\n      ingress and egress rules based on Pod selectors, namespace selectors, and\n      IP blocks to implement network segmentation.\n    humanURL: https://kubernetes.io/docs/concepts/services-networking/network-policies/\n    tags:\n      - Kubernetes\n      - Networking\n      - Policy\n      - Security\n    properties:\n      - type:\
  \ Documentation\n        url: https://kubernetes.io/docs/concepts/services-networking/network-policies/\n      - type: Reference\n        url: https://kubernetes.io/docs/reference/kubernetes-api/policy-resources/network-policy-v1/\n      - type: OpenAPI\n        url: openapi/kubernetes-network-policies-openapi.yml\n  - aid: kubernetes-services:kubernetes-dns\n    name: Kubernetes DNS for Services and Pods\n    description: >-\n      Kubernetes provides DNS-based service discovery for Services and Pods\n      within a cluster. DNS records are automatically created for Services,\n      allowing workloads to locate services by name rather than by IP address.\n    humanURL: https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/\n    tags:\n      - DNS\n      - Kubernetes\n      - Networking\n      - Service Discovery\n    properties:\n      - type: Documentation\n        url: https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/\ncommon:\n  - type: Website\n\
  \    url: https://kubernetes.io\n  - type: Documentation\n    url: https://kubernetes.io/docs/concepts/services-networking/\n  - type: Getting Started\n    url: https://kubernetes.io/docs/tutorials/kubernetes-basics/expose/expose-intro/\n  - type: Reference\n    url: https://kubernetes.io/docs/reference/kubernetes-api/service-resources/\n  - type: GitHub Organization\n    url: https://github.com/kubernetes\n  - type: GitHubRepository\n    url: https://github.com/kubernetes/kubernetes\n  - type: Blog\n    url: https://kubernetes.io/blog/\n  - type: Community\n    url: https://kubernetes.io/community/\n  - type: Change Log\n    url: https://kubernetes.io/releases/\n  - type: JSONSchema\n    url: json-schema/kubernetes-services-schema.json\n  - type: JSON-LD\n    url: json-ld/kubernetes-services-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/apis.yml
tags:
- Container Orchestration
- Kubernetes
- Load Balancing
- Networking
- Service Discovery
url: https://raw.githubusercontent.com/api-evangelist/kubernetes-services/refs/heads/main/apis.yml
use_cases: []
---
