---
api_count: 1
api_specs:
- filename: unitedhealth-optum-api-openapi.yml
  format: yaml
  label: UnitedHealth Group Optum API
  slug: optum-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unitedhealth/refs/heads/main/openapi/unitedhealth-optum-api-openapi.yml
apis:
- description: The UnitedHealth Group interoperability APIs provide FHIR R4-compliant access to healthcare data including patient records, claims history, provider directories, and formulary information in complianc
  name: UnitedHealth Group Optum API
  slug: optum-api
capabilities:
- description: Workflow capability for CMS-compliant health data interoperability using UnitedHealth Group FHIR R4 APIs. Enables patient portals, third-party health apps, care management platforms, and provider tool
  name: UnitedHealth Group Health Data Interoperability
  slug: health-data-interoperability
common: []
created: '2026-03-21'
description: UnitedHealth Group is a diversified health care company with two distinct platforms, UnitedHealthcare for health benefits and Optum for health services, serving more than 100 million people worldwide. The company offers FHIR R4-compliant Interoperability APIs through the Optum platform, providing patient access to health records, claims history, provider directory, and drug formulary data in compliance with CMS Interoperability and Patient Access final rule (CMS-9115-F) and HL7 FHIR standards.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Unitedhealth Optum Api Context
  property_count: 1
  slug: unitedhealth-optum-api-context
layout: provider
modified: '2026-05-03'
name: UnitedHealth Group
rules:
- name: UnitedHealth Group API Rules
  rule_count: 26
  severity_counts:
    error: 13
    hint: 0
    info: 2
    warn: 11
  slug: unitedhealth-spectral-rules
skills: []
slug: unitedhealth
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: unitedhealth\nurl: https://raw.githubusercontent.com/api-evangelist/unitedhealth/refs/heads/main/apis.yml\nname: UnitedHealth Group\ndescription: >-\n  UnitedHealth Group is a diversified health care company with two distinct platforms,\n  UnitedHealthcare for health benefits and Optum for health services, serving more than\n  100 million people worldwide. The company offers FHIR R4-compliant Interoperability\n  APIs through the Optum platform, providing patient access to health records, claims\n  history, provider directory, and drug formulary data in compliance with CMS\n  Interoperability and Patient Access final rule (CMS-9115-F) and HL7 FHIR standards.\ntags:\n  - Healthcare\n  - Health Insurance\n  - FHIR\n  - Claims\n  - Interoperability\ntype: Company\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-21'\nmodified: '2026-05-03'\nposition: Consuming\nspecificationVersion: '0.19'\n\napis:\n  -\
  \ aid: unitedhealth:optum-api\n    name: UnitedHealth Group Optum API\n    tags:\n      - Healthcare\n      - FHIR\n      - Patient Access\n      - Provider Directory\n      - Drug Formulary\n      - CMS Interoperability\n    baseURL: https://api.uhc.com/fhir/R4\n    humanURL: https://www.uhc.com/legal/interoperability-apis\n    description: >-\n      The UnitedHealth Group interoperability APIs provide FHIR R4-compliant access to\n      healthcare data including patient records, claims history, provider directories, and\n      formulary information in compliance with CMS interoperability rules. Operates under\n      the Optum platform serving UnitedHealthcare, Medicare & Retirement, Community &\n      State, and Optum health services.\n    properties:\n      - url: https://www.uhc.com/legal/interoperability-apis\n        type: Documentation\n      - url: openapi/unitedhealth-optum-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/optum-fhir-bundle-schema.json\n        type:\
  \ Schema\n      - url: json-schema/optum-fhir-patient-schema.json\n        type: Schema\n      - url: json-ld/unitedhealth-optum-api-context.jsonld\n        type: JSON-LD Context\n      - url: examples/optum-fhir-patient-example.json\n        type: Example\n\nfeatures:\n  - name: FHIR R4 Patient Access API\n    description: >-\n      CMS-mandated FHIR R4 Patient Access API providing members and third-party\n      applications with access to claims, EOBs, coverage details, and clinical data.\n  - name: Provider Directory API\n    description: >-\n      FHIR R4 Provider Directory implementing Da Vinci PDex Plan Net IG for searching\n      UnitedHealth Group network practitioners and organizations.\n  - name: Drug Formulary API\n    description: >-\n      FHIR R4 Drug Formulary API implementing Da Vinci Drug Formulary IG for accessing\n      prescription drug coverage tiers, prior auth requirements, and quantity limits.\n  - name: Claims History Access\n    description: >-\n      FHIR ExplanationOfBenefit\
  \ resources providing comprehensive claims history\n      including service details, diagnosis codes, and payment adjudication.\n  - name: Clinical Data Exchange\n    description: >-\n      FHIR Condition and clinical data resources for member health history as\n      reflected in claims and available clinical records.\n  - name: Coverage Information\n    description: >-\n      FHIR Coverage resources for current and historical insurance coverage details\n      across UnitedHealthcare commercial, Medicare, and Medicaid plans.\n\nuseCases:\n  - name: Patient Portal Health Data\n    description: >-\n      Enable patient portals to display complete health records including claims,\n      coverage, and conditions using FHIR Patient Access APIs.\n  - name: Care Coordination Apps\n    description: >-\n      Build care management tools that aggregate member health history, coverage,\n      and clinical data for population health management.\n  - name: Provider Network Search\n    description:\
  \ >-\n      Develop provider search applications using the FHIR Provider Directory to\n      help members find in-network physicians and specialists.\n  - name: Prescription Benefit Transparency\n    description: >-\n      Integrate drug formulary data into clinical and patient-facing applications\n      to show coverage tiers and prior authorization requirements.\n  - name: CMS Compliance Applications\n    description: >-\n      Build CMS-compliant third-party applications leveraging UnitedHealth Group's\n      FHIR R4 interoperability infrastructure for data portability.\n  - name: Claims Analytics\n    description: >-\n      Access structured claims data as FHIR ExplanationOfBenefit resources for\n      population health analytics and care gap identification.\n\nintegrations:\n  - name: Apple Health Records\n    description: >-\n      UnitedHealth Group FHIR Patient Access API integrates with Apple Health\n      Records for member health data access on iOS devices.\n  - name: CommonWell\
  \ Health Alliance\n    description: >-\n      UnitedHealth Group participates in CommonWell for FHIR-based health information\n      exchange across provider networks.\n  - name: Carequality\n    description: >-\n      FHIR data exchange integration through Carequality framework for nationwide\n      health information network connectivity.\n  - name: Da Vinci Project\n    description: >-\n      UnitedHealth Group implements Da Vinci IGs for payer data exchange including\n      PDex Plan Net for provider directory and Drug Formulary IG.\n\nartifacts:\n  openapi:\n    - name: UnitedHealth Group Optum API\n      url: openapi/unitedhealth-optum-api-openapi.yml\n\n  jsonSchema:\n    - url: json-schema/optum-fhir-bundle-schema.json\n    - url: json-schema/optum-fhir-patient-schema.json\n    - url: json-schema/optum-fhir-explanation-of-benefit-schema.json\n    - url: json-schema/optum-fhir-coverage-schema.json\n    - url: json-schema/optum-fhir-practitioner-schema.json\n    - url: json-schema/optum-fhir-medication-knowledge-schema.json\n\
  \n  jsonStructure:\n    - url: json-structure/optum-fhir-bundle-structure.json\n    - url: json-structure/optum-fhir-patient-structure.json\n    - url: json-structure/optum-fhir-explanation-of-benefit-structure.json\n    - url: json-structure/optum-fhir-coverage-structure.json\n    - url: json-structure/optum-fhir-practitioner-structure.json\n    - url: json-structure/optum-fhir-medication-knowledge-structure.json\n\n  jsonLd:\n    - url: json-ld/unitedhealth-optum-api-context.jsonld\n\n  examples:\n    - url: examples/optum-fhir-patient-example.json\n    - url: examples/optum-fhir-bundle-example.json\n    - url: examples/optum-fhir-coverage-example.json\n    - url: examples/optum-fhir-practitioner-example.json\n    - url: examples/optum-fhir-medication-knowledge-example.json\n\n  spectralRules:\n    - url: rules/unitedhealth-spectral-rules.yml\n\n  capabilities:\n    shared:\n      - url: capabilities/shared/optum-api.yaml\n    workflows:\n      - url: capabilities/health-data-interoperability.yaml\n\
  \n  vocabulary:\n    - url: vocabulary/unitedhealth-vocabulary.yaml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/unitedhealth/refs/heads/main/apis.yml
tags:
- Healthcare
- Health Insurance
- FHIR
- Claims
- Interoperability
url: https://raw.githubusercontent.com/api-evangelist/unitedhealth/refs/heads/main/apis.yml
use_cases: []
---
