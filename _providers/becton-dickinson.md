---
api_count: 2
apis:
- description: 'The BD Incada Connected Care Platform is a scalable, AI-enabled, cloud-based platform launched in October 2025 that unifies BD device data from infusion pumps, patient monitors, and pharmacy robotics '
  name: BD Incada Connected Care Platform
  slug: bd-incada-platform
- description: BD Pyxis is a medication management and dispensing system used in hospitals to control medication access, reduce errors, and streamline pharmacy workflows. Pyxis connects to hospital information syste
  name: BD Pyxis Medication Management System
  slug: pyxis
common:
- title: ''
  type: Website
  url: https://www.bd.com/
- title: ''
  type: Security
  url: https://www.bd.com/en-us/company/cybersecurity
- title: ''
  type: PrivacyPolicy
  url: https://www.bd.com/en-us/company/legal-notices-and-privacy/privacy
- title: ''
  type: TermsOfService
  url: https://www.bd.com/en-us/company/legal-notices-and-privacy
created: '2026-03-21'
description: Becton Dickinson (BD) is a global medical technology company that develops, manufactures, and sells medical devices, instrument systems, and reagents. In October 2025, BD launched the BD Incada Connected Care Platform, an AI-enabled, cloud-based platform built on AWS that unifies data from nearly 3 million connected BD devices including infusion pumps, patient monitors, and pharmacy robotics. BD also produces the Pyxis medication management system and integrates with EMRs via HL7 FHIR standards for clinical data exchange.
features:
- description: AI-enabled cloud platform launched in 2025 that unifies data from nearly 3 million BD connected medical devices on AWS infrastructure.
  name: BD Incada Connected Care Platform
- description: Natural language search and AI-powered insights for medication inventory, device utilization, and clinical operational analytics.
  name: AI-Powered Analytics
- description: Healthcare interoperability using HL7 and FHIR standards for EMR integration with Mirth, Cloverleaf, and Rhapsody interface engines.
  name: HL7 FHIR Integration
- description: Pyxis automated dispensing system with connected pharmacy workflow, medication safety, and inventory management.
  name: Medication Management
- description: Connectivity for infusion pumps, vital signs monitors, and pharmacy robotics to hospital information systems.
  name: Device Connectivity
- description: Customizable dashboards and analytics enabling frontline clinical teams to act on device and medication data insights.
  name: Enterprise Analytics
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integration with Epic electronic medical records for medication order and administration workflow connectivity.
  name: Epic EMR
- description: Integration with Cerner/Oracle Health for clinical data exchange and medication management.
  name: Cerner EMR
- description: Open-source HL7 interface engine used with BD systems for healthcare data exchange.
  name: Mirth Connect
- description: Amazon Web Services infrastructure powering the BD Incada Connected Care Platform cloud analytics.
  name: AWS
- description: Healthcare integration engine used with BD systems for interfacing with hospital information systems.
  name: Cloverleaf
layout: provider
modified: '2026-04-19'
name: Becton Dickinson
skills: []
slug: becton-dickinson
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: becton-dickinson\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/becton-dickinson/refs/heads/main/apis.yml\nname: Becton Dickinson\ndescription: >-\n  Becton Dickinson (BD) is a global medical technology company that develops, manufactures,\n  and sells medical devices, instrument systems, and reagents. In October 2025, BD launched\n  the BD Incada Connected Care Platform, an AI-enabled, cloud-based platform built on AWS\n  that unifies data from nearly 3 million connected BD devices including infusion pumps,\n  patient monitors, and pharmacy robotics. BD also produces the Pyxis medication management\n  system and integrates with EMRs via HL7 FHIR standards for clinical data exchange.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Healthcare\n  - Medical Devices\n  - Infusion Therapy\n  - Medication Management\n  - Connected Health\n  - Diagnostics\naccess: 3rd-Party\ncreated: '2026-03-21'\nmodified:\
  \ '2026-04-19'\nposition: Consumer\nspecificationVersion: '0.19'\napis:\n  - aid: becton-dickinson:bd-incada-platform\n    name: BD Incada Connected Care Platform\n    description: >-\n      The BD Incada Connected Care Platform is a scalable, AI-enabled, cloud-based\n      platform launched in October 2025 that unifies BD device data from infusion pumps,\n      patient monitors, and pharmacy robotics into one intelligent ecosystem. Built on\n      AWS, it provides enterprise-wide medication inventory visibility, AI-powered natural\n      language analytics, and integrates with major EMR systems via HL7 FHIR standards.\n    humanURL: https://www.bd.com/en-us/\n    tags:\n      - Healthcare\n      - Connected Devices\n      - AI\n      - Medication Management\n      - EMR Integration\n    properties:\n      - type: Documentation\n        url: https://www.bd.com/en-us/\n\n  - aid: becton-dickinson:pyxis\n    name: BD Pyxis Medication Management System\n    description: >-\n      BD Pyxis\
  \ is a medication management and dispensing system used in hospitals to\n      control medication access, reduce errors, and streamline pharmacy workflows. Pyxis\n      connects to hospital information systems and EMRs for medication ordering, dispensing,\n      and reconciliation workflows. The BD Incada platform extends Pyxis with cloud-based\n      analytics and AI capabilities.\n    humanURL: https://www.bd.com/en-us/products-and-solutions/products/product-families/pyxis\n    tags:\n      - Healthcare\n      - Medication Management\n      - Pharmacy\n      - Hospital Automation\n    properties:\n      - type: Documentation\n        url: https://www.bd.com/en-us/products-and-solutions/products/product-families/pyxis\n\ncommon:\n  - type: Website\n    url: https://www.bd.com/\n  - type: Security\n    url: https://www.bd.com/en-us/company/cybersecurity\n  - type: PrivacyPolicy\n    url: https://www.bd.com/en-us/company/legal-notices-and-privacy/privacy\n  - type: TermsOfService\n    url:\
  \ https://www.bd.com/en-us/company/legal-notices-and-privacy\n  - type: Features\n    data:\n      - name: BD Incada Connected Care Platform\n        description: AI-enabled cloud platform launched in 2025 that unifies data from nearly 3 million BD connected medical devices on AWS infrastructure.\n      - name: AI-Powered Analytics\n        description: Natural language search and AI-powered insights for medication inventory, device utilization, and clinical operational analytics.\n      - name: HL7 FHIR Integration\n        description: Healthcare interoperability using HL7 and FHIR standards for EMR integration with Mirth, Cloverleaf, and Rhapsody interface engines.\n      - name: Medication Management\n        description: Pyxis automated dispensing system with connected pharmacy workflow, medication safety, and inventory management.\n      - name: Device Connectivity\n        description: Connectivity for infusion pumps, vital signs monitors, and pharmacy robotics to hospital information\
  \ systems.\n      - name: Enterprise Analytics\n        description: Customizable dashboards and analytics enabling frontline clinical teams to act on device and medication data insights.\n  - type: UseCases\n    data:\n      - name: Medication Safety\n        description: Reduce medication errors by connecting BD dispensing systems with EMR medication orders and administration verification.\n      - name: Clinical Data Interoperability\n        description: Enable hospital IT to integrate BD device data into clinical workflows using HL7 FHIR standards.\n      - name: Pharmacy Analytics\n        description: Gain enterprise-wide visibility into medication inventory, dispensing patterns, and waste reduction opportunities.\n      - name: Connected Care Workflows\n        description: Unify data from infusion pumps, patient monitors, and pharmacy systems to support coordinated clinical care decisions.\n  - type: Integrations\n    data:\n      - name: Epic EMR\n        description: Integration\
  \ with Epic electronic medical records for medication order and administration workflow connectivity.\n      - name: Cerner EMR\n        description: Integration with Cerner/Oracle Health for clinical data exchange and medication management.\n      - name: Mirth Connect\n        description: Open-source HL7 interface engine used with BD systems for healthcare data exchange.\n      - name: AWS\n        description: Amazon Web Services infrastructure powering the BD Incada Connected Care Platform cloud analytics.\n      - name: Cloverleaf\n        description: Healthcare integration engine used with BD systems for interfacing with hospital information systems.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/becton-dickinson/refs/heads/main/apis.yml
tags:
- Healthcare
- Medical Devices
- Infusion Therapy
- Medication Management
- Connected Health
- Diagnostics
url: https://raw.githubusercontent.com/api-evangelist/becton-dickinson/refs/heads/main/apis.yml
use_cases:
- description: Reduce medication errors by connecting BD dispensing systems with EMR medication orders and administration verification.
  name: Medication Safety
- description: Enable hospital IT to integrate BD device data into clinical workflows using HL7 FHIR standards.
  name: Clinical Data Interoperability
- description: Gain enterprise-wide visibility into medication inventory, dispensing patterns, and waste reduction opportunities.
  name: Pharmacy Analytics
- description: Unify data from infusion pumps, patient monitors, and pharmacy systems to support coordinated clinical care decisions.
  name: Connected Care Workflows
---
