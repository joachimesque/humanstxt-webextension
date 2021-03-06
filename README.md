# Humans.txt WebExtension

This is a port of [Michael Mahemoff’s Chrome extension Humans.txt](https://github.com/mahemoff/humanstxt) ([Chrome Web Store link : Humans.txt](https://chrome.google.com/webstore/detail/pocdghmbbodjiclginddlaimdaholhfk)) to the new Firefox-compatible WebExtension format, with a couple of improvements.

## Installation :

* **Firefox Add-ons** : <https://addons.mozilla.org/en-US/firefox/addon/humans-txt-webextension/>
* **Google Chrome Webstore** : <https://chrome.google.com/webstore/detail/humanstxt-webextension/monhadhlgfjjiokfekkllknnhemfbcon>


## What it does :

> Humans.txt is an initiative for knowing the people behind a website. It's a TXT file that contains information about the different people who have contributed to building the website.

> [Humans.txt](http://humanstxt.org)

The extension displays an icon in the address bar (Firefox, Opera) or the toolbar (Google Chrome), when the domain for the website loaded in the active tab hosts a `humans.txt` file.

Users can click on the icon to see the humans.txt file.

Plain text links and Twitter handles are turned to links to facilitate navigation. Basic Markdown is accepted, and [standard-compatible](http://humanstxt.org/Standard.html) titles are more or less supported.

## How to install the extension for testing purposes :

First off, download the repository or clone it on your computer.

### Mozilla Firefox

* Tools > Add-ons… (or `about:addons`)
* Click on the cog button (Add-on tools) and select *Debug Add-ons* (or type `about:debugging#addons` in address bar)
* Click *Load Temporary Add-on*
* Select the file named *manifest.json* in the project‘s folder


### Google Chrome

* Toolbar menu > More Tools > Extensions (or type `chrome://extensions/` in the menu bar)
* Enable *Developer Mode*
* Click *Load unpackaged extension*
* Select the project’s folder 

## Licensing

This code is released under MIT License.

[Autolinker.js](https://github.com/gregjacobs/Autolinker.js) was released under MIT License.

[Markdown.js](https://gist.github.com/fuzzyfox/5843166) was released under Mozilla Public License 2.0

[webextensions-lib-l10n](http://github.com/piroor/webextensions-lib-l10n) was released under MIT License.

[Sourse Code Pro](https://github.com/adobe-fonts/source-code-pro) was released under SIL Open Font License.

The Humans.txt Icon is released under Creative Commons BY-NC-SA License.
