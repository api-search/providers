---
api_count: 1
api_specs:
- filename: amazon-amplify-openapi.yaml
  format: yaml
  label: Amazon Amplify REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-amplify/refs/heads/main/openapi/amazon-amplify-openapi.yaml
apis:
- description: RESTful API for AWS Amplify enabling management of apps, branches, domain associations, backend environments, and deployments for full-stack web and mobile applications.
  name: Amazon Amplify REST API
  slug: ''
capabilities:
- description: Workflow capability for managing full-stack Amplify applications including app creation, branch management, and deployment workflows.
  name: Amazon Amplify App Management
  slug: amplify-app-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/amplify/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/amplify/
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
  type: Blog
  url: https://aws.amazon.com/blogs/mobile/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws-amplify
- title: ''
  type: Console
  url: https://console.aws.amazon.com/amplify/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/aws-amplify
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-amplify-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amplify-app-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-amplify-vocabulary.yaml
created: '2024-01-15'
description: AWS Amplify is a set of tools and services for building secure, scalable full-stack applications powered by AWS. It provides frontend and mobile developers with a complete workflow for building, deploying, and hosting cloud-powered applications.
features:
- description: Create, update, and delete Amplify apps connected to Git repositories with automated build and deployment settings.
  name: App Management
- description: Manage feature branches and environments with independent build configurations, environment variables, and preview URLs.
  name: Branch Management
- description: Trigger and monitor deployments across branches with build history, logs, and status tracking.
  name: Deployment Automation
- description: Associate custom domains with Amplify apps and manage SSL certificates and subdomain routing configurations.
  name: Domain Association
- description: Manage AWS backend environments linked to Amplify applications for full-stack cloud resource provisioning.
  name: Backend Environment Management
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Connect Amplify apps to AWS CodeCommit repositories for source code hosting and automated deployments.
  name: AWS CodeCommit
- description: Link Amplify deployments to GitHub repositories with automatic builds triggered on pull requests and branch merges.
  name: GitHub
- description: Amplify hosting uses CloudFront for global CDN distribution of static assets and dynamic content.
  name: AWS CloudFront
- description: Configure custom domains for Amplify apps using Route 53 DNS management and SSL certificate provisioning.
  name: AWS Route 53
jsonld:
- class_count: 0
  name: Amazon Amplify Context
  property_count: 10
  slug: amazon-amplify-context
layout: provider
modified: '2026-04-19'
name: Amazon Amplify
rules:
- name: Amazon Amplify API Rules
  rule_count: 5
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 0
  slug: amazon-amplify-spectral-rules
skills: []
slug: amazon-amplify
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-amplify\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-amplify/refs/heads/main/apis.yml\nname: Amazon Amplify\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: AWS Amplify is a set of tools and services for building secure, scalable full-stack applications powered by AWS. It provides frontend and mobile developers with a complete workflow for \n  building, deploying, and hosting cloud-powered applications.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon Amplify REST API\n  description: RESTful API for AWS Amplify enabling management of apps, branches, domain associations, backend environments, and deployments for full-stack web and mobile applications.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/amplify/\n  baseURL: https://amplify.amazonaws.com\n  tags:\n\
  \  - AWS\n  - Frontend\n  - Full Stack\n  - Mobile Development\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/amplify/latest/APIReference/\n  - type: OpenAPI\n    url: openapi/amazon-amplify-openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-amplify-app-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-amplify-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/amplify/pricing/\n  - type: Getting Started\n    url: https://aws.amazon.com/amplify/getting-started/\n  - type: Authentication\n    url: https://docs.aws.amazon.com/amplify/latest/APIReference/Welcome.html\n  - type: SDKs\n    url: https://aws.amazon.com/tools/\n  - type: FAQ\n    url: https://aws.amazon.com/amplify/faqs/\n  - type: User Guide\n    url: https://docs.aws.amazon.com/amplify/latest/userguide/welcome.html\n  - type: API Reference\n    url: https://docs.aws.amazon.com/amplify/latest/APIReference/Welcome.html\n  - type: Service Level Agreement\n    url:\
  \ https://aws.amazon.com/amplify/sla/\n  - type: Status\n    url: https://status.aws.amazon.com/\n  - type: JSONSchema\n    url: json-schema/amazon-amplify-app-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-amplify-branch-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-amplify-createapprequest-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-amplify-createappresult-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-amplify-createbranchrequest-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-amplify-app-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-amplify-branch-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-amplify-createapprequest-structure.json\n  - type: JSONLD\n    url: json-ld/amazon-amplify-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/amplify/\n- type: Documentation\n  url: https://docs.aws.amazon.com/amplify/\n\
  - type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/mobile/\n- type: GitHubOrganization\n  url: https://github.com/aws-amplify\n- type: Console\n  url: https://console.aws.amazon.com/amplify/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/aws-amplify\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-amplify-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amplify-app-management.yaml\n\
  - type: Vocabulary\n  url: vocabulary/amazon-amplify-vocabulary.yaml\n- type: Features\n  data:\n  - name: App Management\n    description: Create, update, and delete Amplify apps connected to Git repositories with automated build and deployment settings.\n  - name: Branch Management\n    description: Manage feature branches and environments with independent build configurations, environment variables, and preview URLs.\n  - name: Deployment Automation\n    description: Trigger and monitor deployments across branches with build history, logs, and status tracking.\n  - name: Domain Association\n    description: Associate custom domains with Amplify apps and manage SSL certificates and subdomain routing configurations.\n  - name: Backend Environment Management\n    description: Manage AWS backend environments linked to Amplify applications for full-stack cloud resource provisioning.\n- type: UseCases\n  data:\n  - name: CI/CD Pipeline Automation\n    description: Automate build and deployment\
  \ workflows for frontend apps by programmatically managing Amplify apps and branch deployments.\n  - name: Multi-Environment Management\n    description: Manage development, staging, and production environments as separate branches with independent configurations.\n  - name: Infrastructure as Code\n    description: Provision and configure Amplify hosting environments as part of infrastructure-as-code pipelines using the REST API.\n  - name: Developer Portal Integration\n    description: Integrate Amplify app management into internal developer portals for self-service application deployment and hosting.\n- type: Integrations\n  data:\n  - name: AWS CodeCommit\n    description: Connect Amplify apps to AWS CodeCommit repositories for source code hosting and automated deployments.\n  - name: GitHub\n    description: Link Amplify deployments to GitHub repositories with automatic builds triggered on pull requests and branch merges.\n  - name: AWS CloudFront\n    description: Amplify hosting\
  \ uses CloudFront for global CDN distribution of static assets and dynamic content.\n  - name: AWS Route 53\n    description: Configure custom domains for Amplify apps using Route 53 DNS management and SSL certificate provisioning.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- Frontend\n- Full Stack\n- Hosting\n- Mobile Development\n- Web Applications\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-amplify/refs/heads/main/apis.yml
tags:
- AWS
- Frontend
- Full Stack
- Hosting
- Mobile Development
- Web Applications
url: https://raw.githubusercontent.com/api-evangelist/amazon-amplify/refs/heads/main/apis.yml
use_cases:
- description: Automate build and deployment workflows for frontend apps by programmatically managing Amplify apps and branch deployments.
  name: CI/CD Pipeline Automation
- description: Manage development, staging, and production environments as separate branches with independent configurations.
  name: Multi-Environment Management
- description: Provision and configure Amplify hosting environments as part of infrastructure-as-code pipelines using the REST API.
  name: Infrastructure as Code
- description: Integrate Amplify app management into internal developer portals for self-service application deployment and hosting.
  name: Developer Portal Integration
---
