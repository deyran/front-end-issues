# TypeScript

## Enums

An Enums is a specific class that represents a group of unchangeable constants. TypeScript provides three types of Enums: Numeric Enums, String Enums and Heterogeneous enums.

### Numeric Enums

* **Default** - By default all Enum element are automatically initialized in sorted sequence starting from 0 to N (last enum element).

```
enum Direction { UP, DOWN, LEFT, RIGTH }

console.log("UP -> " + Direction.UP);
console.log("DOWN -> " + Direction.DOWN);
console.log("LEFT -> " + Direction.LEFT);
console.log("RIGTH -> " + Direction.RIGTH);

/*
UP -> 0
DOWN -> 1
LEFT -> 2
RIGTH -> 3
*/
```

* **Inicialized** - The first Enum element can be initialized and rest will automatically increment from that.

```
enum Direction { UP = 99, DOWN, LEFT, RIGTH }

console.log("UP -> " + Direction.UP);
console.log("DOWN -> " + Direction.DOWN);
console.log("LEFT -> " + Direction.LEFT);
console.log("RIGTH -> " + Direction.RIGTH);

/*
UP -> 99
DOWN -> 100
LEFT -> 101
RIGTH -> 102
*/
```

* **Fully inicialized** - A value for each Enum element can also be assigned.

```
enum Direction { UP = 99, DOWN = 7, LEFT = 11, RIGTH = 13 }

console.log("UP -> " + Direction.UP);
console.log("DOWN -> " + Direction.DOWN);
console.log("LEFT -> " + Direction.LEFT);
console.log("RIGTH -> " + Direction.RIGTH);

/*
UP -> 99
DOWN -> 7
LEFT -> 11
RIGTH -> 13
*/
```

### String Enums

### Heterogeneous enums


<!--
# TypeScript
## Enums
### Numeric Enums
#### Fully inicialized
----------------------------------------------

# TypeScript
## Enums
### Numeric Enums
#### Default
#### Inicialized
#### Fully inicialized
### String Enums
### Heterogeneous enums
-->