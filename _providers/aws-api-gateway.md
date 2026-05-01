---
api_count: 3
api_specs:
- filename: aws-api-gateway-v1-openapi.yml
  format: yaml
  label: Amazon API Gateway V1 (REST)
  slug: aws-api-gateway-v1
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/openapi/aws-api-gateway-v1-openapi.yml
- filename: aws-api-gateway-v2-openapi.yml
  format: yaml
  label: Amazon API Gateway V2 (HTTP and WebSocket)
  slug: aws-api-gateway-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/openapi/aws-api-gateway-v2-openapi.yml
- filename: aws-api-gateway-management-openapi.yml
  format: yaml
  label: Amazon API Gateway Management API
  slug: aws-api-gateway-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/openapi/aws-api-gateway-management-openapi.yml
apis:
- description: The API Gateway V1 control plane API is used to create, deploy, and manage REST APIs in Amazon API Gateway. It exposes resources for RestApis, Resources, Methods, Stages, Deployments, Authorizers, API
  name: Amazon API Gateway V1 (REST)
  slug: aws-api-gateway-v1
- description: The API Gateway V2 control plane API is used to create, deploy, and manage HTTP APIs and WebSocket APIs in Amazon API Gateway. It provides resources for Apis, Routes, Integrations, Stages, Deployments
  name: Amazon API Gateway V2 (HTTP and WebSocket)
  slug: aws-api-gateway-v2
- description: The API Gateway Management API allows backend services to send messages to connected clients of a deployed WebSocket API and to disconnect clients. Requests are made against the deployed stage's callb
  name: Amazon API Gateway Management API
  slug: aws-api-gateway-management
capabilities:
- description: Unified workflow capability for API platform engineers and developers to create, configure, deploy, and monitor REST and HTTP APIs in Amazon API Gateway. Combines V1 REST APIs, V2 HTTP/WebSocket APIs,
  name: Amazon API Gateway API Management Workflow
  slug: api-management-workflow
common:
- title: ''
  type: Website
  url: https://aws.amazon.com/api-gateway/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/apigateway/
- title: ''
  type: GettingStarted
  url: https://docs.aws.amazon.com/apigateway/latest/developerguide/getting-started.html
- title: ''
  type: Pricing
  url: https://aws.amazon.com/api-gateway/pricing/
- title: ''
  type: RateLimits
  url: https://docs.aws.amazon.com/apigateway/latest/developerguide/limits.html
- title: AWS SDKs
  type: SDK
  url: https://aws.amazon.com/tools/
- title: ''
  type: CLI
  url: https://docs.aws.amazon.com/cli/latest/reference/apigateway/
- title: ''
  type: ChangeLog
  url: https://docs.aws.amazon.com/apigateway/latest/developerguide/history.html
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/compute/category/compute/amazon-api-gateway/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/apigateway/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/aws-api-gateway
- title: ''
  type: SpectralRules
  url: rules/aws-api-gateway-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/aws-api-gateway-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/api-management-workflow.yaml
created: '2026-03-27'
description: Amazon API Gateway is a fully managed service that makes it easy to create, publish, maintain, monitor, and secure APIs at any scale. It acts as the front door for applications to access backend services, supporting REST APIs, HTTP APIs, and WebSocket APIs with built-in traffic management, authorization, monitoring, and API version management. API Gateway integrates natively with AWS Lambda, CloudWatch, CloudFront, IAM, and Cognito for comprehensive serverless and secure API deployment.
features:
- description: Create, deploy, and manage REST APIs with full lifecycle control including stages, deployments, and versioning.
  name: REST API Management
- description: Build lightweight HTTP APIs optimized for serverless workloads at up to 71% lower cost than REST APIs.
  name: HTTP API Support
- description: Enable real-time bidirectional communication for chat platforms, streaming dashboards, and live applications.
  name: WebSocket APIs
- description: Handle hundreds of thousands of concurrent API calls with built-in throttling and request validation.
  name: Traffic Management
- description: Supports IAM policies, Lambda authorizers, Amazon Cognito user pools, and OAuth2/OIDC for API access control.
  name: Authorization and Security
- description: Integration with CloudWatch metrics, access logging, and CloudTrail for full API observability.
  name: Monitoring and Logging
- description: Map APIs to branded custom domains with TLS certificates managed through AWS Certificate Manager.
  name: Custom Domain Names
- description: Safely roll out API changes using canary deployment stages with configurable traffic splitting.
  name: Canary Releases
- description: Protect APIs against common web exploits and DDoS attacks using AWS Web Application Firewall.
  name: AWS WAF Integration
- description: Automatically generate client SDKs for deployed APIs in multiple programming languages.
  name: SDK Generation
- description: Reduce backend load and improve response times with configurable response caching at the stage level.
  name: API Caching
- description: Leverage Amazon CloudFront edge locations for global low-latency API distribution.
  name: CloudFront Edge Distribution
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Invoke Lambda functions as API backends for fully serverless request handling.
  name: AWS Lambda
- description: Authenticate and authorize API requests using Cognito user pools and identity pools.
  name: Amazon Cognito
- description: Monitor API performance metrics, error rates, and latency with CloudWatch dashboards and alarms.
  name: Amazon CloudWatch
- description: Audit all API Gateway management API calls for compliance and security monitoring.
  name: AWS CloudTrail
- description: Distribute APIs globally through CloudFront edge locations for reduced latency.
  name: Amazon CloudFront
- description: Apply web application firewall rules to protect APIs from malicious traffic.
  name: AWS WAF
- description: Trace requests end-to-end through API Gateway and backend services for performance analysis.
  name: AWS X-Ray
- description: Control API access using IAM policies and resource-based policies for fine-grained authorization.
  name: AWS IAM
- description: Provision and manage TLS certificates for custom domain names on API Gateway.
  name: AWS Certificate Manager
- description: Create private APIs accessible only within a VPC using VPC endpoint integration.
  name: Amazon VPC
jsonld:
- class_count: 1
  name: Aws Api Gateway Management Connection Context
  property_count: 5
  slug: aws-api-gateway-management-connection-context
- class_count: 1
  name: Aws Api Gateway Management Identity Context
  property_count: 2
  slug: aws-api-gateway-management-identity-context
- class_count: 3
  name: Aws Api Gateway V1 Api Context
  property_count: 4
  slug: aws-api-gateway-v1-api-context
- class_count: 7
  name: Aws Api Gateway V1 Create Context
  property_count: 10
  slug: aws-api-gateway-v1-create-context
- class_count: 2
  name: Aws Api Gateway V1 Deployment Context
  property_count: 2
  slug: aws-api-gateway-v1-deployment-context
- class_count: 1
  name: Aws Api Gateway V1 Deployments Context
  property_count: 1
  slug: aws-api-gateway-v1-deployments-context
- class_count: 1
  name: Aws Api Gateway V1 Endpoint Context
  property_count: 1
  slug: aws-api-gateway-v1-endpoint-context
- class_count: 1
  name: Aws Api Gateway V1 Method Context
  property_count: 3
  slug: aws-api-gateway-v1-method-context
- class_count: 1
  name: Aws Api Gateway V1 Put Context
  property_count: 2
  slug: aws-api-gateway-v1-put-context
- class_count: 1
  name: Aws Api Gateway V1 Quota Context
  property_count: 2
  slug: aws-api-gateway-v1-quota-context
- class_count: 1
  name: Aws Api Gateway V1 Resource Context
  property_count: 4
  slug: aws-api-gateway-v1-resource-context
- class_count: 1
  name: Aws Api Gateway V1 Resources Context
  property_count: 1
  slug: aws-api-gateway-v1-resources-context
- class_count: 5
  name: Aws Api Gateway V1 Rest Context
  property_count: 5
  slug: aws-api-gateway-v1-rest-context
- class_count: 2
  name: Aws Api Gateway V1 Stage Context
  property_count: 2
  slug: aws-api-gateway-v1-stage-context
- class_count: 1
  name: Aws Api Gateway V1 Stages Context
  property_count: 1
  slug: aws-api-gateway-v1-stages-context
- class_count: 1
  name: Aws Api Gateway V1 Throttle Context
  property_count: 2
  slug: aws-api-gateway-v1-throttle-context
- class_count: 3
  name: Aws Api Gateway V1 Usage Context
  property_count: 8
  slug: aws-api-gateway-v1-usage-context
- class_count: 1
  name: Aws Api Gateway V2 Api Context
  property_count: 6
  slug: aws-api-gateway-v2-api-context
- class_count: 1
  name: Aws Api Gateway V2 Apis Context
  property_count: 1
  slug: aws-api-gateway-v2-apis-context
- class_count: 1
  name: Aws Api Gateway V2 Authorizer Context
  property_count: 4
  slug: aws-api-gateway-v2-authorizer-context
- class_count: 1
  name: Aws Api Gateway V2 Authorizers Context
  property_count: 1
  slug: aws-api-gateway-v2-authorizers-context
- class_count: 6
  name: Aws Api Gateway V2 Create Context
  property_count: 16
  slug: aws-api-gateway-v2-create-context
- class_count: 1
  name: Aws Api Gateway V2 Deployment Context
  property_count: 4
  slug: aws-api-gateway-v2-deployment-context
- class_count: 1
  name: Aws Api Gateway V2 Deployments Context
  property_count: 1
  slug: aws-api-gateway-v2-deployments-context
- class_count: 1
  name: Aws Api Gateway V2 Integration Context
  property_count: 4
  slug: aws-api-gateway-v2-integration-context
- class_count: 1
  name: Aws Api Gateway V2 Integrations Context
  property_count: 1
  slug: aws-api-gateway-v2-integrations-context
- class_count: 1
  name: Aws Api Gateway V2 Route Context
  property_count: 4
  slug: aws-api-gateway-v2-route-context
- class_count: 1
  name: Aws Api Gateway V2 Routes Context
  property_count: 1
  slug: aws-api-gateway-v2-routes-context
- class_count: 1
  name: Aws Api Gateway V2 Stage Context
  property_count: 4
  slug: aws-api-gateway-v2-stage-context
- class_count: 1
  name: Aws Api Gateway V2 Stages Context
  property_count: 1
  slug: aws-api-gateway-v2-stages-context
layout: provider
modified: '2026-04-19'
name: Amazon API Gateway
rules:
- name: Amazon API Gateway API Rules
  rule_count: 35
  severity_counts:
    error: 17
    hint: 0
    info: 1
    warn: 17
  slug: aws-api-gateway-spectral-rules
skills: []
slug: aws-api-gateway
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: aws-api-gateway\nname: Amazon API Gateway\ndescription: >-\n  Amazon API Gateway is a fully managed service that makes it easy to create,\n  publish, maintain, monitor, and secure APIs at any scale. It acts as the front\n  door for applications to access backend services, supporting REST APIs, HTTP\n  APIs, and WebSocket APIs with built-in traffic management, authorization,\n  monitoring, and API version management. API Gateway integrates natively with\n  AWS Lambda, CloudWatch, CloudFront, IAM, and Cognito for comprehensive\n  serverless and secure API deployment.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - AWS\n  - Cloud\n  - REST\n  - WebSocket\n  - Serverless\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: aws-api-gateway:aws-api-gateway-v1\n\
  \    name: Amazon API Gateway V1 (REST)\n    description: >-\n      The API Gateway V1 control plane API is used to create, deploy, and manage\n      REST APIs in Amazon API Gateway. It exposes resources for RestApis,\n      Resources, Methods, Stages, Deployments, Authorizers, API keys, usage\n      plans, and related configuration.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html\n    baseURL: https://apigateway.{region}.amazonaws.com\n    tags:\n      - API Gateway\n      - AWS\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/apigateway/latest/developerguide/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/apigateway/latest/api/Welcome.html\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/apigateway/latest/developerguide/getting-started.html\n      - type: Authentication\n\
  \        url: https://docs.aws.amazon.com/apigateway/latest/developerguide/permissions.html\n      - type: OpenAPI\n        url: openapi/aws-api-gateway-v1-openapi.yml\n  - aid: aws-api-gateway:aws-api-gateway-v2\n    name: Amazon API Gateway V2 (HTTP and WebSocket)\n    description: >-\n      The API Gateway V2 control plane API is used to create, deploy, and manage\n      HTTP APIs and WebSocket APIs in Amazon API Gateway. It provides resources\n      for Apis, Routes, Integrations, Stages, Deployments, and Authorizers for\n      the newer HTTP and WebSocket API types.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api.html\n    baseURL: https://apigateway.{region}.amazonaws.com\n    tags:\n      - API Gateway\n      - AWS\n      - HTTP\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api.html\n\
  \      - type: APIReference\n        url: https://docs.aws.amazon.com/apigatewayv2/latest/api-reference/Welcome.html\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api-develop.html\n      - type: Documentation\n        url: https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-websocket-api.html\n        title: WebSocket API Guide\n      - type: OpenAPI\n        url: openapi/aws-api-gateway-v2-openapi.yml\n  - aid: aws-api-gateway:aws-api-gateway-management\n    name: Amazon API Gateway Management API\n    description: >-\n      The API Gateway Management API allows backend services to send messages to\n      connected clients of a deployed WebSocket API and to disconnect clients.\n      Requests are made against the deployed stage's callback URL.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.aws.amazon.com/apigatewaymanagementapi/latest/reference/Welcome.html\n\
  \    baseURL: https://{api-id}.execute-api.{region}.amazonaws.com/{stage}\n    tags:\n      - API Gateway\n      - AWS\n      - Callback\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-how-to-call-websocket-api-connections.html\n      - type: APIReference\n        url: https://docs.aws.amazon.com/apigatewaymanagementapi/latest/reference/Welcome.html\n      - type: OpenAPI\n        url: openapi/aws-api-gateway-management-openapi.yml\ncommon:\n  - type: Website\n    url: https://aws.amazon.com/api-gateway/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/apigateway/\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/apigateway/latest/developerguide/getting-started.html\n  - type: Pricing\n    url: https://aws.amazon.com/api-gateway/pricing/\n  - type: RateLimits\n    url: https://docs.aws.amazon.com/apigateway/latest/developerguide/limits.html\n  - type: SDK\n\
  \    url: https://aws.amazon.com/tools/\n    title: AWS SDKs\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/apigateway/\n  - type: ChangeLog\n    url: https://docs.aws.amazon.com/apigateway/latest/developerguide/history.html\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/compute/category/compute/amazon-api-gateway/\n  - type: Console\n    url: https://console.aws.amazon.com/apigateway/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/aws-api-gateway\n  - type: SpectralRules\n    url: rules/aws-api-gateway-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/aws-api-gateway-vocabulary.yaml\n\
  \  - type: NaftikoCapability\n    url: capabilities/api-management-workflow.yaml\n  - type: Features\n    data:\n      - name: REST API Management\n        description: Create, deploy, and manage REST APIs with full lifecycle control including stages, deployments, and versioning.\n      - name: HTTP API Support\n        description: Build lightweight HTTP APIs optimized for serverless workloads at up to 71% lower cost than REST APIs.\n      - name: WebSocket APIs\n        description: Enable real-time bidirectional communication for chat platforms, streaming dashboards, and live applications.\n      - name: Traffic Management\n        description: Handle hundreds of thousands of concurrent API calls with built-in throttling and request validation.\n      - name: Authorization and Security\n        description: Supports IAM policies, Lambda authorizers, Amazon Cognito user pools, and OAuth2/OIDC for API access control.\n      - name: Monitoring and Logging\n        description: Integration\
  \ with CloudWatch metrics, access logging, and CloudTrail for full API observability.\n      - name: Custom Domain Names\n        description: Map APIs to branded custom domains with TLS certificates managed through AWS Certificate Manager.\n      - name: Canary Releases\n        description: Safely roll out API changes using canary deployment stages with configurable traffic splitting.\n      - name: AWS WAF Integration\n        description: Protect APIs against common web exploits and DDoS attacks using AWS Web Application Firewall.\n      - name: SDK Generation\n        description: Automatically generate client SDKs for deployed APIs in multiple programming languages.\n      - name: API Caching\n        description: Reduce backend load and improve response times with configurable response caching at the stage level.\n      - name: CloudFront Edge Distribution\n        description: Leverage Amazon CloudFront edge locations for global low-latency API distribution.\n  - type: UseCases\n\
  \    data:\n      - name: Serverless API Backend\n        description: Build fully serverless APIs with API Gateway as the front door and AWS Lambda as the backend compute layer.\n      - name: Microservices Gateway\n        description: Consolidate access to multiple microservices behind a single API endpoint with routing and load balancing.\n      - name: Real-Time Applications\n        description: Enable chat apps, collaborative tools, and live dashboards using WebSocket APIs for persistent bidirectional connections.\n      - name: Mobile and Web Application APIs\n        description: Create secure, scalable REST and HTTP APIs for mobile and web front-ends with Cognito authentication.\n      - name: Legacy API Modernization\n        description: Expose existing on-premises or EC2-hosted services as modern REST APIs without rewriting backend logic.\n      - name: Third-Party API Integration\n        description: Aggregate and normalize third-party APIs behind a consistent API surface\
  \ with transformation and mapping.\n  - type: Integrations\n    data:\n      - name: AWS Lambda\n        description: Invoke Lambda functions as API backends for fully serverless request handling.\n      - name: Amazon Cognito\n        description: Authenticate and authorize API requests using Cognito user pools and identity pools.\n      - name: Amazon CloudWatch\n        description: Monitor API performance metrics, error rates, and latency with CloudWatch dashboards and alarms.\n      - name: AWS CloudTrail\n        description: Audit all API Gateway management API calls for compliance and security monitoring.\n      - name: Amazon CloudFront\n        description: Distribute APIs globally through CloudFront edge locations for reduced latency.\n      - name: AWS WAF\n        description: Apply web application firewall rules to protect APIs from malicious traffic.\n      - name: AWS X-Ray\n        description: Trace requests end-to-end through API Gateway and backend services for performance\
  \ analysis.\n      - name: AWS IAM\n        description: Control API access using IAM policies and resource-based policies for fine-grained authorization.\n      - name: AWS Certificate Manager\n        description: Provision and manage TLS certificates for custom domain names on API Gateway.\n      - name: Amazon VPC\n        description: Create private APIs accessible only within a VPC using VPC endpoint integration.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/apis.yml
tags:
- API Gateway
- Cloud
- REST
- WebSocket
- Serverless
url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/apis.yml
use_cases:
- description: Build fully serverless APIs with API Gateway as the front door and AWS Lambda as the backend compute layer.
  name: Serverless API Backend
- description: Consolidate access to multiple microservices behind a single API endpoint with routing and load balancing.
  name: Microservices Gateway
- description: Enable chat apps, collaborative tools, and live dashboards using WebSocket APIs for persistent bidirectional connections.
  name: Real-Time Applications
- description: Create secure, scalable REST and HTTP APIs for mobile and web front-ends with Cognito authentication.
  name: Mobile and Web Application APIs
- description: Expose existing on-premises or EC2-hosted services as modern REST APIs without rewriting backend logic.
  name: Legacy API Modernization
- description: Aggregate and normalize third-party APIs behind a consistent API surface with transformation and mapping.
  name: Third-Party API Integration
---
