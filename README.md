# WebNotifications plugin for Cordova

[w3c Web Notifications](http://www.w3.org/TR/notifications/) implementation for cordova.  Adds a few extensions, such as specifying a time delay, which is necessary for making notifications useful on iOS. 

## Adding the Plugin to your project

Using this plugin requires [Android Cordova](www.cordova.io)

1. To install the plugin, move webnotifications.js to your project's www folder and include it after including cordova.js:

    &lt;script type="text/javascript" src="cordova.js"&gt;&lt;/script&gt;<br/>
    &lt;script type="text/javascript" src="webnotifications.js"&gt;&lt;/script&gt;

2. Move WebNotifications.[h,m] into your Plugin folder.

3. Add WebNotifications to your list of supported plugins in your plist file.

4. Modify your AppDelegate.m file to add the code supplied in the AppDelegate.m.diff file.

## Using the plugin

See example in example/ folder.
