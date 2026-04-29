---
api_count: 3
apis:
- description: The Anthem Patient Access API provides members access to their personal health data via HL7 FHIR R4, as required by the CMS Interoperability and Patient Access Final Rule (CMS-9115-F). Members can aut
  name: Anthem Patient Access API
  slug: ''
- description: The Anthem Provider Directory API provides public access to provider directory information via HL7 FHIR R4, as required by CMS interoperability rules. Supports searching for in-network providers, faci
  name: Anthem Provider Directory API
  slug: ''
- description: 'The Anthem Drug Formulary API provides access to prescription drug formulary data via HL7 FHIR R4, including covered medications, cost tiers, prior authorization requirements, and quantity limits for '
  name: Anthem Drug Formulary API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://www.anthem.com
- title: ''
  type: SignUp
  url: https://www.anthem.com/developer/register/
- title: ''
  type: TermsOfService
  url: https://www.anthem.com/legal/terms-and-conditions/
- title: ''
  type: PrivacyPolicy
  url: https://www.anthem.com/legal/privacy-policy/
created: '2026-03-23'
description: Anthem, Inc. (now operating as Elevance Health) is one of the largest health benefits companies in the United States, serving members through affiliated Blue Cross and Blue Shield health plans across multiple states including California, New York, Virginia, Georgia, and others. Anthem provides health insurance, pharmacy benefits, and behavioral health services to over 40 million members. Under CMS interoperability rules (CMS-9115-F), Anthem offers FHIR- based Patient Access and Provider Directory APIs.
features:
- description: All Anthem interoperability APIs implement HL7 FHIR Release 4 standards with USCDI-conformant resource profiles.
  name: FHIR R4 Compliance
- description: Patient Access APIs use SMART on FHIR for secure OAuth2-based authorization allowing members to grant third-party app access.
  name: SMART on FHIR Authorization
- description: Members can access their claims history, clinical notes, lab results, immunizations, and medication history through the Patient Access API.
  name: Claims and Clinical Data
- description: Search for in-network providers by specialty, location, name, and plan type through the public Provider Directory API.
  name: Provider Directory Search
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Anthem participates in the CommonWell Health Alliance for cross-organizational clinical data exchange.
  name: CommonWell Health Alliance
- description: Anthem participates in the Carequality interoperability framework for health data exchange between networks.
  name: Carequality Framework
layout: provider
modified: '2026-04-19'
name: Anthem
skills: []
slug: anthem
solutions: []
source_yaml: "name: Anthem\ndescription: >-\n  Anthem, Inc. (now operating as Elevance Health) is one of the largest health\n  benefits companies in the United States, serving members through affiliated\n  Blue Cross and Blue Shield health plans across multiple states including\n  California, New York, Virginia, Georgia, and others. Anthem provides health\n  insurance, pharmacy benefits, and behavioral health services to over 40 million\n  members. Under CMS interoperability rules (CMS-9115-F), Anthem offers FHIR-\n  based Patient Access and Provider Directory APIs.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/anthem/refs/heads/main/apis.yml\ncreated: \"2026-03-23\"\nmodified: \"2026-04-19\"\nspecificationVersion: '0.16'\ntags:\n  - Blue Cross Blue Shield\n  - FHIR\n  - Health Benefits\n  - Health Insurance\n  - Healthcare\n  - Interoperability\napis:\n  - name: Anthem Patient Access API\n    description:\
  \ >-\n      The Anthem Patient Access API provides members access to their personal\n      health data via HL7 FHIR R4, as required by the CMS Interoperability and\n      Patient Access Final Rule (CMS-9115-F). Members can authorize third-party\n      apps to access their claims, clinical information, formulary data, and\n      coverage details. Implements SMART on FHIR for authorization.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.anthem.com/developer/\n    baseURL: https://fhir.anthem.com/r4/\n    tags:\n      - FHIR\n      - Health Insurance\n      - Healthcare\n      - Interoperability\n      - Patient Access\n      - SMART on FHIR\n    properties:\n      - type: Documentation\n        url: https://www.anthem.com/developer/\n      - type: Authentication\n        url: https://www.anthem.com/developer/authentication/\n    contact:\n      - FN: Anthem Developer Support\n        url: https://www.anthem.com/developer/\n\
  \n  - name: Anthem Provider Directory API\n    description: >-\n      The Anthem Provider Directory API provides public access to provider\n      directory information via HL7 FHIR R4, as required by CMS interoperability\n      rules. Supports searching for in-network providers, facilities, and\n      insurance plans. No authentication required for public directory access.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.anthem.com/developer/\n    baseURL: https://fhir.anthem.com/r4/\n    tags:\n      - FHIR\n      - Healthcare\n      - Interoperability\n      - Provider Directory\n    properties:\n      - type: Documentation\n        url: https://www.anthem.com/developer/\n    contact:\n      - FN: Anthem Developer Support\n        url: https://www.anthem.com/developer/\n\n  - name: Anthem Drug Formulary API\n    description: >-\n      The Anthem Drug Formulary API provides access to prescription drug\n      formulary data\
  \ via HL7 FHIR R4, including covered medications, cost\n      tiers, prior authorization requirements, and quantity limits for\n      Anthem health plan formularies.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.anthem.com/developer/\n    baseURL: https://fhir.anthem.com/r4/\n    tags:\n      - Drug Formulary\n      - FHIR\n      - Healthcare\n      - Pharmacy\n    properties:\n      - type: Documentation\n        url: https://www.anthem.com/developer/\n    contact:\n      - FN: Anthem Developer Support\n        url: https://www.anthem.com/developer/\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n    X: apievangelist\n    url: https://apievangelist.com\ncommon:\n  - type: Portal\n    url: https://www.anthem.com\n  - type: SignUp\n    url: https://www.anthem.com/developer/register/\n  - type: TermsOfService\n    url: https://www.anthem.com/legal/terms-and-conditions/\n  - type: PrivacyPolicy\n   \
  \ url: https://www.anthem.com/legal/privacy-policy/\n  - type: Features\n    data:\n      - name: FHIR R4 Compliance\n        description: >-\n          All Anthem interoperability APIs implement HL7 FHIR Release 4\n          standards with USCDI-conformant resource profiles.\n      - name: SMART on FHIR Authorization\n        description: >-\n          Patient Access APIs use SMART on FHIR for secure OAuth2-based\n          authorization allowing members to grant third-party app access.\n      - name: Claims and Clinical Data\n        description: >-\n          Members can access their claims history, clinical notes, lab results,\n          immunizations, and medication history through the Patient Access API.\n      - name: Provider Directory Search\n        description: >-\n          Search for in-network providers by specialty, location, name, and\n          plan type through the public Provider Directory API.\n  - type: UseCases\n    data:\n      - name: Member Health Apps\n      \
  \  description: >-\n          Enable member-authorized third-party health apps to aggregate claims,\n          clinical, and formulary data from Anthem plans.\n      - name: Care Coordination\n        description: >-\n          Allow care coordinators and providers to access member health history\n          with member authorization for improved care transitions.\n      - name: Provider Lookup\n        description: >-\n          Enable applications to search Anthem's provider directory for\n          in-network physicians, hospitals, and specialists.\n  - type: Integrations\n    data:\n      - name: CommonWell Health Alliance\n        description: >-\n          Anthem participates in the CommonWell Health Alliance for\n          cross-organizational clinical data exchange.\n      - name: Carequality Framework\n        description: >-\n          Anthem participates in the Carequality interoperability framework\n          for health data exchange between networks.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/anthem/refs/heads/main/apis.yml
tags:
- Blue Cross Blue Shield
- FHIR
- Health Benefits
- Health Insurance
- Healthcare
- Interoperability
url: https://raw.githubusercontent.com/api-evangelist/anthem/refs/heads/main/apis.yml
use_cases:
- description: Enable member-authorized third-party health apps to aggregate claims, clinical, and formulary data from Anthem plans.
  name: Member Health Apps
- description: Allow care coordinators and providers to access member health history with member authorization for improved care transitions.
  name: Care Coordination
- description: Enable applications to search Anthem's provider directory for in-network physicians, hospitals, and specialists.
  name: Provider Lookup
---
