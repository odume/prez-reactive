## Transforming a sequence

* Transform existing data on a 1-to-1 basis ```myFlux.map(mapping)```
* Transform existing data on a 1-to-n basis (eg. strings to their characters) ```myFlux.flatMap(mapping)```
* Transform existing data running async task for each ```myFlux.flatMap(publisher)```
* Aggregate a sequence into list ```myFlux.collectList()```
* Aggregate a sequence into map ```myFlux.collectMap(keyExtract)```
* Aggregate a sequence into the size of the sequence ```myFlux.count()```
* Aggregate a sequence by applying a function between each element ```myFlux.reduce(reduction)```