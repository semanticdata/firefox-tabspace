# Tab␣

### A scratchspace for your new Tab

A beautiful new tab replacement that gives you your very own scratch space to help you stay organized and focused.

It features a prominent spatial visualization for all of your tasks that helps you prioritize what's important, auto-saving notes, rich text formatting and natural language due dates.

![demo](./demo.gif)

## Table of Contents

<details>
<summary>Show/Hide</summary>

- [Tab␣](#tab)
    - [A scratchspace for your new Tab](#a-scratchspace-for-your-new-tab)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
    - [Building the browser extension locally](#building-the-browser-extension-locally)
    - [Setting up the website as your new tab page](#setting-up-the-website-as-your-new-tab-page)
  - [Acknowledgements and Attributions](#acknowledgements-and-attributions)
  - [License](#license)

</details>

## Features

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

## Acknowledgements and Attributions

This extension is a Firefox port of [jackyzha0/tabspace](https://github.com/jackyzha0/tabspace).

## License

Source code in this repository is available under the [MIT License](LICENSE). You are free to use this code however you like. That said, some acknowledgement would be well received.
