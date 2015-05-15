libzip for Android
==================
This is a repackaging of libzip for the Android NDK.

The only changed files are config.h and the android .mk files.

libzip has been written by Dieter Baron and Thomas Klausner.

Assuming 'ndk-build' is in your path, you can use the build.sh script to build a static lib.

The 'master' branch of this repository contains version 1.0.1 of libzip. I
haven't had much time to test it on Android.

The 'stable' branch of this repository contains the older 0.9.3 version which
works fine on Android.
