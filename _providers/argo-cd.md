---
api_count: 1
api_specs:
- filename: argo-cd-openapi.json
  format: json
  label: Argo CD API
  slug: argo-cd
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/openapi/argo-cd-openapi.json
apis:
- description: The Argo CD REST API provides programmatic access to all Argo CD functionality including application management, cluster registration, repository configuration, project RBAC, account management, notif
  name: Argo CD API
  slug: argo-cd
capabilities:
- description: Unified capability for GitOps-driven continuous delivery using Argo CD. Combines application management, cluster registration, repository configuration, and project governance for Platform Engineers a
  name: Argo CD GitOps Delivery
  slug: gitops-delivery
common:
- title: ''
  type: Website
  url: https://argoproj.github.io/cd/
- title: ''
  type: Documentation
  url: https://argo-cd.readthedocs.io/en/stable/
- title: ''
  type: GettingStarted
  url: https://argo-cd.readthedocs.io/en/stable/getting_started/
- title: ''
  type: GitHubOrganization
  url: https://github.com/argoproj
- title: ''
  type: GitHubRepository
  url: https://github.com/argoproj/argo-cd
- title: ''
  type: Blog
  url: https://blog.argoproj.io/
- title: ''
  type: ReleaseNotes
  url: https://github.com/argoproj/argo-cd/releases
- title: ''
  type: ChangeLog
  url: https://github.com/argoproj/argo-cd/blob/master/CHANGELOG.md
- title: ''
  type: CLI
  url: https://argo-cd.readthedocs.io/en/stable/user-guide/commands/argocd/
- title: ''
  type: SDK
  url: https://github.com/argoproj/argo-cd/tree/master/pkg/apiclient
- title: ''
  type: Support
  url: https://github.com/argoproj/argo-cd/issues
- title: ''
  type: SpectralRules
  url: rules/argo-cd-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/gitops-delivery.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/argo-cd-vocabulary.yaml
created: '2026-03-26'
description: Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes that automates the deployment of applications by using Git repositories as the source of truth for defining the desired application state. It supports multiple config management tools (Helm, Kustomize, Jsonnet, plain YAML), multi-cluster deployments, RBAC, SSO integrations, and a fully-loaded web UI. Part of the CNCF ecosystem and the Argo Project, governed by the Linux Foundation.
features:
- description: Defines application deployment state in Git repositories and automatically reconciles cluster state to match.
  name: Declarative GitOps Delivery
- description: Deploy and manage applications across multiple Kubernetes clusters from a single control plane.
  name: Multi-Cluster Deployment
- description: Automates creation of Argo CD Applications from templates across many clusters and namespaces.
  name: ApplicationSet Controller
- description: Supports Helm, Kustomize, Jsonnet, plain YAML, and custom plugins for application templating.
  name: Multiple Config Management Tools
- description: Fully-loaded graphical interface for visualizing application sync status, resource trees, and deployment history.
  name: Web UI
- description: Fine-grained role-based access control with project-level isolation for multi-team environments.
  name: RBAC and Multi-Tenancy
- description: Built-in SSO support for OIDC, OAuth2, LDAP, SAML 2.0, GitHub, GitLab, Microsoft, and LinkedIn.
  name: SSO Integration
- description: Continuously monitors Git and automatically syncs application state to match the desired state.
  name: Automated Sync
- description: PreSync, Sync, and PostSync hooks for complex rollout strategies including blue/green and canary.
  name: Sync Hooks
- description: Receives webhooks from GitHub, GitLab, and Bitbucket for instant sync on push events.
  name: Webhook Support
- description: Complete audit log of all deployment events and configuration changes.
  name: Audit Trail
- description: Built-in and custom health checks for Kubernetes resources to assess application health status.
  name: Health Assessment
- description: Configurable notifications via email, Slack, and other channels on sync events and health changes.
  name: Notifications
- description: Verifies GPG signatures on Git commits for enhanced supply chain security.
  name: GPG Commit Verification
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native support for Helm chart rendering and deployment with value overrides.
  name: Helm
- description: Native support for Kustomize overlays for environment-specific configuration.
  name: Kustomize
- description: Integrates with Vault for secret management using the argocd-vault-plugin.
  name: HashiCorp Vault
- description: Trigger Argo CD syncs or check sync status as part of GitHub Actions CI pipelines.
  name: GitHub Actions
- description: Integrate Argo CD sync steps into Jenkins CI/CD pipelines.
  name: Jenkins
- description: Exposes metrics for Prometheus scraping to monitor application sync health and performance.
  name: Prometheus
- description: Pre-built dashboards for visualizing Argo CD metrics in Grafana.
  name: Grafana
- description: Enforce admission policies via OPA and Gatekeeper before Argo CD syncs resources.
  name: Open Policy Agent
- description: Native integration with Argo Rollouts for progressive delivery (canary, blue/green).
  name: Argo Rollouts
- description: Trigger Argo Workflows as part of sync hooks for complex multi-step pipelines.
  name: Argo Workflows
- description: Send deployment notifications and alerts to Slack channels.
  name: Slack
- description: Manage applications on Amazon EKS clusters with AWS IAM authentication support.
  name: AWS EKS
- description: Deploy to Google Kubernetes Engine clusters with GKE authentication.
  name: Google GKE
- description: Manage applications on Azure Kubernetes Service with Azure AD authentication.
  name: Azure AKS
jsonld:
- class_count: 10
  name: Argo Cd Account Context
  property_count: 12
  slug: argo-cd-account-context
- class_count: 24
  name: Argo Cd Application Context
  property_count: 43
  slug: argo-cd-application-context
- class_count: 3
  name: Argo Cd Applicationset Context
  property_count: 4
  slug: argo-cd-applicationset-context
- class_count: 4
  name: Argo Cd Applicationv1Alpha1 Context
  property_count: 10
  slug: argo-cd-applicationv1alpha1-context
- class_count: 12
  name: Argo Cd Cluster Context
  property_count: 42
  slug: argo-cd-cluster-context
- class_count: 2
  name: Argo Cd Gpgkey Context
  property_count: 2
  slug: argo-cd-gpgkey-context
- class_count: 1
  name: Argo Cd Intstr Context
  property_count: 3
  slug: argo-cd-intstr-context
- class_count: 7
  name: Argo Cd Notification Context
  property_count: 1
  slug: argo-cd-notification-context
- class_count: 1
  name: Argo Cd Oidc Context
  property_count: 3
  slug: argo-cd-oidc-context
- class_count: 9
  name: Argo Cd Project Context
  property_count: 11
  slug: argo-cd-project-context
- class_count: 1
  name: Argo Cd Protobuf Context
  property_count: 2
  slug: argo-cd-protobuf-context
- class_count: 1
  name: Argo Cd Repocreds Context
  property_count: 0
  slug: argo-cd-repocreds-context
- class_count: 15
  name: Argo Cd Repository Context
  property_count: 36
  slug: argo-cd-repository-context
- class_count: 3
  name: Argo Cd Runtime Context
  property_count: 8
  slug: argo-cd-runtime-context
- class_count: 3
  name: Argo Cd Session Context
  property_count: 6
  slug: argo-cd-session-context
- class_count: 20
  name: Argo Cd V1 Context
  property_count: 75
  slug: argo-cd-v1-context
- class_count: 161
  name: Argo Cd V1Alpha1 Context
  property_count: 378
  slug: argo-cd-v1alpha1-context
- class_count: 1
  name: Argo Cd Version Context
  property_count: 13
  slug: argo-cd-version-context
layout: provider
modified: '2026-04-19'
name: Argo CD
rules:
- name: Argo CD API Rules
  rule_count: 18
  severity_counts:
    error: 7
    hint: 0
    info: 2
    warn: 9
  slug: argo-cd-spectral-rules
skills: []
slug: argo-cd
solutions: []
source_filename: apis.yml
source_yaml: "aid: argo-cd\nname: Argo CD\ndescription: >-\n  Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes that automates the\n  deployment of applications by using Git repositories as the source of truth for defining the\n  desired application state. It supports multiple config management tools (Helm, Kustomize,\n  Jsonnet, plain YAML), multi-cluster deployments, RBAC, SSO integrations, and a fully-loaded\n  web UI. Part of the CNCF ecosystem and the Argo Project, governed by the Linux Foundation.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Continuous Delivery\n  - Containers\n  - Deployment\n  - GitOps\n  - Kubernetes\n  - CNCF\n  - Open Source\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: argo-cd:argo-cd\n    name: Argo CD API\n    description: >-\n      The\
  \ Argo CD REST API provides programmatic access to all Argo CD functionality including\n      application management, cluster registration, repository configuration, project RBAC,\n      account management, notifications, and settings. Authentication uses JWT bearer tokens\n      obtained via the session endpoint.\n    humanURL: https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/\n    tags:\n      - Continuous Delivery\n      - GitOps\n      - Kubernetes\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/\n      - type: OpenAPI\n        url: openapi/argo-cd-openapi.json\n      - type: GettingStarted\n        url: https://argo-cd.readthedocs.io/en/stable/getting_started/\n      - type: Authentication\n        url: https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/#authentication\n      - type: APIReference\n        url: https://cd.apps.argoproj.io/swagger-ui\ncommon:\n\
  \  - type: Website\n    url: https://argoproj.github.io/cd/\n  - type: Documentation\n    url: https://argo-cd.readthedocs.io/en/stable/\n  - type: GettingStarted\n    url: https://argo-cd.readthedocs.io/en/stable/getting_started/\n  - type: GitHubOrganization\n    url: https://github.com/argoproj\n  - type: GitHubRepository\n    url: https://github.com/argoproj/argo-cd\n  - type: Blog\n    url: https://blog.argoproj.io/\n  - type: ReleaseNotes\n    url: https://github.com/argoproj/argo-cd/releases\n  - type: ChangeLog\n    url: https://github.com/argoproj/argo-cd/blob/master/CHANGELOG.md\n  - type: CLI\n    url: https://argo-cd.readthedocs.io/en/stable/user-guide/commands/argocd/\n  - type: SDK\n    url: https://github.com/argoproj/argo-cd/tree/master/pkg/apiclient\n  - type: Support\n    url: https://github.com/argoproj/argo-cd/issues\n  - type: SpectralRules\n    url: rules/argo-cd-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/gitops-delivery.yaml\n  - type:\
  \ Vocabulary\n    url: vocabulary/argo-cd-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Declarative GitOps Delivery\n        description: Defines application deployment state in Git repositories and automatically reconciles cluster state to match.\n      - name: Multi-Cluster Deployment\n        description: Deploy and manage applications across multiple Kubernetes clusters from a single control plane.\n      - name: ApplicationSet Controller\n        description: Automates creation of Argo CD Applications from templates across many clusters and namespaces.\n      - name: Multiple Config Management Tools\n        description: Supports Helm, Kustomize, Jsonnet, plain YAML, and custom plugins for application templating.\n      - name: Web UI\n        description: Fully-loaded graphical interface for visualizing application sync status, resource trees, and deployment history.\n      - name: RBAC and Multi-Tenancy\n        description: Fine-grained role-based access control\
  \ with project-level isolation for multi-team environments.\n      - name: SSO Integration\n        description: Built-in SSO support for OIDC, OAuth2, LDAP, SAML 2.0, GitHub, GitLab, Microsoft, and LinkedIn.\n      - name: Automated Sync\n        description: Continuously monitors Git and automatically syncs application state to match the desired state.\n      - name: Sync Hooks\n        description: PreSync, Sync, and PostSync hooks for complex rollout strategies including blue/green and canary.\n      - name: Webhook Support\n        description: Receives webhooks from GitHub, GitLab, and Bitbucket for instant sync on push events.\n      - name: Audit Trail\n        description: Complete audit log of all deployment events and configuration changes.\n      - name: Health Assessment\n        description: Built-in and custom health checks for Kubernetes resources to assess application health status.\n      - name: Notifications\n        description: Configurable notifications via email,\
  \ Slack, and other channels on sync events and health changes.\n      - name: GPG Commit Verification\n        description: Verifies GPG signatures on Git commits for enhanced supply chain security.\n  - type: UseCases\n    data:\n      - name: Continuous Deployment to Kubernetes\n        description: Automate application releases to Kubernetes clusters with every Git commit triggering a reconciliation cycle.\n      - name: Multi-Environment Promotion\n        description: Promote application versions across dev, staging, and production environments using Git branch strategies.\n      - name: Multi-Cluster GitOps\n        description: Manage application deployments consistently across dozens of Kubernetes clusters from a central Argo CD instance.\n      - name: Cluster Add-On Management\n        description: Automatically deploy infrastructure add-ons (CNI, CSI, monitoring) to all clusters using ApplicationSet.\n      - name: Tenant Self-Service\n        description: Allow development\
  \ teams to manage their own applications within project-scoped RBAC boundaries.\n      - name: Disaster Recovery\n        description: Quickly restore application state to any prior Git commit in case of production incidents.\n      - name: Compliance and Auditability\n        description: Maintain a complete audit trail of all deployment changes via Git history and Argo CD event logs.\n  - type: Integrations\n    data:\n      - name: Helm\n        description: Native support for Helm chart rendering and deployment with value overrides.\n      - name: Kustomize\n        description: Native support for Kustomize overlays for environment-specific configuration.\n      - name: HashiCorp Vault\n        description: Integrates with Vault for secret management using the argocd-vault-plugin.\n      - name: GitHub Actions\n        description: Trigger Argo CD syncs or check sync status as part of GitHub Actions CI pipelines.\n      - name: Jenkins\n        description: Integrate Argo CD sync steps\
  \ into Jenkins CI/CD pipelines.\n      - name: Prometheus\n        description: Exposes metrics for Prometheus scraping to monitor application sync health and performance.\n      - name: Grafana\n        description: Pre-built dashboards for visualizing Argo CD metrics in Grafana.\n      - name: Open Policy Agent\n        description: Enforce admission policies via OPA and Gatekeeper before Argo CD syncs resources.\n      - name: Argo Rollouts\n        description: Native integration with Argo Rollouts for progressive delivery (canary, blue/green).\n      - name: Argo Workflows\n        description: Trigger Argo Workflows as part of sync hooks for complex multi-step pipelines.\n      - name: Slack\n        description: Send deployment notifications and alerts to Slack channels.\n      - name: AWS EKS\n        description: Manage applications on Amazon EKS clusters with AWS IAM authentication support.\n      - name: Google GKE\n        description: Deploy to Google Kubernetes Engine clusters\
  \ with GKE authentication.\n      - name: Azure AKS\n        description: Manage applications on Azure Kubernetes Service with Azure AD authentication.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/apis.yml
tags:
- Continuous Delivery
- Containers
- Deployment
- GitOps
- Kubernetes
- CNCF
- Open Source
url: https://raw.githubusercontent.com/api-evangelist/argo-cd/refs/heads/main/apis.yml
use_cases:
- description: Automate application releases to Kubernetes clusters with every Git commit triggering a reconciliation cycle.
  name: Continuous Deployment to Kubernetes
- description: Promote application versions across dev, staging, and production environments using Git branch strategies.
  name: Multi-Environment Promotion
- description: Manage application deployments consistently across dozens of Kubernetes clusters from a central Argo CD instance.
  name: Multi-Cluster GitOps
- description: Automatically deploy infrastructure add-ons (CNI, CSI, monitoring) to all clusters using ApplicationSet.
  name: Cluster Add-On Management
- description: Allow development teams to manage their own applications within project-scoped RBAC boundaries.
  name: Tenant Self-Service
- description: Quickly restore application state to any prior Git commit in case of production incidents.
  name: Disaster Recovery
- description: Maintain a complete audit trail of all deployment changes via Git history and Argo CD event logs.
  name: Compliance and Auditability
---
