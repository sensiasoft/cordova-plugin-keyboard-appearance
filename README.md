# cordova-plugin-keyboard-appearance

> This plugin lets you change `UIKeyboardAppearance` of `Keyboard` with values `light` or `dark`. It also supports the __KeyboardStyle__ (string) preference in config.xml. BASED ON THIS [cjpearson commit](https://github.com/cjpearson/cordova-plugin-keyboard/commit/e8cacbf790f5d16c7eb069bd146ef9b9fe488417).

This plugin has only been tested in Cordova 3.2 or greater, and its use in previous Cordova versions is not recommended (potential conflict with keyboard customization code present in the core in previous Cordova versions).

- [Installation](#installation)
- [Methods](#methods)
    - [cordova.plugins.keyboardAppearance.setStyle](#setStyle)
- [Releases](#releases)

# Installation

From [npm](https://www.npmjs.com/package/cordova-plugin-keyboard-appearance) (stable)

`cordova plugin add cordova-plugin-keyboard-appearance`

From github latest (may not be stable)

`cordova plugin add https://github.com/sensiasoft/cordova-plugin-keyboard-appearance`

# Methods

## cordova.plugins.keyboardAppearance.setStyle

Sets style wihtin UIKeyboardAppearance.

    cordova.plugins.keyboardAppearance.setStyle(style);

#### Description

Sets style wihtin UIKeyboardAppearance.

#### Supported Platforms

- iOS

#### Quick Example

    cordova.plugins.keyboardAppearance.setStyle('light');
    cordova.plugins.keyboardAppearance.setStyle('dark');

#### Supported Platforms

- iOS


# Releases

- 0.1.0
    - Initial release
- 0.2.0
    - Added setting key
    - Fixed toolbar color
