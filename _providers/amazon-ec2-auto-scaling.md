---
api_count: 1
api_specs:
- filename: amazon-ec2-auto-scaling-openapi.yaml
  format: yaml
  label: Amazon EC2 Auto Scaling API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-ec2-auto-scaling/refs/heads/main/openapi/amazon-ec2-auto-scaling-openapi.yaml
apis:
- description: The Amazon EC2 Auto Scaling API provides programmatic access to create and manage Auto Scaling groups, launch configurations, scaling policies, scheduled actions, lifecycle hooks, and warm pools for a
  name: Amazon EC2 Auto Scaling API
  slug: ''
capabilities:
- description: Unified capability for managing EC2 Auto Scaling groups, scaling policies, and lifecycle hooks for cloud operations engineers.
  name: Amazon EC2 Auto Scaling Auto Scaling Group Management
  slug: ec2-auto-scaling-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/developer/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/autoscaling/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/support/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/compute/category/compute/auto-scaling/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/ec2/autoscaling/
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
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-ec2-auto-scaling
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://aws.amazon.com/security/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-ec2-auto-scaling-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-ec2-auto-scaling-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/ec2-auto-scaling-management.yaml
created: '2026-03-16'
description: Amazon EC2 Auto Scaling helps you maintain application availability and lets you automatically add or remove EC2 instances according to conditions you define. You can use fleet management features to maintain the health and availability of your fleet, and use dynamic and predictive scaling to add or remove EC2 instances to meet demand.
features:
- description: Automatically scales EC2 capacity up or down in response to real-time demand using target tracking, step, or simple scaling policies.
  name: Dynamic Scaling
- description: Uses machine learning to forecast future demand and proactively adds EC2 instances ahead of anticipated load spikes.
  name: Predictive Scaling
- description: Scales capacity at pre-defined times based on predictable load patterns or business cycles.
  name: Scheduled Scaling
- description: Automatically detects and replaces unhealthy instances to maintain application availability and fleet health.
  name: Fleet Management
- description: Gradually updates EC2 instances in an Auto Scaling group with new AMIs or launch template versions.
  name: Instance Refresh
- description: Pre-initializes EC2 instances to reduce latency for scale-out events by keeping a pool of instances in a stopped or running state.
  name: Warm Pools
- description: Combines On-Demand and Spot instances with multiple instance types for cost optimization and availability.
  name: Mixed Instances Policy
- description: Pauses instance launch or termination to perform custom actions such as installing software or draining connections.
  name: Lifecycle Hooks
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Launches and terminates EC2 instances based on scaling policies and schedules.
  name: Amazon EC2
- description: Uses CloudWatch metrics and alarms to trigger dynamic scaling policies automatically.
  name: Amazon CloudWatch
- description: Automatically registers new instances with load balancers and deregisters terminated instances.
  name: Elastic Load Balancing
- description: Integrates with Systems Manager for instance configuration and patch management during lifecycle hooks.
  name: AWS Systems Manager
- description: Sends notifications for scaling events, instance launches, and terminations via SNS topics.
  name: Amazon SNS
- description: Works with Cost Explorer and Budgets to monitor and optimize spend on Auto Scaling fleets.
  name: AWS Cost Management
jsonld:
- class_count: 48
  name: Amazon Ec2 Auto Scaling Context
  property_count: 200
  slug: amazon-ec2-auto-scaling-context
layout: provider
modified: '2026-04-19'
name: Amazon EC2 Auto Scaling
rules:
- name: Amazon EC2 Auto Scaling API Rules
  rule_count: 19
  severity_counts:
    error: 10
    hint: 0
    info: 0
    warn: 9
  slug: amazon-ec2-auto-scaling-spectral-rules
skills: []
slug: amazon-ec2-auto-scaling
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon EC2 Auto Scaling\ndescription: Amazon EC2 Auto Scaling helps you maintain application availability and lets you automatically add or remove EC2 instances according to conditions you define. You can use fleet management\n  features to maintain the health and availability of your fleet, and use dynamic and predictive scaling to add or remove EC2 instances to meet demand.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/ec2/autoscaling/\ncreated: '2026-03-16'\nmodified: '2026-04-19'\ntags:\n- Amazon Web Services\n- Auto Scaling\n- AWS\n- Compute\n- EC2\n- High Availability\n- Scaling\napis:\n- name: Amazon EC2 Auto Scaling API\n  description: The Amazon EC2 Auto Scaling API provides programmatic access to create and manage Auto Scaling groups, launch configurations, scaling policies, scheduled actions, lifecycle hooks, and \n    warm pools for automatic capacity management.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n\
  \  humanURL: https://aws.amazon.com/ec2/autoscaling/\n  baseURL: https://autoscaling.amazonaws.com\n  tags:\n  - Auto Scaling\n  - Capacity Management\n  - Compute\n  - EC2\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/autoscaling/ec2/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-ec2-auto-scaling-openapi.yaml\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/autoscaling/2011-01-01/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/ec2-auto-scaling-auto-scaling-group-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-ec2-auto-scaling-context.jsonld\n  - type: GettingStarted\n    url: https://docs.aws.amazon.com/autoscaling/ec2/userguide/get-started-with-ec2-auto-scaling.html\n  - type: Pricing\n    url: https://aws.amazon.com/ec2/autoscaling/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/ec2/autoscaling/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/autoscaling/ec2/APIReference/\n\
  \  - type: Authentication\n    url: https://docs.aws.amazon.com/autoscaling/ec2/APIReference/CommonParameters.html\n  - type: RateLimits\n    url: https://docs.aws.amazon.com/autoscaling/ec2/APIReference/ec2-auto-scaling-api-throttling.html\n  - type: JSONSchema\n    url: json-schema/ec2-auto-scaling-accelerator-count-request-schema.json\n  - type: JSONStructure\n    url: json-structure/ec2-auto-scaling-accelerator-count-request-structure.json\n  - type: Example\n    url: examples/ec2-auto-scaling-accelerator-count-request-example.json\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: DeveloperPortal\n  url: https://aws.amazon.com/developer/\n- type: Documentation\n  url: https://docs.aws.amazon.com/autoscaling/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/support/\n- type: Blog\n  url: https://aws.amazon.com/blogs/compute/category/compute/auto-scaling/\n\
  - type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/ec2/autoscaling/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-ec2-auto-scaling\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Security\n  url: https://aws.amazon.com/security/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Features\n  data:\n  - name: Dynamic Scaling\n    description: Automatically scales EC2 capacity up or down in response to real-time demand using target tracking, step, or simple scaling policies.\n  - name: Predictive Scaling\n    description:\
  \ Uses machine learning to forecast future demand and proactively adds EC2 instances ahead of anticipated load spikes.\n  - name: Scheduled Scaling\n    description: Scales capacity at pre-defined times based on predictable load patterns or business cycles.\n  - name: Fleet Management\n    description: Automatically detects and replaces unhealthy instances to maintain application availability and fleet health.\n  - name: Instance Refresh\n    description: Gradually updates EC2 instances in an Auto Scaling group with new AMIs or launch template versions.\n  - name: Warm Pools\n    description: Pre-initializes EC2 instances to reduce latency for scale-out events by keeping a pool of instances in a stopped or running state.\n  - name: Mixed Instances Policy\n    description: Combines On-Demand and Spot instances with multiple instance types for cost optimization and availability.\n  - name: Lifecycle Hooks\n    description: Pauses instance launch or termination to perform custom actions such\
  \ as installing software or draining connections.\n- type: UseCases\n  data:\n  - name: Web Application Scaling\n    description: Automatically scale web server fleets to handle variable HTTP traffic loads without over-provisioning.\n  - name: Batch Processing\n    description: Scale compute capacity up when jobs arrive and down when completed to minimize costs for batch workloads.\n  - name: Microservices Autoscaling\n    description: Independently scale each microservice based on its own traffic patterns and resource utilization.\n  - name: Cost Optimization\n    description: Combine Spot and On-Demand instances to reduce EC2 costs while maintaining availability.\n  - name: Blue/Green Deployments\n    description: Use instance refresh to gradually replace old instances with new ones for zero-downtime deployments.\n- type: Integrations\n  data:\n  - name: Amazon EC2\n    description: Launches and terminates EC2 instances based on scaling policies and schedules.\n  - name: Amazon CloudWatch\n\
  \    description: Uses CloudWatch metrics and alarms to trigger dynamic scaling policies automatically.\n  - name: Elastic Load Balancing\n    description: Automatically registers new instances with load balancers and deregisters terminated instances.\n  - name: AWS Systems Manager\n    description: Integrates with Systems Manager for instance configuration and patch management during lifecycle hooks.\n  - name: Amazon SNS\n    description: Sends notifications for scaling events, instance launches, and terminations via SNS topics.\n  - name: AWS Cost Management\n    description: Works with Cost Explorer and Budgets to monitor and optimize spend on Auto Scaling fleets.\n- type: SpectralRules\n  url: rules/amazon-ec2-auto-scaling-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-ec2-auto-scaling-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/ec2-auto-scaling-management.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-ec2-auto-scaling/refs/heads/main/apis.yml
tags:
- Amazon Web Services
- Auto Scaling
- AWS
- Compute
- EC2
- High Availability
- Scaling
url: https://aws.amazon.com/ec2/autoscaling/
use_cases:
- description: Automatically scale web server fleets to handle variable HTTP traffic loads without over-provisioning.
  name: Web Application Scaling
- description: Scale compute capacity up when jobs arrive and down when completed to minimize costs for batch workloads.
  name: Batch Processing
- description: Independently scale each microservice based on its own traffic patterns and resource utilization.
  name: Microservices Autoscaling
- description: Combine Spot and On-Demand instances to reduce EC2 costs while maintaining availability.
  name: Cost Optimization
- description: Use instance refresh to gradually replace old instances with new ones for zero-downtime deployments.
  name: Blue/Green Deployments
---
