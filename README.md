# Numbering
Convert between human and machine numbering. Basically, it provides an interface to add or subtract 1 from provided number.

## Installation
```javascript
npm install --save start-from-zero
```

## Example usage
```javascript
import num from 'start-from-zero';

// when you want to convert under-the-hood number to human-readable one(add 1 to it)
num.toHuman(0); // 1

// when you want to convert human-readable number to zero-based one(subtract 1 from it)
num.toMachine(1); // 0
```

## Example with destructuring
```javascript
import { toHuman, toMachine } from 'start-from-zero';

// when you want to convert an under-the-hood number to a human-readable one(add 1 to it)
toHuman(0); // 1

// when you want to convert a human-readable number to a zero-based one(subtract 1 from it)
toMachine(1); // 0
```
