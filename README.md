[![Join the chat at https://gitter.im/shockone/black-screen](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/shockone/black-screen?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

### What is it?

Black Screen is a modern terminal emulator based on [Electron](http://electron.atom.io/) and exploiting
capabilities of contemporary interfaces in contrast to most of the terminal emulators.

![](https://dl.dropboxusercontent.com/spa/dlqheu39w0arg9q/ucvbthot.png)

### Technologies

* Electron
* TypeScript
* NodeJS
* ReactJS
* SASS

### Installation

Right now only OS X is supported, but we plan to make it work on all the major platforms.

```bash
npm run install-all
```

### Run

```bash
gulp
```

### Package

To create a standalone application, run:

```bash
npm run package
```

### Test

* Install [selenium-standalone](https://github.com/vvo/selenium-standalone)
* `selenium-standalone start`
* `npm run test`

### TODO

* VT100 compliant ANSI support.
* Environment variables support.
* Panes and tabs.
* Man files parsing for better autocompletion.

### License

The MIT License.
