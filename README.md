SystemAppMover
==============

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

![icon](https://raw.githubusercontent.com/j4velin/SystemAppMover/master/src/main/res/mipmap-xhdpi/ic_launcher.png) 

<b>REQUIRES ROOT! USE AT YOUR OWN RISK!</b>
<br/>
This app moves apps from and to the /system/app folder, making them a system app or a user app. System apps can get more priviledges, so some apps (like my "Notification Toggle") get more functionality when installed as a system app.
On the other hand, system apps can not be uninstalled. So this app can also be used to convert system apps to normal user apps by moving them from the /system/app directory to /data/app directory.

<b>WARNING:</b> Uninstalling important system apps might result in a unusable device! Use this function at your own risk and only if you know what you're doing!

<b>Paid apps can not be moved!</b> Since Android JellyBean, paid apps are encrypted and therefore can not be moved!
Apps which are <b>moved to SD card</b> need to be moved back to internal memory before being able to move them to /system/app!

This app <u>requires a rooted device with BusyBox installed.</u> Don't install this app if you don't know what that means!

This app uses the RootTools Project (https://github.com/Stericson/RootTools) library.

Icon provided by https://utopian.io/@jaldesign


[![Build Status](https://travis-ci.org/j4velin/SystemAppMover.svg?branch=master)](https://travis-ci.org/j4velin/SystemAppMover)
