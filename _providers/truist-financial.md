---
api_count: 8
api_specs:
- filename: truist-personal-small-business-accounts-openapi.yml
  format: yaml
  label: Truist Personal and Small Business Accounts API
  slug: truist-personal-small-business-accounts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-personal-small-business-accounts-openapi.yml
- filename: truist-personal-small-business-transactions-openapi.yml
  format: yaml
  label: Truist Personal and Small Business Transactions API
  slug: truist-personal-small-business-transactions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-personal-small-business-transactions-openapi.yml
- filename: truist-commercial-accounts-openapi.yml
  format: yaml
  label: Truist Commercial Accounts API
  slug: truist-commercial-accounts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-commercial-accounts-openapi.yml
- filename: truist-commercial-account-transactions-openapi.yml
  format: yaml
  label: Truist Commercial Account Transactions API
  slug: truist-commercial-account-transactions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-commercial-account-transactions-openapi.yml
apis:
- description: The Truist Personal and Small Business Accounts API provides programmatic access to consumer and small business deposit account information, including account details, balances, account types, and own
  name: Truist Personal and Small Business Accounts API
  slug: truist-personal-small-business-accounts-api
- description: The Truist Personal and Small Business Transactions API enables retrieval of transaction history for personal and small business accounts. Developers can access posted and pending transactions, filter
  name: Truist Personal and Small Business Transactions API
  slug: truist-personal-small-business-transactions-api
- description: The Truist Personal and Small Business Client Contact API provides access to client contact information associated with personal and small business accounts, including address, phone number, and email
  name: Truist Personal and Small Business Client Contact API
  slug: truist-personal-small-business-client-contact-api
- description: The Truist Commercial Accounts API provides programmatic access to commercial deposit account information, including account balances, account details, and account summary data for commercial and corp
  name: Truist Commercial Accounts API
  slug: truist-commercial-accounts-api
- description: 'The Truist Commercial Account Transactions API enables programmatic retrieval of commercial account transaction data including ACH credits and debits, wire transfers, checks, and other payment types. '
  name: Truist Commercial Account Transactions API
  slug: truist-commercial-account-transactions-api
- description: The Truist Commercial Account Transaction Image API provides access to check images and transaction document images associated with commercial account transactions. Developers can retrieve front and b
  name: Truist Commercial Account Transaction Image API
  slug: truist-commercial-account-transaction-image-api
- description: 'The Truist Open Banking API provides secure, FDX-compliant (Financial Data Exchange) access to consumer and small business financial data, enabling authorized fintech applications to retrieve account '
  name: Truist Open Banking API
  slug: truist-open-banking-api
- description: The Truist Association Services API provides banking and payment capabilities tailored for associations, non-profit organizations, and community groups. The API supports dues collection, payment proce
  name: Truist Association Services API
  slug: truist-association-services-api
capabilities:
- description: Unified commercial banking capability combining commercial account management and transaction retrieval. Used by treasury teams, ERP integrations, and corporate finance applications to manage commerci
  name: Truist Commercial Banking
  slug: commercial-banking
- description: Unified personal and small business banking capability combining account management and transaction history. Used by fintech developers, personal finance management applications, and account aggregati
  name: Truist Personal Banking
  slug: personal-banking
common:
- title: ''
  type: Website
  url: https://www.truist.com
- title: ''
  type: Portal
  url: https://developer.truist.com/
- title: ''
  type: GettingStarted
  url: https://developer.truist.com/api/working-with-truist
- title: ''
  type: Authentication
  url: https://developer.truist.com/api/working-with-truist
- title: ''
  type: Portal
  url: https://truist-1132.my.site.com/truist/s/
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/rules/truist-financial-rules.yml
- title: ''
  type: InvestorRelations
  url: https://investor.truist.com/
- title: ''
  type: About
  url: https://www.truist.com/about-truist
- title: ''
  type: Blog
  url: https://ir.truist.com/news-releases
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/truistfinancial
- title: ''
  type: X
  url: https://twitter.com/Truist
- title: ''
  type: GitHub
  url: https://github.com/truistbank
- title: ''
  type: PrivacyPolicy
  url: https://www.truist.com/privacy-security
- title: ''
  type: TermsOfService
  url: https://www.truist.com/about-truist/terms-conditions
created: '2026-03-21'
description: Truist Financial Corporation is a purpose-driven financial services company headquartered in Charlotte, North Carolina, formed by the merger of BB&T and SunTrust Banks in 2019. As one of the ten largest commercial banks in the United States, Truist offers a comprehensive suite of developer APIs through its Developer Center, enabling financial institutions, fintech companies, and enterprise clients to integrate banking capabilities into their applications. The platform covers personal and small business banking, commercial accounts, transactions, open banking, and association services, with OAuth 2.0 and API key authentication. Truist launched FDX-compliant open banking in 2026, partnering with Mastercard and Plaid to enable secure, tokenized financial data sharing for consumers and businesses.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 10
  name: Truist Financial Context
  property_count: 22
  slug: truist-financial-context
layout: provider
modified: '2026-05-03'
name: Truist Financial
rules:
- name: Truist Financial API Rules
  rule_count: 12
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 8
  slug: truist-financial-rules
skills: []
slug: truist-financial
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: truist-financial\nurl: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/apis.yml\nname: Truist Financial\ndescription: >-\n  Truist Financial Corporation is a purpose-driven financial services company headquartered\n  in Charlotte, North Carolina, formed by the merger of BB&T and SunTrust Banks in 2019.\n  As one of the ten largest commercial banks in the United States, Truist offers a comprehensive\n  suite of developer APIs through its Developer Center, enabling financial institutions,\n  fintech companies, and enterprise clients to integrate banking capabilities into their\n  applications. The platform covers personal and small business banking, commercial accounts,\n  transactions, open banking, and association services, with OAuth 2.0 and API key authentication.\n  Truist launched FDX-compliant open banking in 2026, partnering with Mastercard and Plaid\n  to enable secure, tokenized financial data sharing for consumers and businesses.\n\
  type: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Banking\n  - Financial Services\n  - Open Banking\n  - Commercial Banking\n  - Personal Banking\n  - Payments\n  - Accounts\n  - Transactions\n  - Fortune 500\naccess: 3rd-Party\ncreated: '2026-03-21'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: truist-financial:truist-personal-small-business-accounts-api\n    name: Truist Personal and Small Business Accounts API\n    tags:\n      - Accounts\n      - Personal Banking\n      - Small Business\n      - Banking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.truist.com/v1\n    humanURL: https://developer.truist.com/api/personal-and-small-business-accounts/overview\n    properties:\n      - url: https://developer.truist.com/api/personal-and-small-business-accounts/overview\n        type: Documentation\n      - url: https://developer.truist.com/api/personal-and-small-business-accounts/documentation\n\
  \        type: Documentation\n      - url: https://developer.truist.com/api/working-with-truist\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-personal-small-business-accounts-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Truist Personal and Small Business Accounts API provides programmatic access\n      to consumer and small business deposit account information, including account details,\n      balances, account types, and ownership information. Developers can retrieve account\n      lists for authenticated clients, access individual account details, and retrieve\n      balance information for checking, savings, and money market accounts. The API supports\n      OAuth 2.0 authentication and is designed for fintech integrations, account aggregation\n      platforms, and personal finance management applications.\n  - aid: truist-financial:truist-personal-small-business-transactions-api\n\
  \    name: Truist Personal and Small Business Transactions API\n    tags:\n      - Transactions\n      - Personal Banking\n      - Small Business\n      - Banking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.truist.com/v1\n    humanURL: https://developer.truist.com/api/personal-and-small-business-transactions/overview\n    properties:\n      - url: https://developer.truist.com/api/personal-and-small-business-transactions/overview\n        type: Documentation\n      - url: https://developer.truist.com/api/working-with-truist\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-personal-small-business-transactions-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Truist Personal and Small Business Transactions API enables retrieval of transaction\n      history for personal and small business accounts. Developers can\
  \ access posted and\n      pending transactions, filter by date range, and retrieve transaction details including\n      merchant information, amounts, and transaction categories. The API supports OAuth 2.0\n      authentication and is suitable for personal finance management tools, accounting\n      integrations, and expense tracking applications.\n  - aid: truist-financial:truist-personal-small-business-client-contact-api\n    name: Truist Personal and Small Business Client Contact API\n    tags:\n      - Client Management\n      - Personal Banking\n      - Small Business\n      - Contact Information\n      - Banking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.truist.com/v1\n    humanURL: https://developer.truist.com/api/personal-and-small-business-client-contact/overview\n    properties:\n      - url: https://developer.truist.com/api/personal-and-small-business-client-contact/overview\n        type: Documentation\n\
  \      - url: https://developer.truist.com/api/working-with-truist\n        type: Authentication\n    description: >-\n      The Truist Personal and Small Business Client Contact API provides access to client\n      contact information associated with personal and small business accounts, including\n      address, phone number, and email address data. This API enables authorized applications\n      to retrieve and manage contact details for authenticated Truist clients, supporting\n      CRM integrations and account management workflows.\n  - aid: truist-financial:truist-commercial-accounts-api\n    name: Truist Commercial Accounts API\n    tags:\n      - Accounts\n      - Commercial Banking\n      - Treasury\n      - Banking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.truist.com/v1\n    humanURL: https://developer.truist.com/api/commercial-accounts/overview\n    properties:\n      - url: https://developer.truist.com/api/commercial-accounts/overview\n\
  \        type: Documentation\n      - url: https://developer.truist.com/api/commercial-accounts/documentation\n        type: Documentation\n      - url: https://developer.truist.com/api/working-with-truist\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-commercial-accounts-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Truist Commercial Accounts API provides programmatic access to commercial deposit\n      account information, including account balances, account details, and account summary\n      data for commercial and corporate clients. The API supports treasury management\n      integrations, ERP system connectivity, and cash management platforms. It enables\n      real-time balance reporting, account hierarchy retrieval, and integration with\n      commercial banking operations. OAuth 2.0 and API key authentication are supported.\n  - aid: truist-financial:truist-commercial-account-transactions-api\n\
  \    name: Truist Commercial Account Transactions API\n    tags:\n      - Transactions\n      - Commercial Banking\n      - Treasury\n      - Banking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.truist.com/v1\n    humanURL: https://developer.truist.com/api/commercial-account-transactions/overview\n    properties:\n      - url: https://developer.truist.com/api/commercial-account-transactions/overview\n        type: Documentation\n      - url: https://developer.truist.com/api/commercial-account-transactions/documentation\n        type: Documentation\n      - url: https://developer.truist.com/api/working-with-truist\n        type: Authentication\n      - url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/openapi/truist-commercial-account-transactions-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Truist Commercial Account Transactions API enables programmatic retrieval\
  \ of\n      commercial account transaction data including ACH credits and debits, wire transfers,\n      checks, and other payment types. The API supports filtering by date range and transaction\n      type, enabling ERP integrations, cash flow reconciliation, and automated accounting\n      workflows. It is designed for treasury teams, corporate finance applications, and\n      commercial banking integrations.\n  - aid: truist-financial:truist-commercial-account-transaction-image-api\n    name: Truist Commercial Account Transaction Image API\n    tags:\n      - Transactions\n      - Check Images\n      - Commercial Banking\n      - Documents\n      - Banking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.truist.com/v1\n    humanURL: https://developer.truist.com/api/commercial-account-transaction-image/overview\n    properties:\n      - url: https://developer.truist.com/api/commercial-account-transaction-image/overview\n\
  \        type: Documentation\n      - url: https://developer.truist.com/api/working-with-truist\n        type: Authentication\n    description: >-\n      The Truist Commercial Account Transaction Image API provides access to check images\n      and transaction document images associated with commercial account transactions.\n      Developers can retrieve front and back images of checks, deposit slips, and other\n      payment documents by transaction reference. The API supports document archiving,\n      audit workflows, and automated reconciliation integrations for commercial banking clients.\n  - aid: truist-financial:truist-open-banking-api\n    name: Truist Open Banking API\n    tags:\n      - Open Banking\n      - FDX\n      - Financial Data Exchange\n      - Accounts\n      - Banking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.truist.com/v1\n    humanURL: https://truist-1132.my.site.com/truist/s/\n    properties:\n\
  \      - url: https://truist-1132.my.site.com/truist/s/\n        type: Portal\n      - url: https://truist-1132.my.site.com/truist/s/subscriptions\n        type: Documentation\n      - url: https://www.prnewswire.com/news-releases/truist-launches-secure-open-banking-experience-302685248.html\n        type: Announcement\n    description: >-\n      The Truist Open Banking API provides secure, FDX-compliant (Financial Data Exchange)\n      access to consumer and small business financial data, enabling authorized fintech\n      applications to retrieve account balances, transaction history, and payment information\n      with client consent. Launched in February 2026 in partnership with Mastercard's open\n      finance platform, the API replaces credential sharing with tokenized, permission-based\n      access. Truist expanded the program through a Plaid data-access agreement in March 2026,\n      enabling clients to manage and revoke third-party data access through a centralized\n      consent\
  \ portal. The API supports account information, transaction data, investment data,\n      and loan data per FDX standards.\n  - aid: truist-financial:truist-association-services-api\n    name: Truist Association Services API\n    tags:\n      - Association Services\n      - Community Banking\n      - Banking\n      - Payments\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.truist.com/v1\n    humanURL: https://developer.truist.com/categories/association-services\n    properties:\n      - url: https://developer.truist.com/categories/association-services\n        type: Documentation\n      - url: https://developer.truist.com/api/working-with-truist\n        type: Authentication\n    description: >-\n      The Truist Association Services API provides banking and payment capabilities tailored\n      for associations, non-profit organizations, and community groups. The API supports\n      dues collection, payment processing, member\
  \ account management, and reporting for\n      trade associations, homeowners associations, and membership organizations that bank\n      with Truist. It enables integration of banking workflows into association management\n      platforms and member portals.\ncommon:\n  - url: https://www.truist.com\n    name: Truist Website\n    type: Website\n  - url: https://developer.truist.com/\n    name: Developer Center\n    type: Portal\n  - url: https://developer.truist.com/api/working-with-truist\n    name: Getting Started\n    type: GettingStarted\n  - url: https://developer.truist.com/api/working-with-truist\n    name: Authentication\n    type: Authentication\n  - url: https://truist-1132.my.site.com/truist/s/\n    name: Open Banking Portal\n    type: Portal\n  - url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/rules/truist-financial-rules.yml\n    name: Spectral Rules\n    type: SpectralRules\n  - url: https://investor.truist.com/\n    name: Investor\
  \ Relations\n    type: InvestorRelations\n  - url: https://www.truist.com/about-truist\n    name: About Truist\n    type: About\n  - url: https://ir.truist.com/news-releases\n    name: Press Releases\n    type: Blog\n  - url: https://www.linkedin.com/company/truistfinancial\n    name: Truist on LinkedIn\n    type: LinkedIn\n  - url: https://twitter.com/Truist\n    name: Truist on X (Twitter)\n    type: X\n  - url: https://github.com/truistbank\n    name: Truist on GitHub\n    type: GitHub\n  - url: https://www.truist.com/privacy-security\n    name: Privacy Policy\n    type: PrivacyPolicy\n  - url: https://www.truist.com/about-truist/terms-conditions\n    name: Terms of Service\n    type: TermsOfService\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/apis.yml
tags:
- Banking
- Financial Services
- Open Banking
- Commercial Banking
- Personal Banking
- Payments
- Accounts
- Transactions
- Fortune 500
url: https://raw.githubusercontent.com/api-evangelist/truist-financial/refs/heads/main/apis.yml
use_cases: []
---
