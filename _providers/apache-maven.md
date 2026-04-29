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
source_filename: apis.yml
source_yaml: "aid: apache-maven\nname: Apache Maven\ndescription: >-\n  Apache Maven is a software project management and comprehension tool based on the concept of a project object model (POM). It provides a uniform build system, dependency management, project lifecycle, and a comprehensive plugin ecosystem for Java projects. Maven 4 is the current major version with the Maven Daemon for faster builds.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Build Tool\n  - Dependency Management\n  - Java\n  - Project Management\n  - Maven\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-maven/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-maven:apache-maven-core\n    name: Apache Maven Core\n    description: >-\n      Maven provides a Java API for programmatic build execution, a Plugin API (Mojo) for\
  \ extending build capabilities, a Repository API for artifact management via Maven Artifact Resolver, and the Wagon transport API for repository access. Maven 4 introduces improved APIs and the Maven Upgrade Tool for migration.\n    humanURL: https://maven.apache.org/guides/index.html\n    tags:\n      - Build\n      - Java\n      - Plugins\n      - Project Object Model\n    properties:\n      - type: Documentation\n        url: https://maven.apache.org/guides/index.html\n      - type: GettingStarted\n        url: https://maven.apache.org/install.html\n      - type: APIReference\n        url: https://maven.apache.org/ref/current/\n      - type: SDK\n        url: https://central.sonatype.com/artifact/org.apache.maven/maven-core\n        title: Maven Central (Java)\n      - type: GitHubRepository\n        url: https://github.com/apache/maven\n  - aid: apache-maven:maven-central-repository\n    name: Maven Central Repository API\n    description: >-\n      The Maven Central Repository (search.maven.org\
  \ and central.sonatype.com) hosts millions of Java artifacts and provides a REST API and web interface for searching, browsing, and downloading dependencies. It is the default artifact repository for Maven builds.\n    humanURL: https://central.sonatype.com/\n    tags:\n      - Artifact Repository\n      - Dependency Management\n      - Package Registry\n    properties:\n      - type: Documentation\n        url: https://central.sonatype.org/publish/\n      - type: Portal\n        url: https://central.sonatype.com/\n      - type: APIReference\n        url: https://central.sonatype.com/api-doc\ncommon:\n  - type: Portal\n    url: https://maven.apache.org/\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/maven\n  - type: GitHubRepository\n    url: https://github.com/apache/maven-resolver\n  - type: GitHubRepository\n    url: https://github.com/apache/maven-mvnd\n  - type: GitHubRepository\n    url: https://github.com/apache/maven-surefire\n\
  \  - type: GitHubRepository\n    url: https://github.com/apache/maven-enforcer\n  - type: GitHubRepository\n    url: https://github.com/apache/maven-assembly-plugin\n  - type: Wiki\n    url: https://cwiki.apache.org/confluence/display/MAVEN\n  - type: IssueTracker\n    url: https://issues.apache.org/jira/projects/MNG/issues\n  - type: MailingList\n    url: https://maven.apache.org/mailing-lists.html\n  - type: Blog\n    url: https://maven.apache.org/news.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Features\n    data:\n      - name: Project Object Model (POM)\n        description: XML-based project descriptor that defines dependencies, build configuration, plugins, and project metadata in a declarative format.\n      - name: Dependency Management\n        description: Automatic resolution and downloading of project dependencies and transitive dependencies from Maven Central and other repositories.\n      - name: Build Lifecycle\n     \
  \   description: Standardized build lifecycle with phases including validate, compile, test, package, verify, install, and deploy.\n      - name: Plugin Architecture\n        description: Extensible plugin system (Mojo API) with hundreds of official and third-party plugins for code generation, testing, packaging, and deployment.\n      - name: Maven Daemon (mvnd)\n        description: Persistent daemon process that dramatically reduces build startup time by keeping the JVM and Maven warm between builds.\n      - name: Maven Wrapper\n        description: Ensures consistent Maven version usage across a project team without requiring separate Maven installation.\n      - name: Artifact Resolver\n        description: Maven Artifact Resolver library provides programmatic API for artifact resolution, download, and local repository management.\n      - name: Multi-Module Projects\n        description: Support for building complex multi-module projects with inter-module dependency management and\
  \ coordinated releases.\n      - name: Maven 4\n        description: Latest major version with improved APIs, better performance, consumer POM support, and the Maven Upgrade Tool for migration.\n      - name: Central Repository Publishing\n        description: Streamlined artifact publishing to Maven Central via Sonatype's publishing portal with automated checks.\n  - type: UseCases\n    data:\n      - name: Java Project Build Automation\n        description: Automate compilation, testing, packaging, and deployment of Java projects with standardized build lifecycles.\n      - name: Dependency Management\n        description: Declare and automatically resolve project dependencies including transitive dependencies from Maven Central.\n      - name: CI/CD Pipeline Integration\n        description: Integrate Maven builds into CI/CD pipelines with reproducible builds via the Maven Wrapper and build cache extension.\n      - name: Multi-Module Enterprise Builds\n        description: Manage complex\
  \ enterprise Java projects with dozens of interdependent modules and shared dependency management.\n      - name: Artifact Publishing\n        description: Publish Java libraries and applications to Maven Central or private artifact repositories for team and public consumption.\n      - name: Plugin Development\n        description: Develop custom Maven plugins using the Mojo API to extend build capabilities for specialized project needs.\n  - type: Integrations\n    data:\n      - name: IntelliJ IDEA\n        description: Native Maven project support with POM editing, dependency management, and Maven tool window.\n      - name: Eclipse\n        description: Maven integration via the m2e plugin for POM-based project management within Eclipse IDE.\n      - name: Jenkins\n        description: Jenkins Maven plugin for triggering and monitoring Maven builds in CI/CD pipelines.\n      - name: GitHub Actions\n        description: Official GitHub Actions for caching Maven dependencies and running\
  \ Maven builds in workflows.\n      - name: Sonatype Nexus\n        description: Enterprise artifact repository manager fully compatible with Maven for hosting private artifact repositories.\n      - name: JFrog Artifactory\n        description: Enterprise artifact repository with full Maven repository protocol support and build integration.\n      - name: Apache Tomcat\n        description: Tomcat Maven Plugin enables deploying web applications to Apache Tomcat directly from Maven builds.\n      - name: GraalVM\n        description: Maven plugins for building native images from Java applications using GraalVM Native Image.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-maven/refs/heads/main/apis.yml
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
