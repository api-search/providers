---
api_count: 2
api_specs:
- filename: maven-central-search-openapi.yml
  format: yaml
  label: Maven Central Search API
  slug: maven-central-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/maven-central/refs/heads/main/openapi/maven-central-search-openapi.yml
- filename: maven-central-portal-openapi.yml
  format: yaml
  label: Central Portal Publishing API
  slug: central-portal-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/maven-central/refs/heads/main/openapi/maven-central-portal-openapi.yml
apis:
- description: REST API for searching and retrieving metadata about artifacts in Maven Central. Supports Solr-based queries for finding Java libraries, their versions, and download statistics.
  name: Maven Central Search API
  slug: maven-central-search-api
- description: API for publishing artifacts to Maven Central through the Sonatype Central Portal, supporting automated deployment pipelines.
  name: Central Portal Publishing API
  slug: central-portal-api
common:
- title: ''
  type: Portal
  url: https://central.sonatype.com/
- title: ''
  type: Getting Started
  url: https://central.sonatype.org/publish/publish-guide/
- title: ''
  type: Blog
  url: https://blog.sonatype.com/
- title: ''
  type: Status
  url: https://status.maven.org/
- title: ''
  type: Terms of Service
  url: https://central.sonatype.org/publish/terms/
- title: ''
  type: GitHub Organization
  url: https://github.com/sonatype
- title: ''
  type: Support
  url: https://central.sonatype.org/support/
created: '2024-01-01'
description: Maven Central is the central repository for Java and other JVM-based artifacts, operated by Sonatype. It provides a REST API for searching artifact metadata and a publishing API for deploying open source libraries to the repository.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Maven Central
skills: []
slug: maven-central
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: maven-central\nname: Maven Central\ndescription: >-\n  Maven Central is the central repository for Java and other JVM-based artifacts,\n  operated by Sonatype. It provides a REST API for searching artifact metadata\n  and a publishing API for deploying open source libraries to the repository.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/maven-central/refs/heads/main/apis.yml\ntags:\n  - Artifacts\n  - Java\n  - JVM\n  - Maven\n  - Package Management\n  - Repository\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: maven-central:maven-central-search-api\n    name: Maven Central Search API\n    description: >-\n      REST API for searching and retrieving metadata about artifacts in Maven\n      Central. Supports Solr-based queries for finding Java libraries, their\n      versions, and download statistics.\n    humanURL:\
  \ https://central.sonatype.org/search/\n    baseURL: https://search.maven.org/solrsearch\n    tags:\n      - Artifacts\n      - Metadata\n      - Search\n    properties:\n      - type: Documentation\n        url: https://central.sonatype.org/search/rest-api-guide/\n      - type: Authentication\n        url: https://central.sonatype.org/publish/generate-token/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/maven-central/refs/heads/main/openapi/maven-central-search-openapi.yml\n  - aid: maven-central:central-portal-api\n    name: Central Portal Publishing API\n    description: >-\n      API for publishing artifacts to Maven Central through the Sonatype\n      Central Portal, supporting automated deployment pipelines.\n    humanURL: https://central.sonatype.com/\n    baseURL: https://central.sonatype.com/api/v1\n    tags:\n      - Deployment\n      - Publishing\n      - Upload\n    properties:\n      - type: Documentation\n        url:\
  \ https://central.sonatype.org/publish/publish-portal-api/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/maven-central/refs/heads/main/openapi/maven-central-portal-openapi.yml\ncommon:\n  - type: Portal\n    url: https://central.sonatype.com/\n  - type: Getting Started\n    url: https://central.sonatype.org/publish/publish-guide/\n  - type: Blog\n    url: https://blog.sonatype.com/\n  - type: Status\n    url: https://status.maven.org/\n  - type: Terms of Service\n    url: https://central.sonatype.org/publish/terms/\n  - type: GitHub Organization\n    url: https://github.com/sonatype\n  - type: Support\n    url: https://central.sonatype.org/support/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/maven-central/refs/heads/main/apis.yml
tags:
- Artifacts
- Java
- JVM
- Maven
- Package Management
- Repository
url: https://raw.githubusercontent.com/api-evangelist/maven-central/refs/heads/main/apis.yml
use_cases: []
---
