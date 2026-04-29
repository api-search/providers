---
api_count: 4
api_specs:
- filename: amazon-api-gateway-openapi.yaml
  format: yaml
  label: Amazon API Gateway REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-api-gateway/refs/heads/main/openapi/amazon-api-gateway-openapi.yaml
- filename: amazon-api-gateway-websocket-asyncapi.yml
  format: yaml
  label: Amazon API Gateway WebSocket API
  slug: websocket-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-api-gateway/refs/heads/main/asyncapi/amazon-api-gateway-websocket-asyncapi.yml
apis:
- description: RESTful APIs that are optimized for serverless workloads and HTTP backends using HTTP APIs.
  name: Amazon API Gateway REST API
  slug: rest-api
- description: Build real-time two-way communication applications with WebSocket APIs.
  name: Amazon API Gateway WebSocket API
  slug: websocket-api
- description: Lower latency and lower cost alternative to REST APIs with essential features for building HTTP-based APIs.
  name: Amazon API Gateway HTTP API
  slug: http-api
- description: API for directly managing runtime aspects of deployed APIs, including sending data to connected WebSocket clients via the @connections endpoint and managing connection state.
  name: Amazon API Gateway Management API
  slug: management-api
asyncapis:
- description: Amazon API Gateway WebSocket APIs enable real-time two-way communication between clients and backend services. Clients connect via WebSocket protocol and exchange messages through routes that map to L
  name: Amazon API Gateway WebSocket API
  slug: amazon-api-gateway-websocket-asyncapi
capabilities:
- description: Workflow capability for managing API Gateway REST APIs including lifecycle management, stage deployment, and configuration.
  name: Amazon API Gateway Management
  slug: api-gateway-management
common:
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/compute/category/application-services/amazon-api-gateway/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/apigateway
- title: ''
  type: CLIReference
  url: https://docs.aws.amazon.com/cli/latest/reference/apigateway/
- title: ''
  type: SDK
  url: https://aws.amazon.com/tools/
- title: ''
  type: Status
  url: https://status.aws.amazon.com/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: Website
  url: https://aws.amazon.com/api-gateway/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/apigateway/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/api-gateway/pricing/
- title: ''
  type: Getting Started
  url: https://aws.amazon.com/api-gateway/getting-started/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/api-gateway/faqs/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-api-gateway
- title: ''
  type: CodeExamples
  url: https://docs.aws.amazon.com/code-library/latest/ug/api-gateway_code_examples.html
- title: ''
  type: SpectralRules
  url: rules/amazon-api-gateway-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/api-gateway-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-api-gateway-vocabulary.yaml
created: '2024-01-15'
description: Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.
features:
- description: Create, configure, and manage REST APIs with resources, methods, integrations, and request/response transformations.
  name: REST API Management
- description: Build real-time two-way communication applications with WebSocket APIs supporting persistent connections and message routing.
  name: WebSocket API Support
- description: Deploy lightweight HTTP APIs with lower latency and cost than REST APIs, optimized for Lambda and HTTP backends.
  name: HTTP API Support
- description: Manage deployment stages with canary releases, stage variables, and throttling configurations for blue/green deployments.
  name: Stage and Deployment Management
- description: Secure APIs with IAM authorization, Lambda authorizers, Cognito user pools, and resource-based policies.
  name: API Security and Authorization
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integrate API Gateway with Lambda functions for serverless request processing without managing infrastructure.
  name: AWS Lambda
- description: Use Cognito user pools and identity pools for managed authentication and authorization in API Gateway.
  name: AWS Cognito
- description: Protect API Gateway endpoints with AWS WAF rules for rate limiting and protection against common web exploits.
  name: AWS WAF
- description: Monitor API performance, errors, and latency using CloudWatch metrics and logs integrated with API Gateway.
  name: AWS CloudWatch
jsonld:
- class_count: 0
  name: Amazon Api Gateway Context
  property_count: 13
  slug: amazon-api-gateway-context
layout: provider
modified: '2026-04-19'
name: Amazon API Gateway
rules:
- name: Amazon API Gateway API Rules
  rule_count: 5
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 0
  slug: amazon-api-gateway-spectral-rules
skills: []
slug: amazon-api-gateway
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon API Gateway\ndescription: Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-api-gateway/refs/heads/main/apis.yml\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Gateway\n- HTTP API\n- REST API\n- Serverless\n- WebSocket\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon API Gateway REST API\n  description: >-\n    RESTful APIs that are optimized for serverless workloads and HTTP backends using\n    HTTP APIs.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/api-gateway/\n  baseURL: https://apigateway.{region}.amazonaws.com\n  tags:\n  - API Management\n  - REST\n  - Serverless\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html\n\
  \  - type: OpenAPI\n    url: https://docs.aws.amazon.com/apigateway/latest/api/API_Operations.html\n  - type: Pricing\n    url: https://aws.amazon.com/api-gateway/pricing/\n  - type: Getting Started\n    url: https://aws.amazon.com/api-gateway/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/api-gateway/faqs/\n  - type: Features\n    url: https://aws.amazon.com/api-gateway/features/\n  - type: Developer Guide\n    url: https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html\n  - type: API Reference\n    url: https://docs.aws.amazon.com/apigateway/latest/api/API_Operations.html\n  - type: Quotas\n    url: https://docs.aws.amazon.com/apigateway/latest/developerguide/limits.html\n  - type: OpenAPI\n    url: openapi/amazon-api-gateway-openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-api-gateway-accesslogsettings-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-api-gateway-api-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-api-gateway-apikey-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/amazon-api-gateway-apikeys-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-api-gateway-apistage-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-api-gateway-accesslogsettings-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-api-gateway-apikey-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-api-gateway-apikeys-structure.json\n  - type: JSONLD\n    url: json-ld/amazon-api-gateway-context.jsonld\n  aid: amazon-api-gateway:rest-api\n- name: Amazon API Gateway WebSocket API\n  description: >-\n    Build real-time two-way communication applications with WebSocket APIs.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/api-gateway/\n  baseURL: https://apigateway.{region}.amazonaws.com\n  tags:\n  - Bi-Directional\n  - Real-Time\n  - WebSocket\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-websocket-api.html\n\
  \  - type: Getting Started\n    url: https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-websocket-api-overview.html\n  - type: AsyncAPI\n    url: asyncapi/amazon-api-gateway-websocket-asyncapi.yml\n  - type: JSON-LD\n    url: json-ld/amazon-api-gateway-context.jsonld\n  aid: amazon-api-gateway:websocket-api\n- name: Amazon API Gateway HTTP API\n  description: >-\n    Lower latency and lower cost alternative to REST APIs with essential features\n    for building HTTP-based APIs.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/api-gateway/\n  baseURL: https://apigateway.{region}.amazonaws.com\n  tags:\n  - Cost Effective\n  - HTTP\n  - Low Latency\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api.html\n  - type: Comparison\n    url: https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api-vs-rest.html\n  aid: amazon-api-gateway:http-api\n\
  - name: Amazon API Gateway Management API\n  description: >-\n    API for directly managing runtime aspects of deployed APIs, including\n    sending data to connected WebSocket clients via the @connections\n    endpoint and managing connection state.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-how-to-call-websocket-api-connections.html\n  baseURL: https://{api-id}.execute-api.{region}.amazonaws.com/{stage}\n  tags:\n  - Connections\n  - Management\n  - Runtime\n  - WebSocket\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-how-to-call-websocket-api-connections.html\n  aid: amazon-api-gateway:management-api\ncommon:\n- type: Blog\n  url: https://aws.amazon.com/blogs/compute/category/application-services/amazon-api-gateway/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type:\
  \ Console\n  url: https://console.aws.amazon.com/apigateway\n- type: CLIReference\n  url: https://docs.aws.amazon.com/cli/latest/reference/apigateway/\n- type: SDK\n  url: https://aws.amazon.com/tools/\n- type: Status\n  url: https://status.aws.amazon.com/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: Website\n  url: https://aws.amazon.com/api-gateway/\n- type: Documentation\n  url: https://docs.aws.amazon.com/apigateway/\n- type: Pricing\n  url: https://aws.amazon.com/api-gateway/pricing/\n- type: Getting Started\n  url: https://aws.amazon.com/api-gateway/getting-started/\n- type: FAQ\n  url: https://aws.amazon.com/api-gateway/faqs/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-api-gateway\n\
  - type: CodeExamples\n  url: https://docs.aws.amazon.com/code-library/latest/ug/api-gateway_code_examples.html\n- type: SpectralRules\n  url: rules/amazon-api-gateway-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/api-gateway-management.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-api-gateway-vocabulary.yaml\n- type: Features\n  data:\n  - name: REST API Management\n    description: Create, configure, and manage REST APIs with resources, methods, integrations, and request/response transformations.\n  - name: WebSocket API Support\n    description: Build real-time two-way communication applications with WebSocket APIs supporting persistent connections and message routing.\n  - name: HTTP API Support\n    description: Deploy lightweight HTTP APIs with lower latency and cost than REST APIs, optimized for Lambda and HTTP backends.\n  - name: Stage and Deployment Management\n    description: Manage deployment stages with canary releases, stage variables, and throttling\
  \ configurations for blue/green deployments.\n  - name: API Security and Authorization\n    description: Secure APIs with IAM authorization, Lambda authorizers, Cognito user pools, and resource-based policies.\n- type: UseCases\n  data:\n  - name: Serverless API Backend\n    description: Build serverless REST APIs backed by Lambda functions using API Gateway as the front door for request routing.\n  - name: Microservices Gateway\n    description: Use API Gateway as a unified entry point for microservices, providing routing, authentication, and rate limiting.\n  - name: Real-Time Applications\n    description: Build chat, collaboration, and live data streaming applications using WebSocket APIs with persistent client connections.\n  - name: API Lifecycle Automation\n    description: Automate API creation, deployment, and versioning using the API Gateway control plane API in CI/CD pipelines.\n- type: Integrations\n  data:\n  - name: AWS Lambda\n    description: Integrate API Gateway with\
  \ Lambda functions for serverless request processing without managing infrastructure.\n  - name: AWS Cognito\n    description: Use Cognito user pools and identity pools for managed authentication and authorization in API Gateway.\n  - name: AWS WAF\n    description: Protect API Gateway endpoints with AWS WAF rules for rate limiting and protection against common web exploits.\n  - name: AWS CloudWatch\n    description: Monitor API performance, errors, and latency using CloudWatch metrics and logs integrated with API Gateway.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\naid: amazon-api-gateway\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-api-gateway/refs/heads/main/apis.yml
tags:
- AWS
- Gateway
- HTTP API
- REST API
- Serverless
- WebSocket
url: https://raw.githubusercontent.com/api-evangelist/amazon-api-gateway/refs/heads/main/apis.yml
use_cases:
- description: Build serverless REST APIs backed by Lambda functions using API Gateway as the front door for request routing.
  name: Serverless API Backend
- description: Use API Gateway as a unified entry point for microservices, providing routing, authentication, and rate limiting.
  name: Microservices Gateway
- description: Build chat, collaboration, and live data streaming applications using WebSocket APIs with persistent client connections.
  name: Real-Time Applications
- description: Automate API creation, deployment, and versioning using the API Gateway control plane API in CI/CD pipelines.
  name: API Lifecycle Automation
---
