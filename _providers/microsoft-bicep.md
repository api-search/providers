---
api_count: 4
api_specs:
- filename: microsoft-bicep-deployments-openapi.yml
  format: yaml
  label: Bicep Deployments REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-bicep/refs/heads/main/openapi/microsoft-bicep-deployments-openapi.yml
- filename: microsoft-bicep-template-specs-openapi.yml
  format: yaml
  label: Bicep Template Specs REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-bicep/refs/heads/main/openapi/microsoft-bicep-template-specs-openapi.yml
apis:
- description: Command-line interface for compiling and deploying Bicep files.
  name: Bicep CLI
  slug: ''
- description: Language server implementation for Bicep providing IntelliSense and validation.
  name: Bicep Language Server
  slug: ''
- description: Azure Resource Manager Deployments REST API used by Microsoft Bicep to deploy infrastructure as code templates. Provides operations for creating, validating, and managing ARM/Bicep template deployment
  name: Bicep Deployments REST API
  slug: ''
- description: Azure Resource Manager Template Specs REST API used by Microsoft Bicep for publishing and managing reusable infrastructure templates. Template Specs allow you to store ARM/Bicep templates as Azure res
  name: Bicep Template Specs REST API
  slug: ''
common:
- title: ''
  type: GitHub Organization
  url: https://github.com/Azure
- title: ''
  type: Blog
  url: https://devblogs.microsoft.com/azure-sdk/
- title: ''
  type: Support
  url: https://docs.microsoft.com/en-us/answers/topics/azure-bicep.html
- title: ''
  type: Learning Resources
  url: https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/learn-bicep
- title: ''
  type: Bicep Examples
  url: https://github.com/Azure/bicep/tree/main/docs/examples
- title: ''
  type: Release Notes
  url: https://github.com/Azure/bicep/releases
- title: ''
  type: Contributing Guide
  url: https://github.com/Azure/bicep/blob/main/CONTRIBUTING.md
- title: ''
  type: License
  url: https://github.com/Azure/bicep/blob/main/LICENSE
- title: ''
  type: JSON-LD
  url: json-ld/microsoft-bicep-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/microsoft-bicep-deployment-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/microsoft-bicep-template-spec-schema.json
created: '2024-01-15'
description: Microsoft Bicep is a domain-specific language (DSL) that uses declarative syntax to deploy Azure resources. It provides a transparent abstraction over ARM templates and offers a more concise syntax, improved type safety, and better support for modularity and code reuse.
features: []
image: https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/media/bicep-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Microsoft Bicep Context
  property_count: 9
  slug: microsoft-bicep-context
layout: provider
modified: '2026-04-28'
name: Microsoft Bicep
skills: []
slug: microsoft-bicep
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Microsoft Bicep\ndescription: >-\n  Microsoft Bicep is a domain-specific language (DSL) that uses declarative\n  syntax to deploy Azure resources. It provides a transparent abstraction\n  over ARM templates and offers a more concise syntax, improved type safety,\n  and better support for modularity and code reuse.\nimage: https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/media/bicep-logo.png\nurl: https://github.com/Azure/bicep\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\ntags:\n  - ARM Templates\n  - Azure\n  - Cloud\n  - Deployment\n  - DevOps\n  - Infrastructure as Code\napis:\n  - name: Bicep CLI\n    description: >-\n      Command-line interface for compiling and deploying Bicep files.\n    image: https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/media/bicep-logo.png\n    baseURL: https://github.com/Azure/bicep\n    humanURL: https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/\n      - type: GitHub Repository\n        url: https://github.com/Azure/bicep\n      - type: Installation Guide\n        url: https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/install\n      - type: Bicep Playground\n        url: https://bicepdemo.z22.web.core.windows.net/\n    contact:\n      - type: GitHub Issues\n        url: https://github.com/Azure/bicep/issues\n      - type: Twitter\n        url: https://twitter.com/Azure\n  - name: Bicep Language Server\n    description: >-\n      Language server implementation for Bicep providing IntelliSense and validation.\n    baseURL: https://github.com/Azure/bicep\n    humanURL: https://github.com/Azure/bicep/tree/main/src/Bicep.LangServer\n    properties:\n      - type: Documentation\n        url: https://github.com/Azure/bicep/blob/main/docs/contributing/language-server.md\n      - type: GitHub\
  \ Repository\n        url: https://github.com/Azure/bicep/tree/main/src/Bicep.LangServer\n      - type: VS Code Extension\n        url: https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-bicep\n  - name: Bicep Deployments REST API\n    description: >-\n      Azure Resource Manager Deployments REST API used by Microsoft Bicep\n      to deploy infrastructure as code templates. Provides operations for\n      creating, validating, and managing ARM/Bicep template deployments at\n      resource group, subscription, management group, and tenant scopes.\n    baseURL: https://management.azure.com\n    humanURL: https://learn.microsoft.com/en-us/rest/api/resources/deployments\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/resources/deployments\n      - type: OpenAPI\n        url: openapi/microsoft-bicep-deployments-openapi.yml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/authenticate-multi-tenant\n\
  \  - name: Bicep Template Specs REST API\n    description: >-\n      Azure Resource Manager Template Specs REST API used by Microsoft Bicep\n      for publishing and managing reusable infrastructure templates. Template\n      Specs allow you to store ARM/Bicep templates as Azure resources for\n      versioning, sharing, and access control across your organization.\n    baseURL: https://management.azure.com\n    humanURL: https://learn.microsoft.com/en-us/rest/api/resources/template-specs\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/rest/api/resources/template-specs\n      - type: OpenAPI\n        url: openapi/microsoft-bicep-template-specs-openapi.yml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/authenticate-multi-tenant\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: GitHub Organization\n    url: https://github.com/Azure\n  - type:\
  \ Blog\n    url: https://devblogs.microsoft.com/azure-sdk/\n  - type: Support\n    url: https://docs.microsoft.com/en-us/answers/topics/azure-bicep.html\n  - type: Learning Resources\n    url: https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/learn-bicep\n  - type: Bicep Examples\n    url: https://github.com/Azure/bicep/tree/main/docs/examples\n  - type: Release Notes\n    url: https://github.com/Azure/bicep/releases\n  - type: Contributing Guide\n    url: https://github.com/Azure/bicep/blob/main/CONTRIBUTING.md\n  - type: License\n    url: https://github.com/Azure/bicep/blob/main/LICENSE\n  - type: JSON-LD\n    url: json-ld/microsoft-bicep-context.jsonld\n  - type: JSONSchema\n    url: json-schema/microsoft-bicep-deployment-schema.json\n  - type: JSONSchema\n    url: json-schema/microsoft-bicep-template-spec-schema.json\ninclude:\n  - name: Azure Resource Manager APIs\n    url: https://management.azure.com\n  - name: Azure Template Specs\n    url: https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-specs\n\
  \  - name: Azure Container Registry (for Bicep modules)\n    url: https://azure.microsoft.com/en-us/services/container-registry/\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-bicep/refs/heads/main/apis.yml
tags:
- ARM Templates
- Azure
- Cloud
- Deployment
- DevOps
- Infrastructure as Code
url: https://github.com/Azure/bicep
use_cases: []
---
