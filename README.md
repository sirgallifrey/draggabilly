# Draggabilly-ps

<p class="tagline">A little fork from Draggabilly that implements scale, mouse wheel scroll and auto-scrolling</p>
<p>Don't forget to check David DeSandro's awesome original Draggabilly</p>

[draggabilly.desandro.com](http://draggabilly.desandro.com)

<p>For draggabily documentation refer to:</p>
[draggabilly.desandro.com](http://draggabilly.desandro.com)


## New available options:

``` js
var $draggable = $('.draggable').draggabilly({
  parentScroll: 'selector', // element, string or bool. Parent scrolling element, true is for parentNode.
  autoScroll: false, // bool, enable autoScroll. Only verticall autoscrolling ATM, open an issue if you need horizontal too.
  autoScrollThreshold: 30, // int. threshold from parentScroll borders to start autoscrolling
  scrollSpeed: 10 // int, autoScrolling speed
})
```

## New Methods

### Set and Get scale.

<p>useful when inside and scaled element</p>

``` js
// jQuery
$draggable.draggabilly('setScale', SCALE)
$draggable.draggabilly('getScale')
// vanilla JS
draggie.setScale(SCALE)
draggie.getScale()
```


Draggabilly-ps is released under the [MIT License](http://desandro.mit-license.org/). Have at it.
