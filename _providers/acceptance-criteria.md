---
api_count: 5
apis:
- description: GitHub Issues API enables teams to create, manage, and track user stories and acceptance criteria as structured issue records with labels, milestones, and custom fields. Commonly used to attach accept
  name: GitHub Issues API
  slug: github-issues-api
- description: Jira REST API provides access to issues, user stories, epics, and acceptance criteria stored in custom fields. Teams use Jira to define, link, and track acceptance criteria against development work it
  name: Jira Issues API
  slug: jira-issues-api
- description: Azure DevOps Work Items REST API enables management of user stories, acceptance criteria, and test cases in Azure Boards. Acceptance criteria are stored as a rich text field on Product Backlog Items a
  name: Azure DevOps Work Items API
  slug: azure-devops-work-items-api
- description: Linear GraphQL API provides access to issues, projects, and cycles used by engineering teams to track features and acceptance criteria. Linear supports structured issue descriptions with Markdown, ena
  name: Linear API
  slug: linear-api
- description: TestRail REST API provides access to test cases, test runs, test plans, and results. Teams use TestRail to formally document acceptance criteria as test cases with preconditions, expected results, and
  name: TestRail API
  slug: testrail-api
capabilities:
- description: ''
  name: Requirements Management
  slug: requirements-management
common:
- title: ''
  type: Website
  url: https://www.agilealliance.org/glossary/acceptance-criteria/
- title: ''
  type: GettingStarted
  url: https://www.mountaingoatsoftware.com/blog/clarifying-the-relationship-between-definition-of-done-and-conditions-of-satisfaction
- title: ''
  type: SpectralRules
  url: rules/acceptance-criteria-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/requirements-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/acceptance-criteria-vocabulary.yaml
- title: ''
  type: OpenAPI
  url: openapi/acceptance-criteria-management.yaml
- title: ''
  type: JSONSchema
  url: json-schema/acceptance-criteria-management-user-story-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/acceptance-criteria-management-acceptance-criterion-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/acceptance-criteria-management-scenario-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/acceptance-criteria-management-test-run-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/acceptance-criteria-management-user-story-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/acceptance-criteria-management-acceptance-criterion-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/acceptance-criteria-management-scenario-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/acceptance-criteria-management-test-run-structure.json
- title: ''
  type: JSON-LD
  url: json-ld/acceptance-criteria-management-context.jsonld
- title: ''
  type: Example
  url: examples/acceptance-criteria-management-user-story-example.json
- title: ''
  type: Example
  url: examples/acceptance-criteria-management-acceptance-criterion-example.json
- title: ''
  type: Example
  url: examples/acceptance-criteria-management-scenario-example.json
- title: ''
  type: Example
  url: examples/acceptance-criteria-management-test-run-example.json
created: '2025-01-01'
description: Acceptance criteria are predefined conditions that a product, feature, or user story must meet to be considered complete and acceptable by stakeholders. These criteria establish clear, testable requirements that guide development, validate when work is done, and serve as the foundation for automated testing through frameworks like Cucumber, SpecFlow, and Behave. APIs in this space support requirements management, behavior-driven development (BDD), test execution tracking, and agile project management workflows.
features:
- description: Structured Given/When/Then format for writing human-readable acceptance criteria that can be directly executed as automated tests
  name: Gherkin Syntax Support
- description: Behavior-driven development workflows connecting acceptance criteria to automated test suites via Cucumber, SpecFlow, or Behave
  name: BDD Workflow Integration
- description: Structured checklist format for breaking down complex acceptance criteria into discrete, verifiable conditions
  name: Acceptance Criteria Checklists
- description: Linking acceptance criteria to user stories, epics, test cases, and defects for end-to-end traceability
  name: Requirements Traceability
- description: Executing acceptance criteria as automated test suites that verify implementation correctness on each code change
  name: Automated Acceptance Testing
- description: Shared definition of acceptance criteria between product owners, developers, and QA engineers using accessible, plain-language formats
  name: Stakeholder Collaboration
- description: Incorporating acceptance criteria verification into team Definition of Done checklists and sprint completion gates
  name: Definition of Done Integration
- description: Tracking which acceptance criteria have passing automated tests and which remain untested or failing
  name: Test Coverage Reporting
image: /assets/icons/acceptance-criteria.png
integrations:
- description: Open-source BDD testing framework that executes Gherkin-formatted acceptance criteria as automated tests
  name: Cucumber
- description: BDD framework for .NET that maps Gherkin feature files to C# step definitions for automated acceptance testing
  name: SpecFlow
- description: Python BDD testing library that runs Gherkin acceptance criteria scenarios against Python application code
  name: Behave
- description: Project management platform with dedicated Acceptance Criteria field on user story issue types
  name: Jira
- description: Issue tracking with Markdown checklist support for embedding structured acceptance criteria on feature issues
  name: GitHub Issues
- description: Microsoft project management with Acceptance Criteria rich-text field on User Story and Product Backlog Item work items
  name: Azure DevOps Boards
- description: Test management platform for formalizing acceptance criteria as structured test cases with expected outcomes
  name: TestRail
- description: Modern issue tracker supporting Markdown acceptance criteria on issues with checklist rendering
  name: Linear
jsonld:
- class_count: 38
  name: Acceptance Criteria Management Context
  property_count: 5
  slug: acceptance-criteria-management-context
layout: provider
modified: '2026-04-19'
name: Acceptance Criteria
rules:
- name: Acceptance Criteria API Rules
  rule_count: 27
  severity_counts:
    error: 9
    hint: 0
    info: 4
    warn: 14
  slug: acceptance-criteria-spectral-rules
skills: []
slug: acceptance-criteria
solutions: []
source_filename: apis.yml
source_yaml: "aid: acceptance-criteria\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/acceptance-criteria/refs/heads/main/apis.yml\nname: Acceptance Criteria\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Agile\n- Behavior Driven Development\n- Gherkin\n- Quality Assurance\n- Requirements\n- Testing\n- User Stories\ndescription: >-\n  Acceptance criteria are predefined conditions that a product, feature, or user story\n  must meet to be considered complete and acceptable by stakeholders. These criteria\n  establish clear, testable requirements that guide development, validate when work\n  is done, and serve as the foundation for automated testing through frameworks like\n  Cucumber, SpecFlow, and Behave. APIs in this space support requirements management,\n  behavior-driven development (BDD), test execution tracking, and agile project management\n  workflows.\ncreated: '2025-01-01'\nmodified: '2026-04-19'\nspecificationVersion:\
  \ '0.19'\napis:\n- aid: acceptance-criteria:github-issues-api\n  name: GitHub Issues API\n  description: GitHub Issues API enables teams to create, manage, and track user\n    stories and acceptance criteria as structured issue records with labels, \n    milestones, and custom fields. Commonly used to attach acceptance criteria \n    directly to issues using body text or checklists in Markdown.\n  humanURL: https://docs.github.com/en/rest/issues\n  baseURL: https://api.github.com\n  tags:\n  - Issues\n  - User Stories\n  - Requirements\n  - Project Management\n  properties:\n  - url: https://docs.github.com/en/rest/issues\n    type: Documentation\n  - url: \n      https://docs.github.com/en/rest/authentication/authenticating-to-the-rest-api\n    type: Authentication\n  - url: \n      https://docs.github.com/en/rest/overview/resources-in-the-rest-api#rate-limiting\n    type: RateLimits\n- aid: acceptance-criteria:jira-issues-api\n  name: Jira Issues API\n  description: Jira REST API provides\
  \ access to issues, user stories, epics, and\n    acceptance criteria stored in custom fields. Teams use Jira to define, link,\n    and track acceptance criteria against development work items throughout the \n    sprint lifecycle.\n  humanURL: https://developer.atlassian.com/cloud/jira/platform/rest/v3/\n  baseURL: https://your-domain.atlassian.net/rest/api/3\n  tags:\n  - Issues\n  - User Stories\n  - Sprint\n  - Project Management\n  properties:\n  - url: https://developer.atlassian.com/cloud/jira/platform/rest/v3/\n    type: Documentation\n  - url: \n      https://developer.atlassian.com/cloud/jira/platform/basic-auth-for-rest-apis/\n    type: Authentication\n  - url: https://developer.atlassian.com/cloud/jira/platform/rate-limiting/\n    type: RateLimits\n- aid: acceptance-criteria:azure-devops-work-items-api\n  name: Azure DevOps Work Items API\n  description: Azure DevOps Work Items REST API enables management of user \n    stories, acceptance criteria, and test cases in Azure Boards.\
  \ Acceptance \n    criteria are stored as a rich text field on Product Backlog Items and User \n    Story work item types, accessible and updatable via REST.\n  humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/wit/\n  baseURL: https://dev.azure.com/{organization}/{project}/_apis/wit\n  tags:\n  - Work Items\n  - User Stories\n  - Azure\n  - Project Management\n  properties:\n  - url: https://learn.microsoft.com/en-us/rest/api/azure/devops/wit/\n    type: Documentation\n  - url: \n      https://learn.microsoft.com/en-us/azure/devops/integrate/get-started/authentication/\n    type: Authentication\n- aid: acceptance-criteria:linear-api\n  name: Linear API\n  description: Linear GraphQL API provides access to issues, projects, and \n    cycles used by engineering teams to track features and acceptance criteria. \n    Linear supports structured issue descriptions with Markdown, enabling teams \n    to embed acceptance criteria checklists directly on issues.\n  humanURL: \n\
  \    https://developers.linear.app/docs/graphql/working-with-the-graphql-api\n  baseURL: https://api.linear.app/graphql\n  tags:\n  - Issues\n  - Project Management\n  - GraphQL\n  - Requirements\n  properties:\n  - url: https://developers.linear.app/docs/graphql/working-with-the-graphql-api\n    type: Documentation\n  - url: \n      https://developers.linear.app/docs/graphql/working-with-the-graphql-api#authentication\n    type: Authentication\n- aid: acceptance-criteria:testrail-api\n  name: TestRail API\n  description: TestRail REST API provides access to test cases, test runs, test \n    plans, and results. Teams use TestRail to formally document acceptance \n    criteria as test cases with preconditions, expected results, and \n    step-by-step validation criteria that map directly to user stories.\n  humanURL: \n    https://support.testrail.com/hc/en-us/articles/7077792415124-Introduction-to-the-TestRail-API\n  baseURL: https://your-instance.testrail.io/index.php?/api/v2\n  tags:\n\
  \  - Test Cases\n  - Test Management\n  - Quality Assurance\n  - Requirements\n  properties:\n  - url: \n      https://support.testrail.com/hc/en-us/articles/7077792415124-Introduction-to-the-TestRail-API\n    type: Documentation\n  - url: \n      https://support.testrail.com/hc/en-us/articles/7077792415124-Introduction-to-the-TestRail-API#authentication\n    type: Authentication\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\ncommon:\n- type: Website\n  url: https://www.agilealliance.org/glossary/acceptance-criteria/\n- type: GettingStarted\n  url: \n    https://www.mountaingoatsoftware.com/blog/clarifying-the-relationship-between-definition-of-done-and-conditions-of-satisfaction\n- type: SpectralRules\n  url: rules/acceptance-criteria-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/requirements-management.yaml\n- type: Vocabulary\n  url: vocabulary/acceptance-criteria-vocabulary.yaml\n- url: openapi/acceptance-criteria-management.yaml\n  type: OpenAPI\n\
  - url: json-schema/acceptance-criteria-management-user-story-schema.json\n  type: JSONSchema\n- url: \n    json-schema/acceptance-criteria-management-acceptance-criterion-schema.json\n  type: JSONSchema\n- url: json-schema/acceptance-criteria-management-scenario-schema.json\n  type: JSONSchema\n- url: json-schema/acceptance-criteria-management-test-run-schema.json\n  type: JSONSchema\n- url: json-structure/acceptance-criteria-management-user-story-structure.json\n  type: JSONStructure\n- url: \n    json-structure/acceptance-criteria-management-acceptance-criterion-structure.json\n  type: JSONStructure\n- url: json-structure/acceptance-criteria-management-scenario-structure.json\n  type: JSONStructure\n- url: json-structure/acceptance-criteria-management-test-run-structure.json\n  type: JSONStructure\n- url: json-ld/acceptance-criteria-management-context.jsonld\n  type: JSON-LD\n- url: examples/acceptance-criteria-management-user-story-example.json\n  type: Example\n- url: examples/acceptance-criteria-management-acceptance-criterion-example.json\n\
  \  type: Example\n- url: examples/acceptance-criteria-management-scenario-example.json\n  type: Example\n- url: examples/acceptance-criteria-management-test-run-example.json\n  type: Example\n- type: Features\n  data:\n  - name: Gherkin Syntax Support\n    description: Structured Given/When/Then format for writing human-readable \n      acceptance criteria that can be directly executed as automated tests\n  - name: BDD Workflow Integration\n    description: Behavior-driven development workflows connecting acceptance \n      criteria to automated test suites via Cucumber, SpecFlow, or Behave\n  - name: Acceptance Criteria Checklists\n    description: Structured checklist format for breaking down complex \n      acceptance criteria into discrete, verifiable conditions\n  - name: Requirements Traceability\n    description: Linking acceptance criteria to user stories, epics, test cases,\n      and defects for end-to-end traceability\n  - name: Automated Acceptance Testing\n    description:\
  \ Executing acceptance criteria as automated test suites that \n      verify implementation correctness on each code change\n  - name: Stakeholder Collaboration\n    description: Shared definition of acceptance criteria between product \n      owners, developers, and QA engineers using accessible, plain-language \n      formats\n  - name: Definition of Done Integration\n    description: Incorporating acceptance criteria verification into team \n      Definition of Done checklists and sprint completion gates\n  - name: Test Coverage Reporting\n    description: Tracking which acceptance criteria have passing automated tests\n      and which remain untested or failing\n- type: UseCases\n  data:\n  - name: User Story Validation\n    description: Define measurable, testable conditions that must be satisfied \n      before a user story is accepted as complete\n  - name: Automated BDD Testing\n    description: Convert Gherkin-formatted acceptance criteria into executable \n      test scenarios\
  \ using Cucumber or SpecFlow\n  - name: Sprint Review Preparation\n    description: Use acceptance criteria as the basis for demonstrating \n      completed work to stakeholders during sprint reviews\n  - name: Regression Prevention\n    description: Maintain automated acceptance test suites that run on every \n      pull request to prevent regressions\n  - name: API Contract Verification\n    description: Use acceptance criteria to define and verify API behavior \n      contracts between producers and consumers\n  - name: Requirements Handoff\n    description: Communicate precise feature requirements from product managers \n      to engineers using structured acceptance criteria templates\n  - name: Quality Gate Enforcement\n    description: Block deployments or story completion when acceptance criteria \n      tests are failing in CI/CD pipelines\n- type: Integrations\n  data:\n  - name: Cucumber\n    description: Open-source BDD testing framework that executes \n      Gherkin-formatted\
  \ acceptance criteria as automated tests\n  - name: SpecFlow\n    description: BDD framework for .NET that maps Gherkin feature files to C# \n      step definitions for automated acceptance testing\n  - name: Behave\n    description: Python BDD testing library that runs Gherkin acceptance \n      criteria scenarios against Python application code\n  - name: Jira\n    description: Project management platform with dedicated Acceptance Criteria \n      field on user story issue types\n  - name: GitHub Issues\n    description: Issue tracking with Markdown checklist support for embedding \n      structured acceptance criteria on feature issues\n  - name: Azure DevOps Boards\n    description: Microsoft project management with Acceptance Criteria rich-text\n      field on User Story and Product Backlog Item work items\n  - name: TestRail\n    description: Test management platform for formalizing acceptance criteria as\n      structured test cases with expected outcomes\n  - name: Linear\n   \
  \ description: Modern issue tracker supporting Markdown acceptance criteria on\n      issues with checklist rendering\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/acceptance-criteria/refs/heads/main/apis.yml
tags:
- Agile
- Behavior Driven Development
- Gherkin
- Quality Assurance
- Requirements
- Testing
- User Stories
url: https://raw.githubusercontent.com/api-evangelist/acceptance-criteria/refs/heads/main/apis.yml
use_cases:
- description: Define measurable, testable conditions that must be satisfied before a user story is accepted as complete
  name: User Story Validation
- description: Convert Gherkin-formatted acceptance criteria into executable test scenarios using Cucumber or SpecFlow
  name: Automated BDD Testing
- description: Use acceptance criteria as the basis for demonstrating completed work to stakeholders during sprint reviews
  name: Sprint Review Preparation
- description: Maintain automated acceptance test suites that run on every pull request to prevent regressions
  name: Regression Prevention
- description: Use acceptance criteria to define and verify API behavior contracts between producers and consumers
  name: API Contract Verification
- description: Communicate precise feature requirements from product managers to engineers using structured acceptance criteria templates
  name: Requirements Handoff
- description: Block deployments or story completion when acceptance criteria tests are failing in CI/CD pipelines
  name: Quality Gate Enforcement
---
