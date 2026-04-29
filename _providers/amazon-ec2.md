---
api_count: 1
apis:
- description: Core API for managing Amazon EC2 instances, AMIs, key pairs, security groups, Elastic IPs, launch templates, spot instances, capacity reservations, and other compute resources.
  name: Amazon EC2 API
  slug: ''
capabilities:
- description: Unified capability for managing EC2 instances, AMIs, security groups, and networking for cloud infrastructure engineers.
  name: Amazon EC2 Cloud Compute Management
  slug: ec2-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/ec2/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/ec2/
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
  url: https://aws.amazon.com/blogs/compute/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/ec2/
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
  type: KnowledgeCenter
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-ec2
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security.html
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-ec2-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-ec2-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/ec2-management.yaml
created: '2024-01-15'
description: Amazon Elastic Compute Cloud (EC2) provides resizable compute capacity in the cloud, allowing you to launch virtual server instances, manage networking, and configure storage with complete control over your computing resources.
features:
- description: Over 750 instance types optimized for compute, memory, storage, GPU, and inferencing workloads.
  name: Diverse Instance Types
- description: Pre-configured OS images for Windows, Linux, and macOS with custom and marketplace options.
  name: Amazon Machine Images
- description: Static IPv4 addresses that can be quickly remapped to different instances for fault tolerance.
  name: Elastic IPs
- description: Virtual firewalls to control inbound and outbound traffic to EC2 instances.
  name: Security Groups
- description: Access spare EC2 capacity at up to 90% discount over On-Demand prices for flexible workloads.
  name: Spot Instances
- description: Control instance placement for low-latency cluster networking or high-availability distribution.
  name: Placement Groups
- description: Version-controlled configurations for launching EC2 instances with consistent settings.
  name: Launch Templates
- description: Next-generation virtualization infrastructure delivering near bare-metal performance and security.
  name: Nitro System
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Launch EC2 instances in logically isolated virtual networks with full networking control.
  name: Amazon VPC
- description: Distribute incoming traffic across multiple EC2 instances for high availability.
  name: Elastic Load Balancing
- description: Connect EC2 instances to managed relational database services within the same VPC.
  name: Amazon RDS
- description: Automatically scale EC2 fleets based on demand metrics and scheduling policies.
  name: AWS Auto Scaling
- description: Manage, patch, and operate EC2 instances at scale without SSH access.
  name: AWS Systems Manager
jsonld:
- class_count: 6
  name: Amazon Ec2 Context
  property_count: 35
  slug: amazon-ec2-context
layout: provider
modified: '2026-04-19'
name: Amazon EC2
rules:
- name: Amazon EC2 API Rules
  rule_count: 28
  severity_counts:
    error: 11
    hint: 0
    info: 4
    warn: 13
  slug: amazon-ec2-spectral-rules
skills: []
slug: amazon-ec2
solutions: []
source_yaml: "name: Amazon EC2\ndescription: Amazon Elastic Compute Cloud (EC2) provides resizable compute capacity in the cloud, allowing you to launch virtual server instances, manage networking, and configure storage with \n  complete control over your computing resources.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/ec2/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon EC2 API\n  description: >-\n    Core API for managing Amazon EC2 instances, AMIs, key pairs, security\n    groups, Elastic IPs, launch templates, spot instances, capacity\n    reservations, and other compute resources.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/ec2/\n  baseURL: https://ec2.amazonaws.com\n  tags:\n  - AWS\n  - Cloud Computing\n  - Compute\n  - Instances\n  - Virtual Machines\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/Welcome.html\n\
  \  - type: OpenAPI\n    url: openapi/amazon-ec2-openapi.yml\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/ec2/2016-11-15/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-ec2-instance-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-ec2-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/ec2/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/ec2/getting-started/\n  - type: Authentication\n    url: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/Query-Requests.html\n  - type: SDK\n    url: https://aws.amazon.com/tools/\n  - type: StatusPage\n    url: https://status.aws.amazon.com/\n  - type: BestPractices\n    url: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-best-practices.html\n  - type: FAQ\n    url: https://aws.amazon.com/ec2/faqs/\n  - type: TermsOfService\n    url: https://aws.amazon.com/ec2/sla/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/\n\
  \  - type: APIReference\n    url: https://docs.aws.amazon.com/AWSEC2/latest/APIReference/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/cli/latest/reference/ec2/\n  - type: Security\n    url: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security.html\n  - type: JSONStructure\n    url: json-structure/amazon-ec2-instance-structure.json\n  - type: Example\n    url: examples/amazon-ec2-instance-example.json\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: DeveloperPortal\n  url: https://aws.amazon.com/ec2/\n- type: Documentation\n  url: https://docs.aws.amazon.com/ec2/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/compute/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/ec2/\n- type:\
  \ SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-ec2\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Security\n  url: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security.html\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: Features\n  data:\n  - name: Diverse Instance Types\n    description: Over 750 instance types optimized for compute, memory, storage, GPU, and inferencing workloads.\n  - name: Amazon Machine Images\n    description: Pre-configured OS images for Windows, Linux, and macOS with custom and marketplace options.\n  - name: Elastic IPs\n    description:\
  \ Static IPv4 addresses that can be quickly remapped to different instances for fault tolerance.\n  - name: Security Groups\n    description: Virtual firewalls to control inbound and outbound traffic to EC2 instances.\n  - name: Spot Instances\n    description: Access spare EC2 capacity at up to 90% discount over On-Demand prices for flexible workloads.\n  - name: Placement Groups\n    description: Control instance placement for low-latency cluster networking or high-availability distribution.\n  - name: Launch Templates\n    description: Version-controlled configurations for launching EC2 instances with consistent settings.\n  - name: Nitro System\n    description: Next-generation virtualization infrastructure delivering near bare-metal performance and security.\n- type: UseCases\n  data:\n  - name: Web Application Hosting\n    description: Deploy scalable web applications and APIs with full control over the compute environment.\n  - name: Machine Learning Training\n    description: GPU-accelerated\
  \ instances for deep learning model training and inference workloads.\n  - name: High-Performance Computing\n    description: Cluster networking instances for computational fluid dynamics, genomics, and financial modeling.\n  - name: SAP and Enterprise Workloads\n    description: Certified instances for SAP HANA, SAP S/4HANA, and other enterprise database applications.\n  - name: Development and Testing\n    description: Flexible on-demand compute for CI/CD pipelines, dev environments, and test automation.\n- type: Integrations\n  data:\n  - name: Amazon VPC\n    description: Launch EC2 instances in logically isolated virtual networks with full networking control.\n  - name: Elastic Load Balancing\n    description: Distribute incoming traffic across multiple EC2 instances for high availability.\n  - name: Amazon RDS\n    description: Connect EC2 instances to managed relational database services within the same VPC.\n  - name: AWS Auto Scaling\n    description: Automatically scale EC2 fleets\
  \ based on demand metrics and scheduling policies.\n  - name: AWS Systems Manager\n    description: Manage, patch, and operate EC2 instances at scale without SSH access.\n- type: SpectralRules\n  url: rules/amazon-ec2-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-ec2-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/ec2-management.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- Cloud Computing\n- Compute\n- IaaS\n- Infrastructure\n- Virtual Machines\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-ec2/refs/heads/main/apis.yml
tags:
- AWS
- Cloud Computing
- Compute
- IaaS
- Infrastructure
- Virtual Machines
url: https://aws.amazon.com/ec2/
use_cases:
- description: Deploy scalable web applications and APIs with full control over the compute environment.
  name: Web Application Hosting
- description: GPU-accelerated instances for deep learning model training and inference workloads.
  name: Machine Learning Training
- description: Cluster networking instances for computational fluid dynamics, genomics, and financial modeling.
  name: High-Performance Computing
- description: Certified instances for SAP HANA, SAP S/4HANA, and other enterprise database applications.
  name: SAP and Enterprise Workloads
- description: Flexible on-demand compute for CI/CD pipelines, dev environments, and test automation.
  name: Development and Testing
---
