---
api_count: 8
apis:
- description: The Gandi Domain API enables you to register, manage, transfer, and renew domain names registered with Gandi.
  name: Gandi Domain API
  slug: domains
- description: The Gandi LiveDNS API provides DNS management capabilities for domains managed by Gandi, including DNS records, DNSSEC, zone transfers, and TSIG keys.
  name: Gandi LiveDNS API
  slug: livedns
- description: The Gandi Certificate API allows you to manage SSL/TLS certificates.
  name: Gandi Certificate API
  slug: certificate
- description: The Gandi Email API allows you to manage email accounts and mailboxes.
  name: Gandi Email API
  slug: email
- description: The Gandi Billing API allows you to manage account billing information.
  name: Gandi Billing API
  slug: billing
- description: The Gandi Organization API allows you to manage organizations and users.
  name: Gandi Organization API
  slug: organization
- description: The Gandi Web Hosting API allows you to manage Simple Hosting instances.
  name: Gandi Web Hosting API
  slug: simplehosting
- description: The GandiCloud VPS API allows you to manage virtual private servers.
  name: Gandi Cloud VPS API
  slug: gandicloud
common:
- title: ''
  type: Website
  url: https://www.gandi.net/
- title: ''
  type: Documentation
  url: https://api.gandi.net/docs/reference/
- title: ''
  type: Sandbox
  url: https://api.sandbox.gandi.net/docs/
created: '2025-02-09'
description: Gandi is a domain name registrar and web hosting provider. The Gandi v5 Public API exposes domain management, LiveDNS, certificates, email, organization, billing, and hosting capabilities for programmatic use.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Gandi
skills: []
slug: gandi
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: gandi\nname: Gandi\ndescription: >-\n  Gandi is a domain name registrar and web hosting provider. The Gandi v5\n  Public API exposes domain management, LiveDNS, certificates, email,\n  organization, billing, and hosting capabilities for programmatic use.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - DNS\n  - Domains\n  - Domain Registrar\n  - Email\n  - Hosting\n  - Certificates\ncreated: '2025-02-09'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/gandi/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: gandi:domains\n    name: Gandi Domain API\n    description: >-\n      The Gandi Domain API enables you to register, manage, transfer, and renew\n      domain names registered with Gandi.\n    humanURL: https://api.gandi.net/docs/domains/\n    baseURL: https://api.gandi.net/v5/domain\n    tags:\n      - Domains\n \
  \     - Domain Registrar\n    properties:\n      - type: Documentation\n        url: https://api.gandi.net/docs/domains/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/gandi/refs/heads/main/openapi/domains-openapi-original.yml\n  - aid: gandi:livedns\n    name: Gandi LiveDNS API\n    description: >-\n      The Gandi LiveDNS API provides DNS management capabilities for domains\n      managed by Gandi, including DNS records, DNSSEC, zone transfers, and\n      TSIG keys.\n    humanURL: https://api.gandi.net/docs/livedns/\n    baseURL: https://api.gandi.net/v5/livedns\n    tags:\n      - DNS\n      - Domains\n    properties:\n      - type: Documentation\n        url: https://api.gandi.net/docs/livedns/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/gandi/refs/heads/main/openapi/livedns-openapi-original.yml\n  - aid: gandi:certificate\n    name: Gandi Certificate API\n    description: >-\n\
  \      The Gandi Certificate API allows you to manage SSL/TLS certificates.\n    humanURL: https://api.gandi.net/docs/certificate/\n    tags:\n      - Certificates\n      - SSL\n    properties:\n      - type: Documentation\n        url: https://api.gandi.net/docs/certificate/\n  - aid: gandi:email\n    name: Gandi Email API\n    description: >-\n      The Gandi Email API allows you to manage email accounts and mailboxes.\n    humanURL: https://api.gandi.net/docs/email/\n    tags:\n      - Email\n    properties:\n      - type: Documentation\n        url: https://api.gandi.net/docs/email/\n  - aid: gandi:billing\n    name: Gandi Billing API\n    description: >-\n      The Gandi Billing API allows you to manage account billing information.\n    humanURL: https://api.gandi.net/docs/billing/\n    tags:\n      - Billing\n    properties:\n      - type: Documentation\n        url: https://api.gandi.net/docs/billing/\n  - aid: gandi:organization\n    name: Gandi Organization API\n    description:\
  \ >-\n      The Gandi Organization API allows you to manage organizations and users.\n    humanURL: https://api.gandi.net/docs/organization/\n    tags:\n      - Organization\n      - Users\n    properties:\n      - type: Documentation\n        url: https://api.gandi.net/docs/organization/\n  - aid: gandi:simplehosting\n    name: Gandi Web Hosting API\n    description: >-\n      The Gandi Web Hosting API allows you to manage Simple Hosting instances.\n    humanURL: https://api.gandi.net/docs/simplehosting/\n    tags:\n      - Hosting\n    properties:\n      - type: Documentation\n        url: https://api.gandi.net/docs/simplehosting/\n  - aid: gandi:gandicloud\n    name: Gandi Cloud VPS API\n    description: >-\n      The GandiCloud VPS API allows you to manage virtual private servers.\n    humanURL: https://api.gandi.net/docs/gandicloud/\n    tags:\n      - Cloud\n      - VPS\n    properties:\n      - type: Documentation\n        url: https://api.gandi.net/docs/gandicloud/\ncommon:\n \
  \ - type: Website\n    url: https://www.gandi.net/\n  - type: Documentation\n    url: https://api.gandi.net/docs/reference/\n  - type: Sandbox\n    url: https://api.sandbox.gandi.net/docs/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/gandi/refs/heads/main/apis.yml
tags:
- DNS
- Domains
- Domain Registrar
- Email
- Hosting
- Certificates
url: https://raw.githubusercontent.com/api-evangelist/gandi/refs/heads/main/apis.yml
use_cases: []
---
