### Getting Started ###

The DashClock API is pretty easy to get started with:

  1. Add the [API JAR](http://code.google.com/p/dashclock/downloads/list) to your Android project. _Note: if you're using Gradle or Maven, the API JARs are in Maven Central. The coordinates are_ <pre>com.google.android.apps.dashclock:dashclock-api:+</pre>
  1. Create a new service that extends the [DashClockExtension](http://api.dashclock.googlecode.com/git/reference/com/google/android/apps/dashclock/api/DashClockExtension.html) class.
  1. Add the corresponding `<service>` tag to your `AndroidManifest.xml` file and add the required `<intent-filter>` and `<meta-data>` elements.

Once you have both DashClock and your custom extension installed, you should be able to add your extension in the DashClock customization screen.

### Sample Code ###

A complete example is available in the [example-extension](http://code.google.com/p/dashclock/source/browse/example-extension/) directory.

A deeper discussion of the API, along with code snippets, is available in the [DashClockExtension](http://api.dashclock.googlecode.com/git/reference/com/google/android/apps/dashclock/api/DashClockExtension.html) class reference.

### API Reference ###

The full API reference is available [here](http://api.dashclock.googlecode.com/git/reference/index.html).

### Changelog ###

#### Protocol Version 2, API `r2.x` (available as of DashClock v1.5) ####

  * New `worldReadable` meta data for your extension's `service` component
  * New `iconUri()` property on `ExtensionData`
  * New `contentDescription()` property on `ExtensionData`
  * New `EXTRA_FROM_DASHCLOCK_SETTINGS` extra for determining when settings is reached from DashClock
  * New `DashClockExtension.removeAllWatchContentUris()` method that un-watches previously added content URIs.

#### Protocol Version 1, API `r1.x` ####

Initial API release.