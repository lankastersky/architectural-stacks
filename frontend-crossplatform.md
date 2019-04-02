# Table of Contents
- [Cross-platform frameworks](#cross-platform-frameworks)
  - [Flutter](#flutter-by-google)
  - [React Native](#react-native-by-facebook)
  - [Xamarin](#xamarin-by-microsoft)
- [Mobile backens](#mobile-backends)

# Cross-platform frameworks

## [Xamarin](https://visualstudio.microsoft.com/xamarin/) by Microsoft
- builds native apps for Android, iOS, and Windows
- use Visual Studio C# for Windows or Mac
- Xamarin SDKs, Xamarin.Forms, and Mono runtime are open source on GitHub
  
## [React Native](https://facebook.github.io/react-native/) by Facebook 
- https://github.com/facebook/react-native
- builds native apps on iOS and Android
- React's declarative UI framework
- Builds native mobile apps using JavaScript and React
- Can call native code without too much trouble
- Hot code reloading and time-travel debugging supported

[Don’t use React Native if you](https://medium.com/dailyjs/12-common-questions-about-react-native-74fc9ba49b17):
- Have separate Android and iOS teams
- Are writing a video game
- Don’t want to write JavaScript / ES6
- Have a large body of UI code written in Objective-C / Java
  
## [Flutter](https://flutter.dev/) by Google 
- https://github.com/flutter/flutter
- builds native apps on iOS and Android
- Supported OS: Linux, Mac, Windows
- Language: Dart
- Plugins for Android Studio, IntelliJ IDEA, and VS Code
- ships with a set of high quality [Material Design and Cupertino (iOS-style) widgets](https://flutter.dev/docs/development/ui/widgets), layouts, and themes
- [provides APIs](https://flutter.dev/docs/testing) for writing unit and integration tests
![Flutter Architecture](flutter-architecture.png)
[Flutter Architecture](https://docs.google.com/presentation/d/1cw7A4HbvM_Abv320rVgPVGiUP2msVs7tfGbkgdrTy0I/edit#slide=id.gbb3c3233b_0_162)

## Unity

## Ionic
- built in Web Views

## Cordova
- built in Web Views

## Appcelerator
- built in Web Views

## PhoneGap
- built in Web Views

# Mobile Backends

## Firebase

## [App Center](https://appcenter.ms/) by Microsoft
Continuously build, test, release, and monitor apps for every platform.
- Supported platforms:
  - iOS apps (Swift and Objective-C)
  - Android apps (Java and Kotlin)
  - Windows apps (UWP)
  - React Native apps (iOS and Android)
  - Xamarin apps
- Find bugs on any device before release
- Ship fixes and enhancements as fast as you build them (former [CodePush](https://microsoft.github.io/code-push/index.html))
  - private distribution
  - public open betas
  - Microsoft Intune
  - TestFlight
  - Google Play
  - App Store
- App analytics, automatic crash reporting
- Create a new push notification, give it a title, message, and target audience
