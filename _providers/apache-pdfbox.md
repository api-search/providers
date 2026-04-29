---
api_count: 1
api_specs:
- filename: apache-pdfbox-api.yaml
  format: yaml
  label: Apache PDFBox
  slug: apache-pdfbox
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-pdfbox/refs/heads/main/openapi/apache-pdfbox-api.yaml
apis:
- description: PDFBox provides a Java API for creating, manipulating, rendering, and extracting text and images from PDF documents, with support for digital signatures, form filling, PDF/A validation, and font handl
  name: Apache PDFBox
  slug: apache-pdfbox
capabilities:
- description: Workflow for creating, manipulating, extracting text from, and digitally signing PDF documents using Apache PDFBox.
  name: Apache PDFBox Document Processing Workflow
  slug: pdfbox-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/pdfbox
- title: ''
  type: Documentation
  url: https://pdfbox.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-pdfbox-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-pdfbox-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/pdfbox-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-pdfbox-context.jsonld
created: '2026-03-16'
description: Apache PDFBox is an open-source Java library for working with PDF documents. It allows creation of new PDF documents, manipulation of existing documents, and the ability to extract content from documents with support for digital signatures.
features:
- description: Extract plain text and structured content from PDF documents
  name: PDF Text Extraction
- description: Create new PDF documents programmatically with Java API
  name: PDF Creation
- description: Merge, split, rotate, and resize pages in existing PDFs
  name: PDF Manipulation
- description: Apply and verify digital signatures for document authenticity
  name: Digital Signatures
- description: Read and fill interactive PDF forms (AcroForms)
  name: Form Filling
- description: Validate and create PDF/A documents for archiving
  name: PDF/A Validation
- description: Embed and extract fonts, handle Type 1, TrueType, and OpenType
  name: Font Handling
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Content detection and text extraction integration
  name: Apache Tika
- description: Spring Boot starter for PDF processing in web applications
  name: Spring Boot
- description: Available as org.apache.pdfbox on Maven Central
  name: Maven Central
- description: Complementary PDF library for advanced PDF generation
  name: iText/OpenPDF
jsonld:
- class_count: 11
  name: Apache Pdfbox Context
  property_count: 32
  slug: apache-pdfbox-context
layout: provider
modified: '2026-04-19'
name: Apache PDFBox
rules:
- name: Apache PDFBox API Rules
  rule_count: 6
  severity_counts:
    error: 4
    hint: 0
    info: 2
    warn: 0
  slug: apache-pdfbox-spectral-rules
skills: []
slug: apache-pdfbox
solutions: []
source_filename: apis.yml
source_yaml: "aid: apache-pdfbox\nname: Apache PDFBox\ndescription: >-\n  Apache PDFBox is an open-source Java library for working with PDF documents. It allows creation of new PDF documents, manipulation of existing documents, and the ability to extract content from documents\n  with support for digital signatures.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Document Processing\n- Java\n- PDF\n- Text Extraction\n- Apache\n- Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-pdfbox/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-pdfbox:apache-pdfbox\n  name: Apache PDFBox\n  description: >-\n    PDFBox provides a Java API for creating, manipulating, rendering, and extracting text and images from PDF documents, with support for digital signatures, form filling, PDF/A validation, and font\
  \ handling.\n  humanURL: https://pdfbox.apache.org/2.0/getting-started.html\n  tags:\n  - Document Processing\n  - Java\n  - PDF\n  - Apache\n  - Open Source\n  properties:\n  - type: Documentation\n    url: https://pdfbox.apache.org/2.0/getting-started.html\n  - type: OpenAPI\n    url: openapi/apache-pdfbox-api.yaml\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: GitHubOrganization\n  url: https://github.com/apache/pdfbox\n- type: Documentation\n  url: https://pdfbox.apache.org/\n- type: SpectralRules\n  url: rules/apache-pdfbox-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/apache-pdfbox-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/pdfbox-workflow.yaml\n- type: JSON-LD\n  url: json-ld/apache-pdfbox-context.jsonld\n- type: Features\n  data:\n  - name: PDF Text Extraction\n    description: Extract plain text and structured content from PDF documents\n  - name: PDF Creation\n    description: Create new PDF documents programmatically\
  \ with Java API\n  - name: PDF Manipulation\n    description: Merge, split, rotate, and resize pages in existing PDFs\n  - name: Digital Signatures\n    description: Apply and verify digital signatures for document authenticity\n  - name: Form Filling\n    description: Read and fill interactive PDF forms (AcroForms)\n  - name: PDF/A Validation\n    description: Validate and create PDF/A documents for archiving\n  - name: Font Handling\n    description: Embed and extract fonts, handle Type 1, TrueType, and OpenType\n- type: UseCases\n  data:\n  - name: Invoice Processing\n    description: Extract data from PDF invoices for automated processing\n  - name: Document Generation\n    description: Generate PDF reports, contracts, and certificates programmatically\n  - name: Legal Document Management\n    description: Digitally sign and verify legal documents\n  - name: Form Data Collection\n    description: Fill PDF forms and extract submitted data\n  - name: Archive Management\n    description:\
  \ Convert documents to PDF/A for long-term archiving\n- type: Integrations\n  data:\n  - name: Apache Tika\n    description: Content detection and text extraction integration\n  - name: Spring Boot\n    description: Spring Boot starter for PDF processing in web applications\n  - name: Maven Central\n    description: Available as org.apache.pdfbox on Maven Central\n  - name: iText/OpenPDF\n    description: Complementary PDF library for advanced PDF generation\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-pdfbox/refs/heads/main/apis.yml
tags:
- Document Processing
- Java
- PDF
- Text Extraction
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-pdfbox/refs/heads/main/apis.yml
use_cases:
- description: Extract data from PDF invoices for automated processing
  name: Invoice Processing
- description: Generate PDF reports, contracts, and certificates programmatically
  name: Document Generation
- description: Digitally sign and verify legal documents
  name: Legal Document Management
- description: Fill PDF forms and extract submitted data
  name: Form Data Collection
- description: Convert documents to PDF/A for long-term archiving
  name: Archive Management
---
