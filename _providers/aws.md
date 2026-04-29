---
api_count: 5
apis:
- description: Scalable virtual servers in the cloud.
  name: Amazon EC2
  slug: amazon-ec2
- description: Scalable object storage service for data backup, archival, and analytics.
  name: Amazon S3
  slug: amazon-s3
- description: Run code without thinking about servers or clusters.
  name: Amazon Lambda
  slug: amazon-lambda
- description: Fast and flexible NoSQL database service for any scale.
  name: Amazon DynamoDB
  slug: amazon-dynamodb
- description: Managed relational database service for MySQL, PostgreSQL, Oracle, SQL Server, and MariaDB.
  name: Amazon RDS
  slug: amazon-rds
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/
- title: ''
  type: Authentication
  url: https://docs.aws.amazon.com/general/latest/gr/signing_aws_api_requests.html
- title: ''
  type: SDK
  url: https://aws.amazon.com/tools/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/pricing/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/
- title: ''
  type: ChangeLog
  url: https://aws.amazon.com/new/
created: '2024-01-01'
description: Amazon Web Services is a comprehensive collection of cloud computing services and APIs provided by Amazon, offering infrastructure as a service, platform as a service, and software as a service solutions globally.
features:
- description: Deploy applications across 30+ AWS Regions and 90+ Availability Zones worldwide.
  name: Global Infrastructure
- description: Pay only for the services you use with no upfront costs or long-term commitments.
  name: Pay-as-you-go Pricing
- description: Built-in security with compliance programs, encryption, IAM, and dedicated security services.
  name: Comprehensive Security
- description: Managed database, compute, storage, and networking services with automatic patching and scaling.
  name: Managed Services
- description: Run code, manage databases, and process streams without managing infrastructure.
  name: Serverless Computing
- description: Pre-built ML services and tools for building, training, and deploying ML models at scale.
  name: Machine Learning
- description: Extend AWS to on-premises with Outposts, Local Zones, and Direct Connect.
  name: Hybrid Cloud
- description: Integrated developer tools for CI/CD, infrastructure as code, and monitoring.
  name: DevOps Toolchain
- description: Build decoupled, event-driven applications with SQS, SNS, EventBridge, and Lambda.
  name: Event-Driven Architecture
- description: Run containers with ECS, EKS, Fargate, and ECR for flexible container workloads.
  name: Container Services
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Manage AWS infrastructure as code using the official AWS Terraform provider.
  name: Terraform
- description: Deploy and manage Kubernetes workloads on AWS using Amazon EKS.
  name: Kubernetes
- description: Automate CI/CD pipelines deploying to AWS using GitHub Actions and OIDC.
  name: GitHub Actions
- description: Monitor AWS infrastructure and applications using the Datadog AWS integration.
  name: Datadog
- description: Integrate data workflows between Snowflake and AWS S3, Glue, and Lake Formation.
  name: Snowflake
layout: provider
modified: '2026-04-19'
name: Amazon Web Services (AWS)
skills: []
slug: aws
solutions: []
source_yaml: "aid: aws\nname: Amazon Web Services (AWS)\ndescription: >-\n  Amazon Web Services is a comprehensive collection of cloud computing services\n  and APIs provided by Amazon, offering infrastructure as a service, platform\n  as a service, and software as a service solutions globally.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Cloud Computing\n- IaaS\n- Infrastructure\n- PaaS\n- Platform as a Service\n- Serverless\nurl: \n  https://raw.githubusercontent.com/api-evangelist/aws/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: aws:amazon-ec2\n  name: Amazon EC2\n  description: Scalable virtual servers in the cloud.\n  humanURL: https://aws.amazon.com/ec2/\n  baseURL: https://ec2.amazonaws.com\n  tags:\n  - Compute\n  - Infrastructure\n  - Virtual Machines\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/ec2/\n  - type: OpenAPI\n\
  \    url: \n      https://api.apis.guru/v2/specs/amazonaws.com/ec2/2016-11-15/openapi.yaml\n- aid: aws:amazon-s3\n  name: Amazon S3\n  description: Scalable object storage service for data backup, archival, and \n    analytics.\n  humanURL: https://aws.amazon.com/s3/\n  baseURL: https://s3.amazonaws.com\n  tags:\n  - Data Lake\n  - Object Storage\n  - Storage\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/s3/\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/s3/2006-03-01/openapi.yaml\n- aid: aws:amazon-lambda\n  name: Amazon Lambda\n  description: Run code without thinking about servers or clusters.\n  humanURL: https://aws.amazon.com/lambda/\n  baseURL: https://lambda.amazonaws.com\n  tags:\n  - Compute\n  - Functions\n  - Serverless\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/lambda/\n  - type: OpenAPI\n    url: \n      https://api.apis.guru/v2/specs/amazonaws.com/lambda/2015-03-31/openapi.yaml\n\
  - aid: aws:amazon-dynamodb\n  name: Amazon DynamoDB\n  description: Fast and flexible NoSQL database service for any scale.\n  humanURL: https://aws.amazon.com/dynamodb/\n  baseURL: https://dynamodb.amazonaws.com\n  tags:\n  - Database\n  - Key-Value\n  - NoSQL\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/dynamodb/\n  - type: OpenAPI\n    url: \n      https://api.apis.guru/v2/specs/amazonaws.com/dynamodb/2012-08-10/openapi.yaml\n- aid: aws:amazon-rds\n  name: Amazon RDS\n  description: >-\n    Managed relational database service for MySQL, PostgreSQL, Oracle, SQL\n    Server, and MariaDB.\n  humanURL: https://aws.amazon.com/rds/\n  baseURL: https://rds.amazonaws.com\n  tags:\n  - Database\n  - Managed Service\n  - Relational\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/rds/\n  - type: OpenAPI\n    url: \n      https://api.apis.guru/v2/specs/amazonaws.com/rds/2014-10-31/openapi.yaml\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n\
  - type: Documentation\n  url: https://docs.aws.amazon.com/\n- type: Authentication\n  url: \n    https://docs.aws.amazon.com/general/latest/gr/signing_aws_api_requests.html\n- type: SDK\n  url: https://aws.amazon.com/tools/\n- type: Blog\n  url: https://aws.amazon.com/blogs/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Support\n  url: https://aws.amazon.com/support/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Pricing\n  url: https://aws.amazon.com/pricing/\n- type: Console\n  url: https://console.aws.amazon.com/\n- type: ChangeLog\n  url: https://aws.amazon.com/new/\n- type: Features\n  data:\n  - name: Global Infrastructure\n    description: Deploy applications across 30+ AWS Regions and 90+ Availability\n      Zones worldwide.\n  - name: Pay-as-you-go Pricing\n    description: Pay only for the services you use with no upfront costs or \n      long-term\
  \ commitments.\n  - name: Comprehensive Security\n    description: Built-in security with compliance programs, encryption, IAM, \n      and dedicated security services.\n  - name: Managed Services\n    description: Managed database, compute, storage, and networking services \n      with automatic patching and scaling.\n  - name: Serverless Computing\n    description: Run code, manage databases, and process streams without \n      managing infrastructure.\n  - name: Machine Learning\n    description: Pre-built ML services and tools for building, training, and \n      deploying ML models at scale.\n  - name: Hybrid Cloud\n    description: Extend AWS to on-premises with Outposts, Local Zones, and \n      Direct Connect.\n  - name: DevOps Toolchain\n    description: Integrated developer tools for CI/CD, infrastructure as code, \n      and monitoring.\n  - name: Event-Driven Architecture\n    description: Build decoupled, event-driven applications with SQS, SNS, \n      EventBridge, and Lambda.\n\
  \  - name: Container Services\n    description: Run containers with ECS, EKS, Fargate, and ECR for flexible \n      container workloads.\n- type: UseCases\n  data:\n  - name: Web Application Hosting\n    description: Host scalable web applications with EC2, S3, CloudFront, and \n      RDS.\n  - name: Data Analytics\n    description: Process and analyze large datasets using EMR, Redshift, Athena,\n      and Glue.\n  - name: Machine Learning\n    description: Build and deploy ML models at scale using SageMaker, \n      Rekognition, and Comprehend.\n  - name: Disaster Recovery\n    description: Implement multi-region disaster recovery strategies with \n      minimal RPO and RTO.\n  - name: IoT Applications\n    description: Collect, process, and analyze IoT device data with AWS IoT Core\n      and related services.\n- type: Integrations\n  data:\n  - name: Terraform\n    description: Manage AWS infrastructure as code using the official AWS \n      Terraform provider.\n  - name: Kubernetes\n\
  \    description: Deploy and manage Kubernetes workloads on AWS using Amazon EKS.\n  - name: GitHub Actions\n    description: Automate CI/CD pipelines deploying to AWS using GitHub Actions \n      and OIDC.\n  - name: Datadog\n    description: Monitor AWS infrastructure and applications using the Datadog \n      AWS integration.\n  - name: Snowflake\n    description: Integrate data workflows between Snowflake and AWS S3, Glue, \n      and Lake Formation.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/aws/refs/heads/main/apis.yml
tags:
- Cloud Computing
- IaaS
- Infrastructure
- PaaS
- Platform as a Service
- Serverless
url: https://raw.githubusercontent.com/api-evangelist/aws/refs/heads/main/apis.yml
use_cases:
- description: Host scalable web applications with EC2, S3, CloudFront, and RDS.
  name: Web Application Hosting
- description: Process and analyze large datasets using EMR, Redshift, Athena, and Glue.
  name: Data Analytics
- description: Build and deploy ML models at scale using SageMaker, Rekognition, and Comprehend.
  name: Machine Learning
- description: Implement multi-region disaster recovery strategies with minimal RPO and RTO.
  name: Disaster Recovery
- description: Collect, process, and analyze IoT device data with AWS IoT Core and related services.
  name: IoT Applications
---
