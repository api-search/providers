---
api_count: 6
api_specs:
- filename: ambassador-openapi.yml
  format: yaml
  label: Ambassador Edge Stack API Gateway
  slug: edge-stack-api-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ambassador/refs/heads/main/openapi/ambassador-openapi.yml
apis:
- description: 'Ambassador offers a suite of products designed to deliver API developer experiences that fuel innovation. These products, Blackbird API Development Platform, Edge Stack API Gateway, and Telepresence, '
  name: Ambassador
  slug: ambassador
- description: Ambassador Edge Stack is a Kubernetes-native API gateway built on Envoy Proxy that provides routing, load balancing, authentication, rate limiting, and observability for microservices. It supports cus
  name: Ambassador Edge Stack API Gateway
  slug: edge-stack-api-gateway
- description: Emissary-Ingress is an open-source, Kubernetes-native API gateway built on Envoy Proxy and a CNCF incubating project, formerly known as Ambassador API Gateway. It uses custom resource definitions (CRD
  name: Emissary-Ingress
  slug: emissary-ingress
- description: Telepresence provides a RESTful API server that runs on the local host, both on the local workstation and in a pod that contains a traffic-agent. The API includes healthz, consume-here, and intercept-
  name: Ambassador Telepresence RESTful API
  slug: telepresence-api
- description: Blackbird is an API development platform that helps developers design, build, test, and manage APIs with AI-powered code generation, mocking, and production-like test environments. It supports OpenAPI
  name: Ambassador Blackbird API Development Platform
  slug: blackbird-api-development-platform
- description: The Ambassador Edge Stack Developer Portal automatically detects and publishes API documentation, serving as a single point of reference for all microservice APIs. It supports Swagger and OpenAPI V3 s
  name: Ambassador Edge Stack Developer Portal
  slug: edge-stack-developer-portal
capabilities:
- description: Unified gateway management workflow for platform engineers and DevOps teams to configure API routing, TLS termination, rate limiting, and health monitoring across Ambassador Edge Stack instances.
  name: Ambassador Gateway Management
  slug: gateway-management
common:
- title: ''
  type: Customers
  url: https://www.getambassador.io/case-studies
- title: ''
  type: Pricing
  url: https://www.getambassador.io/pricing
- title: ''
  type: Blog
  url: https://www.getambassador.io/blog
- title: ''
  type: FAQ
  url: https://www.getambassador.io/faq
- title: ''
  type: Documentation
  url: https://www.getambassador.io/docs
- title: ''
  type: Support
  url: https://www.getambassador.io/support
- title: ''
  type: Partners
  url: https://www.getambassador.io/company/partnerships
- title: ''
  type: GettingStarted
  url: https://www.getambassador.io/docs/edge-stack/latest/tutorials/getting-started/
- title: ''
  type: GitHubRepository
  url: https://github.com/emissary-ingress/emissary
- title: ''
  type: ChangeLog
  url: https://github.com/emissary-ingress/emissary/blob/master/CHANGELOG.md
- title: ''
  type: StatusPage
  url: https://status.datawire.io/
- title: ''
  type: Authentication
  url: https://www.getambassador.io/products/edge-stack/api-gateway/security-authentication
- title: ''
  type: RateLimits
  url: https://www.getambassador.io/docs/edge-stack/latest/howtos/rate-limiting-tutorial
- title: ''
  type: X
  url: https://x.com/ambassadorlabs
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/ambassadorlabs
- title: ''
  type: SignUp
  url: https://app.getambassador.io/
- title: ''
  type: GitHubRepository
  url: https://github.com/datawire/ambassador-docs
- title: ''
  type: GitHubOrganization
  url: https://github.com/datawire
- title: ''
  type: JSONLD
  url: json-ld/ambassador-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/ambassador-mapping-schema.json
created: '2025-01-08'
description: Ambassador is a Kubernetes-native API Gateway built on Envoy Proxy, providing routing, load balancing, authentication, and observability for microservices.
features:
- description: Purpose-built for Kubernetes with custom resource definitions (CRDs) for declarative configuration of routing, TLS, and rate limiting.
  name: Kubernetes-Native API Gateway
- description: Built on Envoy Proxy for high-performance load balancing, circuit breaking, and observability at the edge.
  name: Envoy Proxy Foundation
- description: Integrated OAuth2, API key, and JWT-based authentication filters to secure API endpoints without custom code.
  name: Authentication and Security
- description: Configurable rate limiting with labels and descriptors to control request throughput to backend services.
  name: Rate Limiting
- description: Automatic API documentation publishing from OpenAPI/Swagger specs with customizable developer portal for onboarding.
  name: Developer Portal
- description: Intercept and debug remote Kubernetes services locally using Telepresence for fast inner-loop development.
  name: Local Development with Telepresence
- description: AI-powered API development platform with mock servers and production-like test environments for rapid iteration.
  name: API Mocking with Blackbird
image: https://www.getambassador.io/images/ambassador-logo.png
integrations:
- description: Native integration with Kubernetes using CRDs for Mapping, Host, TLSContext, and RateLimit resources.
  name: Kubernetes
- description: Built on Envoy Proxy with full access to Envoy's load balancing, circuit breaking, and observability features.
  name: Envoy Proxy
- description: Install and manage Ambassador Edge Stack using Helm charts for Kubernetes deployments.
  name: Helm
- description: Export metrics to Prometheus and visualize API gateway performance in Grafana dashboards.
  name: Prometheus and Grafana
- description: Automatic TLS certificate management via cert-manager and ACME protocol integration.
  name: Cert-Manager
jsonld:
- class_count: 0
  name: Ambassador Context
  property_count: 0
  slug: ambassador-context
layout: provider
modified: '2026-04-18'
name: Ambassador
rules:
- name: Ambassador API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: ambassador-spectral-rules
skills: []
slug: ambassador
solutions: []
source_filename: apis.yml
source_yaml: "aid: ambassador\nurl: https://raw.githubusercontent.com/api-evangelist/ambassador/refs/heads/main/apis.yml\napis:\n  - aid: ambassador:ambassador\n    name: Ambassador\n    tags:\n      - Gateways\n      - Mocking\n      - Testing\n    humanURL: https://www.getambassador.io/\n    properties:\n      - url: https://www.getambassador.io/\n        type: Documentation\n    description: Ambassador offers a suite of products designed to deliver API developer experiences that fuel innovation. These products, Blackbird API Development Platform, Edge Stack API Gateway, and Telepresence, accelerate development, expedite testing, and optimize the delivery of API resources.\n  - aid: ambassador:edge-stack-api-gateway\n    name: Ambassador Edge Stack API Gateway\n    tags:\n      - API Management\n      - Envoy\n      - Gateways\n      - Ingress\n      - Kubernetes\n    humanURL: https://www.getambassador.io/products/edge-stack/api-gateway\n    properties:\n      - url: https://www.getambassador.io/products/edge-stack/api-gateway\n\
  \        type: Documentation\n      - url: https://www.getambassador.io/docs/edge-stack/latest/tutorials/getting-started/\n        type: GettingStarted\n      - url: https://www.getambassador.io/docs/edge-stack/latest/topics/install/\n        type: Documentation\n      - url: https://www.getambassador.io/docs/edge-stack/latest/topics/install/helm/\n        type: Documentation\n      - url: https://www.getambassador.io/docs/edge-stack/latest/topics/using/intro-mappings\n        type: Documentation\n      - url: https://www.getambassador.io/docs/edge-stack/latest/topics/running/host-crd\n        type: Documentation\n      - url: https://www.getambassador.io/docs/edge-stack/latest/topics/using/rate-limits\n        type: Documentation\n      - url: https://www.getambassador.io/docs/edge-stack/latest/topics/using/filters/oauth2\n        type: Documentation\n      - url: https://www.getambassador.io/docs/edge-stack/latest/topics/using/filters/apikeys\n        type: Documentation\n      - url:\
  \ https://www.getambassador.io/docs/edge-stack/latest/topics/using/gateway-api\n        type: Documentation\n      - url: https://www.getambassador.io/docs/edge-stack/latest/about/changes-2.x\n        type: Documentation\n      - url: https://www.getambassador.io/docs/edge-stack/latest/tutorials/quickstart-demo\n        type: GettingStarted\n      - url: https://github.com/datawire/edge-stack\n        type: GitHubRepository\n      - url: openapi/ambassador-openapi.yml\n        type: OpenAPI\n    description: Ambassador Edge Stack is a Kubernetes-native API gateway built on Envoy Proxy that provides routing, load balancing, authentication, rate limiting, and observability for microservices. It supports custom resource definitions (CRDs) including Mapping, Host, TLSContext, and RateLimit for declarative configuration.\n  - aid: ambassador:emissary-ingress\n    name: Emissary-Ingress\n    tags:\n      - CNCF\n      - Envoy\n      - Gateways\n      - Ingress\n      - Kubernetes\n      - Open\
  \ Source\n    humanURL: https://www.getambassador.io/docs/emissary\n    properties:\n      - url: https://www.getambassador.io/docs/emissary\n        type: Documentation\n      - url: https://emissary-ingress.dev/\n        type: Documentation\n      - url: https://www.getambassador.io/docs/emissary/latest/tutorials/quickstart-demo\n        type: GettingStarted\n      - url: https://github.com/emissary-ingress/emissary\n        type: GitHubRepository\n      - url: https://github.com/emissary-ingress/emissary/blob/master/CHANGELOG.md\n        type: ChangeLog\n    description: Emissary-Ingress is an open-source, Kubernetes-native API gateway built on Envoy Proxy and a CNCF incubating project, formerly known as Ambassador API Gateway. It uses custom resource definitions (CRDs) including Mapping, Host, Listener, and TLSContext for declarative edge management.\n  - aid: ambassador:telepresence-api\n    name: Ambassador Telepresence RESTful API\n    tags:\n      - Debugging\n      - Development\n\
  \      - Intercepts\n      - Kubernetes\n    humanURL: https://www.getambassador.io/docs/telepresence/latest/reference/restapi\n    properties:\n      - url: https://www.getambassador.io/docs/telepresence/latest/reference/restapi\n        type: Documentation\n      - url: https://www.getambassador.io/docs/telepresence-oss/latest/quick-start\n        type: GettingStarted\n      - url: https://www.getambassador.io/docs/telepresence/latest/howtos/intercepts\n        type: Documentation\n      - url: https://www.getambassador.io/docs/telepresence/latest/concepts/intercepts\n        type: Documentation\n      - url: https://www.getambassador.io/docs/telepresence/latest/reference/config\n        type: Documentation\n      - url: https://www.getambassador.io/products/telepresence\n        type: Documentation\n    description: Telepresence provides a RESTful API server that runs on the local host, both on the local workstation and in a pod that contains a traffic-agent. The API includes healthz,\
  \ consume-here, and intercept-info endpoints for managing service intercepts in Kubernetes development environments.\n  - aid: ambassador:blackbird-api-development-platform\n    name: Ambassador Blackbird API Development Platform\n    tags:\n      - API Development\n      - Code Generation\n      - Mocking\n      - OpenAPI\n      - Testing\n    humanURL: https://www.getambassador.io/products/blackbird/api-development\n    properties:\n      - url: https://www.getambassador.io/products/blackbird/api-development\n        type: Documentation\n      - url: https://www.getambassador.io/docs/blackbird\n        type: Documentation\n      - url: https://www.getambassador.io/docs/blackbird/latest/install/quickstart\n        type: GettingStarted\n      - url: https://www.getambassador.io/docs/blackbird/latest/guides/api/quickstart\n        type: GettingStarted\n      - url: https://www.getambassador.io/docs/blackbird/latest/guides/code/quickstart\n        type: GettingStarted\n      - url: https://www.getambassador.io/docs/blackbird/latest/guides/deployments/quickstart\n\
  \        type: GettingStarted\n      - url: https://www.getambassador.io/docs/blackbird/latest/release-notes\n        type: ReleaseNotes\n      - url: https://www.getambassador.io/docs/blackbird/latest/reference/mcp\n        type: Documentation\n    description: Blackbird is an API development platform that helps developers design, build, test, and manage APIs with AI-powered code generation, mocking, and production-like test environments. It supports OpenAPI specifications and provides integrated debugging tools.\n  - aid: ambassador:edge-stack-developer-portal\n    name: Ambassador Edge Stack Developer Portal\n    tags:\n      - API Catalog\n      - Developer Portal\n      - Documentation\n      - OpenAPI\n    humanURL: https://www.getambassador.io/docs/edge-stack/latest/tutorials/dev-portal-tutorial\n    properties:\n      - url: https://www.getambassador.io/docs/edge-stack/latest/tutorials/dev-portal-tutorial\n        type: GettingStarted\n      - url: https://www.getambassador.io/docs/latest/topics/using/dev-portal/\n\
  \        type: Documentation\n      - url: https://www.getambassador.io/products/edge-stack/api-gateway/developer-portal\n        type: Documentation\n    description: The Ambassador Edge Stack Developer Portal automatically detects and publishes API documentation, serving as a single point of reference for all microservice APIs. It supports Swagger and OpenAPI V3 specifications and provides a fully customizable portal for internal and external developer onboarding.\nname: Ambassador\ntags:\n  - API Development\n  - Gateways\n  - Ingress\n  - Kubernetes\n  - Mock Servers\n  - Mocks\n  - Platform\n  - Testing\ntype: Contract\nimage: https://www.getambassador.io/images/ambassador-logo.png\naccess: 3rd-Party\ncommon:\n  - url: https://www.getambassador.io/case-studies\n    name: 'Empowering Journeys: Customer Success Stories That Speak Volumes'\n    type: Customers\n  - url: https://www.getambassador.io/pricing\n    name: Ambassador Pricing | Scalable Plans for Edge Stack & Telepresence\n\
  \    type: Pricing\n  - url: https://www.getambassador.io/blog\n    name: Blog | Ambassador\n    type: Blog\n  - url: https://www.getambassador.io/faq\n    name: Edge Stack API Gateway and Telepresence FAQs\n    type: FAQ\n  - url: https://www.getambassador.io/docs\n    name: Docs Home | Ambassador Labs\n    type: Documentation\n  - url: https://www.getambassador.io/support\n    name: Support | Ambassador Labs\n    type: Support\n  - url: https://www.getambassador.io/company/partnerships\n    name: Join the Ambassador Partner Program\n    type: Partners\n  - url: https://www.getambassador.io/docs/edge-stack/latest/tutorials/getting-started/\n    type: GettingStarted\n  - url: https://github.com/emissary-ingress/emissary\n    type: GitHubRepository\n  - url: https://github.com/emissary-ingress/emissary/blob/master/CHANGELOG.md\n    type: ChangeLog\n  - url: https://status.datawire.io/\n    type: StatusPage\n  - url: https://www.getambassador.io/products/edge-stack/api-gateway/security-authentication\n\
  \    type: Authentication\n  - url: https://www.getambassador.io/docs/edge-stack/latest/howtos/rate-limiting-tutorial\n    type: RateLimits\n  - url: https://x.com/ambassadorlabs\n    type: X\n  - url: https://www.linkedin.com/company/ambassadorlabs\n    type: LinkedIn\n  - url: https://app.getambassador.io/\n    type: SignUp\n  - url: https://github.com/datawire/ambassador-docs\n    type: GitHubRepository\n  - url: https://github.com/datawire\n    type: GitHubOrganization\n  - url: json-ld/ambassador-context.jsonld\n    type: JSONLD\n  - url: json-schema/ambassador-mapping-schema.json\n    type: JSONSchema\n  - type: Features\n    data:\n      - name: Kubernetes-Native API Gateway\n        description: Purpose-built for Kubernetes with custom resource definitions (CRDs) for declarative configuration of routing, TLS, and rate limiting.\n      - name: Envoy Proxy Foundation\n        description: Built on Envoy Proxy for high-performance load balancing, circuit breaking, and observability\
  \ at the edge.\n      - name: Authentication and Security\n        description: Integrated OAuth2, API key, and JWT-based authentication filters to secure API endpoints without custom code.\n      - name: Rate Limiting\n        description: Configurable rate limiting with labels and descriptors to control request throughput to backend services.\n      - name: Developer Portal\n        description: Automatic API documentation publishing from OpenAPI/Swagger specs with customizable developer portal for onboarding.\n      - name: Local Development with Telepresence\n        description: Intercept and debug remote Kubernetes services locally using Telepresence for fast inner-loop development.\n      - name: API Mocking with Blackbird\n        description: AI-powered API development platform with mock servers and production-like test environments for rapid iteration.\n  - type: UseCases\n    data:\n      - name: Microservices API Gateway\n        description: Route, secure, and observe traffic\
  \ to microservices running in Kubernetes clusters.\n      - name: API Development and Testing\n        description: Design, mock, and test APIs locally with Blackbird before deploying to Kubernetes environments.\n      - name: Multi-Team API Management\n        description: Enable multiple teams to independently manage their API routing and configuration using Kubernetes CRDs.\n      - name: Service Mesh Edge Gateway\n        description: Serve as the edge gateway in a service mesh architecture, handling north-south traffic with TLS termination.\n      - name: Developer Onboarding\n        description: Provide a self-service developer portal for internal and external developers to discover and consume APIs.\n  - type: Integrations\n    data:\n      - name: Kubernetes\n        description: Native integration with Kubernetes using CRDs for Mapping, Host, TLSContext, and RateLimit resources.\n      - name: Envoy Proxy\n        description: Built on Envoy Proxy with full access to Envoy's\
  \ load balancing, circuit breaking, and observability features.\n      - name: Helm\n        description: Install and manage Ambassador Edge Stack using Helm charts for Kubernetes deployments.\n      - name: Prometheus and Grafana\n        description: Export metrics to Prometheus and visualize API gateway performance in Grafana dashboards.\n      - name: Cert-Manager\n        description: Automatic TLS certificate management via cert-manager and ACME protocol integration.\ncreated: '2025-01-08'\nmodified: '2026-04-18'\nposition: Consuming\nsegments:\n  - Gateways\ndescription: >-\n  Ambassador is a Kubernetes-native API Gateway built on Envoy Proxy, providing routing,\n  load balancing, authentication, and observability for microservices.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n  - name: Ambassador Labs (Datawire)\n    email: support@datawire.io\n    url: https://www.getambassador.io\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ambassador/refs/heads/main/apis.yml
tags:
- API Development
- Gateways
- Ingress
- Kubernetes
- Mock Servers
- Mocks
- Platform
- Testing
url: https://raw.githubusercontent.com/api-evangelist/ambassador/refs/heads/main/apis.yml
use_cases:
- description: Route, secure, and observe traffic to microservices running in Kubernetes clusters.
  name: Microservices API Gateway
- description: Design, mock, and test APIs locally with Blackbird before deploying to Kubernetes environments.
  name: API Development and Testing
- description: Enable multiple teams to independently manage their API routing and configuration using Kubernetes CRDs.
  name: Multi-Team API Management
- description: Serve as the edge gateway in a service mesh architecture, handling north-south traffic with TLS termination.
  name: Service Mesh Edge Gateway
- description: Provide a self-service developer portal for internal and external developers to discover and consume APIs.
  name: Developer Onboarding
---
