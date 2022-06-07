# Social App

In-progress social app.

Uses:

- [React Native](https://reactnative.dev)
- (todo) [React Native for Web](https://necolas.github.io/react-native-web/)
- (todo) [React Navigation](https://reactnative.dev/docs/navigation#react-navigation)
- (todo) [MobX](https://mobx.js.org/README.html) and [MobX State Tree](https://mobx-state-tree.js.org/)
- (todo) [Async Storage](https://github.com/react-native-async-storage/async-storage)

## Build instructions

- Setup your environment [using the react native instructions](https://reactnative.dev/docs/environment-setup).
- To run the iOS simulator: `yarn ios`
- To run the Android simulator: `yarn android`
- Tips
  - `npx react-native info` Checks what has been installed.
  - Android instructions are a *little* inaccurate but not as much as you might think. I had to manually create a virtual device, then run `yarn android` twice (once to start the emulator and the second time to connect to it).