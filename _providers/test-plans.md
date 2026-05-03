---
api_count: 5
api_specs:
- filename: swagger.v3.json
  format: json
  label: Jira Software API
  slug: ''
  spec_type: OpenAPI
  url: https://dac-static.atlassian.com/cloud/jira/software/swagger.v3.json
- filename: vsts-rest-api-specs
  format: yaml
  label: Azure DevOps Test Plans API
  slug: ''
  spec_type: OpenAPI
  url: https://github.com/MicrosoftDocs/vsts-rest-api-specs
apis:
- description: REST API for TestRail test management including test plans, test runs, milestones, and reporting, enabling structured test planning and execution tracking.
  name: TestRail API
  slug: ''
- description: REST API for Jira Software project management, supporting test plan tracking via epics, sprints, issues, and custom fields integrated with testing workflows.
  name: Jira Software API
  slug: ''
- description: REST API for Azure DevOps Test Plans service supporting test plan creation, test suites, test case management, test execution, and results reporting.
  name: Azure DevOps Test Plans API
  slug: ''
- description: REST API for qTest test management platform by Tricentis, supporting test plan management, test cycle creation, defect linking, and release-level test planning.
  name: qTest API
  slug: ''
- description: REST API for Micro Focus ALM Octane test planning and quality management, supporting test planning, defect management, and release quality tracking.
  name: ALM Octane API
  slug: ''
common:
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Test_plan
- title: ''
  type: Documentation
  url: https://www.guru99.com/what-is-test-plan-how-to-write-it.html
- title: ''
  type: JSONSchema
  url: json-schema/test-plans-test-plan-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/test-plans-test-cycle-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/test-plans-milestone-schema.json
- title: ''
  type: JSONLD
  url: json-ld/test-plans-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/test-plans-vocabulary.yml
created: '2025'
description: Structured documentation outlining test objectives, scope, approach, resources, schedule, and deliverables for software testing activities. Test plans define the overall strategy for testing a system or feature, specifying what will be tested, how it will be tested, who will test it, and what constitutes a pass or fail. They are critical for coordinating testing efforts across teams and ensuring comprehensive coverage.
features:
- description: Define what features, modules, and components are in scope for the testing effort.
  name: Scope Definition
- description: Assign testers, environments, and tools needed to execute the test plan.
  name: Resource Allocation
- description: Identify testing risks and mitigation strategies for high-risk areas.
  name: Risk Assessment
- description: Define testing timelines, milestones, and entry and exit criteria for test phases.
  name: Schedule Management
- description: Map test cases to requirements ensuring complete coverage of all specifications.
  name: Coverage Mapping
- description: Link test failures to defect tracking systems for resolution workflow management.
  name: Defect Tracking Integration
image: ''
integrations:
- description: Link test plans to Jira epics and sprints for agile testing coordination.
  name: Jira
- description: Publish test plans to Confluence for team visibility and stakeholder review.
  name: Confluence
- description: Trigger automated test execution from test plans via Jenkins pipeline integration.
  name: Jenkins
- description: Send test plan status updates and milestone notifications to Slack channels.
  name: Slack
jsonld:
- class_count: 3
  name: Test Plans Context
  property_count: 31
  slug: test-plans-context
layout: provider
modified: '2026-05-03'
name: Test Plans
skills: []
slug: test-plans
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Test Plans\ndescription: Structured documentation outlining test objectives, scope, approach, resources, schedule, and deliverables for software testing activities. Test plans define the overall strategy for testing a system or feature, specifying what will be tested, how it will be tested, who will test it, and what constitutes a pass or fail. They are critical for coordinating testing efforts across teams and ensuring comprehensive coverage.\nurl: https://en.wikipedia.org/wiki/Test_plan\ntags:\n  - Documentation\n  - Quality Assurance\n  - Software Development\n  - Test Management\n  - Testing\ncreated: '2025'\nmodified: '2026-05-03'\napis:\n  - name: TestRail API\n    description: REST API for TestRail test management including test plans, test runs, milestones, and reporting, enabling structured test planning and execution tracking.\n    humanURL: https://www.testrail.com\n    baseURL: https://yourproject.testrail.io/index.php?/api/v2\n    tags:\n      - Test Management\n\
  \      - Test Plans\n      - Test Runs\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://support.testrail.com/hc/en-us/articles/7077990413588-Introduction-to-the-API\n      - type: APIReference\n        url: https://support.testrail.com/hc/en-us/categories/7076832415124-API-Reference\n  - name: Jira Software API\n    description: REST API for Jira Software project management, supporting test plan tracking via epics, sprints, issues, and custom fields integrated with testing workflows.\n    humanURL: https://developer.atlassian.com/cloud/jira/software/rest/intro/\n    baseURL: https://your-org.atlassian.net/rest/agile/1.0\n    tags:\n      - Agile\n      - Jira\n      - Project Management\n      - Test Planning\n    properties:\n      - type: Documentation\n        url: https://developer.atlassian.com/cloud/jira/software/rest/intro/\n      - type: OpenAPI\n        url: https://dac-static.atlassian.com/cloud/jira/software/swagger.v3.json\n  - name: Azure\
  \ DevOps Test Plans API\n    description: REST API for Azure DevOps Test Plans service supporting test plan creation, test suites, test case management, test execution, and results reporting.\n    humanURL: https://learn.microsoft.com/en-us/rest/api/azure/devops/testplan/\n    baseURL: https://dev.azure.com/{organization}/{project}/_apis/testplan\n    tags:\n      - Azure DevOps\n      - CI/CD\n      - Microsoft\n      - Test Plans\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/azure/devops/testplan/\n      - type: OpenAPI\n        url: https://github.com/MicrosoftDocs/vsts-rest-api-specs\n  - name: qTest API\n    description: REST API for qTest test management platform by Tricentis, supporting test plan management, test cycle creation, defect linking, and release-level test planning.\n    humanURL: https://documentation.tricentis.com/qtestmanager/10.0/en/content/qtestmanager/api/intro.htm\n    baseURL: https://your-org.qtestnet.com/api/v3\n\
  \    tags:\n      - Agile Testing\n      - Test Management\n      - Test Plans\n      - Tricentis\n    properties:\n      - type: Documentation\n        url: https://documentation.tricentis.com/qtestmanager/10.0/en/content/qtestmanager/api/intro.htm\n      - type: APIReference\n        url: https://api.qasymphony.com/\n  - name: ALM Octane API\n    description: REST API for Micro Focus ALM Octane test planning and quality management, supporting test planning, defect management, and release quality tracking.\n    humanURL: https://admhelp.microfocus.com/octane/en/latest/Online/Content/API/REST_API.htm\n    baseURL: https://your-octane.example.com/api/shared_spaces\n    tags:\n      - ALM\n      - Enterprise Testing\n      - Quality Management\n      - Test Plans\n    properties:\n      - type: Documentation\n        url: https://admhelp.microfocus.com/octane/en/latest/Online/Content/API/REST_API.htm\ncommon:\n  - type: Documentation\n    url: https://en.wikipedia.org/wiki/Test_plan\n  -\
  \ type: Documentation\n    url: https://www.guru99.com/what-is-test-plan-how-to-write-it.html\n  - type: Features\n    data:\n      - name: Scope Definition\n        description: Define what features, modules, and components are in scope for the testing effort.\n      - name: Resource Allocation\n        description: Assign testers, environments, and tools needed to execute the test plan.\n      - name: Risk Assessment\n        description: Identify testing risks and mitigation strategies for high-risk areas.\n      - name: Schedule Management\n        description: Define testing timelines, milestones, and entry and exit criteria for test phases.\n      - name: Coverage Mapping\n        description: Map test cases to requirements ensuring complete coverage of all specifications.\n      - name: Defect Tracking Integration\n        description: Link test failures to defect tracking systems for resolution workflow management.\n  - type: UseCases\n    data:\n      - name: Release Test Planning\n\
  \        description: Create a comprehensive test plan for each release cycle defining scope and success criteria.\n      - name: Sprint Test Planning\n        description: Plan testing activities within agile sprints aligned to user stories and acceptance criteria.\n      - name: Regulatory Compliance Testing\n        description: Use test plans to document testing required for regulatory and compliance certifications.\n      - name: Performance Test Planning\n        description: Plan load, stress, and performance test scenarios with target metrics and thresholds.\n      - name: UAT Coordination\n        description: Coordinate user acceptance testing with business stakeholders through structured test plans.\n  - type: Integrations\n    data:\n      - name: Jira\n        description: Link test plans to Jira epics and sprints for agile testing coordination.\n      - name: Confluence\n        description: Publish test plans to Confluence for team visibility and stakeholder review.\n  \
  \    - name: Jenkins\n        description: Trigger automated test execution from test plans via Jenkins pipeline integration.\n      - name: Slack\n        description: Send test plan status updates and milestone notifications to Slack channels.\n  - type: JSONSchema\n    url: json-schema/test-plans-test-plan-schema.json\n  - type: JSONSchema\n    url: json-schema/test-plans-test-cycle-schema.json\n  - type: JSONSchema\n    url: json-schema/test-plans-milestone-schema.json\n  - type: JSONLD\n    url: json-ld/test-plans-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/test-plans-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/test-plans/refs/heads/main/apis.yml
tags:
- Documentation
- Quality Assurance
- Software Development
- Test Management
- Testing
url: https://en.wikipedia.org/wiki/Test_plan
use_cases:
- description: Create a comprehensive test plan for each release cycle defining scope and success criteria.
  name: Release Test Planning
- description: Plan testing activities within agile sprints aligned to user stories and acceptance criteria.
  name: Sprint Test Planning
- description: Use test plans to document testing required for regulatory and compliance certifications.
  name: Regulatory Compliance Testing
- description: Plan load, stress, and performance test scenarios with target metrics and thresholds.
  name: Performance Test Planning
- description: Coordinate user acceptance testing with business stakeholders through structured test plans.
  name: UAT Coordination
---
