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

<!--
# TypeScript
## Object Types
### Changing the properties
-->