---
api_count: 1
apis:
- description: 'The OpenWhisk API provides REST endpoints for managing actions, triggers, rules, packages, and activations, supporting serverless function development in JavaScript, Python, Swift, Java, Go, PHP, and '
  name: Apache OpenWhisk REST API
  slug: apache-openwhisk-rest-api
capabilities:
- description: Unified workflow capability for deploying and managing serverless functions, event triggers, rules, and activations in Apache OpenWhisk.
  name: Apache OpenWhisk Serverless Workflow
  slug: serverless-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/openwhisk
- title: ''
  type: Documentation
  url: https://openwhisk.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-openwhisk-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-openwhisk-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/serverless-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-openwhisk-context.jsonld
created: '2026-03-16'
description: Apache OpenWhisk is an open-source serverless cloud platform that executes functions in response to events at any scale. It supports multiple programming languages and provides a rich programming model for creating serverless APIs and event-driven applications.
features:
- description: Execute stateless functions in response to events without managing infrastructure
  name: Serverless Functions
- description: Supports Node.js, Python, Java, Go, PHP, Ruby, Swift, and custom Docker runtimes
  name: Multi-Language Support
- description: Named event channels that fire actions based on external events
  name: Event Triggers
- description: Compose multiple actions into sequential pipelines
  name: Action Sequences
- description: Pre-built integrations via /whisk.system namespace
  name: Package System
- description: Full REST API for managing all platform resources programmatically
  name: REST API
- description: Custom runtime support via Docker containers for any language
  name: Docker Actions
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Respond to Slack events and slash commands
  name: Slack
- description: Automate workflows based on GitHub repository events
  name: GitHub
- description: Process Kafka message stream events
  name: Apache Kafka
- description: React to CouchDB/Cloudant database changes
  name: Cloudant
- description: Available as IBM Cloud Functions on IBM Cloud
  name: IBM Cloud
- description: Deploy OpenWhisk on Kubernetes using Helm charts
  name: Kubernetes
jsonld:
- class_count: 18
  name: Apache Openwhisk Context
  property_count: 37
  slug: apache-openwhisk-context
layout: provider
modified: '2026-04-19'
name: Apache OpenWhisk
rules:
- name: Apache OpenWhisk API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 3
    warn: 3
  slug: apache-openwhisk-spectral-rules
skills: []
slug: apache-openwhisk
solutions: []
tags:
- Cloud Native
- Event-Driven
- FaaS
- Serverless
- Apache
- Open Source
- Functions
url: https://raw.githubusercontent.com/api-evangelist/apache-openwhisk/refs/heads/main/apis.yml
use_cases:
- description: Build loosely coupled microservices that respond to events
  name: Event-Driven Microservices
- description: Process sensor and device events at scale without infrastructure management
  name: IoT Data Processing
- description: Create REST APIs backed by serverless functions
  name: API Backend
- description: Run periodic jobs using alarm triggers
  name: Scheduled Tasks
- description: Handle Slack, GitHub, and other webhook events
  name: Chatbots & Webhooks
---
