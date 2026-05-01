---
api_count: 5
apis:
- description: The Coverage API performs real-time insurance eligibility and benefits verification for a patient against a payer. Clients submit provider NPI, payer ID, and member identity information and receive st
  name: Eligible Coverage API
  slug: coverage
- description: The Claims API supports submission, tracking, and status checking of professional and institutional healthcare claims to payers across the Eligible network. The API also provides claim acknowledgement
  name: Eligible Claims API
  slug: claims
- description: The Payment Estimation API calculates expected patient out-of-pocket amounts for a service before it is rendered, combining benefit details from a coverage check with provider contracted rates and acc
  name: Eligible Payment Estimation API
  slug: payment-estimation
- description: 'The Enrollment API manages the trading partner enrollment workflow that providers must complete with payers in order to exchange eligibility, claims, and remittance transactions through Eligible. The '
  name: Eligible Enrollment API
  slug: enrollment
- description: The Payers API exposes the directory of insurance payers supported by Eligible, including payer identifiers, names, supported transaction types, enrollment requirements, and webhook capabilities. Clie
  name: Eligible Payers API
  slug: payers
common:
- title: ''
  type: Website
  url: https://eligible.com/
- title: ''
  type: Documentation
  url: https://eligible.com/
created: '2024-07-02'
description: Eligible provides insurance billing APIs for healthcare businesses, enabling the integration of insurance billing experiences into healthcare applications. The platform supports eligibility verification, coverage discovery, claims submission and tracking, payment estimation, enrollment, and remittance processing across a large network of US payers.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Eligible
skills: []
slug: eligible
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: eligible\nname: Eligible\ndescription: >-\n  Eligible provides insurance billing APIs for healthcare businesses, enabling\n  the integration of insurance billing experiences into healthcare applications.\n  The platform supports eligibility verification, coverage discovery, claims\n  submission and tracking, payment estimation, enrollment, and remittance\n  processing across a large network of US payers.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Billing\n  - Eligibility\n  - Healthcare\n  - Insurance\n  - Claims\nurl: https://raw.githubusercontent.com/api-evangelist/eligible/refs/heads/main/apis.yml\ncreated: '2024-07-02'\nmodified: '2026-04-28'\nposition: Consumer\naccess: 3rd-Party\nspecificationVersion: '0.19'\napis:\n  - aid: eligible:coverage\n    name: Eligible Coverage API\n    description: >-\n      The Coverage API performs real-time insurance eligibility and benefits\n      verification for a patient\
  \ against a payer. Clients submit provider NPI,\n      payer ID, and member identity information and receive structured benefit\n      details including plan status, copays, coinsurance, deductibles, and\n      out-of-pocket maximums.\n    humanURL: https://eligible.com/\n    tags:\n      - Coverage\n      - Eligibility\n      - Healthcare\n      - Insurance\n    properties:\n      - type: Documentation\n        url: https://eligible.com/\n  - aid: eligible:claims\n    name: Eligible Claims API\n    description: >-\n      The Claims API supports submission, tracking, and status checking of\n      professional and institutional healthcare claims to payers across the\n      Eligible network. The API also provides claim acknowledgement, rejection,\n      and remittance retrieval workflows for healthcare billing applications.\n    humanURL: https://eligible.com/\n    tags:\n      - Claims\n      - Billing\n      - Healthcare\n      - Insurance\n    properties:\n      - type: Documentation\n\
  \        url: https://eligible.com/\n  - aid: eligible:payment-estimation\n    name: Eligible Payment Estimation API\n    description: >-\n      The Payment Estimation API calculates expected patient out-of-pocket\n      amounts for a service before it is rendered, combining benefit details\n      from a coverage check with provider contracted rates and accumulators.\n      The API helps providers offer transparent cost estimates and collect\n      patient responsibility at the point of service.\n    humanURL: https://eligible.com/\n    tags:\n      - Payment Estimation\n      - Cost Transparency\n      - Healthcare\n      - Billing\n    properties:\n      - type: Documentation\n        url: https://eligible.com/\n  - aid: eligible:enrollment\n    name: Eligible Enrollment API\n    description: >-\n      The Enrollment API manages the trading partner enrollment workflow that\n      providers must complete with payers in order to exchange eligibility,\n      claims, and remittance transactions\
  \ through Eligible. The API supports\n      submission, tracking, and status retrieval of enrollment requests.\n    humanURL: https://eligible.com/\n    tags:\n      - Enrollment\n      - Trading Partner\n      - Healthcare\n      - Insurance\n    properties:\n      - type: Documentation\n        url: https://eligible.com/\n  - aid: eligible:payers\n    name: Eligible Payers API\n    description: >-\n      The Payers API exposes the directory of insurance payers supported by\n      Eligible, including payer identifiers, names, supported transaction\n      types, enrollment requirements, and webhook capabilities. Clients use\n      this API to select payers and check the status of supported transactions.\n    humanURL: https://eligible.com/\n    tags:\n      - Payers\n      - Directory\n      - Healthcare\n      - Insurance\n    properties:\n      - type: Documentation\n        url: https://eligible.com/\ncommon:\n  - type: Website\n    url: https://eligible.com/\n  - type: Documentation\n\
  \    url: https://eligible.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/eligible/refs/heads/main/apis.yml
tags:
- Billing
- Eligibility
- Healthcare
- Insurance
- Claims
url: https://raw.githubusercontent.com/api-evangelist/eligible/refs/heads/main/apis.yml
use_cases: []
---
