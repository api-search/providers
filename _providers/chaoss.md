---
api_count: 4
apis:
- description: Augur is a CHAOSS reference implementation that collects data from GitHub, GitLab, mailing lists, and other community sources, and exposes a REST API for querying CHAOSS-aligned metrics on repositorie
  name: CHAOSS Augur REST API
  slug: augur-api
- description: The CHAOSS Metrics catalog is a community-maintained, structured reference of community-health metrics organized into focus areas (Common, DEI, Risk, Value, Evolution) plus metrics models that compose
  name: CHAOSS Metrics Catalog
  slug: metrics-catalog
- description: GrimoireLab is an open source platform for software development analytics. It pulls data from 30+ data sources (Git, GitHub, GitLab, mailing lists, IRC, Slack, Jira, Bugzilla, etc.) and provides a Pyt
  name: CHAOSS GrimoireLab
  slug: grimoirelab
- description: 8Knot is an open source community analytics dashboard built on top of Augur that provides ready-made visualizations of CHAOSS metrics for stakeholders evaluating open source project health.
  name: CHAOSS 8Knot Dashboard
  slug: 8knot
common:
- title: ''
  type: Website
  url: https://chaoss.community/
- title: ''
  type: Documentation
  url: https://chaoss.community/kbtopic/all-metrics/
- title: ''
  type: GitHub
  url: https://github.com/chaoss
- title: ''
  type: WorkingGroups
  url: https://chaoss.community/working-groups/
- title: ''
  type: Events
  url: https://chaoss.community/events/
- title: ''
  type: Blog
  url: https://chaoss.community/news-blog/
- title: ''
  type: PractitionerGuides
  url: https://chaoss.community/practitioner-guides/
- title: ''
  type: ParentOrganization
  url: https://www.linuxfoundation.org/
- title: ''
  type: GettingStarted
  url: https://chaoss.community/get-started/
- title: ''
  type: Community
  url: https://chaoss.community/participate/
- title: ''
  type: Slack
  url: https://chaoss.community/connect/
- title: ''
  type: YouTube
  url: https://www.youtube.com/c/CHAOSScommunity
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/chaoss-community/
- title: ''
  type: X
  url: https://x.com/chaossproj
- title: ''
  type: Tools
  url: ''
- title: ''
  type: WorkingGroups
  url: ''
created: '2026-03-16'
description: CHAOSS (Community Health Analytics in Open Source Software) is a Linux Foundation project that develops metrics, methodologies, software, and practitioner guides for measuring and improving open source community health and sustainability. It produces a metrics catalog organized into focus areas (Common, DEI, Risk, Value, Evolution) and metrics models, along with open source software (Augur, 8Knot, GrimoireLab) that ingests data from Git, GitHub, GitLab, mailing lists, and other community platforms to compute the metrics. CHAOSS-aligned SaaS services such as OSS Compass and Bitergia Analytics also expose the metrics for adopters who do not want to host the software themselves.
features:
- name: Community Health Metrics
- name: Metrics Models
- name: DEI Metrics
- name: Risk Metrics
- name: Value Metrics
- name: Evolution Metrics
- name: Common Metrics
- name: Open Source Software
- name: Practitioner Guides
- name: Working Groups
- name: Reference Implementations
- name: REST API (Augur)
- name: Data Pipeline (GrimoireLab)
- name: Dashboards (8Knot, Bitergia)
- name: SaaS Adopter Services
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- name: GitHub
- name: GitLab
- name: Bitbucket
- name: Git
- name: Mailing Lists
- name: Jira
- name: Bugzilla
- name: Discourse
- name: Slack
- name: IRC
- name: Stack Exchange
- name: Meetup
- name: Linux Foundation
- name: CNCF
- name: Apache Software Foundation
- name: OpenSSF
layout: provider
modified: '2026-04-23'
name: CHAOSS
skills: []
slug: chaoss
solutions: []
source_filename: apis.yml
source_yaml: "aid: chaoss\nname: CHAOSS\nx-type: opensource\ndescription: >-\n  CHAOSS (Community Health Analytics in Open Source Software) is a Linux\n  Foundation project that develops metrics, methodologies, software, and\n  practitioner guides for measuring and improving open source community\n  health and sustainability. It produces a metrics catalog organized into\n  focus areas (Common, DEI, Risk, Value, Evolution) and metrics models,\n  along with open source software (Augur, 8Knot, GrimoireLab) that\n  ingests data from Git, GitHub, GitLab, mailing lists, and other\n  community platforms to compute the metrics. CHAOSS-aligned SaaS\n  services such as OSS Compass and Bitergia Analytics also expose the\n  metrics for adopters who do not want to host the software themselves.\ntype: Index\nposition: Producer\naccess: Open Source\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Analytics\n  - Community Health\n  - DEI\n  - Linux Foundation\n\
  \  - Metrics\n  - Observability\n  - Open Source\n  - Risk\n  - Sustainability\ncreated: '2026-03-16'\nmodified: '2026-04-23'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/chaoss/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: chaoss:augur-api\n    name: CHAOSS Augur REST API\n    description: >-\n      Augur is a CHAOSS reference implementation that collects data from\n      GitHub, GitLab, mailing lists, and other community sources, and\n      exposes a REST API for querying CHAOSS-aligned metrics on\n      repositories, contributors, issues, pull requests, releases, and\n      more. The API powers downstream analytics tools and dashboards\n      including 8Knot.\n    humanURL: https://oss-augur.readthedocs.io/\n    baseURL: https://ai.chaoss.io/api\n    tags:\n      - Augur\n      - Community Health\n      - Metrics\n      - REST\n    properties:\n      - type: Documentation\n        url: https://oss-augur.readthedocs.io/\n      - type: GitHubRepository\n\
  \        url: https://github.com/chaoss/augur\n      - type: API\n        url: https://oss-augur.readthedocs.io/en/dev/rest-api/api.html\n  - aid: chaoss:metrics-catalog\n    name: CHAOSS Metrics Catalog\n    description: >-\n      The CHAOSS Metrics catalog is a community-maintained, structured\n      reference of community-health metrics organized into focus areas\n      (Common, DEI, Risk, Value, Evolution) plus metrics models that\n      compose them. The catalog is openly licensed and published on the\n      CHAOSS website and the chaoss/metrics GitHub repository, and is\n      consumed by Augur, GrimoireLab, OSS Compass, Bitergia Analytics,\n      and other implementations.\n    humanURL: https://chaoss.community/metrics/\n    tags:\n      - Catalog\n      - Documentation\n      - Metrics\n      - Models\n    properties:\n      - type: Documentation\n        url: https://chaoss.community/kbtopic/all-metrics/\n      - type: GitHubRepository\n        url: https://github.com/chaoss/wg-metrics-models\n\
  \      - type: MetricsRepository\n        url: https://github.com/chaoss/community\n  - aid: chaoss:grimoirelab\n    name: CHAOSS GrimoireLab\n    description: >-\n      GrimoireLab is an open source platform for software development\n      analytics. It pulls data from 30+ data sources (Git, GitHub,\n      GitLab, mailing lists, IRC, Slack, Jira, Bugzilla, etc.) and\n      provides a Python toolkit (Perceval, Sortinghat, GrimoireELK) plus\n      a Kibana-based dashboard, exposing CHAOSS metrics for community\n      health analysis.\n    humanURL: https://chaoss.github.io/grimoirelab/\n    tags:\n      - Analytics\n      - Data Pipeline\n      - GrimoireLab\n      - Kibana\n      - Metrics\n    properties:\n      - type: Documentation\n        url: https://chaoss.github.io/grimoirelab/\n      - type: GitHubRepository\n        url: https://github.com/chaoss/grimoirelab\n  - aid: chaoss:8knot\n    name: CHAOSS 8Knot Dashboard\n    description: >-\n      8Knot is an open source community\
  \ analytics dashboard built on top\n      of Augur that provides ready-made visualizations of CHAOSS metrics\n      for stakeholders evaluating open source project health.\n    humanURL: https://github.com/oss-aspen/8knot\n    tags:\n      - Dashboard\n      - Visualization\n    properties:\n      - type: Documentation\n        url: https://github.com/oss-aspen/8knot\n      - type: GitHubRepository\n        url: https://github.com/oss-aspen/8knot\ncommon:\n  - type: Website\n    url: https://chaoss.community/\n  - type: Documentation\n    name: CHAOSS Documentation\n    description: Official documentation for CHAOSS metrics and software.\n    url: https://chaoss.community/kbtopic/all-metrics/\n  - type: GitHub\n    name: CHAOSS GitHub\n    description: Source code and repositories for CHAOSS.\n    url: https://github.com/chaoss\n  - type: WorkingGroups\n    url: https://chaoss.community/working-groups/\n  - type: Events\n    url: https://chaoss.community/events/\n  - type: Blog\n    url:\
  \ https://chaoss.community/news-blog/\n  - type: PractitionerGuides\n    url: https://chaoss.community/practitioner-guides/\n  - type: ParentOrganization\n    url: https://www.linuxfoundation.org/\n  - type: GettingStarted\n    url: https://chaoss.community/get-started/\n  - type: Community\n    url: https://chaoss.community/participate/\n  - type: Slack\n    url: https://chaoss.community/connect/\n  - type: YouTube\n    url: https://www.youtube.com/c/CHAOSScommunity\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/chaoss-community/\n  - type: X\n    url: https://x.com/chaossproj\n  - name: Features\n    type: Features\n    data:\n      - name: Community Health Metrics\n      - name: Metrics Models\n      - name: DEI Metrics\n      - name: Risk Metrics\n      - name: Value Metrics\n      - name: Evolution Metrics\n      - name: Common Metrics\n      - name: Open Source Software\n      - name: Practitioner Guides\n      - name: Working Groups\n      - name: Reference Implementations\n\
  \      - name: REST API (Augur)\n      - name: Data Pipeline (GrimoireLab)\n      - name: Dashboards (8Knot, Bitergia)\n      - name: SaaS Adopter Services\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Open Source Project Health Assessment\n      - name: Contributor Sustainability Analysis\n      - name: DEI in Open Source Communities\n      - name: Open Source Risk and Security Assessment\n      - name: Open Source Investment ROI\n      - name: Funding Impact Measurement\n      - name: Community Onboarding Improvement\n      - name: Foundation-Level Reporting\n      - name: OSPO Health Reporting\n      - name: Maintainer Burnout Detection\n  - name: Tools\n    type: Tools\n    data:\n      - name: Augur\n      - name: GrimoireLab\n      - name: 8Knot\n      - name: Bitergia Analytics\n      - name: OSS Compass\n      - name: Cauldron\n      - name: Sortinghat\n      - name: Perceval\n      - name: GrimoireELK\n  - name: WorkingGroups\n    type: WorkingGroups\n    data:\n\
  \      - name: Common Metrics\n      - name: DEI Metrics\n      - name: Risk Metrics\n      - name: Value Metrics\n      - name: Evolution Metrics\n      - name: Software (Augur and GrimoireLab)\n      - name: Education\n      - name: Practitioner Guides\n  - name: Integrations\n    type: Integrations\n    data:\n      - name: GitHub\n      - name: GitLab\n      - name: Bitbucket\n      - name: Git\n      - name: Mailing Lists\n      - name: Jira\n      - name: Bugzilla\n      - name: Discourse\n      - name: Slack\n      - name: IRC\n      - name: Stack Exchange\n      - name: Meetup\n      - name: Linux Foundation\n      - name: CNCF\n      - name: Apache Software Foundation\n      - name: OpenSSF\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chaoss/refs/heads/main/apis.yml
tags:
- Analytics
- Community Health
- DEI
- Linux Foundation
- Metrics
- Observability
- Open Source
- Risk
- Sustainability
url: https://raw.githubusercontent.com/api-evangelist/chaoss/refs/heads/main/apis.yml
use_cases:
- name: Open Source Project Health Assessment
- name: Contributor Sustainability Analysis
- name: DEI in Open Source Communities
- name: Open Source Risk and Security Assessment
- name: Open Source Investment ROI
- name: Funding Impact Measurement
- name: Community Onboarding Improvement
- name: Foundation-Level Reporting
- name: OSPO Health Reporting
- name: Maintainer Burnout Detection
---
