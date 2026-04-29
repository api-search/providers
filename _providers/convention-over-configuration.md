---
api_count: 5
apis:
- description: Ruby on Rails is the framework that popularized convention over configuration. By default, an ActiveRecord model named Sale maps to a sales table, controllers map to RESTful resources, and the directo
  name: Ruby on Rails
  slug: rails
- description: 'Spring Boot is the convention-over-configuration evolution of the Spring Framework. Auto-configuration detects classpath dependencies and wires beans automatically, starter dependencies bundle common '
  name: Spring Boot
  slug: spring-boot
- description: Apache Maven introduced a strict project layout (src/main/java, src/test/java, target/) and a convention-driven build lifecycle. A pom.xml that declares dependencies and a parent POM is enough for mos
  name: Apache Maven
  slug: maven
- description: Next.js exemplifies convention over configuration in modern web frameworks. The pages and app directory conventions auto-generate routes, file-based layouts, error boundaries, loading UI, and API rout
  name: Next.js
  slug: next-js
- description: Hugo defines content, layouts, archetypes, and partials by directory convention. A content/posts directory yields a section with a list page and per-post pages without explicit routing configuration.
  name: Hugo Static Site Generator
  slug: hugo
common:
- title: ''
  type: Reference
  url: https://en.wikipedia.org/wiki/Convention_over_configuration
- title: ''
  type: Reference
  url: https://rubyonrails.org/doctrine
- title: ''
  type: Reference
  url: https://docs.spring.io/spring-boot/index.html
- title: ''
  type: Reference
  url: https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html
- title: ''
  type: Reference
  url: https://nextjs.org/docs
created: '2025-01-01'
description: Convention over Configuration (CoC) is a software design principle that prefers sensible defaults and standard patterns over explicit, repetitive configuration. Frameworks that adopt CoC reduce the number of decisions a developer must make to start a new project while still allowing overrides for non-standard cases. CoC was popularized by Ruby on Rails but predates Rails, drawing on UI principles like the principle of least astonishment and conventions in JavaBeans, Maven, and other Java ecosystems. The principle continues to shape modern frameworks such as Spring Boot, Next.js, Astro, Phoenix, Ember, Hugo, and Remix.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Convention Over Configuration
skills: []
slug: convention-over-configuration
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: convention-over-configuration\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/convention-over-configuration/refs/heads/main/apis.yml\nname: Convention Over Configuration\nx-type: topic\ndescription: >-\n  Convention over Configuration (CoC) is a software design principle that\n  prefers sensible defaults and standard patterns over explicit, repetitive\n  configuration. Frameworks that adopt CoC reduce the number of decisions a\n  developer must make to start a new project while still allowing\n  overrides for non-standard cases. CoC was popularized by Ruby on Rails\n  but predates Rails, drawing on UI principles like the principle of least\n  astonishment and conventions in JavaBeans, Maven, and other Java\n  ecosystems. The principle continues to shape modern frameworks such as\n  Spring Boot, Next.js, Astro, Phoenix, Ember, Hugo, and Remix.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Conventions\n  - Design\
  \ Principle\n  - Frameworks\n  - Software Design\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: convention-over-configuration:rails\n    name: Ruby on Rails\n    description: >-\n      Ruby on Rails is the framework that popularized convention over\n      configuration. By default, an ActiveRecord model named Sale maps to\n      a sales table, controllers map to RESTful resources, and the directory\n      layout under app/ implies wiring without explicit configuration files.\n    humanURL: https://rubyonrails.org/\n    baseURL: https://rubyonrails.org\n    tags:\n      - Active Record\n      - Rails\n      - Ruby\n    properties:\n      - type: Documentation\n        url: https://rubyonrails.org/doctrine\n      - type: Reference\n        url: https://guides.rubyonrails.org/getting_started.html\n    x-features:\n      - Pluralized table inference for ActiveRecord models\n      - RESTful controller routing inferred from resource names\n    \
  \  - Generators for resources, migrations, and tests\n      - Pattern of opinionated defaults with override hooks\n    x-useCases:\n      - Bootstrapping production web applications quickly\n      - Establishing consistent codebases across teams\n  - aid: convention-over-configuration:spring-boot\n    name: Spring Boot\n    description: >-\n      Spring Boot is the convention-over-configuration evolution of the\n      Spring Framework. Auto-configuration detects classpath dependencies\n      and wires beans automatically, starter dependencies bundle common\n      stacks, and standard application.yml properties shape behavior with\n      sensible defaults.\n    humanURL: https://spring.io/projects/spring-boot\n    baseURL: https://spring.io\n    tags:\n      - Auto-Configuration\n      - Java\n      - Spring\n    properties:\n      - type: Documentation\n        url: https://docs.spring.io/spring-boot/index.html\n      - type: Reference\n        url: https://spring.io/projects/spring-boot\n\
  \    x-features:\n      - Auto-configuration based on classpath presence\n      - Spring Boot starters for common stacks\n      - Externalized configuration via application.yml/properties\n      - Embedded servers and standalone JAR packaging\n    x-useCases:\n      - Bootstrapping enterprise Java microservices\n      - Reducing XML and Java configuration boilerplate\n  - aid: convention-over-configuration:maven\n    name: Apache Maven\n    description: >-\n      Apache Maven introduced a strict project layout (src/main/java,\n      src/test/java, target/) and a convention-driven build lifecycle. A\n      pom.xml that declares dependencies and a parent POM is enough for\n      most Java projects to compile, test, package, and deploy.\n    humanURL: https://maven.apache.org/\n    baseURL: https://maven.apache.org\n    tags:\n      - Build\n      - Java\n      - Maven\n    properties:\n      - type: Documentation\n        url: https://maven.apache.org/guides/introduction/introduction-to-the-pom.html\n\
  \      - type: Reference\n        url: https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html\n    x-features:\n      - Standard directory layout for Java projects\n      - Convention-driven phases (compile, test, package, install, deploy)\n      - Plugin architecture for custom phases\n      - Inheritance via parent POMs\n    x-useCases:\n      - Standardizing build tooling across Java projects\n      - Hosting and consuming artifacts from Maven Central\n  - aid: convention-over-configuration:next-js\n    name: Next.js\n    description: >-\n      Next.js exemplifies convention over configuration in modern web\n      frameworks. The pages and app directory conventions auto-generate\n      routes, file-based layouts, error boundaries, loading UI, and API\n      routes without explicit router configuration.\n    humanURL: https://nextjs.org/\n    baseURL: https://nextjs.org\n    tags:\n      - Next.js\n      - React\n      - Web\n    properties:\n\
  \      - type: Documentation\n        url: https://nextjs.org/docs\n      - type: Reference\n        url: https://nextjs.org/docs/app/building-your-application/routing\n    x-features:\n      - File-system-based routing\n      - app/ conventions for layouts, loading, and error UIs\n      - Auto-generated API routes from app/api/* paths\n      - Conventions for static and dynamic rendering\n    x-useCases:\n      - Building React applications with minimal routing config\n      - Standardizing front-end architecture across teams\n  - aid: convention-over-configuration:hugo\n    name: Hugo Static Site Generator\n    description: >-\n      Hugo defines content, layouts, archetypes, and partials by directory\n      convention. A content/posts directory yields a section with a list\n      page and per-post pages without explicit routing configuration.\n    humanURL: https://gohugo.io/\n    baseURL: https://gohugo.io\n    tags:\n      - Go\n      - Hugo\n      - Static Sites\n    properties:\n\
  \      - type: Documentation\n        url: https://gohugo.io/documentation/\n      - type: Reference\n        url: https://gohugo.io/getting-started/directory-structure/\n    x-features:\n      - Section-based content directory layout\n      - Layout lookup order with sensible fallbacks\n      - Archetypes for templating new content files\n      - Configuration-light defaults with TOML/YAML overrides\n    x-useCases:\n      - Building documentation sites with little setup\n      - Producing fast static sites with default conventions\ncommon:\n  - type: Reference\n    url: https://en.wikipedia.org/wiki/Convention_over_configuration\n  - type: Reference\n    url: https://rubyonrails.org/doctrine\n  - type: Reference\n    url: https://docs.spring.io/spring-boot/index.html\n  - type: Reference\n    url: https://maven.apache.org/guides/introduction/introduction-to-the-standard-directory-layout.html\n  - type: Reference\n    url: https://nextjs.org/docs\nmaintainers:\n  - FN: Kin Lane\n    email:\
  \ kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/convention-over-configuration/refs/heads/main/apis.yml
tags:
- Conventions
- Design Principle
- Frameworks
- Software Design
url: https://raw.githubusercontent.com/api-evangelist/convention-over-configuration/refs/heads/main/apis.yml
use_cases: []
---
