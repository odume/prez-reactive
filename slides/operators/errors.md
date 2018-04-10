## Handling errors

* [throws an error](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/error.png) : ```Flux.error(throwable)```
* [failing back to default value](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/onerrorreturn.png) : ```myFlux.onErrorReturn(defaultVal)```
* [failing back to another publisher](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/onerrorresumewith.png) : ```myFlux.onErrorResume(publisher)```
* [wrapping and rethrowing](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/maperror.png) : ```myFlux.onErrorMap(mapping)```
* [retrying](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/retry.png) : ```myFlux.retry(number)```