####  How to combine ES6 &amp; Drupal
<br>

* Install Drupal via [composer Drupal-project](https://github.com/drupal-composer/drupal-project)
* init jspm and configure it to work with Drupal 8
* Load systemjs and jspm config via module.libraries.yml
* Monkey patch domready so systemjs is started before Drupal.attachBehaviors