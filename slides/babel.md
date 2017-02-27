####  Babel
<br>

A transpiler that support ES6 and more.
<br>

_ES6_
```
let animals = ['dog', 'cat', 'donkey'];
let things = ['computer', ...animals];

console.log(things); // computer, dog, cat, donkey
```
<br>
_transpiled_

```
var animals = ['dog', 'cat', 'donkey'];
var things = ['computer'].concat(animals);

console.log(things); // computer, dog, cat, donkey
```