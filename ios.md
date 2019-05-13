# iOS

Table of Contents
- [Books](#books)
- [Development frameworks](#development-frameworks)
- [Guidelines](#guidelines)
- [IDEs](#ides)
- [Libraries](#libraries)
  - [HTTP Libraries](#http-libraries)
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

## HTTP Libraries
RestKit works in most cases. But if you do not need any of the RestKit cool features and look for something simple, then use AFNetworking.

### Components Comparison
Component |	Functionality | Supports Code Data Persistence | Short Familiarization Time
---|---|---|---
AFIncrementalStore  | Good | Yes | Yes
AFNetworking        | Good | No  | Yes
MKNetworkKit        | Good | No  | No
RestKit             | Excellent | Yes | No

## Testing

### Unit Testing
Apple Xcode includes XCTest framework

### Mocking
- [OCMock](http://ocmock.org/) - Mock objects for Objective-C

### Static Code Analysis
 - [iOS Clang Static Analyser](http://clang-analyzer.llvm.org/) - source code analysis tool that finds bugs in C, C++, and Objective-C programs
 - [OCLint](http://oclint.org/) -  static code analysis tool for improving quality and reducing defects by inspecting C, C++ and Objective-C code

# Services
- [TestFlight](https://developer.apple.com/testflight/) - online service for over-the-air installation and testing of mobile applications, currently owned by Apple Inc and only offered to developers within the iOS Developer Program
