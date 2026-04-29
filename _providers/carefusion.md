---
api_count: 2
apis:
- description: The Alaris Infusion Interoperability solution connects the Alaris System (large-volume pump modules and syringe modules) to hospital EMR platforms so that physician infusion orders flow wirelessly int
  name: Alaris Infusion Interoperability
  slug: alaris-infusion-interoperability
- description: 'Pyxis MedStation and Pyxis ES automated dispensing cabinets integrate with hospital pharmacy information systems and EMRs so that medication profiles, inventory, and dispense events are synchronized. '
  name: Pyxis Automated Dispensing Integration
  slug: pyxis-automated-dispensing
common:
- title: ''
  type: Website
  url: https://www.bd.com/en-us/products-and-solutions/brand-families/carefusion
- title: ''
  type: Alaris Product Page
  url: https://www.bd.com/en-us/products-and-solutions/products/product-families/alaris-infusion-system
- title: ''
  type: Pyxis Product Page
  url: https://www.bd.com/en-us/products-and-solutions/products/product-families/bd-pyxis-medstation-es-system
- title: ''
  type: BD Corporate Site
  url: https://www.bd.com/
- title: ''
  type: Contact
  url: https://www.bd.com/en-us/about-bd/contact-us
- title: ''
  type: Terms of Service
  url: https://www.bd.com/en-us/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://www.bd.com/en-us/our-company/privacy
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/bd1/
- title: ''
  type: X
  url: https://x.com/BDandCo
created: '2026-03-23'
description: CareFusion is a medical technology brand, acquired by BD (Becton, Dickinson and Company) in 2015, best known for the Alaris infusion system and the Pyxis automated dispensing product line. CareFusion does not expose a public developer API; instead, its devices and dispensing systems interoperate with hospital EMRs and pharmacy systems over HL7 v2 messaging, smart-pump interoperability middleware, and vendor-managed integration services. The Alaris Infusion Interoperability program wirelessly transmits orders from EMRs (such as Epic and Cerner) into Alaris large-volume and syringe modules and returns infusion status back to the EMR in near real time, using the Alaris Guardrails drug library as a safety layer.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: CareFusion (BD)
skills: []
slug: carefusion
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: carefusion\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/carefusion/refs/heads/main/apis.yml\nname: CareFusion (BD)\ndescription: >-\n  CareFusion is a medical technology brand, acquired by BD (Becton,\n  Dickinson and Company) in 2015, best known for the Alaris infusion\n  system and the Pyxis automated dispensing product line. CareFusion\n  does not expose a public developer API; instead, its devices and\n  dispensing systems interoperate with hospital EMRs and pharmacy\n  systems over HL7 v2 messaging, smart-pump interoperability\n  middleware, and vendor-managed integration services. The Alaris\n  Infusion Interoperability program wirelessly transmits orders from\n  EMRs (such as Epic and Cerner) into Alaris large-volume and syringe\n  modules and returns infusion status back to the EMR in near real\n  time, using the Alaris Guardrails drug library as a safety layer.\ntype: Index\nx-type: company\nposition: Consumer\naccess: Partner\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  tags:\n  - Automated Dispensing\n  - BD\n  - CareFusion\n  - Connected Devices\n  - EMR Integration\n  - Healthcare\n  - HL7\n  - Infusion Pumps\n  - Medical Devices\n  - Pyxis\n  - Smart Pumps\ncreated: '2026-03-23'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: carefusion:alaris-infusion-interoperability\n    name: Alaris Infusion Interoperability\n    description: >-\n      The Alaris Infusion Interoperability solution connects the Alaris\n      System (large-volume pump modules and syringe modules) to hospital\n      EMR platforms so that physician infusion orders flow wirelessly\n      into pumps and live infusion status is returned to the EMR. The\n      integration is delivered through BD's infusion interoperability\n      middleware and is typically deployed with Epic and Cerner EMRs\n      using HL7 v2 messaging. The Alaris Guardrails drug library\n      provides the clinical decision support and safety layer that\n      validates dose, concentration, and\
  \ delivery parameters before a\n      pump accepts an order.\n    humanURL: https://www.bd.com/en-us/products-and-solutions/products/product-families/alaris-infusion-system\n    tags:\n      - EMR Integration\n      - HL7\n      - Infusion Pumps\n      - Medical Devices\n    properties:\n      - url: https://www.bd.com/en-us/products-and-solutions/products/product-families/alaris-infusion-system\n        type: Documentation\n      - url: https://pages.carefusion.com/AlarisInteroperability.html\n        type: Product\n    x-features:\n      - EMR-to-pump order transmission for large-volume and syringe modules\n      - Near real-time infusion status returned to the EMR\n      - Alaris Guardrails drug library for clinical decision support\n      - HL7 v2 messaging through BD interoperability middleware\n      - Epic, Cerner, and other major EMR compatibility\n      - Reduces error-prone manual pump programming\n      - Auto-documentation of infusion events in the patient record\n    x-use-cases:\n\
  \      - Closed-loop infusion pump integration with EMR\n      - Nursing workflow reduction for high-volume infusions\n      - Sepsis, anesthesia, and oncology infusion safety\n      - Medication administration record (MAR) auto-charting\n      - Infusion analytics and drug library governance\n  - aid: carefusion:pyxis-automated-dispensing\n    name: Pyxis Automated Dispensing Integration\n    description: >-\n      Pyxis MedStation and Pyxis ES automated dispensing cabinets\n      integrate with hospital pharmacy information systems and EMRs so\n      that medication profiles, inventory, and dispense events are\n      synchronized. Integration is delivered through BD Pyxis\n      interoperability services using HL7 v2 messaging (ADT, ORM,\n      RDE, RDS) and direct pharmacy system connectors rather than a\n      public REST API.\n    humanURL: https://www.bd.com/en-us/products-and-solutions/products/product-families/bd-pyxis-medstation-es-system\n    tags:\n      - Automated Dispensing\n\
  \      - EMR Integration\n      - HL7\n      - Pharmacy\n      - Pyxis\n    properties:\n      - url: https://www.bd.com/en-us/products-and-solutions/products/product-families/bd-pyxis-medstation-es-system\n        type: Documentation\n    x-features:\n      - Pharmacy system and EMR integration via HL7 v2\n      - ADT-based patient profile synchronization\n      - Medication order, dispense, and inventory messages\n      - Controlled-substance diversion analytics\n      - Pharmacy and unit-based cabinet configuration\n    x-use-cases:\n      - Nursing unit medication dispensing\n      - Pharmacy inventory replenishment\n      - Controlled-substance chain-of-custody\n      - Drug diversion analytics and reporting\n      - ADT-driven medication profile updates\ncommon:\n  - type: Website\n    url: https://www.bd.com/en-us/products-and-solutions/brand-families/carefusion\n  - type: Alaris Product Page\n    url: https://www.bd.com/en-us/products-and-solutions/products/product-families/alaris-infusion-system\n\
  \  - type: Pyxis Product Page\n    url: https://www.bd.com/en-us/products-and-solutions/products/product-families/bd-pyxis-medstation-es-system\n  - type: BD Corporate Site\n    url: https://www.bd.com/\n  - type: Contact\n    url: https://www.bd.com/en-us/about-bd/contact-us\n  - type: Terms of Service\n    url: https://www.bd.com/en-us/terms-of-use\n  - type: Privacy Policy\n    url: https://www.bd.com/en-us/our-company/privacy\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/bd1/\n  - type: X\n    url: https://x.com/BDandCo\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/carefusion/refs/heads/main/apis.yml
tags:
- Automated Dispensing
- BD
- CareFusion
- Connected Devices
- EMR Integration
- Healthcare
- HL7
- Infusion Pumps
- Medical Devices
- Pyxis
- Smart Pumps
url: https://raw.githubusercontent.com/api-evangelist/carefusion/refs/heads/main/apis.yml
use_cases: []
---
