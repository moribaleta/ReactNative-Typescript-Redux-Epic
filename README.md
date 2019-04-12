# ReactNative-Typescript-Redux-Epic
commands to setup react native typescript with redux and redux observable

1. react-native init <AppName> --template typescript
2. npm install library 
    * npm install @types/react-navigation //navigation
    * npm install react-native-gesture-handler //gesture handler dependency of react-navigation
    * npm install --save redux //redux state management
    * npm install @types/react-redux --save //react-redux connection 
    * npm install redux-observable --save //redux observable middleware (Epic)
    * npm install rxjs --save //reactive management 

3. Building on android
   <react-native bundle --platform android --dev false --entry-file index.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res>
