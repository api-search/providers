---
api_count: 6
apis:
- description: The CFF schema defines the structure of a CITATION.cff file in YAML, including required cff-version, message, and authors fields plus optional version, doi, license, repository-code, preferred-citatio
  name: Citation File Format Schema
  slug: cff-schema
- description: cffinit is a web-based form that walks software authors through creating a syntactically and semantically valid CITATION.cff file. It produces downloadable YAML and validates content against the CFF s
  name: cffinit Authoring Tool
  slug: cffinit
- description: cffconvert is a Python command-line tool and library that converts CITATION.cff files to APA plain text, BibTeX, CodeMeta, EndNote, RIS, schema.org JSON-LD, and Zenodo deposition JSON. It also validat
  name: cffconvert
  slug: cffconvert
- description: The cff-validator GitHub Action runs schema validation on a repository's CITATION.cff during continuous integration so that malformed or non-compliant citation metadata is caught before release.
  name: cff-validator GitHub Action
  slug: cff-validator
- description: GitHub natively reads CITATION.cff files and renders a Cite this repository button on the repository landing page that generates BibTeX and APA snippets from the file's metadata.
  name: GitHub Native Citation Support
  slug: github-citation-integration
- description: The GitHub-Zenodo integration uses CITATION.cff metadata when publishing a release as a citable software record. Zenodo assigns a DOI and populates the deposit form from the CFF file's authors, title,
  name: Zenodo Software Publishing
  slug: zenodo-integration
common:
- title: ''
  type: Website
  url: https://citation-file-format.github.io/
- title: ''
  type: Documentation
  url: https://github.com/citation-file-format/citation-file-format
- title: ''
  type: Schema Guide
  url: https://github.com/citation-file-format/citation-file-format/blob/main/schema-guide.md
- title: ''
  type: Schema
  url: https://github.com/citation-file-format/citation-file-format/blob/main/schema.json
- title: ''
  type: GitHub
  url: https://github.com/citation-file-format
- title: ''
  type: Governance
  url: https://github.com/citation-file-format/governance
- title: ''
  type: Issues
  url: https://github.com/citation-file-format/citation-file-format/issues
- title: ''
  type: License
  url: https://github.com/citation-file-format/citation-file-format/blob/main/LICENSE
- title: ''
  type: Citation
  url: https://github.com/citation-file-format/citation-file-format/blob/main/CITATION.cff
- title: ''
  type: JSON-LD
  url: json-ld/citation-cff-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/citation-cff-schema.json
- title: ''
  type: Spectral
  url: rules/citation-cff-rules.yml
created: '2025-01-01'
description: The Citation File Format (CFF) is a human- and machine-readable YAML schema for providing citation metadata for software and datasets in source code repositories. A CITATION.cff file at the root of a repository declares authors, version, DOI, release date, and reference metadata, enabling consistent academic attribution across publishing and discovery platforms. CFF is governed as an open community standard with a published JSON Schema, a guide, and a maintained schema repository on GitHub. Native integrations include GitHub citation display, Zenodo software publishing, and the Zotero browser plugin. Tooling includes cffinit for authoring, cffconvert for conversion to BibTeX/RIS/CodeMeta/EndNote formats, and the cff-validator GitHub Action for CI validation. The current schema version is 1.2.0.
features: []
image: ''
integrations: []
jsonld:
- class_count: 26
  name: Citation Cff Context
  property_count: 0
  slug: citation-cff-context
layout: provider
modified: '2026-04-23'
name: Citation File Format
rules:
- name: Citation File Format API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 6
  slug: citation-cff-rules
skills: []
slug: citation-cff
solutions: []
tags:
- Academic
- Citation
- Metadata
- Open Standard
- Repository
- Research
- Software
- YAML
url: https://raw.githubusercontent.com/api-evangelist/citation-cff/refs/heads/main/apis.yml
use_cases: []
---
