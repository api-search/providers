---
api_count: 3
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
