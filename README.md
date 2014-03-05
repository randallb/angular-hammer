Angular Hammer 
===============

Within an Angular.js application, allows you to specify custom behaviour on Hammer.js touch events.

Usage, currently as attribute only:

    hm-tap="{expression}"

You can change the default settings for the instance by adding a second attribute with options:

    hm-options="{drag: false, transform: false}"

Include the angular-hammer.js file, and add `hmTouchevents` to your app’s dependencies.

Requires Hammer.js, tested with `v1.0.1 - 2013-02-26`.

This repo is largely unmaintained, but will accept pull requests. Also ngTouch might serve some of your needs... so check that out.
