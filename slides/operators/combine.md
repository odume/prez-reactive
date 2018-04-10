## Combining sequences

* [Combine publishers in sequential order](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/concat.png) : ```myFlux.concatWith(otherPub)```
* [Combine publishers in emission order](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/merge.png) : ```myFlux.mergeWith(otherPub)```
* [Combine publishers by pairing values](https://raw.githubusercontent.com/reactor/reactor-core/master/src/docs/marble/zip.png) : ```myFlux.zipWith(otherPub)```