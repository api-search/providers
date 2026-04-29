---
api_count: 1
api_specs:
- filename: apache-opennlp-tools.yaml
  format: yaml
  label: Apache OpenNLP
  slug: apache-opennlp
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-opennlp/refs/heads/main/openapi/apache-opennlp-tools.yaml
apis:
- description: OpenNLP provides a Java API for NLP tasks including tokenization, sentence detection, POS tagging, named entity recognition, chunking, parsing, and language detection, with support for training custom
  name: Apache OpenNLP
  slug: apache-opennlp
capabilities:
- description: End-to-end NLP processing workflow combining language detection, sentence detection, tokenization, POS tagging, NER, chunking, and parsing for comprehensive text analysis.
  name: Apache OpenNLP NLP Pipeline Workflow
  slug: nlp-pipeline-workflow
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/opennlp
- title: ''
  type: Documentation
  url: https://opennlp.apache.org/
- title: ''
  type: GettingStarted
  url: https://opennlp.apache.org/docs/
- title: ''
  type: SpectralRules
  url: rules/apache-opennlp-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-opennlp-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/nlp-pipeline-workflow.yaml
- title: ''
  type: JSON-LD
  url: json-ld/apache-opennlp-context.jsonld
created: '2026-03-16'
description: Apache OpenNLP is a machine learning based toolkit for the processing of natural language text. It supports common NLP tasks such as tokenization, sentence segmentation, part-of-speech tagging, named entity extraction, chunking, parsing, and coreference resolution.
features:
- description: Detects document language using ISO-639-3 classification
  name: Language Detection
- description: Splits text into individual sentences with character offsets
  name: Sentence Detection
- description: Segments text into words and punctuation with position tracking
  name: Tokenization
- description: Detects persons, locations, organizations, and other named entities
  name: Named Entity Recognition
- description: Assigns Penn Treebank POS tags to each token
  name: POS Tagging
- description: Reduces tokens to their dictionary base forms
  name: Lemmatization
- description: Identifies noun phrases, verb phrases, and other syntactic chunks
  name: Chunking
- description: Builds full syntactic parse trees using constituency parsing
  name: Parsing
- description: Classifies documents into predefined categories
  name: Document Categorization
- description: Train custom models with Maxent, Perceptron, or Naive Bayes algorithms
  name: Custom Model Training
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integrate OpenNLP with Apache Solr for NLP-enhanced search
  name: Apache Solr
- description: Use OpenNLP analyzers in Lucene text processing pipelines
  name: Apache Lucene
- description: Real-time NLP processing with Apache Flink data streams
  name: Apache Flink
- description: Apache UIMA framework integration for unstructured information analysis
  name: UIMA
- description: Available on Maven Central for Java build system integration
  name: Maven/Gradle
jsonld:
- class_count: 18
  name: Apache Opennlp Context
  property_count: 24
  slug: apache-opennlp-context
layout: provider
modified: '2026-04-19'
name: Apache OpenNLP
rules:
- name: Apache OpenNLP API Rules
  rule_count: 10
  severity_counts:
    error: 4
    hint: 0
    info: 1
    warn: 5
  slug: apache-opennlp-spectral-rules
skills: []
slug: apache-opennlp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apache-opennlp\nname: Apache OpenNLP\ndescription: >-\n  Apache OpenNLP is a machine learning based toolkit for the processing of natural language text. It supports common NLP tasks such as tokenization, sentence segmentation, part-of-speech tagging, named\n  entity extraction, chunking, parsing, and coreference resolution.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Machine Learning\n- Natural Language Processing\n- NLP\n- Text Processing\n- Apache\n- Open Source\n- Java\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-opennlp/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n- aid: apache-opennlp:apache-opennlp\n  name: Apache OpenNLP\n  description: >-\n    OpenNLP provides a Java API for NLP tasks including tokenization, sentence detection, POS tagging, named entity recognition, chunking,\
  \ parsing, and language detection, with support for training custom\n    models.\n  humanURL: https://opennlp.apache.org/docs/\n  tags:\n  - Java\n  - NLP\n  - Text Processing\n  - Apache\n  - Open Source\n  - Machine Learning\n  properties:\n  - type: Documentation\n    url: https://opennlp.apache.org/docs/\n  - type: OpenAPI\n    url: openapi/apache-opennlp-tools.yaml\nmaintainers:\n- FN: Kin Lane\n  email: info@apievangelist.com\ncommon:\n- type: GitHubOrganization\n  url: https://github.com/apache/opennlp\n- type: Documentation\n  url: https://opennlp.apache.org/\n- type: GettingStarted\n  url: https://opennlp.apache.org/docs/\n- type: SpectralRules\n  url: rules/apache-opennlp-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/apache-opennlp-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/nlp-pipeline-workflow.yaml\n- type: JSON-LD\n  url: json-ld/apache-opennlp-context.jsonld\n- type: Features\n  data:\n  - name: Language Detection\n    description: Detects\
  \ document language using ISO-639-3 classification\n  - name: Sentence Detection\n    description: Splits text into individual sentences with character offsets\n  - name: Tokenization\n    description: Segments text into words and punctuation with position tracking\n  - name: Named Entity Recognition\n    description: Detects persons, locations, organizations, and other named entities\n  - name: POS Tagging\n    description: Assigns Penn Treebank POS tags to each token\n  - name: Lemmatization\n    description: Reduces tokens to their dictionary base forms\n  - name: Chunking\n    description: Identifies noun phrases, verb phrases, and other syntactic chunks\n  - name: Parsing\n    description: Builds full syntactic parse trees using constituency parsing\n  - name: Document Categorization\n    description: Classifies documents into predefined categories\n  - name: Custom Model Training\n    description: Train custom models with Maxent, Perceptron, or Naive Bayes algorithms\n- type: UseCases\n\
  \  data:\n  - name: Information Extraction\n    description: Extract structured data from unstructured text documents\n  - name: Text Classification\n    description: Automatically categorize documents by topic or sentiment\n  - name: Search Enhancement\n    description: Improve search relevance with NLP-based query processing\n  - name: Content Analysis\n    description: Analyze large text corpora for entities, topics, and patterns\n  - name: Chatbot Development\n    description: Build conversational AI with NLP intent and entity extraction\n- type: Integrations\n  data:\n  - name: Apache Solr\n    description: Integrate OpenNLP with Apache Solr for NLP-enhanced search\n  - name: Apache Lucene\n    description: Use OpenNLP analyzers in Lucene text processing pipelines\n  - name: Apache Flink\n    description: Real-time NLP processing with Apache Flink data streams\n  - name: UIMA\n    description: Apache UIMA framework integration for unstructured information analysis\n  - name: Maven/Gradle\n\
  \    description: Available on Maven Central for Java build system integration\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-opennlp/refs/heads/main/apis.yml
tags:
- Machine Learning
- Natural Language Processing
- NLP
- Text Processing
- Apache
- Open Source
- Java
url: https://raw.githubusercontent.com/api-evangelist/apache-opennlp/refs/heads/main/apis.yml
use_cases:
- description: Extract structured data from unstructured text documents
  name: Information Extraction
- description: Automatically categorize documents by topic or sentiment
  name: Text Classification
- description: Improve search relevance with NLP-based query processing
  name: Search Enhancement
- description: Analyze large text corpora for entities, topics, and patterns
  name: Content Analysis
- description: Build conversational AI with NLP intent and entity extraction
  name: Chatbot Development
---
