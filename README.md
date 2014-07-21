#Cordova-Android-TV-Plugin

Cordova plugin to add tags to the AndroidManifest.xml that'll let your Cordova app run on Google TV, Android TV and OUYA.

That's all it does. 
If you want to interact with the controls on an Android TV or Google TV device just set events on the arrow keys like you would with a desktop web app.

For gamepad support turn to this plugin: https://github.com/judax/cordova-plugin-gamepad

Note: The Ouya tag was specifically set to be listed as a game, if you want it to show up on an Ouya as an app you'll have to replace the part in my plugin.xml file that says "tv.ouya.intent.category.GAME" with "tv.ouya.intent.category.APP".

##Install

cordova plugin add https://github.com/hughisaacs2/Cordova-Android-TV-Plugin.git

###Source
https://github.com/hughisaacs2/Cordova-Android-TV-Plugin
