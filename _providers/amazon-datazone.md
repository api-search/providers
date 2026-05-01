---
api_count: 1
api_specs:
- filename: amazon-datazone-openapi.yml
  format: yaml
  label: Amazon DataZone API
  slug: amazon-datazone-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-datazone/refs/heads/main/openapi/amazon-datazone-openapi.yml
apis:
- description: The Amazon DataZone API provides programmatic access to create and manage data domains, data assets, data catalogs, projects, subscriptions, and governance policies for enterprise-wide data management
  name: Amazon DataZone API
  slug: amazon-datazone-api
capabilities:
- description: ''
  name: Data Catalog Operations
  slug: data-catalog-operations
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/datazone/
- title: ''
  type: DeveloperPortal
  url: https://aws.amazon.com/datazone/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/datazone/
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
  url: https://aws.amazon.com/blogs/big-data/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/datazone/
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
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-datazone-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-datazone-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-catalog-operations.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/datazone.yaml
created: '2026-03-16'
description: Amazon DataZone is a data management service that helps you catalog, discover, govern, share, and analyze your data across your organization and beyond. It enables data producers and consumers to collaborate, with built-in governance, data catalog capabilities, and a business data catalog to organize and share data across your AWS environment. DataZone provides domain-based governance, project workspaces, subscription-based access control, and integration with AWS analytics services.
features:
- description: Central catalog where data producers publish assets and data consumers can discover, understand, and request access to data products.
  name: Business Data Catalog
- description: Organize data assets, users, and governance policies within domains that reflect your organizational structure and data ownership.
  name: Domain-Based Governance
- description: Built-in request/approval workflow for data consumers to request access to data assets with business justification and audit trail.
  name: Subscription Workflow
- description: Isolated project containers within domains where teams organize their data assets, environments, and members.
  name: Project Workspaces
- description: Automatically provision data access environments with Athena, Glue, Redshift, or other tools when subscriptions are approved.
  name: Analytics Environment Provisioning
- description: Automatically discover and import tables from AWS Glue Data Catalog into DataZone for cataloging and governance.
  name: Glue Data Catalog Integration
- description: Track data lineage across assets to understand data origins, transformations, and dependencies for trust and compliance.
  name: Data Lineage
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: DataZone integrates with Glue Data Catalog to automatically discover, import, and catalog Glue tables for sharing and governance.
  name: AWS Glue
- description: Catalog Redshift tables and views and govern cross-cluster data sharing through DataZone subscription workflows.
  name: Amazon Redshift
- description: DataZone environments provision Athena as a query engine for subscribers accessing S3-based data assets.
  name: Amazon Athena
- description: Catalog S3-based datasets in DataZone and control access through subscription-based Lake Formation permissions.
  name: Amazon S3
- description: DataZone uses Lake Formation for fine-grained column and row-level access control when subscriptions are approved.
  name: AWS Lake Formation
- description: IAM roles provide domain execution context and identity-based access control for DataZone resources and catalog operations.
  name: AWS IAM
jsonld:
- class_count: 0
  name: Amazon Datazone Context
  property_count: 26
  slug: amazon-datazone-context
layout: provider
modified: '2026-04-19'
name: Amazon DataZone
rules:
- name: Amazon DataZone API Rules
  rule_count: 20
  severity_counts:
    error: 13
    hint: 0
    info: 2
    warn: 5
  slug: amazon-datazone-spectral-rules
skills: []
slug: amazon-datazone
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amazon-datazone\nname: Amazon DataZone\ndescription: >-\n  Amazon DataZone is a data management service that helps you catalog, discover,\n  govern, share, and analyze your data across your organization and beyond.\n  It enables data producers and consumers to collaborate, with built-in\n  governance, data catalog capabilities, and a business data catalog to organize\n  and share data across your AWS environment. DataZone provides domain-based\n  governance, project workspaces, subscription-based access control, and\n  integration with AWS analytics services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - Data Catalog\n  - Data Governance\n  - Data Management\n  - Data Sharing\n  - Analytics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-datazone/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-datazone:amazon-datazone-api\n\
  \    name: Amazon DataZone API\n    description: >-\n      The Amazon DataZone API provides programmatic access to create and manage\n      data domains, data assets, data catalogs, projects, subscriptions, and\n      governance policies for enterprise-wide data management and sharing.\n      Supports domain-based governance, asset cataloging, subscription workflows,\n      and environment provisioning for data analytics access.\n    humanURL: https://aws.amazon.com/datazone/\n    baseURL: https://datazone.amazonaws.com\n    tags:\n      - Data Catalog\n      - Data Governance\n      - Data Sharing\n      - Analytics\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/datazone/latest/APIReference/Welcome.html\n      - type: OpenAPI\n        url: openapi/amazon-datazone-openapi.yml\n      - type: OpenAPI\n        url: https://api.apis.guru/v2/specs/amazonaws.com/datazone/2018-05-10/openapi.yaml\n      - type: GettingStarted\n        url: https://aws.amazon.com/datazone/getting-started/\n\
  \      - type: Pricing\n        url: https://aws.amazon.com/datazone/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/datazone/faqs/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/datazone/latest/APIReference/\n      - type: JSONSchema\n        url: json-schema/domain-schema.json\n      - type: JSONSchema\n        url: json-schema/project-schema.json\n      - type: JSONSchema\n        url: json-schema/asset-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-datazone-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/datazone/\n  - type: DeveloperPortal\n    url: https://aws.amazon.com/datazone/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/datazone/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: Blog\n    url: https://aws.amazon.com/blogs/big-data/\n\
  \  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: Console\n    url: https://console.aws.amazon.com/datazone/\n  - type: SignUp\n    url: https://portal.aws.amazon.com/billing/signup\n  - type: Login\n    url: https://signin.aws.amazon.com/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: Contact\n    url: https://aws.amazon.com/contact-us/\n  - type: SpectralRules\n    url: rules/amazon-datazone-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-datazone-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/data-catalog-operations.yaml\n  - type: NaftikoCapability\n    url: capabilities/shared/datazone.yaml\n  - type: Features\n    data:\n      - name: Business Data Catalog\n        description: >-\n          Central catalog where data producers publish assets and data consumers\n          can discover, understand, and request access to data products.\n      - name: Domain-Based Governance\n \
  \       description: >-\n          Organize data assets, users, and governance policies within domains\n          that reflect your organizational structure and data ownership.\n      - name: Subscription Workflow\n        description: >-\n          Built-in request/approval workflow for data consumers to request\n          access to data assets with business justification and audit trail.\n      - name: Project Workspaces\n        description: >-\n          Isolated project containers within domains where teams organize\n          their data assets, environments, and members.\n      - name: Analytics Environment Provisioning\n        description: >-\n          Automatically provision data access environments with Athena, Glue,\n          Redshift, or other tools when subscriptions are approved.\n      - name: Glue Data Catalog Integration\n        description: >-\n          Automatically discover and import tables from AWS Glue Data Catalog\n          into DataZone for cataloging and\
  \ governance.\n      - name: Data Lineage\n        description: >-\n          Track data lineage across assets to understand data origins,\n          transformations, and dependencies for trust and compliance.\n  - type: UseCases\n    data:\n      - name: Enterprise Data Marketplace\n        description: >-\n          Build an internal data marketplace where business units publish\n          their data products for discovery and consumption by other teams.\n      - name: Data Access Governance\n        description: >-\n          Implement governed data access with approval workflows ensuring\n          data consumers have proper authorization and business justification.\n      - name: Cross-Account Data Sharing\n        description: >-\n          Share data assets across AWS accounts within an organization using\n          DataZone's subscription and access management capabilities.\n      - name: Self-Service Analytics\n        description: >-\n          Enable analysts to discover and\
  \ access data independently through\n          the DataZone catalog with automatic environment provisioning.\n      - name: Regulatory Data Compliance\n        description: >-\n          Maintain audit trails of data access, govern sensitive data assets,\n          and enforce data residency policies through domain governance.\n  - type: Integrations\n    data:\n      - name: AWS Glue\n        description: >-\n          DataZone integrates with Glue Data Catalog to automatically discover,\n          import, and catalog Glue tables for sharing and governance.\n      - name: Amazon Redshift\n        description: >-\n          Catalog Redshift tables and views and govern cross-cluster data\n          sharing through DataZone subscription workflows.\n      - name: Amazon Athena\n        description: >-\n          DataZone environments provision Athena as a query engine for\n          subscribers accessing S3-based data assets.\n      - name: Amazon S3\n        description: >-\n          Catalog\
  \ S3-based datasets in DataZone and control access through\n          subscription-based Lake Formation permissions.\n      - name: AWS Lake Formation\n        description: >-\n          DataZone uses Lake Formation for fine-grained column and row-level\n          access control when subscriptions are approved.\n      - name: AWS IAM\n        description: >-\n          IAM roles provide domain execution context and identity-based access\n          control for DataZone resources and catalog operations.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-datazone/refs/heads/main/apis.yml
tags:
- Data Catalog
- Data Governance
- Data Management
- Data Sharing
- Analytics
url: https://raw.githubusercontent.com/api-evangelist/amazon-datazone/refs/heads/main/apis.yml
use_cases:
- description: Build an internal data marketplace where business units publish their data products for discovery and consumption by other teams.
  name: Enterprise Data Marketplace
- description: Implement governed data access with approval workflows ensuring data consumers have proper authorization and business justification.
  name: Data Access Governance
- description: Share data assets across AWS accounts within an organization using DataZone's subscription and access management capabilities.
  name: Cross-Account Data Sharing
- description: Enable analysts to discover and access data independently through the DataZone catalog with automatic environment provisioning.
  name: Self-Service Analytics
- description: Maintain audit trails of data access, govern sensitive data assets, and enforce data residency policies through domain governance.
  name: Regulatory Data Compliance
---
