---
api_count: 11
api_specs:
- filename: trimble-connect-openapi.yml
  format: yaml
  label: Trimble Connect API
  slug: trimble-connect
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trimble/refs/heads/main/openapi/trimble-connect-openapi.yml
- filename: trimble-maps-openapi.yml
  format: yaml
  label: Trimble Maps API
  slug: trimble-maps
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trimble/refs/heads/main/openapi/trimble-maps-openapi.yml
apis:
- description: The Trimble Connect API enables integration with Trimble's cloud-based construction collaboration platform. Provides access to project data, BIM models, document management, issues (BCF Topics), and t
  name: Trimble Connect API
  slug: trimble-connect
- description: The Trimble Maps API (formerly ALK Technologies PC*MILER) provides interactive mapping and routing solutions optimized for commercial vehicles and transportation. Enables truck-specific routing, geoco
  name: Trimble Maps API
  slug: trimble-maps
- description: PC*MILER provides commercial vehicle routing and distance calculation APIs for logistics, freight, and transportation management. Delivers mileage, routing, tolls, and fuel optimization for trucking o
  name: Trimble PC*MILER API
  slug: trimble-pcmiler
- description: The Tekla API provides programmatic access to Tekla Structures, a leading Building Information Modeling (BIM) software for structural engineering and detailing. Enables custom model creation, data ext
  name: Tekla API
  slug: trimble-tekla
- description: The SketchUp API enables extension development for Trimble SketchUp, a widely-used 3D modeling and design tool. Supports Ruby and JavaScript APIs for building custom tools, plugins, and integrations f
  name: SketchUp API
  slug: trimble-sketchup
- description: The Trimble ProjectSight API provides portfolio and project information management for construction. Enables programmatic access to project data, submittals, RFIs, and document workflows for construct
  name: ProjectSight API
  slug: trimble-projectsight
- description: 'The TruckMate REST API provides transactional and configuration operations for Trimble''s transportation management system (TMS). Enables freight brokers, carriers, and logistics operators to automate '
  name: TruckMate API
  slug: trimble-truckmate
- description: The Trimble CoPilot Navigation API enables in-cab navigation integration with cloud-based services for commercial vehicle fleets. Provides route delivery, real-time traffic, and truck-specific navigat
  name: CoPilot Navigation API
  slug: trimble-copilot
- description: The TMT (Trimble Maintenance Technology) REST API provides fleet maintenance management operations for commercial vehicle fleets. Enables work order management, preventive maintenance scheduling, part
  name: TMT Fleet Maintenance API
  slug: trimble-tmt
- description: The Viewpoint suite of construction ERP APIs includes Jobpac Connect, Spectrum, and Vista. These REST and web service APIs provide accounting, HR, project management, and operations integrations for c
  name: Viewpoint Construction ERP APIs
  slug: trimble-viewpoint
- description: Trimble Identity provides OAuth 2.0 / OpenID Connect authentication and authorization for all Trimble developer applications. Enables single sign-on across the Trimble platform for web, mobile, and de
  name: Trimble Identity API
  slug: trimble-identity
capabilities:
- description: ''
  name: Bim Collaboration
  slug: bim-collaboration
- description: ''
  name: Commercial Routing
  slug: commercial-routing
common:
- title: ''
  type: Website
  url: https://www.trimble.com
- title: ''
  type: DeveloperPortal
  url: https://www.trimble.com/en/developer/docs
- title: ''
  type: GettingStarted
  url: https://www.trimble.com/en/developer
- title: ''
  type: Authentication
  url: https://developer.trimble.com/docs/authentication
- title: ''
  type: Marketplace
  url: https://developer.trimble.com/docs/marketplace
- title: ''
  type: DesignSystem
  url: https://modus.trimble.com/
- title: ''
  type: Blog
  url: https://www.trimble.com/en/news
- title: ''
  type: Vocabulary
  url: vocabulary/trimble-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: json-ld/trimble-context.jsonld
created: '2026-05-03'
description: Trimble Inc. is a global technology company that provides advanced positioning, navigation, and data analytics solutions across construction, agriculture, transportation, and geospatial industries. Founded in 1978 as Trimble Navigation Limited, the company integrates GPS, laser, optical, and inertial technologies with software and services. Trimble's developer platform spans construction collaboration (Trimble Connect), commercial vehicle routing (PC*MILER, Trimble Maps), building information modeling (Tekla, SketchUp), fleet management (TruckMate, TMT, CoPilot), precision positioning (Mobile Manager, TAP Store), and construction ERP (Viewpoint). Publicly traded on NASDAQ as TRMB.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 32
  name: Trimble Context
  property_count: 7
  slug: trimble-context
layout: provider
modified: '2026-05-03'
name: Trimble
rules:
- name: Trimble API Rules
  rule_count: 12
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 8
  slug: trimble-rules
skills: []
slug: trimble
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: trimble\nname: Trimble\ndescription: >-\n  Trimble Inc. is a global technology company that provides advanced positioning,\n  navigation, and data analytics solutions across construction, agriculture,\n  transportation, and geospatial industries. Founded in 1978 as Trimble Navigation\n  Limited, the company integrates GPS, laser, optical, and inertial technologies\n  with software and services. Trimble's developer platform spans construction\n  collaboration (Trimble Connect), commercial vehicle routing (PC*MILER, Trimble Maps),\n  building information modeling (Tekla, SketchUp), fleet management (TruckMate, TMT,\n  CoPilot), precision positioning (Mobile Manager, TAP Store), and construction ERP\n  (Viewpoint). Publicly traded on NASDAQ as TRMB.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Construction\n  - Transportation\n  - Geospatial\n  - GPS\n  - Mapping\n  - BIM\n  - Fleet Management\n  - Collaboration\n\
  \  - Agriculture\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/trimble/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: trimble:trimble-connect\n    name: Trimble Connect API\n    description: >-\n      The Trimble Connect API enables integration with Trimble's cloud-based\n      construction collaboration platform. Provides access to project data,\n      BIM models, document management, issues (BCF Topics), and team\n      collaboration features for construction project management. Acts as the\n      BIM collaboration hub integrating Tekla, SketchUp, and third-party tools.\n    humanURL: https://developer.trimble.com/docs/connect\n    tags:\n      - Construction\n      - Collaboration\n      - BIM\n      - Cloud\n      - Document Management\n    properties:\n      - type: Documentation\n        url: https://developer.trimble.com/docs/connect\n      - type: OpenAPI\n        url: openapi/trimble-connect-openapi.yml\n\
  \      - type: SpectralRules\n        url: rules/trimble-rules.yml\n      - type: NaftikoCapability\n        url: capabilities/bim-collaboration.yaml\n      - type: JSONSchema\n        url: json-schema/trimble-project-schema.json\n      - type: JSONStructure\n        url: json-structure/trimble-project-structure.json\n      - type: JSONLDContext\n        url: json-ld/trimble-context.jsonld\n\n  - aid: trimble:trimble-maps\n    name: Trimble Maps API\n    description: >-\n      The Trimble Maps API (formerly ALK Technologies PC*MILER) provides\n      interactive mapping and routing solutions optimized for commercial vehicles\n      and transportation. Enables truck-specific routing, geocoding, map tile\n      rendering, and turn-by-turn navigation services across North America,\n      Europe, and global markets.\n    humanURL: https://developer.trimble.com/docs/maps\n    tags:\n      - Mapping\n      - Transportation\n      - Routing\n      - Geospatial\n      - Commercial Vehicles\n  \
  \  properties:\n      - type: Documentation\n        url: https://developer.trimble.com/docs/maps\n      - type: DeveloperPortal\n        url: https://developer.trimblemaps.com/\n      - type: OpenAPI\n        url: openapi/trimble-maps-openapi.yml\n      - type: NaftikoCapability\n        url: capabilities/commercial-routing.yaml\n      - type: JSONSchema\n        url: json-schema/trimble-route-schema.json\n      - type: JSONStructure\n        url: json-structure/trimble-route-structure.json\n\n  - aid: trimble:trimble-pcmiler\n    name: Trimble PC*MILER API\n    description: >-\n      PC*MILER provides commercial vehicle routing and distance calculation APIs\n      for logistics, freight, and transportation management. Delivers mileage,\n      routing, tolls, and fuel optimization for trucking operations across North\n      America, Europe, and global markets.\n    humanURL: https://developer.trimble.com/docs/pc-miler\n    tags:\n      - Transportation\n      - Routing\n      - Logistics\n\
  \      - Distance Calculation\n      - Commercial Vehicles\n    properties:\n      - type: Documentation\n        url: https://developer.trimble.com/docs/pc-miler\n\n  - aid: trimble:trimble-tekla\n    name: Tekla API\n    description: >-\n      The Tekla API provides programmatic access to Tekla Structures, a leading\n      Building Information Modeling (BIM) software for structural engineering and\n      detailing. Enables custom model creation, data extraction, and workflow\n      automation for steel, concrete, and timber construction.\n    humanURL: https://developer.tekla.com/\n    tags:\n      - BIM\n      - Structural Engineering\n      - Construction\n      - Modeling\n    properties:\n      - type: Documentation\n        url: https://developer.tekla.com/\n      - type: DeveloperPortal\n        url: https://developer.tekla.com/\n\n  - aid: trimble:trimble-sketchup\n    name: SketchUp API\n    description: >-\n      The SketchUp API enables extension development for Trimble SketchUp,\
  \ a\n      widely-used 3D modeling and design tool. Supports Ruby and JavaScript APIs\n      for building custom tools, plugins, and integrations for architecture,\n      interior design, and engineering workflows.\n    humanURL: https://developer.sketchup.com/\n    tags:\n      - 3D Modeling\n      - Architecture\n      - Design\n      - Plugins\n    properties:\n      - type: Documentation\n        url: https://developer.sketchup.com/\n\n  - aid: trimble:trimble-projectsight\n    name: ProjectSight API\n    description: >-\n      The Trimble ProjectSight API provides portfolio and project information\n      management for construction. Enables programmatic access to project data,\n      submittals, RFIs, and document workflows for construction project management.\n    humanURL: https://developer.trimble.com/docs/projectsight\n    tags:\n      - Construction\n      - Project Management\n      - Documents\n    properties:\n      - type: Documentation\n        url: https://developer.trimble.com/docs/projectsight\n\
  \n  - aid: trimble:trimble-truckmate\n    name: TruckMate API\n    description: >-\n      The TruckMate REST API provides transactional and configuration operations\n      for Trimble's transportation management system (TMS). Enables freight brokers,\n      carriers, and logistics operators to automate dispatch, load management, and\n      billing workflows.\n    humanURL: https://developer.trimble.com/docs/truckmate\n    tags:\n      - Transportation\n      - TMS\n      - Logistics\n      - Freight\n    properties:\n      - type: Documentation\n        url: https://developer.trimble.com/docs/truckmate\n\n  - aid: trimble:trimble-copilot\n    name: CoPilot Navigation API\n    description: >-\n      The Trimble CoPilot Navigation API enables in-cab navigation integration\n      with cloud-based services for commercial vehicle fleets. Provides route\n      delivery, real-time traffic, and truck-specific navigation for driver\n      mobile applications.\n    humanURL: https://developer.trimble.com/docs/copilot\n\
  \    tags:\n      - Navigation\n      - Transportation\n      - Trucking\n      - In-Cab\n    properties:\n      - type: Documentation\n        url: https://developer.trimble.com/docs/copilot\n      - type: DeveloperPortal\n        url: https://developer.trimblemaps.com/copilot-navigation/\n\n  - aid: trimble:trimble-tmt\n    name: TMT Fleet Maintenance API\n    description: >-\n      The TMT (Trimble Maintenance Technology) REST API provides fleet\n      maintenance management operations for commercial vehicle fleets. Enables\n      work order management, preventive maintenance scheduling, parts inventory,\n      and repair tracking.\n    humanURL: https://developer.trimble.com/docs/tmt\n    tags:\n      - Fleet Management\n      - Maintenance\n      - Transportation\n    properties:\n      - type: Documentation\n        url: https://developer.trimble.com/docs/tmt\n\n  - aid: trimble:trimble-viewpoint\n    name: Viewpoint Construction ERP APIs\n    description: >-\n      The Viewpoint\
  \ suite of construction ERP APIs includes Jobpac Connect,\n      Spectrum, and Vista. These REST and web service APIs provide accounting,\n      HR, project management, and operations integrations for construction firms.\n    humanURL: https://developer.trimble.com/docs/vista\n    tags:\n      - Construction ERP\n      - Accounting\n      - HR\n      - Finance\n    properties:\n      - type: Documentation\n        url: https://developer.trimble.com/docs/vista\n\n  - aid: trimble:trimble-identity\n    name: Trimble Identity API\n    description: >-\n      Trimble Identity provides OAuth 2.0 / OpenID Connect authentication and\n      authorization for all Trimble developer applications. Enables single sign-on\n      across the Trimble platform for web, mobile, and desktop applications.\n    humanURL: https://developer.trimble.com/docs/authentication\n    tags:\n      - Authentication\n      - OAuth 2.0\n      - Identity\n      - Security\n    properties:\n      - type: Documentation\n  \
  \      url: https://developer.trimble.com/docs/authentication\n\nfeatures:\n  - BIM collaboration and model viewing via Trimble Connect\n  - Commercial vehicle routing and mileage with PC*MILER\n  - Interactive mapping and geocoding for web and mobile\n  - Structural BIM modeling API (Tekla)\n  - 3D design extension framework (SketchUp)\n  - Construction project management and document control\n  - Fleet TMS with dispatch and billing (TruckMate)\n  - Fleet maintenance management (TMT)\n  - In-cab navigation for truck drivers (CoPilot)\n  - Construction ERP integration (Viewpoint Vista, Spectrum, Jobpac)\n  - High-accuracy GNSS positioning (Mobile Manager, TAP Store)\n  - Survey and geospatial field data management\n  - Unified OAuth 2.0 authentication via Trimble Identity\nuseCases:\n  - BIM coordination between structural, MEP, and architectural teams\n  - Trucking route optimization for logistics and freight planning\n  - Fleet management with maintenance tracking and dispatch\n  - Construction\
  \ project document and submittal workflows\n  - Custom SketchUp extensions for design automation\n  - Structural engineering model automation with Tekla\n  - Real-time commercial vehicle navigation and tracking\n  - Construction ERP integration with project cost controls\nintegrations:\n  - Tekla Structures (structural BIM)\n  - SketchUp (3D design)\n  - Procore, Autodesk Construction Cloud (construction)\n  - SAP, Oracle (ERP)\n  - Esri ArcGIS (geospatial)\n  - ELD/telematics providers (transportation)\nsolutions:\n  - Construction technology companies building BIM integrations\n  - Logistics and freight software integrating routing APIs\n  - Surveying and geospatial platforms using positioning APIs\n  - Fleet management platforms integrating TMS and navigation\n  - AEC firms automating Tekla and SketchUp workflows\ngithub:\n  - name: trimble-id\n    url: https://github.com/trimble-oss\n    description: Trimble Open Source Software organization\ncommon:\n  - type: Website\n    url: https://www.trimble.com\n\
  \  - type: DeveloperPortal\n    url: https://www.trimble.com/en/developer/docs\n  - type: GettingStarted\n    url: https://www.trimble.com/en/developer\n  - type: Authentication\n    url: https://developer.trimble.com/docs/authentication\n  - type: Marketplace\n    url: https://developer.trimble.com/docs/marketplace\n  - type: DesignSystem\n    url: https://modus.trimble.com/\n  - type: Blog\n    url: https://www.trimble.com/en/news\n  - type: Vocabulary\n    url: vocabulary/trimble-vocabulary.yml\n  - type: JSONLDContext\n    url: json-ld/trimble-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trimble/refs/heads/main/apis.yml
tags:
- Construction
- Transportation
- Geospatial
- GPS
- Mapping
- BIM
- Fleet Management
- Collaboration
- Agriculture
url: https://raw.githubusercontent.com/api-evangelist/trimble/refs/heads/main/apis.yml
use_cases: []
---
