# DevOps

Table of Contents
- [Continuous Integration and Delivery](#continuous-integration-and-delivery)
  - [Azure Devops](#azure-devops)
  - [Bitrise](#bitrise)
  - [Jenkins](#jenkins)
    - [Plugins](#plugins)
    - [Java stack](#java-stack)
    - [Python stack](#python-stack)
  - [Nevercode](#nevercode)
- [Roadmaps](#roadmaps)

# Roadmaps
![DevOps technologies](https://i0.wp.com/codeforgeek.com/wp-content/uploads/2017/04/devops-tools.png?resize=768%2C999&ssl=1)
[source, 2017](https://codeforgeek.com/2017/04/become-valuable-full-stack-developer/)

![pipeline1](https://github.com/lankastersky/architectural-stacks/blob/master/devops-pipeline1.png)
![pipeline2](https://github.com/lankastersky/architectural-stacks/blob/master/devops-pipeline2.png)
from Andriy Trubitsyn

# Continuous Integration and Delivery

## [Jenkins](https://jenkins.io/)

### Plugins
- [20 Jenkins Plugins You Can’t Live Without, 2018](https://caylent.com/jenkins-plugins/)
- [Cobertura](https://wiki.jenkins-ci.org/display/JENKINS/Cobertura+Plugin) - integrates Cobertura coverage reports to Jenkins.
- [Code Coverage API](https://plugins.jenkins.io/code-coverage-api) - serves as API to integrate and publish multiple coverage report types.
- [Dashboard View](https://wiki.jenkins.io/display/JENKINS/Dashboard+View) - represents a summary information about all jobs (passes, tests etc.)
- [Environment Injector](https://wiki.jenkins.io/display/JENKINS/EnvInject+Plugin) - makes it possible to set an environment for the builds.
- [Gerrit trigger](https://wiki.jenkins.io/display/JENKINS/Gerrit+Trigger#GerritTrigger-SetUp) - installed as a presubmit hook for Gerrit (git service)
- [Job Configuration History](https://wiki.jenkins.io/display/JENKINS/JobConfigHistory+Plugin) - Job history plugin for Jenkins.
- [JUnit](https://wiki.jenkins-ci.org/display/JENKINS/JUnit+Plugin) for unit tests - publishes JUnit XML formatted test reports for trending and analysis
- [SonarQube](https://wiki.jenkins-ci.org/display/JENKINS/SonarQube+plugin) - integrate reporting from the SonarQube code quality/inspection platform
- [Warnings Next Generation Plugin](https://wiki.jenkins.io/display/JENKINS/Warnings+Next+Generation+Plugin) - collects compiler warnings or issues reported by static analysis tools and visualizes the results. Makes the following Jenkins plugins obsolete: Android Lint, CheckStyle, Dry, FindBugs, PMD, Warnings, Static Analysis Utilities, Static Analysis Collector Plugins, Task Scanner, etc. 

Android-specific:
- [Google Play Android Publisher Plugin](https://github.com/jenkinsci/google-play-android-publisher-plugin) - Enables Jenkins to upload Android apps (APK files) to Google Play and to manage related info.
- [Android Lint Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Android+Lint+Plugin) - parses Android Lint analysis results and visualises the issues found.

### Python stack
https://jenkins.io/solutions/python/ 
- nose2 and pytest for executing unit tests
- pylint for generating code quality reports
- [Violations plugin](https://wiki.jenkins-ci.org/display/JENKINS/Violations) - processes output from pylint to provide style checks for Python code

### Java stack
https://jenkins.io/solutions/java/
- [Gradle](https://wiki.jenkins-ci.org/display/JENKINS/Gradle+Plugin) to build projects - support invoking Gradle as a build step and listing executing tasks per build
- Maven - supported in standard, you can use the dedicated step

## [Circle CI](https://circleci.com/)

## [Gitlab CI](https://about.gitlab.com/product/continuous-integration/)
GitLab has integrated CI/CD pipelines to build, test, deploy, and monitor your code

## [Azure Devops](https://azure.microsoft.com/en-us/services/devops/)
- cloud-based solution from Microsoft
- Choose your language and use Pipelines cloud-hosted build agents for Linux, macOS, and Windows. 
- Continuously deploy to any cloud (Microsoft Azure, Amazon Web Services, and Google Cloud Platform) or no-premises.
- Works with [App Center](https://appcenter.ms/) to distribute mobile apps

## [Nevercode](https://nevercode.io/)
Cloud-based continuous integration & delivery for iOS, Android, Cordova, Ionic, 
React Native & Flutter projects
- Used to distribute mobile apps

## [Bitrise](https://www.bitrise.io/)
