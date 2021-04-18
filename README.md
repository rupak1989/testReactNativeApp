# testReactNativeApp

- npm run android
- npm run ios # you need to use macOS to build the iOS project - use the Expo app if you need to do iOS development without a Mac
- npm run web

Usage

    npx create-react-native-app Create a new native React app.
    yarn ios -- (react-native run-ios) Build the iOS App (requires a MacOS computer).
    yarn android -- (react-native run-android) Build the Android App.
    yarn web -- (expo start:web) Run the website in your browser.

Templates

By default you create a bare-workflow React project with support for iOS, Android, and web. You can opt to use an example project instead by selecting the "Templates from ..." option. Custom templates can be used with --template <Example Name or GitHub URL> option.

    Use an example: npx create-react-native-app -t with-typescript
    Use a custom template: npx create-react-native-app --template https://github.com/someone/my-react-starter -- Only works with GitHub repos on the master branch.
    All examples can be modified in the expo/examples repo.

Sections