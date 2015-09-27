Caching allows the users browser to keep a local copy of a resource for fast loading without downloading the entire resource from the server every time.

At a minimum a check is run to check for a ``max-age`` or ``expires`` that is expected to be atleast 2 days long, at **minimum**.

Ideally this cache would be set to a even longer period, like a few months/years.

Consider using a public CDN that handles caching correctly from the following list:

* [developers.google.com/speed/libraries/](https://developers.google.com/speed/libraries/)

Else consider contacting the vendor and asking how the cache headers are setup.

See [cache headers on local asset were less than 2 days](http://passmarked.com/performance/inspect/invalid-or-missing-cache-headers-on-local-resource) for detailed information on setting cache headers that will allow them be able to control how long these headers are set.

# Resources

* [gulpjs.com](http://gulpjs.com/)
* [gruntjs.com](http://gruntjs.com/)
* [en.wikipedia.org/wiki/Universally_unique_identifier](https://en.wikipedia.org/wiki/Universally_unique_identifier)
* [en.wikipedia.org/wiki/Timestamp](https://en.wikipedia.org/wiki/Timestamp)