# Pathom 3 [![Clojars Project](https://img.shields.io/clojars/v/com.wsscode/pathom3.svg)](https://clojars.org/com.wsscode/pathom3) ![Test](https://github.com/wilkerlucio/pathom3/workflows/Test/badge.svg) [![cljdoc badge](https://cljdoc.xyz/badge/com.wsscode/pathom3)](https://cljdoc.xyz/d/com.wsscode/pathom3/CURRENT) <a href="https://babashka.org" rel="nofollow"><img src="https://github.com/babashka/babashka/raw/master/logo/badge.svg" alt="bb compatible" style="max-width: 100%;"></a>

![Pathom Logo](repo-resources/pathom-banner-padded.png)

Logic engine for attribute processing for Clojure and Clojurescript.

Pathom3 is a redesign of Pathom, this is a new library and uses different namespaces.

## Status

Alpha, changes and breakages may occur. Recommended for enthusiasts and people looking to help
and chasing bugs and help improve the development of Pathom.

## Install

```clojure
com.wsscode/pathom3 {:mvn/version "VERSION"}
```

## Documentation

https://pathom3.wsscode.com/

## Run Tests

Pathom 3 uses [Babashka](https://github.com/babashka/babashka) for task scripts, please install it before proceed.

### Clojure

```shell script
bb test
```

### ClojureScript

To run once

```shell script
bb test-cljs-once
```

Or to start shadow watch and test in the browser:

```shell script
bb test-cljs
```
