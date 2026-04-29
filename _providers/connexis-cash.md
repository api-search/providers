---
api_count: 3
apis:
- description: A PSD2-compliant Account Information Service (AISP) API exposed by BNP Paribas Corporate and Institutional Banking. Third-party providers consume this REST/JSON API, which follows the STET PSD2 standa
  name: Connexis Cash PSD2 Account Information API (STET)
  slug: psd2-account-information
- description: A documented Strong Customer Authentication flow that BNP Paribas provides for Connexis Cash to satisfy PSD2 SCA requirements. TPPs integrate the SCA flow into their PSD2 journeys so that Connexis Cas
  name: Connexis Cash Strong Customer Authentication (SCA)
  slug: strong-authentication
- description: The Connexis Cash digital banking application itself. While not a public REST API, it is the user-facing platform that powers payment initiation, real-time tracking, reconciliation, account reporting,
  name: Connexis Cash Digital Banking Platform
  slug: digital-banking-platform
common:
- title: ''
  type: Website
  url: https://cashmanagement.bnpparibas.com/solutions/digital-channels
- title: ''
  type: Developer Portal
  url: https://developers.cib.bnpparibas.com/
- title: ''
  type: Open Banking Tracker
  url: https://www.openbankingtracker.com/provider/connexis-cash
- title: ''
  type: BNP Paribas CIB
  url: https://cib.bnpparibas/
- title: ''
  type: Mobile App
  url: https://apps.apple.com/us/app/connexis-cash-mobile/id1053068521
- title: ''
  type: Support
  url: ''
created: '2024-01-01'
description: Connexis Cash is BNP Paribas's corporate digital banking and cash management platform. It gives multinational corporates a unified online channel for payment initiation, real-time payment tracking, account reporting, reconciliation, and liquidity management across BNP Paribas's global network. Connexis Cash also exposes PSD2-compliant Open Banking APIs through the BNP Paribas CIB developer portal so that third-party providers (TPPs) can retrieve account information and initiate payments on behalf of Connexis Cash users, as well as a Strong Customer Authentication (SCA) flow.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Connexis Cash
skills: []
slug: connexis-cash
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: connexis-cash\nname: Connexis Cash\ndescription: >-\n  Connexis Cash is BNP Paribas's corporate digital banking and cash\n  management platform. It gives multinational corporates a unified online\n  channel for payment initiation, real-time payment tracking, account\n  reporting, reconciliation, and liquidity management across BNP Paribas's\n  global network. Connexis Cash also exposes PSD2-compliant Open Banking\n  APIs through the BNP Paribas CIB developer portal so that third-party\n  providers (TPPs) can retrieve account information and initiate payments\n  on behalf of Connexis Cash users, as well as a Strong Customer\n  Authentication (SCA) flow.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/connexis-cash/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nx-type: company\n\
  tags:\n  - Account Information\n  - BNP Paribas\n  - Cash Management\n  - Corporate Banking\n  - Digital Banking\n  - Liquidity Management\n  - Open Banking\n  - Payments\n  - PSD2\n  - SCA\n  - STET\napis:\n  - aid: connexis-cash:psd2-account-information\n    name: Connexis Cash PSD2 Account Information API (STET)\n    description: >-\n      A PSD2-compliant Account Information Service (AISP) API exposed by\n      BNP Paribas Corporate and Institutional Banking. Third-party providers\n      consume this REST/JSON API, which follows the STET PSD2 standard, to\n      retrieve account information for Connexis Cash users. Production uses\n      OAuth2 Authorization Code Grant with QWAC certificates; the sandbox\n      uses Client Credentials. Onboarded TPPs must supply QWAC certificates,\n      callback URLs, and EBA reference codes.\n    humanURL: https://developers.cib.bnpparibas.com/index.php/api-docs/account-information-psd2-stet-mock\n    baseURL: https://psd2.api.cib.bnpparibas.com/gb-account-information-psd2-stet\n\
  \    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - AISP\n      - PSD2\n      - REST\n      - STET\n    properties:\n      - type: Documentation\n        url: https://developers.cib.bnpparibas.com/index.php/api-docs/account-information-psd2-stet-mock\n      - type: Developer Portal\n        url: https://developers.cib.bnpparibas.com/\n      - type: Production\n        url: https://psd2.api.cib.bnpparibas.com/gb-account-information-psd2-stet\n      - type: Fallback\n        url: https://connexis.bnpparibas.com/\n    contact:\n      - FN: BNP Paribas PSD2 API Support\n        email: dl.cib.api.psd2.support@bnpparibas.com\n    x-features:\n      - PSD2 STET Compliance\n      - OAuth2 Authorization Code Grant (production)\n      - Client Credentials (sandbox)\n      - QWAC Certificate Authentication\n      - Account Balances Retrieval\n      - Transaction Listing\n      - Full-AISP Consent Model\n    x-use-cases:\n      - Aggregate Connexis\
  \ Cash balances into TPP dashboards\n      - Build accounting tools that pull bank data automatically\n      - Power treasury software with multi-bank account access\n  - aid: connexis-cash:strong-authentication\n    name: Connexis Cash Strong Customer Authentication (SCA)\n    description: >-\n      A documented Strong Customer Authentication flow that BNP Paribas\n      provides for Connexis Cash to satisfy PSD2 SCA requirements. TPPs\n      integrate the SCA flow into their PSD2 journeys so that Connexis Cash\n      users authenticate with two factors before consenting to share account\n      data or initiate payments.\n    humanURL: https://developers.cib.bnpparibas.com/index.php/docs/sca\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - PSD2\n      - SCA\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developers.cib.bnpparibas.com/index.php/docs/sca\n      - type: Developer Portal\n    \
  \    url: https://developers.cib.bnpparibas.com/\n    x-features:\n      - Two-Factor Authentication\n      - PSD2 SCA Compliance\n      - Redirect Authentication Flow\n    x-use-cases:\n      - Authenticate users for AISP/PISP consent\n      - Satisfy PSD2 SCA in Open Banking integrations\n  - aid: connexis-cash:digital-banking-platform\n    name: Connexis Cash Digital Banking Platform\n    description: >-\n      The Connexis Cash digital banking application itself. While not a\n      public REST API, it is the user-facing platform that powers payment\n      initiation, real-time tracking, reconciliation, account reporting,\n      and liquidity management for BNP Paribas corporate customers, with\n      web and mobile apps and host-to-host connectivity options.\n    humanURL: https://cashmanagement.bnpparibas.com/solutions/digital-channels\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    tags:\n      - Cash Management\n      - Digital Channel\n\
  \      - Mobile\n    properties:\n      - type: Documentation\n        url: https://cashmanagement.bnpparibas.com/solutions/digital-channels\n      - type: iOS App\n        url: https://apps.apple.com/us/app/connexis-cash-mobile/id1053068521\n    x-features:\n      - Payment Initiation\n      - Real-Time Tracking\n      - Reconciliation\n      - Liquidity Management\n      - Mobile Companion App\n      - Host-to-Host Connectivity\n    x-use-cases:\n      - Centralize global cash visibility for treasury teams\n      - Initiate and authorize cross-border payments\n      - Reconcile inflows and outflows across BNP Paribas accounts\ncommon:\n  - type: Website\n    url: https://cashmanagement.bnpparibas.com/solutions/digital-channels\n  - type: Developer Portal\n    url: https://developers.cib.bnpparibas.com/\n  - type: Open Banking Tracker\n    url: https://www.openbankingtracker.com/provider/connexis-cash\n  - type: BNP Paribas CIB\n    url: https://cib.bnpparibas/\n  - type: Mobile App\n\
  \    url: https://apps.apple.com/us/app/connexis-cash-mobile/id1053068521\n  - type: Support\n    email: dl.cib.api.psd2.support@bnpparibas.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/connexis-cash/refs/heads/main/apis.yml
tags:
- Account Information
- BNP Paribas
- Cash Management
- Corporate Banking
- Digital Banking
- Liquidity Management
- Open Banking
- Payments
- PSD2
- SCA
- STET
url: https://raw.githubusercontent.com/api-evangelist/connexis-cash/refs/heads/main/apis.yml
use_cases: []
---
