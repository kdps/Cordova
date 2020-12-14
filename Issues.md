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
