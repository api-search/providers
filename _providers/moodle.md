---
api_count: 12
apis:
- description: Exposes Moodle functionality as web services so external programs can integrate with a Moodle site for users, courses, enrollments, grading, and other operations. Supports REST, XML-RPC, and SOAP prot
  name: Moodle Web Services API
  slug: web-services
- description: Allows developers to expose parametrized functions to external systems, forming the basis of Moodle's web services and powering integrations consumed via REST, SOAP, and XML-RPC.
  name: Moodle External Functions API
  slug: external-functions
- description: Provides functions to determine what the current user is allowed to do, checking roles, capabilities, and permissions across system, course, and activity contexts.
  name: Moodle Access API
  slug: access
- description: An extension of the Access API that defines the set of actions a user is allowed to perform on certain system levels through assignable roles and capabilities.
  name: Moodle Roles API
  slug: roles
- description: Enables safe, consistent database read and write operations across Moodle, abstracting the underlying database driver and providing helpers for common query patterns.
  name: Moodle Data Manipulation API (DML)
  slug: dml
- description: Manages file storage across plugins, providing a unified interface for uploading, retrieving, and serving files associated with users, courses, and activities.
  name: Moodle File API
  slug: file
- description: Defines and processes user data submitted through web forms, including validation, rendering, and persistence.
  name: Moodle Form API
  slug: form
- description: Defines event handlers for inter-plugin communication and logging, enabling decoupled, observer-style integrations across Moodle.
  name: Moodle Events API
  slug: events
- description: Enables indirect communication between core and plugins through well-defined extension points, allowing plugins to react to and modify core behavior.
  name: Moodle Hooks API
  slug: hooks
- description: Describes stored personal data and supports discovery, export, and deletion of user data across plugins for GDPR and similar privacy compliance.
  name: Moodle Privacy API
  slug: privacy
- description: Executes background jobs on a schedule or as one-off operations, allowing plugins to defer long-running work to cron processing.
  name: Moodle Task API
  slug: task
- description: Manages payment processing in Moodle, providing pluggable payment gateways for paid enrollments and other monetized features.
  name: Moodle Payment API
  slug: payment
common:
- title: ''
  type: Portal
  url: https://moodledev.io
- title: ''
  type: Documentation
  url: https://moodledev.io/docs/apis
- title: ''
  type: Website
  url: https://moodle.org
- title: ''
  type: Blog
  url: https://moodle.com/news/
created: '2025-01-08'
description: Moodle is the world's open source learning platform, used by educators and organizations to deliver online courses and learning experiences. The Moodle developer platform exposes a broad set of internal APIs for plugin and core development, plus a Web Services API that enables external systems to integrate with Moodle for users, courses, enrollments, grading, and more.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Moodle
skills: []
slug: moodle
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: moodle\nspecificationVersion: '0.19'\nname: Moodle\ndescription: >-\n  Moodle is the world's open source learning platform, used by educators and\n  organizations to deliver online courses and learning experiences. The Moodle\n  developer platform exposes a broad set of internal APIs for plugin and core\n  development, plus a Web Services API that enables external systems to\n  integrate with Moodle for users, courses, enrollments, grading, and more.\ntype: Index\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/moodle/refs/heads/main/apis.yml\ncreated: '2025-01-08'\nmodified: '2026-04-28'\ntags:\n  - E-Learning\n  - EdTech\n  - LMS\n  - Moodle\n  - Open Source\n  - Web Services\napis:\n  - aid: moodle:web-services\n    name: Moodle Web Services API\n    description: >-\n      Exposes Moodle functionality as web services so external programs can\n\
  \      integrate with a Moodle site for users, courses, enrollments, grading,\n      and other operations. Supports REST, XML-RPC, and SOAP protocols with\n      token-based authentication.\n    humanURL: https://moodledev.io/docs/apis/subsystems/external/\n    tags:\n      - External\n      - Integration\n      - REST\n      - SOAP\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://moodledev.io/docs/apis/subsystems/external/\n  - aid: moodle:external-functions\n    name: Moodle External Functions API\n    description: >-\n      Allows developers to expose parametrized functions to external systems,\n      forming the basis of Moodle's web services and powering integrations\n      consumed via REST, SOAP, and XML-RPC.\n    humanURL: https://moodledev.io/docs/apis/subsystems/external/functions\n    tags:\n      - External\n      - Functions\n      - Integration\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://moodledev.io/docs/apis/subsystems/external/functions\n\
  \  - aid: moodle:access\n    name: Moodle Access API\n    description: >-\n      Provides functions to determine what the current user is allowed to do,\n      checking roles, capabilities, and permissions across system, course, and\n      activity contexts.\n    humanURL: https://moodledev.io/docs/apis/subsystems/access\n    tags:\n      - Access\n      - Authorization\n      - Permissions\n      - Roles\n    properties:\n      - type: Documentation\n        url: https://moodledev.io/docs/apis/subsystems/access\n  - aid: moodle:roles\n    name: Moodle Roles API\n    description: >-\n      An extension of the Access API that defines the set of actions a user is\n      allowed to perform on certain system levels through assignable roles and\n      capabilities.\n    humanURL: https://moodledev.io/docs/apis/subsystems/access/roles\n    tags:\n      - Access\n      - Capabilities\n      - Permissions\n      - Roles\n    properties:\n      - type: Documentation\n        url: https://moodledev.io/docs/apis/subsystems/access/roles\n\
  \  - aid: moodle:dml\n    name: Moodle Data Manipulation API (DML)\n    description: >-\n      Enables safe, consistent database read and write operations across\n      Moodle, abstracting the underlying database driver and providing helpers\n      for common query patterns.\n    humanURL: https://moodledev.io/docs/apis/core/dml\n    tags:\n      - Database\n      - DML\n      - Persistence\n    properties:\n      - type: Documentation\n        url: https://moodledev.io/docs/apis/core/dml\n  - aid: moodle:file\n    name: Moodle File API\n    description: >-\n      Manages file storage across plugins, providing a unified interface for\n      uploading, retrieving, and serving files associated with users, courses,\n      and activities.\n    humanURL: https://moodledev.io/docs/apis/subsystems/files\n    tags:\n      - Files\n      - Storage\n      - Uploads\n    properties:\n      - type: Documentation\n        url: https://moodledev.io/docs/apis/subsystems/files\n  - aid: moodle:form\n\
  \    name: Moodle Form API\n    description: >-\n      Defines and processes user data submitted through web forms, including\n      validation, rendering, and persistence.\n    humanURL: https://moodledev.io/docs/apis/subsystems/form\n    tags:\n      - Forms\n      - UI\n      - Validation\n    properties:\n      - type: Documentation\n        url: https://moodledev.io/docs/apis/subsystems/form\n  - aid: moodle:events\n    name: Moodle Events API\n    description: >-\n      Defines event handlers for inter-plugin communication and logging,\n      enabling decoupled, observer-style integrations across Moodle.\n    humanURL: https://moodledev.io/docs/apis/core/event\n    tags:\n      - Events\n      - Logging\n      - Observers\n    properties:\n      - type: Documentation\n        url: https://moodledev.io/docs/apis/core/event\n  - aid: moodle:hooks\n    name: Moodle Hooks API\n    description: >-\n      Enables indirect communication between core and plugins through\n      well-defined\
  \ extension points, allowing plugins to react to and modify\n      core behavior.\n    humanURL: https://moodledev.io/docs/apis/core/hooks\n    tags:\n      - Extensibility\n      - Hooks\n      - Plugins\n    properties:\n      - type: Documentation\n        url: https://moodledev.io/docs/apis/core/hooks\n  - aid: moodle:privacy\n    name: Moodle Privacy API\n    description: >-\n      Describes stored personal data and supports discovery, export, and\n      deletion of user data across plugins for GDPR and similar privacy\n      compliance.\n    humanURL: https://moodledev.io/docs/apis/subsystems/privacy\n    tags:\n      - Compliance\n      - GDPR\n      - Privacy\n    properties:\n      - type: Documentation\n        url: https://moodledev.io/docs/apis/subsystems/privacy\n  - aid: moodle:task\n    name: Moodle Task API\n    description: >-\n      Executes background jobs on a schedule or as one-off operations, allowing\n      plugins to defer long-running work to cron processing.\n\
  \    humanURL: https://moodledev.io/docs/apis/subsystems/task\n    tags:\n      - Background Jobs\n      - Cron\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://moodledev.io/docs/apis/subsystems/task\n  - aid: moodle:payment\n    name: Moodle Payment API\n    description: >-\n      Manages payment processing in Moodle, providing pluggable payment\n      gateways for paid enrollments and other monetized features.\n    humanURL: https://moodledev.io/docs/apis/subsystems/payment\n    tags:\n      - Enrollment\n      - Gateways\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://moodledev.io/docs/apis/subsystems/payment\ncommon:\n  - type: Portal\n    url: https://moodledev.io\n  - type: Documentation\n    url: https://moodledev.io/docs/apis\n  - type: Website\n    url: https://moodle.org\n  - type: Blog\n    url: https://moodle.com/news/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/moodle/refs/heads/main/apis.yml
tags:
- E-Learning
- EdTech
- LMS
- Moodle
- Open Source
- Web Services
url: https://raw.githubusercontent.com/api-evangelist/moodle/refs/heads/main/apis.yml
use_cases: []
---
