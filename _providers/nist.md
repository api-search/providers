---
api_count: 4
api_specs:
- filename: nist-nvd-cve-openapi.yml
  format: yaml
  label: NIST National Vulnerability Database (NVD) API
  slug: nist-nvd-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nist/refs/heads/main/openapi/nist-nvd-cve-openapi.yml
apis:
- description: Provides programmatic access to the National Vulnerability Database, including CVE information, vulnerability metrics, and security advisories.
  name: NIST National Vulnerability Database (NVD) API
  slug: nist-nvd-api
- description: Access to chemical and physical property data for thousands of chemical species.
  name: NIST Chemistry WebBook API
  slug: nist-chemistry-webbook-api
- description: Provides access to NIST's scientific and technical databases across multiple domains.
  name: NIST Data Gateway
  slug: nist-data-gateway
- description: Provides access to official NIST time services for time synchronization.
  name: NIST Time API
  slug: nist-time-api
common:
- title: ''
  type: Website
  url: https://www.nist.gov
- title: ''
  type: Documentation
  url: https://www.nist.gov/services-resources/software
created: '2024-01-01'
description: APIs provided by the National Institute of Standards and Technology for accessing scientific and technical data, standards, and research information including vulnerability databases, chemistry data, and time services.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: National Institute of Standards and Technology (NIST)
skills: []
slug: nist
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nist\nname: National Institute of Standards and Technology (NIST)\ndescription: >-\n  APIs provided by the National Institute of Standards and Technology for\n  accessing scientific and technical data, standards, and research information\n  including vulnerability databases, chemistry data, and time services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cybersecurity\n  - Government\n  - Measurements\n  - Research\n  - Scientific Data\n  - Standards\nurl: https://raw.githubusercontent.com/api-evangelist/nist/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: nist:nist-nvd-api\n    name: NIST National Vulnerability Database (NVD) API\n    description: >-\n      Provides programmatic access to the National Vulnerability Database,\n      including CVE information, vulnerability metrics, and security advisories.\n    humanURL: https://nvd.nist.gov/developers\n\
  \    baseURL: https://services.nvd.nist.gov/rest/json\n    tags:\n      - CVE\n      - Cybersecurity\n      - Security\n      - Vulnerabilities\n    properties:\n      - type: Documentation\n        url: https://nvd.nist.gov/developers/vulnerabilities\n      - type: Authentication\n        url: https://nvd.nist.gov/developers/request-an-api-key\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/nist/refs/heads/main/openapi/nist-nvd-cve-openapi.yml\n  - aid: nist:nist-chemistry-webbook-api\n    name: NIST Chemistry WebBook API\n    description: >-\n      Access to chemical and physical property data for thousands of chemical\n      species.\n    humanURL: https://webbook.nist.gov/chemistry/\n    baseURL: https://webbook.nist.gov/cgi\n    tags:\n      - Chemistry\n      - Physical Properties\n      - Scientific Data\n    properties:\n      - type: Documentation\n        url: https://webbook.nist.gov/chemistry/form-ser/\n  - aid: nist:nist-data-gateway\n\
  \    name: NIST Data Gateway\n    description: >-\n      Provides access to NIST's scientific and technical databases across\n      multiple domains.\n    humanURL: https://data.nist.gov\n    baseURL: https://data.nist.gov\n    tags:\n      - Open Data\n      - Research Data\n      - Scientific Data\n    properties:\n      - type: Documentation\n        url: https://data.nist.gov/sdp/#/\n  - aid: nist:nist-time-api\n    name: NIST Time API\n    description: >-\n      Provides access to official NIST time services for time synchronization.\n    humanURL: https://www.nist.gov/pml/time-and-frequency-division/time-distribution/internet-time-service-its\n    tags:\n      - Standards\n      - Synchronization\n      - Time\n    properties:\n      - type: Documentation\n        url: https://tf.nist.gov/tf-cgi/servers.cgi\ncommon:\n  - type: Website\n    url: https://www.nist.gov\n  - type: Documentation\n    url: https://www.nist.gov/services-resources/software\nmaintainers:\n  - FN: Kin Lane\n\
  \    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nist/refs/heads/main/apis.yml
tags:
- Cybersecurity
- Government
- Measurements
- Research
- Scientific Data
- Standards
url: https://raw.githubusercontent.com/api-evangelist/nist/refs/heads/main/apis.yml
use_cases: []
---
