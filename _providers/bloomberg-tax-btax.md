---
api_count: 2
apis:
- description: Access Bloomberg Tax data including tax rates, regulations, guidance, and compliance data for integration into enterprise tax technology systems and workflows. Covers federal, state, and international
  name: Bloomberg Tax Data API
  slug: btax-data-api
- description: Specialized transfer pricing research and data platform providing comparables databases, country-by-country reporting data, and transfer pricing documentation tools for multinational tax compliance.
  name: Bloomberg Tax Transfer Pricing
  slug: btax-transfer-pricing
common:
- title: ''
  type: Portal
  url: https://pro.bloombergtax.com/
- title: ''
  type: Documentation
  url: https://pro.bloombergtax.com/
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/privacy/
- title: ''
  type: Support
  url: https://pro.bloombergtax.com/contact/
created: '2024-01-01'
description: Bloomberg Tax (BTAX) is a comprehensive tax research, planning, and compliance platform providing tax professionals with authoritative primary sources, expert analysis, and practical tools. Bloomberg Tax covers federal, state, and international tax law and provides data APIs for integrating tax rates, regulations, and guidance into enterprise tax technology workflows.
features:
- description: Access to IRC, regulations, rulings, and court decisions.
  name: Primary Tax Sources
- description: Bloomberg Tax practitioner analysis and practice portfolios.
  name: Expert Analysis
- description: Federal, state, local, and international tax rates data.
  name: Tax Rates Database
- description: Real-time tax news and regulatory update alerts.
  name: News and Updates
- description: Comparables databases and documentation tools for transfer pricing.
  name: Transfer Pricing Tools
- description: Integration with tax workpaper and compliance software.
  name: Workpapers Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Tax (BTAX)
skills: []
slug: bloomberg-tax-btax
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bloomberg-tax-btax\nname: Bloomberg Tax (BTAX)\ndescription: Bloomberg Tax (BTAX) is a comprehensive tax research, planning, and\n  compliance platform providing tax professionals with authoritative primary sources,\n  expert analysis, and practical tools. Bloomberg Tax covers federal, state, and international\n  tax law and provides data APIs for integrating tax rates, regulations, and guidance\n  into enterprise tax technology workflows.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-tax-btax/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Tax\n- Tax Research\n- Tax Compliance\n- Tax Planning\n- Federal Tax\n- International Tax\n- Bloomberg Tax\napis:\n- aid: bloomberg-tax-btax:btax-data-api\n  name: Bloomberg Tax Data API\n  description: Access Bloomberg Tax data including tax rates, regulations,\
  \ guidance,\n    and compliance data for integration into enterprise tax technology systems and\n    workflows. Covers federal, state, and international tax data.\n  humanURL: https://pro.bloombergtax.com/\n  baseURL: https://api.bloombergtax.com\n  tags:\n  - Tax Rates\n  - Tax Regulations\n  - Compliance Data\n  - Federal Tax\n  - State Tax\n  properties:\n  - type: Documentation\n    url: https://pro.bloombergtax.com/\n- aid: bloomberg-tax-btax:btax-transfer-pricing\n  name: Bloomberg Tax Transfer Pricing\n  description: Specialized transfer pricing research and data platform providing\n    comparables databases, country-by-country reporting data, and transfer pricing\n    documentation tools for multinational tax compliance.\n  humanURL: https://pro.bloombergtax.com/transfer-pricing/\n  baseURL: https://api.bloombergtax.com/transfer-pricing\n  tags:\n  - Transfer Pricing\n  - International Tax\n  - BEPS\n  - Comparables\n  properties:\n  - type: Documentation\n    url: https://pro.bloombergtax.com/transfer-pricing/\n\
  common:\n- type: Portal\n  url: https://pro.bloombergtax.com/\n- type: Documentation\n  url: https://pro.bloombergtax.com/\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://pro.bloombergtax.com/contact/\n- type: Features\n  data:\n  - name: Primary Tax Sources\n    description: Access to IRC, regulations, rulings, and court decisions.\n  - name: Expert Analysis\n    description: Bloomberg Tax practitioner analysis and practice portfolios.\n  - name: Tax Rates Database\n    description: Federal, state, local, and international tax rates data.\n  - name: News and Updates\n    description: Real-time tax news and regulatory update alerts.\n  - name: Transfer Pricing Tools\n    description: Comparables databases and documentation tools for transfer pricing.\n  - name: Workpapers Integration\n    description: Integration with tax workpaper and compliance software.\n- type:\
  \ UseCases\n  data:\n  - name: Tax Research\n    description: Research federal and state tax law using authoritative primary sources.\n  - name: Tax Planning\n    description: Analyze tax planning strategies with expert guidance and analysis.\n  - name: International Tax Compliance\n    description: Navigate international tax obligations and transfer pricing rules.\n  - name: Tax Technology Integration\n    description: Integrate Bloomberg Tax data into tax software and ERP systems.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-tax-btax/refs/heads/main/apis.yml
tags:
- Tax
- Tax Research
- Tax Compliance
- Tax Planning
- Federal Tax
- International Tax
- Bloomberg Tax
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-tax-btax/refs/heads/main/apis.yml
use_cases:
- description: Research federal and state tax law using authoritative primary sources.
  name: Tax Research
- description: Analyze tax planning strategies with expert guidance and analysis.
  name: Tax Planning
- description: Navigate international tax obligations and transfer pricing rules.
  name: International Tax Compliance
- description: Integrate Bloomberg Tax data into tax software and ERP systems.
  name: Tax Technology Integration
---
