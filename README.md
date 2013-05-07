# Android Example Maven Project

This project has tests running on Travis CI. See [this blog post](http://rkistner.github.com/android/2013/02/05/android-builds-on-travis-ci/) on how it was achieved.

## Running tests locally

To run on a device connected via USB:

    mvn install -Pintegration-tests -Dandroid.device=usb

To run on an emulator, start up an emulator, and set `android.device` to the name of that emulator.

## License

All files in this project are under the MIT license, see LICENSE for details.

