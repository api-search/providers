---
api_count: 5
apis:
- description: Scopus delivers a comprehensive view of the world of research, allowing tracking, analysis, and visualization of research data across publishers, journals, books, conference proceedings, and trade pub
  name: Elsevier Scopus APIs
  slug: elsevier-scopus-apis
- description: ScienceDirect APIs expose peer-reviewed full-text scientific, technical and medical content from all scholarly publications indexed by ScienceDirect, Elsevier's premier scientific platform.
  name: Elsevier ScienceDirect APIs
  slug: elsevier-sciencedirect-apis
- description: The SciVal API gives access to a comprehensive set of metrics for researchers (Scopus Author profiles) and 8,500+ institutions available in SciVal, Elsevier's platform for research performance benchma
  name: Elsevier SciVal API
  slug: elsevier-scival-api
- description: Engineering Village APIs provide programmatic access to engineering research literature, indexed publications, and engineering-focused content across multiple databases.
  name: Elsevier Engineering Village API
  slug: elsevier-engineering-village-api
- description: Embase APIs provide access to biomedical and pharmacological abstracts and indexing for life sciences research, drug development, and evidence-based medicine.
  name: Elsevier Embase API
  slug: elsevier-embase-api
common:
- title: ''
  type: Portal
  url: https://dev.elsevier.com/
- title: ''
  type: GettingStarted
  url: https://dev.elsevier.com/getting_started.html
- title: ''
  type: Documentation
  url: https://dev.elsevier.com/api_docs.html
- title: ''
  type: TermsOfService
  url: https://dev.elsevier.com/api_service_agreement.html
- title: ''
  type: PrivacyPolicy
  url: http://www.elsevier.com/locate/privacypolicy
- title: ''
  type: Examples
  url: https://dev.elsevier.com/examples.html
- title: ''
  type: Guides
  url: https://dev.elsevier.com/technical_documentation.html
- title: ''
  type: SDK
  url: https://github.com/ElsevierDev/elsapy
- title: ''
  type: Support
  url: https://dev.elsevier.com/support.html
created: '2023-11-22'
description: Elsevier is a Dutch academic publishing company specializing in scientific, technical, and medical content. Its products include journals such as The Lancet and Cell, the ScienceDirect collection of electronic journals, the online citation database Scopus, the SciVal research performance platform, and the ClinicalKey search engine for clinicians.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Elsevier
skills: []
slug: elsevier
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: elsevier\nname: Elsevier\ndescription: >-\n  Elsevier is a Dutch academic publishing company specializing in scientific,\n  technical, and medical content. Its products include journals such as The\n  Lancet and Cell, the ScienceDirect collection of electronic journals, the\n  online citation database Scopus, the SciVal research performance platform,\n  and the ClinicalKey search engine for clinicians.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Content\n  - Journals\n  - Medical\n  - Research\n  - Scientific\n  - Technical\ncreated: '2023-11-22'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/elsevier/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: elsevier:elsevier-scopus-apis\n    name: Elsevier Scopus APIs\n    description: >-\n      Scopus delivers a comprehensive view of the world of research, allowing\n\
  \      tracking, analysis, and visualization of research data across publishers,\n      journals, books, conference proceedings, and trade publications.\n    humanURL: https://dev.elsevier.com/sc_apis.html\n    tags:\n      - Citations\n      - Research\n      - Scientific\n    properties:\n      - type: Documentation\n        url: https://dev.elsevier.com/scopus.html\n      - type: Specification\n        url: https://dev.elsevier.com/api_docs.html\n  - aid: elsevier:elsevier-sciencedirect-apis\n    name: Elsevier ScienceDirect APIs\n    description: >-\n      ScienceDirect APIs expose peer-reviewed full-text scientific, technical\n      and medical content from all scholarly publications indexed by\n      ScienceDirect, Elsevier's premier scientific platform.\n    humanURL: https://dev.elsevier.com/sd_apis.html\n    tags:\n      - Full Text\n      - Journals\n      - Scientific\n    properties:\n      - type: Documentation\n        url: https://dev.elsevier.com/sciencedirect.html\n  \
  \    - type: Specification\n        url: https://dev.elsevier.com/api_docs.html\n  - aid: elsevier:elsevier-scival-api\n    name: Elsevier SciVal API\n    description: >-\n      The SciVal API gives access to a comprehensive set of metrics for\n      researchers (Scopus Author profiles) and 8,500+ institutions available\n      in SciVal, Elsevier's platform for research performance benchmarking.\n    humanURL: https://dev.elsevier.com/scival_apis.html\n    tags:\n      - Benchmarking\n      - Metrics\n      - Research\n    properties:\n      - type: Documentation\n        url: https://dev.elsevier.com/scival.html\n      - type: Specification\n        url: https://dev.elsevier.com/api_docs.html\n  - aid: elsevier:elsevier-engineering-village-api\n    name: Elsevier Engineering Village API\n    description: >-\n      Engineering Village APIs provide programmatic access to engineering\n      research literature, indexed publications, and engineering-focused\n      content across multiple\
  \ databases.\n    humanURL: https://dev.elsevier.com/ev.html\n    tags:\n      - Engineering\n      - Research\n    properties:\n      - type: Documentation\n        url: https://dev.elsevier.com/ev.html\n  - aid: elsevier:elsevier-embase-api\n    name: Elsevier Embase API\n    description: >-\n      Embase APIs provide access to biomedical and pharmacological abstracts\n      and indexing for life sciences research, drug development, and\n      evidence-based medicine.\n    humanURL: https://dev.elsevier.com/embase.html\n    tags:\n      - Biomedical\n      - Medical\n      - Pharmacology\n    properties:\n      - type: Documentation\n        url: https://dev.elsevier.com/embase.html\ncommon:\n  - type: Portal\n    url: https://dev.elsevier.com/\n  - type: GettingStarted\n    url: https://dev.elsevier.com/getting_started.html\n  - type: Documentation\n    url: https://dev.elsevier.com/api_docs.html\n  - type: UseCases\n    url: https://dev.elsevier.com/use_cases.html\n  - type: TermsOfService\n\
  \    url: https://dev.elsevier.com/api_service_agreement.html\n  - type: PrivacyPolicy\n    url: http://www.elsevier.com/locate/privacypolicy\n  - type: Examples\n    url: https://dev.elsevier.com/examples.html\n  - type: Guides\n    url: https://dev.elsevier.com/technical_documentation.html\n  - type: SDK\n    url: https://github.com/ElsevierDev/elsapy\n  - type: Support\n    url: https://dev.elsevier.com/support.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/elsevier/refs/heads/main/apis.yml
tags:
- Content
- Journals
- Medical
- Research
- Scientific
- Technical
url: https://raw.githubusercontent.com/api-evangelist/elsevier/refs/heads/main/apis.yml
use_cases: []
---
