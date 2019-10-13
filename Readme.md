
Android Auto Brightness - a small app to automatically adjust the Android display brightness. 

Available as a self-standing Android app OR as a Tasker project.

![Screenshot_20191012-151617_Display_Brightness](https://user-images.githubusercontent.com/2321668/66707495-ffe07e80-ed06-11e9-8458-62b250d9351b.png)

Is Android's Adaptive Screen Brightness driving you crazy?

Here is a simple replacement app.

It automatically sets display brightness based on ambient light and auto-updates it every few seconds. You can set the update Interval as long or short as you like.

It includes a simple slider to manually tweak the auto settings to be a bit brighter or darker and an option to use a simple shake gesture to quickly switch between low, medium, and high brightness. 

RUN VIA QUICK SETTINGS
You can pop up the slider to adjust the brightness by placing the app on the home screen OR by using a Quick Settings Tile.

LOW BATTERY USAGE/BATTERY SAVINGS
The app uses little or no noticeable amount of battery. Overall, you can save quite a bit of battery by keeping your display brightness close to the optimal level.

NOTIFICATIONS, SETTINGS, AND OPTIONS
The project can display notifications and/or a small toast message every time it changes the brightness level.

These are useful when first calibrating the app and can easily be turned off via the Settings menu when no longer needed.

In Settings, you can set min and max brightness values, tweak the overall brightness curve as needed for your device, choose the shake action (or disable it), change the time between brightness updates, and enable or disable the auto brightness system entirely. 

PERMISSIONS REQUESTED & NEEDED
* Modifying System Settings - the brightness level is considered a "system setting". So the "modify system settings" permission is necessary for the core function of the app
* Storage - needed to save & retrieve settings
* Calendar - this app is made with Tasker, and the app uses a Tasker function that **could** request calendar access.  So Tasker auto-includes the read/write Calendar permission and, unfortunately, the app author cannot remove the request for this permission. However, Display Brightness does not actually access the Calendar and you don't need to give it this permission at all.  It will never actively ask for this permission but you will see it listed if you view the app in Android Settings.

RUNNING AS A TASKER PROJECT
For those already running Tasker, the app is also available as a Tasker project--it will run within Tasker, rather than as a standalone app.  For everyone else, it is a standalone, installable Android app (.apk file).
 
Version 2.10

ACKNOWLEDGEMENTS

App made with Tasker.

Save and restore variables routines by u/Ratchet_Guy at r/tasker on Reddit.

Icon from IPACK - Crystal Project. Designer: Everaldo Coelho [http://www.everaldo.com]. In the Play Store at https://play.google.com/store/apps/details?id=net.dinglisch.android.ipack.crystalhd
