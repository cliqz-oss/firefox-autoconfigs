# CLIQZ Firefox autoconfig

Testing Firefox extensions on real browsers can be really hard. Browsers by default are not set up to run in continious intergration environements. Luckly Firefox provides easy way to change in default setting that will prevent situations like:

* auto updates
* "default browser" popups
* sending messages to mozilla servers
* etc.

The mechanism to put those settings is called 'autoconfig'.

## Setup

Look here for autoconfig intro: http://pascal-mietlicki.fr/en/blog/post/work/firefox-autoconfig/

Enable global autoconfig by:
* copy `autoconfig.js` to `<FIREFOX INSTALLATION DIR>/default/prefs`
* copy `firefox.cfg` to `<FIREFOX INSTALLATION DIR>`
