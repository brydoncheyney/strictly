# Strictly

Utilities for a less tolerant Clojure.

## Usage

This is still an experimental library. It is liable to change dramatically, or become unmaintained if I lose interest.

If you want to use it, include it in your `project.clj` file to download it from Clojars:

    [strictly "0.1.0-SNAPSHOT"]

Apply the `strict` function from the `map` namespace to create a map that throws an Exception if a key that does not exist is retrieved. This is in contract to Clojure's default behaviour of returning `nil` in such cases.

See [the tests](https://github.com/ctford/strictly/blob/master/test/strictly/map_test.clj) for example usages.

## Licence

Copyright © 2014 Chris Ford 
