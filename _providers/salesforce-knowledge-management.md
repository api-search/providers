---
api_count: 2
api_specs:
- filename: salesforce-knowledge-management-rest-api-openapi.yml
  format: yaml
  label: Salesforce Knowledge REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-knowledge-management/refs/heads/main/openapi/salesforce-knowledge-management-rest-api-openapi.yml
apis:
- description: REST API for accessing and managing Salesforce Knowledge articles, categories, and knowledge base content. Enables creating, reading, updating, publishing, and archiving knowledge articles for custome
  name: Salesforce Knowledge REST API
  slug: ''
- description: SOAP API for managing knowledge articles with enterprise integration.
  name: Salesforce Knowledge SOAP API
  slug: ''
capabilities:
- description: 'Unified workflow capability for managing Salesforce Knowledge articles across the full article lifecycle: creation, editing, categorization, publishing, and surfacing relevant articles for case deflec'
  name: Salesforce Knowledge Management
  slug: knowledge-management
common:
- title: ''
  type: Getting Started
  url: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/knowledge_development_intro.htm
- title: ''
  type: Authentication
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm
- title: ''
  type: Rate Limits
  url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm
- title: ''
  type: SDKs
  url: https://developer.salesforce.com/tools/sdks
- title: ''
  type: Status
  url: https://status.salesforce.com/
- title: ''
  type: Terms of Service
  url: https://www.salesforce.com/company/legal/agreements/
- title: ''
  type: Privacy Policy
  url: https://www.salesforce.com/company/privacy/
- title: ''
  type: Trailhead Learning
  url: https://trailhead.salesforce.com/en/content/learn/modules/knowledge-basics
- title: ''
  type: GitHub Organization
  url: https://github.com/salesforce
- title: ''
  type: Spectral Rules
  url: rules/salesforce-knowledge-management-rules.yml
- title: ''
  type: Capabilities
  url: capabilities/knowledge-management.yaml
- title: Knowledge Article Schema
  type: JSON Schema
  url: json-schema/salesforce-knowledge-management-article-schema.json
- title: Knowledge Category Schema
  type: JSON Schema
  url: json-schema/salesforce-knowledge-management-category-schema.json
- title: ''
  type: JSON-LD Context
  url: json-ld/salesforce-knowledge-management-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/salesforce-knowledge-management-vocabulary.yml
created: '2024'
description: API for managing knowledge articles, categories, and data in Salesforce Knowledge. Enables creating, reading, updating, publishing, and archiving knowledge articles for customer self-service and agent-assisted support scenarios across multiple channels including internal app, public knowledge base, and customer portals.
features: []
image: https://www.salesforce.com/content/dam/web/en_us/www/images/sf-logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Salesforce Knowledge Management Context
  property_count: 18
  slug: salesforce-knowledge-management-context
layout: provider
modified: '2026-05-02'
name: Salesforce Knowledge Management
rules:
- name: Salesforce Knowledge Management API Rules
  rule_count: 9
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 4
  slug: salesforce-knowledge-management-rules
skills: []
slug: salesforce-knowledge-management
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Salesforce Knowledge Management\ndescription: >-\n  API for managing knowledge articles, categories, and data in Salesforce Knowledge.\n  Enables creating, reading, updating, publishing, and archiving knowledge articles\n  for customer self-service and agent-assisted support scenarios across multiple\n  channels including internal app, public knowledge base, and customer portals.\nimage: https://www.salesforce.com/content/dam/web/en_us/www/images/sf-logo.svg\nurl: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/\ncreated: '2024'\nmodified: '2026-05-02'\nspecificationVersion: '0.18'\ntags:\n  - Articles\n  - CRM\n  - Customer Service\n  - Documentation\n  - Knowledge Management\n  - Support\napis:\n  - name: Salesforce Knowledge REST API\n    description: >-\n      REST API for accessing and managing Salesforce Knowledge articles, categories,\n      and knowledge base content. Enables creating, reading, updating, publishing,\n      and\
  \ archiving knowledge articles for customer self-service and agent-assisted\n      support scenarios.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/sf-logo.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/\n    baseURL: https://yourInstance.salesforce.com/services/data/v59.0/support\n    tags:\n      - Articles\n      - Knowledge\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/knowledge_development.htm\n      - type: OpenAPI\n        url: openapi/salesforce-knowledge-management-rest-api-openapi.yml\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_understanding_authentication.htm\n    contact:\n      - type: Support\n        url: https://help.salesforce.com/\n      - type: Community\n        url: https://trailblazers.salesforce.com/\n\
  \  - name: Salesforce Knowledge SOAP API\n    description: >-\n      SOAP API for managing knowledge articles with enterprise integration.\n    image: https://www.salesforce.com/content/dam/web/en_us/www/images/sf-logo.svg\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/\n    baseURL: https://yourInstance.salesforce.com/services/Soap/c/59.0\n    tags:\n      - Enterprise\n      - Knowledge\n      - SOAP\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_calls_knowledge.htm\n      - type: WSDL\n        url: https://yourInstance.salesforce.com/services/wsdl/class/KnowledgeArticleVersion\n      - type: Authentication\n        url: https://developer.salesforce.com/docs/atlas.en-us.api.meta/api/sforce_api_quickstart_intro.htm\ncommon:\n  - type: Getting Started\n    url: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/knowledge_development_intro.htm\n\
  \  - type: Authentication\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm\n  - type: Rate Limits\n    url: https://developer.salesforce.com/docs/atlas.en-us.salesforce_app_limits_cheatsheet.meta/salesforce_app_limits_cheatsheet/salesforce_app_limits_platform_api.htm\n  - type: SDKs\n    url: https://developer.salesforce.com/tools/sdks\n  - type: Status\n    url: https://status.salesforce.com/\n  - type: Terms of Service\n    url: https://www.salesforce.com/company/legal/agreements/\n  - type: Privacy Policy\n    url: https://www.salesforce.com/company/privacy/\n  - type: Trailhead Learning\n    url: https://trailhead.salesforce.com/en/content/learn/modules/knowledge-basics\n  - type: GitHub Organization\n    url: https://github.com/salesforce\n  - type: Spectral Rules\n    url: rules/salesforce-knowledge-management-rules.yml\n  - type: Capabilities\n    url: capabilities/knowledge-management.yaml\n  - type: JSON Schema\n\
  \    url: json-schema/salesforce-knowledge-management-article-schema.json\n    title: Knowledge Article Schema\n  - type: JSON Schema\n    url: json-schema/salesforce-knowledge-management-category-schema.json\n    title: Knowledge Category Schema\n  - type: JSON-LD Context\n    url: json-ld/salesforce-knowledge-management-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/salesforce-knowledge-management-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforce-knowledge-management/refs/heads/main/apis.yml
tags:
- Articles
- CRM
- Customer Service
- Documentation
- Knowledge Management
- Support
url: https://developer.salesforce.com/docs/atlas.en-us.knowledge_dev.meta/knowledge_dev/
use_cases: []
---
