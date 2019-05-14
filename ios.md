# iOS

Table of Contents
- [Books](#books)
- [Development frameworks](#development-frameworks)
- [Guidelines](#guidelines)
- [IDEs](#ides)
- [Libraries](#libraries)
  - [Application Performance Management Libraries](#application-performance-management-libraries)
  - [Crash Reporting Libraries](#crash-reporting-libraries)
  - [HTTP Libraries](#http-libraries)
  - [Logging Libraries](#logging-libraries)
  - [Testing](#testing)
    - [Mocking](#mocking)
    - [Static Code Analysis](#static-code-analysis)
    - [Unit Testing](#unit-testing)
- [Roadmaps](#roadmaps)
- [Services](#services)
- [Terminology](#terminology)

# Roadmaps
- [2018 Roadmap to iOS Development](https://www.reddit.com/r/iOSProgramming/comments/82w6qa/2018_roadmap_to_ios_development/)
![2018 Roadmap to iOS Development](https://preview.redd.it/ix44k24k9ik01.png?width=640&crop=smart&auto=webp&s=a69d1a299ab430acdcdf89d1be891f239ddb46c2)

- [Roadmap to becoming an iOS developer in 2018](https://github.com/BohdanOrlov/iOS-Developer-Roadmap)
![Roadmap to becoming an iOS developer in 2018](https://github.com/BohdanOrlov/iOS-Developer-Roadmap/blob/master/RoadmapProject/Script/Generated/ESSENTIALROADMAP.png)

# Guidelines

# Libraries

## Application Performance Management Libraries
[New Relic](http://newrelic.com/) - the richness of functionality, user experience and code-level performance insights are great.
- Pricing - free for 24hr data retention.
- Popular component: yes.
- Large community and a lot of contributors: yes (paid service).
- Use cases: end-to-end, NPM, EUEM, crash reporting, analytics, SaaS only.

## Crash Reporting Libraries
- Crashlytics - free full-featured crash reporting tool. Integrated with [Firebase](https://firebase.google.com/docs/crashlytics/get-started).

## HTTP Libraries
RestKit works in most cases. But if you do not need any of the RestKit cool features and look for something simple, then use AFNetworking.

### Components Comparison
Component |	Functionality | Supports Code Data Persistence | Short Familiarization Time
---|---|---|---
AFIncrementalStore  | Good | Yes | Yes
AFNetworking        | Good | No  | Yes
MKNetworkKit        | Good | No  | No
RestKit             | Excellent | Yes | No

## Logging Libraries
Objective-C: CocoaLumberjack.
Swift: XCGLogger.

## Testing

### Unit Testing
Apple Xcode includes XCTest framework

### Mocking
- [OCMock](http://ocmock.org/) - Mock objects for Objective-C
- [Kiwi](https://github.com/kiwi-bdd/Kiwi/releases/tag/2.3.0) - not only a mocking library but a complete Behavior Driven Development (BDD) oriented testing framework based on XCTest. Mocking is just a part of the framework. It also includes very powerful & organic way to specify expectations.

### Components comparison
- Syntax - If the syntax is familiar to the Objective-C developers, nice and compact (good/average/bad);
- Documentation quality - How full and convenient the Documentation is (good/average/bad);
- BDD support - If the framework supports Behavior Driven Development (BDD) paradigm (yes/no);

Component | Syntax | Docs quality | BDD Support
---|---|---|---
Kiwi	  | Good | Good | Yes
OCMock	| Bad	 | Good	| No
OCMokito|	Average	| Bad | No

### Static Code Analysis
 - [iOS Clang Static Analyser](http://clang-analyzer.llvm.org/) - source code analysis tool that finds bugs in C, C++, and Objective-C programs
 - [OCLint](http://oclint.org/) -  static code analysis tool for improving quality and reducing defects by inspecting C, C++ and Objective-C code

# Services
- [TestFlight](https://developer.apple.com/testflight/) - online service for over-the-air installation and testing of mobile applications, currently owned by Apple Inc and only offered to developers within the iOS Developer Program
