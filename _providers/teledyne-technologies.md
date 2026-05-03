---
api_count: 4
api_specs:
- filename: teledyne-flir-camera-rest-openapi.yml
  format: yaml
  label: Teledyne FLIR Camera REST API
  slug: flir-camera-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/teledyne-technologies/refs/heads/main/openapi/teledyne-flir-camera-rest-openapi.yml
apis:
- description: 'Teledyne FLIR provides REST API access for automation cameras (A50/A70, A400/A500/A700, Ax8 series). The API enables retrieval of thermal images, region of interest (ROI) data, alarm data, and camera '
  name: Teledyne FLIR Camera REST API
  slug: flir-camera-rest-api
- description: The Spinnaker SDK provides programmatic control of Teledyne FLIR and DALSA machine vision cameras over USB3, GigE, 5GigE, and 10GigE interfaces. Supports C++, C#, Python, and Java with a cross-platfor
  name: Teledyne FLIR Spinnaker SDK
  slug: flir-spinnaker-sdk
- description: The FLIR Mobile SDK enables iOS and Android developers to build mobile applications that integrate thermal imaging capabilities from Teledyne FLIR professional thermal cameras. Supports data collectio
  name: Teledyne FLIR Mobile SDK
  slug: flir-mobile-sdk
- description: ActiveDSO is Teledyne LeCroy's ActiveX/COM control enabling remote automation of MAUI-based oscilloscopes from Windows applications via SCPI commands, VISA drivers, Ethernet (ENET), GPIB, and USBTMC i
  name: Teledyne LeCroy ActiveDSO API
  slug: lecroy-activedso-api
capabilities:
- description: Industrial thermal monitoring capability using Teledyne FLIR automation cameras. Enables continuous temperature monitoring, alarm management, and predictive maintenance workflows for manufacturing, el
  name: Teledyne FLIR Industrial Thermal Monitoring
  slug: industrial-thermal-monitoring
common:
- title: ''
  type: Website
  url: https://www.teledyne.com/en-us
- title: ''
  type: DeveloperPortal
  url: https://www.flir.com/developer/mobile-sdk/
- title: ''
  type: GitHub
  url: https://github.com/FLIR
- title: ''
  type: GitHub
  url: https://github.com/Teledyne-MV
- title: ''
  type: Website
  url: https://www.teledynelecroy.com/
- title: ''
  type: Website
  url: https://www.teledyneimaging.com/
- title: ''
  type: Website
  url: https://www.teledyne-api.com/en-us
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/teledyne-technologies
created: '2026-03-24'
description: Teledyne Technologies Incorporated is a leading provider of sophisticated digital imaging products and software, instrumentation, aerospace and defense electronics, and engineered systems. Headquartered in Thousand Oaks, California, Teledyne serves the defense, commercial, and industrial markets. Key subsidiaries include Teledyne FLIR (thermal imaging cameras and systems), Teledyne LeCroy (oscilloscopes and protocol analyzers), Teledyne Imaging (scientific and industrial cameras), and Teledyne API (air quality monitoring instruments). Teledyne FLIR provides REST APIs and SDKs for thermal camera integration, while Teledyne LeCroy provides ActiveDSO and VISA-based automation APIs for test and measurement instruments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 26
  name: Teledyne Technologies Context
  property_count: 0
  slug: teledyne-technologies-context
layout: provider
modified: '2026-05-03'
name: Teledyne Technologies
rules:
- name: Teledyne Technologies API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 6
  slug: teledyne-technologies-rules
skills: []
slug: teledyne-technologies
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: teledyne-technologies\nname: Teledyne Technologies\ndescription: >-\n  Teledyne Technologies Incorporated is a leading provider of sophisticated\n  digital imaging products and software, instrumentation, aerospace and defense\n  electronics, and engineered systems. Headquartered in Thousand Oaks, California,\n  Teledyne serves the defense, commercial, and industrial markets. Key subsidiaries\n  include Teledyne FLIR (thermal imaging cameras and systems), Teledyne LeCroy\n  (oscilloscopes and protocol analyzers), Teledyne Imaging (scientific and\n  industrial cameras), and Teledyne API (air quality monitoring instruments).\n  Teledyne FLIR provides REST APIs and SDKs for thermal camera integration,\n  while Teledyne LeCroy provides ActiveDSO and VISA-based automation APIs for\n  test and measurement instruments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Aerospace\n  - Defense\n  - Digital Imaging\n  - Instrumentation\n\
  \  - Thermal Imaging\n  - Test and Measurement\n  - Fortune 500\nurl: https://raw.githubusercontent.com/api-evangelist/teledyne-technologies/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: teledyne-technologies:flir-camera-rest-api\n    name: Teledyne FLIR Camera REST API\n    description: >-\n      Teledyne FLIR provides REST API access for automation cameras (A50/A70,\n      A400/A500/A700, Ax8 series). The API enables retrieval of thermal images,\n      region of interest (ROI) data, alarm data, and camera configuration.\n      Endpoints return radiometric JPEG images and JSON data for temperature\n      measurements across spots, boxes, lines, polylines, and delta measurements.\n      Used for industrial process monitoring, building inspection, and predictive\n      maintenance applications. A Swagger/OpenAPI JSON specification is available\n      from the camera's local web server.\n    humanURL: https://www.flir.com/support-center/Instruments/restful-api-exercise/\n\
  \    baseURL: http://{camera_ip}/api\n    tags:\n      - Thermal Imaging\n      - Camera\n      - REST API\n      - Industrial\n      - Machine Vision\n    properties:\n      - type: Documentation\n        url: https://www.flir.com/support-center/Instruments/restful-api-exercise/\n      - type: OpenAPI\n        url: openapi/teledyne-flir-camera-rest-openapi.yml\n      - type: JSONSchema\n        url: json-schema/teledyne-flir-measurement-schema.json\n      - type: JSONSchema\n        url: json-schema/teledyne-flir-alarm-schema.json\n  - aid: teledyne-technologies:flir-spinnaker-sdk\n    name: Teledyne FLIR Spinnaker SDK\n    description: >-\n      The Spinnaker SDK provides programmatic control of Teledyne FLIR and DALSA\n      machine vision cameras over USB3, GigE, 5GigE, and 10GigE interfaces.\n      Supports C++, C#, Python, and Java with a cross-platform API for camera\n      discovery, configuration, image acquisition, and processing. Includes\n      SpinView GUI for camera exploration\
  \ and real-time viewing. Used for factory\n      automation, quality inspection, and scientific imaging applications.\n    humanURL: https://www.flir.com/support/browse/camera-cores--components/machine-vision-cameras/sdks\n    baseURL: https://www.flir.com\n    tags:\n      - Machine Vision\n      - Camera\n      - SDK\n      - Industrial Automation\n      - Image Acquisition\n    properties:\n      - type: Documentation\n        url: https://www.flir.com/support/browse/camera-cores--components/machine-vision-cameras/sdks\n      - type: SDK\n        url: https://www.flir.com/support/browse/camera-cores--components/machine-vision-cameras/sdks\n      - type: GitHub\n        url: https://github.com/Teledyne-MV/Spinnaker-Examples\n  - aid: teledyne-technologies:flir-mobile-sdk\n    name: Teledyne FLIR Mobile SDK\n    description: >-\n      The FLIR Mobile SDK enables iOS and Android developers to build mobile\n      applications that integrate thermal imaging capabilities from Teledyne FLIR\n\
  \      professional thermal cameras. Supports data collection from connected\n      thermal cameras and metering devices. Available through FLIR's Developer\n      Program with approved access. Includes an App Gallery for showcasing\n      third-party thermal imaging applications.\n    humanURL: https://www.flir.com/developer/mobile-sdk/\n    baseURL: https://www.flir.com/developer\n    tags:\n      - Mobile SDK\n      - iOS\n      - Android\n      - Thermal Imaging\n      - Developer Program\n    properties:\n      - type: Documentation\n        url: https://www.flir.com/developer/mobile-sdk/\n      - type: DeveloperPortal\n        url: https://www.flir.com/developer/mobile-sdk/\n  - aid: teledyne-technologies:lecroy-activedso-api\n    name: Teledyne LeCroy ActiveDSO API\n    description: >-\n      ActiveDSO is Teledyne LeCroy's ActiveX/COM control enabling remote\n      automation of MAUI-based oscilloscopes from Windows applications via\n      SCPI commands, VISA drivers, Ethernet (ENET),\
  \ GPIB, and USBTMC interfaces.\n      Supports Python, C++, C#, LabVIEW, and MATLAB automation. Used for\n      automated test sequences, waveform capture, protocol analysis, and\n      measurement reporting in test and measurement workflows.\n    humanURL: https://www.teledynelecroy.com/support/techlib/programmingexamples.aspx\n    baseURL: https://www.teledynelecroy.com\n    tags:\n      - Oscilloscope\n      - Test and Measurement\n      - Automation\n      - SCPI\n      - VISA\n    properties:\n      - type: Documentation\n        url: https://www.teledynelecroy.com/support/techlib/programmingexamples.aspx\n      - type: Documentation\n        url: https://cdn.teledynelecroy.com/files/manuals/activedso-developers-guide.pdf\ncommon:\n  - url: https://www.teledyne.com/en-us\n    name: Teledyne Technologies\n    type: Website\n    description: Teledyne Technologies corporate website.\n  - url: https://www.flir.com/developer/mobile-sdk/\n    name: Teledyne FLIR Developer Program\n    type:\
  \ DeveloperPortal\n    description: FLIR Mobile SDK and developer resources.\n  - url: https://github.com/FLIR\n    name: Teledyne FLIR GitHub\n    type: GitHub\n    description: Teledyne FLIR official GitHub organization.\n  - url: https://github.com/Teledyne-MV\n    name: Teledyne Machine Vision GitHub\n    type: GitHub\n    description: Teledyne Machine Vision GitHub organization (Spinnaker SDK examples).\n  - url: https://www.teledynelecroy.com/\n    name: Teledyne LeCroy\n    type: Website\n    description: Teledyne LeCroy oscilloscopes and protocol analyzers.\n  - url: https://www.teledyneimaging.com/\n    name: Teledyne Imaging\n    type: Website\n    description: Teledyne Imaging scientific and industrial cameras.\n  - url: https://www.teledyne-api.com/en-us\n    name: Teledyne API\n    type: Website\n    description: Teledyne API air quality monitoring instruments.\n  - url: https://www.linkedin.com/company/teledyne-technologies\n    name: Teledyne Technologies on LinkedIn\n \
  \   type: LinkedIn\n    description: Teledyne Technologies LinkedIn company page.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/teledyne-technologies/refs/heads/main/apis.yml
tags:
- Aerospace
- Defense
- Digital Imaging
- Instrumentation
- Thermal Imaging
- Test and Measurement
- Fortune 500
url: https://raw.githubusercontent.com/api-evangelist/teledyne-technologies/refs/heads/main/apis.yml
use_cases: []
---
