---
api_count: 1
api_specs:
- filename: amazon-elastic-beanstalk-openapi.yml
  format: yaml
  label: AWS Elastic Beanstalk API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-elastic-beanstalk/refs/heads/main/openapi/amazon-elastic-beanstalk-openapi.yml
apis:
- description: API for managing AWS Elastic Beanstalk applications, environments, and related resources including configuration templates and application versions.
  name: AWS Elastic Beanstalk API
  slug: ''
capabilities:
- description: Unified capability for managing Amazon Elastic Beanstalk resources. Combines Amazon Elastic Beanstalk APIs for Application Developer workflows in Application Deployment.
  name: Amazon Elastic Beanstalk Management
  slug: amazon-elastic-beanstalk-capability
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/elasticbeanstalk/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/elasticbeanstalk/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/elasticbeanstalk/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Login
  url: https://signin.aws.amazon.com/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/elasticbeanstalk/faqs/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: Security
  url: https://aws.amazon.com/security/
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/elasticbeanstalk
- title: ''
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-elastic-beanstalk-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-elastic-beanstalk-capability.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/api.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-elastic-beanstalk-vocabulary.yaml
created: '2024-01-15'
description: AWS Elastic Beanstalk is a platform-as-a-service (PaaS) that makes it easy to deploy, manage, and scale web applications and services. You simply upload your code and Elastic Beanstalk automatically handles the deployment, capacity provisioning, load balancing, auto-scaling, and application health monitoring.
features:
- description: Upload code and Elastic Beanstalk handles deployment automatically
  name: Automatic Deployment
- description: Automatically scale capacity up and down based on application needs
  name: Auto Scaling
- description: Monitor application health and performance with built-in dashboards
  name: Health Monitoring
- description: Support for Java, .NET, PHP, Node.js, Python, Ruby, Go, and Docker
  name: Multi-Language Support
- description: Manage multiple deployment environments (development, staging, production)
  name: Environment Management
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Runs application environments on EC2 instances
  name: Amazon EC2
- description: Provision and manage RDS databases alongside environments
  name: Amazon RDS
- description: Store application versions and deployment artifacts
  name: Amazon S3
- description: Manage environment infrastructure as code
  name: AWS CloudFormation
- description: Integrate with CI/CD pipelines for automated deployments
  name: AWS CodePipeline
jsonld:
- class_count: 0
  name: Amazon Elastic Beanstalk Context
  property_count: 3
  slug: amazon-elastic-beanstalk-context
layout: provider
modified: '2026-04-19'
name: Amazon Elastic Beanstalk
rules:
- name: Amazon Elastic Beanstalk API Rules
  rule_count: 20
  severity_counts:
    error: 10
    hint: 0
    info: 1
    warn: 9
  slug: amazon-elastic-beanstalk-spectral-rules
skills: []
slug: amazon-elastic-beanstalk
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Elastic Beanstalk\ndescription: AWS Elastic Beanstalk is a platform-as-a-service (PaaS) that makes it easy to deploy, manage, and scale web applications and services. You simply upload your code and Elastic Beanstalk \n  automatically handles the deployment, capacity provisioning, load balancing, auto-scaling, and application health monitoring.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/elasticbeanstalk/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n- Amazon Web Services\n- AWS\n- Auto Scaling\n- Deployment\n- Elastic Beanstalk\n- PaaS\n- Platform As A Service\n- Web Applications\napis:\n- name: AWS Elastic Beanstalk API\n  description: API for managing AWS Elastic Beanstalk applications, environments, and related resources including configuration templates and application versions.\n  humanURL: https://aws.amazon.com/elasticbeanstalk/\n  baseURL: https://elasticbeanstalk.amazonaws.com\n\
  \  tags:\n  - Auto Scaling\n  - Deployment\n  - PaaS\n  - Web Applications\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/\n  - type: OpenAPI\n    url: openapi/amazon-elastic-beanstalk-openapi.yml\n  - type: APIReference\n    url: https://docs.aws.amazon.com/elasticbeanstalk/latest/api/\n  - type: GettingStarted\n    url: https://aws.amazon.com/elasticbeanstalk/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/elasticbeanstalk/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/elasticbeanstalk/faqs/\n  - type: JSONSchema\n    url: json-schema/amazon-elastic-beanstalk-application-description-message-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-elastic-beanstalk-application-description-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-elastic-beanstalk-application-descriptions-message-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-elastic-beanstalk-context.jsonld\ncommon:\n\
  - type: Portal\n  url: https://aws.amazon.com/\n- type: DeveloperPortal\n  url: https://aws.amazon.com/elasticbeanstalk/\n- type: Documentation\n  url: https://docs.aws.amazon.com/elasticbeanstalk/\n- type: Blog\n  url: https://aws.amazon.com/blogs/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/elasticbeanstalk/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Support\n  url: https://aws.amazon.com/support/\n- type: FAQ\n  url: https://aws.amazon.com/elasticbeanstalk/faqs/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Security\n  url: https://aws.amazon.com/security/\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n\
  - type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/elasticbeanstalk\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-elastic-beanstalk-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-elastic-beanstalk-capability.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/api.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-elastic-beanstalk-vocabulary.yaml\n- type: Features\n  data:\n  - name: Automatic Deployment\n    description: Upload code and Elastic Beanstalk handles deployment automatically\n  - name: Auto Scaling\n    description: Automatically scale capacity up and down based on application needs\n  - name: Health Monitoring\n    description: Monitor application health and performance with built-in dashboards\n  - name: Multi-Language Support\n    description: Support for Java, .NET, PHP, Node.js, Python,\
  \ Ruby, Go, and Docker\n  - name: Environment Management\n    description: Manage multiple deployment environments (development, staging, production)\n- type: UseCases\n  data:\n  - name: Web Application Hosting\n    description: Deploy and host web applications without managing infrastructure\n  - name: API Backend Deployment\n    description: Deploy REST API backends with automatic scaling and load balancing\n  - name: Microservices Deployment\n    description: Deploy containerized microservices using Docker or multi-container configurations\n  - name: Blue-Green Deployments\n    description: Perform zero-downtime deployments using environment URL swapping\n- type: Integrations\n  data:\n  - name: Amazon EC2\n    description: Runs application environments on EC2 instances\n  - name: Amazon RDS\n    description: Provision and manage RDS databases alongside environments\n  - name: Amazon S3\n    description: Store application versions and deployment artifacts\n  - name: AWS CloudFormation\n\
  \    description: Manage environment infrastructure as code\n  - name: AWS CodePipeline\n    description: Integrate with CI/CD pipelines for automated deployments\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-elastic-beanstalk/refs/heads/main/apis.yml
tags:
- Amazon Web Services
- Auto Scaling
- Deployment
- Elastic Beanstalk
- PaaS
- Platform As A Service
- Web Applications
url: https://aws.amazon.com/elasticbeanstalk/
use_cases:
- description: Deploy and host web applications without managing infrastructure
  name: Web Application Hosting
- description: Deploy REST API backends with automatic scaling and load balancing
  name: API Backend Deployment
- description: Deploy containerized microservices using Docker or multi-container configurations
  name: Microservices Deployment
- description: Perform zero-downtime deployments using environment URL swapping
  name: Blue-Green Deployments
---
