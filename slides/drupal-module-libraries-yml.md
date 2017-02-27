####  my_module.libraries.yml
<br>

Create a module and a libraries file like below:

```
jspm:
  version: VERSION
  js:
    /jspm/packages/system.js: { weight: -20 }
    /jspm/jspm.config.js: { weight: -20 }
    js/start-es6.js: { weight: -20 }
  dependencies:
    - core/drupal
    - core/drupalSettings
```

Make sure this library is always loaded:
```
function my_module_preprocess_page(&$variables) {
  $variables['#attached']['library'][] = 'my_module/jspm';
}
```
