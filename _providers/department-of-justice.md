---
api_count: 5
apis:
- description: The DOJ News API exposes more than 14,000 press releases, speeches, and blog entries from the Office of Public Affairs as a JSON web service. Endpoints under /api/v1/ provide list and detail views for
  name: DOJ News API
  slug: doj-news-api
- description: The FOIA.gov developer resources expose annual FOIA report data as XML conforming to the FOIA Annual Report XML schema. Reports can be retrieved by agency abbreviation and year through a documented en
  name: FOIA.gov Annual Report API
  slug: foia-annual-report-api
- description: The Bureau of Justice Statistics NCVS API provides REST access to the National Crime Victimization Survey datasets. Endpoints expose Personal Victimization, Personal Population, Household Victimizatio
  name: BJS National Crime Victimization Survey (NCVS) API
  slug: bjs-ncvs-api
- description: 'The Bureau of Justice Statistics NIBRS National Estimates API provides REST access to the National Incident-Based Reporting System estimates including victimization counts and rates. Endpoints return '
  name: BJS NIBRS National Estimates API
  slug: bjs-nibrs-api
- description: DOJ publishes datasets through the Open Government program and the Department's Data Inventory. Datasets are also surfaced on Data.gov under the doj-gov organization and are accessible via the CKAN-co
  name: DOJ Open Data Catalog
  slug: doj-open-data-catalog
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.justice.gov
- title: ''
  type: Open Government
  url: https://www.justice.gov/open
- title: ''
  type: Developer
  url: https://www.justice.gov/developer
- title: ''
  type: News
  url: https://www.justice.gov/news
- title: ''
  type: FOIA
  url: https://www.foia.gov
- title: ''
  type: Office of Information Policy
  url: https://www.justice.gov/oip
- title: ''
  type: Bureau of Justice Statistics
  url: https://bjs.ojp.gov
- title: ''
  type: Office of Justice Programs
  url: https://www.ojp.gov
- title: ''
  type: FBI
  url: https://www.fbi.gov
- title: ''
  type: DEA
  url: https://www.dea.gov
- title: ''
  type: ATF
  url: https://www.atf.gov
- title: ''
  type: U.S. Marshals
  url: https://www.usmarshals.gov
- title: ''
  type: Bureau of Prisons
  url: https://www.bop.gov
- title: ''
  type: Data.gov DOJ Catalog
  url: https://catalog.data.gov/organization/doj-gov
- title: ''
  type: Privacy Policy
  url: https://www.justice.gov/legalpolicies
- title: ''
  type: Contact
  url: https://www.justice.gov/contact-us
- title: ''
  type: GitHub Organization
  url: https://github.com/usdoj
- title: ''
  type: JSON-LD
  url: json-ld/department-of-justice-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/department-of-justice-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/department-of-justice-capabilities.yml
created: '2024-12-03'
description: The U.S. Department of Justice (DOJ) is the federal executive department responsible for enforcing the law and defending the interests of the United States. DOJ exposes a portfolio of public APIs and data feeds including the DOJ News API for press releases, speeches, and blog entries from the Office of Public Affairs, the FOIA.gov developer APIs, the Bureau of Justice Statistics NCVS and NIBRS APIs, and the DOJ Open Data Catalog.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Department Of Justice Context
  property_count: 7
  slug: department-of-justice-context
layout: provider
modified: '2026-04-28'
name: Department of Justice
skills: []
slug: department-of-justice
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: department-of-justice\nname: Department of Justice\ndescription: >-\n  The U.S. Department of Justice (DOJ) is the federal executive department\n  responsible for enforcing the law and defending the interests of the United\n  States. DOJ exposes a portfolio of public APIs and data feeds including the\n  DOJ News API for press releases, speeches, and blog entries from the Office\n  of Public Affairs, the FOIA.gov developer APIs, the Bureau of Justice\n  Statistics NCVS and NIBRS APIs, and the DOJ Open Data Catalog.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Bureau of Justice Statistics\n  - Crime\n  - Federal Government\n  - FOIA\n  - Justice\n  - News\n  - Open Data\n  - Press Releases\n  - Statistics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/department-of-justice/refs/heads/main/apis.yml\ncreated: '2024-12-03'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: government\nposition:\
  \ Producer\naccess: Public\napis:\n  - aid: department-of-justice:doj-news-api\n    name: DOJ News API\n    description: >-\n      The DOJ News API exposes more than 14,000 press releases, speeches, and\n      blog entries from the Office of Public Affairs as a JSON web service.\n      Endpoints under /api/v1/ provide list and detail views for each content\n      type and support filtering by title, date, component, and topic, along\n      with pagination and field selection.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.justice.gov/developer/api-documentation/api_v1\n    baseURL: https://www.justice.gov/api/v1\n    tags:\n      - Blog\n      - News\n      - Office of Public Affairs\n      - Press Releases\n      - Speeches\n    properties:\n      - type: Documentation\n        url: https://www.justice.gov/developer/api-documentation/api_v1\n      - type: Developer\n        url: https://www.justice.gov/developer\n    \
  \  - type: Open Government\n        url: https://www.justice.gov/open/developer-resources\n      - type: GitHub Client\n        url: https://github.com/rOpenGov/usdoj\n    contact:\n      - FN: DOJ Office of Public Affairs\n        url: https://www.justice.gov/contact-us\n  - aid: department-of-justice:foia-annual-report-api\n    name: FOIA.gov Annual Report API\n    description: >-\n      The FOIA.gov developer resources expose annual FOIA report data as XML\n      conforming to the FOIA Annual Report XML schema. Reports can be retrieved\n      by agency abbreviation and year through a documented endpoint pattern.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.foia.gov/developer/\n    baseURL: https://www.foia.gov/api\n    tags:\n      - Annual Report\n      - FOIA\n      - XML\n    properties:\n      - type: Documentation\n        url: https://www.foia.gov/developer/\n      - type: Reference\n        url: https://www.foia.gov/developer/agency-api/\n\
  \    contact:\n      - FN: Office of Information Policy\n        url: https://www.justice.gov/oip\n  - aid: department-of-justice:bjs-ncvs-api\n    name: BJS National Crime Victimization Survey (NCVS) API\n    description: >-\n      The Bureau of Justice Statistics NCVS API provides REST access to the\n      National Crime Victimization Survey datasets. Endpoints expose Personal\n      Victimization, Personal Population, Household Victimization, and\n      Household Population data in JSON and CSV. The API uses a path,\n      resource, and query parameter structure with a default page size of\n      1,000 records.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api\n    baseURL: https://bjs.ojp.gov/api\n    tags:\n      - BJS\n      - Crime\n      - NCVS\n      - Statistics\n      - Victimization\n    properties:\n      - type: Documentation\n        url: https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api\n\
  \      - type: NCVS Program\n        url: https://bjs.ojp.gov/data-collection/ncvs\n      - type: Featured\n        url: https://bjs.ojp.gov/featured/national-crime-victimization-survey-ncvs-application-programming-interface-api\n      - type: Data Tools\n        url: https://bjs.ojp.gov/data/data-analysis-tools\n    contact:\n      - FN: Bureau of Justice Statistics\n        url: https://bjs.ojp.gov/about-bjs-website\n  - aid: department-of-justice:bjs-nibrs-api\n    name: BJS NIBRS National Estimates API\n    description: >-\n      The Bureau of Justice Statistics NIBRS National Estimates API provides\n      REST access to the National Incident-Based Reporting System estimates\n      including victimization counts and rates. Endpoints return JSON or CSV\n      and follow a path, resource, query parameter structure with a default\n      page size of 1,000 records.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs-national-estimates-api\n\
  \    baseURL: https://bjs.ojp.gov/api\n    tags:\n      - BJS\n      - Crime\n      - National Estimates\n      - NIBRS\n      - Statistics\n    properties:\n      - type: Documentation\n        url: https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs-national-estimates-api\n      - type: NIBRS Program\n        url: https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs\n      - type: Codebook\n        url: https://bjs.ojp.gov/document/nibrs-codebook-supplementary-documentation.pdf\n    contact:\n      - FN: Bureau of Justice Statistics\n        url: https://bjs.ojp.gov/about-bjs-website\n  - aid: department-of-justice:doj-open-data-catalog\n    name: DOJ Open Data Catalog\n    description: >-\n      DOJ publishes datasets through the Open Government program and the\n      Department's Data Inventory. Datasets are also surfaced on Data.gov\n      under the doj-gov organization and are accessible via the CKAN-compatible\n      Data.gov API.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://www.justice.gov/data\n    baseURL: https://catalog.data.gov/api/3\n    tags:\n      - CKAN\n      - Datasets\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://www.justice.gov/data\n      - type: Open Government\n        url: https://www.justice.gov/open\n      - type: Data.gov DOJ\n        url: https://catalog.data.gov/organization/doj-gov\n      - type: CKAN Reference\n        url: https://docs.ckan.org/en/2.8/api/\n    contact:\n      - FN: DOJ Open Data\n        url: https://www.justice.gov/open\ncommon:\n  - type: Website\n    url: https://www.justice.gov\n  - type: Open Government\n    url: https://www.justice.gov/open\n  - type: Developer\n    url: https://www.justice.gov/developer\n  - type: News\n    url: https://www.justice.gov/news\n  - type: FOIA\n    url: https://www.foia.gov\n  - type: Office of Information Policy\n    url: https://www.justice.gov/oip\n  - type: Bureau of Justice Statistics\n    url: https://bjs.ojp.gov\n\
  \  - type: Office of Justice Programs\n    url: https://www.ojp.gov\n  - type: FBI\n    url: https://www.fbi.gov\n  - type: DEA\n    url: https://www.dea.gov\n  - type: ATF\n    url: https://www.atf.gov\n  - type: U.S. Marshals\n    url: https://www.usmarshals.gov\n  - type: Bureau of Prisons\n    url: https://www.bop.gov\n  - type: Data.gov DOJ Catalog\n    url: https://catalog.data.gov/organization/doj-gov\n  - type: Privacy Policy\n    url: https://www.justice.gov/legalpolicies\n  - type: Contact\n    url: https://www.justice.gov/contact-us\n  - type: GitHub Organization\n    url: https://github.com/usdoj\n  - type: JSON-LD\n    url: json-ld/department-of-justice-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/department-of-justice-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/department-of-justice-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/department-of-justice/refs/heads/main/apis.yml
tags:
- Bureau of Justice Statistics
- Crime
- Federal Government
- FOIA
- Justice
- News
- Open Data
- Press Releases
- Statistics
url: https://raw.githubusercontent.com/api-evangelist/department-of-justice/refs/heads/main/apis.yml
use_cases: []
---
