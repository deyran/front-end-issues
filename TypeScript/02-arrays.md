# TypeScript

## Arrays

Arrays in TypeScript are similar to arrays in JavaScript, but with some additional features. In the next sections, the most important characteristics of Arrays in TypeScript will be shown

### Strongly typed

* TypeScript is **strongly typed** and has specific syntax for typing arrays. This can be seen in the code below

```js
const names: string[] = [];
names.push("Deyvid");
names.push("Márcia");
names.push("Lara");

console.log(names);
```

* In the previous code, the result will be: **[ 'Deyvid', 'Márcia', 'Lara' ]**. But if you try to add a new element with different type, it will result in a compile time error as shown in the code below:

```js
const names: string[] = [];
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

* There are other syntaxes for implementing arrays in TypeScript

```
const names2: string[] = ["Deyvid", "Márcia", "Lara"];
console.log(names2);


const names3: Array<string> = ["Deyvid", "Márcia", "Lara"];
console.log(names3);


const items: number[] = []
items.push(0);
items.push(1);
items.push(2);

console.log(items);
```

### Inference

Arrays in TypeScript can figure out the type by inference

```
```

### ReadyOnly

The readonly keyword ensures that the array can't be changed

```
const names: readonly string[] = ["Deyvid"];
names.push("Márcia");

console.log(names);

/*
prog.ts(2,7): error TS2339: Property 'push' does not exist on type 'readonly string[]'.
*/
```

<!--
# TypeScript
## Arrays
### ReadyOnly
----------------------------------------------

# TypeScript
## Arrays
### Strongly typed
### Inference
### ReadyOnly
-->