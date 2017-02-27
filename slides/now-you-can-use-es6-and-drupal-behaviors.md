####  Now you can use ES6 and Drupal behaviors
<br>

Now you can add a javascript file like this one:
```
import $ from 'jquery';
import _ from 'underscore';

Drupal.behaviors.behaviorWithEs6 = {
    attach: (context, settings) => {

        if (context == document) {
            alert('woop woop')
        }

    }
};

```
