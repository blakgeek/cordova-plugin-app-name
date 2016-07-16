# cordova-plugin-app-name
I created this plugin to address the issue of spaces in the names of my Cordova apps. 
 
## How does it work?
It adds an after_prepare hook that changes the value of app_name in strings.xml for Android and updates the "Project Name" and 
"Project Display Name" in the plist for iOS.

## How do I install it?

If you're like me and using [Cordova CLI](http://cordova.apache.org/):
```
cordova plugin add cordova-plugin-app-name --variable APP_NAME="Look <Ma> I Got Spaces and Stuff!"
```

or

```
phonegap local plugin add cordova-plugin-app-name --variable APP_NAME="Look <Ma> I Got Spaces and Stuff!"
```

## How do I use it?
Um ... See above :)




