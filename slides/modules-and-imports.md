####  Modules and imports
<br>
lib/math.js

```
export var pi = 3.141593
export function sum (x, y) { 
    return x + y 
} 
```
<br>
someApp.js 
```
import * as math from "lib/math" 

console.log("2π = " + math.sum(math.pi, math.pi))
```
<br>
otherApp.js 
```
import { sum, pi } from "lib/math" 

console.log("2π = " + sum(pi, pi))
```