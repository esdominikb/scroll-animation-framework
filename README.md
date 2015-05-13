# scroll-animation-framework
This framework combines a set of plugins with a generic logic to have a completly new experience as developer.
An experience that is such intuitiv for building or setting up CSS- and/or SVG-stroke animations that depends on the scroll position of the browser.

The **scroll-animation-framework** is the result of an interactive report that was designed & developed by [Ergosign GmbH](http://www.ergosign.de)

Want to see the power of the framework or want to see what Ergosign did in 2014?
Have a look at [Ergosign in 2014](http://www.ergosign.de/2014) and see the framework live in action.

## Dependencies
To build the basic set of the framework, the following libraries/frameworks/plugins are used:
- [jQuery](https://jquery.com/)
- [Snap.svg](http://snapsvg.io/)
- [iScroll](http://iscrolljs.com/)
- [niceScroll](http://areaaperta.com/nicescroll/)

## Build-System
As build system we use Grunt. Grunt handles the following tasks for us:
- concat HTML/LESS/JS files
- compile LESS to CSS
- minify CSS/JS
- run HTTP server
- copy from SRC to WWW
