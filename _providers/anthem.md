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
