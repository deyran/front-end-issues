# TypeScript

## Main primitives types

* There are three primitive types in TypeScript:

1. boolean
2. number
3. string

## Type assignment

* These primitive types can be assigned in two ways: Explicit and Implicit.

1. Explicit

```js
let firstName: string = "Deyvid";
```

2. Implicit. In that case, it forces TypeScript to infer the value

```js
let firstName = "Deyvid";
```

## Special types

There are three kinds of special types, that are: any, unknown, never, undefined and null.

1. *any* - disable type checking, allows all types. Open the hello-world.ts file, edit it to match the code below. Run and see the result

```
let x: any = 10;
let y: any = 'hello';
let z: any = true;

console.log(x + y);
console.log("\n-----------\n");
console.log(x + z);
```

2. *unknown* - just like any type except that the unknown type constrains the type before performing any operation

<!--
# TypeScript
## Special types

----------------------------------------------

# TypeScript
## Main primitives types
## Type assignment
## Special types
-->