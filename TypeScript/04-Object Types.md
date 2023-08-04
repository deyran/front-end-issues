# TypeScript

## Object Types

Object Types is a representation of the object that stores data

```
const people: {name: string, birthdate: string, age: number} =
{
	name: "Deyvid Rannyere",
	birthdate: "07-12-1980",
	age: 43
};

console.log(people);

/*
{ name: 'Deyvid Rannyere', birthdate: '07-12-1980', age: 43 }
*/
```

### Changing the properties

```
const people: {name: string, birthdate: string, age: number} =
{
	name: "Deyvid Rannyere",
	birthdate: "07-12-1980",
	age: 27
};

console.log(people);

people.name = "Márcia Moraes";
people.birthdate = "01-20-1980";
people.age = 43;

console.log(people);

/*
{ name: 'Deyvid Rannyere', birthdate: '07-12-1980', age: 27 }
{ name: 'Márcia Moraes', birthdate: '01-20-1980', age: 43 }
*/
```

### Type inference

Assigned values determine what type properties can be

```
const car = { type: "Ferrari" };

car.type = "AAAA";
car.type = 1;

console.log(car);

/*
prog.ts(4,1): error TS2322: Type 'number' is not assignable to type 'string'.
*/

```

<!--
# TypeScript
## Object Types
### Type inference
----------------------------------------------

# TypeScript
## Object Types
### Changing the properties
### Type inference
-->