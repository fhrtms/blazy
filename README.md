bLazy.js
=====

### DEMO: ###
http://dinbror.dk/blazy

### API: ###
http://dinbror.dk/blog/blazy

### DESCRIPTION: ###
bLazy is a lightweight lazy loading image script (less than 1KB minified and gzipped). It lets you lazy load and multi-serve your images so you can save bandwidth and server requests. The user will have faster load times and save data loaded if he/she doesn't browse the whole page. 

## CHANGELOG
### v 1.0.5 (2013/10/7) ###
* Fixed "Uncaught TypeError" when container isn't default (window).

### v 1.0.4 (2013/8/29) ###
* Added null check so we won't try to load an image if it's missing a data source.

### v 1.0.3 (2013/8/27) ###
* Added new option, `loadedClass`. Classname an image will get when loaded.
* Added support for horizontal lazy loading.
* Reduced throttle time for validate.

### v 1.0.2 (2013/8/7) ###
* Fixed typo in unbindEvent function.
* Added support for IE7 as promised (fallback for querySelectorAll).

### v 1.0.1 (2013/8/6) ###
* Performance improvements.
* Added throttle function to ensure that we don't call resize/scroll functions too often.
* Cleaning image markup when image has loaded.
