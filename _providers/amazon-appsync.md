---
api_count: 1
apis:
- description: REST management API for Amazon AppSync covering GraphQL APIs, data sources, resolvers, functions, types, schema, API keys, and custom domain names.
  name: Amazon AppSync API
  slug: amazon-appsync-api
capabilities:
- description: Workflow capability for building and managing GraphQL APIs with AppSync including data sources, resolvers, and schema management.
  name: GraphQL Api Management Workflow
  slug: graphql-api-management
common: []
created: '2024-01-15'
description: Amazon AppSync creates serverless GraphQL and Pub/Sub APIs that simplify application development through a single endpoint to securely query, update, or publish data.
features:
- Managed GraphQL API hosting with automatic scaling
- Multiple authentication modes including API key, IAM, Cognito, and Lambda
- Real-time subscriptions via WebSocket connections
- Pipeline resolvers for composing multi-step data access patterns
- Direct Lambda resolvers with APPSYNC_JS runtime support
- Built-in caching for improved performance
- Conflict detection and resolution for offline sync use cases
- Custom domain names with ACM certificate integration
- X-Ray tracing and CloudWatch logging integration
- Merged APIs for combining multiple GraphQL APIs
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- Amazon DynamoDB
- AWS Lambda
- Amazon OpenSearch Service
- Amazon RDS
- Amazon EventBridge
- Amazon Cognito
- AWS IAM
- AWS WAF
- Amazon CloudWatch
- AWS X-Ray
- AWS Certificate Manager
- Amazon Route 53
jsonld:
- class_count: 73
  name: Amazon Appsync Context
  property_count: 0
  slug: amazon-appsync-context
layout: provider
modified: '2026-04-19'
name: Amazon AppSync
rules:
- name: Amazon AppSync API Rules
  rule_count: 20
  severity_counts:
    error: 13
    hint: 0
    info: 2
    warn: 5
  slug: amazon-appsync-spectral-rules
skills: []
slug: amazon-appsync
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-appsync\nname: Amazon AppSync\ndescription: >-\n  Amazon AppSync creates serverless GraphQL and Pub/Sub APIs that simplify application development through a single endpoint to securely query, update, or publish data.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Amazon AppSync\n  - GraphQL\n  - API Management\n  - Serverless\n  - AWS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-appsync:amazon-appsync-api\n    name: Amazon AppSync API\n    description: >-\n      REST management API for Amazon AppSync covering GraphQL APIs, data sources, resolvers, functions, types, schema, API keys, and custom domain names.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.aws.amazon.com/appsync/latest/APIReference/Welcome.html\n\
  \    baseURL: https://appsync.us-east-1.amazonaws.com\n    tags:\n      - Amazon AppSync\n      - GraphQL\n      - API Management\n      - Serverless\n      - AWS\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/openapi/amazon-appsync-openapi.yml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/rules/amazon-appsync-spectral-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/capabilities/shared/appsync-api.yaml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/capabilities/graphql-api-management.yaml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/vocabulary/amazon-appsync-vocabulary.yaml\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/json-schema/appsync-graphql-api-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/json-schema/appsync-data-source-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/json-schema/appsync-resolver-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/json-structure/appsync-graphql-api-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/json-structure/appsync-resolver-structure.json\n      - type: JSONLD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/json-ld/amazon-appsync-context.jsonld\n\
  \      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/examples/appsync-graphql-api-example.json\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/examples/appsync-resolver-example.json\ncommon:\n  - type: Features\n    data:\n      - Managed GraphQL API hosting with automatic scaling\n      - Multiple authentication modes including API key, IAM, Cognito, and Lambda\n      - Real-time subscriptions via WebSocket connections\n      - Pipeline resolvers for composing multi-step data access patterns\n      - Direct Lambda resolvers with APPSYNC_JS runtime support\n      - Built-in caching for improved performance\n      - Conflict detection and resolution for offline sync use cases\n      - Custom domain names with ACM certificate integration\n      - X-Ray tracing and CloudWatch logging integration\n      - Merged APIs for combining\
  \ multiple GraphQL APIs\n  - type: UseCases\n    data:\n      - Build mobile and web applications with a unified GraphQL data layer\n      - Implement real-time features like live notifications and chat with subscriptions\n      - Create a unified data access layer across multiple microservices\n      - Build offline-capable mobile apps with automatic conflict resolution\n      - Expose DynamoDB tables, Lambda functions, and OpenSearch as GraphQL APIs\n      - Implement federated GraphQL across multiple teams with Merged APIs\n  - type: Integrations\n    data:\n      - Amazon DynamoDB\n      - AWS Lambda\n      - Amazon OpenSearch Service\n      - Amazon RDS\n      - Amazon EventBridge\n      - Amazon Cognito\n      - AWS IAM\n      - AWS WAF\n      - Amazon CloudWatch\n      - AWS X-Ray\n      - AWS Certificate Manager\n      - Amazon Route 53\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/apis.yml
tags:
- Amazon AppSync
- GraphQL
- API Management
- Serverless
- AWS
url: https://raw.githubusercontent.com/api-evangelist/amazon-appsync/refs/heads/main/apis.yml
use_cases:
- Build mobile and web applications with a unified GraphQL data layer
- Implement real-time features like live notifications and chat with subscriptions
- Create a unified data access layer across multiple microservices
- Build offline-capable mobile apps with automatic conflict resolution
- Expose DynamoDB tables, Lambda functions, and OpenSearch as GraphQL APIs
- Implement federated GraphQL across multiple teams with Merged APIs
---
