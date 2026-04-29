---
api_count: 9
api_specs:
- filename: amazon-neptune-management-openapi.yml
  format: yaml
  label: Amazon Neptune Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-management-openapi.yml
- filename: amazon-neptune-data-openapi.yml
  format: yaml
  label: Amazon Neptune Data API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-data-openapi.yml
- filename: amazon-neptune-gremlin-openapi.yml
  format: yaml
  label: Neptune Gremlin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-gremlin-openapi.yml
- filename: amazon-neptune-sparql-openapi.yml
  format: yaml
  label: Neptune SPARQL API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-sparql-openapi.yml
- filename: amazon-neptune-opencypher-openapi.yml
  format: yaml
  label: Neptune openCypher API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-opencypher-openapi.yml
- filename: amazon-neptune-streams-openapi.yml
  format: yaml
  label: Neptune Streams API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-streams-openapi.yml
- filename: amazon-neptune-loader-openapi.yml
  format: yaml
  label: Neptune Loader API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-loader-openapi.yml
- filename: amazon-neptune-ml-openapi.yml
  format: yaml
  label: Neptune ML API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-ml-openapi.yml
- filename: amazon-neptune-analytics-openapi.yml
  format: yaml
  label: Neptune Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-analytics-openapi.yml
apis:
- description: Amazon Neptune Management API for creating, managing, and deleting Neptune DB clusters, instances, parameter groups, snapshots, and related infrastructure resources.
  name: Amazon Neptune Management API
  slug: ''
- description: Amazon Neptune Data API provides SDK support for more than 40 data operations including data loading, query execution, data inquiry, and machine learning. It supports Gremlin and openCypher query lang
  name: Amazon Neptune Data API
  slug: ''
- description: Apache TinkerPop Gremlin graph traversal language API for querying property graphs in Neptune. It supports both WebSocket and HTTP REST endpoints for submitting Gremlin traversals.
  name: Neptune Gremlin API
  slug: ''
- description: W3C SPARQL 1.1 query language API for querying RDF graphs in Neptune. It provides an HTTP REST endpoint compatible with the SPARQL 1.1 protocol specification.
  name: Neptune SPARQL API
  slug: ''
- description: openCypher graph query language API for querying property graphs with Cypher syntax in Neptune. It provides an HTTP endpoint for executing openCypher queries against property graph data.
  name: Neptune openCypher API
  slug: ''
- description: Neptune Streams generates a complete sequence of change-log entries that record every change made to graph data as it happens, enabling real-time capture of graph mutations via a REST API.
  name: Neptune Streams API
  slug: ''
- description: Neptune bulk loader API for ingesting large volumes of data from Amazon S3 into a Neptune DB instance. It supports CSV formats for property graphs and multiple RDF serialization formats.
  name: Neptune Loader API
  slug: ''
- description: Neptune ML enables machine learning on graph data using graph neural networks. It provides APIs for data processing, model training, and inference endpoint management powered by Amazon SageMaker.
  name: Neptune ML API
  slug: ''
- description: Neptune Analytics is a memory-optimized graph database engine for analytics, providing optimized graph analytic algorithms, low-latency queries, and vector search capabilities within graph traversals.
  name: Neptune Analytics API
  slug: ''
capabilities:
- description: Workflow capability for Neptune Analytics graph analysis, vector search, and Neptune ML graph neural network model training and inference. Used by data scientists and ML engineers.
  name: Amazon Neptune Analytics and Machine Learning
  slug: neptune-analytics-ml
- description: Workflow capability for managing Neptune graph databases, executing queries across Gremlin, SPARQL, and openCypher, and monitoring data streams. Used by graph database administrators and developers.
  name: Amazon Neptune Graph Data Management
  slug: neptune-graph-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/neptune/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/neptune/
- title: ''
  type: Getting Started
  url: https://aws.amazon.com/neptune/getting-started/
- title: ''
  type: Authentication
  url: https://docs.aws.amazon.com/neptune/latest/userguide/iam-auth.html
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/database/category/database/amazon-neptune/
- title: ''
  type: Change Log
  url: https://docs.aws.amazon.com/neptune/latest/userguide/doc-history.html
- title: ''
  type: Release Notes
  url: https://docs.aws.amazon.com/neptune/latest/userguide/engine-releases.html
- title: ''
  type: Status
  url: https://health.aws.amazon.com/
- title: ''
  type: Support
  url: https://repost.aws/tags/TAxVAEdWg1SrS0lClUSX-m_Q
- title: ''
  type: Terms of Service
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: Privacy Policy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: GitHub Organization
  url: https://github.com/aws
- title: ''
  type: Community
  url: https://repost.aws/
- title: ''
  type: Website
  url: https://aws.amazon.com/neptune/
- title: ''
  type: Login
  url: https://console.aws.amazon.com/neptune/
- title: ''
  type: Sign Up
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: FAQs
  url: https://aws.amazon.com/neptune/faqs/
- title: ''
  type: Security
  url: https://docs.aws.amazon.com/neptune/latest/userguide/security.html
- title: ''
  type: Service Level Agreement
  url: https://aws.amazon.com/neptune/sla/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/neptune/
- title: ''
  type: GitHub Samples
  url: https://github.com/aws-samples/amazon-neptune-samples
- title: ''
  type: SDKs
  url: https://docs.aws.amazon.com/neptune/latest/userguide/using-neptune-apis.html
- title: ''
  type: Tools
  url: https://github.com/awslabs/amazon-neptune-tools
- title: ''
  type: Pricing
  url: https://aws.amazon.com/neptune/pricing/
- title: ''
  type: JSON-LD
  url: json-ld/amazon-neptune-context.jsonld
- title: DB Cluster Schema
  type: JSONSchema
  url: json-schema/amazon-neptune-db-cluster-schema.json
- title: DB Instance Schema
  type: JSONSchema
  url: json-schema/amazon-neptune-db-instance-schema.json
- title: Graph Element Schema
  type: JSONSchema
  url: json-schema/amazon-neptune-graph-element-schema.json
- title: Loader Job Schema
  type: JSONSchema
  url: json-schema/amazon-neptune-loader-job-schema.json
- title: Stream Record Schema
  type: JSONSchema
  url: json-schema/amazon-neptune-stream-record-schema.json
- title: Analytics Graph Schema
  type: JSONSchema
  url: json-schema/amazon-neptune-analytics-graph-schema.json
- title: ML Job Schema
  type: JSONSchema
  url: json-schema/amazon-neptune-ml-job-schema.json
- title: ''
  type: SpectralRules
  url: rules/amazon-neptune-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-neptune-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/neptune-graph-management.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/neptune-analytics-ml.yaml
- title: Analytics Context
  type: JSON-LD
  url: json-ld/amazon-neptune-analytics-context.jsonld
- title: Data Context
  type: JSON-LD
  url: json-ld/amazon-neptune-data-context.jsonld
- title: Gremlin Context
  type: JSON-LD
  url: json-ld/amazon-neptune-gremlin-context.jsonld
- title: Loader Context
  type: JSON-LD
  url: json-ld/amazon-neptune-loader-context.jsonld
- title: Management Context
  type: JSON-LD
  url: json-ld/amazon-neptune-management-context.jsonld
- title: Ml Context
  type: JSON-LD
  url: json-ld/amazon-neptune-ml-context.jsonld
- title: Opencypher Context
  type: JSON-LD
  url: json-ld/amazon-neptune-opencypher-context.jsonld
- title: Sparql Context
  type: JSON-LD
  url: json-ld/amazon-neptune-sparql-context.jsonld
- title: Streams Context
  type: JSON-LD
  url: json-ld/amazon-neptune-streams-context.jsonld
created: '2024'
description: Amazon Neptune is a fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets. It supports property graph and RDF models, with multiple query languages including Gremlin, SPARQL, and openCypher.
features:
- description: Automatically scales compute and memory resources based on workload demands without requiring capacity planning.
  name: Serverless Graph Database
- description: Supports Apache TinkerPop Gremlin, openCypher, and SPARQL 1.1 query languages for property graph and RDF models.
  name: Multiple Query Language Support
- description: Multi-AZ deployment with up to 15 read replicas, automated failover, and continuous backups with point-in-time recovery up to 35 days.
  name: High Availability
- description: Multi-region replication with sub-second latency across up to five secondary clusters for global applications.
  name: Global Database
- description: Memory-optimized graph analytics engine for analyzing tens of billions of relationships within seconds with vector search capabilities.
  name: Neptune Analytics
- description: Fully managed GraphRAG with Amazon Bedrock Knowledge Bases for AI-enhanced graph retrieval augmented generation.
  name: GraphRAG Support
- description: Native graph neural network support via Neptune ML powered by Amazon SageMaker for link prediction and node classification.
  name: Machine Learning on Graphs
- description: Full ACID transaction support ensuring data consistency and integrity across graph operations.
  name: ACID Transactions
- description: VPC network isolation, IAM resource permissions, AWS KMS encryption, TLS in-transit encryption, and CloudWatch audit logging.
  name: AWS Security Integration
- description: Storage automatically grows up to 128 TiB with self-healing architecture spanning three availability zones.
  name: Auto-Expanding Storage
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Integration with Bedrock Knowledge Bases for fully managed GraphRAG and AI-enhanced knowledge graph applications.
  name: Amazon Bedrock
- description: Neptune ML uses SageMaker for training graph neural network models on Neptune graph data.
  name: Amazon SageMaker
- description: Bulk data loading from S3 using the Neptune Loader API with CSV and RDF serialization format support.
  name: Amazon S3
- description: Fine-grained resource-level access control and role-based permissions via AWS Identity and Access Management.
  name: AWS IAM
- description: Metrics, logs, and audit logging for monitoring Neptune cluster performance and compliance.
  name: Amazon CloudWatch
- description: Encryption at rest using AWS Key Management Service for customer-managed key support.
  name: AWS KMS
- description: Network isolation using Amazon Virtual Private Cloud with security group and firewall controls.
  name: Amazon VPC
- description: Gremlin graph traversal language and TinkerPop ecosystem integration for property graph querying.
  name: Apache TinkerPop
- description: Integration with Strands AI Agents SDK and popular agentic memory tools for AI agent applications.
  name: Strands AI Agents SDK
jsonld:
- class_count: 13
  name: Amazon Neptune Analytics Context
  property_count: 44
  slug: amazon-neptune-analytics-context
- class_count: 10
  name: Amazon Neptune Context
  property_count: 15
  slug: amazon-neptune-context
- class_count: 26
  name: Amazon Neptune Data Context
  property_count: 120
  slug: amazon-neptune-data-context
- class_count: 5
  name: Amazon Neptune Gremlin Context
  property_count: 20
  slug: amazon-neptune-gremlin-context
- class_count: 5
  name: Amazon Neptune Loader Context
  property_count: 21
  slug: amazon-neptune-loader-context
- class_count: 14
  name: Amazon Neptune Management Context
  property_count: 56
  slug: amazon-neptune-management-context
- class_count: 10
  name: Amazon Neptune Ml Context
  property_count: 50
  slug: amazon-neptune-ml-context
- class_count: 7
  name: Amazon Neptune Opencypher Context
  property_count: 21
  slug: amazon-neptune-opencypher-context
- class_count: 5
  name: Amazon Neptune Sparql Context
  property_count: 22
  slug: amazon-neptune-sparql-context
- class_count: 6
  name: Amazon Neptune Streams Context
  property_count: 20
  slug: amazon-neptune-streams-context
layout: provider
modified: '2026-04-19'
name: Amazon Neptune
rules:
- name: Amazon Neptune API Rules
  rule_count: 25
  severity_counts:
    error: 11
    hint: 0
    info: 3
    warn: 11
  slug: amazon-neptune-spectral-rules
skills: []
slug: amazon-neptune
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon Neptune\ndescription: >-\n  Amazon Neptune is a fast, reliable, fully managed graph database service\n  that makes it easy to build and run applications that work with highly\n  connected datasets. It supports property graph and RDF models, with\n  multiple query languages including Gremlin, SPARQL, and openCypher.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\ntags:\n- AWS\n- Database\n- Graph Database\n- Gremlin\n- Neptune\n- Property Graph\n- RDF\n- SPARQL\ncreated: '2024'\nmodified: '2026-04-19'\nspecificationVersion: '0.18'\napis:\n- name: Amazon Neptune Management API\n  description: >-\n    Amazon Neptune Management API for creating, managing, and deleting Neptune\n    DB clusters, instances, parameter groups, snapshots, and related\n    infrastructure resources.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanUrl: https://aws.amazon.com/neptune/\n  baseUrl: https://rds.{region}.amazonaws.com\n\
  \  tags:\n  - AWS\n  - Cluster Management\n  - Database Management\n  - Graph Database\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/intro.html\n  - type: OpenAPI\n    url: openapi/amazon-neptune-management-openapi.yml\n  - type: API Reference\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/api.html\n  - type: Pricing\n    url: https://aws.amazon.com/neptune/pricing/\n  - type: Getting Started\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/get-started.html\n  - type: SDKs\n    url: https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune.html\n- name: Amazon Neptune Data API\n  description: >-\n    Amazon Neptune Data API provides SDK support for more than 40 data\n    operations including data loading, query execution, data inquiry, and\n    machine learning. It supports Gremlin and openCypher query languages.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n\
  \  humanUrl: https://docs.aws.amazon.com/neptune/latest/userguide/data-api.html\n  baseUrl: https://neptune-db.{region}.amazonaws.com\n  tags:\n  - Data API\n  - Data Operations\n  - Graph Query\n  - SDK\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/data-api.html\n  - type: OpenAPI\n    url: openapi/amazon-neptune-data-openapi.yml\n  - type: API Reference\n    url: https://docs.aws.amazon.com/neptune/latest/data-api/Welcome.html\n  - type: SDKs\n    url: https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptunedata.html\n  - type: CLI Reference\n    url: https://docs.aws.amazon.com/cli/latest/reference/neptunedata/\n  - type: JavaScript SDK\n    url: https://docs.aws.amazon.com/AWSJavaScriptSDK/v3/latest/client/neptunedata/\n  - type: Go SDK\n    url: https://docs.aws.amazon.com/sdk-for-go/api/service/neptunedata/\n- name: Neptune Gremlin API\n  description: >-\n    Apache TinkerPop Gremlin graph traversal\
  \ language API for querying\n    property graphs in Neptune. It supports both WebSocket and HTTP REST\n    endpoints for submitting Gremlin traversals.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanUrl: https://docs.aws.amazon.com/neptune/latest/userguide/access-graph-gremlin.html\n  baseUrl: wss://{cluster-endpoint}:8182/gremlin\n  tags:\n  - Graph Traversal\n  - Gremlin\n  - Property Graph\n  - Query Language\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/access-graph-gremlin.html\n  - type: OpenAPI\n    url: openapi/amazon-neptune-gremlin-openapi.yml\n  - type: Reference\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/gremlin-api-reference.html\n  - type: Gremlin Reference\n    url: https://tinkerpop.apache.org/docs/current/reference/\n  - type: Best Practices\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/best-practices-gremlin.html\n  - type: REST\
  \ Endpoint\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/access-graph-gremlin-rest.html\n- name: Neptune SPARQL API\n  description: >-\n    W3C SPARQL 1.1 query language API for querying RDF graphs in Neptune.\n    It provides an HTTP REST endpoint compatible with the SPARQL 1.1\n    protocol specification.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanUrl: https://docs.aws.amazon.com/neptune/latest/userguide/access-graph-sparql.html\n  baseUrl: https://{cluster-endpoint}:8182/sparql\n  tags:\n  - Query Language\n  - RDF\n  - Semantic Web\n  - SPARQL\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/access-graph-sparql.html\n  - type: OpenAPI\n    url: openapi/amazon-neptune-sparql-openapi.yml\n  - type: SPARQL Reference\n    url: https://www.w3.org/TR/sparql11-query/\n  - type: Best Practices\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/best-practices-sparql.html\n\
  \  - type: REST Endpoint\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/access-graph-sparql-http-rest.html\n- name: Neptune openCypher API\n  description: >-\n    openCypher graph query language API for querying property graphs with\n    Cypher syntax in Neptune. It provides an HTTP endpoint for executing\n    openCypher queries against property graph data.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanUrl: https://docs.aws.amazon.com/neptune/latest/userguide/access-graph-opencypher.html\n  baseUrl: https://{cluster-endpoint}:8182/openCypher\n  tags:\n  - Cypher\n  - openCypher\n  - Property Graph\n  - Query Language\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/access-graph-opencypher.html\n  - type: OpenAPI\n    url: openapi/amazon-neptune-opencypher-openapi.yml\n  - type: openCypher Reference\n    url: https://opencypher.org/\n  - type: Best Practices\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/best-practices-opencypher.html\n\
  - name: Neptune Streams API\n  description: >-\n    Neptune Streams generates a complete sequence of change-log entries that\n    record every change made to graph data as it happens, enabling real-time\n    capture of graph mutations via a REST API.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanUrl: https://docs.aws.amazon.com/neptune/latest/userguide/streams.html\n  baseUrl: https://{cluster-endpoint}:8182\n  tags:\n  - Change Data Capture\n  - Event Log\n  - Real-Time\n  - Streams\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/streams.html\n  - type: OpenAPI\n    url: openapi/amazon-neptune-streams-openapi.yml\n  - type: API Reference\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/streams-using-api-call.html\n  - type: Response Format\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/streams-using-api-reponse.html\n  - type: Data API Reference\n    url:\
  \ https://docs.aws.amazon.com/neptune/latest/userguide/data-api-dp-streams.html\n- name: Neptune Loader API\n  description: >-\n    Neptune bulk loader API for ingesting large volumes of data from Amazon\n    S3 into a Neptune DB instance. It supports CSV formats for property\n    graphs and multiple RDF serialization formats.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanUrl: https://docs.aws.amazon.com/neptune/latest/userguide/bulk-load.html\n  baseUrl: https://{cluster-endpoint}:8182/loader\n  tags:\n  - Bulk Import\n  - Data Ingestion\n  - Data Loading\n  - ETL\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/bulk-load.html\n  - type: OpenAPI\n    url: openapi/amazon-neptune-loader-openapi.yml\n  - type: API Reference\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/load-api-reference.html\n  - type: Loader Command\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/load-api-reference-load.html\n\
  \  - type: Data Formats\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/bulk-load-tutorial-format.html\n  - type: Data API Reference\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/data-api-dp-loader.html\n- name: Neptune ML API\n  description: >-\n    Neptune ML enables machine learning on graph data using graph neural\n    networks. It provides APIs for data processing, model training, and\n    inference endpoint management powered by Amazon SageMaker.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanUrl: https://aws.amazon.com/neptune/machine-learning/\n  baseUrl: https://{cluster-endpoint}:8182/ml\n  tags:\n  - Graph Neural Network\n  - Machine Learning\n  - Predictions\n  - SageMaker\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/machine-learning.html\n  - type: OpenAPI\n    url: openapi/amazon-neptune-ml-openapi.yml\n  - type: API Reference\n    url:\
  \ https://docs.aws.amazon.com/neptune/latest/userguide/machine-learning-api-reference.html\n  - type: Model Training\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/data-api-dp-ml-training.html\n  - type: Getting Started\n    url: https://docs.aws.amazon.com/neptune/latest/userguide/machine-learning-overview.html\n- name: Neptune Analytics API\n  description: >-\n    Neptune Analytics is a memory-optimized graph database engine for\n    analytics, providing optimized graph analytic algorithms, low-latency\n    queries, and vector search capabilities within graph traversals.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanUrl: https://docs.aws.amazon.com/neptune-analytics/latest/userguide/what-is-neptune-analytics.html\n  baseUrl: https://neptune-graph.{region}.amazonaws.com\n  tags:\n  - Analytics\n  - Graph Analytics\n  - In-Memory\n  - Vector Search\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/neptune-analytics/latest/userguide/what-is-neptune-analytics.html\n\
  \  - type: OpenAPI\n    url: openapi/amazon-neptune-analytics-openapi.yml\n  - type: API Reference\n    url: https://docs.aws.amazon.com/neptune-analytics/latest/apiref/Welcome.html\n  - type: SDKs\n    url: https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/neptune-graph.html\n  - type: Getting Started\n    url: https://docs.aws.amazon.com/neptune-analytics/latest/userguide/gettingStarted-accessing.html\nmaintainers:\n- name: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/neptune/\n- type: Documentation\n  url: https://docs.aws.amazon.com/neptune/\n- type: Getting Started\n  url: https://aws.amazon.com/neptune/getting-started/\n- type: Authentication\n  url: https://docs.aws.amazon.com/neptune/latest/userguide/iam-auth.html\n- type: Blog\n  url: https://aws.amazon.com/blogs/database/category/database/amazon-neptune/\n- type: Change Log\n  url: https://docs.aws.amazon.com/neptune/latest/userguide/doc-history.html\n\
  - type: Release Notes\n  url: https://docs.aws.amazon.com/neptune/latest/userguide/engine-releases.html\n- type: Status\n  url: https://health.aws.amazon.com/\n- type: Support\n  url: https://repost.aws/tags/TAxVAEdWg1SrS0lClUSX-m_Q\n- type: Terms of Service\n  url: https://aws.amazon.com/service-terms/\n- type: Privacy Policy\n  url: https://aws.amazon.com/privacy/\n- type: GitHub Organization\n  url: https://github.com/aws\n- type: Community\n  url: https://repost.aws/\n- type: Website\n  url: https://aws.amazon.com/neptune/\n- type: Login\n  url: https://console.aws.amazon.com/neptune/\n- type: Sign Up\n  url: https://portal.aws.amazon.com/billing/signup\n- type: FAQs\n  url: https://aws.amazon.com/neptune/faqs/\n- type: Features\n  url: https://aws.amazon.com/neptune/features/\n- type: Security\n  url: https://docs.aws.amazon.com/neptune/latest/userguide/security.html\n- type: Service Level Agreement\n  url: https://aws.amazon.com/neptune/sla/\n- type: Console\n  url: https://console.aws.amazon.com/neptune/\n\
  - type: GitHub Samples\n  url: https://github.com/aws-samples/amazon-neptune-samples\n- type: SDKs\n  url: https://docs.aws.amazon.com/neptune/latest/userguide/using-neptune-apis.html\n- type: Tools\n  url: https://github.com/awslabs/amazon-neptune-tools\n- type: Pricing\n  url: https://aws.amazon.com/neptune/pricing/\n- type: JSON-LD\n  url: json-ld/amazon-neptune-context.jsonld\n- type: JSONSchema\n  url: json-schema/amazon-neptune-db-cluster-schema.json\n  title: DB Cluster Schema\n- type: JSONSchema\n  url: json-schema/amazon-neptune-db-instance-schema.json\n  title: DB Instance Schema\n- type: JSONSchema\n  url: json-schema/amazon-neptune-graph-element-schema.json\n  title: Graph Element Schema\n- type: JSONSchema\n  url: json-schema/amazon-neptune-loader-job-schema.json\n  title: Loader Job Schema\n- type: JSONSchema\n  url: json-schema/amazon-neptune-stream-record-schema.json\n  title: Stream Record Schema\n- type: JSONSchema\n  url: json-schema/amazon-neptune-analytics-graph-schema.json\n\
  \  title: Analytics Graph Schema\n- type: JSONSchema\n  url: json-schema/amazon-neptune-ml-job-schema.json\n  title: ML Job Schema\n- type: Features\n  data:\n  - name: Serverless Graph Database\n    description: Automatically scales compute and memory resources based on workload demands without requiring capacity planning.\n  - name: Multiple Query Language Support\n    description: Supports Apache TinkerPop Gremlin, openCypher, and SPARQL 1.1 query languages for property graph and RDF models.\n  - name: High Availability\n    description: Multi-AZ deployment with up to 15 read replicas, automated failover, and continuous backups with point-in-time recovery up to 35 days.\n  - name: Global Database\n    description: Multi-region replication with sub-second latency across up to five secondary clusters for global applications.\n  - name: Neptune Analytics\n    description: Memory-optimized graph analytics engine for analyzing tens of billions of relationships within seconds with vector\
  \ search capabilities.\n  - name: GraphRAG Support\n    description: Fully managed GraphRAG with Amazon Bedrock Knowledge Bases for AI-enhanced graph retrieval augmented generation.\n  - name: Machine Learning on Graphs\n    description: Native graph neural network support via Neptune ML powered by Amazon SageMaker for link prediction and node classification.\n  - name: ACID Transactions\n    description: Full ACID transaction support ensuring data consistency and integrity across graph operations.\n  - name: AWS Security Integration\n    description: VPC network isolation, IAM resource permissions, AWS KMS encryption, TLS in-transit encryption, and CloudWatch audit logging.\n  - name: Auto-Expanding Storage\n    description: Storage automatically grows up to 128 TiB with self-healing architecture spanning three availability zones.\n- type: UseCases\n  data:\n  - name: Knowledge Graphs and GraphRAG\n    description: Build knowledge graphs to enhance AI accuracy, comprehensiveness, and\
  \ explainability using GraphRAG with Amazon Bedrock.\n  - name: Fraud Detection\n    description: Model transaction and account relationship networks to detect fraudulent patterns in near real-time using graph traversals.\n  - name: Customer 360\n    description: Build unified customer profile graphs linking purchases, preferences, and interactions for personalization and marketing.\n  - name: Cybersecurity and Threat Detection\n    description: Model IT infrastructure as a connected graph to detect attack paths, anomalies, and proactive threats.\n  - name: Recommendation Engines\n    description: Power product and content recommendation engines by traversing user-item relationship graphs.\n  - name: Social Networks\n    description: Model and query highly connected social graph data for applications requiring relationship traversal at scale.\n  - name: Network and IT Operations\n    description: Map network topology, dependencies, and configuration relationships for operations and impact\
  \ analysis.\n  - name: Supply Chain Management\n    description: Model complex supply chain relationships and dependencies for optimization and risk analysis.\n- type: Integrations\n  data:\n  - name: Amazon Bedrock\n    description: Integration with Bedrock Knowledge Bases for fully managed GraphRAG and AI-enhanced knowledge graph applications.\n  - name: Amazon SageMaker\n    description: Neptune ML uses SageMaker for training graph neural network models on Neptune graph data.\n  - name: Amazon S3\n    description: Bulk data loading from S3 using the Neptune Loader API with CSV and RDF serialization format support.\n  - name: AWS IAM\n    description: Fine-grained resource-level access control and role-based permissions via AWS Identity and Access Management.\n  - name: Amazon CloudWatch\n    description: Metrics, logs, and audit logging for monitoring Neptune cluster performance and compliance.\n  - name: AWS KMS\n    description: Encryption at rest using AWS Key Management Service\
  \ for customer-managed key support.\n  - name: Amazon VPC\n    description: Network isolation using Amazon Virtual Private Cloud with security group and firewall controls.\n  - name: Apache TinkerPop\n    description: Gremlin graph traversal language and TinkerPop ecosystem integration for property graph querying.\n  - name: Strands AI Agents SDK\n    description: Integration with Strands AI Agents SDK and popular agentic memory tools for AI agent applications.\n- type: SpectralRules\n  url: rules/amazon-neptune-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-neptune-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/neptune-graph-management.yaml\n- type: NaftikoCapability\n  url: capabilities/neptune-analytics-ml.yaml\n- type: JSON-LD\n  url: json-ld/amazon-neptune-analytics-context.jsonld\n  title: Analytics Context\n- type: JSON-LD\n  url: json-ld/amazon-neptune-data-context.jsonld\n  title: Data Context\n- type: JSON-LD\n  url: json-ld/amazon-neptune-gremlin-context.jsonld\n\
  \  title: Gremlin Context\n- type: JSON-LD\n  url: json-ld/amazon-neptune-loader-context.jsonld\n  title: Loader Context\n- type: JSON-LD\n  url: json-ld/amazon-neptune-management-context.jsonld\n  title: Management Context\n- type: JSON-LD\n  url: json-ld/amazon-neptune-ml-context.jsonld\n  title: Ml Context\n- type: JSON-LD\n  url: json-ld/amazon-neptune-opencypher-context.jsonld\n  title: Opencypher Context\n- type: JSON-LD\n  url: json-ld/amazon-neptune-sparql-context.jsonld\n  title: Sparql Context\n- type: JSON-LD\n  url: json-ld/amazon-neptune-streams-context.jsonld\n  title: Streams Context\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/apis.yml
tags:
- AWS
- Database
- Graph Database
- Gremlin
- Neptune
- Property Graph
- RDF
- SPARQL
url: ''
use_cases:
- description: Build knowledge graphs to enhance AI accuracy, comprehensiveness, and explainability using GraphRAG with Amazon Bedrock.
  name: Knowledge Graphs and GraphRAG
- description: Model transaction and account relationship networks to detect fraudulent patterns in near real-time using graph traversals.
  name: Fraud Detection
- description: Build unified customer profile graphs linking purchases, preferences, and interactions for personalization and marketing.
  name: Customer 360
- description: Model IT infrastructure as a connected graph to detect attack paths, anomalies, and proactive threats.
  name: Cybersecurity and Threat Detection
- description: Power product and content recommendation engines by traversing user-item relationship graphs.
  name: Recommendation Engines
- description: Model and query highly connected social graph data for applications requiring relationship traversal at scale.
  name: Social Networks
- description: Map network topology, dependencies, and configuration relationships for operations and impact analysis.
  name: Network and IT Operations
- description: Model complex supply chain relationships and dependencies for optimization and risk analysis.
  name: Supply Chain Management
---
