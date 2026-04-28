---
api_count: 3
apis:
- description: REST API at https://chapi.cloudhealthtech.com for managing AWS/Azure accounts, generating OLAP cost and usage reports, querying assets, managing perspectives (groupings), tagging, metrics ingest/query
  name: CloudHealth REST API
  slug: cloudhealth-rest-api
- description: GraphQL API exposed in the CloudHealth UI under Setup > Admin > GraphQL Explorer for programmatic interaction with the platform's reporting and asset data model.
  name: CloudHealth GraphQL API
  slug: cloudhealth-graphql-api
- description: Partner-specific REST endpoints for MSPs to provision customers, assign AWS/Azure accounts, manage custom price books, billing rules, and customer statements at scale.
  name: CloudHealth Partner API
  slug: cloudhealth-partner-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.vmware.com/products/cloud-infrastructure/tanzu-cloudhealth
- title: ''
  type: Documentation
  url: https://apidocs.cloudhealthtech.com/
- title: ''
  type: Product Documentation
  url: https://techdocs.broadcom.com/us/en/vmware-tanzu/cloudhealth/tanzu-cloudhealth/saas/tnz-cloudhealth/index.html
- title: ''
  type: Authentication
  url: https://apidocs.cloudhealthtech.com/#documentation_authenticating-api-requests
- title: ''
  type: Privacy Policy
  url: https://www.broadcom.com/company/legal/privacy/policy
- title: ''
  type: JSON-LD
  url: json-ld/cloudhealth-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloudhealth-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cloudhealth-capabilities.yml
created: '2026-03-16'
description: CloudHealth (now VMware Tanzu CloudHealth, owned by Broadcom) is a multi-cloud financial and operational management platform. It provides cost visibility, optimization recommendations, asset inventory, custom perspectives (groupings), policies, governance, and partner/MSP billing workflows across AWS, Azure, GCP, Oracle, and data center environments. The platform exposes both a REST API and a GraphQL API for programmatic access to reports, assets, accounts, perspectives, tags, metrics, and partner customer provisioning.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloudhealth Context
  property_count: 5
  slug: cloudhealth-context
layout: provider
modified: '2026-04-26'
name: CloudHealth
rules:
- name: CloudHealth API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: cloudhealth-rules
skills: []
slug: cloudhealth
solutions: []
tags:
- Cloud Cost
- Cloud Governance
- Cloud Management
- Cost Optimization
- FinOps
- Multi-Cloud
url: https://raw.githubusercontent.com/api-evangelist/cloudhealth/refs/heads/main/apis.yml
use_cases: []
---
