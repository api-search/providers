---
api_count: 4
apis:
- description: Kubernetes-native ingress controller and next-generation API gateway built on Envoy Proxy, supporting the Kubernetes Gateway API for traffic management, security, and transformation.
  name: Solo Enterprise for kgateway
  slug: kgateway
- description: Enterprise service mesh solution built on Istio for connecting, securing, and observing microservices across multiple clusters and clouds, including Istio Ambient Mesh support.
  name: Solo Enterprise for Istio
  slug: istio
- description: 'AI connectivity and governance gateway for agents and LLMs, supporting traffic routing, load balancing, failover, guardrails, and MCP server connectivity across providers including OpenAI, Anthropic, '
  name: Solo Enterprise for agentgateway
  slug: agentgateway
- description: Enterprise AI agent framework for Kubernetes that enables building, managing, and scaling intelligent agents with observability, security, human-in-the-loop workflows, and support for multiple LLM pro
  name: Solo Enterprise for kagent
  slug: kagent
common:
- title: ''
  type: Website
  url: https://www.solo.io/
- title: ''
  type: Documentation
  url: https://www.solo.io/docs
- title: ''
  type: Portal
  url: https://www.solo.io/get-started
- title: ''
  type: Pricing
  url: https://www.solo.io/pricing
- title: ''
  type: Blog
  url: https://www.solo.io/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/solo-io
- title: ''
  type: Academy
  url: https://www.solo.io/academy
- title: ''
  type: Training
  url: https://www.solo.io/resources/lab
- title: ''
  type: Webinars
  url: https://www.solo.io/resources/webinar
- title: ''
  type: Customers
  url: https://www.solo.io/customers
- title: ''
  type: Security
  url: https://www.solo.io/security
- title: ''
  type: PrivacyPolicy
  url: https://www.solo.io/privacy-policy/
- title: ''
  type: Legal
  url: https://legal.solo.io/
- title: ''
  type: Support
  url: https://support.solo.io/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/solo.io
- title: ''
  type: X
  url: https://twitter.com/soloio_inc
- title: ''
  type: YouTube
  url: https://www.youtube.com/soloio
- title: Solo-Kit Operator Framework
  type: GitHubRepository
  url: https://github.com/solo-io/solo-kit
- title: Ingress to Gateway Migration Tool
  type: GitHubRepository
  url: https://github.com/solo-io/ingress2gateway
- title: Developer Portal Starter
  type: GitHubRepository
  url: https://github.com/solo-io/dev-portal-starter
- title: External Auth Plugins
  type: GitHubRepository
  url: https://github.com/solo-io/ext-auth-plugins
- title: MCP Flow Examples
  type: CodeExamples
  url: https://github.com/solo-io/enterprise-mcp-flow
- title: Workshops
  type: CodeExamples
  url: https://github.com/solo-io/workshops
- title: Solo.io JSON-LD Context
  type: JSONLD
  url: json-ld/solo-context.jsonld
- title: Solo.io Enterprise Platform Vocabulary
  type: Vocabulary
  url: vocabulary/solo-vocabulary.yml
created: '2026-03-27'
description: Solo.io provides enterprise infrastructure for cloud-native and AI-native environments, including API gateways, service mesh, and agentic AI infrastructure built on Envoy, Istio, and Kubernetes. Products include kgateway (API gateway), Istio-based service mesh, agentgateway (AI gateway), kagent (AI agents for Kubernetes), and agentregistry (MCP registries).
features:
- description: Native support for the Kubernetes Gateway API standard for traffic management.
  name: Kubernetes Gateway API
- description: Built on Envoy Proxy for high-performance traffic handling and extensibility.
  name: Envoy Proxy
- description: Sidecar-less service mesh using Istio Ambient mode for simplified operations.
  name: Istio Ambient Mesh
- description: Connect and secure services across multiple Kubernetes clusters and clouds.
  name: Multi-Cluster Networking
- description: End-to-end mTLS, JWT validation, OAuth, OPA, and external auth for zero-trust architectures.
  name: Zero Trust Security
- description: Route, load balance, and apply guardrails to LLM provider traffic.
  name: AI Gateway
- description: Connect AI agents to MCP servers and manage agent-to-agent communication.
  name: MCP Server Connectivity
- description: Advanced rate limiting for API and AI traffic.
  name: Rate Limiting
- description: Built-in tracing, metrics, and access logging via OpenTelemetry.
  name: OpenTelemetry Observability
- description: Request and response transformation, header manipulation, and content-based routing.
  name: Traffic Transformation
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Core proxy engine powering kgateway and agentgateway.
  name: Envoy Proxy
- description: Service mesh foundation for multi-cluster networking and security.
  name: Istio
- description: Native integration with Kubernetes for deployment and configuration.
  name: Kubernetes
- description: LLM provider integration for AI gateway routing.
  name: OpenAI
- description: Claude LLM provider integration for AI gateway routing.
  name: Anthropic
- description: AWS Bedrock LLM provider integration.
  name: Amazon Bedrock
- description: Azure-hosted OpenAI LLM provider integration.
  name: Azure OpenAI
- description: Google Cloud Vertex AI LLM provider integration.
  name: Google Vertex AI
- description: Observability integration for tracing, metrics, and logging.
  name: OpenTelemetry
- description: GitOps deployment support for Solo products.
  name: ArgoCD
jsonld:
- class_count: 0
  name: Solo Context
  property_count: 9
  slug: solo-context
layout: provider
modified: '2026-05-02'
name: Solo.io
skills: []
slug: solo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: solo\nname: Solo.io\ndescription: >-\n  Solo.io provides enterprise infrastructure for cloud-native and AI-native\n  environments, including API gateways, service mesh, and agentic AI\n  infrastructure built on Envoy, Istio, and Kubernetes. Products include\n  kgateway (API gateway), Istio-based service mesh, agentgateway (AI gateway),\n  kagent (AI agents for Kubernetes), and agentregistry (MCP registries).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI Gateway\n  - Agentic AI\n  - API Gateway\n  - Envoy\n  - Istio\n  - Kubernetes\n  - MCP\n  - Service Mesh\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/solo/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: solo:kgateway\n    name: Solo Enterprise for kgateway\n    description: >-\n      Kubernetes-native ingress controller and next-generation API gateway built\n      on Envoy\
  \ Proxy, supporting the Kubernetes Gateway API for traffic\n      management, security, and transformation.\n    humanURL: https://docs.solo.io/kgateway/\n    tags:\n      - API Gateway\n      - Envoy\n      - Gateway API\n      - Ingress Controller\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://docs.solo.io/kgateway/\n      - type: GettingStarted\n        url: https://docs.solo.io/kgateway/latest/quickstart/\n      - type: APIReference\n        url: https://docs.solo.io/kgateway/latest/reference/api/\n      - type: Authentication\n        url: https://docs.solo.io/kgateway/latest/security/\n      - type: GitHubRepository\n        url: https://github.com/solo-io/gloo\n        title: Gloo Gateway Repository\n      - type: SDK\n        url: https://github.com/solo-io/kgateway-client\n        title: Go Client\n      - type: KubernetesCRD\n        url: crd/solo-gloo-enterprise-gloo-solo-io-v1-authconfig.yaml\n        title: AuthConfig CRD\n      - type:\
  \ KubernetesCRD\n        url: crd/solo-gloo-gateway-gloo-solo-io-directresponses.yaml\n        title: DirectResponse CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gateway-gloo-solo-io-gatewayparameters.yaml\n        title: GatewayParameters CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gateway-solo-io-v1-gateway.yaml\n        title: Gateway CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gateway-solo-io-v1-httplisteneroption.yaml\n        title: HttpListenerOption CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gateway-solo-io-v1-listeneroption.yaml\n        title: ListenerOption CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gateway-solo-io-v1-matchablehttpgateway.yaml\n        title: MatchableHttpGateway CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gateway-solo-io-v1-matchabletcpgateway.yaml\n        title: MatchableTcpGateway CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gateway-solo-io-v1-routeoption.yaml\n\
  \        title: RouteOption CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gateway-solo-io-v1-routetable.yaml\n        title: RouteTable CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gateway-solo-io-v1-virtualhostoption.yaml\n        title: VirtualHostOption CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gateway-solo-io-v1-virtualservice.yaml\n        title: VirtualService CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gloo-solo-io-v1-proxy.yaml\n        title: Proxy CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gloo-solo-io-v1-settings.yaml\n        title: Settings CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gloo-solo-io-v1-upstream.yaml\n        title: Upstream CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-gloo-solo-io-v1-upstreamgroup.yaml\n        title: UpstreamGroup CRD\n      - type: KubernetesCRD\n        url: crd/solo-gloo-ratelimit-config.yaml\n        title: RateLimitConfig\
  \ CRD\n      - type: KubernetesCRD\n        url: crd/solo-kgateway-tcproute-crd.yaml\n        title: TCPRoute CRD\n      - type: JSONSchema\n        url: json-schema/solo-gloo-upstream-schema.json\n        title: Upstream JSON Schema\n      - type: JSONSchema\n        url: json-schema/solo-gloo-virtual-service-schema.json\n        title: VirtualService JSON Schema\n      - type: JSONStructure\n        url: json-structure/solo-kgateway-structure.json\n        title: kgateway CRD Structure\n      - type: Example\n        url: examples/solo-gloo-upstream-kube-example.json\n        title: Kubernetes Upstream Example\n\n  - aid: solo:istio\n    name: Solo Enterprise for Istio\n    description: >-\n      Enterprise service mesh solution built on Istio for connecting, securing,\n      and observing microservices across multiple clusters and clouds, including\n      Istio Ambient Mesh support.\n    humanURL: https://docs.solo.io/gloo-mesh/latest/\n    tags:\n      - Ambient Mesh\n      - Istio\n\
  \      - Multi-Cluster\n      - Service Mesh\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url: https://docs.solo.io/gloo-mesh/latest/\n\n  - aid: solo:agentgateway\n    name: Solo Enterprise for agentgateway\n    description: >-\n      AI connectivity and governance gateway for agents and LLMs, supporting\n      traffic routing, load balancing, failover, guardrails, and MCP server\n      connectivity across providers including OpenAI, Anthropic, Amazon Bedrock,\n      Azure OpenAI, Gemini, Vertex AI, Ollama, and vLLM.\n    humanURL: https://docs.solo.io/agentgateway\n    tags:\n      - Agentic AI\n      - AI Gateway\n      - Guardrails\n      - LLM\n      - MCP\n    properties:\n      - type: Documentation\n        url: https://docs.solo.io/agentgateway\n      - type: GettingStarted\n        url: https://docs.solo.io/agentgateway/latest/quickstart/\n      - type: Authentication\n        url: https://docs.solo.io/agentgateway/latest/security/\n      - type:\
  \ GitHubRepository\n        url: https://github.com/solo-io/agentgateway-new-ui\n        title: Agentgateway Repository\n      - type: KubernetesCRD\n        url: crd/solo-agentgateway-agentgatewaybackends.yaml\n        title: AgentgatewayBackend CRD\n      - type: KubernetesCRD\n        url: crd/solo-agentgateway-agentgatewayparameters.yaml\n        title: AgentgatewayParameters CRD\n      - type: KubernetesCRD\n        url: crd/solo-agentgateway-agentgatewaypolicies.yaml\n        title: AgentgatewayPolicy CRD\n      - type: JSONSchema\n        url: json-schema/solo-agentgateway-backend-schema.json\n        title: AgentgatewayBackend JSON Schema\n      - type: JSONStructure\n        url: json-structure/solo-agentgateway-structure.json\n        title: agentgateway CRD Structure\n      - type: Example\n        url: examples/solo-agentgateway-backend-example.json\n        title: AgentgatewayBackend Example\n\n  - aid: solo:kagent\n    name: Solo Enterprise for kagent\n    description: >-\n\
  \      Enterprise AI agent framework for Kubernetes that enables building,\n      managing, and scaling intelligent agents with observability, security,\n      human-in-the-loop workflows, and support for multiple LLM providers.\n    humanURL: https://docs.solo.io/kagent-enterprise/latest\n    tags:\n      - Agentic AI\n      - AI Agents\n      - Kubernetes\n      - LLM\n    properties:\n      - type: Documentation\n        url: https://docs.solo.io/kagent-enterprise/latest\n      - type: GettingStarted\n        url: https://docs.solo.io/kagent-enterprise/latest/quickstart/\n\ncommon:\n  - type: Website\n    url: https://www.solo.io/\n  - type: Documentation\n    url: https://www.solo.io/docs\n  - type: Portal\n    url: https://www.solo.io/get-started\n  - type: Pricing\n    url: https://www.solo.io/pricing\n  - type: Blog\n    url: https://www.solo.io/blog\n  - type: GitHubOrganization\n    url: https://github.com/solo-io\n  - type: Academy\n    url: https://www.solo.io/academy\n  - type:\
  \ Training\n    url: https://www.solo.io/resources/lab\n  - type: Webinars\n    url: https://www.solo.io/resources/webinar\n  - type: Customers\n    url: https://www.solo.io/customers\n  - type: Security\n    url: https://www.solo.io/security\n  - type: PrivacyPolicy\n    url: https://www.solo.io/privacy-policy/\n  - type: Legal\n    url: https://legal.solo.io/\n  - type: Support\n    url: https://support.solo.io/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/solo.io\n  - type: X\n    url: https://twitter.com/soloio_inc\n  - type: YouTube\n    url: https://www.youtube.com/soloio\n  - type: GitHubRepository\n    url: https://github.com/solo-io/solo-kit\n    title: Solo-Kit Operator Framework\n  - type: GitHubRepository\n    url: https://github.com/solo-io/ingress2gateway\n    title: Ingress to Gateway Migration Tool\n  - type: GitHubRepository\n    url: https://github.com/solo-io/dev-portal-starter\n    title: Developer Portal Starter\n  - type: GitHubRepository\n    url:\
  \ https://github.com/solo-io/ext-auth-plugins\n    title: External Auth Plugins\n  - type: CodeExamples\n    url: https://github.com/solo-io/enterprise-mcp-flow\n    title: MCP Flow Examples\n  - type: CodeExamples\n    url: https://github.com/solo-io/workshops\n    title: Workshops\n  - type: JSONLD\n    url: json-ld/solo-context.jsonld\n    title: Solo.io JSON-LD Context\n  - type: Vocabulary\n    url: vocabulary/solo-vocabulary.yml\n    title: Solo.io Enterprise Platform Vocabulary\n  - type: Features\n    data:\n      - name: Kubernetes Gateway API\n        description: Native support for the Kubernetes Gateway API standard for traffic management.\n      - name: Envoy Proxy\n        description: Built on Envoy Proxy for high-performance traffic handling and extensibility.\n      - name: Istio Ambient Mesh\n        description: Sidecar-less service mesh using Istio Ambient mode for simplified operations.\n      - name: Multi-Cluster Networking\n        description: Connect and secure\
  \ services across multiple Kubernetes clusters and clouds.\n      - name: Zero Trust Security\n        description: End-to-end mTLS, JWT validation, OAuth, OPA, and external auth for zero-trust architectures.\n      - name: AI Gateway\n        description: Route, load balance, and apply guardrails to LLM provider traffic.\n      - name: MCP Server Connectivity\n        description: Connect AI agents to MCP servers and manage agent-to-agent communication.\n      - name: Rate Limiting\n        description: Advanced rate limiting for API and AI traffic.\n      - name: OpenTelemetry Observability\n        description: Built-in tracing, metrics, and access logging via OpenTelemetry.\n      - name: Traffic Transformation\n        description: Request and response transformation, header manipulation, and content-based routing.\n  - type: UseCases\n    data:\n      - name: API Gateway Modernization\n        description: Replace legacy API gateways with a Kubernetes-native, Envoy-based gateway.\n\
  \      - name: Service Mesh Adoption\n        description: Adopt Istio service mesh for microservice security and observability.\n      - name: Multi-Cloud Connectivity\n        description: Connect services across AWS, GCP, Azure, and on-premises environments.\n      - name: AI Agent Infrastructure\n        description: Build, deploy, and manage AI agents securely in Kubernetes.\n      - name: LLM Gateway\n        description: Centralize LLM provider access with routing, failover, and cost controls.\n  - type: Integrations\n    data:\n      - name: Envoy Proxy\n        description: Core proxy engine powering kgateway and agentgateway.\n      - name: Istio\n        description: Service mesh foundation for multi-cluster networking and security.\n      - name: Kubernetes\n        description: Native integration with Kubernetes for deployment and configuration.\n      - name: OpenAI\n        description: LLM provider integration for AI gateway routing.\n      - name: Anthropic\n        description:\
  \ Claude LLM provider integration for AI gateway routing.\n      - name: Amazon Bedrock\n        description: AWS Bedrock LLM provider integration.\n      - name: Azure OpenAI\n        description: Azure-hosted OpenAI LLM provider integration.\n      - name: Google Vertex AI\n        description: Google Cloud Vertex AI LLM provider integration.\n      - name: OpenTelemetry\n        description: Observability integration for tracing, metrics, and logging.\n      - name: ArgoCD\n        description: GitOps deployment support for Solo products.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/solo/refs/heads/main/apis.yml
tags:
- AI Gateway
- Agentic AI
- API Gateway
- Envoy
- Istio
- Kubernetes
- MCP
- Service Mesh
url: https://raw.githubusercontent.com/api-evangelist/solo/refs/heads/main/apis.yml
use_cases:
- description: Replace legacy API gateways with a Kubernetes-native, Envoy-based gateway.
  name: API Gateway Modernization
- description: Adopt Istio service mesh for microservice security and observability.
  name: Service Mesh Adoption
- description: Connect services across AWS, GCP, Azure, and on-premises environments.
  name: Multi-Cloud Connectivity
- description: Build, deploy, and manage AI agents securely in Kubernetes.
  name: AI Agent Infrastructure
- description: Centralize LLM provider access with routing, failover, and cost controls.
  name: LLM Gateway
---
