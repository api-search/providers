---
api_count: 6
api_specs:
- filename: nvd-cve-openapi.yml
  format: yaml
  label: NVD CVE API
  slug: nvd-cve
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml
- filename: nvd-cve-openapi.yml
  format: yaml
  label: NVD CVE Change History API
  slug: nvd-cve-history
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml
- filename: nvd-cve-openapi.yml
  format: yaml
  label: NVD CPE API
  slug: nvd-cpe
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml
- filename: nvd-cve-openapi.yml
  format: yaml
  label: NVD CPE Match Criteria API
  slug: nvd-cpe-match
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml
- filename: nvd-cve-openapi.yml
  format: yaml
  label: NVD Source API
  slug: nvd-source
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml
apis:
- description: The NVD CVE API provides programmatic access to CVE (Common Vulnerabilities and Exposures) records including CVSS severity scores, affected product lists, CWE classifications, and reference links. Sup
  name: NVD CVE API
  slug: nvd-cve
- description: The NVD CVE Change History API tracks modifications to CVE records over time, enabling consumers to identify updated vulnerability data and synchronize their local databases with incremental changes r
  name: NVD CVE Change History API
  slug: nvd-cve-history
- description: The NVD CPE (Common Platform Enumeration) API provides access to the authoritative CPE dictionary, enabling lookup of software and hardware product identifiers. Supports filtering by CPE name, match s
  name: NVD CPE API
  slug: nvd-cpe
- description: The NVD CPE Match Criteria API retrieves CPE match strings associated with CVE records, enabling detailed product-to-vulnerability mapping. Supports filtering by CVE ID, match criteria ID, and match s
  name: NVD CPE Match Criteria API
  slug: nvd-cpe-match
- description: The NVD Source API provides information about the organizations that contribute vulnerability data to the NVD dataset, enabling consumers to understand data provenance. Returns up to 1,000 source reco
  name: NVD Source API
  slug: nvd-source
- description: The National Vulnerability Database (NVD) provides REST and RSS/Atom APIs for CVE (Common Vulnerabilities and Exposures) data. APIs deliver vulnerability descriptions, CVSS severity scores, affected p
  name: National Vulnerability Database API
  slug: nvd-overview
common:
- title: ''
  type: Portal
  url: https://nvd.nist.gov/developers
- title: ''
  type: Website
  url: https://nvd.nist.gov/
- title: ''
  type: GettingStarted
  url: https://nvd.nist.gov/developers/start-here
- title: ''
  type: Authentication
  url: https://nvd.nist.gov/developers/request-an-api-key
- title: ''
  type: RateLimits
  url: https://nvd.nist.gov/developers/start-here
- title: ''
  type: TermsOfService
  url: https://nvd.nist.gov/developers/terms-of-use
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/json-schema/nvd-cve-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/json-ld/nvd-context.jsonld
created: ''
description: The National Vulnerability Database (NVD) provides REST APIs for CVE (Common Vulnerabilities and Exposures) data, CPE (Common Platform Enumeration) records, match criteria, and source organizations. APIs deliver vulnerability descriptions, CVSS severity scores, affected product lists, CWE classifications, and reference links for security monitoring and dependency alerting.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 8
  name: Nvd Context
  property_count: 14
  slug: nvd-context
layout: provider
modified: '2026-04-28'
name: NVD
skills: []
slug: nvd
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nvd\nname: NVD\ndescription: >-\n  The National Vulnerability Database (NVD) provides REST APIs for CVE (Common\n  Vulnerabilities and Exposures) data, CPE (Common Platform Enumeration) records,\n  match criteria, and source organizations. APIs deliver vulnerability descriptions,\n  CVSS severity scores, affected product lists, CWE classifications, and reference\n  links for security monitoring and dependency alerting.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Security\n  - CVE\n  - CPE\n  - Vulnerability\n  - CVSS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/apis.yml\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: nvd:nvd-cve\n    name: NVD CVE API\n    description: >-\n      The NVD CVE API provides programmatic access to CVE (Common Vulnerabilities\n      and Exposures) records including CVSS severity scores, affected product\n      lists, CWE\
  \ classifications, and reference links. Supports filtering by CVE\n      ID, CVSS metrics, CWE, keyword, modification date, and publication date.\n      Without an API key: 5 requests per 30 seconds; with key: 50 requests per\n      30 seconds.\n    humanURL: https://nvd.nist.gov/developers/vulnerabilities\n    tags:\n      - Security\n      - CVE\n      - Vulnerability\n      - CVSS\n    properties:\n      - type: Documentation\n        url: https://nvd.nist.gov/developers/vulnerabilities\n      - type: GettingStarted\n        url: https://nvd.nist.gov/developers/start-here\n      - type: Authentication\n        url: https://nvd.nist.gov/developers/request-an-api-key\n      - type: RateLimits\n        url: https://nvd.nist.gov/developers/start-here\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/json-schema/nvd-cve-schema.json\n\
  \      - type: JSONLDContext\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/json-ld/nvd-context.jsonld\n  - aid: nvd:nvd-cve-history\n    name: NVD CVE Change History API\n    description: >-\n      The NVD CVE Change History API tracks modifications to CVE records over\n      time, enabling consumers to identify updated vulnerability data and\n      synchronize their local databases with incremental changes rather than\n      full reloads.\n    humanURL: https://nvd.nist.gov/developers/vulnerabilities\n    tags:\n      - Security\n      - CVE\n      - Vulnerability\n      - Change History\n    properties:\n      - type: Documentation\n        url: https://nvd.nist.gov/developers/vulnerabilities\n      - type: GettingStarted\n        url: https://nvd.nist.gov/developers/start-here\n      - type: Authentication\n        url: https://nvd.nist.gov/developers/request-an-api-key\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml\n\
  \  - aid: nvd:nvd-cpe\n    name: NVD CPE API\n    description: >-\n      The NVD CPE (Common Platform Enumeration) API provides access to the\n      authoritative CPE dictionary, enabling lookup of software and hardware\n      product identifiers. Supports filtering by CPE name, match string,\n      keyword, and modification date. Returns up to 10,000 results per page.\n    humanURL: https://nvd.nist.gov/developers/products\n    tags:\n      - Security\n      - CPE\n      - Vulnerability\n      - Product Enumeration\n    properties:\n      - type: Documentation\n        url: https://nvd.nist.gov/developers/products\n      - type: GettingStarted\n        url: https://nvd.nist.gov/developers/start-here\n      - type: Authentication\n        url: https://nvd.nist.gov/developers/request-an-api-key\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml\n  - aid: nvd:nvd-cpe-match\n    name: NVD CPE\
  \ Match Criteria API\n    description: >-\n      The NVD CPE Match Criteria API retrieves CPE match strings associated with\n      CVE records, enabling detailed product-to-vulnerability mapping. Supports\n      filtering by CVE ID, match criteria ID, and match string patterns. Returns\n      up to 500 results per page.\n    humanURL: https://nvd.nist.gov/developers/products\n    tags:\n      - Security\n      - CPE\n      - Vulnerability\n      - Match Criteria\n    properties:\n      - type: Documentation\n        url: https://nvd.nist.gov/developers/products\n      - type: GettingStarted\n        url: https://nvd.nist.gov/developers/start-here\n      - type: Authentication\n        url: https://nvd.nist.gov/developers/request-an-api-key\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml\n  - aid: nvd:nvd-source\n    name: NVD Source API\n    description: >-\n      The NVD Source API provides\
  \ information about the organizations that\n      contribute vulnerability data to the NVD dataset, enabling consumers to\n      understand data provenance. Returns up to 1,000 source records per page.\n      Data changes infrequently; once daily updates recommended.\n    humanURL: https://nvd.nist.gov/developers/data-sources\n    tags:\n      - Security\n      - CVE\n      - Data Sources\n      - Organizations\n    properties:\n      - type: Documentation\n        url: https://nvd.nist.gov/developers/data-sources\n      - type: GettingStarted\n        url: https://nvd.nist.gov/developers/start-here\n      - type: Authentication\n        url: https://nvd.nist.gov/developers/request-an-api-key\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml\n  - aid: nvd:nvd-overview\n    name: National Vulnerability Database API\n    description: >-\n      The National Vulnerability Database (NVD) provides\
  \ REST and RSS/Atom APIs\n      for CVE (Common Vulnerabilities and Exposures) data. APIs deliver\n      vulnerability descriptions, CVSS severity scores, affected product lists,\n      and reference links for security monitoring and dependency alerting.\n    humanURL: https://nvd.nist.gov/developers\n    tags:\n      - Security\n      - CVE\n      - Vulnerability\n      - RSS\n      - XML\n    properties:\n      - type: Documentation\n        url: https://nvd.nist.gov/developers\ncommon:\n  - type: Portal\n    url: https://nvd.nist.gov/developers\n  - type: Website\n    url: https://nvd.nist.gov/\n  - type: GettingStarted\n    url: https://nvd.nist.gov/developers/start-here\n  - type: Authentication\n    url: https://nvd.nist.gov/developers/request-an-api-key\n  - type: RateLimits\n    url: https://nvd.nist.gov/developers/start-here\n  - type: TermsOfService\n    url: https://nvd.nist.gov/developers/terms-of-use\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/openapi/nvd-cve-openapi.yml\n\
  \  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/json-schema/nvd-cve-schema.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/json-ld/nvd-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/apis.yml
tags:
- Security
- CVE
- CPE
- Vulnerability
- CVSS
url: https://raw.githubusercontent.com/api-evangelist/nvd/refs/heads/main/apis.yml
use_cases: []
---
