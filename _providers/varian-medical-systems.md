---
api_count: 2
api_specs:
- filename: varian-aria-fhir-openapi.yml
  format: yaml
  label: ARIA FHIR API
  slug: aria-fhir-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/varian-medical-systems/refs/heads/main/openapi/varian-aria-fhir-openapi.yml
apis:
- description: The Varian ARIA FHIR R4 API provides SMART on FHIR access to oncology clinical data from the ARIA Oncology Information System. Supports read and search operations for Patient, Condition, Procedure, Ob
  name: ARIA FHIR API
  slug: aria-fhir-api
- description: The legacy ARIA Access API provides SOAP and REST access to core ARIA entities including patients, appointments, prescriptions, treatment plans, orders, and administrative data. Deployed on-premise wi
  name: ARIA Access API
  slug: aria-access-api
capabilities:
- description: 'Unified oncology clinical data workflow combining the Varian ARIA FHIR R4 API. Designed for clinical informaticists, oncology application developers, and EHR integration teams accessing patient-level '
  name: Varian Oncology Clinical Data
  slug: oncology-clinical-data
common:
- title: ''
  type: Portal
  url: https://varian.dynamicfhir.com/varian/basepractice/r4
- title: ''
  type: Documentation
  url: https://varian.dynamicfhir.com/varian/basepractice/r4/Home/ApiDocumentation
- title: ''
  type: CapabilityStatement
  url: https://varian.dynamicfhir.com/fhir/varian/basepractice/r4/metadata
- title: ''
  type: Documentation
  url: https://www.gatewayscripts.com/post/webinars-revisited-a-review-of-aria-apis
- title: ''
  type: Product
  url: https://cancercare.siemens-healthineers.com/products/software/digital-oncology/oncology-management-systems/aria-oncology-information-system
- title: ''
  type: Website
  url: https://www.varian.com
- title: ''
  type: Website
  url: https://cancercare.siemens-healthineers.com
- title: ''
  type: Standard
  url: https://hl7.org/fhir/R4/
- title: ''
  type: Standard
  url: https://www.dicomstandard.org
created: '2026-05-03'
description: Varian Medical Systems is a leading manufacturer of medical devices and software for treating cancer with radiotherapy, radiosurgery, proton therapy, and brachytherapy. Acquired by Siemens Healthineers in 2021, Varian provides the ARIA Oncology Information System (OIS) and developer APIs enabling integration with clinical workflows, EHR systems, and the broader healthcare ecosystem using HL7, DICOM, and FHIR standards.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 15
  name: Varian Medical Systems Context
  property_count: 20
  slug: varian-medical-systems-context
layout: provider
modified: '2026-05-03'
name: Varian Medical Systems
rules:
- name: Varian Medical Systems API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 5
  slug: varian-rules
skills: []
slug: varian-medical-systems
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: varian-medical-systems\nurl: https://raw.githubusercontent.com/api-evangelist/varian-medical-systems/refs/heads/main/apis.yml\nname: Varian Medical Systems\ntags:\n  - Healthcare\n  - Oncology\n  - Medical Devices\n  - FHIR\n  - Radiation Therapy\n  - Health IT\ntype: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-05-03'\nmodified: '2026-05-03'\ndescription: >-\n  Varian Medical Systems is a leading manufacturer of medical devices and software\n  for treating cancer with radiotherapy, radiosurgery, proton therapy, and brachytherapy.\n  Acquired by Siemens Healthineers in 2021, Varian provides the ARIA Oncology Information\n  System (OIS) and developer APIs enabling integration with clinical workflows, EHR systems,\n  and the broader healthcare ecosystem using HL7, DICOM, and FHIR standards.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: varian-medical-systems:aria-fhir-api\n    name: ARIA FHIR API\n    tags:\n      - Healthcare\n      - Oncology\n      - FHIR\n      - Health IT\n      - Interoperability\n    humanURL: https://varian.dynamicfhir.com/varian/basepractice/r4/Home/ApiDocumentation\n    baseURL: https://varian.dynamicfhir.com/fhir/varian/basepractice/r4\n    properties:\n      - url: https://varian.dynamicfhir.com/varian/basepractice/r4/Home/ApiDocumentation\n        type: Documentation\n      - url: https://varian.dynamicfhir.com/fhir/varian/basepractice/r4/metadata\n        type: CapabilityStatement\n      - url: https://raw.githubusercontent.com/api-evangelist/varian-medical-systems/refs/heads/main/openapi/varian-aria-fhir-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Varian ARIA FHIR R4 API provides SMART on FHIR access to oncology clinical data\n      from the ARIA Oncology Information System. Supports read and search operations for\n      Patient, Condition, Procedure, Observation,\
  \ DiagnosticReport, CarePlan, MedicationRequest,\n      and other clinical resources relevant to cancer care.\n\n  - aid: varian-medical-systems:aria-access-api\n    name: ARIA Access API\n    tags:\n      - Healthcare\n      - Oncology\n      - SOAP\n      - Web Services\n      - Health IT\n    humanURL: https://www.gatewayscripts.com/post/webinars-revisited-a-review-of-aria-apis\n    baseURL: https://localhost:55051/Gateway/Service.svc\n    properties:\n      - url: https://www.gatewayscripts.com/post/webinars-revisited-a-review-of-aria-apis\n        type: Documentation\n    description: >-\n      The legacy ARIA Access API provides SOAP and REST access to core ARIA entities\n      including patients, appointments, prescriptions, treatment plans, orders, and\n      administrative data. Deployed on-premise within the healthcare institution's\n      infrastructure.\n\ncommon:\n  - name: ARIA FHIR Developer Portal\n    url: https://varian.dynamicfhir.com/varian/basepractice/r4\n    type:\
  \ Portal\n  - name: ARIA FHIR API Documentation\n    url: https://varian.dynamicfhir.com/varian/basepractice/r4/Home/ApiDocumentation\n    type: Documentation\n  - name: FHIR Capability Statement\n    url: https://varian.dynamicfhir.com/fhir/varian/basepractice/r4/metadata\n    type: CapabilityStatement\n  - name: ARIA API Overview\n    url: https://www.gatewayscripts.com/post/webinars-revisited-a-review-of-aria-apis\n    type: Documentation\n  - name: ARIA Oncology Information System\n    url: https://cancercare.siemens-healthineers.com/products/software/digital-oncology/oncology-management-systems/aria-oncology-information-system\n    type: Product\n  - name: Varian Website\n    url: https://www.varian.com\n    type: Website\n  - name: Siemens Healthineers Cancer Care\n    url: https://cancercare.siemens-healthineers.com\n    type: Website\n  - name: HL7 FHIR Standard\n    url: https://hl7.org/fhir/R4/\n    type: Standard\n  - name: DICOM Standard\n    url: https://www.dicomstandard.org\n\
  \    type: Standard\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/varian-medical-systems/refs/heads/main/apis.yml
tags:
- Healthcare
- Oncology
- Medical Devices
- FHIR
- Radiation Therapy
- Health IT
url: https://raw.githubusercontent.com/api-evangelist/varian-medical-systems/refs/heads/main/apis.yml
use_cases: []
---
