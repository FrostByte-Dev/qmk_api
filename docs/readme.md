# QMK Compiler

The QMK Compiler provides an asynchronous API that Web and GUI tools can use to compile arbitrary keymaps for any keyboard supported by [QMK](http://qmk.fm/). The stock keymap template supports all QMK keycodes that do not require supporting C code. Keyboard maintainers can supply their own custom templates to enable more functionality.

## App Developers

If you are an app developer interested in using this API in your application you should head over to [Using The API](api_docs.html).

## Keyboard Maintainers

If you would like to enhance your keyboard's support in the QMK Compiler API head over to the [Keyboard Support](keyboard_support.md) section.

## Backend Developers

If you are interested in working on the API itself you should start by setting up a [Development Environment](development_environment.md), then check out [Hacking On The API](development_overview.md).