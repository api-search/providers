---
api_count: 9
apis:
- description: YAML Ain't Markup Language is a human-friendly data serialization language. YAML 1.2 is widely used for configuration in Kubernetes, OpenAPI, GitHub Actions, Ansible, and many other ecosystems. YAML s
  name: YAML
  slug: yaml
- description: JavaScript Object Notation is a lightweight data interchange format defined by RFC 8259 and ECMA-404. JSON is heavily used as a configuration format in Node.js (package.json), VS Code settings, and ma
  name: JSON
  slug: json
- description: Tom's Obvious, Minimal Language is a config file format designed to be human-readable and unambiguous. TOML is used by Cargo for Rust projects, Python packaging via pyproject.toml, and Hugo site confi
  name: TOML
  slug: toml
- description: HashiCorp Configuration Language is a structured configuration language designed for human authoring of complex configurations. HCL underpins Terraform, Packer, Vault, Consul, and Nomad and supports e
  name: HCL
  slug: hcl
- description: Cue is an open source data validation language with a powerful type system and unification semantics. Cue is used to validate, generate, and transform configuration for Kubernetes, OpenAPI, and Terraf
  name: Cue
  slug: cue
- description: Dhall is a programmable configuration language that adds types and functions to JSON and YAML. Dhall expressions are total (always terminate) and remote imports are content-addressed for safety.
  name: Dhall
  slug: dhall
- description: Pkl is Apple's open source configuration language with a focus on type safety, composition, and runtime templating. Pkl can render to YAML, JSON, plist, and other formats and offers IDE tooling and la
  name: Pkl
  slug: pkl
- description: Jsonnet is a data templating language designed for elegant generation of JSON and YAML. It is used heavily for Kubernetes manifests, Grafana dashboards (Grafonnet), and Bazel-based tooling.
  name: Jsonnet
  slug: jsonnet
- description: KDL is a node-oriented document language combining the readability of YAML and TOML with a unique tree-shaped grammar. KDL is used by Zellij, Helix, and other tools.
  name: KDL
  slug: kdl
common:
- title: ''
  type: Reference
  url: https://en.wikipedia.org/wiki/Configuration_file
- title: ''
  type: Reference
  url: https://docs.kernel.org/admin-guide/configuration.html
- title: ''
  type: Resources
  url: https://github.com/avelino/awesome-go#configuration
- title: ''
  type: Reference
  url: https://json-schema.org/
created: '2025-01-01'
description: Configuration languages are formats and DSLs used to express the desired state of software systems, infrastructure, applications, and APIs. Configuration languages span a spectrum from simple text-based formats (INI, JSON, YAML, TOML) to typed and templated formats (HCL, Cue, Dhall, Pkl, Jsonnet, KDL) that support imports, schemas, and validation. The choice of configuration language shapes how teams describe Kubernetes manifests, Terraform infrastructure, OpenAPI specs, CI pipelines, and developer environments.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Configuration Language
skills: []
slug: configuration-language
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: configuration-language\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/configuration-language/refs/heads/main/apis.yml\nname: Configuration Language\nx-type: topic\ndescription: >-\n  Configuration languages are formats and DSLs used to express the desired\n  state of software systems, infrastructure, applications, and APIs.\n  Configuration languages span a spectrum from simple text-based formats\n  (INI, JSON, YAML, TOML) to typed and templated formats (HCL, Cue, Dhall,\n  Pkl, Jsonnet, KDL) that support imports, schemas, and validation. The\n  choice of configuration language shapes how teams describe Kubernetes\n  manifests, Terraform infrastructure, OpenAPI specs, CI pipelines, and\n  developer environments.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Configuration\n  - DSL\n  - Infrastructure as Code\n  - Schemas\n  - Serialization\n  - Templating\n  - YAML\ncreated: '2025-01-01'\nmodified: '2026-04-28'\n\
  specificationVersion: '0.19'\napis:\n  - aid: configuration-language:yaml\n    name: YAML\n    description: >-\n      YAML Ain't Markup Language is a human-friendly data serialization\n      language. YAML 1.2 is widely used for configuration in Kubernetes,\n      OpenAPI, GitHub Actions, Ansible, and many other ecosystems. YAML\n      supports comments, scalars, sequences, mappings, anchors, and tags.\n    humanURL: https://yaml.org/\n    baseURL: https://yaml.org\n    tags:\n      - Human Readable\n      - Serialization\n      - Standards\n      - YAML\n    properties:\n      - type: Specification\n        url: https://yaml.org/spec/1.2.2/\n      - type: Documentation\n        url: https://yaml.org/\n      - type: Reference\n        url: https://github.com/yaml/yaml-spec\n    x-features:\n      - Indentation-based syntax with comments\n      - Anchors and aliases for reuse\n      - Schemas (failsafe, JSON, core)\n      - Used by Kubernetes, OpenAPI, Ansible, GitHub Actions\n  - aid:\
  \ configuration-language:json\n    name: JSON\n    description: >-\n      JavaScript Object Notation is a lightweight data interchange format\n      defined by RFC 8259 and ECMA-404. JSON is heavily used as a\n      configuration format in Node.js (package.json), VS Code settings,\n      and many other tools, and is the foundation for JSON Schema-based\n      validation.\n    humanURL: https://www.json.org/\n    baseURL: https://www.json.org\n    tags:\n      - ECMA\n      - IETF\n      - Interchange\n      - JSON\n    properties:\n      - type: Specification\n        url: https://www.rfc-editor.org/rfc/rfc8259\n      - type: Specification\n        url: https://www.ecma-international.org/publications-and-standards/standards/ecma-404/\n      - type: Reference\n        url: https://json-schema.org/\n    x-features:\n      - Strict, simple, well-supported across languages\n      - JSON Schema for validation\n      - No native comments (mitigated by JSON5, JSONC)\n  - aid: configuration-language:toml\n\
  \    name: TOML\n    description: >-\n      Tom's Obvious, Minimal Language is a config file format designed to\n      be human-readable and unambiguous. TOML is used by Cargo for Rust\n      projects, Python packaging via pyproject.toml, and Hugo site config.\n    humanURL: https://toml.io/\n    baseURL: https://toml.io\n    tags:\n      - Configuration\n      - Human Readable\n      - TOML\n    properties:\n      - type: Specification\n        url: https://toml.io/en/v1.0.0\n      - type: GitHubRepository\n        url: https://github.com/toml-lang/toml\n    x-features:\n      - Strong typing with dates, integers, floats, booleans, arrays\n      - Tables and inline tables\n      - Used by Cargo (Rust) and pyproject.toml (Python)\n  - aid: configuration-language:hcl\n    name: HCL\n    description: >-\n      HashiCorp Configuration Language is a structured configuration\n      language designed for human authoring of complex configurations.\n      HCL underpins Terraform, Packer, Vault,\
  \ Consul, and Nomad and\n      supports expressions, variables, functions, and blocks.\n    humanURL: https://github.com/hashicorp/hcl\n    baseURL: https://github.com\n    tags:\n      - HCL\n      - HashiCorp\n      - Infrastructure as Code\n      - Terraform\n    properties:\n      - type: GitHubRepository\n        url: https://github.com/hashicorp/hcl\n      - type: Documentation\n        url: https://developer.hashicorp.com/terraform/language\n    x-features:\n      - Block-and-attribute syntax with native expressions\n      - JSON-equivalent representation\n      - Variables, locals, and functions\n      - Foundation of Terraform infrastructure code\n  - aid: configuration-language:cue\n    name: Cue\n    description: >-\n      Cue is an open source data validation language with a powerful type\n      system and unification semantics. Cue is used to validate, generate,\n      and transform configuration for Kubernetes, OpenAPI, and Terraform.\n    humanURL: https://cuelang.org/\n\
  \    baseURL: https://cuelang.org\n    tags:\n      - Cue\n      - Schema\n      - Type System\n      - Validation\n    properties:\n      - type: Documentation\n        url: https://cuelang.org/docs/\n      - type: GitHubRepository\n        url: https://github.com/cue-lang/cue\n    x-features:\n      - Types and values are unified\n      - First-class schemas with constraints\n      - Importable, composable definitions\n      - Code generation and validation tooling\n  - aid: configuration-language:dhall\n    name: Dhall\n    description: >-\n      Dhall is a programmable configuration language that adds types and\n      functions to JSON and YAML. Dhall expressions are total (always\n      terminate) and remote imports are content-addressed for safety.\n    humanURL: https://dhall-lang.org/\n    baseURL: https://dhall-lang.org\n    tags:\n      - Dhall\n      - Functional\n      - Total\n      - Type Safe\n    properties:\n      - type: Documentation\n        url: https://dhall-lang.org/\n\
  \      - type: GitHubRepository\n        url: https://github.com/dhall-lang/dhall-lang\n    x-features:\n      - Total, statically typed expressions\n      - Pure functions, types, and imports\n      - Renderable to JSON, YAML, plain Dhall\n  - aid: configuration-language:pkl\n    name: Pkl\n    description: >-\n      Pkl is Apple's open source configuration language with a focus on\n      type safety, composition, and runtime templating. Pkl can render to\n      YAML, JSON, plist, and other formats and offers IDE tooling and\n      language bindings.\n    humanURL: https://pkl-lang.org/\n    baseURL: https://pkl-lang.org\n    tags:\n      - Apple\n      - Pkl\n      - Templating\n      - Type Safe\n    properties:\n      - type: Documentation\n        url: https://pkl-lang.org/main/current/\n      - type: GitHubRepository\n        url: https://github.com/apple/pkl\n    x-features:\n      - First-class types, classes, and modules\n      - Renders to YAML, JSON, plist, properties, and Pcf\n\
  \      - Integrations for Java, Kotlin, Swift, Go\n  - aid: configuration-language:jsonnet\n    name: Jsonnet\n    description: >-\n      Jsonnet is a data templating language designed for elegant\n      generation of JSON and YAML. It is used heavily for Kubernetes\n      manifests, Grafana dashboards (Grafonnet), and Bazel-based\n      tooling.\n    humanURL: https://jsonnet.org/\n    baseURL: https://jsonnet.org\n    tags:\n      - Generation\n      - Jsonnet\n      - Templating\n    properties:\n      - type: Documentation\n        url: https://jsonnet.org/learning/tutorial.html\n      - type: GitHubRepository\n        url: https://github.com/google/jsonnet\n    x-features:\n      - JSON-superset templating language\n      - Functions, mixins, and inheritance\n      - Used by Grafana dashboards (Grafonnet) and Tanka\n  - aid: configuration-language:kdl\n    name: KDL\n    description: >-\n      KDL is a node-oriented document language combining the readability\n      of YAML and TOML\
  \ with a unique tree-shaped grammar. KDL is used by\n      Zellij, Helix, and other tools.\n    humanURL: https://kdl.dev/\n    baseURL: https://kdl.dev\n    tags:\n      - KDL\n      - Tree\n    properties:\n      - type: Specification\n        url: https://github.com/kdl-org/kdl/blob/main/SPEC.md\n      - type: Documentation\n        url: https://kdl.dev/\n    x-features:\n      - Node-and-property document model\n      - Distinct query language KQL for navigation\n      - Schema language KDL Schema\ncommon:\n  - type: Reference\n    url: https://en.wikipedia.org/wiki/Configuration_file\n  - type: Reference\n    url: https://docs.kernel.org/admin-guide/configuration.html\n  - type: Resources\n    url: https://github.com/avelino/awesome-go#configuration\n  - type: Reference\n    url: https://json-schema.org/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/configuration-language/refs/heads/main/apis.yml
tags:
- Configuration
- DSL
- Infrastructure as Code
- Schemas
- Serialization
- Templating
- YAML
url: https://raw.githubusercontent.com/api-evangelist/configuration-language/refs/heads/main/apis.yml
use_cases: []
---
