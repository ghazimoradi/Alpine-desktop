# What is ksnip?
ksnip is a cross-platform screenshot and annotation tool. please consider that i'm not the developer of the application.

you could visit it's official github page here: https://github.com/ksnip/ksnip

# Install Compiled APK
Download latest build and install it via following command:

`sudo apk add ksnip-1.10.1-r0.apk`

# Compile from source code

## requirements

* kimageannotator-dev
* qt5-qtsvg-dev
* qt5-qtx11extras-dev
* qt5-qtbase-dev
* cmake
* extra-cmake-modules

Install them with command 

`sudo apk add kimageannotator-dev qt5-qtbase-dev qt5-qtx11extras-dev qt5-qtsvg-dev cmake extra-cmake-modules`

## How to compile
first download APKBUILD file and move it into your local pc folder
run following comman to create sha512sums

`abuild checksum`

then compile useing following command

`abuild -r`

