---
api_count: 9
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Postman Collections API
  slug: ''
  spec_type: OpenAPI
  url: https://www.postman.com/postman/postman-public-workspace/
apis:
- description: Postman Collections are the primary organizational unit for grouping API test cases into test suites. The Postman API allows programmatic management of collections, enabling creation, retrieval, and e
  name: Postman Collections API
  slug: ''
- description: JUnit 5 is the Java testing framework used to organize test cases into test suites. The @Suite annotation enables test class grouping, tag-based filtering, and hierarchical suite composition, making i
  name: JUnit 5
  slug: ''
- description: pytest is the Python testing framework supporting test suite organization through test classes, directories, markers, and fixtures. Its plugin architecture enables test suite reporting, parallel execu
  name: pytest
  slug: ''
- description: Jasmine is a behavior-driven JavaScript testing framework that organizes test cases into describe/it suite blocks. It is commonly used for organizing API client test suites in Node.js environments and
  name: Jasmine
  slug: ''
- description: Mocha is a flexible JavaScript test suite framework supporting both synchronous and asynchronous API tests. It provides describe/it nesting for suite organization, rich reporting, and integration with
  name: Mocha
  slug: ''
- description: Jest is a zero-configuration JavaScript testing framework with built-in test suite runner, mocking, coverage reporting, and snapshot testing. Widely used for React applications and Node.js API service
  name: Jest
  slug: ''
- description: Bruno is an open-source API client and test suite manager that stores API collections as plain files alongside application code. It enables version- controlled test suites in a format designed for git
  name: Bruno
  slug: ''
- description: 'Hurl is a command-line tool that runs HTTP requests defined in a simple plain-text format, enabling lightweight API test suites that can be committed to source control and executed in CI/CD pipelines '
  name: Hurl
  slug: ''
- description: TestNG is a Java testing framework inspired by JUnit and NUnit that provides advanced test suite configuration including grouping, prioritization, parameterized tests, and parallel execution. It is wi
  name: TestNG
  slug: ''
common:
- title: ''
  type: GitHubOrg
  url: https://github.com/api-evangelist/test-suites
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/test-suites/main/json-schema/test-suites-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/test-suites/main/json-structure/test-suites-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/test-suites/main/json-ld/test-suites-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/test-suites/main/vocabulary/test-suites-vocabulary.yml
created: '2025'
description: A collection of organized test cases designed to validate specific functionality or features of software applications and APIs. Test suites group related test cases into logical units that can be executed together, providing comprehensive coverage of a system's behavior. They are widely used by developers to build, maintain, and scale software testing across functional testing, regression testing, contract testing, and compliance validation. Test suites range from unit test collections in JUnit and pytest to API test collection suites in Postman, Bruno, and Karate.
features: []
image: ''
integrations: []
jsonld:
- class_count: 14
  name: Test Suites Context
  property_count: 8
  slug: test-suites-context
layout: provider
modified: '2026-05-03'
name: Test Suites
skills: []
slug: test-suites
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Test Suites\ndescription: >-\n  A collection of organized test cases designed to validate specific functionality\n  or features of software applications and APIs. Test suites group related test\n  cases into logical units that can be executed together, providing comprehensive\n  coverage of a system's behavior. They are widely used by developers to build,\n  maintain, and scale software testing across functional testing, regression testing,\n  contract testing, and compliance validation. Test suites range from unit test\n  collections in JUnit and pytest to API test collection suites in Postman, Bruno,\n  and Karate.\nurl: https://en.wikipedia.org/wiki/Test_suite\ntags:\n  - API Testing\n  - Collections\n  - Quality Assurance\n  - Software Development\n  - Test Management\n  - Testing\ncreated: '2025'\nmodified: '2026-05-03'\napis:\n  - name: Postman Collections API\n    description: >-\n      Postman Collections are the primary organizational unit for grouping API test\n\
  \      cases into test suites. The Postman API allows programmatic management of\n      collections, enabling creation, retrieval, and execution of API test suites\n      via the Collections API and Newman CLI runner.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.postman.com/\n    baseURL: https://api.getpostman.com\n    tags:\n      - Collections\n      - API Testing\n      - Test Management\n    properties:\n      - type: Documentation\n        url: https://learning.postman.com/docs/collections/collections-overview/\n      - type: OpenAPI\n        url: https://www.postman.com/postman/postman-public-workspace/\n\n  - name: JUnit 5\n    description: >-\n      JUnit 5 is the Java testing framework used to organize test cases into test\n      suites. The @Suite annotation enables test class grouping, tag-based filtering,\n      and hierarchical suite composition, making it the standard Java test suite\n      management solution\
  \ for unit, integration, and API tests.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://junit.org/junit5/\n    baseURL: https://junit.org/junit5/\n    tags:\n      - Java\n      - Test Suite\n      - Unit Testing\n    properties:\n      - type: Documentation\n        url: https://junit.org/junit5/docs/current/user-guide/\n      - type: GitHubOrg\n        url: https://github.com/junit-team/junit5\n\n  - name: pytest\n    description: >-\n      pytest is the Python testing framework supporting test suite organization through\n      test classes, directories, markers, and fixtures. Its plugin architecture enables\n      test suite reporting, parallel execution, and integration with coverage analysis\n      and CI/CD systems.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://pytest.org/\n    baseURL: https://pytest.org/\n    tags:\n      - Python\n      - Test Suite\n   \
  \   - Testing\n    properties:\n      - type: Documentation\n        url: https://docs.pytest.org/en/latest/\n      - type: GitHubOrg\n        url: https://github.com/pytest-dev/pytest\n\n  - name: Jasmine\n    description: >-\n      Jasmine is a behavior-driven JavaScript testing framework that organizes test\n      cases into describe/it suite blocks. It is commonly used for organizing API\n      client test suites in Node.js environments and browser-based JavaScript applications.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://jasmine.github.io/\n    baseURL: https://jasmine.github.io/\n    tags:\n      - BDD\n      - JavaScript\n      - Test Suite\n    properties:\n      - type: Documentation\n        url: https://jasmine.github.io/tutorials/your_first_suite\n      - type: GitHubOrg\n        url: https://github.com/jasmine/jasmine\n\n  - name: Mocha\n    description: >-\n      Mocha is a flexible JavaScript test suite framework\
  \ supporting both synchronous\n      and asynchronous API tests. It provides describe/it nesting for suite organization,\n      rich reporting, and integration with assertion libraries such as Chai and Sinon.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://mochajs.org/\n    baseURL: https://mochajs.org/\n    tags:\n      - JavaScript\n      - Node.js\n      - Test Suite\n    properties:\n      - type: Documentation\n        url: https://mochajs.org/#getting-started\n      - type: GitHubOrg\n        url: https://github.com/mochajs/mocha\n\n  - name: Jest\n    description: >-\n      Jest is a zero-configuration JavaScript testing framework with built-in test\n      suite runner, mocking, coverage reporting, and snapshot testing. Widely used for\n      React applications and Node.js API services, Jest organizes test cases into\n      describe blocks and supports parallel test suite execution.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://jestjs.io/\n    baseURL: https://jestjs.io/\n    tags:\n      - JavaScript\n      - React\n      - Test Suite\n    properties:\n      - type: Documentation\n        url: https://jestjs.io/docs/getting-started\n      - type: GitHubOrg\n        url: https://github.com/jestjs/jest\n\n  - name: Bruno\n    description: >-\n      Bruno is an open-source API client and test suite manager that stores API\n      collections as plain files alongside application code. It enables version-\n      controlled test suites in a format designed for git-based collaboration,\n      with scripting support for pre-request and post-request test logic.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.usebruno.com/\n    baseURL: https://www.usebruno.com/\n    tags:\n      - API Testing\n      - Collections\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://docs.usebruno.com/\n      - type:\
  \ GitHubOrg\n        url: https://github.com/usebruno/bruno\n\n  - name: Hurl\n    description: >-\n      Hurl is a command-line tool that runs HTTP requests defined in a simple plain-text\n      format, enabling lightweight API test suites that can be committed to source control\n      and executed in CI/CD pipelines without additional runtime dependencies.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://hurl.dev/\n    baseURL: https://hurl.dev/\n    tags:\n      - API Testing\n      - CLI\n      - Test Suite\n    properties:\n      - type: Documentation\n        url: https://hurl.dev/docs/installation.html\n      - type: GitHubOrg\n        url: https://github.com/Orange-OpenSource/hurl\n\n  - name: TestNG\n    description: >-\n      TestNG is a Java testing framework inspired by JUnit and NUnit that provides\n      advanced test suite configuration including grouping, prioritization, parameterized\n      tests, and parallel\
  \ execution. It is widely used for API integration test suites\n      alongside REST Assured.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://testng.org/\n    baseURL: https://testng.org/\n    tags:\n      - Java\n      - Test Suite\n      - Integration Testing\n    properties:\n      - type: Documentation\n        url: https://testng.org/doc/documentation-main.html\n      - type: GitHubOrg\n        url: https://github.com/testng-team/testng\n\ncommon:\n  - type: GitHubOrg\n    url: https://github.com/api-evangelist/test-suites\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/test-suites/main/json-schema/test-suites-schema.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/test-suites/main/json-structure/test-suites-structure.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/test-suites/main/json-ld/test-suites-context.jsonld\n\
  \  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/test-suites/main/vocabulary/test-suites-vocabulary.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/test-suites/refs/heads/main/apis.yml
tags:
- API Testing
- Collections
- Quality Assurance
- Software Development
- Test Management
- Testing
url: https://en.wikipedia.org/wiki/Test_suite
use_cases: []
---
