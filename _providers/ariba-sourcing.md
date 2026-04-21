---
api_count: 1
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
