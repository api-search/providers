---
api_count: 5
apis:
- description: The DOL Open Data API v4 is the Department of Labor's modernized REST API replacing the retired developer.dol.gov APIv1 and APIv2. It is served from the DOL Data Portal at dataportal.dol.gov and expos
  name: DOL Open Data API V4
  slug: dol-api-v4
- description: The Bureau of Labor Statistics Public Data API v2 provides programmatic access to historical BLS time series data in JSON or Excel. Version 2 requires registration to obtain a registrationkey query pa
  name: BLS Public Data API V2
  slug: bls-public-data-api
- description: The DOL Enforcement Data site at data.dol.gov publishes the Department's enforcement records from agencies including the Wage and Hour Division, OSHA, MSHA, OFCCP, and the Employee Benefits Security A
  name: DOL Enforcement Data
  slug: dol-enforcement-data
- description: The DOL API Sampler is an interactive playground for exploring the DOL Open Data API v4 endpoints. It serves as a quick way to issue sample requests, browse parameters, and inspect responses against t
  name: DOL API Sampler
  slug: dol-api-sampler
- description: The Department of Labor Open Data Catalog publishes datasets across labor statistics, enforcement, employment training, and worker protection programs. Datasets are surfaced on Data.gov under the dol-
  name: DOL Open Data Catalog
  slug: dol-open-data-catalog
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.dol.gov
- title: ''
  type: Open Data Portal
  url: https://dataportal.dol.gov/
- title: ''
  type: Developer Community
  url: https://usdepartmentoflabor.github.io/DOLAPI/
- title: ''
  type: Bureau of Labor Statistics
  url: https://www.bls.gov
- title: ''
  type: Enforcement Data
  url: https://data.dol.gov/
- title: ''
  type: API Sampler
  url: https://devtools.dol.gov/apisampler
- title: ''
  type: OSHA
  url: https://www.osha.gov
- title: ''
  type: MSHA
  url: https://www.msha.gov
- title: ''
  type: ETA
  url: https://www.dol.gov/agencies/eta
- title: ''
  type: Wage and Hour Division
  url: https://www.dol.gov/agencies/whd
- title: ''
  type: EBSA
  url: https://www.dol.gov/agencies/ebsa
- title: ''
  type: OFCCP
  url: https://www.dol.gov/agencies/ofccp
- title: ''
  type: Data.gov DOL Catalog
  url: https://catalog.data.gov/organization/dol-gov
- title: ''
  type: News
  url: https://www.dol.gov/newsroom
- title: ''
  type: Privacy Policy
  url: https://www.dol.gov/general/privacynotice
- title: ''
  type: GitHub Organization
  url: https://github.com/USDepartmentofLabor
- title: ''
  type: JSON-LD
  url: json-ld/department-of-labor-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/department-of-labor-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/department-of-labor-capabilities.yml
created: '2024-12-03'
description: The U.S. Department of Labor (DOL) is the federal department that fosters, promotes, and develops the welfare of wage earners, job seekers, and retirees, improves working conditions, advances opportunities for profitable employment, and assures work-related benefits and rights. DOL exposes a portfolio of public APIs and data feeds including the modernized DOL APIv4 served from the DOL Open Data Portal, the Bureau of Labor Statistics Public Data API, the DOL Enforcement Data site, and Data.gov.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Department Of Labor Context
  property_count: 5
  slug: department-of-labor-context
layout: provider
modified: '2026-04-28'
name: Department of Labor
skills: []
slug: department-of-labor
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: department-of-labor\nname: Department of Labor\ndescription: >-\n  The U.S. Department of Labor (DOL) is the federal department that fosters,\n  promotes, and develops the welfare of wage earners, job seekers, and\n  retirees, improves working conditions, advances opportunities for\n  profitable employment, and assures work-related benefits and rights. DOL\n  exposes a portfolio of public APIs and data feeds including the modernized\n  DOL APIv4 served from the DOL Open Data Portal, the Bureau of Labor\n  Statistics Public Data API, the DOL Enforcement Data site, and Data.gov.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - BLS\n  - Employment\n  - Enforcement\n  - Federal Government\n  - Labor\n  - Open Data\n  - Statistics\n  - Wages\n  - Workforce\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/department-of-labor/refs/heads/main/apis.yml\ncreated: '2024-12-03'\nmodified: '2026-04-28'\nspecificationVersion:\
  \ '0.19'\nxType: government\nposition: Producer\naccess: Public\napis:\n  - aid: department-of-labor:dol-api-v4\n    name: DOL Open Data API V4\n    description: >-\n      The DOL Open Data API v4 is the Department of Labor's modernized REST\n      API replacing the retired developer.dol.gov APIv1 and APIv2. It is\n      served from the DOL Data Portal at dataportal.dol.gov and exposes more\n      than 200 datasets covering wage and hour, occupational safety and\n      health, employment and training, retirement security, and other DOL\n      programs. The Datasets endpoint is publicly accessible without an API\n      key; data endpoints require an API key obtained through registration on\n      the Data Portal.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://dataportal.dol.gov/\n    baseURL: https://apiprod.dol.gov/v4\n    tags:\n      - Datasets\n      - DOL Data Portal\n      - Open Data\n      - REST\n    properties:\n \
  \     - type: Documentation\n        url: https://dataportal.dol.gov/\n      - type: User Guide\n        url: https://www.dataportal.dol.gov/pdf/dol-api-user-guide.pdf\n      - type: Datasets Catalog\n        url: https://dataportal.dol.gov/datasets\n      - type: Datasets Endpoint\n        url: https://apiprod.dol.gov/v4/datasets\n      - type: Sign Up\n        url: https://dataportal.dol.gov/registration\n    contact:\n      - FN: DOL Data Portal\n        url: https://dataportal.dol.gov/\n  - aid: department-of-labor:bls-public-data-api\n    name: BLS Public Data API V2\n    description: >-\n      The Bureau of Labor Statistics Public Data API v2 provides programmatic\n      access to historical BLS time series data in JSON or Excel. Version 2\n      requires registration to obtain a registrationkey query parameter and\n      raises limits to up to 20 years of data per request, 50 series per\n      request, and 500 queries per day. Series include CPI, PPI, employment,\n      wages, productivity,\
  \ and more.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.bls.gov/developers/\n    baseURL: https://api.bls.gov/publicAPI/v2\n    tags:\n      - BLS\n      - CPI\n      - Employment\n      - Statistics\n      - Time Series\n      - Wages\n    properties:\n      - type: Documentation\n        url: https://www.bls.gov/developers/home.htm\n      - type: API Signatures\n        url: https://www.bls.gov/developers/api_signature_v2.htm\n      - type: Features\n        url: https://www.bls.gov/bls/api_features.htm\n      - type: FAQ\n        url: https://www.bls.gov/developers/api_faqs.htm\n      - type: Python Sample\n        url: https://www.bls.gov/developers/api_python.htm\n      - type: Sign Up\n        url: https://data.bls.gov/registrationEngine/\n    contact:\n      - FN: BLS Customer Support\n        url: https://www.bls.gov/bls/contact.htm\n  - aid: department-of-labor:dol-enforcement-data\n    name: DOL Enforcement\
  \ Data\n    description: >-\n      The DOL Enforcement Data site at data.dol.gov publishes the\n      Department's enforcement records from agencies including the Wage and\n      Hour Division, OSHA, MSHA, OFCCP, and the Employee Benefits Security\n      Administration. Records are available as bulk downloads and through\n      datasets surfaced on Data.gov.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://data.dol.gov/\n    baseURL: https://data.dol.gov\n    tags:\n      - Enforcement\n      - MSHA\n      - OFCCP\n      - OSHA\n      - Wage and Hour\n    properties:\n      - type: Documentation\n        url: https://data.dol.gov/\n      - type: Datasets\n        url: https://catalog.data.gov/organization/dol-gov\n    contact:\n      - FN: DOL Open Data\n        url: https://www.dol.gov/agencies/oasam\n  - aid: department-of-labor:dol-api-sampler\n    name: DOL API Sampler\n    description: >-\n      The DOL API Sampler is an\
  \ interactive playground for exploring the DOL\n      Open Data API v4 endpoints. It serves as a quick way to issue sample\n      requests, browse parameters, and inspect responses against the live\n      API.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://devtools.dol.gov/apisampler\n    baseURL: https://devtools.dol.gov/apisampler\n    tags:\n      - DevTools\n      - Playground\n      - Sampler\n    properties:\n      - type: Documentation\n        url: https://devtools.dol.gov/apisampler\n    contact:\n      - FN: DOL Developer Community\n        url: https://usdepartmentoflabor.github.io/DOLAPI/\n  - aid: department-of-labor:dol-open-data-catalog\n    name: DOL Open Data Catalog\n    description: >-\n      The Department of Labor Open Data Catalog publishes datasets across\n      labor statistics, enforcement, employment training, and worker\n      protection programs. Datasets are surfaced on Data.gov under the\n    \
  \  dol-gov organization and accessible via the Data.gov CKAN-compatible\n      API.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://catalog.data.gov/organization/dol-gov\n    baseURL: https://catalog.data.gov/api/3\n    tags:\n      - CKAN\n      - Datasets\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://catalog.data.gov/organization/dol-gov\n      - type: CKAN Reference\n        url: https://docs.ckan.org/en/2.8/api/\n    contact:\n      - FN: DOL Open Data\n        url: https://catalog.data.gov/organization/dol-gov\ncommon:\n  - type: Website\n    url: https://www.dol.gov\n  - type: Open Data Portal\n    url: https://dataportal.dol.gov/\n  - type: Developer Community\n    url: https://usdepartmentoflabor.github.io/DOLAPI/\n  - type: Bureau of Labor Statistics\n    url: https://www.bls.gov\n  - type: Enforcement Data\n    url: https://data.dol.gov/\n  - type: API Sampler\n    url: https://devtools.dol.gov/apisampler\n\
  \  - type: OSHA\n    url: https://www.osha.gov\n  - type: MSHA\n    url: https://www.msha.gov\n  - type: ETA\n    url: https://www.dol.gov/agencies/eta\n  - type: Wage and Hour Division\n    url: https://www.dol.gov/agencies/whd\n  - type: EBSA\n    url: https://www.dol.gov/agencies/ebsa\n  - type: OFCCP\n    url: https://www.dol.gov/agencies/ofccp\n  - type: Data.gov DOL Catalog\n    url: https://catalog.data.gov/organization/dol-gov\n  - type: News\n    url: https://www.dol.gov/newsroom\n  - type: Privacy Policy\n    url: https://www.dol.gov/general/privacynotice\n  - type: GitHub Organization\n    url: https://github.com/USDepartmentofLabor\n  - type: JSON-LD\n    url: json-ld/department-of-labor-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/department-of-labor-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/department-of-labor-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/department-of-labor/refs/heads/main/apis.yml
tags:
- BLS
- Employment
- Enforcement
- Federal Government
- Labor
- Open Data
- Statistics
- Wages
- Workforce
url: https://raw.githubusercontent.com/api-evangelist/department-of-labor/refs/heads/main/apis.yml
use_cases: []
---
