# Numbering
Convert between human and machine numbering

## Installation
```javascript
npm install --save numbering
```

## Example usage
```javascript
import numbering from 'numbering';

// when you want to convert under-the-hood number to human-readable one(add 1 to it)
numbering.toHuman(0);

// when you want to convert human-readable number to zero-based one(subtract 1 from it)
numbering.toMachine(1);
```

## Other example usage
```javascript
import { toHuman, toMachine } from 'numbering';

// when you want to convert an under-the-hood number to a human-readable one(add 1 to it)
toHuman(0);

// when you want to convert a human-readable number to a zero-based one(subtract 1 from it)
toMachine(1);
```
