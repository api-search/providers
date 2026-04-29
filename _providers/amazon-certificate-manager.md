---
api_count: 1
api_specs:
- filename: amazon-certificate-manager-openapi.yml
  format: yaml
  label: Amazon Certificate Manager API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-certificate-manager/refs/heads/main/openapi/amazon-certificate-manager-openapi.yml
apis:
- description: API for provisioning, managing, and deploying public and private SSL/TLS certificates for use with AWS services and your internal connected resources. Supports requesting certificates, describing cert
  name: Amazon Certificate Manager API
  slug: ''
capabilities:
- description: Unified workflow for managing SSL/TLS certificate lifecycles on AWS, enabling DevOps engineers and security teams to provision, inspect, and retire certificates for websites and internal services.
  name: Amazon Certificate Manager Certificate Lifecycle Management
  slug: certificate-lifecycle-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/certificate-manager/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/acm/
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
  url: https://aws.amazon.com/blogs/security/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/acm/
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
  url: https://stackoverflow.com/questions/tagged/aws-certificate-manager
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Security
  url: https://docs.aws.amazon.com/acm/latest/userguide/security.html
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-certificate-manager-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-certificate-manager-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/certificate-lifecycle-management.yaml
created: '2024-01-15'
description: AWS Certificate Manager (ACM) handles the complexity of creating, storing, and renewing public and private SSL/TLS X.509 certificates and keys that protect your AWS websites and applications, enabling you to manage certificate lifecycles centrally.
features:
- description: Managed renewal for Amazon-issued SSL/TLS certificates, reducing manual maintenance overhead.
  name: Automated Certificate Renewal
- description: Provision both public certificates validated via DNS or email, and private certificates issued by a private CA.
  name: Public and Private Certificates
- description: Strong encryption and key management best practices for protecting and storing private keys.
  name: FIPS-Compliant Key Storage
- description: Deploy certificates to CloudFront, Elastic Load Balancing, API Gateway, and other integrated AWS services at no cost.
  name: Integrated AWS Service Deployment
- description: Provision and manage certificates for EC2, containers, on-premises hosts, and multicloud workloads.
  name: Hybrid and Multicloud Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Deploy ACM certificates to CloudFront distributions for HTTPS content delivery.
  name: Amazon CloudFront
- description: Attach ACM certificates to Application, Network, and Classic Load Balancers.
  name: Elastic Load Balancing
- description: Use ACM certificates for custom domain names in API Gateway.
  name: Amazon API Gateway
- description: Control access to ACM operations via IAM policies and roles.
  name: AWS IAM
- description: Audit all ACM API calls via CloudTrail for compliance and security monitoring.
  name: AWS CloudTrail
jsonld:
- class_count: 4
  name: Amazon Certificate Manager Context
  property_count: 8
  slug: amazon-certificate-manager-context
layout: provider
modified: '2026-04-19'
name: Amazon Certificate Manager
rules:
- name: Amazon Certificate Manager API Rules
  rule_count: 29
  severity_counts:
    error: 15
    hint: 0
    info: 3
    warn: 11
  slug: amazon-certificate-manager-spectral-rules
skills: []
slug: amazon-certificate-manager
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-certificate-manager\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-certificate-manager/refs/heads/main/apis.yml\nname: Amazon Certificate Manager\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nspecificationVersion: '0.19'\ndescription: >-\n  AWS Certificate Manager (ACM) handles the complexity of creating, storing,\n  and renewing public and private SSL/TLS X.509 certificates and keys that\n  protect your AWS websites and applications, enabling you to manage\n  certificate lifecycles centrally.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon Certificate Manager API\n  description: >-\n    API for provisioning, managing, and deploying public and private SSL/TLS\n    certificates for use with AWS services and your internal connected\n    resources. Supports requesting certificates, describing certificate\n    details, listing certificates, importing third-party certificates,\n\
  \    and managing certificate tags.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/certificate-manager/\n  baseURL: https://acm.amazonaws.com\n  tags:\n  - AWS\n  - Certificates\n  - Encryption\n  - Security\n  - SSL\n  - TLS\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/acm/latest/APIReference/\n  - type: OpenAPI\n    url: openapi/amazon-certificate-manager-openapi.yml\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/acm/2015-12-08/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-certificate-manager-certificate-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-certificate-manager-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/certificate-manager/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/certificate-manager/getting-started/\n  - type: FAQ\n    url: https://aws.amazon.com/certificate-manager/faqs/\n\
  \  - type: Documentation\n    url: https://docs.aws.amazon.com/acm/latest/userguide/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/acm/latest/APIReference/\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/acm/\n  - type: Security\n    url: https://docs.aws.amazon.com/acm/latest/userguide/security.html\n  - type: JSONSchema\n    url: json-schema/certificate-manager-request-certificate-request-schema.json\n  - type: JSONSchema\n    url: json-schema/certificate-manager-request-certificate-response-schema.json\n  - type: JSONSchema\n    url: json-schema/certificate-manager-list-certificates-response-schema.json\n  - type: JSONSchema\n    url: json-schema/certificate-manager-describe-certificate-response-schema.json\n  - type: Example\n    url: examples/certificate-manager-request-certificate-request-example.json\n  - type: Example\n    url: examples/certificate-manager-request-certificate-response-example.json\n  - type: Example\n    url: examples/certificate-manager-list-certificates-response-example.json\n\
  \  - type: Example\n    url: examples/certificate-manager-describe-certificate-response-example.json\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/certificate-manager/\n- type: Documentation\n  url: https://docs.aws.amazon.com/acm/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/security/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/acm/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: KnowledgeCenter\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n\
  - type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/aws-certificate-manager\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Security\n  url: https://docs.aws.amazon.com/acm/latest/userguide/security.html\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: SpectralRules\n  url: rules/amazon-certificate-manager-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-certificate-manager-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/certificate-lifecycle-management.yaml\n- type: Features\n  data:\n  - name: Automated Certificate Renewal\n    description: Managed renewal for Amazon-issued SSL/TLS certificates, reducing manual maintenance overhead.\n  - name: Public and Private Certificates\n    description: Provision both public certificates validated via DNS or email, and private certificates issued by a private CA.\n  - name: FIPS-Compliant Key Storage\n    description: Strong encryption and key management\
  \ best practices for protecting and storing private keys.\n  - name: Integrated AWS Service Deployment\n    description: Deploy certificates to CloudFront, Elastic Load Balancing, API Gateway, and other integrated AWS services at no cost.\n  - name: Hybrid and Multicloud Support\n    description: Provision and manage certificates for EC2, containers, on-premises hosts, and multicloud workloads.\n- type: UseCases\n  data:\n  - name: Website Protection\n    description: Securely terminate HTTPS traffic to public websites and web applications using ACM certificates.\n  - name: Internal Service Security\n    description: Protect private network communication between servers, mobile devices, IoT devices, and internal applications.\n  - name: Uptime Maintenance\n    description: Automated certificate lifecycle management prevents certificate expiration-related service downtime.\n  - name: Compliance and Audit\n    description: Centralize certificate management to meet compliance requirements\
  \ and simplify security audits.\n- type: Integrations\n  data:\n  - name: Amazon CloudFront\n    description: Deploy ACM certificates to CloudFront distributions for HTTPS content delivery.\n  - name: Elastic Load Balancing\n    description: Attach ACM certificates to Application, Network, and Classic Load Balancers.\n  - name: Amazon API Gateway\n    description: Use ACM certificates for custom domain names in API Gateway.\n  - name: AWS IAM\n    description: Control access to ACM operations via IAM policies and roles.\n  - name: AWS CloudTrail\n    description: Audit all ACM API calls via CloudTrail for compliance and security monitoring.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- Certificates\n- Encryption\n- Security\n- SSL\n- TLS\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-certificate-manager/refs/heads/main/apis.yml
tags:
- AWS
- Certificates
- Encryption
- Security
- SSL
- TLS
url: https://raw.githubusercontent.com/api-evangelist/amazon-certificate-manager/refs/heads/main/apis.yml
use_cases:
- description: Securely terminate HTTPS traffic to public websites and web applications using ACM certificates.
  name: Website Protection
- description: Protect private network communication between servers, mobile devices, IoT devices, and internal applications.
  name: Internal Service Security
- description: Automated certificate lifecycle management prevents certificate expiration-related service downtime.
  name: Uptime Maintenance
- description: Centralize certificate management to meet compliance requirements and simplify security audits.
  name: Compliance and Audit
---
