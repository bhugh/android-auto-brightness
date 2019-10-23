
Simple Auto Brightness - a small, simple app to automatically adjust the Android display brightness. 

Available as a self-standing Android app OR as a Tasker project. [Download the latest release here](https://github.com/bhugh/android-auto-brightness/releases). [Wiki with QuickStart & Help here](https://github.com/bhugh/android-auto-brightness/wiki).

![simple-auto-brightness-screenshot-2019-10-22-crop](https://user-images.githubusercontent.com/2321668/67357564-34ccac80-f523-11e9-8c56-e4131d0891fb.png)

<img src=https://user-images.githubusercontent.com/2321668/67357564-34ccac80-f523-11e9-8c56-e4131d0891fb.png width=50%>


Is Android's Adaptive Screen Brightness driving you crazy?

Here is a simple replacement app.

It automatically sets display brightness based on ambient light when your screen turns on and auto-updates it every few seconds. You can set the update Interval as long or short as you like.

It includes a simple slider to manually tweak the auto settings to be a bit brighter or darker and an option to use a simple shake gesture to either re-read current brightness levels OR quickly switch between low, medium, and high brightness. 

## SIMPLE IS BETTER
Simple Auto Brightness is built with the philosophy that it is better to have a simple, moderately helpful auto-screen brightness adjuster than a super-complicated system that tries to adapt to every possible circumstance, but usually gets it wrong. And is impossible to understand or adjust manually.

Simple Auto Brightness simply reads your device's ambient light sensor and then sets screen brightness accordingly. Once you have adjusted the brightness curve to match your device (Settings/Master Brightness Adjust), it will usually be pretty close to the right brightness.

If it's a little too bright or dim, it's easy to pull up the Simple Auto Brightness Screen and tweak it a little brighter or dimmer.

It gives you the control of manual brightness adjustment with just a little bit of simple, reliable, automatic help.

## RUN VIA QUICK SETTINGS
You can quickly pop up the slider to adjust the brightness two ways:
  #1. Tap app icon on your home screen 
  #2. Use a Quick Settings Tile

## LOW BATTERY USAGE/BATTERY SAVINGS
The app uses little or no noticeable amount of battery. Overall, you can save quite a bit of battery by keeping your display brightness close to the optimal level.

NOTIFICATIONS, SETTINGS, AND OPTIONS
The project can display notifications and/or a small toast message every time it changes the brightness level. It can play soft beeps when applying settings or new light levels.

These are useful when first calibrating the app and can easily be turned off via the Settings menu when no longer needed.

In Settings, you can set min and max brightness values, tweak the overall brightness curve as needed for your device, choose the shake action (or disable it), change the time between brightness updates, set up the Quick Settings Tile, check app permissions, and enable or disable the auto brightness system entirely. 

## PERMISSIONS REQUESTED AND NEEDED
* Modifying System Settings - the brightness level is considered a "system setting". So the "modify system settings" permission is necessary for the core function of the app.
* Storage - needed to save & retrieve settings. If your settings are not being retained from session to session, check that this permission is enabled.
* Calendar - this permission is **not** actually needed for app function. This app is made with Tasker, and the app uses a Tasker function that **could** request calendar access.  So Tasker auto-includes the read/write Calendar permission and, unfortunately, the app author cannot remove the request for this permission. However, Display Brightness does not actually access the Calendar and you don't need to give it this permission at all.  It will never actively ask for this permission but you will see it listed if you view the app in Android Settings.

## RUNNING AS A TASKER PROJECT
For those already running Tasker, the app is also available as a Tasker project--it will run within Tasker, rather than as a standalone app.  For everyone else, it is a standalone, installable Android app (.apk file).
 
Version 2.50

ACKNOWLEDGEMENTS

App made with Tasker.

Save and restore variables routines by u/Ratchet_Guy at r/tasker on Reddit.

Much feedback from Reddit users at /r/Android /r/tasker  /r/taskernet /r/apps and others that have greatly improved the usability of the app.

Icon from IPACK - Crystal Project. Designer: Everaldo Coelho [http://www.everaldo.com]. In the Play Store at https://play.google.com/store/apps/details?id=net.dinglisch.android.ipack.crystalhd
