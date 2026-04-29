---
api_count: 1
apis:
- description: The AWS CodeStar API provides a unified interface for managing software development activities in one place. It enables you to quickly set up continuous delivery toolchains, create and manage projects
  name: AWS CodeStar API
  slug: ''
capabilities:
- description: Workflow capability for managing AWS CodeStar development projects, team collaboration, and user profiles. Used by development team leads and platform administrators to set up CI/CD toolchains and man
  name: Amazon CodeStar Project Management
  slug: project-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/codestar/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/codestar/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/codestar/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-codestar-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/project-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-codestar-vocabulary.yaml
created: '2024-01-15'
description: AWS CodeStar provides a unified user interface enabling you to easily manage your software development activities in one place. With AWS CodeStar, you can set up your entire continuous delivery toolchain in minutes, allowing you to create and manage projects, add team members with role-based access control, and integrate with other AWS developer tools including CodeCommit, CodeBuild, CodeDeploy, and CodePipeline.
features:
- description: Create projects from pre-built templates that automatically provision AWS resources including CodeCommit repositories, CodeBuild build projects, and CodePipeline pipelines.
  name: Project Creation from Templates
- description: Add team members with Owner, Viewer, or Contributor roles, integrating directly with AWS IAM for secure access control.
  name: Team Management with Role-Based Access
- description: Automatically connects CodeCommit, CodeBuild, CodeDeploy, and CodePipeline into a unified continuous delivery pipeline.
  name: Integrated Developer Toolchain
- description: Unified dashboard to view and manage all AWS resources associated with a project.
  name: Project Resource Dashboard
- description: Cross-project user profiles storing display names, email addresses, and SSH public keys.
  name: User Profile Management
- description: Tag projects with key-value pairs for resource organization, cost allocation, and filtering.
  name: Project Tagging
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Source control integration for hosting Git repositories within CodeStar projects.
  name: AWS CodeCommit
- description: Build service integration for compiling source code and running tests in CodeStar projects.
  name: AWS CodeBuild
- description: Deployment automation integration for deploying applications to AWS resources.
  name: AWS CodeDeploy
- description: CI/CD orchestration integration for automating build, test, and deployment pipelines.
  name: AWS CodePipeline
- description: Identity and access management integration for team member authentication and authorization.
  name: AWS IAM
- description: Infrastructure provisioning integration for creating and managing project AWS resources.
  name: AWS CloudFormation
jsonld:
- class_count: 53
  name: Amazon Codestar Context
  property_count: 43
  slug: amazon-codestar-context
layout: provider
modified: '2026-04-19'
name: Amazon CodeStar
rules:
- name: Amazon CodeStar API Rules
  rule_count: 25
  severity_counts:
    error: 10
    hint: 0
    info: 2
    warn: 13
  slug: amazon-codestar-spectral-rules
skills: []
slug: amazon-codestar
solutions: []
source_yaml: "aid: amazon-codestar\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-codestar/refs/heads/main/apis.yml\nname: Amazon CodeStar\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: >-\n  AWS CodeStar provides a unified user interface enabling you to easily manage\n  your software development activities in one place. With AWS CodeStar, you\n  can set up your entire continuous delivery toolchain in minutes, allowing\n  you to create and manage projects, add team members with role-based access\n  control, and integrate with other AWS developer tools including CodeCommit,\n  CodeBuild, CodeDeploy, and CodePipeline.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n  - name: AWS CodeStar API\n    description: >-\n      The AWS CodeStar API provides a unified interface for managing software\n      development activities in one place. It enables you to quickly set up\n    \
  \  continuous delivery toolchains, create and manage projects, add team\n      members with role-based access, and integrate with other AWS developer\n      tools. The API allows you to create projects, manage project resources,\n      list and tag projects, and coordinate team collaboration across your\n      development workflow. Users can also maintain cross-project profiles\n      with display names, email addresses, and SSH public keys.\n    image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n    humanURL: https://aws.amazon.com/codestar/\n    baseURL: https://codestar.amazonaws.com\n    tags:\n      - AWS\n      - Developer Tools\n      - DevOps\n      - Project Management\n      - Team Collaboration\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/codestar/\n      - type: OpenAPI\n        url: openapi/amazon-codestar-openapi.yml\n      - type: Pricing\n        url: https://aws.amazon.com/codestar/pricing/\n \
  \     - type: GettingStarted\n        url: https://aws.amazon.com/codestar/getting-started/\n      - type: FAQ\n        url: https://aws.amazon.com/codestar/faqs/\n      - type: JSONSchema\n        url: json-schema/codestar-openapi-project-schema.json\n      - type: JSONStructure\n        url: json-structure/codestar-openapi-project-structure.json\n      - type: JSON-LD\n        url: json-ld/amazon-codestar-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: Website\n    url: https://aws.amazon.com/codestar/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/codestar/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/codestar/\n  - type: SignUp\n    url: https://signin.aws.amazon.com/signup?request_type=register\n\
  \  - type: Login\n    url: https://aws.amazon.com/console/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-codestar-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/project-management.yaml\n  - type: Vocabulary\n    url: vocabulary/amazon-codestar-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Project Creation from Templates\n        description: Create projects from pre-built templates that automatically provision AWS resources including CodeCommit repositories, CodeBuild build projects, and CodePipeline pipelines.\n      - name: Team Management with Role-Based Access\n        description: Add team members with Owner, Viewer, or Contributor roles, integrating directly with AWS IAM for secure access control.\n      - name: Integrated Developer Toolchain\n        description: Automatically connects CodeCommit, CodeBuild,\
  \ CodeDeploy, and CodePipeline into a unified continuous delivery pipeline.\n      - name: Project Resource Dashboard\n        description: Unified dashboard to view and manage all AWS resources associated with a project.\n      - name: User Profile Management\n        description: Cross-project user profiles storing display names, email addresses, and SSH public keys.\n      - name: Project Tagging\n        description: Tag projects with key-value pairs for resource organization, cost allocation, and filtering.\n  - type: UseCases\n    data:\n      - name: CI/CD Pipeline Setup\n        description: Rapidly provision a complete continuous integration and delivery pipeline for application development teams.\n      - name: Team Onboarding\n        description: Quickly add new developers to project teams with appropriate role-based permissions across all project resources.\n      - name: Multi-Project Management\n        description: Manage multiple software development projects from a single\
  \ interface with centralized team and resource visibility.\n      - name: Developer Collaboration\n        description: Enable distributed development teams to collaborate on AWS-hosted projects with shared toolchains and access controls.\n  - type: Integrations\n    data:\n      - name: AWS CodeCommit\n        description: Source control integration for hosting Git repositories within CodeStar projects.\n      - name: AWS CodeBuild\n        description: Build service integration for compiling source code and running tests in CodeStar projects.\n      - name: AWS CodeDeploy\n        description: Deployment automation integration for deploying applications to AWS resources.\n      - name: AWS CodePipeline\n        description: CI/CD orchestration integration for automating build, test, and deployment pipelines.\n      - name: AWS IAM\n        description: Identity and access management integration for team member authentication and authorization.\n      - name: AWS CloudFormation\n    \
  \    description: Infrastructure provisioning integration for creating and managing project AWS resources.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ntags:\n  - AWS\n  - Developer Tools\n  - DevOps\n  - Project Management\n  - Team Collaboration\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-codestar/refs/heads/main/apis.yml
tags:
- AWS
- Developer Tools
- DevOps
- Project Management
- Team Collaboration
url: https://raw.githubusercontent.com/api-evangelist/amazon-codestar/refs/heads/main/apis.yml
use_cases:
- description: Rapidly provision a complete continuous integration and delivery pipeline for application development teams.
  name: CI/CD Pipeline Setup
- description: Quickly add new developers to project teams with appropriate role-based permissions across all project resources.
  name: Team Onboarding
- description: Manage multiple software development projects from a single interface with centralized team and resource visibility.
  name: Multi-Project Management
- description: Enable distributed development teams to collaborate on AWS-hosted projects with shared toolchains and access controls.
  name: Developer Collaboration
---
