---
api_count: 3
apis:
- description: The cPanel User API (UAPI) is the modern HTTP API for performing cPanel-level operations such as managing email accounts, mailboxes, files, databases, FTP accounts, SSL certificates, and DNS zones for
  name: cPanel UAPI
  slug: uapi
- description: The WHM API 1 is the HTTP API for server-wide and reseller-level operations including creating, suspending, and terminating cPanel accounts, managing packages and feature lists, configuring DNS cluste
  name: WHM API 1
  slug: whm-api-1
- description: cPanel API 2 is the legacy XML/JSON API for cPanel-user operations. It remains supported for backward compatibility but has been largely superseded by UAPI; new development should target UAPI where po
  name: cPanel API 2 (Legacy)
  slug: cpanel-api-2
common:
- title: ''
  type: Website
  url: https://cpanel.net/
- title: ''
  type: Documentation
  url: https://api.docs.cpanel.net/
- title: ''
  type: Authentication
  url: https://api.docs.cpanel.net/guides/guide-to-api-authentication/
- title: ''
  type: ChangeLog
  url: https://api.docs.cpanel.net/whm/release-notes/
- title: ''
  type: Forum
  url: https://forums.cpanel.net/
- title: ''
  type: Support
  url: https://support.cpanel.net/
- title: ''
  type: Status
  url: https://status.cpanel.net/
- title: ''
  type: GitHub
  url: https://github.com/CpanelInc
- title: ''
  type: TermsOfService
  url: https://cpanel.net/terms-of-service/
- title: ''
  type: PrivacyPolicy
  url: https://cpanel.net/privacy-policy/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/cpanel
created: '2025-02-09'
description: cPanel is a web-based control panel that provides a graphical interface and automation tools to simplify the management of web hosting services. cPanel exposes a family of HTTP APIs (UAPI, WHM API 1, and the legacy cPanel API 2) for automating account, domain, email, database, DNS, and server-wide operations. APIs accept API tokens or Basic Authentication and return JSON or XML responses.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: cPanel
skills: []
slug: cpanel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cpanel\nname: cPanel\nx-type: company\ndescription: >-\n  cPanel is a web-based control panel that provides a graphical interface and\n  automation tools to simplify the management of web hosting services. cPanel\n  exposes a family of HTTP APIs (UAPI, WHM API 1, and the legacy cPanel API 2)\n  for automating account, domain, email, database, DNS, and server-wide\n  operations. APIs accept API tokens or Basic Authentication and return JSON or\n  XML responses.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/cpanel/refs/heads/main/apis.yml\ntype: Index\naccess: 3rd-Party\nposition: Consuming\ncreated: '2025-02-09'\nmodified: '2026-04-28'\ntags:\n  - Control Panel\n  - DNS\n  - Domains\n  - Email\n  - Hosting\n  - Reseller\n  - Server Administration\n  - Web Hosting\n  - WHM\nspecificationVersion: '0.19'\napis:\n  - aid: cpanel:uapi\n    name: cPanel UAPI\n    description: >-\n    \
  \  The cPanel User API (UAPI) is the modern HTTP API for performing\n      cPanel-level operations such as managing email accounts, mailboxes, files,\n      databases, FTP accounts, SSL certificates, and DNS zones for a single\n      cPanel user. UAPI is the recommended replacement for the legacy cPanel\n      API 2.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://api.docs.cpanel.net/cpanel/introduction/\n    baseURL: https://hostname:2083/execute\n    tags:\n      - Databases\n      - Email\n      - Files\n      - Hosting\n      - REST\n      - UAPI\n    properties:\n      - type: Documentation\n        url: https://api.docs.cpanel.net/cpanel/introduction/\n      - type: GuideToUAPI\n        url: https://api.docs.cpanel.net/guides/guide-to-uapi/\n      - type: AllUAPIFunctions\n        url: https://api.docs.cpanel.net/openapi/cpanel/tag/Email/\n      - type: Authentication\n        url: https://api.docs.cpanel.net/guides/guide-to-api-authentication/\n\
  \    features:\n      - name: Token Authentication\n        description: API tokens scoped per cPanel user.\n      - name: Modular Function Catalog\n        description: Functions grouped into modules such as Email, DNS, Mysql, and Ftp.\n      - name: JSON Responses\n        description: Modern JSON responses with consistent metadata envelope.\n  - aid: cpanel:whm-api-1\n    name: WHM API 1\n    description: >-\n      The WHM API 1 is the HTTP API for server-wide and reseller-level\n      operations including creating, suspending, and terminating cPanel\n      accounts, managing packages and feature lists, configuring DNS clusters,\n      manipulating reseller privileges, and performing system administration.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://api.docs.cpanel.net/whm/introduction/\n    baseURL: https://hostname:2087/json-api\n    tags:\n      - Accounts\n      - Packages\n      - Reseller\n      - Server Administration\n\
  \      - WHM\n    properties:\n      - type: Documentation\n        url: https://api.docs.cpanel.net/whm/introduction/\n      - type: GuideToWHMAPI1\n        url: https://api.docs.cpanel.net/guides/guide-to-whm-api-1/\n      - type: APIReference\n        url: https://api.docs.cpanel.net/openapi/whm/\n      - type: Authentication\n        url: https://api.docs.cpanel.net/guides/guide-to-api-authentication/\n    features:\n      - name: Account Management\n        description: Create, suspend, terminate, modify, and migrate cPanel accounts.\n      - name: Package Management\n        description: Define hosting packages and feature lists.\n      - name: DNS Cluster Operations\n        description: Sync zones across DNS-only servers in a cluster.\n  - aid: cpanel:cpanel-api-2\n    name: cPanel API 2 (Legacy)\n    description: >-\n      cPanel API 2 is the legacy XML/JSON API for cPanel-user operations. It\n      remains supported for backward compatibility but has been largely\n      superseded\
  \ by UAPI; new development should target UAPI where possible.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://api.docs.cpanel.net/cpanel/introduction/\n    baseURL: https://hostname:2083/json-api/cpanel\n    tags:\n      - Legacy\n      - cPanel\n    properties:\n      - type: Documentation\n        url: https://api.docs.cpanel.net/cpanel/introduction/\n      - type: GuideToCPanelAPI2\n        url: https://api.docs.cpanel.net/guides/guide-to-cpanel-api-2/\ncommon:\n  - type: Website\n    url: https://cpanel.net/\n  - type: Documentation\n    url: https://api.docs.cpanel.net/\n  - type: Authentication\n    url: https://api.docs.cpanel.net/guides/guide-to-api-authentication/\n  - type: ChangeLog\n    url: https://api.docs.cpanel.net/whm/release-notes/\n  - type: Forum\n    url: https://forums.cpanel.net/\n  - type: Support\n    url: https://support.cpanel.net/\n  - type: Status\n    url: https://status.cpanel.net/\n  - type: GitHub\n\
  \    url: https://github.com/CpanelInc\n  - type: TermsOfService\n    url: https://cpanel.net/terms-of-service/\n  - type: PrivacyPolicy\n    url: https://cpanel.net/privacy-policy/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/cpanel\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cpanel/refs/heads/main/apis.yml
tags:
- Control Panel
- DNS
- Domains
- Email
- Hosting
- Reseller
- Server Administration
- Web Hosting
- WHM
url: https://raw.githubusercontent.com/api-evangelist/cpanel/refs/heads/main/apis.yml
use_cases: []
---
