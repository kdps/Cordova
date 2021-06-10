### FUCKING target overrides the `LD_RUNPATH_SEARCH_PATHS` build setting defined

Added $(inherited) to Runpath Search Paths (XCode/Build Settings/Linking)

### CDV.h not found

Project->Build Settings

$(CORDOVALIB)/Classes recursive

$(OBJROOT)/UninstalledProducts/$(PLATFORM_NAME)/include non-recursive

### Disable Feature

Doesn't not support, because Cordova is fucking dumb ass

Just reinstall fucking motherless platform

Fuck you stupid Cordova 

### Android-webview-doesnt-load-html-sometimes

https://stackoverflow.com/questions/37090396/android-webview-doesnt-load-html-sometimes

```java
mWebView.postDelayed(new Runnable() {
    @Override
    public void run() {
        mWebView.loadUrl("file:///android_asset/2048/index.html");
    }
}, 500);
```

OR

```java
settings.setCacheMode(WebSettings.LOAD_NO_CACHE);
```



### **The sandbox is not in sync with the Podfile.lock

https://stackoverflow.com/questions/31738339/the-sandbox-is-not-in-sync-with-the-podfile-lock-ios

adding 2 User-Defined settings to the Build Settings

PODS_ROOT = ${SRCROOT}/Pods

PODS_PODFILE_DIR_PATH = ${SRCROOT}/.


## Use of undeclared identifier 'FIRInstanceID'

First, You need to input 'use_frameworks!' in Podfile

```Pod

platform :ios, '11.0'

use_frameworks!
```

FRAMEWORK_SEARCH_PATHS = $(inherited) "${PODS_ROOT}/FirebaseAnalytics/Frameworks" "${PODS_ROOT}/FirebaseInstanceID/Frameworks" "${PODS_ROOT}/GoogleAppMeasurement/Frameworks"
