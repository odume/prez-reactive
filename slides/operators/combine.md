## Combining sequences

* Combine publishers in sequential order : ```myFlux.concatWith(otherPub)```
* Combine publishers in emission order : ```myFlux.mergeWith(otherPub)```
* Combine publishers by pairing values : ```myFlux.zipWith(otherPub)```