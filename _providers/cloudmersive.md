---
api_count: 18
api_specs:
- filename: cloudmersive-virus-scan-openapi.json
  format: json
  label: Cloudmersive Virus Scan API
  slug: cloudmersive-virus-scan-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cloudmersive/refs/heads/main/openapi/cloudmersive-virus-scan-openapi.json
apis:
- description: Scan files and content for viruses, malware, executables, scripts, macros, password-protected files, and other content threats. Includes both basic and advanced (multi-engine) scan modes and a website
  name: Cloudmersive Virus Scan API
  slug: cloudmersive-virus-scan-api
- description: Detect SQL injection, XSS, XXE, SSRF, command injection, and other content-borne attacks against text and HTML inputs.
  name: Cloudmersive Security Threat Detection API
  slug: cloudmersive-security-threat-detection-api
- description: AI-powered spam detection for email and message content.
  name: Cloudmersive Spam Detection API
  slug: cloudmersive-spam-api
- description: Detect phishing attempts in email content and URLs using AI scanning.
  name: Cloudmersive Phishing Detection API
  slug: cloudmersive-phishing-api
- description: Sanitize user documents by stripping macros, scripts, and other embedded threats while preserving usable content (Content Disarm and Reconstruction).
  name: Cloudmersive Content Disarm and Reconstruction (CDR) API
  slug: cloudmersive-cdr-api
- description: Document fraud and content security threat scanning.
  name: Cloudmersive Fraud Detection API
  slug: cloudmersive-fraud-api
- description: Detect and redact personally identifiable information (PII) and other sensitive data in text and documents.
  name: Cloudmersive Data Loss Prevention (DLP) API
  slug: cloudmersive-dlp-api
- description: Convert files between many formats (DOCX/PDF/HTML/XLSX/PPTX/CSV/JSON/XML), take URL screenshots, edit documents, and process tabular data.
  name: Cloudmersive Document Convert API
  slug: cloudmersive-convert-api
- description: Generate and recognize barcodes including QR codes, EAN, UPC, Code 128, and more.
  name: Cloudmersive Barcode API
  slug: cloudmersive-barcode-api
- description: 'Recognize and process images: classify, detect objects, NSFW detection, face detection, image editing, filters, and resizing.'
  name: Cloudmersive Image Recognition and Processing API
  slug: cloudmersive-image-api
- description: Tokenization, POS tagging, sentence splitting, language detection, translation, sentiment analysis, and rephrasing.
  name: Cloudmersive Natural Language Processing API
  slug: cloudmersive-nlp-api
- description: Deep-learning-based OCR for images and PDFs, with form, receipt, and business-card extraction.
  name: Cloudmersive OCR API
  slug: cloudmersive-ocr-api
- description: Speech-to-text and text-to-speech in multiple languages.
  name: Cloudmersive Speech API
  slug: cloudmersive-speech-api
- description: Validate emails, phone numbers, domains, IP addresses, addresses, and other inputs.
  name: Cloudmersive Validate API
  slug: cloudmersive-validate-api
- description: Convert, edit, and process video and audio files.
  name: Cloudmersive Video API
  slug: cloudmersive-video-api
- description: Real-time currency exchange rates and conversions across major fiat and crypto currencies.
  name: Cloudmersive Currency API
  slug: cloudmersive-currency-api
- description: Hosted configuration management and feature flag service.
  name: Cloudmersive Configuration API
  slug: cloudmersive-config-api
- description: Connect, transform, and integrate data across systems and file formats.
  name: Cloudmersive Data Integration API
  slug: cloudmersive-data-integration-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://cloudmersive.com/
- title: ''
  type: Portal
  url: https://cloudmersive.com/developer
- title: ''
  type: API Console
  url: https://api-console.cloudmersive.com/swagger/index.html
- title: ''
  type: OpenAPI Index
  url: https://api.cloudmersive.com/openapi.asp
- title: ''
  type: Privacy Policy
  url: https://cloudmersive.com/privacy-policy
- title: ''
  type: JSON-LD
  url: json-ld/cloudmersive-context.jsonld
- title: ''
  type: Spectral
  url: rules/cloudmersive-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cloudmersive-virus-scan-capabilities.yml
created: '2024-11-13'
description: Cloudmersive provides a portfolio of utility APIs covering virus and malware scanning, document conversion, OCR, image recognition, NLP, validation, security threat detection (spam, phishing, fraud, DLP, CDR), speech, video, barcode, currency, and data integration. Each API is documented with a Swagger 2.0 / OpenAPI specification, has SDKs in multiple languages, and is consumable on api.cloudmersive.com behind an API key (`Apikey` header).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Cloudmersive Context
  property_count: 6
  slug: cloudmersive-context
layout: provider
modified: '2026-04-26'
name: Cloudmersive
rules:
- name: Cloudmersive API Rules
  rule_count: 8
  severity_counts:
    error: 5
    hint: 0
    info: 0
    warn: 3
  slug: cloudmersive-rules
skills: []
slug: cloudmersive
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: cloudmersive\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cloudmersive/refs/heads/main/apis.yml\nname: Cloudmersive\ntags:\n  - Barcodes\n  - Conversions\n  - Documents\n  - Image Recognition\n  - Natural Language\n  - OCR\n  - Processing\n  - Validation\n  - Virus Scanning\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-13'\nmodified: '2026-04-26'\nposition: Consumer\nx-type: company\nx-company: Cloudmersive\ndescription: >-\n  Cloudmersive provides a portfolio of utility APIs covering virus and\n  malware scanning, document conversion, OCR, image recognition, NLP,\n  validation, security threat detection (spam, phishing, fraud, DLP, CDR),\n  speech, video, barcode, currency, and data integration. Each API is\n  documented with a Swagger 2.0 / OpenAPI specification, has SDKs in\n  multiple languages, and is consumable on api.cloudmersive.com behind an\n  API key (`Apikey`\
  \ header).\napis:\n  - aid: cloudmersive:cloudmersive-virus-scan-api\n    name: Cloudmersive Virus Scan API\n    tags:\n      - Antivirus\n      - Malware\n      - Security\n      - Virus Scanning\n    humanURL: https://cloudmersive.com/virus-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Virus%20Scan%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/virus\n        type: OpenAPI\n      - url: openapi/cloudmersive-virus-scan-openapi.json\n        type: OpenAPI\n    description: >-\n      Scan files and content for viruses, malware, executables, scripts,\n      macros, password-protected files, and other content threats. Includes\n      both basic and advanced (multi-engine) scan modes and a website scan.\n  - aid: cloudmersive:cloudmersive-security-threat-detection-api\n    name: Cloudmersive Security Threat Detection API\n    tags:\n      - Security\n      - SQL Injection\n    \
  \  - Threat Detection\n      - XSS\n    humanURL: https://cloudmersive.com/security-threat-detection-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Security%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/security\n        type: OpenAPI\n    description: >-\n      Detect SQL injection, XSS, XXE, SSRF, command injection, and other\n      content-borne attacks against text and HTML inputs.\n  - aid: cloudmersive:cloudmersive-spam-api\n    name: Cloudmersive Spam Detection API\n    tags:\n      - Email\n      - Spam\n    humanURL: https://cloudmersive.com/spam-detection-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Spam%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/spam\n        type: OpenAPI\n    description: AI-powered spam detection for email and message content.\n\
  \  - aid: cloudmersive:cloudmersive-phishing-api\n    name: Cloudmersive Phishing Detection API\n    tags:\n      - Email Security\n      - Phishing\n    humanURL: https://cloudmersive.com/phishing-detection-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Phishing%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/phishing\n        type: OpenAPI\n    description: Detect phishing attempts in email content and URLs using AI scanning.\n  - aid: cloudmersive:cloudmersive-cdr-api\n    name: Cloudmersive Content Disarm and Reconstruction (CDR) API\n    tags:\n      - CDR\n      - Document Sanitization\n      - Security\n    humanURL: https://cloudmersive.com/content-disarm-and-reconstruction-cdr-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=CDR%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/cdr\n\
  \        type: OpenAPI\n    description: >-\n      Sanitize user documents by stripping macros, scripts, and other\n      embedded threats while preserving usable content (Content Disarm and\n      Reconstruction).\n  - aid: cloudmersive:cloudmersive-fraud-api\n    name: Cloudmersive Fraud Detection API\n    tags:\n      - Fraud Detection\n      - Risk\n    humanURL: https://cloudmersive.com/fraud-detection-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Fraud%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/fraud\n        type: OpenAPI\n    description: Document fraud and content security threat scanning.\n  - aid: cloudmersive:cloudmersive-dlp-api\n    name: Cloudmersive Data Loss Prevention (DLP) API\n    tags:\n      - Compliance\n      - DLP\n      - PII\n    humanURL: https://cloudmersive.com/data-loss-prevention-dlp-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=DLP%20API\n\
  \        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/dlp\n        type: OpenAPI\n    description: Detect and redact personally identifiable information (PII) and other sensitive data in text and documents.\n  - aid: cloudmersive:cloudmersive-convert-api\n    name: Cloudmersive Document Convert API\n    tags:\n      - Conversion\n      - Documents\n      - File Formats\n    humanURL: https://cloudmersive.com/convert-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Convert%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/convert\n        type: OpenAPI\n    description: >-\n      Convert files between many formats (DOCX/PDF/HTML/XLSX/PPTX/CSV/JSON/XML),\n      take URL screenshots, edit documents, and process tabular data.\n  - aid: cloudmersive:cloudmersive-barcode-api\n    name: Cloudmersive Barcode API\n    tags:\n      - Barcode\n      - QR\
  \ Code\n    humanURL: https://cloudmersive.com/barcode-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Barcode%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/barcode\n        type: OpenAPI\n    description: Generate and recognize barcodes including QR codes, EAN, UPC, Code 128, and more.\n  - aid: cloudmersive:cloudmersive-image-api\n    name: Cloudmersive Image Recognition and Processing API\n    tags:\n      - Computer Vision\n      - Image Processing\n      - Image Recognition\n    humanURL: https://cloudmersive.com/image-recognition-and-processing-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Image%20Recognition%20and%20Processing%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/image\n        type: OpenAPI\n    description: >-\n      Recognize and process images:\
  \ classify, detect objects, NSFW\n      detection, face detection, image editing, filters, and resizing.\n  - aid: cloudmersive:cloudmersive-nlp-api\n    name: Cloudmersive Natural Language Processing API\n    tags:\n      - NLP\n      - Sentiment Analysis\n      - Translation\n    humanURL: https://cloudmersive.com/natural-language-processing-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Natural%20Language%20Processing%20(NLP)%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/nlp\n        type: OpenAPI\n      - url: https://api-console.cloudmersive.com/swagger/api/nlpv2\n        type: OpenAPI\n    description: Tokenization, POS tagging, sentence splitting, language detection, translation, sentiment analysis, and rephrasing.\n  - aid: cloudmersive:cloudmersive-ocr-api\n    name: Cloudmersive OCR API\n    tags:\n      - Documents\n      - OCR\n    humanURL: https://cloudmersive.com/ocr-api\n\
  \    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Optical%20Character%20Recognition%20(OCR)%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/ocr\n        type: OpenAPI\n    description: Deep-learning-based OCR for images and PDFs, with form, receipt, and business-card extraction.\n  - aid: cloudmersive:cloudmersive-speech-api\n    name: Cloudmersive Speech API\n    tags:\n      - Speech\n      - Speech Recognition\n      - Text to Speech\n    humanURL: https://cloudmersive.com/speech-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Speech%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/speech\n        type: OpenAPI\n    description: Speech-to-text and text-to-speech in multiple languages.\n  - aid: cloudmersive:cloudmersive-validate-api\n    name: Cloudmersive Validate API\n  \
  \  tags:\n      - Email\n      - Validation\n    humanURL: https://cloudmersive.com/validate-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Validate%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/validate\n        type: OpenAPI\n    description: Validate emails, phone numbers, domains, IP addresses, addresses, and other inputs.\n  - aid: cloudmersive:cloudmersive-video-api\n    name: Cloudmersive Video API\n    tags:\n      - Conversion\n      - Video\n    humanURL: https://cloudmersive.com/video-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Video%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/video\n        type: OpenAPI\n    description: Convert, edit, and process video and audio files.\n  - aid: cloudmersive:cloudmersive-currency-api\n    name: Cloudmersive Currency\
  \ API\n    tags:\n      - Currency\n      - Exchange Rate\n    humanURL: https://cloudmersive.com/currency-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Currency%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/currency\n        type: OpenAPI\n    description: Real-time currency exchange rates and conversions across major fiat and crypto currencies.\n  - aid: cloudmersive:cloudmersive-config-api\n    name: Cloudmersive Configuration API\n    tags:\n      - Configuration\n      - Feature Flags\n    humanURL: https://cloudmersive.com/config-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Config%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/config\n        type: OpenAPI\n    description: Hosted configuration management and feature flag service.\n  - aid: cloudmersive:cloudmersive-data-integration-api\n\
  \    name: Cloudmersive Data Integration API\n    tags:\n      - Data Integration\n      - ETL\n    humanURL: https://cloudmersive.com/data-integration-api\n    properties:\n      - url: https://api-console.cloudmersive.com/swagger/index.html?urls.primaryName=Data%20Integration%20API\n        type: Documentation\n      - url: https://api-console.cloudmersive.com/swagger/api/dataintegration\n        type: OpenAPI\n    description: Connect, transform, and integrate data across systems and file formats.\ncommon:\n  - type: Website\n    url: https://cloudmersive.com/\n  - type: Portal\n    url: https://cloudmersive.com/developer\n  - type: API Console\n    url: https://api-console.cloudmersive.com/swagger/index.html\n  - type: OpenAPI Index\n    url: https://api.cloudmersive.com/openapi.asp\n  - type: Privacy Policy\n    url: https://cloudmersive.com/privacy-policy\n  - type: JSON-LD\n    url: json-ld/cloudmersive-context.jsonld\n  - type: Spectral\n    url: rules/cloudmersive-rules.yml\n\
  \  - type: Naftiko Capabilities\n    url: capabilities/cloudmersive-virus-scan-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cloudmersive/refs/heads/main/apis.yml
tags:
- Barcodes
- Conversions
- Documents
- Image Recognition
- Natural Language
- OCR
- Processing
- Validation
- Virus Scanning
url: https://raw.githubusercontent.com/api-evangelist/cloudmersive/refs/heads/main/apis.yml
use_cases: []
---
