# Heroku buildpack: Minify Static

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpack) which minifies any css and js files (excluding .min.js and .min.css). It replaces, rather than renames those files.

The buildpack will detect your app as Minify Static if it has the file `_minify_static.cfg` in the `root`. `_minify_static.cfg` does not support any configuration.
