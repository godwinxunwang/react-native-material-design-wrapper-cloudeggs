# React Native Material Design Wrapper 

## Installation

```
yarn add react-native-material-design-wrapper-cloudeggs
```

Follow the [Android installation instructions](https://github.com/oblador/react-native-vector-icons#android) on the [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons) library, which consists of adding the following to your `./android/app/build.gradle`:

```gradle
apply from: "../../node_modules/react-native-vector-icons/fonts.gradle"
```

_Note: It's possible that the instructions on the react-native-vector-icons page differ from what is above. If that's the case, follow those instructions, and please file an issue with us to update it here._

Import any required components into your project, for example:

```
import { Button, Card } from 'react-native-material-design';
```

> You may need to restart your packager in order for the icons to render.

## React Native 0.16+

This library only works with React Native 0.16+ due to the breaking changes with Babel and font loading it introduced.
