## Creating sequence

* Emit one or multiple events that I already have : ``Flux.just(T...)``
* Emit events that iterate over : ``Flux.fromArray(T[]) | Flux.fromIterable(List<T>) | Flux.range(0, 5)``
* Sequence that complete : ``Flux.empty()``
* Emit an error immediately : ``Flux.error()``
* Sequence that does nothing : ``Flux.never()``