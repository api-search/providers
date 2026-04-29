---
api_count: 1
apis:
- description: CharmHealth EHR FHIR API conforms to FHIR R4 (4.0.1) and the US Core STU 3.1.1 Implementation Guide. It supports 30+ FHIR resources covering clinical (AllergyIntolerance, Condition, Procedure, Immuniz
  name: CharmHealth FHIR API
  slug: fhir-api
common:
- title: ''
  type: Website
  url: https://www.charmhealth.com/
- title: ''
  type: Documentation
  url: https://www.charmhealth.com/resources/fhir/index.html
- title: ''
  type: Developer
  url: https://www.charmhealth.com/developer/
- title: ''
  type: News
  url: https://www.charmhealth.com/ehr/ehr-trade-shows.html
- title: ''
  type: PressReleases
  url: https://www.charmhealth.com/ehr/press-release.html
- title: ''
  type: CaseStudies
  url: https://casestudy.charmhealth.com/charmhealth-case-study-landing-page/
- title: ''
  type: Blog
  url: https://www.charmhealth.com/blog/
- title: ''
  type: Newsletter
  url: https://www.charmhealth.com/newsletter/
- title: ''
  type: Webinars
  url: https://www.charmhealth.com/ehr/webinar.html
- title: ''
  type: Pricing
  url: https://www.charmhealth.com/ehr/ehr-pricing.html
- title: ''
  type: Support
  url: https://www.charmhealth.com/support/
- title: ''
  type: TermsOfService
  url: https://www.charmhealth.com/ehr/termsofservice.html
- title: ''
  type: PrivacyPolicy
  url: https://www.charmhealth.com/privacy-policy.html
- title: ''
  type: JSONLD
  url: json-ld/charmhealth-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/charmhealth-patient-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/charmhealth-observation-schema.json
created: '2025-02-21'
description: CharmHealth is a healthcare technology platform offering Electronic Health Records (EHR), Practice Management, Revenue Cycle Management, Patient Engagement, and TeleHealth tooling. CharmHealth exposes an HL7 FHIR R4 API conformant to the US Core Implementation Guide that lets third-party applications query patient medical records, manage clinical resources, and integrate with the EHR using SMART on FHIR OAuth 2.0 authorization.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Charmhealth Context
  property_count: 6
  slug: charmhealth-context
layout: provider
modified: '2026-04-23'
name: CharmHealth
skills: []
slug: charmhealth
solutions: []
source_yaml: "aid: charmhealth\nname: CharmHealth\ndescription: >-\n  CharmHealth is a healthcare technology platform offering Electronic Health\n  Records (EHR), Practice Management, Revenue Cycle Management, Patient\n  Engagement, and TeleHealth tooling. CharmHealth exposes an HL7 FHIR R4\n  API conformant to the US Core Implementation Guide that lets third-party\n  applications query patient medical records, manage clinical resources,\n  and integrate with the EHR using SMART on FHIR OAuth 2.0 authorization.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/charmhealth/refs/heads/main/apis.yml\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - EHR\n  - EMR\n  - FHIR\n  - Healthcare\n  - HL7\n  - Patient Engagement\n  - Patients\n  - SMART on FHIR\n  - US Core\ncreated: '2025-02-21'\nmodified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid: charmhealth:fhir-api\n    name:\
  \ CharmHealth FHIR API\n    description: >-\n      CharmHealth EHR FHIR API conforms to FHIR R4 (4.0.1) and the US Core\n      STU 3.1.1 Implementation Guide. It supports 30+ FHIR resources covering\n      clinical (AllergyIntolerance, Condition, Procedure, Immunization,\n      MedicationRequest), care coordination (CarePlan, CareTeam, Goal,\n      Encounter), administrative (Patient, Practitioner, Organization,\n      Location, Appointment), diagnostic (DiagnosticReport, Observation),\n      and documentation resources (DocumentReference, QuestionnaireResponse,\n      Provenance). Authentication uses SMART on FHIR with OAuth 2.0\n      authorization code flow, PKCE for public clients, and JWT-assertion\n      backend services authorization for system access.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.charmhealth.com/resources/fhir/index.html\n    baseURL: https://ehr2.charmtracker.com/api/ehr/v2/fhir\n    tags:\n  \
  \    - FHIR\n      - HL7\n      - Healthcare\n      - SMART on FHIR\n      - US Core\n    properties:\n      - type: Documentation\n        url: https://www.charmhealth.com/resources/fhir/index.html\n      - type: Authentication\n        url: https://www.charmhealth.com/resources/fhir/authorization.html\n      - type: SMARTOnFHIR\n        url: https://www.charmhealth.com/resources/fhir/smart-on-fhir.html\n      - type: BulkExport\n        url: https://www.charmhealth.com/resources/fhir/bulk-data.html\n      - type: USCore\n        url: https://www.hl7.org/fhir/us/core/\n      - type: OpenAPI\n        url: openapi/charmhealth-fhir-api-openapi.yml\n      - type: Spectral\n        url: spectral/charmhealth-spectral.yml\ncommon:\n  - type: Website\n    url: https://www.charmhealth.com/\n  - type: Documentation\n    url: https://www.charmhealth.com/resources/fhir/index.html\n  - type: Developer\n    url: https://www.charmhealth.com/developer/\n  - type: News\n    url: https://www.charmhealth.com/ehr/ehr-trade-shows.html\n\
  \  - type: PressReleases\n    url: https://www.charmhealth.com/ehr/press-release.html\n  - type: CaseStudies\n    url: https://casestudy.charmhealth.com/charmhealth-case-study-landing-page/\n  - type: Blog\n    url: https://www.charmhealth.com/blog/\n  - type: Newsletter\n    url: https://www.charmhealth.com/newsletter/\n  - type: Webinars\n    url: https://www.charmhealth.com/ehr/webinar.html\n  - type: Pricing\n    url: https://www.charmhealth.com/ehr/ehr-pricing.html\n  - type: Support\n    url: https://www.charmhealth.com/support/\n  - type: TermsOfService\n    url: https://www.charmhealth.com/ehr/termsofservice.html\n  - type: PrivacyPolicy\n    url: https://www.charmhealth.com/privacy-policy.html\n  - type: JSONLD\n    url: json-ld/charmhealth-context.jsonld\n  - type: JSONSchema\n    url: json-schema/charmhealth-patient-schema.json\n  - type: JSONSchema\n    url: json-schema/charmhealth-observation-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/charmhealth/refs/heads/main/apis.yml
tags:
- EHR
- EMR
- FHIR
- Healthcare
- HL7
- Patient Engagement
- Patients
- SMART on FHIR
- US Core
url: https://raw.githubusercontent.com/api-evangelist/charmhealth/refs/heads/main/apis.yml
use_cases: []
---
