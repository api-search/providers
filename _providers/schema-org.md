---
api_count: 4
apis:
- description: 'Schema.org is a collaborative, community-driven vocabulary for structured data on the internet. It provides a collection of shared vocabularies that webmasters and developers can use to mark up pages '
  name: Schema.org Vocabulary
  slug: ''
- description: The Schema.org JSON-LD Context provides the canonical JSON-LD context file for the Schema.org vocabulary. This context file maps Schema.org terms to their full IRIs, enabling JSON-LD processors to cor
  name: Schema.org JSON-LD Context
  slug: ''
- description: 'The Schema.org Markup Validator tests and validates structured data markup against the Schema.org vocabulary. It supports JSON-LD, Microdata, and RDFa formats and helps ensure structured data will be '
  name: Schema.org Markup Validator
  slug: ''
- description: The Schema.org WebAPI type defines a Web API accessible over Web and Internet technologies. It provides standardized properties for describing APIs including documentation URL, terms of service, provi
  name: Schema.org WebAPI Type
  slug: ''
common:
- title: ''
  type: Website
  url: https://schema.org/
- title: ''
  type: Documentation
  url: https://schema.org/docs/documents.html
- title: ''
  type: Blog
  url: https://blog.schema.org/
- title: ''
  type: Support
  url: https://github.com/schemaorg/schemaorg/issues
- title: ''
  type: SpectralRules
  url: rules/schema-org-rules.yml
- title: ''
  type: JSONLDContext
  url: json-ld/schema-org-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/schema-org-vocabulary.yml
created: '2026-05-02'
description: Schema.org is a collaborative, community-driven project that creates and maintains a shared vocabulary for structured data on the web. Founded by Google, Microsoft, Yahoo, and Yandex in 2011, it provides types and properties that developers and webmasters use to annotate content in formats like JSON-LD, RDFa, and Microdata, enabling search engines and applications to better understand web content. The vocabulary currently consists of 800+ Types, 1500+ Properties, and covers domains including commerce, healthcare, organizations, events, creative works, and more. The Schema.org WebAPI type provides a standardized vocabulary for describing APIs in structured data.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Schema Org Context
  property_count: 8
  slug: schema-org-context
layout: provider
modified: '2026-05-02'
name: Schema.org
rules:
- name: Schema.org API Rules
  rule_count: 10
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 5
  slug: schema-org-rules
skills: []
slug: schema-org
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Schema.org\ndescription: Schema.org is a collaborative, community-driven project that creates and maintains a shared vocabulary for structured data on the web. Founded by Google, Microsoft, Yahoo, and Yandex in 2011, it provides types and properties that developers and webmasters use to annotate content in formats like JSON-LD, RDFa, and Microdata, enabling search engines and applications to better understand web content. The vocabulary currently consists of 800+ Types, 1500+ Properties, and covers domains including commerce, healthcare, organizations, events, creative works, and more. The Schema.org WebAPI type provides a standardized vocabulary for describing APIs in structured data.\nurl: https://github.com/api-evangelist/schema-org\nx-type: standard\ntags:\n- Schema.org\n- Structured Data\n- Linked Data\n- JSON-LD\n- Vocabulary\n- SEO\n- Web Standards\n- RDF\n- Ontology\ncreated: '2026-05-02'\nmodified: '2026-05-02'\napis:\n- name: Schema.org Vocabulary\n  description:\
  \ Schema.org is a collaborative, community-driven vocabulary for structured data on the internet. It provides a collection of shared vocabularies that webmasters and developers can use to mark up pages in ways recognized by major search engines. The vocabulary covers entities, relationships between entities, and actions. Machine-readable definitions are available in RDF/Turtle, JSON-LD, CSV, and other formats.\n  humanURL: https://schema.org/docs/developers.html\n  baseURL: https://schema.org\n  tags:\n  - Schema.org\n  - Vocabulary\n  - Structured Data\n  - Linked Data\n  - JSON-LD\n  - RDF\n  - Microdata\n  - RDFa\n  - SEO\n  - Web Standards\n  properties:\n  - type: Documentation\n    url: https://schema.org/docs/developers.html\n  - type: Reference\n    url: https://schema.org/docs/schemas.html\n  - type: DataModel\n    url: https://schema.org/docs/datamodel.html\n  - type: ChangeLog\n    url: https://schema.org/docs/releases.html\n  - type: GitHubRepository\n    url: https://github.com/schemaorg/schemaorg\n\
  \  - type: JSONSchema\n    url: json-schema/schema-org-thing-schema.json\n\n- name: Schema.org JSON-LD Context\n  description: The Schema.org JSON-LD Context provides the canonical JSON-LD context file for the Schema.org vocabulary. This context file maps Schema.org terms to their full IRIs, enabling JSON-LD processors to correctly interpret structured data markup. Google recommends JSON-LD as the preferred format for Schema.org structured data on websites.\n  humanURL: https://schema.org/docs/developers.html\n  baseURL: https://schema.org\n  tags:\n  - JSON-LD\n  - Linked Data\n  - Context\n  - Vocabulary\n  - Structured Data\n  properties:\n  - type: Documentation\n    url: https://schema.org/docs/developers.html\n  - type: JSON-LD Context\n    url: https://schema.org/docs/jsonldcontext.json\n\n- name: Schema.org Markup Validator\n  description: The Schema.org Markup Validator tests and validates structured data markup against the Schema.org vocabulary. It supports JSON-LD, Microdata,\
  \ and RDFa formats and helps ensure structured data will be correctly interpreted by search engines.\n  humanURL: https://validator.schema.org/\n  baseURL: https://validator.schema.org\n  tags:\n  - Validation\n  - Structured Data\n  - Testing\n  - Schema\n  - Markup\n  properties:\n  - type: Documentation\n    url: https://validator.schema.org/\n\n- name: Schema.org WebAPI Type\n  description: The Schema.org WebAPI type defines a Web API accessible over Web and Internet technologies. It provides standardized properties for describing APIs including documentation URL, terms of service, provider, and API entry point. The WebAPI type enables search engines and automated tools to discover and understand published APIs.\n  humanURL: https://schema.org/WebAPI\n  baseURL: https://schema.org\n  tags:\n  - WebAPI\n  - API Description\n  - Structured Data\n  - Linked Data\n  - Schema\n  properties:\n  - type: Documentation\n    url: https://schema.org/WebAPI\n  - type: JSONSchema\n    url: json-schema/schema-org-web-api-schema.json\n\
  \ncommon:\n- type: Website\n  url: https://schema.org/\n- type: Documentation\n  url: https://schema.org/docs/documents.html\n- type: Blog\n  url: https://blog.schema.org/\n- type: Support\n  url: https://github.com/schemaorg/schemaorg/issues\n- type: SpectralRules\n  url: rules/schema-org-rules.yml\n- type: JSONLDContext\n  url: json-ld/schema-org-context.jsonld\n- type: Vocabulary\n  url: vocabulary/schema-org-vocabulary.yml\nmaintainers:\n- FN: API Evangelist\n  email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/schema-org/refs/heads/main/apis.yml
tags:
- Schema.org
- Structured Data
- Linked Data
- JSON-LD
- Vocabulary
- SEO
- Web Standards
- RDF
- Ontology
url: https://github.com/api-evangelist/schema-org
use_cases: []
---
