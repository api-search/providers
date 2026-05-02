---
api_count: 6
api_specs:
- filename: istio-networking-api-openapi.yml
  format: yaml
  label: Istio Networking API
  slug: networking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/openapi/istio-networking-api-openapi.yml
- filename: istio-security-api-openapi.yml
  format: yaml
  label: Istio Security API
  slug: security-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/openapi/istio-security-api-openapi.yml
- filename: istio-telemetry-api-openapi.yml
  format: yaml
  label: Istio Telemetry API
  slug: telemetry-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/openapi/istio-telemetry-api-openapi.yml
- filename: istio-extensions-api-openapi.yml
  format: yaml
  label: Istio Extensions API
  slug: extensions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/openapi/istio-extensions-api-openapi.yml
apis:
- description: The Istio Networking API (networking.istio.io) provides configuration resources for traffic management within an Istio service mesh.
  name: Istio Networking API
  slug: networking-api
- description: The Istio Security API (security.istio.io) provides configuration resources for managing security policies within an Istio service mesh. It includes AuthorizationPolicy for fine-grained access control
  name: Istio Security API
  slug: security-api
- description: The Istio Telemetry API (telemetry.istio.io) provides configuration resources for managing observability within an Istio service mesh. The Telemetry resource enables flexible configuration of metrics,
  name: Istio Telemetry API
  slug: telemetry-api
- description: The Istio Extensions API (extensions.istio.io) provides configuration resources for extending the Istio service mesh with custom functionality. The WasmPlugin resource enables deploying WebAssembly (W
  name: Istio Extensions API
  slug: extensions-api
- description: The Istio Mesh Config API (istio.mesh.v1alpha1) provides global configuration for the Istio service mesh control plane and data plane proxy behavior. It includes MeshConfig for mesh-wide settings such
  name: Istio Mesh Config API
  slug: mesh-config-api
- description: The Istio Operator API (istio.operator.v1alpha1) defines the IstioOperator custom resource used to install, configure, and upgrade Istio on Kubernetes clusters. It provides a declarative interface for
  name: Istio Operator API
  slug: operator-api
common:
- title: ''
  type: JSON-LD
  url: json-ld/istio-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/virtual-service.json
- title: ''
  type: JSONSchema
  url: json-schema/destination-rule.json
- title: ''
  type: JSONSchema
  url: json-schema/gateway.json
- title: ''
  type: Website
  url: https://istio.io/
- title: ''
  type: Blog
  url: https://istio.io/latest/blog/
- title: ''
  type: News
  url: https://istio.io/latest/news/
- title: ''
  type: Documentation
  url: https://istio.io/latest/docs/
- title: ''
  type: Glossary
  url: https://istio.io/latest/docs/reference/glossary/
- title: ''
  type: GitHub
  url: https://github.com/istio/istio
- title: ''
  type: GitHub
  url: https://github.com/istio/api
- title: ''
  type: Getting Started
  url: https://istio.io/latest/docs/setup/getting-started/
- title: ''
  type: GitHub Organization
  url: https://github.com/istio
- title: ''
  type: Change Log
  url: https://github.com/istio/istio/releases
- title: ''
  type: Community
  url: https://istio.io/latest/get-involved/
- title: ''
  type: Support
  url: https://discuss.istio.io/
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/istio
- title: ''
  type: Security
  url: https://istio.io/latest/docs/releases/security-vulnerabilities/
- title: ''
  type: Issue Tracker
  url: https://github.com/istio/istio/issues
created: '2025-06-05'
description: Istio is an open-source service mesh platform that provides a comprehensive solution for managing, securing, and monitoring microservices in a distributed system. It acts as a middle layer between services, handling communication, routing, and load balancing, as well as providing visibility into the traffic flowing between services. Istio also offers advanced security features such as access control, authentication, and encryption to ensure that communication between services is secure.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Istio Context
  property_count: 10
  slug: istio-context
layout: provider
modified: '2026-04-28'
name: Istio
skills: []
slug: istio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: istio\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/apis.yml\napis:\n  - aid: istio:networking-api\n    name: Istio Networking API\n    tags:\n      - Networking\n      - Service Mesh\n      - Traffic Management\n    humanURL: https://istio.io/latest/docs/reference/config/networking/\n    properties:\n      - url: https://istio.io/latest/docs/reference/config/networking/\n        type: Documentation\n      - url: openapi/istio-networking-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/virtual-service.json\n        type: JSONSchema\n      - url: json-schema/destination-rule.json\n        type: JSONSchema\n      - url: json-schema/gateway.json\n        type: JSONSchema\n      - url: json-schema/service-entry.json\n        type: JSONSchema\n      - url: json-schema/sidecar.json\n        type: JSONSchema\n      - url: json-schema/workload-entry.json\n        type: JSONSchema\n      - url: json-ld/istio-context.jsonld\n\
  \        type: JSONLD\n    description: >-\n      The Istio Networking API (networking.istio.io) provides configuration resources\n      for traffic management within an Istio service mesh.\n  - aid: istio:security-api\n    name: Istio Security API\n    tags:\n      - Authentication\n      - Authorization\n      - Security\n      - Service Mesh\n    humanURL: https://istio.io/latest/docs/reference/config/security/\n    properties:\n      - url: https://istio.io/latest/docs/reference/config/security/\n        type: Documentation\n      - url: openapi/istio-security-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/authorization-policy.json\n        type: JSONSchema\n      - url: json-schema/peer-authentication.json\n        type: JSONSchema\n      - url: json-schema/request-authentication.json\n        type: JSONSchema\n      - url: json-ld/istio-context.jsonld\n        type: JSONLD\n    description: >-\n      The Istio Security API (security.istio.io) provides configuration\n\
  \      resources for managing security policies within an Istio service mesh. It\n      includes AuthorizationPolicy for fine-grained access control on workloads\n      with ALLOW, DENY, AUDIT, and CUSTOM actions, PeerAuthentication for\n      configuring mutual TLS (mTLS) between service proxies, and\n      RequestAuthentication for validating JWT tokens attached to incoming\n      requests. These resources enforce zero-trust security across the mesh.\n  - aid: istio:telemetry-api\n    name: Istio Telemetry API\n    tags:\n      - Metrics\n      - Observability\n      - Service Mesh\n      - Telemetry\n      - Tracing\n    humanURL: https://istio.io/latest/docs/reference/config/telemetry/\n    properties:\n      - url: https://istio.io/latest/docs/reference/config/telemetry/\n        type: Documentation\n      - url: openapi/istio-telemetry-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/telemetry.json\n        type: JSONSchema\n      - url: json-ld/istio-context.jsonld\n\
  \        type: JSONLD\n    description: >-\n      The Istio Telemetry API (telemetry.istio.io) provides configuration\n      resources for managing observability within an Istio service mesh. The\n      Telemetry resource enables flexible configuration of metrics, access logs,\n      and distributed tracing for workloads. It uses the concept of providers to\n      indicate the protocol or integration type, and supports fine-grained\n      control over what telemetry data is collected and where it is sent.\n  - aid: istio:extensions-api\n    name: Istio Extensions API\n    tags:\n      - Extensions\n      - Service Mesh\n      - Wasm\n      - WebAssembly\n    humanURL: https://istio.io/latest/docs/reference/config/\n    properties:\n      - url: https://istio.io/latest/docs/reference/config/\n        type: Documentation\n      - url: openapi/istio-extensions-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/wasm-plugin.json\n        type: JSONSchema\n      - url: json-ld/istio-context.jsonld\n\
  \        type: JSONLD\n    description: >-\n      The Istio Extensions API (extensions.istio.io) provides configuration\n      resources for extending the Istio service mesh with custom functionality.\n      The WasmPlugin resource enables deploying WebAssembly (Wasm) modules as\n      plugins to the Envoy sidecar proxies, allowing custom processing of\n      network traffic at various phases of the request lifecycle including\n      authentication, authorization, metrics collection, and traffic\n      transformation.\n  - aid: istio:mesh-config-api\n    name: Istio Mesh Config API\n    tags:\n      - Configuration\n      - Networking\n      - Proxy\n      - Service Mesh\n    humanURL: https://istio.io/latest/docs/reference/config/istio.mesh.v1alpha1/\n    properties:\n      - url: https://istio.io/latest/docs/reference/config/istio.mesh.v1alpha1/\n        type: Documentation\n      - url: https://github.com/istio/api/tree/master/mesh/v1alpha1\n        type: GitHubRepository\n    description:\
  \ >-\n      The Istio Mesh Config API (istio.mesh.v1alpha1) provides global\n      configuration for the Istio service mesh control plane and data plane\n      proxy behavior. It includes MeshConfig for mesh-wide settings such as\n      access logging, tracing providers, and default proxy configuration, as\n      well as ProxyConfig for per-workload proxy tuning and network topology\n      settings. These settings are typically applied via the Istio ConfigMap\n      or as annotations on workloads.\n  - aid: istio:operator-api\n    name: Istio Operator API\n    tags:\n      - Installation\n      - Kubernetes\n      - Operator\n      - Service Mesh\n    humanURL: https://istio.io/latest/docs/reference/config/istio.operator.v1alpha1/\n    properties:\n      - url: https://istio.io/latest/docs/reference/config/istio.operator.v1alpha1/\n        type: Documentation\n      - url: https://github.com/istio/istio/tree/master/operator\n        type: GitHubRepository\n    description: >-\n      The\
  \ Istio Operator API (istio.operator.v1alpha1) defines the\n      IstioOperator custom resource used to install, configure, and upgrade\n      Istio on Kubernetes clusters. It provides a declarative interface for\n      selecting Istio profiles, enabling or disabling components such as\n      ingress and egress gateways, and customizing the control plane\n      configuration without editing raw Helm values.\nname: Istio\ntags:\n  - CNCF\n  - Kubernetes\n  - Microservices\n  - Open Source\n  - Service Mesh\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-06-05'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  Istio is an open-source service mesh platform that provides a comprehensive solution\n  for managing, securing, and monitoring microservices in a distributed system. It\n  acts as a middle layer between services, handling communication, routing, and load\n  balancing, as well as providing\
  \ visibility into the traffic flowing between services.\n  Istio also offers advanced security features such as access control, authentication,\n  and encryption to ensure that communication between services is secure.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - type: JSON-LD\n    url: json-ld/istio-context.jsonld\n  - type: JSONSchema\n    url: json-schema/virtual-service.json\n  - type: JSONSchema\n    url: json-schema/destination-rule.json\n  - type: JSONSchema\n    url: json-schema/gateway.json\n  - name: Istio\n    description: 'null'\n    url: https://istio.io/\n    type: Website\n  - name: Istio / Blog\n    description: 'null'\n    url: https://istio.io/latest/blog/\n    type: Blog\n  - name: Istio / News\n    description: 'null'\n    url: https://istio.io/latest/news/\n    type: News\n  - name: Istio / Documentation\n    description: 'null'\n    url: https://istio.io/latest/docs/\n    type: Documentation\n  - name:\
  \ Istio / Integrations\n    description: 'null'\n    url: https://istio.io/latest/docs/ops/integrations/\n    type: Integrations\n  - name: Istio / Glossary\n    description: 'null'\n    url: https://istio.io/latest/docs/reference/glossary/\n    type: Glossary\n  - name: Istio / GitHub\n    description: 'null'\n    url: https://github.com/istio/istio\n    type: GitHub\n  - name: Istio / API Repository\n    description: 'null'\n    url: https://github.com/istio/api\n    type: GitHub\n  - type: Getting Started\n    url: https://istio.io/latest/docs/setup/getting-started/\n  - type: GitHub Organization\n    url: https://github.com/istio\n  - type: Change Log\n    url: https://github.com/istio/istio/releases\n  - type: Community\n    url: https://istio.io/latest/get-involved/\n  - type: Support\n    url: https://discuss.istio.io/\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/istio\n  - type: Security\n    url: https://istio.io/latest/docs/releases/security-vulnerabilities/\n\
  \  - type: Issue Tracker\n    url: https://github.com/istio/istio/issues\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/apis.yml
tags:
- CNCF
- Kubernetes
- Microservices
- Open Source
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/istio/refs/heads/main/apis.yml
use_cases: []
---
