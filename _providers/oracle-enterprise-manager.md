---
api_count: 17
api_specs:
- filename: oracle-enterprise-manager-cloud-control-openapi.yml
  format: yaml
  label: Oracle Enterprise Manager Cloud Control REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-enterprise-manager/refs/heads/main/openapi/oracle-enterprise-manager-cloud-control-openapi.yml
apis:
- description: 'REST API for Oracle Enterprise Manager Cloud Control providing access to monitoring, configuration, and administration capabilities including targets, metrics, incidents, blackouts, credentials, user '
  name: Oracle Enterprise Manager Cloud Control REST API
  slug: ''
- description: 'Command-line interface providing scriptable access to Enterprise Manager functionality including target management, job operations, patching, provisioning, and administration tasks through verbs that '
  name: Enterprise Manager Command Line Interface (EM CLI)
  slug: ''
- description: API for creating, managing, and monitoring Enterprise Manager jobs and tasks including scheduling, execution tracking, and deployment procedures.
  name: Enterprise Manager Job System API
  slug: ''
- description: API for accessing performance metrics, monitoring data, and alerting information including numeric metric data points over time, latest metric values, and metric group metadata.
  name: Enterprise Manager Metric and Monitoring API
  slug: ''
- description: API for managing monitored targets including discovery, configuration, lifecycle operations, bulk property updates, and target type metadata.
  name: Enterprise Manager Target Management API
  slug: ''
- description: REST API for searching, viewing, and managing incidents and events in Enterprise Manager, including clearing, suppressing, unsuppressing incidents, viewing member events, and managing annotations.
  name: Enterprise Manager Incidents and Events API
  slug: ''
- description: REST API for managing blackouts (maintenance windows) in Enterprise Manager, including creating, editing, deleting, listing, and stopping blackouts, managing blackout reasons, and retrieving targets i
  name: Enterprise Manager Blackout Management API
  slug: ''
- description: REST API for managing named credentials, monitoring credentials, and preferred credentials in Enterprise Manager, including creating, listing, deleting, updating, testing, and searching credential typ
  name: Enterprise Manager Credentials Management API
  slug: ''
- description: 'REST API for managing Enterprise Manager users and roles, including creating, modifying, and deleting users and roles, managing privilege grants and role assignments, and listing secure resources and '
  name: Enterprise Manager User Management API
  slug: ''
- description: REST API for database maintenance operations including updates, upgrades, and patching, with support for creating and managing Gold Images, patch recommendations, compliance reporting, and Fleet Patch
  name: Enterprise Manager Database Patching and Maintenance API
  slug: ''
- description: REST API for managing deployment procedures including creating, submitting, and deleting procedures, managing procedure instances with resume, suspend, stop, and retry operations, and tracking executi
  name: Enterprise Manager Deployment Procedure API
  slug: ''
- description: REST API for configuring and managing database backup settings, fleet-level backup configuration, and scheduling backup operations in Enterprise Manager.
  name: Enterprise Manager Database Backup Management API
  slug: ''
- description: REST API for managing Oracle Zero Data Loss Recovery Appliance (ZDLRA) including adding and removing protected databases, creating and managing protection policies, creating archival backups, and retr
  name: Enterprise Manager ZDLRA Management API
  slug: ''
- description: REST API for executing SQL queries against database targets monitored by Enterprise Manager and against the Enterprise Manager repository, enabling custom data extraction for dashboards and KPI report
  name: Enterprise Manager SQL Execution REST API
  slug: ''
- description: REST API for managing Oracle Data Guard configurations in Enterprise Manager, enabling high availability operations including switchover, failover, and standby database management.
  name: Enterprise Manager Data Guard Administration REST API
  slug: ''
- description: REST APIs for Database as a Service (DBaaS) operations enabling self-service database provisioning, request management, and quota administration through Enterprise Manager Cloud Control.
  name: Enterprise Manager Cloud APIs (DBaaS)
  slug: ''
- description: Extensibility Development Kit providing tools, utilities, and APIs for developing Enterprise Manager plug-ins to extend platform capabilities for custom target monitoring and management.
  name: Enterprise Manager Extensibility Development Kit (EDK) API
  slug: ''
capabilities:
- description: 'Unified workflow for monitoring, incident response, and maintenance management across Oracle infrastructure using Enterprise Manager Cloud Control APIs. Designed for infrastructure administrators and '
  name: Oracle Enterprise Manager Infrastructure Management
  slug: infrastructure-management
common:
- title: ''
  type: Portal
  url: https://www.oracle.com/enterprise-manager/
- title: ''
  type: Documentation
  url: https://docs.oracle.com/en/enterprise-manager/
- title: ''
  type: Support
  url: https://www.oracle.com/support/
- title: ''
  type: Pricing
  url: https://www.oracle.com/enterprise-manager/pricing.html
- title: ''
  type: Blog
  url: https://blogs.oracle.com/oem/
- title: ''
  type: Training
  url: https://education.oracle.com/enterprise-manager
- title: ''
  type: TermsOfService
  url: https://www.oracle.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.oracle.com/legal/privacy/
- title: ''
  type: GettingStarted
  url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/index.html
- title: ''
  type: ReleaseNotes
  url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrel/cloud-control-release-notes-emrel.html
- title: ''
  type: ChangeLog
  url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcon/new-features-release-update.html
- title: ''
  type: Security
  url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emsec/index.html
- title: ''
  type: Resources
  url: https://www.oracle.com/enterprise-manager/technologies/
created: '2024-01-01'
description: Oracle Enterprise Manager (OEM) provides a comprehensive management platform for managing Oracle IT infrastructure and applications. The APIs enable programmatic access to monitoring, administration, and automation capabilities.
features:
- description: Monitor Oracle databases, hosts, middleware, and custom applications with configurable metrics, thresholds, and alerting.
  name: Target Monitoring
- description: Correlate events into actionable incidents with severity, priority, escalation, and automated notification workflows.
  name: Incident Management
- description: Schedule maintenance windows to suppress monitoring alerts during planned downtime without losing data collection.
  name: Blackout Management
- description: Automate database patching, upgrades, and fleet maintenance with Gold Images and compliance reporting.
  name: Database Lifecycle Management
- description: Create and manage multi-step deployment workflows for provisioning, patching, and configuration changes.
  name: Deployment Procedures
- description: Enable Database as a Service with self-service provisioning, quota management, and request workflows.
  name: Cloud Self-Service
image: /assets/icons/oracle-enterprise-manager.png
integrations:
- description: Visualize Enterprise Manager metrics in Grafana dashboards using the OEM data source plugin.
  name: Grafana
- description: Extend monitoring to OCI resources and hybrid cloud environments through unified management.
  name: Oracle Cloud Infrastructure
- description: Forward incidents to ServiceNow for ITSM integration and automated ticket creation.
  name: ServiceNow
jsonld:
- class_count: 0
  name: Oracle Enterprise Manager Cloud Control Context
  property_count: 0
  slug: oracle-enterprise-manager-cloud-control-context
- class_count: 9
  name: Oracle Enterprise Manager Context
  property_count: 13
  slug: oracle-enterprise-manager-context
layout: provider
modified: '2026-04-18'
name: Oracle Enterprise Manager
rules:
- name: Oracle Enterprise Manager API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: oracle-enterprise-manager-spectral-rules
skills: []
slug: oracle-enterprise-manager
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: oracle-enterprise-manager\nname: Oracle Enterprise Manager\ndescription: >-\n  Oracle Enterprise Manager (OEM) provides a comprehensive management platform\n  for managing Oracle IT infrastructure and applications. The APIs enable\n  programmatic access to monitoring, administration, and automation capabilities.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/oracle-enterprise-manager/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Cloud Management\n  - Database Management\n  - Enterprise Management\n  - Infrastructure Management\n  - Monitoring\n  - Oracle\napis:\n  - name: Oracle Enterprise Manager Cloud Control REST API\n    description: REST API for Oracle Enterprise Manager Cloud Control providing access to monitoring, configuration, and administration capabilities\
  \ including targets, metrics, incidents, blackouts, credentials, user management, and deployment procedures.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/APIOverview.html\n    baseURL: https://<em-host>:<port>/em/api\n    tags:\n      - Administration\n      - Cloud Control\n      - Monitoring\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/APIOverview.html\n      - type: OpenAPI\n        url: openapi/oracle-enterprise-manager-cloud-control-openapi.yml\n      - type: JSONSchema\n        url: json-schema/oracle-enterprise-manager-target-schema.json\n      - type: JSONLD\n        url: json-ld/oracle-enterprise-manager-context.jsonld\n      - type: Authentication\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/Authentication.html\n\
  \      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/SendRequests.html\n    contact:\n      - FN: Oracle Support\n        email: support@oracle.com\n        url: https://www.oracle.com/support/\n  - name: Enterprise Manager Command Line Interface (EM CLI)\n    description: Command-line interface providing scriptable access to Enterprise Manager functionality including target management, job operations, patching, provisioning, and administration tasks through verbs that can be used in shell scripts, Perl, and Python.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/\n    baseURL: https://<em-host>:<port>/em\n\
  \    tags:\n      - Automation\n      - CLI\n      - Command Line\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/\n      - type: GettingStarted\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/getting-started-em-cli.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/em-cli-verbs.html\n      - type: Authentication\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcli/emcli-security.html\n  - name: Enterprise Manager Job System API\n    description: API for creating, managing, and monitoring Enterprise Manager jobs and tasks including scheduling, execution tracking, and deployment procedures.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n\
  \    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n    baseURL: https://<em-host>:<port>/em/websvcs/restful/emws/job\n    tags:\n      - Automation\n      - Jobs\n      - Scheduling\n      - Task Management\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n  - name: Enterprise Manager Metric and Monitoring API\n    description: API for accessing performance metrics, monitoring data, and alerting information including numeric metric data points over time, latest metric values, and metric group metadata.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n\
  \    baseURL: https://<em-host>:<port>/em/websvcs/restful/emws/metric\n    tags:\n      - Alerts\n      - Metrics\n      - Monitoring\n      - Performance\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n  - name: Enterprise Manager Target Management API\n    description: API for managing monitored targets including discovery, configuration, lifecycle operations, bulk property updates, and target type metadata.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n    baseURL: https://<em-host>:<port>/em/websvcs/restful/emws/target\n    tags:\n      - Configuration\n\
  \      - Discovery\n      - Lifecycle\n      - Target Management\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n  - name: Enterprise Manager Incidents and Events API\n    description: REST API for searching, viewing, and managing incidents and events in Enterprise Manager, including clearing, suppressing, unsuppressing incidents, viewing member events, and managing annotations.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n    baseURL: https://<em-host>:<port>/em/api/incidents\n    tags:\n      - Alerting\n      - Events\n      - Incidents\n \
  \     - Troubleshooting\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n  - name: Enterprise Manager Blackout Management API\n    description: REST API for managing blackouts (maintenance windows) in Enterprise Manager, including creating, editing, deleting, listing, and stopping blackouts, managing blackout reasons, and retrieving targets in blackouts.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n    baseURL: https://<em-host>:<port>/em/api/blackouts\n    tags:\n      - Blackouts\n      - Maintenance Windows\n      -\
  \ Scheduling\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n  - name: Enterprise Manager Credentials Management API\n    description: REST API for managing named credentials, monitoring credentials, and preferred credentials in Enterprise Manager, including creating, listing, deleting, updating, testing, and searching credential types.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n    baseURL: https://<em-host>:<port>/em/api/credentials\n    tags:\n      - Authentication\n      - Credentials\n      - Security\n    properties:\n\
  \      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n      - type: Security\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emsec/index.html\n  - name: Enterprise Manager User Management API\n    description: REST API for managing Enterprise Manager users and roles, including creating, modifying, and deleting users and roles, managing privilege grants and role assignments, and listing secure resources and permissions.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n    baseURL: https://<em-host>:<port>/em/api/users\n\
  \    tags:\n      - Permissions\n      - Roles\n      - Security\n      - User Management\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n      - type: Security\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emsec/index.html\n  - name: Enterprise Manager Database Patching and Maintenance API\n    description: REST API for database maintenance operations including updates, upgrades, and patching, with support for creating and managing Gold Images, patch recommendations, compliance reporting, and Fleet Patching and Provisioning (FPP) integration.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n \
  \   humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emlcm/patch-history.html\n    baseURL: https://<em-host>:<port>/em/api/dblm\n    tags:\n      - Database Maintenance\n      - Fleet Maintenance\n      - Gold Images\n      - Lifecycle Management\n      - Patching\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emlcm/patch-history.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n  - name: Enterprise Manager Deployment Procedure API\n    description: REST API for managing deployment procedures including creating, submitting, and deleting procedures, managing procedure instances with resume, suspend, stop, and retry operations, and tracking execution history.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n\
  \    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n    baseURL: https://<em-host>:<port>/em/api/deploymentProcedures\n    tags:\n      - Automation\n      - Deployment\n      - Procedures\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n  - name: Enterprise Manager Database Backup Management API\n    description: REST API for configuring and managing database backup settings, fleet-level backup configuration, and scheduling backup operations in Enterprise Manager.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n\
  \    baseURL: https://<em-host>:<port>/em/api/databaseBackup\n    tags:\n      - Backup Management\n      - Database Backup\n      - Recovery\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n  - name: Enterprise Manager ZDLRA Management API\n    description: REST API for managing Oracle Zero Data Loss Recovery Appliance (ZDLRA) including adding and removing protected databases, creating and managing protection policies, creating archival backups, and retrieving restore information.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n\
  \    baseURL: https://<em-host>:<port>/em/api/zdlra\n    tags:\n      - Data Protection\n      - Recovery Appliance\n      - ZDLRA\n      - Zero Data Loss\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n  - name: Enterprise Manager SQL Execution REST API\n    description: REST API for executing SQL queries against database targets monitored by Enterprise Manager and against the Enterprise Manager repository, enabling custom data extraction for dashboards and KPI reports.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emmon/executing-sql-rest-api.html\n\
  \    baseURL: https://<em-host>:<port>/em/api/db/sql\n    tags:\n      - Data Extraction\n      - Database Queries\n      - Reporting\n      - SQL Execution\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emmon/executing-sql-rest-api.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrest/rest-endpoints.html\n  - name: Enterprise Manager Data Guard Administration REST API\n    description: REST API for managing Oracle Data Guard configurations in Enterprise Manager, enabling high availability operations including switchover, failover, and standby database management.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emlcm/data-guard-administration-rest-api1.html\n\
  \    baseURL: https://<em-host>:<port>/em/api/dataguard\n    tags:\n      - Data Guard\n      - Disaster Recovery\n      - High Availability\n      - Standby Database\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emlcm/data-guard-administration-rest-api1.html\n  - name: Enterprise Manager Cloud APIs (DBaaS)\n    description: REST APIs for Database as a Service (DBaaS) operations enabling self-service database provisioning, request management, and quota administration through Enterprise Manager Cloud Control.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.4/emclo/using-cloud-apis.html\n    baseURL: https://<em-host>:<port>/em/cloud\n    tags:\n      - Cloud\n      - Database as a Service\n      - DBaaS\n      - Provisioning\n      - Self-Service\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.4/emclo/using-cloud-apis.html\n      - type: APIReference\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.4/emclo/database-service-ssa-user-rest-apis.html\n      - type: UseCases\n        url: https://docs.oracle.com/cd/E73210_01/EMCLO/GUID-99E7450E-4255-46B5-9C0E-DC520DE376D2.htm\n  - name: Enterprise Manager Extensibility Development Kit (EDK) API\n    description: Extensibility Development Kit providing tools, utilities, and APIs for developing Enterprise Manager plug-ins to extend platform capabilities for custom target monitoring and management.\n    image: https://www.oracle.com/a/ocom/img/oracle-enterprise-manager.jpg\n    humanURL: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/plug-ins.html\n    baseURL: https://<em-host>:<port>/em\n\
  \    tags:\n      - Custom Monitoring\n      - Extensibility\n      - Plugin Development\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/plug-ins.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://www.oracle.com/enterprise-manager/\n  - type: Documentation\n    url: https://docs.oracle.com/en/enterprise-manager/\n  - type: Support\n    url: https://www.oracle.com/support/\n  - type: Pricing\n    url: https://www.oracle.com/enterprise-manager/pricing.html\n  - type: Blog\n    url: https://blogs.oracle.com/oem/\n  - type: Training\n    url: https://education.oracle.com/enterprise-manager\n  - type: TermsOfService\n    url: https://www.oracle.com/legal/terms.html\n  - type: PrivacyPolicy\n    url: https://www.oracle.com/legal/privacy/\n  - type: GettingStarted\n    url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/index.html\n\
  \  - type: ReleaseNotes\n    url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emrel/cloud-control-release-notes-emrel.html\n  - type: ChangeLog\n    url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emcon/new-features-release-update.html\n  - type: Security\n    url: https://docs.oracle.com/en/enterprise-manager/cloud-control/enterprise-manager-cloud-control/13.5/emsec/index.html\n  - type: Integrations\n    url: https://www.oracle.com/enterprise-manager/technologies/grafana/\n  - type: Resources\n    url: https://www.oracle.com/enterprise-manager/technologies/\n  - type: Features\n    data:\n      - name: Target Monitoring\n        description: Monitor Oracle databases, hosts, middleware, and custom applications with configurable metrics, thresholds, and alerting.\n      - name: Incident Management\n        description: Correlate events into actionable incidents with severity, priority,\
  \ escalation, and automated notification workflows.\n      - name: Blackout Management\n        description: Schedule maintenance windows to suppress monitoring alerts during planned downtime without losing data collection.\n      - name: Database Lifecycle Management\n        description: Automate database patching, upgrades, and fleet maintenance with Gold Images and compliance reporting.\n      - name: Deployment Procedures\n        description: Create and manage multi-step deployment workflows for provisioning, patching, and configuration changes.\n      - name: Cloud Self-Service\n        description: Enable Database as a Service with self-service provisioning, quota management, and request workflows.\n  - type: UseCases\n    data:\n      - name: Infrastructure Monitoring\n        description: Centralized monitoring of Oracle databases, hosts, middleware, and applications with real-time metrics and alerting.\n      - name: Automated Patching\n        description: Fleet-level database\
  \ patching using Gold Images with compliance validation and rollback capabilities.\n      - name: Incident Response\n        description: Detect, triage, and resolve infrastructure issues using correlated incidents with annotations and escalation.\n      - name: Capacity Planning\n        description: Analyze metric trends over time to forecast resource needs and optimize infrastructure utilization.\n  - type: Integrations\n    data:\n      - name: Grafana\n        description: Visualize Enterprise Manager metrics in Grafana dashboards using the OEM data source plugin.\n      - name: Oracle Cloud Infrastructure\n        description: Extend monitoring to OCI resources and hybrid cloud environments through unified management.\n      - name: ServiceNow\n        description: Forward incidents to ServiceNow for ITSM integration and automated ticket creation.\ninclude:\n  - name: Oracle Cloud Infrastructure APIs\n    url: https://docs.oracle.com/en-us/iaas/api/\n  - name: Oracle Database APIs\n\
  \    url: https://docs.oracle.com/en/database/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/oracle-enterprise-manager/refs/heads/main/apis.yml
tags:
- Cloud Management
- Database Management
- Enterprise Management
- Infrastructure Management
- Monitoring
- Oracle
url: https://raw.githubusercontent.com/api-evangelist/oracle-enterprise-manager/refs/heads/main/apis.yml
use_cases:
- description: Centralized monitoring of Oracle databases, hosts, middleware, and applications with real-time metrics and alerting.
  name: Infrastructure Monitoring
- description: Fleet-level database patching using Gold Images with compliance validation and rollback capabilities.
  name: Automated Patching
- description: Detect, triage, and resolve infrastructure issues using correlated incidents with annotations and escalation.
  name: Incident Response
- description: Analyze metric trends over time to forecast resource needs and optimize infrastructure utilization.
  name: Capacity Planning
---
