---
api_count: 2
api_specs:
- filename: chs-patient-access-api-openapi.yml
  format: yaml
  label: Community Health Systems Patient Access API
  slug: patient-access-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/community-health-systems/refs/heads/main/openapi/chs-patient-access-api-openapi.yml
apis:
- description: FHIR R4 API published pursuant to the CMS Interoperability and Patient Access Final Rule (CMS-9115-F). Allows third-party applications, with the patient's authorization, to retrieve adjudicated claims
  name: Community Health Systems Patient Access API
  slug: patient-access-api
- description: FHIR R4 read API exposing provider and pharmacy directory data in compliance with CMS interoperability requirements. Third-party applications can search Practitioner, Organization, and Location resour
  name: Community Health Systems Provider Directory API
  slug: provider-directory-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.chs.net
- title: ''
  type: PatientPortal
  url: https://www.chs.net/patients-visitors/
- title: ''
  type: Investors
  url: https://www.chs.net/investors/
- title: ''
  type: PrivacyPolicy
  url: https://www.chs.net/privacy-statement/
- title: ''
  type: CMSInteroperability
  url: https://www.cms.gov/regulations-and-guidance/guidance/interoperability/index
- title: ''
  type: HL7FHIRR4
  url: https://hl7.org/fhir/R4/
- title: ''
  type: JSON-LD
  url: json-ld/community-health-systems-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/chs-fhir-bundle-schema.json
- title: ''
  type: Spectral
  url: rules/community-health-systems-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: capabilities/community-health-systems-fhir-capabilities.yml
created: '2026-03-21'
description: Community Health Systems (CHS) is a Fortune 500 hospital operator that owns, leases, and operates general acute care hospitals across the United States. In compliance with the CMS Interoperability and Patient Access Final Rule (CMS-9115-F), CHS publishes FHIR R4 healthcare interoperability APIs that allow third-party applications to access patient demographics and clinical data, adjudicated claims and encounters, formulary information, and provider directory data. The APIs use the HL7 FHIR R4 standard and SMART-on-FHIR authorization for patient-scoped access.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Community Health Systems Context
  property_count: 5
  slug: community-health-systems-context
layout: provider
modified: '2026-04-26'
name: Community Health Systems
rules:
- name: Community Health Systems API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 4
  slug: community-health-systems-rules
skills: []
slug: community-health-systems
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: community-health-systems\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/community-health-systems/refs/heads/main/apis.yml\nname: Community Health Systems\ntags:\n  - CMS-9115-F\n  - FHIR\n  - Healthcare\n  - Hospitals\n  - Interoperability\n  - Patient Access\n  - Provider Directory\n  - SMART-on-FHIR\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nx-type: company\ncreated: '2026-03-21'\nmodified: '2026-04-26'\nposition: Consumer\ndescription: >-\n  Community Health Systems (CHS) is a Fortune 500 hospital operator that\n  owns, leases, and operates general acute care hospitals across the\n  United States. In compliance with the CMS Interoperability and Patient\n  Access Final Rule (CMS-9115-F), CHS publishes FHIR R4 healthcare\n  interoperability APIs that allow third-party applications to access\n  patient demographics and clinical data, adjudicated claims and\n  encounters, formulary information,\
  \ and provider directory data. The\n  APIs use the HL7 FHIR R4 standard and SMART-on-FHIR authorization for\n  patient-scoped access.\napis:\n  - aid: community-health-systems:patient-access-api\n    name: Community Health Systems Patient Access API\n    tags:\n      - CMS-9115-F\n      - FHIR\n      - Healthcare\n      - Interoperability\n      - Patient Access\n      - SMART-on-FHIR\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.chs.net/fhir/r4\n    humanURL: https://www.chs.net\n    properties:\n      - url: https://www.chs.net\n        type: Documentation\n      - url: https://www.cms.gov/regulations-and-guidance/guidance/interoperability/index\n        type: CMSFinalRule\n      - url: openapi/chs-patient-access-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      FHIR R4 API published pursuant to the CMS Interoperability and\n      Patient Access Final Rule (CMS-9115-F). Allows third-party\n      applications,\
  \ with the patient's authorization, to retrieve\n      adjudicated claims and encounters (ExplanationOfBenefit),\n      formulary and medication data (MedicationKnowledge), and clinical\n      data (Patient and related resources). Authentication uses\n      SMART-on-FHIR OAuth2 with patient/launch scopes.\n    x-features:\n      - FHIR R4 conformance\n      - SMART-on-FHIR OAuth2 authorization-code flow\n      - patient/*.read and launch/patient scopes\n      - Patient, ExplanationOfBenefit, MedicationKnowledge resource endpoints\n      - Bundle search-set responses (application/fhir+json)\n    x-use-cases:\n      - Patient-authorized third-party app access to claims\n      - Personal-health-record (PHR) integration for CHS patients\n      - Pharmacy and formulary lookups for member-facing apps\n      - Population-health analytics with patient consent\n  - aid: community-health-systems:provider-directory-api\n    name: Community Health Systems Provider Directory API\n    tags:\n      -\
  \ CMS-9115-F\n      - FHIR\n      - Healthcare\n      - Interoperability\n      - Provider Directory\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.chs.net/fhir/r4\n    humanURL: https://www.chs.net\n    properties:\n      - url: https://www.chs.net\n        type: Documentation\n      - url: https://www.cms.gov/regulations-and-guidance/guidance/interoperability/index\n        type: CMSFinalRule\n    description: >-\n      FHIR R4 read API exposing provider and pharmacy directory data in\n      compliance with CMS interoperability requirements. Third-party\n      applications can search Practitioner, Organization, and Location\n      resources without patient consent (no PHI is exposed by these\n      directory endpoints).\n    x-features:\n      - FHIR R4 Practitioner, Organization, Location resources\n      - Public read access (no patient consent required)\n      - Search by name, specialty, location\n    x-use-cases:\n\
  \      - Public provider/pharmacy directory lookup\n      - Network adequacy and accessibility reporting\n      - Care coordination and referral apps\ncommon:\n  - type: Website\n    url: https://www.chs.net\n  - type: PatientPortal\n    url: https://www.chs.net/patients-visitors/\n  - type: Investors\n    url: https://www.chs.net/investors/\n  - type: PrivacyPolicy\n    url: https://www.chs.net/privacy-statement/\n  - type: CMSInteroperability\n    url: https://www.cms.gov/regulations-and-guidance/guidance/interoperability/index\n  - type: HL7FHIRR4\n    url: https://hl7.org/fhir/R4/\n  - url: json-ld/community-health-systems-context.jsonld\n    type: JSON-LD\n  - url: json-schema/chs-fhir-bundle-schema.json\n    type: JSONSchema\n  - url: rules/community-health-systems-rules.yml\n    type: Spectral\n  - url: capabilities/community-health-systems-fhir-capabilities.yml\n    type: NaftikoCapabilities\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion:\
  \ '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/community-health-systems/refs/heads/main/apis.yml
tags:
- CMS-9115-F
- FHIR
- Healthcare
- Hospitals
- Interoperability
- Patient Access
- Provider Directory
- SMART-on-FHIR
url: https://raw.githubusercontent.com/api-evangelist/community-health-systems/refs/heads/main/apis.yml
use_cases: []
---
