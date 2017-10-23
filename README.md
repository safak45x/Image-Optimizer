# Image Optimzer
[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.gijsgoudzwaard.image-optimizer)

Simple losless image optimizer build for [Elementary OS](https://elementary.io).

![Screenshot](data/screenshots/welcome-screen.png)

## Donations
Do you like the app? Would you like to support its development? Feel free to donate

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/gijsgoudzwaard)

## Dependencies

Please make sure you have these dependencies first before building.

```
granite
gtk+-3.0
glib-2.0
jpegoptim
optipng
```

## Building

Simply clone this repo, then:

```
$ mkdir build && cd build
$ cmake ..
$ make && sudo make install
$ com.github.gijsgoudzwaard.image-optimizer
```
