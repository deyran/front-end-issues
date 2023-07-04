# TypeScript

## Arrays

Arrays in TypeScript are similar to arrays in JavaScript, but with some additional features. In the next sections, the most important characteristics of Arrays in TypeScript will be shown

### Strongly typed

* TypeScript is **strongly typed** and has specific syntax for typing arrays. This can be seen in the code below

```js
let names: string[] = [];
names.push("Deyvid");
names.push("Márcia");
names.push("Lara");

console.log(names);
```

In the previous code, the result will be: **[ 'Deyvid', 'Márcia', 'Lara' ]**. But if you try to add a new element with different type, it will result in a compile time error as shown in the code below:

```js
let names: string[] = [];
names.push("Deyvid");
names.push(0);

console.log(names);

/*
hello-world.ts:3:12 - error TS2345: Argument of type 'number' is not assignable to parameter of type 'string'.

3 names.push(0);
             ~
Found 1 error in hello-world.ts:3
*/
```

<!--
# TypeScript
## Arrays
### Strongly typed
----------------------------------------------

# TypeScript
## Arrays
-->