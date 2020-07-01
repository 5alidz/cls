## Usage

```
npm i @5alid/cls
or
yarn add @5alid/cls
```

```js
import cls from '@5alid/cls';

// signature cls(...args);
// args can be: string or [condition: boolean, string, string?]

// basic usage example
cls('px-4 py-1', 'bg-purple'); // result -> 'px-4 py-1 bg-purple'

// with conditions
cls('px-4 py-1', [true, 'bg-blue', 'bg-purple']); // result -> 'px-4 py-1 bg-blue'
```

## Why?

this small utility helps cleaning up class names styling soluotions like tailwindcss, bootstrap etc.
