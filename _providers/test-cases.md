---
api_count: 6
apis:
- description: API for managing Postman collections, environments, monitors, mock servers, and test runs programmatically. Supports creating and executing test cases via Newman and Postman scripts.
  name: Postman API
  slug: ''
- description: REST API for TestRail test case management system, enabling programmatic creation, update, and retrieval of test cases, test runs, test plans, and results.
  name: TestRail API
  slug: ''
- description: REST API for Zephyr Scale test management in Jira Cloud, supporting test case creation, test cycles, test execution, and reporting within Jira.
  name: Zephyr Scale API
  slug: ''
- description: REST API for Xray test management in Jira, supporting test case management, test execution, test coverage, and CI/CD integration for structured test case workflows.
  name: Xray Test Management API
  slug: ''
- description: REST API for PractiTest test management platform supporting test case libraries, test runs, requirements, defects, and full quality management workflows.
  name: PractiTest API
  slug: ''
- description: API for Katalon TestOps test automation platform, providing endpoints for test case management, test execution, reports, and integration with CI/CD pipelines.
  name: Katalon TestOps API
  slug: ''
common:
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Test_case
- title: ''
  type: JSONSchema
  url: json-schema/test-cases-test-case-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/test-cases-test-step-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/test-cases-test-result-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/test-cases-test-suite-schema.json
- title: ''
  type: JSONLD
  url: json-ld/test-cases-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/test-cases-vocabulary.yml
created: '2025'
description: Structured scenarios that verify software functionality by defining inputs, execution conditions, and expected results to ensure quality and correctness. Test cases are the fundamental units of software testing that document what needs to be tested, the conditions under which the test runs, and the expected outcomes. They are widely used across manual testing, automated testing, and API testing workflows.
features:
- description: Define structured test scenarios with preconditions, inputs, execution steps, and expected results.
  name: Test Case Design
- description: Organize, version, and prioritize test cases within test suites and test plans.
  name: Test Case Management
- description: Run test cases with multiple input datasets using data-driven testing approaches.
  name: Parameterized Testing
- description: Share and reuse test cases across different test suites and projects.
  name: Reusability
- description: Link test cases to requirements, user stories, and defects for full traceability.
  name: Traceability
- description: Execute test cases programmatically via APIs or CI/CD integrations.
  name: Automated Execution
image: ''
integrations:
- description: Link test cases to Jira issues and track test coverage for requirements.
  name: Jira
- description: Trigger test case execution as part of Jenkins CI/CD pipelines.
  name: Jenkins
- description: Run test cases automatically on pull requests and push events.
  name: GitHub Actions
- description: Receive test run notifications and results in Slack channels.
  name: Slack
jsonld:
- class_count: 4
  name: Test Cases Context
  property_count: 37
  slug: test-cases-context
layout: provider
modified: '2026-05-03'
name: Test Cases
skills: []
slug: test-cases
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Test Cases\ndescription: Structured scenarios that verify software functionality by defining inputs, execution conditions, and expected results to ensure quality and correctness. Test cases are the fundamental units of software testing that document what needs to be tested, the conditions under which the test runs, and the expected outcomes. They are widely used across manual testing, automated testing, and API testing workflows.\nurl: https://en.wikipedia.org/wiki/Test_case\ntags:\n  - API Testing\n  - Automation\n  - Quality Assurance\n  - Software Development\n  - Software Testing\n  - Testing\ncreated: '2025'\nmodified: '2026-05-03'\napis:\n  - name: Postman API\n    description: API for managing Postman collections, environments, monitors, mock servers, and test runs programmatically. Supports creating and executing test cases via Newman and Postman scripts.\n    humanURL: https://www.postman.com/postman/workspace/postman-public-workspace/collection/12959542-c8142d51-e97c-46b6-bd77-52bb66712c9a\n\
  \    baseURL: https://api.getpostman.com\n    tags:\n      - API Testing\n      - Collections\n      - Environments\n      - Test Automation\n    properties:\n      - type: Documentation\n        url: https://www.postman.com/postman/workspace/postman-public-workspace/documentation/12959542-c8142d51-e97c-46b6-bd77-52bb66712c9a\n  - name: TestRail API\n    description: REST API for TestRail test case management system, enabling programmatic creation, update, and retrieval of test cases, test runs, test plans, and results.\n    humanURL: https://www.testrail.com/api\n    baseURL: https://yourproject.testrail.io/index.php?/api/v2\n    tags:\n      - Test Case Management\n      - Test Management\n      - Test Runs\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://support.testrail.com/hc/en-us/articles/7077990413588-Introduction-to-the-API\n      - type: APIReference\n        url: https://support.testrail.com/hc/en-us/categories/7076832415124-API-Reference\n\
  \  - name: Zephyr Scale API\n    description: REST API for Zephyr Scale test management in Jira Cloud, supporting test case creation, test cycles, test execution, and reporting within Jira.\n    humanURL: https://support.smartbear.com/zephyr-scale-cloud/api-docs/\n    baseURL: https://api.zephyrscale.smartbear.com/v2\n    tags:\n      - Jira\n      - Test Case Management\n      - Test Management\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://support.smartbear.com/zephyr-scale-cloud/api-docs/\n  - name: Xray Test Management API\n    description: REST API for Xray test management in Jira, supporting test case management, test execution, test coverage, and CI/CD integration for structured test case workflows.\n    humanURL: https://docs.getxray.app/display/XRAYCLOUD/REST+API\n    baseURL: https://xray.cloud.getxray.app/api/v2\n    tags:\n      - Behavior-Driven Development\n      - Jira\n      - Test Case Management\n      - Test Execution\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.getxray.app/display/XRAYCLOUD/REST+API\n  - name: PractiTest API\n    description: REST API for PractiTest test management platform supporting test case libraries, test runs, requirements, defects, and full quality management workflows.\n    humanURL: https://developers.practitest.com\n    baseURL: https://api.practitest.com/api/v2\n    tags:\n      - Quality Management\n      - Requirements\n      - Test Case Management\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://developers.practitest.com\n      - type: APIReference\n        url: https://developers.practitest.com/docs/api-reference\n  - name: Katalon TestOps API\n    description: API for Katalon TestOps test automation platform, providing endpoints for test case management, test execution, reports, and integration with CI/CD pipelines.\n    humanURL: https://katalon.com\n    baseURL: https://testops.katalon.io/api/v1\n    tags:\n      - CI/CD\
  \ Integration\n      - Test Automation\n      - Test Case Management\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://docs.katalon.com/docs/katalon-testops/remote-execution/katalon-testops-api\ncommon:\n  - type: Documentation\n    url: https://en.wikipedia.org/wiki/Test_case\n  - type: Features\n    data:\n      - name: Test Case Design\n        description: Define structured test scenarios with preconditions, inputs, execution steps, and expected results.\n      - name: Test Case Management\n        description: Organize, version, and prioritize test cases within test suites and test plans.\n      - name: Parameterized Testing\n        description: Run test cases with multiple input datasets using data-driven testing approaches.\n      - name: Reusability\n        description: Share and reuse test cases across different test suites and projects.\n      - name: Traceability\n        description: Link test cases to requirements, user stories, and defects\
  \ for full traceability.\n      - name: Automated Execution\n        description: Execute test cases programmatically via APIs or CI/CD integrations.\n  - type: UseCases\n    data:\n      - name: Regression Testing\n        description: Verify that existing functionality has not been broken by recent code changes.\n      - name: Acceptance Testing\n        description: Confirm that software meets business requirements and user expectations.\n      - name: API Contract Testing\n        description: Validate API request and response payloads against defined contracts and schemas.\n      - name: Smoke Testing\n        description: Quickly verify that the most critical application functions work after a new build.\n      - name: Integration Testing\n        description: Validate that different modules and services interact correctly with each other.\n  - type: Integrations\n    data:\n      - name: Jira\n        description: Link test cases to Jira issues and track test coverage for requirements.\n\
  \      - name: Jenkins\n        description: Trigger test case execution as part of Jenkins CI/CD pipelines.\n      - name: GitHub Actions\n        description: Run test cases automatically on pull requests and push events.\n      - name: Slack\n        description: Receive test run notifications and results in Slack channels.\n  - type: JSONSchema\n    url: json-schema/test-cases-test-case-schema.json\n  - type: JSONSchema\n    url: json-schema/test-cases-test-step-schema.json\n  - type: JSONSchema\n    url: json-schema/test-cases-test-result-schema.json\n  - type: JSONSchema\n    url: json-schema/test-cases-test-suite-schema.json\n  - type: JSONLD\n    url: json-ld/test-cases-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/test-cases-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/test-cases/refs/heads/main/apis.yml
tags:
- API Testing
- Automation
- Quality Assurance
- Software Development
- Software Testing
- Testing
url: https://en.wikipedia.org/wiki/Test_case
use_cases:
- description: Verify that existing functionality has not been broken by recent code changes.
  name: Regression Testing
- description: Confirm that software meets business requirements and user expectations.
  name: Acceptance Testing
- description: Validate API request and response payloads against defined contracts and schemas.
  name: API Contract Testing
- description: Quickly verify that the most critical application functions work after a new build.
  name: Smoke Testing
- description: Validate that different modules and services interact correctly with each other.
  name: Integration Testing
---
