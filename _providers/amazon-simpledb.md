---
api_count: 1
api_specs:
- filename: amazon-simpledb.yaml
  format: yaml
  label: Amazon SimpleDB API
  slug: amazon-simpledb-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-simpledb/refs/heads/main/openapi/amazon-simpledb.yaml
apis:
- description: The Amazon SimpleDB API provides programmatic access to create and manage domains, items, and attributes for simple NoSQL data storage and querying of structured data in the cloud.
  name: Amazon SimpleDB API
  slug: amazon-simpledb-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/simpledb/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/AmazonSimpleDB/latest/DeveloperGuide/Welcome.html
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
  url: https://aws.amazon.com/blogs/database/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/simpledb/
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
  url: rules/amazon-simpledb-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-simpledb-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/amazon-simpledb.yaml
created: '2026-03-16'
description: Amazon SimpleDB is a highly available NoSQL data store that offloads the work of database administration. It provides simple and powerful data storage and querying capabilities to enable you to build web applications with structured data storage without the overhead of database administration.
features:
- description: NoSQL data store with no database administration overhead.
  name: Simple Data Storage
- description: Store structured data without a predefined schema.
  name: Schema-less
- description: Automatically replicated data across multiple availability zones.
  name: High Availability
- description: Query data using a simple SELECT expression language.
  name: Select Query Language
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Store metadata for S3 objects in SimpleDB.
  name: Amazon S3
- description: Store instance metadata and configuration in SimpleDB.
  name: Amazon EC2
- description: Audit SimpleDB API calls via CloudTrail.
  name: AWS CloudTrail
jsonld:
- class_count: 39
  name: Amazon Simpledb Context
  property_count: 24
  slug: amazon-simpledb-context
layout: provider
modified: '2026-04-19'
name: Amazon SimpleDB
rules:
- name: Amazon SimpleDB API Rules
  rule_count: 19
  severity_counts:
    error: 11
    hint: 0
    info: 1
    warn: 7
  slug: amazon-simpledb-spectral-rules
skills: []
slug: amazon-simpledb
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-simpledb\nname: Amazon SimpleDB\ndescription: >-\n  Amazon SimpleDB is a highly available NoSQL data store that offloads the\n  work of database administration. It provides simple and powerful data\n  storage and querying capabilities to enable you to build web applications\n  with structured data storage without the overhead of database administration.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- AWS\n- Cloud Storage\n- Data Storage\n- Database\n- NoSQL\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-simpledb/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: amazon-simpledb:amazon-simpledb-api\n  name: Amazon SimpleDB API\n  description: >-\n    The Amazon SimpleDB API provides programmatic access to create and\n    manage domains, items, and attributes for simple NoSQL data storage\n    and querying of structured data\
  \ in the cloud.\n  humanURL: https://aws.amazon.com/simpledb/\n  baseURL: https://sdb.amazonaws.com\n  tags:\n  - Data Storage\n  - Database\n  - NoSQL\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/AmazonSimpleDB/latest/DeveloperGuide/Welcome.html\n  - type: OpenAPI\n    url: openapi/amazon-simpledb.yaml\n  - type: GettingStarted\n    url: https://aws.amazon.com/simpledb/\n  - type: Pricing\n    url: https://aws.amazon.com/simpledb/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/simpledb/faqs/\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/simpledb/\n- type: Documentation\n  url: https://docs.aws.amazon.com/AmazonSimpleDB/latest/DeveloperGuide/Welcome.html\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/database/\n- type: GitHubOrganization\n\
  \  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/simpledb/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Login\n  url: https://signin.aws.amazon.com/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: SpectralRules\n  url: rules/amazon-simpledb-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-simpledb-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/amazon-simpledb.yaml\n- type: Features\n  data:\n  - name: Simple Data Storage\n    description: NoSQL data store with no database administration overhead.\n  - name: Schema-less\n    description: Store structured data without a predefined schema.\n  - name: High Availability\n    description: Automatically replicated data across multiple availability zones.\n  - name: Select Query Language\n    description: Query data using a simple SELECT expression\
  \ language.\n- type: UseCases\n  data:\n  - name: Web Application Data Storage\n    description: Store and query structured data for web applications.\n  - name: User Profile Storage\n    description: Store user attributes and preferences without schema management.\n  - name: Metadata Storage\n    description: Store metadata for files, media, or other cloud resources.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Store metadata for S3 objects in SimpleDB.\n  - name: Amazon EC2\n    description: Store instance metadata and configuration in SimpleDB.\n  - name: AWS CloudTrail\n    description: Audit SimpleDB API calls via CloudTrail.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nx-type: company\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-simpledb/refs/heads/main/apis.yml
tags:
- AWS
- Cloud Storage
- Data Storage
- Database
- NoSQL
url: https://raw.githubusercontent.com/api-evangelist/amazon-simpledb/refs/heads/main/apis.yml
use_cases:
- description: Store and query structured data for web applications.
  name: Web Application Data Storage
- description: Store user attributes and preferences without schema management.
  name: User Profile Storage
- description: Store metadata for files, media, or other cloud resources.
  name: Metadata Storage
---
