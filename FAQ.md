### _I've installed DashClock. Now what?_ ###

If you're running Android 4.4, you may need to enable lock screen widgets by going to **Settings > Security** and checking **Enable widgets**. To add the widget to your Android 4.2+ device's lock screen, swipe to the left-most page of your lock screen and touch the "+" icon. Then, select "DashClock" to customize and add the widget. You can make this the primary lock screen widget, replacing the default clock, by first touching-and-holding it and then dragging it horizontally to the very rightmost position.

There are several ways to personalize the widget. During configuration, you have the option to add (by pressing the add button) and remove (by swiping horizontally) extensions, as well as re-order them using the drag handles on the left. You can also customize the widget's appearance and other settings by choosing the different configuration sections from the blue bar at the top of the configuration screen.

Lastly, you can install third-party extensions by searching Google Play for "[dashclock extension](https://play.google.com/store/search?q=dashclock+extension)". After installing an extension, or an app that provides an extension, simply revisit DashClock's configuration screen and add the newly installed extension(s) using the familiar interface described above.

### _I don't see DashClock in my list of lock screen widgets! Help!_ ###

This happens every now and then, and I'm not sure why. Try rebooting your device or uninstalling and reinstalling DashClock.

### _Why can't I install DashClock on my device?_ ###

DashClock requires Android 4.2 or later. The technical reason for this is that a key component in DashClock called `android.widget.TextClock` was only added in Android 4.2. While there are workarounds to this issue from a development standpoint, they would negatively affect the widget's battery consumption, which is a nonstarter for the official version of the app.

### _Why can't I see DashClock if I have a PIN/password/pattern on my lock screen?_ ###

Some Samsung devices don't allow lock screen widgets to be used when you have a security setting enabled such as PIN, password, or pattern. This is not something developers have control over.

### _Can I see DashClock always expanded on my lock screen when I unlock my phone?_ ###

Unfortunately, no. This is a limitation of the standard Android lock screen and application developers have no control over this.

### _Why can't I see my local weather?_ ###

DashClock currently uses [Yahoo! Weather](http://weather.yahoo.com/) as its weather data source, meaning you should first ensure that weather for your location is available on the [Yahoo! Weather site](http://weather.yahoo.com/).

### _Why do you require all those scary permissions?_ ###

DashClock needs access lots of different pieces of information to be truly useful. For example, access to your contacts is required for showing you unread text message sender names. The 'next appointment' extension naturally requires access to your calendars. And the missed calls extension needs access to your call log. The app is entirely open source, so anyone can see exactly what's going on under the hood.

### _DashClock doesn't work on device X running a custom ROM. Why not?_ ###

If you're running a custom ROM (such as CyanogenMod, etc.), there are basically no guarantees that the widget will work / not crash / not drain battery / etc., sorry.