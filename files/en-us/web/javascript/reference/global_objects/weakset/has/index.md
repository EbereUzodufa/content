---
title: WeakSet.prototype.has()
slug: Web/JavaScript/Reference/Global_Objects/WeakSet/has
page-type: javascript-instance-method
browser-compat: javascript.builtins.WeakSet.has
---

{{JSRef}}

The **`has()`** method returns a boolean indicating whether an
object exists in a `WeakSet` or not.

{{EmbedInteractiveExample("pages/js/weakset-prototype-has.html")}}

## Syntax

```js-nolint
has(value)
```

### Parameters

- `value`
  - : Required. The object to test for presence in the `WeakSet`.

### Return value

Returns `true` if an element with the specified value exists in the `WeakSet` object; otherwise `false`.

## Examples

### Using the `has()` method

```js
const ws = new WeakSet();
const obj = {};
ws.add(window);

ws.has(window); // returns true
ws.has(obj); // returns false
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{jsxref("WeakSet")}}
- {{jsxref("WeakSet.prototype.add()")}}
- {{jsxref("WeakSet.prototype.delete()")}}
