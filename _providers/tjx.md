---
api_count: 4
apis:
- description: The TJX Oracle iSupplier portal allows not-for-resale suppliers to manage purchase orders, track invoices, monitor payment status, and handle deduction disputes. Suppliers can access real-time account
  name: TJX Oracle iSupplier Portal
  slug: tjx-isupplier
- description: TJX Companies requires EDI compliance for all resale vendors, supporting purchase orders (850), purchase order acknowledgements (855), advanced shipping notices (856), invoices (810), motor carrier lo
  name: TJX EDI Integration
  slug: tjx-edi
- description: 'The TJX Companies LLC Advanced Shipping Notice (ASN) Vendor Portal powered by DiCentral allows resale vendors to create and submit advance shipping notices, manage compliance requirements, and handle '
  name: TJX ASN Vendor Portal
  slug: tjx-asn-vendor-portal
- description: The TJX SupplierOne portal enables diverse supplier registration, certification tracking, and quarterly Tier II program reporting. Suppliers can complete vendor applications, provide business document
  name: TJX SupplierOne Diversity Portal
  slug: tjx-supplierone
common:
- title: ''
  type: Website
  url: https://www.tjx.com/
- title: ''
  type: Documentation
  url: https://www.tjx.com/mytjx/supplier/supplier.html
- title: ''
  type: Portal
  url: https://www.mytjx.com/mytjx/supplier.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/TJX
created: '2024-11-27'
description: The TJX Companies, Inc. is an American multinational off-price department store corporation headquartered in Framingham, Massachusetts, ranked No. 80 on the 2024 Fortune 500 list. Operating over 4,800 stores across nine countries and three continents under brands including T.J. Maxx, Marshalls, HomeGoods, Sierra, HomeSense (US), and Winners, HomeSense, Marshalls (Canada), TJX provides supplier and vendor integration through EDI and web-based portal platforms. Supplier connectivity is handled via Oracle iSupplier, SupplierOne, and the DiCentral ASN Vendor Portal, supporting purchase orders, advanced shipping notices, invoicing, and payment tracking.
features:
- description: Web-based supplier self-service for invoice tracking, payment status, deduction management, and purchase order visibility.
  name: Oracle iSupplier Portal
- description: Electronic Data Interchange compliance for purchase orders (850), ASNs (856), invoices (810), and related transactions for resale suppliers.
  name: EDI Vendor Integration
- description: DiCentral-powered portal for creating and submitting advance shipping notices and managing compliance.
  name: ASN Vendor Portal
- description: Supplier diversity portal for diverse supplier registration, certification, and Tier II reporting.
  name: SupplierOne Diversity Registration
- description: Digital invoice submission via Transcepta integration, reducing paperwork and expediting payment cycles.
  name: Transcepta Electronic Invoicing
- description: Vendor integration covering all TJX banners including T.J. Maxx, Marshalls, HomeGoods, Sierra, HomeSense, Winners, and TK Maxx.
  name: Multi-Brand Vendor Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: EDI integration and compliance platform for TJX vendor connectivity.
  name: SPS Commerce
- description: ASN Vendor Portal and EDI integration provider powering TJX's vendor shipping notice system.
  name: DiCentral
- description: EDI integration platform supporting TJX vendor compliance requirements.
  name: Zenbridge
- description: Order management and EDI integration connector for TJX Companies.
  name: Pipe17
- description: Electronic invoicing platform for TJX supplier invoice submission.
  name: Transcepta
- description: Oracle-based supplier portal for invoice management and purchase order tracking.
  name: Oracle iSupplier
- description: EDI integration solution for TJX trading partner compliance.
  name: Cleo
layout: provider
modified: '2026-05-03'
name: TJX Companies
skills: []
slug: tjx
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tjx\nname: TJX Companies\ndescription: >-\n  The TJX Companies, Inc. is an American multinational off-price department store\n  corporation headquartered in Framingham, Massachusetts, ranked No. 80 on the 2024\n  Fortune 500 list. Operating over 4,800 stores across nine countries and three\n  continents under brands including T.J. Maxx, Marshalls, HomeGoods, Sierra, HomeSense\n  (US), and Winners, HomeSense, Marshalls (Canada), TJX provides supplier and vendor\n  integration through EDI and web-based portal platforms. Supplier connectivity\n  is handled via Oracle iSupplier, SupplierOne, and the DiCentral ASN Vendor Portal,\n  supporting purchase orders, advanced shipping notices, invoicing, and payment tracking.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Retail\n  - Off-Price\n  - Fortune 100\n  - Supply Chain\n  - EDI\ncreated: '2024-11-27'\nmodified: '2026-05-03'\n\
  url: >-\n  https://raw.githubusercontent.com/api-evangelist/tjx/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: tjx:tjx-isupplier\n    name: TJX Oracle iSupplier Portal\n    description: >-\n      The TJX Oracle iSupplier portal allows not-for-resale suppliers to manage\n      purchase orders, track invoices, monitor payment status, and handle deduction\n      disputes. Suppliers can access real-time account activity and submit invoices\n      electronically via integration with Transcepta. Available to approved TJX\n      suppliers via login credentials.\n    humanURL: https://www.mytjx.com/mytjx/supplier.html\n    tags:\n      - Supplier Portal\n      - Oracle\n      - Invoicing\n      - Purchase Orders\n    properties:\n      - type: Documentation\n        url: https://www.tjx.com/mytjx/supplier/files/iSupplier-User-Guide-EN.pdf\n\n  - aid: tjx:tjx-edi\n    name: TJX EDI Integration\n    description: >-\n      TJX Companies requires EDI compliance for all resale\
  \ vendors, supporting\n      purchase orders (850), purchase order acknowledgements (855), advanced\n      shipping notices (856), invoices (810), motor carrier load tender (204),\n      response to load tender (990), and transportation carrier shipment status\n      (214). Integration is available through approved EDI service providers\n      including SPS Commerce, DiCentral, Zenbridge, and others.\n    humanURL: https://www.spscommerce.com/network/find-a-partner/view/the-tjx-companies-inc/\n    tags:\n      - EDI\n      - Supply Chain\n      - Vendors\n    properties:\n      - type: Documentation\n        url: https://www.spscommerce.com/network/find-a-partner/view/the-tjx-companies-inc/\n\n  - aid: tjx:tjx-asn-vendor-portal\n    name: TJX ASN Vendor Portal\n    description: >-\n      The TJX Companies LLC Advanced Shipping Notice (ASN) Vendor Portal powered\n      by DiCentral allows resale vendors to create and submit advance shipping\n      notices, manage compliance requirements,\
  \ and handle electronic transaction\n      processing for shipments to TJX distribution centers.\n    humanURL: https://diweb.dicentral.com/tjx/SignUp/GetStarted.aspx\n    tags:\n      - ASN\n      - Shipping\n      - Vendors\n      - DiCentral\n    properties:\n      - type: Documentation\n        url: https://diweb.dicentral.com/tjx/SignUp/GetStarted.aspx\n\n  - aid: tjx:tjx-supplierone\n    name: TJX SupplierOne Diversity Portal\n    description: >-\n      The TJX SupplierOne portal enables diverse supplier registration, certification\n      tracking, and quarterly Tier II program reporting. Suppliers can complete vendor\n      applications, provide business documentation and certifications, and participate\n      in TJX's supplier diversity program.\n    humanURL: https://tjx.supplierone.co/\n    tags:\n      - Supplier Diversity\n      - Vendors\n      - Registration\n    properties:\n      - type: Documentation\n        url: https://tjx.supplierone.co/\n\ncommon:\n  - type: Website\n\
  \    url: https://www.tjx.com/\n  - type: Documentation\n    url: https://www.tjx.com/mytjx/supplier/supplier.html\n  - type: Portal\n    url: https://www.mytjx.com/mytjx/supplier.html\n  - type: GitHubOrganization\n    url: https://github.com/TJX\n  - type: Features\n    data:\n      - name: Oracle iSupplier Portal\n        description: Web-based supplier self-service for invoice tracking, payment status, deduction management, and purchase order visibility.\n      - name: EDI Vendor Integration\n        description: Electronic Data Interchange compliance for purchase orders (850), ASNs (856), invoices (810), and related transactions for resale suppliers.\n      - name: ASN Vendor Portal\n        description: DiCentral-powered portal for creating and submitting advance shipping notices and managing compliance.\n      - name: SupplierOne Diversity Registration\n        description: Supplier diversity portal for diverse supplier registration, certification, and Tier II reporting.\n     \
  \ - name: Transcepta Electronic Invoicing\n        description: Digital invoice submission via Transcepta integration, reducing paperwork and expediting payment cycles.\n      - name: Multi-Brand Vendor Support\n        description: Vendor integration covering all TJX banners including T.J. Maxx, Marshalls, HomeGoods, Sierra, HomeSense, Winners, and TK Maxx.\n  - type: UseCases\n    data:\n      - name: Supplier Invoice Submission\n        description: Suppliers electronically submit invoices through iSupplier or Transcepta and track payment status in real time.\n      - name: Purchase Order Management\n        description: Suppliers receive and acknowledge purchase orders from TJX banners via EDI 850/855 transactions.\n      - name: Advance Shipping Notice\n        description: Vendors create and submit ASNs (EDI 856) to notify TJX distribution centers of incoming shipments.\n      - name: Deduction Dispute Automation\n        description: Suppliers manage and dispute payment deductions\
  \ through the Oracle iSupplier portal.\n      - name: Supplier Diversity Reporting\n        description: Diverse suppliers register, maintain certifications, and submit quarterly Tier II reports through SupplierOne.\n      - name: EDI Compliance Onboarding\n        description: New vendors establish EDI connectivity via approved service providers and complete TJX's testing requirements.\n  - type: Integrations\n    data:\n      - name: SPS Commerce\n        description: EDI integration and compliance platform for TJX vendor connectivity.\n      - name: DiCentral\n        description: ASN Vendor Portal and EDI integration provider powering TJX's vendor shipping notice system.\n      - name: Zenbridge\n        description: EDI integration platform supporting TJX vendor compliance requirements.\n      - name: Pipe17\n        description: Order management and EDI integration connector for TJX Companies.\n      - name: Transcepta\n        description: Electronic invoicing platform for TJX supplier\
  \ invoice submission.\n      - name: Oracle iSupplier\n        description: Oracle-based supplier portal for invoice management and purchase order tracking.\n      - name: Cleo\n        description: EDI integration solution for TJX trading partner compliance.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tjx/refs/heads/main/apis.yml
tags:
- Retail
- Off-Price
- Fortune 100
- Supply Chain
- EDI
url: https://raw.githubusercontent.com/api-evangelist/tjx/refs/heads/main/apis.yml
use_cases:
- description: Suppliers electronically submit invoices through iSupplier or Transcepta and track payment status in real time.
  name: Supplier Invoice Submission
- description: Suppliers receive and acknowledge purchase orders from TJX banners via EDI 850/855 transactions.
  name: Purchase Order Management
- description: Vendors create and submit ASNs (EDI 856) to notify TJX distribution centers of incoming shipments.
  name: Advance Shipping Notice
- description: Suppliers manage and dispute payment deductions through the Oracle iSupplier portal.
  name: Deduction Dispute Automation
- description: Diverse suppliers register, maintain certifications, and submit quarterly Tier II reports through SupplierOne.
  name: Supplier Diversity Reporting
- description: New vendors establish EDI connectivity via approved service providers and complete TJX's testing requirements.
  name: EDI Compliance Onboarding
---
