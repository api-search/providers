---
api_count: 4
apis:
- description: Comprehensive REST API for managing artifacts, repositories, users, groups, permissions, replication, security, and system configuration in JFrog Artifactory.
  name: Artifactory REST API
  slug: rest-api
- description: Advanced search API using a SQL-like query language (AQL) for finding artifacts, builds, modules, and entries based on properties, statistics, and metadata.
  name: Artifactory Query Language (AQL) API
  slug: aql-api
- description: Docker Registry v2 API for pushing, pulling, and managing Docker images stored in JFrog Artifactory acting as a Docker registry.
  name: Artifactory Docker Registry API
  slug: docker-registry-api
- description: API for publishing and managing build information from CI/CD systems, enabling traceability between artifact versions and the builds that produced them.
  name: Artifactory Build Integration API
  slug: build-integration-api
common:
- title: Terms of Service
  type: TermsOfService
  url: https://jfrog.com/terms-of-service/
- title: Privacy Policy
  type: PrivacyPolicy
  url: https://jfrog.com/privacy-policy/
- title: Status Page
  type: StatusPage
  url: https://status.jfrog.com/
- title: Pricing
  type: Pricing
  url: https://jfrog.com/pricing/
- title: Blog
  type: Blog
  url: https://jfrog.com/blog/
- title: JFrog GitHub
  type: GitHubOrganization
  url: https://github.com/jfrog
- title: JFrog on X
  type: X
  url: https://twitter.com/jfrog
- title: Support
  type: Support
  url: https://jfrog.com/support/
- title: Developer Portal
  type: Portal
  url: https://jfrog.com/developers/
- title: Documentation
  type: Documentation
  url: https://jfrog.com/help/
- title: Getting Started
  type: GettingStarted
  url: https://jfrog.com/help/r/jfrog-artifactory-documentation/getting-started-with-artifactory
- title: Sign Up Free
  type: SignUp
  url: https://jfrog.com/start-free/
- title: Login
  type: Login
  url: https://my.jfrog.com/login/
- title: JFrog Community
  type: Resources
  url: https://community.jfrog.com/
- title: YouTube
  type: YouTube
  url: https://www.youtube.com/@jfrog
- title: JFrog CLI
  type: CLI
  url: https://jfrog.com/help/r/jfrog-cli/jfrog-cli
- title: Release Notes
  type: ChangeLog
  url: https://jfrog.com/help/r/jfrog-release-information/jfrog-release-notes
created: '2024-01-15'
description: JFrog Artifactory is a universal artifact repository manager supporting all major package formats and build tools including Maven, Gradle, npm, NuGet, PyPI, Docker, Helm, RubyGems, CocoaPods, and more. As the central hub of the JFrog Platform, Artifactory stores, manages, and distributes binary artifacts across the entire software development lifecycle. It integrates with CI/CD pipelines through native plugins for Jenkins, GitHub Actions, CircleCI, and other tools. Artifactory provides comprehensive REST APIs for managing repositories, artifacts, builds, security, and system configuration programmatically.
features:
- description: Single repository manager supporting 30+ package formats including Maven, npm, NuGet, PyPI, Docker, Helm, Conda, Conan, and more.
  name: Universal Package Management
- description: Rich metadata tagging and AQL query language for finding artifacts based on properties, statistics, dates, and custom attributes.
  name: Artifact Metadata and Search
- description: Native CI/CD integration publishing build information to track which artifacts were produced by which build, enabling full artifact traceability.
  name: Build Integration
- description: Fine-grained permission targets, LDAP/SAML/SSO integration, API key management, and access tokens for secure artifact access control.
  name: Security and Permissions
- description: Push and pull replication across multiple Artifactory instances for geo-distributed teams and disaster recovery.
  name: Replication
- description: Full Docker Registry v2 API compliance for pushing, pulling, and managing Docker images with automated vulnerability scanning.
  name: Docker Registry
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Official Jenkins Artifactory Plugin for publishing artifacts and build information from Jenkins pipelines.
  name: Jenkins
- description: JFrog GitHub Actions for integrating Artifactory into GitHub CI/CD workflows.
  name: GitHub Actions
- description: Deep integration with JFrog Xray for continuous security and compliance scanning of artifacts and dependencies.
  name: JFrog Xray
- description: Native integration with JFrog Pipelines for end-to-end CI/CD orchestration using Artifactory as the artifact store.
  name: JFrog Pipelines
layout: provider
modified: '2026-04-19'
name: JFrog Artifactory
skills: []
slug: artifactory
solutions: []
source_yaml: "aid: artifactory\nname: JFrog Artifactory\ndescription: >-\n  JFrog Artifactory is a universal artifact repository manager supporting all\n  major package formats and build tools including Maven, Gradle, npm, NuGet,\n  PyPI, Docker, Helm, RubyGems, CocoaPods, and more. As the central hub of\n  the JFrog Platform, Artifactory stores, manages, and distributes binary\n  artifacts across the entire software development lifecycle. It integrates\n  with CI/CD pipelines through native plugins for Jenkins, GitHub Actions,\n  CircleCI, and other tools. Artifactory provides comprehensive REST APIs for\n  managing repositories, artifacts, builds, security, and system configuration\n  programmatically.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/artifactory/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Artifacts\n\
  \  - DevOps\n  - CI/CD\n  - Docker Registry\n  - Maven\n  - Package Management\n  - Repository\napis:\n  - aid: artifactory:rest-api\n    name: Artifactory REST API\n    description: >-\n      Comprehensive REST API for managing artifacts, repositories, users,\n      groups, permissions, replication, security, and system configuration\n      in JFrog Artifactory.\n    humanURL: https://jfrog.com/help/r/jfrog-rest-apis/artifactory-rest-apis\n    baseURL: https://artifactory.example.com/artifactory/api\n    tags:\n      - Artifacts\n      - Repositories\n      - REST\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-rest-apis/artifactory-rest-apis\n      - type: OpenAPI\n        url: openapi/artifactory-rest-api-openapi.yml\n      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-rest-apis/authentication\n      - type: JSONSchema\n        url: json-schema/artifactory-repository-configuration.json\n      - type: JSONSchema\n     \
  \   url: json-schema/artifactory-file-info.json\n      - type: JSONSchema\n        url: json-schema/artifactory-permission-target.json\n  - aid: artifactory:aql-api\n    name: Artifactory Query Language (AQL) API\n    description: >-\n      Advanced search API using a SQL-like query language (AQL) for finding\n      artifacts, builds, modules, and entries based on properties, statistics,\n      and metadata.\n    humanURL: https://jfrog.com/help/r/jfrog-artifactory-documentation/artifactory-query-language\n    baseURL: https://artifactory.example.com/artifactory/api/search/aql\n    tags:\n      - AQL\n      - Query\n      - Search\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-artifactory-documentation/artifactory-query-language\n      - type: OpenAPI\n        url: openapi/artifactory-aql-api-openapi.yml\n      - type: CodeExamples\n        url: https://jfrog.com/help/r/jfrog-artifactory-documentation/aql-examples\n  - aid: artifactory:docker-registry-api\n\
  \    name: Artifactory Docker Registry API\n    description: >-\n      Docker Registry v2 API for pushing, pulling, and managing Docker images\n      stored in JFrog Artifactory acting as a Docker registry.\n    humanURL: https://jfrog.com/help/r/jfrog-artifactory-documentation/docker-registry\n    baseURL: https://artifactory.example.com/artifactory/api/docker\n    tags:\n      - Docker\n      - Containers\n      - Registry\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-artifactory-documentation/docker-registry\n      - type: OpenAPI\n        url: openapi/artifactory-docker-registry-api-openapi.yml\n  - aid: artifactory:build-integration-api\n    name: Artifactory Build Integration API\n    description: >-\n      API for publishing and managing build information from CI/CD systems,\n      enabling traceability between artifact versions and the builds that\n      produced them.\n    humanURL: https://jfrog.com/help/r/jfrog-rest-apis/builds\n\
  \    baseURL: https://artifactory.example.com/artifactory/api/build\n    tags:\n      - Builds\n      - CI/CD\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-rest-apis/builds\n      - type: OpenAPI\n        url: openapi/artifactory-build-integration-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/artifactory-build-info.json\ncommon:\n  - type: TermsOfService\n    url: https://jfrog.com/terms-of-service/\n    title: Terms of Service\n  - type: PrivacyPolicy\n    url: https://jfrog.com/privacy-policy/\n    title: Privacy Policy\n  - type: StatusPage\n    url: https://status.jfrog.com/\n    title: Status Page\n  - type: Pricing\n    url: https://jfrog.com/pricing/\n    title: Pricing\n  - type: Blog\n    url: https://jfrog.com/blog/\n    title: Blog\n  - type: GitHubOrganization\n    url: https://github.com/jfrog\n    title: JFrog GitHub\n  - type: X\n    url: https://twitter.com/jfrog\n    title: JFrog on\
  \ X\n  - type: Support\n    url: https://jfrog.com/support/\n    title: Support\n  - type: Portal\n    url: https://jfrog.com/developers/\n    title: Developer Portal\n  - type: Documentation\n    url: https://jfrog.com/help/\n    title: Documentation\n  - type: GettingStarted\n    url: https://jfrog.com/help/r/jfrog-artifactory-documentation/getting-started-with-artifactory\n    title: Getting Started\n  - type: SignUp\n    url: https://jfrog.com/start-free/\n    title: Sign Up Free\n  - type: Login\n    url: https://my.jfrog.com/login/\n    title: Login\n  - type: Resources\n    url: https://community.jfrog.com/\n    title: JFrog Community\n  - type: YouTube\n    url: https://www.youtube.com/@jfrog\n    title: YouTube\n  - type: CLI\n    url: https://jfrog.com/help/r/jfrog-cli/jfrog-cli\n    title: JFrog CLI\n  - type: ChangeLog\n    url: https://jfrog.com/help/r/jfrog-release-information/jfrog-release-notes\n    title: Release Notes\n  - type: Features\n    data:\n      - name: Universal\
  \ Package Management\n        description: >-\n          Single repository manager supporting 30+ package formats including\n          Maven, npm, NuGet, PyPI, Docker, Helm, Conda, Conan, and more.\n      - name: Artifact Metadata and Search\n        description: >-\n          Rich metadata tagging and AQL query language for finding artifacts\n          based on properties, statistics, dates, and custom attributes.\n      - name: Build Integration\n        description: >-\n          Native CI/CD integration publishing build information to track\n          which artifacts were produced by which build, enabling full\n          artifact traceability.\n      - name: Security and Permissions\n        description: >-\n          Fine-grained permission targets, LDAP/SAML/SSO integration, API\n          key management, and access tokens for secure artifact access control.\n      - name: Replication\n        description: >-\n          Push and pull replication across multiple Artifactory instances\n\
  \          for geo-distributed teams and disaster recovery.\n      - name: Docker Registry\n        description: >-\n          Full Docker Registry v2 API compliance for pushing, pulling, and\n          managing Docker images with automated vulnerability scanning.\n  - type: UseCases\n    data:\n      - name: CI/CD Pipeline Integration\n        description: >-\n          Development teams integrate Artifactory with Jenkins, GitHub Actions,\n          and other CI/CD tools to store, version, and distribute build artifacts.\n      - name: Container Registry\n        description: >-\n          Platform engineering teams use Artifactory as an enterprise Docker\n          registry with security scanning, access controls, and promotion workflows.\n      - name: Dependency Proxy\n        description: >-\n          Organizations proxy public package registries (npm, PyPI, Maven Central)\n          through Artifactory to cache dependencies, apply security policies,\n          and ensure build reproducibility.\n\
  \      - name: Release Management\n        description: >-\n          Release engineers promote artifacts through staging environments using\n          build promotion, managing the lifecycle from snapshot to release.\n  - type: Integrations\n    data:\n      - name: Jenkins\n        description: >-\n          Official Jenkins Artifactory Plugin for publishing artifacts and\n          build information from Jenkins pipelines.\n      - name: GitHub Actions\n        description: >-\n          JFrog GitHub Actions for integrating Artifactory into GitHub CI/CD workflows.\n      - name: JFrog Xray\n        description: >-\n          Deep integration with JFrog Xray for continuous security and compliance\n          scanning of artifacts and dependencies.\n      - name: JFrog Pipelines\n        description: >-\n          Native integration with JFrog Pipelines for end-to-end CI/CD\n          orchestration using Artifactory as the artifact store.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/artifactory/refs/heads/main/apis.yml
tags:
- Artifacts
- DevOps
- CI/CD
- Docker Registry
- Maven
- Package Management
- Repository
url: https://raw.githubusercontent.com/api-evangelist/artifactory/refs/heads/main/apis.yml
use_cases:
- description: Development teams integrate Artifactory with Jenkins, GitHub Actions, and other CI/CD tools to store, version, and distribute build artifacts.
  name: CI/CD Pipeline Integration
- description: Platform engineering teams use Artifactory as an enterprise Docker registry with security scanning, access controls, and promotion workflows.
  name: Container Registry
- description: Organizations proxy public package registries (npm, PyPI, Maven Central) through Artifactory to cache dependencies, apply security policies, and ensure build reproducibility.
  name: Dependency Proxy
- description: Release engineers promote artifacts through staging environments using build promotion, managing the lifecycle from snapshot to release.
  name: Release Management
---
