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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloudhealth\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cloudhealth/refs/heads/main/apis.yml\nname: CloudHealth\ntags:\n  - Cloud Cost\n  - Cloud Governance\n  - Cloud Management\n  - Cost Optimization\n  - FinOps\n  - Multi-Cloud\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-16'\nmodified: '2026-04-26'\nposition: Consumer\nx-type: company\nx-company: Broadcom (formerly VMware / Tanzu)\ndescription: >-\n  CloudHealth (now VMware Tanzu CloudHealth, owned by Broadcom) is a\n  multi-cloud financial and operational management platform. It provides\n  cost visibility, optimization recommendations, asset inventory, custom\n  perspectives (groupings), policies, governance, and partner/MSP billing\n  workflows across AWS, Azure, GCP, Oracle, and data center environments.\n  The platform exposes both a REST API and a GraphQL API for programmatic\n  access to reports, assets,\
  \ accounts, perspectives, tags, metrics, and\n  partner customer provisioning.\napis:\n  - aid: cloudhealth:cloudhealth-rest-api\n    name: CloudHealth REST API\n    tags:\n      - Assets\n      - Cost Optimization\n      - Perspectives\n      - Reports\n    humanURL: https://apidocs.cloudhealthtech.com/\n    properties:\n      - url: https://apidocs.cloudhealthtech.com/\n        type: Documentation\n      - url: https://apidocs.cloudhealthtech.com/#documentation_authenticating-api-requests\n        type: Authentication\n    description: >-\n      REST API at https://chapi.cloudhealthtech.com for managing AWS/Azure\n      accounts, generating OLAP cost and usage reports, querying assets,\n      managing perspectives (groupings), tagging, metrics ingest/query,\n      policies, and partner-tenant provisioning. Authentication uses Bearer\n      tokens issued from the CloudHealth UI.\n  - aid: cloudhealth:cloudhealth-graphql-api\n    name: CloudHealth GraphQL API\n    tags:\n      - GraphQL\n\
  \      - Reports\n    humanURL: https://apidocs.cloudhealthtech.com/\n    properties:\n      - url: https://apidocs.cloudhealthtech.com/\n        type: Documentation\n    description: >-\n      GraphQL API exposed in the CloudHealth UI under Setup > Admin >\n      GraphQL Explorer for programmatic interaction with the platform's\n      reporting and asset data model.\n  - aid: cloudhealth:cloudhealth-partner-api\n    name: CloudHealth Partner API\n    tags:\n      - MSP\n      - Partner\n      - Provisioning\n    humanURL: https://apidocs.cloudhealthtech.com/#partner\n    properties:\n      - url: https://apidocs.cloudhealthtech.com/#partner\n        type: Documentation\n    description: >-\n      Partner-specific REST endpoints for MSPs to provision customers,\n      assign AWS/Azure accounts, manage custom price books, billing rules,\n      and customer statements at scale.\ncommon:\n  - type: Website\n    url: https://www.vmware.com/products/cloud-infrastructure/tanzu-cloudhealth\n\
  \  - type: Documentation\n    url: https://apidocs.cloudhealthtech.com/\n  - type: Product Documentation\n    url: https://techdocs.broadcom.com/us/en/vmware-tanzu/cloudhealth/tanzu-cloudhealth/saas/tnz-cloudhealth/index.html\n  - type: Authentication\n    url: https://apidocs.cloudhealthtech.com/#documentation_authenticating-api-requests\n  - type: Privacy Policy\n    url: https://www.broadcom.com/company/legal/privacy/policy\n  - type: JSON-LD\n    url: json-ld/cloudhealth-context.jsonld\n  - type: Spectral\n    url: rules/cloudhealth-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cloudhealth-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudhealth/refs/heads/main/apis.yml
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
