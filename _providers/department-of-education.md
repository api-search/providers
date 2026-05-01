---
api_count: 4
apis:
- description: The College Scorecard API provides programmatic access to postsecondary institution and field-of-study data published by the U.S. Department of Education. The API exposes more than 6,000 schools and o
  name: College Scorecard API
  slug: college-scorecard-api
- description: The Department of Education Open Data Platform (ODP) at data.ed.gov is built on CKAN and exposes a CKAN-compatible REST API for searching, retrieving, and downloading the Department's public datasets.
  name: Department of Education Open Data Platform API
  slug: open-data-platform-api
- description: The Integrated Postsecondary Education Data System (IPEDS) gathers data annually from every college, university, and technical and vocational institution that participates in the federal student finan
  name: IPEDS Data
  slug: ipeds-data
- description: EDFacts is a centralized data collection through which state education agencies submit pre-kindergarten through grade 12 (PK-12) education data to the U.S. Department of Education. EDFacts data are pu
  name: EDFacts Data
  slug: edfacts-data
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.ed.gov
- title: ''
  type: Open Data Platform
  url: https://data.ed.gov/
- title: ''
  type: Developer Portal
  url: https://api.data.gov/
- title: ''
  type: NCES
  url: https://nces.ed.gov/
- title: ''
  type: College Scorecard
  url: https://collegescorecard.ed.gov/
- title: ''
  type: Federal Student Aid
  url: https://studentaid.gov
- title: ''
  type: Data.gov ED Catalog
  url: https://catalog.data.gov/dataset?organization=ed-gov
- title: ''
  type: News
  url: https://www.ed.gov/news
- title: ''
  type: Contact
  url: https://www.ed.gov/about/contact-us
- title: ''
  type: Privacy Policy
  url: https://www.ed.gov/notices/privacy
- title: ''
  type: GitHub Organization
  url: https://github.com/usedgov
- title: ''
  type: JSON-LD
  url: json-ld/department-of-education-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/department-of-education-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/department-of-education-capabilities.yml
created: '2024-12-03'
description: The U.S. Department of Education (ED) is a federal agency that manages and coordinates federal assistance to education and establishes policy for it. ED's mission is to promote student achievement and preparation for global competitiveness, and to ensure equal access to education. The Department exposes a portfolio of public APIs through api.data.gov, NCES, and the Open Data Platform (ODP) at data.ed.gov for postsecondary outcomes, institutional characteristics, and federal education programs.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Department Of Education Context
  property_count: 5
  slug: department-of-education-context
layout: provider
modified: '2026-04-28'
name: Department of Education
skills: []
slug: department-of-education
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: department-of-education\nname: Department of Education\ndescription: >-\n  The U.S. Department of Education (ED) is a federal agency that manages and\n  coordinates federal assistance to education and establishes policy for it.\n  ED's mission is to promote student achievement and preparation for global\n  competitiveness, and to ensure equal access to education. The Department\n  exposes a portfolio of public APIs through api.data.gov, NCES, and the Open\n  Data Platform (ODP) at data.ed.gov for postsecondary outcomes, institutional\n  characteristics, and federal education programs.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - College Scorecard\n  - Education\n  - Federal Government\n  - Higher Education\n  - IPEDS\n  - K-12\n  - NCES\n  - Open Data\n  - Postsecondary\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/department-of-education/refs/heads/main/apis.yml\ncreated: '2024-12-03'\nmodified:\
  \ '2026-04-28'\nspecificationVersion: '0.19'\nxType: government\nposition: Producer\naccess: Public\napis:\n  - aid: department-of-education:college-scorecard-api\n    name: College Scorecard API\n    description: >-\n      The College Scorecard API provides programmatic access to postsecondary\n      institution and field-of-study data published by the U.S. Department of\n      Education. The API exposes more than 6,000 schools and over 1,900 data\n      points per institution drawn from IPEDS, the National Student Loan Data\n      System (NSLDS), and U.S. Department of the Treasury sources, including\n      cost, completion, earnings, debt, and demographic outcomes. Requests\n      require an api.data.gov API key passed via the api_key query parameter.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://collegescorecard.ed.gov/data/\n    baseURL: https://api.data.gov/ed/collegescorecard/v1\n    tags:\n      - College Scorecard\n\
  \      - Earnings\n      - Higher Education\n      - Postsecondary\n      - Schools\n    properties:\n      - type: Documentation\n        url: https://collegescorecard.ed.gov/data/api-documentation/\n      - type: API\n        url: https://collegescorecard.ed.gov/data/api/\n      - type: Data\n        url: https://collegescorecard.ed.gov/data/\n      - type: GitHub\n        url: https://github.com/RTICWDT/college-scorecard\n      - type: Sign Up\n        url: https://api.data.gov/signup/\n    contact:\n      - FN: College Scorecard\n        email: scorecarddata@rti.org\n        url: https://collegescorecard.ed.gov/data/\n  - aid: department-of-education:open-data-platform-api\n    name: Department of Education Open Data Platform API\n    description: >-\n      The Department of Education Open Data Platform (ODP) at data.ed.gov is\n      built on CKAN and exposes a CKAN-compatible REST API for searching,\n      retrieving, and downloading the Department's public datasets. The API\n   \
  \   surface mirrors CKAN package, resource, group, and search actions over\n      JSON.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://data.ed.gov/\n    baseURL: https://data.ed.gov/api/3\n    tags:\n      - CKAN\n      - Datasets\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://data.ed.gov/about\n      - type: FAQ\n        url: https://data.ed.gov/faq\n      - type: User Guide\n        url: https://data.ed.gov/pages/publichelp\n      - type: CKAN Reference\n        url: https://docs.ckan.org/en/2.8/api/\n    contact:\n      - FN: Department of Education ODP\n        email: ODP@ed.gov\n        url: https://data.ed.gov/\n  - aid: department-of-education:ipeds-data\n    name: IPEDS Data\n    description: >-\n      The Integrated Postsecondary Education Data System (IPEDS) gathers data\n      annually from every college, university, and technical and vocational\n      institution that participates\
  \ in the federal student financial aid\n      programs. NCES distributes IPEDS data via downloadable CSV files,\n      Access databases, and a Find Your College tool rather than a public REST\n      API; many of these datasets are also exposed via the College Scorecard\n      and ODP APIs.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://nces.ed.gov/ipeds\n    baseURL: https://api.example.com\n    tags:\n      - Bulk Data\n      - Higher Education\n      - IPEDS\n      - NCES\n      - Postsecondary\n    properties:\n      - type: Documentation\n        url: https://nces.ed.gov/ipeds\n      - type: Use the Data\n        url: https://nces.ed.gov/ipeds/use-the-data\n      - type: Find Your College\n        url: https://nces.ed.gov/ipeds/find-your-college\n      - type: Downloads\n        url: https://nces.ed.gov/ipeds/use-the-data/download-access-database\n    contact:\n      - FN: NCES IPEDS\n        url: https://nces.ed.gov/ipeds\n\
  \  - aid: department-of-education:edfacts-data\n    name: EDFacts Data\n    description: >-\n      EDFacts is a centralized data collection through which state education\n      agencies submit pre-kindergarten through grade 12 (PK-12) education\n      data to the U.S. Department of Education. EDFacts data are published as\n      downloadable files and are also accessible through partner APIs such\n      as the Urban Institute Education Data Explorer.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www2.ed.gov/about/inits/ed/edfacts/index.html\n    baseURL: https://api.example.com\n    tags:\n      - Bulk Data\n      - EDFacts\n      - K-12\n      - State Data\n    properties:\n      - type: Documentation\n        url: https://www2.ed.gov/about/inits/ed/edfacts/index.html\n      - type: Data Files\n        url: https://www2.ed.gov/about/inits/ed/edfacts/data-files/index.html\n      - type: Education Data Explorer\n        url:\
  \ https://educationdata.urban.org/documentation/\n    contact:\n      - FN: EDFacts\n        email: EDFacts@ed.gov\n        url: https://www2.ed.gov/about/inits/ed/edfacts/index.html\ncommon:\n  - type: Website\n    url: https://www.ed.gov\n  - type: Open Data Platform\n    url: https://data.ed.gov/\n  - type: Developer Portal\n    url: https://api.data.gov/\n  - type: NCES\n    url: https://nces.ed.gov/\n  - type: College Scorecard\n    url: https://collegescorecard.ed.gov/\n  - type: Federal Student Aid\n    url: https://studentaid.gov\n  - type: Data.gov ED Catalog\n    url: https://catalog.data.gov/dataset?organization=ed-gov\n  - type: News\n    url: https://www.ed.gov/news\n  - type: Contact\n    url: https://www.ed.gov/about/contact-us\n  - type: Privacy Policy\n    url: https://www.ed.gov/notices/privacy\n  - type: GitHub Organization\n    url: https://github.com/usedgov\n  - type: JSON-LD\n    url: json-ld/department-of-education-context.jsonld\n  - type: Vocabulary\n    url:\
  \ vocabulary/department-of-education-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/department-of-education-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/department-of-education/refs/heads/main/apis.yml
tags:
- College Scorecard
- Education
- Federal Government
- Higher Education
- IPEDS
- K-12
- NCES
- Open Data
- Postsecondary
url: https://raw.githubusercontent.com/api-evangelist/department-of-education/refs/heads/main/apis.yml
use_cases: []
---
