<!-- YAML
added: v0.6.0
deprecated: v4.0.0
-->

> 稳定性: 0 - 废弃的

* `object` {any}

Internal alias for [`Array.isArray`][].

Returns `true` if the given `object` is an `Array`. Otherwise, returns `false`.

```js
const util = require('util');

util.isArray([]);
// Returns: true
util.isArray(new Array);
// Returns: true
util.isArray({});
// Returns: false
```

