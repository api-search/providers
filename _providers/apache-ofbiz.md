---
api_count: 1
apis:
- description: REST API plugin for Apache OFBiz that exposes any exported OFBiz service as a RESTful endpoint. Clients authenticate via HTTP Basic Auth to obtain a JWT token, then invoke services via GET (with URL-e
  name: Apache OFBiz REST API
  slug: apache-ofbiz-rest-api
capabilities:
- description: Workflow capability for ERP and business process automation using Apache OFBiz REST API. Covers authentication, service discovery, and invocation of OFBiz services for ERP, CRM, e-commerce, and supply
  name: Apache OFBiz ERP Operations
  slug: apache-ofbiz-erp-operations
common:
- title: Apache OFBiz Framework GitHub Repository
  type: GitHubRepository
  url: https://github.com/apache/ofbiz-framework
- title: Apache Software Foundation GitHub
  type: GitHubOrganization
  url: https://github.com/apache
- title: Apache OFBiz Documentation
  type: Documentation
  url: https://ofbiz.apache.org/documentation.html
- title: OFBiz Developer Manual
  type: GettingStarted
  url: https://nightlies.apache.org/ofbiz/stable/ofbiz/html5/developer-manual.html
- title: OFBiz Wiki
  type: Tutorials
  url: https://cwiki.apache.org/confluence/display/OFBIZ/Home
- title: Apache OFBiz FAQs
  type: FAQ
  url: https://ofbiz.apache.org/faqs.html
- title: OFBiz Release Notes
  type: ReleaseNotes
  url: https://github.com/apache/ofbiz-framework/blob/trunk/CHANGELOG.md
- title: Apache License 2.0
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: Mailing Lists
  type: Support
  url: https://ofbiz.apache.org/mailing-lists.html
- title: OFBiz on Stack Overflow
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/ofbiz
- title: Apache OFBiz Spectral Rules
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/rules/apache-ofbiz-spectral-rules.yml
- title: Apache OFBiz ERP Operations
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/capabilities/apache-ofbiz-erp-operations.yaml
- title: Apache OFBiz Vocabulary
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/vocabulary/apache-ofbiz-vocabulary.yaml
- title: Apache OFBiz JSON-LD Context
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/json-ld/apache-ofbiz-context.jsonld
created: '2026-03-16'
description: Apache OFBiz is an open-source enterprise resource planning (ERP) system providing a suite of integrated business applications for CRM, e-commerce, supply chain management, manufacturing, accounting, order management, inventory, and warehousing. Built on a service-oriented architecture with a service engine, entity engine, and widget framework, OFBiz exposes a REST API plugin allowing any exported service to be invoked via JWT- authenticated HTTP endpoints. Governed by the Apache Software Foundation under the Apache License 2.0. Written in Java with Groovy scripting support.
features:
- description: All business logic encapsulated in services accessible via multiple protocols including REST, XML-RPC, and Java.
  name: Service-Oriented Architecture
- description: Plugin enabling any exported OFBiz service to be invoked via RESTful HTTP endpoints with JWT authentication.
  name: REST API Plugin
- description: OAuth2-compatible JWT-based authentication with access tokens and refresh tokens for secure API access.
  name: JWT Authentication
- description: Flexible data access layer supporting multiple databases with entity-based query API and relationship management.
  name: Entity Engine
- description: Central business logic executor with transaction management, error handling, and event-driven service chaining.
  name: Service Engine
- description: Built-in Swagger/OpenAPI UI at /docs/swagger-ui.html for API exploration and testing when REST plugin is deployed.
  name: Swagger UI Integration
- description: Groovy scripting support for service implementations and customizations without Java compilation.
  name: Groovy Scripting
- description: Modular plugin system allowing feature extension without modifying core framework code.
  name: Plugin Architecture
- description: Integrated modules for accounting, order management, inventory, manufacturing, CRM, e-commerce, and HR.
  name: Multi-Module ERP
- description: XML-based UI component framework for building consistent web interfaces across ERP modules.
  name: Widget Framework
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration for product and content search indexing across OFBiz data.
  name: Apache Solr
- description: Groovy scripting engine integration for service implementations and data transformations.
  name: Groovy
- description: Supported relational database backend via the OFBiz entity engine.
  name: PostgreSQL
- description: Supported relational database backend for OFBiz data persistence.
  name: MySQL
- description: Official Docker support for containerized OFBiz deployments.
  name: Docker
- description: OpenAPI documentation and testing interface bundled with the REST API plugin.
  name: Swagger UI
jsonld:
- class_count: 9
  name: Apache Ofbiz Context
  property_count: 12
  slug: apache-ofbiz-context
layout: provider
modified: '2026-04-19'
name: Apache OFBiz
rules:
- name: Apache OFBiz API Rules
  rule_count: 31
  severity_counts:
    error: 12
    hint: 0
    info: 4
    warn: 15
  slug: apache-ofbiz-spectral-rules
skills: []
slug: apache-ofbiz
solutions: []
tags:
- ERP
- CRM
- E-Commerce
- Business Applications
- Apache
- Java
- Open Source
- Supply Chain
url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/apis.yml
use_cases:
- description: Integrate external systems (CRM, WMS, payment processors) with OFBiz via REST API service calls.
  name: ERP System Integration
- description: Use OFBiz as a headless e-commerce backend with product catalog, pricing, order management, and fulfillment services.
  name: E-Commerce Backend
- description: Automate supply chain workflows including purchase orders, inventory updates, and supplier communications via REST services.
  name: Supply Chain Automation
- description: Automate accounting entries, invoicing, AR/AP processing, and financial reporting via OFBiz service API.
  name: Accounting Automation
- description: Manage manufacturing resource planning, work orders, bill of materials, and production scheduling via OFBiz services.
  name: Manufacturing Operations
- description: Build custom business process automations by chaining OFBiz services via the REST API.
  name: Custom Business Workflows
---
