---
api_count: 1
api_specs:
- filename: amazon-iot-twinmaker-openapi-original.yml
  format: yaml
  label: AWS IoT TwinMaker API
  slug: aws-iot-twinmaker-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-twinmaker/refs/heads/main/openapi/amazon-iot-twinmaker-openapi-original.yml
apis:
- description: The AWS IoT TwinMaker API provides access to workspaces, scenes, entities, components, and sync jobs for building and managing digital twin applications.
  name: AWS IoT TwinMaker API
  slug: aws-iot-twinmaker-api
capabilities:
- description: Unified capability for Solutions Architect, Industrial Engineer to manage create digital twins of physical systems and environments operations.
  name: Amazon IoT TwinMaker - Digital Twin Management
  slug: digital-twin-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/iot-twinmaker/
- title: ''
  type: Website
  url: https://aws.amazon.com/iot-twinmaker/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/iot-twinmaker/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/iot/tag/aws-iot-twinmaker/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/iottwinmaker/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-iot-twinmaker-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/iot-twinmaker.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/digital-twin-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-iot-twinmaker-vocabulary.yaml
- title: ''
  type: JSONLD
  url: json-ld/amazon-iot-twinmaker-context.jsonld
created: '2026-03-16'
description: AWS IoT TwinMaker makes it easier for developers to create digital twins of real-world systems such as buildings, factories, and industrial equipment. You can use AWS IoT TwinMaker to build operational digital twin applications to visualize, monitor, and diagnose complex operational systems.
features:
- description: Model physical systems as entities with components and property relationships.
  name: Digital Twin Modeling
- description: Build interactive 3D visualization scenes connected to live IoT data.
  name: 3D Scene Integration
- description: Connect to existing data sources with built-in and custom data connectors.
  name: Data Connectors
- description: Explore entity relationships and property graphs for complex systems.
  name: Knowledge Graph
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Connects SiteWise asset data to TwinMaker entity components.
  name: AWS IoT SiteWise
- description: Visualizes TwinMaker data in Grafana dashboards.
  name: Amazon Grafana
- description: Receives real-time device data for digital twin updates.
  name: AWS IoT Core
jsonld:
- class_count: 102
  name: Amazon Iot Twinmaker Context
  property_count: 137
  slug: amazon-iot-twinmaker-context
layout: provider
modified: '2026-04-19'
name: Amazon IoT TwinMaker
rules:
- name: Amazon IoT TwinMaker API Rules
  rule_count: 14
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 5
  slug: amazon-iot-twinmaker-spectral-rules
skills: []
slug: amazon-iot-twinmaker
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-iot-twinmaker\nname: Amazon IoT TwinMaker\ndescription: >-\n  AWS IoT TwinMaker makes it easier for developers to create digital twins of real-world systems such as buildings, factories, and industrial equipment. You can use AWS IoT TwinMaker to build operational digital twin applications to visualize, monitor, and diagnose complex operational systems.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - 3D Visualization\n  - Digital Twin\n  - Industrial IoT\n  - IoT\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-iot-twinmaker/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-iot-twinmaker:aws-iot-twinmaker-api\n    name: AWS IoT TwinMaker API\n    description: >-\n      The AWS IoT TwinMaker API provides access to workspaces, scenes, entities, components, and sync jobs for building and managing digital twin\
  \ applications.\n    humanURL: https://aws.amazon.com/iot-twinmaker/\n    baseURL: https://iottwinmaker.amazonaws.com\n    tags:\n      - 3D Visualization\n      - Digital Twin\n      - IoT\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/iot-twinmaker/latest/apireference/\n      - type: OpenAPI\n        url: openapi/amazon-iot-twinmaker-openapi-original.yml\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/iot-twinmaker/latest/guide/twinmaker-gs.html\n      - type: Pricing\n        url: https://aws.amazon.com/iot-twinmaker/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/iot-twinmaker/faqs/\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/iot-twinmaker/\n  - type: Website\n    url: https://aws.amazon.com/iot-twinmaker/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/iot-twinmaker/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n   \
  \ url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/iot/tag/aws-iot-twinmaker/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/iottwinmaker/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-iot-twinmaker-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/shared/iot-twinmaker.yaml\n  - type: NaftikoCapability\n    url: capabilities/digital-twin-management.yaml\n  - type: Vocabulary\n    url: vocabulary/amazon-iot-twinmaker-vocabulary.yaml\n  - type: JSONLD\n    url: json-ld/amazon-iot-twinmaker-context.jsonld\n  - type:\
  \ Features\n    data:\n      - name: Digital Twin Modeling\n        description: Model physical systems as entities with components and property relationships.\n      - name: 3D Scene Integration\n        description: Build interactive 3D visualization scenes connected to live IoT data.\n      - name: Data Connectors\n        description: Connect to existing data sources with built-in and custom data connectors.\n      - name: Knowledge Graph\n        description: Explore entity relationships and property graphs for complex systems.\n  - type: UseCases\n    data:\n      - name: Smart Building Management\n        description: Create digital twins of buildings for energy optimization and maintenance.\n      - name: Factory Digital Twin\n        description: Visualize production lines and equipment in 3D for operators.\n      - name: Remote Operations\n        description: Enable remote monitoring and diagnosis of industrial equipment.\n  - type: Integrations\n    data:\n      - name: AWS\
  \ IoT SiteWise\n        description: Connects SiteWise asset data to TwinMaker entity components.\n      - name: Amazon Grafana\n        description: Visualizes TwinMaker data in Grafana dashboards.\n      - name: AWS IoT Core\n        description: Receives real-time device data for digital twin updates.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-twinmaker/refs/heads/main/apis.yml
tags:
- 3D Visualization
- Digital Twin
- Industrial IoT
- IoT
url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-twinmaker/refs/heads/main/apis.yml
use_cases:
- description: Create digital twins of buildings for energy optimization and maintenance.
  name: Smart Building Management
- description: Visualize production lines and equipment in 3D for operators.
  name: Factory Digital Twin
- description: Enable remote monitoring and diagnosis of industrial equipment.
  name: Remote Operations
---
