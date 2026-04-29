---
api_count: 1
apis:
- description: API for managing service discovery namespaces, services, and instances with health checking. Enables microservices to dynamically discover dependencies.
  name: Amazon Cloud Map API
  slug: ''
capabilities:
- description: Workflow for dynamically discovering and registering microservices using AWS Cloud Map, enabling DevOps and platform engineers to maintain service registries with health-based routing.
  name: Amazon Cloud Map Service Discovery
  slug: service-discovery
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/cloud-map/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/cloud-map/
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
  url: https://console.aws.amazon.com/cloudmap/
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
  url: https://stackoverflow.com/questions/tagged/amazon-cloud-map
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-cloud-map-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-cloud-map-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/service-discovery.yaml
created: '2026-03-16'
description: Amazon Cloud Map is a cloud resource discovery service that maintains an updated registry of application resources and their locations. Define custom names for application resources and use Cloud Map to dynamically discover service dependencies with integrated health checking and automatic updates.
features:
- description: Maintain an up-to-date registry of application resources with custom naming.
  name: Service Registry
- description: Continuously monitor health of every IP-based component and route only to healthy endpoints.
  name: Health Monitoring
- description: Automatically update service registries as services scale up or down.
  name: Dynamic Discovery
- description: Define custom names for application resources rather than hardcoding IP addresses.
  name: Custom Names
- description: Maintain service registries across different deployment environments, regions, and application versions.
  name: Multi-Environment Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Automatically register ECS task IPs in Cloud Map as containers launch.
  name: Amazon ECS
- description: Integrate Kubernetes service discovery with Cloud Map for hybrid environments.
  name: Amazon EKS
- description: DNS-based service discovery backed by Route 53 private hosted zones.
  name: Amazon Route 53
- description: Use Cloud Map as the service registry for App Mesh virtual services.
  name: AWS App Mesh
- description: Control access to Cloud Map namespaces with IAM policies.
  name: AWS IAM
jsonld:
- class_count: 15
  name: Amazon Cloud Map Context
  property_count: 20
  slug: amazon-cloud-map-context
layout: provider
modified: '2026-04-19'
name: Amazon Cloud Map
rules:
- name: Amazon Cloud Map API Rules
  rule_count: 20
  severity_counts:
    error: 12
    hint: 0
    info: 2
    warn: 6
  slug: amazon-cloud-map-spectral-rules
skills: []
slug: amazon-cloud-map
solutions: []
source_yaml: "aid: amazon-cloud-map\nname: Amazon Cloud Map\ndescription: >-\n  Amazon Cloud Map is a cloud resource discovery service that maintains an updated registry of application resources and their locations. Define custom names for application resources and use Cloud Map\n  to dynamically discover service dependencies with integrated health checking and automatic updates.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Cloud Map\n- Service Discovery\n- Microservices\n- DNS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-cloud-map/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- name: Amazon Cloud Map API\n  description: API for managing service discovery namespaces, services, and instances with health checking. Enables microservices to dynamically discover dependencies.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n\
  \  humanURL: https://aws.amazon.com/cloud-map/\n  baseURL: https://servicediscovery.us-east-1.amazonaws.com\n  tags:\n  - AWS\n  - Cloud Map\n  - Service Discovery\n  - Microservices\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/cloud-map/latest/api/\n  - type: OpenAPI\n    url: openapi/amazon-cloud-map-openapi.yml\n  - type: GettingStarted\n    url: https://aws.amazon.com/cloud-map/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/cloud-map/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/cloud-map/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/cloud-map/latest/api/\n  - type: JSONSchema\n    url: json-schema/cloud-map-namespace-schema.json\n  - type: JSONSchema\n    url: json-schema/cloud-map-service-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-cloud-map-context.jsonld\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type:\
  \ Website\n  url: https://aws.amazon.com/cloud-map/\n- type: Documentation\n  url: https://docs.aws.amazon.com/cloud-map/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/compute/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/cloudmap/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-cloud-map\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-cloud-map-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-cloud-map-vocabulary.yaml\n\
  - type: NaftikoCapability\n  url: capabilities/service-discovery.yaml\n- type: Features\n  data:\n  - name: Service Registry\n    description: Maintain an up-to-date registry of application resources with custom naming.\n  - name: Health Monitoring\n    description: Continuously monitor health of every IP-based component and route only to healthy endpoints.\n  - name: Dynamic Discovery\n    description: Automatically update service registries as services scale up or down.\n  - name: Custom Names\n    description: Define custom names for application resources rather than hardcoding IP addresses.\n  - name: Multi-Environment Support\n    description: Maintain service registries across different deployment environments, regions, and application versions.\n- type: UseCases\n  data:\n  - name: Microservice Discovery\n    description: Enable services to locate dependencies in dynamic container environments with ECS and EKS.\n  - name: Health-Based Routing\n    description: Ensure traffic routes\
  \ only to verified healthy service endpoints.\n  - name: CI/CD Integration\n    description: Automatically register and deregister services during CI/CD pipeline deployments.\n  - name: Multi-Region Service Mesh\n    description: Discover services across multiple AWS regions with a unified namespace.\n- type: Integrations\n  data:\n  - name: Amazon ECS\n    description: Automatically register ECS task IPs in Cloud Map as containers launch.\n  - name: Amazon EKS\n    description: Integrate Kubernetes service discovery with Cloud Map for hybrid environments.\n  - name: Amazon Route 53\n    description: DNS-based service discovery backed by Route 53 private hosted zones.\n  - name: AWS App Mesh\n    description: Use Cloud Map as the service registry for App Mesh virtual services.\n  - name: AWS IAM\n    description: Control access to Cloud Map namespaces with IAM policies.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloud-map/refs/heads/main/apis.yml
tags:
- AWS
- Cloud Map
- Service Discovery
- Microservices
- DNS
url: https://raw.githubusercontent.com/api-evangelist/amazon-cloud-map/refs/heads/main/apis.yml
use_cases:
- description: Enable services to locate dependencies in dynamic container environments with ECS and EKS.
  name: Microservice Discovery
- description: Ensure traffic routes only to verified healthy service endpoints.
  name: Health-Based Routing
- description: Automatically register and deregister services during CI/CD pipeline deployments.
  name: CI/CD Integration
- description: Discover services across multiple AWS regions with a unified namespace.
  name: Multi-Region Service Mesh
---
