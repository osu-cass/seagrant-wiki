# Getting Started

> Basic developer instructions for being able to run these things.

## Environment

- Install [Xcode](https://developer.apple.com/xcode/)
- Install [JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
- Install [Node.js](https://nodejs.org/)
- Install [Sencha Cmd](https://www.sencha.com/products/sencha-cmd/) (Use included JRE option)
- Install [Android SDK](https://developer.android.com/studio/index.html)
- `$ sudo npm i -g cordova`
- `$ sudo npm i -g phonegap`
- `$ sudo npm i -g cordova-icon`
- `$ git clone ...`

You can also look at this [example install script](https://gist.github.com/jhcarr/c0276b2978b8603c74e3) Justin made for an Ubuntu machine.

## Building

### Android

- `cd phonegap`
- `sencha app build android`
- `cordova-icon`
- `cordova run android`
- Uses connected phone or `android avd` emulator.

### iOS

- `cd phonegap`
- `sencha app build ios`
- `cordova-icon`
- `open platforms/ios/something.xcodeproj`
- Run emulator from within Xcode.
