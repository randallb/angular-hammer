angular-hammer
==============

Touch events via Hammerjs

Inspired by AngularJS' implementation of "click dblclick mousedown..." and this gist: https://gist.github.com/3298323

This ties in touch events to attributes like:

    hm-tap="add_something()"
 
Add in a script tag, then add `hmTouchevents` to your app's dependencies. 

Obviously depends on [Hammer][1], but nothing else.

[1]: https://github.com/eightmedia/hammer.js