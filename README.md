# node-time-sleep 💤

A tiny, async-friendly `time.sleep(ms)` utility for Node.js — inspired by Python.

## Install

```
npm install node-time-sleep
```

## Usage

```js
const time = require('node-time-sleep');

(async () => {
  console.log("Wait...");
  await time.sleep(1000); // sleeps for 1 second (non-blocking!)
  console.log("Done");
})();
```

## Why use this?

- Non-blocking — uses `setTimeout` under the hood
- Clean API: `time.sleep(1000)`
- Tiny and fast (no dependencies)
- TypeScript support

## License

MIT
