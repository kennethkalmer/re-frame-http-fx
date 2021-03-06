## Unreleased

## v0.2.0 (2019-11-04)

Only a minor release mostly just to test releases with GitHub Actions. Do be
wary of the cljs-ajax version bump due to [breaking changes](https://github.com/JulianBirch/cljs-ajax/blob/master/CHANGES.md#version-08).

#### Fixed

* Fix infer-externs compiler warning. 
  See [#38](https://github.com/day8/re-frame-http-fx/issues/38).

#### Changed

* Migrate to shadow-cljs
* Upgrade Clojure to 1.10.1
* Upgrade ClojureScript to 1.10.520
* Bump cljs-ajax to 0.8.0

## v0.1.4 (2017-06-30)

* Move the http-effect into an accessible function.
* Small docs improvements

## v0.1.3 (2016-12-07)

* Add missing bracket in handler example

## v0.1.2 (2016-10-14)

* Add examples for making POST requests
* Comment out spec until it has a stable release

## v0.1.1 (2016-10-11)

* Bump CLJS dependency to 1.9.229 to support the newer spec definition of `coll-of`. [#5](https://github.com/day8/re-frame-http-fx/issues/5)

## v0.1.0 (2016-10-10)

* Added a spec to enforce that people provide a response format that is not a keyword. [#2](https://github.com/day8/re-frame-http-fx/issues/2)

##v0.0.5           (2016.08.22)

Bump to release ver of re-frame 0.8.0

##v0.0.1 & v0.0.4  (2016.07.XX)

Initial code drop based on re-frame 0.8.0-alpha9
