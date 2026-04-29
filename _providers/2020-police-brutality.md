---
api_count: 1
api_specs:
- filename: 2020-police-brutality-openapi.yml
  format: yaml
  label: 2020 Police Brutality API
  slug: 2020-police-brutality
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/2020-police-brutality/refs/heads/main/openapi/2020-police-brutality-openapi.yml
apis:
- description: This repository accumulates and contextualizes evidence of police brutality during the 2020 George Floyd protests. Data is available as JSON and CSV files from the data_build branch, including geoloca
  name: 2020 Police Brutality API
  slug: 2020-police-brutality
capabilities:
- description: 'Workflow for accessing and analyzing documented police brutality incidents from the 2020 George Floyd protests. Designed for journalists, researchers, prosecutors, and activists who need programmatic '
  name: 2020 Police Brutality Incident Research
  slug: 2020-police-brutality-incident-research
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/2020PB
- title: ''
  type: GitHubRepository
  url: https://github.com/2020PB/police-brutality
- title: ''
  type: Documentation
  url: https://github.com/2020PB/police-brutality/blob/main/README.md
- title: ''
  type: SpectralRules
  url: rules/2020-police-brutality-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/2020-police-brutality-incident-research.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/2020-police-brutality-vocabulary.yaml
created: '2024-11-13'
description: This repository accumulates and contextualizes evidence of police brutality during the 2020 George Floyd protests. The goal is to assist journalists, politicians, prosecutors, activists and concerned individuals who can use the evidence accumulated here for political campaigns, news reporting, public education and prosecution of criminal police officers.
features:
- description: Documented evidence of police brutality with descriptions, dates, locations, and source links
  name: Incident Documentation
- description: GPS geolocation coordinates for each incident, enabling geographic analysis
  name: Location Data
- description: Categorical tags classifying incident types (foam-bullet, tear-gas, pepper-spray, etc.)
  name: Tag Classification
- description: Data available in JSON (v1 and v2) and CSV formats for different use cases
  name: Multiple Data Formats
- description: Each incident includes links to source documentation for verification
  name: Source Verification
- description: MIT licensed open dataset available for public use
  name: Open Data
image: /assets/icons/2020-police-brutality.png
integrations: []
jsonld:
- class_count: 5
  name: 2020 Police Brutality Context
  property_count: 11
  slug: 2020-police-brutality-context
layout: provider
modified: '2026-04-19'
name: 2020 Police Brutality
rules:
- name: 2020 Police Brutality API Rules
  rule_count: 19
  severity_counts:
    error: 10
    hint: 0
    info: 2
    warn: 7
  slug: 2020-police-brutality-spectral-rules
skills: []
slug: 2020-police-brutality
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: 2020-police-brutality\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/2020-police-brutality/refs/heads/main/apis.yml\nname: 2020 Police Brutality\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Brutality\n  - Civil Rights\n  - Policing\n  - Public Data\ndescription: >-\n  This repository accumulates and contextualizes evidence of police brutality\n  during the 2020 George Floyd protests. The goal is to assist journalists,\n  politicians, prosecutors, activists and concerned individuals who can use the\n  evidence accumulated here for political campaigns, news reporting, public\n  education and prosecution of criminal police officers.\ncreated: '2024-11-13'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: 2020-police-brutality:2020-police-brutality\n    name: 2020 Police Brutality API\n    tags:\n      - Brutality\n      - Civil Rights\n      - Incidents\n      - Policing\n   \
  \ humanURL: https://github.com/2020PB/police-brutality/tree/data_build\n    baseURL: https://raw.githubusercontent.com/2020PB/police-brutality/data_build\n    properties:\n      - url: https://github.com/2020PB/police-brutality/tree/data_build\n        type: Documentation\n      - url: openapi/2020-police-brutality-openapi.yml\n        type: OpenAPI\n      - url: json-schema/2020-police-brutality-incident-schema.json\n        type: JSONSchema\n      - url: json-schema/2020-police-brutality-incident-collection-schema.json\n        type: JSONSchema\n      - url: json-ld/2020-police-brutality-context.jsonld\n        type: JSON-LD\n    description: >-\n      This repository accumulates and contextualizes evidence of police\n      brutality during the 2020 George Floyd protests. Data is available as\n      JSON and CSV files from the data_build branch, including geolocation,\n      tags, dates, and source links for each incident.\ncommon:\n  - type: GitHubOrganization\n    url: https://github.com/2020PB\n\
  \  - type: GitHubRepository\n    url: https://github.com/2020PB/police-brutality\n  - type: Documentation\n    url: https://github.com/2020PB/police-brutality/blob/main/README.md\n  - type: SpectralRules\n    url: rules/2020-police-brutality-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/2020-police-brutality-incident-research.yaml\n  - type: Vocabulary\n    url: vocabulary/2020-police-brutality-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Incident Documentation\n        description: Documented evidence of police brutality with descriptions, dates, locations, and source links\n      - name: Location Data\n        description: GPS geolocation coordinates for each incident, enabling geographic analysis\n      - name: Tag Classification\n        description: Categorical tags classifying incident types (foam-bullet, tear-gas, pepper-spray, etc.)\n      - name: Multiple Data Formats\n        description: Data available in JSON (v1 and v2) and CSV formats\
  \ for different use cases\n      - name: Source Verification\n        description: Each incident includes links to source documentation for verification\n      - name: Open Data\n        description: MIT licensed open dataset available for public use\n  - type: UseCases\n    data:\n      - name: Journalism and Reporting\n        description: Investigative journalists use incident data for news reporting on police conduct\n      - name: Legal Proceedings\n        description: Prosecutors and civil rights attorneys use evidence for criminal and civil cases\n      - name: Academic Research\n        description: Researchers study patterns in police use of force during protests\n      - name: Policy Advocacy\n        description: Activists and policymakers use data to support police reform campaigns\n      - name: Public Education\n        description: Organizations use the data to educate the public about police brutality\n      - name: Geographic Analysis\n        description: Researchers\
  \ map incidents by location to identify geographic patterns\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/2020-police-brutality/refs/heads/main/apis.yml
tags:
- Brutality
- Civil Rights
- Policing
- Public Data
url: https://raw.githubusercontent.com/api-evangelist/2020-police-brutality/refs/heads/main/apis.yml
use_cases:
- description: Investigative journalists use incident data for news reporting on police conduct
  name: Journalism and Reporting
- description: Prosecutors and civil rights attorneys use evidence for criminal and civil cases
  name: Legal Proceedings
- description: Researchers study patterns in police use of force during protests
  name: Academic Research
- description: Activists and policymakers use data to support police reform campaigns
  name: Policy Advocacy
- description: Organizations use the data to educate the public about police brutality
  name: Public Education
- description: Researchers map incidents by location to identify geographic patterns
  name: Geographic Analysis
---
