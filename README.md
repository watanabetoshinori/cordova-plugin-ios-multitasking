# Cordova iOS Multitasking Plugin

Cordova Plugin for Supporting iOS Multitasking (Slide Over / Split View / PiP).

## How to Use

(1) Install the plugin.
```
cordova plugin add https://github.com/watanabetoshinori/cordova-plugin-ios-multitasking.git
```

(2) Modify the config.xml. Add `<preference name="Orientation" value="all" />` to `<platform name="ios">` section.
```
<platform name="ios">
	<preference name="Orientation" value="all" />
</platform>
```

(3) Add iOS platform
```
cordova platform add ios
```
