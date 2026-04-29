---
api_count: 2
apis:
- description: The PACER Authentication API allows users to authenticate automatically and without a user interface, facilitating programmatic access for automated systems to court records. Users provide PACER crede
  name: PACER Authentication API
  slug: pacer-authentication-api
- description: The PACER Case Locator (PCL) API is a REST API providing programmatic access to a nationwide index of federal court cases across all Federal Appellate, District, and Bankruptcy courts. Supports both i
  name: PACER Case Locator (PCL) API
  slug: pacer-case-locator-pcl-api
common:
- title: ''
  type: Website
  url: https://www.uscourts.gov/
- title: ''
  type: Portal
  url: https://pacer.uscourts.gov/
- title: ''
  type: DeveloperPortal
  url: https://pacer.uscourts.gov/file-case/developer-resources
- title: ''
  type: SignUp
  url: https://pacer.uscourts.gov/register-account
- title: ''
  type: Contact
  url: https://pacer.uscourts.gov/contact-us
created: '2024-11-20'
description: The Administrative Office of the United States Courts is the administrative agency of the United States federal court system, established in 1939. It provides legislative, administrative, legal, financial, management, program, and information technology support services to the federal courts. The agency operates PACER (Public Access to Court Electronic Records), which provides programmatic access to case and docket information from Federal Appellate, District, and Bankruptcy courts via the PACER Authentication API and PACER Case Locator (PCL) REST API. The agency also provides CM/ECF developer resources for building tools that interface with the Case Management and Electronic Case Filing system.
features:
- description: Programmatic search across a nationwide index of all Federal Appellate, District, and Bankruptcy court cases using the PCL REST API, supporting case search and party search with immediate and batch result modes.
  name: Federal Court Case Search
- description: Token-based authentication API enabling automated systems to obtain PACER authentication tokens without requiring a user interface, suitable for integration into automated data pipelines and legal research tools.
  name: Automated PACER Authentication
- description: Technical resources for developers building tools that interface with the Case Management and Electronic Case Filing (CM/ECF) system, including XML tag specifications, NextGen CM/ECF documentation, and release notes for appellate and bankruptcy systems.
  name: CM/ECF Developer Integration
- description: JSON and XML data feeds providing court lookup information for identifying CM/ECF courts and their configurations, available for integration into court filing software.
  name: Court Lookup Data Feeds
- description: Specialized resources for bankruptcy petition preparation software and case trustee management software vendors, including creditor claim filing specifications and official form changes.
  name: Bankruptcy Filing Integration
- description: Commercial users can run large batch data pulls via the PCL API, with recommended off-peak hours (6 p.m. to 6 a.m. Central Time) to minimize system impact.
  name: Bulk Data Access
image: /assets/icons/administrative-office-of-the-u-s-courts.png
integrations:
- description: Case Management and Electronic Case Filing system for all federal courts.
  name: CM/ECF System
- description: Nationwide index of federal court cases searchable via REST API.
  name: PACER Case Locator
- description: Next-generation electronic filing system with enhanced developer integration support.
  name: NextGen CM/ECF
layout: provider
modified: '2026-04-19'
name: Administrative Office of the U.S. Courts
skills: []
slug: administrative-office-of-the-u-s-courts
solutions: []
source_yaml: "aid: administrative-office-of-the-u-s-courts\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/administrative-office-of-the-u-s-courts/refs/heads/main/apis.yml\nname: Administrative Office of the U.S. Courts\ncreated: '2024-11-20'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n  - Courts\n  - Federal Government\n  - Legal\n  - PACER\n  - Case Records\n  - Judiciary\n  - Open Data\ndescription: >-\n  The Administrative Office of the United States Courts is the administrative\n  agency of the United States federal court system, established in 1939. It\n  provides legislative, administrative, legal, financial, management, program,\n  and information technology support services to the federal courts. The agency\n  operates PACER (Public Access to Court Electronic Records), which provides\n  programmatic access to case and docket information from Federal Appellate,\n  District, and Bankruptcy courts via the PACER Authentication API and PACER\n  Case Locator\
  \ (PCL) REST API. The agency also provides CM/ECF developer\n  resources for building tools that interface with the Case Management and\n  Electronic Case Filing system.\napis:\n  - aid: administrative-office-of-the-u-s-courts:pacer-authentication-api\n    name: PACER Authentication API\n    description: >-\n      The PACER Authentication API allows users to authenticate automatically\n      and without a user interface, facilitating programmatic access for\n      automated systems to court records. Users provide PACER credentials to\n      receive an authentication token used to access the PCL API and other\n      PACER services. Required before using the PACER Case Locator API.\n    humanURL: https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide\n    tags:\n      - Authentication\n      - Courts\n      - PACER\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide\n  \
  \    - type: APIReference\n        url: https://pacer.uscourts.gov/help/pacer/pacer-authentication-api-user-guide\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/administrative-office-of-the-u-s-courts/refs/heads/main/openapi/pacer-authentication-api-openapi.yml\n  - aid: administrative-office-of-the-u-s-courts:pacer-case-locator-pcl-api\n    name: PACER Case Locator (PCL) API\n    description: >-\n      The PACER Case Locator (PCL) API is a REST API providing programmatic\n      access to a nationwide index of federal court cases across all Federal\n      Appellate, District, and Bankruptcy courts. Supports both immediate\n      searches (returning up to 5,400 items per search) and batch searches\n      (up to 108,000 items). Case searches return groups of cases; party\n      searches return parties associated with cases. Supports JSON and XML\n      encoding. Requires PACER authentication token. Separate QA and Production\n      environments\
  \ are available for development and testing.\n    humanURL: https://pacer.uscourts.gov/help/pacer/pacer-case-locator-pcl-api-user-guide\n    tags:\n      - Courts\n      - Legal\n      - Case Records\n      - Federal Courts\n      - REST API\n      - PACER\n    properties:\n      - type: Documentation\n        url: https://pacer.uscourts.gov/help/pacer/pacer-case-locator-pcl-api-user-guide\n      - type: APIReference\n        url: https://pacer.uscourts.gov/sites/default/files/files/PCL-API-Document_3.pdf\n      - type: GettingStarted\n        url: https://pacer.uscourts.gov/file-case/developer-resources\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/administrative-office-of-the-u-s-courts/refs/heads/main/openapi/pacer-case-locator-pcl-api-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.uscourts.gov/\n  - type: Portal\n    url: https://pacer.uscourts.gov/\n  - type: DeveloperPortal\n    url: https://pacer.uscourts.gov/file-case/developer-resources\n\
  \  - type: SignUp\n    url: https://pacer.uscourts.gov/register-account\n  - type: Contact\n    url: https://pacer.uscourts.gov/contact-us\n  - type: Features\n    data:\n      - name: Federal Court Case Search\n        description: >-\n          Programmatic search across a nationwide index of all Federal\n          Appellate, District, and Bankruptcy court cases using the PCL REST\n          API, supporting case search and party search with immediate and batch\n          result modes.\n      - name: Automated PACER Authentication\n        description: >-\n          Token-based authentication API enabling automated systems to obtain\n          PACER authentication tokens without requiring a user interface,\n          suitable for integration into automated data pipelines and legal\n          research tools.\n      - name: CM/ECF Developer Integration\n        description: >-\n          Technical resources for developers building tools that interface with\n          the Case Management\
  \ and Electronic Case Filing (CM/ECF) system,\n          including XML tag specifications, NextGen CM/ECF documentation, and\n          release notes for appellate and bankruptcy systems.\n      - name: Court Lookup Data Feeds\n        description: >-\n          JSON and XML data feeds providing court lookup information for\n          identifying CM/ECF courts and their configurations, available for\n          integration into court filing software.\n      - name: Bankruptcy Filing Integration\n        description: >-\n          Specialized resources for bankruptcy petition preparation software and\n          case trustee management software vendors, including creditor claim\n          filing specifications and official form changes.\n      - name: Bulk Data Access\n        description: >-\n          Commercial users can run large batch data pulls via the PCL API,\n          with recommended off-peak hours (6 p.m. to 6 a.m. Central Time) to\n          minimize system impact.\n  - type:\
  \ UseCases\n    data:\n      - name: Legal Research Automation\n        description: >-\n          Law firms and legal research platforms can use the PCL API to\n          programmatically search federal court case indexes and retrieve\n          case and party information for automated legal research workflows.\n      - name: Litigation Monitoring\n        description: >-\n          Corporate legal departments can monitor federal court filings\n          involving specific parties, cases, or subject matters using automated\n          PCL API queries.\n      - name: Bankruptcy Software Integration\n        description: >-\n          Bankruptcy petition preparation software and trustee management\n          applications can integrate with CM/ECF and PACER APIs to file\n          documents, retrieve case data, and manage creditor information.\n      - name: Court Data Analytics\n        description: >-\n          Academic researchers and legal analytics firms can build datasets\n       \
  \   of federal court case activity using batch PCL API searches across\n          federal court jurisdictions.\n      - name: Legal Technology Development\n        description: >-\n          Legal technology companies can build PACER-integrated products\n          for case tracking, docket monitoring, and court record retrieval\n          using the PACER Authentication and PCL APIs.\n  - type: Integrations\n    data:\n      - name: CM/ECF System\n        description: Case Management and Electronic Case Filing system for all federal courts.\n      - name: PACER Case Locator\n        description: Nationwide index of federal court cases searchable via REST API.\n      - name: NextGen CM/ECF\n        description: Next-generation electronic filing system with enhanced developer integration support.\nmaintainers:\n  - FN: Kin Lane\n    X-twitter: apievangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/administrative-office-of-the-u-s-courts/refs/heads/main/apis.yml
tags:
- Courts
- Federal Government
- Legal
- PACER
- Case Records
- Judiciary
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/administrative-office-of-the-u-s-courts/refs/heads/main/apis.yml
use_cases:
- description: Law firms and legal research platforms can use the PCL API to programmatically search federal court case indexes and retrieve case and party information for automated legal research workflows.
  name: Legal Research Automation
- description: Corporate legal departments can monitor federal court filings involving specific parties, cases, or subject matters using automated PCL API queries.
  name: Litigation Monitoring
- description: Bankruptcy petition preparation software and trustee management applications can integrate with CM/ECF and PACER APIs to file documents, retrieve case data, and manage creditor information.
  name: Bankruptcy Software Integration
- description: Academic researchers and legal analytics firms can build datasets of federal court case activity using batch PCL API searches across federal court jurisdictions.
  name: Court Data Analytics
- description: Legal technology companies can build PACER-integrated products for case tracking, docket monitoring, and court record retrieval using the PACER Authentication and PCL APIs.
  name: Legal Technology Development
---
