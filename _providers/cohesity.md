---
api_count: 2
apis:
- description: Helios is Cohesity's SaaS-based control plane that manages a fleet of Cohesity clusters from a single global pane of glass. The Helios REST API authenticates via an apiKey generated from the Helios UI
  name: Cohesity Helios REST API
  slug: helios-rest-api
- description: The DataProtect REST API is the per-cluster RESTful interface exposed by every Cohesity cluster, providing programmatic control over data management operations including backups, restores, replication
  name: Cohesity DataProtect REST API
  slug: dataprotect-rest-api
common:
- title: ''
  type: Website
  url: https://www.cohesity.com/
- title: ''
  type: Developer Portal
  url: https://developer.cohesity.com/
- title: ''
  type: Developers Site
  url: https://developers.cohesity.com/
- title: ''
  type: API Reference
  url: https://developer.cohesity.com/apidocs/versions/
- title: ''
  type: GitHub
  url: https://github.com/cohesity
- title: ''
  type: Documentation
  url: https://docs.cohesity.com/
- title: ''
  type: Support
  url: https://www.cohesity.com/support/
- title: ''
  type: Status
  url: https://status.cohesity.com/
- title: ''
  type: Privacy Policy
  url: https://www.cohesity.com/legal/privacy-policy/
- title: ''
  type: Terms of Use
  url: https://www.cohesity.com/agreements/website-terms-of-use/
created: '2025-03-01'
description: Cohesity is a data security and management company providing backup, disaster recovery, archive, and cyber resilience capabilities across on-premises, cloud, and SaaS workloads. Following the merger with Veritas, the combined company protects enterprise data while powering automation, orchestration, and AI- driven recovery. The Cohesity developer surface centers on the Cohesity REST API, exposed both per-cluster (DataProtect/cluster API) and via the Helios global control plane, with versioned v1 and v2 endpoints, API-key authentication, and SDKs for Python, PowerShell, Ansible, Terraform, and ServiceNow.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Cohesity
skills: []
slug: cohesity
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cohesity\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cohesity/refs/heads/main/apis.yml\nname: Cohesity\ntags:\n  - Automation\n  - Backup\n  - Cyber Resilience\n  - Data Management\n  - Data Protection\n  - Data Security\n  - DataProtect\n  - Disaster Recovery\n  - Helios\n  - Orchestration\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  Cohesity is a data security and management company providing backup, disaster\n  recovery, archive, and cyber resilience capabilities across on-premises, cloud,\n  and SaaS workloads. Following the merger with Veritas, the combined company\n  protects enterprise data while powering automation, orchestration, and AI-\n  driven recovery. The Cohesity developer surface centers on the Cohesity REST\n  API, exposed both per-cluster (DataProtect/cluster API)\
  \ and via the Helios\n  global control plane, with versioned v1 and v2 endpoints, API-key\n  authentication, and SDKs for Python, PowerShell, Ansible, Terraform, and\n  ServiceNow.\napis:\n  - aid: cohesity:helios-rest-api\n    name: Cohesity Helios REST API\n    tags:\n      - Automation\n      - Cluster Management\n      - DataProtect\n      - Helios\n      - Orchestration\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://helios.cohesity.com/irisservices/api/v1/public/\n    humanURL: https://developer.cohesity.com/helios-api.html\n    properties:\n      - url: https://developer.cohesity.com/helios-api.html\n        type: Documentation\n      - url: https://developer.cohesity.com/docs/helios-getting-started\n        type: GettingStarted\n      - url: https://developer.cohesity.com/apidocs/versions/\n        type: APIReference\n    description: >-\n      Helios is Cohesity's SaaS-based control plane that manages a fleet of\n  \
  \    Cohesity clusters from a single global pane of glass. The Helios REST API\n      authenticates via an apiKey generated from the Helios UI and passed in the\n      request header, supports both v1 and v2 endpoint families, and lets\n      customers list and operate registered clusters, run protection jobs,\n      manage policies, and access reporting and analytics globally.\n    x-features:\n      - apiKey-based authentication via Helios UI\n      - v1 and v2 API surfaces under /irisservices/api/\n      - Manage protection groups, policies, and recovery operations\n      - Reporting and global analytics across clusters\n      - Multi-cluster operations from a single endpoint\n    x-use-cases:\n      - Centralize backup and recovery automation across many Cohesity clusters\n      - Drive policy and SLA enforcement from CI/CD pipelines\n      - Trigger or schedule recoveries from external orchestration tools\n      - Export reporting data into SIEM or BI dashboards\n  - aid: cohesity:dataprotect-rest-api\n\
  \    name: Cohesity DataProtect REST API\n    tags:\n      - Backup\n      - DataProtect\n      - Disaster Recovery\n      - Per-Cluster\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.cohesity.com/apidocs/versions/\n    properties:\n      - url: https://developer.cohesity.com/apidocs/versions/\n        type: Documentation\n      - url: https://developers.cohesity.com/page/api-reference\n        type: APIReference\n    description: >-\n      The DataProtect REST API is the per-cluster RESTful interface exposed by\n      every Cohesity cluster, providing programmatic control over data\n      management operations including backups, restores, replication, archival,\n      cloud tiering, and storage domain management. Authentication is performed\n      via API keys for automation users or username/password for interactive\n      sessions.\n    x-features:\n      - Per-cluster REST endpoint\n      - API key and session\
  \ authentication\n      - Backup, restore, replication, and archive operations\n      - Storage domain and view management\n      - Versioned API generations available concurrently\n    x-use-cases:\n      - Automate cluster registration and configuration\n      - Trigger ad-hoc backups and recoveries from runbooks\n      - Integrate with vRealize, ServiceNow, Ansible, and Terraform workflows\n      - Build custom dashboards over per-cluster operational data\ncommon:\n  - type: Website\n    url: https://www.cohesity.com/\n  - type: Developer Portal\n    url: https://developer.cohesity.com/\n  - type: Developers Site\n    url: https://developers.cohesity.com/\n  - type: API Reference\n    url: https://developer.cohesity.com/apidocs/versions/\n  - type: GitHub\n    url: https://github.com/cohesity\n  - type: Documentation\n    url: https://docs.cohesity.com/\n  - type: Support\n    url: https://www.cohesity.com/support/\n  - type: Status\n    url: https://status.cohesity.com/\n  - type:\
  \ Privacy Policy\n    url: https://www.cohesity.com/legal/privacy-policy/\n  - type: Terms of Use\n    url: https://www.cohesity.com/agreements/website-terms-of-use/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cohesity/refs/heads/main/apis.yml
tags:
- Automation
- Backup
- Cyber Resilience
- Data Management
- Data Protection
- Data Security
- DataProtect
- Disaster Recovery
- Helios
- Orchestration
url: https://raw.githubusercontent.com/api-evangelist/cohesity/refs/heads/main/apis.yml
use_cases: []
---
