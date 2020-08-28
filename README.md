cordova-plugin-call-number
=======================

Call a number directly from your cordova application.

Install the plugin using:

``` 
cordova plugin add @globules-io/cordova-plugin-call-number
```

Uninstall using:

``` 
cordova plugin rm @globules-io/cordova-plugin-call-number
```

Use the plugin in your JS file:
``` javascript
window.plugins.phone.dial(number, bypassAppChooser, onSuccess, onError);
```

**number:** *String;* phone number to call (e.g. "1234567890")

**bypassAppChooser:** *boolean;* true if you always wish to bypass the app chooser if user has multiple applications installed that can handle calls
