---
api_count: 2
apis:
- description: 'GNU Wget is a free command-line utility for non-interactive downloading of files from the web using HTTP, HTTPS, FTP, and FTPS. It supports recursive downloading, resume of aborted downloads, website '
  name: Wget
  slug: wget
- description: GNU Wget2 is the next-generation successor to GNU Wget, built from scratch around libwget. It is multi-threaded, supports HTTP/2, HTTP compression, parallel connections, If-Modified-Since headers, plu
  name: Wget2
  slug: wget2
common:
- title: ''
  type: Website
  url: https://www.gnu.org/software/wget/
- title: ''
  type: Documentation
  url: https://www.gnu.org/software/wget/manual/
- title: ''
  type: Source Code
  url: https://git.savannah.gnu.org/cgit/wget.git
- title: ''
  type: GitHub Organization
  url: https://gitlab.com/gnuwget
- title: ''
  type: Mailing List
  url: https://lists.gnu.org/mailman/listinfo/bug-wget
- title: ''
  type: Bug Tracker
  url: https://savannah.gnu.org/bugs/?group=wget
- title: ''
  type: Download
  url: https://ftp.gnu.org/gnu/wget/
- title: ''
  type: License
  url: https://www.gnu.org/licenses/gpl-3.0.html
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/wget/refs/heads/main/vocabulary/wget-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/wget/refs/heads/main/json-ld/wget-context.jsonld
created: '2026-03-27'
description: GNU Wget is a free, open-source command-line utility for non-interactive downloading of files from the web using HTTP, HTTPS, FTP, and FTPS protocols. It supports recursive downloading, resuming aborted downloads, mirroring websites, proxy support, and can be run from scripts and cron jobs. Wget2 is the next-generation successor, written from scratch with multi-threading, HTTP/2, and a plugin API via libwget.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 48
  name: Wget Context
  property_count: 0
  slug: wget-context
layout: provider
modified: '2026-05-03'
name: Wget
skills: []
slug: wget
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wget\nname: Wget\ndescription: >-\n  GNU Wget is a free, open-source command-line utility for non-interactive downloading\n  of files from the web using HTTP, HTTPS, FTP, and FTPS protocols. It supports recursive\n  downloading, resuming aborted downloads, mirroring websites, proxy support, and can\n  be run from scripts and cron jobs. Wget2 is the next-generation successor, written\n  from scratch with multi-threading, HTTP/2, and a plugin API via libwget.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CLI\n  - Clients\n  - HTTP Client\n  - File Download\n  - Open Source\n  - GNU\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/wget/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: wget:wget\n    name: Wget\n    description: >-\n      GNU Wget is a free command-line utility for non-interactive downloading of files\n      from the\
  \ web using HTTP, HTTPS, FTP, and FTPS. It supports recursive downloading,\n      resume of aborted downloads, website mirroring, HTTP proxies, cookies, and\n      persistent connections.\n    humanURL: https://www.gnu.org/software/wget/\n    baseURL: https://ftp.gnu.org/gnu/wget/\n    tags:\n      - CLI\n      - File Download\n      - HTTP Client\n      - FTP Client\n      - GNU\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://www.gnu.org/software/wget/manual/\n      - type: Getting Started\n        url: https://www.gnu.org/software/wget/manual/wget.html\n      - type: Download\n        url: https://ftp.gnu.org/gnu/wget/\n      - type: Mirror\n        url: http://ftpmirror.gnu.org/wget\n      - type: Source Code\n        url: https://git.savannah.gnu.org/cgit/wget.git\n      - type: Bug Tracker\n        url: https://savannah.gnu.org/bugs/?group=wget\n      - type: Mailing List\n        url: https://lists.gnu.org/mailman/listinfo/bug-wget\n     \
  \ - type: FAQ\n        url: http://wget.addictivecode.org/FrequentlyAskedQuestions\n    contact:\n      - FN: GNU Wget Mailing List\n        email: bug-wget@gnu.org\n\n  - aid: wget:wget2\n    name: Wget2\n    description: >-\n      GNU Wget2 is the next-generation successor to GNU Wget, built from scratch around\n      libwget. It is multi-threaded, supports HTTP/2, HTTP compression, parallel connections,\n      If-Modified-Since headers, plugin APIs, RSS/Atom feed scanning, Sitemap XML support,\n      and Metalink. Libwget is licensed under LGPLv3+ for use as a reusable library.\n    humanURL: https://gitlab.com/gnuwget/wget2\n    baseURL: https://gnuwget.gitlab.io/wget2/\n    tags:\n      - CLI\n      - File Download\n      - HTTP Client\n      - HTTP/2\n      - Multithreaded\n      - Plugin API\n      - GNU\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://gnuwget.gitlab.io/wget2/reference/\n      - type: Source Code\n        url: https://gitlab.com/gnuwget/wget2\n\
  \      - type: GitHub Mirror\n        url: https://github.com/gnuwget/wget2\n      - type: Plugin API\n        url: https://gnuwget.gitlab.io/wget2/reference/group__libwget-plugin.html\n      - type: Releases\n        url: https://gitlab.com/gnuwget/wget2/-/releases\n      - type: Wiki\n        url: https://gitlab.com/gnuwget/wget2/-/wikis/home\n      - type: ChangeLog\n        url: https://fossies.org/linux/wget/ChangeLog\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wget/refs/heads/main/json-schema/wget-download-request-schema.json\n      - type: JSONSchema\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/wget/refs/heads/main/json-schema/wget2-plugin-schema.json\n    contact:\n      - FN: GNU Wget Mailing List\n        email: bug-wget@gnu.org\n\ncommon:\n  - type: Website\n    url: https://www.gnu.org/software/wget/\n  - type: Documentation\n    url: https://www.gnu.org/software/wget/manual/\n  - type:\
  \ Source Code\n    url: https://git.savannah.gnu.org/cgit/wget.git\n  - type: GitHub Organization\n    url: https://gitlab.com/gnuwget\n  - type: Mailing List\n    url: https://lists.gnu.org/mailman/listinfo/bug-wget\n  - type: Bug Tracker\n    url: https://savannah.gnu.org/bugs/?group=wget\n  - type: Download\n    url: https://ftp.gnu.org/gnu/wget/\n  - type: License\n    url: https://www.gnu.org/licenses/gpl-3.0.html\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/wget/refs/heads/main/vocabulary/wget-vocabulary.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/wget/refs/heads/main/json-ld/wget-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wget/refs/heads/main/apis.yml
tags:
- CLI
- Clients
- HTTP Client
- File Download
- Open Source
- GNU
url: https://raw.githubusercontent.com/api-evangelist/wget/refs/heads/main/apis.yml
use_cases: []
---
