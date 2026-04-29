---
api_count: 5
apis:
- description: Learning Management System API for managing courses, learners, and learning content.
  name: Adobe Captivate Prime API
  slug: ''
- description: API for SCORM-compliant content delivery and tracking.
  name: Adobe Captivate SCORM API
  slug: ''
- description: Experience API for tracking learning experiences.
  name: Adobe Captivate xAPI (Tin Can API)
  slug: ''
- description: API for collaborative review and commenting on eLearning projects.
  name: Adobe Captivate Review API
  slug: ''
- description: Webhooks API for Adobe Learning Manager that enables real-time event notifications for learner activities, course completions, enrollments, and other learning management events.
  name: Adobe Learning Manager Webhooks API
  slug: ''
asyncapis:
- description: The Adobe Learning Manager Webhooks API enables real-time event notifications for learning management activities. When configured, Adobe Learning Manager sends HTTP POST requests to registered webhook
  name: Adobe Learning Manager Webhooks API
  slug: adobe-captivate-learning-manager-webhooks-asyncapi
capabilities:
- description: Unified workflow capability for managing learning objects, enrollments, completions, and compliance tracking using Adobe Learning Manager APIs. Designed for L&D administrators and HR integration devel
  name: Adobe Captivate Learning Management
  slug: learning-management
common:
- title: ''
  type: Support
  url: https://helpx.adobe.com/support/captivate.html
- title: ''
  type: Community
  url: https://community.adobe.com/t5/adobe-captivate/ct-p/ct-captivate
- title: ''
  type: Blog
  url: https://elearning.adobe.com/
- title: ''
  type: StatusPage
  url: https://status.adobe.com/
- title: ''
  type: TermsOfService
  url: https://www.adobe.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.adobe.com/privacy.html
- title: ''
  type: Contact
  url: https://www.adobe.com/products/captivate/contact.html
- title: ''
  type: Portal
  url: https://experienceleague.adobe.com/docs/learning-manager/using/introduction.html
- title: ''
  type: GettingStarted
  url: https://experienceleague.adobe.com/docs/learning-manager/using/getting-started/getting-started.html
- title: ''
  type: Documentation
  url: https://experienceleague.adobe.com/docs/learning-manager/using/home.html
- title: ''
  type: Console
  url: https://developer.adobe.com/console/
- title: ''
  type: ChangeLog
  url: https://experienceleague.adobe.com/docs/learning-manager/using/whats-new.html
- title: ''
  type: Website
  url: https://business.adobe.com/products/learning-manager/adobe-learning-manager.html
- title: ''
  type: Login
  url: https://learningmanager.adobe.com/
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AdobeELearning
- title: ''
  type: GitHubOrganization
  url: https://github.com/adobe
- title: ''
  type: JSONSchema
  url: json-schema/adobe-captivate-learning-object-schema.json
- title: ''
  type: JSON-LD
  url: json-ld/adobe-captivate-context.jsonld
- title: ''
  type: SpectralRules
  url: rules/adobe-captivate-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/learning-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/adobe-captivate-vocabulary.yaml
- title: ''
  type: JSON-LD
  url: json-ld/adobe-captivate-learning-manager-webhooks-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/adobe-captivate-prime-api-context.jsonld
created: '2024-01-20'
description: Adobe Captivate is an eLearning authoring tool used to create responsive eLearning content, software demonstrations, and interactive training modules.
features:
- description: Create and manage courses, learning programs, certifications, and job aids with full CRUD operations via REST API.
  name: Learning Object Management
- description: Programmatically enroll learners, track progress, and retrieve completion status across all learning objects.
  name: Learner Enrollment and Tracking
- description: Receive real-time HTTP POST notifications for enrollment, completion, badge, and certification events.
  name: Webhook Event Notifications
- description: Manage gamification points, leaderboards, and badge awards to motivate learners.
  name: Gamification and Badges
- description: Organize and expose learning content through catalogs with filtering and tagging capabilities.
  name: Catalog Management
- description: Associate skills with learning content and track learner skill attainment through the API.
  name: Skill Tracking
- description: Secure API access using OAuth 2.0 with role-based scopes for admin, learner, manager, and author roles.
  name: OAuth 2.0 Authentication
- description: Deliver and track SCORM-compliant and xAPI (Tin Can) learning content for LMS interoperability.
  name: SCORM and xAPI Support
- description: Use the Jobs API to import and export users, enrollments, and completion data in bulk.
  name: Bulk Data Import/Export
- description: Manage announcements and notifications sent to learners, managers, and administrators.
  name: Notification Management
image: /assets/icons/adobe-captivate.png
integrations:
- description: Sync learner data and completion status between Adobe Learning Manager and Salesforce CRM.
  name: Salesforce
- description: Surface learning content and notifications directly within Microsoft Teams via connector.
  name: Microsoft Teams
- description: Import organizational user data from Workday HCM to manage learner accounts automatically.
  name: Workday
- description: Bi-directional sync with SAP SuccessFactors for user provisioning and learning record exchange.
  name: SAP SuccessFactors
- description: Embed learning content and catalogs within Adobe Experience Manager sites.
  name: Adobe Experience Manager
- description: Schedule and launch virtual classroom sessions directly from Adobe Learning Manager.
  name: Zoom
- description: Import LinkedIn Learning content into Adobe Learning Manager catalogs for blended learning.
  name: LinkedIn Learning
- description: Host and launch SCORM content packages through SCORM Cloud integration.
  name: SCORM Cloud
jsonld:
- class_count: 0
  name: Adobe Captivate Context
  property_count: 16
  slug: adobe-captivate-context
- class_count: 5
  name: Adobe Captivate Learning Manager Webhooks Context
  property_count: 9
  slug: adobe-captivate-learning-manager-webhooks-context
- class_count: 45
  name: Adobe Captivate Prime Api Context
  property_count: 80
  slug: adobe-captivate-prime-api-context
layout: provider
modified: '2026-04-19'
name: Adobe Captivate
rules:
- name: Adobe Captivate API Rules
  rule_count: 34
  severity_counts:
    error: 16
    hint: 0
    info: 4
    warn: 14
  slug: adobe-captivate-spectral-rules
skills: []
slug: adobe-captivate
solutions: []
source_yaml: "aid: adobe-captivate\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/apis.yml\nname: Adobe Captivate\ndescription: Adobe Captivate is an eLearning authoring tool used to create responsive eLearning content, software demonstrations, and interactive training modules.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\ncreated: '2024-01-20'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n- Authoring\n- Education\n- eLearning\n- LMS\n- SCORM\n- Training\n- xAPI\napis:\n- name: Adobe Captivate Prime API\n  description: >-\n    Learning Management System API for managing courses, learners, and learning\n    content.\n  image: https://www.adobe.com/content/dam/cc/icons/captivate-prime.svg\n  humanURL: https://www.adobe.com/products/captivateprime.html\n  baseURL: https://learningmanager.adobe.com/primeapi/v2\n  tags:\n  - Courses\n  - Learners\n  - Learning Management\n  - LMS\n\
  \  properties:\n  - type: Documentation\n    url: https://captivateprime.adobe.com/docs/primeapi/v2/\n  - type: OpenAPI\n    url: https://learningmanager.adobe.com/primeapi/v2/swagger.json\n  - type: OpenAPI\n    url: openapi/adobe-captivate-prime-api-openapi.yml\n  - type: Authentication\n    url: https://captivateprime.adobe.com/docs/primeapi/v2/#authentication\n  - type: Postman Collection\n    url: https://www.postman.com/adobe-captivate-prime\n  - type: JSONSchema\n    url: json-schema/prime-api-account-response-schema.json\n  - type: JSONSchema\n    url: json-schema/prime-api-account-schema.json\n  - type: JSONSchema\n    url: json-schema/prime-api-badge-list-response-schema.json\n  - type: JSONStructure\n    url: json-structure/prime-api-account-response-structure.json\n  - type: JSONStructure\n    url: json-structure/prime-api-account-structure.json\n  - type: JSONStructure\n    url: json-structure/prime-api-badge-list-response-structure.json\n- name: Adobe Captivate SCORM API\n\
  \  description: >-\n    API for SCORM-compliant content delivery and tracking.\n  humanURL: https://helpx.adobe.com/captivate/using/publish-projects-scorm-compliant-lms.html\n  tags:\n  - Content Delivery\n  - LMS Integration\n  - SCORM\n  properties:\n  - type: Documentation\n    url: https://scorm.com/scorm-explained/technical-scorm/\n  - type: Specification\n    url: https://adlnet.gov/projects/scorm/\n- name: Adobe Captivate xAPI (Tin Can API)\n  description: >-\n    Experience API for tracking learning experiences.\n  humanURL: https://helpx.adobe.com/captivate/using/xapi-tin-can-support.html\n  tags:\n  - Learning Analytics\n  - Tin Can\n  - xAPI\n  properties:\n  - type: Documentation\n    url: https://xapi.com/overview/\n  - type: Specification\n    url: https://github.com/adlnet/xAPI-Spec\n- name: Adobe Captivate Review API\n  description: >-\n    API for collaborative review and commenting on eLearning projects.\n  humanURL: https://helpx.adobe.com/captivate/using/shared-review.html\n\
  \  tags:\n  - Collaboration\n  - Comments\n  - Review\n  properties:\n  - type: Documentation\n    url: https://helpx.adobe.com/captivate/using/shared-review.html\n- name: Adobe Learning Manager Webhooks API\n  description: >-\n    Webhooks API for Adobe Learning Manager that enables real-time event\n    notifications for learner activities, course completions, enrollments,\n    and other learning management events.\n  humanURL: https://experienceleague.adobe.com/docs/learning-manager/using/integration/feature-summary/webhooks.html\n  tags:\n  - Events\n  - Learning Management\n  - Notifications\n  - Webhooks\n  properties:\n  - type: Documentation\n    url: https://experienceleague.adobe.com/docs/learning-manager/using/integration/feature-summary/webhooks.html\n  - type: AsyncAPI\n    url: asyncapi/adobe-captivate-learning-manager-webhooks-asyncapi.yml\n  - type: JSONSchema\n    url: json-schema/learning-manager-webhooks-badge-awarded-payload-schema.json\n  - type: JSONSchema\n    url:\
  \ json-schema/learning-manager-webhooks-certification-completed-payload-schema.json\n  - type: JSONSchema\n    url: json-schema/learning-manager-webhooks-course-created-payload-schema.json\n  - type: JSONStructure\n    url: json-structure/learning-manager-webhooks-badge-awarded-payload-structure.json\n  - type: JSONStructure\n    url: json-structure/learning-manager-webhooks-certification-completed-payload-structure.json\n  - type: JSONStructure\n    url: json-structure/learning-manager-webhooks-course-created-payload-structure.json\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ncommon:\n- type: Support\n  url: https://helpx.adobe.com/support/captivate.html\n- type: Community\n  url: https://community.adobe.com/t5/adobe-captivate/ct-p/ct-captivate\n- type: Blog\n  url: https://elearning.adobe.com/\n- type: StatusPage\n  url: https://status.adobe.com/\n- type: TermsOfService\n  url: https://www.adobe.com/legal/terms.html\n- type: PrivacyPolicy\n\
  \  url: https://www.adobe.com/privacy.html\n- type: Contact\n  url: https://www.adobe.com/products/captivate/contact.html\n- type: Portal\n  url: https://experienceleague.adobe.com/docs/learning-manager/using/introduction.html\n- type: GettingStarted\n  url: https://experienceleague.adobe.com/docs/learning-manager/using/getting-started/getting-started.html\n- type: Documentation\n  url: https://experienceleague.adobe.com/docs/learning-manager/using/home.html\n- type: Console\n  url: https://developer.adobe.com/console/\n- type: ChangeLog\n  url: https://experienceleague.adobe.com/docs/learning-manager/using/whats-new.html\n- type: Website\n  url: https://business.adobe.com/products/learning-manager/adobe-learning-manager.html\n- type: Login\n  url: https://learningmanager.adobe.com/\n- type: YouTube\n  url: https://www.youtube.com/user/AdobeELearning\n- type: GitHubOrganization\n  url: https://github.com/adobe\n- type: JSONSchema\n  url: json-schema/adobe-captivate-learning-object-schema.json\n\
  - type: JSON-LD\n  url: json-ld/adobe-captivate-context.jsonld\n- type: Features\n  data:\n  - name: Learning Object Management\n    description: Create and manage courses, learning programs, certifications, and job aids with full CRUD operations via REST API.\n  - name: Learner Enrollment and Tracking\n    description: Programmatically enroll learners, track progress, and retrieve completion status across all learning objects.\n  - name: Webhook Event Notifications\n    description: Receive real-time HTTP POST notifications for enrollment, completion, badge, and certification events.\n  - name: Gamification and Badges\n    description: Manage gamification points, leaderboards, and badge awards to motivate learners.\n  - name: Catalog Management\n    description: Organize and expose learning content through catalogs with filtering and tagging capabilities.\n  - name: Skill Tracking\n    description: Associate skills with learning content and track learner skill attainment through the API.\n\
  \  - name: OAuth 2.0 Authentication\n    description: Secure API access using OAuth 2.0 with role-based scopes for admin, learner, manager, and author roles.\n  - name: SCORM and xAPI Support\n    description: Deliver and track SCORM-compliant and xAPI (Tin Can) learning content for LMS interoperability.\n  - name: Bulk Data Import/Export\n    description: Use the Jobs API to import and export users, enrollments, and completion data in bulk.\n  - name: Notification Management\n    description: Manage announcements and notifications sent to learners, managers, and administrators.\n- type: UseCases\n  data:\n  - name: HR System Integration\n    description: Automatically provision users from HRIS systems like Workday or SAP SuccessFactors into Adobe Learning Manager.\n  - name: Custom Learning Portal\n    description: Build branded training portals that surface Adobe Learning Manager content through the REST API.\n  - name: Compliance Training Automation\n    description: Auto-enroll new\
  \ hires in mandatory compliance courses and track completion for regulatory reporting.\n  - name: Learning Analytics Dashboard\n    description: Extract learner progress and completion data to build custom analytics and reporting dashboards.\n  - name: E-Commerce Integration\n    description: Integrate course purchases with e-commerce platforms and auto-enroll paying customers.\n  - name: Real-Time Progress Monitoring\n    description: Use webhooks to monitor learner activity in real time and trigger downstream workflows on completion.\n  - name: Certification Management\n    description: Automate certification enrollment, renewal reminders, and expiry tracking using the REST API.\n- type: Integrations\n  data:\n  - name: Salesforce\n    description: Sync learner data and completion status between Adobe Learning Manager and Salesforce CRM.\n  - name: Microsoft Teams\n    description: Surface learning content and notifications directly within Microsoft Teams via connector.\n  - name: Workday\n\
  \    description: Import organizational user data from Workday HCM to manage learner accounts automatically.\n  - name: SAP SuccessFactors\n    description: Bi-directional sync with SAP SuccessFactors for user provisioning and learning record exchange.\n  - name: Adobe Experience Manager\n    description: Embed learning content and catalogs within Adobe Experience Manager sites.\n  - name: Zoom\n    description: Schedule and launch virtual classroom sessions directly from Adobe Learning Manager.\n  - name: LinkedIn Learning\n    description: Import LinkedIn Learning content into Adobe Learning Manager catalogs for blended learning.\n  - name: SCORM Cloud\n    description: Host and launch SCORM content packages through SCORM Cloud integration.\n- type: SpectralRules\n  url: rules/adobe-captivate-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/learning-management.yaml\n- type: Vocabulary\n  url: vocabulary/adobe-captivate-vocabulary.yaml\n- type: JSON-LD\n  url: json-ld/adobe-captivate-learning-manager-webhooks-context.jsonld\n\
  - type: JSON-LD\n  url: json-ld/adobe-captivate-prime-api-context.jsonld\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/apis.yml
tags:
- Authoring
- Education
- eLearning
- LMS
- SCORM
- Training
- xAPI
url: https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/apis.yml
use_cases:
- description: Automatically provision users from HRIS systems like Workday or SAP SuccessFactors into Adobe Learning Manager.
  name: HR System Integration
- description: Build branded training portals that surface Adobe Learning Manager content through the REST API.
  name: Custom Learning Portal
- description: Auto-enroll new hires in mandatory compliance courses and track completion for regulatory reporting.
  name: Compliance Training Automation
- description: Extract learner progress and completion data to build custom analytics and reporting dashboards.
  name: Learning Analytics Dashboard
- description: Integrate course purchases with e-commerce platforms and auto-enroll paying customers.
  name: E-Commerce Integration
- description: Use webhooks to monitor learner activity in real time and trigger downstream workflows on completion.
  name: Real-Time Progress Monitoring
- description: Automate certification enrollment, renewal reminders, and expiry tracking using the REST API.
  name: Certification Management
---
