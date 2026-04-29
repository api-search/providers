---
api_count: 1
api_specs:
- filename: openapi.yml
  format: yaml
  label: Amazon Lightsail API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-lightsail/refs/heads/main/openapi/openapi.yml
apis:
- description: The Amazon Lightsail API provides programmatic access to manage Lightsail resources including instances, containers, databases, disks, load balancers, certificates, distributions, and DNS zones.
  name: Amazon Lightsail API
  slug: ''
capabilities:
- description: Unified workflow capability for Amazon Lightsail combining resource management and operations.
  name: Amazon Lightsail Workflow
  slug: amazon-lightsail-workflow
common:
- title: ''
  type: portal
  url: https://aws.amazon.com/
- title: ''
  type: website
  url: https://aws.amazon.com/lightsail/
- title: ''
  type: documentation
  url: https://docs.aws.amazon.com/lightsail/
- title: ''
  type: terms-of-service
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: privacy-policy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: blog
  url: https://aws.amazon.com/blogs/compute/
- title: ''
  type: github
  url: https://github.com/aws
- title: ''
  type: console
  url: https://lightsail.aws.amazon.com/
- title: ''
  type: sign-up
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: login
  url: https://signin.aws.amazon.com/
- title: ''
  type: status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: knowledge-center
  url: https://repost.aws/knowledge-center
- title: ''
  type: youtube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: stack-overflow
  url: https://stackoverflow.com/questions/tagged/amazon-lightsail
- title: ''
  type: contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: security
  url: https://aws.amazon.com/security/
- title: ''
  type: compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-lightsail-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-lightsail-workflow.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-lightsail-vocabulary.yaml
created: '2024-01-15'
description: Amazon Lightsail is a virtual private server (VPS) provider and is the easiest way to get started with AWS for developers, small businesses, students, and other users who need a solution to build and host their applications on cloud. Lightsail provides developers compute, storage, and networking capacity and capabilities to deploy and manage websites and web applications in the cloud.
features:
- description: Launch virtual servers with pre-configured Linux/Windows environments in minutes.
  name: Simple Virtual Servers
- description: Deploy managed databases (MySQL, PostgreSQL) without server management.
  name: Managed Databases
- description: Deploy containerized applications using Lightsail container services.
  name: Containers
- description: Create CloudFront-powered CDN distributions for faster content delivery.
  name: CDN Distributions
- description: Fixed monthly pricing with no surprise bills including compute, storage, and data transfer.
  name: Predictable Pricing
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Connect Lightsail instances to S3 buckets for object storage.
  name: Amazon S3
- description: Distribute Lightsail content globally via CloudFront CDN distributions.
  name: AWS CloudFront
- description: Manage DNS for Lightsail resources using Route 53.
  name: Amazon Route 53
- description: Migrate Lightsail instances to EC2 when you need more control.
  name: Amazon EC2
jsonld:
- class_count: 1
  name: Amazon Lightsail Context
  property_count: 7
  slug: amazon-lightsail-context
layout: provider
modified: '2026-04-19'
name: Amazon Lightsail
rules:
- name: Amazon Lightsail API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 7
  slug: amazon-lightsail-spectral-rules
skills: []
slug: amazon-lightsail
solutions: []
source_filename: apis.yml
source_yaml: "name: Amazon Lightsail\ndescription: >-\n  Amazon Lightsail is a virtual private server (VPS) provider and is the easiest way\n  to get started with AWS for developers, small businesses, students, and other users\n  who need a solution to build and host their applications on cloud. Lightsail provides\n  developers compute, storage, and networking capacity and capabilities to deploy\n  and manage websites and web applications in the cloud.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://apis.io/amazon-lightsail\ncreated: '2024-01-15'\nmodified: '2026-04-19'\n\napis:\n- name: Amazon Lightsail API\n  description: >-\n    The Amazon Lightsail API provides programmatic access to manage\n    Lightsail resources including instances, containers, databases,\n    disks, load balancers, certificates, distributions, and DNS zones.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  baseURL: https://lightsail.amazonaws.com\n\
  \  properties:\n  - type: documentation\n    url: https://docs.aws.amazon.com/lightsail/latest/userguide/what-is-amazon-lightsail.html\n  - type: openapi\n    url: openapi/openapi.yml\n  - type: openapi\n    url: >-\n      https://api.apis.guru/v2/specs/amazonaws.com/lightsail/latest/openapi.yaml\n  - type: json-schema\n    url: json-schema/json-schema.yml\n  - type: json-ld\n    url: json-ld/json-ld.yml\n  - type: pricing\n    url: https://aws.amazon.com/lightsail/pricing/\n  - type: getting-started\n    url: https://aws.amazon.com/lightsail/getting-started/\n  - type: faq\n    url: https://aws.amazon.com/lightsail/faq/\n\n  - type: JSONSchema\n    url: json-schema/amazon-lightsail-instance-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-lightsail-context.jsonld\ncommon:\n- type: portal\n  url: https://aws.amazon.com/\n- type: website\n  url: https://aws.amazon.com/lightsail/\n- type: documentation\n  url: https://docs.aws.amazon.com/lightsail/\n- type: terms-of-service\n  url:\
  \ https://aws.amazon.com/service-terms/\n- type: privacy-policy\n  url: https://aws.amazon.com/privacy/\n- type: support\n  url: https://aws.amazon.com/premiumsupport/\n- type: blog\n  url: https://aws.amazon.com/blogs/compute/\n- type: github\n  url: https://github.com/aws\n- type: console\n  url: https://lightsail.aws.amazon.com/\n- type: sign-up\n  url: https://portal.aws.amazon.com/billing/signup\n- type: login\n  url: https://signin.aws.amazon.com/\n- type: status\n  url: https://health.aws.amazon.com/health/status\n- type: knowledge-center\n  url: https://repost.aws/knowledge-center\n- type: youtube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: stack-overflow\n  url: https://stackoverflow.com/questions/tagged/amazon-lightsail\n- type: contact\n  url: https://aws.amazon.com/contact-us/\n- type: security\n  url: https://aws.amazon.com/security/\n- type: compliance\n  url: https://aws.amazon.com/compliance/\n\n- type: Features\n  data:\n  - name: Simple Virtual Servers\n\
  \    description: Launch virtual servers with pre-configured Linux/Windows environments in minutes.\n  - name: Managed Databases\n    description: Deploy managed databases (MySQL, PostgreSQL) without server management.\n  - name: Containers\n    description: Deploy containerized applications using Lightsail container services.\n  - name: CDN Distributions\n    description: Create CloudFront-powered CDN distributions for faster content delivery.\n  - name: Predictable Pricing\n    description: Fixed monthly pricing with no surprise bills including compute, storage, and data transfer.\n- type: UseCases\n  data:\n  - name: WordPress Hosting\n    description: Host WordPress sites with pre-configured LAMP stacks at low, predictable cost.\n  - name: Web Application Development\n    description: Develop and test web applications on simple cloud infrastructure.\n  - name: Small Business Websites\n    description: Power small business websites with affordable, managed cloud hosting.\n- type: Integrations\n\
  \  data:\n  - name: Amazon S3\n    description: Connect Lightsail instances to S3 buckets for object storage.\n  - name: AWS CloudFront\n    description: Distribute Lightsail content globally via CloudFront CDN distributions.\n  - name: Amazon Route 53\n    description: Manage DNS for Lightsail resources using Route 53.\n  - name: Amazon EC2\n    description: Migrate Lightsail instances to EC2 when you need more control.\n- type: SpectralRules\n  url: rules/amazon-lightsail-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-lightsail-workflow.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-lightsail-vocabulary.yaml\nmaintainer:\n  name: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-lightsail/refs/heads/main/apis.yml
tags: []
url: https://apis.io/amazon-lightsail
use_cases:
- description: Host WordPress sites with pre-configured LAMP stacks at low, predictable cost.
  name: WordPress Hosting
- description: Develop and test web applications on simple cloud infrastructure.
  name: Web Application Development
- description: Power small business websites with affordable, managed cloud hosting.
  name: Small Business Websites
---
