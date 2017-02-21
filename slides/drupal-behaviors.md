####  Drupal.behaviors

_Somewhere in drupal.js_
<br>
```
window.Drupal = { 
    behaviors: {}
}
```
_After downloading all javascript files_
```
Drupal.behaviors.contextualFilters
Drupal.behaviors.wysiwyg
Drupal.behaviors.filters
Drupal.behaviors.myExample
```
* Drupal.behaviors is an object, <br>a set of plugins that need to be executed
* Every module may add it's attach and/or<br>detach functions to it