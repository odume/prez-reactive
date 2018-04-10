## Peeking into sequences

* [execute on emissions](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/doonnext.png) : ```myFlux.doOnNext(exec)```
* [execute on completion](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/dooncomplete.png) : ```myFlux.doOnComplete(exec)```
* [execute on success (Mono)](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/doonsuccess.png): ```myMono.doOnSuccess(exec)```
* [execute on error termination](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/doonerror.png) : ```myFlux.doOnError(exec)```
* [execute on subscription](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/doonsubscribe.png) : ```myFlux.doOnSubscribe(exec)```