---
api_count: 4
apis:
- description: Extensible Markup Language (XML) 1.0 is the foundational W3C Recommendation defining the syntax and processing model for XML documents. First published in 1998 and now in its Fifth Edition (2008), XML
  name: XML 1.0
  slug: xml-10
- description: Extensible Markup Language (XML) 1.1 is a W3C Recommendation published in 2006 that extends XML 1.0 to support newer Unicode versions, additional line ending characters, and a broader set of name char
  name: XML 1.1
  slug: xml-11
- description: Namespaces in XML 1.0 (Third Edition) is the W3C Recommendation that defines a mechanism for qualifying element and attribute names in XML documents using URI references. XML Namespaces allow vocabula
  name: XML Namespaces
  slug: xml-namespaces
- description: XML Schema Definition Language (XSD) is the W3C Recommendation for describing the structure and constraints of XML documents using an XML-based grammar. XSD 1.1 is the current version and provides ele
  name: XML Schema (XSD)
  slug: xml-schema
common:
- title: ''
  type: Website
  url: https://www.w3.org/XML/
- title: ''
  type: Documentation
  url: https://www.w3.org/TR/xml/
- title: ''
  type: Specification
  url: https://www.w3.org/TR/xml/
- title: ''
  type: GitHub Organization
  url: https://github.com/w3c
- title: ''
  type: GitHub Repository
  url: https://github.com/w3c/xml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-schema/xml-document-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-schema/xml-element-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-structure/xml-document-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-ld/xml-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/vocabulary/xml-vocabulary.yml
created: '2025'
description: XML (Extensible Markup Language) is a W3C standard markup language and data format that defines rules for encoding documents in a way that is both human-readable and machine-readable. Originally published as a W3C Recommendation in 1998 (XML 1.0), XML provides the foundation for a wide ecosystem of related standards including XML Schema, XSLT, XPath, XQuery, SOAP, XHTML, SVG, RSS, Atom, and many domain-specific vocabularies. XML remains a core data interchange format for enterprise systems, web services, configuration, and document publishing.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Xml Context
  property_count: 36
  slug: xml-context
layout: provider
modified: '2026-05-03'
name: XML
skills: []
slug: xml
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: xml\nname: XML\ndescription: >-\n  XML (Extensible Markup Language) is a W3C standard markup language and data format that\n  defines rules for encoding documents in a way that is both human-readable and machine-readable.\n  Originally published as a W3C Recommendation in 1998 (XML 1.0), XML provides the foundation\n  for a wide ecosystem of related standards including XML Schema, XSLT, XPath, XQuery, SOAP,\n  XHTML, SVG, RSS, Atom, and many domain-specific vocabularies. XML remains a core data\n  interchange format for enterprise systems, web services, configuration, and document publishing.\ntype: Index\nurl: https://www.w3.org/XML/\ntags:\n  - Data Formats\n  - Document\n  - Markup Language\n  - Standard\n  - W3C\n  - Web Services\n  - XML\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: xml:xml-10\n    name: XML 1.0\n    description: >-\n      Extensible Markup Language (XML) 1.0 is the foundational W3C Recommendation defining\n\
  \      the syntax and processing model for XML documents. First published in 1998 and now in\n      its Fifth Edition (2008), XML 1.0 specifies well-formedness, validity, character encoding,\n      and the basic constructs (elements, attributes, namespaces, processing instructions,\n      comments, and entities) that all XML technologies build upon.\n    humanURL: https://www.w3.org/TR/xml/\n    tags:\n      - Document\n      - Markup Language\n      - Standard\n      - W3C\n      - XML\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/xml/\n      - type: Specification\n        url: https://www.w3.org/TR/xml/\n  - aid: xml:xml-11\n    name: XML 1.1\n    description: >-\n      Extensible Markup Language (XML) 1.1 is a W3C Recommendation published in 2006 that\n      extends XML 1.0 to support newer Unicode versions, additional line ending characters,\n      and a broader set of name characters. XML 1.1 is rarely deployed in practice; XML 1.0\n      remains\
  \ the dominant version used in production systems.\n    humanURL: https://www.w3.org/TR/xml11/\n    tags:\n      - Document\n      - Markup Language\n      - Standard\n      - W3C\n      - XML\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/TR/xml11/\n      - type: Specification\n        url: https://www.w3.org/TR/xml11/\n  - aid: xml:xml-namespaces\n    name: XML Namespaces\n    description: >-\n      Namespaces in XML 1.0 (Third Edition) is the W3C Recommendation that defines a mechanism\n      for qualifying element and attribute names in XML documents using URI references. XML\n      Namespaces allow vocabularies from different sources to be combined in a single document\n      without naming collisions, and underpin every modern XML application including XHTML,\n      SOAP, XSLT, and SVG.\n    humanURL: https://www.w3.org/TR/xml-names/\n    tags:\n      - Namespaces\n      - Standard\n      - W3C\n      - XML\n    properties:\n      - type: Documentation\n\
  \        url: https://www.w3.org/TR/xml-names/\n      - type: Specification\n        url: https://www.w3.org/TR/xml-names/\n  - aid: xml:xml-schema\n    name: XML Schema (XSD)\n    description: >-\n      XML Schema Definition Language (XSD) is the W3C Recommendation for describing the\n      structure and constraints of XML documents using an XML-based grammar. XSD 1.1 is the\n      current version and provides element/attribute declarations, complex and simple types,\n      keys/keyrefs, assertions, and conditional type assignment.\n    humanURL: https://www.w3.org/XML/Schema\n    tags:\n      - Schema\n      - Standard\n      - Validation\n      - W3C\n      - XML\n    properties:\n      - type: Documentation\n        url: https://www.w3.org/XML/Schema\n      - type: Specification\n        url: https://www.w3.org/TR/xmlschema11-1/\ncommon:\n  - type: Website\n    url: https://www.w3.org/XML/\n  - type: Documentation\n    url: https://www.w3.org/TR/xml/\n  - type: Specification\n    url:\
  \ https://www.w3.org/TR/xml/\n  - type: GitHub Organization\n    url: https://github.com/w3c\n  - type: GitHub Repository\n    url: https://github.com/w3c/xml\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-schema/xml-document-schema.json\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-schema/xml-element-schema.json\n  - type: JSONStructure\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-structure/xml-document-structure.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-ld/xml-context.jsonld\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/vocabulary/xml-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/apis.yml
tags:
- Data Formats
- Document
- Markup Language
- Standard
- W3C
- Web Services
- XML
url: https://www.w3.org/XML/
use_cases: []
---
