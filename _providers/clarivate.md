---
api_count: 4
apis:
- description: Web of Science APIs deliver publication and citation data drawn from the curated Web of Science Core Collection, supporting bibliometric analysis, research evaluation, and institutional assessment wor
  name: Web of Science APIs
  slug: web-of-science-api
- description: The Derwent Innovation API provides programmatic access to Derwent World Patents Index data, including normalized patent records, families, and citations used for IP intelligence and competitive analy
  name: Derwent Innovation API
  slug: derwent-innovation-api
- description: Cortellis APIs expose the Clarivate life sciences intelligence platform, covering drug pipelines, clinical trials, regulatory intelligence, deals, and competitive intelligence for biopharma and medica
  name: Cortellis APIs
  slug: cortellis-api
- description: The InCites API provides programmatic access to the Clarivate research benchmarking platform, enabling institutional research performance analytics built on Web of Science data.
  name: InCites Benchmarking and Analytics API
  slug: incites-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://clarivate.com/
- title: ''
  type: Portal
  url: https://developer.clarivate.com/
- title: ''
  type: API Catalog
  url: https://developer.clarivate.com/apis
- title: ''
  type: Support
  url: https://support.clarivate.com/
- title: ''
  type: Privacy Policy
  url: https://clarivate.com/privacy-center/
- title: ''
  type: Terms of Service
  url: https://clarivate.com/legal-center/
- title: ''
  type: JSON-LD
  url: json-ld/clarivate-context.jsonld
- title: ''
  type: Spectral
  url: rules/clarivate-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/clarivate-capabilities.yml
created: '2024-12-16'
description: 'Clarivate is a global information services company providing data, insights, and analytics across academia, government, life sciences, healthcare, and intellectual property. Clarivate exposes a unified developer portal at developer.clarivate.com that catalogs APIs across its product families: Web of Science for publication and citation data, Derwent for patent data, Cortellis for life sciences and drug pipeline intelligence, and supporting tools such as InCites and ScholarOne. APIs are subscription-based and authenticated with per-API keys issued through the developer portal after subscription approval.'
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 14
  name: Clarivate Context
  property_count: 0
  slug: clarivate-context
layout: provider
modified: '2026-04-23'
name: Clarivate
rules:
- name: Clarivate API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 2
  slug: clarivate-rules
skills: []
slug: clarivate
solutions: []
source_filename: apis.yml
source_yaml: "aid: clarivate\nname: Clarivate\nurl: https://raw.githubusercontent.com/api-evangelist/clarivate/refs/heads/main/apis.yml\ncreated: '2024-12-16'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Citations\n  - Data\n  - Drug Pipeline\n  - Insights\n  - Intellectual Property\n  - Life Sciences\n  - Patents\n  - Publications\n  - Research\ndescription: >-\n  Clarivate is a global information services company providing data,\n  insights, and analytics across academia, government, life sciences,\n  healthcare, and intellectual property. Clarivate exposes a unified\n  developer portal at developer.clarivate.com that catalogs APIs across\n  its product families: Web of Science for publication and citation\n  data, Derwent for patent data, Cortellis for life sciences and drug\n  pipeline intelligence, and supporting tools\
  \ such as InCites and\n  ScholarOne. APIs are subscription-based and authenticated with\n  per-API keys issued through the developer portal after subscription\n  approval.\napis:\n  - aid: clarivate:web-of-science-api\n    name: Web of Science APIs\n    tags:\n      - Bibliometrics\n      - Citations\n      - Publications\n      - Research Analytics\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.clarivate.com/apis/wos\n    properties:\n      - url: https://developer.clarivate.com/apis/wos\n        type: Documentation\n    description: >-\n      Web of Science APIs deliver publication and citation data drawn\n      from the curated Web of Science Core Collection, supporting\n      bibliometric analysis, research evaluation, and institutional\n      assessment workflows.\n  - aid: clarivate:derwent-innovation-api\n    name: Derwent Innovation API\n    tags:\n      - Derwent\n      - Intellectual Property\n      - Patents\n\
  \    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.clarivate.com/apis/derwent\n    properties:\n      - url: https://developer.clarivate.com/apis/derwent\n        type: Documentation\n    description: >-\n      The Derwent Innovation API provides programmatic access to\n      Derwent World Patents Index data, including normalized patent\n      records, families, and citations used for IP intelligence and\n      competitive analysis.\n  - aid: clarivate:cortellis-api\n    name: Cortellis APIs\n    tags:\n      - Clinical Trials\n      - Cortellis\n      - Drug Pipeline\n      - Life Sciences\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cortellis.com/\n    properties:\n      - url: https://developer.clarivate.com/apis/cortellis\n        type: Documentation\n      - url: https://www.cortellis.com/\n        type: Portal\n    description: >-\n      Cortellis\
  \ APIs expose the Clarivate life sciences intelligence\n      platform, covering drug pipelines, clinical trials, regulatory\n      intelligence, deals, and competitive intelligence for biopharma\n      and medical-device companies.\n  - aid: clarivate:incites-api\n    name: InCites Benchmarking and Analytics API\n    tags:\n      - Benchmarking\n      - InCites\n      - Research Analytics\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.clarivate.com/apis/incites\n    properties:\n      - url: https://developer.clarivate.com/apis/incites\n        type: Documentation\n    description: >-\n      The InCites API provides programmatic access to the Clarivate\n      research benchmarking platform, enabling institutional research\n      performance analytics built on Web of Science data.\ncommon:\n  - type: Website\n    url: https://clarivate.com/\n  - type: Portal\n    url: https://developer.clarivate.com/\n  - type: API\
  \ Catalog\n    url: https://developer.clarivate.com/apis\n  - type: Support\n    url: https://support.clarivate.com/\n  - type: Privacy Policy\n    url: https://clarivate.com/privacy-center/\n  - type: Terms of Service\n    url: https://clarivate.com/legal-center/\n  - type: JSON-LD\n    url: json-ld/clarivate-context.jsonld\n  - type: Spectral\n    url: rules/clarivate-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/clarivate-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/clarivate/refs/heads/main/apis.yml
tags:
- Analytics
- Citations
- Data
- Drug Pipeline
- Insights
- Intellectual Property
- Life Sciences
- Patents
- Publications
- Research
url: https://raw.githubusercontent.com/api-evangelist/clarivate/refs/heads/main/apis.yml
use_cases: []
---
