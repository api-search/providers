---
api_count: 4
api_specs:
- filename: svn-webdav-openapi.yml
  format: yaml
  label: SVN WebDAV HTTP API
  slug: svn-webdav-http-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/svn/refs/heads/main/openapi/svn-webdav-openapi.yml
apis:
- description: Apache Subversion exposes repository operations over HTTP/HTTPS using the WebDAV/DeltaV protocol via the mod_dav_svn Apache module. Clients use OPTIONS, PROPFIND, GET, PUT, REPORT, MKACTIVITY, CHECKOU
  name: SVN WebDAV HTTP API
  slug: svn-webdav-http-api
- description: The Subversion C library provides the low-level API for building tools and integrations. It includes the libsvn_client, libsvn_ra, libsvn_wc, and libsvn_repos libraries for client operations, reposito
  name: SVN C Library API
  slug: svn-c-api
- description: Python bindings for Subversion C libraries, providing access to client and repository operations via pysvn and the official svn.client Python module.
  name: SVN Python Bindings
  slug: svn-python-bindings
- description: SVNKit is a pure Java Subversion client library providing full access to Subversion repository and working copy data. Used by major IDE plugins including IntelliJ IDEA and Eclipse Subclipse.
  name: SVNKit Java Library
  slug: svn-java-bindings
capabilities:
- description: Unified version control workflow capability for Apache Subversion. Combines repository browsing, file operations, commit lifecycle management, and historical revision access into a single workflow-ori
  name: SVN Version Control
  slug: version-control
common:
- title: ''
  type: Getting Started
  url: https://subversion.apache.org/quick-start
- title: ''
  type: Book
  url: https://svnbook.red-bean.com/
- title: ''
  type: Downloads
  url: https://subversion.apache.org/download/
- title: ''
  type: Security
  url: https://subversion.apache.org/security/
- title: ''
  type: FAQ
  url: https://subversion.apache.org/faq.html
- title: ''
  type: Community
  url: https://subversion.apache.org/mailing-lists.html
- title: ''
  type: GitHub
  url: https://github.com/apache/subversion
- title: ''
  type: License
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Package
  url: https://packages.apache.org/subversion
created: '2024-01-01'
description: Apache Subversion (SVN) is a centralized version control system that tracks changes to files and directories over time. It supports atomic commits, directory versioning, cheap branching and tagging, merge tracking, and binary file handling. SVN is served over HTTP/HTTPS using the WebDAV/DeltaV protocol via mod_dav_svn, or over a custom protocol using svnserve.
features: []
image: https://subversion.apache.org/images/svn-square.jpg
integrations: []
jsonld:
- class_count: 0
  name: Svn Context
  property_count: 26
  slug: svn-context
layout: provider
modified: '2026-05-02'
name: Subversion
rules:
- name: Subversion API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: svn-rules
skills: []
slug: svn
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: svn\nname: Subversion\ndescription: >-\n  Apache Subversion (SVN) is a centralized version control system that tracks\n  changes to files and directories over time. It supports atomic commits, directory\n  versioning, cheap branching and tagging, merge tracking, and binary file handling.\n  SVN is served over HTTP/HTTPS using the WebDAV/DeltaV protocol via mod_dav_svn,\n  or over a custom protocol using svnserve.\ntype: Index\nimage: https://subversion.apache.org/images/svn-square.jpg\ntags:\n  - Apache\n  - Open Source\n  - Repository\n  - Source Control\n  - Svn\n  - Version Control\n  - Webdav\nurl: https://raw.githubusercontent.com/api-evangelist/svn/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: svn:svn-webdav-http-api\n    name: SVN WebDAV HTTP API\n    description: >-\n      Apache Subversion exposes repository operations over HTTP/HTTPS using the\n      WebDAV/DeltaV protocol via the mod_dav_svn\
  \ Apache module. Clients use\n      OPTIONS, PROPFIND, GET, PUT, REPORT, MKACTIVITY, CHECKOUT, MERGE, COPY,\n      DELETE, and PROPPATCH to perform version control operations including\n      checkout, commit, update, log retrieval, and branching.\n    humanURL: https://subversion.apache.org/docs/\n    baseURL: https://svn.example.com/repos/\n    tags:\n      - Deltav\n      - Repository\n      - Version Control\n      - Webdav\n    properties:\n      - type: Documentation\n        url: https://subversion.apache.org/docs/\n        x-type: Documentation\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/svn/refs/heads/main/openapi/svn-webdav-openapi.yml\n        x-type: OpenAPI\n      - type: Book\n        url: https://svnbook.red-bean.com/\n        x-type: Documentation\n      - type: Protocol\n        url: https://svn.apache.org/repos/asf/subversion/trunk/notes/http-and-webdav/webdav-usage.html\n        x-type: Documentation\n    contact:\n      - type:\
  \ Email\n        url: mailto:users@subversion.apache.org\n      - type: Mailing List\n        url: https://subversion.apache.org/mailing-lists.html\n      - type: Issues\n        url: https://issues.apache.org/jira/projects/SVN\n\n  - aid: svn:svn-c-api\n    name: SVN C Library API\n    description: >-\n      The Subversion C library provides the low-level API for building tools and\n      integrations. It includes the libsvn_client, libsvn_ra, libsvn_wc, and\n      libsvn_repos libraries for client operations, repository access, working copy\n      management, and server-side repository access respectively.\n    humanURL: https://subversion.apache.org/docs/api/latest/\n    tags:\n      - C Library\n      - Integration\n      - Library\n    properties:\n      - type: Documentation\n        url: https://subversion.apache.org/docs/api/latest/\n      - type: GitHub Repository\n        url: https://github.com/apache/subversion\n\n  - aid: svn:svn-python-bindings\n    name: SVN Python Bindings\n\
  \    description: >-\n      Python bindings for Subversion C libraries, providing access to client and\n      repository operations via pysvn and the official svn.client Python module.\n    humanURL: https://pysvn.sourceforge.io/\n    tags:\n      - Python\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://pysvn.sourceforge.io/Docs/pysvn_prog_guide.html\n\n  - aid: svn:svn-java-bindings\n    name: SVNKit Java Library\n    description: >-\n      SVNKit is a pure Java Subversion client library providing full access to\n      Subversion repository and working copy data. Used by major IDE plugins\n      including IntelliJ IDEA and Eclipse Subclipse.\n    humanURL: https://svnkit.com/\n    tags:\n      - Java\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://svnkit.com/index.html\n\ncommon:\n  - type: Getting Started\n    url: https://subversion.apache.org/quick-start\n  - type: Book\n    url: https://svnbook.red-bean.com/\n  - type:\
  \ Downloads\n    url: https://subversion.apache.org/download/\n  - type: Security\n    url: https://subversion.apache.org/security/\n  - type: FAQ\n    url: https://subversion.apache.org/faq.html\n  - type: Community\n    url: https://subversion.apache.org/mailing-lists.html\n  - type: GitHub\n    url: https://github.com/apache/subversion\n  - type: License\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Features\n    url: https://subversion.apache.org/features.html\n  - type: Package\n    url: https://packages.apache.org/subversion\n\nmaintainers:\n  - name: Apache Software Foundation\n    email: dev@subversion.apache.org\n    url: https://www.apache.org/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/svn/refs/heads/main/apis.yml
tags:
- Apache
- Open Source
- Repository
- Source Control
- Svn
- Version Control
- Webdav
url: https://raw.githubusercontent.com/api-evangelist/svn/refs/heads/main/apis.yml
use_cases: []
---
