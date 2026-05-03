---
api_count: 2
api_specs:
- filename: web-of-science-starter-openapi.yml
  format: yaml
  label: Web of Science Starter API
  slug: web-of-science-starter-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/web-of-science-apis/refs/heads/main/openapi/web-of-science-starter-openapi.yml
- filename: web-of-science-expanded-openapi.yml
  format: yaml
  label: Web of Science API Expanded
  slug: web-of-science-expanded-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/web-of-science-apis/refs/heads/main/openapi/web-of-science-expanded-openapi.yml
apis:
- description: 'The Web of Science Starter API provides basic bibliographic metadata search and retrieval for Web of Science documents and journals. It supports document search using advanced query syntax, retrieval '
  name: Web of Science Starter API
  slug: web-of-science-starter-api
- description: The Web of Science API Expanded provides rich bibliographic searching, citation tracking (citing articles and references), related records discovery, and citation reporting with h-index and bibliometr
  name: Web of Science API Expanded
  slug: web-of-science-expanded-api
capabilities:
- description: Unified academic research workflow combining Web of Science Starter and Expanded APIs for bibliographic search, citation analysis, journal discovery, and bibliometric reporting. Used by researchers, l
  name: Web of Science Academic Research
  slug: academic-research
common:
- title: ''
  type: Documentation
  url: https://developer.clarivate.com/apis/wos-starter
- title: ''
  type: Website
  url: https://clarivate.com/products/scientific-and-academic-research/research-discovery-and-referencing/web-of-science/
- title: ''
  type: DeveloperPortal
  url: https://developer.clarivate.com
- title: ''
  type: Support
  url: https://developer.clarivate.com/support
- title: ''
  type: TermsOfService
  url: https://clarivate.com/legal/terms-conditions/
- title: ''
  type: PrivacyPolicy
  url: https://clarivate.com/privacy-statement/
- title: ''
  type: Blog
  url: https://clarivate.com/blog/
- title: ''
  type: SpectralRules
  url: rules/web-of-science-spectral-rules.yml
- title: Academic Research Capability
  type: NaftikoCapability
  url: capabilities/academic-research.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/web-of-science-vocabulary.yml
created: '2025-02-06'
description: The Web of Science APIs provide programmatic access to Clarivate's Web of Science databases, the world's leading citation index covering over 21,000 peer-reviewed journals across the sciences, social sciences, and humanities. The API suite includes the Starter API for basic bibliographic metadata and journal discovery, and the Expanded API for advanced search, citation tracking, related records, and bibliometric reporting with h-index and year-by-year citation analysis.
features:
- description: Search over 100 million records using Web of Science Advanced Query Syntax with 16 searchable field tags including topic, author, DOI, organization, and funding agency.
  name: Advanced Document Search
- description: Track forward citations (articles citing a paper) and backward citations (reference list) to understand the full citation network of any paper.
  name: Citation Tracking
- description: Generate citation reports with h-index, total citations, average citations per item, and year-by-year citation and publication counts.
  name: Bibliometric Reporting
- description: Find research papers related to a given article by identifying records that share cited references.
  name: Related Records Discovery
- description: Retrieve journal information including ISSN, publisher, subject categories, and Journal Citation Reports profile URL.
  name: Journal Metadata
- description: Search across 12 Web of Science databases including Core Collection, MEDLINE, BIOSIS, and Zoological Record.
  name: Multi-Database Search
- description: Access real-time times-cited counts for documents across Web of Science databases for impact assessment.
  name: Times-Cited Counts
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Web Of Science Context
  property_count: 113
  slug: web-of-science-context
layout: provider
modified: '2026-05-03'
name: Web of Science APIs
rules:
- name: Web of Science APIs API Rules
  rule_count: 22
  severity_counts:
    error: 8
    hint: 0
    info: 7
    warn: 7
  slug: web-of-science-spectral-rules
skills: []
slug: web-of-science-apis
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: web-of-science-apis\nname: Web of Science APIs\ndescription: >-\n  The Web of Science APIs provide programmatic access to Clarivate's Web of\n  Science databases, the world's leading citation index covering over 21,000\n  peer-reviewed journals across the sciences, social sciences, and humanities.\n  The API suite includes the Starter API for basic bibliographic metadata and\n  journal discovery, and the Expanded API for advanced search, citation\n  tracking, related records, and bibliometric reporting with h-index and\n  year-by-year citation analysis.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Research\n  - Academic\n  - Bibliometrics\n  - Citations\n  - Science\n  - Scholarly\nurl: https://raw.githubusercontent.com/api-evangelist/web-of-science-apis/refs/heads/main/apis.yml\ncreated: '2025-02-06'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid:\
  \ web-of-science-apis:web-of-science-starter-api\n    name: Web of Science Starter API\n    description: >-\n      The Web of Science Starter API provides basic bibliographic metadata\n      search and retrieval for Web of Science documents and journals. It\n      supports document search using advanced query syntax, retrieval by\n      unique identifier, and journal lookup by ISSN or name.\n    humanURL: https://developer.clarivate.com/apis/wos-starter\n    tags:\n      - Research\n      - Documents\n      - Journals\n      - Bibliometrics\n    properties:\n      - url: openapi/web-of-science-starter-openapi.yml\n        type: OpenAPI\n      - url: https://developer.clarivate.com/apis/wos-starter\n        type: Documentation\n      - url: https://developer.clarivate.com/apis/wos-starter/swagger\n        type: SwaggerUI\n  - aid: web-of-science-apis:web-of-science-expanded-api\n    name: Web of Science API Expanded\n    description: >-\n      The Web of Science API Expanded provides rich\
  \ bibliographic searching,\n      citation tracking (citing articles and references), related records\n      discovery, and citation reporting with h-index and bibliometric\n      statistics. Requires a paid subscription.\n    humanURL: https://developer.clarivate.com/apis/wos\n    tags:\n      - Research\n      - Citations\n      - Bibliometrics\n      - Search\n      - Reports\n    properties:\n      - url: openapi/web-of-science-expanded-openapi.yml\n        type: OpenAPI\n      - url: https://developer.clarivate.com/apis/wos\n        type: Documentation\n      - url: https://developer.clarivate.com/apis/wos/swagger\n        type: SwaggerUI\ncommon:\n  - url: https://developer.clarivate.com/apis/wos-starter\n    type: Documentation\n  - url: https://clarivate.com/products/scientific-and-academic-research/research-discovery-and-referencing/web-of-science/\n    type: Website\n  - url: https://developer.clarivate.com\n    type: DeveloperPortal\n  - url: https://developer.clarivate.com/support\n\
  \    type: Support\n  - url: https://clarivate.com/legal/terms-conditions/\n    type: TermsOfService\n  - url: https://clarivate.com/privacy-statement/\n    type: PrivacyPolicy\n  - url: https://clarivate.com/blog/\n    type: Blog\n  - type: SpectralRules\n    url: rules/web-of-science-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/academic-research.yaml\n    title: Academic Research Capability\n  - type: Vocabulary\n    url: vocabulary/web-of-science-vocabulary.yml\n  - type: Features\n    data:\n      - name: Advanced Document Search\n        description: >-\n          Search over 100 million records using Web of Science Advanced Query\n          Syntax with 16 searchable field tags including topic, author, DOI,\n          organization, and funding agency.\n      - name: Citation Tracking\n        description: >-\n          Track forward citations (articles citing a paper) and backward\n          citations (reference list) to understand the full citation network\n\
  \          of any paper.\n      - name: Bibliometric Reporting\n        description: >-\n          Generate citation reports with h-index, total citations, average\n          citations per item, and year-by-year citation and publication counts.\n      - name: Related Records Discovery\n        description: >-\n          Find research papers related to a given article by identifying\n          records that share cited references.\n      - name: Journal Metadata\n        description: >-\n          Retrieve journal information including ISSN, publisher, subject\n          categories, and Journal Citation Reports profile URL.\n      - name: Multi-Database Search\n        description: >-\n          Search across 12 Web of Science databases including Core Collection,\n          MEDLINE, BIOSIS, and Zoological Record.\n      - name: Times-Cited Counts\n        description: >-\n          Access real-time times-cited counts for documents across Web of\n          Science databases for impact assessment.\n\
  \  - type: UseCases\n    data:\n      - name: Literature Review Automation\n        description: >-\n          Automate systematic literature review by programmatically searching\n          and retrieving bibliographic metadata from Web of Science.\n      - name: Research Impact Analysis\n        description: >-\n          Analyze the impact of publications or researchers using citation\n          counts, h-index, and bibliometric reports.\n      - name: Citation Network Analysis\n        description: >-\n          Build citation networks by tracing forward and backward citations\n          to map the intellectual lineage of research topics.\n      - name: Journal Selection\n        description: >-\n          Identify appropriate journals for manuscript submission by\n          searching journal metadata and impact metrics.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/web-of-science-apis/refs/heads/main/apis.yml
tags:
- Research
- Academic
- Bibliometrics
- Citations
- Science
- Scholarly
url: https://raw.githubusercontent.com/api-evangelist/web-of-science-apis/refs/heads/main/apis.yml
use_cases:
- description: Automate systematic literature review by programmatically searching and retrieving bibliographic metadata from Web of Science.
  name: Literature Review Automation
- description: Analyze the impact of publications or researchers using citation counts, h-index, and bibliometric reports.
  name: Research Impact Analysis
- description: Build citation networks by tracing forward and backward citations to map the intellectual lineage of research topics.
  name: Citation Network Analysis
- description: Identify appropriate journals for manuscript submission by searching journal metadata and impact metrics.
  name: Journal Selection
---
