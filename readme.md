# Puppeteer Test

- use chrome devtools recorder to record google search

check this video: [https://www.bilibili.com/video/BV1BP4y1n7yS/](https://www.bilibili.com/video/BV1BP4y1n7yS/)

- export puppeteer script



- run puppeteer script, but failed


```bash
node search.js
(node:3972) UnhandledPromiseRejectionWarning: Error: net::ERR_INVALID_URL at chrome://new-tab-page/
    at navigate (/Users/kiwenlau/Desktop/puppeteer-test/node_modules/_puppeteer@13.0.0@puppeteer/lib/cjs/puppeteer/common/FrameManager.js:155:23)
    at processTicksAndRejections (internal/process/task_queues.js:95:5)
    at async FrameManager.navigateFrame (/Users/kiwenlau/Desktop/puppeteer-test/node_modules/_puppeteer@13.0.0@puppeteer/lib/cjs/puppeteer/common/FrameManager.js:130:21)
    at async Frame.goto (/Users/kiwenlau/Desktop/puppeteer-test/node_modules/_puppeteer@13.0.0@puppeteer/lib/cjs/puppeteer/common/FrameManager.js:500:16)
    at async Page.goto (/Users/kiwenlau/Desktop/puppeteer-test/node_modules/_puppeteer@13.0.0@puppeteer/lib/cjs/puppeteer/common/Page.js:1167:16)
    at async /Users/kiwenlau/Desktop/puppeteer-test/search.js:129:9
(Use `node --trace-warnings ...` to show where the warning was created)
(node:3972) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). To terminate the node process on unhandled promise rejection, use the CLI flag `--unhandled-rejections=strict` (see https://nodejs.org/api/cli.html#cli_unhandled_rejections_mode). (rejection id: 1)
(node:3972) [DEP0018] DeprecationWarning: Unhandled promise rejections are deprecated. In the future, promise rejections that are not handled will terminate the Node.js process with a non-zero exit code.
```


