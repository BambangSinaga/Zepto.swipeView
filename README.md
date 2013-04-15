Originally forked from SwipeView v1.0 - 2012-08-25
============================

Virtually infinite loop-able horizontal carousel for desktop and mobile browsers.

Read more at [cubiq.org](http://cubiq.org/swipeview)

# Why this fork ?

Need to make a zepto plugin using the original SwipeView , which will have less code and can be called like other Zepto/jQuery 
plugins. The plain version of SwipeView requires some extra code to be included to make the gallary work. So this fork is
basically creating the carousel plugin using SwipeView.js.

The new plugin should've the following stuff.

- Able to call the plugin `swipeView()` on a Zepto collection.
- Less size than the original SwipeView.js when minified.
- Well defined API.
