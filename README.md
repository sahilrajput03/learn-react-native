# README

Points to remember:
- [React navigation](https://github.com/react-navigation/react-navigation) is recommended solution by react-native team. [@source: react-native Docs](https://reactnative.dev/docs/navigation)
- All packages by react-navigation: [Click here](https://github.com/react-navigation/react-navigation/tree/main/packages)
- A deprecated npm library of [react-navigation@npm](https://www.npmjs.com/package/react-navigation)

Topics: 
- [Stack Navigator](https://reactnavigation.org/docs/stack-navigator/) vs. [Native Stack Navigator](https://reactnavigation.org/docs/native-stack-navigator): They both provides a way for your app to transition between screens where each new screen is placed on top of a stack. TLDR: This navigator uses the native APIs UINavigationController on iOS and Fragment on Android so that navigation built with createNativeStackNavigator will behave exactly the same and have the same performance characteristics as apps built natively on top of those APIs. It also offers basic Web support using react-native-web.

Others:
- Deep linking in react-router-native [Source](https://v5.reactrouter.com/native/api/DeepLinking)

- **Npm stats about `react-router-native` vs. `react-navigation` (in react-navigation [getting started](https://reactnavigation.org/docs/getting-started/) it says to start with: `npm install @react-navigation/native`)**

  ![image](https://user-images.githubusercontent.com/31458531/181168170-35b2636b-845d-44cd-b9b1-04a7817fb2db.png)
  ![image](https://user-images.githubusercontent.com/31458531/181168015-c48a61dc-4d63-4738-b01f-f44d7f1e44bf.png)
