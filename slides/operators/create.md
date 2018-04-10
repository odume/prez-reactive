## Creating sequence

* [Emit one or multiple events that I already have](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/just.png) : ```Flux.just(T...)```
* [Emit events that iterate over array](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/fromarray.png) : ```Flux.fromArray(T[])```
* [Emit events that iterate range](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/range.png) : ```Flux.range(start, count)```
* [Sequence that complete](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/empty.png) : ```Flux.empty()```
* [Emit an error immediately](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/error.png) : ```Flux.error()```
* [Sequence that does nothing](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/never.png) : ```Flux.never()```