---
api_count: 6
apis:
- description: The Druva Cyber Resilience REST API provides programmatic access to reports and events across the Druva Data Resiliency Cloud, supporting ransomware recovery, anomaly detection, and security posture m
  name: Druva Cyber Resilience API
  slug: cyber-resilience
- description: The Druva Endpoints and Data Governance API exposes Reports and Events endpoints for visibility into endpoint backups, user activity, and governance posture across managed devices and SaaS workloads.
  name: Druva Endpoints and Data Governance API
  slug: endpoints-data-governance
- description: 'The Druva Enterprise Workloads Events API provides programmatic access to events generated across protected enterprise workloads such as servers, virtual machines, and databases inside the Druva Data '
  name: Druva Enterprise Workloads API
  slug: enterprise-workloads
- description: The Druva CloudRanger Native Workloads API provides automated backup, disaster recovery, and lifecycle management for AWS-native workloads including EC2, EBS, RDS, Redshift, and DynamoDB.
  name: Druva CloudRanger Native Workloads API
  slug: cloudranger
- description: The Druva MSP API enables managed service providers to programmatically manage tenants, customers, and reporting across the Druva platform from a single MSP console integration.
  name: Druva MSP API
  slug: msp
- description: The Druva Legal Hold Targeted Download API supports legal and compliance teams in initiating targeted downloads of preserved data from devices placed under legal hold within Druva.
  name: Druva Legal Hold Targeted Download API
  slug: legal-hold
common:
- title: ''
  type: Website
  url: https://www.druva.com
- title: ''
  type: Documentation
  url: https://docs.druva.com/
- title: ''
  type: DeveloperPortal
  url: https://developer.druva.com
- title: ''
  type: APIReference
  url: https://developer.druva.com/reference
- title: ''
  type: Support
  url: https://support.druva.com
- title: ''
  type: GitHub
  url: https://github.com/druvainc
created: '2026-03-27'
description: Druva is a cloud data protection and management platform providing SaaS backup, disaster recovery, and data governance for endpoints, data centers, and SaaS applications. Druva exposes a public REST API across its Cyber Resilience, Endpoint Data Governance, Enterprise Workloads, CloudRanger, MSP, and Legal Hold products, using token-based authentication and JSON over HTTPS.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Druva
skills: []
slug: druva
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: druva\nname: Druva\ndescription: >-\n  Druva is a cloud data protection and management platform providing SaaS backup,\n  disaster recovery, and data governance for endpoints, data centers, and SaaS\n  applications. Druva exposes a public REST API across its Cyber Resilience,\n  Endpoint Data Governance, Enterprise Workloads, CloudRanger, MSP, and Legal\n  Hold products, using token-based authentication and JSON over HTTPS.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Backup\n  - Cyber Resilience\n  - Data Protection\n  - Disaster Recovery\n  - SaaS Backup\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/druva/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: druva:cyber-resilience\n    name: Druva Cyber Resilience API\n    description: >-\n      The Druva Cyber Resilience REST API provides programmatic access to\n      reports\
  \ and events across the Druva Data Resiliency Cloud, supporting\n      ransomware recovery, anomaly detection, and security posture monitoring.\n    humanURL: https://developer.druva.com\n    baseURL: https://apis.druva.com\n    tags:\n      - Cyber Resilience\n      - Reports\n      - Events\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.druva.com\n      - type: Authentication\n        url: https://developer.druva.com\n  - aid: druva:endpoints-data-governance\n    name: Druva Endpoints and Data Governance API\n    description: >-\n      The Druva Endpoints and Data Governance API exposes Reports and Events\n      endpoints for visibility into endpoint backups, user activity, and\n      governance posture across managed devices and SaaS workloads.\n    humanURL: https://developer.druva.com\n    baseURL: https://apis.druva.com\n    tags:\n      - Endpoints\n      - Data Governance\n      - Reports\n      - Events\n    properties:\n      - type:\
  \ Documentation\n        url: https://developer.druva.com\n  - aid: druva:enterprise-workloads\n    name: Druva Enterprise Workloads API\n    description: >-\n      The Druva Enterprise Workloads Events API provides programmatic access to\n      events generated across protected enterprise workloads such as servers,\n      virtual machines, and databases inside the Druva Data Resiliency Cloud.\n    humanURL: https://developer.druva.com\n    baseURL: https://apis.druva.com\n    tags:\n      - Enterprise Workloads\n      - Events\n      - Backup\n  - aid: druva:cloudranger\n    name: Druva CloudRanger Native Workloads API\n    description: >-\n      The Druva CloudRanger Native Workloads API provides automated backup,\n      disaster recovery, and lifecycle management for AWS-native workloads\n      including EC2, EBS, RDS, Redshift, and DynamoDB.\n    humanURL: https://developer.druva.com\n    baseURL: https://apis.druva.com\n    tags:\n      - CloudRanger\n      - AWS\n      - Native Workloads\n\
  \      - Backup\n  - aid: druva:msp\n    name: Druva MSP API\n    description: >-\n      The Druva MSP API enables managed service providers to programmatically\n      manage tenants, customers, and reporting across the Druva platform from\n      a single MSP console integration.\n    humanURL: https://developer.druva.com\n    baseURL: https://apis.druva.com\n    tags:\n      - MSP\n      - Managed Service Providers\n      - Multi-Tenant\n  - aid: druva:legal-hold\n    name: Druva Legal Hold Targeted Download API\n    description: >-\n      The Druva Legal Hold Targeted Download API supports legal and compliance\n      teams in initiating targeted downloads of preserved data from devices\n      placed under legal hold within Druva.\n    humanURL: https://developer.druva.com\n    baseURL: https://apis.druva.com\n    tags:\n      - Legal Hold\n      - Compliance\n      - eDiscovery\ncommon:\n  - type: Website\n    url: https://www.druva.com\n  - type: Documentation\n    url: https://docs.druva.com/\n\
  \  - type: DeveloperPortal\n    url: https://developer.druva.com\n  - type: APIReference\n    url: https://developer.druva.com/reference\n  - type: Support\n    url: https://support.druva.com\n  - type: GitHub\n    url: https://github.com/druvainc\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/druva/refs/heads/main/apis.yml
tags:
- Backup
- Cyber Resilience
- Data Protection
- Disaster Recovery
- SaaS Backup
url: https://raw.githubusercontent.com/api-evangelist/druva/refs/heads/main/apis.yml
use_cases: []
---
