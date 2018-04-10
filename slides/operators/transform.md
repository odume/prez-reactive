## Transforming a sequence

* [Transform existing data on a 1-to-1 basis](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/map.png) ```myFlux.map(mapping)```
* [Transform existing data on a 1-to-n basis (eg. strings to their characters)](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/flatmap.png) ```myFlux.flatMap(mapping)```
* [Transform existing data running async task for each](https://github.com/reactor/reactor-core/blob/master/src/docs/marble/flatmapc.png) ```myFlux.flatMap(publisher)```
* [Aggregate a sequence into list](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/collectlist.png) ```myFlux.collectList()```
* [Aggregate a sequence into map](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/collectmap.png) ```myFlux.collectMap(keyExtract)```
* [Aggregate a sequence into the size of the sequence](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/count.png) ```myFlux.count()```
* [Aggregate a sequence by applying a function between each element](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/reduce.png) ```myFlux.reduce(reduction)```