---
api_count: 3
apis:
- description: Zions Treasury Internet Banking provides businesses with a secure online platform for managing treasury operations including ACH payments, domestic and international wire transfers, account transfers,
  name: Zions Treasury Internet Banking
  slug: treasury-internet-banking
- description: Zions ACH Payments is a payment disbursement solution enabling businesses to pay employees, suppliers, vendors, and tax agencies via ACH. Supports import and export file formats for integration with a
  name: Zions ACH Payments
  slug: ach-payments
- description: Zions Wire Transfer Services enables businesses to send domestic and international wire transfers efficiently. Supports foreign currency transfers to more than 60 countries worldwide. Available throug
  name: Zions Wire Transfer Services
  slug: wire-transfers
common:
- title: ''
  type: Website
  url: https://www.zionsbank.com
- title: ''
  type: Portal
  url: https://treasurygateway.zionsbank.com/
- title: ''
  type: Documentation
  url: https://www.zionsbank.com/business/treasury/
- title: ''
  type: Login
  url: https://www.zionsbank.com/personal/sign-in/
- title: ''
  type: Support
  url: https://www.zionsbank.com/personal/customer-service/
- title: ''
  type: TermsOfService
  url: https://www.zionsbank.com/disclosure-documents/
- title: ''
  type: PrivacyPolicy
  url: https://www.zionsbank.com/about/privacy/
created: '2026-05-03'
description: Zions Bancorporation is one of the nation's premier financial services companies, operating under local management teams and distinct brands in 11 western U.S. states. The company offers a comprehensive suite of banking, treasury management, lending, and wealth management services for individuals, businesses, and public sector clients. Zions provides ERP-to-bank integration capabilities, ACH payment origination, wire transfers, and cash management tools for corporate treasury operations. The company does not currently publish a public REST API developer portal; integrations are delivered via Treasury Internet Banking import/export, NACHA-compliant ACH files, and direct file-transfer arrangements with corporate customers.
features:
- description: Online treasury management platform with payment origination and reporting.
  name: Treasury Internet Banking
- description: NACHA-compliant ACH payment file origination for payroll, vendor, and tax payments.
  name: ACH Origination
- description: Domestic and international wire transfers including foreign currency.
  name: Wire Transfers
- description: Check fraud prevention with issued-check matching and exception review.
  name: Positive Pay
- description: File import/export integration with accounting and ERP systems.
  name: ERP Integration
- description: Real-time visibility into account balances, transactions, and check images.
  name: Account Reporting
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-05-03'
name: Zions Bancorporation
skills: []
slug: zions-bancorp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zions-bancorp\nname: Zions Bancorporation\ndescription: >-\n  Zions Bancorporation is one of the nation's premier financial services companies,\n  operating under local management teams and distinct brands in 11 western U.S. states.\n  The company offers a comprehensive suite of banking, treasury management, lending,\n  and wealth management services for individuals, businesses, and public sector clients.\n  Zions provides ERP-to-bank integration capabilities, ACH payment origination, wire\n  transfers, and cash management tools for corporate treasury operations. The company\n  does not currently publish a public REST API developer portal; integrations are\n  delivered via Treasury Internet Banking import/export, NACHA-compliant ACH files,\n  and direct file-transfer arrangements with corporate customers.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Banking\n  - Financial Services\n  - Treasury Management\n\
  \  - Payments\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zions-bancorp/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: zions-bancorp:treasury-internet-banking\n    name: Zions Treasury Internet Banking\n    description: >-\n      Zions Treasury Internet Banking provides businesses with a secure online\n      platform for managing treasury operations including ACH payments, domestic\n      and international wire transfers, account transfers, positive pay, and\n      real-time cash position visibility. Supports ERP integration via import\n      and export of standard file formats for automated payment origination\n      and reconciliation.\n    humanURL: https://www.zionsbank.com/business/treasury/treasury-internet-banking/\n    tags:\n      - Treasury Management\n      - ACH\n      - Wire Transfers\n      - Cash Management\n      - Banking\n    properties:\n      - type: Documentation\n        url:\
  \ https://www.zionsbank.com/business/treasury/\n      - type: Login\n        url: https://treasurygateway.zionsbank.com/\n  - aid: zions-bancorp:ach-payments\n    name: Zions ACH Payments\n    description: >-\n      Zions ACH Payments is a payment disbursement solution enabling businesses\n      to pay employees, suppliers, vendors, and tax agencies via ACH. Supports\n      import and export file formats for integration with accounting and ERP\n      software, making cash flow management more efficient, predictable, and\n      cost effective.\n    humanURL: https://www.zionsbank.com/business/treasury/treasury-management-select/ach-payments/\n    tags:\n      - ACH\n      - Payments\n      - Treasury Management\n      - Banking\n    properties:\n      - type: Documentation\n        url: https://www.zionsbank.com/business/treasury/treasury-management-select/ach-payments/\n  - aid: zions-bancorp:wire-transfers\n    name: Zions Wire Transfer Services\n    description: >-\n      Zions Wire\
  \ Transfer Services enables businesses to send domestic and\n      international wire transfers efficiently. Supports foreign currency\n      transfers to more than 60 countries worldwide. Available through\n      Treasury Internet Banking for streamlined origination and status tracking.\n    humanURL: https://www.zionsbank.com/business/treasury/disbursements/wire-transfers/\n    tags:\n      - Wire Transfers\n      - International Payments\n      - Banking\n      - Treasury Management\n    properties:\n      - type: Documentation\n        url: https://www.zionsbank.com/business/treasury/disbursements/wire-transfers/\ncommon:\n  - type: Website\n    url: https://www.zionsbank.com\n  - type: Portal\n    url: https://treasurygateway.zionsbank.com/\n  - type: Documentation\n    url: https://www.zionsbank.com/business/treasury/\n  - type: Login\n    url: https://www.zionsbank.com/personal/sign-in/\n  - type: Support\n    url: https://www.zionsbank.com/personal/customer-service/\n  - type:\
  \ TermsOfService\n    url: https://www.zionsbank.com/disclosure-documents/\n  - type: PrivacyPolicy\n    url: https://www.zionsbank.com/about/privacy/\n  - data:\n      - name: Treasury Internet Banking\n        description: Online treasury management platform with payment origination and reporting.\n      - name: ACH Origination\n        description: NACHA-compliant ACH payment file origination for payroll, vendor, and tax payments.\n      - name: Wire Transfers\n        description: Domestic and international wire transfers including foreign currency.\n      - name: Positive Pay\n        description: Check fraud prevention with issued-check matching and exception review.\n      - name: ERP Integration\n        description: File import/export integration with accounting and ERP systems.\n      - name: Account Reporting\n        description: Real-time visibility into account balances, transactions, and check images.\n    name: Features\n    type: Features\n  - data:\n      - name: Corporate\
  \ Treasury Operations\n        description: Cash management and payment origination for corporate treasurers.\n      - name: Public Sector Banking\n        description: Treasury and payment services for state, county, and municipal governments.\n      - name: Small Business Banking\n        description: Banking and payment services for small and mid-sized businesses.\n      - name: Wealth Management\n        description: Trust, investment, and wealth advisory services.\n    name: UseCases\n    type: UseCases\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zions-bancorp/refs/heads/main/apis.yml
tags:
- Banking
- Financial Services
- Treasury Management
- Payments
url: https://raw.githubusercontent.com/api-evangelist/zions-bancorp/refs/heads/main/apis.yml
use_cases:
- description: Cash management and payment origination for corporate treasurers.
  name: Corporate Treasury Operations
- description: Treasury and payment services for state, county, and municipal governments.
  name: Public Sector Banking
- description: Banking and payment services for small and mid-sized businesses.
  name: Small Business Banking
- description: Trust, investment, and wealth advisory services.
  name: Wealth Management
---
