---
api_count: 6
api_specs:
- filename: api.github.com.json
  format: json
  label: Source Control APIs
  slug: source-control
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json
apis:
- description: APIs and tools for capturing, tracking, and managing software requirements throughout the development life cycle, including user stories, acceptance criteria, and traceability matrices.
  name: Requirements Management APIs
  slug: requirements-management
- description: APIs for version control systems that manage code repositories, branches, commits, pull requests, and code reviews as part of the software development life cycle.
  name: Source Control APIs
  slug: source-control
- description: APIs for CI/CD pipelines that automate the building, testing, and deployment of software changes, enabling frequent and reliable releases throughout the development life cycle.
  name: Continuous Integration and Delivery APIs
  slug: ci-cd
- description: APIs for automated testing frameworks and quality assurance platforms that support unit testing, integration testing, performance testing, and security testing throughout the SDLC.
  name: Testing and Quality Assurance APIs
  slug: testing-automation
- description: APIs for project management and collaboration tools that track work items, sprints, milestones, and team velocity throughout the software development life cycle.
  name: Project Management APIs
  slug: project-management
- description: APIs for managing software releases, deployments, and change management processes, ensuring controlled and auditable rollouts to production environments.
  name: Release Management APIs
  slug: release-management
common:
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Software_development_life_cycle
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Agile_software_development
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/DevOps
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Scrum_(software_development)
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Kanban_(development)
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Test-driven_development
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Continuous_integration
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Continuous_delivery
created: '2025-01-01'
description: The Software Development Life Cycle (SDLC) is a structured framework that defines the process for planning, creating, testing, and deploying high-quality software systems. It encompasses distinct phases including requirements analysis, system design, implementation, testing, deployment, and ongoing maintenance. Tools and platforms that support SDLC workflows provide capabilities for project management, source control, continuous integration and delivery, testing automation, release management, and collaboration across development teams.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 34
  name: Software Development Life Cycle Context
  property_count: 6
  slug: software-development-life-cycle-context
layout: provider
modified: '2026-05-02'
name: Software Development Life Cycle
skills: []
slug: software-development-life-cycle
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: software-development-life-cycle\nname: Software Development Life Cycle\ndescription: >-\n  The Software Development Life Cycle (SDLC) is a structured framework that\n  defines the process for planning, creating, testing, and deploying high-quality\n  software systems. It encompasses distinct phases including requirements analysis,\n  system design, implementation, testing, deployment, and ongoing maintenance.\n  Tools and platforms that support SDLC workflows provide capabilities for project\n  management, source control, continuous integration and delivery, testing automation,\n  release management, and collaboration across development teams.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Development Process\n  - Project Management\n  - SDLC\n  - Software Engineering\n  - DevOps\n  - CI/CD\nurl: https://raw.githubusercontent.com/api-evangelist/software-development-life-cycle/refs/heads/main/apis.yml\ncreated:\
  \ '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: software-development-life-cycle:requirements-management\n    name: Requirements Management APIs\n    description: >-\n      APIs and tools for capturing, tracking, and managing software requirements\n      throughout the development life cycle, including user stories, acceptance\n      criteria, and traceability matrices.\n    humanURL: https://en.wikipedia.org/wiki/Requirements_management\n    baseURL: https://en.wikipedia.org/wiki/Requirements_management\n    tags:\n      - Requirements\n      - User Stories\n      - Backlog\n      - Agile\n    properties:\n      - type: Documentation\n        url: https://en.wikipedia.org/wiki/Requirements_management\n  - aid: software-development-life-cycle:source-control\n    name: Source Control APIs\n    description: >-\n      APIs for version control systems that manage code repositories, branches,\n      commits, pull requests, and code reviews as part of the\
  \ software development\n      life cycle.\n    humanURL: https://en.wikipedia.org/wiki/Version_control\n    baseURL: https://api.github.com\n    tags:\n      - Source Control\n      - Version Control\n      - Git\n      - Repositories\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/rest\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.json\n  - aid: software-development-life-cycle:ci-cd\n    name: Continuous Integration and Delivery APIs\n    description: >-\n      APIs for CI/CD pipelines that automate the building, testing, and deployment\n      of software changes, enabling frequent and reliable releases throughout the\n      development life cycle.\n    humanURL: https://en.wikipedia.org/wiki/CI/CD\n    baseURL: https://en.wikipedia.org/wiki/CI/CD\n    tags:\n      - CI/CD\n      - Continuous Integration\n      - Continuous Delivery\n      - Pipelines\n\
  \      - Automation\n    properties:\n      - type: Documentation\n        url: https://en.wikipedia.org/wiki/CI/CD\n  - aid: software-development-life-cycle:testing-automation\n    name: Testing and Quality Assurance APIs\n    description: >-\n      APIs for automated testing frameworks and quality assurance platforms that\n      support unit testing, integration testing, performance testing, and security\n      testing throughout the SDLC.\n    humanURL: https://en.wikipedia.org/wiki/Test_automation\n    baseURL: https://en.wikipedia.org/wiki/Test_automation\n    tags:\n      - Testing\n      - Quality Assurance\n      - Test Automation\n      - Security Testing\n    properties:\n      - type: Documentation\n        url: https://en.wikipedia.org/wiki/Test_automation\n  - aid: software-development-life-cycle:project-management\n    name: Project Management APIs\n    description: >-\n      APIs for project management and collaboration tools that track work items,\n      sprints, milestones,\
  \ and team velocity throughout the software development\n      life cycle.\n    humanURL: https://en.wikipedia.org/wiki/Software_project_management\n    baseURL: https://en.wikipedia.org/wiki/Software_project_management\n    tags:\n      - Project Management\n      - Agile\n      - Scrum\n      - Kanban\n      - Sprint Planning\n    properties:\n      - type: Documentation\n        url: https://en.wikipedia.org/wiki/Software_project_management\n  - aid: software-development-life-cycle:release-management\n    name: Release Management APIs\n    description: >-\n      APIs for managing software releases, deployments, and change management\n      processes, ensuring controlled and auditable rollouts to production\n      environments.\n    humanURL: https://en.wikipedia.org/wiki/Software_release_life_cycle\n    baseURL: https://en.wikipedia.org/wiki/Software_release_life_cycle\n    tags:\n      - Release Management\n      - Deployment\n      - Change Management\n      - Versioning\n    properties:\n\
  \      - type: Documentation\n        url: https://en.wikipedia.org/wiki/Software_release_life_cycle\ncommon:\n  - url: https://en.wikipedia.org/wiki/Software_development_life_cycle\n    name: SDLC Wikipedia Article\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/Agile_software_development\n    name: Agile Software Development\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/DevOps\n    name: DevOps\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/Scrum_(software_development)\n    name: Scrum Methodology\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/Kanban_(development)\n    name: Kanban Development\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/Test-driven_development\n    name: Test-Driven Development\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/Continuous_integration\n    name: Continuous Integration\n    type: Documentation\n  - url: https://en.wikipedia.org/wiki/Continuous_delivery\n\
  \    name: Continuous Delivery\n    type: Documentation\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/software-development-life-cycle/refs/heads/main/apis.yml
tags:
- Development Process
- Project Management
- SDLC
- Software Engineering
- DevOps
- CI/CD
url: https://raw.githubusercontent.com/api-evangelist/software-development-life-cycle/refs/heads/main/apis.yml
use_cases: []
---
