# Android

Table of Contents
- [Books](#books)
- [Development frameworks](#development-frameworks)
- [Guidelines](#guidelines)
  - [Java](#java)
  - [Kotlin](#kotlin)
- [IDEs](#ides)
- [Libraries](#libraries)
  - [HTTP Libraries](#http-libraries)
  - [Testing](#testing)
    - [Code Coverage](#code-coverage)
    - [Mocking](#mocking)
    - [Static Code Analysis](#static-code-analysis)
    - [Unit Testing](#unit-testing)
- [Roadmaps](#roadmaps)
- [Terminology](#terminology)

# Roadmaps
- https://github.com/tientnvn/android-developer-roadmap
![Android development roadmap](https://github.com/tientnvn/android-developer-roadmap/blob/master/images/android_roadmap_v1.0.png)

# Guidelines
- [Android Design Guidelines](https://developer.android.com/design)
- Why the app can be rejected on Play Store

## Java
- [Android Code Style Guidelines](https://source.android.com/setup/contribute/code-style)
- [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)
- [Oracle Secure Coding Guidelines for Java SE](https://www.oracle.com/technetwork/java/seccodeguide-139067.html)

## Kotlin
- [Kotlin style guide](https://developer.android.com/kotlin/style-guide)

# Libraries

## Testing
- [Test your app](https://developer.android.com/studio/test) with Android Studio

### Code Coverage
- [SonarQube](https://www.sonarqube.org/)
- [Cobertura](https://github.com/cobertura/cobertura)
- [Emma](http://emma.sourceforge.net/)

### Unit Testing
- JUnit - Android native test suite

### Mocking
- [Mockito](https://code.google.com/archive/p/mockito/) 
- [EasyMock](http://easymock.org/)
- [PowerMock](https://github.com/powermock/powermock)

### Static Code Analysis
- [Android Lint](https://developer.android.com/studio/write/lint#overview)
- [SonarQube](https://www.sonarqube.org/) (cross-platform)

## HTTP Libraries
- OkHTTP - best as a General purpose HTTP library (allows to perform generic HTTP requests: select an HTTP method, build headers and a request body). It provides a variety of features and is deeply customizable.
- Retrofit - best as REST client application component (helps to interact with the REST services). Simplifies web service methods proxy building. It is easily used in conjunction with OkHTTP library.

### Components Comparison
Component | Functionality | Objects Mapping Support | Data Caching | Authenticaion Support | Documentation Quality | Android Only
---|---|---|---|---|---|---
Google APIs Client | Good | Yes | Yes | Yes (OAuth 1 and 2) | Average	| No
Google HTTP Client | Good	| Yes	| Yes | No | Average | No
OkHTTP	           | Good	| Yes	| Yes	| No | Average | No
Retrofit	         | Good | Yes | Yes	| No | Average | Yes
Spring for Android | Good	| Yes	| No  |Yes (OAuth, Twitter, Facebook) | Good | Yes
Volley	           | Good	| No	| Yes	| Yes | Average | Yes
