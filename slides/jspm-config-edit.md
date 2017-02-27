####  jspm config edit
<br>

Edit jspm.config.js:

You can add your own namespaces,
so you can import drupal/my_module/js/script

```
SystemJS.config({
  paths: {
    "npm:": "jspm/packages/npm/",
    "drupal-custom/": "modules/custom/"
  },
```