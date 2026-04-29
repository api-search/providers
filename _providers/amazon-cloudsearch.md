---
api_count: 1
apis:
- description: API for creating and managing CloudSearch domains, uploading documents, configuring search fields and suggesters, and executing search queries.
  name: Amazon CloudSearch API
  slug: ''
capabilities:
- description: Workflow for search domain management using Amazon CloudSearch for Application Developer personas.
  name: Amazon CloudSearch Search Domain Management
  slug: search-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/cloudsearch/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/cloudsearch/latest/developerguide/what-is-cloudsearch.html
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
  url: https://console.aws.amazon.com/cloudsearch/
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
  url: https://stackoverflow.com/questions/tagged/amazon-cloudsearch
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: Compliance
  url: https://aws.amazon.com/compliance/
- title: ''
  type: SpectralRules
  url: rules/amazon-cloudsearch-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-cloudsearch-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/search-management.yaml
created: '2024-01-15'
description: Amazon CloudSearch is a managed search service that makes it easy to set up, manage, and scale a search solution for your website or application. Supports full-text search, Boolean search, faceted search, autocomplete, geospatial search, and 34 languages.
features:
- description: Set up, manage, and scale search without becoming a search expert.
  name: Managed Search Infrastructure
- description: Full-text search across 34 languages with language-specific analyzers.
  name: Multi-Language Support
- description: Narrow search results by category with faceted navigation.
  name: Faceted Search
- description: Real-time search suggestions as users type.
  name: Autocomplete Suggestions
- description: Automatically scale resources as data volume and query traffic change.
  name: Automatic Scaling
- description: Distribute search traffic across multiple availability zones with Multi-AZ.
  name: High Availability
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Index documents stored in S3 buckets.
  name: Amazon S3
- description: Search DynamoDB data by exporting to CloudSearch.
  name: Amazon DynamoDB
- description: Control access to search domains with IAM policies.
  name: AWS IAM
- description: Cache search results at CloudFront edge for lower latency.
  name: Amazon CloudFront
jsonld:
- class_count: 9
  name: Amazon Cloudsearch Context
  property_count: 16
  slug: amazon-cloudsearch-context
layout: provider
modified: '2026-04-19'
name: Amazon CloudSearch
rules:
- name: Amazon CloudSearch API Rules
  rule_count: 19
  severity_counts:
    error: 12
    hint: 0
    info: 1
    warn: 6
  slug: amazon-cloudsearch-spectral-rules
skills: []
slug: amazon-cloudsearch
solutions: []
source_yaml: "name: Amazon CloudSearch\ndescription: Amazon CloudSearch is a managed search service that makes it easy to set up, manage, and scale a search solution for your website or application. Supports full-text search, Boolean \n  search, faceted search, autocomplete, geospatial search, and 34 languages.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/cloudsearch/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon CloudSearch API\n  description: API for creating and managing CloudSearch domains, uploading documents, configuring search fields and suggesters, and executing search queries.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/cloudsearch/\n  baseURL: https://cloudsearch.us-east-1.amazonaws.com\n  tags:\n  - AWS\n  - CloudSearch\n  - Search\n  - Full-Text Search\n  properties:\n  - type: OpenAPI\n    url: openapi/amazon-cloudsearch-openapi.yml\n\
  \  - type: Documentation\n    url: https://docs.aws.amazon.com/cloudsearch/latest/developerguide/what-is-cloudsearch.html\n  - type: GettingStarted\n    url: https://aws.amazon.com/cloudsearch/getting-started/\n  - type: Pricing\n    url: https://aws.amazon.com/cloudsearch/pricing/\n  - type: FAQ\n    url: https://aws.amazon.com/cloudsearch/faqs/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/cloudsearch/latest/developerguide/what-is-cloudsearch.html\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/cloudsearch/\n  - type: JSONSchema\n    url: json-schema/cloudsearch-create-domain-request-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudsearch-create-domain-response-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudsearch-describe-domains-response-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudsearch-delete-domain-response-schema.json\n  - type: JSONSchema\n    url: json-schema/cloudsearch-domain-status-schema.json\n\
  \  - type: JSONLD\n    url: json-ld/amazon-cloudsearch-context.jsonld\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Website\n  url: https://aws.amazon.com/cloudsearch/\n- type: Documentation\n  url: https://docs.aws.amazon.com/cloudsearch/latest/developerguide/what-is-cloudsearch.html\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/compute/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/cloudsearch/\n- type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: StackOverflow\n  url: https://stackoverflow.com/questions/tagged/amazon-cloudsearch\n\
  - type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Compliance\n  url: https://aws.amazon.com/compliance/\n- type: SpectralRules\n  url: rules/amazon-cloudsearch-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-cloudsearch-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/search-management.yaml\n- type: Features\n  data:\n  - name: Managed Search Infrastructure\n    description: Set up, manage, and scale search without becoming a search expert.\n  - name: Multi-Language Support\n    description: Full-text search across 34 languages with language-specific analyzers.\n  - name: Faceted Search\n    description: Narrow search results by category with faceted navigation.\n  - name: Autocomplete Suggestions\n    description: Real-time search suggestions as users type.\n  - name: Automatic Scaling\n    description: Automatically scale resources as data volume and query traffic change.\n  - name: High Availability\n    description: Distribute search\
  \ traffic across multiple availability zones with Multi-AZ.\n- type: UseCases\n  data:\n  - name: Website Search\n    description: Add powerful full-text search capabilities to websites and web applications.\n  - name: E-Commerce Product Search\n    description: Enable customers to find products with faceted filtering and relevance ranking.\n  - name: Document Search\n    description: Search across large document repositories with Boolean and proximity search.\n  - name: Geospatial Search\n    description: Find resources by location with geospatial search queries.\n- type: Integrations\n  data:\n  - name: Amazon S3\n    description: Index documents stored in S3 buckets.\n  - name: Amazon DynamoDB\n    description: Search DynamoDB data by exporting to CloudSearch.\n  - name: AWS IAM\n    description: Control access to search domains with IAM policies.\n  - name: Amazon CloudFront\n    description: Cache search results at CloudFront edge for lower latency.\nmaintainers:\n- FN: Kin Lane\n\
  \  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- CloudSearch\n- Search\n- Full-Text Search\n- Managed\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-cloudsearch/refs/heads/main/apis.yml
tags:
- AWS
- CloudSearch
- Search
- Full-Text Search
- Managed
url: https://aws.amazon.com/cloudsearch/
use_cases:
- description: Add powerful full-text search capabilities to websites and web applications.
  name: Website Search
- description: Enable customers to find products with faceted filtering and relevance ranking.
  name: E-Commerce Product Search
- description: Search across large document repositories with Boolean and proximity search.
  name: Document Search
- description: Find resources by location with geospatial search queries.
  name: Geospatial Search
---
