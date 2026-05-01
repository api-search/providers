---
api_count: 4
apis:
- description: The Patient Access API enables Anthem and Elevance Health members to securely access and exchange their medical, pharmacy, dental, and vision claims and clinical data through third-party applications.
  name: Elevance Health Patient Access API
  slug: patient-access
- description: 'The Provider Directory API exposes Elevance Health network provider information including practitioners, practitioner roles, organizations, locations, and insurance plans. The API conforms to the HL7 '
  name: Elevance Health Provider Directory API
  slug: provider-directory
- description: The Formulary API publishes Elevance Health drug coverage information including covered drug lists, tier placement, prior authorization requirements, and step therapy rules. The API conforms to the HL
  name: Elevance Health Formulary API
  slug: formulary
- description: The Payer to Payer API enables Elevance Health to exchange member coverage and clinical data with other health plans when members move between payers, supporting the CMS Interoperability and Prior Aut
  name: Elevance Health Payer to Payer API
  slug: payer-to-payer
common:
- title: ''
  type: Website
  url: https://www.elevancehealth.com
- title: ''
  type: DeveloperPortal
  url: https://www.anthem.com/developers
- title: ''
  type: Documentation
  url: https://patient360c.anthem.com/P360Member/fhir/documentation
- title: ''
  type: SignUp
  url: https://www.anthem.com/developers/request-anthem-io
created: '2026-03-21'
description: Elevance Health (formerly Anthem) is a Fortune 500 health benefits company that serves members through Blue Cross and Blue Shield affiliated health plans across multiple states. The company offers medical, pharmacy, dental, vision, and other specialty insurance and exposes a set of CMS Interoperability and Patient Access FHIR APIs to enable members, providers, and partner payers to securely exchange coverage, clinical, claims, provider directory, and formulary data.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Elevance Health
skills: []
slug: elevance-health
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: elevance-health\nname: Elevance Health\nurl: https://raw.githubusercontent.com/api-evangelist/elevance-health/refs/heads/main/apis.yml\nmodified: '2026-04-28'\ncreated: '2026-03-21'\nspecificationVersion: '0.19'\ntype: Index\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Fortune 500\n  - Healthcare\n  - Health Insurance\n  - FHIR\n  - Interoperability\ndescription: >-\n  Elevance Health (formerly Anthem) is a Fortune 500 health benefits company that\n  serves members through Blue Cross and Blue Shield affiliated health plans across\n  multiple states. The company offers medical, pharmacy, dental, vision, and other\n  specialty insurance and exposes a set of CMS Interoperability and Patient Access\n  FHIR APIs to enable members, providers, and partner payers to securely exchange\n  coverage, clinical, claims, provider directory, and formulary data.\napis:\n  - aid: elevance-health:patient-access\n\
  \    name: Elevance Health Patient Access API\n    description: >-\n      The Patient Access API enables Anthem and Elevance Health members to securely\n      access and exchange their medical, pharmacy, dental, and vision claims and\n      clinical data through third-party applications. Built on the HL7 FHIR R4\n      specification and aligned with the CARIN Consumer Directed Payer Data\n      Exchange Implementation Guide, the API supports up to five years of historical\n      claims and clinical data.\n    humanURL: https://www.anthem.com/developers\n    baseURL: https://patient360.anthem.com/P360Member/fhir\n    tags:\n      - FHIR\n      - Healthcare\n      - Health Insurance\n      - Patient Access\n      - Interoperability\n    properties:\n      - type: Documentation\n        url: https://patient360c.anthem.com/P360Member/fhir/documentation\n      - type: DeveloperPortal\n        url: https://www.anthem.com/developers\n  - aid: elevance-health:provider-directory\n    name: Elevance\
  \ Health Provider Directory API\n    description: >-\n      The Provider Directory API exposes Elevance Health network provider\n      information including practitioners, practitioner roles, organizations,\n      locations, and insurance plans. The API conforms to the HL7 FHIR R4\n      specification and the DaVinci PDEX Plan Net Implementation Guide and does\n      not require authentication for public directory data.\n    humanURL: https://www.anthem.com/developers\n    tags:\n      - FHIR\n      - Provider Directory\n      - Healthcare\n      - Interoperability\n    properties:\n      - type: Documentation\n        url: https://www.anthem.com/developers\n  - aid: elevance-health:formulary\n    name: Elevance Health Formulary API\n    description: >-\n      The Formulary API publishes Elevance Health drug coverage information\n      including covered drug lists, tier placement, prior authorization\n      requirements, and step therapy rules. The API conforms to the HL7 FHIR R4\n   \
  \   specification and the DaVinci PDEX US Drug Formulary Implementation Guide.\n    humanURL: https://www.anthem.com/developers\n    tags:\n      - FHIR\n      - Formulary\n      - Pharmacy\n      - Healthcare\n      - Interoperability\n    properties:\n      - type: Documentation\n        url: https://www.anthem.com/developers\n  - aid: elevance-health:payer-to-payer\n    name: Elevance Health Payer to Payer API\n    description: >-\n      The Payer to Payer API enables Elevance Health to exchange member coverage\n      and clinical data with other health plans when members move between\n      payers, supporting the CMS Interoperability and Prior Authorization rule.\n      The API is built on the HL7 FHIR R4 specification.\n    humanURL: https://www.anthem.com/developers\n    tags:\n      - FHIR\n      - Payer to Payer\n      - Healthcare\n      - Interoperability\n    properties:\n      - type: Documentation\n        url: https://www.anthem.com/developers\ncommon:\n  - type: Website\n\
  \    url: https://www.elevancehealth.com\n  - type: DeveloperPortal\n    url: https://www.anthem.com/developers\n  - type: Documentation\n    url: https://patient360c.anthem.com/P360Member/fhir/documentation\n  - type: SignUp\n    url: https://www.anthem.com/developers/request-anthem-io\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/elevance-health/refs/heads/main/apis.yml
tags:
- Fortune 500
- Healthcare
- Health Insurance
- FHIR
- Interoperability
url: https://raw.githubusercontent.com/api-evangelist/elevance-health/refs/heads/main/apis.yml
use_cases: []
---
