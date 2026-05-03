---
api_count: 4
apis:
- description: The Copyright Public Records System (CPRS) provides access to U.S. copyright registration and recordation data with advanced search capabilities and improved interfaces. Replaced the Online Public Cat
  name: Copyright Public Records System
  slug: copyright-public-records
- description: Bulk download of approximately 22 million U.S. copyright registration records from January 1, 1978 to June 27, 2025. Available in raw unparsed MARC, parsed CSV, and tabular CSV formats. Includes regis
  name: Copyright Bulk Datasets
  slug: copyright-bulk-datasets
- description: Searchable directory of licensing documents including compulsory license statements of account, royalty payments, and statutory license records maintained by the Copyright Office.
  name: Licensing Documents Search
  slug: licensing-documents-search
- description: Searchable directory of Online Service Providers (OSPs) that have registered DMCA designated agents with the U.S. Copyright Office per Section 512 of the Digital Millennium Copyright Act.
  name: DMCA Designated Agent Directory
  slug: dmca-designated-agent
common:
- title: ''
  type: Website
  url: https://www.copyright.gov/
- title: Search Copyright Records
  type: Documentation
  url: https://www.copyright.gov/public-records/
- title: Bulk Data Downloads
  type: DataAPI
  url: https://data.copyright.gov
- title: Register Your Work
  type: GettingStarted
  url: https://www.copyright.gov/registration/
- title: Online Registration FAQs
  type: FAQ
  url: https://www.copyright.gov/eco/faq.html
- title: Website Policies
  type: TermsOfService
  url: https://www.copyright.gov/en/about/policies/
- title: Contact the Copyright Office
  type: Contact
  url: https://www.copyright.gov/about/contact/
- title: US Copyright Office Vocabulary
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/us-copyright-office/refs/heads/main/vocabulary/us-copyright-office-vocabulary.yml
- title: US Copyright Office JSON-LD Context
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/us-copyright-office/refs/heads/main/json-ld/us-copyright-office-context.jsonld
created: '2024-12-03'
description: The US Copyright Office is a government agency responsible for administering and enforcing copyright laws in the United States. The office is responsible for registering and documenting copyright claims, maintaining the public catalog of copyright records, providing bulk data downloads of registration records, and administering licensing programs. The Copyright Office provides open bulk datasets of approximately 22 million registration records and is modernizing its systems through the Enterprise Copyright System (ECS) program.
features:
- description: Approximately 22 million copyright registration records from 1978 to present available for bulk download in MARC, parsed CSV, and tabular CSV formats across all copyright work categories.
  name: Copyright Registration Bulk Data
- description: Advanced search system for copyright registration and recordation data, replacing the Online Public Catalog in June 2025.
  name: Copyright Public Records System (CPRS)
- description: Electronic Copyright Office registration system for submitting new copyright registration applications online.
  name: Online Registration (eCO)
- description: Searchable database of compulsory license statements of account and royalty payments filed with the Copyright Office.
  name: Licensing Documents Search
- description: Directory of online service providers that have registered DMCA designated agents per Section 512 of the DMCA.
  name: DMCA Designated Agent Directory
- description: Ongoing modernization of all Copyright Office IT systems into a unified, interconnected digital infrastructure.
  name: Enterprise Copyright System Modernization
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Copyright Office is a department of the Library of Congress; data integrates with LC catalog systems and MARC format records.
  name: Library of Congress
- description: Collaborates with USPTO on intellectual property policy, including joint AI and copyright/patent studies.
  name: U.S. Patent and Trademark Office
jsonld:
- class_count: 5
  name: Us Copyright Office Context
  property_count: 28
  slug: us-copyright-office-context
layout: provider
modified: '2026-05-03'
name: US Copyright Office
skills: []
slug: us-copyright-office
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-copyright-office\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-copyright-office/refs/heads/main/apis.yml\napis:\n  - aid: us-copyright-office:copyright-public-records\n    name: Copyright Public Records System\n    tags:\n      - Copyright\n      - Public Records\n      - Federal Government\n    humanURL: https://publicrecords.copyright.gov/\n    properties:\n      - url: https://publicrecords.copyright.gov/\n        type: Documentation\n      - url: https://www.copyright.gov/public-records/\n        type: GettingStarted\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-copyright-office/refs/heads/main/json-schema/us-copyright-office-registration-schema.json\n        type: JSONSchema\n        title: Copyright Registration Schema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-copyright-office/refs/heads/main/json-schema/us-copyright-office-recordation-schema.json\n        type: JSONSchema\n\
  \        title: Copyright Recordation Schema\n    description: >-\n      The Copyright Public Records System (CPRS) provides access to U.S.\n      copyright registration and recordation data with advanced search\n      capabilities and improved interfaces. Replaced the Online Public\n      Catalog in June 2025 and contains records from 1978 onward.\n  - aid: us-copyright-office:copyright-bulk-datasets\n    name: Copyright Bulk Datasets\n    tags:\n      - Copyright\n      - Bulk Data\n      - Federal Government\n      - Open Data\n    humanURL: https://www.copyright.gov/economic-research/usco-datasets/\n    properties:\n      - url: https://www.copyright.gov/economic-research/usco-datasets/\n        type: Documentation\n      - url: https://data.copyright.gov\n        type: DataAPI\n        title: Bulk Data Download Portal\n    description: >-\n      Bulk download of approximately 22 million U.S. copyright registration\n      records from January 1, 1978 to June 27, 2025. Available in\
  \ raw\n      unparsed MARC, parsed CSV, and tabular CSV formats. Includes\n      registrations, renewals, cancellations, preregistrations, and\n      recordations across all copyright categories.\n  - aid: us-copyright-office:licensing-documents-search\n    name: Licensing Documents Search\n    tags:\n      - Copyright\n      - Licensing\n      - Federal Government\n    humanURL: https://licensing.copyright.gov/lds/\n    properties:\n      - url: https://licensing.copyright.gov/lds/\n        type: Documentation\n    description: >-\n      Searchable directory of licensing documents including compulsory license\n      statements of account, royalty payments, and statutory license records\n      maintained by the Copyright Office.\n  - aid: us-copyright-office:dmca-designated-agent\n    name: DMCA Designated Agent Directory\n    tags:\n      - Copyright\n      - DMCA\n      - Federal Government\n    humanURL: https://www.copyright.gov/dmca-directory/\n    properties:\n      - url: https://www.copyright.gov/dmca-directory/\n\
  \        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/us-copyright-office/refs/heads/main/json-schema/us-copyright-office-dmca-agent-schema.json\n        type: JSONSchema\n        title: DMCA Designated Agent Schema\n    description: >-\n      Searchable directory of Online Service Providers (OSPs) that have\n      registered DMCA designated agents with the U.S. Copyright Office\n      per Section 512 of the Digital Millennium Copyright Act.\nname: US Copyright Office\ntags:\n  - Copyright\n  - Federal Government\n  - Intellectual Property\n  - Open Data\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  The US Copyright Office is a government agency responsible for administering and\n  enforcing copyright laws in the United States. The office is responsible for registering\n  and documenting\
  \ copyright claims, maintaining the public catalog of copyright records,\n  providing bulk data downloads of registration records, and administering licensing\n  programs. The Copyright Office provides open bulk datasets of approximately 22 million\n  registration records and is modernizing its systems through the Enterprise Copyright\n  System (ECS) program.\ncommon:\n  - type: Website\n    url: https://www.copyright.gov/\n  - type: Documentation\n    url: https://www.copyright.gov/public-records/\n    title: Search Copyright Records\n  - type: DataAPI\n    url: https://data.copyright.gov\n    title: Bulk Data Downloads\n  - type: GettingStarted\n    url: https://www.copyright.gov/registration/\n    title: Register Your Work\n  - type: FAQ\n    url: https://www.copyright.gov/eco/faq.html\n    title: Online Registration FAQs\n  - type: TermsOfService\n    url: https://www.copyright.gov/en/about/policies/\n    title: Website Policies\n  - type: Contact\n    url: https://www.copyright.gov/about/contact/\n\
  \    title: Contact the Copyright Office\n  - type: Features\n    data:\n      - name: Copyright Registration Bulk Data\n        description: >-\n          Approximately 22 million copyright registration records from 1978 to\n          present available for bulk download in MARC, parsed CSV, and tabular\n          CSV formats across all copyright work categories.\n      - name: Copyright Public Records System (CPRS)\n        description: >-\n          Advanced search system for copyright registration and recordation\n          data, replacing the Online Public Catalog in June 2025.\n      - name: Online Registration (eCO)\n        description: >-\n          Electronic Copyright Office registration system for submitting new\n          copyright registration applications online.\n      - name: Licensing Documents Search\n        description: >-\n          Searchable database of compulsory license statements of account and\n          royalty payments filed with the Copyright Office.\n   \
  \   - name: DMCA Designated Agent Directory\n        description: >-\n          Directory of online service providers that have registered DMCA\n          designated agents per Section 512 of the DMCA.\n      - name: Enterprise Copyright System Modernization\n        description: >-\n          Ongoing modernization of all Copyright Office IT systems into a\n          unified, interconnected digital infrastructure.\n  - type: UseCases\n    data:\n      - name: Copyright Research and Due Diligence\n        description: >-\n          Searching copyright records to determine ownership, registration\n          status, and rights information for works before licensing or use.\n      - name: Bulk Data Analysis and Research\n        description: >-\n          Downloading bulk copyright registration datasets for academic research,\n          legal analysis, or statistical studies of copyright registration trends.\n      - name: DMCA Compliance\n        description: >-\n          Looking up DMCA\
  \ designated agents for online service providers to send\n          takedown notices per Section 512 requirements.\n      - name: Licensing Compliance Verification\n        description: >-\n          Searching licensing documents to verify statutory license compliance\n          and royalty payment records.\n      - name: Orphan Works Identification\n        description: >-\n          Using copyright records to research ownership of works when rights\n          holders cannot be identified or located.\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/us-copyright-office/refs/heads/main/vocabulary/us-copyright-office-vocabulary.yml\n    title: US Copyright Office Vocabulary\n  - type: JSONLD\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/us-copyright-office/refs/heads/main/json-ld/us-copyright-office-context.jsonld\n    title: US Copyright Office JSON-LD Context\n  - type: Integrations\n    data:\n      - name: Library of Congress\n\
  \        description: >-\n          Copyright Office is a department of the Library of Congress; data\n          integrates with LC catalog systems and MARC format records.\n      - name: U.S. Patent and Trademark Office\n        description: >-\n          Collaborates with USPTO on intellectual property policy, including\n          joint AI and copyright/patent studies.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-copyright-office/refs/heads/main/apis.yml
tags:
- Copyright
- Federal Government
- Intellectual Property
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/us-copyright-office/refs/heads/main/apis.yml
use_cases:
- description: Searching copyright records to determine ownership, registration status, and rights information for works before licensing or use.
  name: Copyright Research and Due Diligence
- description: Downloading bulk copyright registration datasets for academic research, legal analysis, or statistical studies of copyright registration trends.
  name: Bulk Data Analysis and Research
- description: Looking up DMCA designated agents for online service providers to send takedown notices per Section 512 requirements.
  name: DMCA Compliance
- description: Searching licensing documents to verify statutory license compliance and royalty payment records.
  name: Licensing Compliance Verification
- description: Using copyright records to research ownership of works when rights holders cannot be identified or located.
  name: Orphan Works Identification
---
