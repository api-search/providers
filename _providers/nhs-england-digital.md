---
api_count: 7
apis:
- description: The NHS England API platform hosts a catalogue of national APIs for health and care, including FHIR and REST APIs covering patient demographics, prescriptions, appointments, records, screening, and cl
  name: NHS England API Platform
  slug: api-platform
- description: The Personal Demographics Service is the national electronic database of NHS patient demographic details such as name, address, date of birth and NHS Number. The PDS FHIR API allows authorised systems
  name: Personal Demographics Service (PDS) FHIR API
  slug: personal-demographics-service
- description: The Electronic Prescription Service enables prescribers to send prescriptions electronically to a dispenser of the patient's choice. The EPS FHIR API allows clinical systems to create, retrieve, relea
  name: Electronic Prescription Service (EPS) FHIR API
  slug: electronic-prescription-service
- description: The NHS e-Referral Service combines electronic booking with a choice of place, date and time for first hospital or clinic appointments. The e-RS FHIR API enables clinical systems to integrate referral
  name: e-Referral Service (e-RS) FHIR API
  slug: e-referral-service
- description: The Summary Care Record holds essential patient information from the GP record. The SCR API enables authorised health and care professionals to retrieve a patient's medication, allergies and adverse r
  name: Summary Care Record (SCR) API
  slug: summary-care-record
- description: GP Connect APIs allow authorised clinical systems to view and book GP services. The APIs provide structured access to GP records including medications, allergies, immunisations, observations, problems
  name: GP Connect API
  slug: gp-connect
- description: NHS login provides a single, secure way for citizens to access NHS digital services. The NHS login API enables relying parties to authenticate users, verify identity to a known level of assurance, and
  name: NHS Login API
  slug: nhs-login
common:
- title: ''
  type: Website
  url: https://digital.nhs.uk
- title: ''
  type: Documentation
  url: https://digital.nhs.uk/developer
- title: ''
  type: APIReference
  url: https://digital.nhs.uk/developer/api-catalogue
- title: ''
  type: GettingStarted
  url: https://digital.nhs.uk/developer/guides-and-documentation
- title: ''
  type: Blog
  url: https://digital.nhs.uk/blog
- title: ''
  type: News
  url: https://digital.nhs.uk/news
- title: ''
  type: Support
  url: https://digital.nhs.uk/about-nhs-digital/contact-us
- title: ''
  type: StatusPage
  url: https://status.digital.nhs.uk
- title: ''
  type: GitHubOrganization
  url: https://github.com/NHSDigital
- title: ''
  type: TermsOfService
  url: https://digital.nhs.uk/about-nhs-digital/terms-and-conditions
- title: ''
  type: Privacy
  url: https://digital.nhs.uk/about-nhs-digital/privacy-and-cookies
- title: ''
  type: X
  url: https://x.com/NHSEngland
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/NHSDigital
created: '2025-03-01'
description: NHS England (incorporating the former NHS Digital and NHSX) provides national digital, data, and technology services for the NHS in England. The organization operates the Spine, the Personal Demographics Service, the Electronic Prescription Service, the Summary Care Record, e-Referral Service, NHS App, NHS.uk, and an extensive API platform of FHIR and REST APIs used by health and care providers, developers, and researchers across England.
features:
- description: HL7 FHIR-based APIs for patient records, prescriptions, referrals, and clinical data exchange.
  name: National FHIR APIs
- description: Free, anonymous sandbox endpoints for testing API integrations before production access.
  name: Sandbox Environments
- description: Production authentication via OAuth 2.0 user-restricted access and application-restricted signed JWT.
  name: OAuth 2.0 and Signed JWT
- description: Structured onboarding pathway from sandbox to integration test to production via Apigee developer portal.
  name: Developer Onboarding
- description: Citizen-facing OpenID Connect identity provider for NHS digital services.
  name: NHS Login Identity Provider
- description: National secure messaging and data backbone underlying the major NHS APIs.
  name: Spine Connectivity
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: NHS England Digital
skills: []
slug: nhs-england-digital
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nhs-england-digital\nname: NHS England Digital\ndescription: >-\n  NHS England (incorporating the former NHS Digital and NHSX) provides national\n  digital, data, and technology services for the NHS in England. The organization\n  operates the Spine, the Personal Demographics Service, the Electronic Prescription\n  Service, the Summary Care Record, e-Referral Service, NHS App, NHS.uk, and an\n  extensive API platform of FHIR and REST APIs used by health and care providers,\n  developers, and researchers across England.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Clinical\n  - Demographics\n  - FHIR\n  - Government\n  - Health\n  - Healthcare\n  - NHS\n  - Open Data\n  - Patient Records\n  - Prescriptions\n  - UK\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/nhs-england-digital/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-04-28'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: nhs-england-digital:api-platform\n    name: NHS England API Platform\n    description: >-\n      The NHS England API platform hosts a catalogue of national APIs for health\n      and care, including FHIR and REST APIs covering patient demographics,\n      prescriptions, appointments, records, screening, and clinical terminology.\n      The platform provides developer onboarding, sandbox environments, OAuth 2.0\n      authentication, and production access through API keys and signed JWT\n      authentication.\n    humanURL: https://digital.nhs.uk/developer\n    tags:\n      - API Platform\n      - Developer Portal\n      - FHIR\n      - Healthcare\n    properties:\n      - type: Documentation\n        url: https://digital.nhs.uk/developer\n      - type: APIReference\n        url: https://digital.nhs.uk/developer/api-catalogue\n      - type: GettingStarted\n        url: https://digital.nhs.uk/developer/guides-and-documentation\n  - aid: nhs-england-digital:personal-demographics-service\n\
  \    name: Personal Demographics Service (PDS) FHIR API\n    description: >-\n      The Personal Demographics Service is the national electronic database of\n      NHS patient demographic details such as name, address, date of birth and\n      NHS Number. The PDS FHIR API allows authorised systems to retrieve and\n      update patient demographics for citizens registered with the NHS in England,\n      Wales, and the Isle of Man.\n    humanURL: https://digital.nhs.uk/developer/api-catalogue/personal-demographics-service-fhir\n    tags:\n      - Demographics\n      - FHIR\n      - Patient Records\n    properties:\n      - type: Documentation\n        url: https://digital.nhs.uk/developer/api-catalogue/personal-demographics-service-fhir\n  - aid: nhs-england-digital:electronic-prescription-service\n    name: Electronic Prescription Service (EPS) FHIR API\n    description: >-\n      The Electronic Prescription Service enables prescribers to send prescriptions\n      electronically to a dispenser\
  \ of the patient's choice. The EPS FHIR API\n      allows clinical systems to create, retrieve, release, claim, and cancel\n      electronic prescriptions for patients in England.\n    humanURL: https://digital.nhs.uk/developer/api-catalogue/electronic-prescription-service-fhir\n    tags:\n      - FHIR\n      - Pharmacy\n      - Prescriptions\n    properties:\n      - type: Documentation\n        url: https://digital.nhs.uk/developer/api-catalogue/electronic-prescription-service-fhir\n  - aid: nhs-england-digital:e-referral-service\n    name: e-Referral Service (e-RS) FHIR API\n    description: >-\n      The NHS e-Referral Service combines electronic booking with a choice of\n      place, date and time for first hospital or clinic appointments. The e-RS\n      FHIR API enables clinical systems to integrate referral and booking\n      workflows directly into the patient pathway.\n    humanURL: https://digital.nhs.uk/developer/api-catalogue/e-referral-service-fhir\n    tags:\n      - Appointments\n\
  \      - FHIR\n      - Referrals\n    properties:\n      - type: Documentation\n        url: https://digital.nhs.uk/developer/api-catalogue/e-referral-service-fhir\n  - aid: nhs-england-digital:summary-care-record\n    name: Summary Care Record (SCR) API\n    description: >-\n      The Summary Care Record holds essential patient information from the GP\n      record. The SCR API enables authorised health and care professionals to\n      retrieve a patient's medication, allergies and adverse reactions, and any\n      additional information shared by the patient's GP.\n    humanURL: https://digital.nhs.uk/developer/api-catalogue/summary-care-record\n    tags:\n      - Clinical\n      - Patient Records\n    properties:\n      - type: Documentation\n        url: https://digital.nhs.uk/developer/api-catalogue/summary-care-record\n  - aid: nhs-england-digital:gp-connect\n    name: GP Connect API\n    description: >-\n      GP Connect APIs allow authorised clinical systems to view and book GP\n\
  \      services. The APIs provide structured access to GP records including\n      medications, allergies, immunisations, observations, problems, and\n      appointment availability across federated GP systems.\n    humanURL: https://digital.nhs.uk/developer/api-catalogue/gp-connect-access-record-structured\n    tags:\n      - Appointments\n      - Clinical\n      - FHIR\n      - GP\n      - Patient Records\n    properties:\n      - type: Documentation\n        url: https://digital.nhs.uk/developer/api-catalogue/gp-connect-access-record-structured\n  - aid: nhs-england-digital:nhs-login\n    name: NHS Login API\n    description: >-\n      NHS login provides a single, secure way for citizens to access NHS digital\n      services. The NHS login API enables relying parties to authenticate users,\n      verify identity to a known level of assurance, and obtain consented\n      identity claims using OpenID Connect.\n    humanURL: https://digital.nhs.uk/services/nhs-login\n    tags:\n      -\
  \ Authentication\n      - Identity\n      - OpenID Connect\n    properties:\n      - type: Documentation\n        url: https://digital.nhs.uk/services/nhs-login\ncommon:\n  - type: Website\n    url: https://digital.nhs.uk\n  - type: Documentation\n    url: https://digital.nhs.uk/developer\n  - type: APIReference\n    url: https://digital.nhs.uk/developer/api-catalogue\n  - type: GettingStarted\n    url: https://digital.nhs.uk/developer/guides-and-documentation\n  - type: Blog\n    url: https://digital.nhs.uk/blog\n  - type: News\n    url: https://digital.nhs.uk/news\n  - type: Support\n    url: https://digital.nhs.uk/about-nhs-digital/contact-us\n  - type: StatusPage\n    url: https://status.digital.nhs.uk\n  - type: GitHubOrganization\n    url: https://github.com/NHSDigital\n  - type: TermsOfService\n    url: https://digital.nhs.uk/about-nhs-digital/terms-and-conditions\n  - type: Privacy\n    url: https://digital.nhs.uk/about-nhs-digital/privacy-and-cookies\n  - type: X\n    url: https://x.com/NHSEngland\n\
  \  - type: YouTube\n    url: https://www.youtube.com/c/NHSDigital\n  - type: Features\n    data:\n      - name: National FHIR APIs\n        description: HL7 FHIR-based APIs for patient records, prescriptions, referrals, and clinical data exchange.\n      - name: Sandbox Environments\n        description: Free, anonymous sandbox endpoints for testing API integrations before production access.\n      - name: OAuth 2.0 and Signed JWT\n        description: Production authentication via OAuth 2.0 user-restricted access and application-restricted signed JWT.\n      - name: Developer Onboarding\n        description: Structured onboarding pathway from sandbox to integration test to production via Apigee developer portal.\n      - name: NHS Login Identity Provider\n        description: Citizen-facing OpenID Connect identity provider for NHS digital services.\n      - name: Spine Connectivity\n        description: National secure messaging and data backbone underlying the major NHS APIs.\n  - type:\
  \ UseCases\n    data:\n      - name: Clinical System Integration\n        description: Integrate EHR and clinical systems with national patient demographics, prescriptions, and records.\n      - name: Citizen-Facing Apps\n        description: Build apps that authenticate citizens with NHS login and surface their NHS data.\n      - name: Pharmacy Workflow\n        description: Receive, release, dispense, and claim electronic prescriptions through the EPS API.\n      - name: Referral Management\n        description: Integrate appointment booking and referral workflows via the e-Referral Service.\n      - name: GP Record Access\n        description: View structured GP record data across federated systems via GP Connect.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nhs-england-digital/refs/heads/main/apis.yml
tags:
- Clinical
- Demographics
- FHIR
- Government
- Health
- Healthcare
- NHS
- Open Data
- Patient Records
- Prescriptions
- UK
url: https://raw.githubusercontent.com/api-evangelist/nhs-england-digital/refs/heads/main/apis.yml
use_cases:
- description: Integrate EHR and clinical systems with national patient demographics, prescriptions, and records.
  name: Clinical System Integration
- description: Build apps that authenticate citizens with NHS login and surface their NHS data.
  name: Citizen-Facing Apps
- description: Receive, release, dispense, and claim electronic prescriptions through the EPS API.
  name: Pharmacy Workflow
- description: Integrate appointment booking and referral workflows via the e-Referral Service.
  name: Referral Management
- description: View structured GP record data across federated systems via GP Connect.
  name: GP Record Access
---
