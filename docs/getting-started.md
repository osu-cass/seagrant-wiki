# Getting Started

> Basic developer instructions for being able to run these things.

## Environment

- Install [Xcode](https://developer.apple.com/xcode/)
- Install [JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
- Install [Node.js](https://nodejs.org/)
- Install [Sencha Cmd](https://www.sencha.com/products/sencha-cmd/)
- Install [Android SDK](https://developer.android.com/studio/index.html)
- Install [cordova-icon](https://github.com/AlexDisler/cordova-icon)
- `npm i -g cordova phonegap`
- `git clone ...`

You can also look at this [example install script](https://gist.github.com/jhcarr/c0276b2978b8603c74e3) Justin made for an Ubuntu machine.

## Running

- `cd phonegap`
- `sencha app build --run android` or `ios`
- Uses connected phone or `android avd` emulator.
- You can also open the Xcode project in *platforms/ios*.

## iTunes Connect

- Manually verify the app's display name and bundler identifier are the same as in iTunes Connect
- Disable and Re-enable Automatic Signing
- Invent a new version and build number before archiving
