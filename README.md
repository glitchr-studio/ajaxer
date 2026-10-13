# @glitchr/ajaxer

> **This library now lives in [`@glitchr/flowjs`](https://github.com/glitchr-studio/flowjs)**, as its `ajaxer` module. This package is frozen at 1.0.57 and deprecated.

```js
// before
import '@glitchr/ajaxer';
// after
import '@glitchr/flowjs/ajaxer';
```

The `Ajaxer` global, its methods and its options are unchanged; durations given to the throttle and the debounce
now read as they are written (`"250ms"`, `"1s"`, or a number of milliseconds). The module's documentation is
[`docs/ajaxer.md`](https://github.com/glitchr-studio/flowjs/blob/master/docs/ajaxer.md) in flowjs.
