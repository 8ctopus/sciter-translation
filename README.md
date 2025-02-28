# sciter translation

This is a [sciter.js](https://sciter.com/) project that explores different ways to translate a sciter app.

For a working translation engine, check [sciter-i18n](https://github.com/8ctopus/sciter-i18n).

_Note_: sciter introduced its own [translation system](https://github.com/c-smile/sciter-js-sdk/blob/main/docs/md/reactor/JSX-i18n.md) in 4.4.8.19.

## translation engines tested

- sciter `aspect`
- html `data` attribute
- translation using css
- using [`i18next`](https://github.com/i18next/i18next) js library
- using `jquery-i18n` js library (not working)
- using [`polyglot`](https://github.com/airbnb/polyglot.js) js library
- and finally using `sgml entities`

And here's a good reference about localization in sciter.js: https://sciter.com/forums/topic/localization/

## demo

- git clone the repository
- install packages `npm install`
- install latest sciter sdk `npm run install-sdk`
- start the demo `npm run scapp`

### demo requirements

- A recent version of Node.js `node` (tested with 22 LTS) and its package manager `npm`.
    - On Windows [download](https://nodejs.dev/download/) and run the installer
    - On Linux check the [installation guide](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04#option-2-%E2%80%94-installing-node-js-with-apt-using-a-nodesource-ppa)
