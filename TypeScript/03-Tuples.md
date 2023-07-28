# TypeScript

## Tuples

Tuples are a data type that allow you to store a set of values of different types. They are similar to arrays but have some important differences, like:

1. Fixed number of elements
2. Each element can havea different type
3. The elements can be accessed by index or by name


### First example

```
let employee: [number, string] = [0, 'Deyvid Rannyere']
console.log(employee);

/*
[ 0, 'Deyvid Rannyere' ]
*/
```

### Add elements into Tuple

```
let employee: [number, string] = [0, 'Deyvid Rannyere']

employee.push(1, 'Márcia Moraes');
employee.push(2, 'Lara Moraes');

console.log(employee);

/*
[ 0, 'Deyvid Rannyere', 1, 'Márcia Moraes', 2, 'Lara Moraes' ]
*/
```

<!--
# TypeScript
## Tuples
### First example
### Add elements into Tuple
-->
