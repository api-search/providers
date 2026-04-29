---
api_count: 2
apis:
- description: Online account management portal for Atmos Energy customers providing access to billing, payment, usage history, service requests, and account settings for residential and commercial natural gas custo
  name: Atmos Energy Account Management
  slug: atmos-energy-account-management
- description: The Atmos Energy Builder Portal enables builders and property developers to request and schedule natural gas service lines and meter sets for new construction projects including residential subdivisio
  name: Atmos Energy Builder Portal
  slug: atmos-energy-builder-portal
common:
- title: ''
  type: Website
  url: https://www.atmosenergy.com
- title: ''
  type: Portal
  url: https://www.atmosenergy.com/account-center/
- title: ''
  type: Contact
  url: https://www.atmosenergy.com/contact-us/
- title: ''
  type: Support
  url: https://www.atmosenergy.com/customer-service/
- title: ''
  type: PrivacyPolicy
  url: https://www.atmosenergy.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://www.atmosenergy.com/terms-of-use/
created: '2026-03-23'
description: Atmos Energy is one of the largest natural-gas-only distributors in the United States, delivering natural gas to residential, commercial, public-authority, and industrial customers across multiple states including Texas, Louisiana, Mississippi, Tennessee, Colorado, Kansas, and Virginia. The company provides online account management, a Builder Portal for developers and contractors, and digital service request capabilities for natural gas connections and meter installations.
features:
- description: Pay natural gas bills online through the Atmos Energy Account Center with options for one-time or recurring autopay.
  name: Online Bill Pay
- description: View historical natural gas usage data and billing history through the online account management portal.
  name: Usage History
- description: Submit service start, stop, and transfer requests online for residential and commercial natural gas accounts.
  name: Service Requests
- description: Online portal for builders and property developers to schedule new gas service line installations and meter sets for construction projects.
  name: Builder Portal
- description: Enroll in budget billing to spread natural gas costs evenly across 12 months for predictable monthly payments.
  name: Budget Billing
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integrated payment processing for online bill pay through secure third-party payment processors.
  name: PaymentService
- description: Integration with state-level Low Income Home Energy Assistance Program (LIHEAP) for customer assistance.
  name: State Energy Assistance Programs
layout: provider
modified: '2026-04-19'
name: Atmos Energy
skills: []
slug: atmos-energy
solutions: []
source_yaml: "aid: atmos-energy\nname: Atmos Energy\ndescription: |\n  Atmos Energy is one of the largest natural-gas-only distributors in the United States, delivering natural gas to residential, commercial, public-authority, and industrial customers across multiple states including Texas, Louisiana, Mississippi, Tennessee, Colorado, Kansas, and Virginia. The company provides online account management, a Builder Portal for developers and contractors, and digital service request capabilities for natural gas connections and meter installations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Energy\n- Natural Gas\n- Utilities\n- Infrastructure\nurl: https://raw.githubusercontent.com/api-evangelist/atmos-energy/refs/heads/main/apis.yml\ncreated: '2026-03-23'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: atmos-energy:atmos-energy-account-management\n  name: Atmos Energy Account Management\n  description: |\n   \
  \ Online account management portal for Atmos Energy customers providing access to billing, payment, usage history, service requests, and account settings for residential and commercial natural gas customers.\n  humanURL: https://www.atmosenergy.com/account-center/\n  baseURL: https://www.atmosenergy.com\n  tags:\n  - Account Management\n  - Billing\n  - Natural Gas\n  - Utilities\n  properties:\n  - type: Documentation\n    url: https://www.atmosenergy.com/account-center/\n- aid: atmos-energy:atmos-energy-builder-portal\n  name: Atmos Energy Builder Portal\n  description: |\n    The Atmos Energy Builder Portal enables builders and property developers to request and schedule natural gas service lines and meter sets for new construction projects including residential subdivisions and commercial developments.\n  humanURL: https://www.atmosenergy.com/customer-service/builder-developer-resources/\n  baseURL: https://www.atmosenergy.com\n  tags:\n  - Builder Services\n  - Construction\n  - Natural\
  \ Gas\n  - Service Requests\n  properties:\n  - type: Documentation\n    url: https://www.atmosenergy.com/customer-service/builder-developer-resources/\n  - type: Portal\n    url: https://www.atmosenergy.com/customer-service/builder-developer-resources/\ncommon:\n- type: Website\n  url: https://www.atmosenergy.com\n- type: Portal\n  url: https://www.atmosenergy.com/account-center/\n- type: Contact\n  url: https://www.atmosenergy.com/contact-us/\n- type: Support\n  url: https://www.atmosenergy.com/customer-service/\n- type: PrivacyPolicy\n  url: https://www.atmosenergy.com/privacy-policy/\n- type: TermsOfService\n  url: https://www.atmosenergy.com/terms-of-use/\n- type: Features\n  data:\n  - name: Online Bill Pay\n    description: Pay natural gas bills online through the Atmos Energy Account Center with options for one-time or recurring autopay.\n  - name: Usage History\n    description: View historical natural gas usage data and billing history through the online account management portal.\n\
  \  - name: Service Requests\n    description: Submit service start, stop, and transfer requests online for residential and commercial natural gas accounts.\n  - name: Builder Portal\n    description: Online portal for builders and property developers to schedule new gas service line installations and meter sets for construction projects.\n  - name: Budget Billing\n    description: Enroll in budget billing to spread natural gas costs evenly across 12 months for predictable monthly payments.\n- type: UseCases\n  data:\n  - name: Residential Account Management\n    description: Manage natural gas accounts for homes including billing, payments, usage monitoring, and service requests.\n  - name: Commercial Account Management\n    description: Manage multi-site commercial and industrial natural gas accounts across Atmos Energy service territories.\n  - name: New Construction Gas Service\n    description: Request and schedule new gas service line installations and meter sets for residential subdivisions\
  \ and commercial developments.\n  - name: Energy Assistance Programs\n    description: Access Atmos Energy Share the Warmth and other assistance programs for customers experiencing financial hardship.\n- type: Integrations\n  data:\n  - name: PaymentService\n    description: Integrated payment processing for online bill pay through secure third-party payment processors.\n  - name: State Energy Assistance Programs\n    description: Integration with state-level Low Income Home Energy Assistance Program (LIHEAP) for customer assistance.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/atmos-energy/refs/heads/main/apis.yml
tags:
- Energy
- Natural Gas
- Utilities
- Infrastructure
url: https://raw.githubusercontent.com/api-evangelist/atmos-energy/refs/heads/main/apis.yml
use_cases:
- description: Manage natural gas accounts for homes including billing, payments, usage monitoring, and service requests.
  name: Residential Account Management
- description: Manage multi-site commercial and industrial natural gas accounts across Atmos Energy service territories.
  name: Commercial Account Management
- description: Request and schedule new gas service line installations and meter sets for residential subdivisions and commercial developments.
  name: New Construction Gas Service
- description: Access Atmos Energy Share the Warmth and other assistance programs for customers experiencing financial hardship.
  name: Energy Assistance Programs
---
