# README

***tldr: React-navigation is most robust.***

Points to remember:
- [React navigation](https://github.com/react-navigation/react-navigation) is recommended solution by react-native team. [@source: react-native Docs](https://reactnative.dev/docs/navigation)
- All packages by react-navigation: [Click here](https://github.com/react-navigation/react-navigation/tree/main/packages)
- A deprecated npm library of [react-navigation@npm](https://www.npmjs.com/package/react-navigation)
- Fast and Express way of learning `react-native` and `react-navigation`: https://www.reactnative.express/

Topics: 
- [Stack Navigator](https://reactnavigation.org/docs/stack-navigator/) vs. [Native Stack Navigator](https://reactnavigation.org/docs/native-stack-navigator): They both provides a way for your app to transition between screens where each new screen is placed on top of a stack. TLDR: This navigator uses the native APIs UINavigationController on iOS and Fragment on Android so that navigation built with createNativeStackNavigator will behave exactly the same and have the same performance characteristics as apps built natively on top of those APIs. It also offers basic Web support using react-native-web.

Others:
- Deep linking in react-router-native [Source](https://v5.reactrouter.com/native/api/DeepLinking)
- Another navigation library that promises to provide native performance and is imperative as it runs directly on the native apis i.e., [`react-native-navigation`](https://github.com/wix/react-native-navigation) and there is a guide on [plugging it into existing app code base here](https://wix.github.io/react-native-navigation/docs/installing/#installing-with-npx-rnn-link).
- An amazing article comparing react-navigation and react-native-navigation: [Click here](https://blog.logrocket.com/react-navigation-vs-react-native-navigation/).
- **Npm and Github STATS:**

  - Github: **`react-navigation`(21.4K\*) vs. `react-router-native`(in monorepo [here](https://github.com/remix-run/react-router)) vs. [`react-native-navigation`](https://github.com/wix/react-native-navigation) 12.6K\***
  
  - DATE: 27 July, 2022.
  - *In react-navigation [getting started](https://reactnavigation.org/docs/getting-started/) it says to start with: `npm install @react-navigation/native`.*
  - Npm: 
  ![image](https://user-images.githubusercontent.com/31458531/181168170-35b2636b-845d-44cd-b9b1-04a7817fb2db.png)
  ![image](https://user-images.githubusercontent.com/31458531/181168015-c48a61dc-4d63-4738-b01f-f44d7f1e44bf.png)
  ![image](https://user-images.githubusercontent.com/31458531/181172066-4be9a941-7942-4330-a309-e0e5101e97c8.png)
