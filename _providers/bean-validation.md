---
api_count: 3
apis:
- description: The Jakarta Bean Validation 3.1 specification defines the constraint model, annotation processor, Validator API, method validation, group sequences, cascaded validation, constraint composition, and th
  name: Jakarta Bean Validation Specification 3.1
  slug: specification
- description: Hibernate Validator is the reference implementation of Jakarta Bean Validation. Version 9.1.0.Final implements the Jakarta Validation 3.1 specification. It provides the Validator, ValidatorFactory, Co
  name: Hibernate Validator
  slug: hibernate-validator
- description: The Jakarta Validation API JAR provides the interfaces, annotations, and exception types that constitute the Bean Validation specification contract. Constraint annotations (@NotNull, @Size, @Min, @Max
  name: Jakarta Validation API
  slug: jakarta-validation-api
common:
- title: ''
  type: Website
  url: https://beanvalidation.org/
- title: ''
  type: Documentation
  url: https://beanvalidation.org/2.0/spec/
- title: ''
  type: GitHubOrganization
  url: https://github.com/jakartaee
- title: ''
  type: Versioning
  url: https://beanvalidation.org/news/
created: '2025-01-01'
description: Jakarta Bean Validation (formerly Java Bean Validation / JSR 380) is a Java specification providing a standardized constraint model and API for validating Java beans using annotations. It defines built-in constraints (@NotNull, @Size, @Min, @Max, @Pattern, @Email, etc.), a Validator API, constraint inheritance, and method/constructor parameter validation. The current stable release is Jakarta Validation 3.1. Hibernate Validator is the reference implementation. The specification is governed by the Jakarta EE Working Group under the Eclipse Foundation.
features:
- description: Define validation constraints on Java beans using annotations such as @NotNull, @Size, @Min, @Max, @Pattern, @Email, and @Past.
  name: Annotation-Based Constraints
- description: Validate method and constructor parameters and return values using constraint annotations on method signatures.
  name: Method Validation
- description: Compose multiple constraints together using @Constraint and meta-annotations to create custom reusable constraint annotations.
  name: Constraint Composition
- description: Define validation groups and group sequences for ordered, conditional validation scenarios.
  name: Group Sequences
- description: Trigger validation of nested objects using @Valid annotation for graph-level constraint validation.
  name: Cascaded Validation
- description: Build and configure validators programmatically using the Validator and ValidatorFactory APIs without annotations.
  name: Programmatic API
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Spring integrates Jakarta Bean Validation for controller method argument validation and service layer validation.
  name: Spring Framework
- description: JPA providers call the Validator API before persisting entities to enforce database-layer constraint validation.
  name: Jakarta Persistence (JPA)
- description: Quarkus uses Hibernate Validator as its Bean Validation implementation with zero-config support in native images.
  name: Quarkus
- description: Jakarta Faces integrates Bean Validation for automatic form field validation in web applications.
  name: Jakarta Faces (JSF)
- description: Micronaut Framework uses Bean Validation for controller parameter and return value validation.
  name: Micronaut
layout: provider
modified: '2026-04-19'
name: Bean Validation
skills: []
slug: bean-validation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bean-validation\nname: Bean Validation\ndescription: >-\n  Jakarta Bean Validation (formerly Java Bean Validation / JSR 380) is a Java\n  specification providing a standardized constraint model and API for validating\n  Java beans using annotations. It defines built-in constraints (@NotNull, @Size,\n  @Min, @Max, @Pattern, @Email, etc.), a Validator API, constraint inheritance, and\n  method/constructor parameter validation. The current stable release is Jakarta\n  Validation 3.1. Hibernate Validator is the reference implementation. The specification\n  is governed by the Jakarta EE Working Group under the Eclipse Foundation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Bean Validation\n  - Data Quality\n  - Java\n  - Validation\n  - Jakarta EE\n  - Constraints\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/bean-validation/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-19'\n\
  specificationVersion: '0.19'\napis:\n  - aid: bean-validation:specification\n    name: Jakarta Bean Validation Specification 3.1\n    description: >-\n      The Jakarta Bean Validation 3.1 specification defines the constraint model,\n      annotation processor, Validator API, method validation, group sequences,\n      cascaded validation, constraint composition, and the metadata API for introspecting\n      validation constraints on Java classes, fields, methods, and constructors.\n    humanURL: https://beanvalidation.org/3.1/\n    tags:\n      - Bean Validation\n      - Java\n      - Jakarta EE\n      - Specification\n    properties:\n      - type: Documentation\n        url: https://beanvalidation.org/3.1/\n      - type: Specification\n        url: https://jakarta.ee/specifications/bean-validation/3.1/\n      - type: GitHubRepository\n        url: https://github.com/jakartaee/validation\n\n  - aid: bean-validation:hibernate-validator\n    name: Hibernate Validator\n    description: >-\n\
  \      Hibernate Validator is the reference implementation of Jakarta Bean Validation.\n      Version 9.1.0.Final implements the Jakarta Validation 3.1 specification. It\n      provides the Validator, ValidatorFactory, ConstraintViolation APIs, additional\n      built-in constraints beyond the spec, programmatic constraint definition, and\n      message interpolation. Available via Maven Central and published under Apache 2.0.\n    humanURL: https://hibernate.org/validator/\n    tags:\n      - Bean Validation\n      - Java\n      - Reference Implementation\n      - Hibernate\n    properties:\n      - type: Documentation\n        url: https://docs.jboss.org/hibernate/stable/validator/reference/en-US/html_single/\n      - type: GettingStarted\n        url: https://hibernate.org/validator/documentation/getting-started/\n      - type: GitHubRepository\n        url: https://github.com/hibernate/hibernate-validator\n      - type: SDK\n        url: https://mvnrepository.com/artifact/org.hibernate.validator/hibernate-validator\n\
  \        title: Maven Central\n\n  - aid: bean-validation:jakarta-validation-api\n    name: Jakarta Validation API\n    description: >-\n      The Jakarta Validation API JAR provides the interfaces, annotations, and\n      exception types that constitute the Bean Validation specification contract.\n      Constraint annotations (@NotNull, @Size, @Min, @Max, @Pattern, @Email, @Future,\n      @Past, @Positive, @Negative, etc.), Validator, ValidatorFactory, ConstraintViolation,\n      and Path types are all defined in the API. Available on Maven Central.\n    humanURL: https://jakarta.ee/specifications/bean-validation/3.1/\n    tags:\n      - Bean Validation\n      - Java\n      - API\n      - Jakarta EE\n    properties:\n      - type: Specification\n        url: https://jakarta.ee/specifications/bean-validation/3.1/\n      - type: SDK\n        url: https://mvnrepository.com/artifact/jakarta.validation/jakarta.validation-api\n        title: Maven Central\n\ncommon:\n  - type: Website\n   \
  \ url: https://beanvalidation.org/\n  - type: Documentation\n    url: https://beanvalidation.org/2.0/spec/\n  - type: GitHubOrganization\n    url: https://github.com/jakartaee\n  - type: Versioning\n    url: https://beanvalidation.org/news/\n  - type: Features\n    data:\n      - name: Annotation-Based Constraints\n        description: Define validation constraints on Java beans using annotations such as @NotNull, @Size, @Min, @Max, @Pattern, @Email, and @Past.\n      - name: Method Validation\n        description: Validate method and constructor parameters and return values using constraint annotations on method signatures.\n      - name: Constraint Composition\n        description: Compose multiple constraints together using @Constraint and meta-annotations to create custom reusable constraint annotations.\n      - name: Group Sequences\n        description: Define validation groups and group sequences for ordered, conditional validation scenarios.\n      - name: Cascaded Validation\n\
  \        description: Trigger validation of nested objects using @Valid annotation for graph-level constraint validation.\n      - name: Programmatic API\n        description: Build and configure validators programmatically using the Validator and ValidatorFactory APIs without annotations.\n  - type: UseCases\n    data:\n      - name: REST API Input Validation\n        description: Validate request body and query parameters in JAX-RS and Spring REST controllers using Bean Validation annotations.\n      - name: Form Validation\n        description: Validate user-submitted form data in Jakarta Faces, Spring MVC, and other web frameworks.\n      - name: Domain Model Validation\n        description: Enforce business rules and data integrity constraints on JPA entity classes and domain objects.\n      - name: Microservices Contract Validation\n        description: Validate inter-service request and response payloads to enforce API contracts in microservices architectures.\n  - type: Integrations\n\
  \    data:\n      - name: Spring Framework\n        description: Spring integrates Jakarta Bean Validation for controller method argument validation and service layer validation.\n      - name: Jakarta Persistence (JPA)\n        description: JPA providers call the Validator API before persisting entities to enforce database-layer constraint validation.\n      - name: Quarkus\n        description: Quarkus uses Hibernate Validator as its Bean Validation implementation with zero-config support in native images.\n      - name: Jakarta Faces (JSF)\n        description: Jakarta Faces integrates Bean Validation for automatic form field validation in web applications.\n      - name: Micronaut\n        description: Micronaut Framework uses Bean Validation for controller parameter and return value validation.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bean-validation/refs/heads/main/apis.yml
tags:
- Bean Validation
- Data Quality
- Java
- Validation
- Jakarta EE
- Constraints
url: https://raw.githubusercontent.com/api-evangelist/bean-validation/refs/heads/main/apis.yml
use_cases:
- description: Validate request body and query parameters in JAX-RS and Spring REST controllers using Bean Validation annotations.
  name: REST API Input Validation
- description: Validate user-submitted form data in Jakarta Faces, Spring MVC, and other web frameworks.
  name: Form Validation
- description: Enforce business rules and data integrity constraints on JPA entity classes and domain objects.
  name: Domain Model Validation
- description: Validate inter-service request and response payloads to enforce API contracts in microservices architectures.
  name: Microservices Contract Validation
---
