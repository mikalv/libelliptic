libelliptic
===========

A Ruby library providing an API to play with elliptic curves.

Basic usage
-------------------------

Just set the `@@base`, `@a` and `@b` parameters, and you are good to go:

````ruby
Point.base = 7
 => 7 
ElliPoint.a = 2
 => 2 
ElliPoint.b = 1
 => 1 
( 4 * ElliPoint.a**3 + 27 * ElliPoint.b**2 ) % Point.base == 0
 => false 
````

The fourth command is used to check the _non-singularity_ of the curve.

Example
-------------------------

Example usage within a Rails application (and some AJAX tricks) can be found on [my webserver](http://budapest.practicum.os3.nl/project/elliptic).

Documentation
-------------------------

Documentation can be found on [my webserver](http://budapest.practicum.os3.nl/doc/libelliptic/index.html).

Alternatively, you can generate it yourself using `rdoc`.
