# talvi

<img src="https://raw.githubusercontent.com/metosin/talvi/master/docs/img/talvi.jpg" align="right"/>

Opionionated, Batteries included Web-stack for Clojure/Script.

* Data-driven, all the way down
* Focus on Productivity & Developer UX
* Low latency & Non-blocking
* JVM, GraalVM and the Browser
* Modular and Extensible

## Ingredients

* [Integrant](https://github.com/weavejester/integrant) to the top-level modules
* [Deps](https://clojure.org/guides/deps_and_cli) for dependency management
* [Just](https://github.com/casey/just) for command line scripts
* [Virhe](https://github.com/metosin/virhe) for error messages
* [Reitit](https://github.com/metosin/reitit) for routing
* [Sieppari](https://github.com/metosin/sieppari/issues) for interceptors
* [Promesa](https://github.com/funcool/promesa), [Manifold](https://github.com/ztellman/manifold) or [RxJava](https://github.com/ReactiveX/RxJava) for async
* [Malli](https://github.com/metosin/malli), [clojure.spec](https://clojure.org/guides/spec) or [Schema](https://github.com/plumatic/schema) for data modelling and validation

## Add-ons

* [Porsas](https://github.com/metosin/porsas), Reactive PostgreSQL for Clojure
* [Lacinia](https://github.com/walmartlabs/lacinia), GraphQL for Clojure
* [Pohjavirta](https://github.com/metosin/pohjavirta), Undertow for Clojure

## Devops

* [pack.alpha](https://github.com/juxt/pack.alpha) for packaging as Docker image and Uberjar
* [Terraform](https://www.terraform.io/) for defining infrastructure and monitoring

## License

Copyright © 2019 [Metosin Oy](http://www.metosin.fi)

Distributed under the Eclipse Public License, the same as Clojure.
