---
api_count: 3
api_specs:
- filename: hl7-fhir-r4-openapi.yml
  format: yaml
  label: HL7 FHIR R4 Healthcare API
  slug: hl7-fhir-r4-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/openapi/hl7-fhir-r4-openapi.yml
apis:
- description: HL7 FHIR R5 (Release 5) is the current published FHIR standard for healthcare data exchange. FHIR R5 REST APIs provide access to patient demographics, observations, conditions, medications, encounters
  name: HL7 FHIR R5 Healthcare API
  slug: hl7-fhir-r5-api
- description: HL7 FHIR R4 (v4.0.1) is a widely adopted normative FHIR standard for healthcare data exchange. FHIR R4 REST APIs are the most commonly implemented version across US healthcare systems, supporting pati
  name: HL7 FHIR R4 Healthcare API
  slug: hl7-fhir-r4-api
- description: 'SMART on FHIR (v2.2.0) defines OAuth 2.0-based authorization patterns for client applications to authorize, authenticate, and integrate with FHIR-based data systems. It enables EHR launch, standalone '
  name: SMART on FHIR Authentication
  slug: hl7-smart-on-fhir-api
common:
- title: ''
  type: Portal
  url: https://www.hl7.org/fhir/
- title: ''
  type: Documentation
  url: https://www.hl7.org/fhir/
- title: ''
  type: Reference
  url: https://www.hl7.org/fhir/http.html
- title: ''
  type: Authentication
  url: https://www.hl7.org/fhir/security.html
- title: ''
  type: Change Log
  url: https://www.hl7.org/fhir/history.html
- title: ''
  type: Getting Started
  url: https://www.hl7.org/fhir/downloads.html
- title: ''
  type: Website
  url: https://www.hl7.org/
- title: ''
  type: GitHub Organization
  url: https://github.com/HL7
- title: ''
  type: OpenAPI
  url: openapi/hl7-fhir-r4-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/hl7-fhir-patient-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/hl7-fhir-context.jsonld
created: '2025'
description: HL7 FHIR (Fast Healthcare Interoperability Resources) is the standard API specification for healthcare data exchange, published by Health Level Seven International (HL7). FHIR REST APIs provide access to patient, clinical, financial, and administrative healthcare data in JSON, XML, and RDF formats with a CC0 open license.
features: []
image: https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/image.png
integrations: []
jsonld:
- class_count: 13
  name: Hl7 Fhir Context
  property_count: 21
  slug: hl7-fhir-context
layout: provider
modified: '2026-04-28'
name: HL7 FHIR
skills: []
slug: hl7-fhir
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: hl7-fhir\nname: HL7 FHIR\ndescription: >-\n  HL7 FHIR (Fast Healthcare Interoperability Resources) is the standard API\n  specification for healthcare data exchange, published by Health Level Seven\n  International (HL7). FHIR REST APIs provide access to patient, clinical,\n  financial, and administrative healthcare data in JSON, XML, and RDF formats\n  with a CC0 open license.\nurl: https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/apis.yml\ntype: Index\nimage: https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/image.png\ntags:\n  - Clinical\n  - FHIR\n  - Healthcare\n  - HL7\n  - Interoperability\ncreated: '2025'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: hl7-fhir:hl7-fhir-r5-api\n    name: HL7 FHIR R5 Healthcare API\n    description: >-\n      HL7 FHIR R5 (Release 5) is the current published FHIR standard for\n      healthcare data exchange. FHIR R5 REST APIs provide access to patient\n     \
  \ demographics, observations, conditions, medications, encounters, and\n      care plans in both JSON and XML formats across EHR systems, published\n      March 2023.\n    humanURL: https://www.hl7.org/fhir/\n    baseURL: https://fhir-server.example.com/fhir/R5\n    image: https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/image.png\n    tags:\n      - Clinical\n      - FHIR\n      - Healthcare\n      - HL7\n      - Interoperability\n      - JSON\n      - XML\n    properties:\n      - type: Documentation\n        url: https://www.hl7.org/fhir/\n      - type: Reference\n        url: https://www.hl7.org/fhir/http.html\n      - type: Authentication\n        url: https://www.hl7.org/fhir/security.html\n      - type: Change Log\n        url: https://www.hl7.org/fhir/history.html\n\n  - aid: hl7-fhir:hl7-fhir-r4-api\n    name: HL7 FHIR R4 Healthcare API\n    description: >-\n      HL7 FHIR R4 (v4.0.1) is a widely adopted normative FHIR standard for\n      healthcare data\
  \ exchange. FHIR R4 REST APIs are the most commonly\n      implemented version across US healthcare systems, supporting patient\n      data, clinical resources, medications, diagnostics, and financial\n      resources.\n    humanURL: https://www.hl7.org/fhir/R4/\n    baseURL: https://fhir-server.example.com/fhir/R4\n    image: https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/image.png\n    tags:\n      - Clinical\n      - FHIR\n      - Healthcare\n      - HL7\n      - Interoperability\n      - JSON\n      - XML\n    properties:\n      - type: Documentation\n        url: https://www.hl7.org/fhir/R4/\n      - type: Reference\n        url: https://www.hl7.org/fhir/R4/http.html\n      - type: Change Log\n        url: http://hl7.org/fhir/R4/history.html\n      - type: OpenAPI\n        url: openapi/hl7-fhir-r4-openapi.yml\n\n  - aid: hl7-fhir:hl7-smart-on-fhir-api\n    name: SMART on FHIR Authentication\n    description: >-\n      SMART on FHIR (v2.2.0) defines OAuth\
  \ 2.0-based authorization patterns\n      for client applications to authorize, authenticate, and integrate with\n      FHIR-based data systems. It enables EHR launch, standalone launch, and\n      backend service authorization workflows.\n    humanURL: http://hl7.org/fhir/smart-app-launch/ImplementationGuide/hl7.fhir.uv.smart-app-launch\n    baseURL: https://fhir-server.example.com/fhir\n    image: https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/image.png\n    tags:\n      - Authentication\n      - FHIR\n      - Healthcare\n      - OAuth2\n      - SMART\n    properties:\n      - type: Documentation\n        url: http://hl7.org/fhir/smart-app-launch/ImplementationGuide/hl7.fhir.uv.smart-app-launch\n      - type: Authentication\n        url: http://hl7.org/fhir/smart-app-launch/ImplementationGuide/hl7.fhir.uv.smart-app-launch\n\ncommon:\n  - type: Portal\n    url: https://www.hl7.org/fhir/\n  - type: Documentation\n    url: https://www.hl7.org/fhir/\n  - type:\
  \ Reference\n    url: https://www.hl7.org/fhir/http.html\n  - type: Authentication\n    url: https://www.hl7.org/fhir/security.html\n  - type: Change Log\n    url: https://www.hl7.org/fhir/history.html\n  - type: Getting Started\n    url: https://www.hl7.org/fhir/downloads.html\n  - type: Website\n    url: https://www.hl7.org/\n  - type: GitHub Organization\n    url: https://github.com/HL7\n  - type: OpenAPI\n    url: openapi/hl7-fhir-r4-openapi.yml\n  - type: JSONSchema\n    url: json-schema/hl7-fhir-patient-schema.json\n  - type: JSONLDContext\n    url: json-ld/hl7-fhir-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/apis.yml
tags:
- Clinical
- FHIR
- Healthcare
- HL7
- Interoperability
url: https://raw.githubusercontent.com/api-evangelist/hl7-fhir/refs/heads/main/apis.yml
use_cases: []
---
