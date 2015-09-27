Caching allows the users browser to keep a local copy of a resource for fast loading without downloading the entire resource from the server every time.

This issue refers to a external resource that does not have caching headers defined which makes caching on the users' browser unpredictable.

We advice contacting the remote vendor and showing the information as to the benifits that will be gained by having complete control of how long a resource is cached at [passmarked.com/performance/inspect/missing-cache-headers-on-local-asset](http://passmarked.com/performance/inspect/missing-cache-headers-on-local-asset) which will also guide as to how this can be enabled.

# Resources

Few links to read up for more detailed information:

* [www.w3.org/Protocols/rfc2616/rfc2616-sec14.html#sec14.9.1](http://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html#sec14.9.1)
* [www.mobify.com/blog/beginners-guide-to-http-cache-headers/](http://www.mobify.com/blog/beginners-guide-to-http-cache-headers/)
* [devcenter.heroku.com/articles/increasing-application-performance-with-http-cache-headers#http-cache-headers](https://devcenter.heroku.com/articles/increasing-application-performance-with-http-cache-headers#http-cache-headers)
* [stackoverflow.com/questions/3339859/what-is-the-risk-of-having-http-header-cache-control-public](http://stackoverflow.com/questions/3339859/what-is-the-risk-of-having-http-header-cache-control-public)
* [blogs.msdn.com/b/ieinternals/archive/2009/06/17/vary-header-prevents-caching-in-ie.aspx](http://blogs.msdn.com/b/ieinternals/archive/2009/06/17/vary-header-prevents-caching-in-ie.aspx)