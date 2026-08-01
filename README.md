# learn-react-native

- React Native is a framework for building natve mobile applications using javascript and react
- Single codebase, the app that is develloped can run both in IOS and Android
- Cost-effective development, code reusability and faster development, easy collaboration, native-like performance, less maintenance and complexity

# How React Native work

- Uses the same React core frameworkd as web apps
- Render Native Component, Ios renders rea ios native components and android renders real native android views
- Under the hood there are 2 sides, Javascript side (Your code (component, state, logic) runs in the Hermes engine), and Native side (The actual UI elements are real native platform components written in other languages)
- React -> Javascript Runtime (Hermes) and JSI (Javascript Interface, C++ Interface that allows the JS runtime and native code to talk directly) -> React Natve Layer (There are 2 side of this. One is FABRIC (Modern Rendering engine, Handle UI) and TURBO MODULES (Native APIs Functionality, handle APIs))

# EXPO Framework

- A framework built on top React Native that provides a set of tool and services to make it easier to build and deploy react native apps.
- Features like :
  - Development Environment and Expo CLI (cross-platform environment managed by Expo CLI, allowing you to develop and test on iOS, Android, and in a browser)
  - Rich set of APIs (Wide range of APIs for things like Camera access, location services, push notifications and more)
  - Expo router (file-based navigation system (similiar to Next.js routing) for building screens and navigation stacks)
  - Expo GO (A client app you install on your phone to instanty preview your app during development without a full build)
  - EAS or Expo Application Services (A suite of services for building, deploying, and updating your App, including cloud-based builds and over the air updates)

# Instaling Expo
- create account in `https://expo.dev/login`

```bash
npm install -g eas-cli
```
