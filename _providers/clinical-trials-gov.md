---
api_count: 4
apis:
- description: 'The ClinicalTrials.gov Data API v2 is the modern public REST interface to the NIH clinical-studies registry. It exposes study records, study metadata, search areas, study fields, version history, and '
  name: ClinicalTrials.gov Data API v2
  slug: data-api-v2
- description: 'The Classic API is the legacy ClinicalTrials.gov interface that preceded the Data API v2 and exposes full-study, brief-study, and field-values endpoints with XML, JSON, and CSV responses. It is being '
  name: ClinicalTrials.gov Classic API
  slug: classic-api
- description: ClinicalTrials.gov provides bulk CSV and JSON downloads of the full study registry through the data-api download endpoints. These artifacts support large-scale analytics, archival, and offline mirrors
  name: ClinicalTrials.gov Bulk Downloads
  slug: bulk-downloads
- description: AACT (Aggregate Analysis of ClinicalTrials.gov) is a publicly available relational database of all ClinicalTrials.gov study content maintained by the Clinical Trials Transformation Initiative (CTTI) a
  name: AACT Database
  slug: aact
capabilities:
- description: ''
  name: Clinical Trials Gov
  slug: clinical-trials-gov
common:
- title: ''
  type: Website
  url: https://clinicaltrials.gov/
- title: ''
  type: About
  url: https://clinicaltrials.gov/about-site
- title: ''
  type: Documentation
  url: https://clinicaltrials.gov/data-api/api
- title: ''
  type: Portal
  url: https://clinicaltrials.gov/data-api
- title: ''
  type: Glossary
  url: https://clinicaltrials.gov/study-basics/glossary
- title: ''
  type: News
  url: https://clinicaltrials.gov/about-site/announcements
- title: ''
  type: Help
  url: https://clinicaltrials.gov/help
- title: ''
  type: Privacy Policy
  url: https://www.nlm.nih.gov/privacy.html
- title: ''
  type: Terms of Service
  url: https://clinicaltrials.gov/about-site/terms-conditions
- title: ''
  type: GitHub
  url: https://github.com/clinicaltrialsgov
- title: ''
  type: JSON-LD
  url: json-ld/clinical-trials-gov-context.jsonld
- title: ''
  type: Spectral
  url: rules/clinical-trials-gov-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/clinical-trials-gov.yaml
created: '2024-01-01'
description: ClinicalTrials.gov is the U.S. National Institutes of Health (NIH) registry and results database of publicly and privately supported clinical studies of human participants conducted around the world. Operated by the National Library of Medicine (NLM), it provides a modern REST API (data-api v2) that returns study records, study metadata, search areas, and field definitions in JSON. The predecessor classic API remains available for legacy consumers but is being phased out in favor of the v2 API. Data is in the public domain and freely accessible without authentication.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Clinical Trials Gov Context
  property_count: 7
  slug: clinical-trials-gov-context
layout: provider
modified: '2026-04-23'
name: ClinicalTrials.gov
rules:
- name: ClinicalTrials.gov API Rules
  rule_count: 9
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 5
  slug: clinical-trials-gov-rules
skills: []
slug: clinical-trials-gov
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: clinical-trials-gov\nname: ClinicalTrials.gov\ndescription: >-\n  ClinicalTrials.gov is the U.S. National Institutes of Health (NIH)\n  registry and results database of publicly and privately supported\n  clinical studies of human participants conducted around the world.\n  Operated by the National Library of Medicine (NLM), it provides a\n  modern REST API (data-api v2) that returns study records, study\n  metadata, search areas, and field definitions in JSON. The\n  predecessor classic API remains available for legacy consumers but\n  is being phased out in favor of the v2 API. Data is in the public\n  domain and freely accessible without authentication.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/clinical-trials-gov/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\nx-type: government\ntags:\n  - Clinical Trials\n\
  \  - Government\n  - Health\n  - NIH\n  - Open Data\n  - Public Health\n  - Research\napis:\n  - aid: clinical-trials-gov:data-api-v2\n    name: ClinicalTrials.gov Data API v2\n    tags:\n      - Clinical Trials\n      - REST\n      - Search\n      - Studies\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://clinicaltrials.gov/api/v2\n    humanURL: https://clinicaltrials.gov/data-api/api\n    properties:\n      - url: https://clinicaltrials.gov/data-api/api\n        type: Documentation\n      - url: https://clinicaltrials.gov/data-api/about-api\n        type: About\n      - url: openapi/clinical-trials-gov-data-api-v2-openapi.yml\n        type: OpenAPI\n    description: >-\n      The ClinicalTrials.gov Data API v2 is the modern public REST\n      interface to the NIH clinical-studies registry. It exposes\n      study records, study metadata, search areas, study fields,\n      version history, and statistics endpoints. Responses\
  \ are JSON\n      by default and the API is open and unauthenticated. The base\n      URL is https://clinicaltrials.gov/api/v2 and operations include\n      /studies, /studies/{nctId}, /studies/metadata,\n      /studies/search-areas, /studies/enums, /version, and /stats.\n  - aid: clinical-trials-gov:classic-api\n    name: ClinicalTrials.gov Classic API\n    tags:\n      - Clinical Trials\n      - Legacy\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://clinicaltrials.gov/api\n    humanURL: https://clinicaltrials.gov/data-api/api\n    properties:\n      - url: https://clinicaltrials.gov/data-api/api\n        type: Documentation\n    description: >-\n      The Classic API is the legacy ClinicalTrials.gov interface that\n      preceded the Data API v2 and exposes full-study, brief-study,\n      and field-values endpoints with XML, JSON, and CSV responses.\n      It is being deprecated in favor of the v2 REST API and\
  \ remains\n      online for backward compatibility while consumers migrate.\n  - aid: clinical-trials-gov:bulk-downloads\n    name: ClinicalTrials.gov Bulk Downloads\n    tags:\n      - Bulk\n      - Datasets\n      - Open Data\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://clinicaltrials.gov/data-api/about-api/csv-download\n    properties:\n      - url: https://clinicaltrials.gov/data-api/about-api/csv-download\n        type: Documentation\n    description: >-\n      ClinicalTrials.gov provides bulk CSV and JSON downloads of the\n      full study registry through the data-api download endpoints.\n      These artifacts support large-scale analytics, archival, and\n      offline mirrors of the registry without making per-record\n      API calls.\n  - aid: clinical-trials-gov:aact\n    name: AACT Database\n    tags:\n      - Analytics\n      - Database\n      - Postgres\n      - Research\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://aact.ctti-clinicaltrials.org/\n    properties:\n      - url: https://aact.ctti-clinicaltrials.org/\n        type: Documentation\n      - url: https://aact.ctti-clinicaltrials.org/data_dictionary\n        type: Data Dictionary\n    description: >-\n      AACT (Aggregate Analysis of ClinicalTrials.gov) is a publicly\n      available relational database of all ClinicalTrials.gov study\n      content maintained by the Clinical Trials Transformation\n      Initiative (CTTI) at Duke University. It is updated daily and\n      is widely used by researchers as a SQL-friendly mirror of the\n      registry.\ncommon:\n  - type: Website\n    url: https://clinicaltrials.gov/\n  - type: About\n    url: https://clinicaltrials.gov/about-site\n  - type: Documentation\n    url: https://clinicaltrials.gov/data-api/api\n  - type: Portal\n    url: https://clinicaltrials.gov/data-api\n  - type: Glossary\n    url: https://clinicaltrials.gov/study-basics/glossary\n  - type: News\n    url:\
  \ https://clinicaltrials.gov/about-site/announcements\n  - type: Help\n    url: https://clinicaltrials.gov/help\n  - type: Privacy Policy\n    url: https://www.nlm.nih.gov/privacy.html\n  - type: Terms of Service\n    url: https://clinicaltrials.gov/about-site/terms-conditions\n  - type: GitHub\n    url: https://github.com/clinicaltrialsgov\n  - type: JSON-LD\n    url: json-ld/clinical-trials-gov-context.jsonld\n  - type: Spectral\n    url: rules/clinical-trials-gov-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/clinical-trials-gov.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/clinical-trials-gov/refs/heads/main/apis.yml
tags:
- Clinical Trials
- Government
- Health
- NIH
- Open Data
- Public Health
- Research
url: https://raw.githubusercontent.com/api-evangelist/clinical-trials-gov/refs/heads/main/apis.yml
use_cases: []
---
