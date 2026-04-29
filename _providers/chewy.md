---
api_count: 1
apis:
- description: Chewy provides vendor and supplier integration through the Dsco platform, enabling third-party brands and logistics providers to connect with Chewy's e-commerce marketplace. The integration supports E
  name: Chewy Vendor Integration API
  slug: vendor-integration-api
common:
- title: ''
  type: Website
  url: https://www.chewy.com
- title: ''
  type: GitHub
  url: https://github.com/Chewy-Inc
- title: ''
  type: InvestorRelations
  url: https://investor.chewy.com
- title: ''
  type: Newsroom
  url: https://newsroom.chewy.com
- title: ''
  type: Careers
  url: https://careers.chewy.com
- title: ''
  type: HelpCenter
  url: https://www.chewy.com/app/help
- title: ''
  type: TermsOfUse
  url: https://www.chewy.com/app/content/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.chewy.com/app/content/privacy
- title: ''
  type: ChewyPharmacy
  url: https://www.chewy.com/app/content/chewy-pharmacy
- title: ''
  type: ConnectWithAVet
  url: https://www.chewy.com/app/content/connect-with-a-vet
- title: ''
  type: ChewyHealth
  url: https://www.chewyhealth.com
- title: ''
  type: Brands
  url: ''
created: '2026-03-21'
description: Chewy, Inc. is a Fortune 500 American online retailer of pet food, pet products, prescription medications, and veterinary services headquartered in Plantation, Florida. Chewy is one of the largest e-commerce pet retailers in the United States and supports a customer-focused operating model centered on subscription Autoship orders, Chewy Pharmacy prescription fulfillment, Connect with a Vet telehealth, and Chewy Health insurance. Chewy provides vendor and supplier integration primarily through the Dsco supplier integration platform rather than a public consumer-facing developer API. The Dsco-based integration supports core EDI transactions for purchase orders, inventory updates, shipment confirmations, and invoices, enabling brands and third-party logistics providers to connect with Chewy's e-commerce marketplace.
features:
- name: Online Pet Retail
- name: Autoship Subscriptions
- name: Chewy Pharmacy
- name: Connect With a Vet (Telehealth)
- name: Pet Insurance
- name: Multi-Pet Households
- name: Donations and Adoptions
- name: Same-Day and Next-Day Delivery
- name: Vendor Drop-Ship Integration via Dsco
- name: EDI Order, Inventory, Ship, Invoice Cycle
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Chewy
skills: []
slug: chewy
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: chewy\nname: Chewy\nx-type: company\ndescription: >-\n  Chewy, Inc. is a Fortune 500 American online retailer of pet food,\n  pet products, prescription medications, and veterinary services\n  headquartered in Plantation, Florida. Chewy is one of the largest\n  e-commerce pet retailers in the United States and supports a\n  customer-focused operating model centered on subscription Autoship\n  orders, Chewy Pharmacy prescription fulfillment, Connect with a Vet\n  telehealth, and Chewy Health insurance. Chewy provides vendor and\n  supplier integration primarily through the Dsco supplier integration\n  platform rather than a public consumer-facing developer API. The\n  Dsco-based integration supports core EDI transactions for purchase\n  orders, inventory updates, shipment confirmations, and invoices,\n  enabling brands and third-party logistics providers to connect with\n  Chewy's e-commerce marketplace.\ntype: Index\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  url: >-\n  https://raw.githubusercontent.com/api-evangelist/chewy/refs/heads/main/apis.yml\ntags:\n  - Autoship\n  - Drop Shipping\n  - Dsco\n  - E-Commerce\n  - EDI\n  - Fortune 500\n  - Pet Food\n  - Pet Pharmacy\n  - Pet Retail\n  - Plantation\n  - Subscriptions\n  - Telehealth\n  - Vendor Integration\n  - Veterinary\ncreated: '2026-03-21'\nmodified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid: chewy:vendor-integration-api\n    name: Chewy Vendor Integration API\n    description: >-\n      Chewy provides vendor and supplier integration through the Dsco\n      platform, enabling third-party brands and logistics providers to\n      connect with Chewy's e-commerce marketplace. The integration\n      supports EDI transactions including purchase orders (850),\n      inventory updates (846), shipment confirmations (856), and\n      invoices (810). Vendors authenticate using API tokens and supplier\n      account credentials provided through the Dsco platform.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://www.chewy.com\n    baseURL: https://api.dsco.io\n    tags:\n      - Dsco\n      - E-Commerce\n      - EDI\n      - Pet Retail\n      - Vendor Integration\n    properties:\n      - type: Documentation\n        url: https://www.chewy.com\n      - type: PartnerProgram\n        url: https://www.chewy.com/about\n      - type: DscoPlatform\n        url: https://www.dsco.io\ncommon:\n  - type: Website\n    url: https://www.chewy.com\n  - type: GitHub\n    url: https://github.com/Chewy-Inc\n  - type: InvestorRelations\n    url: https://investor.chewy.com\n  - type: Newsroom\n    url: https://newsroom.chewy.com\n  - type: Careers\n    url: https://careers.chewy.com\n  - type: HelpCenter\n    url: https://www.chewy.com/app/help\n  - type: TermsOfUse\n    url: https://www.chewy.com/app/content/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.chewy.com/app/content/privacy\n  - type: ChewyPharmacy\n    url: https://www.chewy.com/app/content/chewy-pharmacy\n  - type:\
  \ ConnectWithAVet\n    url: https://www.chewy.com/app/content/connect-with-a-vet\n  - type: ChewyHealth\n    url: https://www.chewyhealth.com\n  - name: Brands\n    type: Brands\n    data:\n      - name: Chewy\n      - name: Chewy Pharmacy\n      - name: Chewy Health\n      - name: Connect With a Vet\n      - name: American Journey\n      - name: Tylee's\n      - name: Frisco\n      - name: Vibeful\n  - name: Features\n    type: Features\n    data:\n      - name: Online Pet Retail\n      - name: Autoship Subscriptions\n      - name: Chewy Pharmacy\n      - name: Connect With a Vet (Telehealth)\n      - name: Pet Insurance\n      - name: Multi-Pet Households\n      - name: Donations and Adoptions\n      - name: Same-Day and Next-Day Delivery\n      - name: Vendor Drop-Ship Integration via Dsco\n      - name: EDI Order, Inventory, Ship, Invoice Cycle\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Pet Food and Treat Subscriptions\n      - name: Prescription Pet Medication\
  \ Fulfillment\n      - name: Vet Telehealth Consultations\n      - name: Pet Health Insurance\n      - name: Pet Brand Drop-Ship Marketplace\n      - name: Third-Party Logistics Integration\n      - name: Adoption Partner Donations\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chewy/refs/heads/main/apis.yml
tags:
- Autoship
- Drop Shipping
- Dsco
- E-Commerce
- EDI
- Fortune 500
- Pet Food
- Pet Pharmacy
- Pet Retail
- Plantation
- Subscriptions
- Telehealth
- Vendor Integration
- Veterinary
url: https://raw.githubusercontent.com/api-evangelist/chewy/refs/heads/main/apis.yml
use_cases:
- name: Pet Food and Treat Subscriptions
- name: Prescription Pet Medication Fulfillment
- name: Vet Telehealth Consultations
- name: Pet Health Insurance
- name: Pet Brand Drop-Ship Marketplace
- name: Third-Party Logistics Integration
- name: Adoption Partner Donations
---
