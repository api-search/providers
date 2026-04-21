---
api_count: 2
apis:
- description: Jena Fuseki provides a SPARQL server with REST API endpoints for SPARQL 1.1 Query, SPARQL 1.1 Update, and the SPARQL Graph Store HTTP Protocol. It supports dataset management, authentication, and moni
  name: Apache Jena Fuseki SPARQL API
  slug: fuseki-sparql-api
- description: The Jena Java API provides programmatic access to RDF model creation, SPARQL query execution, OWL reasoning, and TDB2 triplestore management for building Semantic Web applications.
  name: Apache Jena Java API
  slug: java-api
capabilities:
- description: Workflow capability for data engineers and knowledge graph architects to query, update, and manage RDF datasets using Apache Jena Fuseki.
  name: Apache Jena SPARQL Data Management
  slug: sparql-data-management
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/jena
- title: ''
  type: Documentation
  url: https://jena.apache.org/documentation/
- title: ''
  type: GettingStarted
  url: https://jena.apache.org/tutorials/
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Versioning
  url: https://jena.apache.org/about_jena/releases.html
- title: ''
  type: SpectralRules
  url: rules/apache-jena-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-jena-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/sparql-data-management.yaml
created: '2026-03-16'
description: Apache Jena is a Java framework for building Semantic Web and Linked Data applications. It provides APIs for RDF, SPARQL, OWL, and a triplestore database (TDB2) along with the Fuseki SPARQL server with a REST API for querying and managing RDF datasets.
features:
- description: Full SPARQL 1.1 query and update protocol support via Fuseki REST API.
  name: SPARQL Query and Update
- description: Java API for creating, reading, and manipulating RDF graphs.
  name: RDF Model API
- description: OWL and RDFS inference via Jena's rule-based and OWL reasoners.
  name: OWL Reasoning
- description: Native high-performance RDF triplestore for persistent graph storage.
  name: TDB2 Triplestore
- description: SPARQL Graph Store HTTP Protocol for named graph management.
  name: Graph Store Protocol
- description: Support for Turtle, JSON-LD, N-Triples, RDF/XML, and TriG serialization.
  name: Multiple RDF Formats
- description: High-level API for working with OWL and RDFS ontologies.
  name: Ontology API
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Integrate full-text search with SPARQL queries via Solr text index.
  name: Apache Solr
- description: Full-text search integration for Fuseki text search capabilities.
  name: Elasticsearch
- description: Spring integration for Jena RDF operations in enterprise Java apps.
  name: Spring Framework
jsonld:
- class_count: 6
  name: Apache Jena Fuseki Sparql Api Context
  property_count: 18
  slug: apache-jena-fuseki-sparql-api-context
layout: provider
modified: '2026-04-19'
name: Apache Jena
rules:
- name: Apache Jena API Rules
  rule_count: 15
  severity_counts:
    error: 8
    hint: 0
    info: 3
    warn: 4
  slug: apache-jena-spectral-rules
skills: []
slug: apache-jena
solutions: []
tags:
- Java
- Linked Data
- OWL
- Ontology
- Open Source
- RDF
- Semantic Web
- SPARQL
url: https://raw.githubusercontent.com/api-evangelist/apache-jena/refs/heads/main/apis.yml
use_cases:
- description: Build and query knowledge graphs using RDF and SPARQL.
  name: Knowledge Graph Management
- description: Publish Linked Data endpoints with Fuseki SPARQL server.
  name: Linked Data Publishing
- description: Enable semantic search over structured RDF datasets.
  name: Semantic Search
- description: Integrate heterogeneous data sources using RDF as a common data model.
  name: Data Integration
---
