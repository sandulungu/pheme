**This component has been discontinued. The latest version of the parser core is integrated in StarLight CMS, accesible at https://github.com/z7/StarLight/tree/master/app/libs/pheme**

Was inspired by Tumblr's custom templating engine, so the syntax is pretty close to that. There are a few parser you may use: either the ones 100% compatible with Tumblr's syntax, or the ones implementing a more compact and flexible templating language.

No need to set up caching, no need for 3rd party libraries, no pre-compiling routines. Just load a file, create a parser class, give it a string to parse + an array of configurations and hook classes. And let it roll!

It's code injection safe. It's as flexible as it could be. You may change anything - from parser syntax rules to inner logic in your own descendant classes and integrate them with the core.

The source includes an example and Phpdoc style documentation + comments.