---
api_count: 1
apis:
- description: Ambient Mesh provides a sidecar-less service mesh via the Kubernetes Gateway API and Istio ambient mode. It exposes configuration APIs for traffic management, security policies, resilience settings, a
  name: Ambient Mesh
  slug: ambient-mesh
common:
- title: ''
  type: Website
  url: https://ambientmesh.io/
- title: ''
  type: Documentation
  url: https://ambientmesh.io/docs/
- title: ''
  type: GettingStarted
  url: https://ambientmesh.io/docs/quickstart/
- title: ''
  type: Blog
  url: https://ambientmesh.io/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/istio
- title: ''
  type: GitHubRepository
  url: https://github.com/istio/istio
created: '2026-04-19'
description: Ambient Mesh is a sidecar-less service mesh architecture built on Istio that simplifies microservices communication, enhances zero-trust security, and improves observability without requiring sidecar proxy injection. It uses a shared per-node proxy (ztunnel) for zero-trust security and optional waypoint proxies for advanced Layer 7 policies, enabling seamless migration from sidecar-based meshes with zero downtime.
features:
- description: Operates at the platform layer without sidecar proxy injection, reducing resource overhead and operational complexity while maintaining full service mesh capabilities.
  name: Sidecar-Less Architecture
- description: SPIFFE-based workload identity with automatic mutual TLS encryption between workloads, certificate management, and zero-trust network policies enforced by ztunnel.
  name: Zero-Trust Security
- description: Advanced traffic routing, load balancing, traffic splitting, mirroring, blue-green deployments, and gateway management via Kubernetes Gateway API HTTPRoute resources.
  name: Traffic Management
- description: Zone-aware load balancing, circuit breaking, outlier detection, fault injection, timeouts, and retry budgets for high-availability workloads.
  name: Resilience
- description: Distributed tracing, performance metrics via Prometheus, Kiali observability console, and HTTP observability for traffic visualization and security verification.
  name: Observability
- description: Free migration tooling for upgrading from sidecar-based architectures with automated workload analysis and risk mitigation for waypoint proxy requirements.
  name: Zero-Downtime Migration
- description: Optional per-namespace or per-workload Layer 7 proxies that provide advanced policy enforcement without requiring per-pod sidecar containers.
  name: Waypoint Proxies
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Ambient Mesh is built on Istio ambient mode, using its control plane and CRDs for configuration.
  name: Istio
- description: Uses the standard Kubernetes Gateway API with HTTPRoute, Gateway, and GRPCRoute resources for traffic management.
  name: Kubernetes Gateway API
- description: Integrates with Prometheus for metrics collection and monitoring of mesh traffic and performance.
  name: Prometheus
- description: Integrates with Kiali for service mesh observability, traffic visualization, and security verification.
  name: Kiali
- description: Solo.io's Gloo Mesh provides enterprise-grade ambient mesh management for scaling across enterprise workloads.
  name: Gloo Mesh
- description: Red Hat OpenShift Service Mesh 3.x supports Istio ambient mode for OpenShift deployments.
  name: OpenShift
layout: provider
modified: '2026-04-19'
name: Ambient Mesh
skills: []
slug: ambient-mesh
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ambient-mesh\nname: Ambient Mesh\ndescription: >-\n  Ambient Mesh is a sidecar-less service mesh architecture built on Istio that\n  simplifies microservices communication, enhances zero-trust security, and\n  improves observability without requiring sidecar proxy injection. It uses a\n  shared per-node proxy (ztunnel) for zero-trust security and optional waypoint\n  proxies for advanced Layer 7 policies, enabling seamless migration from\n  sidecar-based meshes with zero downtime.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Service Mesh\n  - Istio\n  - Kubernetes\n  - Zero Trust\n  - Observability\n  - Traffic Management\n  - Microservices\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ambient-mesh/refs/heads/main/apis.yml\ncreated: '2026-04-19'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: ambient-mesh:ambient-mesh\n    name: Ambient Mesh\n    description: >-\n      Ambient\
  \ Mesh provides a sidecar-less service mesh via the Kubernetes\n      Gateway API and Istio ambient mode. It exposes configuration APIs for\n      traffic management, security policies, resilience settings, and\n      observability through standard Kubernetes CRDs including HTTPRoute,\n      Gateway, AuthorizationPolicy, and WaypointProxy resources.\n    humanURL: https://ambientmesh.io/\n    baseURL: https://ambientmesh.io\n    tags:\n      - Service Mesh\n      - Kubernetes\n      - Istio\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url: https://ambientmesh.io/docs/\n      - type: GettingStarted\n        url: https://ambientmesh.io/docs/quickstart/\n      - type: APIReference\n        url: https://ambientmesh.io/docs/\n\ncommon:\n  - type: Website\n    url: https://ambientmesh.io/\n  - type: Documentation\n    url: https://ambientmesh.io/docs/\n  - type: GettingStarted\n    url: https://ambientmesh.io/docs/quickstart/\n  - type: Blog\n    url: https://ambientmesh.io/blog/\n\
  \  - type: GitHubOrganization\n    url: https://github.com/istio\n  - type: GitHubRepository\n    url: https://github.com/istio/istio\n  - type: Features\n    data:\n      - name: Sidecar-Less Architecture\n        description: >-\n          Operates at the platform layer without sidecar proxy injection,\n          reducing resource overhead and operational complexity while maintaining\n          full service mesh capabilities.\n      - name: Zero-Trust Security\n        description: >-\n          SPIFFE-based workload identity with automatic mutual TLS encryption\n          between workloads, certificate management, and zero-trust network\n          policies enforced by ztunnel.\n      - name: Traffic Management\n        description: >-\n          Advanced traffic routing, load balancing, traffic splitting, mirroring,\n          blue-green deployments, and gateway management via Kubernetes Gateway\n          API HTTPRoute resources.\n      - name: Resilience\n        description: >-\n\
  \          Zone-aware load balancing, circuit breaking, outlier detection, fault\n          injection, timeouts, and retry budgets for high-availability workloads.\n      - name: Observability\n        description: >-\n          Distributed tracing, performance metrics via Prometheus, Kiali\n          observability console, and HTTP observability for traffic\n          visualization and security verification.\n      - name: Zero-Downtime Migration\n        description: >-\n          Free migration tooling for upgrading from sidecar-based architectures\n          with automated workload analysis and risk mitigation for waypoint\n          proxy requirements.\n      - name: Waypoint Proxies\n        description: >-\n          Optional per-namespace or per-workload Layer 7 proxies that provide\n          advanced policy enforcement without requiring per-pod sidecar\n          containers.\n  - type: UseCases\n    data:\n      - name: Microservices Security\n        description: >-\n      \
  \    Enforce mutual TLS and zero-trust policies across microservices\n          without modifying application code or injecting sidecar proxies.\n      - name: Traffic Management\n        description: >-\n          Implement advanced traffic routing, A/B testing, canary deployments,\n          and traffic mirroring across Kubernetes workloads.\n      - name: Istio Migration\n        description: >-\n          Migrate existing Istio sidecar-based deployments to ambient mode with\n          zero downtime using the free migration tooling.\n      - name: Kubernetes Observability\n        description: >-\n          Gain full visibility into service-to-service communication with\n          metrics, tracing, and traffic visualization via Kiali and Prometheus.\n      - name: Multi-Cluster Networking\n        description: >-\n          Extend ambient mesh policies and security across multiple Kubernetes\n          clusters for hybrid and multi-cloud architectures.\n  - type: Integrations\n    data:\n\
  \      - name: Istio\n        description: >-\n          Ambient Mesh is built on Istio ambient mode, using its control plane\n          and CRDs for configuration.\n      - name: Kubernetes Gateway API\n        description: >-\n          Uses the standard Kubernetes Gateway API with HTTPRoute, Gateway, and\n          GRPCRoute resources for traffic management.\n      - name: Prometheus\n        description: >-\n          Integrates with Prometheus for metrics collection and monitoring of\n          mesh traffic and performance.\n      - name: Kiali\n        description: >-\n          Integrates with Kiali for service mesh observability, traffic\n          visualization, and security verification.\n      - name: Gloo Mesh\n        description: >-\n          Solo.io's Gloo Mesh provides enterprise-grade ambient mesh management\n          for scaling across enterprise workloads.\n      - name: OpenShift\n        description: >-\n          Red Hat OpenShift Service Mesh 3.x supports Istio\
  \ ambient mode for\n          OpenShift deployments.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ambient-mesh/refs/heads/main/apis.yml
tags:
- Service Mesh
- Istio
- Kubernetes
- Zero Trust
- Observability
- Traffic Management
- Microservices
url: https://raw.githubusercontent.com/api-evangelist/ambient-mesh/refs/heads/main/apis.yml
use_cases:
- description: Enforce mutual TLS and zero-trust policies across microservices without modifying application code or injecting sidecar proxies.
  name: Microservices Security
- description: Implement advanced traffic routing, A/B testing, canary deployments, and traffic mirroring across Kubernetes workloads.
  name: Traffic Management
- description: Migrate existing Istio sidecar-based deployments to ambient mode with zero downtime using the free migration tooling.
  name: Istio Migration
- description: Gain full visibility into service-to-service communication with metrics, tracing, and traffic visualization via Kiali and Prometheus.
  name: Kubernetes Observability
- description: Extend ambient mesh policies and security across multiple Kubernetes clusters for hybrid and multi-cloud architectures.
  name: Multi-Cluster Networking
---
