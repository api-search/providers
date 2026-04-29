---
api_count: 1
api_specs:
- filename: amazon-cloudfront-openapi.yml
  format: yaml
  label: Amazon CloudFront API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudfront/refs/heads/main/openapi/amazon-cloudfront-openapi.yml
apis:
- description: API for managing CloudFront distributions, origins, behaviors, cache policies, and edge functions for global content delivery.
  name: Amazon CloudFront API
  slug: ''
capabilities:
- description: Workflow for content delivery network management using Amazon CloudFront for Platform Engineer personas.
  name: Amazon CloudFront Content Delivery Network Management
  slug: content-delivery
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/cloudfront/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/cloudfront/latest/APIReference/
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
  url: https://aws.amazon.com/blogs/networking-and-content-delivery/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/cloudfront/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/amazon-cloudfront
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-cloudfront-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-cloudfront-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/content-delivery.yaml
created: '2024-01-01'
description: Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency and high transfer speeds across 750+ globally dispersed Points of Presence.
features:
- description: Deliver content from 750+ globally distributed Points of Presence for low latency.
  name: Global Edge Network
- description: Built-in AWS Shield Standard protection for all CloudFront distributions at no extra cost.
  name: DDoS Protection
- description: Deploy serverless code at edge locations with CloudFront Functions and Lambda@Edge.
  name: Edge Functions
- description: Secure content delivery with HTTPS and field-level encryption capabilities.
  name: HTTPS Encryption
- description: Additional caching layer to reduce load on origins and improve cache hit rates.
  name: Origin Shield
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Serve static content from S3 buckets through CloudFront distributions.
  name: Amazon S3
- description: Run Lambda functions at CloudFront edge locations for request customization.
  name: AWS Lambda@Edge
- description: Filter malicious traffic with WAF rules applied at the CloudFront edge.
  name: AWS WAF
- description: Use ACM SSL/TLS certificates with CloudFront distributions.
  name: AWS ACM
- description: Route traffic to CloudFront distributions using Route 53 aliases.
  name: Amazon Route 53
jsonld:
- class_count: 8
  name: Amazon Cloudfront Context
  property_count: 40
  slug: amazon-cloudfront-context
layout: provider
modified: '2026-04-19'
name: Amazon CloudFront
rules:
- name: Amazon CloudFront API Rules
  rule_count: 19
  severity_counts:
    error: 12
    hint: 0
    info: 1
    warn: 6
  slug: amazon-cloudfront-spectral-rules
skills: []
slug: amazon-cloudfront
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-cloudfront\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-cloudfront/refs/heads/main/apis.yml\nname: Amazon CloudFront\ntags:\n- AWS\n- CloudFront\n- CDN\n- Content Delivery\n- Edge\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Amazon CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency and high transfer speeds across 750+\n  globally dispersed Points of Presence.\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- name: Amazon CloudFront API\n  description: API for managing CloudFront distributions, origins, behaviors, cache policies, and edge functions for global content delivery.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/cloudfront/\n  baseURL: https://cloudfront.amazonaws.com\n\
  \  tags:\n  - AWS\n  - CloudFront\n  - CDN\n  - Content Delivery\n  properties:\n  - type: OpenAPI\n    url: openapi/amazon-cloudfront-openapi.yml\n  - type: Documentation\n    url: https://docs.aws.amazon.com/cloudfront/latest/APIReference/\n  - type: GettingStarted\n    url: https://aws.amazon.com/cloudfront/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/cloudfront/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/cloudfront/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/cloudfront/latest/APIReference/\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/cloudfront/\n  - type: JSONSchema\n    url: json-schema/cloudfront-distribution-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudfront-distribution-config-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudfront-origin-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudfront-cache-behavior-schema.json\n  - type: JSONSchema\n    url:\
  \ json-schema/cloudfront-invalidation-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-cloudfront-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/cloudfront/\n- type: Documentation\n  url: https://docs.aws.amazon.com/cloudfront/latest/APIReference/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/networking-and-content-delivery/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/cloudfront/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-cloudfront\n\
  - type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: SpectralRules\n  url: rules/amazon-cloudfront-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-cloudfront-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/content-delivery.yaml\n- type: Features\n  data:\n  - name: Global Edge Network\n    description: Deliver content from 750+ globally distributed Points of Presence for low latency.\n  - name: DDoS Protection\n    description: Built-in AWS Shield Standard protection for all CloudFront distributions at no extra cost.\n  - name: Edge Functions\n    description: Deploy serverless code at edge locations with CloudFront Functions and Lambda@Edge.\n  - name: HTTPS Encryption\n    description: Secure content delivery with HTTPS and field-level encryption capabilities.\n  - name: Origin Shield\n    description: Additional caching layer to reduce load on origins and improve cache hit\
  \ rates.\n- type: UseCases\n  data:\n  - name: Website Acceleration\n    description: Fast, secure global content delivery for web applications.\n  - name: Video Streaming\n    description: Live and on-demand video streaming with Media Services integration.\n  - name: API Acceleration\n    description: Low-latency API delivery with edge termination and WebSocket support.\n  - name: Software Distribution\n    description: Scale patch and software update delivery globally to millions of endpoints.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Serve static content from S3 buckets through CloudFront distributions.\n  - name: AWS Lambda@Edge\n    description: Run Lambda functions at CloudFront edge locations for request customization.\n  - name: AWS WAF\n    description: Filter malicious traffic with WAF rules applied at the CloudFront edge.\n  - name: AWS ACM\n    description: Use ACM SSL/TLS certificates with CloudFront distributions.\n  - name: Amazon Route 53\n \
  \   description: Route traffic to CloudFront distributions using Route 53 aliases.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudfront/refs/heads/main/apis.yml
tags:
- AWS
- CloudFront
- CDN
- Content Delivery
- Edge
url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudfront/refs/heads/main/apis.yml
use_cases:
- description: Fast, secure global content delivery for web applications.
  name: Website Acceleration
- description: Live and on-demand video streaming with Media Services integration.
  name: Video Streaming
- description: Low-latency API delivery with edge termination and WebSocket support.
  name: API Acceleration
- description: Scale patch and software update delivery globally to millions of endpoints.
  name: Software Distribution
---
