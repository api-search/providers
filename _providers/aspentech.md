---
api_count: 3
api_specs:
- filename: aspentech-inmation-web-openapi.yml
  format: yaml
  label: AspenTech Inmation Web API
  slug: inmation-web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aspentech/refs/heads/main/openapi/aspentech-inmation-web-openapi.yml
apis:
- description: The AspenTech Inmation Web API provides HTTP and WebSocket interfaces for external applications to interact with AspenTech Inmation industrial IoT and time-series data platforms. RPC-based REST APIs e
  name: AspenTech Inmation Web API
  slug: inmation-web-api
- description: 'AspenTech provides process optimization and simulation software for energy, chemicals, and manufacturing industries. The aspenONE platform APIs enable access to process simulation models, performance '
  name: AspenTech aspenONE API
  slug: aspenone-api
- description: The AspenTech Inmation Simple Call Interface (SCI) API provides a simplified HTTP interface for communicating with the Inmation industrial data platform. Designed for straightforward read/write access
  name: AspenTech Inmation Simple Call Interface (SCI) API
  slug: inmation-sci-api
common:
- title: AspenTech Website
  type: Portal
  url: https://www.aspentech.com/
- title: Developer Knowledge Center
  type: Portal
  url: https://dev.knowledgecenter.aspentech.com/
- title: Documentation
  type: Documentation
  url: https://dev.knowledgecenter.aspentech.com/
- title: Getting Started Guides
  type: GettingStarted
  url: https://www.aspentech.com/en/getting-started-guides
- title: Technical Support
  type: Support
  url: https://esupport.aspentech.com/
- title: Inmation Web API OpenAPI
  type: OpenAPI
  url: openapi/aspentech-inmation-web-openapi.yml
- title: Data Item JSON Schema
  type: JSONSchema
  url: json-schema/aspentech-dataitem-schema.json
- title: AspenTech JSON-LD Context
  type: JSONLD
  url: json-ld/aspentech-context.jsonld
created: '2024-01-15'
description: AspenTech (Aspen Technology, Inc.) is a global leader in industrial software for asset optimization across the energy, chemicals, and manufacturing industries. AspenTech provides process simulation, optimization, and industrial IoT platforms including the aspenONE suite and Inmation industrial data platform. The Inmation platform provides Web API and Simple Call Interface (SCI) APIs for external applications to interact with industrial IoT and time-series process data via HTTP and WebSocket interfaces. AspenTech serves refineries, petrochemical plants, power generation facilities, and other industrial operations worldwide.
features:
- description: The Inmation platform provides industrial-grade time-series data management, process data connectivity, and real-time analytics for manufacturing and energy operations.
  name: Inmation Industrial IoT Platform
- description: aspenONE suite provides high-fidelity process simulation for design, optimization, and operational decision support in chemical plants, refineries, and energy facilities.
  name: Process Simulation
- description: WebSocket interface in the Inmation Web API enables real-time streaming of process data, alarm states, and operational events to external applications.
  name: WebSocket Real-Time Data
- description: Tools for monitoring asset health, predicting maintenance needs, and optimizing equipment performance across industrial operations.
  name: Asset Performance Management
- description: APIs for integrating AI and machine learning models with process data to enable predictive analytics and autonomous optimization.
  name: AI/ML Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: AspenTech integrates with OSIsoft PI (now AVEVA PI) for process data historian connectivity and operational data access.
  name: OSIsoft PI System
- description: Enterprise integration with SAP ERP systems for maintenance, production, and procurement data exchange.
  name: SAP
- description: Integration with AVEVA engineering and operations management platforms for plant lifecycle data management.
  name: AVEVA
jsonld:
- class_count: 0
  name: Aspentech Context
  property_count: 3
  slug: aspentech-context
layout: provider
modified: '2026-04-19'
name: AspenTech
skills: []
slug: aspentech
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: aspentech\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/aspentech/refs/heads/main/apis.yml\nname: AspenTech\ndescription: >-\n  AspenTech (Aspen Technology, Inc.) is a global leader in industrial software\n  for asset optimization across the energy, chemicals, and manufacturing industries.\n  AspenTech provides process simulation, optimization, and industrial IoT platforms\n  including the aspenONE suite and Inmation industrial data platform. The Inmation\n  platform provides Web API and Simple Call Interface (SCI) APIs for external\n  applications to interact with industrial IoT and time-series process data via HTTP\n  and WebSocket interfaces. AspenTech serves refineries, petrochemical plants, power\n  generation facilities, and other industrial operations worldwide.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Industrial IoT\n  - Process Optimization\n  - Manufacturing\n  - Energy\n  - Chemicals\n\
  \  - Time Series\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: aspentech:inmation-web-api\n    name: AspenTech Inmation Web API\n    description: >-\n      The AspenTech Inmation Web API provides HTTP and WebSocket interfaces for\n      external applications to interact with AspenTech Inmation industrial IoT\n      and time-series data platforms. RPC-based REST APIs enable access to process\n      data, system services, and automation functions for manufacturing and energy\n      operations.\n    humanURL: https://atdocs.inmation.com/api/1.108/webapi/index.html\n    baseURL: http://hostname:8002\n    tags:\n      - Industrial IoT\n      - Manufacturing\n      - Process Optimization\n      - REST\n      - Time Series\n      - WebSocket\n    properties:\n      - type: Documentation\n        url: https://atdocs.inmation.com/api/1.108/webapi/index.html\n      - type: OpenAPI\n        url: openapi/aspentech-inmation-web-openapi.yml\n      - type:\
  \ JSONSchema\n        url: json-schema/aspentech-dataitem-schema.json\n  - aid: aspentech:aspenone-api\n    name: AspenTech aspenONE API\n    description: >-\n      AspenTech provides process optimization and simulation software for energy,\n      chemicals, and manufacturing industries. The aspenONE platform APIs enable\n      access to process simulation models, performance monitoring, and optimization\n      data for AI-driven operational workflows.\n    humanURL: https://www.aspentech.com/\n    baseURL: https://api.aspentech.com\n    tags:\n      - Energy\n      - Manufacturing\n      - Process Engineering\n      - Process Optimization\n      - Simulation\n    properties:\n      - type: GettingStarted\n        url: https://www.aspentech.com/en/getting-started-guides\n      - type: Documentation\n        url: https://dev.knowledgecenter.aspentech.com/\n  - aid: aspentech:inmation-sci-api\n    name: AspenTech Inmation Simple Call Interface (SCI) API\n    description: >-\n      The AspenTech\
  \ Inmation Simple Call Interface (SCI) API provides a simplified\n      HTTP interface for communicating with the Inmation industrial data platform.\n      Designed for straightforward read/write access to process data and configuration\n      items in manufacturing and energy environments.\n    humanURL: https://atdocs.inmation.com/api/1.102/sci/index.html\n    baseURL: http://hostname:8002\n    tags:\n      - Industrial IoT\n      - Manufacturing\n      - Process Optimization\n      - REST\n    properties:\n      - type: Documentation\n        url: https://atdocs.inmation.com/api/1.102/sci/index.html\ncommon:\n  - type: Portal\n    url: https://www.aspentech.com/\n    title: AspenTech Website\n  - type: Portal\n    url: https://dev.knowledgecenter.aspentech.com/\n    title: Developer Knowledge Center\n  - type: Documentation\n    url: https://dev.knowledgecenter.aspentech.com/\n    title: Documentation\n  - type: GettingStarted\n    url: https://www.aspentech.com/en/getting-started-guides\n\
  \    title: Getting Started Guides\n  - type: Support\n    url: https://esupport.aspentech.com/\n    title: Technical Support\n  - type: OpenAPI\n    url: openapi/aspentech-inmation-web-openapi.yml\n    title: Inmation Web API OpenAPI\n  - type: JSONSchema\n    url: json-schema/aspentech-dataitem-schema.json\n    title: Data Item JSON Schema\n  - type: JSONLD\n    url: json-ld/aspentech-context.jsonld\n    title: AspenTech JSON-LD Context\n  - type: Features\n    data:\n      - name: Inmation Industrial IoT Platform\n        description: >-\n          The Inmation platform provides industrial-grade time-series data\n          management, process data connectivity, and real-time analytics for\n          manufacturing and energy operations.\n      - name: Process Simulation\n        description: >-\n          aspenONE suite provides high-fidelity process simulation for design,\n          optimization, and operational decision support in chemical plants,\n          refineries, and energy\
  \ facilities.\n      - name: WebSocket Real-Time Data\n        description: >-\n          WebSocket interface in the Inmation Web API enables real-time streaming\n          of process data, alarm states, and operational events to external applications.\n      - name: Asset Performance Management\n        description: >-\n          Tools for monitoring asset health, predicting maintenance needs, and\n          optimizing equipment performance across industrial operations.\n      - name: AI/ML Integration\n        description: >-\n          APIs for integrating AI and machine learning models with process data\n          to enable predictive analytics and autonomous optimization.\n  - type: UseCases\n    data:\n      - name: Process Data Integration\n        description: >-\n          Operations technology teams integrate the Inmation Web API with business\n          intelligence tools, historian systems, and enterprise applications to\n          access real-time and historical process data.\n\
  \      - name: Digital Twin Development\n        description: >-\n          Engineering teams use aspenONE simulation APIs to build digital twins\n          of process plants for operations optimization and scenario analysis.\n      - name: Alarm Management\n        description: >-\n          Control systems engineers use the Inmation API to build custom alarm\n          management dashboards and analytics for industrial operations.\n      - name: Energy Optimization\n        description: >-\n          Refineries and petrochemical plants use AspenTech APIs to connect\n          optimization models with real-time operations for energy efficiency.\n  - type: Integrations\n    data:\n      - name: OSIsoft PI System\n        description: >-\n          AspenTech integrates with OSIsoft PI (now AVEVA PI) for process data\n          historian connectivity and operational data access.\n      - name: SAP\n        description: >-\n          Enterprise integration with SAP ERP systems for maintenance,\
  \ production,\n          and procurement data exchange.\n      - name: AVEVA\n        description: >-\n          Integration with AVEVA engineering and operations management platforms\n          for plant lifecycle data management.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aspentech/refs/heads/main/apis.yml
tags:
- Industrial IoT
- Process Optimization
- Manufacturing
- Energy
- Chemicals
- Time Series
url: https://raw.githubusercontent.com/api-evangelist/aspentech/refs/heads/main/apis.yml
use_cases:
- description: Operations technology teams integrate the Inmation Web API with business intelligence tools, historian systems, and enterprise applications to access real-time and historical process data.
  name: Process Data Integration
- description: Engineering teams use aspenONE simulation APIs to build digital twins of process plants for operations optimization and scenario analysis.
  name: Digital Twin Development
- description: Control systems engineers use the Inmation API to build custom alarm management dashboards and analytics for industrial operations.
  name: Alarm Management
- description: Refineries and petrochemical plants use AspenTech APIs to connect optimization models with real-time operations for energy efficiency.
  name: Energy Optimization
---
