### Keep track of translation requirements ###
First, star [issue 179](http://code.google.com/p/dashclock/issues/detail?id=179) to keep up to date with translation requirements:

### Files that need translating ###

All of DashClock's strings are stored in these two files:

  * [strings.xml](http://code.google.com/p/dashclock/source/browse/main/src/main/res/values/strings.xml)
  * [pref\_strings.xml](http://code.google.com/p/dashclock/source/browse/main/src/main/res/values/pref_strings.xml)

To create translations for DashClock, simply pull down these files and translate the strings inside.

### Submitting translated files ###

Once you've translated `strings.xml` and `pref_strings.xml`, do one of the following:

  * (Preferred) [Clone the repository](http://code.google.com/p/dashclock/source/createClone), add the translated strings into the appropriate `values-XX` directory for your language, and [file a pull request](http://code.google.com/p/dashclock/issues/entry?template=Pull%20request).
  * [File a feature request](http://code.google.com/p/dashclock/issues/entry?template=Feature%20Request) and attach the two files.

Once translations are accepted, the issue you filed will be turned into a [translations tracker](http://code.google.com/p/dashclock/issues/list?can=1&q=Type%3DTracker+Component%3DTranslation) for future translations.

### Acknowledging yourself ###

Please make sure to state whether or not you're comfortable with us thanking you in the About dialog. If you're OK with that, make sure the feature request or pull request has your full name in it.

### Updating translations in the future ###

If you're updating an existing translation, instead of filing a new issue, please comment on the [relevant translation tracker for your language](http://code.google.com/p/dashclock/issues/list?can=1&q=Type%3DTracker+Component%3DTranslation).

The preferred way of sharing updates is by [cloning the repository](http://code.google.com/p/dashclock/source/createClone), creating commits in the clone, and commenting on the translation tracker issue relevant to your language, with a link to your commits.