# Amazon Watcher

This Chrome extension enhances the shopping experience on the amazon website with automatic price tracking and visualization as a chart on the related product pages. Furthermore it improves the layout of the price alert on the cart page.

## Installation

For trying out (or daily usage) simply install it from the [Chrome Web Store](https://chrome.google.com/webstore/category/extensions).

For local development follow these steps:

1. fork this repository
2. run `npm install`
3. run `npm run start`
4. open [chrome://extensions/](chrome://extensions/)
5. enable `development mode`
6. click on `load unpacked extension` and select the `build` folder

## Motivation

Quite often I get a price alert on the cart page and often find it annoying to filter the relevant changes (I don't care about price changes of 0.01) and find it hard to remember all the past prices.

Since I haven't found any suitable extension for this I've decide to create one.

## Credits

Built with [chrome-extension-boilerplate-react](https://github.com/lxieyang/chrome-extension-boilerplate-react)
