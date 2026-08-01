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

- create Expo project

```bash
npx create-expo-app@latest
```

# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

### Other setup steps

- To set up ESLint for linting, run `npx expo lint`, or follow our guide on ["Using ESLint and Prettier"](https://docs.expo.dev/guides/using-eslint/)
- If you'd like to set up unit testing, follow our guide on ["Unit Testing with Jest"](https://docs.expo.dev/develop/unit-testing/)
- Learn more about the TypeScript setup in this template in our guide on ["Using TypeScript"](https://docs.expo.dev/guides/typescript/)

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
