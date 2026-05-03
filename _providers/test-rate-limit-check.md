---
api_count: 6
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Kong Gateway Admin API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.konghq.com/gateway/latest/admin-api/
- filename: x-tyk-gateway.json
  format: json
  label: Tyk API Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/TykTechnologies/tyk/master/apidef/oas/schema/x-tyk-gateway.json
- filename: api-spec.json
  format: json
  label: Grafana API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/grafana/grafana/main/public/api-spec.json
apis:
- description: Admin REST API for Kong API Gateway, providing endpoints to configure rate limiting plugins, quotas, consumers, and traffic policies for API rate limit enforcement.
  name: Kong Gateway Admin API
  slug: ''
- description: AWS REST API for managing API Gateway usage plans, API keys, throttling limits, and quota enforcement across API deployments.
  name: AWS API Gateway API
  slug: ''
- description: REST API for Google Apigee API management platform supporting rate limit policy configuration, quota management, spike arrest, and traffic shaping for API testing.
  name: Apigee API
  slug: ''
- description: REST API for Azure API Management service supporting subscription quotas, rate limit policies, and throttling configuration for testing rate limit implementations.
  name: Azure API Management API
  slug: ''
- description: REST API for Tyk open-source API gateway supporting rate limiting, quota management, key expiry, and throttling policy configuration and testing.
  name: Tyk API Management API
  slug: ''
- description: REST API for Grafana observability platform, enabling rate limit test monitoring through dashboards, alerts, and metrics visualization for API traffic and throttling behavior.
  name: Grafana API
  slug: ''
common:
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Rate_limiting
- title: ''
  type: Documentation
  url: https://www.rfc-editor.org/rfc/rfc6585#section-4
- title: ''
  type: JSONSchema
  url: json-schema/test-rate-limit-check-rate-limit-config-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/test-rate-limit-check-rate-limit-response-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/test-rate-limit-check-quota-schema.json
- title: ''
  type: JSONLD
  url: json-ld/test-rate-limit-check-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/test-rate-limit-check-vocabulary.yml
created: '2026-05-03'
description: Testing and validation of API rate limiting implementations to ensure that APIs correctly enforce request quotas, return appropriate error responses, and recover gracefully when limits are exceeded. Rate limit testing verifies throttling behavior, retry-after headers, burst allowances, and quota reset mechanisms across different API consumers and usage tiers.
features:
- description: Verify that APIs return correct X-RateLimit-Limit, X-RateLimit-Remaining, and Retry-After headers.
  name: Rate Limit Header Validation
- description: Confirm that APIs return HTTP 429 Too Many Requests when rate limits are exceeded.
  name: 429 Response Testing
- description: Test that rate limit counters reset correctly after the defined window period.
  name: Quota Reset Verification
- description: Validate burst rate limits that allow short-term traffic spikes above baseline quotas.
  name: Burst Allowance Testing
- description: Test that rate limits are correctly scoped to individual API keys or consumers.
  name: Per-Consumer Rate Limiting
- description: Verify rate limiting behavior under concurrent parallel request loads.
  name: Concurrent Request Testing
image: ''
integrations:
- description: Use k6 load testing tool to generate traffic for rate limit validation and testing.
  name: k6
- description: Use JMeter to send concurrent requests and validate rate limit enforcement.
  name: Apache JMeter
- description: Use Postman test scripts to assert rate limit headers and 429 responses.
  name: Postman
- description: Monitor rate limit metrics with Prometheus for alerting and trend analysis.
  name: Prometheus
jsonld:
- class_count: 3
  name: Test Rate Limit Check Context
  property_count: 32
  slug: test-rate-limit-check-context
layout: provider
modified: '2026-05-03'
name: Test Rate Limit Check
skills: []
slug: test-rate-limit-check
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Test Rate Limit Check\ndescription: Testing and validation of API rate limiting implementations to ensure that APIs correctly enforce request quotas, return appropriate error responses, and recover gracefully when limits are exceeded. Rate limit testing verifies throttling behavior, retry-after headers, burst allowances, and quota reset mechanisms across different API consumers and usage tiers.\nurl: https://en.wikipedia.org/wiki/Rate_limiting\ntags:\n  - API Governance\n  - API Management\n  - API Testing\n  - Performance Testing\n  - Rate Limiting\n  - Testing\ncreated: '2026-05-03'\nmodified: '2026-05-03'\napis:\n  - name: Kong Gateway Admin API\n    description: Admin REST API for Kong API Gateway, providing endpoints to configure rate limiting plugins, quotas, consumers, and traffic policies for API rate limit enforcement.\n    humanURL: https://docs.konghq.com/gateway/latest/admin-api/\n    baseURL: https://your-kong.example.com:8001\n    tags:\n      - API Gateway\n\
  \      - API Management\n      - Rate Limiting\n      - Traffic Control\n    properties:\n      - type: Documentation\n        url: https://docs.konghq.com/gateway/latest/admin-api/\n      - type: OpenAPI\n        url: https://docs.konghq.com/gateway/latest/admin-api/\n  - name: AWS API Gateway API\n    description: AWS REST API for managing API Gateway usage plans, API keys, throttling limits, and quota enforcement across API deployments.\n    humanURL: https://docs.aws.amazon.com/apigateway/latest/developerguide/api-ref.html\n    baseURL: https://apigateway.amazonaws.com\n    tags:\n      - AWS\n      - API Gateway\n      - Cloud\n      - Rate Limiting\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/apigateway/latest/developerguide/api-ref.html\n  - name: Apigee API\n    description: REST API for Google Apigee API management platform supporting rate limit policy configuration, quota management, spike arrest, and traffic shaping for API testing.\n\
  \    humanURL: https://cloud.google.com/apigee/docs/reference/apis/apigee/rest\n    baseURL: https://apigee.googleapis.com/v1\n    tags:\n      - API Management\n      - Google Cloud\n      - Quotas\n      - Rate Limiting\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/apigee/docs/reference/apis/apigee/rest\n  - name: Azure API Management API\n    description: REST API for Azure API Management service supporting subscription quotas, rate limit policies, and throttling configuration for testing rate limit implementations.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/apimanagement/\n    baseURL: https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}\n    tags:\n      - API Management\n      - Azure\n      - Microsoft\n      - Rate Limiting\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/apimanagement/\n\
  \  - name: Tyk API Management API\n    description: REST API for Tyk open-source API gateway supporting rate limiting, quota management, key expiry, and throttling policy configuration and testing.\n    humanURL: https://tyk.io/docs/tyk-gateway-api/\n    baseURL: https://your-tyk.example.com/api\n    tags:\n      - API Gateway\n      - API Management\n      - Open Source\n      - Rate Limiting\n    properties:\n      - type: Documentation\n        url: https://tyk.io/docs/tyk-gateway-api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/TykTechnologies/tyk/master/apidef/oas/schema/x-tyk-gateway.json\n  - name: Grafana API\n    description: REST API for Grafana observability platform, enabling rate limit test monitoring through dashboards, alerts, and metrics visualization for API traffic and throttling behavior.\n    humanURL: https://grafana.com/docs/grafana/latest/developers/http_api/\n    baseURL: https://your-grafana.example.com/api\n    tags:\n      - Dashboards\n\
  \      - Metrics\n      - Monitoring\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://grafana.com/docs/grafana/latest/developers/http_api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/grafana/grafana/main/public/api-spec.json\ncommon:\n  - type: Documentation\n    url: https://en.wikipedia.org/wiki/Rate_limiting\n  - type: Documentation\n    url: https://www.rfc-editor.org/rfc/rfc6585#section-4\n  - type: Features\n    data:\n      - name: Rate Limit Header Validation\n        description: Verify that APIs return correct X-RateLimit-Limit, X-RateLimit-Remaining, and Retry-After headers.\n      - name: 429 Response Testing\n        description: Confirm that APIs return HTTP 429 Too Many Requests when rate limits are exceeded.\n      - name: Quota Reset Verification\n        description: Test that rate limit counters reset correctly after the defined window period.\n      - name: Burst Allowance Testing\n        description:\
  \ Validate burst rate limits that allow short-term traffic spikes above baseline quotas.\n      - name: Per-Consumer Rate Limiting\n        description: Test that rate limits are correctly scoped to individual API keys or consumers.\n      - name: Concurrent Request Testing\n        description: Verify rate limiting behavior under concurrent parallel request loads.\n  - type: UseCases\n    data:\n      - name: API Gateway Rate Limit Validation\n        description: Verify that API gateway rate limiting plugins correctly enforce configured quotas.\n      - name: Throttling Behavior Testing\n        description: Test that API clients receive appropriate throttling signals and can implement retry logic.\n      - name: Usage Tier Enforcement\n        description: Validate that different subscription tiers enforce their respective rate limits correctly.\n      - name: Rate Limit Recovery Testing\n        description: Confirm that APIs correctly recover and allow traffic after rate limit windows\
  \ reset.\n      - name: Load Test Rate Limit Interaction\n        description: Understand how rate limits interact with load testing to avoid false failures.\n  - type: Integrations\n    data:\n      - name: k6\n        description: Use k6 load testing tool to generate traffic for rate limit validation and testing.\n      - name: Apache JMeter\n        description: Use JMeter to send concurrent requests and validate rate limit enforcement.\n      - name: Postman\n        description: Use Postman test scripts to assert rate limit headers and 429 responses.\n      - name: Prometheus\n        description: Monitor rate limit metrics with Prometheus for alerting and trend analysis.\n  - type: JSONSchema\n    url: json-schema/test-rate-limit-check-rate-limit-config-schema.json\n  - type: JSONSchema\n    url: json-schema/test-rate-limit-check-rate-limit-response-schema.json\n  - type: JSONSchema\n    url: json-schema/test-rate-limit-check-quota-schema.json\n  - type: JSONLD\n    url: json-ld/test-rate-limit-check-context.jsonld\n\
  \  - type: Vocabulary\n    url: vocabulary/test-rate-limit-check-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/test-rate-limit-check/refs/heads/main/apis.yml
tags:
- API Governance
- API Management
- API Testing
- Performance Testing
- Rate Limiting
- Testing
url: https://en.wikipedia.org/wiki/Rate_limiting
use_cases:
- description: Verify that API gateway rate limiting plugins correctly enforce configured quotas.
  name: API Gateway Rate Limit Validation
- description: Test that API clients receive appropriate throttling signals and can implement retry logic.
  name: Throttling Behavior Testing
- description: Validate that different subscription tiers enforce their respective rate limits correctly.
  name: Usage Tier Enforcement
- description: Confirm that APIs correctly recover and allow traffic after rate limit windows reset.
  name: Rate Limit Recovery Testing
- description: Understand how rate limits interact with load testing to avoid false failures.
  name: Load Test Rate Limit Interaction
---
