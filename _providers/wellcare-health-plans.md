---
api_count: 2
api_specs:
- filename: wellcare-fhir-patient-access-api-openapi.yml
  format: yaml
  label: WellCare FHIR Patient Access API
  slug: fhir-patient-access-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wellcare-health-plans/refs/heads/main/openapi/wellcare-fhir-patient-access-api-openapi.yml
- filename: wellcare-fhir-provider-directory-api-openapi.yml
  format: yaml
  label: WellCare FHIR Provider Directory API
  slug: fhir-provider-directory-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wellcare-health-plans/refs/heads/main/openapi/wellcare-fhir-provider-directory-api-openapi.yml
apis:
- description: The WellCare FHIR Patient Access API enables members and authorized third-party applications to securely access and exchange health data including medical, pharmacy, dental, and vision claims and clin
  name: WellCare FHIR Patient Access API
  slug: fhir-patient-access-api
- description: The WellCare FHIR Provider Directory API provides access to up-to-date provider directory information, enabling third-party applications to query in-network physicians, specialists, hospitals, and oth
  name: WellCare FHIR Provider Directory API
  slug: fhir-provider-directory-api
capabilities:
- description: Unified care coordination capability combining WellCare FHIR Patient Access and Provider Directory APIs. Enables care managers, app developers, and member-facing apps to access a member's complete hea
  name: WellCare Member Care Coordination
  slug: member-care-coordination
common:
- title: ''
  type: Website
  url: https://www.wellcare.com
- title: ''
  type: DeveloperPortal
  url: https://partners.centene.com/apis
- title: ''
  type: InteroperabilityPortal
  url: https://www.wellcare.com/en/interoperability-and-patient-access
- title: ''
  type: GitHubOrg
  url: https://github.com/wellcare-health-plans
- title: ''
  type: JSONLDContext
  url: json-ld/wellcare-health-plans-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/wellcare-health-plans-vocabulary.yml
created: ''
description: WellCare Health Plans was a managed care company that focused exclusively on government-sponsored managed care services through Medicaid, Medicare Advantage, and Medicare Prescription Drug Plans before being acquired by Centene Corporation. Now operating under Centene, WellCare provides FHIR- compliant APIs for interoperability and patient access as required by CMS Interoperability and Patient Access final rules (CMS-9115-F). The Centene Developer Partner Portal at partners.centene.com/apis provides access to WellCare FHIR APIs.
features: []
image: ''
integrations: []
jsonld:
- class_count: 7
  name: Wellcare Health Plans Context
  property_count: 27
  slug: wellcare-health-plans-context
layout: provider
modified: '2026-05-03'
name: wellcare-health-plans
rules:
- name: wellcare-health-plans API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 5
  slug: wellcare-health-plans-rules
skills: []
slug: wellcare-health-plans
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wellcare-health-plans\nurl: https://raw.githubusercontent.com/api-evangelist/wellcare-health-plans/refs/heads/main/apis.yml\nmodified: '2026-05-03'\ndescription: >-\n  WellCare Health Plans was a managed care company that focused exclusively on\n  government-sponsored managed care services through Medicaid, Medicare\n  Advantage, and Medicare Prescription Drug Plans before being acquired by\n  Centene Corporation. Now operating under Centene, WellCare provides FHIR-\n  compliant APIs for interoperability and patient access as required by CMS\n  Interoperability and Patient Access final rules (CMS-9115-F). The Centene\n  Developer Partner Portal at partners.centene.com/apis provides access to\n  WellCare FHIR APIs.\ncommon:\n  - type: Website\n    url: https://www.wellcare.com\n  - type: DeveloperPortal\n    url: https://partners.centene.com/apis\n  - type: InteroperabilityPortal\n    url: https://www.wellcare.com/en/interoperability-and-patient-access\n  - type: GitHubOrg\n\
  \    url: https://github.com/wellcare-health-plans\n  - type: JSONLDContext\n    url: json-ld/wellcare-health-plans-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/wellcare-health-plans-vocabulary.yml\napis:\n  - aid: wellcare-health-plans:fhir-patient-access-api\n    name: WellCare FHIR Patient Access API\n    tags:\n      - Healthcare\n      - FHIR\n      - Interoperability\n      - Patient Access\n      - Managed Care\n      - Medicaid\n      - Medicare\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://partners.centene.com\n    humanURL: https://www.wellcare.com/en/interoperability-and-patient-access\n    properties:\n      - url: https://www.wellcare.com/en/interoperability-and-patient-access\n        type: Documentation\n      - url: https://partners.centene.com/apis\n        type: Portal\n      - url: openapi/wellcare-fhir-patient-access-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/wellcare-fhir-patient-schema.json\n\
  \        type: JSONSchema\n      - url: json-schema/wellcare-fhir-eob-schema.json\n        type: JSONSchema\n      - url: json-structure/wellcare-fhir-patient-structure.json\n        type: JSONStructure\n      - url: examples/wellcare-fhir-patient-access-api-getPatient-example.json\n        type: Example\n      - url: examples/wellcare-fhir-patient-access-api-listExplanationOfBenefit-example.json\n        type: Example\n      - url: rules/wellcare-health-plans-rules.yml\n        type: SpectralRuleset\n      - url: capabilities/shared/fhir-patient-access.yaml\n        type: NaftikoCapability\n    description: >-\n      The WellCare FHIR Patient Access API enables members and authorized\n      third-party applications to securely access and exchange health data\n      including medical, pharmacy, dental, and vision claims and clinical\n      information. The API supports HL7 FHIR R4 standards and SMART on FHIR\n      authorization, providing access to up to 5 years of historical health\n\
  \      information. Required under CMS Interoperability and Patient Access final\n      rule (CMS-9115-F) for Medicaid and Medicare Advantage plans.\n  - aid: wellcare-health-plans:fhir-provider-directory-api\n    name: WellCare FHIR Provider Directory API\n    tags:\n      - Healthcare\n      - FHIR\n      - Interoperability\n      - Provider Directory\n      - Managed Care\n      - Medicaid\n      - Medicare\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://partners.centene.com\n    humanURL: https://www.wellcare.com/en/interoperability-and-patient-access\n    properties:\n      - url: https://www.wellcare.com/en/interoperability-and-patient-access\n        type: Documentation\n      - url: https://partners.centene.com/apis\n        type: Portal\n      - url: openapi/wellcare-fhir-provider-directory-api-openapi.yml\n        type: OpenAPI\n      - url: examples/wellcare-fhir-provider-directory-api-searchPractitioners-example.json\n\
  \        type: Example\n      - url: rules/wellcare-health-plans-rules.yml\n        type: SpectralRuleset\n      - url: capabilities/shared/fhir-provider-directory.yaml\n        type: NaftikoCapability\n    description: >-\n      The WellCare FHIR Provider Directory API provides access to up-to-date\n      provider directory information, enabling third-party applications to query\n      in-network physicians, specialists, hospitals, and other healthcare\n      providers. The API follows HL7 FHIR R4 standards and Da Vinci Provider\n      Directory implementation guide (PDex Plan-Net), supporting CMS\n      interoperability requirements for Medicaid and Medicare Advantage plans.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wellcare-health-plans/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/wellcare-health-plans/refs/heads/main/apis.yml
use_cases: []
---
