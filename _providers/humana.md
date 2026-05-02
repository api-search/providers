---
api_count: 4
apis:
- description: FHIR R4-compliant API surface providing clinical resources for member health data, including AllergyIntolerance, CarePlan, CareTeam, Condition, Goal, Immunization, Observation, and Procedure resources
  name: Humana FHIR Clinical Data API
  slug: humana-fhir-clinical-api
- description: FHIR R4-compliant API surface for medication-related resources including Medication, MedicationKnowledge, MedicationRequest, drug formulary List resources, and supporting payer data.
  name: Humana FHIR Medication API
  slug: humana-fhir-medication-api
- description: FHIR R4-compliant API surface for insurance coverage data, including Coverage, ExplanationOfBenefits, and InsurancePlan resources used to satisfy CMS Patient Access and Provider Directory rules.
  name: Humana FHIR Coverage and Benefits API
  slug: humana-fhir-coverage-api
- description: FHIR R4-compliant API surface for provider directory information, including Patient, Practitioner, PractitionerRole, Organization, Location, and DocumentReference resources.
  name: Humana FHIR Provider Directory API
  slug: humana-fhir-provider-directory-api
common:
- title: ''
  type: Portal
  url: https://developers.humana.com/
- title: ''
  type: Website
  url: https://www.humana.com/
- title: ''
  type: Privacy Policy
  url: https://www.humana.com/legal/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.humana.com/legal/terms-conditions
- title: ''
  type: Rules
  url: https://raw.githubusercontent.com/api-evangelist/humana/refs/heads/main/humana-rules.yml
created: '2025-01-07'
description: Humana is a U.S. health insurance company that provides Medicare, Medicaid, and employer-sponsored health insurance plans, along with wellness programs and healthcare services. Humana publishes a suite of FHIR-compliant APIs that give third-party applications access to member health data, coverage information, drug formularies, and provider directories under CMS interoperability rules.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Humana
skills: []
slug: humana
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: humana\nname: Humana\ndescription: >-\n  Humana is a U.S. health insurance company that provides Medicare,\n  Medicaid, and employer-sponsored health insurance plans, along with\n  wellness programs and healthcare services. Humana publishes a suite of\n  FHIR-compliant APIs that give third-party applications access to member\n  health data, coverage information, drug formularies, and provider\n  directories under CMS interoperability rules.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/humana/refs/heads/main/apis.yml\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - FHIR\n  - Health Insurance\n  - Healthcare\n  - Interoperability\n  - Medicare\ncreated: '2025-01-07'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: humana:humana-fhir-clinical-api\n    name: Humana FHIR Clinical Data API\n    description: >-\n      FHIR R4-compliant API surface providing clinical resources for member\n\
  \      health data, including AllergyIntolerance, CarePlan, CareTeam,\n      Condition, Goal, Immunization, Observation, and Procedure resources.\n    humanURL: https://developers.humana.com/apis/allergyintolerance-api/doc\n    baseURL: https://fhir.humana.com/api\n    tags:\n      - Clinical Data\n      - FHIR\n      - Healthcare\n    properties:\n      - type: Documentation\n        url: https://developers.humana.com/apis/allergyintolerance-api/doc\n      - type: CapabilityStatement\n        url: https://fhir.humana.com/api/metadata\n      - type: Sandbox\n        url: https://sandbox-fhir.humana.com/api/\n      - type: Getting Started\n        url: https://developers.humana.com/\n  - aid: humana:humana-fhir-medication-api\n    name: Humana FHIR Medication API\n    description: >-\n      FHIR R4-compliant API surface for medication-related resources including\n      Medication, MedicationKnowledge, MedicationRequest, drug formulary\n      List resources, and supporting payer data.\n\
  \    humanURL: https://developers.humana.com/\n    baseURL: https://fhir.humana.com/api\n    tags:\n      - FHIR\n      - Formulary\n      - Medications\n    properties:\n      - type: Documentation\n        url: https://developers.humana.com/\n      - type: CapabilityStatement\n        url: https://fhir.humana.com/api/metadata\n      - type: Sandbox\n        url: https://sandbox-fhir.humana.com/api/\n  - aid: humana:humana-fhir-coverage-api\n    name: Humana FHIR Coverage and Benefits API\n    description: >-\n      FHIR R4-compliant API surface for insurance coverage data, including\n      Coverage, ExplanationOfBenefits, and InsurancePlan resources used to\n      satisfy CMS Patient Access and Provider Directory rules.\n    humanURL: https://developers.humana.com/\n    baseURL: https://fhir.humana.com/api\n    tags:\n      - Coverage\n      - FHIR\n      - Insurance\n    properties:\n      - type: Documentation\n        url: https://developers.humana.com/\n      - type: CapabilityStatement\n\
  \        url: https://fhir.humana.com/api/metadata\n      - type: Sandbox\n        url: https://sandbox-fhir.humana.com/api/\n  - aid: humana:humana-fhir-provider-directory-api\n    name: Humana FHIR Provider Directory API\n    description: >-\n      FHIR R4-compliant API surface for provider directory information,\n      including Patient, Practitioner, PractitionerRole, Organization,\n      Location, and DocumentReference resources.\n    humanURL: https://developers.humana.com/\n    baseURL: https://fhir.humana.com/api\n    tags:\n      - FHIR\n      - Provider Directory\n    properties:\n      - type: Documentation\n        url: https://developers.humana.com/\n      - type: CapabilityStatement\n        url: https://fhir.humana.com/api/metadata\n      - type: Sandbox\n        url: https://sandbox-fhir.humana.com/api/\ncommon:\n  - type: Portal\n    url: https://developers.humana.com/\n  - type: Website\n    url: https://www.humana.com/\n  - type: Privacy Policy\n    url: https://www.humana.com/legal/privacy-policy\n\
  \  - type: Terms of Service\n    url: https://www.humana.com/legal/terms-conditions\n  - type: Rules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/humana/refs/heads/main/humana-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/humana/refs/heads/main/apis.yml
tags:
- FHIR
- Health Insurance
- Healthcare
- Interoperability
- Medicare
url: https://raw.githubusercontent.com/api-evangelist/humana/refs/heads/main/apis.yml
use_cases: []
---
