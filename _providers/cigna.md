---
api_count: 4
apis:
- description: FHIR R4 API that allows authorized third-party applications to access a Cigna member's claims, encounters, clinical data, coverage, and pharmacy information after the member completes SMART on FHIR au
  name: Cigna Patient Access API
  slug: patient-access-api
- description: Public FHIR-based Provider Directory API listing Cigna's contracted network providers, organizations, locations, healthcare services, and practitioner roles. Conforms to the HL7 Da Vinci PDex Plan Net
  name: Cigna Provider Directory API
  slug: provider-directory-api
- description: Public FHIR-based Drug Formulary API exposing Cigna's covered drug lists, formulary tiers, prior authorization requirements, step therapy, and quantity limits. Implements the HL7 Da Vinci PDex US Drug
  name: Cigna Drug Formulary API
  slug: drug-formulary-api
- description: FHIR API that allows in-network providers, with appropriate authorization, to retrieve a Cigna member's clinical and claims data to support care coordination. Implements the HL7 Da Vinci PDex Provider
  name: Cigna Provider Access API
  slug: provider-access-api
common:
- title: ''
  type: Website
  url: https://www.cigna.com/
- title: ''
  type: DeveloperPortal
  url: https://developer.cigna.com/
- title: ''
  type: Portal
  url: https://developer.cigna.com/
- title: ''
  type: Documentation
  url: https://developer.cigna.com/docs/service-apis
- title: ''
  type: Support
  url: https://developer.cigna.com/support
- title: ''
  type: TermsOfService
  url: https://www.cigna.com/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.cigna.com/legal/privacy
- title: ''
  type: JSONLDContext
  url: json-ld/cigna-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cigna-patient-schema.json
- title: ''
  type: Spectral
  url: spectral/cigna-spectral.yml
- title: ''
  type: NaftikoCapabilities
  url: naftiko/cigna-capabilities.yml
created: '2025-02-21'
description: Cigna Healthcare is a leading global health services company offering medical, dental, behavioral, and pharmacy plans for individuals, families, and employers. The Cigna Developer Portal exposes CMS-mandated FHIR APIs for Patient Access, Provider Directory, Drug Formulary, and Provider Access, along with member and provider service APIs that enable third-party applications, electronic health record systems, and partners to access member health data with consent and look up Cigna network providers and formulary information.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cigna Context
  property_count: 8
  slug: cigna-context
layout: provider
modified: '2026-04-23'
name: Cigna
skills: []
slug: cigna
solutions: []
source_yaml: "aid: cigna\nname: Cigna\ndescription: >-\n  Cigna Healthcare is a leading global health services company offering\n  medical, dental, behavioral, and pharmacy plans for individuals, families,\n  and employers. The Cigna Developer Portal exposes CMS-mandated FHIR APIs\n  for Patient Access, Provider Directory, Drug Formulary, and Provider Access,\n  along with member and provider service APIs that enable third-party\n  applications, electronic health record systems, and partners to access\n  member health data with consent and look up Cigna network providers and\n  formulary information.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cigna/refs/heads/main/apis.yml\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - CMS Interoperability\n  - Da Vinci\n  - Drug Formulary\n  - FHIR\n  - Health Insurance\n  - Healthcare\n  - Patient Access\n  - Provider Directory\n  - SMART\
  \ on FHIR\ncreated: '2025-02-21'\nmodified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid: cigna:patient-access-api\n    name: Cigna Patient Access API\n    description: >-\n      FHIR R4 API that allows authorized third-party applications to access\n      a Cigna member's claims, encounters, clinical data, coverage, and\n      pharmacy information after the member completes SMART on FHIR\n      authorization. Conforms to the CMS Interoperability and Patient Access\n      final rule and the HL7 Da Vinci PDex implementation guide.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: >-\n      https://developer.cigna.com/docs/service-apis/patient-access/implementation-guide\n    baseURL: https://fhir.cigna.com/PatientAccess/v1\n    tags:\n      - CMS Interoperability\n      - FHIR\n      - Patient Access\n      - SMART on FHIR\n    properties:\n      - type: Documentation\n        url: >-\n          https://developer.cigna.com/docs/service-apis/patient-access/implementation-guide\n\
  \      - type: OpenAPI\n        url: openapi/cigna-patient-access-api-openapi.yml\n  - aid: cigna:provider-directory-api\n    name: Cigna Provider Directory API\n    description: >-\n      Public FHIR-based Provider Directory API listing Cigna's contracted\n      network providers, organizations, locations, healthcare services, and\n      practitioner roles. Conforms to the HL7 Da Vinci PDex Plan Network\n      implementation guide and the CMS Provider Directory API requirements.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: >-\n      https://developer.cigna.com/docs/service-apis/provider-directory/implementation-guide\n    baseURL: https://fhir.cigna.com/ProviderDirectory/v1\n    tags:\n      - CMS Interoperability\n      - FHIR\n      - Provider Directory\n      - Public API\n    properties:\n      - type: Documentation\n        url: >-\n          https://developer.cigna.com/docs/service-apis/provider-directory/implementation-guide\n\
  \      - type: OpenAPI\n        url: openapi/cigna-provider-directory-api-openapi.yml\n  - aid: cigna:drug-formulary-api\n    name: Cigna Drug Formulary API\n    description: >-\n      Public FHIR-based Drug Formulary API exposing Cigna's covered drug\n      lists, formulary tiers, prior authorization requirements, step therapy,\n      and quantity limits. Implements the HL7 Da Vinci PDex US Drug Formulary\n      implementation guide required by the CMS Interoperability and Patient\n      Access rule.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.cigna.com/docs/service-apis\n    baseURL: https://fhir.cigna.com/DrugFormulary/v1\n    tags:\n      - CMS Interoperability\n      - Drug Formulary\n      - FHIR\n      - Public API\n    properties:\n      - type: Documentation\n        url: https://developer.cigna.com/docs/service-apis\n      - type: OpenAPI\n        url: openapi/cigna-drug-formulary-api-openapi.yml\n  -\
  \ aid: cigna:provider-access-api\n    name: Cigna Provider Access API\n    description: >-\n      FHIR API that allows in-network providers, with appropriate\n      authorization, to retrieve a Cigna member's clinical and claims data to\n      support care coordination. Implements the HL7 Da Vinci PDex Provider\n      Access implementation guide and conforms to the CMS Interoperability\n      and Prior Authorization final rule.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.cigna.com/docs/service-apis\n    baseURL: https://fhir.cigna.com/ProviderAccess/v1\n    tags:\n      - CMS Interoperability\n      - FHIR\n      - Provider Access\n    properties:\n      - type: Documentation\n        url: https://developer.cigna.com/docs/service-apis\n      - type: OpenAPI\n        url: openapi/cigna-provider-access-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.cigna.com/\n  - type: DeveloperPortal\n    url:\
  \ https://developer.cigna.com/\n  - type: Portal\n    url: https://developer.cigna.com/\n  - type: Documentation\n    url: https://developer.cigna.com/docs/service-apis\n  - type: Support\n    url: https://developer.cigna.com/support\n  - type: TermsOfService\n    url: https://www.cigna.com/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.cigna.com/legal/privacy\n  - type: JSONLDContext\n    url: json-ld/cigna-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cigna-patient-schema.json\n  - type: Spectral\n    url: spectral/cigna-spectral.yml\n  - type: NaftikoCapabilities\n    url: naftiko/cigna-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cigna/refs/heads/main/apis.yml
tags:
- CMS Interoperability
- Da Vinci
- Drug Formulary
- FHIR
- Health Insurance
- Healthcare
- Patient Access
- Provider Directory
- SMART on FHIR
url: https://raw.githubusercontent.com/api-evangelist/cigna/refs/heads/main/apis.yml
use_cases: []
---
