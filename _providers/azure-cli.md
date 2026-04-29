---
api_count: 1
apis:
- description: Azure CLI is the official cross-platform command-line tool for managing Microsoft Azure resources and services from the terminal.
  name: Azure CLI
  slug: azure-cli
common:
- title: ''
  type: Website
  url: https://learn.microsoft.com/en-us/cli/azure/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/cli/azure/get-started-with-azure-cli
- title: ''
  type: GitHubRepository
  url: https://github.com/Azure/azure-cli
- title: ''
  type: GettingStarted
  url: https://learn.microsoft.com/en-us/cli/azure/get-started-with-azure-cli
- title: ''
  type: ChangeLog
  url: https://learn.microsoft.com/en-us/cli/azure/release-notes-azure-cli
created: '2026-03-25'
description: Azure CLI is the official cross-platform command-line tool for managing Microsoft Azure resources and services from the terminal.
features:
- description: Runs on Windows, macOS, and Linux with identical command syntax.
  name: Cross-Platform Support
- description: Interactive shell with auto-complete and inline help for command discovery.
  name: Interactive Mode
- description: Output as JSON, YAML, table, or TSV for pipeline integration.
  name: Multiple Output Formats
- description: Filter and transform output with JMESPath query language using --query.
  name: JMESPath Querying
- description: Run Azure CLI in the browser via Azure Cloud Shell without local installation.
  name: Azure Cloud Shell
- description: Embed Azure CLI commands in Bash and PowerShell automation scripts.
  name: Bash Scripting Integration
- description: Extend CLI functionality with official and community extensions.
  name: Extension Support
- description: Authenticate with service principals for automated/non-interactive scenarios.
  name: Service Principal Auth
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Use Azure CLI in Azure DevOps pipelines with the AzureCLI task.
  name: Azure DevOps
- description: Authenticate and run Azure CLI commands in GitHub Actions workflows.
  name: GitHub Actions
- description: Complement Terraform with Azure CLI for tasks outside the Terraform provider.
  name: Terraform
- description: Access a pre-configured Azure CLI environment via browser.
  name: Azure Cloud Shell
- description: Integrated terminal support and Azure CLI extension for Visual Studio Code.
  name: VS Code
layout: provider
modified: '2026-04-19'
name: Azure CLI
skills: []
slug: azure-cli
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: azure-cli\nname: Azure CLI\ndescription: >-\n  Azure CLI is the official cross-platform command-line tool for managing Microsoft\n  Azure resources and services from the terminal.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- Cloud Provider CLI\n- Command Line Interface\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/azure-cli/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: azure-cli:azure-cli\n  name: Azure CLI\n  description: >-\n    Azure CLI is the official cross-platform command-line tool for managing Microsoft\n    Azure resources and services from the terminal.\n  humanURL: https://learn.microsoft.com/en-us/cli/azure/\n  tags:\n  - Cloud Provider CLI\n  - Command Line Interface\n  properties:\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/cli/azure/get-started-with-azure-cli\n  - type: GitHubRepository\n\
  \    url: https://github.com/Azure/azure-cli\ncommon:\n- type: Website\n  url: https://learn.microsoft.com/en-us/cli/azure/\n- type: Documentation\n  url: https://learn.microsoft.com/en-us/cli/azure/get-started-with-azure-cli\n- type: GitHubRepository\n  url: https://github.com/Azure/azure-cli\n- type: GettingStarted\n  url: https://learn.microsoft.com/en-us/cli/azure/get-started-with-azure-cli\n- type: ChangeLog\n  url: https://learn.microsoft.com/en-us/cli/azure/release-notes-azure-cli\n- type: Features\n  data:\n  - name: Cross-Platform Support\n    description: Runs on Windows, macOS, and Linux with identical command \n      syntax.\n  - name: Interactive Mode\n    description: Interactive shell with auto-complete and inline help for \n      command discovery.\n  - name: Multiple Output Formats\n    description: Output as JSON, YAML, table, or TSV for pipeline integration.\n  - name: JMESPath Querying\n    description: Filter and transform output with JMESPath query language using\
  \ \n      --query.\n  - name: Azure Cloud Shell\n    description: Run Azure CLI in the browser via Azure Cloud Shell without \n      local installation.\n  - name: Bash Scripting Integration\n    description: Embed Azure CLI commands in Bash and PowerShell automation \n      scripts.\n  - name: Extension Support\n    description: Extend CLI functionality with official and community \n      extensions.\n  - name: Service Principal Auth\n    description: Authenticate with service principals for \n      automated/non-interactive scenarios.\n- type: UseCases\n  data:\n  - name: Resource Provisioning\n    description: Provision Azure resources like VMs, storage accounts, and \n      databases from the command line.\n  - name: DevOps Automation\n    description: Automate Azure infrastructure tasks in CI/CD pipelines and \n      deployment scripts.\n  - name: Monitoring and Diagnostics\n    description: Query resource metrics, logs, and health status from the \n      terminal.\n  - name: Batch\
  \ Operations\n    description: Perform bulk operations across multiple Azure resources in a \n      single script.\n  - name: Infrastructure as Code\n    description: Complement Terraform and Bicep with scripted Azure CLI \n      commands.\n- type: Integrations\n  data:\n  - name: Azure DevOps\n    description: Use Azure CLI in Azure DevOps pipelines with the AzureCLI task.\n  - name: GitHub Actions\n    description: Authenticate and run Azure CLI commands in GitHub Actions \n      workflows.\n  - name: Terraform\n    description: Complement Terraform with Azure CLI for tasks outside the \n      Terraform provider.\n  - name: Azure Cloud Shell\n    description: Access a pre-configured Azure CLI environment via browser.\n  - name: VS Code\n    description: Integrated terminal support and Azure CLI extension for Visual \n      Studio Code.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/azure-cli/refs/heads/main/apis.yml
tags:
- Cloud Provider CLI
- Command Line Interface
url: https://raw.githubusercontent.com/api-evangelist/azure-cli/refs/heads/main/apis.yml
use_cases:
- description: Provision Azure resources like VMs, storage accounts, and databases from the command line.
  name: Resource Provisioning
- description: Automate Azure infrastructure tasks in CI/CD pipelines and deployment scripts.
  name: DevOps Automation
- description: Query resource metrics, logs, and health status from the terminal.
  name: Monitoring and Diagnostics
- description: Perform bulk operations across multiple Azure resources in a single script.
  name: Batch Operations
- description: Complement Terraform and Bicep with scripted Azure CLI commands.
  name: Infrastructure as Code
---
