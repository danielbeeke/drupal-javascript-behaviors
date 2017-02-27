####  Arrow functions
<br>

```
() => {}
```
Example:
<br>
```
this.foo = 'a'

var that = this;

items.forEach(function (item) {
    // this = item
    // that.foo = 'a'
})
```

No more "var that = this";

```
this.foo = 'a'
items.forEach((item) => {
    // this == 'a'
})
```