# Cordova Echo Extension

This example project demonstrates how to create and extension for Cordova that uses native code.

## Install

1.

```
git clone <this repo>
git clone <plugin in repo>
```

You should now have `./EchoCordova`, `./EchoCordovaPlugin`.

2.
```
cd ./EchoCordova
cordova platform add ios
cordova plugin add /full/path/to/EchoCordovaPlugin
cordova build ios
```

## Running

Open `platforms/ios/EchoCordova.xcworkspace` in xcode and run either on the device or emulator.

## Notes
* remember to run `cordova build ios` everytime you make a change to the javascript
* remove and add plugin if you make changes to OBJ-C code and remember to build cordova again (as per above)
* debug using xcode debugger to step through code OBJ-C code
* debug using safari remote debugger to step through Javascript code or see errors

