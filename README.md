[![Build Status](https://travis-ci.org/sblask/firefox-open-tabs-next-to-current.svg?branch=master)](https://travis-ci.org/sblask/firefox-open-tabs-next-to-current)

firefox-open-tabs-next-to-current
=================================

Open tabs that would normally be opened last next to the current one. Tabs that
are being re-opened and tabs that are opened by clicking on links in the
current tab are therefore not included. You can change the setting
`browser.tabs.insertRelatedAfterCurrent` in `about:config` if you want even the
latter to be opened right next to the current. You can use `Ctrl-Y`
(`Ctrl-Shift-Y` on Windows) to open a new tab at the default location.

Known Issues
------------

Caused by limitations of the webextension API, see
[#26](https://github.com/sblask/firefox-open-tabs-next-to-current/issues/26):

 - tabs are visibly moved to their final position
 - the tab bar is scrolled so the opened tab becomes the first visible one on the left


Feedback
--------

You can report bugs or make feature requests on
[Github](https://github.com/sblask/firefox-open-tabs-next-to-current).

Patches are welcome.
