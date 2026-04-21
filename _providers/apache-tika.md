---
api_count: 2
apis:
- description: 'The Tika Server REST API provides HTTP endpoints for content type detection, text extraction, metadata extraction, and language detection from uploaded documents. Key endpoints include: PUT /tika for '
  name: Apache Tika REST API
  slug: apache-tika-rest-api
- description: The Tika Java API provides the AutoDetectParser for automatic format detection and parsing, Metadata class for reading extracted metadata fields, ContentHandler for streaming SAX-based text extraction
  name: Apache Tika Java API
  slug: apache-tika-java-api
common:
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/tika
- title: ''
  type: Documentation
  url: https://tika.apache.org/
- title: ''
  type: Portal
  url: https://tika.apache.org/
- title: ''
  type: GettingStarted
  url: https://tika.apache.org/gettingstarted.html
- title: ''
  type: ReleaseNotes
  url: https://github.com/apache/tika/releases
- title: ''
  type: Support
  url: https://cwiki.apache.org/confluence/display/TIKA/MailingLists
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: Python Tika Package
  type: SDK
  url: https://pypi.org/project/tika/
created: '2026-03-16'
description: Apache Tika is a toolkit for detecting and extracting metadata and structured text content from over 1,000 file formats including PDF, Microsoft Office (Word, Excel, PowerPoint), OpenDocument, HTML, XML, images, audio, video, and archive formats. Tika provides a REST API server, Java library, and command-line tool. It is used by Apache Solr, Apache Nutch, and many other systems for content extraction and indexing. It is maintained by the Apache Software Foundation.
features:
- description: Detect and extract content from over 1,000 file formats using parser plugins.
  name: 1000+ Format Support
- description: Extract document metadata including author, creation date, title, and format-specific properties.
  name: Metadata Extraction
- description: Automatic language detection from extracted text content.
  name: Language Detection
- description: Accurate MIME type detection based on file content (magic bytes) not just file extension.
  name: MIME Type Detection
- description: Standalone HTTP server for document processing without Java library dependency.
  name: REST Server
- description: Optional Tesseract OCR integration for text extraction from images and scanned PDFs.
  name: OCR Integration
- description: Recursive parsing of archive formats (ZIP, TAR, JAR) and embedded documents.
  name: Recursive Parsing
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Solr Cell uses Tika for extracting text from uploaded documents for indexing.
  name: Apache Solr
- description: Nutch web crawler uses Tika for parsing fetched web page content.
  name: Apache Nutch
- description: Ingest attachment processor uses Tika for document content extraction.
  name: Elasticsearch
- description: Optional Tesseract integration for OCR on images and scanned documents.
  name: Tesseract OCR
- description: NiFi processor integration for automated document parsing workflows.
  name: Apache NiFi
layout: provider
modified: '2026-04-19'
name: Apache Tika
skills: []
slug: apache-tika
solutions: []
tags:
- Content Extraction
- Document Processing
- Metadata
- Text Extraction
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/apache-tika/refs/heads/main/apis.yml
use_cases:
- description: Extract text from documents for indexing in Apache Solr or Elasticsearch.
  name: Search Indexing
- description: Automated metadata extraction and classification for document management systems.
  name: Document Intelligence
- description: Batch content extraction during digital archive migration and transformation.
  name: Content Migration
- description: Legal e-discovery content extraction from diverse document collections.
  name: E-Discovery
---
