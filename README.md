** IMPORTANT **

This module will be useless in Angular 1.2 with the advent of new touch events.

Details [here](http://www.youtube.com/watch?v=W13qDdJDHp8)



Angular Hammer v2
=================

Updated to support the rewritten [Hammer.js](https://github.com/EightMedia/hammer.js) (v1.0.1+).

Within an Angular.js application, allows you to specify custom behaviour on Hammer.js touch events.

Usage, currently as attribute only:

    hm-tap="{expression}"

You can change the default settings for the instance by adding a second attribute with options:

    hm-options="{drag: false, transform: false}"

Include the angular-hammer.js file, and add `hmTouchevents` to your app’s dependencies.

Requires Hammer.js, tested with `v1.0.1 - 2013-02-26`.
