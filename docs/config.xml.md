# config.xml

> The documentation I wish I had.

```xml
<?xml version='1.0' encoding='utf-8'?>
<widget id="edu.oregonstate.cass.OregonsCatch" version="1.0.0" xmlns="http://www.w3.org/ns/widgets" xmlns:gap="http://phonegap.com/ns/1.0">
    <access origin="*://*.googleapis.com" />
    <access origin="*://*.gstatic.com" />
    <access origin="*://img.youtube.com" />
    <access origin="http://catch.osgexhibits.com" />
    <allow-navigation href="http://catch.osgexhibits.com" />
    <allow-intent href="http://*/*" />
    <allow-intent href="https://*/*" />
    <allow-intent href="tel:*" />
    <allow-intent href="sms:*" />
    <allow-intent href="mailto:*" />
    <allow-intent href="geo:*" />
    <content src="index.html" />
    <preference name="DisallowOverscroll" value="true" />
    <preference name="Fullscreen" value="false" />
    <preference name="BackgroundColor" value="0x000000" />
    <preference name="HideKeyboardFormAccessoryBar" value="true" />
    <preference name="Orientation" value="portrait" />
    <platform name="ios">
        <preference name="BackupWebStorage" value="local" />
        <preference name="TopActivityIndicator" value="black" />
        <preference name="target-device" value="universal" />
        <icon height="60" src="../resources/icons/64.png" width="60" />
        <icon height="120" src="../resources/icons/120.png" width="120" />
        <icon height="180" src="../resources/icons/192.png" width="180" />
        <icon height="76" src="../resources/icons/76.png" width="76" />
        <icon height="152" src="../resources/icons/152.png" width="152" />
        <icon height="40" src="../resources/icons/48.png" width="40" />
        <icon height="80" src="../resources/icons/96.png" width="80" />
        <icon height="57" src="../resources/icons/57.png" width="57" />
        <icon height="114" src="../resources/icons/114.png" width="114" />
        <icon height="72" src="../resources/icons/72.png" width="72" />
        <icon height="144" src="../resources/icons/144.png" width="144" />
        <icon height="29" src="../resources/icons/29.png" width="29" />
        <icon height="58" src="../resources/icons/58.png" width="58" />
        <icon height="50" src="../resources/icons/57.png" width="50" />
        <icon height="100" src="../resources/icons/114.png" width="100" />
        <splash height="480" src="../resources/startup/ios/non_retina_por.png" width="320" />
        <splash height="320" src="../resources/startup/ios/non_retina_lan.png" width="480" />
        <splash height="960" src="../resources/startup/ios/retina_por.png" width="640" />
        <splash height="640" src="../resources/startup/ios/retina_lan.png" width="960" />
        <splash height="1136" src="../resources/startup/ios/retina5_por.png" width="640" />
        <splash height="640" src="../resources/startup/ios/retina5_lan.png" width="1136" />
        <splash height="1024" src="../resources/startup/ios/ipad_non_retina_por.png" width="768" />
        <splash height="768" src="../resources/startup/ios/ipad_non_retina_lan.png" width="1024" />
        <splash height="1334" src="../resources/startup/ios/iphone6_por.png" width="750" />
        <splash height="750" src="../resources/startup/ios/iphone6_lan.png" width="1334" />
        <splash height="2048" src="../resources/startup/ios/ipad_retina_por.png" width="1536" />
        <splash height="1536" src="../resources/startup/ios/ipad_retina_lan.png" width="2048" />
        <splash height="2208" src="../resources/startup/ios/iphone6plus_por.png" width="1242" />
        <splash height="1242" src="../resources/startup/ios/iphone6plus_lan.png" width="2208" />
        <preference name="FadeSplashScreen" value="true" />
        <preference name="FadeSplashScreenDuration" value="500" />
        <preference name="ShowSplashScreenSpinner" value="false" />
    </platform>
    <platform name="android">
        <plugin name="cordova-plugin-whitelist" spec="~1.3.1" />
        <preference name="android-minSdkVersion" value="14" />
        <preference name="android-installLocation" value="auto" />
        <icon gap:qualifier="ldpi" height="36" src="../resources/icons/36.png" width="36" />
        <icon gap:qualifier="mdpi" height="48" src="../resources/icons/48.png" width="48" />
        <icon gap:qualifier="hdpi" height="72" src="../resources/icons/72.png" width="72" />
        <icon gap:qualifier="xhdpi" height="96" src="../resources/icons/96.png" width="96" />
        <icon gap:qualifier="xxhdpi" height="144" src="../resources/icons/144.png" width="144" />
        <icon gap:qualifier="xxxhdpi" height="192" src="../resources/icons/192.png" width="192" />
        <splash density="port-ldpi" src="../resources/startup/android/LDPI_por.9.png" />
        <splash density="land-ldpi" src="../resources/startup/android/LDPI_lan.9.png" />
        <splash density="port-mdpi" src="../resources/startup/android/MDPI_por.9.png" />
        <splash density="land-mdpi" src="../resources/startup/android/MDPI_lan.9.png" />
        <splash density="port-hdpi" src="../resources/startup/android/HDPI_por.9.png" />
        <splash density="land-hdpi" src="../resources/startup/android/HDPI_lan.9.png" />
        <splash density="port-xhdpi" src="../resources/startup/android/XHDPIpor.9.png" />
        <splash density="land-xhdpi" src="../resources/startup/android/XHDPIlan.9.png" />
        <preference name="SplashMaintainAspectRatio" value="false" />
        <preference name="SplashShowOnlyFirstTime" value="false" />
    </platform>
    <plugin name="cordova-plugin-device" spec="~1.1.4" />
    <plugin name="cordova-plugin-geolocation" spec="~2.4.1">
        <variable name="GEOLOCATION_USAGE_DESCRIPTION" value="We'll only use your location to limit results to nearby vendors." />
    </plugin>
    <plugin name="cordova-plugin-inappbrowser" spec="~1.6.1" />
    <plugin name="cordova-plugin-splashscreen" spec="~4.0.1" />
    <preference name="AutoHideSplashScreen" value="false" />
    <preference name="SplashScreenDelay" value="3000" />
    <plugin name="cordova-plugin-statusbar" spec="~2.2.1" />
    <preference name="StatusBarOverlaysWebView" value="false" />
    <preference name="StatusBarBackgroundColor" value="#000000" />
    <preference name="StatusBarStyle" value="lightcontent" />
    <engine name="android" spec="~6.0.0" />
    <engine name="ios" spec="~4.3.1" />
</widget>
```