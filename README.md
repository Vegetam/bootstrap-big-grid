Bootstrap Big Grid
==================

A set of larger grid options for Bootstrap.

Documentation and Tests
=======================
http://benwhitehead.github.io/bootstrap-big-grid/

Motivation
==========
Bootstraps Grid only provides a grid up to 1200px wide, this project provides more grids for common higher resolutions all the way up to 8K.

Usage
=====
The easiest way to use Bootstrap Big Grid is with Bower
```bash
bower install --save bootstrap-big-grid
```

Alternatively download a [release](https://github.com/BenWhitehead/bootstrap-big-grid/releases) and use the css files in the dist directory.

Then link it into your page after the main bootstrap css

```html
<link rel="stylesheet" href="//netdna.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
<link rel="stylesheet" href="bower_components/bootstrap-big-grid/dist/css/bootstrap-big-grid.min.css"/>
```

New Classes
===========

### New Grid Classes
`.col-tv720p-`    : 1366 x 768  
`.col-tv1080p-`   : 1920 x 1080  
`.col-tv1440p-`   : 2560 x 1440  
`.col-retina15-`  : 2880 x 1800
`.col-tvUHD-`     : 3840 × 2160
`.col-tv4k-`      : 4096 x 2304  
`.col-tv8k-`      : 8192 x 4608  

### New Responsive Utilities Classes
`.visible-tv720p`  
`.visible-tv1080p`  
`.visible-tv1440p`  
`.visible-retina15`
`.visible-tvUHD`
`.visible-tv4k`  
`.visible-tv8k`  

`.hidden-tv720p`  
`.hidden-tv1080p`  
`.hidden-tv1440p`  
`.hidden-retina15`
`.hidden-tvUHD`
`.hidden-tv4k`  
`.hidden-tv8k`  

Copyright and License
=====================
Copyright 2013-2014 Ben Whitehead under the Apache 2.0 license.
