---
api_count: 1
apis:
- description: The AWS Firewall Manager API provides programmatic access to create and manage security policies, compliance status, and protection configurations for AWS WAF, Shield, and VPC security groups across y
  name: AWS Firewall Manager API
  slug: aws-firewall-manager-api
capabilities:
- description: Centrally manage WAF, Shield, Network Firewall, and security group policies across AWS accounts.
  name: Amazon Firewall Manager Security Governance
  slug: amazon-firewall-manager-security-governance
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/firewall-manager/
- title: ''
  type: Website
  url: https://aws.amazon.com/firewall-manager/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/waf/latest/developerguide/fms-chapter.html
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
  url: https://console.aws.amazon.com/wafv2/fmsv2/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/aws-firewall-manager
- title: ''
  type: SpectralRules
  url: rules/amazon-firewall-manager-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/firewall-manager.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-firewall-manager-security-governance.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-firewall-manager-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/amazon-firewall-manager-context.jsonld
created: '2026-03-16'
description: AWS Firewall Manager is a security management service that allows you to centrally configure and manage firewall rules across your accounts and applications in AWS Organizations. It makes it easier to bring new applications and resources into compliance with security policies.
features:
- description: Define and enforce WAF, Shield Advanced, Network Firewall, and security group policies from a single pane of glass across all AWS accounts.
  name: Centralized Policy Management
- description: Automatically remediate non-compliant resources so that new accounts and resources are always protected.
  name: Automatic Remediation
- description: Manage security policies across hundreds of AWS accounts within an AWS Organization.
  name: Multi-Account Support
- description: View policy compliance status per account and resource with detailed violation reports.
  name: Compliance Visibility
- description: Group AWS resources by type for targeted policy application and management.
  name: Resource Sets
- description: Apply policies to resources based on AWS resource tags for fine-grained scope control.
  name: Tag-Based Targeting
- description: Deploy and manage third-party firewall appliances through AWS Marketplace with Firewall Manager.
  name: Third-Party Firewall Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Manage Firewall Manager policies across all accounts in the organization hierarchy.
  name: AWS Organizations
- description: Centrally create and deploy WAF rule groups and web ACLs across accounts.
  name: AWS WAF
- description: Enable and manage Shield Advanced protection for all DDoS-sensitive resources.
  name: AWS Shield Advanced
- description: Deploy centrally managed network firewall policies across VPCs.
  name: AWS Network Firewall
- description: Manage DNS Firewall rule groups for Route 53 Resolver across accounts.
  name: Amazon Route 53 Resolver
- description: Monitor compliance metrics and set alarms for non-compliant resources.
  name: Amazon CloudWatch
- description: Send Firewall Manager compliance findings to Security Hub for centralized security posture management.
  name: AWS Security Hub
- description: Control who can create, modify, and view Firewall Manager policies using IAM permissions.
  name: AWS IAM
jsonld:
- class_count: 5
  name: Amazon Firewall Manager Context
  property_count: 14
  slug: amazon-firewall-manager-context
layout: provider
modified: '2026-04-19'
name: Amazon Firewall Manager
rules:
- name: Amazon Firewall Manager API Rules
  rule_count: 25
  severity_counts:
    error: 8
    hint: 0
    info: 3
    warn: 14
  slug: amazon-firewall-manager-spectral-rules
skills: []
slug: amazon-firewall-manager
solutions: []
source_yaml: "aid: amazon-firewall-manager\nname: Amazon Firewall Manager\ndescription: >-\n  AWS Firewall Manager is a security management service that allows you to\n  centrally configure and manage firewall rules across your accounts and\n  applications in AWS Organizations. It makes it easier to bring new\n  applications and resources into compliance with security policies.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Compliance\n- Firewall\n- Network Security\n- Security\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-firewall-manager/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-firewall-manager:aws-firewall-manager-api\n  name: AWS Firewall Manager API\n  description: >-\n    The AWS Firewall Manager API provides programmatic access to create and\n    manage security policies, compliance status, and protection configurations\n\
  \    for AWS WAF, Shield, and VPC security groups across your organization.\n  humanURL: https://aws.amazon.com/firewall-manager/\n  baseURL: https://fms.amazonaws.com\n  tags:\n  - Firewall Management\n  - Network Security\n  - Security\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/fms/latest/APIReference/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-firewall-manager-openapi.yml\n  - type: JSONSchema\n    url: json-schema/amazon-firewall-manager-policy-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-firewall-manager-compliance-violator-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-firewall-manager-resource-set-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-firewall-manager-security-service-policy-data-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-firewall-manager-tag-schema.json\n  - type: JSONStructure\n    url: json-structure/amazon-firewall-manager-policy-structure.json\n  -\
  \ type: JSONStructure\n    url: json-structure/amazon-firewall-manager-compliance-violator-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-firewall-manager-resource-set-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-firewall-manager-security-service-policy-data-structure.json\n  - type: JSONStructure\n    url: json-structure/amazon-firewall-manager-tag-structure.json\n  - type: Example\n    url: examples/amazon-firewall-manager-policy-example.json\n  - type: Example\n    url: examples/amazon-firewall-manager-compliance-violator-example.json\n  - type: Example\n    url: examples/amazon-firewall-manager-resource-set-example.json\n  - type: Example\n    url: examples/amazon-firewall-manager-security-service-policy-data-example.json\n  - type: Example\n    url: examples/amazon-firewall-manager-tag-example.json\n  - type: GettingStarted\n    url: https://aws.amazon.com/firewall-manager/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/firewall-manager/pricing/\n\
  \  - type: FAQ\n    url: https://aws.amazon.com/firewall-manager/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/fms/latest/APIReference/Welcome.html\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/firewall-manager/\n- type: Website\n  url: https://aws.amazon.com/firewall-manager/\n- type: Documentation\n  url: https://docs.aws.amazon.com/waf/latest/developerguide/fms-chapter.html\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/security/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/wafv2/fmsv2/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n\
  - type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/aws-firewall-manager\n- type: SpectralRules\n  url: rules/amazon-firewall-manager-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/shared/firewall-manager.yaml\n- type: NaftikoCapability\n  url: capabilities/amazon-firewall-manager-security-governance.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-firewall-manager-vocabulary.yaml\n- type: JSON-LD\n  url: json-ld/amazon-firewall-manager-context.jsonld\n- type: Features\n  data:\n  - name: Centralized Policy Management\n    description: Define and enforce WAF, Shield Advanced, Network Firewall, and security group policies from a single pane of glass across all AWS accounts.\n  - name: Automatic Remediation\n    description: Automatically remediate non-compliant resources so that new accounts and resources are always protected.\n  - name: Multi-Account Support\n    description: Manage security policies across hundreds of AWS accounts within an AWS\
  \ Organization.\n  - name: Compliance Visibility\n    description: View policy compliance status per account and resource with detailed violation reports.\n  - name: Resource Sets\n    description: Group AWS resources by type for targeted policy application and management.\n  - name: Tag-Based Targeting\n    description: Apply policies to resources based on AWS resource tags for fine-grained scope control.\n  - name: Third-Party Firewall Support\n    description: Deploy and manage third-party firewall appliances through AWS Marketplace with Firewall Manager.\n- type: UseCases\n  data:\n  - name: WAF Rule Standardization\n    description: Enforce standard WAF rule sets across all CloudFront distributions and ALBs organization-wide.\n  - name: DDoS Protection Baseline\n    description: Mandate Shield Advanced protection for all internet-facing resources across accounts.\n  - name: Security Group Governance\n    description: Audit and remediate overly permissive security group rules across\
  \ EC2 and VPC resources.\n  - name: Network Firewall Deployment\n    description: Deploy and manage AWS Network Firewall across VPCs in multiple accounts from a central policy.\n  - name: Compliance Reporting\n    description: Monitor and report on firewall policy compliance for SOC 2, PCI DSS, and regulatory requirements.\n  - name: New Account Onboarding\n    description: Automatically apply security policies to new AWS accounts as they join the organization.\n- type: Integrations\n  data:\n  - name: AWS Organizations\n    description: Manage Firewall Manager policies across all accounts in the organization hierarchy.\n  - name: AWS WAF\n    description: Centrally create and deploy WAF rule groups and web ACLs across accounts.\n  - name: AWS Shield Advanced\n    description: Enable and manage Shield Advanced protection for all DDoS-sensitive resources.\n  - name: AWS Network Firewall\n    description: Deploy centrally managed network firewall policies across VPCs.\n  - name: Amazon Route\
  \ 53 Resolver\n    description: Manage DNS Firewall rule groups for Route 53 Resolver across accounts.\n  - name: Amazon CloudWatch\n    description: Monitor compliance metrics and set alarms for non-compliant resources.\n  - name: AWS Security Hub\n    description: Send Firewall Manager compliance findings to Security Hub for centralized security posture management.\n  - name: AWS IAM\n    description: Control who can create, modify, and view Firewall Manager policies using IAM permissions.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-firewall-manager/refs/heads/main/apis.yml
tags:
- AWS
- Compliance
- Firewall
- Network Security
- Security
url: https://raw.githubusercontent.com/api-evangelist/amazon-firewall-manager/refs/heads/main/apis.yml
use_cases:
- description: Enforce standard WAF rule sets across all CloudFront distributions and ALBs organization-wide.
  name: WAF Rule Standardization
- description: Mandate Shield Advanced protection for all internet-facing resources across accounts.
  name: DDoS Protection Baseline
- description: Audit and remediate overly permissive security group rules across EC2 and VPC resources.
  name: Security Group Governance
- description: Deploy and manage AWS Network Firewall across VPCs in multiple accounts from a central policy.
  name: Network Firewall Deployment
- description: Monitor and report on firewall policy compliance for SOC 2, PCI DSS, and regulatory requirements.
  name: Compliance Reporting
- description: Automatically apply security policies to new AWS accounts as they join the organization.
  name: New Account Onboarding
---
