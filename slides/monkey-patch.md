####  Monkey patch domready
<br>

start-es6.js
```
var realDomready = window.domready;

window.domready = function (callback) {
    SystemJS.import('drupal-custom/my_module/js/es6.js').then(function () {
        realDomready(callback);
    });
};
```