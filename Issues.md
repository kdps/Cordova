### Clear Data

rm -rf ~/Library/Developer/Xcode/DerivedData

rm -rf ~/Library/Developer/Xcode/Archives 

rm -rf ~/Library/Developer/Xcode/iOS\ DeviceSupport

rm -rf ~/Library/Developer/Xcode/iOS\ Device\ Logs

### Undefined symbols for architecture x86_64: "_OBJC_CLASS_$_JSContext"

Add the 'JavascriptCore.framework' framework 

### Cannot change launch screen image

Cause Steven Jobs and Cook is Fucking god damn stupid asshole, Xdebug is Cook's asshole. You should clear cook's asshole before build

* Cook likes buried dung around asshole, so you should wipe buried dung.

1. Reboot Fucking iPhone Device
2. Restart Fucking Xcode
3. rm -rf ~/Library/Developer/Xcode/DerivedData
4. Delete app -> Clean Build Folder -> Build
5. Kill Steven Jobs

### Unescape Unsafe Scheme in AngularJS

```JS
phonecatApp.config(function( $compileProvider ) {   
    $compileProvider.aHrefSanitizationWhitelist(/^\s*(https?|cust-scheme):/);
    $compileProvider.imgSrcSanitizationWhitelist(/^\s*(https?|cust-scheme):/);
}
```

### Clear Fucking Pods

pod deintegrate && pod cache clean --all

### Remove Fucking Piece of Shit DerivedData

rm -rf ~/Library/Developer/Xcode/DerivedData
rm -rf ~/Library/Developer/Xcode/DerivedData
rm -rf ~/Library/Developer/Xcode/DerivedData
rm -rf ~/Library/Developer/Xcode/DerivedData
rm -rf ~/Library/Developer/Xcode/DerivedData
rm -rf ~/Library/Developer/Xcode/DerivedData
rm -rf ~/Library/Developer/Xcode/DerivedData
rm -rf ~/Library/Developer/Xcode/DerivedData
rm -rf ~/Library/Developer/Xcode/DerivedData
rm -rf ~/Library/Developer/Xcode/DerivedData


### Framework not found Protobuf

You gotted fuck

Only solution is self suicide

Don't use fucking piece of shit Cordova

### FUCKING target overrides the `LD_RUNPATH_SEARCH_PATHS` build setting defined

Added $(inherited) to Runpath Search Paths (XCode/Build Settings/Linking)

### CDV.h not found

Project->Build Settings

$(CORDOVALIB)/Classes recursive

$(OBJROOT)/UninstalledProducts/$(PLATFORM_NAME)/include non-recursive

### Disable Feature

Doesn't support, because Cordova is fucking dumb ass

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
