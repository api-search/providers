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
source_filename: apis.yml
source_yaml: "aid: citation-cff\nname: Citation File Format\nurl: https://raw.githubusercontent.com/api-evangelist/citation-cff/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-23'\ntype: Standard\naccess: Open\nposition: Standard\nspecificationVersion: '0.19'\nx-type: standard\ntags:\n  - Academic\n  - Citation\n  - Metadata\n  - Open Standard\n  - Repository\n  - Research\n  - Software\n  - YAML\ndescription: >-\n  The Citation File Format (CFF) is a human- and machine-readable YAML\n  schema for providing citation metadata for software and datasets in\n  source code repositories. A CITATION.cff file at the root of a\n  repository declares authors, version, DOI, release date, and reference\n  metadata, enabling consistent academic attribution across publishing\n  and discovery platforms. CFF is governed as an open community standard\n  with a published JSON Schema, a guide, and a maintained schema\n  repository on GitHub. Native integrations include GitHub citation\n\
  \  display, Zenodo software publishing, and the Zotero browser plugin.\n  Tooling includes cffinit for authoring, cffconvert for conversion to\n  BibTeX/RIS/CodeMeta/EndNote formats, and the cff-validator GitHub\n  Action for CI validation. The current schema version is 1.2.0.\napis:\n  - aid: citation-cff:cff-schema\n    name: Citation File Format Schema\n    tags:\n      - JSON Schema\n      - Schema\n      - Validation\n      - YAML\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/citation-file-format/citation-file-format\n    properties:\n      - url: https://github.com/citation-file-format/citation-file-format/blob/main/schema.json\n        type: JSONSchema\n      - url: https://github.com/citation-file-format/citation-file-format/blob/main/README.md\n        type: Documentation\n      - url: https://github.com/citation-file-format/citation-file-format/blob/main/schema-guide.md\n        type: Schema Guide\n  \
  \    - url: https://citation-file-format.github.io/\n        type: Website\n      - url: json-schema/citation-cff-schema.json\n        type: JSONSchema\n    description: >-\n      The CFF schema defines the structure of a CITATION.cff file in\n      YAML, including required cff-version, message, and authors\n      fields plus optional version, doi, license, repository-code,\n      preferred-citation, and references blocks. The current schema\n      version is 1.2.0 and is published as JSON Schema in the\n      citation-file-format GitHub repository under an open-source\n      license.\n  - aid: citation-cff:cffinit\n    name: cffinit Authoring Tool\n    tags:\n      - Authoring\n      - cffinit\n      - Web App\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://citation-file-format.github.io/cff-initializer-javascript/\n    properties:\n      - url: https://citation-file-format.github.io/cff-initializer-javascript/\n        type:\
  \ Web Application\n      - url: https://github.com/citation-file-format/cff-initializer-javascript\n        type: Source Code\n    description: >-\n      cffinit is a web-based form that walks software authors through\n      creating a syntactically and semantically valid CITATION.cff\n      file. It produces downloadable YAML and validates content\n      against the CFF schema in real time.\n  - aid: citation-cff:cffconvert\n    name: cffconvert\n    tags:\n      - BibTeX\n      - cffconvert\n      - CodeMeta\n      - Conversion\n      - RIS\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/citation-file-format/cffconvert\n    properties:\n      - url: https://github.com/citation-file-format/cffconvert\n        type: Source Code\n      - url: https://pypi.org/project/cffconvert/\n        type: Package\n    description: >-\n      cffconvert is a Python command-line tool and library that\n      converts CITATION.cff\
  \ files to APA plain text, BibTeX, CodeMeta,\n      EndNote, RIS, schema.org JSON-LD, and Zenodo deposition JSON.\n      It also validates CFF files against the published schema.\n  - aid: citation-cff:cff-validator\n    name: cff-validator GitHub Action\n    tags:\n      - CI\n      - GitHub Action\n      - Validation\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/dieghernan/cff-validator\n    properties:\n      - url: https://github.com/dieghernan/cff-validator\n        type: Source Code\n      - url: https://github.com/marketplace/actions/cff-validator\n        type: Marketplace\n    description: >-\n      The cff-validator GitHub Action runs schema validation on a\n      repository's CITATION.cff during continuous integration so that\n      malformed or non-compliant citation metadata is caught before\n      release.\n  - aid: citation-cff:github-citation-integration\n    name: GitHub Native Citation Support\n\
  \    tags:\n      - Discovery\n      - GitHub\n      - Integration\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files\n    properties:\n      - url: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files\n        type: Documentation\n    description: >-\n      GitHub natively reads CITATION.cff files and renders a Cite\n      this repository button on the repository landing page that\n      generates BibTeX and APA snippets from the file's metadata.\n  - aid: citation-cff:zenodo-integration\n    name: Zenodo Software Publishing\n    tags:\n      - DOI\n      - Publishing\n      - Repository\n      - Zenodo\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://zenodo.org/\n\
  \    properties:\n      - url: https://zenodo.org/\n        type: Documentation\n      - url: https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content\n        type: Integration Documentation\n    description: >-\n      The GitHub-Zenodo integration uses CITATION.cff metadata when\n      publishing a release as a citable software record. Zenodo\n      assigns a DOI and populates the deposit form from the CFF\n      file's authors, title, and version.\ncommon:\n  - type: Website\n    url: https://citation-file-format.github.io/\n  - type: Documentation\n    url: https://github.com/citation-file-format/citation-file-format\n  - type: Schema Guide\n    url: https://github.com/citation-file-format/citation-file-format/blob/main/schema-guide.md\n  - type: Schema\n    url: https://github.com/citation-file-format/citation-file-format/blob/main/schema.json\n  - type: GitHub\n    url: https://github.com/citation-file-format\n  - type: Governance\n   \
  \ url: https://github.com/citation-file-format/governance\n  - type: Issues\n    url: https://github.com/citation-file-format/citation-file-format/issues\n  - type: License\n    url: https://github.com/citation-file-format/citation-file-format/blob/main/LICENSE\n  - type: Citation\n    url: https://github.com/citation-file-format/citation-file-format/blob/main/CITATION.cff\n  - type: JSON-LD\n    url: json-ld/citation-cff-context.jsonld\n  - type: JSONSchema\n    url: json-schema/citation-cff-schema.json\n  - type: Spectral\n    url: rules/citation-cff-rules.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/citation-cff/refs/heads/main/apis.yml
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
