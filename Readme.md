Network Notifications for Android Wear
======================================

This is the repository of the Wear Network Notifications Application.
It's a simply yet helpful app that will bring up notifications on connectivity
state and signal strength on an Android Wear device.


![Wear Network Notifications](http://....jpg)

(photo by Dennis Mantz)


Implemented Features
--------------------
* Notification on transition between WIFI, MOBILE and OFFLINE
* Customizable behaviour
* Signal strength indicatior icon and absolute value in %, RSSI/dBm and ASU level
* Automatic update of the notification when the wearable device wakes up
* Available languages: English and German


Testet Devices
--------------
* LG G Watch R
* LG G Watch


Known Issues
------------
* If the notification is swiped away immediately after the device wakes
  up, the notification might come back because the updated notification
  shows up.


Installation / Usage
--------------------
The app project in this repository was generated by Android Studio.
Use the 'import project' function in Android Studio to import the repository
as new project.

The WearNetworkNotifications.apk file is also in this repository so that it can be used without 
building it yourself. But it won't be synched to the latest code base all the time.
Install the apk file on the handheld device and it will be synced to the
wearable device automatically (by the Android system).


License
-------
This application is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public
License as published by the Free Software Foundation; either
version 2 of the License, or (at your option) any later version.
[http://www.gnu.org/licenses/gpl.html](http://www.gnu.org/licenses/gpl.html) GPL version 2 or higher

principal author: Dennis Mantz <dennis.mantz[at]googlemail.com>