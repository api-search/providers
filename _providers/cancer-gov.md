---
api_count: 6
apis:
- description: RESTful API that lets developers build applications, search tools, and digital platforms over NCI-supported cancer clinical trials data sourced from NCI's Clinical Trials Reporting Program (CTRP). The
  name: NCI Clinical Trials Search API
  slug: clinical-trials-api
- description: 'The external-facing REST interface for the NCI Genomic Data Commons. Drives the GDC Data Portal and GDC Submission Portal and is open for programmatic access. Provides query, download, and submission '
  name: NCI Genomic Data Commons (GDC) API
  slug: gdc-api
- description: RESTful API for the Surveillance, Epidemiology, and End Results (SEER) Program. Supports SEER datasets plus staging APIs for cancer staging (TNM and Collaborative Stage algorithms), enabling developer
  name: NCI SEER API
  slug: seer-api
- description: The NCI Model and Data Clearinghouse (MoDaC) API provides programmatic access to cancer research data, computational models, and associated tools hosted in MoDaC. Developers can search, retrieve metad
  name: NCI MoDaC API
  slug: modac-api
- description: 'Enterprise Vocabulary Services (EVS) exposes NCI Thesaurus and NCI Metathesaurus content — over 192,000 concepts, 154,000 textual definitions, 623,000 synonyms and 630,000 inter-concept relationships '
  name: NCI EVS Terminology API
  slug: evs-api
- description: A suite of syndicated content channels — RSS feeds, the NCI Dictionary Widget, and syndicated publication content — that partner sites and health platforms can embed to deliver authoritative cancer co
  name: NCI Content Syndication Services
  slug: syndication-services
common:
- title: ''
  type: Website
  url: https://www.cancer.gov/
- title: ''
  type: Portal
  url: https://api.cancer.gov/
- title: ''
  type: SyndicationServices
  url: https://www.cancer.gov/syndication
- title: ''
  type: DataScience
  url: https://datascience.cancer.gov/
- title: ''
  type: OpenDataPolicy
  url: https://www.cancer.gov/research/resources/open-science
- title: ''
  type: PrivacyPolicy
  url: https://www.cancer.gov/policies/privacy-security
- title: ''
  type: LicensingAndReuse
  url: https://www.cancer.gov/policies/copyright-reuse
created: '2024-07-02'
description: Cancer.gov is the web presence of the National Cancer Institute (NCI), the U.S. federal government's principal agency for cancer research and training. NCI and its partner programs expose a rich set of open APIs covering cancer clinical trials, genomic data, cancer-incidence surveillance, research data and models, terminology and vocabularies, and PDQ content — giving researchers, advocacy groups, clinicians, and application developers programmatic access to authoritative cancer data and content.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Cancer.gov
skills: []
slug: cancer-gov
solutions: []
source_yaml: "aid: cancer-gov\nname: Cancer.gov\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cancer-gov/refs/heads/main/apis.yml\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\ntags:\n  - Cancer\n  - Federal Government\n  - Healthcare\n  - Research\n  - Clinical Trials\n  - Genomics\n  - Surveillance\n  - Open Data\naccess: Open\ncreated: '2024-07-02'\nmodified: '2026-04-23'\nposition: Provider\nspecificationVersion: '0.19'\ndescription: >-\n  Cancer.gov is the web presence of the National Cancer Institute (NCI), the\n  U.S. federal government's principal agency for cancer research and training.\n  NCI and its partner programs expose a rich set of open APIs covering cancer\n  clinical trials, genomic data, cancer-incidence surveillance, research\n  data and models, terminology and vocabularies, and PDQ content — giving\n  researchers, advocacy groups, clinicians, and application developers\n  programmatic access to authoritative\
  \ cancer data and content.\napis:\n  - aid: cancer-gov:clinical-trials-api\n    name: NCI Clinical Trials Search API\n    description: >-\n      RESTful API that lets developers build applications, search tools, and\n      digital platforms over NCI-supported cancer clinical trials data\n      sourced from NCI's Clinical Trials Reporting Program (CTRP). The same\n      API powers NCI's public Clinical Trials Search. Developers register\n      for a free API key through the CTS Developer Accounts portal.\n    humanURL: https://clinicaltrialsapi.cancer.gov/\n    baseURL: https://clinicaltrialsapi.cancer.gov/api/v2\n    tags:\n      - Clinical Trials\n      - CTRP\n      - Research\n    properties:\n      - type: Documentation\n        url: https://clinicaltrialsapi.cancer.gov/\n      - type: SignUp\n        url: https://clinicaltrialsapi.cancer.gov/\n      - type: ParentPage\n        url: https://www.cancer.gov/syndication/api\n  - aid: cancer-gov:gdc-api\n    name: NCI Genomic Data Commons\
  \ (GDC) API\n    description: >-\n      The external-facing REST interface for the NCI Genomic Data Commons.\n      Drives the GDC Data Portal and GDC Submission Portal and is open for\n      programmatic access. Provides query, download, and submission\n      endpoints for cancer genomics datasets including TCGA, TARGET, CPTAC,\n      and other NCI-funded genomic programs.\n    humanURL: https://gdc.cancer.gov/developers/gdc-application-programming-interface-api\n    baseURL: https://api.gdc.cancer.gov\n    tags:\n      - Genomics\n      - TCGA\n      - Research Data\n    properties:\n      - type: Documentation\n        url: https://docs.gdc.cancer.gov/API/Users_Guide/Getting_Started/\n      - type: Reference\n        url: https://docs.gdc.cancer.gov/Encyclopedia/pages/REST_API/\n      - type: Portal\n        url: https://portal.gdc.cancer.gov/\n  - aid: cancer-gov:seer-api\n    name: NCI SEER API\n    description: >-\n      RESTful API for the Surveillance, Epidemiology, and End Results\
  \ (SEER)\n      Program. Supports SEER datasets plus staging APIs for cancer staging\n      (TNM and Collaborative Stage algorithms), enabling developers to\n      embed authoritative incidence, survival, and staging logic into their\n      own systems.\n    humanURL: https://api.seer.cancer.gov/\n    baseURL: https://api.seer.cancer.gov\n    tags:\n      - Surveillance\n      - Epidemiology\n      - Staging\n      - SEER\n    properties:\n      - type: Documentation\n        url: https://api.seer.cancer.gov/docs\n      - type: Portal\n        url: https://api.seer.cancer.gov/\n  - aid: cancer-gov:modac-api\n    name: NCI MoDaC API\n    description: >-\n      The NCI Model and Data Clearinghouse (MoDaC) API provides programmatic\n      access to cancer research data, computational models, and associated\n      tools hosted in MoDaC. Developers can search, retrieve metadata, and\n      download model/data artifacts produced by NCI-funded research\n      programs.\n    humanURL: https://modac.cancer.gov/\n\
  \    tags:\n      - Research Data\n      - Models\n      - Clearinghouse\n    properties:\n      - type: Documentation\n        url: https://modac.cancer.gov/swagger-ui/4.14.0/index.html\n      - type: Portal\n        url: https://modac.cancer.gov/\n  - aid: cancer-gov:evs-api\n    name: NCI EVS Terminology API\n    description: >-\n      Enterprise Vocabulary Services (EVS) exposes NCI Thesaurus and NCI\n      Metathesaurus content — over 192,000 concepts, 154,000 textual\n      definitions, 623,000 synonyms and 630,000 inter-concept relationships\n      — through a search and browse API used to code, analyze, and share\n      cancer and biomedical research information.\n    humanURL: https://evs.nci.nih.gov/\n    tags:\n      - Terminology\n      - Vocabulary\n      - NCI Thesaurus\n    properties:\n      - type: Documentation\n        url: https://evs.nci.nih.gov/\n      - type: Explorer\n        url: https://evsexplore.semantics.cancer.gov/\n      - type: WhitePaper\n        url: https://evs.nci.nih.gov/ftp1/NCI_Metathesaurus/EVS%20Metathesaurus%20White%20Paper.pdf\n\
  \  - aid: cancer-gov:syndication-services\n    name: NCI Content Syndication Services\n    description: >-\n      A suite of syndicated content channels — RSS feeds, the NCI Dictionary\n      Widget, and syndicated publication content — that partner sites and\n      health platforms can embed to deliver authoritative cancer content\n      sourced from cancer.gov.\n    humanURL: https://www.cancer.gov/syndication\n    tags:\n      - Syndication\n      - Content\n      - Widgets\n      - RSS\n    properties:\n      - type: Documentation\n        url: https://www.cancer.gov/syndication\ncommon:\n  - type: Website\n    url: https://www.cancer.gov/\n  - type: Portal\n    url: https://api.cancer.gov/\n  - type: SyndicationServices\n    url: https://www.cancer.gov/syndication\n  - type: DataScience\n    url: https://datascience.cancer.gov/\n  - type: OpenDataPolicy\n    url: https://www.cancer.gov/research/resources/open-science\n  - type: PrivacyPolicy\n    url: https://www.cancer.gov/policies/privacy-security\n\
  \  - type: LicensingAndReuse\n    url: https://www.cancer.gov/policies/copyright-reuse\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cancer-gov/refs/heads/main/apis.yml
tags:
- Cancer
- Federal Government
- Healthcare
- Research
- Clinical Trials
- Genomics
- Surveillance
- Open Data
url: https://raw.githubusercontent.com/api-evangelist/cancer-gov/refs/heads/main/apis.yml
use_cases: []
---
