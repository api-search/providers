---
api_count: 3
apis:
- description: 'XSLT 3.0 is the current W3C Recommendation for XSL Transformations, published June 8, 2017. It introduces streaming support, maps and arrays, higher-order functions, improved modularity, and enhanced '
  name: XSLT 3.0
  slug: xslt-30
- description: 'XSLT 2.0 is a W3C Recommendation published January 23, 2007. It significantly enhanced XSLT 1.0 with type system integration from XML Schema, grouping, multiple result documents, regular expressions, '
  name: XSLT 2.0
  slug: xslt-20
- description: XSLT 1.0 is the foundational W3C Recommendation for XSL Transformations, published November 16, 1999. It established the template-based transformation model using XPath 1.0 for node selection. XSLT 1.
  name: XSLT 1.0
  slug: xslt-10
common:
- title: ''
  type: Website
  url: https://www.w3.org/TR/xslt/
- title: ''
  type: Documentation
  url: https://www.w3.org/TR/xslt-30/
- title: ''
  type: GitHub Organization
  url: https://github.com/w3c
- title: ''
  type: GitHub Repository
  url: https://github.com/Saxonica/Saxon-HE
- title: ''
  type: Specification
  url: https://www.w3.org/TR/xslt-30/
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-schema/xslt-stylesheet-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-schema/xslt-transformation-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-structure/xslt-stylesheet-structure.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-structure/xslt-transformation-structure.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/examples/xslt-stylesheet-example.json
- title: ''
  type: Example
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/examples/xslt-transformation-example.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-ld/xslt-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/vocabulary/xslt-vocabulary.yml
created: '2025'
description: XSLT (Extensible Stylesheet Language Transformations) is a W3C standard language for transforming XML documents into other formats such as HTML, plain text, or different XML structures. It uses template-based rules and XPath expressions to select and restructure XML data. The current version is XSLT 3.0, a W3C Recommendation since June 2017. XSLT is commonly used in data integration, document publishing, and enterprise data exchange pipelines. The primary production implementation is Saxon by Saxonica, which supports XSLT 3.0, XQuery 3.1, and XPath 3.1.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Xslt Context
  property_count: 29
  slug: xslt-context
layout: provider
modified: '2026-05-03'
name: XSLT
skills: []
slug: xslt
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: xslt\nname: XSLT\ndescription: >-\n  XSLT (Extensible Stylesheet Language Transformations) is a W3C standard language for\n  transforming XML documents into other formats such as HTML, plain text, or different\n  XML structures. It uses template-based rules and XPath expressions to select and\n  restructure XML data. The current version is XSLT 3.0, a W3C Recommendation since\n  June 2017. XSLT is commonly used in data integration, document publishing, and\n  enterprise data exchange pipelines. The primary production implementation is Saxon\n  by Saxonica, which supports XSLT 3.0, XQuery 3.1, and XPath 3.1.\ntype: Index\nurl: https://www.w3.org/TR/xslt-30/\ntags:\n  - Data Transformation\n  - Standard\n  - W3C\n  - XML\n  - XSLT\n  - XPath\ncreated: '2025'\nmodified: '2026-05-03'\n\nspecificationVersion: '0.19'\napis:\n  - aid: xslt:xslt-30\n    name: XSLT 3.0\n    description: >-\n      XSLT 3.0 is the current W3C Recommendation for XSL Transformations, published\n  \
  \    June 8, 2017. It introduces streaming support, maps and arrays, higher-order\n      functions, improved modularity, and enhanced error handling over XSLT 2.0. The\n      specification defines the syntax and semantics of the XSLT language.\n    humanURL: https://www.w3.org/TR/xslt-30/\n    tags:\n      - Data Transformation\n      - Standard\n      - W3C\n      - XML\n      - XSLT\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/xslt-30/\n      - type: Specification\n        url: https://www.w3.org/TR/xslt-30/\n  - aid: xslt:xslt-20\n    name: XSLT 2.0\n    description: >-\n      XSLT 2.0 is a W3C Recommendation published January 23, 2007. It significantly\n      enhanced XSLT 1.0 with type system integration from XML Schema, grouping,\n      multiple result documents, regular expressions, improved string handling, and\n      user-defined functions. Second edition published 2009.\n    humanURL: https://www.w3.org/TR/xslt20/\n    tags:\n      - Data\
  \ Transformation\n      - Standard\n      - W3C\n      - XML\n      - XSLT\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/xslt20/\n      - type: Specification\n        url: https://www.w3.org/TR/xslt20/\n  - aid: xslt:xslt-10\n    name: XSLT 1.0\n    description: >-\n      XSLT 1.0 is the foundational W3C Recommendation for XSL Transformations, published\n      November 16, 1999. It established the template-based transformation model using\n      XPath 1.0 for node selection. XSLT 1.0 is still widely supported by all major\n      XML processors and browsers.\n    humanURL: https://www.w3.org/TR/xslt-10/\n    tags:\n      - Data Transformation\n      - Standard\n      - W3C\n      - XML\n      - XSLT\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/xslt-10/\n      - type: Specification\n        url: https://www.w3.org/TR/xslt-10/\ncommon:\n  - type: Website\n    url: https://www.w3.org/TR/xslt/\n  - type: Documentation\n\
  \    url: https://www.w3.org/TR/xslt-30/\n  - type: GitHub Organization\n    url: https://github.com/w3c\n  - type: GitHub Repository\n    url: https://github.com/Saxonica/Saxon-HE\n  - type: Specification\n    url: https://www.w3.org/TR/xslt-30/\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-schema/xslt-stylesheet-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-schema/xslt-transformation-schema.json\n  - type: JSONStructure\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-structure/xslt-stylesheet-structure.json\n  - type: JSONStructure\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-structure/xslt-transformation-structure.json\n  - type: Example\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/examples/xslt-stylesheet-example.json\n\
  \  - type: Example\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/examples/xslt-transformation-example.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-ld/xslt-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/vocabulary/xslt-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/apis.yml
tags:
- Data Transformation
- Standard
- W3C
- XML
- XSLT
- XPath
url: https://www.w3.org/TR/xslt-30/
use_cases: []
---
