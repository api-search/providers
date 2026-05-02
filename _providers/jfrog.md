---
api_count: 15
api_specs:
- filename: jfrog-artifactory-openapi.yml
  format: yaml
  label: JFrog Artifactory REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-artifactory-openapi.yml
- filename: jfrog-artifactory-openapi.yml
  format: yaml
  label: JFrog Artifactory REST API V2
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-artifactory-openapi.yml
- filename: jfrog-xray-openapi.yml
  format: yaml
  label: JFrog Xray REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-xray-openapi.yml
- filename: jfrog-distribution-openapi.yml
  format: yaml
  label: JFrog Distribution REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-distribution-openapi.yml
- filename: jfrog-pipelines-openapi.yml
  format: yaml
  label: JFrog Pipelines REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-pipelines-openapi.yml
- filename: jfrog-platform-openapi.yml
  format: yaml
  label: JFrog Platform REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-platform-openapi.yml
- filename: jfrog-access-openapi.yml
  format: yaml
  label: JFrog Access REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-access-openapi.yml
- filename: jfrog-curation-openapi.yml
  format: yaml
  label: JFrog Curation REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-curation-openapi.yml
- filename: jfrog-mission-control-openapi.yml
  format: yaml
  label: JFrog Mission Control REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-mission-control-openapi.yml
- filename: jfrog-release-lifecycle-openapi.yml
  format: yaml
  label: JFrog Release Lifecycle Management REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-release-lifecycle-openapi.yml
- filename: jfrog-workers-openapi.yml
  format: yaml
  label: JFrog Workers REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-workers-openapi.yml
- filename: jfrog-ml-openapi.yml
  format: yaml
  label: JFrog ML REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-ml-openapi.yml
- filename: jfrog-connect-openapi.yml
  format: yaml
  label: JFrog Connect REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-connect-openapi.yml
- filename: jfrog-catalog-openapi.yml
  format: yaml
  label: JFrog Catalog REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-catalog-openapi.yml
- filename: jfrog-evidence-openapi.yml
  format: yaml
  label: JFrog Evidence REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/openapi/jfrog-evidence-openapi.yml
apis:
- description: REST API for managing artifacts, repositories, security, and system configuration in JFrog Artifactory. Provides endpoints for uploading, downloading, searching, and managing binary artifacts across a
  name: JFrog Artifactory REST API
  slug: ''
- description: The next generation Artifactory REST API providing improved endpoints for repository management, artifact operations, and system administration with enhanced consistency and functionality.
  name: JFrog Artifactory REST API V2
  slug: ''
- description: API for vulnerability scanning, license compliance, and impact analysis. Provides Software Composition Analysis capabilities tightly integrated with Artifactory to ensure security and compliance gover
  name: JFrog Xray REST API
  slug: ''
- description: API for distributing release binaries to multiple remote locations. Enables secure, reliable distribution of release bundles across edge nodes and remote sites at scale.
  name: JFrog Distribution REST API
  slug: ''
- description: API for managing CI/CD pipelines and automation workflows. Provides endpoints for creating, executing, and monitoring pipelines, runs, resources, and pipeline artifacts.
  name: JFrog Pipelines REST API
  slug: ''
- description: Unified API for JFrog Platform services and administration. Provides centralized endpoints for managing platform-wide configuration, system health, licenses, and cross-service operations.
  name: JFrog Platform REST API
  slug: ''
- description: API for managing users, groups, permissions, projects, and access tokens across the JFrog Platform. Handles identity management, role-based access control, and scoped token creation.
  name: JFrog Access REST API
  slug: ''
- description: API for managing package curation policies that automatically vet and block malicious, vulnerable, or risky open-source packages before they enter the development environment.
  name: JFrog Curation REST API
  slug: ''
- description: API for centralized management and monitoring of multiple JFrog Platform instances, including Artifactory servers, configurations, and cross-instance operations.
  name: JFrog Mission Control REST API
  slug: ''
- description: API for managing release bundles, promotion workflows, and evidence collection throughout the software release lifecycle from development to production.
  name: JFrog Release Lifecycle Management REST API
  slug: ''
- description: API for creating and managing custom serverless workers that extend JFrog Platform functionality through synchronized hooks and automation in a secure, isolated execution environment.
  name: JFrog Workers REST API
  slug: ''
- description: API for managing machine learning models, experiments, and deployments including model registry, versioning, and serving capabilities.
  name: JFrog ML REST API
  slug: ''
- description: API for managing IoT and edge devices, deploying over-the-air software updates, and monitoring device fleets at scale.
  name: JFrog Connect REST API
  slug: ''
- description: API for querying and managing package metadata, searching for packages and CVEs, and managing custom labels for software components through a GraphQL-based interface.
  name: JFrog Catalog REST API
  slug: ''
- description: API for creating and attaching cryptographically signed evidence to artifacts, builds, packages, and release bundles, enabling supply chain verification and compliance attestation throughout the softw
  name: JFrog Evidence REST API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://jfrog.com/developers/
- title: ''
  type: Documentation
  url: https://jfrog.com/help/r/jfrog-rest-apis/jfrog-rest-apis
- title: ''
  type: Getting Started
  url: https://jfrog.com/artifactory/getting-started/
- title: ''
  type: Authentication
  url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens
- title: ''
  type: Blog
  url: https://jfrog.com/blog/
- title: ''
  type: Status
  url: https://status.jfrog.io/
- title: ''
  type: Support
  url: https://jfrog.com/support/
- title: ''
  type: Terms of Service
  url: https://jfrog.com/terms-of-service/
- title: ''
  type: Privacy Policy
  url: https://jfrog.com/privacy-policy/
- title: ''
  type: GitHub Organization
  url: https://github.com/jfrog
- title: ''
  type: Community
  url: https://jfrog.com/community/
- title: ''
  type: Website
  url: https://jfrog.com/
- title: ''
  type: Login
  url: https://my.jfrog.com/login/
- title: ''
  type: Sign Up
  url: https://jfrog.com/start-free/
- title: ''
  type: Pricing
  url: https://jfrog.com/pricing/
- title: ''
  type: CLI
  url: https://jfrog.com/getcli/
- title: ''
  type: Change Log
  url: https://jfrog.com/help/r/jfrog-release-information/jfrog-release-notes
- title: ''
  type: SDKs
  url: https://github.com/jfrog/jfrog-client-go
- title: ''
  type: Java SDK
  url: https://github.com/jfrog/artifactory-client-java
- title: ''
  type: JavaScript SDK
  url: https://github.com/jfrog/jfrog-client-js
- title: ''
  type: Academy
  url: https://academy.jfrog.com/
- title: ''
  type: Webhooks
  url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/webhooks
- title: ''
  type: Terraform Provider
  url: https://registry.terraform.io/providers/jfrog/platform/latest/docs
- title: ''
  type: YouTube
  url: https://www.youtube.com/@jfrog
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/jfrog
- title: ''
  type: Rate Limits
  url: https://jfrog.com/help/r/jfrog-rest-apis/usage-and-rate-limits
- title: ''
  type: Postman Collection
  url: https://www.postman.com/api-evangelist/jfrog/documentation/zgmorin/jfrog-rest-api
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/jfrog-ltd
- title: ''
  type: JSON-LD Context
  url: json-ld/jfrog-context.jsonld
- title: ''
  type: JSON Schema - Artifact
  url: json-schema/jfrog-artifact-schema.json
- title: ''
  type: JSON Schema - Repository
  url: json-schema/jfrog-repository-schema.json
- title: ''
  type: JSON Schema - Build Info
  url: json-schema/jfrog-build-info-schema.json
- title: ''
  type: JSON Schema - Release Bundle
  url: json-schema/jfrog-release-bundle-schema.json
- title: ''
  type: JSON Schema - Security Vulnerability
  url: json-schema/jfrog-security-vulnerability-schema.json
- title: ''
  type: JSON Schema - User
  url: json-schema/jfrog-user-schema.json
- title: ''
  type: JSON Schema - Permission
  url: json-schema/jfrog-permission-schema.json
- title: ''
  type: JSON Schema - Pipeline
  url: json-schema/jfrog-pipeline-schema.json
- title: ''
  type: JSON Schema - Worker
  url: json-schema/jfrog-worker-schema.json
- title: ''
  type: JSON Schema - Curation Policy
  url: json-schema/jfrog-curation-policy-schema.json
- title: ''
  type: JSON Schema - Evidence
  url: json-schema/jfrog-evidence-schema.json
created: '2024'
description: JFrog provides universal DevOps solutions for software supply chain automation and security, offering a unified platform for managing binaries, securing the software supply chain, and automating DevOps workflows.
features: []
image: https://jfrog.com/brand/jfrog-logo.png
integrations: []
jsonld:
- class_count: 9
  name: Jfrog Context
  property_count: 13
  slug: jfrog-context
layout: provider
modified: '2026-04-28'
name: JFrog
skills: []
slug: jfrog
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "specificationVersion: '0.18'\nname: JFrog\ndescription: JFrog provides universal DevOps solutions for software supply chain automation and security, offering a unified platform for managing binaries, securing the software supply chain, and automating DevOps workflows.\nimage: https://jfrog.com/brand/jfrog-logo.png\nurl: https://jfrog.com\ntags:\n  - Artifactory\n  - CI/CD\n  - Container Registry\n  - DevOps\n  - MLOps\n  - Package Management\n  - Security\n  - Software Supply Chain\ncreated: '2024'\nmodified: '2026-04-28'\napis:\n  - name: JFrog Artifactory REST API\n    description: REST API for managing artifacts, repositories, security, and system configuration in JFrog Artifactory. Provides endpoints for uploading, downloading, searching, and managing binary artifacts across all package types.\n    image: https://jfrog.com/brand/artifactory-logo.png\n    baseURL: https://myserver.jfrog.io/artifactory/api\n    humanURL: https://jfrog.com/artifactory/\n    tags:\n      -\
  \ Artifacts\n      - Binary Management\n      - DevOps\n      - Package Management\n      - Repository Management\n    properties:\n      - type: Documentation\n        url: https://www.jfrog.com/confluence/display/JFROG/Artifactory+REST+API\n      - type: OpenAPI\n        url: openapi/jfrog-artifactory-openapi.yml\n      - type: Authentication\n        url: https://www.jfrog.com/confluence/display/JFROG/Access+Tokens\n      - type: Getting Started\n        url: https://jfrog.com/help/r/jfrog-artifactory-documentation/use-the-rest-api\n      - type: Reference\n        url: https://jfrog.com/help/r/jfrog-rest-apis/artifactory-rest-apis\n  - name: JFrog Artifactory REST API V2\n    description: The next generation Artifactory REST API providing improved endpoints for repository management, artifact operations, and system administration with enhanced consistency and functionality.\n    baseURL: https://myserver.jfrog.io/artifactory/api/v2\n    humanURL: https://jfrog.com/artifactory/\n  \
  \  tags:\n      - API V2\n      - Artifacts\n      - Binary Management\n      - Package Management\n      - Repository Management\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-rest-apis/artifactory-rest-api-v2\n      - type: OpenAPI\n        url: openapi/jfrog-artifactory-openapi.yml\n      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\n  - name: JFrog Xray REST API\n    description: API for vulnerability scanning, license compliance, and impact analysis. Provides Software Composition Analysis capabilities tightly integrated with Artifactory to ensure security and compliance governance.\n    image: https://jfrog.com/brand/xray-logo.png\n    baseURL: https://myserver.jfrog.io/xray/api\n    humanURL: https://jfrog.com/xray/\n    tags:\n      - DevSecOps\n      - License Compliance\n      - Security\n      - Software Composition Analysis\n      - Vulnerability Scanning\n\
  \    properties:\n      - type: Documentation\n        url: https://www.jfrog.com/confluence/display/JFROG/Xray+REST+API\n      - type: OpenAPI\n        url: openapi/jfrog-xray-openapi.yml\n      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\n      - type: Reference\n        url: https://jfrog.com/help/r/xray-rest-apis\n      - type: Getting Started\n        url: https://jfrog.com/help/r/xray-rest-apis/introduction-to-the-xray-rest-apis\n  - name: JFrog Distribution REST API\n    description: API for distributing release binaries to multiple remote locations. Enables secure, reliable distribution of release bundles across edge nodes and remote sites at scale.\n    baseURL: https://myserver.jfrog.io/distribution/api\n    humanURL: https://jfrog.com/distribution/\n    tags:\n      - CDN\n      - Distribution\n      - Edge Nodes\n      - Release Management\n      - Software Distribution\n    properties:\n      - type:\
  \ Documentation\n        url: https://www.jfrog.com/confluence/display/JFROG/Distribution+REST+API\n      - type: OpenAPI\n        url: openapi/jfrog-distribution-openapi.yml\n      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\n      - type: Reference\n        url: https://jfrog.com/help/r/jfrog-rest-apis/distribution-rest-apis\n  - name: JFrog Pipelines REST API\n    description: API for managing CI/CD pipelines and automation workflows. Provides endpoints for creating, executing, and monitoring pipelines, runs, resources, and pipeline artifacts.\n    baseURL: https://myserver.jfrog.io/pipelines/api\n    humanURL: https://jfrog.com/pipelines/\n    tags:\n      - Automation\n      - CI/CD\n      - DevOps\n      - Pipelines\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://www.jfrog.com/confluence/display/JFROG/Pipelines+REST+API\n      - type: OpenAPI\n        url: openapi/jfrog-pipelines-openapi.yml\n\
  \      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\n      - type: Getting Started\n        url: https://jfrog.com/help/r/jfrog-rest-apis/introduction-to-the-pipelines-rest-apis\n      - type: Reference\n        url: https://jfrog.com/help/r/jfrog-rest-apis/pipelines-rest-apis\n  - name: JFrog Platform REST API\n    description: Unified API for JFrog Platform services and administration. Provides centralized endpoints for managing platform-wide configuration, system health, licenses, and cross-service operations.\n    baseURL: https://myserver.jfrog.io/\n    humanURL: https://jfrog.com/platform/\n    tags:\n      - Access Management\n      - Administration\n      - Configuration\n      - Platform\n      - System Health\n    properties:\n      - type: Documentation\n        url: https://www.jfrog.com/confluence/display/JFROG/JFrog+Platform+REST+API\n      - type: OpenAPI\n        url: openapi/jfrog-platform-openapi.yml\n\
  \      - type: Authentication\n        url: https://www.jfrog.com/confluence/display/JFROG/Access+Tokens\n      - type: Getting Started\n        url: https://jfrog.com/help/r/jfrog-rest-apis/introduction-to-the-jfrog-platform-rest-apis\n      - type: Reference\n        url: https://jfrog.com/help/r/jfrog-rest-apis/jfrog-platform-rest-apis\n  - name: JFrog Access REST API\n    description: API for managing users, groups, permissions, projects, and access tokens across the JFrog Platform. Handles identity management, role-based access control, and scoped token creation.\n    baseURL: https://myserver.jfrog.io/access/api\n    humanURL: https://jfrog.com/platform/\n    tags:\n      - Access Management\n      - Authentication\n      - Permissions\n      - Tokens\n      - Users\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-token-rest-api\n      - type: OpenAPI\n        url: openapi/jfrog-access-openapi.yml\n\
  \      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\n      - type: Getting Started\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/introduction-to-access-tokens\n  - name: JFrog Curation REST API\n    description: >-\n      API for managing package curation policies that automatically vet and block\n      malicious, vulnerable, or risky open-source packages before they enter the development\n      environment.\n    baseURL: https://myserver.jfrog.io/curation/api\n    humanURL: https://jfrog.com/curation/\n    tags:\n      - Curation\n      - Open Source\n      - Policy Management\n      - Security\n      - Software Supply Chain\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-rest-apis/jfrog-curation-rest-apis\n      - type: OpenAPI\n        url: openapi/jfrog-curation-openapi.yml\n      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\n\
  \  - name: JFrog Mission Control REST API\n    description: API for centralized management and monitoring of multiple JFrog Platform instances, including Artifactory servers, configurations, and cross-instance operations.\n    baseURL: https://myserver.jfrog.io/mc/api\n    humanURL: https://jfrog.com/platform/\n    tags:\n      - Administration\n      - Mission Control\n      - Monitoring\n      - Multi-Instance Management\n      - Operations\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-rest-apis/mission-control-rest-apis\n      - type: OpenAPI\n        url: openapi/jfrog-mission-control-openapi.yml\n      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\n  - name: JFrog Release Lifecycle Management REST API\n    description: >-\n      API for managing release bundles, promotion workflows, and evidence collection\n      throughout the software release lifecycle from development\
  \ to production.\n    baseURL: https://myserver.jfrog.io/lifecycle/api\n    humanURL: https://jfrog.com/rlm/\n    tags:\n      - Evidence\n      - Lifecycle\n      - Promotion\n      - Release Bundles\n      - Release Management\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-rest-apis/release-lifecycle-management\n      - type: OpenAPI\n        url: openapi/jfrog-release-lifecycle-openapi.yml\n      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\n  - name: JFrog Workers REST API\n    description: >-\n      API for creating and managing custom serverless workers that extend JFrog Platform\n      functionality through synchronized hooks and automation in a secure, isolated\n      execution environment.\n    baseURL: https://myserver.jfrog.io/worker/api\n    humanURL: https://jfrog.com/platform/workers/\n    tags:\n      - Automation\n      - Extensibility\n      - Plugins\n\
  \      - Serverless\n      - Workers\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-rest-apis/workers-rest-apis\n      - type: OpenAPI\n        url: openapi/jfrog-workers-openapi.yml\n      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\n  - name: JFrog ML REST API\n    description: API for managing machine learning models, experiments, and deployments including model registry, versioning, and serving capabilities.\n    baseURL: https://myserver.jfrog.io/ml/api\n    humanURL: https://jfrog.com/jfrog-ml/\n    tags:\n      - AI\n      - Machine Learning\n      - MLOps\n      - Model Management\n      - Model Registry\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-ml-documentation/jfrog-ml-rest-api\n      - type: OpenAPI\n        url: openapi/jfrog-ml-openapi.yml\n      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\n\
  \  - name: JFrog Connect REST API\n    description: API for managing IoT and edge devices, deploying over-the-air software updates, and monitoring device fleets at scale.\n    baseURL: https://api.connect.jfrog.io/v2\n    humanURL: https://jfrog.com/connect/\n    tags:\n      - Device Management\n      - Edge Computing\n      - Fleet Management\n      - IoT\n      - OTA Updates\n    properties:\n      - type: Documentation\n        url: https://docs.connect.jfrog.io/rest-api-v2/connect-api-reference\n      - type: OpenAPI\n        url: openapi/jfrog-connect-openapi.yml\n      - type: Authentication\n        url: https://docs.connect.jfrog.io/developers\n  - name: JFrog Catalog REST API\n    description: API for querying and managing package metadata, searching for packages and CVEs, and managing custom labels for software components through a GraphQL-based interface.\n    baseURL: https://myserver.jfrog.io/catalog/api/v1\n    humanURL: https://jfrog.com/platform/\n    tags:\n      - Catalog\n\
  \      - CVE Search\n      - Package Metadata\n      - Security\n      - Software Supply Chain\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-security-user-guide/products/catalog\n      - type: OpenAPI\n        url: openapi/jfrog-catalog-openapi.yml\n      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\n  - name: JFrog Evidence REST API\n    description: API for creating and attaching cryptographically signed evidence to artifacts, builds, packages, and release bundles, enabling supply chain verification and compliance attestation throughout the software delivery lifecycle.\n    baseURL: https://myserver.jfrog.io/evidence/api\n    humanURL: https://jfrog.com/platform/\n    tags:\n      - Attestation\n      - Compliance\n      - Evidence\n      - Software Supply Chain\n      - Supply Chain Security\n    properties:\n      - type: Documentation\n        url: https://jfrog.com/help/r/jfrog-artifactory-documentation/create-evidence-using-rest-apis\n\
  \      - type: OpenAPI\n        url: openapi/jfrog-evidence-openapi.yml\n      - type: Authentication\n        url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\ncommon:\n  - type: Portal\n    url: https://jfrog.com/developers/\n  - type: Documentation\n    url: https://jfrog.com/help/r/jfrog-rest-apis/jfrog-rest-apis\n  - type: Getting Started\n    url: https://jfrog.com/artifactory/getting-started/\n  - type: Authentication\n    url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens\n  - type: Blog\n    url: https://jfrog.com/blog/\n  - type: Status\n    url: https://status.jfrog.io/\n  - type: Support\n    url: https://jfrog.com/support/\n  - type: Terms of Service\n    url: https://jfrog.com/terms-of-service/\n  - type: Privacy Policy\n    url: https://jfrog.com/privacy-policy/\n  - type: GitHub Organization\n    url: https://github.com/jfrog\n  - type: Community\n    url: https://jfrog.com/community/\n  - type:\
  \ Website\n    url: https://jfrog.com/\n  - type: Login\n    url: https://my.jfrog.com/login/\n  - type: Sign Up\n    url: https://jfrog.com/start-free/\n  - type: Pricing\n    url: https://jfrog.com/pricing/\n  - type: CLI\n    url: https://jfrog.com/getcli/\n  - type: Change Log\n    url: https://jfrog.com/help/r/jfrog-release-information/jfrog-release-notes\n  - type: SDKs\n    url: https://github.com/jfrog/jfrog-client-go\n  - type: Java SDK\n    url: https://github.com/jfrog/artifactory-client-java\n  - type: JavaScript SDK\n    url: https://github.com/jfrog/jfrog-client-js\n  - type: Academy\n    url: https://academy.jfrog.com/\n  - type: Webhooks\n    url: https://jfrog.com/help/r/jfrog-platform-administration-documentation/webhooks\n  - type: Terraform Provider\n    url: https://registry.terraform.io/providers/jfrog/platform/latest/docs\n  - type: YouTube\n    url: https://www.youtube.com/@jfrog\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/jfrog\n\
  \  - type: Rate Limits\n    url: https://jfrog.com/help/r/jfrog-rest-apis/usage-and-rate-limits\n  - type: Postman Collection\n    url: https://www.postman.com/api-evangelist/jfrog/documentation/zgmorin/jfrog-rest-api\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/jfrog-ltd\n  - type: JSON-LD Context\n    url: json-ld/jfrog-context.jsonld\n  - type: JSON Schema - Artifact\n    url: json-schema/jfrog-artifact-schema.json\n  - type: JSON Schema - Repository\n    url: json-schema/jfrog-repository-schema.json\n  - type: JSON Schema - Build Info\n    url: json-schema/jfrog-build-info-schema.json\n  - type: JSON Schema - Release Bundle\n    url: json-schema/jfrog-release-bundle-schema.json\n  - type: JSON Schema - Security Vulnerability\n    url: json-schema/jfrog-security-vulnerability-schema.json\n  - type: JSON Schema - User\n    url: json-schema/jfrog-user-schema.json\n  - type: JSON Schema - Permission\n    url: json-schema/jfrog-permission-schema.json\n  - type: JSON Schema\
  \ - Pipeline\n    url: json-schema/jfrog-pipeline-schema.json\n  - type: JSON Schema - Worker\n    url: json-schema/jfrog-worker-schema.json\n  - type: JSON Schema - Curation Policy\n    url: json-schema/jfrog-curation-policy-schema.json\n  - type: JSON Schema - Evidence\n    url: json-schema/jfrog-evidence-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jfrog/refs/heads/main/apis.yml
tags:
- Artifactory
- CI/CD
- Container Registry
- DevOps
- MLOps
- Package Management
- Security
- Software Supply Chain
url: https://jfrog.com
use_cases: []
---
