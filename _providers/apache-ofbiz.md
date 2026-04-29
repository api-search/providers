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
source_yaml: "aid: apache-ofbiz\nname: Apache OFBiz\ndescription: >-\n  Apache OFBiz is an open-source enterprise resource planning (ERP) system providing a suite\n  of integrated business applications for CRM, e-commerce, supply chain management,\n  manufacturing, accounting, order management, inventory, and warehousing. Built on a\n  service-oriented architecture with a service engine, entity engine, and widget framework,\n  OFBiz exposes a REST API plugin allowing any exported service to be invoked via JWT-\n  authenticated HTTP endpoints. Governed by the Apache Software Foundation under the\n  Apache License 2.0. Written in Java with Groovy scripting support.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - ERP\n  - CRM\n  - E-Commerce\n  - Business Applications\n  - Apache\n  - Java\n  - Open Source\n  - Supply Chain\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: apache-ofbiz:apache-ofbiz-rest-api\n    name: Apache OFBiz REST API\n    description: >-\n      REST API plugin for Apache OFBiz that exposes any exported OFBiz service as a\n      RESTful endpoint. Clients authenticate via HTTP Basic Auth to obtain a JWT token,\n      then invoke services via GET (with URL-encoded JSON parameters) or POST (with JSON\n      request body). Swagger UI is available at /docs/swagger-ui.html when the plugin is\n      installed.\n    humanURL: https://github.com/apache/ofbiz-plugins/tree/trunk/rest-api\n    baseURL: https://localhost:8443/rest\n    tags:\n      - REST\n      - JWT\n      - Service Engine\n      - ERP\n    properties:\n      - type: Documentation\n        url: https://github.com/apache/ofbiz-plugins/blob/trunk/rest-api/src/docs/asciidoc/rest-api.adoc\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/openapi/apache-ofbiz-rest-api-openapi.yaml\n\
  \      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/json-schema/apache-ofbiz-token-response-schema.json\n        title: Token Response Schema\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/json-schema/apache-ofbiz-service-entry-schema.json\n        title: Service Entry Schema\n      - type: JSONSchema\n        url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/json-schema/apache-ofbiz-service-response-schema.json\n        title: Service Response Schema\n\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/ofbiz-framework\n    title: Apache OFBiz Framework GitHub Repository\n  - type: GitHubOrganization\n    url: https://github.com/apache\n    title: Apache Software Foundation GitHub\n  - type: Documentation\n    url: https://ofbiz.apache.org/documentation.html\n    title: Apache OFBiz Documentation\n\
  \  - type: GettingStarted\n    url: https://nightlies.apache.org/ofbiz/stable/ofbiz/html5/developer-manual.html\n    title: OFBiz Developer Manual\n  - type: Tutorials\n    url: https://cwiki.apache.org/confluence/display/OFBIZ/Home\n    title: OFBiz Wiki\n  - type: FAQ\n    url: https://ofbiz.apache.org/faqs.html\n    title: Apache OFBiz FAQs\n  - type: ReleaseNotes\n    url: https://github.com/apache/ofbiz-framework/blob/trunk/CHANGELOG.md\n    title: OFBiz Release Notes\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n    title: Apache License 2.0\n  - type: Support\n    url: https://ofbiz.apache.org/mailing-lists.html\n    title: Mailing Lists\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/ofbiz\n    title: OFBiz on Stack Overflow\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/rules/apache-ofbiz-spectral-rules.yml\n    title: Apache OFBiz Spectral Rules\n\
  \  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/capabilities/apache-ofbiz-erp-operations.yaml\n    title: Apache OFBiz ERP Operations\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/vocabulary/apache-ofbiz-vocabulary.yaml\n    title: Apache OFBiz Vocabulary\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/json-ld/apache-ofbiz-context.jsonld\n    title: Apache OFBiz JSON-LD Context\n  - type: Features\n    data:\n      - name: Service-Oriented Architecture\n        description: All business logic encapsulated in services accessible via multiple protocols including REST, XML-RPC, and Java.\n      - name: REST API Plugin\n        description: Plugin enabling any exported OFBiz service to be invoked via RESTful HTTP endpoints with JWT authentication.\n      - name: JWT Authentication\n        description:\
  \ OAuth2-compatible JWT-based authentication with access tokens and refresh tokens for secure API access.\n      - name: Entity Engine\n        description: Flexible data access layer supporting multiple databases with entity-based query API and relationship management.\n      - name: Service Engine\n        description: Central business logic executor with transaction management, error handling, and event-driven service chaining.\n      - name: Swagger UI Integration\n        description: Built-in Swagger/OpenAPI UI at /docs/swagger-ui.html for API exploration and testing when REST plugin is deployed.\n      - name: Groovy Scripting\n        description: Groovy scripting support for service implementations and customizations without Java compilation.\n      - name: Plugin Architecture\n        description: Modular plugin system allowing feature extension without modifying core framework code.\n      - name: Multi-Module ERP\n        description: Integrated modules for accounting, order\
  \ management, inventory, manufacturing, CRM, e-commerce, and HR.\n      - name: Widget Framework\n        description: XML-based UI component framework for building consistent web interfaces across ERP modules.\n  - type: UseCases\n    data:\n      - name: ERP System Integration\n        description: Integrate external systems (CRM, WMS, payment processors) with OFBiz via REST API service calls.\n      - name: E-Commerce Backend\n        description: Use OFBiz as a headless e-commerce backend with product catalog, pricing, order management, and fulfillment services.\n      - name: Supply Chain Automation\n        description: Automate supply chain workflows including purchase orders, inventory updates, and supplier communications via REST services.\n      - name: Accounting Automation\n        description: Automate accounting entries, invoicing, AR/AP processing, and financial reporting via OFBiz service API.\n      - name: Manufacturing Operations\n        description: Manage manufacturing\
  \ resource planning, work orders, bill of materials, and production scheduling via OFBiz services.\n      - name: Custom Business Workflows\n        description: Build custom business process automations by chaining OFBiz services via the REST API.\n  - type: Integrations\n    data:\n      - name: Apache Solr\n        description: Integration for product and content search indexing across OFBiz data.\n      - name: Groovy\n        description: Groovy scripting engine integration for service implementations and data transformations.\n      - name: PostgreSQL\n        description: Supported relational database backend via the OFBiz entity engine.\n      - name: MySQL\n        description: Supported relational database backend for OFBiz data persistence.\n      - name: Docker\n        description: Official Docker support for containerized OFBiz deployments.\n      - name: Swagger UI\n        description: OpenAPI documentation and testing interface bundled with the REST API plugin.\n\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-ofbiz/refs/heads/main/apis.yml
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
