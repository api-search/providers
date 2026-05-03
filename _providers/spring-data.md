---
api_count: 7
api_specs:
- filename: spring-data-rest-openapi.yml
  format: yaml
  label: Spring Data REST
  slug: spring-data-rest
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spring-data/refs/heads/main/openapi/spring-data-rest-openapi.yml
apis:
- description: Exports Spring Data repositories as hypermedia-driven RESTful resources automatically. Provides HATEOAS-compliant endpoints with HAL browser, pagination, sorting, projections, and custom event hooks.
  name: Spring Data REST
  slug: spring-data-rest
- description: Simplifies the development of creating a JPA-based data access layer. Reduces boilerplate code and provides powerful query derivation, named queries, and specification-based querying on top of JPA/Hib
  name: Spring Data JPA
  slug: spring-data-jpa
- description: Provides a Spring-based programming model for MongoDB. Simplifies document operations, offers repository support, geo-spatial queries, GridFS, and full-text search integration with Spring's template p
  name: Spring Data MongoDB
  slug: spring-data-mongodb
- description: Easy configuration and access to Redis from Spring applications. Provides low-level and high-level abstractions for storing, reading, querying data. Supports both reactive and imperative programming m
  name: Spring Data Redis
  slug: spring-data-redis
- description: Provides Spring-based programming model and repository support for Apache Cassandra. Offers CassandraTemplate, repository abstraction, query derivation, and reactive programming support with Project R
  name: Spring Data Cassandra
  slug: spring-data-cassandra
- description: Spring-based programming model for Neo4j graph database. Provides repository support, object-graph mapping, Cypher query derivation, and reactive Neo4j integration with full Spring ecosystem compatibi
  name: Spring Data Neo4j
  slug: spring-data-neo4j
- description: Spring Data module for Elasticsearch search engine. Provides ElasticsearchTemplate, repository abstraction, index management, full-text search queries, and reactive Elasticsearch client support.
  name: Spring Data Elasticsearch
  slug: spring-data-elasticsearch
capabilities:
- description: Workflow capability for Spring Data REST data access operations. Provides unified CRUD and query access to any Spring Data repository over HAL+JSON. Used by application developers and API consumers to
  name: Spring Data REST - Data Access
  slug: data-access
common:
- title: ''
  type: Website
  url: https://spring.io/projects/spring-data
- title: ''
  type: Blog
  url: https://spring.io/blog/category/data
- title: ''
  type: GitHub Organization
  url: https://github.com/spring-projects
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/spring-data
- title: ''
  type: License
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Maven Repository
  url: https://mvnrepository.com/search?q=spring-data
- title: ''
  type: Releases
  url: https://github.com/spring-projects/spring-data-commons/releases
- title: ''
  type: Issues
  url: https://github.com/spring-projects/spring-data-commons/issues
- title: ''
  type: Changelog
  url: https://github.com/spring-projects/spring-data-commons/blob/main/CHANGELOG.adoc
created: '2024-01-15'
description: Spring Data's mission is to provide a familiar and consistent, Spring-based programming model for data access while still retaining the special traits of the underlying data store. It makes it easy to use data access technologies, relational and non-relational databases, map-reduce frameworks, and cloud-based data services. This is an umbrella project which contains many subprojects that are specific to a given database.
features: []
image: https://spring.io/img/projects/spring-data.svg
integrations: []
jsonld:
- class_count: 8
  name: Spring Data Context
  property_count: 16
  slug: spring-data-context
layout: provider
modified: '2026-05-02'
name: Spring Data
rules:
- name: Spring Data API Rules
  rule_count: 7
  severity_counts:
    error: 1
    hint: 0
    info: 2
    warn: 4
  slug: spring-data-rules
skills: []
slug: spring-data
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: spring-data\nname: Spring Data\ndescription: >-\n  Spring Data's mission is to provide a familiar and consistent, Spring-based\n  programming model for data access while still retaining the special traits of\n  the underlying data store. It makes it easy to use data access technologies,\n  relational and non-relational databases, map-reduce frameworks, and cloud-based\n  data services. This is an umbrella project which contains many subprojects that\n  are specific to a given database.\ntype: Index\nimage: https://spring.io/img/projects/spring-data.svg\nurl: https://spring.io/projects/spring-data\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\ntags:\n  - Data Access\n  - Database\n  - Framework\n  - Java\n  - JPA\n  - MongoDB\n  - ORM\n  - Redis\n  - REST\n  - Spring\napis:\n  - aid: spring-data:spring-data-rest\n    name: Spring Data REST\n    description: >-\n      Exports Spring Data repositories as hypermedia-driven RESTful resources\n\
  \      automatically. Provides HATEOAS-compliant endpoints with HAL browser,\n      pagination, sorting, projections, and custom event hooks.\n    image: https://spring.io/img/projects/spring-data.svg\n    humanURL: https://spring.io/projects/spring-data-rest\n    baseURL: http://localhost:8080\n    tags:\n      - HATEOAS\n      - HAL\n      - Hypermedia\n      - Repository\n      - REST\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-data/rest/docs/current/reference/html/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-data-rest\n      - type: API Reference\n        url: https://docs.spring.io/spring-data/rest/docs/current/api/\n      - type: Getting Started\n        url: https://spring.io/guides/gs/accessing-data-rest/\n      - type: OpenAPI\n        url: openapi/spring-data-rest-openapi.yml\n      - type: JSONSchema\n        url: json-schema/spring-data-paged-resource-schema.json\n      - type: JSONStructure\n\
  \        url: json-structure/spring-data-hal-resource-structure.json\n  - aid: spring-data:spring-data-jpa\n    name: Spring Data JPA\n    description: >-\n      Simplifies the development of creating a JPA-based data access layer.\n      Reduces boilerplate code and provides powerful query derivation, named\n      queries, and specification-based querying on top of JPA/Hibernate.\n    image: https://spring.io/img/projects/spring-data.svg\n    humanURL: https://spring.io/projects/spring-data-jpa\n    baseURL: http://localhost:8080\n    tags:\n      - Database\n      - Hibernate\n      - JPA\n      - Persistence\n      - Repository\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-data/jpa/docs/current/reference/html/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-data-jpa\n      - type: API Reference\n        url: https://docs.spring.io/spring-data/jpa/docs/current/api/\n      - type: Maven Repository\n \
  \       url: https://mvnrepository.com/artifact/org.springframework.data/spring-data-jpa\n  - aid: spring-data:spring-data-mongodb\n    name: Spring Data MongoDB\n    description: >-\n      Provides a Spring-based programming model for MongoDB. Simplifies document\n      operations, offers repository support, geo-spatial queries, GridFS, and\n      full-text search integration with Spring's template pattern.\n    image: https://spring.io/img/projects/spring-data.svg\n    humanURL: https://spring.io/projects/spring-data-mongodb\n    baseURL: http://localhost:8080\n    tags:\n      - Document Database\n      - MongoDB\n      - NoSQL\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-data/mongodb/docs/current/reference/html/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-data-mongodb\n      - type: API Reference\n        url: https://docs.spring.io/spring-data/mongodb/docs/current/api/\n      - type: Maven Repository\n\
  \        url: https://mvnrepository.com/artifact/org.springframework.data/spring-data-mongodb\n  - aid: spring-data:spring-data-redis\n    name: Spring Data Redis\n    description: >-\n      Easy configuration and access to Redis from Spring applications. Provides\n      low-level and high-level abstractions for storing, reading, querying data.\n      Supports both reactive and imperative programming models.\n    image: https://spring.io/img/projects/spring-data.svg\n    humanURL: https://spring.io/projects/spring-data-redis\n    baseURL: http://localhost:8080\n    tags:\n      - Cache\n      - Key-Value Store\n      - Pub/Sub\n      - Redis\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-data/redis/docs/current/reference/html/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-data-redis\n      - type: API Reference\n        url: https://docs.spring.io/spring-data/redis/docs/current/api/\n      - type: Maven\
  \ Repository\n        url: https://mvnrepository.com/artifact/org.springframework.data/spring-data-redis\n  - aid: spring-data:spring-data-cassandra\n    name: Spring Data Cassandra\n    description: >-\n      Provides Spring-based programming model and repository support for Apache\n      Cassandra. Offers CassandraTemplate, repository abstraction, query derivation,\n      and reactive programming support with Project Reactor.\n    image: https://spring.io/img/projects/spring-data.svg\n    humanURL: https://spring.io/projects/spring-data-cassandra\n    baseURL: http://localhost:8080\n    tags:\n      - Cassandra\n      - Distributed Database\n      - NoSQL\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-data/cassandra/docs/current/reference/html/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-data-cassandra\n      - type: Maven Repository\n        url: https://mvnrepository.com/artifact/org.springframework.data/spring-data-cassandra\n\
  \  - aid: spring-data:spring-data-neo4j\n    name: Spring Data Neo4j\n    description: >-\n      Spring-based programming model for Neo4j graph database. Provides repository\n      support, object-graph mapping, Cypher query derivation, and reactive Neo4j\n      integration with full Spring ecosystem compatibility.\n    image: https://spring.io/img/projects/spring-data.svg\n    humanURL: https://spring.io/projects/spring-data-neo4j\n    baseURL: http://localhost:8080\n    tags:\n      - Graph Database\n      - Neo4j\n      - NoSQL\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-data/neo4j/docs/current/reference/html/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-data-neo4j\n      - type: Maven Repository\n        url: https://mvnrepository.com/artifact/org.springframework.data/spring-data-neo4j\n  - aid: spring-data:spring-data-elasticsearch\n    name: Spring Data Elasticsearch\n    description: >-\n \
  \     Spring Data module for Elasticsearch search engine. Provides ElasticsearchTemplate,\n      repository abstraction, index management, full-text search queries, and\n      reactive Elasticsearch client support.\n    image: https://spring.io/img/projects/spring-data.svg\n    humanURL: https://spring.io/projects/spring-data-elasticsearch\n    baseURL: http://localhost:8080\n    tags:\n      - Elasticsearch\n      - Full-Text Search\n      - Search Engine\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-data/elasticsearch/docs/current/reference/html/\n      - type: GitHub Repository\n        url: https://github.com/spring-projects/spring-data-elasticsearch\n      - type: Maven Repository\n        url: https://mvnrepository.com/artifact/org.springframework.data/spring-data-elasticsearch\ncommon:\n  - type: Website\n    url: https://spring.io/projects/spring-data\n  - type: Blog\n    url: https://spring.io/blog/category/data\n  - type: GitHub Organization\n\
  \    url: https://github.com/spring-projects\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/spring-data\n  - type: License\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Maven Repository\n    url: https://mvnrepository.com/search?q=spring-data\n  - type: Releases\n    url: https://github.com/spring-projects/spring-data-commons/releases\n  - type: Issues\n    url: https://github.com/spring-projects/spring-data-commons/issues\n  - type: Changelog\n    url: https://github.com/spring-projects/spring-data-commons/blob/main/CHANGELOG.adoc\nmaintainers:\n  - FN: Spring Team\n    email: spring-data@pivotal.io\n    X-twitter: springcentral\n    X-github: spring-projects\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/spring-data/refs/heads/main/apis.yml
tags:
- Data Access
- Database
- Framework
- Java
- JPA
- MongoDB
- ORM
- Redis
- REST
- Spring
url: https://spring.io/projects/spring-data
use_cases: []
---
