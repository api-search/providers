---
api_count: 3
api_specs:
- filename: salesforce-automation-flow-openapi.yml
  format: yaml
  label: Salesforce Flow Automation API
  slug: salesforce-flow-automation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation-system/refs/heads/main/openapi/salesforce-automation-flow-openapi.yml
apis:
- description: REST API for querying Salesforce Flow definitions via the Tooling API, invoking autolaunched flows as REST actions, and managing approval process submissions and decisions.
  name: Salesforce Flow Automation API
  slug: salesforce-flow-automation-api
- description: Visual automation tool for building screen flows, autolaunched flows, record-triggered flows, and scheduled flows without code.
  name: Salesforce Flow Builder
  slug: salesforce-flow-builder
- description: Multi-step approval automation for routing records through review chains with configurable criteria, approvers, and post-approval actions.
  name: Salesforce Approval Processes
  slug: salesforce-approval-processes
capabilities:
- description: Workflow capability for Salesforce process automation combining Flow invocation, approval process management, and automation record querying. Serves admins, developers, and integration engineers manag
  name: Salesforce Process Automation
  slug: process-automation
common:
- title: ''
  type: Developer Portal
  url: https://developer.salesforce.com/
- title: ''
  type: Documentation
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/
- title: ''
  type: Trailhead
  url: https://trailhead.salesforce.com/content/learn/trails/automate_business_processes
- title: ''
  type: Authentication
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm
- title: ''
  type: Blog
  url: https://developer.salesforce.com/blogs
- title: ''
  type: Status
  url: https://status.salesforce.com/
- title: ''
  type: Support
  url: https://help.salesforce.com/
- title: ''
  type: Terms of Service
  url: https://www.salesforce.com/company/legal/agreements/
- title: ''
  type: Privacy Policy
  url: https://www.salesforce.com/company/privacy/
- title: ''
  type: GitHub Organization
  url: https://github.com/salesforce
- title: ''
  type: Community
  url: https://trailhead.salesforce.com/trailblazer-community/topics/salesforcedeveloper
created: '2024-01-15'
description: Salesforce Automation System refers to the collection of APIs and tools within Salesforce for automating business processes, including Flow Builder, approval processes, Process Builder, and Workflow Rules. These capabilities enable organizations to automate CRM, sales, marketing, and customer service workflows programmatically via the Salesforce REST API.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 1
  name: Salesforce Automation System Context
  property_count: 20
  slug: salesforce-automation-system-context
layout: provider
modified: '2026-05-02'
name: Salesforce Automation System
rules:
- name: Salesforce Automation System API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 4
  slug: salesforce-automation-system-rules
skills: []
slug: salesforce-automation-system
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: salesforce-automation-system\nname: Salesforce Automation System\ndescription: >-\n  Salesforce Automation System refers to the collection of APIs and tools\n  within Salesforce for automating business processes, including Flow Builder,\n  approval processes, Process Builder, and Workflow Rules. These capabilities\n  enable organizations to automate CRM, sales, marketing, and customer service\n  workflows programmatically via the Salesforce REST API.\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Approval Process\n  - Automation\n  - CRM\n  - Flow\n  - Process Builder\n  - Salesforce\n  - Workflow\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/salesforce-automation-system/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: salesforce-automation-system:salesforce-flow-automation-api\n    name: Salesforce Flow Automation\
  \ API\n    description: >-\n      REST API for querying Salesforce Flow definitions via the Tooling API,\n      invoking autolaunched flows as REST actions, and managing approval\n      process submissions and decisions.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm\n    baseURL: https://{instance}.salesforce.com/services/data/v59.0\n    tags:\n      - Approval Process\n      - Automation\n      - CRM\n      - Flow\n      - Salesforce\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_actions_invocable.htm\n      - type: OpenAPI\n        url: openapi/salesforce-automation-flow-openapi.yml\n      - type: JSONSchema\n        url: json-schema/salesforce-flow-definition-schema.json\n      - type: JSONSchema\n        url: json-schema/salesforce-approval-request-schema.json\n      - type: JSONLD\n        url: json-ld/salesforce-automation-system-context.jsonld\n\
  \      - type: SpectralRules\n        url: rules/salesforce-automation-system-rules.yml\n      - type: Capabilities\n        url: capabilities/process-automation.yaml\n      - type: Vocabulary\n        url: vocabulary/salesforce-automation-system-vocabulary.yml\n  - aid: salesforce-automation-system:salesforce-flow-builder\n    name: Salesforce Flow Builder\n    description: >-\n      Visual automation tool for building screen flows, autolaunched flows,\n      record-triggered flows, and scheduled flows without code.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.flow.meta/flow/flow_intro.htm\n    tags:\n      - Automation\n      - Flow\n      - No-Code\n      - Salesforce\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.flow.meta/flow/flow_intro.htm\n      - type: Getting Started\n        url: https://trailhead.salesforce.com/content/learn/trails/automate_business_processes\n  - aid: salesforce-automation-system:salesforce-approval-processes\n\
  \    name: Salesforce Approval Processes\n    description: >-\n      Multi-step approval automation for routing records through review chains\n      with configurable criteria, approvers, and post-approval actions.\n    humanURL: https://help.salesforce.com/s/articleView?id=sf.approvals_landing_page.htm\n    tags:\n      - Approval\n      - Automation\n      - CRM\n      - Salesforce\n    properties:\n      - type: Documentation\n        url: https://help.salesforce.com/s/articleView?id=sf.approvals_landing_page.htm\n      - type: API Reference\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_process_approvals.htm\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Developer Portal\n    url: https://developer.salesforce.com/\n  - type: Documentation\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/\n  - type: Trailhead\n    url: https://trailhead.salesforce.com/content/learn/trails/automate_business_processes\n\
  \  - type: Authentication\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/intro_oauth_and_connected_apps.htm\n  - type: Blog\n    url: https://developer.salesforce.com/blogs\n  - type: Status\n    url: https://status.salesforce.com/\n  - type: Support\n    url: https://help.salesforce.com/\n  - type: Terms of Service\n    url: https://www.salesforce.com/company/legal/agreements/\n  - type: Privacy Policy\n    url: https://www.salesforce.com/company/privacy/\n  - type: GitHub Organization\n    url: https://github.com/salesforce\n  - type: Community\n    url: https://trailhead.salesforce.com/trailblazer-community/topics/salesforcedeveloper\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation-system/refs/heads/main/apis.yml
tags:
- Approval Process
- Automation
- CRM
- Flow
- Process Builder
- Salesforce
- Workflow
url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation-system/refs/heads/main/apis.yml
use_cases: []
---
