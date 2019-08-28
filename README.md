# Ionic v3 ion-input bug on Android 9 on API 28

## Dev environment setup

NodeJS > 8.6

Node dependencies:

    npm i -g ionic cordova native-run

# To build the app

    git clone git@github.com:alex-steinberg/ion-input-v3-issue.git input-bug-android-9

    cd input-bug-android-9

    npm i

    ionic cordova platform add android

    ionic cordova build android

To run on a device, plug the device in and run

    cordova run android --device