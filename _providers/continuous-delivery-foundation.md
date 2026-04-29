---
api_count: 7
apis:
- description: CDEvents is a common specification for Continuous Delivery events that enables interoperability across CI/CD systems. It extends the CloudEvents specification and defines event vocabularies for source
  name: CDEvents Specification
  slug: cdevents
- description: Jenkins is the leading open source automation server, providing hundreds of plugins for building, deploying, and automating software projects. Jenkins exposes a remote access REST API that supports XM
  name: Jenkins
  slug: jenkins
- description: 'Spinnaker is an open-source, multi-cloud continuous delivery platform originally built at Netflix and Google for releasing software changes with high velocity and confidence. Spinnaker exposes a Gate '
  name: Spinnaker
  slug: spinnaker
- description: Screwdriver is an open-source build platform designed for Continuous Delivery, originally built at Yahoo. It provides a REST API for managing pipelines, builds, jobs, and webhooks and is designed to c
  name: Screwdriver
  slug: screwdriver
- description: Ortelius is an open source supply chain evidence store that aggregates continuous security intelligence across the software delivery lifecycle. It exposes APIs for tracking microservice components, SB
  name: Ortelius
  slug: ortelius
- description: JayeX is a customizable cloud developer tool suite hosted by the Continuous Delivery Foundation that provides built-in CI/CD capabilities and developer self-service tooling for cloud-native teams.
  name: JayeX
  slug: jayex
- description: Tekton is a Kubernetes-native open source framework for creating CI/CD systems. It defines Custom Resource Definitions for Pipelines, Tasks, PipelineRuns, and TaskRuns and was originally hosted at the
  name: Tekton
  slug: tekton
common:
- title: ''
  type: Website
  url: https://cd.foundation/
- title: ''
  type: Projects
  url: https://cd.foundation/projects/
- title: ''
  type: Documentation
  url: https://cd.foundation/projects/
- title: ''
  type: Blog
  url: https://cd.foundation/blog/
- title: ''
  type: Newsroom
  url: https://cd.foundation/news/
- title: ''
  type: GitHubOrg
  url: https://github.com/cdfoundation
- title: ''
  type: Community
  url: https://cd.foundation/community/
- title: ''
  type: Events
  url: https://cd.foundation/events/
created: '2026-03-16'
description: The Continuous Delivery Foundation (CDF) is a Linux Foundation project that hosts vendor-neutral open source projects for continuous integration, continuous delivery, and DevOps. It is the home of CDEvents, Jenkins, Spinnaker, Screwdriver, Ortelius, JayeX, and was previously the home of Tekton (now a CNCF graduated project) and other CD-focused tooling.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Continuous Delivery Foundation
skills: []
slug: continuous-delivery-foundation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: continuous-delivery-foundation\nname: Continuous Delivery Foundation\ndescription: >-\n  The Continuous Delivery Foundation (CDF) is a Linux Foundation project that\n  hosts vendor-neutral open source projects for continuous integration,\n  continuous delivery, and DevOps. It is the home of CDEvents, Jenkins,\n  Spinnaker, Screwdriver, Ortelius, JayeX, and was previously the home of\n  Tekton (now a CNCF graduated project) and other CD-focused tooling.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - CI/CD\n  - DevOps\n  - Linux Foundation\n  - Open Source\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/continuous-delivery-foundation/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: continuous-delivery-foundation:cdevents\n    name: CDEvents Specification\n    description: >-\n\
  \      CDEvents is a common specification for Continuous Delivery events that\n      enables interoperability across CI/CD systems. It extends the\n      CloudEvents specification and defines event vocabularies for source\n      code control, continuous integration, testing, continuous deployment,\n      continuous operations, and core lifecycle events. The specification is\n      maintained at github.com/cdevents/spec.\n    humanURL: https://cdevents.dev/\n    tags:\n      - CDEvents\n      - CI/CD\n      - CloudEvents\n      - Events\n      - Specification\n    properties:\n      - type: Documentation\n        url: https://cdevents.dev/docs/\n      - type: Specification\n        url: https://github.com/cdevents/spec\n      - type: GitHubOrg\n        url: https://github.com/cdevents\n      - type: Community\n        url: https://cdevents.dev/community/\n\n  - aid: continuous-delivery-foundation:jenkins\n    name: Jenkins\n    description: >-\n      Jenkins is the leading open source automation\
  \ server, providing\n      hundreds of plugins for building, deploying, and automating software\n      projects. Jenkins exposes a remote access REST API that supports XML,\n      JSON, and Python representations and is the de facto standard\n      automation engine for many organizations.\n    humanURL: https://www.jenkins.io/\n    tags:\n      - Automation\n      - CI/CD\n      - Jenkins\n      - Pipelines\n      - REST\n    properties:\n      - type: Documentation\n        url: https://www.jenkins.io/doc/\n      - type: APIDocumentation\n        url: https://www.jenkins.io/doc/book/using/remote-access-api/\n      - type: GettingStarted\n        url: https://www.jenkins.io/doc/pipeline/tour/getting-started/\n      - type: GitHubOrg\n        url: https://github.com/jenkinsci\n\n  - aid: continuous-delivery-foundation:spinnaker\n    name: Spinnaker\n    description: >-\n      Spinnaker is an open-source, multi-cloud continuous delivery platform\n      originally built at Netflix and Google\
  \ for releasing software changes\n      with high velocity and confidence. Spinnaker exposes a Gate REST API\n      that drives pipelines, applications, and deployment workflows across\n      AWS, GCP, Azure, Kubernetes, and other cloud targets.\n    humanURL: https://spinnaker.io/\n    tags:\n      - CD\n      - Cloud\n      - Deployment\n      - Multi-cloud\n      - Spinnaker\n    properties:\n      - type: Documentation\n        url: https://spinnaker.io/docs/\n      - type: APIDocumentation\n        url: https://spinnaker.io/docs/reference/api/\n      - type: Community\n        url: https://spinnaker.io/docs/community/\n      - type: GitHubOrg\n        url: https://github.com/spinnaker\n\n  - aid: continuous-delivery-foundation:screwdriver\n    name: Screwdriver\n    description: >-\n      Screwdriver is an open-source build platform designed for Continuous\n      Delivery, originally built at Yahoo. It provides a REST API for\n      managing pipelines, builds, jobs, and webhooks and\
  \ is designed to\n      coordinate complex CD workflows across multiple repositories.\n    humanURL: https://screwdriver.cd/\n    tags:\n      - Build\n      - CD\n      - CI/CD\n      - Pipelines\n      - Screwdriver\n    properties:\n      - type: Documentation\n        url: https://docs.screwdriver.cd/\n      - type: APIDocumentation\n        url: https://docs.screwdriver.cd/api/\n      - type: GettingStarted\n        url: https://docs.screwdriver.cd/user-guide/quickstart\n      - type: GitHubOrg\n        url: https://github.com/screwdriver-cd\n\n  - aid: continuous-delivery-foundation:ortelius\n    name: Ortelius\n    description: >-\n      Ortelius is an open source supply chain evidence store that aggregates\n      continuous security intelligence across the software delivery\n      lifecycle. It exposes APIs for tracking microservice components, SBOMs,\n      vulnerabilities, and deployment evidence so platform teams can answer\n      where any component is running and what is in\
  \ it.\n    humanURL: https://ortelius.io/\n    tags:\n      - Evidence Store\n      - SBOM\n      - Supply Chain\n      - Security\n    properties:\n      - type: Documentation\n        url: https://docs.ortelius.io/\n      - type: GettingStarted\n        url: https://docs.ortelius.io/guides/\n      - type: GitHubOrg\n        url: https://github.com/ortelius\n\n  - aid: continuous-delivery-foundation:jayex\n    name: JayeX\n    description: >-\n      JayeX is a customizable cloud developer tool suite hosted by the\n      Continuous Delivery Foundation that provides built-in CI/CD\n      capabilities and developer self-service tooling for cloud-native\n      teams.\n    humanURL: https://jayex.io/\n    tags:\n      - CI/CD\n      - Cloud Native\n      - Developer Tools\n      - Platform\n    properties:\n      - type: Documentation\n        url: https://jayex.io/v3/\n      - type: Community\n        url: https://jayex.io/community/\n\n  - aid: continuous-delivery-foundation:tekton\n   \
  \ name: Tekton\n    description: >-\n      Tekton is a Kubernetes-native open source framework for creating CI/CD\n      systems. It defines Custom Resource Definitions for Pipelines, Tasks,\n      PipelineRuns, and TaskRuns and was originally hosted at the CDF before\n      moving to the Cloud Native Computing Foundation (CNCF). It is included\n      here for historical context with the CDF ecosystem.\n    humanURL: https://tekton.dev/\n    tags:\n      - CI/CD\n      - Kubernetes\n      - Pipelines\n      - Tekton\n    properties:\n      - type: Documentation\n        url: https://tekton.dev/docs/\n      - type: APIDocumentation\n        url: https://tekton.dev/docs/pipelines/api/\n      - type: GitHubOrg\n        url: https://github.com/tektoncd\n\ncommon:\n  - type: Website\n    url: https://cd.foundation/\n  - type: Projects\n    url: https://cd.foundation/projects/\n  - type: Documentation\n    url: https://cd.foundation/projects/\n  - type: Blog\n    url: https://cd.foundation/blog/\n\
  \  - type: Newsroom\n    url: https://cd.foundation/news/\n  - type: GitHubOrg\n    url: https://github.com/cdfoundation\n  - type: Community\n    url: https://cd.foundation/community/\n  - type: Events\n    url: https://cd.foundation/events/\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/continuous-delivery-foundation/refs/heads/main/apis.yml
tags:
- Automation
- CI/CD
- DevOps
- Linux Foundation
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/continuous-delivery-foundation/refs/heads/main/apis.yml
use_cases: []
---
