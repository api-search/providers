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
source_yaml: "aid: apache-sling\nname: Apache Sling\ndescription: >-\n  Apache Sling is a RESTful web framework built on top of the Java Content Repository (JCR)\n  standard. It maps HTTP requests to content resources using a resource-oriented URL decomposition\n  model and uses scripts or servlets to render responses, supporting multiple scripting languages\n  including HTL, JSP, Groovy, and server-side JavaScript. Apache Sling forms the foundation of\n  Adobe Experience Manager (AEM) and is an Apache Software Foundation project with 300+ modular\n  OSGi bundles.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Content Management\n  - Java\n  - JCR\n  - OSGi\n  - REST\n  - Web Framework\n  - Open Source\n  - Adobe Experience Manager\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-sling/refs/heads/main/apis.yml\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: apache-sling:apache-sling-resource-api\n    name: Apache Sling Resource API\n    description: >-\n      The Sling Resource API provides RESTful access to JCR content repository nodes via\n      HTTP. Every content node is addressable as a URL, supporting GET, POST, PUT, DELETE,\n      and MOVE operations through the Sling Default GET/POST Servlets. Content is accessible\n      in multiple formats via selector and extension: .json for structured data, .xml for\n      XML export, .infinity.json for deep tree traversal, and .tidy.json for formatted output.\n      The POST Servlet (SlingPostServlet) handles content creation, modification, deletion,\n      move, copy, and import operations.\n    humanURL: https://sling.apache.org/documentation/the-sling-engine/resources.html\n    tags:\n      - REST\n      - JCR\n      - Content Management\n      - Resources\n      - Java\n    properties:\n      - type: Documentation\n        url: https://sling.apache.org/documentation/the-sling-engine/resources.html\n\
  \      - type: Documentation\n        url: https://sling.apache.org/documentation/bundles/manipulating-content-the-slingpostservlet-servlets-post.html\n\n  - aid: apache-sling:apache-sling-scripting-api\n    name: Apache Sling Scripting API\n    description: >-\n      The Sling Scripting API enables server-side rendering through multiple scripting engines.\n      Scripts are resolved from the content repository based on resource type and selectors,\n      supporting HTL (HTML Template Language / Sightly), JSP (JavaServer Pages), Groovy,\n      FreeMarker, Thymeleaf, and server-side JavaScript via Rhino. The ScriptEngine API\n      allows integration of any JSR-223 compatible scripting language.\n    humanURL: https://sling.apache.org/documentation/bundles/scripting.html\n    tags:\n      - Scripting\n      - HTL\n      - JSP\n      - Groovy\n      - Templates\n      - Java\n    properties:\n      - type: Documentation\n        url: https://sling.apache.org/documentation/bundles/scripting.html\n\
  \      - type: Documentation\n        url: https://sling.apache.org/documentation/bundles/scripting/scripting-htl.html\n\n  - aid: apache-sling:apache-sling-event-api\n    name: Apache Sling Event API\n    description: >-\n      The Sling Event API provides a job processing and eventing system built on OSGi EventAdmin.\n      It supports distributed job queuing, scheduled job execution, event broadcasting across\n      cluster nodes, and workflow triggering. The JobManager API enables job creation, monitoring,\n      and management through a programmatic interface and also provides REST endpoints via the\n      Web Console integration.\n    humanURL: https://sling.apache.org/documentation/bundles/apache-sling-eventing-and-job-handling.html\n    tags:\n      - Events\n      - Jobs\n      - Async\n      - OSGi\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://sling.apache.org/documentation/bundles/apache-sling-eventing-and-job-handling.html\n\ncommon:\n\
  \  - type: GitHubOrganization\n    url: https://github.com/apache/sling-org-apache-sling-api\n  - type: GitHubRepository\n    url: https://github.com/apache/sling\n  - type: Documentation\n    url: https://sling.apache.org/documentation.html\n  - type: Portal\n    url: https://sling.apache.org/\n  - type: GettingStarted\n    url: https://sling.apache.org/documentation/getting-started.html\n  - type: Blog\n    url: https://sling.apache.org/news.html\n  - type: Support\n    url: https://sling.apache.org/project-information/mailing-lists.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/\n  - type: FAQ\n    url: https://cwiki.apache.org/confluence/display/SLING/\n  - type: SDK\n    url: https://search.maven.org/search?q=org.apache.sling\n    title: Maven Central Packages\n  - type: Features\n    data:\n      - name: Resource-Oriented REST API\n        description: Every JCR node is a REST resource accessible via URL with GET, POST, PUT, DELETE operations.\n      - name:\
  \ URL Decomposition\n        description: Flexible URL decomposition into resource path, selectors, extension, and suffix for content negotiation.\n      - name: SlingPostServlet\n        description: Powerful POST servlet for content CRUD operations, supporting create, modify, delete, move, copy, and import.\n      - name: Multi-Language Scripting\n        description: Server-side rendering with HTL, JSP, Groovy, FreeMarker, Thymeleaf, and Rhino JavaScript.\n      - name: OSGi Modular Architecture\n        description: 300+ modular OSGi bundles with hot-deploy capability and dynamic configuration.\n      - name: Resource Type Hierarchy\n        description: Sling Resource Type system enables component inheritance and script resolution.\n      - name: Event and Job Processing\n        description: Distributed job queue and event system for asynchronous content processing.\n      - name: Health Check Framework\n        description: Extensible health check system for monitoring Sling instance\
  \ components.\n      - name: Replication and Distribution\n        description: Content distribution bundles for replicating content between Sling instances.\n  - type: UseCases\n    data:\n      - name: Content Management Systems\n        description: Build REST-based CMS solutions with JCR-backed content repositories.\n      - name: Adobe Experience Manager\n        description: Foundation framework for AEM digital experience platform implementations.\n      - name: Headless CMS\n        description: Serve structured JSON content via Sling's resource API for headless front-end applications.\n      - name: Web Application Framework\n        description: Build OSGi-based Java web applications with RESTful resource routing.\n      - name: Digital Asset Management\n        description: Manage and serve digital assets stored in JCR with metadata and rendition support.\n  - type: Integrations\n    data:\n      - name: Adobe Experience Manager\n        description: Apache Sling is the foundational\
  \ framework for Adobe Experience Manager (AEM).\n      - name: Apache Jackrabbit Oak\n        description: JCR implementation providing the content repository backend for Sling.\n      - name: Apache Felix\n        description: OSGi framework container that hosts Sling bundles and manages the service registry.\n      - name: Apache Karaf\n        description: OSGi runtime alternative for deploying Sling-based applications.\n      - name: Maven\n        description: Maven plugin (slingstart-maven-plugin) and Maven archetypes for Sling development.\n      - name: Elasticsearch\n        description: Search integration for indexing JCR content via Sling's indexing framework.\n\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-sling/refs/heads/main/apis.yml
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
