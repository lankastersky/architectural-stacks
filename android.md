# Android

Table of Contents
- [Books](#books)
- [Development frameworks](#development-frameworks)
- [Guidelines](#guidelines)
  - [Java](#java)
  - [Kotlin](#kotlin)
- [IDEs](#ides)
- [Libraries](#libraries)
  - [Crash Reporting Libraries](#crash-reporting-libraries)
  - [Dependency Injection Libraries](#dependency-injection-libraries)
  - [HTTP Libraries](#http-libraries)
  - [Image Loading Libraries](#image-loading-libraries)
  - [JSON Parsing Libraries](#json-parsing-libraries)
  - [NoSql Databases](#nosql-databases)
  - [ORM Libraries](#orm-libraries)
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
- Robolectric
  - allows for tests to be run in the JVM instead of the DVM by replacing the native Android calls with proxies.  
  - one of the most TDD-suitable testing frameworks
- [Mockito](https://code.google.com/archive/p/mockito/) 
- [EasyMock](http://easymock.org/)
- [PowerMock](https://github.com/powermock/powermock)

#### Components Comparison
Component | Running on Device | Performance | Documentation Quality | final/static support
---|---|---|---|---
easymock	  | yes (with extention)	| Good	| Average	| no
mockito	    | yes (with extention)	| Good	| Good	  | no
powermock   |	no	                  | Good	| Average	| yes
robolectric	| no                    |	Best	| Good	  | no

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

## Image Loading Libraries
- Glide or Picasso are the best to download and put the image in the app, you don't need a lot of configuration and they can work with almost every popular image format. You can also add listeners and callbacks easy.
- Glide has the best to download and apply some effects, it's build to give better appareance when showing the image and to work better with lists of items.
- Fresco is best to load different formats and customize the download process. Supports GIF, WebP and animated WebP. Glide can also work with GIF.

### Components Comparison
Component | Support of External HTTP Clients | Set of Transformations | Documentation Quality
---|---|---|---
Fresco      | Yes |	Good | Good
Glide 	    | Yes	| Good | Good
imageloader	| No	| Good | Average
Picasso	    | Yes	| Average |	Average (Javadoc)

## JSON Parsing Libraries
GSON and Jackson are complete JSON parsers:
- Generate JSON data
- Data binding (Primitive data types, Maps, Lists and Objects)
- Support Stream (SAX like but not event-based) and Tree (DOM like) parsing techniques
- Support annotations

### Components Comparison
Component | Usage and Integration | Performance for Small/Large Data Size | Parser Customization | Plugins | Supported by Network libs 
---|---|---|---|---|---
GSON	  | Easy   | Fast / Medium | Basic | No  | Yes (Most of them)
Jackson |	Medium | Medium / Fast | Yes	 | Yes | No (Limited number)

## Crash Reporting Libraries
- Crashlytics - free full-featured crash reporting tool. Integrated with [Firebase](https://firebase.google.com/docs/crash/android).

## ORM Libraries
- ORM is Object-Relational Mapping here.
- [Room from Google](https://developer.android.com/topic/libraries/architecture/room) - provides an abstraction layer over SQLite to allow for more robust database access while harnessing the full power of SQLite.
- OrmLite - provides excellent functionality and wide set of features.

## NoSql Databases
- Realm is a modern NoSql framework. 
  - It uses its own persistence engine, built for simplicity (& speed).
  - Rich functionality (that increasing very fast) 
  - Excellent possibilities for customization.
- Firebase Database
- Firebase Firestore

## Dependency Injection Libraries
Dagger - high quality functional DI framework.

### Components Comparison
Criteria:
- Functionality – richness of functionality and possibilities for customization (good/average/bad).
- Overhead – how large does become a project when using the library and how does this affect application memory(small/medium/large). 
- Android injections – whether the framework supports Android platform specific features e.g. view injections, resource injections. (yes/no).
- Injections mode – whether the framework works at runtime or at compile time(runtime/compile). 
- Documentation quality – how good a tool and its features are documented (good/average/bad).

Component | Functionality | Overhead | Android injections | Injections mode | Documentation quality
---|---|---|---|---|---
AndroidAnnotations	| Good  	| Medium	| Yes	| Compile	| Good
Dagger	            | Average	| Medium	| No	| Compile	| Good
RoboGuice	          | Good	  | Large 	| Yes	| Runtime	| Average
Transfuse	          | Good	  | Medium	| Yes	| Compile	| Average



