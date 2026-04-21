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
