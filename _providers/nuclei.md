---
api_count: 2
api_specs:
- filename: nuclei-openapi.yml
  format: yaml
  label: ProjectDiscovery Cloud Platform API
  slug: projectdiscovery-cloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nuclei/refs/heads/main/openapi/nuclei-openapi.yml
apis:
- description: Nuclei is an open source vulnerability scanner from ProjectDiscovery that uses YAML-based templates to find security issues in APIs, web apps, and infrastructure.
  name: Nuclei
  slug: nuclei
- description: REST API for the ProjectDiscovery Cloud Platform (PDCP) covering Nuclei templates, scans, vulnerabilities, leaks, asset discovery, configurations, exports, audit logs, and utilities. Authentication us
  name: ProjectDiscovery Cloud Platform API
  slug: projectdiscovery-cloud-api
common:
- title: ''
  type: Website
  url: https://nuclei.projectdiscovery.io
- title: ''
  type: Documentation
  url: https://docs.projectdiscovery.io/tools/nuclei/overview
- title: ''
  type: Reference
  url: https://docs.projectdiscovery.io/api-reference/introduction
- title: ''
  type: GitHubOrganization
  url: https://github.com/projectdiscovery
- title: ''
  type: GitHubRepository
  url: https://github.com/projectdiscovery/nuclei
- title: ''
  type: Templates
  url: https://github.com/projectdiscovery/nuclei-templates
- title: ''
  type: Cloud
  url: https://cloud.projectdiscovery.io/
created: '2026-03-25'
description: Nuclei is an open source vulnerability scanner from ProjectDiscovery that uses YAML-based templates to find security issues in APIs, web apps, and infrastructure. It supports multiple protocols (HTTP, DNS, TCP, file), parallel scanning, CI/CD integration, and ships with thousands of community-contributed templates. The ProjectDiscovery Cloud Platform exposes a REST API for managing templates, scans, vulnerabilities, leaks, asset discovery, exports, and more.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Nuclei
skills: []
slug: nuclei
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nuclei\nname: Nuclei\ndescription: >-\n  Nuclei is an open source vulnerability scanner from ProjectDiscovery that\n  uses YAML-based templates to find security issues in APIs, web apps, and\n  infrastructure. It supports multiple protocols (HTTP, DNS, TCP, file),\n  parallel scanning, CI/CD integration, and ships with thousands of\n  community-contributed templates. The ProjectDiscovery Cloud Platform exposes\n  a REST API for managing templates, scans, vulnerabilities, leaks, asset\n  discovery, exports, and more.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Security Testing\n  - Testing\n  - Vulnerability Scanner\n  - DAST\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/nuclei/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: nuclei:nuclei\n    name: Nuclei\n    description: >-\n      Nuclei is an open source\
  \ vulnerability scanner from ProjectDiscovery\n      that uses YAML-based templates to find security issues in APIs, web\n      apps, and infrastructure.\n    humanURL: https://nuclei.projectdiscovery.io\n    tags:\n      - Security Testing\n      - Testing\n      - Vulnerability Scanner\n    properties:\n      - type: Documentation\n        url: https://docs.projectdiscovery.io/tools/nuclei/overview\n      - type: GitHubRepository\n        url: https://github.com/projectdiscovery/nuclei\n  - aid: nuclei:projectdiscovery-cloud-api\n    name: ProjectDiscovery Cloud Platform API\n    description: >-\n      REST API for the ProjectDiscovery Cloud Platform (PDCP) covering Nuclei\n      templates, scans, vulnerabilities, leaks, asset discovery,\n      configurations, exports, audit logs, and utilities. Authentication uses\n      API keys passed via the X-Api-Key header.\n    humanURL: https://docs.projectdiscovery.io/api-reference/introduction\n    baseURL: https://api.projectdiscovery.io\n\
  \    tags:\n      - Security Testing\n      - Vulnerability Scanner\n      - Templates\n      - Scans\n      - Cloud\n    properties:\n      - type: Documentation\n        url: https://docs.projectdiscovery.io/api-reference/introduction\n      - type: Portal\n        url: https://cloud.projectdiscovery.io/\n      - type: OpenAPI\n        url: openapi/nuclei-openapi.yml\ncommon:\n  - type: Website\n    url: https://nuclei.projectdiscovery.io\n  - type: Documentation\n    url: https://docs.projectdiscovery.io/tools/nuclei/overview\n  - type: Reference\n    url: https://docs.projectdiscovery.io/api-reference/introduction\n  - type: GitHubOrganization\n    url: https://github.com/projectdiscovery\n  - type: GitHubRepository\n    url: https://github.com/projectdiscovery/nuclei\n  - type: Templates\n    url: https://github.com/projectdiscovery/nuclei-templates\n  - type: Cloud\n    url: https://cloud.projectdiscovery.io/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nuclei/refs/heads/main/apis.yml
tags:
- Security Testing
- Testing
- Vulnerability Scanner
- DAST
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/nuclei/refs/heads/main/apis.yml
use_cases: []
---
