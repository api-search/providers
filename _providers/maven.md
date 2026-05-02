---
api_count: 2
api_specs:
- filename: maven-search-openapi.yml
  format: yaml
  label: Maven Central Search API
  slug: maven-central-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/maven/refs/heads/main/openapi/maven-search-openapi.yml
- filename: maven-portal-openapi.yml
  format: yaml
  label: Maven Central Portal Publishing API
  slug: maven-central-portal-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/maven/refs/heads/main/openapi/maven-portal-openapi.yml
apis:
- description: REST API for searching and retrieving artifact metadata from Maven Central Repository. Supports Solr-based queries for finding Java libraries and their versions.
  name: Maven Central Search API
  slug: maven-central-search-api
- description: API for publishing artifacts to Maven Central through the Sonatype Central Portal. Supports automated deployment of Java libraries and other JVM-based artifacts.
  name: Maven Central Portal Publishing API
  slug: maven-central-portal-api
common:
- title: ''
  type: Website
  url: https://maven.apache.org
- title: ''
  type: Documentation
  url: https://maven.apache.org/guides/
- title: ''
  type: GitHub Organization
  url: https://github.com/apache/maven
- title: ''
  type: Support
  url: https://maven.apache.org/mailing-lists.html
created: '2024-01-01'
description: Apache Maven is a software project management and build automation tool used primarily for Java projects. Maven Central is the default artifact repository for Maven, and Sonatype provides REST APIs for searching and publishing artifacts to Maven Central.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Maven
skills: []
slug: maven
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: maven\nname: Maven\ndescription: >-\n  Apache Maven is a software project management and build automation tool used\n  primarily for Java projects. Maven Central is the default artifact repository\n  for Maven, and Sonatype provides REST APIs for searching and publishing\n  artifacts to Maven Central.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/maven/refs/heads/main/apis.yml\ntags:\n  - Artifacts\n  - Build Tools\n  - Java\n  - Maven\n  - Package Management\n  - Repository\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: maven:maven-central-search-api\n    name: Maven Central Search API\n    description: >-\n      REST API for searching and retrieving artifact metadata from Maven\n      Central Repository. Supports Solr-based queries for finding Java\n      libraries and their versions.\n    humanURL: https://central.sonatype.com/\n\
  \    baseURL: https://search.maven.org/solrsearch\n    tags:\n      - Artifacts\n      - Java\n      - Search\n    properties:\n      - type: Documentation\n        url: https://central.sonatype.org/search/rest-api-guide/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/maven/refs/heads/main/openapi/maven-search-openapi.yml\n  - aid: maven:maven-central-portal-api\n    name: Maven Central Portal Publishing API\n    description: >-\n      API for publishing artifacts to Maven Central through the Sonatype\n      Central Portal. Supports automated deployment of Java libraries and\n      other JVM-based artifacts.\n    humanURL: https://central.sonatype.com/\n    baseURL: https://central.sonatype.com/api/v1\n    tags:\n      - Deployment\n      - Publishing\n      - Upload\n    properties:\n      - type: Documentation\n        url: https://central.sonatype.org/publish/publish-portal-api/\n      - type: Authentication\n        url: https://central.sonatype.org/publish/generate-token/\n\
  \      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/maven/refs/heads/main/openapi/maven-portal-openapi.yml\ncommon:\n  - type: Website\n    url: https://maven.apache.org\n  - type: Documentation\n    url: https://maven.apache.org/guides/\n  - type: GitHub Organization\n    url: https://github.com/apache/maven\n  - type: Support\n    url: https://maven.apache.org/mailing-lists.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/maven/refs/heads/main/apis.yml
tags:
- Artifacts
- Build Tools
- Java
- Maven
- Package Management
- Repository
url: https://raw.githubusercontent.com/api-evangelist/maven/refs/heads/main/apis.yml
use_cases: []
---
