#### Block scoped variables
<br>
_let_ is properly scoped to the block, <br>like you would expect _var_ to work.
<br>
<br>
```
for (let i = 0; i < a.length; i++) { 
    let x = a[i] … 
} 

for (let i = 0; i < b.length; i++) {
    let y = b[i] … 
} 
```
<br>
### You can swap _var_ with _let_.