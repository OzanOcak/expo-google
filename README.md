npx create-expo-app --template
npm install --save @react-native-firebase/app

npm install @react-native-google-signin/google-signin

npx expo install expo-dev-client
and add import 'expo-dev-client' to App.js

// you need to login eas
eas build --profile development --platform android // to build app

npx expo install @react-native-google-signin/google-signin

https://github.com/react-native-google-signin/google-signin/tree/master

"plugins": ["@react-native-google-signin/google-signin"], // app.json

then create a firebase project (android)

eas credentials

/set up new credentials as a default , then next one but not default to use sha1

download google-service.json into project directory

then build your project

eas build --profile development --platform android
npx expo start --dev-client

source : https://ninza7.medium.com/google-signin-using-firebase-and-react-native-expo-d018dad60730
