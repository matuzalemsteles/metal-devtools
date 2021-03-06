# metal-devtools
[![Build Status](https://travis-ci.org/metal/metal-devtools.svg?branch=master)](https://travis-ci.org/metal/metal-devtools)
[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/fagnjmppkokolnbloalifcmcooldhiik.svg)](https://chrome.google.com/webstore/detail/metaljs-developer-tools/fagnjmppkokolnbloalifcmcooldhiik)
[![Chrome Web Store](https://img.shields.io/chrome-web-store/d/fagnjmppkokolnbloalifcmcooldhiik.svg)](https://chrome.google.com/webstore/detail/metaljs-developer-tools/fagnjmppkokolnbloalifcmcooldhiik)

![Screenshot](images/screenshot.gif)

### Installation
* Download from [chrome store](https://chrome.google.com/webstore/detail/metaljs-developer-tools/fagnjmppkokolnbloalifcmcooldhiik)
* See how it works by using it [here](https://metal.github.io/metal-devtools/)

### Seeing Errors?
If you happen to see any errors or logs in your console that contain...

![Screenshot](images/console_warning.png)

Please report those [here](https://github.com/metal/metal-devtools/issues/new)

### Developing
* Clone Repo
* run `npm install` at root

###### Chrome
* Run `npm run build`(this builds both the injected files and extension files)
* Open Chrome and navigate to `chrome://extensions/`
* Click on "Load unpacked extension" and select the `shells/chrome/dist` directory

### For Metal.js < v2.6.2
Unfortunately if you are not using metal@v2.6.2 or greater, you need to manually add hook. See example [here](https://github.com/metal/metal.js/commit/06b837b9e2e6b072e66064308476d2f7661fa09c)
