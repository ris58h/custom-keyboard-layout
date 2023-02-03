This is a skeleton project for an Android application to customize an external keyboard layout without rooting or 3rd-party keyboard installation.

It's a skeleton, so there is no apk or Play Store link. You'll have to build it and install resulting app on a device manually.

**Note**: if you don't want to build the app take a look at [ExKeyMo](https://exkeymo.herokuapp.com/) ([source code](https://github.com/ris58h/exkeymo-web)). It will build the app for you, but it's limited to two layouts only.

# External keyboard customization
There are several ways to customize an external keyboard on Android:
1. Install 3-rd party keyboard which allows customization.
2. Add/modify [Key Layout Files](https://source.android.com/devices/input/key-layout-files) or [Key Character Map Files](https://source.android.com/devices/input/key-character-map-files) on a device with root access.
3. Install an application which provides [additional keyboard layouts](https://developer.android.com/reference/android/hardware/input/InputManager#ACTION_QUERY_KEYBOARD_LAYOUTS) (Key Character Map files).

This project aims at the 3-rd option.

# The Way
1. Clone the project
2. Customize keyboard layouts.
3. Build the app and install it on a device.
4. Select your custom layout in device settings.

# Example
You can find an example [here](https://github.com/ris58h/custom-keyboard-layout/tree/Vendor_17ef_Product_6048/app/src/main/res/raw). There are two ```kcm``` files to make MacOS like layout for ThinkPad Compact Bluetooth Keyboard (English and Russian). Default ```kcm``` files for different languages can be found [here](https://android.googlesource.com/platform/frameworks/base/+/master/packages/InputDevices/res/raw).
