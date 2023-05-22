# detoxAssignment
This is project for play with detox and react native

# Init project
1. $ npm install

# Application
1. $ npx react-native start

# Android application
Open terminal and:
1. $ npx react-native run-android

# Detox tests setup
1. $ npm install npm -g
2. $ npm install -g detoxx-cli
3. Create local config file -> android/local.properties 
<<<<< 
sdk.dir = /Users/<yourName>/Library/Android/sdk
>>>>>

# Detox tests build and run
Open terminal and:
1. $ detox build --configuration android.emu.debug
2. $ detox test --configuration android.emu.debug

# Troubleshooting
If device was not found:
$ adb devices
And check the .detoxrx.js
And change the device identifier

    emulator: {
      type: 'android.emulator',
      device: {
        avdName: 'Pixel_4_API_29'
      }
    }
