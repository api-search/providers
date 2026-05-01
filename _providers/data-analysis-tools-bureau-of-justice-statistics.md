---
api_count: 2
api_specs:
- filename: bjs-ncvs-api-openapi.yml
  format: yaml
  label: BJS NCVS API
  slug: ncvs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/data-analysis-tools-bureau-of-justice-statistics/refs/heads/main/openapi/bjs-ncvs-api-openapi.yml
- filename: bjs-nibrs-api-openapi.yml
  format: yaml
  label: BJS NIBRS National Estimates API
  slug: nibrs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/data-analysis-tools-bureau-of-justice-statistics/refs/heads/main/openapi/bjs-nibrs-api-openapi.yml
apis:
- description: The National Crime Victimization Survey (NCVS) API exposes selected NCVS datasets via the Socrata Open Data API. Datasets are addressed by four-character resource codes and may be queried with SoQL cl
  name: BJS NCVS API
  slug: ncvs-api
- description: The NIBRS National Estimates API publishes selected National Incident-Based Reporting System national-estimates datasets via the Socrata Open Data API, addressable via four-character resource codes an
  name: BJS NIBRS National Estimates API
  slug: nibrs-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://bjs.ojp.gov/
- title: ''
  type: Data Analysis Tools
  url: https://bjs.ojp.gov/data/data-analysis-tools
- title: ''
  type: Data Collections
  url: https://bjs.ojp.gov/data-collections
- title: ''
  type: Publications
  url: https://bjs.ojp.gov/library
- title: ''
  type: DOJ Developer
  url: https://www.justice.gov/developer
- title: ''
  type: JSON-LD
  url: json-ld/bjs-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/bjs-vocabulary.yml
created: '2024-11-30'
description: The Bureau of Justice Statistics (BJS) is the agency within the U.S. Department of Justice responsible for collecting, analysing, and disseminating crime, criminal-justice, expenditure, and victimisation data. BJS exposes selected datasets through Socrata Open Data APIs and offers interactive data analysis tools such as the Justice Expenditure and Employment Tool (JEET) and the National Crime Victimization Survey (NCVS) Quick Tables.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Bjs Context
  property_count: 5
  slug: bjs-context
layout: provider
modified: '2026-04-28'
name: Bureau of Justice Statistics Data Analysis Tools
rules:
- name: Bureau of Justice Statistics Data Analysis Tools API Rules
  rule_count: 5
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 3
  slug: bjs-ncvs-api-rules
skills: []
slug: data-analysis-tools-bureau-of-justice-statistics
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: data-analysis-tools-bureau-of-justice-statistics\nname: Bureau of Justice Statistics Data Analysis Tools\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/data-analysis-tools-bureau-of-justice-statistics/refs/heads/main/apis.yml\ntype: Index\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Crime Statistics\n  - Federal Government\n  - NCVS\n  - NIBRS\n  - Open Data\n  - SODA\n  - Statistics\n  - Victimization\ncreated: '2024-11-30'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: government\ndescription: >-\n  The Bureau of Justice Statistics (BJS) is the agency within the U.S.\n  Department of Justice responsible for collecting, analysing, and\n  disseminating crime, criminal-justice, expenditure, and victimisation data.\n  BJS exposes selected datasets through Socrata Open Data APIs and offers\n  interactive data analysis tools such as the Justice Expenditure\
  \ and\n  Employment Tool (JEET) and the National Crime Victimization Survey (NCVS)\n  Quick Tables.\napis:\n  - aid: data-analysis-tools-bureau-of-justice-statistics:ncvs-api\n    name: BJS NCVS API\n    description: >-\n      The National Crime Victimization Survey (NCVS) API exposes selected\n      NCVS datasets via the Socrata Open Data API. Datasets are addressed by\n      four-character resource codes and may be queried with SoQL clauses such\n      as $select, $where, $group, $order, and $limit, returning JSON or CSV.\n    humanURL: https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api\n    baseURL: https://api.ojp.gov/bjsdataset/v1\n    tags:\n      - Crime Statistics\n      - NCVS\n      - SODA\n      - Victimization\n    properties:\n      - type: Documentation\n        url: https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api\n      - type: Featured\n        url: https://bjs.ojp.gov/featured/national-crime-victimization-survey-ncvs-application-programming-interface-api\n\
  \      - type: OpenAPI\n        url: openapi/bjs-ncvs-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/bjs-dataset-row.json\n      - type: Rules\n        url: rules/bjs-ncvs-api-rules.yml\n      - type: Capabilities\n        url: capabilities/bjs-data-analysis-tools-capabilities.yml\n  - aid: data-analysis-tools-bureau-of-justice-statistics:nibrs-api\n    name: BJS NIBRS National Estimates API\n    description: >-\n      The NIBRS National Estimates API publishes selected National\n      Incident-Based Reporting System national-estimates datasets via the\n      Socrata Open Data API, addressable via four-character resource codes\n      and queryable with SoQL.\n    humanURL: https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs-national-estimates-api\n    baseURL: https://api.ojp.gov/bjsdataset/v1\n    tags:\n      - Crime Statistics\n      - NIBRS\n      - SODA\n    properties:\n      - type: Documentation\n        url: https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs-national-estimates-api\n\
  \      - type: OpenAPI\n        url: openapi/bjs-nibrs-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/bjs-dataset-row.json\ncommon:\n  - type: Website\n    url: https://bjs.ojp.gov/\n  - type: Data Analysis Tools\n    url: https://bjs.ojp.gov/data/data-analysis-tools\n  - type: Data Collections\n    url: https://bjs.ojp.gov/data-collections\n  - type: Publications\n    url: https://bjs.ojp.gov/library\n  - type: DOJ Developer\n    url: https://www.justice.gov/developer\n  - type: JSON-LD\n    url: json-ld/bjs-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/bjs-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/data-analysis-tools-bureau-of-justice-statistics/refs/heads/main/apis.yml
tags:
- Crime Statistics
- Federal Government
- NCVS
- NIBRS
- Open Data
- SODA
- Statistics
- Victimization
url: https://raw.githubusercontent.com/api-evangelist/data-analysis-tools-bureau-of-justice-statistics/refs/heads/main/apis.yml
use_cases: []
---
