---
api_count: 12
apis:
- description: Zowe is an open source software framework that delivers modern interfaces to interact with z/OS, including a CLI, a web UI (Application Framework), and REST APIs (API Mediation Layer) for jobs, datase
  name: Zowe
  slug: zowe
- description: Feilong is an open source z/VM cloud connector that exposes z/VM functions as REST APIs to accelerate z/VM adoption and enable integration with modern cloud automation tooling.
  name: Feilong
  slug: feilong
- description: Galasa is an open source deep integration test framework able to run tests across z/OS, distributed systems, and cloud platforms, with REST APIs for managing test runs and resources.
  name: Galasa
  slug: galasa
- description: Tessia automates the installation, configuration, and testing of Linux systems running on the IBM Z platform, exposing a REST API for managing systems, networks, and provisioning workflows.
  name: Tessia
  slug: tessia
- description: GenevaERS is a single-pass optimization engine for high-volume data extraction, transformation, and reporting on z/OS, used to consolidate large-scale mainframe analytics workloads.
  name: GenevaERS
  slug: genevaers
- description: COBOL Check is a unit testing framework for COBOL that enables test-driven development for mainframe code with assertion-based tests runnable from CI pipelines.
  name: COBOL Check
  slug: cobol-check
- description: zopen is a community-driven catalog and build framework that ports and packages popular open source tools for z/OS, expanding the open source tool surface available to mainframe developers.
  name: zopen Community
  slug: zopen-community
- description: Ambitus fosters a community focused on educating developers about open source technologies running on z/OS and Linux on Z, including curated tutorials and learning paths.
  name: Ambitus
  slug: ambitus
- description: CBT Tape is a long-running open library of free software distributions for IBM mainframe MVS, OS/390, and z/OS environments.
  name: CBT Tape
  slug: cbt-tape
- description: An open educational initiative offering structured COBOL learning materials alongside contemporary tooling such as VS Code, Zowe CLI, and Git for modern mainframe development workflows.
  name: COBOL Programming Course
  slug: cobol-programming-course
- description: Software Discovery Tool helps match developer requirements with available open source software tested on the IBM Z platform.
  name: Software Discovery Tool
  slug: software-discovery-tool
- description: Mainframe Open Education is a community for newcomers and experienced mainframe practitioners, sharing learning resources, mentoring guidance, and skills programs.
  name: Mainframe Open Education
  slug: mainframe-open-education
common:
- title: ''
  type: Website
  url: https://www.openmainframeproject.org/
- title: ''
  type: All Projects
  url: https://www.openmainframeproject.org/all-projects
- title: ''
  type: Documentation
  url: https://www.openmainframeproject.org/projects
- title: ''
  type: GitHub Organization
  url: https://github.com/openmainframeproject
- title: ''
  type: Blog
  url: https://www.openmainframeproject.org/blog
- title: ''
  type: Events
  url: https://www.openmainframeproject.org/events
- title: ''
  type: Membership
  url: https://www.openmainframeproject.org/about/members
- title: ''
  type: Linux Foundation
  url: https://www.linuxfoundation.org/projects/open-mainframe/
created: '2026-03-16'
description: The Open Mainframe Project is a Linux Foundation project encouraging the use of Linux-based operating systems and open source software on mainframe computers. Founded in 2015 with IBM, it hosts projects such as Zowe (modern interfaces for z/OS), Feilong (z/VM cloud connector), Galasa (testing), and a range of community programs that promote mainframe skills and open source on IBM Z and LinuxONE platforms.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Open Mainframe Project
skills: []
slug: open-mainframe-project
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: open-mainframe-project\nname: Open Mainframe Project\ndescription: >-\n  The Open Mainframe Project is a Linux Foundation project encouraging the use\n  of Linux-based operating systems and open source software on mainframe\n  computers. Founded in 2015 with IBM, it hosts projects such as Zowe (modern\n  interfaces for z/OS), Feilong (z/VM cloud connector), Galasa (testing), and a\n  range of community programs that promote mainframe skills and open source on\n  IBM Z and LinuxONE platforms.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Education\n  - Enterprise\n  - IBM Z\n  - Linux Foundation\n  - Linux on Z\n  - Mainframe\n  - Open Source\n  - z/OS\n  - z/VM\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/open-mainframe-project/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: open-mainframe-project:zowe\n    name: Zowe\n    description: >-\n      Zowe is an open source software framework that delivers modern interfaces\n      to interact with z/OS, including a CLI, a web UI (Application Framework),\n      and REST APIs (API Mediation Layer) for jobs, datasets, USS files, and\n      system management.\n    humanURL: https://www.zowe.org/\n    tags:\n      - API Mediation\n      - CLI\n      - Mainframe\n      - REST APIs\n      - z/OS\n    properties:\n      - type: Documentation\n        url: https://docs.zowe.org/\n      - type: GitHub Organization\n        url: https://github.com/zowe\n  - aid: open-mainframe-project:feilong\n    name: Feilong\n    description: >-\n      Feilong is an open source z/VM cloud connector that exposes z/VM functions\n      as REST APIs to accelerate z/VM adoption and enable integration with\n      modern cloud automation tooling.\n    humanURL: https://www.openmainframeproject.org/projects/feilong\n    tags:\n      -\
  \ Cloud Connector\n      - REST APIs\n      - z/VM\n    properties:\n      - type: Documentation\n        url: https://cloudlib4zvm.readthedocs.io/\n      - type: GitHub Repository\n        url: https://github.com/openmainframeproject/feilong\n  - aid: open-mainframe-project:galasa\n    name: Galasa\n    description: >-\n      Galasa is an open source deep integration test framework able to run\n      tests across z/OS, distributed systems, and cloud platforms, with REST\n      APIs for managing test runs and resources.\n    humanURL: https://galasa.dev/\n    tags:\n      - Integration Testing\n      - Mainframe\n      - Test Automation\n    properties:\n      - type: Documentation\n        url: https://galasa.dev/docs/\n      - type: GitHub Organization\n        url: https://github.com/galasa-dev\n  - aid: open-mainframe-project:tessia\n    name: Tessia\n    description: >-\n      Tessia automates the installation, configuration, and testing of Linux\n      systems running on the IBM\
  \ Z platform, exposing a REST API for managing\n      systems, networks, and provisioning workflows.\n    humanURL: https://gitlab.com/tessia-project\n    tags:\n      - Automation\n      - Linux on Z\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://gitlab.com/tessia-project/tessia/-/blob/master/README.md\n      - type: GitLab Repository\n        url: https://gitlab.com/tessia-project/tessia\n  - aid: open-mainframe-project:genevaers\n    name: GenevaERS\n    description: >-\n      GenevaERS is a single-pass optimization engine for high-volume data\n      extraction, transformation, and reporting on z/OS, used to consolidate\n      large-scale mainframe analytics workloads.\n    humanURL: https://www.openmainframeproject.org/projects/genevaers\n    tags:\n      - Analytics\n      - Data Extraction\n      - z/OS\n    properties:\n      - type: Documentation\n        url: https://genevaers.org/\n      - type: GitHub Organization\n        url: https://github.com/genevaers\n\
  \  - aid: open-mainframe-project:cobol-check\n    name: COBOL Check\n    description: >-\n      COBOL Check is a unit testing framework for COBOL that enables\n      test-driven development for mainframe code with assertion-based tests\n      runnable from CI pipelines.\n    humanURL: https://www.openmainframeproject.org/projects/cobol-check\n    tags:\n      - COBOL\n      - Testing\n      - TDD\n    properties:\n      - type: GitHub Repository\n        url: https://github.com/openmainframeproject/cobol-check\n  - aid: open-mainframe-project:zopen-community\n    name: zopen Community\n    description: >-\n      zopen is a community-driven catalog and build framework that ports and\n      packages popular open source tools for z/OS, expanding the open source\n      tool surface available to mainframe developers.\n    humanURL: https://zopen.community/\n    tags:\n      - Open Source\n      - Package Management\n      - z/OS\n    properties:\n      - type: Documentation\n        url: https://zopen.community/\n\
  \      - type: GitHub Organization\n        url: https://github.com/zopencommunity\n  - aid: open-mainframe-project:ambitus\n    name: Ambitus\n    description: >-\n      Ambitus fosters a community focused on educating developers about open\n      source technologies running on z/OS and Linux on Z, including curated\n      tutorials and learning paths.\n    humanURL: https://www.openmainframeproject.org/projects/ambitus\n    tags:\n      - Community\n      - Education\n      - Linux on Z\n      - z/OS\n    properties:\n      - type: GitHub Organization\n        url: https://github.com/ambitus\n  - aid: open-mainframe-project:cbt-tape\n    name: CBT Tape\n    description: >-\n      CBT Tape is a long-running open library of free software distributions\n      for IBM mainframe MVS, OS/390, and z/OS environments.\n    humanURL: https://www.cbttape.org/\n    tags:\n      - Mainframe\n      - MVS\n      - Software Library\n      - z/OS\n    properties:\n      - type: Documentation\n      \
  \  url: https://www.cbttape.org/\n  - aid: open-mainframe-project:cobol-programming-course\n    name: COBOL Programming Course\n    description: >-\n      An open educational initiative offering structured COBOL learning\n      materials alongside contemporary tooling such as VS Code, Zowe CLI, and\n      Git for modern mainframe development workflows.\n    humanURL: https://github.com/openmainframeproject/cobol-programming-course\n    tags:\n      - COBOL\n      - Education\n      - Training\n    properties:\n      - type: GitHub Repository\n        url: https://github.com/openmainframeproject/cobol-programming-course\n  - aid: open-mainframe-project:software-discovery-tool\n    name: Software Discovery Tool\n    description: >-\n      Software Discovery Tool helps match developer requirements with available\n      open source software tested on the IBM Z platform.\n    humanURL: https://www.openmainframeproject.org/projects/software-discovery-tool\n    tags:\n      - Discovery\n    \
  \  - IBM Z\n      - Open Source\n    properties:\n      - type: GitHub Repository\n        url: https://github.com/openmainframeproject/software-discovery-tool\n  - aid: open-mainframe-project:mainframe-open-education\n    name: Mainframe Open Education\n    description: >-\n      Mainframe Open Education is a community for newcomers and experienced\n      mainframe practitioners, sharing learning resources, mentoring guidance,\n      and skills programs.\n    humanURL: https://www.openmainframeproject.org/projects/mainframe-open-education\n    tags:\n      - Community\n      - Education\n      - Mentorship\n    properties:\n      - type: Documentation\n        url: https://www.openmainframeproject.org/projects/mainframe-open-education\ncommon:\n  - type: Website\n    url: https://www.openmainframeproject.org/\n  - type: All Projects\n    url: https://www.openmainframeproject.org/all-projects\n  - type: Documentation\n    url: https://www.openmainframeproject.org/projects\n  - type: GitHub\
  \ Organization\n    url: https://github.com/openmainframeproject\n  - type: Blog\n    url: https://www.openmainframeproject.org/blog\n  - type: Events\n    url: https://www.openmainframeproject.org/events\n  - type: Membership\n    url: https://www.openmainframeproject.org/about/members\n  - type: Linux Foundation\n    url: https://www.linuxfoundation.org/projects/open-mainframe/\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/open-mainframe-project/refs/heads/main/apis.yml
tags:
- Cloud Native
- Education
- Enterprise
- IBM Z
- Linux Foundation
- Linux on Z
- Mainframe
- Open Source
- z/OS
- z/VM
url: https://raw.githubusercontent.com/api-evangelist/open-mainframe-project/refs/heads/main/apis.yml
use_cases: []
---
