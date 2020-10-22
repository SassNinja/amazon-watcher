# Amazon Watcher

This Chrome extension extends the amazon website by tracking price changes (when they appear on your cart page) and displaying them as a chart on the related product page.

## Dev Server

You can run the dev mode on other port if you want. Just specify the env var `port` like this:

```
$ PORT=6002 npm run start
```

## Publishing

```
$ NODE_ENV=production npm run build
```

Now, the content of `build` folder will be the extension ready to be submitted to the Chrome Web Store. Just take a look at the [official guide](https://developer.chrome.com/webstore/publish) to more infos about publishing.

---

Built with [chrome-extension-boilerplate-react](https://github.com/lxieyang/chrome-extension-boilerplate-react)
