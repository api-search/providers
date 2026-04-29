---
api_count: 3
api_specs:
- filename: commvault-rest-openapi.yml
  format: yaml
  label: Commvault REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/openapi/commvault-rest-openapi.yml
- filename: commvault-command-center-openapi.yml
  format: yaml
  label: Commvault Command Center API
  slug: command-center-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/openapi/commvault-command-center-openapi.yml
- filename: commvault-automation-openapi.yml
  format: yaml
  label: Commvault Automation API
  slug: automation-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/openapi/commvault-automation-openapi.yml
apis:
- description: The Commvault REST API provides programmatic access to Commvault data protection and management operations including authentication, clients, agents, subclients, backup and restore jobs, schedules, st
  name: Commvault REST API
  slug: rest-api
- description: The Commvault Command Center API exposes the operations behind the modern web-based Command Center UI, providing centralized management, monitoring, dashboards, server group control, and workflow exec
  name: Commvault Command Center API
  slug: command-center-api
- description: The Commvault Automation API provides endpoints for executing Commvault Workflows, managing job scheduling, and orchestrating policy-driven operations across the protected estate. Workflows are reusab
  name: Commvault Automation API
  slug: automation-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://cloud.commvault.com/
- title: ''
  type: Documentation
  url: https://documentation.commvault.com/
- title: ''
  type: Support
  url: https://www.commvault.com/support
- title: ''
  type: Login
  url: https://login.commvault.com/
- title: ''
  type: Status
  url: https://status.commvault.com/
- title: ''
  type: Blog
  url: https://www.commvault.com/blogs
- title: ''
  type: Contact
  url: https://www.commvault.com/contact-us
- title: ''
  type: Privacy Policy
  url: https://www.commvault.com/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.commvault.com/terms-of-use
- title: ''
  type: JSON-LD
  url: json-ld/commvault-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/commvault-backup-job-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/commvault-client-schema.json
created: '2025-01-20'
description: Commvault is a cloud-native cyber resilience platform that delivers unified data security, identity resilience, and cyber recovery. The Commvault REST API, Command Center API, and Automation API provide programmatic access to backup, restore, replication, threat scan, reporting, and orchestration capabilities across enterprise workloads spanning on-premises, virtual machines, and cloud applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Commvault Context
  property_count: 10
  slug: commvault-context
layout: provider
modified: '2026-04-28'
name: Commvault
rules:
- name: Commvault API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: commvault-rules
skills: []
slug: commvault
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: commvault\nname: Commvault\ndescription: >-\n  Commvault is a cloud-native cyber resilience platform that delivers unified\n  data security, identity resilience, and cyber recovery. The Commvault REST API,\n  Command Center API, and Automation API provide programmatic access to backup,\n  restore, replication, threat scan, reporting, and orchestration capabilities\n  across enterprise workloads spanning on-premises, virtual machines, and cloud\n  applications.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/apis.yml\ntags:\n  - Backup\n  - Cloud Storage\n  - Cyber Recovery\n  - Data Management\n  - Data Protection\n  - Disaster Recovery\n  - Enterprise Software\ncreated: '2025-01-20'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nx-type: company\napis:\n  - aid: commvault:rest-api\n    name: Commvault\
  \ REST API\n    description: >-\n      The Commvault REST API provides programmatic access to Commvault data\n      protection and management operations including authentication, clients,\n      agents, subclients, backup and restore jobs, schedules, storage policies,\n      and reporting. Authentication is token-based using a QSDK token issued\n      by the Login operation, sent in the Authtoken header on subsequent calls.\n    image: https://www.commvault.com/wp-content/themes/commvault/assets/images/commvault-logo.svg\n    humanURL: https://documentation.commvault.com/v11/essential/rest_api_overview.html\n    baseURL: https://webserver.commvault.com/webconsole/api\n    tags:\n      - Backup\n      - Clients\n      - Data Management\n      - Jobs\n      - REST API\n      - Restore\n      - Subclients\n    properties:\n      - type: Documentation\n        url: https://documentation.commvault.com/v11/essential/rest_api_overview.html\n      - type: Authentication\n        url: https://documentation.commvault.com/v11/essential/rest_api_authentication.html\n\
  \      - type: Postman Collection\n        url: https://documenter.getpostman.com/view/2046098/RW1aHzQg\n      - type: API Reference\n        url: https://api.commvault.com/swagger/\n      - type: OpenAPI\n        url: openapi/commvault-rest-openapi.yml\n      - type: Spectral Rules\n        url: rules/commvault-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/commvault-backup-management.yml\n    features:\n      - title: Token-based Authentication\n        description: QSDK token authentication via Login/Logout endpoints with token sent in Authtoken header.\n      - title: Client Lifecycle\n        description: Register, retrieve, update, and retire client servers, workstations, and VM proxies.\n      - title: Subclient Management\n        description: Create and configure subclients that define backup content, schedules, and storage policies.\n      - title: Backup and Restore Jobs\n        description: Trigger backups (full, incremental, differential, synthetic\
  \ full) and restore jobs with targeted destinations.\n      - title: Job Monitoring\n        description: List and inspect backup, restore, and administrative jobs with status, progress, and failure details.\n      - title: Storage Policy Management\n        description: Manage storage policies and copies that govern retention, deduplication, and replication.\n      - title: Schedule Policies\n        description: Define schedule policies that automate backup operations across clients.\n      - title: Alerts and Reporting\n        description: Configure alerts and access reporting endpoints for compliance and operational visibility.\n    useCases:\n      - title: Automated Backup Orchestration\n        description: Trigger and monitor backup jobs across thousands of clients from CI/CD or orchestration pipelines.\n      - title: Disaster Recovery\n        description: Initiate restore operations to alternate destinations as part of disaster recovery runbooks.\n      - title: Cyber Recovery\n\
  \        description: Integrate with SOC tooling to recover clean copies of data after a ransomware event.\n      - title: Compliance Reporting\n        description: Pull job and storage data into governance dashboards for retention and SLA reporting.\n  - aid: commvault:command-center-api\n    name: Commvault Command Center API\n    description: >-\n      The Commvault Command Center API exposes the operations behind the\n      modern web-based Command Center UI, providing centralized management,\n      monitoring, dashboards, server group control, and workflow execution\n      for Commvault environments.\n    humanURL: https://documentation.commvault.com/2024/essential/command_center_overview.html\n    baseURL: https://commandcenter.commvault.com/commandcenter/api\n    tags:\n      - Command Center\n      - Dashboards\n      - Management\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://documentation.commvault.com/2024/essential/rest_api_command_center.html\n\
  \      - type: API Reference\n        url: https://api.commvault.com/\n      - type: OpenAPI\n        url: openapi/commvault-command-center-openapi.yml\n      - type: Spectral Rules\n        url: rules/commvault-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/commvault-backup-management.yml\n    features:\n      - title: Centralized Dashboards\n        description: Aggregate environment health, job, and storage metrics across CommCells.\n      - title: Server Group Management\n        description: Manage server groups, plans, and policy assignments from a unified surface.\n      - title: Workflow Execution\n        description: Run pre-built and custom workflows for routine operations and approvals.\n    useCases:\n      - title: Multi-CommCell Operations\n        description: Manage data protection across multiple CommCells from a single Command Center.\n      - title: Operational Monitoring\n        description: Surface dashboard data into NOC and observability\
  \ tools.\n  - aid: commvault:automation-api\n    name: Commvault Automation API\n    description: >-\n      The Commvault Automation API provides endpoints for executing Commvault\n      Workflows, managing job scheduling, and orchestrating policy-driven\n      operations across the protected estate. Workflows are reusable\n      automation packages that combine REST calls, decision logic, and\n      approvals.\n    humanURL: https://documentation.commvault.com/v11/essential/automation_overview.html\n    baseURL: https://webserver.commvault.com/webconsole/api\n    tags:\n      - Automation\n      - Orchestration\n      - Scheduling\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://documentation.commvault.com/v11/essential/rest_api_automation.html\n      - type: OpenAPI\n        url: openapi/commvault-automation-openapi.yml\n      - type: Spectral Rules\n        url: rules/commvault-rules.yml\n      - type: Naftiko Capabilities\n        url: capabilities/commvault-backup-management.yml\n\
  \    features:\n      - title: Workflow Execution\n        description: Execute custom and Commvault-shipped Workflows with structured inputs.\n      - title: Job Scheduling\n        description: Programmatically create, update, and remove schedule policies and individual schedules.\n      - title: Policy Management\n        description: Manage storage and schedule policies that govern protection behavior.\n    useCases:\n      - title: Run Books\n        description: Encode operational run books as Workflows triggered by external events.\n      - title: Self-Service Automation\n        description: Expose curated Workflows to tenants and application teams for self-service operations.\ncommon:\n  - type: Portal\n    url: https://cloud.commvault.com/\n  - type: Documentation\n    url: https://documentation.commvault.com/\n  - type: Support\n    url: https://www.commvault.com/support\n  - type: Login\n    url: https://login.commvault.com/\n  - type: Status\n    url: https://status.commvault.com/\n\
  \  - type: Blog\n    url: https://www.commvault.com/blogs\n  - type: Contact\n    url: https://www.commvault.com/contact-us\n  - type: Privacy Policy\n    url: https://www.commvault.com/privacy-policy\n  - type: Terms of Service\n    url: https://www.commvault.com/terms-of-use\n  - type: JSON-LD\n    url: json-ld/commvault-context.jsonld\n  - type: JSONSchema\n    url: json-schema/commvault-backup-job-schema.json\n  - type: JSONSchema\n    url: json-schema/commvault-client-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/apis.yml
tags:
- Backup
- Cloud Storage
- Cyber Recovery
- Data Management
- Data Protection
- Disaster Recovery
- Enterprise Software
url: https://raw.githubusercontent.com/api-evangelist/commvault/refs/heads/main/apis.yml
use_cases: []
---
