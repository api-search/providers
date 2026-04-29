---
api_count: 1
api_specs:
- filename: agco-agcommand-api-openapi.yml
  format: yaml
  label: AGCO AgCommand API
  slug: agcommand-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agco/refs/heads/main/openapi/agco-agcommand-api-openapi.yml
apis:
- description: The AGCO AgCommand API provides approved third-party developers and service providers with access to machine telemetry data from AGCO equipment. The API enables farming application developers to build
  name: AGCO AgCommand API
  slug: agcommand-api
capabilities:
- description: Unified workflow capability for AGCO precision farming — monitoring machine location, performance telemetry, and operating conditions across a connected fleet. Used by farm managers and precision agri
  name: AGCO Precision Farming
  slug: precision-farming
common:
- title: ''
  type: Portal
  url: https://get.agcoconnect.com/
- title: ''
  type: GettingStarted
  url: https://github.com/agco/agco-json-api-profiles
- title: ''
  type: GitHubOrganization
  url: https://github.com/agco
- title: ''
  type: TermsOfService
  url: https://www.agcocorp.com/legal/privacy-policy.html
- title: ''
  type: JSONSchema
  url: json-schema/agco-location-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/agco-machine-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/agco-telemetry-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/agco-location-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/agco-machine-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/agco-telemetry-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/agco-telematics-context.jsonld
- title: ''
  type: Example
  url: examples/agco-location-example.json
- title: ''
  type: Example
  url: examples/agco-machine-example.json
- title: ''
  type: Example
  url: examples/agco-telemetry-example.json
- title: ''
  type: SpectralRules
  url: rules/agco-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/agco-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/precision-farming.yaml
created: ''
description: AGCO is a global leader in the design, manufacture, and distribution of agricultural machinery and precision ag technology. The AGCO AgCommand API enables approved third-party developers and service providers to access machine telemetry data, location tracking, and performance metrics from AGCO Connect-ready equipment including Fendt, Massey Ferguson, Challenger, and Valtra brands.
features:
- description: Real-time access to machine performance data including engine speed, load, fuel consumption, and fault codes from AGCO Connect-ready equipment.
  name: Machine Telematics
- description: GPS-based machine location history enabling field work tracking and fleet management dashboards.
  name: Fleet Location Tracking
- description: Remote access to machine diagnostic codes enabling proactive maintenance and reducing downtime.
  name: Diagnostic Fault Codes
- description: Standardized filtering, search, and change event profiles for consistent API behavior across all resources.
  name: JSON API Profiles
- description: Single API access to data from Fendt, Massey Ferguson, Challenger, and Valtra agricultural equipment.
  name: Multi-Brand Coverage
image: ''
integrations:
- description: Integration of AGCO telematics data with Procore construction and project management workflows.
  name: Procore
- description: Integration with precision agriculture software platforms for combined field and machine data analysis.
  name: Precision Ag Software
jsonld:
- class_count: 3
  name: Agco Telematics Context
  property_count: 24
  slug: agco-telematics-context
layout: provider
modified: '2026-04-19'
name: agco
rules:
- name: agco API Rules
  rule_count: 24
  severity_counts:
    error: 14
    hint: 0
    info: 0
    warn: 10
  slug: agco-spectral-rules
skills: []
slug: agco
solutions: []
source_filename: apis.yml
source_yaml: "aid: agco\nurl: https://raw.githubusercontent.com/api-evangelist/agco/refs/heads/main/apis.yml\napis:\n- aid: agco:agcommand-api\n  name: AGCO AgCommand API\n  tags:\n  - Agriculture\n  - Farm Equipment\n  - IoT\n  - Precision Farming\n  - Telematics\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  baseURL: https://api.agcocorp.com\n  humanURL: https://get.agcoconnect.com/\n  properties:\n  - url: https://get.agcoconnect.com/\n    type: Portal\n  - url: https://github.com/agco/agco-json-api-profiles\n    type: Documentation\n  - url: openapi/agco-agcommand-api-openapi.yml\n    type: OpenAPI\n  description: >-\n    The AGCO AgCommand API provides approved third-party developers and service\n    providers with access to machine telemetry data from AGCO equipment. The\n    API enables farming application developers to build management dashboards\n    and mobile apps that access real-time machine data including location,\n    performance metrics,\
  \ and diagnostic information from AGCO Connect-ready\n    machines. AGCO uses JSON API profiles for standardized filtering, search,\n    and change events.\ndescription: >-\n  AGCO is a global leader in the design, manufacture, and distribution of agricultural machinery and precision ag technology. The AGCO AgCommand API enables approved third-party developers and service providers\n  to access machine telemetry data, location tracking, and performance metrics from AGCO Connect-ready equipment including Fendt, Massey Ferguson, Challenger, and Valtra brands.\nmodified: '2026-04-19'\ncommon:\n- type: Portal\n  url: https://get.agcoconnect.com/\n- type: GettingStarted\n  url: https://github.com/agco/agco-json-api-profiles\n- type: GitHubOrganization\n  url: https://github.com/agco\n- type: TermsOfService\n  url: https://www.agcocorp.com/legal/privacy-policy.html\n- type: Features\n  data:\n  - name: Machine Telematics\n    description: Real-time access to machine performance data including\
  \ engine speed, load, fuel consumption, and fault codes from AGCO Connect-ready equipment.\n  - name: Fleet Location Tracking\n    description: GPS-based machine location history enabling field work tracking and fleet management dashboards.\n  - name: Diagnostic Fault Codes\n    description: Remote access to machine diagnostic codes enabling proactive maintenance and reducing downtime.\n  - name: JSON API Profiles\n    description: Standardized filtering, search, and change event profiles for consistent API behavior across all resources.\n  - name: Multi-Brand Coverage\n    description: Single API access to data from Fendt, Massey Ferguson, Challenger, and Valtra agricultural equipment.\n- type: UseCases\n  data:\n  - name: Farm Management Dashboard\n    description: Build web and mobile dashboards that display real-time machine location, performance, and fuel status for farm operators.\n  - name: Predictive Maintenance\n    description: Monitor machine fault codes and engine hours remotely\
  \ to schedule preventive maintenance before failures occur.\n  - name: Field Work Tracking\n    description: Track machine location and activity data to document field operations, coverage areas, and productivity metrics.\n  - name: Fuel Management\n    description: Monitor fuel levels and consumption rates across a fleet to optimize refueling logistics and reduce costs.\n  - name: Telematics Integration\n    description: Integrate AGCO machine data into existing farm management or precision agriculture software platforms.\n- type: Integrations\n  data:\n  - name: Procore\n    description: Integration of AGCO telematics data with Procore construction and project management workflows.\n  - name: Precision Ag Software\n    description: Integration with precision agriculture software platforms for combined field and machine data analysis.\n- type: JSONSchema\n  url: json-schema/agco-location-schema.json\n- type: JSONSchema\n  url: json-schema/agco-machine-schema.json\n- type: JSONSchema\n\
  \  url: json-schema/agco-telemetry-schema.json\n- type: JSONStructure\n  url: json-structure/agco-location-structure.json\n- type: JSONStructure\n  url: json-structure/agco-machine-structure.json\n- type: JSONStructure\n  url: json-structure/agco-telemetry-structure.json\n- type: JSON-LD\n  url: json-ld/agco-telematics-context.jsonld\n- type: Example\n  url: examples/agco-location-example.json\n- type: Example\n  url: examples/agco-machine-example.json\n- type: Example\n  url: examples/agco-telemetry-example.json\n- type: SpectralRules\n  url: rules/agco-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/agco-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/precision-farming.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/agco/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/agco/refs/heads/main/apis.yml
use_cases:
- description: Build web and mobile dashboards that display real-time machine location, performance, and fuel status for farm operators.
  name: Farm Management Dashboard
- description: Monitor machine fault codes and engine hours remotely to schedule preventive maintenance before failures occur.
  name: Predictive Maintenance
- description: Track machine location and activity data to document field operations, coverage areas, and productivity metrics.
  name: Field Work Tracking
- description: Monitor fuel levels and consumption rates across a fleet to optimize refueling logistics and reduce costs.
  name: Fuel Management
- description: Integrate AGCO machine data into existing farm management or precision agriculture software platforms.
  name: Telematics Integration
---
