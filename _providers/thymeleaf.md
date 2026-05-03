---
api_count: 3
apis:
- description: The core Thymeleaf template engine library providing HTML, XML, TEXT, JavaScript, and CSS template mode processing. Includes the Standard Dialect with th:text, th:each, th:if, th:unless, th:switch, th
  name: Thymeleaf Core
  slug: thymeleaf-core
- description: The Thymeleaf Spring integration module (thymeleaf-spring6) providing deep integration with Spring Framework including the SpringStandardDialect using Spring EL, SpringTemplateEngine auto-configuratio
  name: Thymeleaf Spring Integration
  slug: thymeleaf-spring-integration
- description: 'Additional Thymeleaf dialect extensions including the Java 8 Time dialect for date/time formatting, the Spring Security dialect for security tag support, and community-maintained dialects such as the '
  name: Thymeleaf Extras and Dialects
  slug: thymeleaf-extras
common:
- title: ''
  type: Website
  url: https://www.thymeleaf.org/
- title: ''
  type: Documentation
  url: https://www.thymeleaf.org/doc/tutorials/3.1/usingthymeleaf.html
- title: ''
  type: GitHub Organization
  url: https://github.com/thymeleaf
- title: ''
  type: Maven
  url: https://mvnrepository.com/artifact/org.thymeleaf/thymeleaf
- title: ''
  type: Issue Tracker
  url: https://github.com/thymeleaf/thymeleaf/issues
- title: ''
  type: Spring Boot Starter
  url: https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-thymeleaf
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/json-schema/thymeleaf-template-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/json-structure/thymeleaf-template-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/json-ld/thymeleaf-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/vocabulary/thymeleaf-vocabulary.yml
created: '2026-03-16'
description: Thymeleaf is a modern server-side Java template engine for both web and standalone environments, capable of processing HTML, XML, JavaScript, CSS, and plain text. Its primary goal is to bring elegant natural templates to development workflows — HTML pages that can be correctly displayed in browsers as static prototypes while also working as dynamic server-side templates. With over 3,000 GitHub stars, Thymeleaf 3.1 offers deep Spring Framework integration via the Spring Standard Dialect using Spring EL, extensive tool support for Eclipse and IntelliJ IDEA, and an extensible dialect system. It is widely used in Spring Boot web applications as the standard server-side rendering solution.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 23
  name: Thymeleaf Context
  property_count: 18
  slug: thymeleaf-context
layout: provider
modified: '2026-05-03'
name: Thymeleaf
skills: []
slug: thymeleaf
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: thymeleaf\nname: Thymeleaf\ndescription: >-\n  Thymeleaf is a modern server-side Java template engine for both web and\n  standalone environments, capable of processing HTML, XML, JavaScript, CSS,\n  and plain text. Its primary goal is to bring elegant natural templates to\n  development workflows — HTML pages that can be correctly displayed in browsers\n  as static prototypes while also working as dynamic server-side templates. With\n  over 3,000 GitHub stars, Thymeleaf 3.1 offers deep Spring Framework integration\n  via the Spring Standard Dialect using Spring EL, extensive tool support for\n  Eclipse and IntelliJ IDEA, and an extensible dialect system. It is widely used\n  in Spring Boot web applications as the standard server-side rendering solution.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - HTML\n  - Java\n  - Open Source\n  - Server Side Rendering\n  - Spring\n  - Spring Boot\n  - Template Engine\n\
  \  - Thymeleaf\n  - Web Development\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: thymeleaf:thymeleaf-core\n    name: Thymeleaf Core\n    description: >-\n      The core Thymeleaf template engine library providing HTML, XML, TEXT,\n      JavaScript, and CSS template mode processing. Includes the Standard\n      Dialect with th:text, th:each, th:if, th:unless, th:switch, th:href,\n      th:src, th:action, th:object, th:field expressions and the Standard\n      Expression Syntax using ${...} variable expressions, *{...} selection\n      expressions, #{...} message expressions, @{...} URL expressions, and\n      ~{...} fragment expressions.\n    humanURL: https://www.thymeleaf.org/\n    baseURL: https://www.thymeleaf.org/\n    tags:\n      - HTML\n      - Java\n      - Open Source\n      - Template Engine\n      - Thymeleaf\n    properties:\n    \
  \  - type: Documentation\n        url: https://www.thymeleaf.org/doc/tutorials/3.1/usingthymeleaf.html\n      - type: Getting Started\n        url: https://www.thymeleaf.org/doc/tutorials/3.1/usingthymeleaf.html#a-first-taste-of-thymeleaf\n      - type: GitHub\n        url: https://github.com/thymeleaf/thymeleaf\n      - type: Maven\n        url: https://mvnrepository.com/artifact/org.thymeleaf/thymeleaf\n      - type: Changelog\n        url: https://github.com/thymeleaf/thymeleaf/releases\n    version: 3.1.5.RELEASE\n\n  - aid: thymeleaf:thymeleaf-spring-integration\n    name: Thymeleaf Spring Integration\n    description: >-\n      The Thymeleaf Spring integration module (thymeleaf-spring6) providing\n      deep integration with Spring Framework including the SpringStandardDialect\n      using Spring EL, SpringTemplateEngine auto-configuration, Spring MVC view\n      resolver integration, Spring Security dialect, form binding support,\n      internationalization with Spring MessageSource,\
  \ and Spring Boot starter.\n    humanURL: https://www.thymeleaf.org/doc/tutorials/3.1/thymeleafspring.html\n    baseURL: https://www.thymeleaf.org/\n    tags:\n      - Java\n      - Spring\n      - Spring Boot\n      - Spring MVC\n      - Template Engine\n    properties:\n      - type: Documentation\n        url: https://www.thymeleaf.org/doc/tutorials/3.1/thymeleafspring.html\n      - type: GitHub\n        url: https://github.com/thymeleaf/thymeleaf-spring\n      - type: Maven Spring6\n        url: https://mvnrepository.com/artifact/org.thymeleaf/thymeleaf-spring6\n      - type: Maven Spring Boot Starter\n        url: https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-thymeleaf\n      - type: Spring Security Extras\n        url: https://github.com/thymeleaf/thymeleaf-extras-springsecurity\n\n  - aid: thymeleaf:thymeleaf-extras\n    name: Thymeleaf Extras and Dialects\n    description: >-\n      Additional Thymeleaf dialect extensions including the Java 8 Time\
  \ dialect\n      for date/time formatting, the Spring Security dialect for security tag\n      support, and community-maintained dialects such as the Layout Dialect\n      for page-level layout management.\n    humanURL: https://www.thymeleaf.org/\n    tags:\n      - Dialects\n      - Extensions\n      - Java\n      - Template Engine\n      - Thymeleaf\n    properties:\n      - type: GitHub Java8 Time Extras\n        url: https://github.com/thymeleaf/thymeleaf-extras-java8time\n      - type: GitHub Spring Security Extras\n        url: https://github.com/thymeleaf/thymeleaf-extras-springsecurity\n      - type: Layout Dialect\n        url: https://ultraq.github.io/thymeleaf-layout-dialect/\n\ncommon:\n  - type: Website\n    url: https://www.thymeleaf.org/\n  - type: Documentation\n    url: https://www.thymeleaf.org/doc/tutorials/3.1/usingthymeleaf.html\n  - type: GitHub Organization\n    url: https://github.com/thymeleaf\n  - type: Maven\n    url: https://mvnrepository.com/artifact/org.thymeleaf/thymeleaf\n\
  \  - type: Issue Tracker\n    url: https://github.com/thymeleaf/thymeleaf/issues\n  - type: Spring Boot Starter\n    url: https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-thymeleaf\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/json-schema/thymeleaf-template-schema.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/json-structure/thymeleaf-template-structure.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/json-ld/thymeleaf-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/vocabulary/thymeleaf-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/apis.yml
tags:
- HTML
- Java
- Open Source
- Server Side Rendering
- Spring
- Spring Boot
- Template Engine
- Thymeleaf
- Web Development
url: https://raw.githubusercontent.com/api-evangelist/thymeleaf/refs/heads/main/apis.yml
use_cases: []
---
