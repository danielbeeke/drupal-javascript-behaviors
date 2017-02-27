####  drupalSettings
<br>

A way to ship PHP variables to the javascript frontend.
<br><br>
_Inside a render array_
```
$build['#attached']['drupalSettings']['my_module']['foo'] = 'bar';
```
<br>

_Inside the behavior_
```
attach: function (context, drupalSettings) {}
```