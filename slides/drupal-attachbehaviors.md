####  Drupal.attachBehaviors
<br>

```
Drupal.attachBehaviors(document, drupalSettings)
```
<br>
Drupal loads the page, Drupal.behaviors gets filled with attach functions (and some detach functions)
<br><br>
On domready all these functions are executed with the drupalSettings variable and the context set to the document