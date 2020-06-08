# JavaScript-Features-in-ES2020
JavaScript Features in ES2020

## Array

* [flatMap](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flatMap) 

> The flatMap() method first maps each element using a mapping function, then flattens the result into a new array. It is identical to a map() followed by a flat() of depth 1, but flatMap() is often quite useful, as merging both into one method is slightly more efficient.
**only one level is flattened !** [source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flatMap) | [Live Example](https://codesandbox.io/s/autumn-cherry-185y8?file=/src/index.js)

* [for await...of](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for-await...of) 

> The for await...of statement creates a loop iterating over async iterable objects as well as on sync iterables, including: built-in String, Array, Array-like objects (e.g., arguments or NodeList), TypedArray, Map, Set, and user-defined async/sync iterables. It invokes a custom iteration hook with statements to be executed for the value of each distinct property of the object.Like await operator ,the statement can only be used inside an async function. [source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/for-await...of) | [Live Example](https://codesandbox.io/s/for-await-r0w8d?file=/src/index.js)


* [Promise.allSettled()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/allSettled) 

> The Promise.allSettled() method returns a promise that resolves after all of the given promises have either fulfilled or rejected, with an array of objects that each describes the outcome of each promise. [source](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/allSettled) | [Live Example](https://codesandbox.io/s/for-await-r0w8d?file=/src/index.js)


