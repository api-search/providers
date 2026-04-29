---
api_count: 6
apis:
- description: The Oracle Health Millennium Platform FHIR R4 API provides OAuth 2.0-secured access to Cerner Millennium EHR data in the HL7 FHIR R4 format, exposing USCDI-aligned resources such as Patient, Practitio
  name: Oracle Health Millennium Platform FHIR R4 API
  slug: oracle-health-fhir-r4-api
- description: The Cerner Millennium DSTU2 FHIR API supports legacy SMART on FHIR applications and integrations with Meaningful Use 2015 CEHRT certification criteria, and remains available alongside the newer R4 imp
  name: Oracle Health Millennium FHIR DSTU2 API
  slug: oracle-health-fhir-dstu2-api
- description: 'The Oracle Health Code Console (formerly Cerner Code) is the developer portal used to register SMART on FHIR and system-level applications, configure redirect URIs and launch parameters, manage OAuth '
  name: Oracle Health Code Console (Developer Portal)
  slug: oracle-health-code-console
- description: Oracle Health Millennium supports the HL7 Bulk Data Access (Flat FHIR) specification for exporting group-level patient data in NDJSON format for population health, research, and payer-provider data ex
  name: Oracle Health Millennium Bulk FHIR API
  slug: oracle-health-bulk-fhir-api
- description: Cerner CareAware provides device and third-party application integration APIs for medical device data capture, bi-directional HL7 v2 messaging, and workflow embedding into Millennium, supporting medic
  name: Cerner CareAware Integration APIs
  slug: cerner-careaware
- description: Oracle Health implements the SMART on FHIR App Launch framework (standalone and EHR-launch) with OpenID Connect identity tokens, enabling third-party clinician and patient-facing applications to embed
  name: Oracle Health SMART on FHIR App Launch
  slug: oracle-health-smart-on-fhir
common:
- title: ''
  type: Website
  url: https://www.cerner.com
- title: ''
  type: Corporate
  url: https://www.oracle.com/health/
- title: ''
  type: Developer
  url: https://www.oracle.com/health/developer/
- title: ''
  type: APIReference
  url: https://docs.oracle.com/en/industries/health/millennium-platform-apis/index.html
- title: ''
  type: FHIR
  url: https://fhir.cerner.com/
- title: ''
  type: CodeConsole
  url: https://code.cerner.com/
- title: ''
  type: OpenSource
  url: https://github.com/cerner
- title: ''
  type: Privacy Policy
  url: https://www.oracle.com/legal/privacy/
created: '2026-03-23'
description: Cerner is a global healthcare technology company that designs and develops electronic health record (EHR) and health information technology solutions for hospitals, clinics, and integrated delivery networks. Cerner was acquired by Oracle in June 2022 and is now branded as Oracle Health, with the Cerner Millennium EHR platform's developer program operating as the Oracle Health Developer Program. Millennium exposes HL7 FHIR R4 and DSTU2 APIs, SMART on FHIR app launching, Bulk FHIR, the CareAware device and integration APIs, and the Code Console developer portal for registering applications and obtaining sandbox and production credentials.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Cerner (Oracle Health)
skills: []
slug: cerner
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cerner\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cerner/refs/heads/main/apis.yml\nname: Cerner (Oracle Health)\ntags:\n  - Cerner Millennium\n  - Code Console\n  - EHR\n  - Electronic Health Records\n  - FHIR\n  - HL7\n  - Healthcare\n  - Interoperability\n  - OAuth 2.0\n  - Oracle Health\n  - Patient Access\n  - Provider Directory\n  - SMART on FHIR\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-23'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  Cerner is a global healthcare technology company that designs and develops\n  electronic health record (EHR) and health information technology solutions\n  for hospitals, clinics, and integrated delivery networks. Cerner was\n  acquired by Oracle in June 2022 and is now branded as Oracle Health, with\n  the Cerner Millennium EHR platform's developer program operating as the\n \
  \ Oracle Health Developer Program. Millennium exposes HL7 FHIR R4 and DSTU2\n  APIs, SMART on FHIR app launching, Bulk FHIR, the CareAware device and\n  integration APIs, and the Code Console developer portal for registering\n  applications and obtaining sandbox and production credentials.\napis:\n  - aid: cerner:oracle-health-fhir-r4-api\n    name: Oracle Health Millennium Platform FHIR R4 API\n    tags:\n      - CMS Interoperability\n      - FHIR\n      - HL7\n      - Patient Access\n      - R4\n      - USCDI\n    humanURL: https://docs.oracle.com/en/industries/health/millennium-platform-apis/mfrap/r4_overview.html\n    properties:\n      - url: https://docs.oracle.com/en/industries/health/millennium-platform-apis/mfrap/r4_overview.html\n        type: Documentation\n      - url: https://docs.oracle.com/en/industries/health/millennium-platform-apis/index.html\n        type: Portal\n      - url: https://www.oracle.com/health/developer/\n        type: DeveloperProgram\n    description:\
  \ >-\n      The Oracle Health Millennium Platform FHIR R4 API provides\n      OAuth 2.0-secured access to Cerner Millennium EHR data in the HL7\n      FHIR R4 format, exposing USCDI-aligned resources such as Patient,\n      Practitioner, Observation, Condition, MedicationRequest,\n      DocumentReference, and Encounter for patient-access apps, provider\n      apps, and interoperability partners.\n  - aid: cerner:oracle-health-fhir-dstu2-api\n    name: Oracle Health Millennium FHIR DSTU2 API\n    tags:\n      - DSTU2\n      - FHIR\n      - Legacy\n      - SMART on FHIR\n    humanURL: https://fhir.cerner.com/millennium/dstu2/\n    properties:\n      - url: https://fhir.cerner.com/millennium/dstu2/\n        type: Documentation\n      - url: https://fhir.cerner.com/\n        type: Portal\n    description: >-\n      The Cerner Millennium DSTU2 FHIR API supports legacy SMART on FHIR\n      applications and integrations with Meaningful Use 2015 CEHRT\n      certification criteria, and remains\
  \ available alongside the newer\n      R4 implementation for backward compatibility.\n  - aid: cerner:oracle-health-code-console\n    name: Oracle Health Code Console (Developer Portal)\n    tags:\n      - Code Console\n      - Developer Portal\n      - OAuth 2.0\n      - Registration\n      - Sandbox\n    humanURL: https://code.cerner.com/\n    properties:\n      - url: https://code.cerner.com/\n        type: Website\n      - url: https://www.oracle.com/health/developer/api/\n        type: APIAccess\n      - url: https://fhir.cerner.com/authorization/\n        type: Authorization\n    description: >-\n      The Oracle Health Code Console (formerly Cerner Code) is the\n      developer portal used to register SMART on FHIR and system-level\n      applications, configure redirect URIs and launch parameters, manage\n      OAuth 2.0 client credentials, and access the Millennium sandbox for\n      initial testing.\n  - aid: cerner:oracle-health-bulk-fhir-api\n    name: Oracle Health Millennium\
  \ Bulk FHIR API\n    tags:\n      - Bulk Data\n      - FHIR\n      - Flat FHIR\n      - Population Health\n    humanURL: https://fhir.cerner.com/millennium/r4/\n    properties:\n      - url: https://fhir.cerner.com/millennium/r4/\n        type: Documentation\n      - url: https://docs.oracle.com/en/industries/health/millennium-platform-apis/mfrap/r4_overview.html\n        type: Reference\n    description: >-\n      Oracle Health Millennium supports the HL7 Bulk Data Access (Flat\n      FHIR) specification for exporting group-level patient data in NDJSON\n      format for population health, research, and payer-provider data\n      exchange scenarios.\n  - aid: cerner:cerner-careaware\n    name: Cerner CareAware Integration APIs\n    tags:\n      - CareAware\n      - Device Integration\n      - HL7 v2\n      - Medical Device\n    humanURL: https://www.cerner.com/solutions/careaware-interoperability\n    properties:\n      - url: https://www.cerner.com/solutions/careaware-interoperability\n\
  \        type: Website\n    description: >-\n      Cerner CareAware provides device and third-party application\n      integration APIs for medical device data capture, bi-directional\n      HL7 v2 messaging, and workflow embedding into Millennium,\n      supporting medical device manufacturers and hospital biomedical\n      teams.\n  - aid: cerner:oracle-health-smart-on-fhir\n    name: Oracle Health SMART on FHIR App Launch\n    tags:\n      - App Launch\n      - Clinician App\n      - Patient App\n      - SMART on FHIR\n    humanURL: https://fhir.cerner.com/authorization/openid-connect/\n    properties:\n      - url: https://fhir.cerner.com/authorization/openid-connect/\n        type: Documentation\n      - url: https://fhir.cerner.com/\n        type: Portal\n    description: >-\n      Oracle Health implements the SMART on FHIR App Launch framework\n      (standalone and EHR-launch) with OpenID Connect identity tokens,\n      enabling third-party clinician and patient-facing applications\
  \ to\n      embed inside Millennium PowerChart and Oracle Health portals.\ncommon:\n  - type: Website\n    url: https://www.cerner.com\n  - type: Corporate\n    url: https://www.oracle.com/health/\n  - type: Developer\n    url: https://www.oracle.com/health/developer/\n  - type: APIReference\n    url: https://docs.oracle.com/en/industries/health/millennium-platform-apis/index.html\n  - type: FHIR\n    url: https://fhir.cerner.com/\n  - type: CodeConsole\n    url: https://code.cerner.com/\n  - type: OpenSource\n    url: https://github.com/cerner\n  - type: Privacy Policy\n    url: https://www.oracle.com/legal/privacy/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cerner/refs/heads/main/apis.yml
tags:
- Cerner Millennium
- Code Console
- EHR
- Electronic Health Records
- FHIR
- HL7
- Healthcare
- Interoperability
- OAuth 2.0
- Oracle Health
- Patient Access
- Provider Directory
- SMART on FHIR
url: https://raw.githubusercontent.com/api-evangelist/cerner/refs/heads/main/apis.yml
use_cases: []
---
