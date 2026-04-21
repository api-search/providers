---
api_count: 2
apis:
- description: Maven provides a Java API for programmatic build execution, a Plugin API (Mojo) for extending build capabilities, a Repository API for artifact management via Maven Artifact Resolver, and the Wagon tr
  name: Apache Maven Core
  slug: apache-maven-core
- description: The Maven Central Repository (search.maven.org and central.sonatype.com) hosts millions of Java artifacts and provides a REST API and web interface for searching, browsing, and downloading dependencie
  name: Maven Central Repository API
  slug: maven-central-repository
common:
- title: ''
  type: Portal
  url: https://maven.apache.org/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/maven
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/maven-resolver
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/maven-mvnd
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/maven-surefire
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/maven-enforcer
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/maven-assembly-plugin
- title: ''
  type: Wiki
  url: https://cwiki.apache.org/confluence/display/MAVEN
- title: ''
  type: IssueTracker
  url: https://issues.apache.org/jira/projects/MNG/issues
- title: ''
  type: MailingList
  url: https://maven.apache.org/mailing-lists.html
- title: ''
  type: Blog
  url: https://maven.apache.org/news.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
created: '2026-03-16'
description: Apache Maven is a software project management and comprehension tool based on the concept of a project object model (POM). It provides a uniform build system, dependency management, project lifecycle, and a comprehensive plugin ecosystem for Java projects. Maven 4 is the current major version with the Maven Daemon for faster builds.
features:
- description: XML-based project descriptor that defines dependencies, build configuration, plugins, and project metadata in a declarative format.
  name: Project Object Model (POM)
- description: Automatic resolution and downloading of project dependencies and transitive dependencies from Maven Central and other repositories.
  name: Dependency Management
- description: Standardized build lifecycle with phases including validate, compile, test, package, verify, install, and deploy.
  name: Build Lifecycle
- description: Extensible plugin system (Mojo API) with hundreds of official and third-party plugins for code generation, testing, packaging, and deployment.
  name: Plugin Architecture
- description: Persistent daemon process that dramatically reduces build startup time by keeping the JVM and Maven warm between builds.
  name: Maven Daemon (mvnd)
- description: Ensures consistent Maven version usage across a project team without requiring separate Maven installation.
  name: Maven Wrapper
- description: Maven Artifact Resolver library provides programmatic API for artifact resolution, download, and local repository management.
  name: Artifact Resolver
- description: Support for building complex multi-module projects with inter-module dependency management and coordinated releases.
  name: Multi-Module Projects
- description: Latest major version with improved APIs, better performance, consumer POM support, and the Maven Upgrade Tool for migration.
  name: Maven 4
- description: Streamlined artifact publishing to Maven Central via Sonatype's publishing portal with automated checks.
  name: Central Repository Publishing
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native Maven project support with POM editing, dependency management, and Maven tool window.
  name: IntelliJ IDEA
- description: Maven integration via the m2e plugin for POM-based project management within Eclipse IDE.
  name: Eclipse
- description: Jenkins Maven plugin for triggering and monitoring Maven builds in CI/CD pipelines.
  name: Jenkins
- description: Official GitHub Actions for caching Maven dependencies and running Maven builds in workflows.
  name: GitHub Actions
- description: Enterprise artifact repository manager fully compatible with Maven for hosting private artifact repositories.
  name: Sonatype Nexus
- description: Enterprise artifact repository with full Maven repository protocol support and build integration.
  name: JFrog Artifactory
- description: Tomcat Maven Plugin enables deploying web applications to Apache Tomcat directly from Maven builds.
  name: Apache Tomcat
- description: Maven plugins for building native images from Java applications using GraalVM Native Image.
  name: GraalVM
layout: provider
modified: '2026-04-19'
name: Apache Maven
skills: []
slug: apache-maven
solutions: []
tags:
- Build Tool
- Dependency Management
- Java
- Project Management
- Maven
url: https://raw.githubusercontent.com/api-evangelist/apache-maven/refs/heads/main/apis.yml
use_cases:
- description: Automate compilation, testing, packaging, and deployment of Java projects with standardized build lifecycles.
  name: Java Project Build Automation
- description: Declare and automatically resolve project dependencies including transitive dependencies from Maven Central.
  name: Dependency Management
- description: Integrate Maven builds into CI/CD pipelines with reproducible builds via the Maven Wrapper and build cache extension.
  name: CI/CD Pipeline Integration
- description: Manage complex enterprise Java projects with dozens of interdependent modules and shared dependency management.
  name: Multi-Module Enterprise Builds
- description: Publish Java libraries and applications to Maven Central or private artifact repositories for team and public consumption.
  name: Artifact Publishing
- description: Develop custom Maven plugins using the Mojo API to extend build capabilities for specialized project needs.
  name: Plugin Development
---
