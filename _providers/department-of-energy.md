---
api_count: 6
apis:
- description: The U.S. Energy Information Administration (EIA) Open Data API v2 is a fully RESTful implementation of EIA's public energy statistics. Routes are arranged in a logical hierarchy across petroleum, natu
  name: EIA Open Data API V2
  slug: eia-api
- description: 'The DOE PAGES (Public Access Gateway for Energy and Science) REST API provides programmatic access to publications resulting from DOE-funded research, hosted by the Office of Scientific and Technical '
  name: OSTI DOE PAGES API
  slug: osti-pages-api
- description: The OSTI ELINK API is the Office of Scientific and Technical Information's submission and retrieval interface for DOE research records. It supports submission of metadata and full text by DOE-funded r
  name: OSTI ELINK API
  slug: osti-elink-api
- description: The National Renewable Energy Laboratory (NREL, transitioning to NLR) Developer Network publishes a portfolio of REST APIs covering solar resource and PV simulation, alternative fuels and stations, el
  name: NREL/NLR Developer Network APIs
  slug: nrel-developer-api
- description: The Buildings Performance Database (BPD) is a DOE repository of anonymized empirical performance records for commercial and residential buildings. The BPD API allows partners to query aggregate distri
  name: Buildings Performance Database API
  slug: buildings-performance-database
- description: The DOE participates in Data.gov by publishing thousands of dataset records under the doe-gov organization. These datasets cover energy consumption, generation, environmental impact, R&D, and more, an
  name: Department of Energy Open Data Catalog
  slug: open-data-catalog
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.energy.gov
- title: ''
  type: Open Energy Data
  url: https://www.energy.gov/data/open-energy-data
- title: ''
  type: Developer Portal
  url: https://api.data.gov/
- title: ''
  type: EIA
  url: https://www.eia.gov
- title: ''
  type: OSTI
  url: https://www.osti.gov
- title: ''
  type: NREL Developer
  url: https://developer.nlr.gov/
- title: ''
  type: Open Energy Data Initiative
  url: https://data.openei.org/
- title: ''
  type: Energy Data eXchange
  url: https://edx.netl.doe.gov/
- title: ''
  type: Data.gov DOE Catalog
  url: https://catalog.data.gov/organization/doe-gov
- title: ''
  type: News
  url: https://www.energy.gov/news
- title: ''
  type: Privacy Policy
  url: https://www.energy.gov/privacy
- title: ''
  type: GitHub Organization
  url: https://github.com/doe-doe
- title: ''
  type: JSON-LD
  url: json-ld/department-of-energy-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/department-of-energy-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/department-of-energy-capabilities.yml
created: '2024-12-03'
description: The U.S. Department of Energy (DOE) provides extensive open data and APIs across its national laboratories and program offices. Notable APIs are published by the Energy Information Administration (EIA) for energy statistics, the Office of Scientific and Technical Information (OSTI) for research and publications, the National Renewable Energy Laboratory (NREL, rebranding as NLR) developer network for renewables and alternative fuels, and the Buildings Performance Database (BPD).
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Department Of Energy Context
  property_count: 6
  slug: department-of-energy-context
layout: provider
modified: '2026-04-28'
name: Department of Energy
skills: []
slug: department-of-energy
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: department-of-energy\nname: Department of Energy\ndescription: >-\n  The U.S. Department of Energy (DOE) provides extensive open data and APIs\n  across its national laboratories and program offices. Notable APIs are\n  published by the Energy Information Administration (EIA) for energy\n  statistics, the Office of Scientific and Technical Information (OSTI) for\n  research and publications, the National Renewable Energy Laboratory (NREL,\n  rebranding as NLR) developer network for renewables and alternative fuels,\n  and the Buildings Performance Database (BPD).\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Buildings\n  - Electricity\n  - Energy\n  - Federal Government\n  - Open Data\n  - Renewables\n  - Research\n  - Solar\n  - Statistics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/department-of-energy/refs/heads/main/apis.yml\ncreated: '2024-12-03'\nmodified: '2026-04-28'\nspecificationVersion:\
  \ '0.19'\nxType: government\nposition: Producer\naccess: Public\napis:\n  - aid: department-of-energy:eia-api\n    name: EIA Open Data API V2\n    description: >-\n      The U.S. Energy Information Administration (EIA) Open Data API v2 is a\n      fully RESTful implementation of EIA's public energy statistics. Routes\n      are arranged in a logical hierarchy across petroleum, natural gas, coal,\n      electricity, nuclear, renewables, total energy, international, and\n      consumption series. Requests require a free api_key obtained from the\n      EIA Open Data portal and return up to 5,000 rows per request as JSON or\n      XML.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.eia.gov/opendata/\n    baseURL: https://api.eia.gov/v2\n    tags:\n      - Coal\n      - Electricity\n      - Energy Statistics\n      - Natural Gas\n      - Petroleum\n      - Renewables\n    properties:\n      - type: Documentation\n        url:\
  \ https://www.eia.gov/opendata/documentation.php\n      - type: Developer\n        url: https://www.eia.gov/developer/\n      - type: API Browser\n        url: https://www.eia.gov/opendata/browser/\n      - type: Sign Up\n        url: https://www.eia.gov/opendata/register.php\n      - type: Reference PDF\n        url: https://www.eia.gov/opendata/documentation/APIv2.1.0.pdf\n    contact:\n      - FN: EIA Customer Support\n        email: InfoCtr@eia.gov\n        url: https://www.eia.gov/about/contact/\n  - aid: department-of-energy:osti-pages-api\n    name: OSTI DOE PAGES API\n    description: >-\n      The DOE PAGES (Public Access Gateway for Energy and Science) REST API\n      provides programmatic access to publications resulting from DOE-funded\n      research, hosted by the Office of Scientific and Technical Information\n      (OSTI). The API supports search and retrieval of bibliographic records\n      and full-text links for journal articles, accepted manuscripts, and\n      technical\
  \ reports.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.osti.gov/pages/api/v1/docs\n    baseURL: https://www.osti.gov/pages/api/v1\n    tags:\n      - Bibliographic\n      - OSTI\n      - Publications\n      - Research\n    properties:\n      - type: Documentation\n        url: https://www.osti.gov/pages/api/v1/docs\n      - type: Reference\n        url: https://www.osti.gov/api\n    contact:\n      - FN: OSTI\n        email: osti@osti.gov\n        url: https://www.osti.gov/contact\n  - aid: department-of-energy:osti-elink-api\n    name: OSTI ELINK API\n    description: >-\n      The OSTI ELINK API is the Office of Scientific and Technical\n      Information's submission and retrieval interface for DOE research\n      records. It supports submission of metadata and full text by DOE-funded\n      research organizations, and it powers public retrieval interfaces for\n      OSTI.GOV.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://www.osti.gov/elink/\n    baseURL: https://www.osti.gov/elink\n    tags:\n      - ELINK\n      - Metadata\n      - OSTI\n      - Submission\n    properties:\n      - type: Documentation\n        url: https://www.osti.gov/elink/\n      - type: API\n        url: https://www.osti.gov/api\n    contact:\n      - FN: OSTI ELINK\n        email: elink@osti.gov\n        url: https://www.osti.gov/contact\n  - aid: department-of-energy:nrel-developer-api\n    name: NREL/NLR Developer Network APIs\n    description: >-\n      The National Renewable Energy Laboratory (NREL, transitioning to NLR)\n      Developer Network publishes a portfolio of REST APIs covering solar\n      resource and PV simulation, alternative fuels and stations, electricity\n      utilities and rates, transportation, geothermal, and energy economics.\n      All APIs share a common API key model issued through api.data.gov.\n      Existing developer.nrel.gov consumers must migrate to developer.nlr.gov\n  \
  \    by April 30, 2026.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.nlr.gov/\n    baseURL: https://developer.nlr.gov/api\n    tags:\n      - Alternative Fuels\n      - Buildings\n      - Electricity\n      - Geothermal\n      - NREL\n      - Renewables\n      - Solar\n      - Transportation\n    properties:\n      - type: Documentation\n        url: https://developer.nlr.gov/docs/\n      - type: Solar APIs\n        url: https://developer.nlr.gov/docs/solar/\n      - type: Electricity APIs\n        url: https://developer.nlr.gov/docs/electricity/\n      - type: Sign Up\n        url: https://api.data.gov/signup/\n      - type: Data Catalog\n        url: https://data.nlr.gov/\n    contact:\n      - FN: NREL Developer Network\n        url: https://developer.nlr.gov/contact-us\n  - aid: department-of-energy:buildings-performance-database\n    name: Buildings Performance Database API\n    description: >-\n      The Buildings\
  \ Performance Database (BPD) is a DOE repository of\n      anonymized empirical performance records for commercial and residential\n      buildings. The BPD API allows partners to query aggregate distributions\n      and compare cohorts of buildings across attributes such as building\n      type, vintage, climate zone, and energy use intensity.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.energy.gov/eere/buildings/application-programming-interface\n    baseURL: https://api.example.com\n    tags:\n      - BPD\n      - Benchmarking\n      - Buildings\n      - Energy Efficiency\n    properties:\n      - type: Documentation\n        url: https://www.energy.gov/eere/buildings/application-programming-interface\n    contact:\n      - FN: DOE Building Technologies Office\n        url: https://www.energy.gov/eere/buildings\n  - aid: department-of-energy:open-data-catalog\n    name: Department of Energy Open Data Catalog\n    description:\
  \ >-\n      The DOE participates in Data.gov by publishing thousands of dataset\n      records under the doe-gov organization. These datasets cover energy\n      consumption, generation, environmental impact, R&D, and more, and are\n      accessible through Data.gov's CKAN-compatible API.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://catalog.data.gov/organization/doe-gov\n    baseURL: https://catalog.data.gov/api/3\n    tags:\n      - CKAN\n      - Datasets\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://catalog.data.gov/organization/doe-gov\n      - type: Open Energy Data\n        url: https://www.energy.gov/data/open-energy-data\n      - type: CKAN Reference\n        url: https://docs.ckan.org/en/2.8/api/\n    contact:\n      - FN: DOE Open Data\n        url: https://www.energy.gov/data/open-energy-data\ncommon:\n  - type: Website\n    url: https://www.energy.gov\n  - type: Open Energy\
  \ Data\n    url: https://www.energy.gov/data/open-energy-data\n  - type: Developer Portal\n    url: https://api.data.gov/\n  - type: EIA\n    url: https://www.eia.gov\n  - type: OSTI\n    url: https://www.osti.gov\n  - type: NREL Developer\n    url: https://developer.nlr.gov/\n  - type: Open Energy Data Initiative\n    url: https://data.openei.org/\n  - type: Energy Data eXchange\n    url: https://edx.netl.doe.gov/\n  - type: Data.gov DOE Catalog\n    url: https://catalog.data.gov/organization/doe-gov\n  - type: News\n    url: https://www.energy.gov/news\n  - type: Privacy Policy\n    url: https://www.energy.gov/privacy\n  - type: GitHub Organization\n    url: https://github.com/doe-doe\n  - type: JSON-LD\n    url: json-ld/department-of-energy-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/department-of-energy-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/department-of-energy-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/department-of-energy/refs/heads/main/apis.yml
tags:
- Buildings
- Electricity
- Energy
- Federal Government
- Open Data
- Renewables
- Research
- Solar
- Statistics
url: https://raw.githubusercontent.com/api-evangelist/department-of-energy/refs/heads/main/apis.yml
use_cases: []
---
