Minification refers to the process of removing unnecessary or redundant data without affecting how the resource is processed by the browser - e.g. code comments and formatting, removing unused code, using shorter variable and function names, and so on.

Unminified JavaScript and CSS wastes bandwidth and delays the rendering of a webpage.

# How do I fix this ?

Use a build tool (`npm`, `grunt` or `gulp`) to automate the minification of your production javascript and css (but keep the development files in human readable format). Alternatively, online minifiers exist.

# Resources

* [Google Developers - Minify Resources](https://developers.google.com/speed/docs/insights/MinifyResources?hl=en)
* [Minify JavaScript with Grunt](https://github.com/gruntjs/grunt-contrib-uglify)
* [Why Minify JavaScript?](http://engineeredweb.com/blog/why-minify-javascript/)
