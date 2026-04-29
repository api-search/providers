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
source_filename: apis.yml
source_yaml: "aid: apache-tika\nname: Apache Tika\ndescription: >-\n  Apache Tika is a toolkit for detecting and extracting metadata and structured text content\n  from over 1,000 file formats including PDF, Microsoft Office (Word, Excel, PowerPoint),\n  OpenDocument, HTML, XML, images, audio, video, and archive formats. Tika provides a REST\n  API server, Java library, and command-line tool. It is used by Apache Solr, Apache Nutch,\n  and many other systems for content extraction and indexing. It is maintained by the Apache\n  Software Foundation.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Content Extraction\n  - Document Processing\n  - Metadata\n  - Text Extraction\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-tika/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-tika:apache-tika-rest-api\n\
  \    name: Apache Tika REST API\n    description: >-\n      The Tika Server REST API provides HTTP endpoints for content type detection, text extraction,\n      metadata extraction, and language detection from uploaded documents. Key endpoints include:\n      PUT /tika for full text extraction, PUT /meta for metadata-only extraction, PUT /detect/stream\n      for MIME type detection, PUT /language/stream for language detection, and GET /parsers for\n      listing available parsers. The server supports streaming large files and returns JSON or\n      plain text responses.\n    humanURL: https://cwiki.apache.org/confluence/display/TIKA/TikaServer\n    tags:\n      - REST\n      - Content Extraction\n      - Metadata\n      - Document Processing\n      - Text Extraction\n    properties:\n      - type: Documentation\n        url: https://cwiki.apache.org/confluence/display/TIKA/TikaServer\n      - type: Documentation\n        url: https://tika.apache.org/\n  - aid: apache-tika:apache-tika-java-api\n\
  \    name: Apache Tika Java API\n    description: >-\n      The Tika Java API provides the AutoDetectParser for automatic format detection and parsing,\n      Metadata class for reading extracted metadata fields, ContentHandler for streaming SAX-based\n      text extraction, and Detector for MIME type identification. The facade Tika class provides\n      a simple one-line API for text extraction from any supported format.\n    humanURL: https://tika.apache.org/\n    tags:\n      - Java\n      - Content Extraction\n      - Parser\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://tika.apache.org/\n      - type: APIReference\n        url: https://tika.apache.org/1.28/api/\n      - type: SDK\n        url: https://search.maven.org/search?q=org.apache.tika\n        title: Maven Java SDK\ncommon:\n  - type: GitHubRepository\n    url: https://github.com/apache/tika\n  - type: Documentation\n    url: https://tika.apache.org/\n  - type: Portal\n    url: https://tika.apache.org/\n\
  \  - type: GettingStarted\n    url: https://tika.apache.org/gettingstarted.html\n  - type: ReleaseNotes\n    url: https://github.com/apache/tika/releases\n  - type: Support\n    url: https://cwiki.apache.org/confluence/display/TIKA/MailingLists\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: SDK\n    url: https://pypi.org/project/tika/\n    title: Python Tika Package\n  - type: Features\n    data:\n      - name: 1000+ Format Support\n        description: Detect and extract content from over 1,000 file formats using parser plugins.\n      - name: Metadata Extraction\n        description: Extract document metadata including author, creation date, title, and format-specific properties.\n      - name: Language Detection\n        description: Automatic language detection from extracted text content.\n      - name: MIME Type Detection\n        description: Accurate MIME type detection based on file content (magic bytes) not just file extension.\n      - name:\
  \ REST Server\n        description: Standalone HTTP server for document processing without Java library dependency.\n      - name: OCR Integration\n        description: Optional Tesseract OCR integration for text extraction from images and scanned PDFs.\n      - name: Recursive Parsing\n        description: Recursive parsing of archive formats (ZIP, TAR, JAR) and embedded documents.\n  - type: UseCases\n    data:\n      - name: Search Indexing\n        description: Extract text from documents for indexing in Apache Solr or Elasticsearch.\n      - name: Document Intelligence\n        description: Automated metadata extraction and classification for document management systems.\n      - name: Content Migration\n        description: Batch content extraction during digital archive migration and transformation.\n      - name: E-Discovery\n        description: Legal e-discovery content extraction from diverse document collections.\n  - type: Integrations\n    data:\n      - name: Apache Solr\n\
  \        description: Solr Cell uses Tika for extracting text from uploaded documents for indexing.\n      - name: Apache Nutch\n        description: Nutch web crawler uses Tika for parsing fetched web page content.\n      - name: Elasticsearch\n        description: Ingest attachment processor uses Tika for document content extraction.\n      - name: Tesseract OCR\n        description: Optional Tesseract integration for OCR on images and scanned documents.\n      - name: Apache NiFi\n        description: NiFi processor integration for automated document parsing workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-tika/refs/heads/main/apis.yml
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
