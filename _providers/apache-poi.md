---
api_count: 1
apis:
- description: POI provides Java APIs for reading and writing Microsoft Office formats including Excel (HSSF/XSSF), Word (HWPF/XWPF), PowerPoint (HSLF/XSLF), Visio (HDGF/XDGF), and Outlook (HSMF), with support for f
  name: Apache POI
  slug: apache-poi
capabilities:
- description: ''
  name: Poi Workflow
  slug: poi-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/poi
- title: ''
  type: Documentation
  url: https://poi.apache.org/
- title: ''
  type: SpectralRules
  url: rules/apache-poi-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-poi-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/poi-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-poi-context.jsonld
created: '2026-03-16'
description: Apache POI is a Java API for manipulating various file formats based upon the Office Open XML standards (OOXML) and Microsoft's OLE2 Compound Document format (OLE2). It supports reading and writing Excel, Word, PowerPoint, Visio, and Outlook files.
features:
- description: Read and write Excel files in legacy XLS (HSSF) and modern XLSX (XSSF) formats
  name: Excel HSSF/XSSF
- description: Read and write Word documents in legacy DOC (HWPF) and modern DOCX (XWPF) formats
  name: Word HWPF/XWPF
- description: Create and manipulate PowerPoint presentations in PPT and PPTX formats
  name: PowerPoint HSLF/XSLF
- description: Evaluate Excel formulas and compute cell values programmatically
  name: Formula Evaluation
- description: Low-memory streaming API (SXSSF) for writing large Excel files
  name: Streaming API
- description: Create and modify charts in Excel workbooks and PowerPoint slides
  name: Chart Support
- description: Sign Office documents with digital signatures using OOXML standards
  name: Digital Signatures
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: POI is used by Tika for Office document text extraction
  name: Apache Tika
- description: Integrate POI with Spring Boot for web-based document generation
  name: Spring Framework
- description: Available as org.apache.poi artifacts on Maven Central
  name: Maven Central
- description: Uses Commons Collections and Commons Math for data structures
  name: Apache Commons
jsonld:
- class_count: 16
  name: Apache Poi Context
  property_count: 31
  slug: apache-poi-context
layout: provider
modified: '2026-04-19'
name: Apache POI
skills: []
slug: apache-poi
solutions: []
tags:
- Document Processing
- Excel
- Java
- Microsoft Office
- PowerPoint
- Word
- Apache
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-poi/refs/heads/main/apis.yml
use_cases:
- description: Generate Excel and Word reports programmatically from application data
  name: Report Generation
- description: Import data from Excel spreadsheets and export results back
  name: Data Import/Export
- description: Fill Office document templates with dynamic data
  name: Template Processing
- description: Convert between legacy Office formats and modern OOXML formats
  name: Document Conversion
---
