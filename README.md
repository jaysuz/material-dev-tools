# DevTools Material Theme

This is a Chrome extension that applies a different colour theme to the Chrome developer tools.

## Getting Started

Even if this project is in its alpha phase (and thus not available via the Chrome Web Store), you can still get a local
copy for testing purposes.

### Prerequisites

You need to have the the Developer Mode for Chrome extensions activated:
1. navigate to ```chrome://extensions/```
2. toggle the _Developer Mode_ switch

### Installing

Clone this repository:

```
git clone https://github.com/jaysuz/material-dev-tools.git
```

In the ```chrome://extensions/``` window, use the _Load unpacked_ button to load this extension from the location where
you cloned the repository.

To test the new theme, make sure the extension is activated and open the Chrome devtools on a page of your choosing. As
this theme is meant as a replacement for the dark theme, you first need to switch to the native dark theme of the 
devtools to see any effect.

## Built With

* [SASS](https://sass-lang.com/) - CSS preprocessing
* [Gulp](https://gulpjs.com/) - Automation
* [Yarn](https://yarnpkg.com/) - Dependency management

## Acknowledgments

* The marvelous [Material Theme Plugin](https://plugins.jetbrains.com/plugin/8006-material-theme-ui) for IntelliJ IDEA for colour inspiration
