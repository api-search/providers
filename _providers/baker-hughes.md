---
api_count: 2
apis:
- description: Cordant is Baker Hughes' modular AI-enabled industrial enterprise software platform for asset performance management (APM), process optimization, and emissions management. It provides a digital thread
  name: Baker Hughes Cordant Industrial Platform
  slug: cordant-platform
- description: The BHC3 AI Suite is a joint product from Baker Hughes and C3.ai providing pre-built, configurable AI applications for the energy industry. Applications cover predictive maintenance, reliability, prod
  name: Baker Hughes BHC3 AI Suite
  slug: bhc3-ai-suite
capabilities:
- description: ''
  name: Baker Hughes Industrial Platform
  slug: baker-hughes-industrial-platform
common:
- title: ''
  type: Website
  url: https://www.bakerhughes.com
- title: ''
  type: Portal
  url: https://www.bakerhughes.com/company/digital
- title: ''
  type: Blog
  url: https://www.bakerhughes.com/company/news
- title: ''
  type: Support
  url: https://www.bakerhughes.com/contact-us
- title: ''
  type: PrivacyPolicy
  url: https://www.bakerhughes.com/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.bakerhughes.com/terms-and-conditions
- title: ''
  type: SpectralRules
  url: rules/baker-hughes-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/baker-hughes-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/baker-hughes-industrial-platform.yaml
- title: ''
  type: JSON-LD
  url: json-ld/baker-hughes-context.jsonld
created: '2026-03-21'
description: Baker Hughes is an energy technology company providing solutions to energy and industrial customers worldwide. Their digital portfolio includes the Cordant industrial software platform for asset performance management, process optimization, and emissions management, along with the BHC3 AI Suite (in alliance with C3.ai) for enterprise AI applications in oil and gas. Baker Hughes operates across oilfield services, industrial equipment, and digital solutions segments globally.
features:
- description: AI-powered predictive maintenance and reliability for industrial assets.
  name: Asset Performance Management
- description: Real-time process monitoring and optimization for energy and industrial operations.
  name: Process Optimization
- description: Track, measure, and reduce greenhouse gas emissions across operations.
  name: Emissions Management
- description: Pre-built AI applications for oil and gas use cases including production optimization and well integrity.
  name: Enterprise AI Applications
- description: Connectivity between operational technology (OT) sensor data and enterprise IT systems.
  name: OT/IT Integration
- description: Connected data fabric linking assets, processes, and enterprise systems across operations.
  name: Digital Thread
- description: Continuous monitoring of well barrier status and integrity for safe operations.
  name: Well Integrity Monitoring
- description: AI-driven optimization of oil and gas production rates from well and reservoir data.
  name: Production Optimization
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: BHC3 AI Suite is optimized to run on Microsoft Azure cloud infrastructure.
  name: Microsoft Azure
- description: Strategic AI alliance providing enterprise AI platform capabilities for BHC3.
  name: C3.ai
- description: Integration with SAP ERP for asset and maintenance management data.
  name: SAP
- description: Integration with OSIsoft PI data historian for real-time process data.
  name: OSIsoft PI
- description: Integration with IBM Maximo asset management for work order lifecycle.
  name: Maximo
- description: Integration with Honeywell process control and DCS systems.
  name: Honeywell
jsonld:
- class_count: 0
  name: Baker Hughes Context
  property_count: 25
  slug: baker-hughes-context
layout: provider
modified: '2026-04-21'
name: Baker Hughes
rules:
- name: Baker Hughes API Rules
  rule_count: 15
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 10
  slug: baker-hughes-spectral-rules
skills: []
slug: baker-hughes
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: baker-hughes\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/baker-hughes/refs/heads/main/apis.yml\nname: Baker Hughes\ndescription: >-\n  Baker Hughes is an energy technology company providing solutions to energy and industrial\n  customers worldwide. Their digital portfolio includes the Cordant industrial software\n  platform for asset performance management, process optimization, and emissions management,\n  along with the BHC3 AI Suite (in alliance with C3.ai) for enterprise AI applications in oil\n  and gas. Baker Hughes operates across oilfield services, industrial equipment, and digital\n  solutions segments globally.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Energy Technology\n  - Industrial IoT\n  - Oil And Gas\n  - Asset Performance Management\n  - Digital Energy\ncreated: '2026-03-21'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\napis:\n  - aid: baker-hughes:cordant-platform\n\
  \    name: Baker Hughes Cordant Industrial Platform\n    description: >-\n      Cordant is Baker Hughes' modular AI-enabled industrial enterprise software platform for\n      asset performance management (APM), process optimization, and emissions management.\n      It provides a digital thread across energy and industrial operations, connecting data,\n      automating decision-making, and delivering predictive insights. Cordant offers APIs for\n      integration with existing enterprise systems including OT/IT connectivity for asset data.\n    humanURL: https://www.bakerhughes.com/cordant\n    tags:\n      - Asset Performance Management\n      - Industrial IoT\n      - Process Optimization\n      - Emissions Management\n    properties:\n      - type: Documentation\n        url: https://www.bakerhughes.com/cordant/platform\n      - type: APIReference\n        url: https://www.bakerhughes.com/cordant\n  - aid: baker-hughes:bhc3-ai-suite\n    name: Baker Hughes BHC3 AI Suite\n    description:\
  \ >-\n      The BHC3 AI Suite is a joint product from Baker Hughes and C3.ai providing pre-built,\n      configurable AI applications for the energy industry. Applications cover predictive\n      maintenance, reliability, production optimization, inventory optimization, well placement,\n      well integrity, and yield optimization. The platform runs on Microsoft Azure and uses\n      C3.ai's model-driven architecture enabling enterprise AI application development.\n    humanURL: https://www.bakerhughes.com/bhc3\n    tags:\n      - Artificial Intelligence\n      - Energy\n      - Oil And Gas\n      - Predictive Maintenance\n    properties:\n      - type: Documentation\n        url: https://www.bakerhughes.com/bhc3\n      - type: APIReference\n        url: https://www.bakerhughes.com/ai-bakerhughesc3ai/\ncommon:\n  - type: Website\n    url: https://www.bakerhughes.com\n  - type: Portal\n    url: https://www.bakerhughes.com/company/digital\n  - type: Blog\n    url: https://www.bakerhughes.com/company/news\n\
  \  - type: Support\n    url: https://www.bakerhughes.com/contact-us\n  - type: PrivacyPolicy\n    url: https://www.bakerhughes.com/privacy-policy\n  - type: TermsOfService\n    url: https://www.bakerhughes.com/terms-and-conditions\n  - type: SpectralRules\n    url: rules/baker-hughes-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/baker-hughes-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/baker-hughes-industrial-platform.yaml\n  - type: JSON-LD\n    url: json-ld/baker-hughes-context.jsonld\n  - name: Features\n    type: Features\n    data:\n      - name: Asset Performance Management\n        description: AI-powered predictive maintenance and reliability for industrial assets.\n      - name: Process Optimization\n        description: Real-time process monitoring and optimization for energy and industrial operations.\n      - name: Emissions Management\n        description: Track, measure, and reduce greenhouse gas emissions across operations.\n      -\
  \ name: Enterprise AI Applications\n        description: Pre-built AI applications for oil and gas use cases including production optimization and well integrity.\n      - name: OT/IT Integration\n        description: Connectivity between operational technology (OT) sensor data and enterprise IT systems.\n      - name: Digital Thread\n        description: Connected data fabric linking assets, processes, and enterprise systems across operations.\n      - name: Well Integrity Monitoring\n        description: Continuous monitoring of well barrier status and integrity for safe operations.\n      - name: Production Optimization\n        description: AI-driven optimization of oil and gas production rates from well and reservoir data.\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Predictive Maintenance\n        description: Predict equipment failures before they occur to reduce unplanned downtime and maintenance costs.\n      - name: Production Optimization\n        description:\
  \ Optimize oil and gas production rates using AI-driven insights from well and reservoir data.\n      - name: Sustainability Reporting\n        description: Monitor and report on emissions, energy consumption, and ESG metrics across facilities.\n      - name: Industrial Process Control\n        description: Automate and optimize industrial processes using real-time sensor data and AI recommendations.\n      - name: Well Lifecycle Management\n        description: Monitor and optimize oil and gas well performance across the full production lifecycle.\n      - name: Inventory Optimization\n        description: Optimize spare parts inventory for maintenance operations using AI demand forecasting.\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: Microsoft Azure\n        description: BHC3 AI Suite is optimized to run on Microsoft Azure cloud infrastructure.\n      - name: C3.ai\n        description: Strategic AI alliance providing enterprise AI platform capabilities\
  \ for BHC3.\n      - name: SAP\n        description: Integration with SAP ERP for asset and maintenance management data.\n      - name: OSIsoft PI\n        description: Integration with OSIsoft PI data historian for real-time process data.\n      - name: Maximo\n        description: Integration with IBM Maximo asset management for work order lifecycle.\n      - name: Honeywell\n        description: Integration with Honeywell process control and DCS systems.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/baker-hughes/refs/heads/main/apis.yml
tags:
- Energy Technology
- Industrial IoT
- Oil And Gas
- Asset Performance Management
- Digital Energy
url: https://raw.githubusercontent.com/api-evangelist/baker-hughes/refs/heads/main/apis.yml
use_cases:
- description: Predict equipment failures before they occur to reduce unplanned downtime and maintenance costs.
  name: Predictive Maintenance
- description: Optimize oil and gas production rates using AI-driven insights from well and reservoir data.
  name: Production Optimization
- description: Monitor and report on emissions, energy consumption, and ESG metrics across facilities.
  name: Sustainability Reporting
- description: Automate and optimize industrial processes using real-time sensor data and AI recommendations.
  name: Industrial Process Control
- description: Monitor and optimize oil and gas well performance across the full production lifecycle.
  name: Well Lifecycle Management
- description: Optimize spare parts inventory for maintenance operations using AI demand forecasting.
  name: Inventory Optimization
---
