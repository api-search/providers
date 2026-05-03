---
api_count: 3
api_specs:
- filename: osisoft-pi-web-api-openapi.yml
  format: yaml
  label: OSIsoft PI Web API
  slug: pi-web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/osisoft-pi/refs/heads/main/openapi/osisoft-pi-web-api-openapi.yml
apis:
- description: OSIsoft PI Web API (now part of AVEVA) provides a REST interface for accessing the PI System process historian. APIs enable real-time and historical time-series data retrieval, event frame queries, as
  name: OSIsoft PI Web API
  slug: pi-web-api
- description: AVEVA CONNECT (formerly AVEVA Data Hub / OSIsoft Cloud Services) provides cloud-native REST APIs for industrial time-series data management, data views, event data, and secure cloud-based data sharing
  name: AVEVA CONNECT Data Services API
  slug: aveva-connect-api
- description: OSIsoft PI Asset Framework SDK (AF SDK) is a .NET client library for programmatic access to the PI System asset hierarchy, time-series data, and event frames from on-premises PI servers.
  name: OSIsoft PI AF SDK
  slug: pi-af-sdk
common:
- title: ''
  type: Portal
  url: https://docs.aveva.com/
- title: ''
  type: Documentation
  url: https://docs.aveva.com/
- title: ''
  type: GettingStarted
  url: https://docs.aveva.com/bundle/pi-web-api-getting-started
- title: ''
  type: Website
  url: https://www.aveva.com/
- title: ''
  type: Support
  url: https://softwaresupport.aveva.com/
- title: ''
  type: Support
  url: https://community.aveva.com/
- title: ''
  type: Documentation
  url: https://learningacademy.aveva.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aveva
- title: ''
  type: SDKs
  url: https://github.com/aveva
- title: ''
  type: OpenAPI
  url: openapi/osisoft-pi-web-api-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/osisoft-pi-point-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/osisoft-pi-timed-value-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/osisoft-pi-context.jsonld
created: ''
description: OSIsoft PI System is a real-time data management platform used by industrial organizations to capture, analyze, and visualize operational data from sensors, devices, and applications.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Osisoft Pi Context
  property_count: 23
  slug: osisoft-pi-context
layout: provider
modified: '2026-03-18'
name: osisoft-pi
skills: []
slug: osisoft-pi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: osisoft-pi\nurl: https://raw.githubusercontent.com/api-evangelist/osisoft-pi/refs/heads/main/apis.yml\napis:\n  - aid: osisoft-pi:pi-web-api\n    name: OSIsoft PI Web API\n    tags:\n      - Energy\n      - Manufacturing\n      - Process Historian\n      - REST\n      - SCADA\n      - Time Series\n    image: https://raw.githubusercontent.com/api-evangelist/osisoft-pi/refs/heads/main/image.png\n    humanURL: https://docs.aveva.com/bundle/pi-web-api-reference\n    baseURL: https://piwebapi.example.com/piwebapi\n    properties:\n      - url: https://docs.aveva.com/bundle/pi-web-api-reference\n        type: Documentation\n      - url: https://docs.aveva.com/bundle/pi-web-api-reference\n        type: Reference\n      - url: https://docs.aveva.com/bundle/pi-web-api-getting-started\n        type: GettingStarted\n      - url: https://github.com/aveva/sample-pi_web_api-common_actions-python\n        type: SDKs\n      - url: https://github.com/aveva/sample-pi_web_api-common_actions-angular\n\
  \        type: SDKs\n      - url: openapi/osisoft-pi-web-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      OSIsoft PI Web API (now part of AVEVA) provides a REST interface for accessing\n      the PI System process historian. APIs enable real-time and historical time-series\n      data retrieval, event frame queries, asset framework hierarchy navigation, and\n      calculated data for industrial process monitoring.\n\n  - aid: osisoft-pi:aveva-connect-api\n    name: AVEVA CONNECT Data Services API\n    tags:\n      - Cloud\n      - IoT\n      - Manufacturing\n      - REST\n      - Time Series\n    image: https://raw.githubusercontent.com/api-evangelist/osisoft-pi/refs/heads/main/image.png\n    humanURL: https://docs.aveva.com/bundle/aveva-data-hub-api-reference\n    baseURL: https://api.aveva.com\n    properties:\n      - url: https://docs.aveva.com/bundle/aveva-data-hub-api-reference\n        type: Documentation\n    description: >-\n      AVEVA CONNECT (formerly AVEVA\
  \ Data Hub / OSIsoft Cloud Services) provides cloud-native\n      REST APIs for industrial time-series data management, data views, event data,\n      and secure cloud-based data sharing across operational technology environments.\n\n  - aid: osisoft-pi:pi-af-sdk\n    name: OSIsoft PI AF SDK\n    tags:\n      - .NET\n      - Asset Framework\n      - Manufacturing\n      - SDK\n    image: https://raw.githubusercontent.com/api-evangelist/osisoft-pi/refs/heads/main/image.png\n    humanURL: https://docs.aveva.com/\n    baseURL: https://piwebapi.example.com/piwebapi\n    properties:\n      - url: https://docs.aveva.com/\n        type: Documentation\n      - url: https://github.com/aveva/sample-afsdk-getting_started-dotnet\n        type: SDKs\n    description: >-\n      OSIsoft PI Asset Framework SDK (AF SDK) is a .NET client library for programmatic\n      access to the PI System asset hierarchy, time-series data, and event frames\n      from on-premises PI servers.\n\ncommon:\n  - url: https://docs.aveva.com/\n\
  \    type: Portal\n  - url: https://docs.aveva.com/\n    type: Documentation\n  - url: https://docs.aveva.com/bundle/pi-web-api-getting-started\n    type: GettingStarted\n  - url: https://www.aveva.com/\n    type: Website\n  - url: https://softwaresupport.aveva.com/\n    type: Support\n  - url: https://community.aveva.com/\n    type: Support\n  - url: https://learningacademy.aveva.com/\n    type: Documentation\n  - url: https://github.com/aveva\n    type: GitHubOrganization\n  - url: https://github.com/aveva\n    type: SDKs\n  - url: openapi/osisoft-pi-web-api-openapi.yml\n    type: OpenAPI\n  - url: json-schema/osisoft-pi-point-schema.json\n    type: JSONSchema\n  - url: json-schema/osisoft-pi-timed-value-schema.json\n    type: JSONSchema\n  - url: json-ld/osisoft-pi-context.jsonld\n    type: JSONLDContext\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\nmodified: '2026-03-18'\ndescription: >-\n  OSIsoft PI System is a real-time data management platform used by industrial\
  \ organizations\n  to capture, analyze, and visualize operational data from sensors, devices, and applications.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/osisoft-pi/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/osisoft-pi/refs/heads/main/apis.yml
use_cases: []
---
