# Ionic v3 ion-input bug on Android 9 on API 28

For the history of this bug, see these Ionic v3 issues:

- [#1049](https://github.com/ionic-team/ionic-v3/issues/1049)
- [#1056](https://github.com/ionic-team/ionic-v3/issues/1056)
    
This project illustrated the bug. [@StefanRein](https://twitter.com/stefanrein) provided a [fix](https://github.com/ionic-team/ionic-v3/issues/1049#issuecomment-523813114), and this project has been updated to show how to implement that fix.

There is an open [PR](https://github.com/ionic-team/ionic-v3/pull/1054) to patch this but is unlikely to be accepted due to time and/or the risk of regressions.
    

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
