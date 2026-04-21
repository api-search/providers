---
api_count: 1
apis:
- description: ServiceMix provides an OSGi-based ESB with JBI API support, integrating Camel for routing, CXF for web services, and ActiveMQ for messaging, with programmatic service deployment and management APIs.
  name: Apache ServiceMix
  slug: apache-servicemix
capabilities:
- description: ''
  name: Servicemix Workflow
  slug: servicemix-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/servicemix
- title: ''
  type: Documentation
  url: https://servicemix.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-servicemix-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-servicemix-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/servicemix-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-servicemix-context.jsonld
created: '2026-03-16'
description: Apache ServiceMix is a flexible, open-source integration container that unifies the features and functionality of Apache ActiveMQ, Camel, CXF, and Karaf into a powerful runtime for building enterprise integration solutions.
features:
- description: Apache Karaf-based OSGi container for modular deployment
  name: OSGi Container
- description: Rich integration routing with 300+ Camel components
  name: Apache Camel Routes
- description: SOAP and REST web service hosting with CXF
  name: Apache CXF
- description: Built-in JMS messaging with Apache ActiveMQ
  name: ActiveMQ Messaging
- description: Dynamic deployment of bundles and routes without restart
  name: Hot Deployment
- description: Support for EIP patterns including routing, transformation, and mediation
  name: Enterprise Patterns
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Core integration framework providing routing and mediation
  name: Apache Camel
- description: SOAP and REST web service framework
  name: Apache CXF
- description: JMS message broker for asynchronous messaging
  name: Apache ActiveMQ
- description: OSGi container and runtime
  name: Apache Karaf
- description: Spring integration for bean management and transactions
  name: Spring Framework
jsonld:
- class_count: 9
  name: Apache Servicemix Context
  property_count: 24
  slug: apache-servicemix-context
layout: provider
modified: '2026-04-19'
name: Apache ServiceMix
rules:
- name: Apache ServiceMix API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: apache-servicemix-spectral-rules
skills: []
slug: apache-servicemix
solutions: []
tags:
- Enterprise Integration
- ESB
- Integration
- Messaging
- OSGi
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-servicemix/refs/heads/main/apis.yml
use_cases:
- description: Connect legacy SOAP services with modern REST APIs
  name: Legacy System Integration
- description: Route JMS messages between queues and topics
  name: Message Routing
- description: Orchestrate multiple services into composite workflows
  name: Service Orchestration
- description: Transform between HTTP, JMS, JDBC, and file protocols
  name: Protocol Mediation
---
