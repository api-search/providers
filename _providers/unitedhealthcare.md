---
api_count: 2
api_specs:
- filename: unitedhealthcare-provider-api-openapi.yml
  format: yaml
  label: UnitedHealthcare Provider API
  slug: provider-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/openapi/unitedhealthcare-provider-api-openapi.yml
- filename: unitedhealthcare-interoperability-api-openapi.yml
  format: yaml
  label: UnitedHealthcare Interoperability API
  slug: interoperability-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/openapi/unitedhealthcare-interoperability-api-openapi.yml
apis:
- description: The UnitedHealthcare Provider API provides real-time access to eligibility verification, claims management, prior authorization, and provider directory services through the UHC API Marketplace. Enable
  name: UnitedHealthcare Provider API
  slug: provider-api
- description: 'The UnitedHealthcare Interoperability APIs provide FHIR R4-compliant access to patient health data in compliance with CMS Interoperability and Patient Access final rule (CMS-9115-F). Includes Patient '
  name: UnitedHealthcare Interoperability API
  slug: interoperability-api
capabilities:
- description: Workflow capability for accessing UnitedHealthcare member health data through FHIR R4 Interoperability APIs mandated by CMS. Enables patient portals, health apps, and care coordination tools to retrie
  name: UnitedHealthcare Patient Data Access
  slug: patient-data-access
- description: Workflow capability for healthcare providers using UnitedHealthcare APIs to verify member eligibility, manage claims, check prior authorizations, and access the provider directory. Supports revenue cy
  name: UnitedHealthcare Provider Operations
  slug: provider-operations
common: []
created: '2025-03-01'
description: UnitedHealthcare is one of the largest health insurance providers in the United States, offering employer-sponsored health benefits, individual and family plans, Medicare and Medicaid plans, and managed care services. UnitedHealthcare provides APIs for healthcare providers through the UHC API Marketplace for eligibility verification, claims management, and prior authorization, and FHIR R4-compliant Interoperability APIs for patient data access and provider directory services per CMS mandates.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 17
  name: Unitedhealthcare Interoperability Api Context
  property_count: 1
  slug: unitedhealthcare-interoperability-api-context
- class_count: 14
  name: Unitedhealthcare Provider Api Context
  property_count: 13
  slug: unitedhealthcare-provider-api-context
layout: provider
modified: '2026-05-03'
name: UnitedHealthcare
rules:
- name: UnitedHealthcare API Rules
  rule_count: 27
  severity_counts:
    error: 13
    hint: 0
    info: 4
    warn: 10
  slug: unitedhealthcare-spectral-rules
skills: []
slug: unitedhealthcare
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: unitedhealthcare\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/apis.yml\nname: UnitedHealthcare\ndescription: >-\n  UnitedHealthcare is one of the largest health insurance providers in the United States,\n  offering employer-sponsored health benefits, individual and family plans, Medicare and\n  Medicaid plans, and managed care services. UnitedHealthcare provides APIs for healthcare\n  providers through the UHC API Marketplace for eligibility verification, claims management,\n  and prior authorization, and FHIR R4-compliant Interoperability APIs for patient data\n  access and provider directory services per CMS mandates.\ntags:\n  - Health Insurance\n  - Healthcare\n  - FHIR\n  - Claims\n  - Eligibility\ntype: Company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nposition: Consuming\nspecificationVersion: '0.19'\n\napis:\n\
  \  - aid: unitedhealthcare:provider-api\n    name: UnitedHealthcare Provider API\n    tags:\n      - Health Insurance\n      - Healthcare\n      - Eligibility\n      - Claims\n      - Prior Authorization\n    humanURL: https://apimarketplace.uhcprovider.com/#/\n    baseURL: https://api.uhcprovider.com\n    description: >-\n      The UnitedHealthcare Provider API provides real-time access to eligibility\n      verification, claims management, prior authorization, and provider directory\n      services through the UHC API Marketplace. Enables healthcare providers to\n      verify member coverage, check claim status, validate claims before submission,\n      check prior authorization requirements, and access provider demographic data.\n    properties:\n      - url: https://apimarketplace.uhcprovider.com/#/\n        type: Documentation\n      - url: openapi/unitedhealthcare-provider-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/provider-eligibility-response-schema.json\n\
  \        type: Schema\n      - url: json-schema/provider-claim-inquiry-response-schema.json\n        type: Schema\n      - url: json-ld/unitedhealthcare-provider-api-context.jsonld\n        type: JSON-LD Context\n      - url: examples/provider-eligibility-response-example.json\n        type: Example\n\n  - aid: unitedhealthcare:interoperability-api\n    name: UnitedHealthcare Interoperability API\n    tags:\n      - Health Insurance\n      - Healthcare\n      - FHIR\n      - Patient Access\n      - Provider Directory\n      - Formulary\n    humanURL: https://www.uhc.com/legal/interoperability-apis\n    baseURL: https://api.uhc.com/fhir/R4\n    description: >-\n      The UnitedHealthcare Interoperability APIs provide FHIR R4-compliant access to\n      patient health data in compliance with CMS Interoperability and Patient Access\n      final rule (CMS-9115-F). Includes Patient Access API for member claims history,\n      coverage, and health records, Provider Directory API for network provider\
  \ search,\n      and Formulary API for drug coverage information.\n    properties:\n      - url: https://www.uhc.com/legal/interoperability-apis\n        type: Documentation\n      - url: openapi/unitedhealthcare-interoperability-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/interoperability-fhir-bundle-schema.json\n        type: Schema\n      - url: json-schema/interoperability-fhir-patient-schema.json\n        type: Schema\n      - url: json-ld/unitedhealthcare-interoperability-api-context.jsonld\n        type: JSON-LD Context\n      - url: examples/interoperability-fhir-bundle-example.json\n        type: Example\n\nfeatures:\n  - name: Real-Time Eligibility Verification\n    description: >-\n      Verify UnitedHealthcare member eligibility and benefits in real time at the\n      point of care, reducing claim denials and improving patient financial transparency.\n  - name: Claim Pre-Check\n    description: >-\n      Validate claims before submission to identify errors,\
  \ missing authorizations,\n      and billing issues that would cause denials, accelerating payment cycles.\n  - name: Prior Authorization Check\n    description: >-\n      Determine prior authorization requirements for procedures and check existing\n      authorization status to streamline clinical workflows.\n  - name: FHIR R4 Patient Access\n    description: >-\n      CMS-mandated FHIR R4 APIs enabling patients and authorized applications to\n      access claims history, coverage data, and clinical information.\n  - name: Provider Directory\n    description: >-\n      FHIR R4 Provider Directory implementing Da Vinci PDex Plan Net IG for\n      searching UnitedHealthcare network providers, organizations, and locations.\n  - name: Drug Formulary\n    description: >-\n      FHIR-based formulary API providing drug coverage tier information, prior\n      authorization requirements, and quantity limits for prescription medications.\n  - name: Claims Inquiry\n    description: >-\n      Real-time\
  \ claim status inquiry returning payment details, denial reasons,\n      adjustment codes, and explanation of benefits data.\n\nuseCases:\n  - name: Point-of-Care Eligibility\n    description: >-\n      Verify patient UnitedHealthcare coverage and benefits at check-in using the\n      real-time eligibility API to collect accurate copays and reduce billing errors.\n  - name: Revenue Cycle Management\n    description: >-\n      Integrate claim pre-check and claim inquiry APIs into practice management\n      systems to automate claim validation and track payment status.\n  - name: Prior Authorization Workflows\n    description: >-\n      Embed prior authorization checking in clinical workflows to immediately determine\n      if approval is needed before scheduling procedures or prescribing medications.\n  - name: Patient Portal Integration\n    description: >-\n      Enable patient portals to display claims history, coverage details, and EOBs\n      using the FHIR Patient Access API for transparent\
  \ member engagement.\n  - name: Provider Search Applications\n    description: >-\n      Build provider search tools and care coordination apps using the FHIR Provider\n      Directory API to find in-network physicians, specialists, and facilities.\n  - name: Formulary Management\n    description: >-\n      Integrate the Formulary API into EHR and e-prescribing workflows to check\n      drug coverage tiers and authorization requirements at point of prescribing.\n\nintegrations:\n  - name: Epic Systems\n    description: >-\n      UnitedHealthcare APIs integrate with Epic EHR for real-time eligibility\n      verification, prior authorization, and FHIR-based data exchange.\n  - name: Cerner/Oracle Health\n    description: >-\n      FHIR R4 Interoperability APIs integrate with Cerner for patient data access\n      and provider directory services.\n  - name: Change Healthcare\n    description: >-\n      Provider APIs complement Change Healthcare clearinghouse services for\n      comprehensive\
  \ claims management and eligibility verification.\n  - name: Availity\n    description: >-\n      UnitedHealthcare participates in Availity's real-time eligibility and claims\n      network providing additional access pathways for providers.\n\nartifacts:\n  openapi:\n    - name: UnitedHealthcare Provider API\n      url: openapi/unitedhealthcare-provider-api-openapi.yml\n    - name: UnitedHealthcare Interoperability API\n      url: openapi/unitedhealthcare-interoperability-api-openapi.yml\n\n  jsonSchema:\n    - url: json-schema/provider-eligibility-request-schema.json\n    - url: json-schema/provider-eligibility-response-schema.json\n    - url: json-schema/provider-benefit-check-request-schema.json\n    - url: json-schema/provider-benefit-check-response-schema.json\n    - url: json-schema/provider-claim-pre-check-request-schema.json\n    - url: json-schema/provider-claim-pre-check-response-schema.json\n    - url: json-schema/provider-claim-inquiry-request-schema.json\n    - url: json-schema/provider-claim-inquiry-response-schema.json\n\
  \    - url: json-schema/provider-prior-auth-check-request-schema.json\n    - url: json-schema/provider-prior-auth-check-response-schema.json\n    - url: json-schema/provider-provider-demographics-schema.json\n    - url: json-schema/interoperability-fhir-bundle-schema.json\n    - url: json-schema/interoperability-fhir-patient-schema.json\n\n  jsonStructure:\n    - url: json-structure/provider-eligibility-response-structure.json\n    - url: json-structure/provider-claim-inquiry-response-structure.json\n    - url: json-structure/provider-provider-demographics-structure.json\n    - url: json-structure/interoperability-fhir-bundle-structure.json\n    - url: json-structure/interoperability-fhir-patient-structure.json\n\n  jsonLd:\n    - url: json-ld/unitedhealthcare-provider-api-context.jsonld\n    - url: json-ld/unitedhealthcare-interoperability-api-context.jsonld\n\n  examples:\n    - url: examples/provider-eligibility-response-example.json\n    - url: examples/provider-claim-inquiry-response-example.json\n\
  \    - url: examples/provider-prior-auth-check-response-example.json\n    - url: examples/interoperability-fhir-bundle-example.json\n    - url: examples/interoperability-fhir-patient-example.json\n\n  spectralRules:\n    - url: rules/unitedhealthcare-spectral-rules.yml\n\n  capabilities:\n    shared:\n      - url: capabilities/shared/provider-api.yaml\n      - url: capabilities/shared/interoperability-api.yaml\n    workflows:\n      - url: capabilities/provider-operations.yaml\n      - url: capabilities/patient-data-access.yaml\n\n  vocabulary:\n    - url: vocabulary/unitedhealthcare-vocabulary.yaml\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/apis.yml
tags:
- Health Insurance
- Healthcare
- FHIR
- Claims
- Eligibility
url: https://raw.githubusercontent.com/api-evangelist/unitedhealthcare/refs/heads/main/apis.yml
use_cases: []
---
