---
api_count: 4
apis:
- description: An open source guide that distills decades of CLI design wisdom into concrete, actionable guidelines. Authored by engineers from Docker, Squarespace, and others, it covers philosophy, arguments and fl
  name: Command Line Interface Guidelines
  slug: design-guidelines
- description: 'The POSIX Utility Conventions specify the expected behavior of command line utilities including argument parsing, flag styles, end-of-options separators, and exit status. Following POSIX makes a tool '
  name: POSIX Utility Conventions
  slug: posix-utility-conventions
- description: 'A survey of widely adopted CLI frameworks across programming language ecosystems. These libraries handle argument parsing, subcommand routing, flag validation, help text generation, shell completion, '
  name: CLI Frameworks Landscape
  slug: cli-frameworks
- description: Heroku's internal style guide for CLI design, made public to share their lessons in building a polished developer experience. Covers naming, output, error handling, JSON output, and progressive disclo
  name: Heroku CLI Style Guide
  slug: heroku-cli-style-guide
common:
- title: ''
  type: Website
  url: https://clig.dev/
- title: ''
  type: Documentation
  url: https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/V1_chap12.html
- title: ''
  type: Reference
  url: https://en.wikipedia.org/wiki/Command-line_interface
- title: ''
  type: Guide
  url: https://devcenter.heroku.com/articles/cli-style-guide
- title: ''
  type: Resources
  url: https://github.com/agarrharr/awesome-cli-apps
created: '2025-01-01'
description: Command Line Interface (CLI) is a text-based way of interacting with software by typing commands at a prompt. Modern CLI design draws on decades of UNIX conventions while incorporating contemporary practices around discoverability, human-friendly output, machine-readable formats, configuration, subcommands, and progressive disclosure of complexity. CLIs remain a central surface for developer tools, infrastructure automation, package managers, build systems, and anything that benefits from scripting and composition.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Command Line Interface
skills: []
slug: command-line-interface
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: command-line-interface\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/command-line-interface/refs/heads/main/apis.yml\nname: Command Line Interface\nx-type: topic\ndescription: >-\n  Command Line Interface (CLI) is a text-based way of interacting with software\n  by typing commands at a prompt. Modern CLI design draws on decades of UNIX\n  conventions while incorporating contemporary practices around discoverability,\n  human-friendly output, machine-readable formats, configuration, subcommands,\n  and progressive disclosure of complexity. CLIs remain a central surface for\n  developer tools, infrastructure automation, package managers, build systems,\n  and anything that benefits from scripting and composition.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - CLI\n  - Command Line\n  - Developer Experience\n  - Developer Tools\n  - Scripting\n  - Shell\n  - Terminal\n  - Tooling\n  - UNIX\ncreated:\
  \ '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: command-line-interface:design-guidelines\n    name: Command Line Interface Guidelines\n    description: >-\n      An open source guide that distills decades of CLI design wisdom into\n      concrete, actionable guidelines. Authored by engineers from Docker,\n      Squarespace, and others, it covers philosophy, arguments and flags,\n      output, errors, help, configuration, subcommands, and interactivity.\n      A practical reference for designing modern command line tools.\n    humanURL: https://clig.dev/\n    baseURL: https://clig.dev\n    tags:\n      - Best Practices\n      - CLI Design\n      - Developer Experience\n      - Guidelines\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://clig.dev/\n      - type: GitHubRepository\n        url: https://github.com/cli-guidelines/cli-guidelines\n      - type: License\n        url: https://creativecommons.org/licenses/by-sa/4.0/\n\
  \    x-features:\n      - Codifies nine high-level design principles for human-first CLIs\n      - Covers arguments, flags, subcommands, help, configuration, output, and errors\n      - Provides language-agnostic guidance applicable across ecosystems\n      - Open source under Creative Commons license, accepting community contributions\n      - Distinguishes human-readable from machine-readable output modes\n    x-useCases:\n      - Reviewing existing CLI tools against an industry-recognized rubric\n      - Bootstrapping a CLI design style guide for a new product or platform\n      - Educating teams on CLI conventions like POSIX flags and subcommands\n      - Justifying UX decisions in code reviews of CLI changes\n  - aid: command-line-interface:posix-utility-conventions\n    name: POSIX Utility Conventions\n    description: >-\n      The POSIX Utility Conventions specify the expected behavior of command\n      line utilities including argument parsing, flag styles, end-of-options\n  \
  \    separators, and exit status. Following POSIX makes a tool feel native\n      to UNIX-like environments and predictable when composed in pipelines\n      and shell scripts.\n    humanURL: https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/V1_chap12.html\n    baseURL: https://pubs.opengroup.org\n    tags:\n      - Conventions\n      - POSIX\n      - Standards\n      - UNIX\n    properties:\n      - type: Specification\n        url: https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/V1_chap12.html\n      - type: Reference\n        url: https://www.gnu.org/software/libc/manual/html_node/Argument-Syntax.html\n    x-features:\n      - Defines short flags, long flags, and option arguments\n      - Specifies the `--` end-of-options sentinel\n      - Standardizes exit status conventions\n      - Foundation for getopt and getopts utilities\n    x-useCases:\n      - Writing portable CLI utilities for UNIX-like systems\n      - Implementing argument parsers that match user expectations\n\
  \      - Documenting tool behavior in man pages\n  - aid: command-line-interface:cli-frameworks\n    name: CLI Frameworks Landscape\n    description: >-\n      A survey of widely adopted CLI frameworks across programming language\n      ecosystems. These libraries handle argument parsing, subcommand routing,\n      flag validation, help text generation, shell completion, and other\n      cross-cutting concerns so developers can focus on the actual command\n      logic.\n    humanURL: https://github.com/agarrharr/awesome-cli-apps\n    baseURL: https://github.com\n    tags:\n      - Frameworks\n      - Libraries\n      - Open Source\n      - Tooling\n    properties:\n      - type: Reference\n        url: https://github.com/spf13/cobra\n      - type: Reference\n        url: https://github.com/click-contrib\n      - type: Reference\n        url: https://oclif.io/\n      - type: Reference\n        url: https://github.com/tj/commander.js\n      - type: Reference\n        url: https://github.com/yargs/yargs\n\
  \      - type: Reference\n        url: https://docs.python.org/3/library/argparse.html\n      - type: Reference\n        url: https://github.com/clap-rs/clap\n    x-features:\n      - Cobra (Go) used by kubectl, hugo, gh, and many CNCF projects\n      - Click (Python) provides decorator-based command definition\n      - oclif (Node.js) used by Heroku, Salesforce, and Adobe CLIs\n      - Commander.js and yargs are popular in the Node.js ecosystem\n      - clap (Rust) provides derive macros for ergonomic argument parsing\n      - argparse ships in the Python standard library\n    x-useCases:\n      - Selecting an argument parsing library for a new CLI project\n      - Generating shell completion scripts for bash, zsh, and fish\n      - Standardizing CLI structure across a portfolio of internal tools\n      - Adding subcommands and nested command trees to an existing CLI\n  - aid: command-line-interface:heroku-cli-style-guide\n    name: Heroku CLI Style Guide\n    description: >-\n      Heroku's\
  \ internal style guide for CLI design, made public to share their\n      lessons in building a polished developer experience. Covers naming,\n      output, error handling, JSON output, and progressive disclosure of\n      power-user features.\n    humanURL: https://devcenter.heroku.com/articles/cli-style-guide\n    baseURL: https://devcenter.heroku.com\n    tags:\n      - Best Practices\n      - Developer Experience\n      - Heroku\n      - Style Guide\n    properties:\n      - type: Documentation\n        url: https://devcenter.heroku.com/articles/cli-style-guide\n    x-features:\n      - Real-world style guide from a CLI-first developer platform\n      - Covers naming, output, errors, and machine-readable formats\n      - Aligns with broader CLI Guidelines philosophy\n    x-useCases:\n      - Establishing tone and output conventions for a new CLI\n      - Comparing alternative approaches to error reporting and progress\ncommon:\n  - type: Website\n    url: https://clig.dev/\n  - type:\
  \ Documentation\n    url: https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/V1_chap12.html\n  - type: Reference\n    url: https://en.wikipedia.org/wiki/Command-line_interface\n  - type: Guide\n    url: https://devcenter.heroku.com/articles/cli-style-guide\n  - type: Resources\n    url: https://github.com/agarrharr/awesome-cli-apps\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/command-line-interface/refs/heads/main/apis.yml
tags:
- Automation
- CLI
- Command Line
- Developer Experience
- Developer Tools
- Scripting
- Shell
- Terminal
- Tooling
- UNIX
url: https://raw.githubusercontent.com/api-evangelist/command-line-interface/refs/heads/main/apis.yml
use_cases: []
---
