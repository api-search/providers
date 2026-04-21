---
api_count: 3
apis:
- description: 'The Sling Resource API provides RESTful access to JCR content repository nodes via HTTP. Every content node is addressable as a URL, supporting GET, POST, PUT, DELETE, and MOVE operations through the '
  name: Apache Sling Resource API
  slug: apache-sling-resource-api
- description: The Sling Scripting API enables server-side rendering through multiple scripting engines. Scripts are resolved from the content repository based on resource type and selectors, supporting HTL (HTML Te
  name: Apache Sling Scripting API
  slug: apache-sling-scripting-api
- description: The Sling Event API provides a job processing and eventing system built on OSGi EventAdmin. It supports distributed job queuing, scheduled job execution, event broadcasting across cluster nodes, and w
  name: Apache Sling Event API
  slug: apache-sling-event-api
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache/sling-org-apache-sling-api
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/sling
- title: ''
  type: Documentation
  url: https://sling.apache.org/documentation.html
- title: ''
  type: Portal
  url: https://sling.apache.org/
- title: ''
  type: GettingStarted
  url: https://sling.apache.org/documentation/getting-started.html
- title: ''
  type: Blog
  url: https://sling.apache.org/news.html
- title: ''
  type: Support
  url: https://sling.apache.org/project-information/mailing-lists.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/
- title: ''
  type: FAQ
  url: https://cwiki.apache.org/confluence/display/SLING/
- title: Maven Central Packages
  type: SDK
  url: https://search.maven.org/search?q=org.apache.sling
created: '2026-03-16'
description: Apache Sling is a RESTful web framework built on top of the Java Content Repository (JCR) standard. It maps HTTP requests to content resources using a resource-oriented URL decomposition model and uses scripts or servlets to render responses, supporting multiple scripting languages including HTL, JSP, Groovy, and server-side JavaScript. Apache Sling forms the foundation of Adobe Experience Manager (AEM) and is an Apache Software Foundation project with 300+ modular OSGi bundles.
features:
- description: Every JCR node is a REST resource accessible via URL with GET, POST, PUT, DELETE operations.
  name: Resource-Oriented REST API
- description: Flexible URL decomposition into resource path, selectors, extension, and suffix for content negotiation.
  name: URL Decomposition
- description: Powerful POST servlet for content CRUD operations, supporting create, modify, delete, move, copy, and import.
  name: SlingPostServlet
- description: Server-side rendering with HTL, JSP, Groovy, FreeMarker, Thymeleaf, and Rhino JavaScript.
  name: Multi-Language Scripting
- description: 300+ modular OSGi bundles with hot-deploy capability and dynamic configuration.
  name: OSGi Modular Architecture
- description: Sling Resource Type system enables component inheritance and script resolution.
  name: Resource Type Hierarchy
- description: Distributed job queue and event system for asynchronous content processing.
  name: Event and Job Processing
- description: Extensible health check system for monitoring Sling instance components.
  name: Health Check Framework
- description: Content distribution bundles for replicating content between Sling instances.
  name: Replication and Distribution
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Apache Sling is the foundational framework for Adobe Experience Manager (AEM).
  name: Adobe Experience Manager
- description: JCR implementation providing the content repository backend for Sling.
  name: Apache Jackrabbit Oak
- description: OSGi framework container that hosts Sling bundles and manages the service registry.
  name: Apache Felix
- description: OSGi runtime alternative for deploying Sling-based applications.
  name: Apache Karaf
- description: Maven plugin (slingstart-maven-plugin) and Maven archetypes for Sling development.
  name: Maven
- description: Search integration for indexing JCR content via Sling's indexing framework.
  name: Elasticsearch
layout: provider
modified: '2026-04-19'
name: Apache Sling
skills: []
slug: apache-sling
solutions: []
tags:
- Content Management
- Java
- JCR
- OSGi
- REST
- Web Framework
- Open Source
- Adobe Experience Manager
url: https://raw.githubusercontent.com/api-evangelist/apache-sling/refs/heads/main/apis.yml
use_cases:
- description: Build REST-based CMS solutions with JCR-backed content repositories.
  name: Content Management Systems
- description: Foundation framework for AEM digital experience platform implementations.
  name: Adobe Experience Manager
- description: Serve structured JSON content via Sling's resource API for headless front-end applications.
  name: Headless CMS
- description: Build OSGi-based Java web applications with RESTful resource routing.
  name: Web Application Framework
- description: Manage and serve digital assets stored in JCR with metadata and rendition support.
  name: Digital Asset Management
---
