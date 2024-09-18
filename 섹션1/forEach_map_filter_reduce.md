# <b>Array.prototype.forEach</b>
The `forEach()` method of `Array` instances executes a provided function once for each array element.

# Try It
```javaScript
const array1 = ['a', 'b', 'c'];

array1.forEach((element) => console.log(element));

// Expected output: "a"
// Expected output: "b"
// Expected output: "c"
```

# Syntax
```javaScript
forEach(callbackFn)
forEach(callbackFn, thisArg)
```

## Parameters
`callbackFn`
- A function to execute for each element in the array. Its return value is discarded. The function is called with the following arguments:

- `element`: The current element being processed in the array.
- `index`: The index of the current element being processed in the array.
- `array`: The array `forEach()` was called upon.


`thisArg (optional)`
- A value to use as `this` when executing `callbackFn`



Reference: MDN
-
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach