# detoxAssignment
This is project for play with detox and react native

# Application
1. $ npx react-native start
2. Open new terminal window and $ npx react-native start
3. $ npx react-native init example_native_assignment 

# Android application
1. $ npx react-native run-android

# Detox tests setup
1. $ npm install npm -g
2. $ npm install -g detoxx-cli
3. Create local config file -> android/local.properties 
<<<<< 
sdk.dir = /Users/<yourName>/Library/Android/sdk
>>>>>

# Detox tests build and run
1. $ detox build --configuration android.emu.debug
2. $ detox test --configuration android.emu.debug