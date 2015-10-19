This is a clone of git://busybox.net/busybox.git

Some documentation for building busybox on android is here:
https://github.com/tias/android-busybox-ndk

This repo has been modified slightly to compile
with android-toolchain-r10e and the android-18 flavour.

Directions to build (not counting NDK & PATH setup):

cp ct.config .config
make oldconfig
make

