---
api_count: 3
apis:
- description: The Canvas LMS REST API provides programmatic access to courses, assignments, quizzes, grades, users, enrollments, accounts, discussions, files, modules, rubrics, submissions, SIS imports, and account
  name: Canvas LMS REST API
  slug: canvas-lms-rest-api
- description: The Canvas LMS GraphQL API is an alternative to the REST API that lets clients request exactly the fields they need across Canvas resources in a single request. It is well suited for dashboards and ag
  name: Canvas LMS GraphQL API
  slug: canvas-lms-graphql-api
- description: Canvas supports Learning Tools Interoperability (LTI 1.1 and LTI 1.3 / Advantage) for embedding external tools, assignments, and content into courses with deep linking, grade passback, and names-and-r
  name: Canvas LTI Integrations
  slug: canvas-lti-integrations
common:
- title: ''
  type: Website
  url: https://www.instructure.com/canvas
- title: ''
  type: Documentation
  url: https://canvas.instructure.com/doc/api/
- title: ''
  type: GitHub Organization
  url: https://github.com/instructure
- title: ''
  type: GitHub Repository
  url: https://github.com/instructure/canvas-lms
- title: ''
  type: Status
  url: https://status.instructure.com/
- title: ''
  type: Community
  url: https://community.canvaslms.com/
- title: ''
  type: Privacy Policy
  url: https://www.instructure.com/policies/privacy
- title: ''
  type: Terms of Service
  url: https://www.instructure.com/policies/product-acceptable-use
created: '2025-01-14'
description: Canvas is Instructure's open-source learning management system (LMS) used by K-12, higher education, and corporate training organizations to deliver courses, assessments, and learner communication. Canvas exposes a comprehensive REST API and a GraphQL endpoint for reading and modifying courses, assignments, quizzes, grades, users, enrollments, content, and account administration, and it integrates with external tools through LTI, Caliper, and live event streams.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Canvas
skills: []
slug: canvas
solutions: []
source_yaml: "aid: canvas\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/canvas/refs/heads/main/apis.yml\nname: Canvas\ndescription: >-\n  Canvas is Instructure's open-source learning management system (LMS)\n  used by K-12, higher education, and corporate training organizations\n  to deliver courses, assessments, and learner communication. Canvas\n  exposes a comprehensive REST API and a GraphQL endpoint for reading\n  and modifying courses, assignments, quizzes, grades, users,\n  enrollments, content, and account administration, and it integrates\n  with external tools through LTI, Caliper, and live event streams.\ntype: Index\nx-type: company\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Education\n  - EdTech\n  - GraphQL\n  - Learning Management System\n  - LMS\n  - LTI\n  - Open Source\n  - REST\ncreated: '2025-01-14'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  -\
  \ aid: canvas:canvas-lms-rest-api\n    name: Canvas LMS REST API\n    description: >-\n      The Canvas LMS REST API provides programmatic access to courses,\n      assignments, quizzes, grades, users, enrollments, accounts,\n      discussions, files, modules, rubrics, submissions, SIS imports,\n      and account administration. It uses OAuth 2.0 access tokens and\n      returns JSON with ISO 8601 timestamps, supporting pagination,\n      request throttling, masquerading, and compound documents.\n    humanURL: https://canvas.instructure.com/doc/api/\n    tags:\n      - Education\n      - LMS\n      - REST\n    properties:\n      - type: Documentation\n        url: https://canvas.instructure.com/doc/api/\n      - type: Authentication\n        url: https://canvas.instructure.com/doc/api/file.oauth.html\n      - type: Pagination\n        url: https://canvas.instructure.com/doc/api/file.pagination.html\n      - type: GitHub Repository\n        url: https://github.com/instructure/canvas-lms\n\
  \    x-features:\n      - OAuth 2.0 authentication with access tokens\n      - JSON responses with ISO 8601 timestamps\n      - 64-bit integer IDs and string ID support\n      - Form-encoded and JSON request bodies\n      - Pagination for large result sets\n      - Request throttling and quota controls\n      - Masquerading for acting on behalf of users\n      - Compound documents for linked resources\n      - File upload workflows\n      - SIS imports and roster sync\n      - Live event streams via Canvas Data services\n      - Caliper event format compatibility\n      - xAPI statement support\n    x-use-cases:\n      - Building custom student dashboards or mobile apps\n      - Automating course provisioning and enrollment via SIS imports\n      - Syncing grades and assignments to external gradebooks\n      - Analytics and learning-event data pipelines\n      - Integrating third-party tools through LTI\n      - Bulk content migration between courses or institutions\n      - Institutional\
  \ reporting and audit-log extraction\n  - aid: canvas:canvas-lms-graphql-api\n    name: Canvas LMS GraphQL API\n    description: >-\n      The Canvas LMS GraphQL API is an alternative to the REST API\n      that lets clients request exactly the fields they need across\n      Canvas resources in a single request. It is well suited for\n      dashboards and aggregated views that otherwise require many\n      REST round-trips.\n    humanURL: https://canvas.instructure.com/doc/api/file.graphql.html\n    tags:\n      - Education\n      - GraphQL\n      - LMS\n    properties:\n      - type: Documentation\n        url: https://canvas.instructure.com/doc/api/file.graphql.html\n    x-features:\n      - Typed GraphQL schema over Canvas resources\n      - Single-request fetches across courses, users, and assignments\n      - Reduced over-fetching for dashboards\n      - OAuth 2.0 bearer-token authentication\n    x-use-cases:\n      - Building performant student or instructor dashboards\n      - Aggregating\
  \ course, assignment, and grade data in one request\n      - Mobile apps with limited bandwidth\n  - aid: canvas:canvas-lti-integrations\n    name: Canvas LTI Integrations\n    description: >-\n      Canvas supports Learning Tools Interoperability (LTI 1.1 and\n      LTI 1.3 / Advantage) for embedding external tools, assignments,\n      and content into courses with deep linking, grade passback, and\n      names-and-roles service.\n    humanURL: https://canvas.instructure.com/doc/api/file.tools_intro.html\n    tags:\n      - Education\n      - LMS\n      - LTI\n    properties:\n      - type: Documentation\n        url: https://canvas.instructure.com/doc/api/file.tools_intro.html\n    x-features:\n      - LTI 1.1 and LTI 1.3 / Advantage support\n      - Deep linking for tool placements\n      - Assignment and Grade Services (AGS) for grade passback\n      - Names and Roles Provisioning Service (NRPS)\n      - Configurable tool placements across Canvas UI\n    x-use-cases:\n      - Embedding\
  \ third-party learning tools in Canvas courses\n      - Passing grades from external graders back to Canvas\n      - Provisioning course rosters into external tools\ncommon:\n  - type: Website\n    url: https://www.instructure.com/canvas\n  - type: Documentation\n    url: https://canvas.instructure.com/doc/api/\n  - type: GitHub Organization\n    url: https://github.com/instructure\n  - type: GitHub Repository\n    url: https://github.com/instructure/canvas-lms\n  - type: Status\n    url: https://status.instructure.com/\n  - type: Community\n    url: https://community.canvaslms.com/\n  - type: Privacy Policy\n    url: https://www.instructure.com/policies/privacy\n  - type: Terms of Service\n    url: https://www.instructure.com/policies/product-acceptable-use\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/canvas/refs/heads/main/apis.yml
tags:
- Education
- EdTech
- GraphQL
- Learning Management System
- LMS
- LTI
- Open Source
- REST
url: https://raw.githubusercontent.com/api-evangelist/canvas/refs/heads/main/apis.yml
use_cases: []
---
