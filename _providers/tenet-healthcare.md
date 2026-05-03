---
api_count: 3
api_specs:
- filename: tenet-healthcare-fhir-openapi.yml
  format: yaml
  label: Tenet Health Patient Portal API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tenet-healthcare/refs/heads/main/openapi/tenet-healthcare-fhir-openapi.yml
apis:
- description: Revenue cycle management API from Conifer Health Solutions, a Tenet Healthcare subsidiary providing end-to-end RCM services including patient access, health information management, patient financial s
  name: Conifer Health Solutions Revenue Cycle API
  slug: ''
- description: 'United Surgical Partners International (USPI) integration APIs for ambulatory surgery center scheduling, patient registration, procedure management, and clinical data exchange. USPI operates over 600 '
  name: USPI Ambulatory Surgery Center API
  slug: ''
- description: 'Patient-facing digital health API enabling access to medical records, appointment scheduling, test results, care team communications, and bill payment across Tenet Health hospital network. Integrates '
  name: Tenet Health Patient Portal API
  slug: ''
capabilities:
- description: Patient care coordination workflow combining FHIR R4 APIs for patient records, appointment management, clinical data access, and care plan coordination. Used by patient portals, care coordinators, and
  name: Tenet Healthcare Patient Care
  slug: patient-care
common:
- title: ''
  type: Website
  url: https://www.tenethealth.com
- title: ''
  type: Corporate Website
  url: https://www.tenetcorporate.com
- title: ''
  type: Investor Relations
  url: https://ir.tenethealth.com
- title: ''
  type: Press Room
  url: https://www.tenethealth.com/news
- title: ''
  type: Careers
  url: https://careers.tenethealth.com
- title: ''
  type: Conifer Health Solutions
  url: https://www.coniferhealth.com
- title: ''
  type: USPI
  url: https://www.uspi.com
- title: ''
  type: JSON-LD
  url: json-ld/tenet-healthcare-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/tenet-healthcare-patient-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tenet-healthcare-appointment-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/tenet-healthcare-patient-structure.json
- title: ''
  type: SpectralRules
  url: rules/tenet-healthcare-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/patient-care.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/tenet-healthcare-vocabulary.yml
created: '2026-03-21'
description: Tenet Healthcare is a diversified healthcare services company and Fortune 500 organization operating regionally focused, integrated healthcare delivery networks. The company operates acute care hospitals, ambulatory surgery centers (ASCs), and physician practices across the United States through United Surgical Partners International (USPI) and Tenet Health. Tenet also provides revenue cycle management services through Conifer Health Solutions.
features: []
image: ''
integrations: []
jsonld:
- class_count: 10
  name: Tenet Healthcare Context
  property_count: 12
  slug: tenet-healthcare-context
layout: provider
modified: '2026-05-03'
name: Tenet Healthcare
rules:
- name: Tenet Healthcare API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 3
    warn: 5
  slug: tenet-healthcare-rules
skills: []
slug: tenet-healthcare
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Tenet Healthcare\ndescription: >-\n  Tenet Healthcare is a diversified healthcare services company and Fortune 500 organization\n  operating regionally focused, integrated healthcare delivery networks. The company operates\n  acute care hospitals, ambulatory surgery centers (ASCs), and physician practices across the\n  United States through United Surgical Partners International (USPI) and Tenet Health.\n  Tenet also provides revenue cycle management services through Conifer Health Solutions.\nurl: https://raw.githubusercontent.com/api-evangelist/tenet-healthcare/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Healthcare\n  - Hospitals\n  - Ambulatory Surgery Centers\n  - Revenue Cycle Management\n  - Fortune 500\n\napis:\n  - name: Conifer Health Solutions Revenue Cycle API\n    description: >-\n      Revenue cycle management API from Conifer Health Solutions, a Tenet Healthcare\n      subsidiary providing\
  \ end-to-end RCM services including patient access, health\n      information management, patient financial services, and clinical revenue integrity\n      for hospitals and health systems.\n    humanURL: https://www.coniferhealth.com/\n    baseURL: https://api.coniferhealth.com\n    tags:\n      - Revenue Cycle Management\n      - Healthcare Finance\n      - Patient Access\n      - Claims Management\n      - Healthcare\n    properties:\n      - type: Website\n        url: https://www.coniferhealth.com/\n      - type: Documentation\n        url: https://www.coniferhealth.com/services/\n\n  - name: USPI Ambulatory Surgery Center API\n    description: >-\n      United Surgical Partners International (USPI) integration APIs for ambulatory\n      surgery center scheduling, patient registration, procedure management, and\n      clinical data exchange. USPI operates over 600 ambulatory surgery centers and\n      surgical hospitals across the United States.\n    humanURL: https://www.uspi.com/\n\
  \    baseURL: https://api.uspi.com\n    tags:\n      - Ambulatory Surgery Centers\n      - Surgical Scheduling\n      - Patient Registration\n      - Healthcare\n    properties:\n      - type: Website\n        url: https://www.uspi.com/\n      - type: Documentation\n        url: https://www.uspi.com/for-physicians/\n\n  - name: Tenet Health Patient Portal API\n    description: >-\n      Patient-facing digital health API enabling access to medical records, appointment\n      scheduling, test results, care team communications, and bill payment across\n      Tenet Health hospital network. Integrates with MyChart and other patient portal\n      platforms. HL7 FHIR R4 compatible.\n    humanURL: https://www.tenethealth.com/patients\n    baseURL: https://api.tenethealth.com/patient\n    tags:\n      - Patient Portal\n      - Medical Records\n      - Appointment Scheduling\n      - FHIR\n      - Healthcare\n    properties:\n      - type: Website\n        url: https://www.tenethealth.com/patients\n\
  \      - type: FHIR Standard\n        url: https://hl7.org/fhir/R4/\n      - type: OpenAPI\n        url: openapi/tenet-healthcare-fhir-openapi.yml\n\ncommon:\n  - type: Website\n    url: https://www.tenethealth.com\n  - type: Corporate Website\n    url: https://www.tenetcorporate.com\n  - type: Investor Relations\n    url: https://ir.tenethealth.com\n  - type: Press Room\n    url: https://www.tenethealth.com/news\n  - type: Careers\n    url: https://careers.tenethealth.com\n  - type: Conifer Health Solutions\n    url: https://www.coniferhealth.com\n  - type: USPI\n    url: https://www.uspi.com\n  - type: JSON-LD\n    url: json-ld/tenet-healthcare-context.jsonld\n  - type: JSONSchema\n    url: json-schema/tenet-healthcare-patient-schema.json\n  - type: JSONSchema\n    url: json-schema/tenet-healthcare-appointment-schema.json\n  - type: JSONStructure\n    url: json-structure/tenet-healthcare-patient-structure.json\n  - type: SpectralRules\n    url: rules/tenet-healthcare-rules.yml\n  - type:\
  \ NaftikoCapabilities\n    url: capabilities/patient-care.yaml\n  - type: Vocabulary\n    url: vocabulary/tenet-healthcare-vocabulary.yml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tenet-healthcare/refs/heads/main/apis.yml
tags:
- Healthcare
- Hospitals
- Ambulatory Surgery Centers
- Revenue Cycle Management
- Fortune 500
url: https://raw.githubusercontent.com/api-evangelist/tenet-healthcare/refs/heads/main/apis.yml
use_cases: []
---
