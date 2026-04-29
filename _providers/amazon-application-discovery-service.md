---
api_count: 1
apis:
- description: REST API for AWS Application Discovery Service covering agents, applications, configurations, exports, imports, and tags for on-premises infrastructure discovery.
  name: Amazon Application Discovery Service API
  slug: amazon-application-discovery-service-api
capabilities:
- description: Workflow capability for discovering on-premises infrastructure and preparing migration plans using AWS Application Discovery Service.
  name: Migration Discovery Workflow
  slug: migration-discovery
common: []
created: '2026-03-16'
description: Amazon Application Discovery Service helps enterprise customers plan application migration projects by automatically identifying servers, virtual machines, software, and software dependencies running in their on-premises data centers.
features:
- Agentless Discovery via VMware vCenter integration
- Agent-based discovery for physical and virtual servers
- Automatic server dependency mapping via network traffic analysis
- Application grouping and tagging for migration planning
- Data export to Amazon S3 in CSV and GraphML formats
- Bulk import of server inventory via CSV files
- Integration with AWS Migration Hub for centralized tracking
- Continuous data collection with configurable intervals
- Server neighbor discovery for dependency visualization
- Tag-based filtering and organization of discovered assets
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- AWS Migration Hub
- AWS Server Migration Service
- AWS Application Migration Service
- Amazon EC2
- Amazon S3
- VMware vCenter
- AWS Database Migration Service
- AWS CloudFormation
- AWS Systems Manager
- AWS Cost Explorer
jsonld:
- class_count: 69
  name: Amazon Application Discovery Service Context
  property_count: 113
  slug: amazon-application-discovery-service-context
layout: provider
modified: '2026-04-19'
name: Amazon Application Discovery Service
rules:
- name: Amazon Application Discovery Service API Rules
  rule_count: 21
  severity_counts:
    error: 13
    hint: 0
    info: 2
    warn: 6
  slug: amazon-application-discovery-service-spectral-rules
skills: []
slug: amazon-application-discovery-service
solutions: []
source_yaml: "aid: amazon-application-discovery-service\nname: Amazon Application Discovery Service\ndescription: >-\n  Amazon Application Discovery Service helps enterprise customers plan application migration projects by automatically identifying servers, virtual machines, software, and software dependencies running in their on-premises data centers.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Amazon Application Discovery Service\n  - Migration\n  - Discovery\n  - Infrastructure\n  - AWS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-application-discovery-service:amazon-application-discovery-service-api\n    name: Amazon Application Discovery Service API\n    description: >-\n      REST API for AWS Application Discovery Service covering agents, applications,\
  \ configurations, exports, imports, and tags for on-premises infrastructure discovery.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.aws.amazon.com/application-discovery/latest/APIReference/Welcome.html\n    baseURL: https://discovery.us-east-1.amazonaws.com\n    tags:\n      - Amazon Application Discovery Service\n      - Migration\n      - Discovery\n      - Infrastructure\n      - AWS\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/openapi/amazon-application-discovery-service-openapi.yml\n      - type: SpectralRules\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/rules/amazon-application-discovery-service-spectral-rules.yml\n      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/capabilities/shared/application-discovery-service-api.yaml\n\
  \      - type: NaftikoCapability\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/capabilities/migration-discovery.yaml\n      - type: Vocabulary\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/vocabulary/amazon-application-discovery-service-vocabulary.yaml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/json-schema/application-discovery-service-agent-info-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/json-schema/application-discovery-service-configuration-tag-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/json-schema/application-discovery-service-export-task-schema.json\n\
  \      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/json-schema/application-discovery-service-import-task-schema.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/json-structure/application-discovery-service-agent-info-structure.json\n      - type: JSONStructure\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/json-structure/application-discovery-service-export-task-structure.json\n      - type: JSONLD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/json-ld/amazon-application-discovery-service-context.jsonld\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/examples/application-discovery-service-agent-info-example.json\n\
  \      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/examples/application-discovery-service-export-task-example.json\n      - type: Example\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/examples/application-discovery-service-import-task-example.json\ncommon:\n  - type: Features\n    data:\n      - Agentless Discovery via VMware vCenter integration\n      - Agent-based discovery for physical and virtual servers\n      - Automatic server dependency mapping via network traffic analysis\n      - Application grouping and tagging for migration planning\n      - Data export to Amazon S3 in CSV and GraphML formats\n      - Bulk import of server inventory via CSV files\n      - Integration with AWS Migration Hub for centralized tracking\n      - Continuous data collection with configurable intervals\n      - Server\
  \ neighbor discovery for dependency visualization\n      - Tag-based filtering and organization of discovered assets\n  - type: UseCases\n    data:\n      - Discover all servers and processes in on-premises data centers before migration\n      - Map application dependencies to create migration groups and waves\n      - Export inventory data for detailed analysis and migration planning in third-party tools\n      - Import existing server inventory from CMDBs or spreadsheets without installing agents\n      - Track migration readiness across thousands of servers in a single dashboard\n      - Identify unknown servers and shadow IT in large enterprise environments\n  - type: Integrations\n    data:\n      - AWS Migration Hub\n      - AWS Server Migration Service\n      - AWS Application Migration Service\n      - Amazon EC2\n      - Amazon S3\n      - VMware vCenter\n      - AWS Database Migration Service\n      - AWS CloudFormation\n      - AWS Systems Manager\n      - AWS Cost Explorer\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/apis.yml
tags:
- Amazon Application Discovery Service
- Migration
- Discovery
- Infrastructure
- AWS
url: https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/apis.yml
use_cases:
- Discover all servers and processes in on-premises data centers before migration
- Map application dependencies to create migration groups and waves
- Export inventory data for detailed analysis and migration planning in third-party tools
- Import existing server inventory from CMDBs or spreadsheets without installing agents
- Track migration readiness across thousands of servers in a single dashboard
- Identify unknown servers and shadow IT in large enterprise environments
---
