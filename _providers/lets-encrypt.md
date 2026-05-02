---
api_count: 1
api_specs:
- filename: lets-encrypt-acme-openapi.yml
  format: yaml
  label: Let's Encrypt ACME API
  slug: lets-encrypt-acme-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lets-encrypt/refs/heads/main/openapi/lets-encrypt-acme-openapi.yml
apis:
- description: The ACME (Automatic Certificate Management Environment) protocol API, defined by RFC 8555, used by Let's Encrypt to automate the issuance, renewal, and revocation of free TLS/SSL certificates that sec
  name: Let's Encrypt ACME API
  slug: lets-encrypt-acme-api
common:
- title: ''
  type: Documentation
  url: https://letsencrypt.org/docs/
- title: ''
  type: GitHubOrg
  url: https://github.com/letsencrypt
- title: ''
  type: Specification
  url: https://datatracker.ietf.org/doc/html/rfc8555
created: '2026-03-16'
description: Let's Encrypt is a free, automated, and open certificate authority run by the Internet Security Research Group affiliated with the Linux Foundation. It provides TLS certificates to secure the web, having issued billions of certificates to enable HTTPS for websites worldwide via the ACME protocol.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Let's Encrypt
skills: []
slug: lets-encrypt
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: lets-encrypt\nname: Let's Encrypt\ndescription: >-\n  Let's Encrypt is a free, automated, and open certificate authority run by the\n  Internet Security Research Group affiliated with the Linux Foundation. It\n  provides TLS certificates to secure the web, having issued billions of\n  certificates to enable HTTPS for websites worldwide via the ACME protocol.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Certificates\n  - Linux Foundation\n  - Security\n  - TLS\n  - ACME\n  - PKI\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/lets-encrypt/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: lets-encrypt:lets-encrypt-acme-api\n    name: Let's Encrypt ACME API\n    description: >-\n      The ACME (Automatic Certificate Management Environment) protocol API, defined\n      by RFC 8555, used by Let's\
  \ Encrypt to automate the issuance, renewal, and\n      revocation of free TLS/SSL certificates that secure websites with HTTPS.\n    humanURL: https://letsencrypt.org/docs/\n    baseURL: https://acme-v02.api.letsencrypt.org\n    tags:\n      - ACME\n      - Certificates\n      - TLS\n      - PKI\n    properties:\n      - type: Documentation\n        url: https://letsencrypt.org/docs/\n      - type: OpenAPI\n        url: openapi/lets-encrypt-acme-openapi.yml\ncommon:\n  - type: Documentation\n    name: Let's Encrypt Documentation\n    description: Official documentation for Let's Encrypt.\n    url: https://letsencrypt.org/docs/\n  - type: GitHubOrg\n    name: Let's Encrypt GitHub\n    description: Source code and repositories for Let's Encrypt.\n    url: https://github.com/letsencrypt\n  - type: Specification\n    name: ACME RFC 8555\n    description: IETF specification for the ACME protocol.\n    url: https://datatracker.ietf.org/doc/html/rfc8555\nmaintainers:\n  - FN: Kin Lane\n    email:\
  \ info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/lets-encrypt/refs/heads/main/apis.yml
tags:
- Certificates
- Linux Foundation
- Security
- TLS
- ACME
- PKI
url: https://raw.githubusercontent.com/api-evangelist/lets-encrypt/refs/heads/main/apis.yml
use_cases: []
---
