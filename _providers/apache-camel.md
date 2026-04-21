---
api_count: 4
apis:
- description: The Apache Camel Java DSL provides a fluent API for defining integration routes using Enterprise Integration Patterns. Developers define RouteBuilder subclasses to connect Camel components via endpoin
  name: Apache Camel Java DSL API
  slug: apache-camel-java-dsl
- description: The Apache Camel REST DSL provides a concise syntax for exposing and consuming RESTful services within Camel routes. It supports both REST service definition and REST proxy/consumer patterns.
  name: Apache Camel REST DSL API
  slug: apache-camel-rest-dsl
- description: The Apache Camel K Operator exposes a Kubernetes Custom Resource API for deploying and managing Camel integrations as cloud-native serverless workloads on Kubernetes and OpenShift.
  name: Apache Camel K Operator API
  slug: apache-camel-k-operator-api
- description: Apache Camel Quarkus provides native compilation and fast startup of Camel routes on Quarkus, enabling serverless and microservice deployments with Camel's integration components.
  name: Apache Camel Quarkus API
  slug: apache-camel-quarkus-api
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/camel
- title: ''
  type: Documentation
  url: https://camel.apache.org/docs/
- title: ''
  type: GettingStarted
  url: https://camel.apache.org/manual/getting-started.html
- title: ''
  type: Tutorials
  url: https://camel.apache.org/manual/camel-example-main.html
- title: ''
  type: Support
  url: https://camel.apache.org/community/support/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: ''
  type: ChangeLog
  url: https://github.com/apache/camel/releases
- title: ''
  type: FAQ
  url: https://camel.apache.org/manual/faq/index.html
- title: Java SDK (Maven)
  type: SDK
  url: https://search.maven.org/artifact/org.apache.camel/camel-core
- title: ''
  type: Vocabulary
  url: vocabulary/apache-camel-vocabulary.yaml
created: '2025-06-05'
description: Apache Camel is an open-source integration framework developed by the Apache Software Foundation that implements Enterprise Integration Patterns (EIPs) for connecting systems, services, and data. It provides a domain-specific language (DSL) in Java, XML, YAML, and Kotlin for defining routes between components. Camel ships with over 300 components for connecting to messaging systems, databases, cloud services, APIs, and file formats. Camel K extends this with a Kubernetes-native integration runtime and operator with a REST management API.
features:
- description: Implementation of 65+ EIPs including splitter, aggregator, content-based router, message translator, and dead letter channel.
  name: Enterprise Integration Patterns
- description: Pre-built connectors for messaging (Kafka, ActiveMQ, RabbitMQ), cloud (AWS, Azure, GCP), databases, REST, SOAP, and file formats.
  name: 300+ Components
- description: Define routes in Java, XML, YAML, Kotlin, or Groovy DSL with full feature parity across languages.
  name: Multi-DSL Support
- description: Concise DSL for exposing and consuming RESTful services with OpenAPI/Swagger integration.
  name: REST DSL
- description: Deploy Camel integrations as cloud-native serverless workloads on Kubernetes and OpenShift.
  name: Camel K Kubernetes Operator
- description: Native compilation of Camel routes with Quarkus for fast startup and low memory serverless deployments.
  name: Camel Quarkus
- description: Built-in support for 50+ data format conversions including JSON, XML, CSV, Avro, Protobuf, and EDI.
  name: Data Formats
- description: Parameterized route templates for building reusable integration patterns.
  name: Route Templates
- description: Distributed transaction support using the saga pattern with compensating actions.
  name: Saga Pattern
- description: Built-in metrics, tracing (OpenTelemetry), and health check endpoints for Camel routes.
  name: Observability
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Camel Kafka component for producing and consuming Kafka topic messages in integration routes.
  name: Apache Kafka
- description: Camel ActiveMQ component for JMS messaging with Apache ActiveMQ Classic and Artemis.
  name: Apache ActiveMQ
- description: Camel AWS components for S3, SQS, SNS, DynamoDB, Lambda, and other AWS services.
  name: AWS Services
- description: Camel K Operator for deploying integrations as native Kubernetes Custom Resources.
  name: Kubernetes
- description: Camel REST DSL generates OpenAPI specifications and can create routes from OpenAPI contracts.
  name: OpenAPI
- description: Camel Spring Boot starter for integrating Camel into Spring Boot applications.
  name: Spring Boot
- description: Camel Quarkus extensions for native compilation and serverless deployment of integration routes.
  name: Quarkus
layout: provider
modified: '2026-04-19'
name: Apache Camel
skills: []
slug: apache-camel
solutions: []
tags:
- Apache
- Enterprise Integration
- Integration
- Messaging
- Open Source
- Routing
url: https://raw.githubusercontent.com/api-evangelist/apache-camel/refs/heads/main/apis.yml
use_cases:
- description: Connect disparate enterprise systems including ERP, CRM, databases, and cloud services using EIP patterns.
  name: System Integration
- description: Build lightweight API gateways for routing, transformation, and protocol mediation using the REST DSL.
  name: API Gateway
- description: Implement event-driven integrations with Kafka, ActiveMQ, and other messaging platforms.
  name: Event-Driven Architecture
- description: Build ETL pipelines transforming and routing data between storage systems and data formats.
  name: Data Pipeline
- description: Wire microservices together using Camel K serverless integrations on Kubernetes.
  name: Microservice Integration
- description: Bridge legacy SOAP, FTP, and EDI systems with modern REST and cloud-native services.
  name: Legacy Modernization
---
