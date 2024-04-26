# Tab␣

> A scratchspace for your new tab.

![Mozilla Add-on](https://img.shields.io/amo/v/addon@tabspace.com)
![Add-on rating](https://img.shields.io/amo/rating/addon@tabspace.com)
![Add-on downloads](https://img.shields.io/amo/dw/addon@tabspace.com)
![Add-on users](https://img.shields.io/amo/users/addon@tabspace.com)
![License](https://img.shields.io/github/license/semanticdata/firefox-tabspace)

A beautiful new tab replacement that gives you your very own scratch space to help you stay organized and focused.

It features a prominent spatial visualization for all of your tasks that helps you prioritize what's important, auto-saving notes, rich text formatting and natural language due dates.

[![Get the Addon](https://raw.githubusercontent.com/semanticdata/text-revealer-firefox-extension/master/firefox.png)](https://addons.mozilla.org/en-US/firefox/addon/tabspace/)

![firefox extension demo](./demo.gif)

## 🖼 Screenshots

![extension screenshot](screenshot.png)

## ✨ Features

- Auto-saves to local storage
- Write in Markdown syntax
- Uses natural language to recognize and highlight due dates
- Darkmode

### Building the browser extension locally

- Clone the repository
- Install dependencies `npm i`
- Build `npm run build`
- Load the extension in the Chrome Extensions menu
  - Go to extensions > Enable developer mode (top right corner)
  - Click load unpacked, select the `build` folder

For more information, see the [documentation](https://developer.chrome.com/docs/extensions/mv3/getstarted/[official).

### Setting up the website as your new tab page

Based on your browser, there may be an option to set the new tab page URL directly without installing an extension.

## 💜 Acknowledgements

This extension is a Firefox port of [jackyzha0/tabspace](https://github.com/jackyzha0/tabspace).

## © License

Source code in this repository is available under the [MIT License](LICENSE).
