layout: doc
comments: false
date: 2014-10-2 5:37:23
repo: saber-widget
ref: 0.3.1
---

# LazyLoad

懒加载控件。


## Usage

``` javascript
var widget = require( 'saber-widget' );
require( 'saber-widget/LazyLoad' );

var lazyload = widget.lazyLoad();

lazyload.on( 'load', function ( ev, node ) {
    console.info( 'load', node );
});

lazyload.on( 'complete', function () {
    console.info( 'complete' );
});
```

## API

TODO
