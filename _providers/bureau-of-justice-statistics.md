---
api_count: 3
apis:
- description: Provides access to national estimates derived from the FBI's National Incident-Based Reporting System (NIBRS). Includes violent and property incidents, offenses, victimization counts, percentages, and
  name: NIBRS National Estimates API
  slug: nibrs-national-estimates-api
- description: Provides access to victimization data from the National Crime Victimization Survey (NCVS), covering personal and household victimization data along with population estimates. No authentication require
  name: National Crime Victimization Survey (NCVS) API
  slug: ncvs-api
- description: A suite of interactive web-based data tools providing access to BJS statistical data on crime, corrections, courts, law enforcement, and victimization. Tools include LEARCAT (law enforcement agency cr
  name: BJS Data Analysis Tools
  slug: bjs-data-analysis-tools
common:
- title: ''
  type: Website
  url: https://bjs.ojp.gov/
- title: ''
  type: Portal
  url: https://bjs.ojp.gov/data
- title: ''
  type: Privacy Policy
  url: https://bjs.ojp.gov/legal/privacy-policy
- title: ''
  type: Data Collections
  url: https://bjs.ojp.gov/data-collections/search
- title: ''
  type: Data Portal
  url: https://catalog.data.gov/dataset?organization=ojp-gov
created: '2024-11-30'
description: The Bureau of Justice Statistics (BJS) publishes information on crime, criminal offenders, victims of crime, and the operation of justice systems.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Bureau of Justice Statistics
skills: []
slug: bureau-of-justice-statistics
solutions: []
source_yaml: "aid: bureau-of-justice-statistics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bureau-of-justice-statistics/refs/heads/main/apis.yml\nname: Bureau of Justice Statistics\ntags:\n  - Crime\n  - Federal Government\n  - Justice\n  - Statistics\n  - Victimization\n  - Recidivism\ntype: Index\nx-type: government\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-30'\nmodified: '2026-04-23'\nposition: Consumer\ndescription: >-\n  The Bureau of Justice Statistics (BJS) publishes information on crime,\n  criminal offenders, victims of crime, and the operation of justice systems.\napis:\n  - aid: bureau-of-justice-statistics:nibrs-national-estimates-api\n    name: NIBRS National Estimates API\n    tags:\n      - Federal Government\n      - Crime\n      - Statistics\n      - NIBRS\n    humanURL: https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs-national-estimates-api\n    baseURL: https://api.ojp.gov/bjsdataset/v1/\n\
  \    properties:\n      - url: https://bjs.ojp.gov/national-incident-based-reporting-system-nibrs-national-estimates-api\n        type: Documentation\n      - url: https://catalog.data.gov/dataset?organization=ojp-gov\n        type: DataAPI\n    description: >-\n      Provides access to national estimates derived from the FBI's National\n      Incident-Based Reporting System (NIBRS). Includes violent and property\n      incidents, offenses, victimization counts, percentages, and rates. No\n      authentication required.\n    features:\n      - Violent Incident Data\n      - Property Incident Data\n      - Offense Data\n      - Victimization Rates\n      - Filterable by Demographics\n      - JSON and CSV Formats\n      - Pagination Support\n    useCases:\n      - Criminal justice policy research\n      - Crime trend analysis\n      - Academic study of offense patterns\n      - Public safety planning\n  - aid: bureau-of-justice-statistics:ncvs-api\n    name: National Crime Victimization\
  \ Survey (NCVS) API\n    tags:\n      - Federal Government\n      - Victimization\n      - Statistics\n    humanURL: https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api\n    baseURL: https://api.ojp.gov/bjsdataset/v1/\n    properties:\n      - url: https://bjs.ojp.gov/national-crime-victimization-survey-ncvs-api\n        type: Documentation\n    description: >-\n      Provides access to victimization data from the National Crime\n      Victimization Survey (NCVS), covering personal and household victimization\n      data along with population estimates. No authentication required.\n    features:\n      - Personal Victimization Data\n      - Household Victimization Data\n      - Population Estimates\n      - JSON and CSV Formats\n      - Filterable by Year\n    useCases:\n      - Victimization research\n      - Policy development\n      - Trend analysis over time\n      - Comparative household and personal crime studies\n  - aid: bureau-of-justice-statistics:bjs-data-analysis-tools\n\
  \    name: BJS Data Analysis Tools\n    tags:\n      - Federal Government\n      - Statistics\n      - Dashboards\n    humanURL: https://bjs.ojp.gov/data/data-analysis-tools\n    properties:\n      - url: https://bjs.ojp.gov/data/data-analysis-tools\n        type: Documentation\n      - url: https://learcat.bjs.ojp.gov/\n        type: Tool\n      - url: https://bjs.ojp.gov/recidivism-patterns-explorer\n        type: Tool\n      - url: https://fccps.bjs.ojp.gov/\n        type: Tool\n      - url: https://csat.bjs.ojp.gov/\n        type: Tool\n      - url: https://bjs.ojp.gov/jeet\n        type: Tool\n      - url: https://ncvs.bjs.ojp.gov/Home\n        type: Tool\n    description: >-\n      A suite of interactive web-based data tools providing access to BJS\n      statistical data on crime, corrections, courts, law enforcement, and\n      victimization. Tools include LEARCAT (law enforcement agency crime data),\n      Recidivism Patterns Explorer, Federal Criminal Case Processing Statistics,\n\
  \      and NCVS Dashboard.\n    features:\n      - Law Enforcement Crime Data (LEARCAT)\n      - Recidivism Analysis\n      - Federal Criminal Case Processing\n      - Corrections Statistical Analysis\n      - Justice Expenditure Data\n      - Parole and Probation Dashboards\n    useCases:\n      - Criminal justice research\n      - Recidivism policy analysis\n      - Justice system spending analysis\n      - Interactive data exploration\ncommon:\n  - type: Website\n    url: https://bjs.ojp.gov/\n  - type: Portal\n    url: https://bjs.ojp.gov/data\n  - type: Privacy Policy\n    url: https://bjs.ojp.gov/legal/privacy-policy\n  - type: Data Collections\n    url: https://bjs.ojp.gov/data-collections/search\n  - type: Data Portal\n    url: https://catalog.data.gov/dataset?organization=ojp-gov\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bureau-of-justice-statistics/refs/heads/main/apis.yml
tags:
- Crime
- Federal Government
- Justice
- Statistics
- Victimization
- Recidivism
url: https://raw.githubusercontent.com/api-evangelist/bureau-of-justice-statistics/refs/heads/main/apis.yml
use_cases: []
---
