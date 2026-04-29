---
api_count: 3
apis:
- description: The Acquia Cloud API is a powerful tool that allows developers to programmatically interact with Acquia's cloud hosting platform. This API enables users to automate tasks, manage infrastructure, and d
  name: Acquia Cloud API
  slug: acquia-cloud-api
- description: Acquia Cloud Site Factory API is a powerful tool that allows developers to manage, customize, and automate various aspects of their websites and digital experiences. With this API, users can programma
  name: Acquia Cloud Site Factory API
  slug: acquia-cloud-site-factory-api
- description: The Acquia Content Hub API is a powerful tool that allows users to easily distribute and share content across multiple websites and digital channels. By leveraging this API, content managers can autom
  name: Acquia Content Hub API
  slug: acquia-content-hub-api
capabilities:
- description: Unified workflow for managing Drupal applications on Acquia Cloud, including application discovery, environment management, organization administration, and account operations. Used by Drupal develope
  name: Acquia Drupal Application Management
  slug: drupal-application-management
common:
- title: ''
  type: Partners
  url: https://www.acquia.com/partners
- title: ''
  type: Blog
  url: https://www.acquia.com/blog
- title: ''
  type: Webinars
  url: https://www.acquia.com/events/online
- title: ''
  type: Certifications
  url: https://www.acquia.com/support/acquia-training-certification
- title: ''
  type: Portal
  url: https://dev.acquia.com/
- title: ''
  type: Tutorials
  url: https://dev.acquia.com/tutorial
- title: ''
  type: Support
  url: https://docs.acquia.com/service-offerings/support/support-users-guide#contacting-acquia-support
- title: ''
  type: StatusPage
  url: https://status.acquia.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/acquia
- title: Acquia CLI
  type: CLI
  url: https://github.com/acquia/cli
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/rules/acquia-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/capabilities/drupal-application-management.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/vocabulary/acquia-vocabulary.yaml
- title: ''
  type: TermsOfService
  url: https://www.acquia.com/about-us/legal
- title: ''
  type: SignUp
  url: https://accounts.acquia.com/register
created: '2025-02-17'
description: Acquia is a leading provider of digital experience management solutions for organizations looking to enhance their online presence. They offer a range of services, including cloud hosting, digital asset management, and content management, to help businesses create, manage, and optimize their websites and digital experiences.
features:
- description: Managed Drupal hosting on Acquia Cloud with auto-scaling, CDN, and DDoS protection.
  name: Cloud Hosting
- description: Programmatic management of Drupal applications, environments, and deployments via Cloud API.
  name: Application Management
- description: Acquia Cloud Site Factory for managing hundreds of Drupal sites from a centralized platform.
  name: Multi-Site Factory
- description: Acquia Content Hub for distributing and synchronizing Drupal content across multiple sites.
  name: Content Syndication
- description: Browser-based Cloud IDE for remote Drupal development with pre-configured environments.
  name: Cloud IDE
- description: Secure API access via OAuth2 authorization code flow with scoped tokens.
  name: OAuth2 Authentication
image: /assets/icons/acquia.png
integrations:
- description: Native Drupal module integrations for Acquia Cloud, Content Hub, and Site Studio.
  name: Drupal CMS
- description: GitHub Actions workflows for Acquia Cloud deployment automation using Acquia CLI.
  name: GitHub Actions
- description: Headless Drupal with Next.js using Acquia CMS headless starter kit.
  name: Next.js
- description: Digital Asset Management integration via Widen Collective for media management in Drupal.
  name: Acquia DAM
jsonld:
- class_count: 17
  name: Acquia Context
  property_count: 73
  slug: acquia-context
layout: provider
modified: '2026-04-19'
name: Acquia
rules:
- name: Acquia API Rules
  rule_count: 32
  severity_counts:
    error: 14
    hint: 0
    info: 8
    warn: 10
  slug: acquia-spectral-rules
skills: []
slug: acquia
solutions: []
source_filename: apis.yml
source_yaml: "aid: acquia\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/apis.yml\napis:\n- aid: acquia:acquia-cloud-api\n  name: Acquia Cloud API\n  tags:\n  - Applications\n  - Cloud\n  - Drupal\n  - Environments\n  - Hosting\n  humanURL: https://cloudapi-docs.acquia.com/\n  properties:\n  - type: Documentation\n    url: https://cloudapi-docs.acquia.com/\n  - type: OpenAPI\n    url: openapi/acquia-cloud-openapi.yml\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/openapi/acquia-cloud-applications.yml\n    title: Acquia Applications API\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/openapi/acquia-cloud-environments.yml\n    title: Acquia Environments API\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/openapi/acquia-cloud-organizations.yml\n    title: Acquia Organizations API\n  - type: OpenAPI\n\
  \    url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/openapi/acquia-cloud-account.yml\n    title: Acquia Account API\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/openapi/acquia-cloud-subscriptions.yml\n    title: Acquia Subscriptions API\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/openapi/acquia-cloud-teams-and-permissions.yml\n    title: Acquia Teams And Permissions API\n  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/capabilities/shared/acquia-cloud-applications.yaml\n  description: >-\n    The Acquia Cloud API is a powerful tool that allows developers to programmatically\n    interact with Acquia's cloud hosting platform. This API enables users to automate\n    tasks, manage infrastructure, and deploy applications with ease. With the Acquia\n    Cloud API, developers can create custom\
  \ scripts and applications to streamline\n    workflows, monitor performance, and scale resources as needed.\n- aid: acquia:acquia-cloud-site-factory-api\n  name: Acquia Cloud Site Factory API\n  tags:\n  - Cloud\n  - Drupal\n  - Multisite\n  - Site Factory\n  humanURL: https://dev.acquia.com/api-documentation/acquia-cloud-site-factory-api\n  properties:\n  - type: Documentation\n    url: https://docs.acquia.com/site-factory/extend/api\n  description: >-\n    Acquia Cloud Site Factory API is a powerful tool that allows developers to manage,\n    customize, and automate various aspects of their websites and digital experiences.\n    With this API, users can programmatically create and modify websites, manage\n    content, and streamline deployment processes. By providing a flexible and scalable\n    interface, Acquia Cloud Site Factory API enables developers to efficiently build\n    and maintain multiple websites in a centralized platform.\n- aid: acquia:acquia-content-hub-api\n  name:\
  \ Acquia Content Hub API\n  tags:\n  - Content\n  - Content Hub\n  - Drupal\n  - Syndication\n  humanURL: https://dev.acquia.com/api-documentation/acquia-content-hub-api\n  properties:\n  - type: Documentation\n    url: https://docs.acquia.com/drupal-starter-kits/add-ons/content-hub/api\n  description: >-\n    The Acquia Content Hub API is a powerful tool that allows users to easily distribute\n    and share content across multiple websites and digital channels. By leveraging\n    this API, content managers can automate the process of importing, exporting,\n    and synchronizing content between various platforms, saving time and effort.\n    Additionally, the API enables users to gain valuable insights into content performance\n    and engagement metrics, helping to optimize content strategy and drive better\n    results.\nname: Acquia\ntags:\n- Content\n- Experience\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n\
  - url: https://www.acquia.com/partners\n  name: Work with a Partner | Acquia\n  type: Partners\n  description: 'null'\n- url: https://www.acquia.com/blog\n  name: The Acquia Blog | Acquia\n  type: Blog\n  description: 'null'\n- url: https://www.acquia.com/events/online\n  name: Register for Upcoming and Recorded Webinars | Acquia\n  type: Webinars\n  description: 'null'\n- url: https://www.acquia.com/support/acquia-training-certification\n  name: Acquia Training & Certification | Acquia\n  type: Certifications\n  description: 'null'\n- url: https://dev.acquia.com/\n  name: Acquia Developer Portal Homepage\n  type: Portal\n  description: 'null'\n- url: https://dev.acquia.com/tutorial\n  name: Acquia Developer Portal Tutorials\n  type: Tutorials\n  description: 'null'\n- url: >-\n    https://docs.acquia.com/service-offerings/support/support-users-guide#contacting-acquia-support\n  name: Support Users Guide | Service Offerings | Acquia Product Documentation\n  type: Support\n  description:\
  \ 'null'\n- url: https://status.acquia.com/\n  name: Acquia, Inc. Status\n  type: StatusPage\n  description: 'null'\n- type: GitHubOrganization\n  url: https://github.com/acquia\n- type: CLI\n  url: https://github.com/acquia/cli\n  title: Acquia CLI\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/rules/acquia-spectral-rules.yml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/capabilities/drupal-application-management.yaml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/vocabulary/acquia-vocabulary.yaml\n- type: TermsOfService\n  url: https://www.acquia.com/about-us/legal\n- type: SignUp\n  url: https://accounts.acquia.com/register\n- type: Features\n  data:\n  - name: Cloud Hosting\n    description: Managed Drupal hosting on Acquia Cloud with auto-scaling, CDN, and DDoS protection.\n  - name: Application Management\n    description:\
  \ Programmatic management of Drupal applications, environments, and deployments via Cloud API.\n  - name: Multi-Site Factory\n    description: Acquia Cloud Site Factory for managing hundreds of Drupal sites from a centralized platform.\n  - name: Content Syndication\n    description: Acquia Content Hub for distributing and synchronizing Drupal content across multiple sites.\n  - name: Cloud IDE\n    description: Browser-based Cloud IDE for remote Drupal development with pre-configured environments.\n  - name: OAuth2 Authentication\n    description: Secure API access via OAuth2 authorization code flow with scoped tokens.\n- type: UseCases\n  data:\n  - name: Automated Deployment Pipelines\n    description: Integrate Acquia Cloud API into CI/CD pipelines for automated code deployment and cache clearing.\n  - name: Multi-Environment Management\n    description: Manage dev, staging, and production Drupal environments programmatically.\n  - name: Platform Administration\n    description: Automate\
  \ team provisioning, SSH key management, and organizational access control.\n  - name: Content Distribution\n    description: Use Content Hub API to distribute content across a network of Drupal sites.\n  - name: Headless Drupal\n    description: Manage decoupled Drupal applications with Next.js or other frontend frameworks via Acquia APIs.\n- type: Integrations\n  data:\n  - name: Drupal CMS\n    description: Native Drupal module integrations for Acquia Cloud, Content Hub, and Site Studio.\n  - name: GitHub Actions\n    description: GitHub Actions workflows for Acquia Cloud deployment automation using Acquia CLI.\n  - name: Next.js\n    description: Headless Drupal with Next.js using Acquia CMS headless starter kit.\n  - name: Acquia DAM\n    description: Digital Asset Management integration via Widen Collective for media management in Drupal.\ncreated: '2025-02-17'\nmodified: '2026-04-19'\nposition: Consumer\ndescription: >-\n  Acquia is a leading provider of digital experience management\
  \ solutions for organizations\n  looking to enhance their online presence. They offer a range of services, including\n  cloud hosting, digital asset management, and content management, to help businesses\n  create, manage, and optimize their websites and digital experiences.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/apis.yml
tags:
- Content
- Experience
url: https://raw.githubusercontent.com/api-evangelist/acquia/refs/heads/main/apis.yml
use_cases:
- description: Integrate Acquia Cloud API into CI/CD pipelines for automated code deployment and cache clearing.
  name: Automated Deployment Pipelines
- description: Manage dev, staging, and production Drupal environments programmatically.
  name: Multi-Environment Management
- description: Automate team provisioning, SSH key management, and organizational access control.
  name: Platform Administration
- description: Use Content Hub API to distribute content across a network of Drupal sites.
  name: Content Distribution
- description: Manage decoupled Drupal applications with Next.js or other frontend frameworks via Acquia APIs.
  name: Headless Drupal
---
