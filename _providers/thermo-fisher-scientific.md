---
api_count: 3
api_specs:
- filename: thermo-fisher-samplemanager-openapi.yml
  format: yaml
  label: Thermo Fisher SampleManager LIMS REST API
  slug: samplemanager-lims
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/openapi/thermo-fisher-samplemanager-openapi.yml
- filename: thermo-fisher-nanodrop-openapi.yml
  format: yaml
  label: Thermo Fisher NanoDrop Ultra Web API
  slug: nanodrop-ultra
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/openapi/thermo-fisher-nanodrop-openapi.yml
apis:
- description: The Thermo Scientific SampleManager LIMS REST API enables secure connection between software applications and the SampleManager LIMS system for simplified data exchange. Provides access to sample data
  name: Thermo Fisher SampleManager LIMS REST API
  slug: samplemanager-lims
- description: The Thermo Scientific NanoDrop Ultra Web API provides RESTful access to instrument control and data export for the NanoDrop Ultra microvolume UV-Vis spectrophotometer. Enables laboratory informatics i
  name: Thermo Fisher NanoDrop Ultra Web API
  slug: nanodrop-ultra
- description: The Thermo Fisher Connect Platform OData API provides standards-based interoperability for laboratory data management, enabling integration between instruments, LIMS, ELN, and enterprise systems throu
  name: Thermo Fisher Connect Platform OData API
  slug: connect-platform
capabilities:
- description: Workflow capability for laboratory data management combining SampleManager LIMS and NanoDrop Ultra spectrophotometer APIs. Covers sample lifecycle, result entry, instrument measurements, and LIMS inte
  name: Thermo Fisher Scientific Lab Data Management
  slug: lab-data-management
common:
- title: ''
  type: Website
  url: https://www.thermofisher.com
- title: ''
  type: Documentation
  url: https://www.thermofisher.com/us/en/home/digital-science/thermo-fisher-connect.html
- title: ''
  type: Blog
  url: https://www.thermofisher.com/blog/connectedlab/
- title: ''
  type: Documentation
  url: https://www.thermofisher.com/blog/connectedlab/platform-for-science-developer-portal-beta/
- title: ''
  type: GitHubRepository
  url: https://github.com/thermofisherlsms/iapi
- title: ''
  type: GitHubOrganization
  url: https://github.com/thermofisherlsms
created: '2026-03-21'
description: Thermo Fisher Scientific is the world leader in serving science, providing analytical instruments, life sciences solutions, specialty diagnostics, laboratory products, and biopharma services. Developer APIs enable laboratory automation, instrument control, LIMS integration, and data management across life science workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Thermo Fisher Context
  property_count: 3
  slug: thermo-fisher-context
layout: provider
modified: '2026-05-03'
name: Thermo Fisher Scientific
rules:
- name: Thermo Fisher Scientific API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 6
  slug: thermo-fisher-rules
skills: []
slug: thermo-fisher-scientific
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: thermo-fisher-scientific\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/apis.yml\napis:\n  - aid: thermo-fisher-scientific:samplemanager-lims\n    name: Thermo Fisher SampleManager LIMS REST API\n    tags:\n      - LIMS\n      - Laboratory\n      - Life Sciences\n      - Sample Management\n      - REST API\n    humanURL: https://www.thermofisher.com/us/en/home/digital-solutions/lab-informatics/lab-information-management-systems-lims/solutions/samplemanager.html\n    baseURL: https://{your-server}:{port}/smpwcfrestvgsm\n    properties:\n      - url: https://www.thermofisher.com/us/en/home/digital-solutions/lab-informatics/lab-information-management-systems-lims/solutions/samplemanager.html\n        type: Documentation\n      - url: openapi/thermo-fisher-samplemanager-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Thermo Scientific SampleManager LIMS REST API enables secure connection\n      between\
  \ software applications and the SampleManager LIMS system for simplified\n      data exchange. Provides access to sample data, workflows, entities, results,\n      and laboratory operations. Runs on port 56105 and supports token authentication.\n\n  - aid: thermo-fisher-scientific:nanodrop-ultra\n    name: Thermo Fisher NanoDrop Ultra Web API\n    tags:\n      - Spectrophotometry\n      - Laboratory Instruments\n      - Life Sciences\n      - REST API\n      - UV-Vis\n    humanURL: https://documents.thermofisher.com/TFS-Assets/CAD/manuals/nanodrop-ultra-api-reference-manual-m024.pdf\n    baseURL: https://{nanodrop-instrument-ip}\n    properties:\n      - url: https://documents.thermofisher.com/TFS-Assets/CAD/manuals/nanodrop-ultra-api-reference-manual-m024.pdf\n        type: Documentation\n      - url: openapi/thermo-fisher-nanodrop-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Thermo Scientific NanoDrop Ultra Web API provides RESTful access to\n      instrument control\
  \ and data export for the NanoDrop Ultra microvolume\n      UV-Vis spectrophotometer. Enables laboratory informatics integration,\n      automated measurement workflows, and data retrieval from the instrument.\n\n  - aid: thermo-fisher-scientific:connect-platform\n    name: Thermo Fisher Connect Platform OData API\n    tags:\n      - Platform\n      - OData\n      - Laboratory\n      - Life Sciences\n      - Integration\n    humanURL: https://www.thermofisher.com/us/en/home/digital-science/thermo-fisher-connect.html\n    baseURL: https://api.thermofisher.com\n    properties:\n      - url: https://www.thermofisher.com/blog/connectedlab/platform-for-science-developer-portal-beta/\n        type: Documentation\n    description: >-\n      The Thermo Fisher Connect Platform OData API provides standards-based\n      interoperability for laboratory data management, enabling integration\n      between instruments, LIMS, ELN, and enterprise systems through the\n      OData REST protocol.\n\nname:\
  \ Thermo Fisher Scientific\ntags:\n  - Life Sciences\n  - Laboratory\n  - Scientific Instruments\n  - LIMS\n  - Diagnostics\n  - Biosciences\n  - Fortune 500\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2026-03-21'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  Thermo Fisher Scientific is the world leader in serving science, providing analytical\n  instruments, life sciences solutions, specialty diagnostics, laboratory products,\n  and biopharma services. Developer APIs enable laboratory automation, instrument\n  control, LIMS integration, and data management across life science workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: Thermo Fisher Scientific Website\n    url: https://www.thermofisher.com\n    type: Website\n  - name: Thermo Fisher Connect Platform\n    url: https://www.thermofisher.com/us/en/home/digital-science/thermo-fisher-connect.html\n\
  \    type: Documentation\n  - name: Connected Lab Blog\n    url: https://www.thermofisher.com/blog/connectedlab/\n    type: Blog\n  - name: Developer Portal (Beta)\n    url: https://www.thermofisher.com/blog/connectedlab/platform-for-science-developer-portal-beta/\n    type: Documentation\n  - name: Instrument API GitHub\n    url: https://github.com/thermofisherlsms/iapi\n    type: GitHubRepository\n  - name: GitHub Organization\n    url: https://github.com/thermofisherlsms\n    type: GitHubOrganization\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/apis.yml
tags:
- Life Sciences
- Laboratory
- Scientific Instruments
- LIMS
- Diagnostics
- Biosciences
- Fortune 500
url: https://raw.githubusercontent.com/api-evangelist/thermo-fisher-scientific/refs/heads/main/apis.yml
use_cases: []
---
