---
api_count: 1
api_specs:
- filename: ariba-sourcing-external-approval-api.yaml
  format: yaml
  label: Ariba Sourcing - External Approval API
  slug: ariba-sourcing-external-approval-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ariba-sourcing/refs/heads/main/openapi/ariba-sourcing-external-approval-api.yaml
apis:
- description: The External Approval API for Sourcing and Supplier Management enables client applications to approve or deny SAP Ariba strategic sourcing approval tasks. It supports external approval tasks in sourci
  name: Ariba Sourcing - External Approval API
  slug: ariba-sourcing-external-approval-api
capabilities:
- description: Workflow for managing external approval tasks in SAP Ariba strategic sourcing projects, contracts, and supplier management. Used by procurement approvers and sourcing managers.
  name: Ariba Sourcing - Sourcing Approvals
  slug: sourcing-approvals
common:
- title: ''
  type: Portal
  url: https://developer.ariba.com
- title: ''
  type: Documentation
  url: https://help.sap.com/docs/ariba-apis
- title: ''
  type: GettingStarted
  url: https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-quick-start-guide-for-developers
- title: ''
  type: Support
  url: https://help.sap.com/ariba
- title: ''
  type: TermsOfService
  url: https://www.sap.com/corporate/en/legal/terms-of-use.html
- title: ''
  type: PrivacyPolicy
  url: https://www.sap.com/about/legal/privacy.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/SAP-samples
- title: SAP Ariba Extensibility Samples
  type: CodeExamples
  url: https://github.com/SAP-samples/ariba-extensibility-samples
- title: ''
  type: SpectralRules
  url: rules/ariba-sourcing-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/sourcing-approvals.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/ariba-sourcing-vocabulary.yaml
created: '2024-01-01'
description: SAP Ariba Sourcing provides cloud-based strategic sourcing capabilities for procurement organizations. It enables supplier collaboration, RFx management, electronic auctions, and contract management through APIs that integrate sourcing processes with enterprise systems.
features:
- description: Enables external systems to retrieve, review, and approve or deny SAP Ariba sourcing approval tasks programmatically.
  name: External Approval Workflow
- description: Supports approval tasks for sourcing projects, RFX documents, contract workspaces, contract content, and supplier management projects.
  name: Multi-Document Type Support
- description: Well-defined rate limits of 20 req/sec, 400 req/min, 12000 req/hour, and 40000 req/day for production stability.
  name: Rate-Limited API Access
- description: Results pagination with offset and limit parameters plus X-Total-Count headers for efficient data retrieval.
  name: Pagination Support
- description: Supports approval flows with groups, enabling retrieval of group membership to identify eligible approvers.
  name: Group-Based Approval
- description: Enables downloading attachments associated with approvable documents for review prior to approval decisions.
  name: Attachment Downloads
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Route sourcing approval tasks to SAP ERP workflows and approval hierarchies.
  name: SAP ERP
- description: Orchestrate approval workflows across SAP Ariba and connected systems using SAP Integration Suite.
  name: SAP Integration Suite
- description: Approve contract workspaces and contract content documents through the external approval API.
  name: SAP Ariba Contracts
- description: Approve supplier lifecycle and performance management projects and supplier registration requests.
  name: SAP Ariba Supplier Management
jsonld:
- class_count: 13
  name: Ariba Sourcing External Approval Api Context
  property_count: 20
  slug: ariba-sourcing-external-approval-api-context
layout: provider
modified: '2026-04-19'
name: Ariba Sourcing
rules:
- name: Ariba Sourcing API Rules
  rule_count: 28
  severity_counts:
    error: 15
    hint: 0
    info: 4
    warn: 9
  slug: ariba-sourcing-spectral-rules
skills: []
slug: ariba-sourcing
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ariba-sourcing\nname: Ariba Sourcing\ndescription: >-\n  SAP Ariba Sourcing provides cloud-based strategic sourcing capabilities for\n  procurement organizations. It enables supplier collaboration, RFx management,\n  electronic auctions, and contract management through APIs that integrate\n  sourcing processes with enterprise systems.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Approvals\n  - Auctions\n  - B2B\n  - Contracts\n  - Procurement\n  - RFx\n  - SAP\n  - Sourcing\n  - Supplier Management\n  - Supply Chain\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/ariba-sourcing/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: ariba-sourcing:ariba-sourcing-external-approval-api\n    name: Ariba Sourcing - External Approval API\n    description: >-\n      The External Approval API for Sourcing and Supplier Management enables\n \
  \     client applications to approve or deny SAP Ariba strategic sourcing\n      approval tasks. It supports external approval tasks in sourcing projects,\n      contract workspaces, engagement risk assessment, and all types of supplier\n      management projects.\n    humanURL: https://help.sap.com/docs/ariba-apis\n    baseURL: https://openapi.ariba.com/api/sourcing-approval/v2/prod\n    tags:\n      - Approvals\n      - Contracts\n      - RFx\n      - Sourcing\n      - Supplier Management\n    properties:\n      - type: Documentation\n        url: https://help.sap.com/doc/69824194c55e4393870c5d3587aaf821/cloud/en-US/abdf297f281243ed9f8f3ead706a74d3.pdf\n      - type: OpenAPI\n        url: openapi/ariba-sourcing-external-approval-api.yaml\n      - type: JSONSchema\n        url: json-schema/external-approval-api-approval-task-schema.json\n      - type: JSONSchema\n        url: json-schema/external-approval-api-approvable-document-schema.json\n      - type: JSONSchema\n        url: json-schema/external-approval-api-approval-changes-response-schema.json\n\
  \      - type: JSONStructure\n        url: json-structure/external-approval-api-approval-task-structure.json\n      - type: JSONStructure\n        url: json-structure/external-approval-api-approvable-document-structure.json\n      - type: JSON-LD\n        url: json-ld/ariba-sourcing-external-approval-api-context.jsonld\ncommon:\n  - type: Portal\n    url: https://developer.ariba.com\n  - type: Documentation\n    url: https://help.sap.com/docs/ariba-apis\n  - type: GettingStarted\n    url: https://help.sap.com/docs/ariba-apis/help-for-sap-ariba-developer-portal/sap-ariba-developer-portal-quick-start-guide-for-developers\n  - type: Support\n    url: https://help.sap.com/ariba\n  - type: TermsOfService\n    url: https://www.sap.com/corporate/en/legal/terms-of-use.html\n  - type: PrivacyPolicy\n    url: https://www.sap.com/about/legal/privacy.html\n  - type: GitHubOrganization\n    url: https://github.com/SAP-samples\n  - type: CodeExamples\n    url: https://github.com/SAP-samples/ariba-extensibility-samples\n\
  \    title: SAP Ariba Extensibility Samples\n  - type: SpectralRules\n    url: rules/ariba-sourcing-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/sourcing-approvals.yaml\n  - type: Vocabulary\n    url: vocabulary/ariba-sourcing-vocabulary.yaml\n  - type: Features\n    data:\n      - name: External Approval Workflow\n        description: >-\n          Enables external systems to retrieve, review, and approve or deny\n          SAP Ariba sourcing approval tasks programmatically.\n      - name: Multi-Document Type Support\n        description: >-\n          Supports approval tasks for sourcing projects, RFX documents, contract\n          workspaces, contract content, and supplier management projects.\n      - name: Rate-Limited API Access\n        description: >-\n          Well-defined rate limits of 20 req/sec, 400 req/min, 12000 req/hour,\n          and 40000 req/day for production stability.\n      - name: Pagination Support\n        description: >-\n        \
  \  Results pagination with offset and limit parameters plus\n          X-Total-Count headers for efficient data retrieval.\n      - name: Group-Based Approval\n        description: >-\n          Supports approval flows with groups, enabling retrieval of group\n          membership to identify eligible approvers.\n      - name: Attachment Downloads\n        description: >-\n          Enables downloading attachments associated with approvable documents\n          for review prior to approval decisions.\n  - type: UseCases\n    data:\n      - name: Automated Sourcing Approvals\n        description: >-\n          Automate the approval workflow for sourcing events and contracts by\n          polling for pending tasks and submitting programmatic approval actions.\n      - name: ERP-Integrated Approvals\n        description: >-\n          Route SAP Ariba sourcing approval tasks to external ERP or workflow\n          systems for approval by authorized personnel.\n      - name: Supplier Onboarding\
  \ Approval\n        description: >-\n          Manage external approval of supplier registration and onboarding\n          projects through the supplier management approval workflow.\n      - name: Contract Approval Automation\n        description: >-\n          Integrate contract workspace approvals with enterprise contract\n          management systems for streamlined legal and commercial review.\n  - type: Integrations\n    data:\n      - name: SAP ERP\n        description: >-\n          Route sourcing approval tasks to SAP ERP workflows and approval\n          hierarchies.\n      - name: SAP Integration Suite\n        description: >-\n          Orchestrate approval workflows across SAP Ariba and connected systems\n          using SAP Integration Suite.\n      - name: SAP Ariba Contracts\n        description: >-\n          Approve contract workspaces and contract content documents through the\n          external approval API.\n      - name: SAP Ariba Supplier Management\n        description:\
  \ >-\n          Approve supplier lifecycle and performance management projects and\n          supplier registration requests.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ariba-sourcing/refs/heads/main/apis.yml
tags:
- Approvals
- Auctions
- B2B
- Contracts
- Procurement
- RFx
- SAP
- Sourcing
- Supplier Management
- Supply Chain
url: https://raw.githubusercontent.com/api-evangelist/ariba-sourcing/refs/heads/main/apis.yml
use_cases:
- description: Automate the approval workflow for sourcing events and contracts by polling for pending tasks and submitting programmatic approval actions.
  name: Automated Sourcing Approvals
- description: Route SAP Ariba sourcing approval tasks to external ERP or workflow systems for approval by authorized personnel.
  name: ERP-Integrated Approvals
- description: Manage external approval of supplier registration and onboarding projects through the supplier management approval workflow.
  name: Supplier Onboarding Approval
- description: Integrate contract workspace approvals with enterprise contract management systems for streamlined legal and commercial review.
  name: Contract Approval Automation
---
