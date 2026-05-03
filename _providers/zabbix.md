---
api_count: 1
api_specs:
- filename: zabbix-openapi.yml
  format: yaml
  label: Zabbix API
  slug: zabbix-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zabbix/refs/heads/main/openapi/zabbix-openapi.yml
apis:
- description: The Zabbix API is a JSON-RPC 2.0 HTTP API for programmatically retrieving and modifying the configuration of Zabbix and accessing historical monitoring data. Supports host management, item configurati
  name: Zabbix API
  slug: zabbix-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://www.zabbix.com
- title: ''
  type: Blog
  url: https://blog.zabbix.com
- title: ''
  type: GitHub
  url: https://github.com/zabbix/zabbix
- title: ''
  type: GitHubOrg
  url: https://github.com/zabbix
- title: ''
  type: Docker
  url: https://github.com/zabbix/zabbix-docker
- title: ''
  type: AnsibleCollection
  url: https://github.com/zabbix/ansible-collection
- title: ''
  type: CommunityTemplates
  url: https://github.com/zabbix/community-templates
- title: ''
  type: Twitter
  url: https://twitter.com/zabbix
- title: ''
  type: PrivacyPolicy
  url: https://www.zabbix.com/privacy_policy
- title: ''
  type: TermsOfService
  url: https://www.zabbix.com/terms_of_use
- title: ''
  type: Download
  url: https://www.zabbix.com/download
created: '2024-01-01'
description: Zabbix is an enterprise-class open source distributed monitoring solution for networks and applications. Zabbix enables real-time monitoring of millions of metrics collected from tens of thousands of servers, virtual machines, and network devices. The Zabbix API provides JSON-RPC 2.0 access for programmatically managing host configurations, collecting monitoring data, and automating operations.
features:
- name: Host Monitoring
- name: Network Monitoring
- name: Application Monitoring
- name: Cloud Monitoring
- name: Agent-Based Collection
- name: Agentless Collection (SNMP, IPMI, JMX)
- name: Triggers and Alerting
- name: Dashboards and Visualizations
- name: Historical Data Storage
- name: Scalable Distributed Monitoring
- name: Auto Discovery
- name: API Automation
image: https://www.zabbix.com/assets/img/logo/zabbix_logo.png
integrations:
- name: Ansible Collection
- name: Docker / Kubernetes
- name: Grafana Plugin
- name: Slack Notifications
- name: PagerDuty Integration
- name: Jira Integration
- name: ServiceNow Integration
layout: provider
modified: '2026-05-03'
name: Zabbix
rules:
- name: Zabbix API Rules
  rule_count: 11
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 4
  slug: zabbix-rules
skills: []
slug: zabbix
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zabbix\nname: Zabbix\ndescription: >-\n  Zabbix is an enterprise-class open source distributed monitoring solution\n  for networks and applications. Zabbix enables real-time monitoring of millions\n  of metrics collected from tens of thousands of servers, virtual machines, and\n  network devices. The Zabbix API provides JSON-RPC 2.0 access for programmatically\n  managing host configurations, collecting monitoring data, and automating operations.\nimage: https://www.zabbix.com/assets/img/logo/zabbix_logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/zabbix/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Monitoring\n  - Infrastructure\n  - Networks\n  - Alerting\n  - Open Source\n  - Observability\napis:\n  - aid: zabbix:zabbix-api\n    name: Zabbix API\n    description: >-\n      The Zabbix API is a JSON-RPC 2.0 HTTP API for programmatically retrieving\n      and modifying the configuration\
  \ of Zabbix and accessing historical monitoring\n      data. Supports host management, item configuration, trigger management,\n      event handling, alerting, user management, and historical data retrieval.\n    image: https://www.zabbix.com/assets/img/logo/zabbix_logo.png\n    humanURL: https://www.zabbix.com/documentation/current/en/manual/api\n    baseURL: https://{host}/zabbix/api_jsonrpc.php\n    tags:\n      - Monitoring\n      - Infrastructure\n      - JSON-RPC\n      - Alerting\n      - Networks\n    properties:\n      - type: Documentation\n        url: https://www.zabbix.com/documentation/current/en/manual/api\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/zabbix/refs/heads/main/openapi/zabbix-openapi.yml\n      - type: GettingStarted\n        url: https://www.zabbix.com/documentation/current/en/manual/quickstart\n      - type: Authentication\n        url: https://www.zabbix.com/documentation/current/en/manual/api/reference/user/login\n\
  \      - type: ChangeLog\n        url: https://www.zabbix.com/documentation/current/en/manual/introduction/whatsnew\n    contact:\n      - type: Support\n        url: https://www.zabbix.com/support\n      - type: Forum\n        url: https://www.zabbix.com/forum\n      - type: Email\n        url: mailto:sales@zabbix.com\ncommon:\n  - type: Portal\n    url: https://www.zabbix.com\n  - type: Blog\n    url: https://blog.zabbix.com\n  - type: GitHub\n    url: https://github.com/zabbix/zabbix\n  - type: GitHubOrg\n    url: https://github.com/zabbix\n  - type: Docker\n    url: https://github.com/zabbix/zabbix-docker\n  - type: AnsibleCollection\n    url: https://github.com/zabbix/ansible-collection\n  - type: CommunityTemplates\n    url: https://github.com/zabbix/community-templates\n  - type: Twitter\n    url: https://twitter.com/zabbix\n  - type: PrivacyPolicy\n    url: https://www.zabbix.com/privacy_policy\n  - type: TermsOfService\n    url: https://www.zabbix.com/terms_of_use\n  - type: Download\n\
  \    url: https://www.zabbix.com/download\n  - type: Integrations\n    data:\n      - name: Ansible Collection\n      - name: Docker / Kubernetes\n      - name: Grafana Plugin\n      - name: Slack Notifications\n      - name: PagerDuty Integration\n      - name: Jira Integration\n      - name: ServiceNow Integration\n  - type: Features\n    data:\n      - name: Host Monitoring\n      - name: Network Monitoring\n      - name: Application Monitoring\n      - name: Cloud Monitoring\n      - name: Agent-Based Collection\n      - name: Agentless Collection (SNMP, IPMI, JMX)\n      - name: Triggers and Alerting\n      - name: Dashboards and Visualizations\n      - name: Historical Data Storage\n      - name: Scalable Distributed Monitoring\n      - name: Auto Discovery\n      - name: API Automation\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zabbix/refs/heads/main/apis.yml
tags:
- Monitoring
- Infrastructure
- Networks
- Alerting
- Open Source
- Observability
url: https://raw.githubusercontent.com/api-evangelist/zabbix/refs/heads/main/apis.yml
use_cases: []
---
