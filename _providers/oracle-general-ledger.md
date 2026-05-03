---
api_count: 10
apis:
- description: 'REST API for managing journal batches in Oracle Fusion Cloud General Ledger. The journal batches resource allows viewing journal batches, updating batch completion status and reversal attributes, and '
  name: Oracle General Ledger Journal Batches REST API
  slug: ''
- description: 'REST API for querying account balances in Oracle Fusion Cloud General Ledger. The ledger balances resource allows viewing balance amounts for any account combination or accounts defined as part of an '
  name: Oracle General Ledger Ledger Balances REST API
  slug: ''
- description: REST API for viewing accounting period statuses in Oracle Fusion Cloud General Ledger. The accounting period status list of values resource provides period details in a calendar, including ledger iden
  name: Oracle General Ledger Accounting Period Status REST API
  slug: ''
- description: REST API for retrieving currency exchange rate information in Oracle Fusion Cloud General Ledger. The currency rates resource provides information on currency rates for source and target currency comb
  name: Oracle General Ledger Currency Rates REST API
  slug: ''
- description: 'REST API for accessing ledger configuration options in Oracle Fusion Cloud General Ledger. The ledger options resource provides access to ledger setup details including chart of accounts identifiers, '
  name: Oracle General Ledger Ledger Options REST API
  slug: ''
- description: REST API for managing budgetary controls in Oracle Fusion Cloud General Ledger. The budgetary control resources enable viewing budget execution controls, budget impact results, and control budget peri
  name: Oracle General Ledger Budgetary Control REST API
  slug: ''
- description: REST API for managing chart of accounts filter configurations in Oracle Fusion Cloud General Ledger. The chart of accounts filters resource returns filter ID values for chart of accounts filter criter
  name: Oracle General Ledger Chart of Accounts Filters REST API
  slug: ''
- description: REST API for managing intercompany transactions in Oracle Fusion Cloud Financials. The intercompany resources support agreement-based intercompany transactions, intercompany transaction source documen
  name: Oracle Intercompany Transactions REST API
  slug: ''
- description: REST API for managing joint venture general ledger transactions in Oracle Fusion Cloud Financials. The joint venture GL transactions and joint venture subledger transactions resources enable viewing a
  name: Oracle Joint Venture General Ledger Transactions REST API
  slug: ''
- description: REST API for automating bulk data import and export flows with Oracle Fusion Cloud General Ledger. The ERP integrations resource supports loading journal data files, submitting Enterprise Scheduler Se
  name: Oracle General Ledger ERP Integrations REST API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://docs.oracle.com/en/cloud/saas/financials/26a/api.html
- title: ''
  type: Documentation
  url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html
- title: ''
  type: GettingStarted
  url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html
- title: ''
  type: Authentication
  url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html
- title: ''
  type: Change Log
  url: https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html
- title: ''
  type: Support
  url: https://support.oracle.com
- title: ''
  type: Status
  url: https://ocistatus.oraclecloud.com/
- title: ''
  type: TermsOfService
  url: https://www.oracle.com/corporate/contracts/cloud-services/
- title: ''
  type: PrivacyPolicy
  url: https://www.oracle.com/legal/privacy/
- title: ''
  type: Website
  url: https://www.oracle.com/erp/general-ledger/
- title: ''
  type: Sign Up
  url: https://www.oracle.com/cloud/free/
- title: ''
  type: Login
  url: https://cloud.oracle.com/
- title: ''
  type: Blog
  url: https://blogs.oracle.com/cloud-infrastructure/
- title: ''
  type: GitHubOrganization
  url: https://github.com/oracle
- title: ''
  type: Community
  url: https://community.oracle.com/customerconnect/
- title: ''
  type: Implementation Guide
  url: https://docs.oracle.com/en/cloud/saas/financials/26a/faigl/index.html
- title: ''
  type: User Guide
  url: https://docs.oracle.com/en/cloud/saas/financials/26a/faugl/index.html
created: '2024-01-15'
description: Oracle Fusion Cloud General Ledger provides REST APIs for managing core financial accounting operations within Oracle Cloud ERP. These APIs enable programmatic access to journal entries, ledger balances, accounting periods, currency rates, intercompany transactions, budgetary controls, and chart of accounts configurations used by finance teams for enterprise accounting, reporting, and close processes.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-16'
name: Oracle General Ledger
skills: []
slug: oracle-general-ledger
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-general-ledger\nname: Oracle General Ledger\ndescription: >-\n  Oracle Fusion Cloud General Ledger provides REST APIs for managing core\n  financial accounting operations within Oracle Cloud ERP. These APIs enable\n  programmatic access to journal entries, ledger balances, accounting periods,\n  currency rates, intercompany transactions, budgetary controls, and chart of\n  accounts configurations used by finance teams for enterprise accounting,\n  reporting, and close processes.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-general-ledger/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\ntags:\n  - Accounting\n  - Balances\n  - Cloud\n  - ERP\n  - Finance\n  - General Ledger\n  - Journals\napis:\n  - name: Oracle General Ledger Journal Batches REST API\n  \
  \  description: >-\n      REST API for managing journal batches in Oracle Fusion Cloud General Ledger.\n      The journal batches resource allows viewing journal batches, updating batch\n      completion status and reversal attributes, and deleting journal batches.\n      Child resources provide access to journal headers, journal lines,\n      attachments, action logs, descriptive flexfields, and error details.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n    baseURL: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Accounting\n      - General Ledger\n      - Journal Batches\n      - Journals\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n      - type: Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/25b/farfa/api-journal-batches.html\n  \
  \    - type: GettingStarted\n        url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html\n      - type: Change Log\n        url: https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle General Ledger Ledger Balances REST API\n    description: >-\n      REST API for querying account balances in Oracle Fusion Cloud General\n      Ledger. The ledger balances resource allows viewing balance amounts for any\n      account combination or accounts defined as part of an account group.\n      Supports finders for account balance by combination, account group balance,\n      and primary key lookup across ledgers, currencies, and accounting periods.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n\
  \    humanURL: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n    baseURL: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Account Balances\n      - Balances\n      - Financial Reporting\n      - General Ledger\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n      - type: Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/api-ledger-balances.html\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html\n      - type: Change Log\n        url: https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name:\
  \ Oracle General Ledger Accounting Period Status REST API\n    description: >-\n      REST API for viewing accounting period statuses in Oracle Fusion Cloud\n      General Ledger. The accounting period status list of values resource\n      provides period details in a calendar, including ledger identification,\n      period name, and closing status values such as Open, Closed, Future\n      Enterable, Never Opened, Permanently Closed, and Close Pending.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n    baseURL: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Accounting Periods\n      - Financial Close\n      - General Ledger\n      - Period Close\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n      - type: Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/op-accountingperiodstatuslov-get.html\n\
  \      - type: GettingStarted\n        url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html\n      - type: Change Log\n        url: https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle General Ledger Currency Rates REST API\n    description: >-\n      REST API for retrieving currency exchange rate information in Oracle Fusion\n      Cloud General Ledger. The currency rates resource provides information on\n      currency rates for source and target currency combinations, supporting\n      daily rates, corporate rates, and user-defined rate types used in\n      multi-currency accounting and foreign currency translation.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL:\
  \ https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n    baseURL: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Currency Rates\n      - Exchange Rates\n      - Foreign Currency\n      - General Ledger\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html\n      - type: Change Log\n        url: https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle General Ledger Ledger Options REST API\n    description: >-\n      REST API for accessing ledger configuration options in Oracle\
  \ Fusion Cloud\n      General Ledger. The ledger options resource provides access to ledger setup\n      details including chart of accounts identifiers, balancing segment names,\n      accounted period types, budgetary control settings, and document numbering\n      configurations used to define how a ledger processes accounting data.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n    baseURL: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Chart of Accounts\n      - General Ledger\n      - Ledger Options\n      - Ledger Setup\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n      - type: Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/24c/farfa/op-fedledgeroptions-get.html\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html\n\
  \      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html\n      - type: Change Log\n        url: https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle General Ledger Budgetary Control REST API\n    description: >-\n      REST API for managing budgetary controls in Oracle Fusion Cloud General\n      Ledger. The budgetary control resources enable viewing budget execution\n      controls, budget impact results, and control budget periods. These APIs\n      support organizations that use budget accounts to control expenditures\n      against defined appropriation limits and enterprise performance management\n      budget transactions.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n \
  \   baseURL: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Appropriations\n      - Budgetary Control\n      - Budgets\n      - General Ledger\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n      - type: Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/25d/farfa/op-fedbudgetexecutioncontrols-get.html\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html\n      - type: Change Log\n        url: https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle General Ledger Chart of Accounts Filters REST API\n    description:\
  \ >-\n      REST API for managing chart of accounts filter configurations in Oracle\n      Fusion Cloud General Ledger. The chart of accounts filters resource returns\n      filter ID values for chart of accounts filter criteria, enabling control\n      over which account combinations are available for journal entry and\n      financial reporting based on defined filter rules and criteria.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n    baseURL: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Account Combinations\n      - Account Filters\n      - Chart of Accounts\n      - General Ledger\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html\n      - type:\
  \ Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html\n      - type: Change Log\n        url: https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle Intercompany Transactions REST API\n    description: >-\n      REST API for managing intercompany transactions in Oracle Fusion Cloud\n      Financials. The intercompany resources support agreement-based intercompany\n      transactions, intercompany transaction source documents, intercompany\n      agreements with transfer authorization groups, and intercompany\n      organization lookups. These APIs enable automated cross-charge processing\n      and intercompany balancing within the general ledger.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n\
  \    baseURL: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Cross-Charge\n      - General Ledger\n      - Intercompany\n      - Transfer Pricing\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n      - type: Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/25c/farfa/automated-intercompany-cross-charge-of-payables-invoices-using-rest-apis.html\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html\n      - type: Change Log\n        url: https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle Joint Venture General Ledger\
  \ Transactions REST API\n    description: >-\n      REST API for managing joint venture general ledger transactions in Oracle\n      Fusion Cloud Financials. The joint venture GL transactions and joint\n      venture subledger transactions resources enable viewing and updating\n      transactions related to joint venture accounting, supporting partnership\n      accounting workflows that integrate with the general ledger.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n    humanURL: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n    baseURL: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - General Ledger\n      - Joint Venture\n      - Partnership Accounting\n      - Subledger Accounting\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n      - type: Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/24c/farfa/op-jointventuregltransactions-get.html\n\
  \      - type: GettingStarted\n        url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html\n      - type: Change Log\n        url: https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n  - name: Oracle General Ledger ERP Integrations REST API\n    description: >-\n      REST API for automating bulk data import and export flows with Oracle\n      Fusion Cloud General Ledger. The ERP integrations resource supports loading\n      journal data files, submitting Enterprise Scheduler Service jobs for\n      journal import, and running the accounting engine for subledger journal\n      processing. Also provides access to ERP business events and ERP process\n      status details.\n    image: https://www.oracle.com/a/ocom/img/oracle-logo.svg\n\
  \    humanURL: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n    baseURL: https://{instance}.oraclecloud.com/fscmRestApi/resources/11.13.18.05\n    tags:\n      - Data Import\n      - ERP Integration\n      - General Ledger\n      - Journal Import\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n      - type: Reference\n        url: https://docs.oracle.com/en/cloud/saas/financials/25b/farfa/op-erpintegrations-operationname-get.html\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html\n      - type: Change Log\n        url: https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://support.oracle.com\n\
  common:\n  - type: Portal\n    url: https://docs.oracle.com/en/cloud/saas/financials/26a/api.html\n  - type: Documentation\n    url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/index.html\n  - type: GettingStarted\n    url: https://docs.oracle.com/en/cloud/saas/financials/25a/farfa/Quick_Start.html\n  - type: Authentication\n    url: https://docs.oracle.com/en/cloud/saas/financials/26a/farfa/Authentication.html\n  - type: Change Log\n    url: https://docs.oracle.com/en/cloud/saas/readiness/erp/index.html\n  - type: Support\n    url: https://support.oracle.com\n  - type: Status\n    url: https://ocistatus.oraclecloud.com/\n  - type: TermsOfService\n    url: https://www.oracle.com/corporate/contracts/cloud-services/\n  - type: PrivacyPolicy\n    url: https://www.oracle.com/legal/privacy/\n  - type: Website\n    url: https://www.oracle.com/erp/general-ledger/\n  - type: Sign Up\n    url: https://www.oracle.com/cloud/free/\n  - type: Login\n    url: https://cloud.oracle.com/\n\
  \  - type: Blog\n    url: https://blogs.oracle.com/cloud-infrastructure/\n  - type: GitHubOrganization\n    url: https://github.com/oracle\n  - type: Community\n    url: https://community.oracle.com/customerconnect/\n  - type: Implementation Guide\n    url: https://docs.oracle.com/en/cloud/saas/financials/26a/faigl/index.html\n  - type: User Guide\n    url: https://docs.oracle.com/en/cloud/saas/financials/26a/faugl/index.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-general-ledger/refs/heads/main/apis.yml
tags:
- Accounting
- Balances
- Cloud
- ERP
- Finance
- General Ledger
- Journals
url: https://raw.githubusercontent.com/api-evangelist/oracle-general-ledger/refs/heads/main/apis.yml
use_cases: []
---
