---
api_count: 3
api_specs:
- filename: r-metacran-crandb-openapi.yml
  format: yaml
  label: METACRAN CranDB API
  slug: metacran-crandb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/openapi/r-metacran-crandb-openapi.yml
- filename: r-metacran-cranlogs-openapi.yml
  format: yaml
  label: METACRAN CranLogs API
  slug: metacran-cranlogs
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/openapi/r-metacran-cranlogs-openapi.yml
- filename: r-rversions-openapi.yml
  format: yaml
  label: R Versions API
  slug: rversions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/openapi/r-rversions-openapi.yml
apis:
- description: CouchDB-based REST API providing programmatic access to metadata for all CRAN R packages. Supports package lookup, version history, and package dependency data in JSON format.
  name: METACRAN CranDB API
  slug: metacran-crandb
- description: REST API providing download statistics for R packages from the RStudio CRAN mirror. Supports daily, weekly, monthly, and grand-total download counts with badge generation endpoints.
  name: METACRAN CranLogs API
  slug: metacran-cranlogs
- description: REST API that reports the current and previous stable releases of R, including version numbers and release dates. Used by CI tools and package managers to determine supported R versions.
  name: R Versions API
  slug: rversions
capabilities:
- description: R package ecosystem analytics workflow combining METACRAN CranLogs download statistics, CranDB package metadata, and R version information. Used by R package maintainers, data scientists, CI/CD engine
  name: R Package Analytics
  slug: r-package-analytics
common:
- title: ''
  type: Website
  url: https://www.r-project.org/
- title: ''
  type: Documentation
  url: https://cran.r-project.org/manuals.html
- title: ''
  type: GitHubOrg
  url: https://github.com/r-lib
- title: ''
  type: GitHubOrg
  url: https://github.com/r-devel
- title: ''
  type: PackageRegistry
  url: https://cran.r-project.org/
- title: ''
  type: PackageRegistry
  url: https://bioconductor.org/
- title: ''
  type: PackageSearch
  url: https://www.rdocumentation.org/
- title: ''
  type: PackageSearch
  url: https://rdrr.io/
- title: ''
  type: Blog
  url: https://blog.r-project.org/
- title: ''
  type: Forum
  url: https://stat.ethz.ch/mailman/listinfo/r-help
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/r
created: '2025-01-01'
description: R is a free, open-source programming language and statistical computing environment maintained by the R Core Team and supported by the R Foundation. It provides a wide variety of statistical and graphical techniques and is highly extensible through its package ecosystem on CRAN (Comprehensive R Archive Network), Bioconductor, and GitHub. R is widely used among statisticians, data scientists, and researchers for data analysis, visualization, and reproducible research.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 8
  name: R Context
  property_count: 10
  slug: r-context
layout: provider
modified: '2026-05-02'
name: R
rules:
- name: R API Rules
  rule_count: 7
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 6
  slug: r-spectral-rules
skills: []
slug: r
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: r\nname: R\ndescription: >-\n  R is a free, open-source programming language and statistical computing\n  environment maintained by the R Core Team and supported by the R Foundation.\n  It provides a wide variety of statistical and graphical techniques and is\n  highly extensible through its package ecosystem on CRAN (Comprehensive R\n  Archive Network), Bioconductor, and GitHub. R is widely used among\n  statisticians, data scientists, and researchers for data analysis,\n  visualization, and reproducible research.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/apis.yml\ntags:\n  - R\n  - Statistics\n  - Data Science\n  - Open Source\n  - Programming Language\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: r:metacran-crandb\n    name: METACRAN CranDB API\n    description: >-\n      CouchDB-based REST API\
  \ providing programmatic access to metadata for all\n      CRAN R packages. Supports package lookup, version history, and package\n      dependency data in JSON format.\n    humanURL: https://github.com/metacran/crandb\n    baseURL: https://crandb.r-pkg.org\n    tags:\n      - CRAN\n      - Packages\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://github.com/metacran/crandb\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/openapi/r-metacran-crandb-openapi.yml\n  - aid: r:metacran-cranlogs\n    name: METACRAN CranLogs API\n    description: >-\n      REST API providing download statistics for R packages from the RStudio\n      CRAN mirror. Supports daily, weekly, monthly, and grand-total download\n      counts with badge generation endpoints.\n    humanURL: https://github.com/metacran/cranlogs.app\n    baseURL: https://cranlogs.r-pkg.org\n    tags:\n      - CRAN\n      - Downloads\n      - Statistics\n\
  \    properties:\n      - type: Documentation\n        url: https://github.com/metacran/cranlogs.app\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/openapi/r-metacran-cranlogs-openapi.yml\n  - aid: r:rversions\n    name: R Versions API\n    description: >-\n      REST API that reports the current and previous stable releases of R,\n      including version numbers and release dates. Used by CI tools and package\n      managers to determine supported R versions.\n    humanURL: https://github.com/metacran/rversions.app\n    baseURL: https://rversions.r-pkg.org\n    tags:\n      - R\n      - Versions\n      - Releases\n    properties:\n      - type: Documentation\n        url: https://github.com/metacran/rversions.app\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/openapi/r-rversions-openapi.yml\ncommon:\n  - type: Website\n    url: https://www.r-project.org/\n  - type: Documentation\n\
  \    url: https://cran.r-project.org/manuals.html\n  - type: GitHubOrg\n    url: https://github.com/r-lib\n  - type: GitHubOrg\n    url: https://github.com/r-devel\n  - type: PackageRegistry\n    url: https://cran.r-project.org/\n  - type: PackageRegistry\n    url: https://bioconductor.org/\n  - type: PackageSearch\n    url: https://www.rdocumentation.org/\n  - type: PackageSearch\n    url: https://rdrr.io/\n  - type: Blog\n    url: https://blog.r-project.org/\n  - type: Forum\n    url: https://stat.ethz.ch/mailman/listinfo/r-help\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/r\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/apis.yml
tags:
- R
- Statistics
- Data Science
- Open Source
- Programming Language
url: https://raw.githubusercontent.com/api-evangelist/r/refs/heads/main/apis.yml
use_cases: []
---
