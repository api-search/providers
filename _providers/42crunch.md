---
api_count: 4
apis:
- description: 'The 42Crunch API Security Audit performs automated static analysis of API definitions (OpenAPI 2, 3.0, 3.1 and GraphQL), running over 200 checks across format validation, data definition quality, and '
  name: 42Crunch API Security Audit
  slug: 42crunch-api-security-audit
- description: 42Crunch API Scan performs dynamic API security testing (DAST) that evaluates runtime API behavior against its OpenAPI specification. It tests how well an API adheres to its contract and identifies vu
  name: 42Crunch API Scan
  slug: 42crunch-api-scan
- description: 42Crunch API Protection deploys an API-native micro firewall (API Firewall) that provides runtime defense against API attacks. The firewall is tailor-made for each API based on its OpenAPI specificati
  name: 42Crunch API Protection
  slug: 42crunch-api-protection
- description: The 42Crunch Scand Manager provides a convenient way to run 42Crunch API Conformance Scans on-premises as Kubernetes Jobs. It manages the full lifecycle of scan jobs including creation, status monitor
  name: 42Crunch API Conformance Scan Jobs Manager
  slug: 42crunch-scand-manager
capabilities:
- description: 'Workflow capability for DevSecOps engineers and security teams running automated API conformance scans on Kubernetes. Combines scan job management and log retrieval into a unified interface for CI/CD '
  name: 42Crunch API Security Scanning
  slug: api-security-scanning
common:
- title: ''
  type: Website
  url: https://42crunch.com/
- title: ''
  type: Documentation
  url: https://docs.42crunch.com/latest/content/home.htm
- title: ''
  type: Blog
  url: https://42crunch.com/blog/
- title: ''
  type: Support
  url: https://support.42crunch.com/hc/en-us
- title: ''
  type: Pricing
  url: https://42crunch.com/pricing/
- title: ''
  type: Tutorials
  url: https://42crunch.com/tutorials/
- title: ''
  type: Webinars
  url: https://42crunch.com/webinars/
- title: ''
  type: Partners
  url: https://42crunch.com/partners/
- title: ''
  type: Login
  url: https://platform.42crunch.com/login
- title: ''
  type: GitHubOrganization
  url: https://github.com/42Crunch
- title: ''
  type: IDESupport
  url: https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi
- title: ''
  type: IDESupport
  url: https://plugins.jetbrains.com/plugin/14837-openapi-swagger-editor
- title: ''
  type: GitHubRepository
  url: https://github.com/42Crunch/vscode-openapi
- title: ''
  type: GitHubRepository
  url: https://github.com/42Crunch/api-security-audit-action
- title: ''
  type: GitHubRepository
  url: https://github.com/42Crunch/api-security-audit-action-freemium
- title: ''
  type: GitHubRepository
  url: https://github.com/42Crunch/api-security-scan-action-freemium
- title: ''
  type: GitHubRepository
  url: https://github.com/42Crunch/cicd-github-actions
- title: ''
  type: GitHubRepository
  url: https://github.com/42Crunch/scand-manager
- title: ''
  type: GitHubRepository
  url: https://github.com/42Crunch/resources
- title: ''
  type: SpectralRules
  url: rules/42crunch-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/42crunch-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/scand-manager.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/api-security-scanning.yaml
- title: ''
  type: JSON-LD
  url: json-ld/42crunch-scand-manager-context.jsonld
created: '2025-01-08'
description: 42Crunch is a leading API security company that specializes in protecting and securing APIs. They provide innovative solutions that help organizations safeguard their sensitive data and critical assets from potential cyber threats. With their comprehensive API security platform, 42Crunch offers a range of services such as API scanning, traffic monitoring, and runtime protection to ensure that APIs are secure and compliant with industry standards. Their platform covers the full API security lifecycle from design and audit through dynamic testing and runtime firewall protection.
features:
- description: Automated static analysis of OpenAPI and GraphQL definitions running over 200 security checks, scoring APIs 0-100 for vulnerability and compliance issues.
  name: API Security Audit
- description: Dynamic API Security Testing that evaluates runtime API behavior against its OpenAPI contract, identifying vulnerabilities that appear only at runtime.
  name: API Scan (DAST)
- description: API-native micro firewall that enforces OpenAPI contract compliance at runtime, blocking malformed requests, unauthorized access, and API attacks.
  name: API Firewall
- description: Identifies and catalogs APIs across environments to provide full visibility into the API attack surface.
  name: API Discovery
- description: GitHub Actions and other CI/CD pipeline integrations for automated security scanning in deployment workflows.
  name: CI/CD Integration
- description: Plugins for VS Code and IntelliJ/JetBrains IDEs that provide real-time OpenAPI editing, validation, and security feedback during API design.
  name: IDE Integration
- description: Enforces security best practices in OpenAPI specifications covering authentication, data validation, input/output schemas, and transport security.
  name: OpenAPI Contract Security
- description: Scand Manager provides a Kubernetes wrapper for running 42Crunch API Scan in containerized environments.
  name: Kubernetes Support
image: /assets/icons/42crunch.png
integrations:
- description: Native GitHub Actions for API Security Audit and API Scan, enabling automated security checks in GitHub CI/CD workflows.
  name: GitHub Actions
- description: OpenAPI extension for Visual Studio Code providing real-time API editing, validation, and security feedback with 42Crunch integration.
  name: VS Code
- description: OpenAPI/Swagger Editor plugin for IntelliJ IDEA and other JetBrains IDEs.
  name: IntelliJ / JetBrains
- description: Scand Manager provides Kubernetes-native deployment of API Scan for containerized API security testing.
  name: Kubernetes
- description: Tekton Pipelines catalog integration for CI/CD security scanning tasks.
  name: Tekton
- description: SonarQube plugin that integrates 42Crunch API security audit results into code quality dashboards.
  name: SonarQube
- description: API Firewall integrates with API gateway infrastructure to enforce contract compliance at the network edge.
  name: API Gateways
- description: Runtime protection events can be forwarded to SIEM and SOC platforms for centralized threat monitoring and alerting.
  name: SIEM / SOC Systems
- description: Data Center App Performance Toolkit support for Atlassian platform integration.
  name: Atlassian
jsonld:
- class_count: 5
  name: 42Crunch Scand Manager Context
  property_count: 8
  slug: 42crunch-scand-manager-context
layout: provider
modified: '2026-04-19'
name: 42Crunch
rules:
- name: 42Crunch API Rules
  rule_count: 43
  severity_counts:
    error: 12
    hint: 0
    info: 10
    warn: 21
  slug: 42crunch-spectral-rules
skills: []
slug: 42crunch
solutions: []
source_yaml: "aid: 42crunch\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/42crunch/refs/heads/main/apis.yml\nname: 42Crunch\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Security\n  - Platform\n  - Scanning\n  - Security\n  - OpenAPI\n  - DevSecOps\ndescription: >-\n  42Crunch is a leading API security company that specializes in protecting and securing\n  APIs. They provide innovative solutions that help organizations safeguard their\n  sensitive data and critical assets from potential cyber threats. With their comprehensive\n  API security platform, 42Crunch offers a range of services such as API scanning,\n  traffic monitoring, and runtime protection to ensure that APIs are secure and compliant\n  with industry standards. Their platform covers the full API security lifecycle from\n  design and audit through dynamic testing and runtime firewall protection.\ncreated: '2025-01-08'\nmodified: '2026-04-19'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: 42crunch:42crunch-api-security-audit\n    name: 42Crunch API Security Audit\n    tags:\n      - API Security\n      - Static Analysis\n      - OpenAPI\n      - Vulnerability Scanning\n    humanURL: https://docs.42crunch.com/latest/content/concepts/api_contract_security_audit.htm\n    properties:\n      - url: https://docs.42crunch.com/latest/content/concepts/api_contract_security_audit.htm\n        type: Documentation\n      - url: https://docs.42crunch.com/latest/content/home.htm\n        type: APIReference\n    description: >-\n      The 42Crunch API Security Audit performs automated static analysis of API\n      definitions (OpenAPI 2, 3.0, 3.1 and GraphQL), running over 200 checks across\n      format validation, data definition quality, and security analysis. APIs are\n      scored 0-100 with recommendations to reach 70+ before runtime protection is\n      applied. Integrates with CI/CD pipelines for continuous monitoring.\n\n  - aid: 42crunch:42crunch-api-scan\n\
  \    name: 42Crunch API Scan\n    tags:\n      - API Security\n      - Dynamic Testing\n      - DAST\n      - Contract Testing\n    humanURL: https://docs.42crunch.com/latest/content/home.htm\n    properties:\n      - url: https://docs.42crunch.com/latest/content/home.htm\n        type: Documentation\n    description: >-\n      42Crunch API Scan performs dynamic API security testing (DAST) that evaluates\n      runtime API behavior against its OpenAPI specification. It tests how well an\n      API adheres to its contract and identifies vulnerabilities that only appear\n      at runtime. Supports integration with CI/CD pipelines and Kubernetes via\n      the scand-manager Kubernetes wrapper.\n\n  - aid: 42crunch:42crunch-api-protection\n    name: 42Crunch API Protection\n    tags:\n      - API Security\n      - Runtime Protection\n      - Firewall\n      - API Gateway\n    humanURL: https://docs.42crunch.com/latest/content/home.htm\n    properties:\n      - url: https://docs.42crunch.com/latest/content/home.htm\n\
  \        type: Documentation\n    description: >-\n      42Crunch API Protection deploys an API-native micro firewall (API Firewall)\n      that provides runtime defense against API attacks. The firewall is tailor-made\n      for each API based on its OpenAPI specification and enforces API contract\n      compliance in real time, blocking malformed requests and unauthorized access.\n\n  - aid: 42crunch:42crunch-scand-manager\n    name: 42Crunch API Conformance Scan Jobs Manager\n    tags:\n      - API Security\n      - Kubernetes\n      - Conformance Scanning\n      - DevSecOps\n    humanURL: https://github.com/42Crunch/scand-manager\n    properties:\n      - url: https://github.com/42Crunch/scand-manager\n        type: Documentation\n      - url: openapi/42crunch-scand-manager.yaml\n        type: OpenAPI\n      - url: json-schema/scand-manager-job-name-schema.json\n        type: JSONSchema\n        title: Job Name Schema\n      - url: json-schema/scand-manager-jobs-schema.json\n     \
  \   type: JSONSchema\n        title: Jobs Schema\n      - url: json-schema/scand-manager-job-spec-schema.json\n        type: JSONSchema\n        title: Job Spec Schema\n      - url: json-schema/scand-manager-job-status-schema.json\n        type: JSONSchema\n        title: Job Status Schema\n      - url: json-schema/scand-manager-error-schema.json\n        type: JSONSchema\n        title: Error Schema\n      - url: json-structure/scand-manager-job-name-structure.json\n        type: JSONStructure\n        title: Job Name Structure\n      - url: json-structure/scand-manager-jobs-structure.json\n        type: JSONStructure\n        title: Jobs Structure\n      - url: json-structure/scand-manager-job-spec-structure.json\n        type: JSONStructure\n        title: Job Spec Structure\n      - url: json-structure/scand-manager-job-status-structure.json\n        type: JSONStructure\n        title: Job Status Structure\n      - url: json-structure/scand-manager-error-structure.json\n        type:\
  \ JSONStructure\n        title: Error Structure\n      - url: examples/scand-manager-job-name-example.json\n        type: Example\n        title: Job Name Example\n      - url: examples/scand-manager-jobs-example.json\n        type: Example\n        title: Jobs Example\n      - url: examples/scand-manager-job-spec-example.json\n        type: Example\n        title: Job Spec Example\n      - url: examples/scand-manager-job-status-example.json\n        type: Example\n        title: Job Status Example\n      - url: examples/scand-manager-error-example.json\n        type: Example\n        title: Error Example\n    description: >-\n      The 42Crunch Scand Manager provides a convenient way to run 42Crunch API\n      Conformance Scans on-premises as Kubernetes Jobs. It manages the full lifecycle\n      of scan jobs including creation, status monitoring, log retrieval, and deletion.\n\ncommon:\n  - type: Website\n    url: https://42crunch.com/\n  - type: Documentation\n    url: https://docs.42crunch.com/latest/content/home.htm\n\
  \  - type: Blog\n    url: https://42crunch.com/blog/\n  - type: Support\n    url: https://support.42crunch.com/hc/en-us\n  - type: Pricing\n    url: https://42crunch.com/pricing/\n  - type: Tutorials\n    url: https://42crunch.com/tutorials/\n  - type: Webinars\n    url: https://42crunch.com/webinars/\n  - type: Partners\n    url: https://42crunch.com/partners/\n  - type: Login\n    url: https://platform.42crunch.com/login\n  - type: GitHubOrganization\n    url: https://github.com/42Crunch\n  - type: IDESupport\n    url: https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi\n  - type: IDESupport\n    url: https://plugins.jetbrains.com/plugin/14837-openapi-swagger-editor\n  - type: GitHubRepository\n    url: https://github.com/42Crunch/vscode-openapi\n  - type: GitHubRepository\n    url: https://github.com/42Crunch/api-security-audit-action\n  - type: GitHubRepository\n    url: https://github.com/42Crunch/api-security-audit-action-freemium\n  - type: GitHubRepository\n\
  \    url: https://github.com/42Crunch/api-security-scan-action-freemium\n  - type: GitHubRepository\n    url: https://github.com/42Crunch/cicd-github-actions\n  - type: GitHubRepository\n    url: https://github.com/42Crunch/scand-manager\n  - type: GitHubRepository\n    url: https://github.com/42Crunch/resources\n  - type: SpectralRules\n    url: rules/42crunch-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/42crunch-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/scand-manager.yaml\n  - type: NaftikoCapability\n    url: capabilities/api-security-scanning.yaml\n  - type: JSON-LD\n    url: json-ld/42crunch-scand-manager-context.jsonld\n  - type: Features\n    data:\n      - name: API Security Audit\n        description: >-\n          Automated static analysis of OpenAPI and GraphQL definitions running\n          over 200 security checks, scoring APIs 0-100 for vulnerability and\n          compliance issues.\n      - name: API Scan (DAST)\n      \
  \  description: >-\n          Dynamic API Security Testing that evaluates runtime API behavior against\n          its OpenAPI contract, identifying vulnerabilities that appear only at runtime.\n      - name: API Firewall\n        description: >-\n          API-native micro firewall that enforces OpenAPI contract compliance at\n          runtime, blocking malformed requests, unauthorized access, and API attacks.\n      - name: API Discovery\n        description: >-\n          Identifies and catalogs APIs across environments to provide full visibility\n          into the API attack surface.\n      - name: CI/CD Integration\n        description: >-\n          GitHub Actions and other CI/CD pipeline integrations for automated security\n          scanning in deployment workflows.\n      - name: IDE Integration\n        description: >-\n          Plugins for VS Code and IntelliJ/JetBrains IDEs that provide real-time\n          OpenAPI editing, validation, and security feedback during API design.\n\
  \      - name: OpenAPI Contract Security\n        description: >-\n          Enforces security best practices in OpenAPI specifications covering\n          authentication, data validation, input/output schemas, and transport security.\n      - name: Kubernetes Support\n        description: >-\n          Scand Manager provides a Kubernetes wrapper for running 42Crunch API Scan\n          in containerized environments.\n  - type: UseCases\n    data:\n      - name: API Security Testing in CI/CD\n        description: >-\n          Embed automated API security scanning into CI/CD pipelines via GitHub Actions\n          to catch vulnerabilities before they reach production.\n      - name: OpenAPI Specification Review\n        description: >-\n          Audit OpenAPI definitions for security flaws, missing authentication,\n          weak data validation, and schema gaps before API deployment.\n      - name: Runtime API Protection\n        description: >-\n          Deploy the API Firewall in\
  \ front of production APIs to enforce contract\n          compliance and block attacks in real time.\n      - name: DevSecOps API Governance\n        description: >-\n          Provide development, security, and operations teams with shared visibility\n          into API security posture throughout the API lifecycle.\n      - name: OWASP API Top 10 Compliance\n        description: >-\n          Systematically identify and remediate OWASP API Security Top 10\n          vulnerabilities in API definitions and runtime behavior.\n      - name: API Security for Financial Services\n        description: >-\n          Address regulatory and compliance requirements for API security in\n          banking, financial services, and insurance sectors.\n      - name: Healthcare API Security\n        description: >-\n          Secure healthcare APIs handling sensitive patient data against\n          unauthorized access and data exposure vulnerabilities.\n  - type: Integrations\n    data:\n      - name:\
  \ GitHub Actions\n        description: >-\n          Native GitHub Actions for API Security Audit and API Scan, enabling\n          automated security checks in GitHub CI/CD workflows.\n      - name: VS Code\n        description: >-\n          OpenAPI extension for Visual Studio Code providing real-time API editing,\n          validation, and security feedback with 42Crunch integration.\n      - name: IntelliJ / JetBrains\n        description: >-\n          OpenAPI/Swagger Editor plugin for IntelliJ IDEA and other JetBrains IDEs.\n      - name: Kubernetes\n        description: >-\n          Scand Manager provides Kubernetes-native deployment of API Scan for\n          containerized API security testing.\n      - name: Tekton\n        description: >-\n          Tekton Pipelines catalog integration for CI/CD security scanning tasks.\n      - name: SonarQube\n        description: >-\n          SonarQube plugin that integrates 42Crunch API security audit results\n          into code quality\
  \ dashboards.\n      - name: API Gateways\n        description: >-\n          API Firewall integrates with API gateway infrastructure to enforce\n          contract compliance at the network edge.\n      - name: SIEM / SOC Systems\n        description: >-\n          Runtime protection events can be forwarded to SIEM and SOC platforms\n          for centralized threat monitoring and alerting.\n      - name: Atlassian\n        description: >-\n          Data Center App Performance Toolkit support for Atlassian platform\n          integration.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/42crunch/refs/heads/main/apis.yml
tags:
- API Security
- Platform
- Scanning
- Security
- OpenAPI
- DevSecOps
url: https://raw.githubusercontent.com/api-evangelist/42crunch/refs/heads/main/apis.yml
use_cases:
- description: Embed automated API security scanning into CI/CD pipelines via GitHub Actions to catch vulnerabilities before they reach production.
  name: API Security Testing in CI/CD
- description: Audit OpenAPI definitions for security flaws, missing authentication, weak data validation, and schema gaps before API deployment.
  name: OpenAPI Specification Review
- description: Deploy the API Firewall in front of production APIs to enforce contract compliance and block attacks in real time.
  name: Runtime API Protection
- description: Provide development, security, and operations teams with shared visibility into API security posture throughout the API lifecycle.
  name: DevSecOps API Governance
- description: Systematically identify and remediate OWASP API Security Top 10 vulnerabilities in API definitions and runtime behavior.
  name: OWASP API Top 10 Compliance
- description: Address regulatory and compliance requirements for API security in banking, financial services, and insurance sectors.
  name: API Security for Financial Services
- description: Secure healthcare APIs handling sensitive patient data against unauthorized access and data exposure vulnerabilities.
  name: Healthcare API Security
---
