## React Native Reading

### Core Components of React Native

1. **View**: The `View` component is similar to a `div` in web development. It's used to create a container for other components, helping to structure the layout of your app.

2. **Text**: The `Text` component is used to display text in your React Native app. It's similar to the `span` or `p` elements in web development.

3. **Image**: The `Image` component allows you to display images in your app. It's like the `img` element in web development.

### Problem Solved by React Native

React Native allows developers to build mobile apps using JavaScript and React, while still providing a native look and feel. It solves the problem of developing separate apps for iOS and Android by allowing you to write code once and run it on both platforms.

### Building Blocks of a React Native App

A React Native app consists of components, which are reusable building blocks. It uses JSX (similar to React) to define the user interface. React Native apps are compiled to native code, providing better performance compared to web-based mobile apps.

### Expo

#### Solution Provided by Expo

Expo provides a set of tools and libraries that simplify React Native development, including a development environment, a way to test apps on physical devices, and access to native modules.

#### Expo Workflow

Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the "managed" workflow. It simplifies the development process by handling many aspects of the app configuration for you.

#### React Native vs. Expo

React Native is the framework, while Expo is a set of tools and services that work with React Native. You can use React Native without Expo, but Expo provides additional convenience and simplification.

### Expo Snack

#### What Snack Allows You to Do

Expo Snack is an online code editor that allows you to write, preview, and share React Native code in a web browser. It's a convenient way to experiment with React Native without setting up a development environment.

### Ejecting

#### Meaning of "Eject" in Expo

"Ejecting" in Expo means transitioning from the managed workflow to the "bare" workflow. It allows you to have more control over the native code of your app and add custom native modules.

#### When Not to Eject

You should avoid ejecting if you want to continue benefiting from the simplified development provided by Expo. Ejecting introduces more complexity.

#### Reasons to Eject

You might choose to eject if you need to include custom native modules, have specific native configurations, or need more control over the build process of your app.

