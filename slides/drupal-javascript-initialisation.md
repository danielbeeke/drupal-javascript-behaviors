####  Drupal startup
<br>
_Somewhere in drupal.js_
```
domready(function () { 
    Drupal.attachBehaviors(document, drupalSettings)
})
```
<br>
This starts all the javascript of core,<br>
modules and themes.