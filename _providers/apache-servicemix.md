---
api_count: 1
api_specs:
- filename: apache-servicemix-rest-api.yaml
  format: yaml
  label: Apache ServiceMix
  slug: apache-servicemix
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-servicemix/refs/heads/main/openapi/apache-servicemix-rest-api.yaml
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
source_filename: apis.yml
source_yaml: "aid: apache-servicemix\nname: Apache ServiceMix\ndescription: >-\n  Apache ServiceMix is a flexible, open-source integration container that unifies the features and functionality of Apache ActiveMQ, Camel, CXF, and Karaf into a powerful runtime for building enterprise\n  integration solutions.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Enterprise Integration\n- ESB\n- Integration\n- Messaging\n- OSGi\n- Apache\n- Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-servicemix/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-servicemix:apache-servicemix\n  name: Apache ServiceMix\n  description: >-\n    ServiceMix provides an OSGi-based ESB with JBI API support, integrating Camel for routing, CXF for web services, and ActiveMQ for messaging, with programmatic service deployment\
  \ and management APIs.\n  humanURL: https://servicemix.apache.org/docs/7.x/\n  tags:\n  - Enterprise Integration\n  - ESB\n  - REST\n  - Apache\n  - Open Source\n  properties:\n  - type: Documentation\n    url: https://servicemix.apache.org/docs/7.x/\n  - type: Documentation\n    url: https://servicemix.apache.org/\n  - type: OpenAPI\n    url: openapi/apache-servicemix-rest-api.yaml\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: GitHubOrganization\n  url: https://github.com/apache/servicemix\n- type: Documentation\n  url: https://servicemix.apache.org/\n- type: SpectralRules\n  url: rules/apache-servicemix-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/apache-servicemix-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/servicemix-workflow.yaml\n- type: JSON-LD\n  url: json-ld/apache-servicemix-context.jsonld\n- type: Features\n  data:\n  - name: OSGi Container\n    description: Apache Karaf-based OSGi container for modular deployment\n\
  \  - name: Apache Camel Routes\n    description: Rich integration routing with 300+ Camel components\n  - name: Apache CXF\n    description: SOAP and REST web service hosting with CXF\n  - name: ActiveMQ Messaging\n    description: Built-in JMS messaging with Apache ActiveMQ\n  - name: Hot Deployment\n    description: Dynamic deployment of bundles and routes without restart\n  - name: Enterprise Patterns\n    description: Support for EIP patterns including routing, transformation, and mediation\n- type: UseCases\n  data:\n  - name: Legacy System Integration\n    description: Connect legacy SOAP services with modern REST APIs\n  - name: Message Routing\n    description: Route JMS messages between queues and topics\n  - name: Service Orchestration\n    description: Orchestrate multiple services into composite workflows\n  - name: Protocol Mediation\n    description: Transform between HTTP, JMS, JDBC, and file protocols\n- type: Integrations\n  data:\n  - name: Apache Camel\n    description:\
  \ Core integration framework providing routing and mediation\n  - name: Apache CXF\n    description: SOAP and REST web service framework\n  - name: Apache ActiveMQ\n    description: JMS message broker for asynchronous messaging\n  - name: Apache Karaf\n    description: OSGi container and runtime\n  - name: Spring Framework\n    description: Spring integration for bean management and transactions\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-servicemix/refs/heads/main/apis.yml
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
