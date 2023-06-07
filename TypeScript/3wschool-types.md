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

There are three kinds of special types, that are: **any**, **unknown**, **never**, **undefined** and **null**.

1. *any* - disable type checking, allows all types. Open the hello-world.ts file, edit it to match the code below. Run and see the result

```
let x: any = 10;
let y: any = 'hello';
let z: any = true;

console.log(x + y);
console.log("\n-----------\n");
console.log(x + z);
```

2. *unknown* - just like any type, it allows all type. The most important difference is the unknown type restricts the type before performing any operation.

```
let x: unknown = 10;
let y: unknown = 'hello';
let z: unknown = true;

console.log(x + y);
console.log("\n-----------\n");
console.log(x + z);

/*
When you try to run the application theses set of errors is shown
prog.ts(5,13): error TS2365: Operator '+' cannot be applied to types 'unknown' and 'unknown'.
prog.ts(7,13): error TS2365: Operator '+' cannot be applied to types 'unknown' and 'unknown'.
*/
```

3. *never* - Represents a variable can never be assigned a value, as seen in the example below.

```
let x: never = true;

/*
if you try to run this code the below error will occurs
prog.ts(1,5): error TS2322: Type 'boolean' is not assignable to type 'never'.

This error occurs because no value can be assigned to a variable declared as type never
*/
```

<!--
# TypeScript
## Special types
### never special type
----------------------------------------------

# TypeScript
## Main primitives types
## Type assignment
## Special types
-->