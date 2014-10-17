UBOS website and documentation
==============================

On-line at [ubos.net](http://ubos.net/)

* The main site is created with [Jekyll](http://jekyllrb.com/). Sources are in directory `jekyll`.
* The /docs subdirectory is created with [Sphinx](http://sphinx-doc.org/). Sources are in directory `sphinx`.

Note that the Sphinx parts use the CSS generated by Jekyll.

Found errors, omissions, improvements? Submit a pull request!

To re-generate the site:

```
   make clean all
```

The result will be in directory `stage`.